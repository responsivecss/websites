# responsive websites
Collection of best responsive design websites

/*
Theme Name: Css Zeal
Theme URI: 
Description: The Css Zeal theme for WordPress is sophisticated, lightweight, and adaptable. Make it yours with a custom menu, header image, and background -- then go further with available theme options for light or dark color scheme, custom link colors, and three layout choices. Twenty Eleven comes equipped with a Showcase page template that transforms your front page into a showcase to show off your best content, widget support galore (sidebar, three footer areas, and a Showcase page widget area), and a custom "Ephemera" widget to display your Aside, Link, Quote, or Status posts. Included are styles for print and for the admin editor, support for featured images (as custom header images on posts and pages and as large images on featured "sticky" posts), and special styles for six different post formats.
Version: 1.0
License: GNU General Public License
License URI: license.txt
Tags: dark, light, white, black, gray, one-column, two-columns, left-sidebar, right-sidebar, fixed-width, flexible-width, custom-background, custom-colors, custom-header, custom-menu, editor-style, featured-image-header, featured-images, full-width-template, microformats, post-formats, rtl-language-support, sticky-post, theme-options, translation-ready
*/

/* =Reset default browser CSS. Based on work by Eric Meyer: http://meyerweb.com/eric/tools/css/reset/index.html
-------------------------------------------------------------- */

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, font, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td {
	border: 0;
	font-family: inherit;
	font-size: 100%;
	font-style: inherit;
	font-weight: inherit;
	margin: 0;
	outline: 0;
	padding: 0;
	vertical-align: baseline;
}
:focus {/* remember to define focus styles! */
	outline: 0;
}
body {
	background: #fff;
	line-height: 1;
}
ol, ul {
	list-style: none;
}
table {/* tables still need 'cellspacing="0"' in the markup */
	border-collapse: separate;
	border-spacing: 0;
}
caption, th, td {
	font-weight: normal;
	text-align: left;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: "";
}
blockquote, q {
	quotes: "" "";
}
a img {
	border: 0;
}
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}


/* =Structure
----------------------------------------------- */

body {
	padding: 0;
}
.innerHead{ margin: 0 auto; max-width: 1150px; position:relative;}
#page {
	margin: 0 auto 2% auto;
	max-width: 1150px;
	position:relative;
}
#branding hgroup {
	margin: 0;
	float:left;
}
#access div {
	
}
#primary {
	float: left;
	margin: 0;
	width: 100%;
	padding:0%;
	/*background: url( images/page-bg.png) left top repeat;*/
	min-height:500px;
	/*border:1px solid #a7a7a7;*/
}
.submissionCounter{ position:absolute; top:35px; right:20px; display:none;}
.home .submissionCounter{ display:block;}
.submitCounter{ background: url(images/counter1.png) left top no-repeat; width: 15px; height: 36px; float:left; text-align:center; padding: 2px 10px; font-size: 20px; font-weight: bold; color:#818181;}
.howManySubmitted{
clear: both;
font-weight: bold;
font-style: italic;
width: 150px;
font-size: 13px;
line-height:18px;
color:#818181;
}
.submitWebsiteLink{ float:right!important; margin-left:50px;}
.submitWebsiteLink a { text-transform:uppercase; width:175px!important; background-color:#3ea5f0 !important; color:#ffffff !important; padding:10px;}
.submitWebsiteLink a:hover { text-transform:uppercase; width:175px!important; background-color:#616161 !important; color:#ffffff !important; padding:10px;}
.singular #primary{ /* width:100%;*/} 
#content {
	margin:0;
	width: 100%;
	background:none!important;
	/*padding:2%;*/
	border: none;
}
#secondary {
	float: right;
	padding:2%;
	width: 17%;
	border:1px solid #a7a7a7;
	background:#f7f7f7;
}

/* Singular */
.singular #primary {
	margin: 0;
}
.singular #content,
.left-sidebar.singular #content {
	margin: 0%;
	position: relative;
	width: auto;
	padding:0px!important;
}
.singular .entry-header,
.singular .entry-content,
.singular footer.entry-meta,
.singular #comments-title {
	
    margin: 5px auto;
	width: 100%;
}

.singular .entry-header{ border-bottom: 0px solid #DBDBDB !important;}
.singular #comments-title {
	font-size:20px;
	font-weight:bold;
	color:#000;
	text-transform:none;
}

/* Attachments */
.singular .image-attachment .entry-content {
	margin: 0 auto;
	width: auto;
}
.singular .image-attachment .entry-description {
	margin: 0 auto;
	width: 100%;
}

/* Showcase */
.page-template-showcase-php #primary,
.left-sidebar.page-template-showcase-php #primary {
	margin: 0;
}
.page-template-showcase-php #content,
.left-sidebar.page-template-showcase-php #content {
	margin: 0 7.6%;
	width: auto;
}
.page-template-showcase-php section.recent-posts {
	float: right;
	margin: 0 0 0 31%;
	width: 69%;
}
.page-template-showcase-php #main .widget-area {
	float: left;
	margin: 0 -22.15% 0 0;
	width: 22.15%;
}

/* error404 */
.error404 #primary {
	
	margin: 0;
}
.error404 #primary #content {
	margin: 0;
	width: auto;
}

/* Alignment */
.alignleft {
	display: inline;
	float: left;
	margin-right: 1.625em;
}
.alignright {
	display: inline;
	float: right;
	margin-left: 1.625em;
}
.aligncenter {
	clear: both;
	display: block;
	margin-left: auto;
	margin-right: auto;
}

/* Right Content */
.left-sidebar #primary {
	float: right;
	margin: 0 0 0 -26.4%;
	width: 100%;
}
.left-sidebar #content {
	margin: 0 7.6% 0 34%;
	width: 58.4%;
}
.left-sidebar #secondary {
	float: left;
	margin-left: 7.6%;
	margin-right: 0;
	width: 18.8%;
}

/* One column */
.one-column #page {
	max-width: 690px;
}
.one-column #content {
	margin: 0 7.6%;
	width: auto;
}
.one-column #nav-below {
	border-bottom: 1px solid #ddd;
	margin-bottom: 1.625em;
}
.one-column #secondary {
	float: none;
	margin: 0 7.6%;
	width: auto;
}
/* Simplify the showcase template */
.one-column .page-template-showcase-php section.recent-posts {
	float: none;
	margin: 0;
	width: 100%;
}
.one-column .page-template-showcase-php #main .widget-area {
	float: none;
	margin: 0;
	width: auto;
}
.one-column .page-template-showcase-php .other-recent-posts {
	border-bottom: 1px solid #ddd;
}
/* Simplify the showcase template when small feature */
.one-column section.featured-post .attachment-small-feature {
	border: none;
	display: block;
	height: auto;
	max-width: 60%;
	position: static;
}
.one-column article.feature-image.small {
	margin: 0 0 1.625em;
	padding: 0;
}
.one-column article.feature-image.small .entry-title {
	font-size: 20px;
	line-height: 1.3em;
}
.one-column article.feature-image.small .entry-summary {
	height: 150px;
	overflow: hidden;
	padding: 0;
	text-overflow: ellipsis;
}
.one-column article.feature-image.small .entry-summary a {
	left: -9%;
}
/* Remove the margin on singular articles */
.one-column.singular .entry-header,
.one-column.singular .entry-content,
.one-column.singular footer.entry-meta,
.one-column.singular #comments-title {
	width: 100%;
}
/* Simplify the pullquotes and pull styles */
.one-column.singular blockquote.pull {
	margin: 0 0 1.625em;
}
.one-column.singular .pull.alignleft {
	margin: 0 1.625em 0 0;
}
.one-column.singular .pull.alignright {
	margin: 0 0 0 1.625em;
}
.one-column.singular .entry-meta .edit-link a {
	position: absolute;
	left: 0;
	top: 40px;
}
.one-column.singular #author-info {
	margin: 2.2em -8.8% 0;
	padding: 20px 8.8%;
}
/* Make sure we have room for our comment avatars */
.one-column .commentlist > li.comment {
	margin-left: 102px;
	width: auto;
}
/* Make sure the logo and search form don't collide */
.one-column #branding #searchform {
	right: 40px;
	top: 4em;
}
/* Talking avatars take up too much room at this size */
.one-column .commentlist > li.comment {
	margin-left: 0;
}
.one-column .commentlist > li.comment .comment-meta,
.one-column .commentlist > li.comment .comment-content {
	margin-right: 85px;
}
.one-column .commentlist .avatar {
	background: transparent;
	display: block;
	padding: 0;
	top: 1.625em;
	left: auto;
	right: 1.625em;
}
.one-column .commentlist .children .avatar {
	background: none;
	padding: 0;
	position: absolute;
	top: 2.2em;
	left: 2.2em;
}
.one-column #respond {
	width: auto;
}


/* =Global
----------------------------------------------- */

body, input, textarea {
	color: #373737;
	font: 15px Verdana,Arial,Helvetica,sans-serif;
	font-weight: 300;
	line-height: 1.625;
}
body {
	
	background: url("images/body-bg.png") repeat scroll 0 0 #f3f3f3 ;
  /*background-color:#f1f1f1;*/
}
#page {
	
}

/* Headings */
h1,h2,h3,h4,h5,h6 {
	clear: both;
}
hr {
	background-color: #ccc;
	border: 0;
	height: 1px;
	margin-bottom: 1.625em;
}

/* Text elements */
p {
	margin-bottom: 1.625em;
}
ul, ol {
	margin: 0 0 1.625em 2.5em;
}
ul {
	list-style: square;
}
ol {
	list-style-type: decimal;
}
ol ol {
	list-style: upper-alpha;
}
ol ol ol {
	list-style: lower-roman;
}
ol ol ol ol {
	list-style: lower-alpha;
}
ul ul, ol ol, ul ol, ol ul {
	margin-bottom: 0;
}
dl {
	margin: 0 1.625em;
}
dt {
	font-weight: bold;
}
dd {
	margin-bottom: 1.625em;
}
strong {
	font-weight: bold;
}
cite, em, i {
	font-style: italic;
}
blockquote {
	font-family: Georgia, "Bitstream Charter", serif;
	font-style: italic;
	font-weight: normal;
	margin: 0 3em;
}
blockquote em, blockquote i, blockquote cite {
	font-style: normal;
}
blockquote cite {
	color: #666;
	font: 12px "Helvetica Neue", Helvetica, Arial, sans-serif;
	font-weight: 300;
	letter-spacing: 0.05em;
	text-transform: uppercase;
}
pre {
	background: #f4f4f4;
	font: 13px "Courier 10 Pitch", Courier, monospace;
	line-height: 1.5;
	margin-bottom: 1.625em;
	overflow: auto;
	padding: 0.75em 1.625em;
}
code, kbd {
	font: 13px Monaco, Consolas, "Andale Mono", "DejaVu Sans Mono", monospace;
}
abbr, acronym, dfn {
	border-bottom: 1px dotted #666;
	cursor: help;
}
address {
	display: block;
	margin: 0 0 1.625em;
}
ins {
	background: #fff9c0;
	text-decoration: none;
}
sup,
sub {
	font-size: 10px;
	height: 0;
	line-height: 1;
	position: relative;
	vertical-align: baseline;
}
sup {
	bottom: 1ex;
}
sub {
	top: .5ex;
}

/* Forms */
input[type=text],
input[type=password],
textarea {
	background: #fafafa;
	border: 1px solid #ddd;
	color: #888;
}
input[type=text]:focus,
textarea:focus {
	color: #373737;
}
textarea {
	padding-left: 3px;
	width: 98%;
}
input[type=text] {
	padding: 3px;
}
input#s {
	/* background: url(images/search.png) no-repeat 5px center; */
	-moz-border-radius: 2px;
	border-radius: 0px;
	font-size: 14px;
	height: 32px;
	line-height: 1.2em;
	padding: 2px 10px 2px 10px;
	border-right: none;
}
input#searchsubmit {
	display: none;
}

/* Links */
a {
	color: #1982d1;
	text-decoration: none;
}
a:focus,
a:active,
a:hover {
	text-decoration: underline;
}

/* Assistive text */
.assistive-text {
	position: absolute !important;
	clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
	clip: rect(1px, 1px, 1px, 1px);
}
#access a.assistive-text:active,
#access a.assistive-text:focus {
	/*background: #eee;
	border-bottom: 1px solid #ddd;
	color: #1982d1;
	clip: auto !important;
	font-size: 12px;
	position: absolute;
	text-decoration: underline;
	top: 0;
	left: 7.6%;*/
}


/* =Header
----------------------------------------------- */
.clear{ clear:both;}
#branding {
	padding: 0;
	position: relative;
	z-index: 9998;
	background: #ffffff;
}
#site-title {
	/*padding: 2% 0 0;*/
}
#site-title a {
	color: #111;
	font-size: 30px;
	font-weight: bold;
	line-height: 36px;
	text-decoration: none;
	text-indent:-9999px;
	line-height:0px;
	background:url(images/v2/logo.png) left top no-repeat;
	height:57px;
	width:288px;
	float:left;
}
#site-title a:hover,
#site-title a:focus,
#site-title a:active {
	color: #1982d1;
}
#site-description {
	color: #7a7a7a;
	font-size: 14px;
	margin: 0;
	display:none;
}
#branding img {
	height: auto;
	margin-bottom: -7px;
	width: 100%;
}
.topHeader{  padding: 20px 0 5px;}

/* =Menu
-------------------------------------------------------------- */
.menu{ /*float:right;*/}
#access {
	/*background:url(images/menu-bg.png) left top repeat-x;/* Show a solid color for older browsers */
	/*border-top:10px solid #bfbfbf;
	border-bottom:2px solid #bfbfbf;
	clear: both;*/
	display: block;
	float: right;
	margin: 0 auto 6px;
	margin-right:50px;
	/*width: 75%;*/
	
}
#access ul {
	font-size: 13px;
	list-style: none;
	margin: 5px 0 0 -0.8125em;
	padding-left: 0;
}
#access li {
	float: left;
	position: relative;
}
#access a {
	color:#b0aba5;
  display:block;
  padding: 7px;
	vertical-align:middle;
	text-decoration: none;
	text-align:center;
	font-size:15px;
	width:80px;
	
}
#access ul ul {
	-moz-box-shadow: 0 3px 3px rgba(0,0,0,0.2);
	-webkit-box-shadow: 0 3px 3px rgba(0,0,0,0.2);
	box-shadow: 0 3px 3px rgba(0,0,0,0.2);
	display: none;
	float: left;
	margin: 0;
	position: absolute;
	top: 3.333em;
	left: 0;
	width: 188px;
	z-index: 99999;
}
#access ul ul ul {
	left: 100%;
	top: 0;
}
#access ul ul a {
	background: #f9f9f9;
	border-bottom: 1px dotted #ddd;
	color: #444;
	font-size: 13px;
	font-weight: normal;
	height: auto;
	line-height: 1.4em;
	padding: 10px 10px;
	width: 168px;
}
#access li:hover > a,
#access ul ul :hover > a,
#access a:focus {
	background: #efefef;
}
#access li:hover > a,
#access a:focus {
	background: none; color:#3b2e1c; font-weight:normal; width:80px; cursor:pointer!important;
}
#access ul li:hover > ul {
	display: block;
}
#access .current-menu-item > a,
#access .current-menu-ancestor > a,
#access .current_page_item > a,
#access .current_page_ancestor > a {
	font-weight: bold;
	color:#3c3d3f;
}
#access ul li.current-menu-item a{ background: none; color:#3b2e1c; font-weight:normal; width:80px;}

.submitMenu{  position: absolute;
    right: 0;
    top: 70px; 
	color:#fff;
	 }
.submitMenu ul{ list-style-type:none;}
.submitMenu ul li a{ color:#fff; background:url("images/submit-menu-bg.png") left center no-repeat; padding-left:20px;}
.submitMenu ul li a:hover{ text-decoration:none;}
/* Search Form */
#branding #searchform {
	
	text-align: right;
	float:right;
	position:relative;
}
#branding #searchform div {
	margin: 0;
}
#branding #s {
	background-color: #fff;
	width: 180px;
}
#branding #s:focus {
	/*background-color: #f9f9f9;
	width: 196px;*/
}
#branding #searchsubmit {
	display: block;
	/*background: url(images/search-btn.png) left top no-repeat; */
	/* width:44px;  */
	height: 35px;
	border:none;
	float:right;
	text-indent:-9999px;
	line-height:0px;
	position:absolute; right:1px; top:2px;
	cursor:text;
	background: #fff;
}
#branding .only-search #searchform {
	top: 5px;
	z-index: 1;
}
#branding .only-search #s {
	background-color: #666;
	border-color: #000;
	color: #222;
}
#branding .only-search #s,
#branding .only-search #s:focus {
	width: 85%;
}
#branding .only-search #s:focus {
	background-color: #bbb;
}
#branding .with-image #searchform {
	top: auto;
	bottom: -27px;
	max-width: 195px;
}
#branding .only-search + #access div {
	padding-right: 205px;
}


/* =Content
----------------------------------------------- */

#main {
	clear: both;
	padding: 10px 0 0;
	position:relative;
}
.page-title {
	color: #666;
	font-size: 10px;
	font-weight: 500;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	margin: 0 0 2.6em;
	text-transform: uppercase;
}
.page-title a {
	font-size: 12px;
	font-weight: bold;
	letter-spacing: 0;
	text-transform: none;
}
.hentry,
.no-results {
	border-bottom: 1px solid #ddd;
	margin: 0 0 3em;
	padding: 0 0 1.625em;
	position: relative;
}
.hentry:last-child,
.no-results {
	border-bottom: none;
}
.blog .sticky .entry-header .entry-meta {
	clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
	clip: rect(1px, 1px, 1px, 1px);
	position: absolute !important;
}
.entry-title,
.entry-header .entry-meta {
	padding-right: 76px;
}
.entry-title {
	clear: both;
	color: #373737;
	font-size: 26px;
	font-weight: bold;
	line-height: 1.5em;
	padding-bottom: 15px;
    padding-top: 5px;
}
.entry-title,
.entry-title a {
	color: #222;
	text-decoration: none;
}
.entry-title a:hover,
.entry-title a:focus,
.entry-title a:active {
	color: #1982d1;
}
.entry-meta {
	color: #666;
	clear: both;
	font-size: 12px;
	line-height: 18px;
}
.entry-meta a {
	font-weight: bold;
}
.single-author .entry-meta .by-author {
	display: none;
}
.entry-content,
.entry-summary {
	padding: 0;
}
.entry-content h1,
.entry-content h2,
.comment-content h1,
.comment-content h2 {
	color: #000;
	font-weight: bold;
	margin: 0 0 .8125em;
}
.entry-content h3,
.comment-content h3 {
	font-size: 10px;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	text-transform: uppercase;
}
.entry-content table,
.comment-content table {
	border-bottom: 1px solid #ddd;
	margin: 0 0 1.625em;
	width: 100%;
}
.entry-content th,
.comment-content th {
	color: #666;
	font-size: 10px;
	font-weight: 500;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	text-transform: uppercase;
}
.entry-content td,
.comment-content td {
	border-top: 1px solid #ddd;
	padding: 6px 10px 6px 0;
}

.comment-content ul,
.comment-content ol {
	margin-bottom: 1.625em;
}
.comment-content ul ul,
.comment-content ol ol,
.comment-content ul ol,
.comment-content ol ul {
	margin-bottom: 0;
}
dl.gallery-item {
	margin: 0;
}
.page-link {
	clear: both;
	display: block;
	margin: 0 0 1.625em;
}
.page-link a {
	background: #eee;
	color: #373737;
	margin: 0;
	padding: 2px 3px;
	text-decoration: none;
}
.page-link a:hover {
	background: #888;
	color: #fff;
	font-weight: bold;
}
.page-link span {
	margin-right: 6px;
}
.entry-meta .edit-link a,
.commentlist .edit-link a {
	background: #eee;
	-moz-border-radius: 3px;
	border-radius: 3px;
	color: #666;
	float: right;
	font-size: 12px;
	line-height: 1.5em;
	font-weight: 300;
	text-decoration: none;
	padding: 0 8px;
}
.entry-meta .edit-link a:hover,
.commentlist .edit-link a:hover {
	background: #888;
	color: #fff;
}
.entry-content .edit-link {
	clear: both;
	display: block;
}

/* Images */
.entry-content img,
.comment-content img,
.widget img {
	/*max-width: 97.5%; /* Fluid images for posts, comments, and widgets */
}
img[class*="align"],
img[class*="wp-image-"],
img[class*="attachment-"] {
	height: auto; /* Make sure images with WordPress-added height and width attributes are scaled correctly */
}
img.size-full,
img.size-large {
	max-width: 97.5%;
	width: auto; /* Prevent stretching of full-size and large-size images with height and width attributes in IE8 */
	height: auto; /* Make sure images with WordPress-added height and width attributes are scaled correctly */
}
.entry-content img.wp-smiley {
	border: none;
	margin-bottom: 0;
	margin-top: 0;
	padding: 0;
}
img.alignleft,
img.alignright,
img.aligncenter {
	margin-bottom: 1.625em;
}
p img,
.wp-caption {
	margin-top: 0.4em;
}
.wp-caption {
	background: #eee;
	margin-bottom: 1.625em;
	max-width: 96%;
	padding: 9px;
}
.wp-caption img {
	display: block;
	margin: 0 auto;
	max-width: 98%;
}
.wp-caption .wp-caption-text,
.gallery-caption {
	color: #666;
	font-family: Georgia, serif;
	font-size: 12px;
}
.wp-caption .wp-caption-text {
	margin-bottom: 0.6em;
	padding: 10px 0 5px 40px;
	position: relative;
}
.wp-caption .wp-caption-text:before {
	color: #666;
	content: '\2014';
	font-size: 14px;
	font-style: normal;
	font-weight: bold;
	margin-right: 5px;
	position: absolute;
	left: 10px;
	top: 7px;
}
#content .gallery {
	margin: 0 auto 1.625em;
}
#content .gallery a img {
	border: none;
}
img#wpstats {
	display: block;
	margin: 0 auto 1.625em;
}
#content .gallery-columns-4 .gallery-item {
	width: 23%;
	padding-right: 2%;
}
#content .gallery-columns-4 .gallery-item img {
	width: 100%;
	height: auto;
}

/* Image borders */
img[class*="align"],
img[class*="wp-image-"],
#content .gallery .gallery-icon img {/* Add fancy borders to all WordPress-added images but not things like badges and icons and the like */
	border: 1px solid #ddd;
	padding: 6px;
}
.wp-caption img {
	border-color: #eee;
}
a:focus img[class*="align"],
a:hover img[class*="align"],
a:active img[class*="align"],
a:focus img[class*="wp-image-"],
a:hover img[class*="wp-image-"],
a:active img[class*="wp-image-"],
#content .gallery .gallery-icon a:focus img,
#content .gallery .gallery-icon a:hover img,
#content .gallery .gallery-icon a:active img {/* Add some useful style to those fancy borders for linked images ... */
	background: #eee;
	border-color: #bbb;
}
.wp-caption a:focus img,
.wp-caption a:active img,
.wp-caption a:hover img {/* ... including captioned images! */
	background: #fff;
	border-color: #ddd;
}

/* Make sure embeds and iframes fit their containers */
embed,
iframe,
object {
	max-width: 100%;
}

/* Password Protected Posts */
.post-password-required .entry-header .comments-link {
	margin: 1.625em 0 0;
}
.post-password-required input[type=password] {
	margin: 0.8125em 0;
}
.post-password-required input[type=password]:focus {
	background: #f7f7f7;
}

/* Author Info */
#author-info {
	font-size: 12px;
	overflow: hidden;
}
.singular #author-info {
	background: #f9f9f9;
	border-top: 1px solid #ddd;
	border-bottom: 1px solid #ddd;
	margin: 2.2em -35.6% 0 -35.4%;
	padding: 20px 35.4%;
}
.archive #author-info {
	border-bottom: 1px solid #ddd;
	margin: 0 0 2.2em;
	padding: 0 0 2.2em;
}
#author-avatar {
	float: left;
	margin-right: -78px;
}
#author-avatar img {
	background: #fff;
	-moz-border-radius: 3px;
	border-radius: 3px;
	-webkit-box-shadow: 0 1px 2px #bbb;
	-moz-box-shadow: 0 1px 2px #bbb;
	box-shadow: 0 1px 2px #bbb;
	padding: 3px;
}
#author-description {
	float: left;
	margin-left: 108px;
}
#author-description h2 {
	color: #000;
	font-size: 15px;
	font-weight: bold;
	margin: 5px 0 10px;
}

/* Comments link */
.entry-header .comments-link a {
	background: #eee url(images/comment-bubble.png) no-repeat;
	color: #666;
	font-size: 13px;
	font-weight: normal;
	line-height: 35px;
	overflow: hidden;
	padding: 0 0 0;
	position: absolute;
	top: 1.5em;
	right: 0;
	text-align: center;
	text-decoration: none;
	width: 43px;
	height: 36px;
}
.entry-header .comments-link a:hover,
.entry-header .comments-link a:focus,
.entry-header .comments-link a:active {
	background-color: #1982d1;
	color: #fff;
	color: rgba(255,255,255,0.8);
}
.entry-header .comments-link .leave-reply {
	visibility: hidden;
}

/*
Post Formats Headings
To hide the headings, display: none the ".entry-header .entry-format" selector,
and remove the padding rules below.
*/
.entry-header .entry-format {
	color: #666;
	font-size: 10px;
	font-weight: 500;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	position: absolute;
	text-transform: uppercase;
	top: -5px;
}
.entry-header hgroup .entry-title {
	padding-top: 15px;
}
article.format-aside .entry-content,
article.format-link .entry-content,
article.format-status .entry-content {
	padding: 20px 0 0;
}
article.format-status .entry-content {
	min-height: 65px;
}
.recent-posts .entry-header .entry-format {
	display: none;
}
.recent-posts .entry-header hgroup .entry-title {
	padding-top: 0;
}

/* Singular content styles for Posts and Pages */
.singular .hentry {
	border-bottom: none;
	position: relative;
}
.singular.page .hentry {
	padding: 0;
}
.singular .entry-title {
    /*border-bottom: 1px solid #CCCCCC;*/
    color: #373737;
    font-size: 28px;
    font-weight: normal;
    line-height: 30px;
}
.singular .entry-title,
.singular .entry-header .entry-meta {
	padding-right: 0;
}
.singular .entry-header .entry-meta {
	position: absolute;
	top: 0;
	left: 0;
}
blockquote.pull {
	font-size: 21px;
	font-weight: bold;
	line-height: 1.6125em;
	margin: 0 0 1.625em;
	text-align: center;
}
.singular blockquote.pull {
	margin: 0 -22.25% 1.625em;
}
.pull.alignleft {
	margin: 0 1.625em 0 0;
	text-align: right;
	width: 33%;
}
.singular .pull.alignleft {
	margin: 0 1.625em 0 -22.25%;
}
.pull.alignright {
	margin: 0 0 0 1.625em;
	text-align: left;
	width: 33%;
}
.singular .pull.alignright {
	margin: 0 -22.25% 0 1.625em;
}
.singular blockquote.pull.alignleft,
.singular blockquote.pull.alignright {
	width: 33%;
}
.singular .entry-meta .edit-link a {
	/*bottom: auto;
	left: 50px;
	position: absolute;
	right: auto;
	top: 80px;*/
	margin-top:10px;
}


/* =Aside
----------------------------------------------- */

.format-aside .entry-title,
.format-aside .entry-header .comments-link {
	display: none;
}
.singular .format-aside .entry-title {
	display: block;
}
.format-aside .entry-content {
	padding: 0;
}
.singular .format-aside .entry-content {
	padding: 1.625em 0 0;
}


/* =Link
----------------------------------------------- */

.format-link .entry-title,
.format-link .entry-header .comments-link {
	display: none;
}
.singular .format-link .entry-title {
	display: block;
}
.format-link .entry-content {
	padding: 0;
}
.singular .format-link .entry-content {
	padding: 1.625em 0 0;
}


/* =Gallery
----------------------------------------------- */

.format-gallery .gallery-thumb {
	float: left;
	display: block;
	margin: .375em 1.625em 0 0;
}


/* =Status
----------------------------------------------- */

.format-status .entry-title,
.format-status .entry-header .comments-link {
	display: none;
}
.singular .format-status .entry-title {
	display: block;
}
.format-status .entry-content {
	padding: 0;
}
.singular .format-status .entry-content {
	padding: 1.625em 0 0;
}
.format-status img.avatar {
	-moz-border-radius: 3px;
	border-radius: 3px;
	-webkit-box-shadow: 0 1px 2px #ccc;
	-moz-box-shadow: 0 1px 2px #ccc;
	box-shadow: 0 1px 2px #ccc;
	float: left;
	margin: 4px 10px 2px 0;
	padding: 0;
}


/* =Quote
----------------------------------------------- */

.format-quote blockquote {
	color: #555;
	font-size: 17px;
	margin: 0;
}


/* =Image
----------------------------------------------- */

.indexed.format-image .entry-header {
	min-height: 61px; /* Prevent the comment icon from colliding with the image when there is no title */
}
.indexed.format-image .entry-content {
	padding-top: 0.5em;
}
.indexed.format-image p,
.indexed.format-image p img {
	margin-bottom: 0;
}
.indexed.format-image footer.entry-meta {
	background: #ddd;
	margin-top: -7px;
	padding: 20px 30px;
	overflow: hidden;
}
.indexed.format-image div.entry-meta {
	display: inline-block;
	float: left;
	width: 35%;
}
.indexed.format-image div.entry-meta + div.entry-meta {
	float: none;
	width: 65%;
}
.indexed.format-image .entry-meta span.cat-links,
.indexed.format-image .entry-meta span.tag-links,
.indexed.format-image .entry-meta span.comments-link {
	display: block;
}
.indexed.format-image footer.entry-meta a {
	color: #444;
}
.indexed.format-image footer.entry-meta a:hover {
	color: #fff;
}
#content .indexed.format-image img {
	border: none;
	max-width: 100%;
	padding: 0;
}
.indexed.format-image .wp-caption {
	background: #111;
	margin-bottom: 0;
	max-width: 96%;
	padding: 11px;
}
.indexed.format-image .wp-caption .wp-caption-text {
	color: #ddd;
}
.indexed.format-image .wp-caption .wp-caption-text:before {
	color: #444;
}
.indexed.format-image a:hover img {
	opacity: 0.8;
}


/* =error404
----------------------------------------------- */

.error404 #main #searchform {
	overflow: hidden;
	padding: 2%;
	margin:2%;
}
.error404 ul{ margin-left:10px!important;}
.error404 #main #s {
	width: 95%;
}
.error404 #main .widget {
	clear: none;
	float: left;
	margin-right: 3.7%;
	width: 30.85%;
}
.error404 #main .widget_archive {
	margin-right: 0;
}
.error404 #main .widget_tag_cloud {
	float: none;
	margin-right: 0;
	width: 100%;
}
.error404 .widgettitle {
	font-size: 10px;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	text-transform: uppercase;
}


/* =Showcase
----------------------------------------------- */

h1.showcase-heading {
	color: #666;
	font-size: 10px;
	font-weight: 500;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	text-transform: uppercase;
}

/* Intro */
article.intro {
	background: #f9f9f9;
	border-bottom: none;
	margin: -1.855em -8.9% 1.625em;
	padding: 0 8.9%;
}
article.intro .entry-title {
	display: none;
}
article.intro .entry-content {
	color: #111;
	font-size: 16px;
	padding: 1.625em 0 0.625em;
}
article.intro .edit-link a {
	background: #aaa;
	-moz-border-radius: 3px;
	border-radius: 3px;
	color: #fff;
	font-size: 12px;
	padding: 0 8px;
	position: absolute;
	top: 30px;
	right: 20px;
	text-decoration: none;
}
article.intro .edit-link a:hover,
article.intro .edit-link a:focus,
article.intro .edit-link a:active {
	background: #777;
}

/* Featured post */
section.featured-post {
	float: left;
	margin: -1.625em -8.9% 1.625em;
	padding: 1.625em 8.9% 0;
	position: relative;
	width: 100%;
}
section.featured-post .hentry {
	border: none;
	color: #666;
	margin: 0;
}
section.featured-post .entry-meta {
	clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
	clip: rect(1px, 1px, 1px, 1px);
	position: absolute !important;
}

/* Small featured post */
section.featured-post .attachment-small-feature {
	float: right;
	height: auto;
	margin: 0 -8.9% 1.625em 0;
	max-width: 59%;
	position: relative;
	right: -15px;
}
section.featured-post.small {
	padding-top: 0;
}
section.featured-post .attachment-small-feature:hover,
section.featured-post .attachment-small-feature:focus,
section.featured-post .attachment-small-feature:active {
	opacity: .8;
}
article.feature-image.small {
	float: left;
	margin: 0 0 1.625em;
	width: 45%;
}
article.feature-image.small .entry-title {
	line-height: 1.2em;
}
article.feature-image.small .entry-summary {
	color: #555;
	font-size: 13px;
}
article.feature-image.small .entry-summary p a {
	background: #222;
	color: #eee;
	display: block;
	left: -23.8%;
	padding: 9px 26px 9px 85px;
	position: relative;
	text-decoration: none;
	top: 20px;
	width: 180px;
	z-index: 1;
}
article.feature-image.small .entry-summary p a:hover {
	background: #1982d1;
	color: #eee;
	color: rgba(255,255,255,0.8);
}

/* Large featured post */
section.feature-image.large {
	border: none;
	max-height: 288px;
	padding: 0;
	width: 100%;
}
section.feature-image.large .showcase-heading {
	display: none;
}
section.feature-image.large .hentry {
	border-bottom: none;
	left: 9%;
	margin: 1.625em 9% 0 0;
	position: absolute;
	top: 0;
}
article.feature-image.large .entry-title a {
	background: #222;
	background: rgba(0,0,0,0.8);
	-moz-border-radius: 3px;
	border-radius: 3px;
	color: #fff;
	display: inline-block;
	font-weight: 300;
	padding: .2em 20px;
}
section.feature-image.large:hover .entry-title a,
section.feature-image.large .entry-title:hover a {
	background: #eee;
	background: rgba(255,255,255,0.8);
	color: #222;
}
article.feature-image.large .entry-summary {
	display: none;
}
section.feature-image.large img {
	display: block;
	height: auto;
	max-width: 117.9%;
	padding: 0 0 6px;
}

/* Featured Slider */
.featured-posts {
	border-bottom: 1px solid #ddd;
	display: block;
	height: 328px;
	margin: 1.625em -8.9% 20px;
	max-width: 1024px;
	padding: 0;
	position: relative;
	overflow: hidden;
}
.featured-posts .showcase-heading {
	padding-left: 8.9%;
}
.featured-posts section.featured-post {
	background: #fff;
	height: 288px;
	left: 0;
	margin: 0;
	position: absolute;
	top: 30px;
	width: auto;
}
.featured-posts section.featured-post.large {
	max-width: 100%;
	overflow: hidden;
}
.featured-posts section.featured-post {
	-webkit-transition-duration: 200ms;
	-webkit-transition-property: opacity, visibility;
	-webkit-transition-timing-function: ease;
	-moz-transition-duration: 200ms;
	-moz-transition-property: opacity, visibility;
	-moz-transition-timing-function: ease;
}
.featured-posts section.featured-post {
	opacity: 0;
	visibility: hidden;
}
.featured-posts #featured-post-1 {
	opacity: 1;
	visibility: visible;
}
.featured-post .feature-text:after,
.featured-post .feature-image.small:after {
	content: ' ';
	background: -moz-linear-gradient(top, rgba(255,255,255,0) 0%, rgba(255,255,255,1) 100%); /* FF3.6+ */
	background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(255,255,255,0)), color-stop(100%,rgba(255,255,255,1))); /* Chrome,Safari4+ */
	background: -webkit-linear-gradient(top, rgba(255,255,255,0) 0%,rgba(255,255,255,1) 100%); /* Chrome10+,Safari5.1+ */
	background: -o-linear-gradient(top, rgba(255,255,255,0) 0%,rgba(255,255,255,1) 100%); /* Opera11.10+ */
	background: -ms-linear-gradient(top, rgba(255,255,255,0) 0%,rgba(255,255,255,1) 100%); /* IE10+ */
	filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#00ffffff', endColorstr='#ffffff',GradientType=0 ); /* IE6-9 */
	background: linear-gradient(top, rgba(255,255,255,0) 0%,rgba(255,255,255,1) 100%); /* W3C */
	width: 100%;
	height: 45px;
	position: absolute;
	top: 230px;
}
.featured-post .feature-image.small:after {
	top: 253px;
}
#content .feature-slider {
	top: 5px;
	right: 8.9%;
	overflow: visible;
	position: absolute;
}
.feature-slider ul {
	list-style-type: none;
	margin: 0;
}
.feature-slider li {
	float: left;
	margin: 0 6px;
}
.feature-slider a {
	background: #3c3c3c;
	background: rgba(60,60,60,0.9);
	-moz-border-radius: 12px;
	border-radius: 12px;
	-webkit-box-shadow: inset 1px 1px 5px rgba(0,0,0,0.5), inset 0 0 2px rgba(255,255,255,0.5);
	-moz-box-shadow: inset 1px 1px 5px rgba(0,0,0,0.5), inset 0 0 2px rgba(255,255,255,0.5);
	box-shadow: inset 1px 1px 5px rgba(0,0,0,0.5), inset 0 0 2px rgba(255,255,255,0.5);
	display: block;
	width: 14px;
	height: 14px;
}
.feature-slider a.active {
	background: #1982d1;
	-webkit-box-shadow: inset 1px 1px 5px rgba(0,0,0,0.4), inset 0 0 2px rgba(255,255,255,0.8);
	-moz-box-shadow: inset 1px 1px 5px rgba(0,0,0,0.4), inset 0 0 2px rgba(255,255,255,0.8);
	box-shadow: inset 1px 1px 5px rgba(0,0,0,0.4), inset 0 0 2px rgba(255,255,255,0.8);
	cursor: default;
	opacity: 0.5;
}

/* Recent Posts */
section.recent-posts {
	padding: 0 0 1.625em;
}
section.recent-posts .hentry {
	border: none;
	margin: 0;
}
section.recent-posts .other-recent-posts {
	border-bottom: 1px solid #ddd;
	list-style: none;
	margin: 0;
}
section.recent-posts .other-recent-posts li {
	padding: 0.3125em 0;
	position: relative;
}
section.recent-posts .other-recent-posts .entry-title {
	border-top: 1px solid #ddd;
	font-size: 17px;
}
section.recent-posts .other-recent-posts a[rel="bookmark"] {
	color: #373737;
	float: left;
	max-width: 84%;
}
section.recent-posts .other-recent-posts a[rel="bookmark"]:after {
	content: '-';
	color: transparent;
	font-size: 11px;
}
section.recent-posts .other-recent-posts a[rel="bookmark"]:hover {
}
section.recent-posts .other-recent-posts .comments-link a,
section.recent-posts .other-recent-posts .comments-link > span {
	border-bottom: 2px solid #999;
	bottom: -2px;
	color: #444;
	display: block;
	font-size: 10px;
	font-weight: 500;
	line-height: 2.76333em;
	padding: 0.3125em 0 0.3125em 1em;
	position: absolute;
	right: 0;
	text-align: right;
	text-transform: uppercase;
	z-index: 1;
}
section.recent-posts .other-recent-posts .comments-link > span {
	border-color: #bbb;
	color: #888;
}
section.recent-posts .other-recent-posts .comments-link a:hover {
	color: #1982d1;
	border-color: #1982d1;
}
section.recent-posts .other-recent-posts li:after {
	clear: both;
	content: '.';
	display: block;
	height: 0;
	visibility: hidden;
}


/* =Attachments
----------------------------------------------- */

.image-attachment div.attachment {
	background: #f9f9f9;
	border: 1px solid #ddd;
	border-width: 1px 0;
	margin: 0 -8.9% 1.625em;
	overflow: hidden;
	padding: 1.625em 1.625em 0;
	text-align: center;
}
.image-attachment div.attachment img {
	display: block;
	height: auto;
	margin: 0 auto 1.625em;
	max-width: 100%;
}
.image-attachment div.attachment a img {
	border-color: #f9f9f9;
}
.image-attachment div.attachment a:focus img,
.image-attachment div.attachment a:hover img,
.image-attachment div.attachment a:active img {
	border-color: #ddd;
	background: #fff;
}
.image-attachment .entry-caption p {
	font-size: 10px;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	margin: 0 0 2.6em;
	text-transform: uppercase;
}


/* =Navigation
-------------------------------------------------------------- */

#content nav {
	clear: both;
	overflow: hidden;
	padding: 0 0 1.625em;
}
#content nav a {
	font-size: 12px;
	font-weight: bold;
	line-height: 2.2em;
}
#nav-above {
	padding: 0 0 1.625em;
}
#nav-above {
	display: none;
}
.paged #nav-above {
	display: block;
}
.nav-previous {
	float: left;
	width: 50%;
}
.nav-next {
	float: right;
	text-align: right;
	width: 50%;
}
#content nav .meta-nav {
	font-weight: normal;
}

/* Singular navigation */
#nav-single {
	float: right;
	position: relative;
	top: -0.3em;
	text-align: right;
	z-index: 1;
}
#nav-single .nav-previous,
#nav-single .nav-next {
	float: none;
	width: auto;
}
#nav-single .nav-next {
	padding-left: .5em;
}


/* =Widgets
----------------------------------------------- */

.widget-area {
	font-size: 12px;
}
.widget {
	clear: both;
	margin: 0 0 2.2em;
}
.widget-title {
	color: #7f7f7f;
	font-size: 10px;
	font-weight: 500;
	letter-spacing: 0.1em;
	line-height: 2.6em;
	text-transform: uppercase;
}
.widget ul {
	font-size: 15px;
	margin: 0;
}
.widget ul ul {
	margin-left: 1.5em;
}
.widget ul li {
	color: #777;
	font-size: 13px;
}
.widget a {
	font-weight: bold;
	text-decoration: none;
}
.widget a:hover,
.widget a:focus,
.widget a:active {
	text-decoration: underline;
}

/* Search Widget */
.widget_search form {
	margin: 0 0 1.625em;
}
.widget_search #s {
	width: 65%;
}
.widget_search #searchsubmit {
	background: #ddd;
	border: 1px solid #ccc;
	-webkit-box-shadow: inset 0px -1px 1px rgba(0, 0, 0, 0.09);
	-moz-box-shadow: inset 0px -1px 1px rgba(0, 0, 0, 0.09);
	box-shadow: inset 0px -1px 1px rgba(0, 0, 0, 0.09);
	color: #888;
	font-size: 13px;
	line-height: 25px;
	position: relative;
	top: -2px;
}
.widget_search #searchsubmit:active {
	background: #1982d1;
	border-color: #0861a5;
	-webkit-box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.1);
	-moz-box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.1);
	box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.1);
	color: #bfddf3;
}

/* Ephemera Widget */
section.ephemera ol,
.widget_csszeal_ephemera ol {
	list-style: square;
	margin: 5px 0 0;
}
.widget_csszeal_ephemera .widget-entry-title {
	font-size: 15px;
	font-weight: bold;
	padding: 0;
}
.widget_csszeal_ephemera .comments-link a,
.widget_csszeal_ephemera .comments-link > span {
	color: #666;
	display: block;
	font-size: 10px;
	font-weight: 500;
	line-height: 2.76333em;
	text-transform: uppercase;
}
section.ephemera .entry-title .comments-link a:hover,
.widget_csszeal_ephemera .entry-title .comments-link a:hover {
}
section.ephemera .entry-title a span {
	color: #29628d;
}

/* Twitter */
.widget_twitter li {
	list-style-type: none;
	margin-bottom: 14px;
}
.widget_twitter .timesince {
	display: block;
	font-size: 11px;
	margin-right: -10px;
	text-align: right;
}

/* Widget Image */
.widget_image img {
	height: auto;
	max-width: 100%;
}

/* Calendar Widget */

.widget_calendar #wp-calendar {
	color: #555;
	width: 95%;
	text-align: center;
}
.widget_calendar #wp-calendar caption,
.widget_calendar #wp-calendar td,
.widget_calendar #wp-calendar th {
	text-align: center;
}
.widget_calendar #wp-calendar caption {
	font-size: 11px;
	font-weight: 500;
	padding: 5px 0 3px 0;
	text-transform: uppercase;
}
.widget_calendar #wp-calendar th {
	background: #f4f4f4;
	border-top: 1px solid #ccc;
	border-bottom: 1px solid #ccc;
	font-weight: bold;
}
.widget_calendar #wp-calendar tfoot td {
	background: #f4f4f4;
	border-top: 1px solid #ccc;
	border-bottom: 1px solid #ccc;
}


/* =Comments
----------------------------------------------- */

#comments-title {
	color: #666;
	font-size: 10px;
	font-weight: 500;
	line-height: 2.6em;
	padding: 0 0 2.6em;
	text-transform: uppercase;
}
.nopassword,
.nocomments {
	color: #aaa;
	font-size: 24px;
	font-weight: 100;
	margin: 26px 0;
	text-align: center;
}
.commentlist {
	list-style: none;
	margin: 0 0 0 100px;
	width: 68.9%;
}
.content .commentlist,
.page-template-sidebar-page-php .commentlist {
	width: 100%; /* reset the width for the one-column and sidebar page layout */
}
.commentlist > li.comment {
	margin: 0 0 60px;
	position: relative;
}
.commentlist .pingback {
	margin: 0 0 1.625em;
	padding: 0 1.625em;
}
.commentlist .children {
	list-style: none;
	margin: 0;
}
.commentlist .children li.comment {
	background: #fff;
	border-left: 1px solid #ddd;
	-moz-border-radius: 0 3px 3px 0;
	border-radius: 0 3px 3px 0;
	margin: 1.625em 0 0;
	padding: 1.625em;
	position: relative;
}
.commentlist .children li.comment .fn {
	display: block;
}
.comment-meta .fn {
	font-style: normal;
}
.comment-meta {
	color: #666;
	font-size: 12px;
	line-height: 2.2em;
}
.commentlist .children li.comment .comment-meta {
	line-height: 1.625em;
	margin-left: 50px;
}
.commentlist .children li.comment .comment-content {
	margin: 1.625em 0 0;
}
.comment-meta a {
	font-weight: bold;
}
.comment-meta a:focus,
.comment-meta a:active,
.comment-meta a:hover {
}
.commentlist .avatar {
	-moz-border-radius: 3px;
	border-radius: 3px;
	-webkit-box-shadow: 0 1px 2px #ccc;
	-moz-box-shadow: 0 1px 2px #ccc;
	box-shadow: 0 1px 2px #ccc;
	left: -102px;
	padding: 0;
	position: absolute;
	top: 0;
}
.commentlist > li:before {
	
}
.commentlist > li.pingback:before {
	content: '';
}
.commentlist .children .avatar {
	background: none;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
	box-shadow: none;
	left: 2.2em;
	padding: 0;
	top: 2.2em;
}
a.comment-reply-link {
	
	color: #666;
	display: inline-block;
	font-size: 12px;
	padding: 0 8px;
	text-decoration: none;
}
a.comment-reply-link:hover,
a.comment-reply-link:focus,
a.comment-reply-link:active {
	text-decoration:underline;
}
a.comment-reply-link > span {
	display: inline-block;
	position: relative;
	top: -1px;
}

/* Post author highlighting */
.commentlist > li.bypostauthor {
	/*background: #ddd;*/
	border-color: #d3d3d3;
}
.commentlist > li.bypostauthor .comment-meta {
	color: #575757;
}
.commentlist > li.bypostauthor .comment-meta a:focus,
.commentlist > li.bypostauthor .comment-meta a:active,
.commentlist > li.bypostauthor .comment-meta a:hover {
}
.commentlist > li.bypostauthor:before {
	/*content: url(images/comment-arrow-bypostauthor.png);*/
}

/* Post Author threaded comments */
.commentlist .children > li.bypostauthor {
	background: #ddd;
	border-color: #d3d3d3;
}

/* sidebar-page.php comments */
/* Make sure we have room for our comment avatars */
.page-template-sidebar-page-php .commentlist > li.comment,
.page-template-sidebar-page-php.commentlist .pingback {
	margin-left: 102px;
	width: auto;
}
/* And a full-width comment form */
.page-template-sidebar-page-php #respond {
	width: auto;
}

/* Comment Form */
#respond {
	position: relative;
	width: 70%;
}
#respond input[type="text"],
#respond textarea {
	background: #fff;
	border: 1px solid #E6E6E6;
	position: relative;
	padding: 10px;
	-moz-border-radius:5px;
	-webkit-border-radius:5px;
	border-radius:5px;
}
#respond .comment-form-author,
#respond .comment-form-email,
#respond .comment-form-url,
#respond .comment-form-comment {
	position: relative;
}
#respond .comment-form-author label,
#respond .comment-form-email label,
#respond .comment-form-url label,
#respond .comment-form-comment label {
	
	color: #555;
	display: inline-block;
	font-size: 14px;
	padding: 4px;
	z-index: 1;
	font-weight:bold;
}
#respond input[type="text"]:focus,
#respond textarea:focus {
	text-indent: 0;
	z-index: 1;
}
#respond textarea {
	resize: vertical;
	width: 75%;
	display:block;
}
#respond .comment-form-author .required,
#respond .comment-form-email .required {
	color: #bd3500;
	z-index: 1;
}
#respond .comment-notes,
#respond .logged-in-as {
	font-size: 13px;
}
#respond p {
	margin: 10px 0;
}
#respond .form-submit {
	float: left;
	margin: -20px 0 10px;
}
#respond input#submit {
	background: url('images/v2/comment-submit.gif') left top no-repeat;
	border: none;
	cursor: pointer;
	font-size: 15px;
	margin: 20px 0;
	text-indent:-9999px;
	line-height:0px;
	padding: 5px 42px 5px 22px;
	position: relative;
	width:166px;
	height:50px;
	
	
}
#respond input#submit:active {
	background: #1982d1;
	color: #bfddf3;
}
#respond #cancel-comment-reply-link {
	color: #666;
	margin-left: 10px;
	text-decoration: none;
}
#respond .logged-in-as a:hover,
#respond #cancel-comment-reply-link:hover {
	text-decoration: underline;
}
.commentlist #respond {
	margin: 1.625em 0 0;
	width: auto;
}
#reply-title {
	color: #373737;
	font-size: 24px;
	font-weight: bold;
	line-height: 30px;
}
#cancel-comment-reply-link {
	color: #888;
	display: block;
	font-size: 10px;
	font-weight: normal;
	line-height: 2.2em;
	letter-spacing: 0.05em;
	position: absolute;
	right: 1.625em;
	text-decoration: none;
	text-transform: uppercase;
	top: 1.1em;
}
#cancel-comment-reply-link:focus,
#cancel-comment-reply-link:active,
#cancel-comment-reply-link:hover {
	color: #ff4b33;
}
#respond label {
	line-height: 2.2em;
}
#respond input[type=text] {
	display: block;
	height: 24px;
	width: 75%;
}
#respond p {
	font-size: 12px;
}
p.comment-form-comment {
	margin: 0;
}
.form-allowed-tags {
	display: none;
}


/* =Footer
----------------------------------------------- */

#colophon {
	clear: both;
	background:#ffffff;
}
#supplementary {
	padding: 30px 0px;
	overflow: hidden;
	margin:0px auto;
	width:1150px;
}

/* Two Footer Widget Areas */
#supplementary.two .widget-area {
	float: left;
	margin-right: 3.7%;
	width: 48.1%;
}
#supplementary.two .widget-area + .widget-area {
	margin-right: 0;
}

/* Three Footer Widget Areas */
#supplementary.three .widget-area {
	float: left;
	margin-right: 3.7%;
	width: 30.85%;
}
#supplementary.three .widget-area + .widget-area + .widget-area {
	margin-right: 0;
}

/* Site Generator Line */
.footerWrapper{ width:1150px; margin:0px auto; }
#site-generator {
	background: #ffffff;
	color: #AAABAC;
	font-size: 12px;
	line-height: 2.2em;
	padding: 1.2em 0.5em 1.2em 0;
	text-align: left;
	width:34%;
	float:left;
}
#site-generator a{color:#AAABAC!important;}
.footerMenu{ float:right; width:64%; padding-top:1.2em;}
.footerMenu ul li{ display:inline; margin-left:30px; color:#596659!important;}
.footerMenu ul li a{ color:#AAABAC!important;}
.footerMenu ul{}
#site-generator a {
	color: #555;
	font-weight: normal;
}
#site-generator .sep {
	background: url(images/wordpress.png) center left no-repeat;
	color: transparent;
	display: inline-block;
	height: 16px;
	line-height: 16px;
	margin: 0 7px;
	width: 16px;
}
.footerMenu ul { margin:0px;}
.footerMenu ul li{ display:none;}
.footerMenu ul li.submitWebsiteLink { /*display:block;*/}

/* =Responsive Structure
----------------------------------------------- */

@media (max-width: 800px) {
	.home .submissionCounter{ display:none;}
	/* Simplify the basic layout */
	#main #content {
		margin: 0 0.6%;
		
		width:98%!important;
	}
	#nav-below {
		border-bottom: 1px solid #ddd;
		margin-bottom: 1.625em;
	}
	#main #secondary {
		float: none;
		margin: 0 7.6%;
		width: auto;
	}
	/* Simplify the showcase template */
	.page-template-showcase-php .featured-posts {
		min-height: 280px;
	}
	.featured-posts section.featured-post {
		height: auto;
	}
	.page-template-showcase-php section.recent-posts {
		float: none;
		margin: 0;
		width: 100%;
	}
	.page-template-showcase-php #main .widget-area {
		float: none;
		margin: 0;
		width: auto;
	}
	.page-template-showcase-php .other-recent-posts {
		border-bottom: 1px solid #ddd;
	}
	/* Simplify the showcase template when small feature */
	section.featured-post .attachment-small-feature,
	.one-column section.featured-post .attachment-small-feature {
		border: none;
		display: block;
		float: left;
		height: auto;
		margin: 0.625em auto 1.025em;
		max-width: 30%;
		position: static;
	}
	article.feature-image.small {
		float: right;
		margin: 0 0 1.625em;
		width: 64%;
	}
	.one-column article.feature-image.small .entry-summary {
		height: auto;
	}
	article.feature-image.small .entry-summary p a {
		left: 0;
		padding-left: 20px;
		padding-right: 20px;
		width: auto;
	}
	/* Remove the margin on singular articles */
	.singular .entry-header,
	.singular .entry-content,
	.singular footer.entry-meta,
	.singular #comments-title {
		width: 100%;
	}
	/* Simplify the pullquotes and pull styles */
	.singular blockquote.pull {
		margin: 0 0 1.625em;
	}
	.singular .pull.alignleft {
		margin: 0 1.625em 0 0;
	}
	.singular .pull.alignright {
		margin: 0 0 0 1.625em;
	}
	.singular .entry-meta .edit-link a {
		left: 0;
		position: absolute;
		top: 40px;
	}
	.singular #author-info {
		margin: 2.2em -8.8% 0;
		padding: 20px 8.8%;
	}
	/* Make sure we have room for our comment avatars */
	.commentlist {
		width: 100%;
	}
	.commentlist > li.comment,
	.commentlist .pingback {
		margin-left: 102px;
		width: auto;
	}
	/* And a full-width comment form */
	#respond {
		width: auto;
	}
	/* No need to float footer widgets at this size */
	#colophon #supplementary .widget-area {
		float: none;
		margin-right: 0;
		width: auto;
	}
	/* No need to float 404 widgets at this size */
	.error404 #main .widget {
		float: none;
		margin-right: 0;
		width: auto;
	}
	

}
@media (max-width: 650px) {
	/* @media (max-width: 650px) Reduce font-sizes for better readability on smaller devices */
	body, input, textarea {
		font-size: 13px;
	}
	.headerRight{ float:left!important; width:100%!important;}
	#access{ width:100%}
	#site-title a {
		font-size: 24px;
	}
	#site-description {
		font-size: 12px;
	}
	#access ul {
		font-size: 12px;
	}
	article.intro .entry-content {
		font-size: 12px;
	}
	.entry-title {
		font-size: 21px;
	}
	.featured-post .entry-title {
		font-size: 14px;
	}
	.singular .entry-title {
		font-size: 28px;
	}
	.entry-meta {
		font-size: 12px;
	}
	blockquote {
		margin: 0;
	}
	blockquote.pull {
		font-size: 17px;
	}
	/* Reposition the site title and description slightly */
	#site-title {
	 float:left;
	}
	#site-title,
	#site-description {
		margin-right: 0;
	}
	/* Make sure the logo and search form don't collide */
	#branding #searchform {
		/*top: 1.625em !important;*/
	}
	/* Floated content doesn't work well at this size */
	.alignleft,
	.alignright {
		float: none;
		margin-left: 0;
		margin-right: 0;
	}
	/* Make sure the post-post navigation doesn't collide with anything */
	#nav-single {
		display: block;
		position: static;
	}
	.singular .hentry {
		padding: 1.625em 0 0;
	}
	.singular.page .hentry {
		width:100%!important; padding:0.4em 0 0 0 ; margin:0;
	}
	/* Talking avatars take up too much room at this size */
	.commentlist > li.comment,
	.commentlist > li.pingback {
		margin-left: 0 !important;
	}
	.commentlist .avatar {
		background: transparent;
		display: block;
		padding: 0;
		position: static;
	}
	.commentlist .children .avatar {
		background: none;
		left: 2.2em;
		padding: 0;
		position: absolute;
		top: 2.2em;
	}
	/* Use the available space in the smaller comment form */
	#respond input[type="text"] {
		width: 95%;
	}
	#respond .comment-form-author .required,
	#respond .comment-form-email .required {
		left: 95%;
	}
	#content .gallery-columns-3 .gallery-item {
		width: 31%;
		padding-right: 2%;
	}
	#content .gallery-columns-3 .gallery-item img {
		width: 100%;
		height: auto;
	}
	#supplementary, .footerWrapper{ width:100%!important;}
	.entry-content .siteLink a{ font-size:12px;}
	
	.entry-content a.viewAllAnchor{ font-size:14px!important;}
	.viewAllLink a{ background-size:100%!important;}
	.searchOuter .hentry, .ui-tabs-panel .hentry, .catDisplay .hentry, #catsData .hentry{ width:100%!important; padding:0.4em 0 0 0 ; margin:0;}
	.showcase{ background-size:90%!important; width:83%!important; margin-bottom:15px!important; padding:30px 20px !important;}
 .footerMenu{word-wrap:break-word; width:145px!important;}
 #site-generator{ width:50%!important;word-wrap:break-word;}
 .headerRight .headerSearch{ width:200px; margin:0px 10px!important; float:right!important; }
 
  .headerRight .headerSearch #s{ margin-bottom:10px;}
  #page .pagination span, .pagination a{ padding:10px 4px 10px!important; margin:2px 2px 2px 0!important; font-size:8px!important; }
}
@media (max-width: 320px) {
#site-generator{ width:31%!important;word-wrap:break-word;}
}
@media (max-width: 450px) {
	#content .gallery-columns-2 .gallery-item {
		width: 45%;
		padding-right: 4%;
	}
	#content .gallery-columns-2 .gallery-item img {
		width: 100%;
		height: auto;
	}
	.searchOuter .hentry, .ui-tabs-panel .hentry, .catDisplay .hentry, #catsData .hentry{ width:100%!important; padding:0.4em 0 0 0 ; margin:0;}
	

}
@media only screen and (min-device-width: 320px) and (max-device-width: 480px) {
	body {
		padding: 0;
	}
	#page {
		margin-top: 0;
	}
	#branding {
		border-top: none;
	}
	.shoutOuter{ width:100%;}
	.entry-content img, .comment-content img, .widget img{ width:100%;}
	#main #content{ margin: 0 0.6%; width: 98% !important;}
	.searchOuter .hentry, .ui-tabs-panel .hentry, .catDisplay .hentry, #catsData .hentry{ width:100%!important; padding:0.4em 0 0 0 ; margin:0;}

}


/* =Print
----------------------------------------------- */

@media print {
	body {
		background: none !important;
		font-size: 10pt;
	}
	footer.entry-meta a[rel=bookmark]:link:after,
	footer.entry-meta a[rel=bookmark]:visited:after {
		content: " [" attr(href) "] "; /* Show URLs */
	}
	#page {
		clear: both !important;
		display: block !important;
		float: none !important;
		max-width: 100%;
		position: relative !important;
	}
	#branding {
		border-top: none !important;
		padding: 0;
	}
	#branding hgroup {
		margin: 0;
	}
	#site-title a {
		font-size: 21pt;
	}
	#site-description {
		font-size: 10pt;
	}
	#branding #searchform {
		display: none;
	}
	#branding img {
		display: none;
	}
	#access {
		display: none;
	}
	#main {
		border-top: none;
		box-shadow: none;
	}
	#primary {
		float: left;
		margin: 0;
		width: 100%;
	}
	#content {
		margin: 0;
		width: auto;
	}
	.singular #content {
		margin: 0;
		width: 100%;
	}
	.singular .entry-header .entry-meta {
		position: static;
	}
	.entry-meta .edit-link a {
		display: none;
	}
	#content nav {
		display: none;
	}
	.singular .entry-header,
	.singular .entry-content,
	.singular footer.entry-meta,
	.singular #comments-title {
		margin: 0;
		width: 100%;
	}
	.singular .hentry {
		padding: 0;
	}
	.entry-title,
	.singular .entry-title {
		font-size: 21pt;
	}
	.entry-meta {
		font-size: 10pt;
	}
	.entry-header .comments-link {
		display: none;
	}
	.page-link {
		display: none;
	}
	.singular #author-info {
		background: none;
		border-bottom: none;
		border-top: none;
		margin: 2.2em 0 0;
		padding: 0;
	}
	#respond {
		display: none;
	}
	.widget-area {
		display: none;
	}
	#colophon {
		display: none;
	}

	/* Comments */
	.commentlist > li.comment {
		background: none;
		border: 1px solid #ddd;
		-moz-border-radius: 3px 3px 3px 3px;
		border-radius: 3px 3px 3px 3px;
		margin: 0 auto 1.625em;
		padding: 1.625em;
		position: relative;
		width: auto;
	}
	.commentlist .avatar {
		height: 39px;
		left: 2.2em;
		top: 2.2em;
		width: 39px;
	}
	.commentlist li.comment .comment-meta {
		line-height: 1.625em;
		margin-left: 50px;
	}
	.commentlist li.comment .fn {
		display: block;
	}
	.commentlist li.comment .comment-content {
		margin: 1.625em 0 0;
	}
	.commentlist .comment-edit-link {
		display: none;
	}
	.commentlist > li::before,
	.commentlist > li.bypostauthor::before {
		content: '';
	}
	.commentlist .reply {
		display: none;
	}

	/* Post author highlighting */
	.commentlist > li.bypostauthor {
		color: #444;
	}
	.commentlist > li.bypostauthor .comment-meta {
		color: #666;
	}
	.commentlist > li.bypostauthor:before {
		content: none;
	}

	/* Post Author threaded comments */
	.commentlist .children > li.bypostauthor {
		background: #fff;
		border-color: #ddd;
	}
	.commentlist .children > li.bypostauthor > article,
	.commentlist .children > li.bypostauthor > article .comment-meta {
		color: #666;
	}

}


/* =IE7
----------------------------------------------- */

#ie7 article.intro {
	margin-left: -7.6%;
	margin-right: -7.6%;
	padding-left: -7.6%;
	padding-right: -7.6%;
	max-width: 1024px;
}
#ie7 section.featured-post {
	margin-left: -7.6%;
	margin-right: -7.6%;
	max-width: 850px;
}
#ie7 section.recent-posts {
	margin-right: 7.6%;
}
.innerPagesParent #content{  padding: 0% !important;  width: 100% !important;}
.page-header-search a{  }
.searchWord{ font-weight:normal;}

.page-header-search{ margin-bottom:20px; border-bottom:0px solid #DBDBDB; }
.page-header-search a{ color:#1982D1!important; }
.entryLast{ margin-right:0px!important;}
.errorField{ border:1px solid #FF1746!important; background:#FFE1EA!important; }
.ui-tabs .ui-tabs-nav li.searchForm{padding:15px 0 0 !important;}
.searchForm{ float:right!important; }
.searchForm #s{ background-color:#EFEFEF!important;}
div.searchForm{ margin-top: 10px; position: absolute; right: 0; top: 10px; z-index: 1000;}
.wpcf7-text{ width:96%; padding:10px!important;}
div.wpcf7{ padding:10px!important;}
div.wpcf7-validation-errors{ border:none!important; color:#ff0000!important;}
.wpcf7-textarea{ width:99%; height:220px; resize:none;}
.wpcf7-submit{ background:url("images/v2/submit-form.gif") left top no-repeat; width:94px; height:37px; border:none; padding:0px; line-height:0px; cursor:pointer; text-indent:-9999px; float:right!important;}
.innerPagesParent .entry-content a{ color:#0D63AB!important;}
#tabs .ui-tabs-nav li a{ color:#7F7F7F !important;}
.page-header-search h1{ font-size:22px!important; font-weight:normal!important;}
div.wpcf7-mail-sent-ok {
border: none!important;
color:#548C00!important;
font-weight: bold!important;
}

.singular .singlePage{ border-bottom:none!important; border-top: 1px solid #DBDBDB !important;
    margin-top: 15px!important; padding-top:15px!important;}
.singular .singlePage h1{ font-weight:bold;}
.headerBottom{ position:relative; }
.headerBottom .headerBorder { width:33.33%; float:left; height:1px; background:#DFDEDC; }
.headerBottom .blue{ background:#DFDEDC;  }
.headerBottom .red{background: #DFDEDC; }
.ui-widget-content{background:none!important;}
.entry-content .ui-tabs-panel{ /*background:none!important*/;}
.showcase{ padding:40px 20px; background:url(images/v2/tagline.png) left center no-repeat;  margin-top:5px; width:95%; float:left; margin-bottom:30px; }
.showcase span{ font-weight:bold; }
.showcase span.italics{ font-style:italic; }
.showcase span.submitFree{margin-left:5px;  background:#09AEED; padding:2px 15px; color:#fff; border:1px solid #fff;border-radius:5px;  }
.showcase a, .showcase a:hover{ text-decoration:none;}
.headerRight{ float:right; width:65%;}
.headerRight .headerSearch{ float:right; margin-top:5px; position: absolute; right: 0px; z-index: 999; }
.headerSearch.dontShow form{ display:none;}
.footerSection{ background:#ffffff; border-top:1px solid #ececec;  }
.footerSection .widget-title{ color: #626262; font-size: 18px; text-transform: none; font-weight: normal; margin-bottom: 5px; font-family: Arial, Helvetica, sans-serif !important;}
.footerSection #tags{ width:98%!important; border:1px solid #eaeaea; padding:.8%; margin:0px!important; background:#f8f8f8; }
.footerSection #tags .widget-title{ display:none;}
.footerSection #tags .widget{ margin:0px;}
.footerSection #tags a{ color:#B6B6B6; line-height:24px; }
.homeSocialIcons{ position:absolute; top:60px; right:0px; z-index:100;}
.homeSocialIcons li{ list-style-type:none;}
.homeSocialIcons > li{ margin:0px;}
.homeSocialIcons a{ cursor:pointer; }
.searchTrigger{float: right; height: 36px; width: 36px; border:1px solid #E7E7E7; /* margin-left: 10px; */ background:url(images/search-icon.jpg) center center no-repeat; cursor:pointer;}
.searchTrigger.triggerOpen{ margin-left:0px;}

@media only screen and (max-width: 480px) {
	/* Mobile styles go here */
	.page  #branding hgroup, .category #branding hgroup{ width:100%!important;}
	.page .headerRight, .category .headerRight{ width:100%!important;}
	.entry-content a.viewAllAnchor{ margin-top:0px!important;}
	.entry-content .shoutOuter{ width:100%; height:auto ;padding-bottom:7px;}
	.contentHolder{ width :100%!important; clear:both; margin-top:20%;}
	.showcase{ float:left;}
	.showcase span.submitFree{ float:right;}
	.viewAllLink a{ height:70px!important; }
	.submit-left{ width:100%!important; }
	
	.submit-right{ float:left!important; width:100%!important; }
	.innerHolder h1{ font-size:14px!important;}
	#site-title a{ margin-left:5%;}
	.entry-content img, .comment-content img, .widget img{ width:100%;}
	#main #content{ margin: 0 0.6%; width: 98% !important;}
	.uploadOuter{ height:auto!important;}
	.fileUpload label{ margin-left:0px!important;}
	.uploadHelp, .uploadHelp em{ margin-left:0px!important; word-wrap:break-word; font-size:10px!important;}
	.formError{ left:0px!important;}
	
	
}

@media only screen and (max-width: 640px) {
	/* Mobile styles go here */
	.entry-content .shoutOuter{ width:100%; height:auto; padding-bottom:7px;}
		#site-title a{ margin-left:5%;}
	.entry-content img, .comment-content img, .widget img{ width:100%;}
	#main #content{ margin: 0 0.6%; width: 98% !important;}
		
}

@media only screen and (max-width:768px){
.submitBtn{  width: 100%!important; background-size: 100%!important;}
  .headerRight .headerSearch #s{ margin-bottom:10px;}
  .homeSocialIcons{ display:none!important;}
}

@media only screen and (max-width: 1024px) {
	/* Mobile styles go here */
	#branding hgroup{ width:30%!important;}
	.headerRight{ width:65%!important;}
	#access{width:99%!important;}
	.entry-content .shoutOuter{ width:100%; height:auto; padding-bottom:7px;}
		#site-title a{ margin-left:5%;}
	.entry-content img, .comment-content img, .widget img{ width:100%;}
	#main #content{ margin: 0 0.6%; width: 98% !important;}
	#supplementary, .footerWrapper{ width:100%!important;}
}
#widget_sp_image-2{
	margin-bottom:0px !important;
}
/* 13-09-2014 Logo padding */
.showcase_homen img{
	 padding: 20px 0 0;
}
.resultHead{
	font-weight:normal !important;
}
.three #third .simple-social-icons{
	margin-left:100px;
}
/* 13-09-2014*/

#supplementary .textwidget, #supplementary .textwidget a {color: #7f7f7f; font-weight:normal}
#submitAmount label{ padding-right:20px;}
#submitAmount input{ width:30px; text-align:center;}
#submitAmount .submitButtonDonation{ width:150px;}
