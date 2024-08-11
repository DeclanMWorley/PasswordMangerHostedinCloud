
				<!DOCTYPE html>
				<html>
					<head>
						<meta charset="UTF-8">
						<meta name="viewport" content="width=device-width, initial-scale=1" />
						<link rel="stylesheet" href="pluginAssets/highlight.js/atom-one-light.css">
						<title>Cloud Password Manager | Declan Worley</title>
					</head>
					<body>
						<div class="exported-note"><div class="exported-note-title">Cloud Password Manager | Declan Worley</div>

<style>
		/* https://necolas.github.io/normalize.css/ */
		html{line-height:1.15;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}
		article,aside,footer,header,nav,section{display:block}h1{font-size:2em;margin:.67em 0}hr{box-sizing:content-box;height:0;overflow:visible}
		pre{font-family:monospace,monospace;font-size:1em}a{background-color:transparent;-webkit-text-decoration-skip:objects}
		b,strong{font-weight:bolder}small{font-size:80%}img{border-style:none}

		body {
			font-size: 15px;
			color: #32373F;
			word-wrap: break-word;
			line-height: 1.6em;
			background-color: #ffffff;
			font-family: 'Avenir Next', 'Avenir', 'Arial', sans-serif;
			padding-bottom: 0px;
			padding-top: 0px;
		}
		kbd {
			border: 1px solid rgb(220, 220, 220);
			box-shadow: inset 0 -1px 0 rgb(220, 220, 220);
			padding: 2px 4px;
			border-radius: 3px;
			background-color: rgb(243, 243, 243);
		}
		::-webkit-scrollbar {
			width: 7px;
			height: 7px;
		}
		::-webkit-scrollbar-corner {
			background: none;
		}
		::-webkit-scrollbar-track {
			border: none;
		}
		::-webkit-scrollbar-thumb {
			background: rgba(100, 100, 100, 0.3); 
			border-radius: 5px;
		}
		::-webkit-scrollbar-track:hover {
			background: rgba(0, 0, 0, 0.1); 
		}
		::-webkit-scrollbar-thumb:hover {
			background: rgba(100, 100, 100, 0.7); 
		}

		

		/* Remove top padding and margin from first child so that top of rendered text is aligned to top of text editor text */

		#rendered-md > h1:first-child,
		#rendered-md > h2:first-child,
		#rendered-md > h3:first-child,
		#rendered-md > h4:first-child,
		#rendered-md > ul:first-child,
		#rendered-md > ol:first-child,
		#rendered-md > table:first-child,
		#rendered-md > blockquote:first-child,
		#rendered-md > img:first-child,
		#rendered-md > p:first-child {
			margin-top: 0;
			padding-top: 0;
		}
		
		p, h1, h2, h3, h4, h5, h6, ul, table {
			margin-top: .6em;
			margin-bottom: 1.35em;

			/*
				Adds support for RTL text in the note body. It automatically detects the direction using the content.
				Issue: https://github.com/laurent22/joplin/issues/3991
			*/
			unicode-bidi: plaintext;
		}

		h1, h2, h3, h4, h5, h6, ul, table {
			margin-bottom: 0.65em;
		}

		h1, h2, h3, h4, h5, h6 {
			line-height: 1.5em;
		}
		h1 {
			font-size: 1.5em;
			font-weight: bold;
			border-bottom: 1px solid #dddddd;
			padding-bottom: .3em;
		}
		h2 {
			font-size: 1.3em;
			font-weight: bold;
			padding-bottom: .1em; */
		}
		h3 {
			font-size: 1.1em;
			font-weight: bold;
		}
		h4, h5, h6 {
			font-size: 1em;
			font-weight: bold;
		}

		.exported-note-title {
			font-size: 2em;
			font-weight: bold;
			margin-bottom: 0.8em;
			line-height: 1.5em;
			padding-bottom: .35em;
			border-bottom: 1px solid #dddddd;
		}

		a {
			color: #155BDA;
		}
		ul, ol {
			padding-left: 0;
			margin-left: 1.7em;
		}
		li {
			margin-bottom: .4em;
		}
		li p {
			margin-top: 0.2em;
			margin-bottom: 0;
		}

		.resource-icon {
			display: inline-block;
			position: relative;
			top: 0.3em;
			text-decoration: none;
			width: 1.2em;
			height: 1.4em;
			margin-right: 0.4em;
			background-color:  #155BDA;
		}
    /* These icons are obtained from the wonderful ForkAwesome project by copying the src svgs 
     * into the css classes below.
     * svgs are obtained from https://github.com/ForkAwesome/Fork-Awesome/tree/master/src/icons/svg
     * instead of the svg width, height property you must use a viewbox here, 0 0 1536 1792 is typically the actual size of the icon
     * each line begins with the pre-amble -webkit-mask: url("data:image/svg+xml;utf8,
     * and of course finishes with ");
     * to prevent artifacts it is also necessary to include -webkit-mask-repeat: no-repeat;
     * on the following line
     * */
		.fa-joplin {
			/* Awesome Font file */
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M373.834 128C168.227 128 0 296.223 0 501.834v788.336C0 1495.778 168.227 1664 373.834 1664h788.336c205.608 0 373.83-168.222 373.83-373.83V501.834C1536 296.224 1367.778 128 1162.17 128zm397.222 205.431h417.424a7.132 7.132 0 0 1 7.132 7.133v132.552c0 4.461-3.619 8.073-8.077 8.073h-57.23c-24.168 0-43.768 19.338-44.284 43.374v2.377h-.017v136.191h-.053l-.466 509.375c-5.02 77.667-39.222 149.056-96.324 201.046-60.28 54.834-141.948 85.017-229.962 85.017-12.45 0-25.208-.61-37.907-1.785-92.157-8.682-181.494-48.601-251.662-112.438-71.99-65.517-117.147-150.03-127.164-238-11.226-98.763 23.42-192.783 95.045-257.937 81.99-74.637 198.185-101.768 316.613-75.704 5.574 1.227 9.55 6.282 9.55 11.997v199.52c-.199 2.625-1.481 6.599-8.183 2.896-.663-.365-1.194-.511-1.653-.531-21.987-10.587-45.159-17.57-68.559-19.916-.38-.04-.757-.124-1.138-.163-.537-.048-1.034-.033-1.556-.075-4.13-.354-8.183-.517-12.203-.58-.87-.011-1.771-.127-2.641-.127-.486 0-.951.05-1.437.057-1.464.011-2.886.115-4.33.163-2.76.102-5.497.211-8.182.448-.273.024-.547.07-.835.097-25.509 2.4-47.864 11.104-65.012 25.47-.954.802-1.974 1.53-2.9 2.36a1.34 1.34 0 0 1-.168.146c-23.96 21.8-34.881 53.872-30.726 90.316 4.62 40.737 26.94 81.156 62.841 113.823 35.908 32.67 80.335 52.977 125.113 57.186 35.118 3.36 66.547-3.919 89.899-20.461a97.255 97.255 0 0 0 9.365-7.501c2.925-2.661 5.569-5.5 8.086-8.416.3-.348.672-.673.975-1.024 8.253-9.864 14.222-21.067 17.996-33.148.639-2.034 1.051-4.148 1.564-6.227.381-1.563.81-3.106 1.112-4.693.555-2.784.923-5.632 1.253-8.49.086-.709.183-1.414.237-2.128.492-4.893.693-9.858.55-14.91h.013V521.623c-2.01-22.626-20.78-40.434-43.928-40.434h-57.23a8.071 8.071 0 0 1-8.077-8.073V340.564a7.132 7.132 0 0 1 7.136-7.133z'/></svg>");
		}
		.fa-file-image {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-128-448v320H256v-192l192-192 128 128 384-384zm-832-192c-106 0-192-86-192-192s86-192 192-192 192 86 192 192-86 192-192 192z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-pdf {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-514-593c25 20 53 38 84 56 42-5 81-7 117-7 67 0 152 8 177 49 7 10 13 28 2 52-1 1-2 3-3 4v1c-3 18-18 38-71 38-64 0-161-29-245-73-139 15-285 46-392 83-103 176-182 262-242 262-10 0-19-2-28-7l-24-12c-3-1-4-3-6-5-5-5-9-16-6-36 10-46 64-123 188-188 8-5 18-2 23 6 1 1 2 3 2 4 31-51 67-116 107-197 45-90 80-178 104-262-32-109-42-221-24-287 7-25 22-40 42-40h22c15 0 27 5 35 15 12 14 15 36 9 68-1 3-2 6-4 8 1 3 1 5 1 8v30c-1 63-2 123-14 192 35 105 87 190 146 238zm-576 411c30-14 73-57 137-158-75 58-122 124-137 158zm398-920c-10 28-10 76-2 132 3-16 5-31 7-44 2-17 5-31 7-43 1-3 2-5 4-8-1-1-1-3-2-5-1-18-7-29-13-36 0 2-1 3-1 4zm-124 661c88-35 186-63 284-81-10-8-20-15-29-23-49-43-93-103-127-176-19 61-47 126-83 197-15 28-30 56-45 83zm646-16c-5-5-31-24-140-24 49 18 94 28 124 28 9 0 14 0 18-1 0-1-1-2-2-3z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-word {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM233 768v107h70l164 661h159l128-485c5-15 8-30 10-46 1-8 2-16 2-24h4l3 24c3 14 4 30 9 46l128 485h159l164-661h70V768h-300v107h90l-99 438c-4 16-6 33-7 46l-2 21h-4c0-6-2-14-3-21-3-13-5-30-9-46L825 768H711l-144 545c-4 16-5 33-8 46l-4 21h-4l-2-21c-1-13-3-30-7-46l-99-438h90V768H233z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-powerpoint {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-992-234v106h327v-106h-93v-167h137c43 0 82-2 118-15 90-31 146-124 146-233s-54-193-137-228c-38-15-84-19-130-19H416v107h92v555h-92zm353-280H650V882h120c35 0 62 6 83 18 36 21 56 62 56 115 0 56-20 99-62 120-21 10-47 15-78 15z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-excel {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-979-234v106h281v-106h-75l103-161c12-19 18-34 21-34h2c1 4 3 7 5 10 4 8 10 14 17 24l107 161h-76v106h291v-106h-68l-192-273 195-282h67V768H828v107h74l-103 159c-12 19-21 34-21 33h-2c-1-4-3-7-5-10-4-7-9-14-17-23L648 875h76V768H434v107h68l189 272-194 283h-68z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-audio {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM620 850c12 5 20 17 20 30v544c0 13-8 25-20 30-4 1-8 2-12 2-8 0-16-3-23-9l-166-167H288c-18 0-32-14-32-32v-192c0-18 14-32 32-32h131l166-167c10-9 23-12 35-7zm417 689c19 0 37-8 50-24 83-102 129-231 129-363s-46-261-129-363c-22-28-63-32-90-10-28 23-32 63-9 91 65 80 100 178 100 282s-35 202-100 282c-23 28-19 68 9 90 12 10 26 15 40 15zm-211-148c17 0 34-7 47-20 56-60 87-137 87-219s-31-159-87-219c-24-26-65-27-91-3-25 24-27 65-2 91 33 36 52 82 52 131s-19 95-52 131c-25 26-23 67 2 91 13 11 29 17 44 17z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-video {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM768 768c70 0 128 58 128 128v384c0 70-58 128-128 128H384c-70 0-128-58-128-128V896c0-70 58-128 128-128h384zm492 2c12 5 20 17 20 30v576c0 13-8 25-20 30-4 1-8 2-12 2-8 0-17-3-23-9l-265-266v-90l265-266c6-6 15-9 23-9 4 0 8 1 12 2z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-archive {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M640 384V256H512v128h128zm128 128V384H640v128h128zM640 640V512H512v128h128zm128 128V640H640v128h128zm700-388c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H768v128H640V128H128v1536h1280zM781 943c85 287 107 349 107 349 5 17 8 34 8 52 0 111-108 192-256 192s-256-81-256-192c0-18 3-35 8-52 0 0 21-62 120-396V768h128v128h79c29 0 54 19 62 47zm-141 465c71 0 128-29 128-64s-57-64-128-64-128 29-128 64 57 64 128 64z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-code {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM480 768c11-14 31-17 45-6l51 38c14 11 17 31 6 45l-182 243 182 243c11 14 8 34-6 45l-51 38c-14 11-34 8-45-6l-226-301c-8-11-8-27 0-38zm802 301c8 11 8 27 0 38l-226 301c-11 14-31 17-45 6l-51-38c-14-11-17-31-6-45l182-243-182-243c-11-14-8-34 6-45l51-38c14-11 34-8 45 6zm-620 461c-18-3-29-20-26-37l138-831c3-18 20-29 37-26l63 10c18 3 29 20 26 37l-138 831c-3 18-20 29-37 26z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-alt, .fa-file-csv {
      /* fork-awesome doesn't have csv so we use the text icon */
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM384 800c0-18 14-32 32-32h704c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64zm736 224c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64c0-18 14-32 32-32h704zm0 256c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64c0-18 14-32 32-32h704z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		blockquote {
			border-left: 4px solid rgb(220, 220, 220);
			padding-left: 1.2em;
			margin-left: 0;
			opacity: 0.7;
		}

		.jop-tinymce table,
		table {
			text-align: left;
			border-collapse: collapse;
			border: 1px solid rgb(220, 220, 220);
			background-color: #ffffff;
		}

		.jop-tinymce table td, .jop-tinymce table th,
		table td, th {
			text-align: left;
			padding: .5em 1em .5em 1em;
			font-size: 15;
			color: #32373F;
			font-family: 'Avenir Next', 'Avenir', 'Arial', sans-serif;
		}

		.jop-tinymce table td,
		table td {
			border: 1px solid rgb(220, 220, 220);
		}

		.jop-tinymce table th,
		table th {
			border: 1px solid rgb(220, 220, 220);
			border-bottom: 2px solid rgb(220, 220, 220);
			background-color: rgb(247, 247, 247);
		}

		.jop-tinymce table tr:nth-child(even),
		table tr:nth-child(even) {
			background-color: rgb(247, 247, 247);
		}

		.jop-tinymce table tr:hover,
		table tr:hover {
			background-color: #e5e5e5;
		}

		hr {
			border: none;
			border-bottom: 2px solid #dddddd;
		}
		img {
			max-width: 100%;
			height: auto;
		}
		
		.inline-code,
		.mce-content-body code {
			border: 1px solid rgb(220, 220, 220);
			background-color: rgb(243, 243, 243);
			padding-right: .2em;
			padding-left: .2em;
			border-radius: .25em;
			color: rgb(0,0,0);
			font-size: .9em;
		}

		.highlighted-keyword {
			background-color: #F3B717;
			color: black;
		}

		.not-loaded-resource img {
			width: 1.15em;
			height: 1.15em;
			background: white;
			padding: 2px !important;
			border-radius: 2px;
			box-shadow: 0 1px 3px #000000aa;
		}

		a.not-loaded-resource img {
			margin-right: .2em;
		}

		a.not-loaded-resource {
			display: flex;
			flex-direction: row;
			align-items: center;
		}

		.md-checkbox input[type=checkbox]:checked {
			opacity: 0.7;
		}

		.jop-tinymce ul.joplin-checklist .checked,
		.md-checkbox .checkbox-label-checked {
			opacity: 0.5;
		}

		.exported-note {
			padding: 1em;
		}

		.joplin-editable .joplin-source {
			display: none;
		}

		mark {
			background: #F7D26E;
			color: black;
		}

		/* =============================================== */
		/* For TinyMCE */
		/* =============================================== */

		.mce-content-body {
			/* Note: we give a bit more padding at the bottom, to allow scrolling past the end of the document */
			padding: 5px 10px 10em 0;
		}

		/*
		.mce-content-body code {
			background-color: transparent;
		}
		*/

		.mce-content-body [data-mce-selected=inline-boundary] {
			background-color: transparent;
		}

		.mce-content-body .joplin-editable {
			cursor: pointer !important;
		}

		.mce-content-body.mce-content-readonly {
			opacity: 0.5;
		}

		/* We need that to make sure click events have the A has a target */
		.katex a span {
			pointer-events: none;
		}

		.media-player {
			width: 100%;
			margin-top: 10px;
		}

		.media-player.media-pdf {
			min-height: 35rem;
			width: 100%;
			max-width: 1000px;
			margin: 0;
			border: 0;
			display: block;
		}

		/* Clear the CODE style if the element is within a joplin-editable block */
		.mce-content-body .joplin-editable code {
			border: none;
			background: none;
			padding: 0;
			color: inherit;
			font-size: inherit;
		}

		/* To make code blocks horizontally scrollable */
		/* https://github.com/laurent22/joplin/issues/5740 */
		pre.hljs {
			overflow-x: auto;
		}

		.joplin-table-wrapper{
			overflow-x: auto;
			overflow-y: hidden;
		}

		/* =============================================== */
		/* For TinyMCE */
		/* =============================================== */

		@media print {
			body {
				height: auto !important;
			}

			pre {
				white-space: pre-wrap;
			}

			.code, .inline-code {
				border: 1px solid #CBCBCB;
			}

			#joplin-container-content {
				/* The height of the content is set dynamically by JavaScript (in updateBodyHeight) to go
				   around various issues related to scrolling. However when printing we don't want this
				   fixed size as that would crop the content. So we set it to auto here. "important" is
				   needed to override the style set by JavaScript at the element-level. */
				height: auto !important;
			}
		}
	

				/*
					FOR THE MARKDOWN EDITOR
				*/

				/* Remove the indentation from the checkboxes at the root of the document
				   (otherwise they are too far right), but keep it for their children to allow
				   nested lists. Make sure this value matches the UL margin. */

				li.md-checkbox {
					list-style-type: none;
				}

				li.md-checkbox input[type=checkbox] {
					margin-left: -1.71em;
					margin-right: 0.7em;
				}
				
				ul.joplin-checklist {
					list-style:none;
				}

				/*
					FOR THE RICH TEXT EDITOR
				*/

				ul.joplin-checklist li::before {
					content:"\f14a";
					font-family:"Font Awesome 5 Free";
					background-size: 16px 16px;
					pointer-events: all;
					cursor: pointer;
					width: 1em;
					height: 1em;
					margin-left: -1.3em;
					position: absolute;
					color: #32373F;
				}

				.joplin-checklist li:not(.checked)::before {
					content:"\f0c8";
				}
.mermaid { width: 640px; }
pre.mermaid > svg { white-space: unset; }
.mermaid-export-graph {
					opacity: 0;
					height: 0;
					z-index: 1;
					position: relative;
				} 
				.joplin-editable:hover .mermaid-export-graph,
				.joplin-editable .mermaid-export-graph:has(:focus-visible) {
					opacity: 1;
				}
				.mermaid-export-graph > button:hover {
					background-color: #CBDAF1 !important;
				}</style><div id="rendered-md"><h1 id="password-manager-hosted-on-aws-cloud-declan-worley">Password Manager Hosted on AWS Cloud | Declan Worley</h1>
<h2 id="objective">Objective:</h2>
<p>To setup and configure Passbolt, an open-source password manager, on an AWS Ec2 Instance. In this lab, we will walk through my process of creating the EC2 instance, configuring Passbolt on the instance, and securing the traffic to our password manager with HTTPS.</p>
<h4 id="systemssoftware-utilized-aws-ec2-instance-passbolt-ubuntu-24">Systems/Software Utilized: AWS EC2 Instance, Passbolt, Ubuntu 24</h4>
<br class="jop-noMdConv"/>
<h2 id="task-1-aws-instance-creation-and-setup">Task 1) AWS Instance Creation and Setup</h2>
<p>Passbolt is an open-source password manager that helps users securely manage their passwords online. We can deploy this to AWS through the Passbolt Community Edition page on their website, and go through the instance setup as usual.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/098672b16cc74c1b92a6bd63083eb7ce.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<p>Here, we allow HTTP, HTTPS, and SSH. HTTP and HTTPS allows us to setup and configure Passbolt, while SSH is used to manage our virtual instance once it us up and running.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/2ab79657068d41e6a736b96d4422d658.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h4 id="create-our-keypairs">Create our keypairs</h4>
<p>Lastly in configuration, we need to create our keypairs to make sure access to our EC2 instance is secured. To do this, we can hop onto our Ubuntu host and generate a new keypair using <code class="inline-code">ssh-keygen -t rsa</code>, and copy the contents of the public key into our AWS dashboard (cat /home/ubuntu/.ssh/id_rsa.pub)</p>
<p>Once you have imported your public key from your Ubuntu machine, make sure to choose it under the <em>Key Pair Settings</em> dropdown in your Instance Creation menu.<br>
<img src="../_resources/f147f7f32af64f8cbf0f65726b9c32b0.png" alt="30880f244216fd8ba2907d0887829220.png"><br>
<br class="jop-noMdConv"/></p>
<p>Now we can access Passbolt Web Interface by navigating to <code class="inline-code">http://54.159.245.100/install</code>. Currently, HTTP is being used to access our manager, however, we can set it up to use HTTPS so that our password traffic will not be in plain text.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/a0946457f35b425da1038f9aee5051ad.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h2 id="task-2-https-configuration">Task 2) HTTPS configuration</h2>
<p>HTTPS will be configured so that the traffic passing to our password manager will not be in plain text, but rather encrypted. To do this, we will need a domain name. For this example, I will be using declanworley.com on NameCheap. We can go to our Dashboard, click on the domain, and then navigate to <em>Advanced DNS</em> settings. Here we can create a new A Record:</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/fc54520902f7407c8d8090e28decde11.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<p>There is also some configuration that needs to be completed on our Ubuntu host as well. I'll connect to the EC2 instance through SSH and I am greeted to instructions from passbolt regarding the SSL setup. It says here we need to edit our /etc/nginx/sites-enabled/nginx-passbolt.conf and modify the server_name to our domain. Then we can start the SSL configuration wizard by running `sudo dpkg-reconfigure passbolt-ce-server`.</p>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/b017bdd6e0084c6fb2dbef336e84e048.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<ol>
<li>
<p><strong>Configuring nginx-passbolt.conf</strong></p>
<div style="text-align: center;" class="jop-noMdConv">
&Tab;<img src="../_resources/5344164c0b1548b5b13ebfa23d892662.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
</li>
<li>
<p><strong>SSL configuration wizard.</strong></p>
</li>
</ol>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="../_resources/15447fc963794ca4994cfbb6b4735984.png" width="50%" class="jop-noMdConv"/>
    </div>
    <div class="jop-noMdConv">
        <img src="../_resources/af67d75480c84a1bb259f1fc9aa4158d.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="../_resources/f417faf725d94683a7fea0fadb4387ec.png" width="50%" class="jop-noMdConv"/>
    </div>
    <div class="jop-noMdConv">
        <img src="../_resources/a4aa9c3db0ab49db9d4ff0b019d308d1.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<div style="text-align:center;  " class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="../_resources/9d79852987c044e6b450a07890e44a38.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<p>When we check back on our Passbolt dashboard, we can now access it at <a data-from-md title='https://declanworley.com' href='https://declanworley.com'>https://declanworley.com</a> and see that SSL access has now been enabled. Next, we will move on to finishing configuration.</p>
<br class="jop-noMdConv"/>
<h3 id="task-3-completing-passbolt-setup-through-web-interface">Task 3) Completing Passbolt Setup through Web Interface</h3>
<p>The rest of the Passbolt configuration is pretty straightforward. I will use the default settings for the database details, and supply some personal information, such as email and name, for the OpenPGP settings and SMTP server. I used my gmail for the SMTP settings, which allows users to receive important verification emails when creating an account, as well as providing forgot password features. A future project could involve setting up your own SMTP server, and using it for the emails used by this password manager.</p>
<div style="display: flex; flex-direction: row;" class="jop-noMdConv"><div style="margin-right: 10px;" class="jop-noMdConv"><img src="../_resources/16983461a10a4fa9b980995f12774451.png" width="448" class="jop-noMdConv" height="50%"/></div><div class="jop-noMdConv"><img src="../_resources/1b4647f98b324c5b88286f0fa4134942.png" width="687" class="jop-noMdConv" height="50%"/></div></div>
<h3 id="setup-complete-lets-test-it">Setup Complete, Let's test it</h3>
<p>I found out that Passbolt doesn't work well with Opera, but it supports Chrome, Edge, Firefox, and other popular browsers. For this lab, I will use the extension for Microsoft Edge. Next, you are guided to make a passphrase to access your Passbolt account, download your recovery kit in case of lost access, and making a security token. Here my test security token is a gray TST, this will help ensure you aren't on a phising page.</p>
<div style="display: flex; justify-content: center; " class="jop-noMdConv">
    
    <div style="display: flex; align-items: center;" class="jop-noMdConv">
        <img src="../_resources/b18fff4c2a9b40ce89f41db57338f2c3.png" width="45%" style="margin-right: 15px;" class="jop-noMdConv"/>
        <img src="../_resources/a13d4a4fa73b41f9b26cff3ffa47e729.png" width="70%" class="jop-noMdConv"/>
    </div>
</div>
<div style="text-align:center; " class="jop-noMdConv">
    <div style="margin-right: 10px;" class="jop-noMdConv">
        <img src="../_resources/6ef57f1babff4e469d4a52b59b16834e.png" width="50%" class="jop-noMdConv"/>
    </div>
</div>
<p>Once logged in, there is an empty password table. We can start using our new password manager by creating a password and supplying it with some information:</p>
<ul>
<li>Name: A name to recognize your password.</li>
<li>URL: The site that the password will be used on. I will use LinkedIn as an example.</li>
<li>Username &amp; Password: Self-explanatory; you can supply your login information here, and it will be used to automatically fill out your login forms.</li>
</ul>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/ac75fb9c1ed7431fa08d65f9673f9952.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/5bc3148474c2405aad8d00ac0d584504.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<div style="text-align: center;" class="jop-noMdConv">
  <img src="../_resources/62b8379dafd4474db97fed620ebe4a14.png" style="width: 50%px;" class="jop-noMdConv"/>
</div>
<h2 id="conclusion">Conclusion:</h2>
<p>Password managers are an essnetial cybersecurity tool that you can utilize to protect your accounts across the internet. They allow you to easily vary your passwords from website to website, which in turn greatly lowers your risk of being hacked through data breaches. They are particularly important for companies where employees use multiple sites that aren't covered by single sign-on (SSO), as one leaked password won't grant malicious users access to other accounts.</p>
<p>By completing this lab, we successfully set up and secured a Passbolt password manager on an AWS EC2 instance, and configured it for HTTPS access. This process not only highlights the benefits of password managers but also the importance of securing web applications in general.</p>
</div></div>
					</body>
				</html>
			