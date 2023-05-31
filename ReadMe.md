<!DOCTYPE html>
<!-- saved from url=(0034)https://api-documen.readme.io/docs -->
<html ng-app="hub" lang="en" style="" data-color-mode="auto" class=" useReactApp  userLoggedIn"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><script src="./API Documentation_ Direct Debit APIs_files/force-firefox-anchor-jump.js"></script><meta http-equiv="X-UA-Compatible" content="IE=edge"><meta name="readme-deploy" content="4.406.0"><meta name="readme-subdomain" content="api-documen"><meta name="readme-version" content="1.0"><meta name="viewport" content="width=device-width, initial-scale=1.0"><meta name="twitter:card" content="summary_large_image"><meta property="og:site_name" content="Direct Debit API Documentation"><meta property="og:description" content="Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.Direc..."><link id="favicon" rel="shortcut icon" href="https://api-documen.readme.io/favicon.ico" type="image/x-icon"><link rel="canonical" href="https://api-documen.readme.io/docs"><!-- Lightweight jQuery replacement--><script src="./API Documentation_ Direct Debit APIs_files/cash.min.js"></script><!-- Custom CSS--><style>:root{--project-color-primary:#048ef5;--project-color-inverse:#fff;--recipe-button-color:#048ef5;--recipe-button-color-hover:#025491;--recipe-button-color-active:#02375e;--recipe-button-color-focus:rgba(4, 142, 245, 0.25);--recipe-button-color-disabled:#c7e6fe}[id=enterprise] .ReadMeUI[is=AlgoliaSearch]{--project-color-primary:#048ef5;--project-color-inverse:#fff}a{color:#048ef5}a:hover{color:#025491}a.text-muted:hover{color:#048ef5}.btn.btn-primary{background-color:#048ef5}.btn.btn-primary:hover{background-color:#025491}.theme-line #hub-landing-top h2{color:#048ef5}#hub-landing-top .btn:hover{color:#048ef5}.theme-line #hub-landing-top .btn:hover{color:#fff}.theme-solid header#hub-header #header-top{background-color:#048ef5}.theme-solid.header-gradient header#hub-header #header-top{background:linear-gradient(to bottom,#048ef5,#0063ac)}.theme-solid.header-custom header#hub-header #header-top{background-image:url(undefined)}.theme-line header#hub-header #header-top{border-bottom-color:#048ef5}.theme-line header#hub-header #header-top .btn{background-color:#048ef5}header#hub-header #header-top #header-logo{width:40px;height:40px;margin-top:0;background-image:url(https://files.readme.io/97584af-brandmark-white.svg)}html:not(.useReactApp) nav#hub-sidebar ul a:hover:not(.active){color:#048ef5}html:not(.useReactApp) nav#hub-sidebar ul a.active,html:not(.useReactApp) nav#hub-sidebar ul>li.subnav-expanded>a{color:#fff;background-color:#048ef5}html:not(.useReactApp) nav#hub-sidebar ul a.active:not(.active),html:not(.useReactApp) nav#hub-sidebar ul>li.subnav-expanded>a:not(.active){color:#384248}html:not(.useReactApp) nav#hub-sidebar ul.subpages{border-left-color:#048ef5}html:not(.useReactApp) nav#hub-sidebar ul.subpages:after{background-color:#048ef5!important}html:not(.useReactApp) nav#hub-sidebar ul.subpages:after>li>a.subpage.active{color:#fff!important;background-color:#048ef5}#hub-subheader-parent #hub-subheader .hub-subheader-breadcrumbs .dropdown-menu a:hover{background-color:#048ef5}#subheader-links a.active{color:#048ef5!important;box-shadow:inset 0 -2px 0 #048ef5}#subheader-links a:hover{color:#048ef5!important;box-shadow:inset 0 -2px 0 #048ef5;opacity:.7}.discussion .submit-vote.submit-vote-parent.voted a.submit-vote-button{background-color:#048ef5}section#hub-discuss .discussion a .discuss-body h4{color:#048ef5}section#hub-discuss .discussion a:hover .discuss-body h4{color:#025491}#hub-subheader-parent #hub-subheader.sticky-header.sticky{border-bottom-color:#048ef5}#hub-subheader-parent #hub-subheader.sticky-header.sticky .search-box{border-bottom-color:#048ef5}#hub-search-results h3 em{color:#048ef5}.main_background,.tag-item{background:#048ef5!important}.main_background:hover{background:#025491!important}.main_color{color:#048ef5!important}.border_bottom_main_color{border-bottom:2px solid #048ef5}.main_color_hover:hover{color:#048ef5!important}section#hub-discuss h1{color:#048ef5}#hub-reference .hub-api .api-definition .api-try-it-out.active{border-color:#048ef5;background-color:#048ef5}#hub-reference .hub-api .api-definition .api-try-it-out.active:hover{background-color:#025491;border-color:#025491}#hub-reference .hub-api .api-definition .api-try-it-out:hover{border-color:#048ef5;color:#048ef5}#hub-reference .hub-reference .logs .logs-empty .logs-login-button,#hub-reference .hub-reference .logs .logs-login .logs-login-button{background-color:var(--project-color-primary,#048ef5);border-color:var(--project-color-primary,#048ef5)}#hub-reference .hub-reference .logs .logs-empty .logs-login-button:hover,#hub-reference .hub-reference .logs .logs-login .logs-login-button:hover{background-color:#025491;border-color:#025491}#hub-reference .hub-reference .logs .logs-empty>svg>path,#hub-reference .hub-reference .logs .logs-login>svg>path{fill:#048ef5;fill:var(--project-color-primary,#048ef5)}#hub-reference .hub-reference .logs:last-child .logs-empty,#hub-reference .hub-reference .logs:last-child .logs-login{margin-bottom:35px}#hub-reference .hub-reference .hub-reference-section .hub-reference-left header .hub-reference-edit:hover{color:#048ef5}.main-color-accent{border-bottom:3px solid #048ef5;padding-bottom:8px}</style><meta name="loadedProject" content="api-documen"><script>var storedColorMode = `auto` === 'auto' ? window.localStorage.getItem('color-scheme') : `auto`
document.querySelector('[data-color-mode]').setAttribute('data-color-mode', storedColorMode)</script><script id="config" type="application/json" data-json="{&quot;algoliaIndex&quot;:&quot;readme_search_v2&quot;,&quot;asset_url&quot;:&quot;https://cdn.readme.io&quot;,&quot;domain&quot;:&quot;readme.io&quot;,&quot;domainFull&quot;:&quot;https://dash.readme.com&quot;,&quot;dashMetricsUrl&quot;:&quot;https://m.readme.io&quot;,&quot;metricsUrl&quot;:&quot;https://metrics.readme.io&quot;,&quot;wsMetricsUrl&quot;:&quot;wss://m.readme.io&quot;,&quot;releaseVersion&quot;:&quot;4.406.0&quot;,&quot;sentry&quot;:{&quot;enabled&quot;:true,&quot;dsn&quot;:&quot;https://3bbe57a973254129bcb93e47dc0cc46f@o343074.ingest.sentry.io/2052166&quot;,&quot;tracesSampleRate&quot;:0},&quot;sslGenerationService&quot;:&quot;ssl.readmessl.com&quot;}"></script><style>/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }
</style><style>/*
  Name:       material
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-material-palenight.CodeMirror {
  background-color: #292D3E;
  color: #A6ACCD;
}

.cm-s-material-palenight .CodeMirror-gutters {
  background: #292D3E;
  color: #676E95;
  border: none;
}

.cm-s-material-palenight .CodeMirror-guttermarker,
.cm-s-material-palenight .CodeMirror-guttermarker-subtle,
.cm-s-material-palenight .CodeMirror-linenumber {
  color: #676E95;
}

.cm-s-material-palenight .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}

.cm-s-material-palenight div.CodeMirror-selected {
  background: rgba(113, 124, 180, 0.2);
}

.cm-s-material-palenight.CodeMirror-focused div.CodeMirror-selected {
  background: rgba(113, 124, 180, 0.2);
}

.cm-s-material-palenight .CodeMirror-line::selection,
.cm-s-material-palenight .CodeMirror-line>span::selection,
.cm-s-material-palenight .CodeMirror-line>span>span::selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material-palenight .CodeMirror-line::-moz-selection,
.cm-s-material-palenight .CodeMirror-line>span::-moz-selection,
.cm-s-material-palenight .CodeMirror-line>span>span::-moz-selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material-palenight .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
}

.cm-s-material-palenight .cm-keyword {
  color: #C792EA;
}

.cm-s-material-palenight .cm-operator {
  color: #89DDFF;
}

.cm-s-material-palenight .cm-variable-2 {
  color: #EEFFFF;
}

.cm-s-material-palenight .cm-variable-3,
.cm-s-material-palenight .cm-type {
  color: #f07178;
}

.cm-s-material-palenight .cm-builtin {
  color: #FFCB6B;
}

.cm-s-material-palenight .cm-atom {
  color: #F78C6C;
}

.cm-s-material-palenight .cm-number {
  color: #FF5370;
}

.cm-s-material-palenight .cm-def {
  color: #82AAFF;
}

.cm-s-material-palenight .cm-string {
  color: #C3E88D;
}

.cm-s-material-palenight .cm-string-2 {
  color: #f07178;
}

.cm-s-material-palenight .cm-comment {
  color: #676E95;
}

.cm-s-material-palenight .cm-variable {
  color: #f07178;
}

.cm-s-material-palenight .cm-tag {
  color: #FF5370;
}

.cm-s-material-palenight .cm-meta {
  color: #FFCB6B;
}

.cm-s-material-palenight .cm-attribute {
  color: #C792EA;
}

.cm-s-material-palenight .cm-property {
  color: #C792EA;
}

.cm-s-material-palenight .cm-qualifier {
  color: #DECB6B;
}

.cm-s-material-palenight .cm-variable-3,
.cm-s-material-palenight .cm-type {
  color: #DECB6B;
}


.cm-s-material-palenight .cm-error {
  color: rgba(255, 255, 255, 1.0);
  background-color: #FF5370;
}

.cm-s-material-palenight .CodeMirror-matchingbracket {
  text-decoration: underline;
  color: white !important;
}</style><style>/* neo theme for codemirror */

/* Color scheme */

.cm-s-neo.CodeMirror {
  background-color:#ffffff;
  color:#2e383c;
  line-height:1.4375;
}
.cm-s-neo .cm-comment { color:#75787b; }
.cm-s-neo .cm-keyword, .cm-s-neo .cm-property { color:#1d75b3; }
.cm-s-neo .cm-atom,.cm-s-neo .cm-number { color:#75438a; }
.cm-s-neo .cm-node,.cm-s-neo .cm-tag { color:#9c3328; }
.cm-s-neo .cm-string { color:#b35e14; }
.cm-s-neo .cm-variable,.cm-s-neo .cm-qualifier { color:#047d65; }


/* Editor styling */

.cm-s-neo pre {
  padding:0;
}

.cm-s-neo .CodeMirror-gutters {
  border:none;
  border-right:10px solid transparent;
  background-color:transparent;
}

.cm-s-neo .CodeMirror-linenumber {
  padding:0;
  color:#e0e2e5;
}

.cm-s-neo .CodeMirror-guttermarker { color: #1d75b3; }
.cm-s-neo .CodeMirror-guttermarker-subtle { color: #e0e2e5; }

.cm-s-neo .CodeMirror-cursor {
  width: auto;
  border: 0;
  background: rgba(155,157,162,0.37);
  z-index: 1;
}
</style><style>.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}
</style><style>.CodeEditor{}
</style><style>.CodeMirror-simplescroll-horizontal div,.CodeMirror-simplescroll-vertical div{position:absolute;background:#ccc;-moz-box-sizing:border-box;box-sizing:border-box;border:1px solid #bbb;border-radius:2px}.CodeMirror-simplescroll-horizontal,.CodeMirror-simplescroll-vertical{position:absolute;z-index:6;background:#eee}.CodeMirror-simplescroll-horizontal{bottom:0;left:0;height:8px}.CodeMirror-simplescroll-horizontal div{bottom:0;height:100%}.CodeMirror-simplescroll-vertical{right:0;top:0;width:8px}.CodeMirror-simplescroll-vertical div{right:0;width:100%}.CodeMirror-overlayscroll .CodeMirror-scrollbar-filler,.CodeMirror-overlayscroll .CodeMirror-gutter-filler{display:none}.CodeMirror-overlayscroll-horizontal div,.CodeMirror-overlayscroll-vertical div{position:absolute;background:#bcd;border-radius:3px}.CodeMirror-overlayscroll-horizontal,.CodeMirror-overlayscroll-vertical{position:absolute;z-index:6}.CodeMirror-overlayscroll-horizontal{bottom:0;left:0;height:6px}.CodeMirror-overlayscroll-horizontal div{bottom:0;height:100%}.CodeMirror-overlayscroll-vertical{right:0;top:0;width:6px}.CodeMirror-overlayscroll-vertical div{right:0;width:100%}
</style><style>.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay,.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>span,.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>p{color:rgba(255,255,255,0.5)}.CodeEditor.cm-s-material-palenight .cm-highlight{background:rgba(0,0,0,0.25)}.CodeEditor.cm-s-material-palenight .CodeMirror{background:#242e34;color:#fff}.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay,.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>span,.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>p{color:rgba(0,0,0,0.5)}.CodeEditor.cm-s-neo .cm-highlight{background:rgba(0,0,0,0.1)}.CodeEditor.cm-s-neo .CodeMirror{background:#fff;color:#000}.CodeEditor .cm-linerow.cm-overlay,.CodeEditor .cm-linerow.cm-overlay .cm-lineNumber{opacity:0.75}.CodeMirror-scrollbar-filler{display:none !important}.CodeMirror-overlayscroll-horizontal div,.CodeMirror-overlayscroll-vertical div{background:rgba(202,202,202,0.5) !important}.cm-linerow{position:relative;text-indent:47px;transition:background 0.5s cubic-bezier(0.16, 1, 0.3, 1),color 0.5s cubic-bezier(0.16, 1, 0.3, 1),opacity 0.5s cubic-bezier(0.16, 1, 0.3, 1)}.cm-linerow>span,.cm-linerow>p{transition:color 0.5s cubic-bezier(0.16, 1, 0.3, 1)}.cm-lineNumber{color:#676e95;display:inline-block;left:0;margin:0;min-width:43px;padding:0 6px 0 10px;position:absolute;right:auto;text-align:right;text-indent:0;top:0;transition:opacity 0.5s cubic-bezier(0.16, 1, 0.3, 1);-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}
</style><link rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/routes-Logs.e926d2a30c4ca8db9674.js"><link rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/1491.d46d6a0b8581dbf0239f.js"><link rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/routes-GraphQL.0f6b00d22ee90fc493e9.js"><style>.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay,.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>span,.CodeEditor.cm-s-material-palenight:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>p{color:rgba(255,255,255,0.5)}.CodeEditor.cm-s-material-palenight .cm-highlight{background:rgba(0,0,0,0.25)}.CodeEditor.cm-s-material-palenight .CodeMirror{background:#242e34;color:#fff}.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay,.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>span,.CodeEditor.cm-s-neo:not(.CodeEditor-Input_highlight) .cm-linerow.cm-overlay>p{color:rgba(0,0,0,0.5)}.CodeEditor.cm-s-neo .cm-highlight{background:rgba(0,0,0,0.1)}.CodeEditor.cm-s-neo .CodeMirror{background:#fff;color:#000}.CodeEditor .cm-linerow.cm-overlay,.CodeEditor .cm-linerow.cm-overlay .cm-lineNumber{opacity:0.75}.cm-linerow{position:relative;text-indent:47px;transition:background 0.5s cubic-bezier(0.16, 1, 0.3, 1),color 0.5s cubic-bezier(0.16, 1, 0.3, 1),opacity 0.5s cubic-bezier(0.16, 1, 0.3, 1)}.cm-linerow>span,.cm-linerow>p{transition:color 0.5s cubic-bezier(0.16, 1, 0.3, 1)}.cm-lineNumber{color:#676e95;display:inline-block;left:0;margin:0;min-width:43px;padding:0 6px 0 10px;position:absolute;right:auto;text-align:right;text-indent:0;top:0;transition:opacity 0.5s cubic-bezier(0.16, 1, 0.3, 1);-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}
</style><style>/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }
</style><style>/*
  Name:       material
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-material-palenight.CodeMirror {
  background-color: #292D3E;
  color: #A6ACCD;
}

.cm-s-material-palenight .CodeMirror-gutters {
  background: #292D3E;
  color: #676E95;
  border: none;
}

.cm-s-material-palenight .CodeMirror-guttermarker,
.cm-s-material-palenight .CodeMirror-guttermarker-subtle,
.cm-s-material-palenight .CodeMirror-linenumber {
  color: #676E95;
}

.cm-s-material-palenight .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}

.cm-s-material-palenight div.CodeMirror-selected {
  background: rgba(113, 124, 180, 0.2);
}

.cm-s-material-palenight.CodeMirror-focused div.CodeMirror-selected {
  background: rgba(113, 124, 180, 0.2);
}

.cm-s-material-palenight .CodeMirror-line::selection,
.cm-s-material-palenight .CodeMirror-line>span::selection,
.cm-s-material-palenight .CodeMirror-line>span>span::selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material-palenight .CodeMirror-line::-moz-selection,
.cm-s-material-palenight .CodeMirror-line>span::-moz-selection,
.cm-s-material-palenight .CodeMirror-line>span>span::-moz-selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material-palenight .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
}

.cm-s-material-palenight .cm-keyword {
  color: #C792EA;
}

.cm-s-material-palenight .cm-operator {
  color: #89DDFF;
}

.cm-s-material-palenight .cm-variable-2 {
  color: #EEFFFF;
}

.cm-s-material-palenight .cm-variable-3,
.cm-s-material-palenight .cm-type {
  color: #f07178;
}

.cm-s-material-palenight .cm-builtin {
  color: #FFCB6B;
}

.cm-s-material-palenight .cm-atom {
  color: #F78C6C;
}

.cm-s-material-palenight .cm-number {
  color: #FF5370;
}

.cm-s-material-palenight .cm-def {
  color: #82AAFF;
}

.cm-s-material-palenight .cm-string {
  color: #C3E88D;
}

.cm-s-material-palenight .cm-string-2 {
  color: #f07178;
}

.cm-s-material-palenight .cm-comment {
  color: #676E95;
}

.cm-s-material-palenight .cm-variable {
  color: #f07178;
}

.cm-s-material-palenight .cm-tag {
  color: #FF5370;
}

.cm-s-material-palenight .cm-meta {
  color: #FFCB6B;
}

.cm-s-material-palenight .cm-attribute {
  color: #C792EA;
}

.cm-s-material-palenight .cm-property {
  color: #C792EA;
}

.cm-s-material-palenight .cm-qualifier {
  color: #DECB6B;
}

.cm-s-material-palenight .cm-variable-3,
.cm-s-material-palenight .cm-type {
  color: #DECB6B;
}


.cm-s-material-palenight .cm-error {
  color: rgba(255, 255, 255, 1.0);
  background-color: #FF5370;
}

.cm-s-material-palenight .CodeMirror-matchingbracket {
  text-decoration: underline;
  color: white !important;
}</style><style>/* neo theme for codemirror */

/* Color scheme */

.cm-s-neo.CodeMirror {
  background-color:#ffffff;
  color:#2e383c;
  line-height:1.4375;
}
.cm-s-neo .cm-comment { color:#75787b; }
.cm-s-neo .cm-keyword, .cm-s-neo .cm-property { color:#1d75b3; }
.cm-s-neo .cm-atom,.cm-s-neo .cm-number { color:#75438a; }
.cm-s-neo .cm-node,.cm-s-neo .cm-tag { color:#9c3328; }
.cm-s-neo .cm-string { color:#b35e14; }
.cm-s-neo .cm-variable,.cm-s-neo .cm-qualifier { color:#047d65; }


/* Editor styling */

.cm-s-neo pre {
  padding:0;
}

.cm-s-neo .CodeMirror-gutters {
  border:none;
  border-right:10px solid transparent;
  background-color:transparent;
}

.cm-s-neo .CodeMirror-linenumber {
  padding:0;
  color:#e0e2e5;
}

.cm-s-neo .CodeMirror-guttermarker { color: #1d75b3; }
.cm-s-neo .CodeMirror-guttermarker-subtle { color: #e0e2e5; }

.cm-s-neo .CodeMirror-cursor {
  width: auto;
  border: 0;
  background: rgba(155,157,162,0.37);
  z-index: 1;
}
</style><style>.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}
</style><style>.CodeEditor{}
</style><style id="_goober"> @keyframes go2264125279{from{transform:scale(0) rotate(45deg);opacity:0;}to{transform:scale(1) rotate(45deg);opacity:1;}}@keyframes go3020080000{from{transform:scale(0);opacity:0;}to{transform:scale(1);opacity:1;}}@keyframes go463499852{from{transform:scale(0) rotate(90deg);opacity:0;}to{transform:scale(1) rotate(90deg);opacity:1;}}@keyframes go1268368563{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}@keyframes go1310225428{from{transform:scale(0) rotate(45deg);opacity:0;}to{transform:scale(1) rotate(45deg);opacity:1;}}@keyframes go651618207{0%{height:0;width:0;opacity:0;}40%{height:0;width:6px;opacity:1;}100%{opacity:1;height:10px;}}@keyframes go901347462{from{transform:scale(0.6);opacity:0.4;}to{transform:scale(1);opacity:1;}}.go4109123758{z-index:9999;}.go4109123758 > *{pointer-events:auto;}</style><link rel="stylesheet" type="text/css" href="./API Documentation_ Direct Debit APIs_files/index.ccccbfa05ae490f7d57f.css"><meta property="og:image"><title>API Documentation: Direct Debit APIs</title><meta content="API Documentation: Direct Debit APIs" property="og:title"><meta name="description" content="Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.Direc..."></head><body ng-class="{&#39;hub-full&#39;: state.current().opts.full, &#39;hub-reference-parent&#39;: state.current().name.includes(&#39;reference&#39;), &#39;hub-guides-parent&#39;: state.current().name.includes(&#39;docs&#39;), &#39;no-sidebar&#39;: !state.current().opts.sidebar, &#39;hub-is-home&#39;: state.current().name == &#39;home&#39; &amp;&amp; &#39;docs&#39; == &#39;landing&#39;, &#39;hub-suggested-edits&#39;: suggestedEdits.isEnabled}" class="toolbarCount_undefined body-none theme-solid header-solid header-bg-size-auto header-bg-pos-tl header-overlay-triangles reference-layout-row lumosity-normal "><div id="ssr-top"><script>NG_BUNDLES = ["https://cdn.readme.io/public/js/hub2.7e1d2cce93625837ebf9.js","https://cdn.readme.io/public/js/runtime.9e78a8796bf333cd5615.js","https://cdn.readme.io/public/js/vendors.dca14c696102539401b9.js"];</script><link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.1ada8671884e2a5b981e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/Footer.ce31c64f1a0ffb7d435e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Changelog.cad5bec3c55393966d1b.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-GraphQL.f2d3af92ef871087ac03.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/SuperHub.929f5d16267b23c1ad0a.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Discuss.188926678170117f9a58.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Logs.ec687e4939817bd9220e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/Header.d3ecf3304683529b0a5e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Landing.bdff7e649eb6babb416e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Doc.6395c734e10e17d28bce.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/3435.712376fa4a815db02c49.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Reference.b79573f9d765f290015c.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/7552.68baa92913937ef996bb.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/775.d6a5b9d4cbcbc46667ba.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/4003.f1a2d17f7d83782d4d04.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="./API Documentation_ Direct Debit APIs_files/810.4d152e913ccec49edcc5.css">
<link data-chunk="New" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/New.cd3f281d0b09185ae462.css">
<link data-chunk="ngz" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/ngz.01bc90ad45be7ccacf88.css">
<link data-chunk="routes-Suggestions-ngz-Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Suggestions-ngz-Header.0f3cc7b3c9b6779eaadb.css">
<link data-chunk="List" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/List.4182c8122b1d7f67e908.css">
<link data-chunk="Editor" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/Editor.c4d1bf0d80942de0f2e0.css">
<link data-chunk="Page" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/Page.29330b9a37a5b2f9ae85.css">
<link data-chunk="Page" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/5237.7f85fd936563585fd14c.css">
<link data-chunk="routes-Discuss" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Discuss.188926678170117f9a58.css">
<link data-chunk="routes-Reference" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Reference.b79573f9d765f290015c.css">
<link data-chunk="Post" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/Post.04ecd438561f0feaee02.css">
<link data-chunk="routes-Changelog" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Changelog.cad5bec3c55393966d1b.css">
<link data-chunk="routes-PageNotFound" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.1ada8671884e2a5b981e.css">
<link data-chunk="routes-Doc" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Doc.6395c734e10e17d28bce.css">
<link data-chunk="Footer" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/Footer.ce31c64f1a0ffb7d435e.css">
<link data-chunk="routes-Landing" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/routes-Landing.bdff7e649eb6babb416e.css">
<link data-chunk="Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/Header.d3ecf3304683529b0a5e.css">
<link data-chunk="Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/3435.712376fa4a815db02c49.css">
<link data-chunk="Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/7552.68baa92913937ef996bb.css">
<link data-chunk="Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/775.d6a5b9d4cbcbc46667ba.css">
<link data-chunk="Header" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/4003.f1a2d17f7d83782d4d04.css">
<link data-chunk="SuperHub" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/SuperHub.929f5d16267b23c1ad0a.css">
<link data-chunk="SuperHub" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/810.4d152e913ccec49edcc5.css">
<link data-chunk="main" rel="preload" as="style" href="./API Documentation_ Direct Debit APIs_files/main.676a0f4ea7e1507f2ca0.css">
<link data-chunk="main" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/main.fe8f2143b599d626bc1c.js">
<link data-chunk="SuperHub" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/7588.d0ec234c05764b817112.js">
<link data-chunk="SuperHub" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/5585.bb6134c216753e282710.js">
<link data-chunk="SuperHub" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/9156.14658dc3d8f611201899.js">
<link data-chunk="SuperHub" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/105.22bd58d20006978de049.js">
<link data-chunk="SuperHub" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/SuperHub.491ab883a5dd2a460f91.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/2807.3aa20e12efd9c25d3701.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4134.9dd24f2c079a17d11463.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4301.e92eebfb5383857a31d4.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4003.ee4230c1f52ba67fdb01.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/775.d5a8ac18b455514b0c5e.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/7552.fa985385affa26865c32.js">
<link data-chunk="Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/Header.f029887c6e55d26ed9c6.js">
<link data-chunk="routes-Landing" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/1158.c4279af9447c30a12a3a.js">
<link data-chunk="routes-Landing" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/1730.496a9b2e3fc2de3fb2f3.js">
<link data-chunk="routes-Landing" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/6683.2e39c459b33e86fd12e5.js">
<link data-chunk="routes-Landing" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/2926.6ceb29a1bfcee886def7.js">
<link data-chunk="routes-Landing" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Landing.962002218245a3b99f3f.js">
<link data-chunk="Footer" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/Footer.ed749644b3cba8655c14.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4127.6fe612d1b203ef5191f3.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/713.cd13007ec2bac8b6a1ea.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/1581.845926ab06e2fa0f9be2.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/2069.daa15a4d13acfe8f99f1.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/7367.e9df727d550f9dbdb6ca.js">
<link data-chunk="routes-Doc" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Doc.fdbf93e3b7a06afd0634.js">
<link data-chunk="routes-PageNotFound" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.944d69719216150b1549.js">
<link data-chunk="routes-Changelog" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Changelog.b91d70147e95510bbb10.js">
<link data-chunk="Post" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/6265.4d0ff1476b3f59d84c32.js">
<link data-chunk="Post" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/Post.4dc7cb3a600e401a610a.js">
<link data-chunk="routes-Reference" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/9509.04bba54c54fa9dd1c5f5.js">
<link data-chunk="routes-Reference" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/2053.dbbc8cd2a5d634d615e6.js">
<link data-chunk="routes-Reference" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/8457.1d9d61c673fd8b6e3676.js">
<link data-chunk="routes-Reference" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Reference.3a44fdc4ad14d7ba6bcb.js">
<link data-chunk="core-icons-more-vertical-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-more-vertical-svg.228db57c23169aaa56d6.js">
<link data-chunk="core-icons-chevron-down-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-chevron-down-svg.09fdf86b58640880691c.js">
<link data-chunk="core-icons-arrow-right-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-arrow-right-svg.1e7f2192b7bda6b4a5e1.js">
<link data-chunk="CustomPage" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/CustomPage.9dc25d4d0248b160ff3d.js">
<link data-chunk="routes-CustomPage" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-CustomPage.39e8a82f13bff819cb9e.js">
<link data-chunk="routes-Discuss" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4775.c3adf5c11671821d7f08.js">
<link data-chunk="routes-Discuss" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/3393.951a5bb57c48d1f013c6.js">
<link data-chunk="routes-Discuss" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Discuss.a01c70343fbef3cd1c01.js">
<link data-chunk="Page" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4553.7b4d16a51d1bb7ee54a3.js">
<link data-chunk="Page" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/3210.529ad6704964fbc21117.js">
<link data-chunk="Page" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/5237.18898667cd1691af4721.js">
<link data-chunk="Page" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/4141.a8a05e082ed667262ffb.js">
<link data-chunk="Page" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/Page.23ffcc4ca59d55f9da36.js">
<link data-chunk="core-icons-menu-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-menu-svg.b9a5673111bcd429344f.js">
<link data-chunk="Editor" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/9510.e91d25bc50ff7f1ad1c0.js">
<link data-chunk="Editor" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/Editor.8c3adc7fa2cd87f474d3.js">
<link data-chunk="core-icons-x-circle-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-x-circle-svg.1253cc725f6ab78a786d.js">
<link data-chunk="core-icons-suggested-edits-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-suggested-edits-svg.93755393eff5d50dda67.js">
<link data-chunk="core-icons-arrow-up-right-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-arrow-up-right-svg.957c5be2eea3961b4701.js">
<link data-chunk="List" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/List.99613c6b125692b5f28f.js">
<link data-chunk="core-icons-trending-up-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-trending-up-svg.b09fd55fdbf98ea428b4.js">
<link data-chunk="core-icons-callout-info-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-callout-info-svg.991471218275384a0302.js">
<link data-chunk="core-icons-inbox-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-inbox-svg.149edca4fd1e661cba53.js">
<link data-chunk="routes-Tutorials" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Tutorials.62176318efe03678558a.js">
<link data-chunk="core-icons-star-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-star-svg.b4e382f3c0a9bfe7faa8.js">
<link data-chunk="routes-Suggestions-ngz-Header" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Suggestions-ngz-Header.6dd03d5ad8adf3769195.js">
<link data-chunk="ngz" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/ngz.f158c5fcbef9f77398f7.js">
<link data-chunk="core-icons-key-svg" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/core-icons-key-svg.1832e12a64afa7e249a9.js">
<link data-chunk="New" rel="preload" as="script" href="./API Documentation_ Direct Debit APIs_files/New.eb7645286e26aeac12e5.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/7588.d0ec234c05764b817112.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/2807.3aa20e12efd9c25d3701.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/4134.9dd24f2c079a17d11463.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/4127.6fe612d1b203ef5191f3.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/713.cd13007ec2bac8b6a1ea.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/1581.845926ab06e2fa0f9be2.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/2069.daa15a4d13acfe8f99f1.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/9509.04bba54c54fa9dd1c5f5.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/2053.dbbc8cd2a5d634d615e6.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/7367.e9df727d550f9dbdb6ca.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/8457.1d9d61c673fd8b6e3676.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/4003.ee4230c1f52ba67fdb01.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/775.d5a8ac18b455514b0c5e.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/7552.fa985385affa26865c32.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/105.22bd58d20006978de049.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Reference.3a44fdc4ad14d7ba6bcb.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/6683.2e39c459b33e86fd12e5.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Doc.fdbf93e3b7a06afd0634.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/1158.c4279af9447c30a12a3a.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/1730.496a9b2e3fc2de3fb2f3.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/2926.6ceb29a1bfcee886def7.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Landing.962002218245a3b99f3f.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-CustomPage.39e8a82f13bff819cb9e.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/4301.e92eebfb5383857a31d4.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/Header.f029887c6e55d26ed9c6.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Tutorials.62176318efe03678558a.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/3393.951a5bb57c48d1f013c6.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/routes-Logs.e926d2a30c4ca8db9674.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/4775.c3adf5c11671821d7f08.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Discuss.a01c70343fbef3cd1c01.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/5585.bb6134c216753e282710.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/9156.14658dc3d8f611201899.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/SuperHub.491ab883a5dd2a460f91.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/1491.d46d6a0b8581dbf0239f.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="https://cdn.readme.io/public/hub/web/routes-GraphQL.0f6b00d22ee90fc493e9.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-Changelog.b91d70147e95510bbb10.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/Footer.ed749644b3cba8655c14.js">
<link data-parent-chunk="main" rel="prefetch" as="script" href="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.944d69719216150b1549.js">
<link data-chunk="main" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/main.676a0f4ea7e1507f2ca0.css">
<link data-chunk="SuperHub" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/810.4d152e913ccec49edcc5.css">
<link data-chunk="SuperHub" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/SuperHub.929f5d16267b23c1ad0a.css">
<link data-chunk="Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/4003.f1a2d17f7d83782d4d04.css">
<link data-chunk="Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/775.d6a5b9d4cbcbc46667ba.css">
<link data-chunk="Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/7552.68baa92913937ef996bb.css">
<link data-chunk="Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/3435.712376fa4a815db02c49.css">
<link data-chunk="Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/Header.d3ecf3304683529b0a5e.css">
<link data-chunk="routes-Landing" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Landing.bdff7e649eb6babb416e.css">
<link data-chunk="Footer" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/Footer.ce31c64f1a0ffb7d435e.css">
<link data-chunk="routes-Doc" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Doc.6395c734e10e17d28bce.css">
<link data-chunk="routes-PageNotFound" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.1ada8671884e2a5b981e.css">
<link data-chunk="routes-Changelog" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Changelog.cad5bec3c55393966d1b.css">
<link data-chunk="Post" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/Post.04ecd438561f0feaee02.css">
<link data-chunk="routes-Reference" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Reference.b79573f9d765f290015c.css">
<link data-chunk="routes-Discuss" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Discuss.188926678170117f9a58.css">
<link data-chunk="Page" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/5237.7f85fd936563585fd14c.css">
<link data-chunk="Page" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/Page.29330b9a37a5b2f9ae85.css">
<link data-chunk="Editor" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/Editor.c4d1bf0d80942de0f2e0.css">
<link data-chunk="List" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/List.4182c8122b1d7f67e908.css">
<link data-chunk="routes-Suggestions-ngz-Header" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/routes-Suggestions-ngz-Header.0f3cc7b3c9b6779eaadb.css">
<link data-chunk="ngz" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/ngz.01bc90ad45be7ccacf88.css">
<link data-chunk="New" rel="stylesheet" href="./API Documentation_ Direct Debit APIs_files/New.cd3f281d0b09185ae462.css"></div><div id="ssr-main"><div class="App ThemeContext ThemeContext_dark " style="--color-primary: #048ef5; --color-primary-inverse: #fff; --color-primary-alt: #0063ac; --color-primary-darken-10: #0371c3; --color-primary-darken-20: #025491; --color-primary-alpha-25: rgba(4, 142, 245, 0.25); --color-link-primary: #048ef5; --color-link-primary-darken-10: #0371c3; --color-link-primary-darken-20: #025491; --color-link-primary-alpha-50: rgba(4, 142, 245, 0.5); --color-link-primary-alpha-25: rgba(4, 142, 245, 0.25); --color-link-background: rgba(4, 142, 245, 0.09); --color-link-text: #fff; --color-login-link: #118cfd; --color-login-link-text: #fff; --color-login-link-darken-10: #0272d9; --color-login-link-primary-alpha-50: rgba(17, 140, 253, 0.5);"><header class="Header3zzata9F_ZPQ rm-Header "><div class="Header-topuTMpygDG4e1V rm-Header-top"><div class="rm-Container rm-Container_flex"><div style="outline:none" tabindex="-1"><a href="https://api-documen.readme.io/docs#content" target="_self" class="Button Button_md Header-jumpTo3IWKQXmhSI5D rm-JumpTo Button_primary">Jump to Content</a></div><div class="Header-leftADQdGVqx1wqU"><a class="Header-logo1Xy41PtkzbdG rm-Logo" href="https://api-documen.readme.io/docs" target="_self"><img alt="Direct Debit API Documentation" class="Header-logo-img3YvV4lcGKkeb rm-Logo-img " src="./API Documentation_ Direct Debit APIs_files/97584af-brandmark-white.svg"></a></div><div class="Header-leftADQdGVqx1wqU Header-left_mobile1RG-X93lx6PF"><div><div class=""><div class="Flyout95xhYIIoTKtc undefined rm-Flyout" data-testid="flyout"><div class="MobileFlyout1hHJpUd-nYkd"><a aria-current="page" class="NavItem-item1gDDTqaXGhm1 NavItem-item_mobile1qG3gd-Mkck-  active" href="https://api-documen.readme.io/docs" target="_self"><i class="NavItem-item-anchorzz3banOxXKjr icon-guides"></i><span class="NavItem-textSlZuuL489uiw">Guides</span></a><a class="NavItem-item1gDDTqaXGhm1 NavItem-item_mobile1qG3gd-Mkck- NavItem_dropdown-muted1xJVuczwGc74" href="https://api-documen.readme.io/recipes" target="_self"><i class="NavItem-item-anchorzz3banOxXKjr icon-recipes"></i><span class="NavItem-textSlZuuL489uiw">Recipes</span><span class="icon-eye-off NavItem-hiddenS0Zb1tCAe_Vd"></span></a><a class="NavItem-item1gDDTqaXGhm1 NavItem-item_mobile1qG3gd-Mkck- NavItem_dropdown-muted1xJVuczwGc74" href="https://api-documen.readme.io/reference" target="_self"><i class="NavItem-item-anchorzz3banOxXKjr icon-references"></i><span class="NavItem-textSlZuuL489uiw">API Reference</span><span class="icon-eye-off NavItem-hiddenS0Zb1tCAe_Vd"></span></a><a class="NavItem-item1gDDTqaXGhm1 NavItem-item_mobile1qG3gd-Mkck- " href="https://api-documen.readme.io/changelog" target="_self"><i class="NavItem-item-anchorzz3banOxXKjr icon-changelog"></i><span class="NavItem-textSlZuuL489uiw">Changelog</span></a><a class="NavItem-item1gDDTqaXGhm1 NavItem-item_mobile1qG3gd-Mkck- " href="https://api-documen.readme.io/discuss" target="_self"><i class="NavItem-item-anchorzz3banOxXKjr icon-discussions"></i><span class="NavItem-textSlZuuL489uiw">Discussions</span></a><div class="NavItem-item1gDDTqaXGhm1 NavItem-item_inactiveMQoyhN045qAn">v<!-- -->1.0</div><hr class="MobileFlyout-divider10xf7R2X1MeW"><select class="Select Select_md NavItem-item1gDDTqaXGhm1 NavItem-item_select3UEfLN-oSjxp NavItem-item_mobile1qG3gd-Mkck-"><option selected="" data-url="" disabled="" value="Account">Oladele Oluwabukola</option><option data-url="/dash" value="Admin Panel">Admin Panel</option><option data-url="/suggested-edits" value="Suggested Edits">Suggested Edits</option><option data-url="/logout?redirect_uri=/docs" value="Log Out">Log Out</option></select><a class="MobileFlyout-logo3Lq1eTlk1K76 Header-logo1Xy41PtkzbdG rm-Logo" href="https://api-documen.readme.io/docs" target="_self"><img alt="Direct Debit API Documentation" class="Header-logo-img3YvV4lcGKkeb rm-Logo-img" src="./API Documentation_ Direct Debit APIs_files/97584af-brandmark-white.svg"></a></div></div></div><button aria-label="Toggle navigation menu" class="icon-menu menu3d6DYNDa3tk5" type="button"></button></div><div class="Header-left-nav2xWPWMNHOGf_"><i class="icon-guides Header-left-nav-icon10glJKFwewOv"></i>Guides</div></div><div class="Header-right21PC2XTT6aMg"><div class="rm-Header-top-link_login Dropdown Dropdown_closed"><div aria-haspopup="dialog" class="Dropdown-toggle" role="button" aria-expanded="false"><button class="Button Button_slate_text Button_md Header-link2tXYTgXq85zW undefined NavItem_mdrYO3ChA2kYvP rm-Header-top-link Button_primary" type="button"><span>Oladele Oluwabukola</span><span class="IconWrapper Icon-wrapper2z2wVIeGsiUy"><svg fill="none" viewBox="0 0 24 24" aria-labelledby="Icon-chevron-down-bec1b212-2b8e-4511-8ddf-eb2251228fe5" class="Icon Icon3_D2ysxFZ_ll Icon-svg2Lm7f6G9Ly5a undefined" data-name="chevron-down" role="img" style="--icon-color:inherit;--icon-size:var(--icon-md);--icon-stroke-width:2px"><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" d="m6 9 6 6 6-6" class="icon-stroke-width"></path></svg></span></button></div></div><div class="ThemeToggle-wrapper1M_iJESXCpGR Dropdown Dropdown_closed"><div aria-haspopup="dialog" class="Dropdown-toggle" role="button" aria-expanded="false"><button aria-label="Toggle to light mode" id="ThemeToggle-button-2623123f-3107-41d0-abd3-4c212e66c76c" class="Button Button_slate_text Button_sm rm-ThemeToggle ThemeToggle2tVPbUyQbWDo ThemeToggle_active3jPkR2CMm1JP Button_primary" type="button"><svg aria-labelledby="ThemeToggle-button-2623123f-3107-41d0-abd3-4c212e66c76c" class="Icon ThemeToggle-Icon3g9ZT7pRMwCv ThemeToggle-Icon_active18I2-19CkbgD" role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Moon (Dark Mode)</title><path d="M19 14.79C18.8427 16.4922 18.2039 18.1144 17.1582 19.4668C16.1126 20.8192 14.7035 21.8458 13.0957 22.4265C11.4879 23.0073 9.74798 23.1181 8.0795 22.7461C6.41102 22.3741 4.88299 21.5345 3.67423 20.3258C2.46546 19.117 1.62594 17.589 1.25391 15.9205C0.881876 14.252 0.992717 12.5121 1.57346 10.9043C2.1542 9.29651 3.18083 7.88737 4.53321 6.84175C5.8856 5.79614 7.5078 5.15731 9.21 5C8.21341 6.34827 7.73385 8.00945 7.85853 9.68141C7.98322 11.3534 8.70386 12.9251 9.8894 14.1106C11.0749 15.2961 12.6466 16.0168 14.3186 16.1415C15.9906 16.2662 17.6517 15.7866 19 14.79Z"></path><path class="ThemeToggle-Icon-star3wweJby1gM4w" d="M18.3707 1C18.3707 3.22825 16.2282 5.37069 14 5.37069C16.2282 5.37069 18.3707 7.51313 18.3707 9.74138C18.3707 7.51313 20.5132 5.37069 22.7414 5.37069C20.5132 5.37069 18.3707 3.22825 18.3707 1Z"></path></svg><svg aria-labelledby="ThemeToggle-button-2623123f-3107-41d0-abd3-4c212e66c76c" class="Icon ThemeToggle-Icon3g9ZT7pRMwCv " role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Sun (Light Mode)</title><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M12 1V3"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M18.36 5.64L19.78 4.22"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M21 12H23"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M18.36 18.36L19.78 19.78"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M12 21V23"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M4.22 19.78L5.64 18.36"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M1 12H3"></path><path class="ThemeToggle-Icon-ray2ab8_BwBkrTx" d="M4.22 4.22L5.64 5.64"></path><path d="M12 17C14.7614 17 17 14.7614 17 12C17 9.23858 14.7614 7 12 7C9.23858 7 7 9.23858 7 12C7 14.7614 9.23858 17 12 17Z"></path></svg></button></div></div><div class="Header-searchtb6Foi0-D9Vx "><button aria-label="Search" class="rm-SearchToggle" data-symbol="⌘"><div class="icon-search1 rm-SearchToggle-icon"></div></button></div></div></div></div><div class="rm-Header-bottom" style="display:flex"><div class="Header-bottom2eLKOFXMEmh5 "><div class="rm-Container rm-Container_flex"><nav class="Header-leftADQdGVqx1wqU"><span class="undefined NavItem_inactive1YE6SGanIJp5 rm-Header-bottom-link">v<!-- -->1.0</span><a aria-current="page" class="Button Button_md Button_slate_text rm-Header-bottom-link  active" href="https://api-documen.readme.io/docs" target="_self"><i class="icon-guides"></i><span>Guides</span></a><a class="Button Button_md Button_slate_text rm-Header-bottom-link NavItem_muted2-OqeulnYimX" href="https://api-documen.readme.io/recipes" target="_self"><i class="icon-recipes"></i><span>Recipes</span><span class="icon-eye-off NavItem-hiddenS0Zb1tCAe_Vd"></span></a><a class="Button Button_md Button_slate_text rm-Header-bottom-link NavItem_muted2-OqeulnYimX" href="https://api-documen.readme.io/reference" target="_self"><i class="icon-references"></i><span>API Reference</span><span class="icon-eye-off NavItem-hiddenS0Zb1tCAe_Vd"></span></a><a class="Button Button_md Button_slate_text rm-Header-bottom-link " href="https://api-documen.readme.io/changelog" target="_self"><i class="icon-changelog"></i><span>Changelog</span></a><a class="Button Button_md Button_slate_text rm-Header-bottom-link " href="https://api-documen.readme.io/discuss" target="_self"><i class="icon-discussions"></i><span>Discussions</span></a></nav><div class="Header-searchtb6Foi0-D9Vx Header-search_featherYsmQBn55F3d9"><button aria-label="Search" class="rm-SearchToggle" data-symbol="⌘"><div class="icon-search1 rm-SearchToggle-icon"></div><div class="Header-search-placeholder3Vx4OmMPcjAi rm-SearchToggle-placeholder">Search</div><div class="rm-SearchToggle-shortcut">⌘K</div></button></div></div></div><select class="Select Select_sm MobileSubnav1DsTfasXloM2"><option data-url="" disabled="" value="Documentation: direct debit api documentation">Documentation: direct debit api documentation</option><optgroup label="API Documentation: Direct Debit APIs"><option data-url="/docs/api-documentation-direct-debit-apis" value="API Documentation: Direct Debit APIs">API Documentation: Direct Debit APIs</option><option data-url="/docs/mandate-module" value="Mandate Module">Mandate Module</option><option data-url="/docs/transactions-module" value="Transactions Module">Transactions Module</option><option data-url="/docs/beneficiaries-module" value="Beneficiaries Module">Beneficiaries Module</option><option data-url="/docs/banks" value="Banks">Banks</option><option data-url="/docs/conclusion" value="Conclusion">Conclusion</option></optgroup></select></div><div class="notranslate hub-search-results--reactApp " id="hub-search-results"><div class="hub-container"><div class="modal-backdrop show-modal rm-SearchModal" role="button" tabindex="0"><div class="AlgoliaSearch1uFG9utXJ4-6 " id="AppSearch" role="tabpanel" tabindex="0"><div class="AlgoliaSearch-Col2ycAQ9JMrSYg"><div class="SearchBox1zrymSLJX6TP"><input autocapitalize="off" autocomplete="off" autocorrect="off" spellcheck="false" tabindex="0" class="Input Input_md SearchBox-InputUQZAW9QXMe-c" type="search" value=""></div><div class="SearchTabs9v4kr3U2lwvI"><div class="Tabs Tabs-list" role="tablist"><div aria-label="All" aria-selected="true" class="SearchTabs-Tab2715KRxrb5JT Tabs-listItem Tabs-listItem_active" role="tab" tabindex="-1"><span class="SearchTabs-Tab2715KRxrb5JT"><i class="icon icon-search1"></i>All</span></div><div aria-label="Guides" aria-selected="false" class="SearchTabs-Tab2715KRxrb5JT Tabs-listItem " role="tab" tabindex="-1"><span class="SearchTabs-Tab2715KRxrb5JT"><i class="icon icon-guides"></i>Guides</span></div><div aria-label="Changelog" aria-selected="false" class="SearchTabs-Tab2715KRxrb5JT Tabs-listItem " role="tab" tabindex="-1"><span class="SearchTabs-Tab2715KRxrb5JT"><i class="icon icon-changelog"></i>Changelog</span></div><div aria-label="Discussions" aria-selected="false" class="SearchTabs-Tab2715KRxrb5JT Tabs-listItem " role="tab" tabindex="-1"><span class="SearchTabs-Tab2715KRxrb5JT"><i class="icon icon-discussions"></i>Discussions</span></div></div></div><div class="SearchResults2G1wv8-Fb__d SearchResults_empty4svl7jAtcKBq"><i class="icon icon-search"></i><h6 level="6" text="Title" class="Title  Title6 ">Start typing to search…</h6></div></div></div></div></div></div></header><div class="rm-Guides"><div class="rm-Container rm-Container_flex"><nav class="Nav3C5f8FcjkaHj hub-sidebar reference-redesign rm-Sidebar_guides rm-Sidebar" id="hub-sidebar"><section class="Sidebar1t2G1ZJq-vU1 rm-Sidebar hub-sidebar-content"><div class="Sidebar-listWrapper6Q9_yUrG906C rm-Sidebar-section"><h3 class="Sidebar-headingTRQyOa2pk0gh rm-Sidebar-heading">Documentation: direct debit api documentation</h3><ul class=" Sidebar-list3cZWQLaBf9k8 rm-Sidebar-list" style=""><li class="Sidebar-item23D-2Kd61_k3 subnav-expanded"><a class="Sidebar-link2Dsha-r-GKh2 Sidebar-link_parent3OBrzjAJRSfq   active text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/api-documentation-direct-debit-apis"><span class="Sidebar-link-textLuTE1ySm4Kqn"><button aria-expanded="true" aria-label="Hide subpages for API Documentation: Direct Debit APIs" class="Sidebar-link-buttonWrapper3hnFHNku8_BJ"><i class="Sidebar-link-expandIcon2yVH6SarI6NW icon-chevron-rightward"></i></button><span>API Documentation: Direct Debit APIs</span></span></a><ul class="subpages Sidebar-list3cZWQLaBf9k8 rm-Sidebar-list"><li class="Sidebar-item23D-2Kd61_k3"><a class="Sidebar-link2Dsha-r-GKh2   childless subpage text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/mandate-module"><span class="Sidebar-link-textLuTE1ySm4Kqn"><span>Mandate Module</span></span></a></li><li class="Sidebar-item23D-2Kd61_k3"><a class="Sidebar-link2Dsha-r-GKh2   childless subpage text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/transactions-module"><span class="Sidebar-link-textLuTE1ySm4Kqn"><span>Transactions Module</span></span></a></li><li class="Sidebar-item23D-2Kd61_k3"><a class="Sidebar-link2Dsha-r-GKh2   childless subpage text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/beneficiaries-module"><span class="Sidebar-link-textLuTE1ySm4Kqn"><span>Beneficiaries Module</span></span></a></li><li class="Sidebar-item23D-2Kd61_k3"><a class="Sidebar-link2Dsha-r-GKh2   childless subpage text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/banks"><span class="Sidebar-link-textLuTE1ySm4Kqn"><span>Banks</span></span></a></li><li class="Sidebar-item23D-2Kd61_k3"><a class="Sidebar-link2Dsha-r-GKh2   childless subpage text-wrap rm-Sidebar-link" target="_self" href="https://api-documen.readme.io/docs/conclusion"><span class="Sidebar-link-textLuTE1ySm4Kqn"><span>Conclusion</span></span></a></li></ul></li></ul></div><div class="readme-logo" id="readmeLogo">Powered by&nbsp;<a aria-label="ReadMe" href="https://readme.com/?ref_src=hub&amp;project=api-documen" style="color:unset" target="_self"><i class="icon icon-readme" style="display:inline-block;min-width:71px"></i></a></div></section></nav><article class="rm-Article " id="content"><header id="content-head"><div class="row clearfix"><div class="col-xs-9"><h1>API Documentation: Direct Debit APIs</h1></div><div class="col-xs-3"><a class="suggestEdits" href="https://api-documen.readme.io/edit/api-documentation-direct-debit-apis" target="_self"><i class="icon icon-register"></i>Suggest Edits</a></div></div></header><div class="grid-container-fluid" id="content-container"><section class="content-body grid-75"><div class="markdown-body ng-non-bindable" style="margin-left:31px"><p>Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.</p>
<p>Direct debit helps businesses that require recurring payments on specific dates with fixed amounts, such as insurance premiums, loan repayments, service subscriptions, or variable recurring payments on different dates (e.g., postpaid lines, electricity usage).</p>
<p>This Direct debit API facilitates the process for Service Providers (referred to as Billers) to generate debit mandate instructions on their clients/customers' bank accounts for services rendered or products sold.</p>
<p>These debit mandate instructions are created as digital versions of physical instructions that are duly signed by the account owners (clients/customers). Once generated, the mandate instructions are automatically sent to the bank where the account is held for review and approval. The approval process requires the bank to contact the account owner to authorize the mandate, which typically takes 24 to 48 hours.</p>
<p>The system automatically assigns a unique mandate code to each initiated mandate. This mandate code is used to initiate a direct debit transaction on the bank account associated with the debit mandate instruction.</p>
<p>This document provides a comprehensive overview and detailed specifications of the Direct Debit APIs, including all the necessary information for seamless integration into your respective applications.</p>
<p>The direct debit service consist of four main modules: </p>
<ul>
<li>Mandate</li>
<li>Transactions</li>
<li>Beneficiaries</li>
<li>Banks</li>
</ul>
<p>These modules allow users to manage mandates, initiate transactions, and get beneficiaries for direct debit operations.</p>
<h3 class="heading heading-3 header-scroll" align=""><div class="heading-anchor anchor waypoint" id="base-url"></div><div class="heading-text"><div id="section-base-url" class="heading-anchor_backwardsCompatibility"></div>Base URL</div><a aria-label="Skip link to Base URL" class="heading-anchor-icon fa fa-anchor" href="https://api-documen.readme.io/docs#base-url" target="_self"></a></h3>
<p>All API requests should be made to the following base URL: <button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">{{}}</span></code></p>
<h3 class="heading heading-3 header-scroll" align=""><div class="heading-anchor anchor waypoint" id="authentication"></div><div class="heading-text"><div id="section-authentication" class="heading-anchor_backwardsCompatibility"></div>Authentication</div><a aria-label="Skip link to Authentication" class="heading-anchor-icon fa fa-anchor" href="https://api-documen.readme.io/docs#authentication" target="_self"></a></h3>
<p>API requests require authentication using an API key. This is also a unique alphanumeric key that is used to authenticate every request sent. It is to be contained in the request body of any request sent.</p>
<p>Include the API key in the request header as follows:</p>
<p>Authorization: <button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">Bearer {API_KEY}</span></code></p>
<p><strong>How to get your API Key</strong><br>
<em>Step 1:</em> Login to Direct Debit portal<br>
<em>Step 2:</em> Navigate to the API Module<br>
<em>Step 3:</em> Click on ‘Create API Keys”<br>
<em>Step 4:</em> Input the following values</p>
<ul>
<li><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">API Key</span></code> (Name of the application intending to use the Keys)</li>
<li><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">Description</span></code> (</li>
<li><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">Webhook URL -</span></code> (URL of the application intending to use the keys)</li>
<li><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">Timeout -</span></code> (duration after which a request is considered unsuccessful)</li>
</ul>
<p><em>Step 5:</em> Complete these values and click on <button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">‘Create Key</span></code>’</p>
<p><strong>Encryption</strong><br>
The system is able to receive and send encrypted payloads. To operate in an encryption mode, the admin will turn this setting on within the Admin console. </p>
<!-- -->
<h3 class="heading heading-3 header-scroll" align=""><div class="heading-anchor anchor waypoint" id="error-handling"></div><div class="heading-text"><div id="section-error-handling" class="heading-anchor_backwardsCompatibility"></div>Error Handling</div><a aria-label="Skip link to Error Handling" class="heading-anchor-icon fa fa-anchor" href="https://api-documen.readme.io/docs#error-handling" target="_self"></a></h3>
<p>Errors are returned with appropriate HTTP status codes and error messages in the response body. Refer to the <a target="_self" href="https://api-documen.readme.io/docs">API Error Handling documentation</a> for more details.</p>
<p>**HTTP status codes</p>
<p>**These are 3-digit responses issued by the server. They are standard responses and can be easily interpreted based on their first digits.</p>
<blockquote class="callout callout_okay" theme="👍"><h3 class="callout-heading"><span class="callout-icon">👍</span><p>2XX - Success of some kind</p></h3></blockquote>
<blockquote class="callout callout_error" theme="❗️"><h3 class="callout-heading"><span class="callout-icon">❗️</span><p>4XX - Error occurred on client’s end</p></h3></blockquote>
<blockquote class="callout callout_error" theme="❗️"><h3 class="callout-heading"><span class="callout-icon">❗️</span><p>5XX - Error occurred in the server’s end</p></h3></blockquote>
<p>The codes for this API include:</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">200</span></code> - OK</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">201</span></code> - Created</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">202</span></code> - Accepted (Request accepted, and queued for execution)</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">400</span></code> - Bad request</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">401</span></code> - Authentication failure</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">403</span></code> - Forbidden</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">404</span></code> - Resource not found</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">409</span></code> - Conflict</p>
<p><button aria-label="Copy Code" class="rdmd-code-copy fa"></button><code class="rdmd-code lang- theme-light" data-lang="" name=""><span class="cm-s-neo">500</span></code> - Internal Server Error</p></div><div id="updated-at"><p class="DateLine "><i class="icon icon-watch"></i>Updated<!-- --> <!-- -->about 1 hour ago<!-- --> </p></div><hr id="next-steps-divider"><nav aria-label="Pagination" class="Pagination1KE9HXCXYd0E rm-Pagination"><a class="Pagination-link1SfnH-8-DxMA Pagination-link_right2v3HzuwWFxb4" aria-label="Next Page: Mandate Module" href="https://api-documen.readme.io/docs/mandate-module"><div class="Pagination-text3yhjKs84FCa6 Pagination-text_right3I2htOlt_CfS">Mandate Module</div><span class="Pagination-iconGA9TkfVeYvTp icon-arrow-right2"></span></a></nav><div class="PageThumbs"><div class="PageThumbs-helpful">Did this page help you?<div class="PageThumbs-cta"><div class="Dropdown Dropdown_closed"><div aria-haspopup="dialog" class="Dropdown-toggle" role="button" aria-expanded="false"><button class="Button Button_sm PageThumbs-button Button_secondary Button_secondary_text" type="button"><i class="icon icon-thumbs-up-2"></i><span>Yes</span></button></div></div><div class="Dropdown Dropdown_closed"><div aria-haspopup="dialog" class="Dropdown-toggle" role="button" aria-expanded="false"><button class="Button Button_sm PageThumbs-button Button_secondary Button_secondary_text" type="button"><i class="icon icon-thumbs-down1"></i><span>No</span></button></div></div></div></div></div></section><section class="content-toc grid-25"><nav><ul class="toc-list"><li><a class="tocHeader" href="https://api-documen.readme.io/docs#" target="_self"><i class="icon icon-text-align-left"></i>Table of Contents</a></li><li class="toc-children"><ul>
<li><a href="https://api-documen.readme.io/docs#base-url" target="_self">Base URL</a></li>
<li><a href="https://api-documen.readme.io/docs#authentication" target="_self">Authentication</a></li>
<li><a href="https://api-documen.readme.io/docs#error-handling" target="_self">Error Handling</a></li>
</ul></li></ul></nav></section></div><div class="ModalWrapper" id="tutorialmodal-root"></div></article></div></div><footer class="AppFooter rm-Banners"><div data-testid="inactive-banner" class="Banner2qY-Hhfqm_Gx Banner_secondary1reFai47T0j4 Banner_smUPcJRlth4_Dl Banner_fixeda1mFpjcc1TJ6"><i class="icon-warning"></i>This site is only viewable by admins.<a href="https://api-documen.readme.io/dash?to=plans" target="_self">Launch it to make it public.</a></div></footer><div class="ModalWrapper" id="ChatGPT-modal"></div></div></div><div class="ng-non-bindable"><script id="ssr-props" data-initial-props="{&quot;baseUrl&quot;:&quot;/&quot;,&quot;apiBaseUrl&quot;:&quot;/&quot;,&quot;search&quot;:{&quot;appId&quot;:&quot;T28YKFATPY&quot;,&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;searchApiKey&quot;:&quot;MTRmYTlmZTU4MjZhNGJiNTFkZDk1MGUxOTE3Njc1MGQzNjI1MmE3YTNjMDE1MWM4YzNlODdlMjQ0MzIyYjgzOHRhZ0ZpbHRlcnM9KHByb2plY3Q6NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2JjKSwodmVyc2lvbjpub25lLHZlcnNpb246NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2M0KSwoaGlkZGVuOm5vbmUsaGlkZGVuOmZhbHNlKSwoaW5kZXg6Q3VzdG9tUGFnZSxpbmRleDpQYWdlLGluZGV4OkJsb2csaW5kZXg6RGlzY3Vzcyk=&quot;,&quot;indexName&quot;:&quot;readme_search_v2&quot;,&quot;projectsMeta&quot;:[{&quot;modules&quot;:{&quot;landing&quot;:false,&quot;docs&quot;:true,&quot;examples&quot;:true,&quot;reference&quot;:false,&quot;graphql&quot;:false,&quot;changelog&quot;:true,&quot;discuss&quot;:true,&quot;suggested_edits&quot;:true,&quot;logs&quot;:false,&quot;custompages&quot;:false,&quot;tutorials&quot;:false},&quot;id&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;name&quot;:&quot;Direct Debit API Documentation&quot;,&quot;subdomain&quot;:&quot;api-documen&quot;,&quot;subpath&quot;:&quot;&quot;,&quot;nav_names&quot;:{&quot;docs&quot;:&quot;&quot;,&quot;reference&quot;:&quot;&quot;,&quot;changelog&quot;:&quot;&quot;,&quot;discuss&quot;:&quot;&quot;,&quot;recipes&quot;:&quot;&quot;,&quot;tutorials&quot;:&quot;&quot;}}],&quot;UrlManager&quot;:{&quot;options&quot;:{&quot;parent&quot;:null,&quot;hasOneChild&quot;:null,&quot;project&quot;:null,&quot;version&quot;:null,&quot;lang&quot;:&quot;en&quot;},&quot;defaults&quot;:{&quot;child&quot;:null,&quot;lang&quot;:&quot;en&quot;,&quot;version&quot;:null}},&quot;urlManagerOpts&quot;:{&quot;lang&quot;:&quot;en&quot;,&quot;parent&quot;:{&quot;childrenProjects&quot;:[]},&quot;project&quot;:{&quot;subdomain&quot;:&quot;api-documen&quot;},&quot;version&quot;:&quot;1.0&quot;}},&quot;sidebars&quot;:{&quot;docs&quot;:[{&quot;_id&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;title&quot;:&quot;Documentation: direct debit api documentation&quot;,&quot;slug&quot;:&quot;documentation&quot;,&quot;order&quot;:9999,&quot;reference&quot;:false,&quot;version&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;createdAt&quot;:&quot;2023-05-31T09:47:09.865Z&quot;,&quot;__v&quot;:0,&quot;pages&quot;:[{&quot;_id&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;API Documentation: Direct Debit APIs&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;api-documentation-direct-debit-apis&quot;,&quot;order&quot;:0,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:35:44.029Z&quot;,&quot;parentDoc&quot;:null,&quot;children&quot;:[{&quot;_id&quot;:&quot;64774d950e2961004637d4aa&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;Mandate Module&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;mandate-module&quot;,&quot;order&quot;:0,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;parentDoc&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:37:25.944Z&quot;,&quot;isBodyEmpty&quot;:false},{&quot;_id&quot;:&quot;64774dd0265157000b6a2c4d&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;Transactions Module&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;transactions-module&quot;,&quot;order&quot;:1,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;parentDoc&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:38:24.193Z&quot;,&quot;isBodyEmpty&quot;:false},{&quot;_id&quot;:&quot;64774e09f4221100256d5060&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;Beneficiaries Module&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;beneficiaries-module&quot;,&quot;order&quot;:2,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;parentDoc&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:39:21.978Z&quot;,&quot;isBodyEmpty&quot;:false},{&quot;_id&quot;:&quot;64774e387edcf70437bf3eed&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;Banks&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;banks&quot;,&quot;order&quot;:3,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;parentDoc&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:40:08.444Z&quot;,&quot;isBodyEmpty&quot;:false},{&quot;_id&quot;:&quot;64774e629ff0c00043e6c824&quot;,&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;title&quot;:&quot;Conclusion&quot;,&quot;icon&quot;:&quot;&quot;,&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;conclusion&quot;,&quot;order&quot;:4,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;parentDoc&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:40:50.397Z&quot;,&quot;isBodyEmpty&quot;:false}],&quot;isBodyEmpty&quot;:false}]}],&quot;refs&quot;:[]},&quot;activeDoc&quot;:&quot;api-documentation-direct-debit-apis&quot;,&quot;rdmd&quot;:{&quot;baseUrl&quot;:&quot;/&quot;,&quot;body&quot;:&quot;Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.\n\nDirect debit helps businesses that require recurring payments on specific dates with fixed amounts, such as insurance premiums, loan repayments, service subscriptions, or variable recurring payments on different dates (e.g., postpaid lines, electricity usage).\n\nThis Direct debit API facilitates the process for Service Providers (referred to as Billers) to generate debit mandate instructions on their clients/customers&#39; bank accounts for services rendered or products sold.\n\nThese debit mandate instructions are created as digital versions of physical instructions that are duly signed by the account owners (clients/customers). Once generated, the mandate instructions are automatically sent to the bank where the account is held for review and approval. The approval process requires the bank to contact the account owner to authorize the mandate, which typically takes 24 to 48 hours.\n\nThe system automatically assigns a unique mandate code to each initiated mandate. This mandate code is used to initiate a direct debit transaction on the bank account associated with the debit mandate instruction.\n\nThis document provides a comprehensive overview and detailed specifications of the Direct Debit APIs, including all the necessary information for seamless integration into your respective applications.\n\nThe direct debit service consist of four main modules: \n\n- Mandate\n- Transactions\n- Beneficiaries\n- Banks\n\nThese modules allow users to manage mandates, initiate transactions, and get beneficiaries for direct debit operations.\n\n### Base URL\n\nAll API requests should be made to the following base URL: `{{}}`\n\n### Authentication\n\nAPI requests require authentication using an API key. This is also a unique alphanumeric key that is used to authenticate every request sent. It is to be contained in the request body of any request sent.\n\nInclude the API key in the request header as follows:\n\nAuthorization: `Bearer {API_KEY}`\n\n**How to get your API Key**  \n_Step 1:_ Login to Direct Debit portal  \n_Step 2:_ Navigate to the API Module  \n_Step 3:_ Click on ‘Create API Keys”  \n_Step 4:_ Input the following values\n\n- `API Key` (Name of the application intending to use the Keys)\n- `Description` (\n- `Webhook URL -` (URL of the application intending to use the keys)\n- `Timeout -` (duration after which a request is considered unsuccessful)\n\n_Step 5:_ Complete these values and click on `‘Create Key`’\n\n**Encryption**  \nThe system is able to receive and send encrypted payloads. To operate in an encryption mode, the admin will turn this setting on within the Admin console. \n\n&lt;xx&gt;\n\n### Error Handling\n\nErrors are returned with appropriate HTTP status codes and error messages in the response body. Refer to the [API Error Handling documentation](&lt;&gt;) for more details.\n\n\\*\\*HTTP status codes\n\n\\*\\*These are 3-digit responses issued by the server. They are standard responses and can be easily interpreted based on their first digits.\n\n&gt; 👍 2XX - Success of some kind\n\n&gt; ❗️ 4XX - Error occurred on client’s end\n\n&gt; ❗️ 5XX - Error occurred in the server’s end\n\nThe codes for this API include:\n\n`200` - OK\n\n`201` - Created\n\n`202` - Accepted (Request accepted, and queued for execution)\n\n`400` - Bad request\n\n`401` - Authentication failure\n\n`403` - Forbidden\n\n`404` - Resource not found\n\n`409` - Conflict\n\n`500` - Internal Server Error&quot;,&quot;opts&quot;:{&quot;alwaysThrow&quot;:false,&quot;compatibilityMode&quot;:false,&quot;copyButtons&quot;:true,&quot;correctnewlines&quot;:false,&quot;markdownOptions&quot;:{&quot;fences&quot;:true,&quot;commonmark&quot;:true,&quot;gfm&quot;:true,&quot;ruleSpaces&quot;:false,&quot;listItemIndent&quot;:&quot;1&quot;,&quot;spacedTable&quot;:true,&quot;paddedTable&quot;:true},&quot;lazyImages&quot;:true,&quot;normalize&quot;:true,&quot;safeMode&quot;:false,&quot;settings&quot;:{&quot;position&quot;:false},&quot;theme&quot;:&quot;light&quot;},&quot;terms&quot;:[{&quot;_id&quot;:&quot;6477179dbfb850002a4107bd&quot;,&quot;term&quot;:&quot;parliament&quot;,&quot;definition&quot;:&quot;Owls are generally solitary, but when seen together the group is called a &#39;parliament&#39;!&quot;}],&quot;variables&quot;:{&quot;user&quot;:{&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;name&quot;:&quot;Oladele Oluwabukola&quot;,&quot;email_verified&quot;:true,&quot;teammateUserId&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;fromReadmeKey&quot;:&quot;779f9&quot;,&quot;keys&quot;:null,&quot;iat&quot;:1685543768,&quot;exp&quot;:1685543888},&quot;defaults&quot;:[]},&quot;dehydrated&quot;:{&quot;toc&quot;:&quot;&lt;nav&gt;&lt;ul class=\&quot;toc-list\&quot;&gt;&lt;li&gt;&lt;a class=\&quot;tocHeader\&quot; href=\&quot;#\&quot;&gt;&lt;i class=\&quot;icon icon-text-align-left\&quot;&gt;&lt;/i&gt;Table of Contents&lt;/a&gt;&lt;/li&gt;&lt;li class=\&quot;toc-children\&quot;&gt;&lt;ul&gt;\n&lt;li&gt;&lt;a href=\&quot;#base-url\&quot;&gt;Base URL&lt;/a&gt;&lt;/li&gt;\n&lt;li&gt;&lt;a href=\&quot;#authentication\&quot;&gt;Authentication&lt;/a&gt;&lt;/li&gt;\n&lt;li&gt;&lt;a href=\&quot;#error-handling\&quot;&gt;Error Handling&lt;/a&gt;&lt;/li&gt;\n&lt;/ul&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/nav&gt;&quot;,&quot;body&quot;:&quot;&lt;p&gt;Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.&lt;/p&gt;\n&lt;p&gt;Direct debit helps businesses that require recurring payments on specific dates with fixed amounts, such as insurance premiums, loan repayments, service subscriptions, or variable recurring payments on different dates (e.g., postpaid lines, electricity usage).&lt;/p&gt;\n&lt;p&gt;This Direct debit API facilitates the process for Service Providers (referred to as Billers) to generate debit mandate instructions on their clients/customers&amp;#x27; bank accounts for services rendered or products sold.&lt;/p&gt;\n&lt;p&gt;These debit mandate instructions are created as digital versions of physical instructions that are duly signed by the account owners (clients/customers). Once generated, the mandate instructions are automatically sent to the bank where the account is held for review and approval. The approval process requires the bank to contact the account owner to authorize the mandate, which typically takes 24 to 48 hours.&lt;/p&gt;\n&lt;p&gt;The system automatically assigns a unique mandate code to each initiated mandate. This mandate code is used to initiate a direct debit transaction on the bank account associated with the debit mandate instruction.&lt;/p&gt;\n&lt;p&gt;This document provides a comprehensive overview and detailed specifications of the Direct Debit APIs, including all the necessary information for seamless integration into your respective applications.&lt;/p&gt;\n&lt;p&gt;The direct debit service consist of four main modules: &lt;/p&gt;\n&lt;ul&gt;\n&lt;li&gt;Mandate&lt;/li&gt;\n&lt;li&gt;Transactions&lt;/li&gt;\n&lt;li&gt;Beneficiaries&lt;/li&gt;\n&lt;li&gt;Banks&lt;/li&gt;\n&lt;/ul&gt;\n&lt;p&gt;These modules allow users to manage mandates, initiate transactions, and get beneficiaries for direct debit operations.&lt;/p&gt;\n&lt;h3 class=\&quot;heading heading-3 header-scroll\&quot; align=\&quot;\&quot;&gt;&lt;div class=\&quot;heading-anchor anchor waypoint\&quot; id=\&quot;base-url\&quot;&gt;&lt;/div&gt;&lt;div class=\&quot;heading-text\&quot;&gt;&lt;div id=\&quot;section-base-url\&quot; class=\&quot;heading-anchor_backwardsCompatibility\&quot;&gt;&lt;/div&gt;Base URL&lt;/div&gt;&lt;a aria-label=\&quot;Skip link to Base URL\&quot; class=\&quot;heading-anchor-icon fa fa-anchor\&quot; href=\&quot;#base-url\&quot;&gt;&lt;/a&gt;&lt;/h3&gt;\n&lt;p&gt;All API requests should be made to the following base URL: &lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;{{}}&lt;/code&gt;&lt;/p&gt;\n&lt;h3 class=\&quot;heading heading-3 header-scroll\&quot; align=\&quot;\&quot;&gt;&lt;div class=\&quot;heading-anchor anchor waypoint\&quot; id=\&quot;authentication\&quot;&gt;&lt;/div&gt;&lt;div class=\&quot;heading-text\&quot;&gt;&lt;div id=\&quot;section-authentication\&quot; class=\&quot;heading-anchor_backwardsCompatibility\&quot;&gt;&lt;/div&gt;Authentication&lt;/div&gt;&lt;a aria-label=\&quot;Skip link to Authentication\&quot; class=\&quot;heading-anchor-icon fa fa-anchor\&quot; href=\&quot;#authentication\&quot;&gt;&lt;/a&gt;&lt;/h3&gt;\n&lt;p&gt;API requests require authentication using an API key. This is also a unique alphanumeric key that is used to authenticate every request sent. It is to be contained in the request body of any request sent.&lt;/p&gt;\n&lt;p&gt;Include the API key in the request header as follows:&lt;/p&gt;\n&lt;p&gt;Authorization: &lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;Bearer {API_KEY}&lt;/code&gt;&lt;/p&gt;\n&lt;p&gt;&lt;strong&gt;How to get your API Key&lt;/strong&gt;&lt;br/&gt;\n&lt;em&gt;Step 1:&lt;/em&gt; Login to Direct Debit portal&lt;br/&gt;\n&lt;em&gt;Step 2:&lt;/em&gt; Navigate to the API Module&lt;br/&gt;\n&lt;em&gt;Step 3:&lt;/em&gt; Click on ‘Create API Keys”&lt;br/&gt;\n&lt;em&gt;Step 4:&lt;/em&gt; Input the following values&lt;/p&gt;\n&lt;ul&gt;\n&lt;li&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;API Key&lt;/code&gt; (Name of the application intending to use the Keys)&lt;/li&gt;\n&lt;li&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;Description&lt;/code&gt; (&lt;/li&gt;\n&lt;li&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;Webhook URL -&lt;/code&gt; (URL of the application intending to use the keys)&lt;/li&gt;\n&lt;li&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;Timeout -&lt;/code&gt; (duration after which a request is considered unsuccessful)&lt;/li&gt;\n&lt;/ul&gt;\n&lt;p&gt;&lt;em&gt;Step 5:&lt;/em&gt; Complete these values and click on &lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;‘Create Key&lt;/code&gt;’&lt;/p&gt;\n&lt;p&gt;&lt;strong&gt;Encryption&lt;/strong&gt;&lt;br/&gt;\nThe system is able to receive and send encrypted payloads. To operate in an encryption mode, the admin will turn this setting on within the Admin console. &lt;/p&gt;\n&lt;!-- --&gt;\n&lt;h3 class=\&quot;heading heading-3 header-scroll\&quot; align=\&quot;\&quot;&gt;&lt;div class=\&quot;heading-anchor anchor waypoint\&quot; id=\&quot;error-handling\&quot;&gt;&lt;/div&gt;&lt;div class=\&quot;heading-text\&quot;&gt;&lt;div id=\&quot;section-error-handling\&quot; class=\&quot;heading-anchor_backwardsCompatibility\&quot;&gt;&lt;/div&gt;Error Handling&lt;/div&gt;&lt;a aria-label=\&quot;Skip link to Error Handling\&quot; class=\&quot;heading-anchor-icon fa fa-anchor\&quot; href=\&quot;#error-handling\&quot;&gt;&lt;/a&gt;&lt;/h3&gt;\n&lt;p&gt;Errors are returned with appropriate HTTP status codes and error messages in the response body. Refer to the &lt;a href=\&quot;\&quot; target=\&quot;\&quot; title=\&quot;\&quot;&gt;API Error Handling documentation&lt;/a&gt; for more details.&lt;/p&gt;\n&lt;p&gt;**HTTP status codes&lt;/p&gt;\n&lt;p&gt;**These are 3-digit responses issued by the server. They are standard responses and can be easily interpreted based on their first digits.&lt;/p&gt;\n&lt;blockquote class=\&quot;callout callout_okay\&quot; theme=\&quot;👍\&quot;&gt;&lt;h3 class=\&quot;callout-heading\&quot;&gt;&lt;span class=\&quot;callout-icon\&quot;&gt;👍&lt;/span&gt;&lt;p&gt;2XX - Success of some kind&lt;/p&gt;&lt;/h3&gt;&lt;/blockquote&gt;\n&lt;blockquote class=\&quot;callout callout_error\&quot; theme=\&quot;❗️\&quot;&gt;&lt;h3 class=\&quot;callout-heading\&quot;&gt;&lt;span class=\&quot;callout-icon\&quot;&gt;❗️&lt;/span&gt;&lt;p&gt;4XX - Error occurred on client’s end&lt;/p&gt;&lt;/h3&gt;&lt;/blockquote&gt;\n&lt;blockquote class=\&quot;callout callout_error\&quot; theme=\&quot;❗️\&quot;&gt;&lt;h3 class=\&quot;callout-heading\&quot;&gt;&lt;span class=\&quot;callout-icon\&quot;&gt;❗️&lt;/span&gt;&lt;p&gt;5XX - Error occurred in the server’s end&lt;/p&gt;&lt;/h3&gt;&lt;/blockquote&gt;\n&lt;p&gt;The codes for this API include:&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;200&lt;/code&gt; - OK&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;201&lt;/code&gt; - Created&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;202&lt;/code&gt; - Accepted (Request accepted, and queued for execution)&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;400&lt;/code&gt; - Bad request&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;401&lt;/code&gt; - Authentication failure&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;403&lt;/code&gt; - Forbidden&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;404&lt;/code&gt; - Resource not found&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;409&lt;/code&gt; - Conflict&lt;/p&gt;\n&lt;p&gt;&lt;button aria-label=\&quot;Copy Code\&quot; class=\&quot;rdmd-code-copy fa\&quot;&gt;&lt;/button&gt;&lt;code class=\&quot;rdmd-code lang- theme-light\&quot; data-lang=\&quot;\&quot; name=\&quot;\&quot;&gt;500&lt;/code&gt; - Internal Server Error&lt;/p&gt;&quot;}},&quot;doc&quot;:{&quot;metadata&quot;:{&quot;image&quot;:[],&quot;title&quot;:&quot;&quot;,&quot;description&quot;:&quot;&quot;},&quot;api&quot;:{&quot;method&quot;:&quot;get&quot;,&quot;url&quot;:&quot;&quot;,&quot;auth&quot;:&quot;required&quot;,&quot;params&quot;:[]},&quot;next&quot;:{&quot;description&quot;:&quot;&quot;,&quot;pages&quot;:[]},&quot;algolia&quot;:{&quot;recordCount&quot;:4,&quot;publishPending&quot;:false,&quot;updatedAt&quot;:&quot;2023-05-31T13:43:34.988Z&quot;},&quot;title&quot;:&quot;API Documentation: Direct Debit APIs&quot;,&quot;icon&quot;:&quot;&quot;,&quot;updates&quot;:[],&quot;type&quot;:&quot;basic&quot;,&quot;slug&quot;:&quot;api-documentation-direct-debit-apis&quot;,&quot;excerpt&quot;:&quot;&quot;,&quot;body&quot;:&quot;Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.\n\nDirect debit helps businesses that require recurring payments on specific dates with fixed amounts, such as insurance premiums, loan repayments, service subscriptions, or variable recurring payments on different dates (e.g., postpaid lines, electricity usage).\n\nThis Direct debit API facilitates the process for Service Providers (referred to as Billers) to generate debit mandate instructions on their clients/customers&#39; bank accounts for services rendered or products sold.\n\nThese debit mandate instructions are created as digital versions of physical instructions that are duly signed by the account owners (clients/customers). Once generated, the mandate instructions are automatically sent to the bank where the account is held for review and approval. The approval process requires the bank to contact the account owner to authorize the mandate, which typically takes 24 to 48 hours.\n\nThe system automatically assigns a unique mandate code to each initiated mandate. This mandate code is used to initiate a direct debit transaction on the bank account associated with the debit mandate instruction.\n\nThis document provides a comprehensive overview and detailed specifications of the Direct Debit APIs, including all the necessary information for seamless integration into your respective applications.\n\nThe direct debit service consist of four main modules: \n\n- Mandate\n- Transactions\n- Beneficiaries\n- Banks\n\nThese modules allow users to manage mandates, initiate transactions, and get beneficiaries for direct debit operations.\n\n### Base URL\n\nAll API requests should be made to the following base URL: `{{}}`\n\n### Authentication\n\nAPI requests require authentication using an API key. This is also a unique alphanumeric key that is used to authenticate every request sent. It is to be contained in the request body of any request sent.\n\nInclude the API key in the request header as follows:\n\nAuthorization: `Bearer {API_KEY}`\n\n**How to get your API Key**  \n_Step 1:_ Login to Direct Debit portal  \n_Step 2:_ Navigate to the API Module  \n_Step 3:_ Click on ‘Create API Keys”  \n_Step 4:_ Input the following values\n\n- `API Key` (Name of the application intending to use the Keys)\n- `Description` (\n- `Webhook URL -` (URL of the application intending to use the keys)\n- `Timeout -` (duration after which a request is considered unsuccessful)\n\n_Step 5:_ Complete these values and click on `‘Create Key`’\n\n**Encryption**  \nThe system is able to receive and send encrypted payloads. To operate in an encryption mode, the admin will turn this setting on within the Admin console. \n\n&lt;xx&gt;\n\n### Error Handling\n\nErrors are returned with appropriate HTTP status codes and error messages in the response body. Refer to the [API Error Handling documentation](&lt;&gt;) for more details.\n\n\\*\\*HTTP status codes\n\n\\*\\*These are 3-digit responses issued by the server. They are standard responses and can be easily interpreted based on their first digits.\n\n&gt; 👍 2XX - Success of some kind\n\n&gt; ❗️ 4XX - Error occurred on client’s end\n\n&gt; ❗️ 5XX - Error occurred in the server’s end\n\nThe codes for this API include:\n\n`200` - OK\n\n`201` - Created\n\n`202` - Accepted (Request accepted, and queued for execution)\n\n`400` - Bad request\n\n`401` - Authentication failure\n\n`403` - Forbidden\n\n`404` - Resource not found\n\n`409` - Conflict\n\n`500` - Internal Server Error&quot;,&quot;order&quot;:0,&quot;isReference&quot;:false,&quot;deprecated&quot;:false,&quot;hidden&quot;:false,&quot;sync_unique&quot;:&quot;&quot;,&quot;link_url&quot;:&quot;&quot;,&quot;link_external&quot;:false,&quot;previousSlug&quot;:&quot;&quot;,&quot;slugUpdatedAt&quot;:&quot;2023-05-30T22:09:35.528Z&quot;,&quot;revision&quot;:4,&quot;_id&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;user&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;category&quot;:&quot;6477179dbfb850002a4107c6&quot;,&quot;createdAt&quot;:&quot;2023-05-31T13:35:44.029Z&quot;,&quot;updatedAt&quot;:&quot;2023-05-31T13:43:34.632Z&quot;,&quot;version&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;__v&quot;:0,&quot;parentDoc&quot;:null,&quot;isApi&quot;:false,&quot;id&quot;:&quot;64774d30916bd9003c381905&quot;},&quot;hideTOC&quot;:false,&quot;meta&quot;:{&quot;slug&quot;:&quot;api-documentation-direct-debit-apis&quot;,&quot;type&quot;:&quot;docs&quot;,&quot;parent&quot;:null,&quot;image&quot;:[],&quot;title&quot;:&quot;API Documentation: Direct Debit APIs&quot;,&quot;title_raw&quot;:&quot;API Documentation: Direct Debit APIs&quot;,&quot;description&quot;:&quot;Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.Direc...&quot;,&quot;_id&quot;:&quot;64774d30916bd9003c381905&quot;,&quot;hidden&quot;:false},&quot;slugUrl&quot;:&quot;/docs/api-documentation-direct-debit-apis&quot;,&quot;config&quot;:{&quot;algoliaIndex&quot;:&quot;readme_search_v2&quot;,&quot;asset_url&quot;:&quot;https://cdn.readme.io&quot;,&quot;domain&quot;:&quot;readme.io&quot;,&quot;domainFull&quot;:&quot;https://dash.readme.com&quot;,&quot;dashMetricsUrl&quot;:&quot;https://m.readme.io&quot;,&quot;metricsUrl&quot;:&quot;https://metrics.readme.io&quot;,&quot;wsMetricsUrl&quot;:&quot;wss://m.readme.io&quot;,&quot;releaseVersion&quot;:&quot;4.406.0&quot;,&quot;sentry&quot;:{&quot;enabled&quot;:true,&quot;dsn&quot;:&quot;https://3bbe57a973254129bcb93e47dc0cc46f@o343074.ingest.sentry.io/2052166&quot;,&quot;tracesSampleRate&quot;:0},&quot;sslGenerationService&quot;:&quot;ssl.readmessl.com&quot;},&quot;context&quot;:{&quot;user&quot;:{&quot;user&quot;:{&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;name&quot;:&quot;Oladele Oluwabukola&quot;,&quot;email_verified&quot;:true,&quot;teammateUserId&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;fromReadmeKey&quot;:&quot;779f9&quot;,&quot;keys&quot;:null,&quot;iat&quot;:1685543768,&quot;exp&quot;:1685543888},&quot;email_verified&quot;:true,&quot;fromReadme&quot;:true,&quot;_id&quot;:&quot;64771a44a4cec60282f206bd&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;provider&quot;:&quot;readme&quot;,&quot;permissions&quot;:[{&quot;userType&quot;:&quot;admin&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;}],&quot;groups&quot;:[],&quot;createdAt&quot;:&quot;2023-05-31T09:58:28.425Z&quot;,&quot;lastSeen&quot;:&quot;2023-05-31T14:36:09.402Z&quot;,&quot;isEndUser&quot;:false,&quot;__v&quot;:0,&quot;loggedIn&quot;:true,&quot;search&quot;:{&quot;app&quot;:&quot;T28YKFATPY&quot;,&quot;token&quot;:&quot;MTRmYTlmZTU4MjZhNGJiNTFkZDk1MGUxOTE3Njc1MGQzNjI1MmE3YTNjMDE1MWM4YzNlODdlMjQ0MzIyYjgzOHRhZ0ZpbHRlcnM9KHByb2plY3Q6NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2JjKSwodmVyc2lvbjpub25lLHZlcnNpb246NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2M0KSwoaGlkZGVuOm5vbmUsaGlkZGVuOmZhbHNlKSwoaW5kZXg6Q3VzdG9tUGFnZSxpbmRleDpQYWdlLGluZGV4OkJsb2csaW5kZXg6RGlzY3Vzcyk=&quot;,&quot;filters&quot;:&quot;tagFilters=(project:6477179dbfb850002a4107bc),(version:none,version:6477179dbfb850002a4107c4),(hidden:none,hidden:false),(index:CustomPage,index:Page,index:Blog,index:Discuss)&quot;,&quot;metaData&quot;:[{&quot;modules&quot;:{&quot;landing&quot;:false,&quot;docs&quot;:true,&quot;examples&quot;:true,&quot;reference&quot;:false,&quot;graphql&quot;:false,&quot;changelog&quot;:true,&quot;discuss&quot;:true,&quot;suggested_edits&quot;:true,&quot;logs&quot;:false,&quot;custompages&quot;:false,&quot;tutorials&quot;:false},&quot;id&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;name&quot;:&quot;Direct Debit API Documentation&quot;,&quot;subdomain&quot;:&quot;api-documen&quot;,&quot;subpath&quot;:&quot;&quot;,&quot;nav_names&quot;:{&quot;docs&quot;:&quot;&quot;,&quot;reference&quot;:&quot;&quot;,&quot;changelog&quot;:&quot;&quot;,&quot;discuss&quot;:&quot;&quot;,&quot;recipes&quot;:&quot;&quot;,&quot;tutorials&quot;:&quot;&quot;}}]},&quot;isAdmin&quot;:true},&quot;terms&quot;:[{&quot;_id&quot;:&quot;6477179dbfb850002a4107bd&quot;,&quot;term&quot;:&quot;parliament&quot;,&quot;definition&quot;:&quot;Owls are generally solitary, but when seen together the group is called a &#39;parliament&#39;!&quot;}],&quot;variables&quot;:{&quot;user&quot;:{&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;name&quot;:&quot;Oladele Oluwabukola&quot;,&quot;email_verified&quot;:true,&quot;teammateUserId&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;fromReadmeKey&quot;:&quot;779f9&quot;,&quot;keys&quot;:null,&quot;iat&quot;:1685543768,&quot;exp&quot;:1685543888},&quot;defaults&quot;:[]},&quot;project&quot;:{&quot;_id&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;appearance&quot;:{&quot;rdmd&quot;:{&quot;callouts&quot;:{&quot;useIconFont&quot;:false},&quot;theme&quot;:{&quot;background&quot;:&quot;&quot;,&quot;border&quot;:&quot;&quot;,&quot;markdownEdge&quot;:&quot;&quot;,&quot;markdownFont&quot;:&quot;&quot;,&quot;markdownFontSize&quot;:&quot;&quot;,&quot;markdownLineHeight&quot;:&quot;&quot;,&quot;markdownRadius&quot;:&quot;&quot;,&quot;markdownText&quot;:&quot;&quot;,&quot;markdownTitle&quot;:&quot;&quot;,&quot;markdownTitleFont&quot;:&quot;&quot;,&quot;mdCodeBackground&quot;:&quot;&quot;,&quot;mdCodeFont&quot;:&quot;&quot;,&quot;mdCodeRadius&quot;:&quot;&quot;,&quot;mdCodeTabs&quot;:&quot;&quot;,&quot;mdCodeText&quot;:&quot;&quot;,&quot;tableEdges&quot;:&quot;&quot;,&quot;tableHead&quot;:&quot;&quot;,&quot;tableHeadText&quot;:&quot;&quot;,&quot;tableRow&quot;:&quot;&quot;,&quot;tableStripe&quot;:&quot;&quot;,&quot;tableText&quot;:&quot;&quot;,&quot;text&quot;:&quot;&quot;,&quot;title&quot;:&quot;&quot;}},&quot;main_body&quot;:{&quot;type&quot;:&quot;links&quot;},&quot;colors&quot;:{&quot;highlight&quot;:&quot;&quot;,&quot;main&quot;:&quot;#048ef5&quot;,&quot;main_alt&quot;:&quot;&quot;,&quot;header_text&quot;:&quot;&quot;,&quot;body_highlight&quot;:&quot;&quot;,&quot;custom_login_link_color&quot;:&quot;&quot;},&quot;typography&quot;:{&quot;headline&quot;:&quot;Open+Sans:400:sans-serif&quot;,&quot;body&quot;:&quot;Open+Sans:400:sans-serif&quot;,&quot;typekit&quot;:false,&quot;tk_key&quot;:&quot;&quot;,&quot;tk_headline&quot;:&quot;&quot;,&quot;tk_body&quot;:&quot;&quot;},&quot;header&quot;:{&quot;style&quot;:&quot;solid&quot;,&quot;img&quot;:[],&quot;img_size&quot;:&quot;auto&quot;,&quot;img_pos&quot;:&quot;tl&quot;},&quot;body&quot;:{&quot;style&quot;:&quot;none&quot;},&quot;global_landing_page&quot;:{&quot;html&quot;:&quot;&quot;,&quot;redirect&quot;:&quot;&quot;},&quot;referenceSimpleMode&quot;:true,&quot;referenceLayout&quot;:&quot;row&quot;,&quot;link_logo_to_url&quot;:false,&quot;theme&quot;:&quot;solid&quot;,&quot;colorScheme&quot;:&quot;auto&quot;,&quot;overlay&quot;:&quot;triangles&quot;,&quot;landing&quot;:true,&quot;sticky&quot;:false,&quot;hide_logo&quot;:false,&quot;childrenAsPills&quot;:false,&quot;subheaderStyle&quot;:&quot;links&quot;,&quot;splitReferenceDocs&quot;:false,&quot;showMetricsInReference&quot;:true,&quot;logo&quot;:[&quot;https://files.readme.io/45785f4-brandmark-blue.svg&quot;,&quot;readme.svg&quot;,60,60,&quot;#048ef5&quot;],&quot;loginLogo&quot;:[],&quot;logo_white&quot;:[],&quot;logo_white_use&quot;:false,&quot;logo_large&quot;:false,&quot;favicon&quot;:[],&quot;stylesheet&quot;:&quot;&quot;,&quot;stylesheet_hub2&quot;:&quot;&quot;,&quot;stylesheet_hub3&quot;:&quot;&quot;,&quot;javascript&quot;:&quot;&quot;,&quot;javascript_hub2&quot;:&quot;&quot;,&quot;html_promo&quot;:&quot;&quot;,&quot;html_body&quot;:&quot;&quot;,&quot;html_footer&quot;:&quot;&quot;,&quot;html_head&quot;:&quot;&quot;,&quot;html_footer_meta&quot;:&quot;&quot;,&quot;html_hidelinks&quot;:false,&quot;showVersion&quot;:true,&quot;hideTableOfContents&quot;:false,&quot;nextStepsLabel&quot;:&quot;&quot;,&quot;promos&quot;:[{&quot;extras&quot;:{&quot;type&quot;:&quot;buttons&quot;,&quot;buttonPrimary&quot;:&quot;get-started&quot;,&quot;buttonSecondary&quot;:&quot;none&quot;},&quot;title&quot;:&quot;The API Documentation Developer Hub&quot;,&quot;text&quot;:&quot;Welcome to the API Documentation developer hub. You&#39;ll find comprehensive guides and documentation to help you start working with API Documentation as quickly as possible, as well as support if you get stuck. Let&#39;s jump right in!&quot;,&quot;_id&quot;:&quot;6477179dbfb850002a4107be&quot;}]},&quot;custom_domain&quot;:&quot;&quot;,&quot;childrenProjects&quot;:[],&quot;description&quot;:&quot;&quot;,&quot;error404&quot;:&quot;&quot;,&quot;first_page&quot;:&quot;docs&quot;,&quot;flags&quot;:{&quot;allowApiExplorerJsonEditor&quot;:false,&quot;allowDarkMode&quot;:true,&quot;allowReusableOTPs&quot;:false,&quot;alwaysShowDocPublishStatus&quot;:false,&quot;allowXFrame&quot;:false,&quot;correctnewlines&quot;:false,&quot;dashReact&quot;:false,&quot;disablePasswordlessLogin&quot;:false,&quot;directGoogleToStableVersion&quot;:false,&quot;disableAnonForum&quot;:false,&quot;enterprise&quot;:false,&quot;graphql&quot;:false,&quot;migrationRun&quot;:false,&quot;migrationSwaggerRun&quot;:false,&quot;newEditor&quot;:true,&quot;newEditorDash&quot;:true,&quot;newMarkdownBetaProgram&quot;:true,&quot;newSearch&quot;:true,&quot;oauth&quot;:false,&quot;oldMarkdown&quot;:false,&quot;owlbotAi&quot;:false,&quot;rdmdCompatibilityMode&quot;:false,&quot;reviewWorkflow&quot;:true,&quot;singleProjectEnterprise&quot;:false,&quot;speedyRender&quot;:false,&quot;staging&quot;:false,&quot;star&quot;:false,&quot;superHub&quot;:false,&quot;swagger&quot;:false,&quot;translation&quot;:false,&quot;useReactApp&quot;:true,&quot;useReactGLP&quot;:true},&quot;fullBaseUrl&quot;:&quot;https://api-documen.readme.io/&quot;,&quot;glossaryTerms&quot;:[{&quot;_id&quot;:&quot;6477179dbfb850002a4107bd&quot;,&quot;term&quot;:&quot;parliament&quot;,&quot;definition&quot;:&quot;Owls are generally solitary, but when seen together the group is called a &#39;parliament&#39;!&quot;}],&quot;graphqlSchema&quot;:&quot;&quot;,&quot;hasOneChild&quot;:false,&quot;healthCheck&quot;:{&quot;provider&quot;:&quot;&quot;,&quot;settings&quot;:{}},&quot;intercom_secure_emailonly&quot;:false,&quot;intercom&quot;:&quot;&quot;,&quot;is_active&quot;:false,&quot;internal&quot;:&quot;&quot;,&quot;landing_bottom&quot;:[],&quot;metrics&quot;:{&quot;monthlyLimit&quot;:0,&quot;thumbsEnabled&quot;:true},&quot;modules&quot;:{&quot;landing&quot;:false,&quot;docs&quot;:true,&quot;examples&quot;:true,&quot;reference&quot;:false,&quot;graphql&quot;:false,&quot;changelog&quot;:true,&quot;discuss&quot;:true,&quot;suggested_edits&quot;:true,&quot;logs&quot;:false,&quot;custompages&quot;:false,&quot;tutorials&quot;:false},&quot;name&quot;:&quot;Direct Debit API Documentation&quot;,&quot;nav_names&quot;:{&quot;docs&quot;:&quot;&quot;,&quot;reference&quot;:&quot;&quot;,&quot;changelog&quot;:&quot;&quot;,&quot;discuss&quot;:&quot;&quot;,&quot;recipes&quot;:&quot;&quot;,&quot;tutorials&quot;:&quot;&quot;},&quot;oauth_url&quot;:&quot;&quot;,&quot;onboardingCompleted&quot;:{&quot;documentation&quot;:true,&quot;appearance&quot;:false,&quot;jwt&quot;:false,&quot;api&quot;:false,&quot;logs&quot;:false,&quot;domain&quot;:false},&quot;owlbot&quot;:{&quot;enabled&quot;:false,&quot;isPaying&quot;:false},&quot;owner&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;plan&quot;:&quot;free&quot;,&quot;planOverride&quot;:&quot;&quot;,&quot;planTrial&quot;:&quot;business2018&quot;,&quot;readmeScore&quot;:{},&quot;reCaptchaSiteKey&quot;:&quot;&quot;,&quot;stable&quot;:{&quot;_id&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;version&quot;:&quot;1.0&quot;,&quot;version_clean&quot;:&quot;1.0.0&quot;,&quot;codename&quot;:&quot;&quot;,&quot;is_stable&quot;:true,&quot;is_beta&quot;:false,&quot;is_hidden&quot;:false,&quot;is_deprecated&quot;:false,&quot;categories&quot;:[&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c8&quot;,&quot;6477571dec49c703acc13fbd&quot;,&quot;647757a71345090029293073&quot;],&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;releaseDate&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;createdAt&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;__v&quot;:1},&quot;subdomain&quot;:&quot;api-documen&quot;,&quot;subpath&quot;:&quot;&quot;,&quot;topnav&quot;:{&quot;left&quot;:[],&quot;right&quot;:[{&quot;type&quot;:&quot;user&quot;,&quot;text&quot;:&quot;Oladele Oluwabukola&quot;}],&quot;bottom&quot;:[],&quot;edited&quot;:true},&quot;translate&quot;:{&quot;provider&quot;:&quot;transifex&quot;,&quot;show_widget&quot;:false,&quot;key_public&quot;:&quot;&quot;,&quot;key_secret&quot;:&quot;&quot;,&quot;org_name&quot;:&quot;&quot;,&quot;project_name&quot;:&quot;&quot;,&quot;languages&quot;:[]},&quot;url&quot;:&quot;&quot;,&quot;versions&quot;:[{&quot;_id&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;version&quot;:&quot;1.0&quot;,&quot;version_clean&quot;:&quot;1.0.0&quot;,&quot;codename&quot;:&quot;&quot;,&quot;is_stable&quot;:true,&quot;is_beta&quot;:false,&quot;is_hidden&quot;:false,&quot;is_deprecated&quot;:false,&quot;categories&quot;:[&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c8&quot;,&quot;6477571dec49c703acc13fbd&quot;,&quot;647757a71345090029293073&quot;],&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;releaseDate&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;createdAt&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;__v&quot;:1}],&quot;variableDefaults&quot;:[],&quot;webhookEnabled&quot;:false,&quot;isHubEditable&quot;:true},&quot;version&quot;:{&quot;_id&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;version&quot;:&quot;1.0&quot;,&quot;version_clean&quot;:&quot;1.0.0&quot;,&quot;codename&quot;:&quot;&quot;,&quot;is_stable&quot;:true,&quot;is_beta&quot;:false,&quot;is_hidden&quot;:false,&quot;is_deprecated&quot;:false,&quot;categories&quot;:[&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c8&quot;,&quot;6477571dec49c703acc13fbd&quot;,&quot;647757a71345090029293073&quot;],&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;releaseDate&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;createdAt&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;__v&quot;:1}},&quot;reqUrl&quot;:&quot;/docs&quot;,&quot;version&quot;:{&quot;_id&quot;:&quot;6477179dbfb850002a4107c4&quot;,&quot;version&quot;:&quot;1.0&quot;,&quot;version_clean&quot;:&quot;1.0.0&quot;,&quot;codename&quot;:&quot;&quot;,&quot;is_stable&quot;:true,&quot;is_beta&quot;:false,&quot;is_hidden&quot;:false,&quot;is_deprecated&quot;:false,&quot;categories&quot;:[&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c6&quot;,&quot;6477179dbfb850002a4107c8&quot;,&quot;6477571dec49c703acc13fbd&quot;,&quot;647757a71345090029293073&quot;],&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;releaseDate&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;createdAt&quot;:&quot;2023-05-31T09:47:09.830Z&quot;,&quot;__v&quot;:1},&quot;user&quot;:{&quot;user&quot;:{&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;name&quot;:&quot;Oladele Oluwabukola&quot;},&quot;email_verified&quot;:true,&quot;fromReadme&quot;:true,&quot;_id&quot;:&quot;64771a44a4cec60282f206bd&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;provider&quot;:&quot;readme&quot;,&quot;permissions&quot;:[{&quot;userType&quot;:&quot;admin&quot;,&quot;project&quot;:&quot;6477179dbfb850002a4107bc&quot;}],&quot;groups&quot;:[],&quot;createdAt&quot;:&quot;2023-05-31T09:58:28.425Z&quot;,&quot;lastSeen&quot;:&quot;2023-05-31T14:36:09.402Z&quot;,&quot;isEndUser&quot;:false,&quot;__v&quot;:0},&quot;lang&quot;:&quot;en&quot;,&quot;langFull&quot;:&quot;Default&quot;,&quot;isDetachedProductionSite&quot;:false,&quot;rdmdOpts&quot;:{&quot;normalize&quot;:true,&quot;correctnewlines&quot;:false,&quot;compatibilityMode&quot;:false}}"></script></div><div ng-class="{active:contentLoadingSection || contentLoading}" class="hub-loading-indicator"></div><div id="hub-container" ng-class="{loading:contentLoadingSection}"><div class="hub-container"><div state-container="" ng-attr-id="{{state.current().root !== &#39;docs&#39; &amp;&amp; &#39;react-app-content-container&#39;}}"><div id="replace-view" ng-non-bindable=""><meta ng-non-bindable="" name="meta:slug" content="api-documentation-direct-debit-apis"><meta ng-non-bindable="" name="meta:type" content="docs"><meta ng-non-bindable="" name="meta:parent"><meta ng-non-bindable="" name="meta:image" content=""><meta ng-non-bindable="" name="meta:title" content="API Documentation: Direct Debit APIs"><meta ng-non-bindable="" name="meta:title_raw" content="API Documentation: Direct Debit APIs"><meta ng-non-bindable="" name="meta:description" content="Direct debit is a payment method which allows an account holder, to grant an authorization, for a biller (or a lender) to take money from their bank account for services as of when due. Direct debit is similar to debit cards in its ability to debit a customer’s account with prior authorization.Direc..."><meta ng-non-bindable="" name="meta:_id" content="64774d30916bd9003c381905"><meta ng-non-bindable="" name="meta:hidden"><div ng-if="!suggestedEdits.isEnabled" class="templateBlock--docs"></div></div></div></div></div><footer></footer><script>var is_hub = true;
var is_hub2 = true;
var is_hub_edit = true;
</script><div id="ssr-end"><script id="__LOADABLE_REQUIRED_CHUNKS__" type="application/json">[7588,5585,9156,105,1560,2807,4134,4301,4003,775,7552,9351,1158,1730,6683,2926,428,9097,4127,713,1581,2069,7367,3879,4670,5079,6265,2332,9509,2053,8457,788,295,748,7667,8011,4196,4775,3393,9556,4553,3210,5237,4141,439,4372,9510,8196,6952,3337,4022,6842,5443,6605,2652,7815,2647,9502,2642,7023,1217]</script><script id="__LOADABLE_REQUIRED_CHUNKS___ext" type="application/json">{"namedChunks":["SuperHub","Header","routes-Landing","Footer","routes-Doc","routes-PageNotFound","routes-Changelog","Post","routes-Reference","core-icons-more-vertical-svg","core-icons-chevron-down-svg","core-icons-arrow-right-svg","CustomPage","routes-CustomPage","routes-Discuss","Page","core-icons-menu-svg","Editor","core-icons-x-circle-svg","core-icons-suggested-edits-svg","core-icons-arrow-up-right-svg","List","core-icons-trending-up-svg","core-icons-callout-info-svg","core-icons-inbox-svg","routes-Tutorials","core-icons-star-svg","routes-Suggestions-ngz-Header","ngz","core-icons-key-svg","New"]}</script>
<script async="" data-chunk="main" src="./API Documentation_ Direct Debit APIs_files/main.fe8f2143b599d626bc1c.js"></script>
<script async="" data-chunk="SuperHub" src="./API Documentation_ Direct Debit APIs_files/7588.d0ec234c05764b817112.js"></script>
<script async="" data-chunk="SuperHub" src="./API Documentation_ Direct Debit APIs_files/5585.bb6134c216753e282710.js"></script>
<script async="" data-chunk="SuperHub" src="./API Documentation_ Direct Debit APIs_files/9156.14658dc3d8f611201899.js"></script>
<script async="" data-chunk="SuperHub" src="./API Documentation_ Direct Debit APIs_files/105.22bd58d20006978de049.js"></script>
<script async="" data-chunk="SuperHub" src="./API Documentation_ Direct Debit APIs_files/SuperHub.491ab883a5dd2a460f91.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/2807.3aa20e12efd9c25d3701.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/4134.9dd24f2c079a17d11463.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/4301.e92eebfb5383857a31d4.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/4003.ee4230c1f52ba67fdb01.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/775.d5a8ac18b455514b0c5e.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/7552.fa985385affa26865c32.js"></script>
<script async="" data-chunk="Header" src="./API Documentation_ Direct Debit APIs_files/Header.f029887c6e55d26ed9c6.js"></script>
<script async="" data-chunk="routes-Landing" src="./API Documentation_ Direct Debit APIs_files/1158.c4279af9447c30a12a3a.js"></script>
<script async="" data-chunk="routes-Landing" src="./API Documentation_ Direct Debit APIs_files/1730.496a9b2e3fc2de3fb2f3.js"></script>
<script async="" data-chunk="routes-Landing" src="./API Documentation_ Direct Debit APIs_files/6683.2e39c459b33e86fd12e5.js"></script>
<script async="" data-chunk="routes-Landing" src="./API Documentation_ Direct Debit APIs_files/2926.6ceb29a1bfcee886def7.js"></script>
<script async="" data-chunk="routes-Landing" src="./API Documentation_ Direct Debit APIs_files/routes-Landing.962002218245a3b99f3f.js"></script>
<script async="" data-chunk="Footer" src="./API Documentation_ Direct Debit APIs_files/Footer.ed749644b3cba8655c14.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/4127.6fe612d1b203ef5191f3.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/713.cd13007ec2bac8b6a1ea.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/1581.845926ab06e2fa0f9be2.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/2069.daa15a4d13acfe8f99f1.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/7367.e9df727d550f9dbdb6ca.js"></script>
<script async="" data-chunk="routes-Doc" src="./API Documentation_ Direct Debit APIs_files/routes-Doc.fdbf93e3b7a06afd0634.js"></script>
<script async="" data-chunk="routes-PageNotFound" src="./API Documentation_ Direct Debit APIs_files/routes-PageNotFound.944d69719216150b1549.js"></script>
<script async="" data-chunk="routes-Changelog" src="./API Documentation_ Direct Debit APIs_files/routes-Changelog.b91d70147e95510bbb10.js"></script>
<script async="" data-chunk="Post" src="./API Documentation_ Direct Debit APIs_files/6265.4d0ff1476b3f59d84c32.js"></script>
<script async="" data-chunk="Post" src="./API Documentation_ Direct Debit APIs_files/Post.4dc7cb3a600e401a610a.js"></script>
<script async="" data-chunk="routes-Reference" src="./API Documentation_ Direct Debit APIs_files/9509.04bba54c54fa9dd1c5f5.js"></script>
<script async="" data-chunk="routes-Reference" src="./API Documentation_ Direct Debit APIs_files/2053.dbbc8cd2a5d634d615e6.js"></script>
<script async="" data-chunk="routes-Reference" src="./API Documentation_ Direct Debit APIs_files/8457.1d9d61c673fd8b6e3676.js"></script>
<script async="" data-chunk="routes-Reference" src="./API Documentation_ Direct Debit APIs_files/routes-Reference.3a44fdc4ad14d7ba6bcb.js"></script>
<script async="" data-chunk="core-icons-more-vertical-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-more-vertical-svg.228db57c23169aaa56d6.js"></script>
<script async="" data-chunk="core-icons-chevron-down-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-chevron-down-svg.09fdf86b58640880691c.js"></script>
<script async="" data-chunk="core-icons-arrow-right-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-arrow-right-svg.1e7f2192b7bda6b4a5e1.js"></script>
<script async="" data-chunk="CustomPage" src="./API Documentation_ Direct Debit APIs_files/CustomPage.9dc25d4d0248b160ff3d.js"></script>
<script async="" data-chunk="routes-CustomPage" src="./API Documentation_ Direct Debit APIs_files/routes-CustomPage.39e8a82f13bff819cb9e.js"></script>
<script async="" data-chunk="routes-Discuss" src="./API Documentation_ Direct Debit APIs_files/4775.c3adf5c11671821d7f08.js"></script>
<script async="" data-chunk="routes-Discuss" src="./API Documentation_ Direct Debit APIs_files/3393.951a5bb57c48d1f013c6.js"></script>
<script async="" data-chunk="routes-Discuss" src="./API Documentation_ Direct Debit APIs_files/routes-Discuss.a01c70343fbef3cd1c01.js"></script>
<script async="" data-chunk="Page" src="./API Documentation_ Direct Debit APIs_files/4553.7b4d16a51d1bb7ee54a3.js"></script>
<script async="" data-chunk="Page" src="./API Documentation_ Direct Debit APIs_files/3210.529ad6704964fbc21117.js"></script>
<script async="" data-chunk="Page" src="./API Documentation_ Direct Debit APIs_files/5237.18898667cd1691af4721.js"></script>
<script async="" data-chunk="Page" src="./API Documentation_ Direct Debit APIs_files/4141.a8a05e082ed667262ffb.js"></script>
<script async="" data-chunk="Page" src="./API Documentation_ Direct Debit APIs_files/Page.23ffcc4ca59d55f9da36.js"></script>
<script async="" data-chunk="core-icons-menu-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-menu-svg.b9a5673111bcd429344f.js"></script>
<script async="" data-chunk="Editor" src="./API Documentation_ Direct Debit APIs_files/9510.e91d25bc50ff7f1ad1c0.js"></script>
<script async="" data-chunk="Editor" src="./API Documentation_ Direct Debit APIs_files/Editor.8c3adc7fa2cd87f474d3.js"></script>
<script async="" data-chunk="core-icons-x-circle-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-x-circle-svg.1253cc725f6ab78a786d.js"></script>
<script async="" data-chunk="core-icons-suggested-edits-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-suggested-edits-svg.93755393eff5d50dda67.js"></script>
<script async="" data-chunk="core-icons-arrow-up-right-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-arrow-up-right-svg.957c5be2eea3961b4701.js"></script>
<script async="" data-chunk="List" src="./API Documentation_ Direct Debit APIs_files/List.99613c6b125692b5f28f.js"></script>
<script async="" data-chunk="core-icons-trending-up-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-trending-up-svg.b09fd55fdbf98ea428b4.js"></script>
<script async="" data-chunk="core-icons-callout-info-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-callout-info-svg.991471218275384a0302.js"></script>
<script async="" data-chunk="core-icons-inbox-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-inbox-svg.149edca4fd1e661cba53.js"></script>
<script async="" data-chunk="routes-Tutorials" src="./API Documentation_ Direct Debit APIs_files/routes-Tutorials.62176318efe03678558a.js"></script>
<script async="" data-chunk="core-icons-star-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-star-svg.b4e382f3c0a9bfe7faa8.js"></script>
<script async="" data-chunk="routes-Suggestions-ngz-Header" src="./API Documentation_ Direct Debit APIs_files/routes-Suggestions-ngz-Header.6dd03d5ad8adf3769195.js"></script>
<script async="" data-chunk="ngz" src="./API Documentation_ Direct Debit APIs_files/ngz.f158c5fcbef9f77398f7.js"></script>
<script async="" data-chunk="core-icons-key-svg" src="./API Documentation_ Direct Debit APIs_files/core-icons-key-svg.1832e12a64afa7e249a9.js"></script>
<script async="" data-chunk="New" src="./API Documentation_ Direct Debit APIs_files/New.eb7645286e26aeac12e5.js"></script></div><script id="hub-me" type="application/json" data-json="{&quot;loggedIn&quot;:true,&quot;search&quot;:{&quot;app&quot;:&quot;T28YKFATPY&quot;,&quot;token&quot;:&quot;MTRmYTlmZTU4MjZhNGJiNTFkZDk1MGUxOTE3Njc1MGQzNjI1MmE3YTNjMDE1MWM4YzNlODdlMjQ0MzIyYjgzOHRhZ0ZpbHRlcnM9KHByb2plY3Q6NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2JjKSwodmVyc2lvbjpub25lLHZlcnNpb246NjQ3NzE3OWRiZmI4NTAwMDJhNDEwN2M0KSwoaGlkZGVuOm5vbmUsaGlkZGVuOmZhbHNlKSwoaW5kZXg6Q3VzdG9tUGFnZSxpbmRleDpQYWdlLGluZGV4OkJsb2csaW5kZXg6RGlzY3Vzcyk=&quot;,&quot;filters&quot;:&quot;tagFilters=(project:6477179dbfb850002a4107bc),(version:none,version:6477179dbfb850002a4107c4),(hidden:none,hidden:false),(index:CustomPage,index:Page,index:Blog,index:Discuss)&quot;,&quot;metaData&quot;:[{&quot;modules&quot;:{&quot;landing&quot;:false,&quot;docs&quot;:true,&quot;examples&quot;:true,&quot;reference&quot;:false,&quot;graphql&quot;:false,&quot;changelog&quot;:true,&quot;discuss&quot;:true,&quot;suggested_edits&quot;:true,&quot;logs&quot;:false,&quot;custompages&quot;:false,&quot;tutorials&quot;:false},&quot;id&quot;:&quot;6477179dbfb850002a4107bc&quot;,&quot;name&quot;:&quot;Direct Debit API Documentation&quot;,&quot;subdomain&quot;:&quot;api-documen&quot;,&quot;subpath&quot;:&quot;&quot;,&quot;nav_names&quot;:{&quot;docs&quot;:&quot;&quot;,&quot;reference&quot;:&quot;&quot;,&quot;changelog&quot;:&quot;&quot;,&quot;discuss&quot;:&quot;&quot;,&quot;recipes&quot;:&quot;&quot;,&quot;tutorials&quot;:&quot;&quot;}}]},&quot;isAdmin&quot;:true,&quot;user&quot;:{&quot;email&quot;:&quot;adelebukky150@gmail.com&quot;,&quot;name&quot;:&quot;Oladele Oluwabukola&quot;,&quot;email_verified&quot;:true,&quot;teammateUserId&quot;:&quot;647285e0f88f5100273cb433&quot;,&quot;fromReadmeKey&quot;:&quot;779f9&quot;,&quot;keys&quot;:null,&quot;iat&quot;:1685543768,&quot;exp&quot;:1685543888},&quot;_id&quot;:&quot;64771a44a4cec60282f206bd&quot;}"></script><script id="readme-data-baseUrl" type="application/json" data-json="&quot;/&quot;"></script><div class="hub-footer"></div></body></html>
