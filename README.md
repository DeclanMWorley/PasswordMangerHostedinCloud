
<div id="rendered-md"><h1 id="password-manager-hosted-on-aws-cloud-declan-worley">Password Manager Hosted on AWS Cloud | Declan Worley</h1>

<h2 id="objective">Objective:</h2>
<p>To setup and configure Passbolt, an open-source password manager, on an AWS Ec2 Instance. In this lab, we will walk through my process of creating the EC2 instance, configuring Passbolt on the instance, and securing the traffic to our password manager with HTTPS.</p>
<h4 id="systemssoftware-utilized-aws-ec2-instance-passbolt-ubuntu-24">Systems/Software Utilized: AWS EC2 Instance, Passbolt, Ubuntu 24</h4>
<br class="jop-noMdConv"/>
<h2 id="task-1-aws-instance-creation-and-setup">Task 1) AWS Instance Creation and Setup</h2>
<p>Passbolt is an open-source password manager that helps users securely manage their passwords online. We can deploy this to AWS through the Passbolt Community Edition page on their website, and go through the instance setup as usual.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/098672b16cc74c1b92a6bd63083eb7ce.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<p>Here, we allow HTTP, HTTPS, and SSH. HTTP and HTTPS allows us to setup and configure Passbolt, while SSH is used to manage our virtual instance once it us up and running.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/2ab79657068d41e6a736b96d4422d658.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h4 id="create-our-keypairs">Create our keypairs</h4>
<p>Lastly in configuration, we need to create our keypairs to make sure access to our EC2 instance is secured. To do this, we can hop onto our Ubuntu host and generate a new keypair using <code class="inline-code">ssh-keygen -t rsa</code>, and copy the contents of the public key into our AWS dashboard (cat /home/ubuntu/.ssh/id_rsa.pub)</p>
<p>Once you have imported your public key from your Ubuntu machine, make sure to choose it under the <em>Key Pair Settings</em> dropdown in your Instance Creation menu.<br>
<img src="./_resources/f147f7f32af64f8cbf0f65726b9c32b0.png" alt="30880f244216fd8ba2907d0887829220.png"><br>
<br class="jop-noMdConv"/></p>
<p>Now we can access Passbolt Web Interface by navigating to <code class="inline-code">http://54.159.245.100/install</code>. Currently, HTTP is being used to access our manager, however, we can set it up to use HTTPS so that our password traffic will not be in plain text.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/a0946457f35b425da1038f9aee5051ad.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h2 id="task-2-https-configuration">Task 2) HTTPS configuration</h2>
<p>HTTPS will be configured so that the traffic passing to our password manager will not be in plain text, but rather encrypted. To do this, we will need a domain name. For this example, I will be using declanworley.com on NameCheap. We can go to our Dashboard, click on the domain, and then navigate to <em>Advanced DNS</em> settings. Here we can create a new A Record:</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/fc54520902f7407c8d8090e28decde11.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<p>There is also some configuration that needs to be completed on our Ubuntu host as well. I'll connect to the EC2 instance through SSH and I am greeted to instructions from passbolt regarding the SSL setup. It says here we need to edit our /etc/nginx/sites-enabled/nginx-passbolt.conf and modify the server_name to our domain. Then we can start the SSL configuration wizard by running `sudo dpkg-reconfigure passbolt-ce-server`.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/b017bdd6e0084c6fb2dbef336e84e048.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<ol>
<li>
<p><strong>Configuring nginx-passbolt.conf</strong></p>
<div style="text-align: center;" class="jop-noMdConv">
&Tab;<img src="./_resources/5344164c0b1548b5b13ebfa23d892662.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
</li>
<li>
<p><strong>SSL configuration wizard.</strong></p>
</li>
</ol>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="./_resources/15447fc963794ca4994cfbb6b4735984.png" width="50%" class="jop-noMdConv"/>
    </div>
    <div class="jop-noMdConv">
        <img src="./_resources/af67d75480c84a1bb259f1fc9aa4158d.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="./_resources/f417faf725d94683a7fea0fadb4387ec.png" width="50%" class="jop-noMdConv"/>
    </div>
    <div class="jop-noMdConv">
        <img src="./_resources/a4aa9c3db0ab49db9d4ff0b019d308d1.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<div style="text-align:center;  " class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="./_resources/9d79852987c044e6b450a07890e44a38.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<p>When we check back on our Passbolt dashboard, we can now access it at <a data-from-md title='https://declanworley.com' href='https://declanworley.com'>https://declanworley.com</a> and see that SSL access has now been enabled. Next, we will move on to finishing configuration.</p>
<br class="jop-noMdConv"/>
<h3 id="task-3-completing-passbolt-setup-through-web-interface">Task 3) Completing Passbolt Setup through Web Interface</h3>
<p>The rest of the Passbolt configuration is pretty straightforward. I will use the default settings for the database details, and supply some personal information, such as email and name, for the OpenPGP settings and SMTP server. I used my gmail for the SMTP settings, which allows users to receive important verification emails when creating an account, as well as providing forgot password features. A future project could involve setting up your own SMTP server, and using it for the emails used by this password manager.</p>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv"><div style="margin-right: 10px;" class="jop-noMdConv"><img src="./_resources/16983461a10a4fa9b980995f12774451.png" width="448" class="jop-noMdConv" height="50%"/></div><div class="jop-noMdConv"><img src="./_resources/1b4647f98b324c5b88286f0fa4134942.png" width="687" class="jop-noMdConv" height="50%"/></div></div>
<h3 id="setup-complete-lets-test-it">Setup Complete, Let's test it</h3>
<p>I found out that Passbolt doesn't work well with Opera, but it supports Chrome, Edge, Firefox, and other popular browsers. For this lab, I will use the extension for Microsoft Edge. Next, you are guided to make a passphrase to access your Passbolt account, download your recovery kit in case of lost access, and making a security token. Here my test security token is a gray TST, this will help ensure you aren't on a phising page.</p>
    
<div style="display: flex; align-items: center;" class="jop-noMdConv">
        <img src="./_resources/b18fff4c2a9b40ce89f41db57338f2c3.png" width="45%" style="margin-right: 15px;" class="jop-noMdConv"/>
        <img src="./_resources/a13d4a4fa73b41f9b26cff3ffa47e729.png" width="70%" class="jop-noMdConv"/>
</div>

<div style="text-align:center; " class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="./_resources/6ef57f1babff4e469d4a52b59b16834e.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<p>Once logged in, there is an empty password table. We can start using our new password manager by creating a password and supplying it with some information:</p>
<ul>
<li>Name: A name to recognize your password.</li>
<li>URL: The site that the password will be used on. I will use LinkedIn as an example.</li>
<li>Username &amp; Password: Self-explanatory; you can supply your login information here, and it will be used to automatically fill out your login forms.</li>
</ul>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/ac75fb9c1ed7431fa08d65f9673f9952.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/5bc3148474c2405aad8d00ac0d584504.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="./_resources/62b8379dafd4474db97fed620ebe4a14.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h2 id="conclusion">Conclusion:</h2>
<p>Password managers are an essnetial cybersecurity tool that you can utilize to protect your accounts across the internet. They allow you to easily vary your passwords from website to website, which in turn greatly lowers your risk of being hacked through data breaches. They are particularly important for companies where employees use multiple sites that aren't covered by single sign-on (SSO), as one leaked password won't grant malicious users access to other accounts.</p>
<p>By completing this lab, we successfully set up and secured a Passbolt password manager on an AWS EC2 instance, and configured it for HTTPS access. This process not only highlights the benefits of password managers but also the importance of securing web applications in general.</p>
</div></div>
					</body>
				</html>
			
