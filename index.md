<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><style>
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
	text-indent: -1.7em;
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
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

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
	
</style></head><body><article id="c08c1719-3a23-4658-99d2-ea6db784dcae" class="page sans"><header><div class="page-header-icon undefined"><span class="icon">📚</span></div><h1 class="page-title">Biblioteca</h1></header><div class="page-body"><figure id="10a6e01a-4a55-4666-b873-6e57beab4fd4" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Appunti%20Christian%2010a6e01a4a554666b8736e57beab4fd4.html"><span class="icon">🫀</span>Appunti Christian</a></figure><p id="3f912ea8-a9fd-4ba1-afac-fe3b9a426a4f" class="">
</p><p id="ff82a866-a849-4bba-8ea9-a9e343a14b43" class=""><a href="https://kinsta.com/knowledgebase/sorry-this-file-type-is-not-permitted-for-security-reasons/">https://kinsta.com/knowledgebase/sorry-this-file-type-is-not-permitted-for-security-reasons/</a></p><div id="cd2eae02-805d-4edb-8cbb-25a1b739706a" class="column-list"><div id="5de51f90-7ae4-4c6a-808a-1b7be5ff8565" style="width:31.25%" class="column"><h1 id="7eb2d4a7-2d2f-482b-87dc-c086d6aef632" class="">Imprenditoria e burocrazia</h1><figure id="84ca4828-c398-459b-95d4-f157ad156c0e" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Macro%20economia%2084ca4828c398459b95d4f157ad156c0e.html"><span class="icon">📈</span>Macro economia</a></figure><figure id="20e62721-924f-4fa0-835c-d9f53c441681" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Costi%20burocratici%20per%20una%20srl%2020e62721924f4fa0835cd9f53c441681.html"><span class="icon">🕠</span>Costi burocratici per una srl</a></figure><figure id="3eae0ae8-6179-4901-a714-d2f0928b7856" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Fiscalita%CC%80%20generale%203eae0ae861794901a714d2f0928b7856.html"><span class="icon">💳</span>Fiscalità generale</a></figure><figure id="f9ab976a-0bb4-4303-a6ed-d613324ddc32" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Tutela%20legale%20digitale%20f9ab976a0bb44303a6edd613324ddc32.html"><span class="icon">💼</span>Tutela legale digitale</a></figure><figure id="d178c589-8eed-4f5c-a2a9-a6c7fa609c1d" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Appunti%20tecnici%20d178c5898eed4f5ca2a9a6c7fa609c1d.html"><span class="icon">📈</span>Appunti tecnici</a></figure><p id="283954ef-fcd6-4145-9f7d-42ff05ae6a1f" class="">
</p><figure id="c84fc170-9567-4fcb-82f2-921af12809d0" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Siti%20per%20gli%20imprenditori%20c84fc17095674fcb82f2921af12809d0.html"><span class="icon">🌐</span>Siti per gli imprenditori</a></figure></div><div id="99462fa6-b047-4fae-b4be-523a1047ca1e" style="width:25%" class="column"><h1 id="54650cd1-fc5e-47e2-8749-627a1b93534a" class="">Coding </h1><figure id="78320310-e1a4-424b-93ec-e591028c9951" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/CSS%2078320310e1a4424b93ece591028c9951.html"><img class="icon" src="Biblioteca%20c08c17193a23465899d2ea6db784dcae/CSS%2078320310e1a4424b93ece591028c9951/732190.png"/>CSS</a></figure><figure id="5fec0cfe-6bb0-4b33-a4c2-f4ee6a3795ee" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Bootstrap%205fec0cfe6bb04b33a4c2f4ee6a3795ee.html"><img class="icon" src="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Bootstrap%205fec0cfe6bb04b33a4c2f4ee6a3795ee/bootstrap-logo.png"/>Bootstrap</a></figure><figure id="9ccd5386-6553-4ac9-9671-b31a20e206a3" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Javascript%209ccd538665534ac99671b31a20e206a3.html"><img class="icon" src="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Javascript%209ccd538665534ac99671b31a20e206a3/Js.png"/>Javascript</a></figure><figure id="d0543851-8753-4afe-8eab-e4d900b4a65c" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/11ty%20e%20NJK%20d054385187534afe8eabe4d900b4a65c.html"><span class="icon">🅾️</span>11ty e NJK</a></figure><figure id="e260214b-d992-4d76-8189-3b7d7d6de28f" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Elementor%20e260214bd9924d7681893b7d7d6de28f.html"><span class="icon">🎱</span>Elementor</a></figure><figure id="b3ac17b8-4839-445f-be2f-c6c8319af215" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Flutter%20b3ac17b84839445fbe2fc6c8319af215.html"><span class="icon">❤️‍🔥</span>Flutter</a></figure><figure id="8be73c17-9df9-4d33-a7df-03184acac831" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Indicizzazione%208be73c179df94d33a7df03184acac831.html"><span class="icon">🚪</span>Indicizzazione</a></figure><figure id="6e4c946e-f955-4e56-ba7c-0fb81214fd19" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Prestashop%206e4c946ef9554e56ba7c0fb81214fd19.html"><span class="icon">🐧</span>Prestashop</a></figure><figure id="049ff20c-3865-4631-9f1e-504b073b2300" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Wordpress%20049ff20c386546319f1e504b073b2300.html"><span class="icon">💺</span>Wordpress</a></figure><figure id="55499e21-d41e-42b5-b3fa-c6f4bac6ab00" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Ottimizzazione%2055499e21d41e42b5b3fac6f4bac6ab00.html"><span class="icon">🖱️</span>Ottimizzazione</a></figure><figure id="81578dfa-1755-4fa1-8030-1e7baa909fe2" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Node%20js%2081578dfa17554fa180301e7baa909fe2.html"><span class="icon">🥌</span>Node.js</a></figure><figure id="da334a88-f034-4d78-b66d-3e2595f7b072" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Tecnologie%20da334a88f0344d78b66d3e2595f7b072.html">Tecnologie</a></figure><figure id="5999969c-e552-45c2-a3c1-9c11b612be72" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Infrastruttura%20di%20rete%205999969ce55245c2a3c19c11b612be72.html">Infrastruttura di rete</a></figure></div><div id="f4775dc8-6308-4e37-b4d9-31023e353d49" style="width:21.875%" class="column"><h1 id="d4ad9a21-2f54-4f5e-81e6-510a7e30be4f" class="">Social</h1><figure id="f6998496-15a5-4cd0-844c-da021b23e1f1" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/LinkedIn%20f699849615a54cd0844cda021b23e1f1.html"><span class="icon">🫂</span>LinkedIn</a></figure><figure id="f83bf735-6655-47a2-8897-9cc7b1df9faa" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/TikTok%20e%20Reel%20f83bf735665547a288979cc7b1df9faa.html"><span class="icon">🎥</span>TikTok e Reel</a></figure><figure id="a99dacea-82f9-4093-bf46-6980e8dee434" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Premiere%20a99dacea82f94093bf466980e8dee434.html"><span class="icon">📹</span>Premiere</a></figure><figure id="84945732-7a4a-42cd-be24-0a5d22ad4a2d" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Google%20Analytics%20-%20I%20problemi%20del%20GDPR%20849457327a4a42cdbe240a5d22ad4a2d.html"><span class="icon">📢</span>Google Analytics - I problemi del GDPR</a></figure><p id="13eaa3d9-4256-49de-9003-86d53f278b4c" class="">
</p></div><div id="94325c3c-f01c-43bd-816b-f6ffa6c9cadf" style="width:21.875%" class="column"><h1 id="455d3227-5941-4068-90b7-b78928bc0981" class="">Comunicazione</h1><figure id="7edcc772-d7cc-4a97-bfc0-7ff4143eb5c2" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Comunicazione%207edcc772d7cc4a97bfc07ff4143eb5c2.html"><span class="icon">🗣️</span>Comunicazione</a></figure><figure id="e29d4be7-cc45-447f-9ead-c34fda0b009b" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Marketing%20e29d4be7cc45447f9eadc34fda0b009b.html"><span class="icon">🔛</span>Marketing</a></figure><figure id="470ca835-9da7-47f4-9924-55c29a1779d6" class="link-to-page"><a href="Biblioteca%20c08c17193a23465899d2ea6db784dcae/Podcasts%20470ca8359da747f4992455c29a1779d6.html"><span class="icon">🎙️</span>Podcasts</a></figure><p id="5df14633-5f8c-4a60-9bdd-6076a1107f77" class="">
</p></div></div><p id="bfece4bc-b71e-4cf9-ab7e-6df431c73c14" class="">
</p></div></article></body></html>
