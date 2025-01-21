:root {
	--blue-gradient: linear-gradient(to bottom, #245edb 0%, #3f8cf3 9%, #245edb 18%, #245edb 92%, #333 100%) center/cover no-repeat;
}

body {
	background-image: url('https://s3.amazonaws.com//depot.pacdudegames.com/spacehey/bliss.jpg');
	background-size: cover;
	background-position: center;
	background-attachment: fixed;
}
body:before {
	content: " ";
	height: 100vh;
	width: 100vw;
	display: block;
	position: fixed;
	top: 0;
	left: 0;
	z-index: 100;
	background-image: url('https://media.giphy.com/media/LbSdXQbS0XVVC/giphy.gif');
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center center;
	animation: yourAnimation 3s ease 0s 1 normal forwards;
	pointer-events: none;
}
@keyframes yourAnimation { 0.0% { opacity: 1; } 75% { opacity: 1; } 100% { opacity: 0; } }
nav, footer {
	margin: 1em;
	position: relative;
	box-shadow: 5px 8px 10px #0006;
}
footer{
	margin-bottom:3rem;
	border:2px solid #1D43D1;
}
nav .top, nav .links {
	border-left: 2px solid #1D43D1;
	border-right: 2px solid #1D43D1;
}
nav .info{
	border-left: 2px solid #1D43D1;
	border-right: 2px solid #1D43D1;
}
nav .links {
	border-bottom: 2px solid #1D43D1;
}
nav:before {
	content: "SpaceHey Header";
	display: block;
	padding: 1em;
	background: linear-gradient(to bottom, #245edb 0%, #3f8cf3 9%, #245edb 18%, #245edb 92%, #333 100%) center/cover no-repeat;
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
	font-size: 1em;
	text-shadow: 2px 2px 0px #000;
	border-radius: 10px 10px 0 0;
}
nav:after {
	content: "X";
	display: inline-block;
	padding: .4em .6em;
	width: fit-content;
	border-radius: 5px;
	background: linear-gradient(180deg, rgba(233,145,126,1) 0%, rgba(223,89,65,1) 29%, rgba(156,32,15,1) 100%);
	border: 1px solid #FFF;
	position: absolute;
	top: 0;
	right: 0;
	margin-top: .5em;
	margin-right: .5em;
	pointer-events: none;
}
main:before {
	content: url('https://media.giphy.com/media/w3AmrG1E1vr56/giphy.gif');
	position: fixed;
	bottom: 0;
	right: 0;
	transform: translateX(-3vw) translateY(-6vh);
	pointer-events: none;
}
main {
	background: none;
	position: relative;
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
}
.profile h1 {
	border: 2px solid #1B44B8;
	border-radius: 5px 5px 0 0;
	padding: .5em;
	color: #FFF;
	text-shadow: 2px 2px 0 #000;
	background: var(--blue-gradient);
	margin-bottom: 0;
}
.profile .left {
	display: flex;
	flex-direction: column;
	width: 100%;
}
.profile .general-about {
	background: #FFF;
	border-left: 2px solid #1B44B8;
	border-right: 2px solid #1B44B8;
	border-bottom: 2px solid #1B44B8;
	padding: 1em;
	box-shadow: 5px 8px 10px #0006;
}
.general-about .profile-pic {
	margin: 0 1em 0 0;
}
.profile .left .mood {
	margin-top: 1em;
	background: #FFF;
	border-radius: 11px 11px 0 0;
	box-shadow: 5px 8px 10px #0006;
	border-left: 2px solid #1B44B8;
	border-right: 2px solid #1B44B8;
	border-bottom: 2px solid #1B44B8;
}
.profile .left .mood p {
	margin-left: 1em;
	margin-top: 1em;
}
.profile .left .mood:before {
	-moz-background-clip: padding;
	-webkit-background-clip: padding-box;
	background-clip: padding-box;
	content: "ðŸ™‚ Mood";
	display: block;
	padding: .5em;
	border: 2px solid #1B44B8;
	background: var(--blue-gradient);
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
	font-size: 1em;
	text-shadow: 2px 2px 0px #000;
	border-radius: 10px 10px 0 0;
	color: #FFF;
}
nav:after {
	content: "X";
	display: inline-block;
	padding: .4em .6em;
	width: fit-content;
	border-radius: 5px;
	background: linear-gradient(180deg, rgba(233,145,126,1) 0%, rgba(223,89,65,1) 29%, rgba(156,32,15,1) 100%);
	border: 1px solid #FFF;
	position: absolute;
	top: 0;
	right: 0;
	margin-top: .5em;
	margin-right: .5em;
}
.left .contact {
	position: fixed;
	bottom: 0;
	left: 0;
	width: 100%;
	margin: 0;
	padding: 0;
	z-index: 10;
}
.left .contact {
	border: 0;
	background: linear-gradient(180deg, #0997ff, #0053ee 8%, #0050ee 40%, #06f 88%, #06f 93%, #005bff 95%, #003dd7 96%, #003dd7);
}
.profile .contact .heading {
	background: radial-gradient(circle, #5eac56 0%, #3c873c 100%) center/cover no-repeat;
	display: flex;
	border-radius: 0 40px 50px 0;
	align-items: center;
	-webkit-filter: drop-shadow(0px 0px 7px #000);
	box-shadow: -2px -2px 10px rgba(0,0,0,.25) inset, 2px 2px 10px rgba(0,0,0,0.5) inset;
	margin-right: .5em;
}
.profile .contact .heading h4 {
	font-size: 0;
}
.profile .contact .heading h4:after {
	content: "ðŸ’¬ start";
	font-size: 1.4rem;
	font-family: sans-serif;
	font-weight: bold;
	font-style: italic;
	text-shadow: 2px 2px 5px #0007;
	padding-right: 1.2rem;
	white-space: nowrap;
}
.profile .contact .inner {
	overflow-y: scroll;
}
.profile .contact .inner, .profile .contact .inner .f-row, .profile .contact .inner .f-row .f-col {
	display: flex;
	margin: 0;
	align-items: center;
}
.profile .f-col a {
	white-space: nowrap;
	border: 1px solid #003c74;
	background: linear-gradient(180deg,#366EF3,#2D69F4 86%,#1A3EB4);
	border-radius: 3px;
	padding: .5em;
	margin-left: .3em;
	font-weight: normal;
	color: #FFF;
}
.profile .f-col a:hover {
	background: linear-gradient(180deg,#1C35B4,#2450D7 86%,#1A3EB4);
	text-decoration: none;
}
.profile .url-info, .profile .profile-info {
	background-color: #E7E5CF;
	border: 0;
	box-shadow: 2px 2px 0px #FFFFFF inset, -2px -2px 0px #5D5C51 inset, 5px 8px 10px #0006;
	padding: 10px;
}
.profile .url-info p {
	text-align: center;
}
.left .table-section {
	border-radius: 10px 10px 0 0;
	border: 2px solid #1B44B8;
	box-shadow: 5px 8px 10px #0006;
}
.left .table-section .details-table tr {
	display: flex;
	flex-direction: column;
}
.left .table-section .heading {
	-moz-background-clip: padding;
	-webkit-background-clip: padding-box;
	background-clip: padding-box;
	padding: 1em;
	background: var(--blue-gradient);
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
	font-size: 1em;
	text-shadow: 2px 2px 0px #000;
	border-radius: 10px 10px 0 0;
	color: #FFF;
}
.left .table-section .inner, .left .table-section .details-table td, .left .table-section .details-table td:first-child {
	width: 100%;
	background: #E7E4CF;
}
.left .table-section .details-table td:first-child p {
	padding: .3em .3em 1em .3em;
	border-bottom: 2px ridge #E7E4CF;
}
.left .table-section .details-table td p {
	padding: .3em;
	line-height: initial;
}
.profile .left .table-section:last-child .details-table tbody {
	display: flex;
	flex-direction:column;
}
.profile .left .table-section:last-child .details-table tbody tr {
	display: flex;
	flex-direction: column;
	flex: 1;
	line-height: 0;
}
.profile .left .table-section:last-child .details-table tbody tr td {
	width: 100%!important;
	text-align: left;
	background: none;
}
.profile .left .table-section:last-child .details-table tbody tr td p a {
	font-size: 0;
	transition: all .3s
}
.profile .left .table-section:last-child .details-table tbody tr td p img {
	font-size: 64px;
	height: auto;
	margin: 0;
}

.profile .right .blog-preview {
	margin-top: 1em;
	background: #FFF;
	border-radius: 11px 11px 0 0;
	box-shadow: 5px 8px 10px #0006;
	border-left: 3px solid #1B44B8;
	border-right: 2px solid #1B44B8;
	border-bottom: 2px solid #1B44B8;
}
.profile .right .blog-preview p, .profile .right .blog-preview h4 {
	font-family: "Lucida Console", "Lucida Sans Typewriter", monaco, "Bitstream Vera Sans Mono", monospace;
	margin-left: 1em;
	margin-top: 1em;
}
.profile .right .blog-preview:before {
	-moz-background-clip: padding;
	-webkit-background-clip: padding-box;
	background-clip: padding-box;
	content: "ðŸ“ Notepad";
	display: block;
	padding: .5em;
	border: 2px solid #1B44B8;
	background: var(--blue-gradient);
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
	font-size: 1em;
	text-shadow: 2px 2px 0px #000;
	border-radius: 10px 10px 0 0;
	color: #FFF;
}
.profile .right .blurbs, .profile .right .friends{
	margin-top: 1em;
	background: #FFF;
	border-radius: 11px 11px 0 0;
	box-shadow: 5px 8px 10px #0006;
	border-left: 3px solid #1B44B8;
	border-right: 2px solid #1B44B8;
	border-bottom: 2px solid #1B44B8;
}
.profile .right .blurbs .heading, .profile .right .friends .heading{
	-moz-background-attachment-clip: padding;
	-webkit-background-clip: padding-box;
	background-clip: padding-box;
	display: block;
	padding: .7em;
	border: 2px solid #1B44B8;
	background: var(--blue-gradient);
	font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
	font-size: 1em;
	text-shadow: 2px 2px 0px #000;
	border-radius: 10px 10px 0 0;
	color: #FFF;
}
.profile .right .blurbs .heading h4:before{
	content: "ðŸ’» ";
}
.profile .right .comments-table{
	height:300px;
	overflow-y:scroll;
	display:block;
	background-color:#E7E4CF;
}
.comments-table td{
	background:#FFFFFF;
}
.profile .right .comments-table td:first-child{
	background:#F8F6F0;
	border-right:1px solid #BEBBAA;
	border-bottom:1px solid #BEBBAA;
}
.comment-replies{
	border: 0;
	border-left: 5px solid #ffbd2e;
}
