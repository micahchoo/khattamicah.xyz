
<!doctype html>
<!-- The following comment is called a MOTW comment and is necessary for the TiddlyIE Internet Explorer extension -->
<!-- saved from url=(0021)https://tiddlywiki.com -->
<html lang="en-GB">
<head>
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<!--~~ Raw markup for the top of the head section ~~-->

<meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
<meta name="application-name" content="TiddlyWiki" />
<meta name="generator" content="TiddlyWiki" />
<meta name="tiddlywiki-version" content="5.2.5" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
<meta name="mobile-web-app-capable" content="yes"/>
<meta name="format-detection" content="telephone=no" />
<meta name="copyright" content="TiddlyWiki created by Jeremy Ruston, (jeremy [at] jermolene [dot] com)

Copyright (c) 2004-2007, Jeremy Ruston
Copyright (c) 2007-2022, UnaMesa Association
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS 'AS IS'
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE." />
<link id="faviconLink" rel="shortcut icon" href="favicon.ico">
<title>TiddlyWiki — a non-linear personal web notebook</title>
<!--~~ This is a Tiddlywiki file. The points of interest in the file are marked with this pattern ~~-->

<!--~~ Raw markup ~~-->



</head>
<body class="tc-body">
<!--~~ Raw markup for the top of the body section ~~-->

<!--~~ Static styles ~~-->
<div id="styleArea">
<style data-tiddler-title="$:/boot/boot.css" data-tiddler-type="text/css" type="text/css">/*
Basic styles used before we boot up the parsing engine
*/

/*
Error message and password prompt
*/

.tc-error-form {
	font-family: sans-serif;
	color: #fff;
	z-index: 20000;
	position: fixed;
	background-color: rgb(255, 75, 75);
	border: 8px solid rgb(255, 0, 0);
	border-radius: 8px;
	width: 50%;
	margin-left: 25%;
	margin-top: 4em;
	padding: 0 2em 1em 2em;
}

.tc-error-form h1 {
	text-align: center;
}

.tc-error-prompt {
	text-align: center;
	color: #000;
}

.tc-error-message {
	overflow: auto;
	max-height: 40em;
	padding-right: 1em;
	margin: 1em 0;
	white-space: pre-line;
}

.tc-password-wrapper {
    font-family: sans-serif;
	z-index: 20000;
	position: fixed;
	text-align: center;
	width: 200px;
	top: 4em;
	left: 50%;
	margin-left: -144px; /* - width/2 - paddingHorz/2 - border */
	padding: 16px 16px 16px 16px;
	border-radius: 8px;
}

.tc-password-wrapper {
	color: #000;
	text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
	background-color: rgb(197, 235, 183);
	border: 8px solid rgb(164, 197, 152);
}

.tc-password-wrapper form {
	text-align: left;
}

.tc-password-wrapper h1 {
	font-size: 16px;
	line-height: 20px;
	padding-bottom: 16px;
}

.tc-password-wrapper input {
	width: 100%;
}
</style>
</div>
<!--~~ Static content for Google and browsers without JavaScript ~~-->
<noscript>
<div id="splashArea">


<div class=" tc-reveal" hidden="true"></div>



<style>
.tc-remove-when-wiki-loaded {display: none;}
</style>

</div>
</noscript>
<!--~~ Ordinary tiddlers ~~-->
<script class="tiddlywiki-tiddler-store" type="application/json">[
{"title":"$:/isEncrypted","text":"no"},
{"title":"$:/themes/tiddlywiki/snowwhite","name":"Snow White","author":"JeremyRuston","core-version":">=5.0.0","plugin-type":"theme","description":"Emphasises individual tiddlers","dependents":"$:/themes/tiddlywiki/vanilla","plugin-priority":"0","version":"5.2.5","type":"application/json","text":"{\"tiddlers\":{\"$:/themes/tiddlywiki/snowwhite/base\":{\"title\":\"$:/themes/tiddlywiki/snowwhite/base\",\"tags\":\"[[$:/tags/Stylesheet]]\",\"text\":\"\\\\define sidebarbreakpoint-minus-one()\\n\u003C$text text={{{ [{$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint}removesuffix[px]subtract[1]addsuffix[px]] ~[{$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint}] }}}/>\\n\\\\end\\n\\n\\\\rules only filteredtranscludeinline transcludeinline macrodef macrocallinline\\n\\n.tc-sidebar-header {\\n\\ttext-shadow: 0 1px 0 \u003C\u003Ccolour sidebar-foreground-shadow>>;\\n}\\n\\n.tc-tiddler-info {\\n\\t\u003C\u003Cbox-shadow \\\"inset 1px 2px 3px rgba(0,0,0,0.1)\\\">>\\n}\\n\\n@media screen {\\n\\t.tc-tiddler-frame {\\n\\t\\t\u003C\u003Cbox-shadow \\\"1px 1px 5px rgba(0, 0, 0, 0.3)\\\">>\\n\\t}\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\t.tc-tiddler-frame {\\n\\t\\t\u003C\u003Cbox-shadow none>>\\n\\t}\\n}\\n\\n.tc-page-controls button svg, .tc-tiddler-controls button svg, .tc-topbar button svg {\\n\\t\u003C\u003Ctransition \\\"fill 150ms ease-in-out\\\">>\\n}\\n\\n.tc-tiddler-controls button.tc-selected,\\n.tc-page-controls button.tc-selected {\\n\\t\u003C\u003Cfilter \\\"drop-shadow(0px -1px 2px rgba(0,0,0,0.25))\\\">>\\n}\\n\\n.tc-tiddler-frame input.tc-edit-texteditor,\\n.tc-tiddler-frame select.tc-edit-texteditor {\\n\\t\u003C\u003Cbox-shadow \\\"inset 0 1px 8px rgba(0, 0, 0, 0.15)\\\">>\\n}\\n\\n.tc-edit-tags {\\n\\t\u003C\u003Cbox-shadow \\\"inset 0 1px 8px rgba(0, 0, 0, 0.15)\\\">>\\n}\\n\\n.tc-tiddler-frame .tc-edit-tags input.tc-edit-texteditor {\\n\\t\u003C\u003Cbox-shadow \\\"none\\\">>\\n\\tborder: none;\\n\\toutline: none;\\n}\\n\\ntextarea.tc-edit-texteditor {\\n\\tfont-family: {{$:/themes/tiddlywiki/vanilla/settings/editorfontfamily}};\\n}\\n\\ncanvas.tc-edit-bitmapeditor  {\\n\\t\u003C\u003Cbox-shadow \\\"2px 2px 5px rgba(0, 0, 0, 0.5)\\\">>\\n}\\n\\n.tc-drop-down {\\n\\tborder-radius: 4px;\\n\\t\u003C\u003Cbox-shadow \\\"2px 2px 10px rgba(0, 0, 0, 0.5)\\\">>\\n}\\n\\n.tc-block-dropdown {\\n\\tborder-radius: 4px;\\n\\t\u003C\u003Cbox-shadow \\\"2px 2px 10px rgba(0, 0, 0, 0.5)\\\">>\\n}\\n\\n.tc-modal {\\n\\tborder-radius: 6px;\\n\\t\u003C\u003Cbox-shadow \\\"0 3px 7px rgba(0,0,0,0.3)\\\">>\\n}\\n\\n.tc-modal-footer {\\n\\tborder-radius: 0 0 6px 6px;\\n\\t\u003C\u003Cbox-shadow \\\"inset 0 1px 0 #fff\\\">>;\\n}\\n\\n\\n.tc-alert {\\n\\tborder-radius: 6px;\\n\\t\u003C\u003Cbox-shadow \\\"0 3px 7px rgba(0,0,0,0.6)\\\">>\\n}\\n\\n.tc-notification {\\n\\tborder-radius: 6px;\\n\\t\u003C\u003Cbox-shadow \\\"0 3px 7px rgba(0,0,0,0.3)\\\">>\\n\\ttext-shadow: 0 1px 0 rgba(255,255,255, 0.8);\\n}\\n\\n.tc-sidebar-lists .tc-tab-set .tc-tab-divider {\\n\\tborder-top: none;\\n\\theight: 1px;\\n\\t\u003C\u003Cbackground-linear-gradient \\\"left, rgba(0,0,0,0.15) 0%, rgba(0,0,0,0.0) 100%\\\">>\\n}\\n\\n.tc-more-sidebar > .tc-tab-set > .tc-tab-buttons > button {\\n\\t\u003C\u003Cbackground-linear-gradient \\\"left, rgba(0,0,0,0.01) 0%, rgba(0,0,0,0.1) 100%\\\">>\\n}\\n\\n.tc-more-sidebar > .tc-tab-set > .tc-tab-buttons > button.tc-tab-selected {\\n\\t\u003C\u003Cbackground-linear-gradient \\\"left, rgba(0,0,0,0.05) 0%, rgba(255,255,255,0.05) 100%\\\">>\\n}\\n\\n.tc-message-box img {\\n\\t\u003C\u003Cbox-shadow \\\"1px 1px 3px rgba(0,0,0,0.5)\\\">>\\n}\\n\\n.tc-plugin-info {\\n\\t\u003C\u003Cbox-shadow \\\"1px 1px 3px rgba(0,0,0,0.5)\\\">>\\n}\\n\"}}}"},
{"title":"$:/themes/tiddlywiki/vanilla","name":"Vanilla","author":"JeremyRuston","core-version":">=5.0.0","plugin-type":"theme","description":"Basic theme","plugin-priority":"0","version":"5.2.5","dependents":"","type":"application/json","text":"{\"tiddlers\":{\"$:/themes/tiddlywiki/vanilla/themetweaks\":{\"title\":\"$:/themes/tiddlywiki/vanilla/themetweaks\",\"tags\":\"$:/tags/ControlPanel/Appearance\",\"caption\":\"{{$:/language/ThemeTweaks/ThemeTweaks}}\",\"text\":\"\\\\define lingo-base() $:/language/ThemeTweaks/\\n\\n\\\\define replacement-text()\\n[img[$(imageTitle)$]]\\n\\\\end\\n\\n\\\\define backgroundimage-dropdown()\\n\u003Cdiv class=\\\"tc-drop-down-wrapper\\\">\\n\u003C$set name=\\\"state\\\" value=\u003C\u003Cqualify \\\"$:/state/popup/themetweaks/backgroundimage\\\">>>\\n\u003C$button popup=\u003C\u003Cstate>> class=\\\"tc-btn-invisible tc-btn-dropdown\\\">{{$:/core/images/down-arrow}}\u003C/$button>\\n\u003C$reveal state=\u003C\u003Cstate>> type=\\\"popup\\\" position=\\\"belowleft\\\" text=\\\"\\\" default=\\\"\\\" class=\\\"tc-popup-keep\\\">\\n\u003Cdiv class=\\\"tc-drop-down\\\" style=\\\"text-align:center;\\\">\\n\u003C$macrocall $name=\\\"image-picker\\\" actions=\\\"\\\"\\\"\\n\\n\u003C$action-setfield\\n\\t$tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimage\\\"\\n\\t$value=\u003C\u003CimageTitle>>\\n/>\\n\\n\u003C$action-deletetiddler $tiddler=\u003C\u003Cstate>>/>\\n\\n\\\"\\\"\\\"/>\\n\u003C/div>\\n\u003C/$reveal>\\n\u003C/$set>\\n\u003C/div>\\n\\\\end\\n\\n\\\\define backgroundimageattachment-dropdown()\\n\u003C$select tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimageattachment\\\" default=\\\"scroll\\\">\\n\u003Coption value=\\\"scroll\\\">\u003C\u003Clingo Settings/BackgroundImageAttachment/Scroll>>\u003C/option>\\n\u003Coption value=\\\"fixed\\\">\u003C\u003Clingo Settings/BackgroundImageAttachment/Fixed>>\u003C/option>\\n\u003C/$select>\\n\\\\end\\n\\n\\\\define backgroundimagesize-dropdown()\\n\u003C$select tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize\\\" default=\\\"scroll\\\">\\n\u003Coption value=\\\"auto\\\">\u003C\u003Clingo Settings/BackgroundImageSize/Auto>>\u003C/option>\\n\u003Coption value=\\\"cover\\\">\u003C\u003Clingo Settings/BackgroundImageSize/Cover>>\u003C/option>\\n\u003Coption value=\\\"contain\\\">\u003C\u003Clingo Settings/BackgroundImageSize/Contain>>\u003C/option>\\n\u003C/$select>\\n\\\\end\\n\\n\u003C\u003Clingo ThemeTweaks/Hint>>\\n\\n! \u003C\u003Clingo Options>>\\n\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/options/sidebarlayout\\\">\u003C\u003Clingo Options/SidebarLayout>>\u003C/$link> |\u003C$select tiddler=\\\"$:/themes/tiddlywiki/vanilla/options/sidebarlayout\\\">\u003Coption value=\\\"fixed-fluid\\\">\u003C\u003Clingo Options/SidebarLayout/Fixed-Fluid>>\u003C/option>\u003Coption value=\\\"fluid-fixed\\\">\u003C\u003Clingo Options/SidebarLayout/Fluid-Fixed>>\u003C/option>\u003C/$select> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/options/stickytitles\\\">\u003C\u003Clingo Options/StickyTitles>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Options/StickyTitles/Hint>>// |\u003C$select tiddler=\\\"$:/themes/tiddlywiki/vanilla/options/stickytitles\\\">\u003Coption value=\\\"no\\\">{{$:/language/No}}\u003C/option>\u003Coption value=\\\"yes\\\">{{$:/language/Yes}}\u003C/option>\u003C/$select> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/options/codewrapping\\\">\u003C\u003Clingo Options/CodeWrapping>>\u003C/$link> |\u003C$select tiddler=\\\"$:/themes/tiddlywiki/vanilla/options/codewrapping\\\">\u003Coption value=\\\"pre\\\">{{$:/language/No}}\u003C/option>\u003Coption value=\\\"pre-wrap\\\">{{$:/language/Yes}}\u003C/option>\u003C/$select> |\\n\\n! \u003C\u003Clingo Settings>>\\n\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/fontfamily\\\">\u003C\u003Clingo Settings/FontFamily>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/fontfamily\\\" default=\\\"\\\" tag=\\\"input\\\"/> | |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/codefontfamily\\\">\u003C\u003Clingo Settings/CodeFontFamily>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/codefontfamily\\\" default=\\\"\\\" tag=\\\"input\\\"/> | |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/editorfontfamily\\\">\u003C\u003Clingo Settings/EditorFontFamily>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/editorfontfamily\\\" default=\\\"\\\" tag=\\\"input\\\"/> | |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimage\\\">\u003C\u003Clingo Settings/BackgroundImage>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimage\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\u003C\u003Cbackgroundimage-dropdown>> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimageattachment\\\">\u003C\u003Clingo Settings/BackgroundImageAttachment>>\u003C/$link> |\u003C\u003Cbackgroundimageattachment-dropdown>> | |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize\\\">\u003C\u003Clingo Settings/BackgroundImageSize>>\u003C/$link> |\u003C\u003Cbackgroundimagesize-dropdown>> | |\\n\\n! \u003C\u003Clingo Metrics>>\\n\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/fontsize\\\">\u003C\u003Clingo Metrics/FontSize>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/fontsize\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/lineheight\\\">\u003C\u003Clingo Metrics/LineHeight>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/lineheight\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/bodyfontsize\\\">\u003C\u003Clingo Metrics/BodyFontSize>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/bodyfontsize\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/bodylineheight\\\">\u003C\u003Clingo Metrics/BodyLineHeight>>\u003C/$link> |\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/bodylineheight\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/storyleft\\\">\u003C\u003Clingo Metrics/StoryLeft>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/StoryLeft/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/storyleft\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/storytop\\\">\u003C\u003Clingo Metrics/StoryTop>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/StoryTop/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/storytop\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/storyright\\\">\u003C\u003Clingo Metrics/StoryRight>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/StoryRight/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/storyright\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/storywidth\\\">\u003C\u003Clingo Metrics/StoryWidth>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/StoryWidth/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/storywidth\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth\\\">\u003C\u003Clingo Metrics/TiddlerWidth>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/TiddlerWidth/Hint>>//\u003Cbr> |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint\\\">\u003C\u003Clingo Metrics/SidebarBreakpoint>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/SidebarBreakpoint/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n|\u003C$link to=\\\"$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth\\\">\u003C\u003Clingo Metrics/SidebarWidth>>\u003C/$link>\u003Cbr>//\u003C\u003Clingo Metrics/SidebarWidth/Hint>>// |^\u003C$edit-text tiddler=\\\"$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth\\\" default=\\\"\\\" tag=\\\"input\\\"/> |\\n\"},\"$:/themes/tiddlywiki/vanilla/base\":{\"title\":\"$:/themes/tiddlywiki/vanilla/base\",\"tags\":\"[[$:/tags/Stylesheet]]\",\"code-body\":\"yes\",\"text\":\"\\\\define custom-background-datauri()\\n\u003C$set name=\\\"background\\\" value={{$:/themes/tiddlywiki/vanilla/settings/backgroundimage}}>\\n\u003C$list filter=\\\"[\u003Cbackground>is[image]]\\\">\\n`background: url(`\\n\u003C$list filter=\\\"[\u003Cbackground>!has[_canonical_uri]]\\\">\\n`\\\"`\u003C$macrocall $name=\\\"datauri\\\" title={{$:/themes/tiddlywiki/vanilla/settings/backgroundimage}}/>`\\\"`\\n\u003C/$list>\\n\u003C$list filter=\\\"[\u003Cbackground>has[_canonical_uri]]\\\">\\n`\\\"`\u003C$view tiddler={{$:/themes/tiddlywiki/vanilla/settings/backgroundimage}} field=\\\"_canonical_uri\\\"/>`\\\"`\\n\u003C/$list>\\n`) center center;`\\n`background-attachment: `{{$:/themes/tiddlywiki/vanilla/settings/backgroundimageattachment}}`;\\n-webkit-background-size:` {{$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize}}`;\\n-moz-background-size:` {{$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize}}`;\\n-o-background-size:` {{$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize}}`;\\nbackground-size:` {{$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize}}`;`\\n\u003C/$list>\\n\u003C/$set>\\n\\\\end\\n\\n\\\\define sidebarbreakpoint()\\n\u003C$text text={{$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint}}/>\\n\\\\end\\n\\n\\\\define sidebarbreakpoint-minus-one()\\n\u003C$text text={{{ [{$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint}removesuffix[px]subtract[1]addsuffix[px]] ~[{$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint}] }}}/>\\n\\\\end\\n\\n\\\\define tiddler-width()\\n\\t\u003C$text text={{$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth}}/>\\n\\\\end\\n\\n\\\\define if-fluid-fixed(text,hiddenSidebarText)\\n\u003C$reveal state=\\\"$:/themes/tiddlywiki/vanilla/options/sidebarlayout\\\" type=\\\"match\\\" text=\\\"fluid-fixed\\\">\\n$text$\\n\u003C$reveal state=\\\"$:/state/sidebar\\\" type=\\\"nomatch\\\" text=\\\"yes\\\" default=\\\"yes\\\">\\n$hiddenSidebarText$\\n\u003C/$reveal>\\n\u003C/$reveal>\\n\\\\end\\n\\n\\\\define if-editor-height-fixed(then,else)\\n\u003C$reveal state=\\\"$:/config/TextEditor/EditorHeight/Mode\\\" type=\\\"match\\\" text=\\\"fixed\\\">\\n$then$\\n\u003C/$reveal>\\n\u003C$reveal state=\\\"$:/config/TextEditor/EditorHeight/Mode\\\" type=\\\"match\\\" text=\\\"auto\\\">\\n$else$\\n\u003C/$reveal>\\n\\\\end\\n\\n\\\\define set-type-selector-min-width()\\n\u003C$set name=\\\"typeLength\\\" value={{{ [all[shadows+tiddlers]prefix[$:/language/Docs/Types/]get[name]length[]maxall[]] }}}>\\n\\n\\t.tc-type-selector-dropdown-wrapper {\\n\\t\\tmin-width: calc(\u003C\u003CtypeLength>>ch + 4em);\\n\\t}\\n\\n\\t.tc-type-selector-dropdown-wrapper input.tc-edit-typeeditor {\\n\\t\\tmin-width: \u003C\u003CtypeLength>>ch;\\n\\t}\\n\\n\u003C/$set>\\n\\\\end\\n\\n\\\\rules only filteredtranscludeinline transcludeinline macrodef macrocallinline macrocallblock\\n\\n/*\\n** Start with the normalize CSS reset, and then belay some of its effects\\n*/\\n\\n{{$:/themes/tiddlywiki/vanilla/reset}}\\n\\n*, input[type=\\\"search\\\"] {\\n\\tbox-sizing: border-box;\\n\\t-moz-box-sizing: border-box;\\n\\t-webkit-box-sizing: border-box;\\n}\\n\\n/*\\n** Button default styles. Makes them look consistent for all browsers\\n*/\\nhtml button {\\n\\tline-height: 1.2;\\n\\tcolor: \u003C\u003Ccolour button-foreground>>;\\n\\tfill: \u003C\u003Ccolour button-foreground>>;\\n\\tbackground: \u003C\u003Ccolour button-background>>;\\n\\tborder-color: \u003C\u003Ccolour button-border>>;\\n}\\n\\nbutton:disabled svg {\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n/*\\n** Basic element styles\\n*/\\n\\nhtml, body {\\n\\tfont-family: {{$:/themes/tiddlywiki/vanilla/settings/fontfamily}};\\n\\ttext-rendering: optimizeLegibility; /* Enables kerning and ligatures etc. */\\n\\t-webkit-font-smoothing: antialiased;\\n\\t-moz-osx-font-smoothing: grayscale;\\n}\\n\\nhtml:-webkit-full-screen {\\n\\tbackground-color: \u003C\u003Ccolour page-background>>;\\n}\\n\\nbody.tc-body {\\n\\tfont-size: {{$:/themes/tiddlywiki/vanilla/metrics/fontsize}};\\n\\tline-height: {{$:/themes/tiddlywiki/vanilla/metrics/lineheight}};\\n\\tword-wrap: break-word;\\n\\t\u003C\u003Ccustom-background-datauri>>\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n\\tbackground-color: \u003C\u003Ccolour page-background>>;\\n\\tfill: \u003C\u003Ccolour foreground>>;\\n}\\n\\n\u003C\u003Cif-background-attachment \\\"\\\"\\\"\\n\\nbody.tc-body {\\n\\tbackground-color: transparent;\\n}\\n\\n\\\"\\\"\\\">>\\n\\n/**\\n * Correct the font size and margin on `h1` elements within `section` and\\n * `article` contexts in Chrome, Firefox, and Safari.\\n */\\n\\nh1 {\\n\\tfont-size: 2em;\\n}\\n\\nh1, h2, h3, h4, h5, h6 {\\n\\tline-height: 1.2;\\n\\tfont-weight: normal;\\n}\\n\\npre {\\n\\tdisplay: block;\\n\\tmargin-top: 1em;\\n\\tmargin-bottom: 1em;\\n\\tword-break: break-word;\\n\\tword-wrap: break-word;\\n\\twhite-space: {{$:/themes/tiddlywiki/vanilla/options/codewrapping}};\\n\\tbackground-color: \u003C\u003Ccolour pre-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour pre-border>>;\\n\\tpadding: 0 3px 2px;\\n\\tborder-radius: 3px;\\n\\tfont-family: {{$:/themes/tiddlywiki/vanilla/settings/codefontfamily}};\\n}\\n\\ncode {\\n\\tcolor: \u003C\u003Ccolour code-foreground>>;\\n\\tbackground-color: \u003C\u003Ccolour code-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour code-border>>;\\n\\twhite-space: {{$:/themes/tiddlywiki/vanilla/options/codewrapping}};\\n\\tpadding: 0 3px 2px;\\n\\tborder-radius: 3px;\\n\\tfont-family: {{$:/themes/tiddlywiki/vanilla/settings/codefontfamily}};\\n}\\n\\nblockquote {\\n\\tborder-left: 5px solid \u003C\u003Ccolour blockquote-bar>>;\\n\\tmargin-left: 25px;\\n\\tpadding-left: 10px;\\n\\tquotes: \\\"\\\\201C\\\"\\\"\\\\201D\\\"\\\"\\\\2018\\\"\\\"\\\\2019\\\";\\n}\\n\\nblockquote > div {\\n\\tmargin-top: 1em;\\n\\tmargin-bottom: 1em;\\n}\\n\\nblockquote.tc-big-quote {\\n\\tfont-family: Georgia, serif;\\n\\tposition: relative;\\n\\tbackground: \u003C\u003Ccolour pre-background>>;\\n\\tborder-left: none;\\n\\tmargin-left: 50px;\\n\\tmargin-right: 50px;\\n\\tpadding: 10px;\\n\\tborder-radius: 8px;\\n}\\n\\nblockquote.tc-big-quote cite:before {\\n\\tcontent: \\\"\\\\2014 \\\\2009\\\";\\n}\\n\\nblockquote.tc-big-quote:before {\\n\\tfont-family: Georgia, serif;\\n\\tcolor: \u003C\u003Ccolour blockquote-bar>>;\\n\\tcontent: open-quote;\\n\\tfont-size: 8em;\\n\\tline-height: 0.1em;\\n\\tmargin-right: 0.25em;\\n\\tvertical-align: -0.4em;\\n\\tposition: absolute;\\n\\tleft: -50px;\\n\\ttop: 42px;\\n}\\n\\nblockquote.tc-big-quote:after {\\n\\tfont-family: Georgia, serif;\\n\\tcolor: \u003C\u003Ccolour blockquote-bar>>;\\n\\tcontent: close-quote;\\n\\tfont-size: 8em;\\n\\tline-height: 0.1em;\\n\\tmargin-right: 0.25em;\\n\\tvertical-align: -0.4em;\\n\\tposition: absolute;\\n\\tright: -80px;\\n\\tbottom: -20px;\\n}\\n\\ndl dt {\\n\\tfont-weight: bold;\\n\\tmargin-top: 6px;\\n}\\n\\ntextarea,\\ninput[type=text],\\ninput[type=search],\\ninput[type=\\\"\\\"],\\ninput:not([type]) {\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n}\\n\\ninput[type=\\\"checkbox\\\"] {\\n\\tvertical-align: middle;\\n}\\n\\ninput[type=\\\"search\\\"]::-webkit-search-decoration,\\ninput[type=\\\"search\\\"]::-webkit-search-cancel-button,\\ninput[type=\\\"search\\\"]::-webkit-search-results-button,\\ninput[type=\\\"search\\\"]::-webkit-search-results-decoration {\\n\\t-webkit-appearance:none;\\n}\\n\\n.tc-muted {\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\nsvg.tc-image-button {\\n\\tpadding: 0px 1px 1px 0px;\\n}\\n\\n.tc-icon-wrapper > svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n}\\n\\nkbd {\\n\\tdisplay: inline-block;\\n\\tpadding: 3px 5px;\\n\\tfont-size: 0.8em;\\n\\tline-height: 1.2;\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n\\tvertical-align: middle;\\n\\tbackground-color: \u003C\u003Ccolour background>>;\\n\\tborder: solid 1px \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-bottom-color: \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-radius: 3px;\\n\\tbox-shadow: inset 0 -1px 0 \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n::selection {\\n\\tbackground-color: Highlight;\\n\\tcolor: HighlightText;\\n\\tbackground-color: \u003C\u003Ccolour selection-background>>;\\n\\tcolor: \u003C\u003Ccolour selection-foreground>>;\\n}\\n\\n.tc-inline-style {\\n\\tbackground: \u003C\u003Ccolour highlight-background>>;\\n\\tcolor: \u003C\u003Ccolour highlight-foreground>>;\\n}\\n\\nform.tc-form-inline {\\n\\tdisplay: inline;\\n}\\n\\n/*\\nMarkdown likes putting code elements inside pre elements\\n*/\\npre > code {\\n\\tpadding: 0;\\n\\tborder: none;\\n\\tbackground-color: inherit;\\n\\tcolor: inherit;\\n}\\n\\n/*\\nTable defaults\\n*/\\n\\ntable {\\n\\tborder: 1px solid \u003C\u003Ccolour table-border>>;\\n\\twidth: auto;\\n\\tmax-width: 100%;\\n\\tcaption-side: bottom;\\n\\tmargin-top: 1em;\\n\\tmargin-bottom: 1em;\\n\\t/* next 2 elements needed, since normalize 8.0.1 */\\n\\tborder-collapse: collapse;\\n\\tborder-spacing: 0;\\n}\\n\\ntable th, table td {\\n\\tpadding: 0 7px 0 7px;\\n\\tborder-top: 1px solid \u003C\u003Ccolour table-border>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour table-border>>;\\n}\\n\\ntable thead tr td, table th {\\n\\tbackground-color: \u003C\u003Ccolour table-header-background>>;\\n\\tfont-weight: bold;\\n}\\n\\ntable tfoot tr td {\\n\\tbackground-color: \u003C\u003Ccolour table-footer-background>>;\\n}\\n\\n/*\\nTable utility classes\\n*/\\n\\n/* Remove borders from table as used in eg: GettingStarted*/\\n.tc-table-no-border,\\n.tc-table-no-border th,\\n.tc-table-no-border td {\\n\\tborder: initial;\\n}\\n\\n/* First column in table width will fit to text.*/\\n/* This rule makes most sense with tc-first-link-nowrap*/\\n.tc-first-col-min-width td:nth-child(1) {\\n\\twidth: 1%;\\n}\\n\\n/*\\n** Utility classes work well with tables but also for other containers\\n*/\\n\\n/* First link A element will not wrap */\\n.tc-first-link-nowrap:first-of-type a {\\n\\twhite-space: nowrap;\\n}\\n\\n/* Move the table to the center of the container */\\n.tc-center {\\n\\tmargin-left: auto;\\n\\tmargin-right: auto;\\n}\\n\\n.tc-max-width {\\n\\twidth: 100%;\\n}\\n\\n.tc-max-width-80 {\\n\\tmax-width: 80%;\\n}\\n\\n/* Allow input and textarea to look like the ControlPanel inputs */\\n.tc-edit-max-width input,\\n.tc-edit-max-width textarea {\\n\\twidth: 100%;\\n\\tpadding: 3px;\\n}\\n\\n/*\\nCSV parser plugin\\n*/\\n\\n.tc-csv-table {\\n\\twhite-space: nowrap;\\n}\\n\\n.tc-csv-table th,\\n.tc-csv-table td {\\n\\twhite-space: pre-line;\\n}\\n\\n/*\\nTiddler frame in story river\\n*/\\n\\n.tc-tiddler-frame img,\\n.tc-tiddler-frame svg,\\n.tc-tiddler-frame canvas,\\n.tc-tiddler-frame embed,\\n.tc-tiddler-frame iframe {\\n\\tmax-width: 100%;\\n}\\n\\n.tc-tiddler-body > embed,\\n.tc-tiddler-body > iframe {\\n\\twidth: 100%;\\n\\theight: 600px;\\n}\\n\\n:root {\\n\\tcolor-scheme: {{{ [{$:/palette}get[color-scheme]] ~light }}};\\n}\\n\\n/*\\n** Links\\n*/\\n\\nbutton.tc-tiddlylink,\\na.tc-tiddlylink {\\n\\ttext-decoration: none;\\n\\tfont-weight: 500;\\n\\tcolor: \u003C\u003Ccolour tiddler-link-foreground>>;\\n\\t-webkit-user-select: inherit; /* Otherwise the draggable attribute makes links impossible to select */\\n\\t-webkit-touch-callout: none; /* Prevents long presses from bringing up a link preview */\\n}\\n\\n.tc-sidebar-lists a.tc-tiddlylink {\\n\\tcolor: \u003C\u003Ccolour sidebar-tiddler-link-foreground>>;\\n}\\n\\n.tc-sidebar-lists a.tc-tiddlylink:hover {\\n\\tcolor: \u003C\u003Ccolour sidebar-tiddler-link-foreground-hover>>;\\n}\\n\\nbutton.tc-tiddlylink:hover,\\na.tc-tiddlylink:hover {\\n\\ttext-decoration: underline;\\n}\\n\\na.tc-tiddlylink-resolves {\\n}\\n\\na.tc-tiddlylink-shadow {\\n\\tfont-weight: bold;\\n}\\n\\na.tc-tiddlylink-shadow.tc-tiddlylink-resolves {\\n\\tfont-weight: normal;\\n}\\n\\na.tc-tiddlylink-missing {\\n\\tfont-style: italic;\\n}\\n\\na.tc-tiddlylink-external {\\n\\ttext-decoration: underline;\\n\\tcolor: \u003C\u003Ccolour external-link-foreground>>;\\n\\tbackground-color: \u003C\u003Ccolour external-link-background>>;\\n}\\n\\na.tc-tiddlylink-external:visited {\\n\\tcolor: \u003C\u003Ccolour external-link-foreground-visited>>;\\n\\tbackground-color: \u003C\u003Ccolour external-link-background-visited>>;\\n}\\n\\na.tc-tiddlylink-external:hover {\\n\\tcolor: \u003C\u003Ccolour external-link-foreground-hover>>;\\n\\tbackground-color: \u003C\u003Ccolour external-link-background-hover>>;\\n}\\n\\n.tc-drop-down a.tc-tiddlylink:hover {\\n\\tcolor: \u003C\u003Ccolour tiddler-link-background>>;\\n}\\n\\n/*\\n** Drag and drop styles\\n*/\\n\\n.tc-tiddler-dragger {\\n\\tposition: relative;\\n\\tz-index: -10000;\\n}\\n\\n.tc-tiddler-dragger-inner {\\n\\tposition: absolute;\\n\\ttop: -1000px;\\n\\tleft: -1000px;\\n\\tdisplay: inline-block;\\n\\tpadding: 8px 20px;\\n\\tfont-size: 16.9px;\\n\\tfont-weight: bold;\\n\\tline-height: 20px;\\n\\tcolor: \u003C\u003Ccolour dragger-foreground>>;\\n\\ttext-shadow: 0 1px 0 rgba(0, 0, 0, 1);\\n\\twhite-space: nowrap;\\n\\tvertical-align: baseline;\\n\\tbackground-color: \u003C\u003Ccolour dragger-background>>;\\n\\tborder-radius: 20px;\\n}\\n\\n.tc-tiddler-dragger-cover {\\n\\tposition: absolute;\\n\\tbackground-color: \u003C\u003Ccolour page-background>>;\\n}\\n\\n.tc-page-container > .tc-dropzone {\\n\\tmin-height: 100vh;\\n}\\n\\n.tc-dropzone {\\n\\tposition: relative;\\n}\\n\\n.tc-dropzone.tc-dragover:before {\\n\\tz-index: 10000;\\n\\tdisplay: block;\\n\\tposition: fixed;\\n\\ttop: 0;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tbackground: \u003C\u003Ccolour dropzone-background>>;\\n\\ttext-align: center;\\n\\tcontent: \\\"\u003C\u003Clingo DropMessage>>\\\";\\n}\\n\\n.tc-droppable > .tc-droppable-placeholder {\\n\\tdisplay: none;\\n}\\n\\n.tc-droppable.tc-dragover > .tc-droppable-placeholder {\\n\\tdisplay: block;\\n\\tborder: 2px dashed \u003C\u003Ccolour dropzone-background>>;\\n}\\n\\n.tc-draggable {\\n\\tcursor: move;\\n}\\n\\n.tc-sidebar-tab-open .tc-droppable-placeholder, .tc-tagged-draggable-list .tc-droppable-placeholder,\\n.tc-links-draggable-list .tc-droppable-placeholder {\\n\\tline-height: 2em;\\n\\theight: 2em;\\n}\\n\\n.tc-sidebar-tab-open-item {\\n\\tposition: relative;\\n}\\n\\n.tc-sidebar-tab-open .tc-btn-invisible.tc-btn-mini svg {\\n\\tfont-size: 0.7em;\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n/*\\n** Plugin reload warning\\n*/\\n\\n.tc-plugin-reload-warning {\\n\\tz-index: 1000;\\n\\tdisplay: block;\\n\\tposition: fixed;\\n\\ttop: 0;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tbackground: \u003C\u003Ccolour alert-background>>;\\n\\ttext-align: center;\\n}\\n\\n/*\\n** Buttons\\n*/\\n\\nbutton svg, button img, label svg, label img {\\n\\tvertical-align: middle;\\n}\\n\\n.tc-btn-invisible {\\n\\tpadding: 0;\\n\\tmargin: 0;\\n\\tbackground: none;\\n\\tborder: none;\\n\\tcursor: pointer;\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n\\tfill: \u003C\u003Ccolour foreground>>;\\n}\\n\\nbutton:disabled.tc-btn-invisible  {\\n\\tcursor: default; \\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-btn-boxed {\\n\\tfont-size: 0.6em;\\n\\tpadding: 0.2em;\\n\\tmargin: 1px;\\n\\tbackground: none;\\n\\tborder: 1px solid \u003C\u003Ccolour tiddler-controls-foreground>>;\\n\\tborder-radius: 0.25em;\\n}\\n\\nhtml body.tc-body .tc-btn-boxed svg {\\n\\tfont-size: 1.6666em;\\n}\\n\\n.tc-btn-boxed:hover {\\n\\tbackground: \u003C\u003Ccolour muted-foreground>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n}\\n\\nhtml body.tc-body .tc-btn-boxed:hover svg {\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-btn-rounded {\\n\\tfont-size: 0.5em;\\n\\tline-height: 2;\\n\\tpadding: 0em 0.3em 0.2em 0.4em;\\n\\tmargin: 1px;\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tbackground: \u003C\u003Ccolour muted-foreground>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tborder-radius: 2em;\\n}\\n\\nhtml body.tc-body .tc-btn-rounded svg {\\n\\tfont-size: 1.6666em;\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-btn-rounded:hover {\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\nhtml body.tc-body .tc-btn-rounded:hover svg {\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-btn-icon svg {\\n\\theight: 1em;\\n\\twidth: 1em;\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n\\n.tc-btn-text {\\n\\tmargin-left: 7px;\\n}\\n\\n/* used for documentation \\\"fake\\\" buttons */\\n.tc-btn-standard {\\n\\tline-height: 1.8;\\n\\tcolor: #667;\\n\\tbackground-color: #e0e0e0;\\n\\tborder: 1px solid #888;\\n\\tpadding: 2px 1px 2px 1px;\\n\\tmargin: 1px 4px 1px 4px;\\n}\\n\\n.tc-btn-big-green {\\n\\tdisplay: inline-block;\\n\\tpadding: 8px;\\n\\tmargin: 4px 8px 4px 8px;\\n\\tbackground: \u003C\u003Ccolour download-background>>;\\n\\tcolor: \u003C\u003Ccolour download-foreground>>;\\n\\tfill: \u003C\u003Ccolour download-foreground>>;\\n\\tborder: none;\\n\\tborder-radius: 2px;\\n\\tfont-size: 1.2em;\\n\\tline-height: 1.4em;\\n\\ttext-decoration: none;\\n}\\n\\n.tc-btn-big-green svg,\\n.tc-btn-big-green img {\\n\\theight: 2em;\\n\\twidth: 2em;\\n\\tvertical-align: middle;\\n\\tfill: \u003C\u003Ccolour download-foreground>>;\\n}\\n\\n.tc-primary-btn {\\n\\tbackground: \u003C\u003Ccolour primary>>;\\n}\\n\\n.tc-sidebar-lists input {\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n}\\n\\n.tc-sidebar-lists button {\\n\\tcolor: \u003C\u003Ccolour sidebar-button-foreground>>;\\n\\tfill: \u003C\u003Ccolour sidebar-button-foreground>>;\\n}\\n\\n.tc-sidebar-lists button.tc-btn-mini {\\n\\tcolor: \u003C\u003Ccolour sidebar-muted-foreground>>;\\n}\\n\\n.tc-sidebar-lists button.tc-btn-mini:hover {\\n\\tcolor: \u003C\u003Ccolour sidebar-muted-foreground-hover>>;\\n}\\n\\n.tc-sidebar-lists button small {\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n}\\n\\nbutton svg.tc-image-button, button .tc-image-button img {\\n\\theight: 1em;\\n\\twidth: 1em;\\n}\\n\\n.tc-unfold-banner {\\n\\tposition: absolute;\\n\\tpadding: 0;\\n\\tmargin: 0;\\n\\tbackground: none;\\n\\tborder: none;\\n\\twidth: 100%;\\n\\twidth: calc(100% + 2px);\\n\\tmargin-left: -43px;\\n\\ttext-align: center;\\n\\tborder-top: 2px solid \u003C\u003Ccolour tiddler-info-background>>;\\n\\tmargin-top: 4px;\\n}\\n\\n.tc-unfold-banner:hover {\\n\\tbackground: \u003C\u003Ccolour tiddler-info-background>>;\\n\\tborder-top: 2px solid \u003C\u003Ccolour tiddler-info-border>>;\\n}\\n\\n.tc-unfold-banner svg, .tc-fold-banner svg {\\n\\theight: 0.75em;\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground>>;\\n}\\n\\n.tc-unfold-banner:hover svg, .tc-fold-banner:hover svg {\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground-hover>>;\\n}\\n\\n.tc-fold-banner {\\n\\tposition: absolute;\\n\\tpadding: 0;\\n\\tmargin: 0;\\n\\tbackground: none;\\n\\tborder: none;\\n\\twidth: 23px;\\n\\ttext-align: center;\\n\\tmargin-left: -35px;\\n\\ttop: 6px;\\n\\tbottom: 6px;\\n}\\n\\n.tc-fold-banner:hover {\\n\\tbackground: \u003C\u003Ccolour tiddler-info-background>>;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\n\\t.tc-unfold-banner {\\n\\t\\tposition: static;\\n\\t\\twidth: calc(100% + 59px);\\n\\t}\\n\\n\\t.tc-fold-banner {\\n\\t\\twidth: 16px;\\n\\t\\tmargin-left: -16px;\\n\\t\\tfont-size: 0.75em;\\n\\t}\\n\\n}\\n\\n/*\\n** Tags and missing tiddlers\\n*/\\n\\n.tc-tag-list-item {\\n\\tposition: relative;\\n\\tdisplay: inline-block;\\n}\\n\\n.tc-tags-wrapper {\\n\\tmargin: 4px 0 14px 0;\\n}\\n\\n.tc-tags-wrapper .tc-tag-list-item {\\n\\tmargin-right: 7px;\\n}\\n\\n.tc-missing-tiddler-label {\\n\\tfont-style: italic;\\n\\tfont-weight: normal;\\n\\tdisplay: inline-block;\\n\\tfont-size: 11.844px;\\n\\tline-height: 14px;\\n\\twhite-space: nowrap;\\n\\tvertical-align: baseline;\\n}\\n\\n.tc-block-tags-dropdown > .tc-btn-invisible:hover {\\n\\tbackground-color: \u003C\u003Ccolour primary>>;\\n}\\n\\nbutton.tc-tag-label, span.tc-tag-label {\\n\\tdisplay: inline-block;\\n\\tpadding: 0.16em 0.7em;\\n\\tfont-size: 0.9em;\\n\\tfont-weight: normal;\\n\\tline-height: 1.2em;\\n\\tcolor: \u003C\u003Ccolour tag-foreground>>;\\n\\twhite-space: break-spaces;\\n\\tvertical-align: baseline;\\n\\tbackground-color: \u003C\u003Ccolour tag-background>>;\\n\\tborder-radius: 1em;\\n}\\n\\n.tc-sidebar-scrollable .tc-tag-label {\\n\\ttext-shadow: none;\\n}\\n\\n.tc-untagged-separator {\\n\\twidth: 10em;\\n\\tleft: 0;\\n\\tmargin-left: 0;\\n\\tborder: 0;\\n\\theight: 1px;\\n\\tbackground: \u003C\u003Ccolour tab-divider>>;\\n}\\n\\nbutton.tc-untagged-label {\\n\\tbackground-color: \u003C\u003Ccolour untagged-background>>;\\n}\\n\\n.tc-tag-label svg, .tc-tag-label img {\\n\\theight: 1em;\\n\\twidth: 1em;\\n\\tmargin-right: 3px;\\n\\tmargin-bottom: 1px;\\n\\tvertical-align: bottom;\\n}\\n\\n.tc-edit-tags button.tc-remove-tag-button svg {\\n\\tfont-size: 0.7em;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-tag-manager-table .tc-tag-label {\\n}\\n\\n.tc-tag-manager-tag {\\n\\twidth: 100%;\\n}\\n\\nbutton.tc-btn-invisible.tc-remove-tag-button {\\n\\toutline: none;\\n}\\n\\n.tc-tag-button-selected,\\n.tc-list-item-selected a.tc-tiddlylink, a.tc-list-item-selected {\\n\\tbackground-color: \u003C\u003Ccolour primary>>;\\n\\tcolor: \u003C\u003Ccolour tiddler-background>>;\\n}\\n\\n/*\\n** Page layout\\n*/\\n\\n.tc-topbar {\\n\\tposition: fixed;\\n\\tz-index: 1200;\\n}\\n\\n.tc-topbar-left {\\n\\tleft: 29px;\\n\\ttop: 5px;\\n}\\n\\n.tc-topbar-right {\\n\\ttop: 5px;\\n\\tright: 29px;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\n\\t.tc-topbar-right {\\n\\t\\tright: 10px;\\n\\t}\\n\\n}\\n\\n.tc-topbar button {\\n\\tpadding: 8px;\\n}\\n\\n.tc-topbar svg {\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-topbar button:hover svg {\\n\\tfill: \u003C\u003Ccolour foreground>>;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\n\\t.tc-show-sidebar-btn svg.tc-image-chevron-left, .tc-hide-sidebar-btn svg.tc-image-chevron-right {\\n\\t\\ttransform: rotate(-90deg);\\n\\t}\\n\\n}\\n\\n.tc-sidebar-header {\\n\\tcolor: \u003C\u003Ccolour sidebar-foreground>>;\\n\\tfill: \u003C\u003Ccolour sidebar-foreground>>;\\n}\\n\\n.tc-sidebar-header .tc-title a.tc-tiddlylink-resolves {\\n\\tfont-weight: normal;\\n}\\n\\n.tc-sidebar-header .tc-sidebar-lists p {\\n\\tmargin-top: 3px;\\n\\tmargin-bottom: 3px;\\n}\\n\\n.tc-sidebar-header .tc-missing-tiddler-label {\\n\\tcolor: \u003C\u003Ccolour sidebar-foreground>>;\\n}\\n\\n.tc-advanced-search input {\\n\\twidth: 60%;\\n}\\n\\n.tc-search a svg {\\n\\twidth: 1.2em;\\n\\theight: 1.2em;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-page-controls {\\n\\tmargin-top: 14px;\\n\\tfont-size: 1.5em;\\n}\\n\\n.tc-page-controls .tc-drop-down {\\n\\tfont-size: 1rem;\\n}\\n\\n.tc-page-controls button {\\n\\tmargin-right: 0.5em;\\n}\\n\\n.tc-page-controls a.tc-tiddlylink:hover {\\n\\ttext-decoration: none;\\n}\\n\\n.tc-page-controls img {\\n\\twidth: 1em;\\n}\\n\\n.tc-page-controls svg {\\n\\tfill: \u003C\u003Ccolour sidebar-controls-foreground>>;\\n}\\n\\n.tc-page-controls button:hover svg, .tc-page-controls a:hover svg {\\n\\tfill: \u003C\u003Ccolour sidebar-controls-foreground-hover>>;\\n}\\n\\n.tc-sidebar-lists .tc-menu-list-item {\\n\\twhite-space: nowrap;\\n}\\n\\n.tc-menu-list-count {\\n\\tfont-weight: bold;\\n}\\n\\n.tc-menu-list-subitem {\\n\\tpadding-left: 7px;\\n}\\n\\n.tc-story-river {\\n\\tposition: relative;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\n\\t.tc-sidebar-header {\\n\\t\\tpadding: 14px;\\n\\t\\tmin-height: 32px;\\n\\t\\tmargin-top: {{$:/themes/tiddlywiki/vanilla/metrics/storytop}};\\n\\t\\ttransition:  min-height {{$:/config/AnimationDuration}}ms ease-in-out, padding-top {{$:/config/AnimationDuration}}ms ease-in-out, padding-bottom {{$:/config/AnimationDuration}}ms ease-in-out;\\n\\t}\\n\\t\\n\\t\u003C\u003Cif-no-sidebar \\\"\\\"\\\"\\n\\n\\t\\t.tc-sidebar-header {\\n\\t\\t\\tmin-height: 0;\\n\\t\\t\\tpadding-top: 0;\\n\\t\\t\\tpadding-bottom: 0;\\n\\t\\t}\\n\\n\\t\\\"\\\"\\\">>\\n\\n\\t.tc-story-river {\\n\\t\\tposition: relative;\\n\\t\\tpadding: 0;\\n\\t}\\n}\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\\t.tc-message-box {\\n\\t\\tmargin: 21px -21px 21px -21px;\\n\\t}\\n\\n\\t.tc-sidebar-scrollable {\\n\\t\\tposition: fixed;\\n\\t\\ttop: {{$:/themes/tiddlywiki/vanilla/metrics/storytop}};\\n\\t\\tleft: {{$:/themes/tiddlywiki/vanilla/metrics/storyright}};\\n\\t\\tbottom: 0;\\n\\t\\tright: 0;\\n\\t\\toverflow-y: auto;\\n\\t\\toverflow-x: auto;\\n\\t\\t-webkit-overflow-scrolling: touch;\\n\\t\\tmargin: 0 0 0 -42px;\\n\\t\\tpadding: 71px 0 28px 42px;\\n\\t}\\n\\n\\thtml[dir=\\\"rtl\\\"] .tc-sidebar-scrollable {\\n\\t\\tleft: auto;\\n\\t\\tright: {{$:/themes/tiddlywiki/vanilla/metrics/storyright}};\\n\\t}\\n\\n\\t.tc-story-river {\\n\\t\\tposition: relative;\\n\\t\\tleft: {{$:/themes/tiddlywiki/vanilla/metrics/storyleft}};\\n\\t\\ttop: {{$:/themes/tiddlywiki/vanilla/metrics/storytop}};\\n\\t\\twidth: {{$:/themes/tiddlywiki/vanilla/metrics/storywidth}};\\n\\t\\tpadding: 42px 42px 42px 42px;\\n\\t}\\n\\n\u003C\u003Cif-no-sidebar \\\"\\n\\n\\t.tc-story-river {\\n\\t\\twidth: calc(100% - {{$:/themes/tiddlywiki/vanilla/metrics/storyleft}});\\n\\t}\\n\\n\\\">>\\n\\n\\t.tc-story-river.tc-static-story-river {\\n\\t\\tmargin-right: 0;\\n\\t\\tpadding-right: 42px;\\n\\t}\\n\\n}\\n\\n@media print {\\n\\n\\tbody.tc-body {\\n\\t\\tbackground-color: transparent;\\n\\t}\\n\\n\\t.tc-sidebar-header, .tc-topbar {\\n\\t\\tdisplay: none;\\n\\t}\\n\\n\\t.tc-story-river {\\n\\t\\tmargin: 0;\\n\\t\\tpadding: 0;\\n\\t}\\n\\n\\t.tc-story-river .tc-tiddler-frame {\\n\\t\\tmargin: 0;\\n\\t\\tborder: none;\\n\\t\\tpadding: 0;\\n\\t}\\n}\\n\\n/*\\n** Tiddler styles\\n*/\\n\\n.tc-tiddler-frame {\\n\\tposition: relative;\\n\\tmargin-bottom: 28px;\\n\\tbackground-color: \u003C\u003Ccolour tiddler-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour tiddler-border>>;\\n}\\n\\n{{$:/themes/tiddlywiki/vanilla/sticky}}\\n\\n.tc-tiddler-info {\\n\\toverflow: hidden;\\n\\tpadding: 14px 42px 14px 42px;\\n\\tbackground-color: \u003C\u003Ccolour tiddler-info-background>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour tiddler-info-border>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tiddler-info-border>>;\\n}\\n\\n.tc-tiddler-info p {\\n\\tmargin-top: 3px;\\n\\tmargin-bottom: 3px;\\n}\\n\\n.tc-tiddler-info .tc-tab-buttons button.tc-tab-selected {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-info-tab-background>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tiddler-info-tab-background>>;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\n\\t.tc-tiddler-info {\\n\\t\\tpadding: 14px 14px 14px 14px;\\n\\t}\\n\\n}\\n\\n.tc-view-field-table {\\n\\twidth: 100%;\\n}\\n\\n.tc-view-field-name {\\n\\twidth: 1%; /* Makes this column be as narrow as possible */\\n\\twhite-space: nowrap;\\n\\tvertical-align: top;\\n\\ttext-align: right;\\n\\tfont-style: italic;\\n\\tfont-weight: normal;\\n}\\n\\n.tc-view-field-value {\\n\\tword-break: break-all;\\n}\\n\\n@media (max-width: \u003C\u003Csidebarbreakpoint-minus-one>>) {\\n\\t.tc-tiddler-frame {\\n\\t\\tpadding: 14px 14px 14px 14px;\\n\\t\\tmargin-bottom: .5em;\\n\\t}\\n\\n\\t.tc-tiddler-info {\\n\\t\\tmargin: 0 -14px 0 -14px;\\n\\t}\\n}\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\t.tc-tiddler-frame {\\n\\t\\tpadding: 28px 42px 42px 42px;\\n\\t\\twidth: {{$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth}};\\n\\t\\tborder-radius: 2px;\\n\\t}\\n\\n\u003C\u003Cif-no-sidebar \\\"\\n\\n\\t.tc-tiddler-frame {\\n\\t\\twidth: 100%;\\n\\t}\\n\\n\\\">>\\n\\n\\t.tc-tiddler-info {\\n\\t\\tmargin: 0 -42px 0 -42px;\\n\\t}\\n}\\n\\n\\n/* prevent overflow for table content for small screens*/\\n@media (max-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\t.tc-tiddler-frame tr {\\n\\t\\tword-wrap: anywhere;\\n\\t}\\n\\n\\t.tc-tiddler-frame table blockquote {\\n\\t\\tmargin-left: 12.5px;\\n\\t\\tmargin-right: 12.5px; \\n\\t}\\n\\n\\t.tc-tiddler-frame table dd {\\n\\t\\tmargin-left: 12.5px;\\n\\t}\\n\\n\\t.tc-tiddler-frame table ol,\\n\\t.tc-tiddler-frame table ul {\\n\\t\\tpadding-left: 20px;\\n\\t}\\n}\\n\\n.tc-site-title,\\n.tc-titlebar {\\n\\tfont-weight: normal;\\n\\tfont-size: 2.35em;\\n\\tline-height: 1.35em;\\n\\tcolor: \u003C\u003Ccolour tiddler-title-foreground>>;\\n\\tmargin: 0;\\n}\\n\\n.tc-site-title {\\n\\tcolor: \u003C\u003Ccolour site-title-foreground>>;\\n}\\n\\n.tc-tiddler-title-icon {\\n\\tvertical-align: middle;\\n\\tmargin-right: .1em;\\n}\\n\\n.tc-system-title-prefix {\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-titlebar h2 {\\n\\tfont-size: 1em;\\n\\tdisplay: inline;\\n}\\n\\n.tc-titlebar img {\\n\\theight: 1em;\\n}\\n\\n.tc-subtitle {\\n\\tfont-size: 0.9em;\\n\\tcolor: \u003C\u003Ccolour tiddler-subtitle-foreground>>;\\n\\tfont-weight: normal;\\n}\\n\\n.tc-subtitle .tc-tiddlylink {\\n\\tmargin-right: .3em;\\n}\\n\\n.tc-tiddler-missing .tc-title {\\n\\tfont-style: italic;\\n\\tfont-weight: normal;\\n}\\n\\n.tc-tiddler-frame .tc-tiddler-controls {\\n\\tfloat: right;\\n\\tpadding: 3px; /* make space for outline */\\n}\\n\\n.tc-tiddler-controls .tc-drop-down {\\n\\tfont-size: 0.6em;\\n}\\n\\n.tc-tiddler-controls .tc-drop-down .tc-drop-down {\\n\\tfont-size: 1em;\\n}\\n\\n.tc-tiddler-controls > span > button,\\n.tc-tiddler-controls > span > span > button,\\n.tc-tiddler-controls > span > span > span > button {\\n\\tvertical-align: baseline;\\n\\tmargin-left:5px;\\n}\\n\\n.tc-tiddler-controls button svg, .tc-tiddler-controls button img,\\n.tc-search button svg, .tc-search a svg {\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground>>;\\n}\\n\\n.tc-tiddler-controls button svg, .tc-tiddler-controls button img {\\n\\theight: 0.75em;\\n}\\n\\n.tc-search button svg, .tc-search a svg {\\n\\theight: 1.2em;\\n\\twidth: 1.2em;\\n\\tmargin: 0 0.25em;\\n}\\n\\n.tc-tiddler-controls button.tc-selected svg,\\n.tc-page-controls button.tc-selected svg  {\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground-selected>>;\\n}\\n\\n.tc-tiddler-controls button.tc-btn-invisible:hover svg,\\n.tc-search button:hover svg, .tc-search a:hover svg {\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground-hover>>;\\n}\\n\\n@media print {\\n\\t.tc-tiddler-controls {\\n\\t\\tdisplay: none;\\n\\t}\\n}\\n\\n.tc-tiddler-help { /* Help prompts within tiddler template */\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n\\tmargin-top: 14px;\\n}\\n\\n.tc-tiddler-help a.tc-tiddlylink {\\n\\tcolor: \u003C\u003Ccolour very-muted-foreground>>;\\n}\\n\\n.tc-tiddler-frame .tc-edit-texteditor {\\n\\twidth: 100%;\\n\\tmargin: 4px 0 4px 0;\\n}\\n\\n.tc-tiddler-frame input.tc-edit-texteditor,\\n.tc-tiddler-frame textarea.tc-edit-texteditor,\\n.tc-tiddler-frame iframe.tc-edit-texteditor,\\n.tc-tiddler-frame select.tc-edit-texteditor {\\n\\tpadding: 3px 3px 3px 3px;\\n\\tborder: 1px solid \u003C\u003Ccolour tiddler-editor-border>>;\\n\\tline-height: 1.3em;\\n\\tfont-family: {{$:/themes/tiddlywiki/vanilla/settings/editorfontfamily}};\\n}\\n\\n.tc-tiddler-frame input.tc-edit-texteditor,\\n.tc-tiddler-frame textarea.tc-edit-texteditor,\\n.tc-tiddler-frame iframe.tc-edit-texteditor {\\n\\t-webkit-appearance: none;\\n}\\n\\n.tc-tiddler-frame input.tc-edit-texteditor,\\n.tc-tiddler-frame select.tc-edit-texteditor,\\n.tc-tiddler-frame textarea.tc-edit-texteditor {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-editor-background>>;\\n}\\n\\n.tc-tiddler-frame iframe.tc-edit-texteditor {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-background>>;\\n}\\n\\n.tc-tiddler-frame .tc-edit-fields input.tc-edit-fieldeditor,\\n.tc-tiddler-frame .tc-edit-fields select.tc-edit-fieldeditor,\\n.tc-tiddler-frame .tc-edit-fields textarea.tc-edit-fieldeditor {\\n\\tmargin: 0;\\n\\tpadding: 2px 3px;\\n}\\n\\n.tc-tiddler-frame .tc-binary-warning {\\n\\twidth: 100%;\\n\\theight: 5em;\\n\\ttext-align: center;\\n\\tpadding: 3em 3em 6em 3em;\\n\\tbackground: \u003C\u003Ccolour alert-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour alert-border>>;\\n}\\n\\ncanvas.tc-edit-bitmapeditor  {\\n\\tborder: 6px solid \u003C\u003Ccolour tiddler-editor-border-image>>;\\n\\tcursor: crosshair;\\n\\t-moz-user-select: none;\\n\\t-webkit-user-select: none;\\n\\t-ms-user-select: none;\\n\\tmargin-top: 6px;\\n\\tmargin-bottom: 6px;\\n}\\n\\n.tc-edit-bitmapeditor-width {\\n\\tdisplay: block;\\n}\\n\\n.tc-edit-bitmapeditor-height {\\n\\tdisplay: block;\\n}\\n\\n.tc-tiddler-body {\\n\\tclear: both;\\n}\\n\\n.tc-tiddler-frame .tc-tiddler-body {\\n\\tfont-size: {{$:/themes/tiddlywiki/vanilla/metrics/bodyfontsize}};\\n\\tline-height: {{$:/themes/tiddlywiki/vanilla/metrics/bodylineheight}};\\n}\\n\\n.tc-titlebar, .tc-tiddler-edit-title {\\n\\toverflow: hidden; /* https://github.com/Jermolene/TiddlyWiki5/issues/282 */\\n}\\n\\nhtml body.tc-body.tc-single-tiddler-window {\\n\\tmargin: 1em;\\n\\tbackground: \u003C\u003Ccolour tiddler-background>>;\\n}\\n\\n.tc-single-tiddler-window img,\\n.tc-single-tiddler-window svg,\\n.tc-single-tiddler-window canvas,\\n.tc-single-tiddler-window embed,\\n.tc-single-tiddler-window iframe {\\n\\tmax-width: 100%;\\n}\\n\\n/*\\n** Editor\\n*/\\n\\n.tc-editor-toolbar {\\n\\tmargin-top: 8px;\\n}\\n\\n.tc-editor-toolbar button {\\n\\tvertical-align: middle;\\n\\tbackground-color: \u003C\u003Ccolour tiddler-controls-foreground>>;\\n\\tcolor: \u003C\u003Ccolour tiddler-controls-foreground-selected>>;\\n\\tfill: \u003C\u003Ccolour tiddler-controls-foreground-selected>>;\\n\\tborder-radius: 4px;\\n\\tpadding: 3px;\\n\\tmargin: 2px 0 2px 4px;\\n}\\n\\n.tc-editor-toolbar button.tc-text-editor-toolbar-item-adjunct {\\n\\tmargin-left: 1px;\\n\\twidth: 1em;\\n\\tborder-radius: 8px;\\n}\\n\\n.tc-editor-toolbar button.tc-text-editor-toolbar-item-start-group {\\n\\tmargin-left: 11px;\\n}\\n\\n.tc-editor-toolbar button.tc-selected {\\n\\tbackground-color: \u003C\u003Ccolour primary>>;\\n}\\n\\n.tc-editor-toolbar button svg {\\n\\twidth: 1.6em;\\n\\theight: 1.2em;\\n}\\n\\n.tc-editor-toolbar button:hover {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-controls-foreground-selected>>;\\n\\tfill: \u003C\u003Ccolour background>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-editor-toolbar .tc-text-editor-toolbar-more {\\n\\twhite-space: normal;\\n}\\n\\n.tc-editor-toolbar .tc-text-editor-toolbar-more button {\\n\\tdisplay: inline-block;\\n\\tpadding: 3px;\\n\\twidth: auto;\\n}\\n\\n.tc-editor-toolbar .tc-search-results {\\n\\tpadding: 0;\\n}\\n\\n.tc-editor-toolbar button.tc-editortoolbar-stamp-button + .tc-popup .tc-drop-down > p {\\n\\tmargin: 0;\\n\\tpadding: 0;\\n}\\n\\n.tc-editor-toolbar button.tc-editortoolbar-stamp-button + .tc-popup .tc-drop-down a.tc-tiddlylink {\\n\\tfont-weight: normal;\\n}\\n\\n/*\\n** Adjustments for fluid-fixed mode\\n*/\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\u003C\u003Cif-fluid-fixed text:\\\"\\\"\\\"\\n\\n\\t.tc-story-river {\\n\\t\\tpadding-right: 0;\\n\\t\\tposition: relative;\\n\\t\\twidth: auto;\\n\\t\\tleft: 0;\\n\\t\\tmargin-left: {{$:/themes/tiddlywiki/vanilla/metrics/storyleft}};\\n\\t\\tmargin-right: {{$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth}};\\n\\t}\\n\\n\\t.tc-tiddler-frame {\\n\\t\\twidth: 100%;\\n\\t}\\n\\n\\t.tc-sidebar-scrollable {\\n\\t\\tleft: auto;\\n\\t\\tbottom: 0;\\n\\t\\tright: 0;\\n\\t\\twidth: {{$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth}};\\n\\t}\\n\\n\\tbody.tc-body .tc-storyview-zoomin-tiddler {\\n\\t\\twidth: 100%;\\n\\t\\twidth: calc(100% - 42px);\\n\\t}\\n\\n\\\"\\\"\\\" hiddenSidebarText:\\\"\\\"\\\"\\n\\n\\t.tc-story-river {\\n\\t\\tpadding-right: 3em;\\n\\t\\tmargin-right: 0;\\n\\t}\\n\\n\\tbody.tc-body .tc-storyview-zoomin-tiddler {\\n\\t\\twidth: 100%;\\n\\t\\twidth: calc(100% - 84px);\\n\\t}\\n\\n\\\"\\\"\\\">>\\n\\n}\\n\\n/*\\n** Toolbar buttons\\n*/\\n\\n.tc-page-controls svg.tc-image-new-button {\\n\\tfill: \u003C\u003Ccolour toolbar-new-button>>;\\n}\\n\\n.tc-page-controls svg.tc-image-options-button {\\n\\tfill: \u003C\u003Ccolour toolbar-options-button>>;\\n}\\n\\n.tc-page-controls svg.tc-image-save-button {\\n\\tfill: \u003C\u003Ccolour toolbar-save-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-info-button {\\n\\tfill: \u003C\u003Ccolour toolbar-info-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-edit-button {\\n\\tfill: \u003C\u003Ccolour toolbar-edit-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-close-button {\\n\\tfill: \u003C\u003Ccolour toolbar-close-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-delete-button {\\n\\tfill: \u003C\u003Ccolour toolbar-delete-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-cancel-button {\\n\\tfill: \u003C\u003Ccolour toolbar-cancel-button>>;\\n}\\n\\n.tc-tiddler-controls button svg.tc-image-done-button {\\n\\tfill: \u003C\u003Ccolour toolbar-done-button>>;\\n}\\n\\n.tc-page-controls svg.tc-image-layout-button {\\n\\tfill: \u003C\u003Ccolour toolbar-options-button>>;\\n}\\n\\n/*\\n** Tiddler edit mode\\n*/\\n\\n.tc-tiddler-edit-frame em.tc-edit {\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n\\tfont-style: normal;\\n}\\n\\n.tc-edit-type-dropdown a.tc-tiddlylink-missing {\\n\\tfont-style: normal;\\n}\\n\\n.tc-type-selector .tc-edit-typeeditor {\\n\\twidth: auto;\\n}\\n\\n.tc-type-selector-dropdown-wrapper {\\n\\tdisplay: inline-block;\\n}\\n\\n\u003C\u003Cset-type-selector-min-width>>\\n\\n.tc-edit-tags {\\n\\tborder: 1px solid \u003C\u003Ccolour tiddler-editor-border>>;\\n\\tpadding: 4px 8px 4px 8px;\\n}\\n\\n.tc-edit-add-tag {\\n\\tdisplay: inline-block;\\n}\\n\\n.tc-edit-add-tag .tc-add-tag-name input {\\n\\twidth: 50%;\\n}\\n\\n.tc-edit-add-tag .tc-keyboard {\\n\\tdisplay:inline;\\n}\\n\\n.tc-edit-tags .tc-tag-label {\\n\\tdisplay: inline-block;\\n}\\n\\n.tc-edit-tags-list {\\n\\tmargin: 14px 0 14px 0;\\n}\\n\\n.tc-remove-tag-button {\\n\\tpadding-left: 4px;\\n}\\n\\n.tc-tiddler-preview {\\n\\toverflow: auto;\\n}\\n\\n.tc-tiddler-preview-preview {\\n\\tfloat: right;\\n\\twidth: 49%;\\n\\tborder: 1px solid \u003C\u003Ccolour tiddler-editor-border>>;\\n\\tmargin: 4px 0 3px 3px;\\n\\tpadding: 3px 3px 3px 3px;\\n}\\n\\n\u003C\u003Cif-editor-height-fixed then:\\\"\\\"\\\"\\n\\n.tc-tiddler-preview-preview {\\n\\toverflow-y: scroll;\\n\\theight: {{$:/config/TextEditor/EditorHeight/Height}};\\n}\\n\\n\\\"\\\"\\\">>\\n\\n.tc-tiddler-frame .tc-tiddler-preview .tc-edit-texteditor {\\n\\twidth: 49%;\\n}\\n\\n.tc-tiddler-frame .tc-tiddler-preview canvas.tc-edit-bitmapeditor {\\n\\tmax-width: 49%;\\n}\\n\\n.tc-edit-fields {\\n\\twidth: 100%;\\n}\\n\\n.tc-edit-fields.tc-edit-fields-small {\\n\\tmargin-top: 0;\\n\\tmargin-bottom: 0;\\n}\\n\\n.tc-edit-fields table, .tc-edit-fields tr, .tc-edit-fields td {\\n\\tborder: none;\\n\\tpadding: 4px;\\n}\\n\\n.tc-edit-fields > tbody > .tc-edit-field:nth-child(odd) {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-editor-fields-odd>>;\\n}\\n\\n.tc-edit-fields > tbody > .tc-edit-field:nth-child(even) {\\n\\tbackground-color: \u003C\u003Ccolour tiddler-editor-fields-even>>;\\n}\\n\\n.tc-edit-field-name {\\n\\ttext-align: right;\\n}\\n\\n.tc-edit-field-value input {\\n\\twidth: 100%;\\n}\\n\\n.tc-edit-field-remove {\\n}\\n\\n.tc-edit-field-remove svg {\\n\\theight: 1em;\\n\\twidth: 1em;\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-edit-field-add-name-wrapper input.tc-edit-texteditor {\\n\\twidth: auto;\\n}\\n\\n.tc-edit-field-add-name-wrapper {\\n\\tdisplay: inline-block;\\n}\\n\\n.tc-edit-field-add-value {\\n\\tdisplay: inline-block;\\n}\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\\t.tc-edit-field-add-value {\\n\\t\\twidth: 35%;\\n\\t}\\n\\n}\\n\\n.tc-edit-field-add-button {\\n\\tdisplay: inline-block;\\n\\twidth: 10%;\\n}\\n\\n\\n/*\\n** Tiddler editor dropzone\\n*/\\n\\n.tc-dropzone-editor {\\n\\tposition:relative;\\n}\\n\\n.tc-dropzone-editor.tc-dragover .tc-editor-toolbar::after{\\n\\tz-index: 10000;\\n\\ttop:0;\\n\\tleft:0;\\n\\tright:0;\\n\\theight: 100%;\\n\\tbackground: \u003C\u003Ccolour dropzone-background>>;\\n\\tcontent: \\\"\u003C\u003Clingo DropMessage>>\\\";\\n\\tpointer-events: none;\\n\\tposition: absolute;\\n\\tdisplay: flex;\\n\\talign-items: center;\\n\\tjustify-content: center;\\n\\tbackground-color: \u003C\u003Ccolor background>>;\\n\\tborder: 4px dashed \u003C\u003Ccolor modal-border>>;\\n\\tfont-weight: bold;\\n\\tfont-size: 150%;\\n\\topacity: 0.8;\\n\\tcolor: \u003C\u003Ccolor foreground>>;\\n}\\n\\n.tc-editor-importpopup {\\n\\twidth: 100%;\\n\\theight: 100%;\\n}\\n\\n.tc-editor-import {\\n\\tposition: absolute;\\n\\ttop: 50%;\\n\\tleft: 50%;\\n\\ttransform: translate(-50%, -50%);\\n\\tbackground: \u003C\u003Ccolor pre-background>>;\\n\\tbox-shadow: 2px 2px 10px \u003C\u003Ccolour foreground>>;\\n\\tpadding: 10px;\\n\\twidth: 96%;\\n\\tborder: 1px solid \u003C\u003Ccolor tiddler-controls-foreground>>;\\n\\ttext-align:center;\\n}\\n\\n.tc-editor-import img {\\n\\tmax-height: 500px;\\n}\\n\\n/*\\n** Storyview Classes\\n*/\\n\\n.tc-viewswitcher .tc-image-button {\\n\\tmargin-right: .3em;\\n}\\n\\n.tc-storyview-zoomin-tiddler {\\n\\tposition: absolute;\\n\\tdisplay: block;\\n\\twidth: 100%;\\n}\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\\t.tc-storyview-zoomin-tiddler {\\n\\t\\twidth: calc(100% - 84px);\\n\\t}\\n\\n}\\n\\n/*\\n** Dropdowns\\n*/\\n\\n.tc-btn-dropdown {\\n\\ttext-align: left;\\n}\\n\\n.tc-btn-dropdown svg, .tc-btn-dropdown img {\\n\\theight: 1em;\\n\\twidth: 1em;\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-drop-down-wrapper {\\n\\tposition: relative;\\n}\\n\\n.tc-drop-down {\\n\\tmin-width: 380px;\\n\\tborder: 1px solid \u003C\u003Ccolour dropdown-border>>;\\n\\tbackground-color: \u003C\u003Ccolour dropdown-background>>;\\n\\tpadding: 7px 0 7px 0;\\n\\tmargin: 4px 0 0 0;\\n\\twhite-space: nowrap;\\n\\ttext-shadow: none;\\n\\tline-height: 1.4;\\n}\\n\\n.tc-drop-down .tc-drop-down {\\n\\tmargin-left: 14px;\\n}\\n\\n.tc-drop-down button svg, .tc-drop-down a svg  {\\n\\tfill: \u003C\u003Ccolour foreground>>;\\n}\\n\\n.tc-drop-down button:disabled svg {\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-drop-down button.tc-btn-invisible:hover svg {\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-drop-down .tc-drop-down-info {\\n\\tpadding-left: 14px;\\n}\\n\\n.tc-drop-down p {\\n\\tpadding: 0 14px 0 14px;\\n}\\n\\n.tc-drop-down svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n}\\n\\n.tc-drop-down img {\\n\\twidth: 1em;\\n}\\n\\n.tc-drop-down a, .tc-drop-down button {\\n\\tdisplay: block;\\n\\tpadding: 0 14px 0 14px;\\n\\twidth: 100%;\\n\\ttext-align: left;\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n\\tline-height: 1.4;\\n}\\n\\n.tc-drop-down .tc-tab-set .tc-tab-buttons button {\\n\\tdisplay: inline-block;\\n\\twidth: auto;\\n\\tmargin-bottom: 0px;\\n\\tborder-bottom-left-radius: 0;\\n\\tborder-bottom-right-radius: 0;\\n}\\n\\n.tc-drop-down .tc-prompt {\\n\\tpadding: 0 14px;\\n}\\n\\n.tc-drop-down .tc-chooser {\\n\\tborder: none;\\n}\\n\\n.tc-drop-down .tc-chooser .tc-swatches-horiz {\\n\\tfont-size: 0.4em;\\n\\tpadding-left: 1.2em;\\n}\\n\\n.tc-drop-down .tc-file-input-wrapper {\\n\\twidth: 100%;\\n}\\n\\n.tc-drop-down .tc-file-input-wrapper button {\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n}\\n\\n.tc-drop-down a:hover, .tc-drop-down button:hover, .tc-drop-down .tc-file-input-wrapper:hover button {\\n\\tcolor: \u003C\u003Ccolour tiddler-link-background>>;\\n\\tbackground-color: \u003C\u003Ccolour tiddler-link-foreground>>;\\n\\ttext-decoration: none;\\n}\\n\\n.tc-drop-down .tc-tab-buttons button {\\n\\tbackground-color: \u003C\u003Ccolour dropdown-tab-background>>;\\n}\\n\\n.tc-drop-down .tc-tab-buttons button.tc-tab-selected {\\n\\tbackground-color: \u003C\u003Ccolour dropdown-tab-background-selected>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour dropdown-tab-background-selected>>;\\n}\\n\\n.tc-drop-down-bullet {\\n\\tdisplay: inline-block;\\n\\twidth: 0.5em;\\n}\\n\\n.tc-drop-down .tc-tab-contents a {\\n\\tpadding: 0 0.5em 0 0.5em;\\n}\\n\\n.tc-block-dropdown-wrapper {\\n\\tposition: relative;\\n}\\n\\n.tc-block-dropdown {\\n\\tposition: absolute;\\n\\tmin-width: 220px;\\n\\tborder: 1px solid \u003C\u003Ccolour dropdown-border>>;\\n\\tbackground-color: \u003C\u003Ccolour dropdown-background>>;\\n\\tpadding: 7px 0;\\n\\tmargin: 4px 0 0 0;\\n\\twhite-space: nowrap;\\n\\tz-index: 1000;\\n\\ttext-shadow: none;\\n}\\n\\n.tc-block-dropdown.tc-search-drop-down {\\n\\tmargin-left: -12px;\\n}\\n\\n.tc-block-dropdown a {\\n\\tdisplay: block;\\n\\tpadding: 4px 14px 4px 14px;\\n}\\n\\n.tc-block-dropdown.tc-search-drop-down a {\\n\\tdisplay: block;\\n\\tpadding: 0px 10px 0px 10px;\\n}\\n\\n.tc-drop-down .tc-dropdown-item-plain,\\n.tc-block-dropdown .tc-dropdown-item-plain {\\n\\tpadding: 4px 14px 4px 7px;\\n}\\n\\n.tc-drop-down .tc-dropdown-item,\\n.tc-block-dropdown .tc-dropdown-item {\\n\\tpadding: 4px 14px 4px 7px;\\n\\tcolor: \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-block-dropdown a.tc-tiddlylink:hover {\\n\\tcolor: \u003C\u003Ccolour tiddler-link-background>>;\\n\\tbackground-color: \u003C\u003Ccolour tiddler-link-foreground>>;\\n\\ttext-decoration: none;\\n}\\n\\n.tc-search-results {\\n\\tpadding: 0 7px 0 7px;\\n}\\n\\n.tc-image-chooser, .tc-colour-chooser {\\n\\twhite-space: normal;\\n}\\n\\n.tc-image-chooser a,\\n.tc-colour-chooser a {\\n\\tdisplay: inline-block;\\n\\tvertical-align: top;\\n\\ttext-align: center;\\n\\tposition: relative;\\n}\\n\\n.tc-image-chooser a {\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tpadding: 2px;\\n\\tmargin: 2px;\\n\\twidth: 4em;\\n\\theight: 4em;\\n}\\n\\n.tc-colour-chooser a {\\n\\tpadding: 3px;\\n\\twidth: 2em;\\n\\theight: 2em;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-image-chooser a:hover,\\n.tc-colour-chooser a:hover {\\n\\tbackground: \u003C\u003Ccolour primary>>;\\n\\tpadding: 0px;\\n\\tborder: 3px solid \u003C\u003Ccolour primary>>;\\n}\\n\\n.tc-image-chooser a svg,\\n.tc-image-chooser a img {\\n\\tdisplay: inline-block;\\n\\twidth: auto;\\n\\theight: auto;\\n\\tmax-width: 3.5em;\\n\\tmax-height: 3.5em;\\n\\tposition: absolute;\\n\\ttop: 0;\\n\\tbottom: 0;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tmargin: auto;\\n}\\n\\n/* Make search dropdown visible on small screens. issue #7003 */\\n@media (max-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\\t.tc-sidebar-search .tc-block-dropdown-wrapper {\\n\\t\\tposition: initial;\\n\\t}\\n\\n}\\n\\n/*\\n** Modals\\n*/\\n\\n.tc-modal-wrapper {\\n\\tposition: fixed;\\n\\toverflow: auto;\\n\\toverflow-y: scroll;\\n\\ttop: 0;\\n\\tright: 0;\\n\\tbottom: 0;\\n\\tleft: 0;\\n\\tz-index: 900;\\n}\\n\\n.tc-modal-backdrop {\\n\\tposition: fixed;\\n\\ttop: 0;\\n\\tright: 0;\\n\\tbottom: 0;\\n\\tleft: 0;\\n\\tz-index: 1000;\\n\\tbackground-color: \u003C\u003Ccolour modal-backdrop>>;\\n}\\n\\n.tc-modal {\\n\\tz-index: 1100;\\n\\tbackground-color: \u003C\u003Ccolour modal-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour modal-border>>;\\n}\\n\\n@media (max-width: 55em) {\\n\\t.tc-modal {\\n\\t\\tposition: fixed;\\n\\t\\ttop: 1em;\\n\\t\\tleft: 1em;\\n\\t\\tright: 1em;\\n\\t}\\n\\n\\t.tc-modal-body {\\n\\t\\toverflow-y: auto;\\n\\t\\tmax-height: 400px;\\n\\t\\tmax-height: 60vh;\\n\\t}\\n}\\n\\n@media (min-width: 55em) {\\n\\t.tc-modal {\\n\\t\\tposition: fixed;\\n\\t\\ttop: 2em;\\n\\t\\tleft: 25%;\\n\\t\\twidth: 50%;\\n\\t}\\n\\n\\t.tc-modal-body {\\n\\t\\toverflow-y: auto;\\n\\t\\tmax-height: 400px;\\n\\t\\tmax-height: 60vh;\\n\\t}\\n}\\n\\n.tc-modal-header {\\n\\tpadding: 9px 15px;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour modal-header-border>>;\\n}\\n\\n.tc-modal-header h3 {\\n\\tmargin: 0;\\n\\tline-height: 30px;\\n}\\n\\n.tc-modal-header img, .tc-modal-header svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n}\\n\\n.tc-modal-body {\\n\\tpadding: 15px;\\n}\\n\\n.tc-modal-footer {\\n\\tpadding: 14px 15px 15px;\\n\\tmargin-bottom: 0;\\n\\ttext-align: right;\\n\\tbackground-color: \u003C\u003Ccolour modal-footer-background>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour modal-footer-border>>;\\n}\\n\\n.tc-modal-prevent-scroll {\\n\\toverflow: hidden;\\n}\\n\\n/*\\n** Centered modals\\n*/\\n.tc-modal-centered .tc-modal {\\n\\twidth: auto;\\n\\ttop: 50%;\\n\\tleft: 50%;\\n\\ttransform: translate(-50%, -50%) !important;\\n}\\n\\n/*\\n** Notifications\\n*/\\n\\n.tc-notification {\\n\\tposition: fixed;\\n\\ttop: 14px;\\n\\tright: 42px;\\n\\tz-index: 1300;\\n\\tmax-width: 280px;\\n\\tpadding: 0 14px 0 14px;\\n\\tbackground-color: \u003C\u003Ccolour notification-background>>;\\n\\tborder: 1px solid \u003C\u003Ccolour notification-border>>;\\n}\\n\\n/*\\n** Tabs\\n*/\\n\\n.tc-tab-set.tc-vertical {\\n\\tdisplay: -webkit-flex;\\n\\tdisplay: flex;\\n}\\n\\n.tc-tab-buttons {\\n\\tfont-size: 0.85em;\\n\\tpadding-top: 1em;\\n\\tmargin-bottom: -2px;\\n}\\n\\n.tc-tab-buttons.tc-vertical  {\\n\\tz-index: 100;\\n\\tdisplay: block;\\n\\tpadding-top: 14px;\\n\\tvertical-align: top;\\n\\ttext-align: right;\\n\\tmargin-bottom: inherit;\\n\\tmargin-right: -1px;\\n\\tmax-width: 33%;\\n\\t-webkit-flex: 0 0 auto;\\n\\tflex: 0 0 auto;\\n}\\n\\n.tc-tab-buttons button.tc-tab-selected {\\n\\tcolor: \u003C\u003Ccolour tab-foreground-selected>>;\\n\\tbackground-color: \u003C\u003Ccolour tab-background-selected>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border-selected>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-border-selected>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour tab-border-selected>>;\\n}\\n\\n.tc-tab-buttons button {\\n\\tcolor: \u003C\u003Ccolour tab-foreground>>;\\n\\tpadding: 3px 5px 3px 5px;\\n\\tmargin-right: 0.3em;\\n\\tfont-weight: normal;\\n\\tborder: none;\\n\\tbackground: inherit;\\n\\tbackground-color: \u003C\u003Ccolour tab-background>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-top-left-radius: 2px;\\n\\tborder-top-right-radius: 2px;\\n\\tborder-bottom-left-radius: 0;\\n\\tborder-bottom-right-radius: 0;\\n}\\n\\n.tc-tab-buttons.tc-vertical button {\\n\\tdisplay: block;\\n\\twidth: 100%;\\n\\tmargin-top: 3px;\\n\\tmargin-right: 0;\\n\\ttext-align: right;\\n\\tbackground-color: \u003C\u003Ccolour tab-background>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-right: none;\\n\\tborder-top-left-radius: 2px;\\n\\tborder-bottom-left-radius: 2px;\\n\\tborder-top-right-radius: 0;\\n\\tborder-bottom-right-radius: 0;\\n}\\n\\n.tc-tab-buttons.tc-vertical button.tc-tab-selected {\\n\\tbackground-color: \u003C\u003Ccolour tab-background-selected>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour tab-background-selected>>;\\n}\\n\\n.tc-tab-divider {\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-divider>>;\\n}\\n\\n.tc-tab-divider.tc-vertical  {\\n\\tdisplay: none;\\n}\\n\\n.tc-tab-content {\\n\\tmargin-top: 14px;\\n}\\n\\n.tc-tab-content.tc-vertical  {\\n\\tdisplay: inline-block;\\n\\tvertical-align: top;\\n\\tpadding-top: 0;\\n\\tpadding-left: 14px;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\t-webkit-flex: 1 0 70%;\\n\\tflex: 1 0 70%;\\n\\toverflow: auto;\\n}\\n\\n.tc-sidebar-lists .tc-tab-buttons {\\n\\tmargin-bottom: -1px;\\n}\\n\\n.tc-sidebar-lists .tc-tab-buttons button.tc-tab-selected {\\n\\tbackground-color: \u003C\u003Ccolour sidebar-tab-background-selected>>;\\n\\tcolor: \u003C\u003Ccolour sidebar-tab-foreground-selected>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour sidebar-tab-border-selected>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour sidebar-tab-border-selected>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour sidebar-tab-border-selected>>;\\n}\\n\\n.tc-sidebar-lists .tc-tab-buttons button {\\n\\tbackground-color: \u003C\u003Ccolour sidebar-tab-background>>;\\n\\tcolor: \u003C\u003Ccolour sidebar-tab-foreground>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour sidebar-tab-border>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour sidebar-tab-border>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour sidebar-tab-border>>;\\n}\\n\\n.tc-sidebar-lists .tc-tab-divider {\\n\\tborder-top: 1px solid \u003C\u003Ccolour sidebar-tab-divider>>;\\n}\\n\\n.tc-more-sidebar > .tc-tab-set > .tc-tab-buttons > button {\\n\\tdisplay: block;\\n\\twidth: 100%;\\n\\tbackground-color: \u003C\u003Ccolour sidebar-tab-background>>;\\n\\tborder-top: none;\\n\\tborder-left: none;\\n\\tborder-bottom: none;\\n\\tborder-right: 1px solid #ccc;\\n\\tmargin-bottom: inherit;\\n}\\n\\n.tc-more-sidebar > .tc-tab-set > .tc-tab-buttons > button.tc-tab-selected {\\n\\tbackground-color: \u003C\u003Ccolour sidebar-tab-background-selected>>;\\n\\tborder: none;\\n}\\n\\n/*\\n** Manager\\n*/\\n\\n.tc-manager-wrapper {\\n\\t\\n}\\n\\n.tc-manager-controls {\\n\\t\\n}\\n\\n.tc-manager-control {\\n\\tmargin: 0.5em 0;\\n}\\n\\n.tc-manager-control select {\\n\\tmax-width: 100%;\\n}\\n\\n.tc-manager-list {\\n\\twidth: 100%;\\n\\tborder-top: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-right: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-manager-list-item {\\n\\n}\\n\\n.tc-manager-list-item-heading {\\n\\tdisplay: block;\\n\\twidth: 100%;\\n\\ttext-align: left;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tpadding: 3px;\\n}\\n\\n.tc-manager-list-item-heading-selected {\\n\\tfont-weight: bold;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tfill: \u003C\u003Ccolour background>>;\\n\\tbackground-color: \u003C\u003Ccolour foreground>>;\\n}\\n\\n.tc-manager-list-item-heading:hover {\\n\\tbackground: \u003C\u003Ccolour primary>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-manager-list-item-content {\\n\\tdisplay: flex;\\n}\\n\\n.tc-manager-list-item-content-sidebar {\\n\\tflex: 1 0;\\n\\tbackground: \u003C\u003Ccolour tiddler-editor-background>>;\\n\\tborder-right: 0.5em solid \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-bottom: 0.5em solid \u003C\u003Ccolour muted-foreground>>;\\n\\twhite-space: nowrap;\\n}\\n\\n.tc-manager-list-item-content-item-heading {\\n\\tdisplay: block;\\n\\twidth: 100%;\\n\\ttext-align: left;\\n\\tbackground: \u003C\u003Ccolour muted-foreground>>;\\n\\ttext-transform: uppercase;\\n\\tfont-size: 0.6em;\\n\\tfont-weight: bold;\\n\\tpadding: 0.5em 0 0.5em 0;\\n}\\n\\n.tc-manager-list-item-content-item-body {\\n\\tpadding: 0 0.5em 0 0.5em;\\n}\\n\\n.tc-manager-list-item-content-item-body > pre {\\n\\tmargin: 0.5em 0 0.5em 0;\\n\\tborder: none;\\n\\tbackground: inherit;\\n}\\n\\n.tc-manager-list-item-content-tiddler {\\n\\tflex: 3 1;\\n\\tborder-left: 0.5em solid \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-right: 0.5em solid \u003C\u003Ccolour muted-foreground>>;\\n\\tborder-bottom: 0.5em solid \u003C\u003Ccolour muted-foreground>>;\\n}\\n\\n.tc-manager-list-item-content-item-body > table {\\n\\tborder: none;\\n\\tpadding: 0;\\n\\tmargin: 0;\\n}\\n\\n.tc-manager-list-item-content-item-body > table td {\\n\\tborder: none;\\n}\\n\\n.tc-manager-icon-editor > button {\\n\\twidth: 100%;\\n}\\n\\n.tc-manager-icon-editor > button > svg,\\n.tc-manager-icon-editor > button > button {\\n\\twidth: 100%;\\n\\theight: auto;\\n}\\n\\n/*\\n** Import table\\n*/\\n\\n.tc-import-table {\\n\\twidth: 100%;\\n}\\n\\n.tc-import-table svg.tc-image-edit-button {\\n\\tmax-width: unset;\\n}\\n\\n.tc-import-table th:first-of-type {\\n\\twidth: 10%;\\n}\\n\\n.tc-import-table th:last-of-type {\\n\\twidth: 30%;\\n}\\n\\n.tc-import-table .tc-row-disabled {\\n\\tbackground: \u003C\u003Ccolour very-muted-foreground>>10;\\n\\topacity: 0.8;\\n}\\n\\n.tc-import-table .tc-row-warning {\\n\\tbackground: \u003C\u003Ccolour diff-delete-background>>50;\\n}\\n\\n/*\\n** Alerts\\n*/\\n\\n.tc-alerts {\\n\\tposition: fixed;\\n\\ttop: 28px;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tmax-width: 50%;\\n\\tz-index: 20000;\\n}\\n\\n.tc-alert {\\n\\tposition: relative;\\n\\tmargin: 14px;\\n\\tpadding: 7px;\\n\\tborder: 1px solid \u003C\u003Ccolour alert-border>>;\\n\\tbackground-color: \u003C\u003Ccolour alert-background>>;\\n}\\n\\n.tc-alert-toolbar {\\n\\tposition: absolute;\\n\\ttop: 7px;\\n\\tright: 7px;\\n\\tline-height: 0;\\n}\\n\\n.tc-alert-toolbar svg {\\n\\tfill: \u003C\u003Ccolour alert-muted-foreground>>;\\n}\\n\\n.tc-alert-subtitle {\\n\\tcolor: \u003C\u003Ccolour alert-muted-foreground>>;\\n\\tfont-weight: bold;\\n\\tfont-size: 0.8em;\\n\\tmargin-bottom: 0.5em;\\n}\\n\\n.tc-alert-body > p {\\n\\tmargin: 0;\\n}\\n\\n.tc-alert-highlight {\\n\\tcolor: \u003C\u003Ccolour alert-highlight>>;\\n}\\n\\n@media (min-width: \u003C\u003Csidebarbreakpoint>>) {\\n\\n\\t.tc-static-alert {\\n\\t\\tposition: relative;\\n\\t}\\n\\n\\t.tc-static-alert-inner {\\n\\t\\tposition: absolute;\\n\\t\\tz-index: 100;\\n\\t}\\n\\n}\\n\\n.tc-static-alert-inner {\\n\\tpadding: 0 2px 2px 42px;\\n\\tcolor: \u003C\u003Ccolour static-alert-foreground>>;\\n}\\n\\n/*\\n** Floating drafts list\\n*/\\n\\n.tc-drafts-list {\\n\\tz-index: 2000;\\n\\tposition: fixed;\\n\\tfont-size: 0.8em;\\n\\tleft: 0;\\n\\tbottom: 0;\\n}\\n\\n.tc-drafts-list a {\\n\\tmargin: 0 0.5em;\\n\\tpadding: 4px 4px;\\n\\tborder-top-left-radius: 4px;\\n\\tborder-top-right-radius: 4px;\\n\\tborder: 1px solid \u003C\u003Ccolour background>>;\\n\\tborder-bottom: none;\\n\\tbackground: \u003C\u003Ccolour dirty-indicator>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-drafts-list a:hover {\\n\\ttext-decoration: none;\\n\\tbackground: \u003C\u003Ccolour foreground>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-drafts-list a svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n\\tvertical-align: text-bottom;\\n}\\n\\n/*\\n** Control panel\\n*/\\n\\n.tc-control-panel td {\\n\\tpadding: 4px;\\n}\\n\\n.tc-control-panel table, .tc-control-panel table input, .tc-control-panel table textarea {\\n\\twidth: 100%;\\n}\\n\\n.tc-plugin-info {\\n\\tdisplay: flex;\\n\\ttext-shadow: none;\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tfill: \u003C\u003Ccolour muted-foreground>>;\\n\\tbackground-color: \u003C\u003Ccolour background>>;\\n\\tmargin: 0.5em 0 0.5em 0;\\n\\tpadding: 4px;\\n\\talign-items: center;\\n}\\n\\n.tc-sidebar-lists a.tc-tiddlylink.tc-plugin-info {\\n\\tcolor: \u003C\u003Ccolour tiddler-link-foreground>>;\\n}\\n\\n\\n.tc-plugin-info-sub-plugins .tc-plugin-info {\\n\\tmargin: 0.5em;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-plugin-info-sub-plugin-indicator {\\n\\tmargin: -16px 1em 0 2em;\\n}\\n\\n.tc-plugin-info-sub-plugin-indicator button {\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tbackground: \u003C\u003Ccolour foreground>>;\\n\\tborder-radius: 8px;\\n\\tpadding: 2px 7px;\\n\\tfont-size: 0.75em;\\n}\\n\\n.tc-plugin-info-sub-plugins .tc-plugin-info-dropdown {\\n\\tmargin-left: 1em;\\n\\tmargin-right: 1em;\\n}\\n\\n.tc-plugin-info-disabled {\\n\\tbackground: -webkit-repeating-linear-gradient(45deg, #ff0, #ff0 10px, #eee 10px, #eee 20px);\\n\\tbackground: repeating-linear-gradient(45deg, #ff0, #ff0 10px, #eee 10px, #eee 20px);\\n}\\n\\n.tc-plugin-info-disabled:hover {\\n\\tbackground: -webkit-repeating-linear-gradient(45deg, #aa0, #aa0 10px, #888 10px, #888 20px);\\n\\tbackground: repeating-linear-gradient(45deg, #aa0, #aa0 10px, #888 10px, #888 20px);\\n}\\n\\na.tc-tiddlylink.tc-plugin-info:hover {\\n\\ttext-decoration: none;\\n\\tbackground-color: \u003C\u003Ccolour primary>>;\\n\\tcolor: \u003C\u003Ccolour background>>;\\n\\tfill: \u003C\u003Ccolour foreground>>;\\n}\\n\\na.tc-tiddlylink.tc-plugin-info:hover > .tc-plugin-info-chunk > svg {\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-plugin-info-chunk {\\n\\tmargin: 2px;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-toggle {\\n\\tflex-grow: 0;\\n\\tflex-shrink: 0;\\n\\tline-height: 1;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-icon {\\n\\tflex-grow: 0;\\n\\tflex-shrink: 0;\\n\\tline-height: 1;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-description {\\n\\tflex-grow: 1;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-buttons {\\n\\tfont-size: 0.8em;\\n\\tline-height: 1.2;\\n\\tflex-grow: 0;\\n\\tflex-shrink: 0;\\n\\ttext-align: right;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-description h1 {\\n\\tfont-size: 1em;\\n\\tline-height: 1.2;\\n\\tmargin: 2px 0 2px 0;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-description h2 {\\n\\tfont-size: 0.8em;\\n\\tline-height: 1.2;\\n\\tmargin: 2px 0 2px 0;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-description div {\\n\\tfont-size: 0.7em;\\n\\tline-height: 1.2;\\n\\tmargin: 2px 0 2px 0;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-toggle img, .tc-plugin-info-chunk.tc-plugin-info-toggle svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n}\\n\\n.tc-plugin-info-chunk.tc-plugin-info-icon img, .tc-plugin-info-chunk.tc-plugin-info-icon svg {\\n\\twidth: 2em;\\n\\theight: 2em;\\n}\\n\\n.tc-plugin-info-dropdown {\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n\\tmargin-top: -8px;\\n}\\n\\n.tc-plugin-info-dropdown-message {\\n\\tbackground: \u003C\u003Ccolour message-background>>;\\n\\tpadding: 0.5em 1em 0.5em 1em;\\n\\tfont-weight: bold;\\n\\tfont-size: 0.8em;\\n}\\n\\n.tc-plugin-info-dropdown-body {\\n\\tpadding: 1em 1em 0 1em;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n}\\n\\n.tc-plugin-info-sub-plugins {\\n\\tpadding: 0.5em;\\n\\tmargin: 0 1em 1em 1em;\\n\\tbackground: \u003C\u003Ccolour notification-background>>;\\n}\\n\\n.tc-install-plugin {\\n\\tfont-weight: bold;\\n\\tbackground: green;\\n\\tcolor: white;\\n\\tfill: white;\\n\\tborder-radius: 4px;\\n\\tpadding: 3px;\\n}\\n\\n.tc-install-plugin.tc-reinstall-downgrade {\\n\\tbackground: red;\\n}\\n\\n.tc-install-plugin.tc-reinstall {\\n\\tbackground: blue;\\n}\\n\\n.tc-install-plugin.tc-reinstall-upgrade {\\n\\tbackground: orange;\\n}\\n\\n.tc-check-list {\\n\\tline-height: 2em;\\n}\\n\\n.tc-check-list .tc-image-button {\\n\\theight: 1.5em;\\n}\\n\\n/*\\n** Message boxes\\n*/\\n\\n.tc-message-box {\\n\\tborder: 1px solid \u003C\u003Ccolour message-border>>;\\n\\tbackground: \u003C\u003Ccolour message-background>>;\\n\\tpadding: 0px 21px 0px 21px;\\n\\tfont-size: 12px;\\n\\tline-height: 18px;\\n\\tcolor: \u003C\u003Ccolour message-foreground>>;\\n}\\n\\n.tc-message-box svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n\\tvertical-align: text-bottom;\\n}\\n\\n/*\\n** Pictures\\n*/\\n\\n.tc-bordered-image {\\n\\tborder: 1px solid \u003C\u003Ccolour muted-foreground>>;\\n\\tpadding: 5px;\\n\\tmargin: 5px;\\n}\\n\\n/*\\n** Floats\\n*/\\n\\n.tc-float-right {\\n\\tfloat: right;\\n}\\n\\n/*\\n** Chooser\\n*/\\n\\n.tc-chooser {\\n\\tborder-right: 1px solid \u003C\u003Ccolour table-header-background>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour table-header-background>>;\\n}\\n\\n\\n.tc-chooser-item {\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour table-header-background>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour table-header-background>>;\\n\\tpadding: 2px 4px 2px 14px;\\n}\\n\\n.tc-drop-down .tc-chooser-item {\\n\\tpadding: 2px;\\n}\\n\\n.tc-chosen,\\n.tc-chooser-item:hover {\\n\\tbackground-color: \u003C\u003Ccolour table-header-background>>;\\n\\tborder-color: \u003C\u003Ccolour table-footer-background>>;\\n}\\n\\n.tc-chosen .tc-tiddlylink {\\n\\tcursor:default;\\n}\\n\\n.tc-chooser-item .tc-tiddlylink {\\n\\tdisplay: block;\\n\\ttext-decoration: none;\\n\\tbackground-color: transparent;\\n}\\n\\n.tc-chooser-item:hover .tc-tiddlylink:hover {\\n\\ttext-decoration: none;\\n}\\n\\n.tc-drop-down .tc-chosen .tc-tiddlylink,\\n.tc-drop-down .tc-chooser-item .tc-tiddlylink:hover {\\n\\tcolor: \u003C\u003Ccolour foreground>>;\\n}\\n\\n.tc-chosen > .tc-tiddlylink:before {\\n\\tmargin-left: -10px;\\n\\tposition: relative;\\n\\tcontent: \\\"» \\\";\\n}\\n\\n.tc-chooser-item svg,\\n.tc-chooser-item img{\\n\\twidth: 1em;\\n\\theight: 1em;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-language-chooser .tc-image-button img {\\n\\twidth: 2em;\\n\\tvertical-align: -0.15em;\\n}\\n\\n/*\\n** Palette swatches\\n*/\\n\\n.tc-swatches-horiz {\\n}\\n\\n.tc-swatches-horiz .tc-swatch {\\n\\tdisplay: inline-block;\\n}\\n\\n.tc-swatch {\\n\\twidth: 2em;\\n\\theight: 2em;\\n\\tmargin: 0.4em;\\n\\tborder: 1px solid #888;\\n}\\n\\ninput.tc-palette-manager-colour-input {\\n\\twidth: 100%;\\n\\tpadding: 0;\\n}\\n\\n/*\\n** Table of contents\\n*/\\n\\n.tc-sidebar-lists .tc-table-of-contents {\\n\\twhite-space: nowrap;\\n}\\n\\n.tc-table-of-contents button {\\n\\tcolor: \u003C\u003Ccolour sidebar-foreground>>;\\n}\\n\\n.tc-table-of-contents svg {\\n\\twidth: 0.7em;\\n\\theight: 0.7em;\\n\\tvertical-align: middle;\\n\\tfill: \u003C\u003Ccolour sidebar-foreground>>;\\n}\\n\\n.tc-table-of-contents ol {\\n\\tlist-style-type: none;\\n\\tpadding-left: 0;\\n}\\n\\n.tc-table-of-contents ol ol {\\n\\tpadding-left: 1em;\\n}\\n\\n.tc-table-of-contents li {\\n\\tfont-size: 1.0em;\\n\\tfont-weight: bold;\\n}\\n\\n.tc-table-of-contents li a {\\n\\tfont-weight: bold;\\n}\\n\\n.tc-table-of-contents li li {\\n\\tfont-size: 0.95em;\\n\\tfont-weight: normal;\\n\\tline-height: 1.4;\\n}\\n\\n.tc-table-of-contents li li a {\\n\\tfont-weight: normal;\\n}\\n\\n.tc-table-of-contents li li li {\\n\\tfont-size: 0.95em;\\n\\tfont-weight: normal;\\n\\tline-height: 1.5;\\n}\\n\\n.tc-table-of-contents li li li li {\\n\\tfont-size: 0.95em;\\n\\tfont-weight: normal;\\n}\\n\\n.tc-tabbed-table-of-contents {\\n\\tdisplay: -webkit-flex;\\n\\tdisplay: flex;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents {\\n\\tz-index: 100;\\n\\tdisplay: inline-block;\\n\\tpadding-left: 1em;\\n\\tmax-width: 50%;\\n\\t-webkit-flex: 0 0 auto;\\n\\tflex: 0 0 auto;\\n\\tbackground: \u003C\u003Ccolour tab-background>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tab-border>>;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item > a,\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item-selected > a {\\n\\tdisplay: block;\\n\\tpadding: 0.12em 1em 0.12em 0.25em;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item > a {\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-background>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-background>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tab-background>>;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item > a:hover {\\n\\ttext-decoration: none;\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tbackground: \u003C\u003Ccolour tab-border>>;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item-selected > a {\\n\\tborder-top: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-left: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tborder-bottom: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n\\tmargin-right: -1px;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-table-of-contents .toc-item-selected > a:hover {\\n\\ttext-decoration: none;\\n}\\n\\n.tc-tabbed-table-of-contents .tc-tabbed-table-of-contents-content {\\n\\tdisplay: inline-block;\\n\\tvertical-align: top;\\n\\tpadding-left: 1.5em;\\n\\tpadding-right: 1.5em;\\n\\tborder: 1px solid \u003C\u003Ccolour tab-border>>;\\n\\t-webkit-flex: 1 0 50%;\\n\\tflex: 1 0 50%;\\n}\\n\\n/*\\n** Dirty indicator\\n*/\\n\\nhtml body.tc-dirty span.tc-dirty-indicator, html body.tc-dirty span.tc-dirty-indicator svg {\\n\\tfill: \u003C\u003Ccolour dirty-indicator>>;\\n\\tcolor: \u003C\u003Ccolour dirty-indicator>>;\\n}\\n\\n/*\\n** File inputs\\n*/\\n\\n.tc-file-input-wrapper {\\n\\tposition: relative;\\n\\toverflow: hidden;\\n\\tdisplay: inline-block;\\n\\tvertical-align: middle;\\n}\\n\\n.tc-file-input-wrapper input[type=file] {\\n\\tposition: absolute;\\n\\ttop: 0;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tbottom: 0;\\n\\tfont-size: 999px;\\n\\tmax-width: 100%;\\n\\tmax-height: 100%;\\n\\tfilter: alpha(opacity=0);\\n\\topacity: 0;\\n\\toutline: none;\\n\\tbackground: white;\\n\\tcursor: pointer;\\n\\tdisplay: inline-block;\\n}\\n\\n::-webkit-file-upload-button {\\n\\tcursor:pointer;\\n}\\n\\n/*\\n** Thumbnail macros\\n*/\\n\\n.tc-thumbnail-wrapper {\\n\\tposition: relative;\\n\\tdisplay: inline-block;\\n\\tmargin: 6px;\\n\\tvertical-align: top;\\n}\\n\\n.tc-thumbnail-right-wrapper {\\n\\tfloat:right;\\n\\tmargin: 0.5em 0 0.5em 0.5em;\\n}\\n\\n.tc-thumbnail-image {\\n\\ttext-align: center;\\n\\toverflow: hidden;\\n\\tborder-radius: 3px;\\n}\\n\\n.tc-thumbnail-image svg,\\n.tc-thumbnail-image img {\\n\\tfilter: alpha(opacity=1);\\n\\topacity: 1;\\n\\tmin-width: 100%;\\n\\tmin-height: 100%;\\n\\tmax-width: 100%;\\n}\\n\\n.tc-thumbnail-wrapper:hover .tc-thumbnail-image svg,\\n.tc-thumbnail-wrapper:hover .tc-thumbnail-image img {\\n\\tfilter: alpha(opacity=0.8);\\n\\topacity: 0.8;\\n}\\n\\n.tc-thumbnail-background {\\n\\tposition: absolute;\\n\\tborder-radius: 3px;\\n}\\n\\n.tc-thumbnail-icon svg,\\n.tc-thumbnail-icon img {\\n\\twidth: 3em;\\n\\theight: 3em;\\n\\t\u003C\u003Cfilter \\\"drop-shadow(2px 2px 4px rgba(0,0,0,0.3))\\\">>\\n}\\n\\n.tc-thumbnail-wrapper:hover .tc-thumbnail-icon svg,\\n.tc-thumbnail-wrapper:hover .tc-thumbnail-icon img {\\n\\tfill: #fff;\\n\\t\u003C\u003Cfilter \\\"drop-shadow(3px 3px 4px rgba(0,0,0,0.6))\\\">>\\n}\\n\\n.tc-thumbnail-icon {\\n\\tposition: absolute;\\n\\ttop: 0;\\n\\tleft: 0;\\n\\tright: 0;\\n\\tbottom: 0;\\n\\tdisplay: -webkit-flex;\\n\\t-webkit-align-items: center;\\n\\t-webkit-justify-content: center;\\n\\tdisplay: flex;\\n\\talign-items: center;\\n\\tjustify-content: center;\\n}\\n\\n.tc-thumbnail-caption {\\n\\tposition: absolute;\\n\\tbackground-color: #777;\\n\\tcolor: #fff;\\n\\ttext-align: center;\\n\\tbottom: 0;\\n\\twidth: 100%;\\n\\tfilter: alpha(opacity=0.9);\\n\\topacity: 0.9;\\n\\tline-height: 1.4;\\n\\tborder-bottom-left-radius: 3px;\\n\\tborder-bottom-right-radius: 3px;\\n}\\n\\n.tc-thumbnail-wrapper:hover .tc-thumbnail-caption {\\n\\tfilter: alpha(opacity=1);\\n\\topacity: 1;\\n}\\n\\n/*\\n** Diffs\\n*/\\n\\n.tc-diff-equal {\\n\\tbackground-color: \u003C\u003Ccolour diff-equal-background>>;\\n\\tcolor: \u003C\u003Ccolour diff-equal-foreground>>;\\n}\\n\\n.tc-diff-insert {\\n\\tbackground-color: \u003C\u003Ccolour diff-insert-background>>;\\n\\tcolor: \u003C\u003Ccolour diff-insert-foreground>>;\\n}\\n\\n.tc-diff-delete {\\n\\tbackground-color: \u003C\u003Ccolour diff-delete-background>>;\\n\\tcolor: \u003C\u003Ccolour diff-delete-foreground>>;\\n}\\n\\n.tc-diff-invisible {\\n\\tbackground-color: \u003C\u003Ccolour diff-invisible-background>>;\\n\\tcolor: \u003C\u003Ccolour diff-invisible-foreground>>;\\n}\\n\\n.tc-diff-tiddlers th {\\n\\ttext-align: right;\\n\\tbackground: \u003C\u003Ccolour background>>;\\n\\tfont-weight: normal;\\n\\tfont-style: italic;\\n}\\n\\n.tc-diff-tiddlers pre {\\n\\tmargin: 0;\\n\\tpadding: 0;\\n\\tborder: none;\\n\\tbackground: none;\\n}\\n\\n/*\\n** Errors\\n*/\\n\\n.tc-error {\\n\\tbackground: #f00;\\n\\tcolor: #fff;\\n}\\n\\n/*\\n** Tree macro\\n*/\\n\\n.tc-tree div {\\n\\tpadding-left: 14px;\\n}\\n\\n.tc-tree ol {\\n\\tlist-style-type: none;\\n\\tpadding-left: 0;\\n\\tmargin-top: 0;\\n}\\n\\n.tc-tree ol ol {\\n\\tpadding-left: 1em;\\n}\\n\\n.tc-tree button {\\n\\tcolor: #acacac;\\n}\\n\\n.tc-tree svg {\\n\\tfill: #acacac;\\n}\\n\\n.tc-tree span svg {\\n\\twidth: 1em;\\n\\theight: 1em;\\n\\tvertical-align: baseline;\\n}\\n\\n.tc-tree li span {\\n\\tcolor: lightgray;\\n}\\n\\nselect {\\n\\tcolor: \u003C\u003Ccolour select-tag-foreground>>;\\n\\tbackground: \u003C\u003Ccolour select-tag-background>>;\\n}\\n\\n/*\\n** Utility classes for SVG icons\\n*/\\n\\n.tc-fill-background {\\n\\tfill: \u003C\u003Ccolour background>>;\\n}\\n\\n/*\\n** Flexbox utility classes\\n*/\\n\\n.tc-flex {\\n\\tdisplay: -webkit-flex;\\n\\tdisplay: flex;\\n}\\n\\n.tc-flex-column {\\n\\tflex-direction: column;\\n}\\n\\n.tc-flex-row {\\n\\tflex-direction: row;\\n}\\n\\n.tc-flex-grow-1 {\\n\\tflex-grow: 1;\\n}\\n\\n.tc-flex-grow-2 {\\n\\tflex-grow: 2;\\n}\\n\\n/*\\n** Other utility classes\\n*/\\n\\n.tc-tiny-gap {\\n\\tmargin-left: .25em;\\n\\tmargin-right: .25em;\\n}\\n\\n.tc-tiny-gap-left {\\n\\tmargin-left: .25em;\\n}\\n\\n.tc-tiny-gap-right {\\n\\tmargin-right: .25em;\\n}\\n\\n.tc-small-gap {\\n\\tmargin-left: .5em;\\n\\tmargin-right: .5em;\\n}\\n\\n.tc-small-gap-left {\\n\\tmargin-left: .5em;\\n}\\n\\n.tc-small-gap-right {\\n\\tmargin-right: .5em;\\n}\\n\\n.tc-big-gap {\\n\\tmargin-left: 1em;\\n\\tmargin-right: 1em;\\n}\\n\\n.tc-big-gap-left {\\n\\tmargin-left: 1em;\\n}\\n\\n.tc-big-gap-right {\\n\\tmargin-right: 1em;\\n}\\n\\n.tc-word-break {\\n\\tword-break: break-all;\\n}\\n\"},\"$:/themes/tiddlywiki/vanilla/metrics/bodyfontsize\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/bodyfontsize\",\"text\":\"15px\"},\"$:/themes/tiddlywiki/vanilla/metrics/bodylineheight\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/bodylineheight\",\"text\":\"22px\"},\"$:/themes/tiddlywiki/vanilla/metrics/fontsize\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/fontsize\",\"text\":\"14px\"},\"$:/themes/tiddlywiki/vanilla/metrics/lineheight\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/lineheight\",\"text\":\"20px\"},\"$:/themes/tiddlywiki/vanilla/metrics/storyleft\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/storyleft\",\"text\":\"0px\"},\"$:/themes/tiddlywiki/vanilla/metrics/storytop\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/storytop\",\"text\":\"0px\"},\"$:/themes/tiddlywiki/vanilla/metrics/storyright\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/storyright\",\"text\":\"770px\"},\"$:/themes/tiddlywiki/vanilla/metrics/storywidth\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/storywidth\",\"text\":\"770px\"},\"$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/tiddlerwidth\",\"text\":\"686px\"},\"$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/sidebarbreakpoint\",\"text\":\"960px\"},\"$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth\":{\"title\":\"$:/themes/tiddlywiki/vanilla/metrics/sidebarwidth\",\"text\":\"350px\"},\"$:/themes/tiddlywiki/vanilla/options/stickytitles\":{\"title\":\"$:/themes/tiddlywiki/vanilla/options/stickytitles\",\"text\":\"no\"},\"$:/themes/tiddlywiki/vanilla/options/sidebarlayout\":{\"title\":\"$:/themes/tiddlywiki/vanilla/options/sidebarlayout\",\"text\":\"fixed-fluid\"},\"$:/themes/tiddlywiki/vanilla/options/codewrapping\":{\"title\":\"$:/themes/tiddlywiki/vanilla/options/codewrapping\",\"text\":\"pre-wrap\"},\"$:/themes/tiddlywiki/vanilla/reset\":{\"title\":\"$:/themes/tiddlywiki/vanilla/reset\",\"type\":\"text/css\",\"text\":\"/*! modern-normalize v1.0.0 | MIT License | https://github.com/sindresorhus/modern-normalize */\\n\\n/*\\nDocument\\n========\\n*/\\n\\n/**\\nUse a better box model (opinionated).\\n*/\\n\\n*,\\n*::before,\\n*::after {\\n  box-sizing: border-box;\\n}\\n\\n/**\\nUse a more readable tab size (opinionated).\\n*/\\n\\n:root {\\n  -moz-tab-size: 4;\\n  tab-size: 4;\\n}\\n\\n/**\\n1. Correct the line height in all browsers.\\n2. Prevent adjustments of font size after orientation changes in iOS.\\n*/\\n\\nhtml {\\n  line-height: 1.15; /* 1 */\\n  -webkit-text-size-adjust: 100%; /* 2 */\\n}\\n\\n/*\\nSections\\n========\\n*/\\n\\n/**\\nRemove the margin in all browsers.\\n*/\\n\\nbody {\\n  margin: 0;\\n}\\n\\n/**\\nImprove consistency of default fonts in all browsers. (https://github.com/sindresorhus/modern-normalize/issues/3)\\n*/\\n\\nbody {\\n  font-family:\\n    system-ui,\\n    -apple-system, /* Firefox supports this but not yet `system-ui` */\\n    'Segoe UI',\\n    Roboto,\\n    Helvetica,\\n    Arial,\\n    sans-serif,\\n    'Apple Color Emoji',\\n    'Segoe UI Emoji';\\n}\\n\\n/*\\nGrouping content\\n================\\n*/\\n\\n/**\\n1. Add the correct height in Firefox.\\n2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)\\n*/\\n\\nhr {\\n  height: 0; /* 1 */\\n  color: inherit; /* 2 */\\n}\\n\\n/*\\nText-level semantics\\n====================\\n*/\\n\\n/**\\nAdd the correct text decoration in Chrome, Edge, and Safari.\\n*/\\n\\nabbr[title] {\\n  text-decoration: underline dotted;\\n}\\n\\n/**\\nAdd the correct font weight in Edge and Safari.\\n*/\\n\\nb,\\nstrong {\\n  font-weight: bolder;\\n}\\n\\n/**\\n1. Improve consistency of default fonts in all browsers. (https://github.com/sindresorhus/modern-normalize/issues/3)\\n2. Correct the odd 'em' font sizing in all browsers.\\n*/\\n\\ncode,\\nkbd,\\nsamp,\\npre {\\n  font-family:\\n    ui-monospace,\\n    SFMono-Regular,\\n    Consolas,\\n    'Liberation Mono',\\n    Menlo,\\n    monospace; /* 1 */\\n  font-size: 1em; /* 2 */\\n}\\n\\n/**\\nAdd the correct font size in all browsers.\\n*/\\n\\nsmall {\\n  font-size: 80%;\\n}\\n\\n/**\\nPrevent 'sub' and 'sup' elements from affecting the line height in all browsers.\\n*/\\n\\nsub,\\nsup {\\n  font-size: 75%;\\n  line-height: 0;\\n  position: relative;\\n  vertical-align: baseline;\\n}\\n\\nsub {\\n  bottom: -0.25em;\\n}\\n\\nsup {\\n  top: -0.5em;\\n}\\n\\n/*\\nTabular data\\n============\\n*/\\n\\n/**\\n1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)\\n2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)\\n*/\\n\\ntable {\\n  text-indent: 0; /* 1 */\\n  border-color: inherit; /* 2 */\\n}\\n\\n/*\\nForms\\n=====\\n*/\\n\\n/**\\n1. Change the font styles in all browsers.\\n2. Remove the margin in Firefox and Safari.\\n*/\\n\\nbutton,\\ninput,\\noptgroup,\\nselect,\\ntextarea {\\n  font-family: inherit; /* 1 */\\n  font-size: 100%; /* 1 */\\n  line-height: 1.15; /* 1 */\\n  margin: 0; /* 2 */\\n}\\n\\n/**\\nRemove the inheritance of text transform in Edge and Firefox.\\n1. Remove the inheritance of text transform in Firefox.\\n*/\\n\\nbutton,\\nselect { /* 1 */\\n  text-transform: none;\\n}\\n\\n/**\\nCorrect the inability to style clickable types in iOS and Safari.\\n*/\\n\\nbutton,\\n[type='button'],\\n[type='reset'],\\n[type='submit'] {\\n  -webkit-appearance: button;\\n}\\n\\n/**\\nRemove the inner border and padding in Firefox.\\n*/\\n\\n::-moz-focus-inner {\\n  border-style: none;\\n  padding: 0;\\n}\\n\\n/**\\nRestore the focus styles unset by the previous rule.\\n*/\\n\\n:-moz-focusring {\\n  outline: 1px dotted ButtonText;\\n}\\n\\n/**\\nRemove the additional ':invalid' styles in Firefox.\\nSee: https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737\\n*/\\n\\n:-moz-ui-invalid {\\n  box-shadow: none;\\n}\\n\\n/**\\nRemove the padding so developers are not caught out when they zero out 'fieldset' elements in all browsers.\\n*/\\n\\nlegend {\\n  padding: 0;\\n}\\n\\n/**\\nAdd the correct vertical alignment in Chrome and Firefox.\\n*/\\n\\nprogress {\\n  vertical-align: baseline;\\n}\\n\\n/**\\nCorrect the cursor style of increment and decrement buttons in Safari.\\n*/\\n\\n::-webkit-inner-spin-button,\\n::-webkit-outer-spin-button {\\n  height: auto;\\n}\\n\\n/**\\n1. Correct the odd appearance in Chrome and Safari.\\n2. Correct the outline style in Safari.\\n*/\\n\\n[type='search'] {\\n  -webkit-appearance: textfield; /* 1 */\\n  outline-offset: -2px; /* 2 */\\n}\\n\\n/**\\nRemove the inner padding in Chrome and Safari on macOS.\\n*/\\n\\n::-webkit-search-decoration {\\n  -webkit-appearance: none;\\n}\\n\\n/**\\n1. Correct the inability to style clickable types in iOS and Safari.\\n2. Change font properties to 'inherit' in Safari.\\n*/\\n\\n::-webkit-file-upload-button {\\n  -webkit-appearance: button; /* 1 */\\n  font: inherit; /* 2 */\\n}\\n\\n/*\\nInteractive\\n===========\\n*/\\n\\n/*\\nAdd the correct display in Chrome and Safari.\\n*/\\n\\nsummary {\\n  display: list-item;\\n}\\n\"},\"$:/themes/tiddlywiki/vanilla/settings/fontfamily\":{\"title\":\"$:/themes/tiddlywiki/vanilla/settings/fontfamily\",\"text\":\"-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji;\"},\"$:/themes/tiddlywiki/vanilla/settings/codefontfamily\":{\"title\":\"$:/themes/tiddlywiki/vanilla/settings/codefontfamily\",\"text\":\"\\\"SFMono-Regular\\\",Consolas,\\\"Liberation Mono\\\",Menlo,Courier,monospace\"},\"$:/themes/tiddlywiki/vanilla/settings/backgroundimageattachment\":{\"title\":\"$:/themes/tiddlywiki/vanilla/settings/backgroundimageattachment\",\"text\":\"fixed\"},\"$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize\":{\"title\":\"$:/themes/tiddlywiki/vanilla/settings/backgroundimagesize\",\"text\":\"auto\"},\"$:/themes/tiddlywiki/vanilla/sticky\":{\"title\":\"$:/themes/tiddlywiki/vanilla/sticky\",\"code-body\":\"yes\",\"text\":\"\u003C$reveal state=\\\"$:/themes/tiddlywiki/vanilla/options/stickytitles\\\" type=\\\"match\\\" text=\\\"yes\\\">\\n``\\n.tc-tiddler-title {\\n\\tposition: -webkit-sticky;\\n\\tposition: -moz-sticky;\\n\\tposition: -o-sticky;\\n\\tposition: -ms-sticky;\\n\\tposition: sticky;\\n\\ttop: 0px;\\n\\tbackground: ``\u003C\u003Ccolour tiddler-background>>``;\\n\\tz-index: 500;\\n}\\n\\n``\\n\u003C$list filter=\\\"[range[100]]\\\">\\n`.tc-story-river .tc-tiddler-frame:nth-child(100n+`\u003C$text text=\u003C\u003CcurrentTiddler>>/>`) {\\nz-index: `\u003C$text text={{{ [[200]subtract\u003CcurrentTiddler>] }}}/>`;\\n}\\n`\\n\u003C/$list>\\n\u003C/$reveal>\\n\"}}}"}
]</script><div id="storeArea" style="display:none;"></div>
<!--~~ Library modules ~~-->
<div id="libraryModules" style="display:none;">
<script data-tiddler-library="yes" data-tiddler-title="$:/library/sjcl.js" data-tiddler-type="application/javascript" type="text/javascript">"use strict";var sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec:{},exception:{corrupt:function(a){this.toString=function(){return"CORRUPT: "+this.message};this.message=a},invalid:function(a){this.toString=function(){return"INVALID: "+this.message};this.message=a},bug:function(a){this.toString=function(){return"BUG: "+this.message};this.message=a},notReady:function(a){this.toString=function(){return"NOT READY: "+this.message};this.message=a}}};
sjcl.cipher.aes=function(a){this.s[0][0][0]||this.O();var b,c,d,e,f=this.s[0][4],g=this.s[1];b=a.length;var h=1;if(4!==b&&6!==b&&8!==b)throw new sjcl.exception.invalid("invalid aes key size");this.b=[d=a.slice(0),e=[]];for(a=b;a<4*b+28;a++){c=d[a-1];if(0===a%b||8===b&&4===a%b)c=f[c>>>24]<<24^f[c>>16&255]<<16^f[c>>8&255]<<8^f[c&255],0===a%b&&(c=c<<8^c>>>24^h<<24,h=h<<1^283*(h>>7));d[a]=d[a-b]^c}for(b=0;a;b++,a--)c=d[b&3?a:a-4],e[b]=4>=a||4>b?c:g[0][f[c>>>24]]^g[1][f[c>>16&255]]^g[2][f[c>>8&255]]^g[3][f[c&
255]]};
sjcl.cipher.aes.prototype={encrypt:function(a){return t(this,a,0)},decrypt:function(a){return t(this,a,1)},s:[[[],[],[],[],[]],[[],[],[],[],[]]],O:function(){var a=this.s[0],b=this.s[1],c=a[4],d=b[4],e,f,g,h=[],k=[],l,n,m,p;for(e=0;0x100>e;e++)k[(h[e]=e<<1^283*(e>>7))^e]=e;for(f=g=0;!c[f];f^=l||1,g=k[g]||1)for(m=g^g<<1^g<<2^g<<3^g<<4,m=m>>8^m&255^99,c[f]=m,d[m]=f,n=h[e=h[l=h[f]]],p=0x1010101*n^0x10001*e^0x101*l^0x1010100*f,n=0x101*h[m]^0x1010100*m,e=0;4>e;e++)a[e][f]=n=n<<24^n>>>8,b[e][m]=p=p<<24^p>>>8;for(e=
0;5>e;e++)a[e]=a[e].slice(0),b[e]=b[e].slice(0)}};
function t(a,b,c){if(4!==b.length)throw new sjcl.exception.invalid("invalid aes block size");var d=a.b[c],e=b[0]^d[0],f=b[c?3:1]^d[1],g=b[2]^d[2];b=b[c?1:3]^d[3];var h,k,l,n=d.length/4-2,m,p=4,r=[0,0,0,0];h=a.s[c];a=h[0];var q=h[1],v=h[2],w=h[3],x=h[4];for(m=0;m<n;m++)h=a[e>>>24]^q[f>>16&255]^v[g>>8&255]^w[b&255]^d[p],k=a[f>>>24]^q[g>>16&255]^v[b>>8&255]^w[e&255]^d[p+1],l=a[g>>>24]^q[b>>16&255]^v[e>>8&255]^w[f&255]^d[p+2],b=a[b>>>24]^q[e>>16&255]^v[f>>8&255]^w[g&255]^d[p+3],p+=4,e=h,f=k,g=l;for(m=
0;4>m;m++)r[c?3&-m:m]=x[e>>>24]<<24^x[f>>16&255]<<16^x[g>>8&255]<<8^x[b&255]^d[p++],h=e,e=f,f=g,g=b,b=h;return r}
sjcl.bitArray={bitSlice:function(a,b,c){a=sjcl.bitArray.$(a.slice(b/32),32-(b&31)).slice(1);return void 0===c?a:sjcl.bitArray.clamp(a,c-b)},extract:function(a,b,c){var d=Math.floor(-b-c&31);return((b+c-1^b)&-32?a[b/32|0]<<32-d^a[b/32+1|0]>>>d:a[b/32|0]>>>d)&(1<<c)-1},concat:function(a,b){if(0===a.length||0===b.length)return a.concat(b);var c=a[a.length-1],d=sjcl.bitArray.getPartial(c);return 32===d?a.concat(b):sjcl.bitArray.$(b,d,c|0,a.slice(0,a.length-1))},bitLength:function(a){var b=a.length;return 0===
b?0:32*(b-1)+sjcl.bitArray.getPartial(a[b-1])},clamp:function(a,b){if(32*a.length<b)return a;a=a.slice(0,Math.ceil(b/32));var c=a.length;b=b&31;0<c&&b&&(a[c-1]=sjcl.bitArray.partial(b,a[c-1]&2147483648>>b-1,1));return a},partial:function(a,b,c){return 32===a?b:(c?b|0:b<<32-a)+0x10000000000*a},getPartial:function(a){return Math.round(a/0x10000000000)||32},equal:function(a,b){if(sjcl.bitArray.bitLength(a)!==sjcl.bitArray.bitLength(b))return!1;var c=0,d;for(d=0;d<a.length;d++)c|=a[d]^b[d];return 0===
c},$:function(a,b,c,d){var e;e=0;for(void 0===d&&(d=[]);32<=b;b-=32)d.push(c),c=0;if(0===b)return d.concat(a);for(e=0;e<a.length;e++)d.push(c|a[e]>>>b),c=a[e]<<32-b;e=a.length?a[a.length-1]:0;a=sjcl.bitArray.getPartial(e);d.push(sjcl.bitArray.partial(b+a&31,32<b+a?c:d.pop(),1));return d},i:function(a,b){return[a[0]^b[0],a[1]^b[1],a[2]^b[2],a[3]^b[3]]},byteswapM:function(a){var b,c;for(b=0;b<a.length;++b)c=a[b],a[b]=c>>>24|c>>>8&0xff00|(c&0xff00)<<8|c<<24;return a}};
sjcl.codec.utf8String={fromBits:function(a){var b="",c=sjcl.bitArray.bitLength(a),d,e;for(d=0;d<c/8;d++)0===(d&3)&&(e=a[d/4]),b+=String.fromCharCode(e>>>8>>>8>>>8),e<<=8;return decodeURIComponent(escape(b))},toBits:function(a){a=unescape(encodeURIComponent(a));var b=[],c,d=0;for(c=0;c<a.length;c++)d=d<<8|a.charCodeAt(c),3===(c&3)&&(b.push(d),d=0);c&3&&b.push(sjcl.bitArray.partial(8*(c&3),d));return b}};
sjcl.codec.hex={fromBits:function(a){var b="",c;for(c=0;c<a.length;c++)b+=((a[c]|0)+0xf00000000000).toString(16).substr(4);return b.substr(0,sjcl.bitArray.bitLength(a)/4)},toBits:function(a){var b,c=[],d;a=a.replace(/\s|0x/g,"");d=a.length;a=a+"00000000";for(b=0;b<a.length;b+=8)c.push(parseInt(a.substr(b,8),16)^0);return sjcl.bitArray.clamp(c,4*d)}};
sjcl.codec.base32={B:"ABCDEFGHIJKLMNOPQRSTUVWXYZ234567",X:"0123456789ABCDEFGHIJKLMNOPQRSTUV",BITS:32,BASE:5,REMAINING:27,fromBits:function(a,b,c){var d=sjcl.codec.base32.BASE,e=sjcl.codec.base32.REMAINING,f="",g=0,h=sjcl.codec.base32.B,k=0,l=sjcl.bitArray.bitLength(a);c&&(h=sjcl.codec.base32.X);for(c=0;f.length*d<l;)f+=h.charAt((k^a[c]>>>g)>>>e),g<d?(k=a[c]<<d-g,g+=e,c++):(k<<=d,g-=d);for(;f.length&7&&!b;)f+="=";return f},toBits:function(a,b){a=a.replace(/\s|=/g,"").toUpperCase();var c=sjcl.codec.base32.BITS,
d=sjcl.codec.base32.BASE,e=sjcl.codec.base32.REMAINING,f=[],g,h=0,k=sjcl.codec.base32.B,l=0,n,m="base32";b&&(k=sjcl.codec.base32.X,m="base32hex");for(g=0;g<a.length;g++){n=k.indexOf(a.charAt(g));if(0>n){if(!b)try{return sjcl.codec.base32hex.toBits(a)}catch(p){}throw new sjcl.exception.invalid("this isn't "+m+"!");}h>e?(h-=e,f.push(l^n>>>h),l=n<<c-h):(h+=d,l^=n<<c-h)}h&56&&f.push(sjcl.bitArray.partial(h&56,l,1));return f}};
sjcl.codec.base32hex={fromBits:function(a,b){return sjcl.codec.base32.fromBits(a,b,1)},toBits:function(a){return sjcl.codec.base32.toBits(a,1)}};
sjcl.codec.base64={B:"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/",fromBits:function(a,b,c){var d="",e=0,f=sjcl.codec.base64.B,g=0,h=sjcl.bitArray.bitLength(a);c&&(f=f.substr(0,62)+"-_");for(c=0;6*d.length<h;)d+=f.charAt((g^a[c]>>>e)>>>26),6>e?(g=a[c]<<6-e,e+=26,c++):(g<<=6,e-=6);for(;d.length&3&&!b;)d+="=";return d},toBits:function(a,b){a=a.replace(/\s|=/g,"");var c=[],d,e=0,f=sjcl.codec.base64.B,g=0,h;b&&(f=f.substr(0,62)+"-_");for(d=0;d<a.length;d++){h=f.indexOf(a.charAt(d));
if(0>h)throw new sjcl.exception.invalid("this isn't base64!");26<e?(e-=26,c.push(g^h>>>e),g=h<<32-e):(e+=6,g^=h<<32-e)}e&56&&c.push(sjcl.bitArray.partial(e&56,g,1));return c}};sjcl.codec.base64url={fromBits:function(a){return sjcl.codec.base64.fromBits(a,1,1)},toBits:function(a){return sjcl.codec.base64.toBits(a,1)}};sjcl.hash.sha256=function(a){this.b[0]||this.O();a?(this.F=a.F.slice(0),this.A=a.A.slice(0),this.l=a.l):this.reset()};sjcl.hash.sha256.hash=function(a){return(new sjcl.hash.sha256).update(a).finalize()};
sjcl.hash.sha256.prototype={blockSize:512,reset:function(){this.F=this.Y.slice(0);this.A=[];this.l=0;return this},update:function(a){"string"===typeof a&&(a=sjcl.codec.utf8String.toBits(a));var b,c=this.A=sjcl.bitArray.concat(this.A,a);b=this.l;a=this.l=b+sjcl.bitArray.bitLength(a);if(0x1fffffffffffff<a)throw new sjcl.exception.invalid("Cannot hash more than 2^53 - 1 bits");if("undefined"!==typeof Uint32Array){var d=new Uint32Array(c),e=0;for(b=512+b-(512+b&0x1ff);b<=a;b+=512)u(this,d.subarray(16*e,
16*(e+1))),e+=1;c.splice(0,16*e)}else for(b=512+b-(512+b&0x1ff);b<=a;b+=512)u(this,c.splice(0,16));return this},finalize:function(){var a,b=this.A,c=this.F,b=sjcl.bitArray.concat(b,[sjcl.bitArray.partial(1,1)]);for(a=b.length+2;a&15;a++)b.push(0);b.push(Math.floor(this.l/0x100000000));for(b.push(this.l|0);b.length;)u(this,b.splice(0,16));this.reset();return c},Y:[],b:[],O:function(){function a(a){return 0x100000000*(a-Math.floor(a))|0}for(var b=0,c=2,d,e;64>b;c++){e=!0;for(d=2;d*d<=c;d++)if(0===c%d){e=
!1;break}e&&(8>b&&(this.Y[b]=a(Math.pow(c,.5))),this.b[b]=a(Math.pow(c,1/3)),b++)}}};
function u(a,b){var c,d,e,f=a.F,g=a.b,h=f[0],k=f[1],l=f[2],n=f[3],m=f[4],p=f[5],r=f[6],q=f[7];for(c=0;64>c;c++)16>c?d=b[c]:(d=b[c+1&15],e=b[c+14&15],d=b[c&15]=(d>>>7^d>>>18^d>>>3^d<<25^d<<14)+(e>>>17^e>>>19^e>>>10^e<<15^e<<13)+b[c&15]+b[c+9&15]|0),d=d+q+(m>>>6^m>>>11^m>>>25^m<<26^m<<21^m<<7)+(r^m&(p^r))+g[c],q=r,r=p,p=m,m=n+d|0,n=l,l=k,k=h,h=d+(k&l^n&(k^l))+(k>>>2^k>>>13^k>>>22^k<<30^k<<19^k<<10)|0;f[0]=f[0]+h|0;f[1]=f[1]+k|0;f[2]=f[2]+l|0;f[3]=f[3]+n|0;f[4]=f[4]+m|0;f[5]=f[5]+p|0;f[6]=f[6]+r|0;f[7]=
f[7]+q|0}
sjcl.mode.ccm={name:"ccm",G:[],listenProgress:function(a){sjcl.mode.ccm.G.push(a)},unListenProgress:function(a){a=sjcl.mode.ccm.G.indexOf(a);-1<a&&sjcl.mode.ccm.G.splice(a,1)},fa:function(a){var b=sjcl.mode.ccm.G.slice(),c;for(c=0;c<b.length;c+=1)b[c](a)},encrypt:function(a,b,c,d,e){var f,g=b.slice(0),h=sjcl.bitArray,k=h.bitLength(c)/8,l=h.bitLength(g)/8;e=e||64;d=d||[];if(7>k)throw new sjcl.exception.invalid("ccm: iv must be at least 7 bytes");for(f=2;4>f&&l>>>8*f;f++);f<15-k&&(f=15-k);c=h.clamp(c,
8*(15-f));b=sjcl.mode.ccm.V(a,b,c,d,e,f);g=sjcl.mode.ccm.C(a,g,c,b,e,f);return h.concat(g.data,g.tag)},decrypt:function(a,b,c,d,e){e=e||64;d=d||[];var f=sjcl.bitArray,g=f.bitLength(c)/8,h=f.bitLength(b),k=f.clamp(b,h-e),l=f.bitSlice(b,h-e),h=(h-e)/8;if(7>g)throw new sjcl.exception.invalid("ccm: iv must be at least 7 bytes");for(b=2;4>b&&h>>>8*b;b++);b<15-g&&(b=15-g);c=f.clamp(c,8*(15-b));k=sjcl.mode.ccm.C(a,k,c,l,e,b);a=sjcl.mode.ccm.V(a,k.data,c,d,e,b);if(!f.equal(k.tag,a))throw new sjcl.exception.corrupt("ccm: tag doesn't match");
return k.data},na:function(a,b,c,d,e,f){var g=[],h=sjcl.bitArray,k=h.i;d=[h.partial(8,(b.length?64:0)|d-2<<2|f-1)];d=h.concat(d,c);d[3]|=e;d=a.encrypt(d);if(b.length)for(c=h.bitLength(b)/8,65279>=c?g=[h.partial(16,c)]:0xffffffff>=c&&(g=h.concat([h.partial(16,65534)],[c])),g=h.concat(g,b),b=0;b<g.length;b+=4)d=a.encrypt(k(d,g.slice(b,b+4).concat([0,0,0])));return d},V:function(a,b,c,d,e,f){var g=sjcl.bitArray,h=g.i;e/=8;if(e%2||4>e||16<e)throw new sjcl.exception.invalid("ccm: invalid tag length");
if(0xffffffff<d.length||0xffffffff<b.length)throw new sjcl.exception.bug("ccm: can't deal with 4GiB or more data");c=sjcl.mode.ccm.na(a,d,c,e,g.bitLength(b)/8,f);for(d=0;d<b.length;d+=4)c=a.encrypt(h(c,b.slice(d,d+4).concat([0,0,0])));return g.clamp(c,8*e)},C:function(a,b,c,d,e,f){var g,h=sjcl.bitArray;g=h.i;var k=b.length,l=h.bitLength(b),n=k/50,m=n;c=h.concat([h.partial(8,f-1)],c).concat([0,0,0]).slice(0,4);d=h.bitSlice(g(d,a.encrypt(c)),0,e);if(!k)return{tag:d,data:[]};for(g=0;g<k;g+=4)g>n&&(sjcl.mode.ccm.fa(g/
k),n+=m),c[3]++,e=a.encrypt(c),b[g]^=e[0],b[g+1]^=e[1],b[g+2]^=e[2],b[g+3]^=e[3];return{tag:d,data:h.clamp(b,l)}}};
sjcl.mode.ocb2={name:"ocb2",encrypt:function(a,b,c,d,e,f){if(128!==sjcl.bitArray.bitLength(c))throw new sjcl.exception.invalid("ocb iv must be 128 bits");var g,h=sjcl.mode.ocb2.S,k=sjcl.bitArray,l=k.i,n=[0,0,0,0];c=h(a.encrypt(c));var m,p=[];d=d||[];e=e||64;for(g=0;g+4<b.length;g+=4)m=b.slice(g,g+4),n=l(n,m),p=p.concat(l(c,a.encrypt(l(c,m)))),c=h(c);m=b.slice(g);b=k.bitLength(m);g=a.encrypt(l(c,[0,0,0,b]));m=k.clamp(l(m.concat([0,0,0]),g),b);n=l(n,l(m.concat([0,0,0]),g));n=a.encrypt(l(n,l(c,h(c))));
d.length&&(n=l(n,f?d:sjcl.mode.ocb2.pmac(a,d)));return p.concat(k.concat(m,k.clamp(n,e)))},decrypt:function(a,b,c,d,e,f){if(128!==sjcl.bitArray.bitLength(c))throw new sjcl.exception.invalid("ocb iv must be 128 bits");e=e||64;var g=sjcl.mode.ocb2.S,h=sjcl.bitArray,k=h.i,l=[0,0,0,0],n=g(a.encrypt(c)),m,p,r=sjcl.bitArray.bitLength(b)-e,q=[];d=d||[];for(c=0;c+4<r/32;c+=4)m=k(n,a.decrypt(k(n,b.slice(c,c+4)))),l=k(l,m),q=q.concat(m),n=g(n);p=r-32*c;m=a.encrypt(k(n,[0,0,0,p]));m=k(m,h.clamp(b.slice(c),p).concat([0,
0,0]));l=k(l,m);l=a.encrypt(k(l,k(n,g(n))));d.length&&(l=k(l,f?d:sjcl.mode.ocb2.pmac(a,d)));if(!h.equal(h.clamp(l,e),h.bitSlice(b,r)))throw new sjcl.exception.corrupt("ocb: tag doesn't match");return q.concat(h.clamp(m,p))},pmac:function(a,b){var c,d=sjcl.mode.ocb2.S,e=sjcl.bitArray,f=e.i,g=[0,0,0,0],h=a.encrypt([0,0,0,0]),h=f(h,d(d(h)));for(c=0;c+4<b.length;c+=4)h=d(h),g=f(g,a.encrypt(f(h,b.slice(c,c+4))));c=b.slice(c);128>e.bitLength(c)&&(h=f(h,d(h)),c=e.concat(c,[-2147483648,0,0,0]));g=f(g,c);
return a.encrypt(f(d(f(h,d(h))),g))},S:function(a){return[a[0]<<1^a[1]>>>31,a[1]<<1^a[2]>>>31,a[2]<<1^a[3]>>>31,a[3]<<1^135*(a[0]>>>31)]}};
sjcl.mode.gcm={name:"gcm",encrypt:function(a,b,c,d,e){var f=b.slice(0);b=sjcl.bitArray;d=d||[];a=sjcl.mode.gcm.C(!0,a,f,d,c,e||128);return b.concat(a.data,a.tag)},decrypt:function(a,b,c,d,e){var f=b.slice(0),g=sjcl.bitArray,h=g.bitLength(f);e=e||128;d=d||[];e<=h?(b=g.bitSlice(f,h-e),f=g.bitSlice(f,0,h-e)):(b=f,f=[]);a=sjcl.mode.gcm.C(!1,a,f,d,c,e);if(!g.equal(a.tag,b))throw new sjcl.exception.corrupt("gcm: tag doesn't match");return a.data},ka:function(a,b){var c,d,e,f,g,h=sjcl.bitArray.i;e=[0,0,
0,0];f=b.slice(0);for(c=0;128>c;c++){(d=0!==(a[Math.floor(c/32)]&1<<31-c%32))&&(e=h(e,f));g=0!==(f[3]&1);for(d=3;0<d;d--)f[d]=f[d]>>>1|(f[d-1]&1)<<31;f[0]>>>=1;g&&(f[0]^=-0x1f000000)}return e},j:function(a,b,c){var d,e=c.length;b=b.slice(0);for(d=0;d<e;d+=4)b[0]^=0xffffffff&c[d],b[1]^=0xffffffff&c[d+1],b[2]^=0xffffffff&c[d+2],b[3]^=0xffffffff&c[d+3],b=sjcl.mode.gcm.ka(b,a);return b},C:function(a,b,c,d,e,f){var g,h,k,l,n,m,p,r,q=sjcl.bitArray;m=c.length;p=q.bitLength(c);r=q.bitLength(d);h=q.bitLength(e);
g=b.encrypt([0,0,0,0]);96===h?(e=e.slice(0),e=q.concat(e,[1])):(e=sjcl.mode.gcm.j(g,[0,0,0,0],e),e=sjcl.mode.gcm.j(g,e,[0,0,Math.floor(h/0x100000000),h&0xffffffff]));h=sjcl.mode.gcm.j(g,[0,0,0,0],d);n=e.slice(0);d=h.slice(0);a||(d=sjcl.mode.gcm.j(g,h,c));for(l=0;l<m;l+=4)n[3]++,k=b.encrypt(n),c[l]^=k[0],c[l+1]^=k[1],c[l+2]^=k[2],c[l+3]^=k[3];c=q.clamp(c,p);a&&(d=sjcl.mode.gcm.j(g,h,c));a=[Math.floor(r/0x100000000),r&0xffffffff,Math.floor(p/0x100000000),p&0xffffffff];d=sjcl.mode.gcm.j(g,d,a);k=b.encrypt(e);
d[0]^=k[0];d[1]^=k[1];d[2]^=k[2];d[3]^=k[3];return{tag:q.bitSlice(d,0,f),data:c}}};sjcl.misc.hmac=function(a,b){this.W=b=b||sjcl.hash.sha256;var c=[[],[]],d,e=b.prototype.blockSize/32;this.w=[new b,new b];a.length>e&&(a=b.hash(a));for(d=0;d<e;d++)c[0][d]=a[d]^909522486,c[1][d]=a[d]^1549556828;this.w[0].update(c[0]);this.w[1].update(c[1]);this.R=new b(this.w[0])};
sjcl.misc.hmac.prototype.encrypt=sjcl.misc.hmac.prototype.mac=function(a){if(this.aa)throw new sjcl.exception.invalid("encrypt on already updated hmac called!");this.update(a);return this.digest(a)};sjcl.misc.hmac.prototype.reset=function(){this.R=new this.W(this.w[0]);this.aa=!1};sjcl.misc.hmac.prototype.update=function(a){this.aa=!0;this.R.update(a)};sjcl.misc.hmac.prototype.digest=function(){var a=this.R.finalize(),a=(new this.W(this.w[1])).update(a).finalize();this.reset();return a};
sjcl.misc.pbkdf2=function(a,b,c,d,e){c=c||1E4;if(0>d||0>c)throw new sjcl.exception.invalid("invalid params to pbkdf2");"string"===typeof a&&(a=sjcl.codec.utf8String.toBits(a));"string"===typeof b&&(b=sjcl.codec.utf8String.toBits(b));e=e||sjcl.misc.hmac;a=new e(a);var f,g,h,k,l=[],n=sjcl.bitArray;for(k=1;32*l.length<(d||1);k++){e=f=a.encrypt(n.concat(b,[k]));for(g=1;g<c;g++)for(f=a.encrypt(f),h=0;h<f.length;h++)e[h]^=f[h];l=l.concat(e)}d&&(l=n.clamp(l,d));return l};
sjcl.prng=function(a){this.c=[new sjcl.hash.sha256];this.m=[0];this.P=0;this.H={};this.N=0;this.U={};this.Z=this.f=this.o=this.ha=0;this.b=[0,0,0,0,0,0,0,0];this.h=[0,0,0,0];this.L=void 0;this.M=a;this.D=!1;this.K={progress:{},seeded:{}};this.u=this.ga=0;this.I=1;this.J=2;this.ca=0x10000;this.T=[0,48,64,96,128,192,0x100,384,512,768,1024];this.da=3E4;this.ba=80};
sjcl.prng.prototype={randomWords:function(a,b){var c=[],d;d=this.isReady(b);var e;if(d===this.u)throw new sjcl.exception.notReady("generator isn't seeded");if(d&this.J){d=!(d&this.I);e=[];var f=0,g;this.Z=e[0]=(new Date).valueOf()+this.da;for(g=0;16>g;g++)e.push(0x100000000*Math.random()|0);for(g=0;g<this.c.length&&(e=e.concat(this.c[g].finalize()),f+=this.m[g],this.m[g]=0,d||!(this.P&1<<g));g++);this.P>=1<<this.c.length&&(this.c.push(new sjcl.hash.sha256),this.m.push(0));this.f-=f;f>this.o&&(this.o=
f);this.P++;this.b=sjcl.hash.sha256.hash(this.b.concat(e));this.L=new sjcl.cipher.aes(this.b);for(d=0;4>d&&(this.h[d]=this.h[d]+1|0,!this.h[d]);d++);}for(d=0;d<a;d+=4)0===(d+1)%this.ca&&y(this),e=z(this),c.push(e[0],e[1],e[2],e[3]);y(this);return c.slice(0,a)},setDefaultParanoia:function(a,b){if(0===a&&"Setting paranoia=0 will ruin your security; use it only for testing"!==b)throw new sjcl.exception.invalid("Setting paranoia=0 will ruin your security; use it only for testing");this.M=a},addEntropy:function(a,
b,c){c=c||"user";var d,e,f=(new Date).valueOf(),g=this.H[c],h=this.isReady(),k=0;d=this.U[c];void 0===d&&(d=this.U[c]=this.ha++);void 0===g&&(g=this.H[c]=0);this.H[c]=(this.H[c]+1)%this.c.length;switch(typeof a){case "number":void 0===b&&(b=1);this.c[g].update([d,this.N++,1,b,f,1,a|0]);break;case "object":c=Object.prototype.toString.call(a);if("[object Uint32Array]"===c){e=[];for(c=0;c<a.length;c++)e.push(a[c]);a=e}else for("[object Array]"!==c&&(k=1),c=0;c<a.length&&!k;c++)"number"!==typeof a[c]&&
(k=1);if(!k){if(void 0===b)for(c=b=0;c<a.length;c++)for(e=a[c];0<e;)b++,e=e>>>1;this.c[g].update([d,this.N++,2,b,f,a.length].concat(a))}break;case "string":void 0===b&&(b=a.length);this.c[g].update([d,this.N++,3,b,f,a.length]);this.c[g].update(a);break;default:k=1}if(k)throw new sjcl.exception.bug("random: addEntropy only supports number, array of numbers or string");this.m[g]+=b;this.f+=b;h===this.u&&(this.isReady()!==this.u&&A("seeded",Math.max(this.o,this.f)),A("progress",this.getProgress()))},
isReady:function(a){a=this.T[void 0!==a?a:this.M];return this.o&&this.o>=a?this.m[0]>this.ba&&(new Date).valueOf()>this.Z?this.J|this.I:this.I:this.f>=a?this.J|this.u:this.u},getProgress:function(a){a=this.T[a?a:this.M];return this.o>=a?1:this.f>a?1:this.f/a},startCollectors:function(){if(!this.D){this.a={loadTimeCollector:B(this,this.ma),mouseCollector:B(this,this.oa),keyboardCollector:B(this,this.la),accelerometerCollector:B(this,this.ea),touchCollector:B(this,this.qa)};if(window.addEventListener)window.addEventListener("load",
this.a.loadTimeCollector,!1),window.addEventListener("mousemove",this.a.mouseCollector,!1),window.addEventListener("keypress",this.a.keyboardCollector,!1),window.addEventListener("devicemotion",this.a.accelerometerCollector,!1),window.addEventListener("touchmove",this.a.touchCollector,!1);else if(document.attachEvent)document.attachEvent("onload",this.a.loadTimeCollector),document.attachEvent("onmousemove",this.a.mouseCollector),document.attachEvent("keypress",this.a.keyboardCollector);else throw new sjcl.exception.bug("can't attach event");
this.D=!0}},stopCollectors:function(){this.D&&(window.removeEventListener?(window.removeEventListener("load",this.a.loadTimeCollector,!1),window.removeEventListener("mousemove",this.a.mouseCollector,!1),window.removeEventListener("keypress",this.a.keyboardCollector,!1),window.removeEventListener("devicemotion",this.a.accelerometerCollector,!1),window.removeEventListener("touchmove",this.a.touchCollector,!1)):document.detachEvent&&(document.detachEvent("onload",this.a.loadTimeCollector),document.detachEvent("onmousemove",
this.a.mouseCollector),document.detachEvent("keypress",this.a.keyboardCollector)),this.D=!1)},addEventListener:function(a,b){this.K[a][this.ga++]=b},removeEventListener:function(a,b){var c,d,e=this.K[a],f=[];for(d in e)e.hasOwnProperty(d)&&e[d]===b&&f.push(d);for(c=0;c<f.length;c++)d=f[c],delete e[d]},la:function(){C(this,1)},oa:function(a){var b,c;try{b=a.x||a.clientX||a.offsetX||0,c=a.y||a.clientY||a.offsetY||0}catch(d){c=b=0}0!=b&&0!=c&&this.addEntropy([b,c],2,"mouse");C(this,0)},qa:function(a){a=
a.touches[0]||a.changedTouches[0];this.addEntropy([a.pageX||a.clientX,a.pageY||a.clientY],1,"touch");C(this,0)},ma:function(){C(this,2)},ea:function(a){a=a.accelerationIncludingGravity.x||a.accelerationIncludingGravity.y||a.accelerationIncludingGravity.z;if(window.orientation){var b=window.orientation;"number"===typeof b&&this.addEntropy(b,1,"accelerometer")}a&&this.addEntropy(a,2,"accelerometer");C(this,0)}};
function A(a,b){var c,d=sjcl.random.K[a],e=[];for(c in d)d.hasOwnProperty(c)&&e.push(d[c]);for(c=0;c<e.length;c++)e[c](b)}function C(a,b){"undefined"!==typeof window&&window.performance&&"function"===typeof window.performance.now?a.addEntropy(window.performance.now(),b,"loadtime"):a.addEntropy((new Date).valueOf(),b,"loadtime")}function y(a){a.b=z(a).concat(z(a));a.L=new sjcl.cipher.aes(a.b)}function z(a){for(var b=0;4>b&&(a.h[b]=a.h[b]+1|0,!a.h[b]);b++);return a.L.encrypt(a.h)}
function B(a,b){return function(){b.apply(a,arguments)}}sjcl.random=new sjcl.prng(6);
a:try{var D,E,F,G;if(G="undefined"!==typeof module&&module.exports){var H;try{H=require("crypto")}catch(a){H=null}G=E=H}if(G&&E.randomBytes)D=E.randomBytes(128),D=new Uint32Array((new Uint8Array(D)).buffer),sjcl.random.addEntropy(D,1024,"crypto['randomBytes']");else if("undefined"!==typeof window&&"undefined"!==typeof Uint32Array){F=new Uint32Array(32);if(window.crypto&&window.crypto.getRandomValues)window.crypto.getRandomValues(F);else if(window.msCrypto&&window.msCrypto.getRandomValues)window.msCrypto.getRandomValues(F);
else break a;sjcl.random.addEntropy(F,1024,"crypto['getRandomValues']")}}catch(a){"undefined"!==typeof window&&window.console&&(console.log("There was an error collecting entropy from the browser:"),console.log(a))}
sjcl.json={defaults:{v:1,iter:1E4,ks:128,ts:64,mode:"ccm",adata:"",cipher:"aes"},ja:function(a,b,c,d){c=c||{};d=d||{};var e=sjcl.json,f=e.g({iv:sjcl.random.randomWords(4,0)},e.defaults),g;e.g(f,c);c=f.adata;"string"===typeof f.salt&&(f.salt=sjcl.codec.base64.toBits(f.salt));"string"===typeof f.iv&&(f.iv=sjcl.codec.base64.toBits(f.iv));if(!sjcl.mode[f.mode]||!sjcl.cipher[f.cipher]||"string"===typeof a&&100>=f.iter||64!==f.ts&&96!==f.ts&&128!==f.ts||128!==f.ks&&192!==f.ks&&0x100!==f.ks||2>f.iv.length||
4<f.iv.length)throw new sjcl.exception.invalid("json encrypt: invalid parameters");"string"===typeof a?(g=sjcl.misc.cachedPbkdf2(a,f),a=g.key.slice(0,f.ks/32),f.salt=g.salt):sjcl.ecc&&a instanceof sjcl.ecc.elGamal.publicKey&&(g=a.kem(),f.kemtag=g.tag,a=g.key.slice(0,f.ks/32));"string"===typeof b&&(b=sjcl.codec.utf8String.toBits(b));"string"===typeof c&&(f.adata=c=sjcl.codec.utf8String.toBits(c));g=new sjcl.cipher[f.cipher](a);e.g(d,f);d.key=a;f.ct="ccm"===f.mode&&sjcl.arrayBuffer&&sjcl.arrayBuffer.ccm&&
b instanceof ArrayBuffer?sjcl.arrayBuffer.ccm.encrypt(g,b,f.iv,c,f.ts):sjcl.mode[f.mode].encrypt(g,b,f.iv,c,f.ts);return f},encrypt:function(a,b,c,d){var e=sjcl.json,f=e.ja.apply(e,arguments);return e.encode(f)},ia:function(a,b,c,d){c=c||{};d=d||{};var e=sjcl.json;b=e.g(e.g(e.g({},e.defaults),b),c,!0);var f,g;f=b.adata;"string"===typeof b.salt&&(b.salt=sjcl.codec.base64.toBits(b.salt));"string"===typeof b.iv&&(b.iv=sjcl.codec.base64.toBits(b.iv));if(!sjcl.mode[b.mode]||!sjcl.cipher[b.cipher]||"string"===
typeof a&&100>=b.iter||64!==b.ts&&96!==b.ts&&128!==b.ts||128!==b.ks&&192!==b.ks&&0x100!==b.ks||!b.iv||2>b.iv.length||4<b.iv.length)throw new sjcl.exception.invalid("json decrypt: invalid parameters");"string"===typeof a?(g=sjcl.misc.cachedPbkdf2(a,b),a=g.key.slice(0,b.ks/32),b.salt=g.salt):sjcl.ecc&&a instanceof sjcl.ecc.elGamal.secretKey&&(a=a.unkem(sjcl.codec.base64.toBits(b.kemtag)).slice(0,b.ks/32));"string"===typeof f&&(f=sjcl.codec.utf8String.toBits(f));g=new sjcl.cipher[b.cipher](a);f="ccm"===
b.mode&&sjcl.arrayBuffer&&sjcl.arrayBuffer.ccm&&b.ct instanceof ArrayBuffer?sjcl.arrayBuffer.ccm.decrypt(g,b.ct,b.iv,b.tag,f,b.ts):sjcl.mode[b.mode].decrypt(g,b.ct,b.iv,f,b.ts);e.g(d,b);d.key=a;return 1===c.raw?f:sjcl.codec.utf8String.fromBits(f)},decrypt:function(a,b,c,d){var e=sjcl.json;return e.ia(a,e.decode(b),c,d)},encode:function(a){var b,c="{",d="";for(b in a)if(a.hasOwnProperty(b)){if(!b.match(/^[a-z0-9]+$/i))throw new sjcl.exception.invalid("json encode: invalid property name");c+=d+'"'+
b+'":';d=",";switch(typeof a[b]){case "number":case "boolean":c+=a[b];break;case "string":c+='"'+escape(a[b])+'"';break;case "object":c+='"'+sjcl.codec.base64.fromBits(a[b],0)+'"';break;default:throw new sjcl.exception.bug("json encode: unsupported type");}}return c+"}"},decode:function(a){a=a.replace(/\s/g,"");if(!a.match(/^\{.*\}$/))throw new sjcl.exception.invalid("json decode: this isn't json!");a=a.replace(/^\{|\}$/g,"").split(/,/);var b={},c,d;for(c=0;c<a.length;c++){if(!(d=a[c].match(/^\s*(?:(["']?)([a-z][a-z0-9]*)\1)\s*:\s*(?:(-?\d+)|"([a-z0-9+\/%*_.@=\-]*)"|(true|false))$/i)))throw new sjcl.exception.invalid("json decode: this isn't json!");
null!=d[3]?b[d[2]]=parseInt(d[3],10):null!=d[4]?b[d[2]]=d[2].match(/^(ct|adata|salt|iv)$/)?sjcl.codec.base64.toBits(d[4]):unescape(d[4]):null!=d[5]&&(b[d[2]]="true"===d[5])}return b},g:function(a,b,c){void 0===a&&(a={});if(void 0===b)return a;for(var d in b)if(b.hasOwnProperty(d)){if(c&&void 0!==a[d]&&a[d]!==b[d])throw new sjcl.exception.invalid("required parameter overridden");a[d]=b[d]}return a},sa:function(a,b){var c={},d;for(d in a)a.hasOwnProperty(d)&&a[d]!==b[d]&&(c[d]=a[d]);return c},ra:function(a,
b){var c={},d;for(d=0;d<b.length;d++)void 0!==a[b[d]]&&(c[b[d]]=a[b[d]]);return c}};sjcl.encrypt=sjcl.json.encrypt;sjcl.decrypt=sjcl.json.decrypt;sjcl.misc.pa={};sjcl.misc.cachedPbkdf2=function(a,b){var c=sjcl.misc.pa,d;b=b||{};d=b.iter||1E3;c=c[a]=c[a]||{};d=c[d]=c[d]||{firstSalt:b.salt&&b.salt.length?b.salt.slice(0):sjcl.random.randomWords(2,0)};c=void 0===b.salt?d.firstSalt:b.salt;d[c]=d[c]||sjcl.misc.pbkdf2(a,c,b.iter);return{key:d[c].slice(0),salt:c.slice(0)}};
"undefined"!==typeof module&&module.exports&&(module.exports=sjcl);"function"===typeof define&&define([],function(){return sjcl});
</script>
</div>
<!--~~ Boot kernel prologue ~~-->
<div id="bootKernelPrefix" style="display:none;">
<script data-tiddler-title="$:/boot/bootprefix.js" data-tiddler-type="application/javascript" type="text/javascript">/*\
title: $:/boot/bootprefix.js
type: application/javascript

This file sets up the globals that need to be available when JavaScript modules are executed in the browser. The overall sequence is:

# BootPrefix.js
# <module definitions>
# Boot.js

See Boot.js for further details of the boot process.

\*/

var _bootprefix = (function($tw) {

"use strict";

$tw = $tw || Object.create(null);
$tw.boot = $tw.boot || Object.create(null);

// Detect platforms
if(!("browser" in $tw)) {
	$tw.browser = typeof(window) !== "undefined" ? {} : null;
}
if(!("node" in $tw)) {
	$tw.node = typeof(process) === "object" ? {} : null;
}
if(!("nodeWebKit" in $tw)) {
	$tw.nodeWebKit = $tw.node && global.window && global.window.nwDispatcher ? {} : null;
}

// Set default boot tasks
$tw.boot.tasks = {
	trapErrors: !!($tw.browser && !$tw.node),
	readBrowserTiddlers: !!($tw.browser && !$tw.node)
};

/*
Information about each module is kept in an object with these members:
	moduleType: type of module
	definition: object, function or string defining the module; see below
	exports: exports of the module, filled in after execution

The `definition` can be of several types:

* An object can be used to directly specify the exports of the module
* A function with the arguments `module,require,exports` that returns `exports`
* A string function body with the same arguments

Each moduleInfo object is stored in two hashmaps: $tw.modules.titles and $tw.modules.types. The first is indexed by title and the second is indexed by type and then title
*/
$tw.modules = {
	titles: {}, // hashmap by module name of moduleInfo
	types: {} // hashmap by module type and then name of moduleInfo
};

/*
Define a JavaScript tiddler module for later execution
	moduleName: name of module being defined
	moduleType: type of module
	definition: module definition; see discussion above
*/
$tw.modules.define = function(moduleName,moduleType,definition) {
	// Create the moduleInfo
	var moduleInfo = {
		moduleType: moduleType,
		definition: definition,
		exports: undefined
	};
	// If the definition is already an object we can use it as the exports
	if(typeof moduleInfo.definition === "object") {
		moduleInfo.exports = definition;
	}
	// Store the module in the titles hashmap
	if(Object.prototype.hasOwnProperty.call($tw.modules.titles,moduleName)) {
		console.log("Warning: Redefined module - " + moduleName);
	}
	$tw.modules.titles[moduleName] = moduleInfo;
	// Store the module in the types hashmap
	if(!Object.prototype.hasOwnProperty.call($tw.modules.types,moduleType)) {
		$tw.modules.types[moduleType] = {};
	}
	if(Object.prototype.hasOwnProperty.call($tw.modules.types[moduleType],moduleName)) {
		console.log("Warning: Redefined module - " + moduleName);
	}
	$tw.modules.types[moduleType][moduleName] = moduleInfo;
};

/*
External JavaScript can populate this array before calling boot.js in order to preload tiddlers
*/
$tw.preloadTiddlers = $tw.preloadTiddlers || [];

/*
Convenience function for pushing a tiddler onto the preloading array
*/
$tw.preloadTiddler = function(fields) {
	$tw.preloadTiddlers.push(fields);
};

/*
Convenience function for pushing an array of tiddlers onto the preloading array
*/
$tw.preloadTiddlerArray = function(fieldsArray) {
	$tw.preloadTiddlers.push.apply($tw.preloadTiddlers,fieldsArray);
};

return $tw;

});

if(typeof(exports) === "undefined") {
	// Set up $tw global for the browser
	window.$tw = _bootprefix(window.$tw);
} else {
	// Export functionality as a module
	exports.bootprefix = _bootprefix;
}
//# sourceURL=$:/boot/bootprefix.js
</script>
</div>
<!--~~ Boot kernel ~~-->
<div id="bootKernel" style="display:none;">
<script data-tiddler-title="$:/boot/boot.js" data-tiddler-type="application/javascript" type="text/javascript">/*\
title: $:/boot/boot.js
type: application/javascript

The main boot kernel for TiddlyWiki. This single file creates a barebones TW environment that is just sufficient to bootstrap the modules containing the main logic of the application.

On the server this file is executed directly to boot TiddlyWiki. In the browser, this file is packed into a single HTML file.

\*/

var _boot = (function($tw) {

/*jslint node: true, browser: true */
/*global modules: false, $tw: false */
"use strict";

// Include bootprefix if we're not given module data
if(!$tw) {
	$tw = require("./bootprefix.js").bootprefix();
}

$tw.utils = $tw.utils || Object.create(null);

/////////////////////////// Standard node.js libraries

var fs, path, vm;
if($tw.node) {
	fs = require("fs");
	path = require("path");
	vm = require("vm");
}

/////////////////////////// Utility functions

$tw.boot.log = function(str) {
	$tw.boot.logMessages = $tw.boot.logMessages || [];
	$tw.boot.logMessages.push(str);
}

/*
Check if an object has a property
*/
$tw.utils.hop = function(object,property) {
	return object ? Object.prototype.hasOwnProperty.call(object,property) : false;
};

/*
Determine if a value is an array
*/
$tw.utils.isArray = function(value) {
	return Object.prototype.toString.call(value) == "[object Array]";
};

/*
Check if an array is equal by value and by reference.
*/
$tw.utils.isArrayEqual = function(array1,array2) {
	if(array1 === array2) {
		return true;
	}
	array1 = array1 || [];
	array2 = array2 || [];
	if(array1.length !== array2.length) {
		return false;
	}
	return array1.every(function(value,index) {
		return value === array2[index];
	});
};

/*
Add an entry to a sorted array if it doesn't already exist, while maintaining the sort order
*/
$tw.utils.insertSortedArray = function(array,value) {
	var low = 0, high = array.length - 1, mid, cmp;
	while(low <= high) {
		mid = (low + high) >> 1;
		cmp = value.localeCompare(array[mid]);
		if(cmp > 0) {
			low = mid + 1;
		} else if(cmp < 0) {
			high = mid - 1;
		} else {
			return array;
		}
	}
	array.splice(low,0,value);
	return array;
};

/*
Push entries onto an array, removing them first if they already exist in the array
	array: array to modify (assumed to be free of duplicates)
	value: a single value to push or an array of values to push
*/
$tw.utils.pushTop = function(array,value) {
	var t,p;
	if($tw.utils.isArray(value)) {
		// Remove any array entries that are duplicated in the new values
		if(value.length !== 0) {
			if(array.length !== 0) {
				if(value.length < array.length) {
					for(t=0; t<value.length; t++) {
						p = array.indexOf(value[t]);
						if(p !== -1) {
							array.splice(p,1);
						}
					}
				} else {
					for(t=array.length-1; t>=0; t--) {
						p = value.indexOf(array[t]);
						if(p !== -1) {
							array.splice(t,1);
						}
					}
				}
			}
			// Push the values on top of the main array
			array.push.apply(array,value);
		}
	} else {
		p = array.indexOf(value);
		if(p !== -1) {
			array.splice(p,1);
		}
		array.push(value);
	}
	return array;
};

/*
Determine if a value is a date
*/
$tw.utils.isDate = function(value) {
	return Object.prototype.toString.call(value) === "[object Date]";
};

/*
Iterate through all the own properties of an object or array. Callback is invoked with (element,title,object)
*/
$tw.utils.each = function(object,callback) {
	var next,f,length;
	if(object) {
		if(Object.prototype.toString.call(object) == "[object Array]") {
			for (f=0, length=object.length; f<length; f++) {
				next = callback(object[f],f,object);
				if(next === false) {
					break;
				}
		    }
		} else {
			var keys = Object.keys(object);
			for (f=0, length=keys.length; f<length; f++) {
				var key = keys[f];
				next = callback(object[key],key,object);
				if(next === false) {
					break;
				}
			}
		}
	}
};

/*
Helper for making DOM elements
tag: tag name
options: see below
Options include:
namespace: defaults to http://www.w3.org/1999/xhtml
attributes: hashmap of attribute values
style: hashmap of styles
text: text to add as a child node
children: array of further child nodes
innerHTML: optional HTML for element
class: class name(s)
document: defaults to current document
eventListeners: array of event listeners (this option won't work until $tw.utils.addEventListeners() has been loaded)
*/
$tw.utils.domMaker = function(tag,options) {
	var doc = options.document || document;
	var element = doc.createElementNS(options.namespace || "http://www.w3.org/1999/xhtml",tag);
	if(options["class"]) {
		element.className = options["class"];
	}
	if(options.text) {
		element.appendChild(doc.createTextNode(options.text));
	}
	$tw.utils.each(options.children,function(child) {
		element.appendChild(child);
	});
	if(options.innerHTML) {
		element.innerHTML = options.innerHTML;
	}
	$tw.utils.each(options.attributes,function(attribute,name) {
		element.setAttribute(name,attribute);
	});
	$tw.utils.each(options.style,function(value,name) {
		element.style[name] = value;
	});
	if(options.eventListeners) {
		$tw.utils.addEventListeners(element,options.eventListeners);
	}
	return element;
};

/*
Display an error and exit
*/
$tw.utils.error = function(err) {
	// Prepare the error message
	var errHeading = ( $tw.language == undefined ? "Internal JavaScript Error" : $tw.language.getString("InternalJavaScriptError/Title") ),
		promptMsg = ( $tw.language == undefined ? "Well, this is embarrassing. It is recommended that you restart TiddlyWiki by refreshing your browser" : $tw.language.getString("InternalJavaScriptError/Hint") );
	// Log the error to the console
	console.error($tw.node ? "\x1b[1;31m" + err + "\x1b[0m" : err);
	if($tw.browser && !$tw.node) {
		// Display an error message to the user
		var dm = $tw.utils.domMaker,
			heading = dm("h1",{text: errHeading}),
			prompt = dm("div",{text: promptMsg, "class": "tc-error-prompt"}),
			message = dm("div",{text: err, "class":"tc-error-message"}),
			button = dm("div",{children: [dm("button",{text: ( $tw.language == undefined ? "close" : $tw.language.getString("Buttons/Close/Caption") )})], "class": "tc-error-prompt"}),
			form = dm("form",{children: [heading,prompt,message,button], "class": "tc-error-form"});
		document.body.insertBefore(form,document.body.firstChild);
		form.addEventListener("submit",function(event) {
			document.body.removeChild(form);
			event.preventDefault();
			return false;
		},true);
		return null;
	} else if(!$tw.browser) {
		// Exit if we're under node.js
		process.exit(1);
	}
};

/*
Use our custom error handler if we're in the browser
*/
if($tw.boot.tasks.trapErrors) {
	window.onerror = function(errorMsg,url,lineNumber) {
		$tw.utils.error(errorMsg);
		return false;
	};
}

/*
Extend an object with the properties from a list of source objects
*/
$tw.utils.extend = function(object /*, sourceObjectList */) {
	$tw.utils.each(Array.prototype.slice.call(arguments,1),function(source) {
		if(source) {
			for (var p in source) {
				object[p] = source[p];
			}
		}
	});
	return object;
};

/*
Fill in any null or undefined properties of an object with the properties from a list of source objects. Each property that is an object is called recursively
*/
$tw.utils.deepDefaults = function(object /*, sourceObjectList */) {
	$tw.utils.each(Array.prototype.slice.call(arguments,1),function(source) {
		if(source) {
			for (var p in source) {
				if(object[p] === null || object[p] === undefined) {
					object[p] = source[p];
				}
				if(typeof object[p] === "object" && typeof source[p] === "object") {
					$tw.utils.deepDefaults(object[p],source[p]);
				}
			}
		}
	});
	return object;
};

/*
Convert a URIComponent encoded string to a string safely
*/
$tw.utils.decodeURIComponentSafe = function(s) {
	var v = s;
	try {
		v = decodeURIComponent(s);
	} catch(e) {}
	return v;
};

/*
Convert a URI encoded string to a string safely
*/
$tw.utils.decodeURISafe = function(s) {
	var v = s;
	try {
		v = decodeURI(s);
	} catch(e) {}
	return v;
};

/*
Convert "&amp;" to &, "&nbsp;" to nbsp, "&lt;" to <, "&gt;" to > and "&quot;" to "
*/
$tw.utils.htmlDecode = function(s) {
	return s.toString().replace(/&lt;/mg,"<").replace(/&nbsp;/mg,"\xA0").replace(/&gt;/mg,">").replace(/&quot;/mg,"\"").replace(/&amp;/mg,"&");
};

/*
Get the browser location.hash. We don't use location.hash because of the way that Firefox auto-urldecodes it (see http://stackoverflow.com/questions/1703552/encoding-of-window-location-hash)
*/
$tw.utils.getLocationHash = function() {
	var href = window.location.href;
	var idx = href.indexOf('#');
	if(idx === -1) {
		return "#";
	} else if(idx < href.length-1 && href[idx+1] === '#') {
		// Special case: ignore location hash if it itself starts with a #
		return "#";
	} else {
		return href.substring(idx);
	}
};

/*
Pad a string to a given length with "0"s. Length defaults to 2
*/
$tw.utils.pad = function(value,length) {
	length = length || 2;
	var s = value.toString();
	if(s.length < length) {
		s = "000000000000000000000000000".substr(0,length - s.length) + s;
	}
	return s;
};

// Convert a date into UTC YYYYMMDDHHMMSSmmm format
$tw.utils.stringifyDate = function(value) {
	return value.getUTCFullYear() +
			$tw.utils.pad(value.getUTCMonth() + 1) +
			$tw.utils.pad(value.getUTCDate()) +
			$tw.utils.pad(value.getUTCHours()) +
			$tw.utils.pad(value.getUTCMinutes()) +
			$tw.utils.pad(value.getUTCSeconds()) +
			$tw.utils.pad(value.getUTCMilliseconds(),3);
};

// Parse a date from a UTC YYYYMMDDHHMMSSmmm format string
$tw.utils.parseDate = function(value) {
	if(typeof value === "string") {
		var negative = 1;
		if(value.charAt(0) === "-") {
			negative = -1;
			value = value.substr(1);
		}
		var year = parseInt(value.substr(0,4),10) * negative,
			d = new Date(Date.UTC(year,
				parseInt(value.substr(4,2),10)-1,
				parseInt(value.substr(6,2),10),
				parseInt(value.substr(8,2)||"00",10),
				parseInt(value.substr(10,2)||"00",10),
				parseInt(value.substr(12,2)||"00",10),
				parseInt(value.substr(14,3)||"000",10)));
		  d.setUTCFullYear(year); // See https://stackoverflow.com/a/5870822
		  return d;
	} else if($tw.utils.isDate(value)) {
		return value;
	} else {
		return null;
	}
};

// Stringify an array of tiddler titles into a list string
$tw.utils.stringifyList = function(value) {
	if($tw.utils.isArray(value)) {
		var result = new Array(value.length);
		for(var t=0, l=value.length; t<l; t++) {
			var entry = value[t] || "";
			if(entry.indexOf(" ") !== -1) {
				result[t] = "[[" + entry + "]]";
			} else {
				result[t] = entry;
			}
		}
		return result.join(" ");
	} else {
		return value || "";
	}
};

// Parse a string array from a bracketted list. For example "OneTiddler [[Another Tiddler]] LastOne"
$tw.utils.parseStringArray = function(value, allowDuplicate) {
	if(typeof value === "string") {
		var memberRegExp = /(?:^|[^\S\xA0])(?:\[\[(.*?)\]\])(?=[^\S\xA0]|$)|([\S\xA0]+)/mg,
			results = [], names = {},
			match;
		do {
			match = memberRegExp.exec(value);
			if(match) {
				var item = match[1] || match[2];
				if(item !== undefined && (!$tw.utils.hop(names,item) || allowDuplicate)) {
					results.push(item);
					names[item] = true;
				}
			}
		} while(match);
		return results;
	} else if($tw.utils.isArray(value)) {
		return value;
	} else {
		return null;
	}
};

// Parse a block of name:value fields. The `fields` object is used as the basis for the return value
$tw.utils.parseFields = function(text,fields) {
	fields = fields || Object.create(null);
	text.split(/\r?\n/mg).forEach(function(line) {
		if(line.charAt(0) !== "#") {
			var p = line.indexOf(":");
			if(p !== -1) {
				var field = line.substr(0, p).trim(),
					value = line.substr(p+1).trim();
				if(field) {
					fields[field] = value;
				}
			}
		}
	});
	return fields;
};

// Safely parse a string as JSON
$tw.utils.parseJSONSafe = function(text,defaultJSON) {
	try {
		return JSON.parse(text);
	} catch(e) {
		if(typeof defaultJSON === "function") {
			return defaultJSON(e);
		} else {
			return defaultJSON || {};
		}
	}
};

/*
Resolves a source filepath delimited with `/` relative to a specified absolute root filepath.
In relative paths, the special folder name `..` refers to immediate parent directory, and the
name `.` refers to the current directory
*/
$tw.utils.resolvePath = function(sourcepath,rootpath) {
	// If the source path starts with ./ or ../ then it is relative to the root
	if(sourcepath.substr(0,2) === "./" || sourcepath.substr(0,3) === "../" ) {
		var src = sourcepath.split("/"),
			root = rootpath.split("/");
		// Remove the filename part of the root
		root.splice(root.length-1,1);
		// Process the source path bit by bit onto the end of the root path
		while(src.length > 0) {
			var c = src.shift();
			if(c === "..") { // Slice off the last root entry for a double dot
				if(root.length > 0) {
					root.splice(root.length-1,1);
				}
			} else if(c !== ".") { // Ignore dots
				root.push(c); // Copy other elements across
			}
		}
		return root.join("/");
	} else {
		// If it isn't relative, just return the path
		if(rootpath) {
			var root = rootpath.split("/");
			// Remove the filename part of the root
			root.splice(root.length - 1, 1);
			return root.join("/") + "/" + sourcepath;
		} else {
			return sourcepath;
		}
	}
};

/*
Parse a semantic version string into its constituent parts -- see https://semver.org
*/
$tw.utils.parseVersion = function(version) {
	var match = /^v?((\d+)\.(\d+)\.(\d+))(?:-([\dA-Za-z\-]+(?:\.[\dA-Za-z\-]+)*))?(?:\+([\dA-Za-z\-]+(?:\.[\dA-Za-z\-]+)*))?$/.exec(version);
	if(match) {
		return {
			version: match[1],
			major: parseInt(match[2],10),
			minor: parseInt(match[3],10),
			patch: parseInt(match[4],10),
			prerelease: match[5],
			build: match[6]
		};
	} else {
		return null;
	}
};

/*
Returns +1 if the version string A is greater than the version string B, 0 if they are the same, and +1 if B is greater than A.
Missing or malformed version strings are parsed as 0.0.0
*/
$tw.utils.compareVersions = function(versionStringA,versionStringB) {
	var defaultVersion = {
			major: 0,
			minor: 0,
			patch: 0
		},
		versionA = $tw.utils.parseVersion(versionStringA) || defaultVersion,
		versionB = $tw.utils.parseVersion(versionStringB) || defaultVersion,
		diff = [
			versionA.major - versionB.major,
			versionA.minor - versionB.minor,
			versionA.patch - versionB.patch
		];
	if((diff[0] > 0) || (diff[0] === 0 && diff[1] > 0) || (diff[0] === 0 & diff[1] === 0 & diff[2] > 0)) {
		return +1;
	} else if((diff[0] < 0) || (diff[0] === 0 && diff[1] < 0) || (diff[0] === 0 & diff[1] === 0 & diff[2] < 0)) {
		return -1;
	} else {
		return 0;
	}
};

/*
Returns true if the version string A is greater than the version string B. Returns true if the versions are the same
*/
$tw.utils.checkVersions = function(versionStringA,versionStringB) {
	return $tw.utils.compareVersions(versionStringA,versionStringB) !== -1;
};

/*
Register file type information
options: {flags: flags,deserializerType: deserializerType}
	flags:"image" for image types
	deserializerType: defaults to type if not specified
*/
$tw.utils.registerFileType = function(type,encoding,extension,options) {
	options = options || {};
	if($tw.utils.isArray(extension)) {
		$tw.utils.each(extension,function(extension) {
			$tw.config.fileExtensionInfo[extension] = {type: type};
		});
		extension = extension[0];
	} else {
		$tw.config.fileExtensionInfo[extension] = {type: type};
	}
	$tw.config.contentTypeInfo[type] = {encoding: encoding, extension: extension, flags: options.flags || [], deserializerType: options.deserializerType || type};
};

/*
Given an extension, always access the $tw.config.fileExtensionInfo
using a lowercase extension only.
*/
$tw.utils.getFileExtensionInfo = function(ext) {
	return ext ? $tw.config.fileExtensionInfo[ext.toLowerCase()] : null;
}

/*
Given an extension, get the correct encoding for that file.
defaults to utf8
*/
$tw.utils.getTypeEncoding = function(ext) {
	var extensionInfo = $tw.utils.getFileExtensionInfo(ext),
		type = extensionInfo ? extensionInfo.type : null,
		typeInfo = type ? $tw.config.contentTypeInfo[type] : null;
	return typeInfo ? typeInfo.encoding : "utf8";
};

/*
Run code globally with specified context variables in scope
*/
$tw.utils.evalGlobal = function(code,context,filename) {
	var contextCopy = $tw.utils.extend(Object.create(null),context);
	// Get the context variables as a pair of arrays of names and values
	var contextNames = [], contextValues = [];
	$tw.utils.each(contextCopy,function(value,name) {
		contextNames.push(name);
		contextValues.push(value);
	});
	// Add the code prologue and epilogue
	code = "(function(" + contextNames.join(",") + ") {(function(){\n" + code + "\n;})();\nreturn exports;\n})\n";
	// Compile the code into a function
	var fn;
	if($tw.browser) {
		fn = window["eval"](code + "\n\n//# sourceURL=" + filename);
	} else {
		fn = vm.runInThisContext(code,filename);
	}
	// Call the function and return the exports
	return fn.apply(null,contextValues);
};

/*
Run code in a sandbox with only the specified context variables in scope
*/
$tw.utils.evalSandboxed = $tw.browser ? $tw.utils.evalGlobal : function(code,context,filename) {
	var sandbox = $tw.utils.extend(Object.create(null),context);
	vm.runInNewContext(code,sandbox,filename);
	return sandbox.exports;
};

/*
Creates a PasswordPrompt object
*/
$tw.utils.PasswordPrompt = function() {
	// Store of pending password prompts
	this.passwordPrompts = [];
	// Create the wrapper
	this.promptWrapper = $tw.utils.domMaker("div",{"class":"tc-password-wrapper"});
	document.body.appendChild(this.promptWrapper);
	// Hide the empty wrapper
	this.setWrapperDisplay();
};

/*
Hides or shows the wrapper depending on whether there are any outstanding prompts
*/
$tw.utils.PasswordPrompt.prototype.setWrapperDisplay = function() {
	if(this.passwordPrompts.length) {
		this.promptWrapper.style.display = "block";
	} else {
		this.promptWrapper.style.display = "none";
	}
};

/*
Adds a new password prompt. Options are:
submitText: text to use for submit button (defaults to "Login")
serviceName: text of the human readable service name
noUserName: set true to disable username prompt
canCancel: set true to enable a cancel button (callback called with null)
repeatPassword: set true to prompt for the password twice
callback: function to be called on submission with parameter of object {username:,password:}. Callback must return `true` to remove the password prompt
*/
$tw.utils.PasswordPrompt.prototype.createPrompt = function(options) {
	// Create and add the prompt to the DOM
	var self = this,
		submitText = options.submitText || "Login",
		dm = $tw.utils.domMaker,
		children = [dm("h1",{text: options.serviceName})];
	if(!options.noUserName) {
		children.push(dm("input",{
			attributes: {type: "text", name: "username", placeholder: $tw.language.getString("Encryption/Username")}
		}));
	}
	children.push(dm("input",{
		attributes: {
			type: "password",
			name: "password",
			placeholder: ( $tw.language == undefined ? "Password" : $tw.language.getString("Encryption/Password") )
		}
	}));
	if(options.repeatPassword) {
		children.push(dm("input",{
			attributes: {
				type: "password",
				name: "password2",
				placeholder: $tw.language.getString("Encryption/RepeatPassword")
			}
		}));
	}
	if(options.canCancel) {
		children.push(dm("button",{
			text: $tw.language.getString("Encryption/Cancel"),
			attributes: {
				type: "button"
			},
			eventListeners: [{
					name: "click",
					handlerFunction: function(event) {
						self.removePrompt(promptInfo);
						options.callback(null);
					}
				}]
		}));
	}
	children.push(dm("button",{
		attributes: {type: "submit"},
		text: submitText
	}));
	var form = dm("form",{
		attributes: {autocomplete: "off"},
		children: children
	});
	this.promptWrapper.appendChild(form);
	window.setTimeout(function() {
		form.elements[0].focus();
	},10);
	// Add a submit event handler
	var self = this;
	form.addEventListener("submit",function(event) {
		// Collect the form data
		var data = {},t;
		$tw.utils.each(form.elements,function(element) {
			if(element.name && element.value) {
				data[element.name] = element.value;
			}
		});
		// Check that the passwords match
		if(options.repeatPassword && data.password !== data.password2) {
			alert($tw.language.getString("Encryption/PasswordNoMatch"));
		} else {
			// Call the callback
			if(options.callback(data)) {
				// Remove the prompt if the callback returned true
				self.removePrompt(promptInfo);
			} else {
				// Clear the password if the callback returned false
				$tw.utils.each(form.elements,function(element) {
					if(element.name === "password" || element.name === "password2") {
						element.value = "";
					}
				});
			}
		}
		event.preventDefault();
		return false;
	},true);
	// Add the prompt to the list
	var promptInfo = {
		serviceName: options.serviceName,
		callback: options.callback,
		form: form,
		owner: this
	};
	this.passwordPrompts.push(promptInfo);
	// Make sure the wrapper is displayed
	this.setWrapperDisplay();
	return promptInfo;
};

$tw.utils.PasswordPrompt.prototype.removePrompt = function(promptInfo) {
	var i = this.passwordPrompts.indexOf(promptInfo);
	if(i !== -1) {
		this.passwordPrompts.splice(i,1);
		promptInfo.form.parentNode.removeChild(promptInfo.form);
		this.setWrapperDisplay();
	}
}

/*
Crypto helper object for encrypted content. It maintains the password text in a closure, and provides methods to change
the password, and to encrypt/decrypt a block of text
*/
$tw.utils.Crypto = function() {
	var sjcl = $tw.node ? (global.sjcl || require("./sjcl.js")) : window.sjcl,
		currentPassword = null,
		callSjcl = function(method,inputText,password) {
			password = password || currentPassword;
			var outputText;
			try {
				if(password) {
					outputText = sjcl[method](password,inputText);
				}
			} catch(ex) {
				console.log("Crypto error:" + ex);
				outputText = null;
			}
			return outputText;
		};
	this.setPassword = function(newPassword) {
		currentPassword = newPassword;
		this.updateCryptoStateTiddler();
	};
	this.updateCryptoStateTiddler = function() {
		if($tw.wiki) {
			var state = currentPassword ? "yes" : "no",
				tiddler = $tw.wiki.getTiddler("$:/isEncrypted");
			if(!tiddler || tiddler.fields.text !== state) {
				$tw.wiki.addTiddler(new $tw.Tiddler({title: "$:/isEncrypted", text: state}));
			}
		}
	};
	this.hasPassword = function() {
		return !!currentPassword;
	}
	this.encrypt = function(text,password) {
		return callSjcl("encrypt",text,password);
	};
	this.decrypt = function(text,password) {
		return callSjcl("decrypt",text,password);
	};
};

/////////////////////////// Module mechanism

/*
Execute the module named 'moduleName'. The name can optionally be relative to the module named 'moduleRoot'
*/
$tw.modules.execute = function(moduleName,moduleRoot) {
	var name = moduleName;
	if(moduleName.charAt(0) === ".") {
		name = $tw.utils.resolvePath(moduleName,moduleRoot)
	}
	if(!$tw.modules.titles[name]) {
		if($tw.modules.titles[name + ".js"]) {
			name = name + ".js";
		} else if($tw.modules.titles[name + "/index.js"]) {
			name = name + "/index.js";
		} else if($tw.modules.titles[moduleName]) {
			name = moduleName;
		} else if($tw.modules.titles[moduleName + ".js"]) {
			name = moduleName + ".js";
		} else if($tw.modules.titles[moduleName + "/index.js"]) {
			name = moduleName + "/index.js";
		}
	}
	var moduleInfo = $tw.modules.titles[name],
		tiddler = $tw.wiki.getTiddler(name),
		_exports = {},
		sandbox = {
			module: {exports: _exports},
			//moduleInfo: moduleInfo,
			exports: _exports,
			console: console,
			setInterval: setInterval,
			clearInterval: clearInterval,
			setTimeout: setTimeout,
			clearTimeout: clearTimeout,
			Buffer: $tw.browser ? undefined : Buffer,
			$tw: $tw,
			require: function(title) {
				return $tw.modules.execute(title, name);
			}
		};

	Object.defineProperty(sandbox.module, "id", {
		value: name,
		writable: false,
		enumerable: true,
		configurable: false
	});

	if(!$tw.browser) {
		$tw.utils.extend(sandbox,{
			process: process
		});
	} else {
		/*
		CommonJS optional require.main property:
		 In a browser we offer a fake main module which points back to the boot function
		 (Theoretically, this may allow TW to eventually load itself as a module in the browser)
		*/
		Object.defineProperty(sandbox.require, "main", {
			value: (typeof(require) !== "undefined") ? require.main : {TiddlyWiki: _boot},
			writable: false,
			enumerable: true,
			configurable: false
		});
	}
	if(!moduleInfo) {
		// We could not find the module on this path
		// Try to defer to browserify etc, or node
		var deferredModule;
		if($tw.browser) {
			if(window.require) {
				try {
					return window.require(moduleName);
				} catch(e) {}
			}
			throw "Cannot find module named '" + moduleName + "' required by module '" + moduleRoot + "', resolved to " + name;
		} else {
			// If we don't have a module with that name, let node.js try to find it
			return require(moduleName);
		}
	}
	// Execute the module if we haven't already done so
	if(!moduleInfo.exports) {
		try {
			// Check the type of the definition
			if(typeof moduleInfo.definition === "function") { // Function
				moduleInfo.exports = _exports;
				moduleInfo.definition(moduleInfo,moduleInfo.exports,sandbox.require);
			} else if(typeof moduleInfo.definition === "string") { // String
				moduleInfo.exports = _exports;
				$tw.utils.evalSandboxed(moduleInfo.definition,sandbox,tiddler.fields.title);
				if(sandbox.module.exports) {
					moduleInfo.exports = sandbox.module.exports; //more codemirror workaround
				}
			} else { // Object
				moduleInfo.exports = moduleInfo.definition;
			}
		} catch(e) {
			if (e instanceof SyntaxError) {
				var line = e.lineNumber || e.line; // Firefox || Safari
				if (typeof(line) != "undefined" && line !== null) {
					$tw.utils.error("Syntax error in boot module " + name + ":" + line + ":\n" + e.stack);
				} else if(!$tw.browser) {
					// this is the only way to get node.js to display the line at which the syntax error appeared,
					// and $tw.utils.error would exit anyway
					// cf. https://bugs.chromium.org/p/v8/issues/detail?id=2589
					throw e;
				} else {
					// Opera: line number is included in e.message
					// Chrome/IE: there's currently no way to get the line number
					$tw.utils.error("Syntax error in boot module " + name + ": " + e.message + "\n" + e.stack);
				}
			} else {
				// line number should be included in e.stack for runtime errors
				$tw.utils.error("Error executing boot module " + name + ": " + JSON.stringify(e) + "\n\n" + e.stack);
			}
		}
	}
	// Return the exports of the module
	return moduleInfo.exports;
};

/*
Apply a callback to each module of a particular type
	moduleType: type of modules to enumerate
	callback: function called as callback(title,moduleExports) for each module
*/
$tw.modules.forEachModuleOfType = function(moduleType,callback) {
	var modules = $tw.modules.types[moduleType];
	$tw.utils.each(modules,function(element,title) {
		callback(title,$tw.modules.execute(title));
	});
};

/*
Get all the modules of a particular type in a hashmap by their `name` field
*/
$tw.modules.getModulesByTypeAsHashmap = function(moduleType,nameField) {
	nameField = nameField || "name";
	var results = Object.create(null);
	$tw.modules.forEachModuleOfType(moduleType,function(title,module) {
		results[module[nameField]] = module;
	});
	return results;
};

/*
Apply the exports of the modules of a particular type to a target object
*/
$tw.modules.applyMethods = function(moduleType,targetObject) {
	if(!targetObject) {
		targetObject = Object.create(null);
	}
	$tw.modules.forEachModuleOfType(moduleType,function(title,module) {
		$tw.utils.each(module,function(element,title,object) {
			targetObject[title] = module[title];
		});
	});
	return targetObject;
};

/*
Return a class created from a modules. The module should export the properties to be added to those of the optional base class
*/
$tw.modules.createClassFromModule = function(moduleExports,baseClass) {
	var newClass = function() {};
	if(baseClass) {
		newClass.prototype = new baseClass();
		newClass.prototype.constructor = baseClass;
	}
	$tw.utils.extend(newClass.prototype,moduleExports);
	return newClass;
};

/*
Return an array of classes created from the modules of a specified type. Each module should export the properties to be added to those of the optional base class
*/
$tw.modules.createClassesFromModules = function(moduleType,subType,baseClass) {
	var classes = Object.create(null);
	$tw.modules.forEachModuleOfType(moduleType,function(title,moduleExports) {
		if(!subType || moduleExports.types[subType]) {
			classes[moduleExports.name] = $tw.modules.createClassFromModule(moduleExports,baseClass);
		}
	});
	return classes;
};

/////////////////////////// Barebones tiddler object

/*
Construct a tiddler object from a hashmap of tiddler fields. If multiple hasmaps are provided they are merged,
taking precedence to the right
*/
$tw.Tiddler = function(/* [fields,] fields */) {
	this.fields = Object.create(null);
	this.cache = Object.create(null);
	for(var c=0; c<arguments.length; c++) {
		var arg = arguments[c],
			src = (arg instanceof $tw.Tiddler) ? arg.fields : arg;
		for(var t in src) {
			if(src[t] === undefined || src[t] === null) {
				if(t in this.fields) {
					delete this.fields[t]; // If we get a field that's undefined, delete any previous field value
				}
			} else {
				// Parse the field with the associated field module (if any)
				var fieldModule = $tw.Tiddler.fieldModules[t],
					value;
				if(fieldModule && fieldModule.parse) {
					value = fieldModule.parse.call(this,src[t]);
				} else {
					value = src[t];
				}
				// Freeze the field to keep it immutable
				if(value != null && typeof value === "object") {
					Object.freeze(value);
				}
				this.fields[t] = value;
			}
		}
	}
	// Freeze the tiddler against modification
	Object.freeze(this.fields);
	Object.freeze(this);
};

$tw.Tiddler.prototype.hasField = function(field) {
	return $tw.utils.hop(this.fields,field);
};

/*
Compare two tiddlers for equality
tiddler: the tiddler to compare
excludeFields: array of field names to exclude from the comparison
*/
$tw.Tiddler.prototype.isEqual = function(tiddler,excludeFields) {
	if(!(tiddler instanceof $tw.Tiddler)) {
		return false;
	}
	excludeFields = excludeFields || [];
	var self = this,
		differences = []; // Fields that have differences
	// Add to the differences array
	function addDifference(fieldName) {
		// Check for this field being excluded
		if(excludeFields.indexOf(fieldName) === -1) {
			// Save the field as a difference
			$tw.utils.pushTop(differences,fieldName);
		}
	}
	// Returns true if the two values of this field are equal
	function isFieldValueEqual(fieldName) {
		var valueA = self.fields[fieldName],
			valueB = tiddler.fields[fieldName];
		// Check for identical string values
		if(typeof(valueA) === "string" && typeof(valueB) === "string" && valueA === valueB) {
			return true;
		}
		// Check for identical array values
		if($tw.utils.isArray(valueA) && $tw.utils.isArray(valueB) && $tw.utils.isArrayEqual(valueA,valueB)) {
			return true;
		}
		// Check for identical date values
		if($tw.utils.isDate(valueA) && $tw.utils.isDate(valueB) && valueA.getTime() === valueB.getTime()) {
			return true;
		}
		// Otherwise the fields must be different
		return false;
	}
	// Compare our fields
	for(var fieldName in this.fields) {
		if(!isFieldValueEqual(fieldName)) {
			addDifference(fieldName);
		}
	}
	// There's a difference for every field in the other tiddler that we don't have
	for(fieldName in tiddler.fields) {
		if(!(fieldName in this.fields)) {
			addDifference(fieldName);
		}
	}
	// Return whether there were any differences
	return differences.length === 0;
};

/*
Register and install the built in tiddler field modules
*/
$tw.modules.define("$:/boot/tiddlerfields/modified","tiddlerfield",{
	name: "modified",
	parse: $tw.utils.parseDate,
	stringify: $tw.utils.stringifyDate
});
$tw.modules.define("$:/boot/tiddlerfields/created","tiddlerfield",{
	name: "created",
	parse: $tw.utils.parseDate,
	stringify: $tw.utils.stringifyDate
});
$tw.modules.define("$:/boot/tiddlerfields/color","tiddlerfield",{
	name: "color",
	editTag: "input",
	editType: "color"
});
$tw.modules.define("$:/boot/tiddlerfields/tags","tiddlerfield",{
	name: "tags",
	parse: $tw.utils.parseStringArray,
	stringify: $tw.utils.stringifyList
});
$tw.modules.define("$:/boot/tiddlerfields/list","tiddlerfield",{
	name: "list",
	parse: $tw.utils.parseStringArray,
	stringify: $tw.utils.stringifyList
});

/////////////////////////// Barebones wiki store

/*
Wiki constructor. State is stored in private members that only a small number of privileged accessor methods have direct access. Methods added via the prototype have to use these accessors and cannot access the state data directly.
options include:
enableIndexers - Array of indexer names to enable, or null to use all available indexers
*/
$tw.Wiki = function(options) {
	options = options || {};
	var self = this,
		tiddlers = Object.create(null), // Hashmap of tiddlers
		tiddlerTitles = null, // Array of tiddler titles
		getTiddlerTitles = function() {
			if(!tiddlerTitles) {
				tiddlerTitles = Object.keys(tiddlers).sort(function(a,b) {return a.localeCompare(b);});
			}
			return tiddlerTitles;
		},
		pluginTiddlers = [], // Array of tiddlers containing registered plugins, ordered by priority
		pluginInfo = Object.create(null), // Hashmap of parsed plugin content
		shadowTiddlers = Object.create(null), // Hashmap by title of {source:, tiddler:}
		shadowTiddlerTitles = null,
		getShadowTiddlerTitles = function() {
			if(!shadowTiddlerTitles) {
				shadowTiddlerTitles = Object.keys(shadowTiddlers);
			}
			return shadowTiddlerTitles;
		},
		enableIndexers = options.enableIndexers || null,
		indexers = [],
		indexersByName = Object.create(null);

	this.addIndexer = function(indexer,name) {
		// Bail if this indexer is not enabled
		if(enableIndexers && enableIndexers.indexOf(name) === -1) {
			return;
		}
		indexers.push(indexer);
		indexersByName[name] = indexer;
		indexer.init();
	};

	this.getIndexer = function(name) {
		return indexersByName[name] || null;
	};

	// Add a tiddler to the store
	this.addTiddler = function(tiddler) {
		if(!(tiddler instanceof $tw.Tiddler)) {
			tiddler = new $tw.Tiddler(tiddler);
		}
		// Save the tiddler
		if(tiddler) {
			var title = tiddler.fields.title;
			if(title) {
// Uncomment the following line for detailed logs of all tiddler writes
// console.log("Adding",title,tiddler)
				// Record the old tiddler state
				var updateDescriptor = {
					old: {
						tiddler: this.getTiddler(title),
						shadow: this.isShadowTiddler(title),
						exists: this.tiddlerExists(title)
					}
				}
				// Save the new tiddler
				tiddlers[title] = tiddler;
				// Check we've got the title
				tiddlerTitles = $tw.utils.insertSortedArray(tiddlerTitles || [],title);
				// Record the new tiddler state
				updateDescriptor["new"] = {
					tiddler: tiddler,
					shadow: this.isShadowTiddler(title),
					exists: this.tiddlerExists(title)
				}
				// Update indexes
				this.clearCache(title);
				this.clearGlobalCache();
				$tw.utils.each(indexers,function(indexer) {
					indexer.update(updateDescriptor);
				});
				// Queue a change event
				this.enqueueTiddlerEvent(title);
			}
		}
	};

	// Delete a tiddler
	this.deleteTiddler = function(title) {
// Uncomment the following line for detailed logs of all tiddler deletions
// console.log("Deleting",title)
		if($tw.utils.hop(tiddlers,title)) {
			// Record the old tiddler state
			var updateDescriptor = {
				old: {
					tiddler: this.getTiddler(title),
					shadow: this.isShadowTiddler(title),
					exists: this.tiddlerExists(title)
				}
			}
			// Delete the tiddler
			delete tiddlers[title];
			// Delete it from the list of titles
			if(tiddlerTitles) {
				var index = tiddlerTitles.indexOf(title);
				if(index !== -1) {
					tiddlerTitles.splice(index,1);
				}
			}
			// Record the new tiddler state
			updateDescriptor["new"] = {
				tiddler: this.getTiddler(title),
				shadow: this.isShadowTiddler(title),
				exists: this.tiddlerExists(title)
			}
			// Update indexes
			this.clearCache(title);
			this.clearGlobalCache();
			$tw.utils.each(indexers,function(indexer) {
				indexer.update(updateDescriptor);
			});
			// Queue a change event
			this.enqueueTiddlerEvent(title,true);
		}
	};

	// Get a tiddler from the store
	this.getTiddler = function(title) {
		if(title) {
			var t = tiddlers[title];
			if(t !== undefined) {
				return t;
			} else {
				var s = shadowTiddlers[title];
				if(s !== undefined) {
					return s.tiddler;
				}
			}
		}
		return undefined;
	};

	// Get an array of all tiddler titles
	this.allTitles = function() {
		return getTiddlerTitles().slice(0);
	};

	// Iterate through all tiddler titles
	this.each = function(callback) {
		var titles = getTiddlerTitles(),
			index,titlesLength,title;
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			callback(tiddlers[title],title);
		}
	};

	// Get an array of all shadow tiddler titles
	this.allShadowTitles = function() {
		return getShadowTiddlerTitles().slice(0);
	};

	// Iterate through all shadow tiddler titles
	this.eachShadow = function(callback) {
		var titles = getShadowTiddlerTitles(),
			index,titlesLength,title;
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			if(tiddlers[title]) {
				callback(tiddlers[title],title);
			} else {
				var shadowInfo = shadowTiddlers[title];
				callback(shadowInfo.tiddler,title);
			}
		}
	};

	// Iterate through all tiddlers and then the shadows
	this.eachTiddlerPlusShadows = function(callback) {
		var index,titlesLength,title,
			titles = getTiddlerTitles();
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			callback(tiddlers[title],title);
		}
		titles = getShadowTiddlerTitles();
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			if(!tiddlers[title]) {
				var shadowInfo = shadowTiddlers[title];
				callback(shadowInfo.tiddler,title);
			}
		}
	};

	// Iterate through all the shadows and then the tiddlers
	this.eachShadowPlusTiddlers = function(callback) {
		var index,titlesLength,title,
			titles = getShadowTiddlerTitles();
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			if(tiddlers[title]) {
				callback(tiddlers[title],title);
			} else {
				var shadowInfo = shadowTiddlers[title];
				callback(shadowInfo.tiddler,title);
			}
		}
		titles = getTiddlerTitles();
		for(index = 0, titlesLength = titles.length; index < titlesLength; index++) {
			title = titles[index];
			if(!shadowTiddlers[title]) {
				callback(tiddlers[title],title);
			}
		}
	};

	// Test for the existence of a tiddler (excludes shadow tiddlers)
	this.tiddlerExists = function(title) {
		return !!$tw.utils.hop(tiddlers,title);
	};

	// Determines if a tiddler is a shadow tiddler, regardless of whether it has been overridden by a real tiddler
	this.isShadowTiddler = function(title) {
		return $tw.utils.hop(shadowTiddlers,title);
	};

	this.getShadowSource = function(title) {
		if($tw.utils.hop(shadowTiddlers,title)) {
			return shadowTiddlers[title].source;
		}
		return null;
	};

	// Get an array of all the currently recognised plugin types
	this.getPluginTypes = function() {
		var types = [];
		$tw.utils.each(pluginTiddlers,function(pluginTiddler) {
			var pluginType = pluginTiddler.fields["plugin-type"];
			if(pluginType && types.indexOf(pluginType) === -1) {
				types.push(pluginType);
			}
		});
		return types;
	};

	// Read plugin info for all plugins, or just an array of titles. Returns the number of plugins updated or deleted
	this.readPluginInfo = function(titles) {
		var results = {
			modifiedPlugins: [],
			deletedPlugins: []
		};
		$tw.utils.each(titles || getTiddlerTitles(),function(title) {
			var tiddler = tiddlers[title];
			if(tiddler) {
				if(tiddler.fields.type === "application/json" && tiddler.hasField("plugin-type") && tiddler.fields.text) {
					pluginInfo[tiddler.fields.title] = $tw.utils.parseJSONSafe(tiddler.fields.text);
					results.modifiedPlugins.push(tiddler.fields.title);
				}
			} else {
				if(pluginInfo[title]) {
					delete pluginInfo[title];
					results.deletedPlugins.push(title);
				}
			}
		});
		return results;
	};

	// Get plugin info for a plugin
	this.getPluginInfo = function(title) {
		return pluginInfo[title];
	};

	// Register the plugin tiddlers of a particular type, or null/undefined for any type, optionally restricting registration to an array of tiddler titles. Return the array of titles affected
	this.registerPluginTiddlers = function(pluginType,titles) {
		var self = this,
			registeredTitles = [],
			checkTiddler = function(tiddler,title) {
				if(tiddler && tiddler.fields.type === "application/json" && tiddler.fields["plugin-type"] && (!pluginType || tiddler.fields["plugin-type"] === pluginType)) {
					var disablingTiddler = self.getTiddler("$:/config/Plugins/Disabled/" + title);
					if(title === "$:/core" || !disablingTiddler || (disablingTiddler.fields.text || "").trim() !== "yes") {
						self.unregisterPluginTiddlers(null,[title]); // Unregister the plugin if it's already registered
						pluginTiddlers.push(tiddler);
						registeredTitles.push(tiddler.fields.title);
					}
				}
			};
		if(titles) {
			$tw.utils.each(titles,function(title) {
				checkTiddler(self.getTiddler(title),title);
			});
		} else {
			this.each(function(tiddler,title) {
				checkTiddler(tiddler,title);
			});
		}
		return registeredTitles;
	};

	// Unregister the plugin tiddlers of a particular type, or null/undefined for any type, optionally restricting unregistering to an array of tiddler titles. Returns an array of the titles affected
	this.unregisterPluginTiddlers = function(pluginType,titles) {
		var self = this,
			unregisteredTitles = [];
		// Remove any previous registered plugins of this type
		for(var t=pluginTiddlers.length-1; t>=0; t--) {
			var tiddler = pluginTiddlers[t];
			if(tiddler.fields["plugin-type"] && (!pluginType || tiddler.fields["plugin-type"] === pluginType) && (!titles || titles.indexOf(tiddler.fields.title) !== -1)) {
				unregisteredTitles.push(tiddler.fields.title);
				pluginTiddlers.splice(t,1);
			}
		}
		return unregisteredTitles;
	};

	// Unpack the currently registered plugins, creating shadow tiddlers for their constituent tiddlers
	this.unpackPluginTiddlers = function() {
		var self = this;
		// Sort the plugin titles by the `plugin-priority` field
		pluginTiddlers.sort(function(a,b) {
			if("plugin-priority" in a.fields && "plugin-priority" in b.fields) {
				return a.fields["plugin-priority"] - b.fields["plugin-priority"];
			} else if("plugin-priority" in a.fields) {
				return -1;
			} else if("plugin-priority" in b.fields) {
				return +1;
			} else if(a.fields.title < b.fields.title) {
				return -1;
			} else if(a.fields.title === b.fields.title) {
				return 0;
			} else {
				return +1;
			}
		});
		// Now go through the plugins in ascending order and assign the shadows
		shadowTiddlers = Object.create(null);
		$tw.utils.each(pluginTiddlers,function(tiddler) {
			// Extract the constituent tiddlers
			if($tw.utils.hop(pluginInfo,tiddler.fields.title)) {
				$tw.utils.each(pluginInfo[tiddler.fields.title].tiddlers,function(constituentTiddler,constituentTitle) {
					// Save the tiddler object
					if(constituentTitle) {
						shadowTiddlers[constituentTitle] = {
							source: tiddler.fields.title,
							tiddler: new $tw.Tiddler(constituentTiddler,{title: constituentTitle})
						};
					}
				});
			}
		});
		shadowTiddlerTitles = null;
		this.clearCache(null);
		this.clearGlobalCache();
		$tw.utils.each(indexers,function(indexer) {
			indexer.rebuild();
		});
	};

	if(this.addIndexersToWiki) {
		this.addIndexersToWiki();
	}
};

// Dummy methods that will be filled in after boot
$tw.Wiki.prototype.clearCache =
$tw.Wiki.prototype.clearGlobalCache =
$tw.Wiki.prototype.enqueueTiddlerEvent = function() {};

// Add an array of tiddlers
$tw.Wiki.prototype.addTiddlers = function(tiddlers) {
	for(var t=0; t<tiddlers.length; t++) {
		this.addTiddler(tiddlers[t]);
	}
};

/*
Define all modules stored in ordinary tiddlers
*/
$tw.Wiki.prototype.defineTiddlerModules = function() {
	this.each(function(tiddler,title) {
		if(tiddler.hasField("module-type")) {
			switch (tiddler.fields.type) {
				case "application/javascript":
					// We only define modules that haven't already been defined, because in the browser modules in system tiddlers are defined in inline script
					if(!$tw.utils.hop($tw.modules.titles,tiddler.fields.title)) {
						$tw.modules.define(tiddler.fields.title,tiddler.fields["module-type"],tiddler.fields.text);
					}
					break;
				case "application/json":
					$tw.modules.define(tiddler.fields.title,tiddler.fields["module-type"],$tw.utils.parseJSONSafe(tiddler.fields.text));
					break;
				case "application/x-tiddler-dictionary":
					$tw.modules.define(tiddler.fields.title,tiddler.fields["module-type"],$tw.utils.parseFields(tiddler.fields.text));
					break;
			}
		}
	});
};

/*
Register all the module tiddlers that have a module type
*/
$tw.Wiki.prototype.defineShadowModules = function() {
	var self = this;
	this.eachShadow(function(tiddler,title) {
		// Don't define the module if it is overidden by an ordinary tiddler
		if(!self.tiddlerExists(title) && tiddler.hasField("module-type")) {
			// Define the module
			$tw.modules.define(tiddler.fields.title,tiddler.fields["module-type"],tiddler.fields.text);
		}
	});
};

/*
Enable safe mode by deleting any tiddlers that override a shadow tiddler
*/
$tw.Wiki.prototype.processSafeMode = function() {
	var self = this,
		overrides = [];
	// Find the overriding tiddlers
	this.each(function(tiddler,title) {
		if(self.isShadowTiddler(title)) {
			console.log(title);
			overrides.push(title);
		}
	});
	// Assemble a report tiddler
	var titleReportTiddler = "TiddlyWiki Safe Mode",
		report = [];
	report.push("TiddlyWiki has been started in [[safe mode|https://tiddlywiki.com/static/SafeMode.html]]. All plugins are temporarily disabled. Most customisations have been disabled by renaming the following tiddlers:")
	// Delete the overrides
	overrides.forEach(function(title) {
		var tiddler = self.getTiddler(title),
			newTitle = "SAFE: " + title;
		self.deleteTiddler(title);
		self.addTiddler(new $tw.Tiddler(tiddler, {title: newTitle}));
		report.push("* [[" + title + "|" + newTitle + "]]");
	});
	report.push()
	this.addTiddler(new $tw.Tiddler({title: titleReportTiddler, text: report.join("\n\n")}));
	// Set $:/DefaultTiddlers to point to our report
	this.addTiddler(new $tw.Tiddler({title: "$:/DefaultTiddlers", text: "[[" + titleReportTiddler + "]]"}));
};

/*
Extracts tiddlers from a typed block of text, specifying default field values
*/
$tw.Wiki.prototype.deserializeTiddlers = function(type,text,srcFields,options) {
	srcFields = srcFields || Object.create(null);
	options = options || {};
	var deserializer = $tw.Wiki.tiddlerDeserializerModules[options.deserializer],
		fields = Object.create(null);
	if(!deserializer) {
		deserializer = $tw.Wiki.tiddlerDeserializerModules[type];
	}
	if(!deserializer && $tw.utils.getFileExtensionInfo(type)) {
		// If we didn't find the serializer, try converting it from an extension to a content type
		type = $tw.utils.getFileExtensionInfo(type).type;
		deserializer = $tw.Wiki.tiddlerDeserializerModules[type];
	}
	if(!deserializer && $tw.config.contentTypeInfo[type]) {
		// see if this type has a different deserializer registered with it
		type = $tw.config.contentTypeInfo[type].deserializerType;
		deserializer = $tw.Wiki.tiddlerDeserializerModules[type];
	}
	if(!deserializer) {
		// If we still don't have a deserializer, treat it as plain text
		deserializer = $tw.Wiki.tiddlerDeserializerModules["text/plain"];
	}
	for(var f in srcFields) {
		fields[f] = srcFields[f];
	}
	if(deserializer) {
		return deserializer.call(this,text,fields,type);
	} else {
		// Return a raw tiddler for unknown types
		fields.text = text;
		return [fields];
	}
};

/*
Register the built in tiddler deserializer modules
*/
var deserializeHeaderComment = function(text,fields) {
		var headerCommentRegExp = new RegExp($tw.config.jsModuleHeaderRegExpString,"mg"),
			match = headerCommentRegExp.exec(text);
		fields.text = text;
		if(match) {
			fields = $tw.utils.parseFields(match[1].split(/\r?\n\r?\n/mg)[0],fields);
		}
		return [fields];
	};
$tw.modules.define("$:/boot/tiddlerdeserializer/js","tiddlerdeserializer",{
	"application/javascript": deserializeHeaderComment
});
$tw.modules.define("$:/boot/tiddlerdeserializer/css","tiddlerdeserializer",{
	"text/css": deserializeHeaderComment
});
$tw.modules.define("$:/boot/tiddlerdeserializer/tid","tiddlerdeserializer",{
	"application/x-tiddler": function(text,fields) {
		var split = text.split(/\r?\n\r?\n/mg);
		if(split.length >= 1) {
			fields = $tw.utils.parseFields(split[0],fields);
		}
		if(split.length >= 2) {
			fields.text = split.slice(1).join("\n\n");
		}
		return [fields];
	}
});
$tw.modules.define("$:/boot/tiddlerdeserializer/tids","tiddlerdeserializer",{
	"application/x-tiddlers": function(text,fields) {
		var titles = [],
			tiddlers = [],
			match = /\r?\n\r?\n/mg.exec(text);
		if(match) {
			fields = $tw.utils.parseFields(text.substr(0,match.index),fields);
			var lines = text.substr(match.index + match[0].length).split(/\r?\n/mg);
			for(var t=0; t<lines.length; t++) {
				var line = lines[t];
				if(line.charAt(0) !== "#") {
					var colonPos= line.indexOf(":");
					if(colonPos !== -1) {
						var tiddler = $tw.utils.extend(Object.create(null),fields);
						tiddler.title = (tiddler.title || "") + line.substr(0,colonPos).trim();
						if(titles.indexOf(tiddler.title) !== -1) {
							console.log("Warning: .multids file contains multiple definitions for " + tiddler.title);
						}
						titles.push(tiddler.title);
						tiddler.text = line.substr(colonPos + 2).trim();
						tiddlers.push(tiddler);
					}
				}
			}
		}
		return tiddlers;
	}
});
$tw.modules.define("$:/boot/tiddlerdeserializer/txt","tiddlerdeserializer",{
	"text/plain": function(text,fields,type) {
		fields.text = text;
		fields.type = type || "text/plain";
		return [fields];
	}
});
$tw.modules.define("$:/boot/tiddlerdeserializer/html","tiddlerdeserializer",{
	"text/html": function(text,fields) {
		fields.text = text;
		fields.type = "text/html";
		return [fields];
	}
});
$tw.modules.define("$:/boot/tiddlerdeserializer/json","tiddlerdeserializer",{
	"application/json": function(text,fields) {
		var isTiddlerValid = function(data) {
				// Not valid if it's not an object with a title property
				if(typeof(data) !== "object" || !$tw.utils.hop(data,"title")) {
					return false;
				}
				for(var f in data) {
					if($tw.utils.hop(data,f)) {
						// Check field name doesn't contain control characters
						if(typeof(data[f]) !== "string" || /[\x00-\x1F]/.test(f)) {
							return false;
						}
					}
				}
				return true;
			},
			isTiddlerArrayValid = function(data) {
				for(var t=0; t<data.length; t++) {
					if(!isTiddlerValid(data[t])) {
						return false;
					}
				}
				return true;
			},
			data = $tw.utils.parseJSONSafe(text);
		if($tw.utils.isArray(data) && isTiddlerArrayValid(data)) {
			return data;
		} else if(isTiddlerValid(data)) {
			return [data];
		} else {
			// Plain JSON file
			fields.text = text;
			fields.type = "application/json";
			return [fields];
		}
	}
});

/////////////////////////// Browser definitions

if($tw.browser && !$tw.node) {

/*
Decrypt any tiddlers stored within the element with the ID "encryptedArea". The function is asynchronous to allow the user to be prompted for a password
	callback: function to be called the decryption is complete
*/
$tw.boot.decryptEncryptedTiddlers = function(callback) {
	var encryptedArea = document.getElementById("encryptedStoreArea");
	if(encryptedArea) {
		var encryptedText = encryptedArea.innerHTML,
			prompt = "Enter a password to decrypt this TiddlyWiki";
		// Prompt for the password
		if($tw.utils.hop($tw.boot,"encryptionPrompts")) {
			prompt = $tw.boot.encryptionPrompts.decrypt;
		}
		$tw.passwordPrompt.createPrompt({
			serviceName: prompt,
			noUserName: true,
			submitText: "Decrypt",
			callback: function(data) {
				// Attempt to decrypt the tiddlers
				$tw.crypto.setPassword(data.password);
				var decryptedText = $tw.crypto.decrypt(encryptedText);
				if(decryptedText) {
					var json = $tw.utils.parseJSONSafe(decryptedText);
					for(var title in json) {
						$tw.preloadTiddler(json[title]);
					}
					// Call the callback
					callback();
					// Exit and remove the password prompt
					return true;
				} else {
					// We didn't decrypt everything, so continue to prompt for password
					return false;
				}
			}
		});
	} else {
		// Just invoke the callback straight away if there weren't any encrypted tiddlers
		callback();
	}
};

/*
Register a deserializer that can extract tiddlers from the DOM
*/
$tw.modules.define("$:/boot/tiddlerdeserializer/dom","tiddlerdeserializer",{
	"(DOM)": function(node) {
		var extractTextTiddlers = function(node) {
				var e = node.firstChild;
				while(e && e.nodeName.toLowerCase() !== "pre") {
					e = e.nextSibling;
				}
				var title = node.getAttribute ? node.getAttribute("title") : null;
				if(e && title) {
					var attrs = node.attributes,
						tiddler = {
							text: $tw.utils.htmlDecode(e.innerHTML)
						};
					for(var i=attrs.length-1; i >= 0; i--) {
						tiddler[attrs[i].name] = attrs[i].value;
					}
					return [tiddler];
				} else {
					return null;
				}
			},
			extractModuleTiddlers = function(node) {
				if(node.hasAttribute && node.hasAttribute("data-tiddler-title")) {
					var text = node.innerHTML,
						s = text.indexOf("{"),
						e = text.lastIndexOf("}");
					if(node.hasAttribute("data-module") && s !== -1 && e !== -1) {
						text = text.substring(s+1,e);
					}
					var fields = {text: text},
						attributes = node.attributes;
					for(var a=0; a<attributes.length; a++) {
						if(attributes[a].nodeName.substr(0,13) === "data-tiddler-") {
							fields[attributes[a].nodeName.substr(13)] = attributes[a].value;
						}
					}
					return [fields];
				} else {
					return null;
				}
			},
			t,result = [];
		if(node) {
			var type = (node.getAttribute && node.getAttribute("type")) || null;
			if(type) {
				// A new-style container with an explicit deserialization type
				result = $tw.wiki.deserializeTiddlers(type,node.textContent);
			} else {
				// An old-style container of classic DIV-based tiddlers
				for(t = 0; t < node.childNodes.length; t++) {
					var childNode = node.childNodes[t],
						tiddlers = extractTextTiddlers(childNode);
					tiddlers = tiddlers || extractModuleTiddlers(childNode);
					if(tiddlers) {
						result.push.apply(result,tiddlers);
					}
				}
			}
		}
		return result;
	}
});

$tw.loadTiddlersBrowser = function() {
	// In the browser, we load tiddlers from certain elements
	var containerSelectors = [
		// IDs for old-style v5.1.x tiddler stores
		"#libraryModules",
		"#modules",
		"#bootKernelPrefix",
		"#bootKernel",
		"#styleArea",
		"#storeArea",
		"#systemArea",
		// Classes for new-style v5.2.x JSON tiddler stores
		"script.tiddlywiki-tiddler-store"
	];
	for(var t=0; t<containerSelectors.length; t++) {
		var nodes = document.querySelectorAll(containerSelectors[t]);
		for(var n=0; n<nodes.length; n++) {
			$tw.wiki.addTiddlers($tw.wiki.deserializeTiddlers("(DOM)",nodes[n]));
		}
	}
};

} else {

/////////////////////////// Server definitions

/*
Get any encrypted tiddlers
*/
$tw.boot.decryptEncryptedTiddlers = function(callback) {
	// Storing encrypted tiddlers on the server isn't supported yet
	callback();
};

} // End of if($tw.browser && !$tw.node)

/////////////////////////// Node definitions

if($tw.node) {

/*
Load the tiddlers contained in a particular file (and optionally extract fields from the accompanying .meta file) returned as {filepath:,type:,tiddlers:[],hasMetaFile:}
*/
$tw.loadTiddlersFromFile = function(filepath,fields) {
	var ext = path.extname(filepath),
		extensionInfo = $tw.utils.getFileExtensionInfo(ext),
		type = extensionInfo ? extensionInfo.type : null,
		typeInfo = type ? $tw.config.contentTypeInfo[type] : null,
		data = fs.readFileSync(filepath,typeInfo ? typeInfo.encoding : "utf8"),
		tiddlers = $tw.wiki.deserializeTiddlers(ext,data,fields),
		metadata = $tw.loadMetadataForFile(filepath);
	if(metadata) {
		if(type === "application/json") {
			tiddlers = [{text: data, type: "application/json"}];
		}
		tiddlers = [$tw.utils.extend({},tiddlers[0],metadata)];
	}
	return {filepath: filepath, type: type, tiddlers: tiddlers, hasMetaFile: !!metadata};
};

/*
Load the metadata fields in the .meta file corresponding to a particular file
*/
$tw.loadMetadataForFile = function(filepath) {
	var metafilename = filepath + ".meta";
	if(fs.existsSync(metafilename)) {
		return $tw.utils.parseFields(fs.readFileSync(metafilename,"utf8") || "");
	} else {
		return null;
	}
};

/*
A default set of files for TiddlyWiki to ignore during load.
This matches what NPM ignores, and adds "*.meta" to ignore tiddler
metadata files.
*/
$tw.boot.excludeRegExp = /^\.DS_Store$|^.*\.meta$|^\..*\.swp$|^\._.*$|^\.git$|^\.hg$|^\.lock-wscript$|^\.svn$|^\.wafpickle-.*$|^CVS$|^npm-debug\.log$/;

/*
Load all the tiddlers recursively from a directory, including honouring `tiddlywiki.files` files for drawing in external files. Returns an array of {filepath:,type:,tiddlers: [{..fields...}],hasMetaFile:}. Note that no file information is returned for externally loaded tiddlers, just the `tiddlers` property.
*/
$tw.loadTiddlersFromPath = function(filepath,excludeRegExp) {
	excludeRegExp = excludeRegExp || $tw.boot.excludeRegExp;
	var tiddlers = [];
	if(fs.existsSync(filepath)) {
		var stat = fs.statSync(filepath);
		if(stat.isDirectory()) {
			var files = fs.readdirSync(filepath);
			// Look for a tiddlywiki.files file
			if(files.indexOf("tiddlywiki.files") !== -1) {
				Array.prototype.push.apply(tiddlers,$tw.loadTiddlersFromSpecification(filepath,excludeRegExp));
			} else {
				// If not, read all the files in the directory
				$tw.utils.each(files,function(file) {
					if(!excludeRegExp.test(file) && file !== "plugin.info") {
						tiddlers.push.apply(tiddlers,$tw.loadTiddlersFromPath(filepath + path.sep + file,excludeRegExp));
					}
				});
			}
		} else if(stat.isFile()) {
			tiddlers.push($tw.loadTiddlersFromFile(filepath,{title: filepath}));
		}
	}
	return tiddlers;
};

/*
Load all the tiddlers defined by a `tiddlywiki.files` specification file
filepath: pathname of the directory containing the specification file
*/
$tw.loadTiddlersFromSpecification = function(filepath,excludeRegExp) {
	var tiddlers = [];
	// Read the specification
	var filesInfo = $tw.utils.parseJSONSafe(fs.readFileSync(filepath + path.sep + "tiddlywiki.files","utf8"));
	// Helper to process a file
	var processFile = function(filename,isTiddlerFile,fields,isEditableFile) {
		var extInfo = $tw.config.fileExtensionInfo[path.extname(filename)],
			type = (extInfo || {}).type || fields.type || "text/plain",
			typeInfo = $tw.config.contentTypeInfo[type] || {},
			pathname = path.resolve(filepath,filename),
			text = fs.readFileSync(pathname,typeInfo.encoding || "utf8"),
			metadata = $tw.loadMetadataForFile(pathname) || {},
			fileTiddlers;
		if(isTiddlerFile) {
			fileTiddlers = $tw.wiki.deserializeTiddlers(path.extname(pathname),text,metadata) || [];
		} else {
			fileTiddlers =  [$tw.utils.extend({text: text},metadata)];
		}
		var combinedFields = $tw.utils.extend({},fields,metadata);
		$tw.utils.each(fileTiddlers,function(tiddler) {
			$tw.utils.each(combinedFields,function(fieldInfo,name) {
				if(typeof fieldInfo === "string" || $tw.utils.isArray(fieldInfo)) {
					tiddler[name] = fieldInfo;
				} else {
					var value = tiddler[name];
					switch(fieldInfo.source) {
						case "filename":
							value = path.basename(filename);
							break;
						case "filename-uri-decoded":
							value = $tw.utils.decodeURIComponentSafe(path.basename(filename));
							break;
						case "basename":
							value = path.basename(filename,path.extname(filename));
							break;
						case "basename-uri-decoded":
							value = $tw.utils.decodeURIComponentSafe(path.basename(filename,path.extname(filename)));
							break;
						case "extname":
							value = path.extname(filename);
							break;
						case "created":
							value = new Date(fs.statSync(pathname).birthtime);
							break;
						case "modified":
							value = new Date(fs.statSync(pathname).mtime);
							break;
					}
					if(fieldInfo.prefix) {
						value = fieldInfo.prefix + value;
					}
					if(fieldInfo.suffix) {
						value = value + fieldInfo.suffix;
					}
					tiddler[name] = value;
				}
			});
		});
		if(isEditableFile) {
			tiddlers.push({filepath: pathname, hasMetaFile: !!metadata && !isTiddlerFile, isEditableFile: true, tiddlers: fileTiddlers});
		} else {
			tiddlers.push({tiddlers: fileTiddlers});
		}
	};
	// Helper to recursively search subdirectories
	var getAllFiles = function(dirPath, recurse, arrayOfFiles) {
		recurse = recurse || false;
		arrayOfFiles = arrayOfFiles || [];
		var files = fs.readdirSync(dirPath);
		files.forEach(function(file) {
			if (recurse && fs.statSync(dirPath + path.sep + file).isDirectory()) {
				arrayOfFiles = getAllFiles(dirPath + path.sep + file, recurse, arrayOfFiles);
			} else if(fs.statSync(dirPath + path.sep + file).isFile()){
				arrayOfFiles.push(path.join(dirPath, path.sep, file));
			}
		});
		return arrayOfFiles;
	}
	// Process the listed tiddlers
	$tw.utils.each(filesInfo.tiddlers,function(tidInfo) {
		if(tidInfo.prefix && tidInfo.suffix) {
			tidInfo.fields.text = {prefix: tidInfo.prefix,suffix: tidInfo.suffix};
		} else if(tidInfo.prefix) {
			tidInfo.fields.text = {prefix: tidInfo.prefix};
		} else if(tidInfo.suffix) {
			tidInfo.fields.text = {suffix: tidInfo.suffix};
		}
		processFile(tidInfo.file,tidInfo.isTiddlerFile,tidInfo.fields);
	});
	// Process any listed directories
	$tw.utils.each(filesInfo.directories,function(dirSpec) {
		// Read literal directories directly
		if(typeof dirSpec === "string") {
			var pathname = path.resolve(filepath,dirSpec);
			if(fs.existsSync(pathname) && fs.statSync(pathname).isDirectory()) {
				tiddlers.push.apply(tiddlers,$tw.loadTiddlersFromPath(pathname,excludeRegExp));
			}
		} else {
			// Process directory specifier
			var dirPath = path.resolve(filepath,dirSpec.path);
			if(fs.existsSync(dirPath) && fs.statSync(dirPath).isDirectory()) {
				var	files = getAllFiles(dirPath, dirSpec.searchSubdirectories),
					fileRegExp = new RegExp(dirSpec.filesRegExp || "^.*$"),
					metaRegExp = /^.*\.meta$/;
				for(var t=0; t<files.length; t++) {
					var thisPath = path.relative(filepath, files[t]),
					filename = path.basename(thisPath);
					if(filename !== "tiddlywiki.files" && !metaRegExp.test(filename) && fileRegExp.test(filename)) {
						processFile(thisPath,dirSpec.isTiddlerFile,dirSpec.fields,dirSpec.isEditableFile);
					}
				}
			} else {
				console.log("Warning: a directory in a tiddlywiki.files file does not exist.");
				console.log("dirPath: " + dirPath);
				console.log("tiddlywiki.files location: " + filepath);
			}
		}
	});
	return tiddlers;
};

/*
Load the tiddlers from a plugin folder, and package them up into a proper JSON plugin tiddler
*/
$tw.loadPluginFolder = function(filepath,excludeRegExp) {
	excludeRegExp = excludeRegExp || $tw.boot.excludeRegExp;
	var infoPath = filepath + path.sep + "plugin.info";
	if(fs.existsSync(filepath) && fs.statSync(filepath).isDirectory()) {
		// Read the plugin information
		if(!fs.existsSync(infoPath) || !fs.statSync(infoPath).isFile()) {
			console.log("Warning: missing plugin.info file in " + filepath);
			return null;
		}
		var pluginInfo = $tw.utils.parseJSONSafe(fs.readFileSync(infoPath,"utf8"));
		// Read the plugin files
		var pluginFiles = $tw.loadTiddlersFromPath(filepath,excludeRegExp);
		// Save the plugin tiddlers into the plugin info
		pluginInfo.tiddlers = pluginInfo.tiddlers || Object.create(null);
		for(var f=0; f<pluginFiles.length; f++) {
			var tiddlers = pluginFiles[f].tiddlers;
			for(var t=0; t<tiddlers.length; t++) {
				var tiddler= tiddlers[t];
				if(tiddler.title) {
					pluginInfo.tiddlers[tiddler.title] = tiddler;
				}
			}
		}
		// Give the plugin the same version number as the core if it doesn't have one
		if(!("version" in pluginInfo)) {
			pluginInfo.version = $tw.packageInfo.version;
		}
		// Use "plugin" as the plugin-type if we don't have one
		if(!("plugin-type" in pluginInfo)) {
			pluginInfo["plugin-type"] = "plugin";
		}
		pluginInfo.dependents = pluginInfo.dependents || [];
		pluginInfo.type = "application/json";
		// Set plugin text
		pluginInfo.text = JSON.stringify({tiddlers: pluginInfo.tiddlers});
		delete pluginInfo.tiddlers;
		// Deserialise array fields (currently required for the dependents field)
		for(var field in pluginInfo) {
			if($tw.utils.isArray(pluginInfo[field])) {
				pluginInfo[field] = $tw.utils.stringifyList(pluginInfo[field]);
			}
		}
		return pluginInfo;
	} else {
			return null;
	}
};

/*
name: Name of the plugin to find
paths: array of file paths to search for it
Returns the path of the plugin folder
*/
$tw.findLibraryItem = function(name,paths) {
	var pathIndex = 0;
	do {
		var pluginPath = path.resolve(paths[pathIndex],"./" + name)
		if(fs.existsSync(pluginPath) && fs.statSync(pluginPath).isDirectory()) {
			return pluginPath;
		}
	} while(++pathIndex < paths.length);
	return null;
};

/*
name: Name of the plugin to load
paths: array of file paths to search for it
*/
$tw.loadPlugin = function(name,paths) {
	var pluginPath = $tw.findLibraryItem(name,paths);
	if(pluginPath) {
		var pluginFields = $tw.loadPluginFolder(pluginPath);
		if(pluginFields) {
			$tw.wiki.addTiddler(pluginFields);
			return;
		}
	}
	console.log("Warning: Cannot find plugin '" + name + "'");
};

/*
libraryPath: Path of library folder for these plugins (relative to core path)
envVar: Environment variable name for these plugins
Returns an array of search paths
*/
$tw.getLibraryItemSearchPaths = function(libraryPath,envVar) {
	var pluginPaths = [path.resolve($tw.boot.corePath,libraryPath)],
		env = process.env[envVar];
	if(env) {
		env.split(path.delimiter).map(function(item) {
			if(item) {
				pluginPaths.push(item);
			}
		});
	}
	return pluginPaths;
};

/*
plugins: Array of names of plugins (eg, "tiddlywiki/filesystemadaptor")
libraryPath: Path of library folder for these plugins (relative to core path)
envVar: Environment variable name for these plugins
*/
$tw.loadPlugins = function(plugins,libraryPath,envVar) {
	if(plugins) {
		var pluginPaths = $tw.getLibraryItemSearchPaths(libraryPath,envVar);
		for(var t=0; t<plugins.length; t++) {
			$tw.loadPlugin(plugins[t],pluginPaths);
		}
	}
};

/*
path: path of wiki directory
options:
	parentPaths: array of parent paths that we mustn't recurse into
	readOnly: true if the tiddler file paths should not be retained
*/
$tw.loadWikiTiddlers = function(wikiPath,options) {
	options = options || {};
	var parentPaths = options.parentPaths || [],
		wikiInfoPath = path.resolve(wikiPath,$tw.config.wikiInfo),
		wikiInfo,
		pluginFields;
	// Bail if we don't have a wiki info file
	if(fs.existsSync(wikiInfoPath)) {
		wikiInfo = $tw.utils.parseJSONSafe(fs.readFileSync(wikiInfoPath,"utf8"));
	} else {
		return null;
	}
	// Save the path to the tiddlers folder for the filesystemadaptor
	var config = wikiInfo.config || {};
	if($tw.boot.wikiPath == wikiPath) {
		$tw.boot.wikiTiddlersPath = path.resolve($tw.boot.wikiPath,config["default-tiddler-location"] || $tw.config.wikiTiddlersSubDir);
	}
	// Load any parent wikis
	if(wikiInfo.includeWikis) {
		parentPaths = parentPaths.slice(0);
		parentPaths.push(wikiPath);
		$tw.utils.each(wikiInfo.includeWikis,function(info) {
			if(typeof info === "string") {
				info = {path: info};
			}
			var resolvedIncludedWikiPath = path.resolve(wikiPath,info.path);
			if(parentPaths.indexOf(resolvedIncludedWikiPath) === -1) {
				var subWikiInfo = $tw.loadWikiTiddlers(resolvedIncludedWikiPath,{
					parentPaths: parentPaths,
					readOnly: info["read-only"]
				});
				// Merge the build targets
				wikiInfo.build = $tw.utils.extend([],subWikiInfo.build,wikiInfo.build);
			} else {
				$tw.utils.error("Cannot recursively include wiki " + resolvedIncludedWikiPath);
			}
		});
	}
	// Load any plugins, themes and languages listed in the wiki info file
	$tw.loadPlugins(wikiInfo.plugins,$tw.config.pluginsPath,$tw.config.pluginsEnvVar);
	$tw.loadPlugins(wikiInfo.themes,$tw.config.themesPath,$tw.config.themesEnvVar);
	$tw.loadPlugins(wikiInfo.languages,$tw.config.languagesPath,$tw.config.languagesEnvVar);
	// Load the wiki files, registering them as writable
	var resolvedWikiPath = path.resolve(wikiPath,$tw.config.wikiTiddlersSubDir);
	$tw.utils.each($tw.loadTiddlersFromPath(resolvedWikiPath),function(tiddlerFile) {
		if(!options.readOnly && tiddlerFile.filepath) {
			$tw.utils.each(tiddlerFile.tiddlers,function(tiddler) {
				$tw.boot.files[tiddler.title] = {
					filepath: tiddlerFile.filepath,
					type: tiddlerFile.type,
					hasMetaFile: tiddlerFile.hasMetaFile,
					isEditableFile: config["retain-original-tiddler-path"] || tiddlerFile.isEditableFile || tiddlerFile.filepath.indexOf($tw.boot.wikiTiddlersPath) !== 0
				};
			});
		}
		$tw.wiki.addTiddlers(tiddlerFile.tiddlers);
	});
	if ($tw.boot.wikiPath == wikiPath) {
		// Save the original tiddler file locations if requested
		var output = {}, relativePath, fileInfo;
		for(var title in $tw.boot.files) {
			fileInfo = $tw.boot.files[title];
			if(fileInfo.isEditableFile) {
				relativePath = path.relative($tw.boot.wikiTiddlersPath,fileInfo.filepath);
				fileInfo.originalpath = relativePath;
				output[title] =
					path.sep === "/" ?
					relativePath :
					relativePath.split(path.sep).join("/");
			}
		}
		if(Object.keys(output).length > 0){
			$tw.wiki.addTiddler({title: "$:/config/OriginalTiddlerPaths", type: "application/json", text: JSON.stringify(output)});
		}
	}
	// Load any plugins within the wiki folder
	var wikiPluginsPath = path.resolve(wikiPath,$tw.config.wikiPluginsSubDir);
	if(fs.existsSync(wikiPluginsPath)) {
		var pluginFolders = fs.readdirSync(wikiPluginsPath);
		for(var t=0; t<pluginFolders.length; t++) {
			pluginFields = $tw.loadPluginFolder(path.resolve(wikiPluginsPath,"./" + pluginFolders[t]));
			if(pluginFields) {
				$tw.wiki.addTiddler(pluginFields);
			}
		}
	}
	// Load any themes within the wiki folder
	var wikiThemesPath = path.resolve(wikiPath,$tw.config.wikiThemesSubDir);
	if(fs.existsSync(wikiThemesPath)) {
		var themeFolders = fs.readdirSync(wikiThemesPath);
		for(var t=0; t<themeFolders.length; t++) {
			pluginFields = $tw.loadPluginFolder(path.resolve(wikiThemesPath,"./" + themeFolders[t]));
			if(pluginFields) {
				$tw.wiki.addTiddler(pluginFields);
			}
		}
	}
	// Load any languages within the wiki folder
	var wikiLanguagesPath = path.resolve(wikiPath,$tw.config.wikiLanguagesSubDir);
	if(fs.existsSync(wikiLanguagesPath)) {
		var languageFolders = fs.readdirSync(wikiLanguagesPath);
		for(var t=0; t<languageFolders.length; t++) {
			pluginFields = $tw.loadPluginFolder(path.resolve(wikiLanguagesPath,"./" + languageFolders[t]));
			if(pluginFields) {
				$tw.wiki.addTiddler(pluginFields);
			}
		}
	}
	return wikiInfo;
};

$tw.loadTiddlersNode = function() {
	// Load the boot tiddlers
	$tw.utils.each($tw.loadTiddlersFromPath($tw.boot.bootPath),function(tiddlerFile) {
		$tw.wiki.addTiddlers(tiddlerFile.tiddlers);
	});
	// Load the core tiddlers
	$tw.wiki.addTiddler($tw.loadPluginFolder($tw.boot.corePath));
	// Load any extra plugins
	$tw.utils.each($tw.boot.extraPlugins,function(name) {
		if(name.charAt(0) === "+") { // Relative path to plugin
			var pluginFields = $tw.loadPluginFolder(name.substring(1));
			if(pluginFields) {
				$tw.wiki.addTiddler(pluginFields);
			}
		} else {
			var parts = name.split("/"),
				type = parts[0];
			if(parts.length  === 3 && ["plugins","themes","languages"].indexOf(type) !== -1) {
				$tw.loadPlugins([parts[1] + "/" + parts[2]],$tw.config[type + "Path"],$tw.config[type + "EnvVar"]);
			}
		}
	});
	// Load the tiddlers from the wiki directory
	if($tw.boot.wikiPath) {
		$tw.boot.wikiInfo = $tw.loadWikiTiddlers($tw.boot.wikiPath);
	}
};

// End of if($tw.node)
}

/////////////////////////// Main startup function called once tiddlers have been decrypted

/*
Startup TiddlyWiki
*/
$tw.boot.initStartup = function(options) {
	// Get the URL hash and check for safe mode
	$tw.locationHash = "#";
	if($tw.browser && !$tw.node) {
		if(location.hash === "#:safe") {
			$tw.safeMode = true;
		} else {
			$tw.locationHash = $tw.utils.getLocationHash();
		}
	}
	// Initialise some more $tw properties
	$tw.utils.deepDefaults($tw,{
		modules: { // Information about each module
			titles: Object.create(null), // hashmap by module title of {fn:, exports:, moduleType:}
			types: {} // hashmap by module type of hashmap of exports
		},
		config: { // Configuration overridables
			pluginsPath: "../plugins/",
			themesPath: "../themes/",
			languagesPath: "../languages/",
			editionsPath: "../editions/",
			wikiInfo: "./tiddlywiki.info",
			wikiPluginsSubDir: "./plugins",
			wikiThemesSubDir: "./themes",
			wikiLanguagesSubDir: "./languages",
			wikiTiddlersSubDir: "./tiddlers",
			wikiOutputSubDir: "./output",
			jsModuleHeaderRegExpString: "^\\/\\*\\\\(?:\\r?\\n)((?:^[^\\r\\n]*(?:\\r?\\n))+?)(^\\\\\\*\\/$(?:\\r?\\n)?)",
			fileExtensionInfo: Object.create(null), // Map file extension to {type:}
			contentTypeInfo: Object.create(null), // Map type to {encoding:,extension:}
			pluginsEnvVar: "TIDDLYWIKI_PLUGIN_PATH",
			themesEnvVar: "TIDDLYWIKI_THEME_PATH",
			languagesEnvVar: "TIDDLYWIKI_LANGUAGE_PATH",
			editionsEnvVar: "TIDDLYWIKI_EDITION_PATH"
		},
		log: {}, // Log flags
		unloadTasks: []
	});
	if(!$tw.boot.tasks.readBrowserTiddlers) {
		// For writable tiddler files, a hashmap of title to {filepath:,type:,hasMetaFile:}
		$tw.boot.files = Object.create(null);
		// System paths and filenames
		$tw.boot.bootPath = options.bootPath || path.dirname(module.filename);
		$tw.boot.corePath = path.resolve($tw.boot.bootPath,"../core");
		// If there's no arguments then default to `--help`
		if($tw.boot.argv.length === 0) {
			$tw.boot.argv = ["--help"];
		}
		// Parse any extra plugin references
		$tw.boot.extraPlugins = $tw.boot.extraPlugins || [];
		while($tw.boot.argv[0] && $tw.boot.argv[0].indexOf("+") === 0) {
			$tw.boot.extraPlugins.push($tw.boot.argv[0].substring(1));
			$tw.boot.argv.splice(0,1);
		}
		// If the first command line argument doesn't start with `--` then we
		// interpret it as the path to the wiki folder, which will otherwise default
		// to the current folder
		if($tw.boot.argv[0] && $tw.boot.argv[0].indexOf("--") !== 0) {
			$tw.boot.wikiPath = $tw.boot.argv[0];
			$tw.boot.argv = $tw.boot.argv.slice(1);
		} else {
			$tw.boot.wikiPath = process.cwd();
		}
		// Read package info
		$tw.packageInfo = $tw.packageInfo || require("../package.json");
		// Check node version number
		if(!$tw.utils.checkVersions(process.version.substr(1),$tw.packageInfo.engines.node.substr(2))) {
			$tw.utils.error("TiddlyWiki5 requires node.js version " + $tw.packageInfo.engines.node);
		}
	}
	// Add file extension information
	$tw.utils.registerFileType("text/vnd.tiddlywiki","utf8",".tid");
	$tw.utils.registerFileType("application/x-tiddler","utf8",".tid");
	$tw.utils.registerFileType("application/x-tiddlers","utf8",".multids");
	$tw.utils.registerFileType("application/x-tiddler-html-div","utf8",".tiddler");
	$tw.utils.registerFileType("text/vnd.tiddlywiki2-recipe","utf8",".recipe");
	$tw.utils.registerFileType("text/plain","utf8",".txt");
	$tw.utils.registerFileType("text/css","utf8",".css");
	$tw.utils.registerFileType("text/html","utf8",[".html",".htm"]);
	$tw.utils.registerFileType("application/hta","utf16le",".hta",{deserializerType:"text/html"});
	$tw.utils.registerFileType("application/javascript","utf8",".js");
	$tw.utils.registerFileType("application/json","utf8",".json");
	$tw.utils.registerFileType("application/pdf","base64",".pdf",{flags:["image"]});
	$tw.utils.registerFileType("application/zip","base64",".zip");
	$tw.utils.registerFileType("application/x-zip-compressed","base64",".zip");
	$tw.utils.registerFileType("image/jpeg","base64",[".jpg",".jpeg"],{flags:["image"]});
	$tw.utils.registerFileType("image/jpg","base64",[".jpg",".jpeg"],{flags:["image"]});
	$tw.utils.registerFileType("image/png","base64",".png",{flags:["image"]});
	$tw.utils.registerFileType("image/gif","base64",".gif",{flags:["image"]});
	$tw.utils.registerFileType("image/webp","base64",".webp",{flags:["image"]});
	$tw.utils.registerFileType("image/heic","base64",".heic",{flags:["image"]});
	$tw.utils.registerFileType("image/heif","base64",".heif",{flags:["image"]});
	$tw.utils.registerFileType("image/svg+xml","utf8",".svg",{flags:["image"]});
	$tw.utils.registerFileType("image/vnd.microsoft.icon","base64",".ico",{flags:["image"]});
	$tw.utils.registerFileType("image/x-icon","base64",".ico",{flags:["image"]});
	$tw.utils.registerFileType("application/font-woff","base64",".woff");
	$tw.utils.registerFileType("application/x-font-ttf","base64",".woff");
	$tw.utils.registerFileType("application/font-woff2","base64",".woff2");
	$tw.utils.registerFileType("audio/ogg","base64",".ogg");
	$tw.utils.registerFileType("audio/mp4","base64",[".mp4",".m4a"]);
	$tw.utils.registerFileType("video/ogg","base64",[".ogm",".ogv",".ogg"]);
	$tw.utils.registerFileType("video/webm","base64",".webm");
	$tw.utils.registerFileType("video/mp4","base64",".mp4");
	$tw.utils.registerFileType("audio/mp3","base64",".mp3");
	$tw.utils.registerFileType("text/markdown","utf8",[".md",".markdown"],{deserializerType:"text/x-markdown"});
	$tw.utils.registerFileType("text/x-markdown","utf8",[".md",".markdown"]);
	$tw.utils.registerFileType("application/enex+xml","utf8",".enex");
	$tw.utils.registerFileType("application/vnd.openxmlformats-officedocument.wordprocessingml.document","base64",".docx");
	$tw.utils.registerFileType("application/vnd.openxmlformats-officedocument.spreadsheetml.sheet","base64",".xlsx");
	$tw.utils.registerFileType("application/vnd.openxmlformats-officedocument.presentationml.presentation","base64",".pptx");
	$tw.utils.registerFileType("text/x-bibtex","utf8",".bib",{deserializerType:"application/x-bibtex"});
	$tw.utils.registerFileType("application/x-bibtex","utf8",".bib");
	$tw.utils.registerFileType("application/epub+zip","base64",".epub");
	$tw.utils.registerFileType("application/octet-stream","base64",".octet-stream");
	// Create the wiki store for the app
	$tw.wiki = new $tw.Wiki($tw.safeMode && {enableIndexers: []});
	// Install built in tiddler fields modules
	$tw.Tiddler.fieldModules = $tw.modules.getModulesByTypeAsHashmap("tiddlerfield");
	// Install the tiddler deserializer modules
	$tw.Wiki.tiddlerDeserializerModules = Object.create(null);
	$tw.modules.applyMethods("tiddlerdeserializer",$tw.Wiki.tiddlerDeserializerModules);
	// Call unload handlers in the browser
	if($tw.browser) {
		window.onbeforeunload = function(event) {
			event = event || {};
			var result;
			$tw.utils.each($tw.unloadTasks,function(task) {
				var r = task(event);
				if(r) {
					result = r;
				}
			});
			return result;
		}
	}
};
$tw.boot.loadStartup = function(options){

	// Load tiddlers
	if($tw.boot.tasks.readBrowserTiddlers) {
		$tw.loadTiddlersBrowser();
	} else {
		$tw.loadTiddlersNode();
	}
	// Load any preloaded tiddlers
	if($tw.preloadTiddlers) {
		$tw.wiki.addTiddlers($tw.preloadTiddlers);
	}
	// Give hooks a chance to modify the store
	$tw.hooks.invokeHook("th-boot-tiddlers-loaded");
}
$tw.boot.execStartup = function(options){
	// Unpack plugin tiddlers
	$tw.wiki.readPluginInfo();
	$tw.wiki.registerPluginTiddlers("plugin",$tw.safeMode ? ["$:/core"] : undefined);
	$tw.wiki.unpackPluginTiddlers();
	// Process "safe mode"
	if($tw.safeMode) {
		$tw.wiki.processSafeMode();
	}
	// Register typed modules from the tiddlers we've just loaded
	$tw.wiki.defineTiddlerModules();
	// And any modules within plugins
	$tw.wiki.defineShadowModules();
	// Make sure the crypto state tiddler is up to date
	if($tw.crypto) {
		$tw.crypto.updateCryptoStateTiddler();
	}
	// Gather up any startup modules
	$tw.boot.remainingStartupModules = []; // Array of startup modules
	$tw.modules.forEachModuleOfType("startup",function(title,module) {
		if(module.startup) {
			$tw.boot.remainingStartupModules.push(module);
		}
	});
	// Keep track of the startup tasks that have been executed
	$tw.boot.executedStartupModules = Object.create(null);
	$tw.boot.disabledStartupModules = $tw.boot.disabledStartupModules || [];
	// Repeatedly execute the next eligible task
	$tw.boot.executeNextStartupTask(options.callback);
}
/*
Startup TiddlyWiki
*/
$tw.boot.startup = function(options) {
	options = options || {};
	// Get the URL hash and check for safe mode
	$tw.boot.initStartup(options);
	$tw.boot.loadStartup(options);
	$tw.boot.execStartup(options);
};

/*
Add another unload task
*/
$tw.addUnloadTask = function(task) {
	if($tw.unloadTasks.indexOf(task) === -1) {
		$tw.unloadTasks.push(task);
	}
}

/*
Execute the remaining eligible startup tasks
*/
$tw.boot.executeNextStartupTask = function(callback) {
	// Find the next eligible task
	var taskIndex = 0, task,
		asyncTaskCallback = function() {
			if(task.name) {
				$tw.boot.executedStartupModules[task.name] = true;
			}
			return $tw.boot.executeNextStartupTask(callback);
		};
	while(taskIndex < $tw.boot.remainingStartupModules.length) {
		task = $tw.boot.remainingStartupModules[taskIndex];
		if($tw.boot.isStartupTaskEligible(task)) {
			// Remove this task from the list
			$tw.boot.remainingStartupModules.splice(taskIndex,1);
			// Assemble log message
			var s = ["Startup task:",task.name];
			if(task.platforms) {
				s.push("platforms:",task.platforms.join(","));
			}
			if(task.after) {
				s.push("after:",task.after.join(","));
			}
			if(task.before) {
				s.push("before:",task.before.join(","));
			}
			$tw.boot.log(s.join(" "));
			// Execute task
			if(!$tw.utils.hop(task,"synchronous") || task.synchronous) {
				task.startup();
				if(task.name) {
					$tw.boot.executedStartupModules[task.name] = true;
				}
				return $tw.boot.executeNextStartupTask(callback);
			} else {
				task.startup(asyncTaskCallback);
				return true;
			}
		}
		taskIndex++;
	}
	if(typeof callback === 'function') {
		callback();
	}
	return false;
};

/*
Returns true if we are running on one of the platforms specified in taskModule's
`platforms` array; or if `platforms` property is not defined.
*/
$tw.boot.doesTaskMatchPlatform = function(taskModule) {
	var platforms = taskModule.platforms;
	if(platforms) {
		for(var t=0; t<platforms.length; t++) {
			switch (platforms[t]) {
				case "browser":
					if ($tw.browser) {
						return true;
					}
					break;
				case "node":
					if ($tw.node) {
						return true;
					}
					break;
				default:
					$tw.utils.error("Module " + taskModule.name + ": '" + platforms[t] + "' in export.platforms invalid");
			}
		}
		return false;
	}
	return true;
};

$tw.boot.isStartupTaskEligible = function(taskModule) {
	var t;
	// Check that the platform is correct
	if(!$tw.boot.doesTaskMatchPlatform(taskModule)) {
		return false;
	}
	var name = taskModule.name,
		remaining = $tw.boot.remainingStartupModules;
	if(name) {
		// Fail if this module is disabled
		if($tw.boot.disabledStartupModules.indexOf(name) !== -1) {
			return false;
		}
		// Check that no other outstanding tasks must be executed before this one
		for(t=0; t<remaining.length; t++) {
			var task = remaining[t];
			if(task.before && task.before.indexOf(name) !== -1) {
				if($tw.boot.doesTaskMatchPlatform(task) && (!task.name || $tw.boot.disabledStartupModules.indexOf(task.name) === -1)) {
					return false;
				}
			}
		}
	}
	// Check that all of the tasks that we must be performed after has been done
	var after = taskModule.after;
	if(after) {
		for(t=0; t<after.length; t++) {
			if(!$tw.boot.executedStartupModules[after[t]]) {
				return false;
			}
		}
	}
	return true;
};

/*
Global Hooks mechanism which allows plugins to modify default functionality
*/
$tw.hooks = $tw.hooks || { names: {}};

/*
Add hooks to the  hashmap
*/
$tw.hooks.addHook = function(hookName,definition) {
	if($tw.utils.hop($tw.hooks.names,hookName)) {
		$tw.hooks.names[hookName].push(definition);
	}
	else {
		$tw.hooks.names[hookName] = [definition];
	}
};

/*
Invoke the hook by key
*/
$tw.hooks.invokeHook = function(hookName /*, value,... */) {
	var args = Array.prototype.slice.call(arguments,1);
	if($tw.utils.hop($tw.hooks.names,hookName)) {
		for (var i = 0; i < $tw.hooks.names[hookName].length; i++) {
			args[0] = $tw.hooks.names[hookName][i].apply(null,args);
		}
	}
	return args[0];
};

/////////////////////////// Main boot function to decrypt tiddlers and then startup

$tw.boot.boot = function(callback) {
	// Initialise crypto object
	$tw.crypto = new $tw.utils.Crypto();
	// Initialise password prompter
	if($tw.browser && !$tw.node) {
		$tw.passwordPrompt = new $tw.utils.PasswordPrompt();
	}
	// Preload any encrypted tiddlers
	$tw.boot.decryptEncryptedTiddlers(function() {
		// Startup
		$tw.boot.startup({callback: callback});
	});
};

/////////////////////////// Autoboot in the browser

if($tw.browser && !$tw.boot.suppressBoot) {
	$tw.boot.boot();
}

return $tw;

});

if(typeof(exports) !== "undefined") {
	exports.TiddlyWiki = _boot;
} else {
	_boot(window.$tw);
}
//# sourceURL=$:/boot/boot.js
</script>
</div>
<!--~~ Raw markup for the bottom of the body section ~~-->

</body>
</html>