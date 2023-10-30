<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>PRAMOD SUBEDI</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-interactiveBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="88ceff29-a9cf-4714-bd01-25bc1ac34591" class="page sans"><header><h1 class="page-title">PRAMOD SUBEDI</h1><p class="page-description"></p></header><div class="page-body"><div id="548c433f-3ea5-45db-b7c6-6ef65f4feede" class="column-list"><div id="6535e13f-79f0-4cd7-a4e9-436ab34d3d60" style="width:25%" class="column"></div><div id="d73de7fd-6f09-4a5d-884a-fdaf7dab950f" style="width:25%" class="column"></div><div id="9f149b8b-8b35-4d6a-937c-37fc30797c5c" style="width:25%" class="column"></div><div id="863e4359-f527-4e93-869a-71806d0ea3eb" style="width:25%" class="column"></div></div><div id="5c1a3646-a82e-40ef-a651-7f609bfa78f2" class="column-list"><div id="f685096d-b30f-41ef-83a0-103f99ef753a" style="width:50%" class="column"><h1 id="dcd70778-1458-44f8-9554-728dbbf128ff" class="">Hey there! 👋🏻 
I&#x27;m Pramod.</h1><p id="0fa8a930-1bfd-4ae5-ba9d-243cba900cbb" class=""><a href="mailto:subedi019@gmail.com">subedi019@gmail.com</a></p><h3 id="36a8aa9c-0887-4571-868a-15c80339d5a8" class="">Forestry Student </h3><blockquote id="1a2bcb85-a148-4700-a7d8-127dff8eabc9" class="">I’m a passionate and driven forestry student with strong interest in nature and wildlife conservation. Proficient in using research tools like gis to analyze problems related to natural resources and also able to develop creative and engaging posters and materials to promote biodiversity conservation.</blockquote><p id="e0e24cd2-10d9-4692-aa47-5a0d92355aab" class=""><em>“The clearest way into the Universe is through a forest wilderness.”
John Muir</em></p><p id="862d3bee-f440-42b9-8c0c-bac5e590d06b" class="">
</p><div><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="e8e9417c-466f-4788-aba3-844098a9da8f"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/download.jpeg"/></div><div style="width:100%"><a href="https://www.facebook.com/subedi019">Facebook</a></div></figure></div><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="25571642-3abd-458d-a44a-865fbf5311ba"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/LinkedIn.png"/></div><div style="width:100%"><a href="https://www.linkedin.com/in/pramod--subedi/">LinkedIn</a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1d1afcd9-58c8-4ae8-ba3a-40d483b3ad2e"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/download.png"/></div><div style="width:100%"><a href="https://wa.me/9866371854">WhatsApp</a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="39db286c-aa4d-41d6-acde-02b39f13937a"><div style="font-size:1.5em"><span class="icon">💬</span></div><div style="width:100%"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Contact%20db5da81f4abe409aa0aa8c7f40a844bf.html">Let’s chat</a></div></figure></div><div id="3c9b21ef-a87f-4cee-80d8-e2dece3cc66a" style="width:50%" class="column"><p id="504b73c2-f222-4ce0-81d1-deeecfcca2d2" class="">
</p><figure id="3aca7244-062e-4cf0-99db-4a9cb3f6ca5d" class="image"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Removal-210.png"><img style="width:581px" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Removal-210.png"/></a></figure><p id="042b4fe4-7cd8-43a5-8e83-1b089ea3a917" class="">
</p></div></div><hr id="680a3f98-0f91-41b8-ac5d-8ec1cf7a2ee8"/><h2 id="115e50c5-0d3b-45ce-93e4-955e495c8f21" class="">Projects</h2><div id="ae2ecc2e-e487-4470-a363-e741d3a8f123" class="collection-content"><h4 class="collection-title">Projects</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesTitle"><path d="M0.637695 13.1914C1.0957 13.1914 1.32812 13 1.47852 12.5215L2.24414 10.3887H6.14746L6.90625 12.5215C7.05664 13 7.2959 13.1914 7.74707 13.1914C8.22559 13.1914 8.5332 12.9043 8.5332 12.4531C8.5332 12.2891 8.50586 12.1523 8.44434 11.9678L5.41602 3.79199C5.2041 3.21777 4.82129 2.9375 4.19922 2.9375C3.60449 2.9375 3.21484 3.21777 3.0166 3.78516L-0.0322266 12.002C-0.09375 12.1797 -0.121094 12.3232 -0.121094 12.4668C-0.121094 12.918 0.166016 13.1914 0.637695 13.1914ZM2.63379 9.12402L4.17871 4.68066H4.21973L5.76465 9.12402H2.63379ZM12.2793 13.2324C13.3115 13.2324 14.2891 12.6787 14.7129 11.8037H14.7402V12.5762C14.7471 12.9863 15.0273 13.2393 15.4238 13.2393C15.834 13.2393 16.1143 12.9795 16.1143 12.5215V8.00977C16.1143 6.49902 14.9658 5.52148 13.1543 5.52148C11.7666 5.52148 10.6592 6.08887 10.2695 6.99121C10.1943 7.15527 10.1533 7.3125 10.1533 7.46289C10.1533 7.81152 10.4062 8.04395 10.7686 8.04395C11.0215 8.04395 11.2129 7.94824 11.3496 7.73633C11.7529 6.99121 12.2861 6.65625 13.1064 6.65625C14.0977 6.65625 14.6992 7.20996 14.6992 8.1123V8.67285L12.5664 8.7959C10.7686 8.8916 9.77734 9.69824 9.77734 11.0107C9.77734 12.3369 10.8096 13.2324 12.2793 13.2324ZM12.6621 12.1387C11.8008 12.1387 11.2129 11.667 11.2129 10.9561C11.2129 10.2725 11.7598 9.82129 12.7578 9.75977L14.6992 9.62988V10.3203C14.6992 11.3457 13.7969 12.1387 12.6621 12.1387Z"></path></svg></span>Name</th><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesText"><path d="M1.56738 3.25879H14.4258C14.7676 3.25879 15.0479 2.97852 15.0479 2.63672C15.0479 2.29492 14.7744 2.02148 14.4258 2.02148H1.56738C1.21875 2.02148 0.952148 2.29492 0.952148 2.63672C0.952148 2.97852 1.22559 3.25879 1.56738 3.25879ZM1.56738 6.84082H14.4258C14.7676 6.84082 15.0479 6.56055 15.0479 6.21875C15.0479 5.87695 14.7744 5.60352 14.4258 5.60352H1.56738C1.21875 5.60352 0.952148 5.87695 0.952148 6.21875C0.952148 6.56055 1.22559 6.84082 1.56738 6.84082ZM1.56738 10.4229H14.4258C14.7676 10.4229 15.0479 10.1426 15.0479 9.80078C15.0479 9.45898 14.7744 9.18555 14.4258 9.18555H1.56738C1.21875 9.18555 0.952148 9.45898 0.952148 9.80078C0.952148 10.1426 1.22559 10.4229 1.56738 10.4229ZM1.56738 14.0049H8.75879C9.10059 14.0049 9.38086 13.7246 9.38086 13.3828C9.38086 13.041 9.10742 12.7676 8.75879 12.7676H1.56738C1.21875 12.7676 0.952148 13.041 0.952148 13.3828C0.952148 13.7246 1.22559 14.0049 1.56738 14.0049Z"></path></svg></span>Brief Summary</th><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesDate"><path d="M3.29688 14.4561H12.7031C14.1797 14.4561 14.9453 13.6904 14.9453 12.2344V3.91504C14.9453 2.45215 14.1797 1.69336 12.7031 1.69336H3.29688C1.82031 1.69336 1.05469 2.45215 1.05469 3.91504V12.2344C1.05469 13.6973 1.82031 14.4561 3.29688 14.4561ZM3.27637 13.1162C2.70898 13.1162 2.39453 12.8154 2.39453 12.2207V5.9043C2.39453 5.30273 2.70898 5.00879 3.27637 5.00879H12.71C13.2842 5.00879 13.6055 5.30273 13.6055 5.9043V12.2207C13.6055 12.8154 13.2842 13.1162 12.71 13.1162H3.27637ZM6.68066 7.38086H7.08398C7.33008 7.38086 7.41211 7.30566 7.41211 7.05957V6.66309C7.41211 6.41699 7.33008 6.3418 7.08398 6.3418H6.68066C6.44141 6.3418 6.35938 6.41699 6.35938 6.66309V7.05957C6.35938 7.30566 6.44141 7.38086 6.68066 7.38086ZM8.92285 7.38086H9.31934C9.56543 7.38086 9.64746 7.30566 9.64746 7.05957V6.66309C9.64746 6.41699 9.56543 6.3418 9.31934 6.3418H8.92285C8.67676 6.3418 8.59473 6.41699 8.59473 6.66309V7.05957C8.59473 7.30566 8.67676 7.38086 8.92285 7.38086ZM11.1582 7.38086H11.5547C11.8008 7.38086 11.8828 7.30566 11.8828 7.05957V6.66309C11.8828 6.41699 11.8008 6.3418 11.5547 6.3418H11.1582C10.9121 6.3418 10.8301 6.41699 10.8301 6.66309V7.05957C10.8301 7.30566 10.9121 7.38086 11.1582 7.38086ZM4.44531 9.58203H4.84863C5.09473 9.58203 5.17676 9.50684 5.17676 9.26074V8.86426C5.17676 8.61816 5.09473 8.54297 4.84863 8.54297H4.44531C4.20605 8.54297 4.12402 8.61816 4.12402 8.86426V9.26074C4.12402 9.50684 4.20605 9.58203 4.44531 9.58203ZM6.68066 9.58203H7.08398C7.33008 9.58203 7.41211 9.50684 7.41211 9.26074V8.86426C7.41211 8.61816 7.33008 8.54297 7.08398 8.54297H6.68066C6.44141 8.54297 6.35938 8.61816 6.35938 8.86426V9.26074C6.35938 9.50684 6.44141 9.58203 6.68066 9.58203ZM8.92285 9.58203H9.31934C9.56543 9.58203 9.64746 9.50684 9.64746 9.26074V8.86426C9.64746 8.61816 9.56543 8.54297 9.31934 8.54297H8.92285C8.67676 8.54297 8.59473 8.61816 8.59473 8.86426V9.26074C8.59473 9.50684 8.67676 9.58203 8.92285 9.58203ZM11.1582 9.58203H11.5547C11.8008 9.58203 11.8828 9.50684 11.8828 9.26074V8.86426C11.8828 8.61816 11.8008 8.54297 11.5547 8.54297H11.1582C10.9121 8.54297 10.8301 8.61816 10.8301 8.86426V9.26074C10.8301 9.50684 10.9121 9.58203 11.1582 9.58203ZM4.44531 11.7832H4.84863C5.09473 11.7832 5.17676 11.708 5.17676 11.4619V11.0654C5.17676 10.8193 5.09473 10.7441 4.84863 10.7441H4.44531C4.20605 10.7441 4.12402 10.8193 4.12402 11.0654V11.4619C4.12402 11.708 4.20605 11.7832 4.44531 11.7832ZM6.68066 11.7832H7.08398C7.33008 11.7832 7.41211 11.708 7.41211 11.4619V11.0654C7.41211 10.8193 7.33008 10.7441 7.08398 10.7441H6.68066C6.44141 10.7441 6.35938 10.8193 6.35938 11.0654V11.4619C6.35938 11.708 6.44141 11.7832 6.68066 11.7832ZM8.92285 11.7832H9.31934C9.56543 11.7832 9.64746 11.708 9.64746 11.4619V11.0654C9.64746 10.8193 9.56543 10.7441 9.31934 10.7441H8.92285C8.67676 10.7441 8.59473 10.8193 8.59473 11.0654V11.4619C8.59473 11.708 8.67676 11.7832 8.92285 11.7832Z"></path></svg></span>Created</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/rocket_gray.svg" style="width:14px;height:14px"/></span>Project</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/stars_gray.svg" style="width:14px;height:14px"/></span>Service</th><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesSelect"><path d="M8 15.126C11.8623 15.126 15.0615 11.9336 15.0615 8.06445C15.0615 4.20215 11.8623 1.00293 7.99316 1.00293C4.13086 1.00293 0.938477 4.20215 0.938477 8.06445C0.938477 11.9336 4.1377 15.126 8 15.126ZM8 13.7383C4.85547 13.7383 2.33301 11.209 2.33301 8.06445C2.33301 4.91992 4.84863 2.39746 7.99316 2.39746C11.1377 2.39746 13.6738 4.91992 13.6738 8.06445C13.6738 11.209 11.1445 13.7383 8 13.7383ZM7.62402 10.6348C7.79492 10.915 8.20508 10.9287 8.37598 10.6348L10.666 6.73145C10.8574 6.41016 10.7002 6.04102 10.3652 6.04102H5.62793C5.29297 6.04102 5.14941 6.43066 5.32031 6.73145L7.62402 10.6348Z"></path></svg></span>Tag</th></tr></thead><tbody><tr id="81bce759-f357-4b71-ae34-d43a78c93187"><td class="cell-title"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Projects%20ae2ecc2ee4874470a363e741d3a8f123/Research%2081bce759f3574b71ae34d43a78c93187.html">Research</a></td><td class="cell-fOK|">We as forestry science students, conducted a study on floral diversity of Bakaiya Rural Municipality of Makawanpur district. With the support of the rural municipality, we handed over the book titled &quot;Important Medicinal Plant and Tree species of Bakaiya Rural Municipality&quot; to the Chairperson and Chief Administrative Officer of the rural municipality on May 19, 2023. This book includes various plant species, trees, their distribution, significance, and the measures required for their conservation in Bakaiya Rural Municipality.</td><td class="cell-o@TZ"><time>@November 23, 2022</time></td><td class="cell-HXh&gt;">Assessment of floral diversity of Bakaiya Rural Municipality</td><td class="cell-lDgk"><span class="selected-value select-value-color-default">Environmental service</span></td><td class="cell-Bell"><span class="selected-value select-value-color-green">Featured</span></td></tr></tbody></table><br/><br/></div><p id="5cb7a31b-44aa-4d13-b445-7846cc6e81a7" class="">
</p><hr id="b2e8e89c-02b4-4652-b7c3-b9c98281f579"/><h2 id="0ffb52ff-affe-496c-922c-4a5ccad62c0d" class="">Experience</h2><blockquote id="ff88a340-2581-4ad3-b00b-e22c855e819a" class="">Volunteer<strong> | Small Mammals Conservation and Research Foundation (SMCRF)</strong><em><em><em><em><em><em><em><em><em><em><em><em><em><em><em>
September</em></em></em></em></em></em></em></em></em></em></em></em></em></em></em> 2023 - Present<p id="c2e107f2-0eb8-4575-a18a-a99429bc47af" class="">As a volunteer and intern, i am responsible for community outreach program and conducting school awareness programs.</p></blockquote><blockquote id="be6959c3-2708-4962-9dbd-56f3f46f23a3" class=""><strong>Senior Designer | NYCA Udayapur</strong><em><em><em><em><em><em><em><em><em><em><em><em><em><em><em>
January</em></em></em></em></em></em></em></em></em></em></em></em></em></em></em> 2023 - Present<p id="6afdbee6-b0e5-48b3-bb1d-67002c7f711a" class="">As a Design Lead at NYCA Udayapur, I led the design team in the creation of visually captivating experiences.</p></blockquote><blockquote id="1c3948d4-f03d-42bf-98f9-802bd4be1dfd" class=""><strong>Design Lead | BCN Katari</strong><em><em><em><em><em><em><em><em><em><em><em><em><em><em><em>
January</em></em></em></em></em></em></em></em></em></em></em></em></em></em></em> 2023 - Present<p id="9775beb6-cd4d-499a-9745-ece43a6ac51f" class="">As a Senior Designer at BCN Katari, I managed all design projects for the company. I was responsible for developing and implementing design strategies, creating visual assets for conservation campaigns, and ensuring that all design work met the highest standards of quality.</p></blockquote><hr id="a0767641-4fb7-421f-8b92-ae61c1d0dc6c"/><hr id="6f014551-6522-4736-8ed2-4b33d7245eee"/><div id="6398fc1b-4488-4f97-9da7-22adf876815d" class="column-list"><div id="3f508511-d98f-451d-abbb-0ba2f2eea58a" style="width:13.793103448275868%" class="column"><figure id="9e1c6a2d-ebf8-4db0-9206-0e5be7e79d9e" class="image"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Removal-210%201.png"><img style="width:581px" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Removal-210%201.png"/></a></figure></div><div id="b641680a-1164-4c89-9e8a-45ca86fc8109" style="width:58.620689655172434%" class="column"><p id="da38d1b3-a56b-498e-aae4-b4bc82e923d7" class="">I have a passion for birds!!</p><hr id="7b147c46-3238-4158-9b3c-064bf95ce225"/><figure id="9a3e5333-427c-48c7-8800-de3333c2d883" class="link-to-page"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/About%209a3e5333427c48c78800de3333c2d883.html"><img class="icon" src="https://www.notion.so/icons/circle-dot_lightgray.svg"/>About</a></figure><figure id="bc1811c9-9cab-416b-9bbd-66a80a473abf" class="link-to-page"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Projects%20bc1811c99cab416b9bbd66a80a473abf.html"><img class="icon" src="https://www.notion.so/icons/circle-dot_lightgray.svg"/>Projects</a></figure><figure id="db5da81f-4abe-409a-a0aa-8c7f40a844bf" class="link-to-page"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Contact%20db5da81f4abe409aa0aa8c7f40a844bf.html"><img class="icon" src="https://www.notion.so/icons/circle-dot_lightgray.svg"/>Contact</a></figure><p id="75e4ba71-63d2-4c3e-947d-d61edb805696" class="">
</p></div><div id="ddbef380-0a2d-41a4-bec0-b0cbe7aa3334" style="width:27.586206896551737%" class="column"><div><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="e8e9417c-466f-4788-aba3-844098a9da8f"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/download.jpeg"/></div><div style="width:100%"><a href="https://www.facebook.com/subedi019">Facebook</a></div></figure></div><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="2a0c765c-42bd-4c4a-aecf-ee8b6812bbbd"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/LinkedIn.png"/></div><div style="width:100%"><a href="https://www.linkedin.com/in/pramod--subedi/">LinkedIn</a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="2407ec45-b977-4550-b8fe-045174eb72ab"><div style="font-size:1.5em"><img class="icon" src="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/download%201.png"/></div><div style="width:100%"><a href="https://wa.me/9866371854">WhatsApp</a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="23ebfe57-28de-46c1-9754-ef85605a22cd"><div style="font-size:1.5em"><span class="icon">💬</span></div><div style="width:100%"><a href="PRAMOD%20SUBEDI%2088ceff29a9cf4714bd0125bc1ac34591/Contact%20db5da81f4abe409aa0aa8c7f40a844bf.html">Let’s chat</a></div></figure></div></div><hr id="0002bd51-f564-4a3a-8438-e170f9f4169b"/><p id="8b8d7d66-ee0e-4f41-9a58-c9d78864d938" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
