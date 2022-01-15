@import url("https://capnkitten.github.io/BetterDiscord/Themes/user-icons.css");
:root {
  --app-font: 'Google Sans';
  --app-bg: var(--main-alt);
  --accent-hue: 224;
  --accent-saturation: 71%;
  --accent-lightness: 61%;
  --accent-hsl: var(--accent-hue),calc(var(--accent-saturation) * var(--saturation-factor)),var(--accent-lightness);
  --avatar-radius: 50%;
  --accent-button-action: #fff;
  --accent-button-action-hover: 0.06;
  --accent-button-action-active: 0.12;
  --accent-text-color: #fff;
  --alert-color: #f04747;
  --alert-button-action: #fff;
  --alert-button-action-hover: 0.1;
  --alert-button-action-active: 0.2;
  --alert-text-color: #fff;
  --success-color: #43b581;
  --message-radius: 19px;
  --message-padding: 8px 12px;
  --message-padding-alt: 4px 12px 8px 12px;
  --main-textarea-radius: 24px;
  --media-radius: 19px;
  --card-radius: 8px;
  --card-radius-big: 16px;
  --button-height: 38px;
  --button-radius: calc(var(--button-height) / 2);
  --button-padding: 0 20px;
  --input-height: var(--button-height);
  --input-radius: var(--button-radius);
  --popout-radius: var(--card-radius);
  --popout-radius-big: var(--card-radius-big);
  --spotify-color: #1db954;
  --stream-color: #593695;
  --stream-flash: 89,54,149;
  --xbox-color: #107c10;
  --supporter-color: hsl(var(--accent-hsl));
  --tooltip-color: rgba(97,97,97,0.9);
  --tooltip-text-color: #ddd;
  --tooltip-font-size: 12px;
  --tooltip-padding: 8px;
  --tooltip-radius: 8px;
  --tooltip-shadow: 0px 5px 15px rgba(0,0,0,0.2);
  --shadow-1dp: 0 2px 2px 0 rgba(0,0,0,0.14), 0 3px 1px -2px rgba(0,0,0,0.2), 0 1px 5px 0 rgba(0,0,0,0.12);
  --shadow-2dp: 0 4px 5px 0 rgba(0,0,0,0.14), 0 1px 10px 0 rgba(0,0,0,0.12), 0 2px 4px -1px rgba(0,0,0,0.2);
  --shadow-3dp: 0 8px 10px 1px rgba(0,0,0,0.14), 0 3px 14px 2px rgba(0,0,0,0.12), 0 5px 5px -3px rgba(0,0,0,0.2);
  --default-animation: cubic-bezier(0.4,0,0.2,1);
  --default-time: 250ms;
  --window-title-bar: 22px;
  --window-button-min: #ffbd44;
  --window-button-max: #00ca4e;
  --window-button-close: #ff605c;
  --code-font: Consolas,Andale Mono WT,Andale Mono,Lucida Console,Lucida Sans Typewriter,DejaVu Sans Mono,Bitstream Vera Sans Mono,Liberation Mono,Nimbus Mono L,Monaco,Courier New,Courier,monospace; }

.theme-dark {
  --main-color: #16171a;
  --main-alt: #0f1012;
  --server-color: #232327;
  --status-picker-color: #2c2d31;
  --sidebar-panel-color: #212226;
  --chat-color: #202225;
  --message-color: #292d30;
  --message-color-hover: #303438;
  --message-color-alt: #1c1e21;
  --attachment-color: rgb(0,0,0,0.325);
  --main-textarea-color: #303338;
  --main-textarea-color-alt: #3b3f42;
  --main-textarea-border: #3e434a;
  --typing-color: rgba(32,34,37,0.9);
  --popout-color: #2c2f33;
  --popout-color-alt: #202225;
  --popout-header-border: #444;
  --separator-color: #444;
  --input-color: rgba(255,255,255,0.075);
  --input-border-color: #444;
  --input-padding: 0 8px;
  --tab-border-color: #fff;
  --menu-item-hover: rgba(255,255,255,0.075);
  --menu-item-select: rgba(255,255,255,0.1);
  --menu-item-select-accent: hsla(var(--accent-hsl),0.25);
  --menu-item-text-color: #aaa;
  --card-color: transparent;
  --card-color-hover: #292b2f;
  --card-color-alt: #2a2c30;
  --card-color-alt-hover: #35383d;
  --card-border-color: #444;
  --card-header-text-color: #dcddde;
  --button-link-color: 255,255,255;
  --button-link-text-color: #fff;
  --button-border-color: #444;
  --slider-color: #4f545c;
  --switch-knob-color: 0,0%,47%;
  --switch-slider-color: 240,1%,20%;
  --md-ripple-color: 0,100%,100%;
  --emoji-category-header: rgba(44,47,51,0.95);
  --scrollbar-color: 255,255,255;
  --window-button: rgba(255,255,255,0.1);
  --window-button-inactive: rgba(255,255,255,0.05); }

.theme-light {
  --main-color: #e8eaeb;
  --main-alt: #ddd;
  --server-color: #eee;
  --status-picker-color: #d2d4d5;
  --sidebar-panel-color: #dbddde;
  --chat-color: #fff;
  --message-color: #edeff0;
  --message-color-hover: #e1e2e3;
  --message-color-alt: #e8e8e8;
  --attachment-color: rgba(0,0,0,0.1);
  --main-textarea-color: #fff;
  --main-textarea-color-alt: #ccc;
  --main-textarea-border: #dadce0;
  --typing-color: rgba(255,255,255,0.8);
  --popout-color: #fff;
  --popout-color-alt: #e5e5e5;
  --popout-header-border: #ccc;
  --separator-color: #ccc;
  --input-color: #d2d4d4;
  --input-border-color: #aaa;
  --tab-border-color: #777;
  --menu-item-hover: rgba(0,0,0,0.1);
  --menu-item-select: rgba(0,0,0,0.125);
  --menu-item-select-accent: hsla(var(--accent-hsl),0.25);
  --menu-item-text-color: #333;
  --card-color: transparent;
  --card-color-hover: #eee;
  --card-color-alt: transparent;
  --card-color-alt-hover: #d4d4d4;
  --card-border-color: #ccc;
  --card-header-text-color: #333;
  --button-link-color: 0,0,0;
  --button-link-text-color: #333;
  --button-border-color: #ccc;
  --slider-color: #999;
  --switch-knob-color: 0,0%,100%;
  --switch-slider-color: 210,1%,73%;
  --md-ripple-color: 0,0%,0%;
  --emoji-category-header: rgba(255,255,255,0.9);
  --scrollbar-color: 0,0,0;
  --window-button: rgba(0,0,0,0.2);
  --window-button-inactive: rgba(0,0,0,0.1); }

/*
 *
 *	APP ELEMENTS
 *
 */
* {
  font-family: var(--app-font), sans-serif !important; }

::selection {
  background: hsla(var(--accent-hsl), 0.35);
  text-shadow: none; }

body,
.app-3xd6d0,
.appMount-2yBXZl {
  background-color: transparent; }

.bg-1QIAus,
.container-2RRFHK {
  background: var(--app-bg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover; }

.platform-win .bg-1QIAus {
  top: calc((var(--window-title-bar) + 4px) * -1); }

.anchor-1MIwyf {
  color: hsl(var(--accent-hsl)); }

.low-saturation .anchor-1MIwyf {
  color: hsl(var(--accent-hsl)); }

.wordmark-2u86JB.wordmarkWindows-2dq6rw {
  width: auto;
  height: var(--window-title-bar);
  padding: 0 0 0 4px;
  line-height: var(--window-title-bar);
  font-size: 0.9em;
  color: var(--text-normal); }
  .wordmark-2u86JB.wordmarkWindows-2dq6rw:before, .wordmark-2u86JB.wordmarkWindows-2dq6rw:after {
    position: relative;
    width: auto;
    height: 22px; }
  .wordmark-2u86JB.wordmarkWindows-2dq6rw:after {
    content: "Discord"; }
  .wordmark-2u86JB.wordmarkWindows-2dq6rw svg {
    display: none; }

.typeWindows-2-g3UY.withFrame-2dL45i {
  height: var(--window-title-bar);
  margin-top: 0; }
.typeWindows-2-g3UY .winButton-3UMjdg {
  height: var(--window-title-bar);
  top: 0; }
  .typeWindows-2-g3UY .winButton-3UMjdg:before {
    position: absolute;
    content: " ";
    width: 12px;
    height: 12px;
    background-position: center;
    -webkit-mask-size: contain;
    mask-size: contain;
    filter: brightness(40%);
    z-index: 2;
    opacity: 0;
    transition: var(--default-time) var(--default-animation) opacity;
    pointer-events: none; }
  .typeWindows-2-g3UY .winButton-3UMjdg:hover:before {
    opacity: 1; }
  .typeWindows-2-g3UY .winButton-3UMjdg:after {
    position: absolute;
    content: " ";
    width: 16px;
    height: 16px;
    border-radius: 50%;
    background-color: var(--window-button);
    transition: var(--default-time) var(--default-animation);
    pointer-events: none; }
  .typeWindows-2-g3UY .winButton-3UMjdg:active:after {
    opacity: 0.65; }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonMinMax-3RsPUg:nth-last-of-type(2):hover:after {
    background-color: var(--window-button-max); }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonMinMax-3RsPUg:nth-last-of-type(2):before {
    background-color: var(--window-button-max);
    -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_maximize.svg);
    mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_maximize.svg);
    -webkit-mask-repeat: no-repeat;
    mask-repeat: no-repeat; }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonMinMax-3RsPUg:nth-last-of-type(1):hover:after {
    background-color: var(--window-button-min); }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonMinMax-3RsPUg:nth-last-of-type(1):before {
    background-color: var(--window-button-min);
    -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_minimize.svg);
    mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_minimize.svg);
    -webkit-mask-repeat: no-repeat;
    mask-repeat: no-repeat; }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonClose-3Q8ZH5:hover:after {
    background-color: var(--window-button-close); }
  .typeWindows-2-g3UY .winButton-3UMjdg.winButtonClose-3Q8ZH5:before {
    background-color: var(--window-button-close);
    -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_close.svg);
    mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/window_close.svg);
    -webkit-mask-repeat: no-repeat;
    mask-repeat: no-repeat; }
  .typeWindows-2-g3UY .winButton-3UMjdg:hover, .typeWindows-2-g3UY .winButton-3UMjdg:active {
    background-color: transparent; }
  .typeWindows-2-g3UY .winButton-3UMjdg svg {
    display: none; }

html:not(.app-focused) .typeWindows-2-g3UY .winButton-3UMjdg:after {
  background-color: var(--window-button-inactive); }
html:not(.app-focused) .typeWindows-2-g3UY .winButton-3UMjdg.winButtonMinMax-3RsPUg:after {
  background-color: var(--window-button-inactive); }

/*
 *
 *	NOTICES
 *
 */
.notice-2HEN-u {
  border-radius: 0;
  z-index: 1 !important; }
  .notice-2HEN-u.notice-12Koq-, .notice-2HEN-u.notice-1x8lm- {
    background-color: hsl(var(--accent-hsl)); }
    .notice-2HEN-u.notice-12Koq- .button-f2h6uQ, .notice-2HEN-u.notice-1x8lm- .button-f2h6uQ {
      background-color: rgba(var(--button-link-color), 0.15) !important;
      box-shadow: none !important; }
    .notice-2HEN-u.notice-12Koq- .header-26uvhX, .notice-2HEN-u.notice-1x8lm- .header-26uvhX {
      color: var(--accent-text-color); }
  .notice-2HEN-u .button-1iHNQ2 {
    padding: var(--button-padding);
    background-color: rgba(var(--button-link-color), 0.2);
    border-radius: var(--button-radius);
    border: none;
    line-height: 24px;
    color: var(--button-text-color); }
    .notice-2HEN-u .button-1iHNQ2:hover {
      background-color: rgba(var(--button-link-color), 0.35);
      color: var(--button-text-color); }

/*
 *
 *	LOGIN SCREEN
 *
 */
.authBox-1HR6Ha {
  padding: 16px;
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big);
  box-shadow: var(--shadow-3dp); }
  .authBox-1HR6Ha .mainLoginContainer-wHmAjP {
    margin-right: 24px;
    padding-right: 24px;
    border-right: 1px solid var(--card-border-color); }
  .authBox-1HR6Ha .verticalSeparator-2r9gHa {
    display: none; }
  .authBox-1HR6Ha .qrLogin-1ejtpI {
    height: 320px; }
  .authBox-1HR6Ha .needAccount-MrvMN7 {
    line-height: 24px; }
  .authBox-1HR6Ha .linkButton-2ax8wP {
    --button-height: 17px;
    --button-padding: 0;
    background-color: transparent !important;
    font-size: 14px !important;
    font-weight: 400 !important; }
    .authBox-1HR6Ha .linkButton-2ax8wP:hover {
      text-decoration: underline !important; }
  .authBox-1HR6Ha .needAccount-MrvMN7 + .linkButton-2ax8wP {
    position: relative;
    top: -3px; }

.navRow-dG-XX8 {
  height: auto;
  padding: 8px;
  background-color: transparent;
  border-top: 1px solid var(--card-border-color); }
  .navRow-dG-XX8 .button-1cRKG6 {
    margin: 0; }

/*
 *
 *	ACCOUNT SWITCHER
 *
 */
[aria-label="Manage Accounts"] .modal-1ocm0B {
  padding: 0; }

.list-3-WAYB {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .list-3-WAYB .accountCard-2lki2x {
    padding: 16px;
    background-color: transparent;
    border-radius: var(--card-radius-big);
    position: relative;
    border-bottom: none; }
    .list-3-WAYB .accountCard-2lki2x:after {
      position: absolute;
      content: " ";
      width: calc(100% - 64px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .list-3-WAYB .accountCard-2lki2x:last-of-type:after {
      display: none; }
  .list-3-WAYB .userActionMenu-3-DfuT {
    background-color: transparent !important;
    border-radius: 50% !important;
    position: relative; }
    .list-3-WAYB .userActionMenu-3-DfuT:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .list-3-WAYB .userActionMenu-3-DfuT:hover:after {
      opacity: 1;
      transform: scale(1.2);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .list-3-WAYB .userActionMenu-3-DfuT:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
    .list-3-WAYB .userActionMenu-3-DfuT .contents-3ca1mk {
      height: 24px;
      transform: rotate(90deg); }
  .list-3-WAYB .separator-3pyJLj {
    display: none; }

.modalCloseButton-3DSpqK {
  z-index: 2; }
  .modalCloseButton-3DSpqK .contents-3ca1mk {
    height: 24px; }

.button-3e8L6b {
  margin: 16px 0 0; }

.container-5N5x2A {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--shadow-3dp); }
  .container-5N5x2A .pointer-1bsD64 {
    border-top-color: var(--popout-color); }

.actions-1qEPMo {
  margin: 16px 0 0; }

/* ACCOUNT SWITCHER -> ADD ACCOUNT */
.navRow-dG-XX8 {
  background-color: transparent !important; }
  .navRow-dG-XX8 .backButton-2rLJZw,
  .navRow-dG-XX8 .continueButton-3SZT3h {
    margin: 0; }

/*
 *
 *	AUTHORIZE APP
 *
 */
.oauth2Wrapper-p_8bbd {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf {
    padding: 0; }
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .header-3cN3a_ {
      border-radius: 0; }
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .header-3cN3a_,
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .scopes-uCLYQv {
      border-bottom: 1px solid var(--popout-header-border); }
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .header-3cN3a_,
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .scopes-uCLYQv,
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .applicationDetails-3O3kc- {
      padding: 16px; }
    .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .entry-2w47SK {
      margin-top: 0;
      margin-bottom: 8px; }
      .oauth2Wrapper-p_8bbd .authorize-2xTTr- .content-3oGIwf .entry-2w47SK:last-child {
        margin-bottom: 0; }
  .oauth2Wrapper-p_8bbd .authorize-2xTTr- .footer-3Gu_Tl {
    padding: 8px;
    background-color: transparent;
    border-radius: 0 0 var(--popout-radius-big) var(--popout-radius-big);
    border-top: 1px solid var(--popout-header-border); }

/*
 *
 *	TITLE BAR
 *
 */
.title-31SJ6t {
  z-index: 1; }

.container-ZMc96U {
  box-shadow: var(--elevation-low); }
  .container-ZMc96U.transparent-1lUmft {
    box-shadow: none; }
  .container-ZMc96U.themed-Hp1KC_ {
    background-color: var(--main-color); }

.children-3xh0VB:after {
  background: linear-gradient(90deg, transparent 0, var(--main-color)) !important; }
.children-3xh0VB .topPill-3DJJNV {
  height: 100%; }
  .children-3xh0VB .topPill-3DJJNV .item-3XjbnG {
    height: 48px;
    padding: 0 8px;
    line-height: 48px;
    background-color: transparent !important;
    border-radius: 0;
    color: var(--interactive-normal) !important; }
    .children-3xh0VB .topPill-3DJJNV .item-3XjbnG:hover {
      color: var(--interactive-hover) !important; }
    .children-3xh0VB .topPill-3DJJNV .item-3XjbnG[aria-selected="true"] {
      position: relative;
      background-color: transparent !important;
      color: var(--interactive-active) !important; }
      .children-3xh0VB .topPill-3DJJNV .item-3XjbnG[aria-selected="true"]:after {
        position: absolute;
        content: " ";
        width: 90%;
        height: 3px;
        left: 0;
        right: 0;
        bottom: 0;
        margin: 0 auto;
        background: var(--tab-border-color);
        border-radius: 3px 3px 0 0;
        transition: var(--default-time) ease all; }

.topic-11NuQZ a {
  color: hsl(var(--accent-hsl)); }

.wrapper-1ZcZW- {
  background-color: hsla(var(--accent-hsl), 0.2);
  color: hsl(var(--accent-hsl)); }
  .wrapper-1ZcZW-:hover {
    background-color: hsla(var(--accent-hsl), 0.35);
    color: hsl(var(--accent-hsl)); }

/* TITLE BAR -> SEARCH BAR */
.search-1FM8Qc {
  width: 160px;
  transition: 300ms ease width; }
  .search-1FM8Qc .searchBar-zdmu7v {
    width: 100%;
    height: 32px;
    background-color: var(--input-color);
    border-radius: 16px; }
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-root {
      padding: 6px 0;
      padding-left: 8px; }
      .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-root .public-DraftEditorPlaceholder-root {
        padding-left: 2px; }
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchFilter-2UfsDk,
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchFilter-2UfsDk + span[data-offset-key],
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchAnswer-23w-CH span[data-offset-key] {
      background-color: rgba(255, 255, 255, 0.15); }
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchFilter-2UfsDk {
      margin-right: 2px;
      padding: 0 4px 0 8px;
      border-radius: 10px 0 0 10px; }
      .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchFilter-2UfsDk:only-child {
        padding: 0 8px;
        border-radius: 11px; }
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchAnswer-23w-CH {
      background-color: transparent; }
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchFilter-2UfsDk + span[data-offset-key],
    .search-1FM8Qc .searchBar-zdmu7v .DraftEditor-editorContainer .searchAnswer-23w-CH span[data-offset-key] {
      display: inline-block;
      height: 20px;
      margin: 0 2px 0 -2px;
      padding: 0px 8px 0px 0;
      border-radius: 0 11px 11px 0;
      color: #fff; }
    .search-1FM8Qc .searchBar-zdmu7v .icon-1nNws_ {
      width: 32px;
      height: 32px; }
  .search-1FM8Qc.open-3y3yI_ {
    width: 240px; }

/*.search-1FM8Qc {
	width: 32px;

	&:focus-within,
	&.open-3y3yI_ {
		width: 240px;

		.searchBar-zdmu7v {
			.DraftEditor-root {
				padding-left: 8px;
			}
		}
	}

	.searchBar-zdmu7v {
		.DraftEditor-root {
			padding-left: 0;
		}
	}
}*/
/* TITLE BAR -> ICONS */
.iconWrapper-2awDjA.clickable-ZD7xvu {
  position: relative; }
  .iconWrapper-2awDjA.clickable-ZD7xvu:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--md-ripple-color), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .iconWrapper-2awDjA.clickable-ZD7xvu:hover:after {
    opacity: 1;
    transform: scale(1.5);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .iconWrapper-2awDjA.clickable-ZD7xvu:active:after {
    background-color: hsla(var(--md-ripple-color), 0.2); }
.iconWrapper-2awDjA foreignObject {
  mask: none !important; }
.iconWrapper-2awDjA .icon-2xnN2Y path {
  /* TITLE BAR -> ICONS -> REFRESH STAGE DISCOVERY */
  /* TITLE BAR -> ICONS -> NEW GROUP DM */
  /* TITLE BAR -> ICONS -> START VOICE CALL */
  /* TITLE BAR -> ICONS -> START VIDEO CALL */
  /* TITLE BAR -> ICONS -> ADD FRIENDS TO DM */
  /* TITLE BAR -> ICONS -> MUTE CHANNEL */
  /* TITLE BAR -> ICONS -> UNMUTE CHANNEL */
  /* TITLE BAR -> ICONS -> PINNED MESSAGES */
  /* TITLE BAR -> ICONS -> MEMBERS LIST */
  /* TITLE BAR -> ICONS -> UPDATE */
  /* TITLE BAR -> ICONS -> INBOX */
  /* TITLE BAR -> ICONS -> HELP */ }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M12 2C6.485 2 2 6.485 2 12H5.33333C5.33333 8.32333 8.32333 5.33333 12 5.33333C15.6767 5.33333 18.6667 8.32333 18.6667 12C18.6667 15.6767 15.6767 18.6667 12 18.6667C10.2033 18.6667 8.55833 17.9333 7.315 16.6867L10.3333 13.6667H2V22L4.935 19.065C6.79833 20.94 9.30167 22 12 22C17.515 22 22 17.515 22 12C22 6.48667 17.515 2 12 2Z"] {
    d: path("M17.65 6.35C16.2 4.9 14.21 4 12 4c-4.42 0-7.99 3.58-7.99 8s3.57 8 7.99 8c3.73 0 6.84-2.55 7.73-6h-2.08c-.82 2.33-3.04 4-5.65 4-3.31 0-6-2.69-6-6s2.69-6 6-6c1.66 0 3.14.69 4.22 1.78L13 11h7V4l-2.35 2.35z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M20.998 0V3H23.998V5H20.998V8H18.998V5H15.998V3H18.998V0H20.998ZM2.99805 20V24L8.33205 20H14.998C16.102 20 16.998 19.103 16.998 18V9C16.998 7.896 16.102 7 14.998 7H1.99805C0.894047 7 -0.00195312 7.896 -0.00195312 9V18C-0.00195312 19.103 0.894047 20 1.99805 20H2.99805Z"] {
    d: path("M4 4h16v12H5.17L4 17.17V4m0-2c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2H4zm2 10h12v2H6v-2zm0-3h12v2H6V9zm0-3h12v2H6V6z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M11 5V3C16.515 3 21 7.486 21 13H19C19 8.589 15.411 5 11 5ZM17 13H15C15 10.795 13.206 9 11 9V7C14.309 7 17 9.691 17 13ZM11 11V13H13C13 11.896 12.105 11 11 11ZM14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16Z"] {
    d: path("M6.54 5c.06.89.21 1.76.45 2.59l-1.2 1.2c-.41-1.2-.67-2.47-.76-3.79h1.51m9.86 12.02c.85.24 1.72.39 2.6.45v1.49c-1.32-.09-2.59-.35-3.8-.75l1.2-1.19M7.5 3H4c-.55 0-1 .45-1 1 0 9.39 7.61 17 17 17 .55 0 1-.45 1-1v-3.49c0-.55-.45-1-1-1-1.24 0-2.45-.2-3.57-.57-.1-.04-.21-.05-.31-.05-.26 0-.51.1-.71.29l-2.2 2.2c-2.83-1.45-5.15-3.76-6.59-6.59l2.2-2.2c.28-.28.36-.67.25-1.02C8.7 6.45 8.5 5.25 8.5 4c0-.55-.45-1-1-1z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
    d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M21 3H24V5H21V8H19V5H16V3H19V0H21V3ZM10 12C12.205 12 14 10.205 14 8C14 5.795 12.205 4 10 4C7.795 4 6 5.795 6 8C6 10.205 7.795 12 10 12ZM10 13C5.289 13 2 15.467 2 19V20H18V19C18 15.467 14.711 13 10 13Z"] {
    d: path("M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0-6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4zm-6 4c.22-.72 3.31-2 6-2 2.7 0 5.8 1.29 6 2H9zm-3-3v-3h3v-2H6V7H4v3H1v2h3v3z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M18 9V14C18 15.657 19.344 17 21 17V18H3V17C4.656 17 6 15.657 6 14V9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9ZM11.9999 21C10.5239 21 9.24793 20.19 8.55493 19H15.4449C14.7519 20.19 13.4759 21 11.9999 21Z"] {
    d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5v6z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M21.178 1.70703L22.592 3.12103L4.12103 21.593L2.70703 20.178L21.178 1.70703Z"] {
    d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm0-15.5c2.49 0 4 2.02 4 4.5v.1l2 2V11c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68c-.24.06-.47.15-.69.23l1.64 1.64c.18-.02.36-.05.55-.05zM5.41 3.35L4 4.76l2.81 2.81C6.29 8.57 6 9.74 6 11v5l-2 2v1h14.24l1.74 1.74 1.41-1.41L5.41 3.35zM16 17H8v-6c0-.68.12-1.32.34-1.9L16 16.76V17z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M21.178 1.70703L22.592 3.12103L4.12103 21.593L2.70703 20.178L21.178 1.70703Z"] ~ path {
    display: none; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M22 12L12.101 2.10101L10.686 3.51401L12.101 4.92901L7.15096 9.87801V9.88001L5.73596 8.46501L4.32196 9.88001L8.56496 14.122L2.90796 19.778L4.32196 21.192L9.97896 15.536L14.222 19.778L15.636 18.364L14.222 16.95L19.171 12H19.172L20.586 13.414L22 12Z"] {
    d: path("M16,12V4H17V2H7V4H8V12L6,14V16H11.2V22H12.8V16H18V14L16,12M8.8,14L10,12.8V4H14V12.8L15.2,14H8.8Z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"], .iconWrapper-2awDjA .icon-2xnN2Y path[d="M6 1C3.243 1 1 3.244 1 6c0 2.758 2.243 5 5 5s5-2.242 5-5c0-2.756-2.243-5-5-5zm0 2.376a.625.625 0 110 1.25.625.625 0 010-1.25zM7.5 8.5h-3v-1h1V6H5V5h1a.5.5 0 01.5.5v2h1v1z"] {
    d: path("M16.5,6.5A2,2 0 0,1 18.5,8.5A2,2 0 0,1 16.5,10.5A2,2 0 0,1 14.5,8.5A2,2 0 0,1 16.5,6.5M16.5,12A3.5,3.5 0 0,0 20,8.5A3.5,3.5 0 0,0 16.5,5A3.5,3.5 0 0,0 13,8.5A3.5,3.5 0 0,0 16.5,12M7.5,6.5A2,2 0 0,1 9.5,8.5A2,2 0 0,1 7.5,10.5A2,2 0 0,1 5.5,8.5A2,2 0 0,1 7.5,6.5M7.5,12A3.5,3.5 0 0,0 11,8.5A3.5,3.5 0 0,0 7.5,5A3.5,3.5 0 0,0 4,8.5A3.5,3.5 0 0,0 7.5,12M21.5,17.5H14V16.25C14,15.79 13.8,15.39 13.5,15.03C14.36,14.73 15.44,14.5 16.5,14.5C18.94,14.5 21.5,15.71 21.5,16.25M12.5,17.5H2.5V16.25C2.5,15.71 5.06,14.5 7.5,14.5C9.94,14.5 12.5,15.71 12.5,16.25M16.5,13C15.3,13 13.43,13.34 12,14C10.57,13.33 8.7,13 7.5,13C5.33,13 1,14.08 1,16.25V19H23V16.25C23,14.08 18.67,13 16.5,13Z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M6 1C3.243 1 1 3.244 1 6c0 2.758 2.243 5 5 5s5-2.242 5-5c0-2.756-2.243-5-5-5zm0 2.376a.625.625 0 110 1.25.625.625 0 010-1.25zM7.5 8.5h-3v-1h1V6H5V5h1a.5.5 0 01.5.5v2h1v1z"] {
    transform: scale(0.5); }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] ~ path {
    display: none; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M16.293 9.293L17.707 10.707L12 16.414L6.29297 10.707L7.70697 9.293L11 12.586V2H13V12.586L16.293 9.293ZM18 20V18H20V20C20 21.102 19.104 22 18 22H6C4.896 22 4 21.102 4 20V18H6V20H18Z"] {
    d: path("M11 8v5l4.25 2.52.77-1.28-3.52-2.09V8zm10 2V3l-2.64 2.64C16.74 4.01 14.49 3 12 3c-4.97 0-9 4.03-9 9s4.03 9 9 9 9-4.03 9-9h-2c0 3.86-3.14 7-7 7s-7-3.14-7-7 3.14-7 7-7c1.93 0 3.68.79 4.95 2.05L14 10h7z") !important;
    fill: var(--success-color); }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M19 3H4.99C3.88 3 3.01 3.89 3.01 5L3 19C3 20.1 3.88 21 4.99 21H19C20.1 21 21 20.1 21 19V5C21 3.89 20.1 3 19 3ZM19 15H15C15 16.66 13.65 18 12 18C10.35 18 9 16.66 9 15H4.99V5H19V15Z"] {
    d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H5v-3h3.56c.69 1.19 1.97 2 3.45 2s2.75-.81 3.45-2H19v3zm0-5h-4.99c0 1.1-.9 2-2 2s-2-.9-2-2H5V5h14v9z") !important; }
  .iconWrapper-2awDjA .icon-2xnN2Y path[d="M12 2C6.486 2 2 6.487 2 12C2 17.515 6.486 22 12 22C17.514 22 22 17.515 22 12C22 6.487 17.514 2 12 2ZM12 18.25C11.31 18.25 10.75 17.691 10.75 17C10.75 16.31 11.31 15.75 12 15.75C12.69 15.75 13.25 16.31 13.25 17C13.25 17.691 12.69 18.25 12 18.25ZM13 13.875V15H11V12H12C13.104 12 14 11.103 14 10C14 8.896 13.104 8 12 8C10.896 8 10 8.896 10 10H8C8 7.795 9.795 6 12 6C14.205 6 16 7.795 16 10C16 11.861 14.723 13.429 13 13.875Z"] {
    d: path("M11,18H13V16H11V18M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M12,20C7.59,20 4,16.41 4,12C4,7.59 7.59,4 12,4C16.41,4 20,7.59 20,12C20,16.41 16.41,20 12,20M12,6A4,4 0 0,0 8,10H10A2,2 0 0,1 12,8A2,2 0 0,1 14,10C14,12 11,11.75 11,15H13C13,12.75 16,12.5 16,10A4,4 0 0,0 12,6Z") !important; }

/*
 *
 *	SERVER LIST
 *
 */
.wrapper-1_HaEi {
  background-color: var(--server-color); }
  .wrapper-1_HaEi .scroller-3X7KbA {
    background-color: transparent; }
  .wrapper-1_HaEi .tree-3agP2X:focus {
    outline: none; }

.wrapper-3kah-n .childWrapper-1j_1ub {
  background-color: hsl(var(--accent-hsl));
  border-radius: var(--avatar-radius);
  color: var(--accent-text-color); }
.wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub {
  background-color: hsl(var(--accent-hsl));
  color: var(--accent-text-color); }
.wrapper-3kah-n:hover .childWrapper-1j_1ub {
  background-color: hsl(var(--accent-hsl));
  color: var(--accent-text-color); }

.circleButtonMask-1_597P,
.circleIconButton-1VxDrg {
  border-radius: var(--avatar-radius) !important;
  background-color: hsl(var(--accent-hsl));
  color: var(--accent-text-color); }
  .circleButtonMask-1_597P.selected-2r1Hvo,
  .circleIconButton-1VxDrg.selected-2r1Hvo {
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color); }

.childWrapper-1j_1ub rect {
  rx: var(--avatar-radius); }

.circleButtonMask-1_597P {
  background-color: var(--menu-item-select) !important;
  transition: var(--default-time) var(--default-animation) background-color; }
  .circleButtonMask-1_597P path {
    transition: var(--default-time) var(--default-animation) fill; }
  .circleButtonMask-1_597P:hover {
    background-color: hsl(var(--accent-hsl)) !important; }
    .circleButtonMask-1_597P:hover path {
      fill: var(--accent-text-color); }

/* SERVER LIST -> SERVER */
.listItem-3SmSlK .wrapper-28eC3z {
  border-radius: var(--avatar-radius); }
  .listItem-3SmSlK .wrapper-28eC3z .icon-3AqZ2e {
    border-radius: var(--avatar-radius); }
  .listItem-3SmSlK .wrapper-28eC3z .lowerBadge-3WTshO {
    width: auto;
    height: auto; }
    .listItem-3SmSlK .wrapper-28eC3z .lowerBadge-3WTshO .numberBadge-37OJ3S {
      background-color: var(--alert-color) !important;
      box-shadow: var(--shadow-1dp);
      color: var(--alert-text-color); }
    .listItem-3SmSlK .wrapper-28eC3z .lowerBadge-3WTshO.unread-badge {
      right: unset;
      left: -2px; }
      .listItem-3SmSlK .wrapper-28eC3z .lowerBadge-3WTshO.unread-badge .numberBadge-37OJ3S {
        background-color: hsl(var(--accent-hsl)) !important;
        color: var(--accent-text-color) !important; }
  .listItem-3SmSlK .wrapper-28eC3z .upperBadge-1V6Iyi .iconBadge-1D5-9X {
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color);
    border-radius: 50%;
    animation: audio-flash 2.5s linear infinite; }
    .listItem-3SmSlK .wrapper-28eC3z .upperBadge-1V6Iyi .iconBadge-1D5-9X.participating-2Z81oO {
      background-color: hsl(var(--accent-hsl));
      color: var(--accent-text-color); }
    .listItem-3SmSlK .wrapper-28eC3z .upperBadge-1V6Iyi .iconBadge-1D5-9X .icon-2Ug6UV path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"] {
      d: path("M3 9v6h4l5 5V4L7 9H3zm7-.17v6.34L7.83 13H5v-2h2.83L10 8.83zM16.5 12c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77 0-4.28-2.99-7.86-7-8.77z"); }
    .listItem-3SmSlK .wrapper-28eC3z .upperBadge-1V6Iyi .iconBadge-1D5-9X .icon-2Ug6UV path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
      d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z"); }
.listItem-3SmSlK.frame-oXWS21 .childWrapper-1j_1ub {
  padding: 0 6px;
  border-radius: 12px;
  text-transform: capitalize; }

.folder-241Joy,
.folderIconWrapper-1oRIZr {
  border-radius: var(--avatar-radius); }

.centerTarget-S6BLFQ.dragOver-1OKbo2:before {
  background-color: hsl(var(--accent-hsl));
  box-shadow: var(--shadow-1dp); }

.target-1eRTCg.dragOver-1OKbo2:before {
  background-color: hsl(var(--accent-hsl)); }

/* SERVER LIST -> SERVER -> FOLDER */
.folder-1hbNCn,
.folderIconWrapper-1_bOZe {
  border-radius: var(--avatar-radius); }

.iconInactive-26M06U {
  border-radius: var(--avatar-radius); }

/*
 *
 *	INVITED TO SERVER
 *
 */
.container-1Gt1iQ {
  border-radius: var(--popout-radius-big);
  box-shadow: var(--shadow-3dp); }

.contentWrapper-3oy4Xo {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) 0 0 var(--popout-radius-big); }

.inviteSplash-2Q0PLE {
  border-radius: 0 var(--popout-radius-big) var(--popout-radius-big) 0; }

/*
 *
 *	CREATE/JOIN SERVER
 *
 */
.layer-1Ixpg3 .theme-light {
  --popout-color: #2c2f33;
  --popout-header-border: #444;
  --separator-color: #444;
  --card-color: transparent;
  --card-color-hover: #292b2f;
  --card-color-alt: #2a2c30;
  --card-color-alt-hover: #35383d;
  --card-border-color: #444;
  --card-header-text-color: #dcddde;
  --button-link-color: 255,255,255;
  --button-link-text-color: #fff;
  --md-ripple-color: 0,100%,100%;
  --header-primary: #fff;
  --header-secondary: #b9bbbe;
  --text-normal: #dcddde;
  --interactive-normal: #b9bbbe;
  --scrollbar-color: 255,255,255; }

.title-1LqMUp {
  margin-top: 0; }

.templatesList-uohY49,
.optionsList-dmHy1l {
  margin-top: 0; }

.container-x8Y1ix {
  margin-top: 8px;
  margin-bottom: 0;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  transition: var(--default-time) var(--default-animation) background-color; }
  .container-x8Y1ix:hover {
    background-color: var(--card-color-alt); }
  .container-x8Y1ix:first-child {
    margin-top: 0; }
  .container-x8Y1ix .text-PdAsFQ {
    color: var(--text-normal); }

.rowContainer-3t7486 {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .rowContainer-3t7486:hover {
    background-color: var(--card-color-alt); }

.skip-2hTIXL {
  margin-top: 16px;
  margin-bottom: 0; }

/*
 *
 *	HOME TAB
 *
 */
.privateChannels-oVe7HL {
  background-color: transparent; }
  .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG {
    height: 32px;
    padding: 0 10px;
    background-color: var(--input-color);
    border-radius: 16px; }
  .privateChannels-oVe7HL .scroller-WSmht3 {
    background-color: transparent; }
  .privateChannels-oVe7HL .content-2a4AW9 {
    margin-bottom: 20px; }
  .privateChannels-oVe7HL .container-1oeRFJ {
    margin-left: 0;
    padding: 0; }
    .privateChannels-oVe7HL .container-1oeRFJ .layout-1qmrhw {
      padding: 1px 16px;
      border-radius: 0 21px 21px 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .privateChannels-oVe7HL .container-1oeRFJ:hover .layout-1qmrhw {
        background-color: var(--menu-item-hover); }

      .privateChannels-oVe7HL .container-1oeRFJ.selected-1-Z6gm .layout-1qmrhw {
        background-color: var(--menu-item-select-accent); }

/* HOME TAB -> STAGE DISCOVERY */
.stageSection-3mAD8V {
  background-color: var(--chat-color); }

.container-2rNpDV {
  background-color: hsl(var(--accent-hsl));
  border-radius: var(--card-radius-big); }
  .container-2rNpDV .header-3g0E_g,
  .container-2rNpDV .body-3MGQWc {
    color: var(--accent-text-color) !important; }

.container-S9SaVf {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }
  .container-S9SaVf .contentContainer-r2-Vlj {
    padding: 0; }
    .container-S9SaVf .contentContainer-r2-Vlj .guildInfoContainer-1dd0zN {
      padding: 16px ;
      background-color: transparent;
      border-bottom: 1px solid var(--card-border-color);
      font-size: 1em;
      color: var(--card-header-text-color);
      font-weight: 500; }
      .container-S9SaVf .contentContainer-r2-Vlj .guildInfoContainer-1dd0zN .rightJustifiedContent-2QwekV {
        height: 20px; }
    .container-S9SaVf .contentContainer-r2-Vlj .topicText-2H6hYP {
      margin: 0 0 12px;
      padding: 16px 16px 0; }
    .container-S9SaVf .contentContainer-r2-Vlj .grid-3fdl0Y {
      padding: 0 16px 16px; }

.container-1oAagU {
  background-color: var(--main-color); }
  .container-1oAagU .scroller-hE2gWq {
    margin-left: 0;
    border-left: none; }

/* HOME TAB - > FRIENDS LIST */
.container-2cd8Mz {
  background-color: var(--chat-color) !important; }

.theme-light .peopleColumn-1wMU14 .searchBar-2aylmZ .inner-2pOSmK {
  --input-color: #fff; }

.peopleColumn-1wMU14 .searchBar-2aylmZ {
  position: relative;
  width: 100%;
  height: auto;
  margin: 0 0 -56px;
  padding: 16px 16px 0;
  background-color: transparent;
  z-index: 99;
  overflow: visible; }
  .peopleColumn-1wMU14 .searchBar-2aylmZ:before {
    position: absolute;
    content: " ";
    width: calc(100% - 32px);
    height: 40px;
    background-color: var(--chat-color);
    box-shadow: var(--shadow-2dp);
    border-radius: 20px;
    transition: var(--default-time) var(--default-animation) box-shadow; }
  .peopleColumn-1wMU14 .searchBar-2aylmZ:focus-within:before {
    box-shadow: var(--shadow-3dp); }
  .peopleColumn-1wMU14 .searchBar-2aylmZ .inner-2pOSmK {
    background-color: var(--input-color);
    border-radius: 20px; }
    .peopleColumn-1wMU14 .searchBar-2aylmZ .inner-2pOSmK .input-2m5SfJ {
      height: 40px; }
      .peopleColumn-1wMU14 .searchBar-2aylmZ .inner-2pOSmK .input-2m5SfJ::-webkit-input-placeholder {
        font-weight: 500; }
    .peopleColumn-1wMU14 .searchBar-2aylmZ .inner-2pOSmK .iconLayout-3Bjizv {
      width: 40px;
      height: 40px; }

.peopleList-2VBrVI {
  margin-top: 0;
  padding-top: 64px; }
  .peopleList-2VBrVI .title-x4dI75 {
    height: 40px;
    margin: 0;
    padding: 0 16px;
    line-height: 40px;
    font-size: 14px;
    text-transform: none; }
  .peopleList-2VBrVI .peopleListItem-u6dGxF {
    margin: 0;
    padding: 0 16px;
    position: relative;
    border-bottom: none;
    border-radius: 0;
    border-top: none;
    transition: var(--default-time) var(--default-animation) background-color; }
    .peopleList-2VBrVI .peopleListItem-u6dGxF:after {
      position: absolute;
      content: " ";
      width: calc(100% - 60px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .peopleList-2VBrVI .peopleListItem-u6dGxF:last-of-type:after {
      display: none; }
    .peopleList-2VBrVI .peopleListItem-u6dGxF:hover {
      background-color: var(--menu-item-hover); }
    .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x- {
      background-color: transparent;
      position: relative; }
      .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x-:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x-:hover:after {
        opacity: 1;
        transform: scale(1);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x-:active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
      .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x- .icon-1WVg4I {
        transform: scale(1.2); }
        .peopleList-2VBrVI .peopleListItem-u6dGxF .actionButton-3-B2x- .icon-1WVg4I path[d="M4.79805 3C3.80445 3 2.99805 3.8055 2.99805 4.8V15.6C2.99805 16.5936 3.80445 17.4 4.79805 17.4H7.49805V21L11.098 17.4H19.198C20.1925 17.4 20.998 16.5936 20.998 15.6V4.8C20.998 3.8055 20.1925 3 19.198 3H4.79805Z"] {
          d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H6l-2 2V4h16v12z"); }

/* HOME TAB -> NOW PLAYING */
.nowPlayingColumn-1eCBCN {
  background-color: var(--main-color); }
  .nowPlayingColumn-1eCBCN .container-1oAagU {
    background-color: var(--main-color); }
    .nowPlayingColumn-1eCBCN .container-1oAagU .scroller-hE2gWq {
      margin-left: 0;
      border-left: none; }

.header-13Cw0- {
  font-size: 14px;
  text-transform: none; }

.emptyCard-KDifrB {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.wrapper-2RrXDg {
  margin: 0;
  background-color: transparent;
  border-radius: 0;
  border: none;
  border-left: 1px solid var(--card-border-color);
  border-right: 1px solid var(--card-border-color);
  transition: var(--default-time) var(--default-animation) background-color; }
  .wrapper-2RrXDg:hover {
    background-color: var(--card-color-hover) !important; }
    .wrapper-2RrXDg:hover .body-16rSsp {
      background-color: var(--card-color-alt-hover); }
  .wrapper-2RrXDg:not(:only-of-type) {
    position: relative;
    border-bottom: none; }
    .wrapper-2RrXDg:not(:only-of-type):after {
      position: absolute;
      content: " ";
      width: calc(100% - 60px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .wrapper-2RrXDg:not(:only-of-type):last-of-type:after {
      display: none; }
    .wrapper-2RrXDg:not(:only-of-type):first-of-type {
      border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
      border-top: 1px solid var(--card-border-color); }
    .wrapper-2RrXDg:not(:only-of-type):nth-last-child(2) {
      border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
      border-bottom: 1px solid var(--card-border-color); }
      .wrapper-2RrXDg:not(:only-of-type):nth-last-child(2):after {
        display: none; }
  .wrapper-2RrXDg .body-16rSsp {
    margin-left: 44px;
    background-color: var(--card-color-alt);
    border-radius: var(--card-radius-big);
    transition: var(--default-time) var(--default-animation) background-color; }
  .wrapper-2RrXDg .section-3G9aLW {
    background-color: transparent;
    border-radius: var(--card-radius-big); }
  .wrapper-2RrXDg .separator-2OaeRP {
    background-color: var(--card-border-color); }
  .wrapper-2RrXDg .applicationStreamingPreviewWrapper-7j27t8,
  .wrapper-2RrXDg .applicationStreamingPreviewSize-17Trrk img {
    border-radius: var(--card-radius-big); }

.header-13Cw0- + .wrapper-2RrXDg:nth-last-child(2) {
  border-radius: var(--card-radius-big); }

.popout-3Zw0qN {
  padding: 8px 0;
  background-color: var(--popout-color) !important;
  border-radius: var(--card-radius);
  box-shadow: var(--shadow-3dp) !important; }
  .popout-3Zw0qN .wrapper-3Rixsz {
    margin: 0;
    padding: 9px 12px;
    border-radius: 0;
    transition: var(--default-time) var(--default-animation) background-color; }
    .popout-3Zw0qN .wrapper-3Rixsz:hover {
      background-color: var(--menu-item-hover); }
    .popout-3Zw0qN .wrapper-3Rixsz .colorStandard-21JIj7 {
      font-weight: 500;
      color: var(--menu-item-text-color); }
  .popout-3Zw0qN .memberListContainer-13tNU9 {
    margin-top: 0; }
    .popout-3Zw0qN .memberListContainer-13tNU9 .memberListItem-31QoHj {
      margin: 0;
      padding: 6px 12px;
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .popout-3Zw0qN .memberListContainer-13tNU9 .memberListItem-31QoHj:hover {
        background-color: var(--menu-item-hover); }
      .popout-3Zw0qN .memberListContainer-13tNU9 .memberListItem-31QoHj .colorStandard-21JIj7 {
        color: var(--menu-item-text-color); }
      .popout-3Zw0qN .memberListContainer-13tNU9 .memberListItem-31QoHj .nameTag-H6kSJ0 .discriminator-19kRMP,
      .popout-3Zw0qN .memberListContainer-13tNU9 .memberListItem-31QoHj .nameTag-H6kSJ0 .username-3JLfHz {
        font-weight: 500; }
    .popout-3Zw0qN .memberListContainer-13tNU9 .memberListHeader-543n-J {
      margin: 8px 0;
      padding: 0 12px;
      color: var(--menu-item-text-color);
      text-transform: none; }
  .popout-3Zw0qN .separator-2OaeRP {
    margin: 8px 0;
    background-color: var(--separator-color); }

.memberItem-2FOuJI {
  padding: 0; }

/* HOME TAB -> FIND OR START A CONVERSATION */
.quickswitcher-pKcM9U {
  padding: 0;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .quickswitcher-pKcM9U .input-3r5zZY {
    height: 48px;
    line-height: 48px;
    margin: 16px;
    padding: 0 16px;
    background-color: var(--input-color);
    border-radius: 24px;
    box-shadow: none; }
  .quickswitcher-pKcM9U .scroller-2qwVWY {
    margin-top: 0;
    margin-right: 0;
    background-color: transparent;
    border-top: 1px solid var(--card-border-color); }
  .quickswitcher-pKcM9U .result-u66Ywh {
    border-radius: 0;
    transition: var(--default-time) var(--default-animation) background-color; }
    .quickswitcher-pKcM9U .result-u66Ywh.resultFocused-3aIoYe {
      background-color: var(--menu-item-hover); }
  .quickswitcher-pKcM9U .protip-1jXzAl {
    padding: 8px;
    border-top-color: var(--card-border-color); }

/* HOME TAB -> LIBRARY */
.scroller-2XLwLg,
.scroller-1TOeMq {
  background-color: var(--chat-color); }

.container-3u6dG- {
  padding-bottom: 8px; }
  .container-3u6dG- .header-2EadGG {
    height: 42px;
    padding: 0 16px;
    line-height: 42px;
    background-color: var(--chat-color);
    border-bottom: 1px solid var(--card-border-color); }
    .container-3u6dG- .header-2EadGG.stickyHeader-fX4ei6 {
      width: 100%; }
    .container-3u6dG- .header-2EadGG .headerCell-3WoADH {
      border: none;
      font-size: 14px;
      text-transform: none; }
      .container-3u6dG- .header-2EadGG .headerCell-3WoADH.headerCellSorted-2sXjX3 .headerCellContent-iBms3e {
        position: relative;
        background-color: transparent !important; }
        .container-3u6dG- .header-2EadGG .headerCell-3WoADH.headerCellSorted-2sXjX3 .headerCellContent-iBms3e:after {
          position: absolute;
          content: " ";
          width: 100%;
          height: 3px;
          left: 0;
          right: 0;
          bottom: 0;
          margin: 0 auto;
          background: var(--tab-border-color);
          border-radius: 3px 3px 0 0;
          transition: var(--default-time) ease all; }
        .container-3u6dG- .header-2EadGG .headerCell-3WoADH.headerCellSorted-2sXjX3 .headerCellContent-iBms3e:after {
          width: calc(100% - 22px);
          left: 0;
          right: auto; }
  .container-3u6dG- .rowWrapper-N-4fji {
    margin: 0;
    position: relative;
    border-bottom: none;
    border-radius: 0;
    transition: var(--default-time) var(--default-animation) background-color; }
    .container-3u6dG- .rowWrapper-N-4fji:after {
      position: absolute;
      content: " ";
      width: calc(100% - 66px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .container-3u6dG- .rowWrapper-N-4fji:last-of-type:after {
      display: none; }
    .container-3u6dG- .rowWrapper-N-4fji.rowWrapperActive-nOO7R3 {
      margin: 0;
      padding: 0;
      background-color: var(--menu-item-hover); }
    .container-3u6dG- .rowWrapper-N-4fji .row-1_1Nya {
      margin: 0;
      padding: 0 16px;
      border-top: none !important; }
    .container-3u6dG- .rowWrapper-N-4fji .nameBodyCell-2RYQL9,
    .container-3u6dG- .rowWrapper-N-4fji .settingIcon-1PlYq2,
    .container-3u6dG- .rowWrapper-N-4fji .textCell-sKsLUQ {
      transition: var(--default-time) var(--default-animation) opacity; }
    .container-3u6dG- .rowWrapper-N-4fji .nameBodyCell-2RYQL9 {
      padding-left: 0; }

.body-3KonCR {
  min-width: 350px;
  max-width: 1200px;
  padding: 60px 40px 80px; }

.wrapper-QQNZRu .foreground-2JnqVD {
  stroke: var(--slider-color) !important; }
.wrapper-QQNZRu .foreground-2JnqVD {
  stroke: hsl(var(--accent-hsl)) !important; }

/* HOME TAB -> NITRO */
.applicationStore-2nk7Lo {
  background-color: var(--chat-color); }
  .applicationStore-2nk7Lo .scroller-29cQFV {
    background-color: transparent; }

.premiumContainer-3GGa8Q {
  min-width: 350px;
  max-width: 1200px; }

.banner-3Kac2g,
.hero-1aNo0v {
  max-width: 100%;
  background-size: cover;
  border-radius: var(--card-radius-big); }
  .banner-3Kac2g.stickersHero-rhTlUd,
  .hero-1aNo0v.stickersHero-rhTlUd {
    background-position: center;
    background-size: cover; }

.hero-1aNo0v .button-f2h6uQ.lookInverted-2mDUMi,
.wrapper-3nSjSv .button-f2h6uQ.lookInverted-2mDUMi {
  background-color: rgba(255, 255, 255, 0.1) !important;
  box-shadow: none !important;
  color: #fff !important; }

.detailsBlock-FoDTGA {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.feature-2IUcBI {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  background-color: transparent !important; }

.featureStickers-Pc_FBx .stickerImageSection-7EUs8E {
  background-color: var(--card-color-alt);
  border-radius: var(--card-radius-big); }

/* HOME TAB -> ADD FRIEND */
.sectionHeader-20RGqu {
  border-color: var(--card-border-color) !important; }

.addFriendInputWrapper-kkoSV9 {
  height: calc(var(--input-height) * 1.316);
  margin: 12px 0 0 0;
  padding: 0 8px 0 16px;
  background-color: var(--input-color);
  border-radius: calc(var(--input-radius) * 1.316);
  border: none; }
  .addFriendInputWrapper-kkoSV9 .addFriendInput-1Ta-rO,
  .addFriendInputWrapper-kkoSV9 .addFriendHint-1EVQJY {
    padding: 0;
    line-height: var(--input-height);
    font-weight: 400; }
    .addFriendInputWrapper-kkoSV9 .addFriendInput-1Ta-rO::-webkit-input-placeholder,
    .addFriendInputWrapper-kkoSV9 .addFriendHint-1EVQJY::-webkit-input-placeholder {
      color: var(--text-muted);
      font-weight: 500; }

/*
 *
 *	SERVER DISCOVERY
 *
 */
.pageWrapper-2PwDoS {
  background-color: var(--chat-color) !important; }

.headerImage-2D5D-v {
  border-radius: var(--card-radius-big);
  box-shadow: var(--shadow-1dp); }

.search-25t1e9 .searchBox-31Zv9h {
  border-radius: 18px;
  border: none;
  box-shadow: none;
  transition: var(--default-time) var(--default-animation) box-shadow; }
  .search-25t1e9 .searchBox-31Zv9h:focus-within {
    box-shadow: var(--shadow-3dp); }
  .search-25t1e9 .searchBox-31Zv9h .searchBoxInputWrapper-3XLwVB {
    border-bottom: none !important; }
    .search-25t1e9 .searchBox-31Zv9h .searchBoxInputWrapper-3XLwVB:before, .search-25t1e9 .searchBox-31Zv9h .searchBoxInputWrapper-3XLwVB:after {
      display: none; }
  .search-25t1e9 .searchBox-31Zv9h .searchBoxInput-P0mWHW {
    padding: 8px 16px; }

/* SERVER DISCOVERY -> SIDEBAR */
.sidebar-1tnWFu .categoryItem-3zFJns {
  margin: 0 8px 0 0;
  border-radius: 0 21px 21px 0; }
  .sidebar-1tnWFu .categoryItem-3zFJns .wrappedLayout-31F4iI {
    border-radius: 0 21px 21px 0; }
  .sidebar-1tnWFu .categoryItem-3zFJns:hover .layout-1qmrhw {
    background-color: var(--menu-item-hover); }
  .sidebar-1tnWFu .categoryItem-3zFJns.selectedCategoryItem-3X8ujp {
    color: var(--menu-item-text-color); }
    .sidebar-1tnWFu .categoryItem-3zFJns.selectedCategoryItem-3X8ujp .itemInner-3gVXMG {
      background-color: var(--menu-item-select); }

/* SERVER DISCOVERY -> CARDS */
.card-2TuZPZ {
  background-color: var(--card-color-alt) !important;
  border-radius: var(--card-radius-big);
  box-shadow: none !important;
  transition: var(--default-time) var(--default-animation) transform, var(--default-time) var(--default-animation) box-shadow; }
  .card-2TuZPZ:hover {
    box-shadow: var(--shadow-3dp) !important; }
    .card-2TuZPZ:hover .guildInfo-PdhToW {
      border-color: transparent; }
  .card-2TuZPZ .cardHeader-1kPMOm {
    margin-bottom: 0; }
  .card-2TuZPZ .guildInfo-PdhToW {
    padding-top: 32px;
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border: 1px solid var(--card-border-color);
    border-top: none;
    transition: var(--default-time) var(--default-animation) border-color; }
  .card-2TuZPZ .guildIcon-1nnIAv foreignObject {
    mask: none !important; }
  .card-2TuZPZ .guildIcon-1nnIAv .iconMask-2fMR98 {
    background-color: var(--card-color-alt) !important;
    border-radius: 50%; }
    .card-2TuZPZ .guildIcon-1nnIAv .iconMask-2fMR98 .avatar-30VHqO {
      border-radius: 50%; }

/*
 *
 *	SERVER BOOST PAGE
 *
 */
.perksModal-fSYqOq {
  background-color: var(--main-color) !important;
  background-image: none !important; }

.ctaBar-2UsjF2 {
  background-image: none !important;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.wrapper-WLdlSO {
  background-color: var(--chat-color); }
  .wrapper-WLdlSO .navigationBar-2Z_P4D {
    background-color: var(--main-color);
    box-shadow: var(--elevation-low); }

.heroContent-1Wj0uW .button-f2h6uQ {
  --accent-button-action: #000;
  background-color: #fff !important; }

.progressBarTrack-xPgjRk {
  height: 4px;
  background-color: hsl(var(--switch-slider-color)); }
  .progressBarTrack-xPgjRk.progressBarFill-3z0vRF {
    background-image: none;
    background-color: hsl(var(--accent-hsl)); }

.progressBarMarkerUnlocked-3YdWPU:before {
  background-image: none;
  background-color: hsl(var(--accent-hsl)); }
.progressBarMarkerUnlocked-3YdWPU .progressBarMarkerNumSubscriptionsRequired-1DMOqy {
  color: var(--accent-text-color); }

.planCard-vET3Ia {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  transition: var(--default-time) var(--default-animation); }
  .planCard-vET3Ia:hover {
    background-color: var(--background-modifier-hover);
    border-color: transparent;
    box-shadow: var(--shadow-3dp);
    transform: translateY(-4px); }

.perksTable-H9sPBm {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .perksTable-H9sPBm .perksTableRowHeading-jY6XJu {
    padding: 16px !important;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
  .perksTable-H9sPBm .perksTableRow-31boQO {
    padding: 0 16px;
    border-top: none !important;
    border-bottom: 1px solid var(--card-border-color);
    transition: var(--default-time) var(--default-animation) background-color; }
    .perksTable-H9sPBm .perksTableRow-31boQO:last-of-type {
      border-bottom: none; }
    .perksTable-H9sPBm .perksTableRow-31boQO:hover {
      background-color: var(--menu-item-hover); }
  .perksTable-H9sPBm .perksTableRowLabelCopy-1tRwM4 {
    font-size: 16px; }

.perkPopout-18_jX- {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .perkPopout-18_jX- .perkPopoutDescription-Expmm3 {
    border-top: 1px solid var(--popout-header-border); }

/* SERVER BOOST PAGE -> LEVELS */
.tierMarkerBackground-G8FoN4 {
  background-color: var(--main-color) !important; }

.tierWrapper-W9ajqp {
  border-radius: 0;
  box-shadow: none !important; }

.carouselItem-g4c5Xp {
  background-color: var(--card-color-alt);
  border-radius: var(--card-radius-big);
  transition: var(--default-time) var(--default-animation) box-shadow; }
  .carouselItem-g4c5Xp.carouselItemSelected-JFUsnG {
    box-shadow: var(--shadow-3dp); }
    .carouselItem-g4c5Xp.carouselItemSelected-JFUsnG .tier-12tKuZ .tierHeader---JJFb.tierHeaderLocked-1s2JJz {
      border-color: transparent;
      border-bottom-color: var(--card-border-color); }
    .carouselItem-g4c5Xp.carouselItemSelected-JFUsnG .tier-12tKuZ .tierBody-16Chc9 {
      border-color: transparent; }
  .carouselItem-g4c5Xp .tier-12tKuZ {
    border-radius: var(--card-radius-big); }
    .carouselItem-g4c5Xp .tier-12tKuZ .tierHeader---JJFb,
    .carouselItem-g4c5Xp .tier-12tKuZ .tierBody-16Chc9 {
      transition: var(--default-time) var(--default-animation) border-color; }
    .carouselItem-g4c5Xp .tier-12tKuZ .tierHeader---JJFb {
      border-radius: var(--card-radius-big) var(--card-radius-big) 0 0; }
      .carouselItem-g4c5Xp .tier-12tKuZ .tierHeader---JJFb.tierHeaderLocked-1s2JJz {
        background-color: transparent !important;
        border: 1px solid var(--card-border-color); }
      .carouselItem-g4c5Xp .tier-12tKuZ .tierHeader---JJFb .tierLock-3CSxSX path {
        d: path("M18 8h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2zM9 6c0-1.66 1.34-3 3-3s3 1.34 3 3v2H9V6zm9 14H6V10h12v10zm-6-3c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2z") !important; }
      .carouselItem-g4c5Xp .tier-12tKuZ .tierHeader---JJFb .tierUnlocked-25K6Kv {
        font-size: 14px;
        text-transform: none; }
    .carouselItem-g4c5Xp .tier-12tKuZ .tierBody-16Chc9 {
      background-color: transparent;
      border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
      border: 1px solid var(--card-border-color);
      border-top: none; }

.perk-2WeBWW {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

/* SERVER BOOST -> SERVER MODAL */
.perks-2IIbWQ {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .perks-2IIbWQ .perkRow-10K6XE {
    margin: 0;
    padding: 16px;
    position: relative;
    border-bottom: none; }
    .perks-2IIbWQ .perkRow-10K6XE:after {
      position: absolute;
      content: " ";
      width: calc(100% - 56px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .perks-2IIbWQ .perkRow-10K6XE:last-of-type:after {
      display: none; }

/*
 *
 *	DIRECT MESSAGES
 *
 */
.wrapper-1gVUIN {
  box-shadow: var(--shadow-3dp); }
  .wrapper-1gVUIN.minimum-fXpVNc {
    background-color: var(--chat-color); }

.content-1jQy2l:before {
  display: none; }

.border-2BJQjd {
  transition: var(--default-time) var(--default-animation) box-shadow; }
  .border-2BJQjd.speaking-3RWJBr {
    box-shadow: inset 0 0 0 3px hsl(var(--accent-hsl)), inset 0 0 0 4px var(--background-floating); }

/* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE */
.root-22AK9z {
  /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS */ }
  .root-22AK9z .videoControls-353CsJ .contextMenuNub-NuTZ_U.colorable-3rVGna.white-11auuQ {
    background-color: #2f3136;
    color: #fff; }
  .root-22AK9z .videoControls-353CsJ .container-a_NK-C .button-f2h6uQ {
    border-radius: 28px !important; }
    .root-22AK9z .videoControls-353CsJ .container-a_NK-C .button-f2h6uQ:hover {
      background-color: rgba(var(--button-link-color), 0.1) !important; }
  .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.primaryDark-2UJt1G {
    background-color: var(--menu-item-hover); }
    .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.primaryDark-2UJt1G:hover {
      background-color: var(--menu-item-select); }
  .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.white-11auuQ {
    background-color: #fff; }
    .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.white-11auuQ:hover {
      background-color: #ddd; }
  .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.red-3T8maV {
    background-color: var(--alert-color); }
    .root-22AK9z .videoControls-353CsJ .colorable-3rVGna.red-3T8maV:hover {
      background-color: var(--alert-color); }
  .root-22AK9z .videoControls-353CsJ .button-f2h6uQ {
    border-radius: 50% !important; }
    .root-22AK9z .videoControls-353CsJ .button-f2h6uQ:not(.centerButton-1IShs7) {
      background-color: transparent !important;
      position: relative; }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ:not(.centerButton-1IShs7):after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ:not(.centerButton-1IShs7):hover:after {
        opacity: 1;
        transform: scale(1.5);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ:not(.centerButton-1IShs7):active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
    .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path {
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> TURN ON CAMERA */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> JOIN CALL */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> STOP SCREEN SHARE */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> SCREEN SHARE */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> MUTE */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> UNMUTE */
      /* DIRECT MESSAGES -> VIDEO CALL/SCREEN SHARE -> CONTROLS -> END CALL */ }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
        d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M11 5V3C16.515 3 21 7.486 21 13H19C19 8.589 15.411 5 11 5ZM17 13H15C15 10.795 13.206 9 11 9V7C14.309 7 17 9.691 17 13ZM11 11V13H13C13 11.896 12.105 11 11 11ZM14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16Z"] {
        d: path("M20 15.45c-1.25 0-2.45-.2-3.57-.57-.1-.03-.21-.05-.31-.05-.26 0-.51.1-.71.29l-2.2 2.2c-2.83-1.44-5.15-3.75-6.59-6.59l2.2-2.21c.28-.26.36-.65.25-1C8.7 6.4 8.5 5.2 8.5 3.95c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1 0 9.39 7.61 17 17 17 .55 0 1-.45 1-1v-3.5c0-.55-.45-1-1-1zM5.03 4.95h1.5c.07.88.22 1.75.45 2.58l-1.2 1.21c-.4-1.21-.66-2.47-.75-3.79zM19 18.92c-1.32-.09-2.6-.35-3.8-.76l1.2-1.2c.85.24 1.72.39 2.6.45v1.51zM18 5.95v-3h-2v3h-3v2h3v3h2v-3h3v-2z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M4 2.5C2.897 2.5 2 3.397 2 4.5V15.5C2 16.604 2.897 17.5 4 17.5H11V19.5H7V21.5H17V19.5H13V17.5H20C21.103 17.5 22 16.604 22 15.5V4.5C22 3.397 21.103 2.5 20 2.5H4ZM14.5483 6L16 7.45174L13.4466 9.99485L16 12.5483L14.5483 14L12.0051 11.4466L9.45174 14L8 12.5483L10.5534 9.99485L8 7.45174L9.45174 6L12.0051 8.55341L14.5483 6Z"] {
        d: path("M21.79 18l2 2H24v-2h-2.21zM1.11 2.98l1.55 1.56c-.41.37-.66.89-.66 1.48V16c0 1.1.9 2 2.01 2H0v2h18.13l2.71 2.71 1.41-1.41L2.52 1.57 1.11 2.98zM4 6.02h.13l4.95 4.93C7.94 12.07 7.31 13.52 7 15c.96-1.29 2.13-2.08 3.67-2.46l3.46 3.48H4v-10zm16 0v10.19l1.3 1.3c.42-.37.7-.89.7-1.49v-10c0-1.11-.9-2-2-2H7.8l2 2H20zm-7.07 3.13l2.79 2.78 1.28-1.2L13 7v2.13l-.07.02z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M2 4.5C2 3.397 2.897 2.5 4 2.5H20C21.103 2.5 22 3.397 22 4.5V15.5C22 16.604 21.103 17.5 20 17.5H13V19.5H17V21.5H7V19.5H11V17.5H4C2.897 17.5 2 16.604 2 15.5V4.5ZM13.2 14.3375V11.6C9.864 11.6 7.668 12.6625 6 15C6.672 11.6625 8.532 8.3375 13.2 7.6625V5L18 9.6625L13.2 14.3375Z"] {
        d: path("M20 18c1.1 0 1.99-.9 1.99-2L22 6c0-1.11-.9-2-2-2H4c-1.11 0-2 .89-2 2v10c0 1.1.89 2 2 2H0v2h24v-2h-4zM4 16V6h16v10.01L4 16zm9-6.87c-3.89.54-5.44 3.2-6 5.87 1.39-1.87 3.22-2.72 6-2.72v2.19l4-3.74L13 7v2.13z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"] {
        d: path("M12 14c1.66 0 3-1.34 3-3V5c0-1.66-1.34-3-3-3S9 3.34 9 5v6c0 1.66 1.34 3 3 3zm-1-9c0-.55.45-1 1-1s1 .45 1 1v6c0 .55-.45 1-1 1s-1-.45-1-1V5zm6 6c0 2.76-2.24 5-5 5s-5-2.24-5-5H5c0 3.53 2.61 6.43 6 6.92V21h2v-3.08c3.39-.49 6-3.39 6-6.92h-2z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"] ~ path {
        display: none; }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] {
        d: path("M10.8 4.9c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2l-.01 3.91L15 10.6V5c0-1.66-1.34-3-3-3-1.54 0-2.79 1.16-2.96 2.65l1.76 1.76V4.9zM19 11h-1.7c0 .58-.1 1.13-.27 1.64l1.27 1.27c.44-.88.7-1.87.7-2.91zM4.41 2.86L3 4.27l6 6V11c0 1.66 1.34 3 3 3 .23 0 .44-.03.65-.08l1.66 1.66c-.71.33-1.5.52-2.31.52-2.76 0-5.3-2.1-5.3-5.1H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c.91-.13 1.77-.45 2.55-.9l4.2 4.2 1.41-1.41L4.41 2.86"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] ~ path {
        display: none; }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M21.1169 1.11603L22.8839 2.88403L19.7679 6.00003L22.8839 9.11603L21.1169 10.884L17.9999 7.76803L14.8839 10.884L13.1169 9.11603L16.2329 6.00003L13.1169 2.88403L14.8839 1.11603L17.9999 4.23203L21.1169 1.11603ZM18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22Z"] {
        d: path("M18.59 10.52c1.05.51 2.04 1.15 2.96 1.91l-1.07 1.07c-.58-.47-1.21-.89-1.88-1.27v-1.71m-13.2 0v1.7c-.65.37-1.28.79-1.87 1.27l-1.07-1.07c.91-.75 1.9-1.38 2.94-1.9M12 7C7.46 7 3.34 8.78.29 11.67c-.18.18-.29.43-.29.71s.11.53.29.7l2.48 2.48c.18.18.43.29.71.29.27 0 .52-.1.7-.28.79-.73 1.68-1.36 2.66-1.85.33-.16.56-.51.56-.9v-3.1C8.85 9.25 10.4 9 12 9s3.15.25 4.59.73v3.1c0 .4.23.74.56.9.98.49 1.88 1.11 2.67 1.85.18.17.43.28.7.28.28 0 .53-.11.71-.29l2.48-2.48c.18-.18.29-.43.29-.71s-.11-.53-.29-.71C20.66 8.78 16.54 7 12 7z"); }
      .root-22AK9z .videoControls-353CsJ .button-f2h6uQ path[d="M20 11V13.5H4V4.5H13V2.5H4C3.46957 2.5 2.96086 2.71071 2.58579 3.08579C2.21071 3.46086 2 3.96957 2 4.5L2 15.5C2 16.0304 2.21071 16.5391 2.58579 16.9142C2.96086 17.2893 3.46957 17.5 4 17.5H11V19.5H7V21.5H17V19.5H13V17.5H20C20.5304 17.5 21.0391 17.2893 21.4142 16.9142C21.7893 16.5391 22 16.0304 22 15.5V11H20Z"] ~ path {
        display: none; }
  .root-22AK9z .bottomControls-31YuPK .leftTrayIcon-3kMl25:after {
    display: none; }

.quickSelect-384d3G {
  margin-top: 12px; }

.regionSelectPopout-3sEzVB {
  padding: 8px 0;
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--shadow-3dp); }
  .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS {
    position: relative;
    padding: 9px 12px;
    transition: var(--default-time) ease background-color; }
    .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS:hover {
      background-color: var(--menu-item-hover) !important; }
    .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS.selected {
      background-color: var(--menu-item-select) !important; }
    .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS .regionSelectFlag-2YbDyH {
      position: absolute;
      left: 12px; }
    .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS .regionSelectName-1Tj9C9 {
      margin-left: 0;
      margin-right: 24px;
      font-size: 14px;
      text-align: left;
      color: var(--menu-item-text-color) !important; }
    .regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS .check-K_srvn {
      position: absolute;
      right: 12px; }

.scroller-3b1p7z {
  padding: 8px 0;
  padding-right: 0 !important;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius); }
  .scroller-3b1p7z .memberListHeader-1V_jWz {
    margin: 8px 0;
    padding: 0 12px;
    color: var(--menu-item-text-color);
    text-transform: none; }
  .scroller-3b1p7z .memberListItem-3V-x8Q {
    margin: 0;
    padding: 6px 12px;
    border-radius: 0;
    transition: var(--default-time) var(--default-animation) background-color; }
    .scroller-3b1p7z .memberListItem-3V-x8Q:not(.popoutDisabled-PP2QdB):hover {
      background-color: var(--menu-item-hover) !important; }
    .scroller-3b1p7z .memberListItem-3V-x8Q .colorStandard-21JIj7 {
      color: var(--menu-item-text-color); }
  .scroller-3b1p7z::-webkit-scrollbar {
    width: 0 !important; }

.tile-2TcwiO {
  border-radius: var(--card-radius-big); }

.participantsButton-1WBdFP {
  background-color: #2f3136 !important;
  border-radius: 16px !important; }
  .participantsButton-1WBdFP:hover {
    background-color: #202225 !important; }

.overlayTitle-2efoIF {
  border-radius: 16px; }

/*
 *
 *	CHANNELS LIST
 *
 */
.sidebar-1tnWFu {
  border-radius: 0 !important; }
  .sidebar-1tnWFu,
  .sidebar-1tnWFu .container-1NXEtd {
    background-color: var(--main-color); }
  .sidebar-1tnWFu .container-1NXEtd .content-2a4AW9 {
    margin-bottom: 11px; }
  .sidebar-1tnWFu .container-q97qHp {
    font-size: 14px;
    text-transform: none; }
  .sidebar-1tnWFu .container-1-ERn5:not(.hasBanner-2IrYih) .header-3OsQeK, .sidebar-1tnWFu .container-1-ERn5:not(.hasBanner-2IrYih) .header-3OsQeK:hover {
    background-color: var(--main-color); }

/* CHANNELS LIST -> CREATE CHANNEL */
.searchBox-2ktdj3 {
  padding: 0 0 12px; }
  .searchBox-2ktdj3 .searchBar-3OIGe3 {
    position: relative;
    height: auto;
    max-height: unset;
    padding: 0;
    background-color: transparent;
    border-radius: 0;
    border: none;
    border-bottom: 1px solid var(--input-border-color) !important; }
    .searchBox-2ktdj3 .searchBar-3OIGe3:before, .searchBox-2ktdj3 .searchBar-3OIGe3:after {
      position: absolute;
      content: " ";
      height: 2px;
      width: 0;
      bottom: -1px;
      background: hsla(var(--accent-hsl));
      transition: 300ms ease all;
      z-index: 2; }
    .searchBox-2ktdj3 .searchBar-3OIGe3:before {
      left: 50%; }
    .searchBox-2ktdj3 .searchBar-3OIGe3:after {
      right: 50%; }
    .searchBox-2ktdj3 .searchBar-3OIGe3:focus-within:before, .searchBox-2ktdj3 .searchBar-3OIGe3:focus-within:after {
      width: 50%; }
    .searchBox-2ktdj3 .searchBar-3OIGe3 .input-2FSSDe {
      padding: 0; }

.richTag-20_n21 {
  background-color: var(--menu-item-hover);
  border-radius: 13px; }
  .richTag-20_n21:hover {
    background-color: var(--menu-item-select); }
  .richTag-20_n21.tag-15zcD_:first-of-type {
    margin-left: 0; }
  .richTag-20_n21.tag-15zcD_:last-of-type {
    margin-right: 0; }

.inputPrefix-1HHwWv {
  top: 10px;
  left: 0; }
  .inputPrefix-1HHwWv + .input-2g-os5 {
    padding-left: 20px; }

/* CHANNELS LIST -> CHANNEL */
.containerDefault-YUSmu3.selected-2TbFuo {
  background-color: var(--menu-item-select-accent);
  border-radius: 0 24px 24px 0; }
.containerDefault-YUSmu3 .modeSelected-3DmyhH .content-1gYQeQ, .containerDefault-YUSmu3 .modeSelected-3DmyhH:hover .content-1gYQeQ {
  background-color: transparent; }
.containerDefault-YUSmu3 .content-1gYQeQ {
  margin-left: 0;
  border-radius: 0 24px 24px 0; }
.containerDefault-YUSmu3 .typeThread-2Aqh6X .mainContent-20q_Hp {
  margin-left: 34px; }

.wrapper-NhbLHG .content-1gYQeQ {
  margin-left: 0;
  border-radius: 0 24px 24px 0; }

.containerDefault-3TQ5YN .addButton-2mlqCW {
  background-color: transparent !important;
  position: relative; }
  .containerDefault-3TQ5YN .addButton-2mlqCW:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--md-ripple-color), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .containerDefault-3TQ5YN .addButton-2mlqCW:hover:after {
    opacity: 1;
    transform: scale(1.5);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .containerDefault-3TQ5YN .addButton-2mlqCW:active:after {
    background-color: hsla(var(--md-ripple-color), 0.2); }

.containerDragAfter-3aBiOW:after,
.containerDragBefore-1s5Qg6:before {
  left: 0;
  background-color: hsl(var(--accent-hsl)); }

.containerUserOver-SDa1HW:after {
  right: 4px;
  background-color: hsla(var(--accent-hsl), 0.1);
  border-radius: var(--card-radius-big);
  border-color: hsla(var(--accent-hsl), 0.5); }

.content-1Tgc42 {
  border-radius: 15px;
  /* CHANNELS LIST -> CHANNEL -> VOICE ICONS */ }
  .content-1Tgc42 .icons-2mwuFp .icon-N9JZb6 path {
    display: none;
    /* CHANNELS LIST -> CHANNEL -> VOICE ICONS -> MUTED */
    /* CHANNELS LIST -> CHANNEL -> VOICE ICONS -> DEAFENED */
    /* CHANNELS LIST -> CHANNEL -> VOICE ICONS -> WEBCAM */ }
    .content-1Tgc42 .icons-2mwuFp .icon-N9JZb6 path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] {
      display: block;
      d: path("M10.8 4.9c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2l-.01 3.91L15 10.6V5c0-1.66-1.34-3-3-3-1.54 0-2.79 1.16-2.96 2.65l1.76 1.76V4.9zM19 11h-1.7c0 .58-.1 1.13-.27 1.64l1.27 1.27c.44-.88.7-1.87.7-2.91zM4.41 2.86L3 4.27l6 6V11c0 1.66 1.34 3 3 3 .23 0 .44-.03.65-.08l1.66 1.66c-.71.33-1.5.52-2.31.52-2.76 0-5.3-2.1-5.3-5.1H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c.91-.13 1.77-.45 2.55-.9l4.2 4.2 1.41-1.41L4.41 2.86z") !important; }
    .content-1Tgc42 .icons-2mwuFp .icon-N9JZb6 path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] {
      display: block;
      d: path("M4.34 2.93L2.93 4.34 7.29 8.7 7 9H3v6h4l5 5v-6.59l4.18 4.18c-.65.49-1.38.88-2.18 1.11v2.06c1.34-.3 2.57-.92 3.61-1.75l2.05 2.05 1.41-1.41L4.34 2.93zM10 15.17L7.83 13H5v-2h2.83l.88-.88L10 11.41v3.76zM19 12c0 .82-.15 1.61-.41 2.34l1.53 1.53c.56-1.17.88-2.48.88-3.87 0-4.28-2.99-7.86-7-8.77v2.06c2.89.86 5 3.54 5 6.71zm-7-8l-1.88 1.88L12 7.76zm4.5 8c0-1.77-1.02-3.29-2.5-4.03v1.79l2.48 2.48c.01-.08.02-.16.02-.24z") !important; }
    .content-1Tgc42 .icons-2mwuFp .icon-N9JZb6 path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
      display: block;
      d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z") !important; }

.streamPreview-3qoMP4 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .streamPreview-3qoMP4 .watchButton-2v6cPT {
    background-color: rgba(var(--button-link-color), 0.075) !important;
    box-shadow: none !important;
    color: var(--button-link-text-color) !important;
    transition: var(--default-time) var(--default-animation) background-color !important; }
    .streamPreview-3qoMP4 .watchButton-2v6cPT:hover {
      background-color: rgba(var(--button-link-color), 0.125) !important; }

/* CHANNELS LIST -> CHANNEL -> ICONS */
.iconItem-1EjiK0 {
  position: relative;
  margin: 0 0 0 10px;
  padding: 2px;
  position: relative; }
  .iconItem-1EjiK0:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--md-ripple-color), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .iconItem-1EjiK0:hover:after {
    opacity: 1;
    transform: scale(1.4);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .iconItem-1EjiK0:active:after {
    background-color: hsla(var(--md-ripple-color), 0.2); }
  .iconItem-1EjiK0[role] .actionIcon-2sw4Sl:active {
    transform: translateY(0); }
  .iconItem-1EjiK0[role] .actionIcon-2sw4Sl path {
    transform: scale(0.72); }
  .iconItem-1EjiK0 .actionIcon-2sw4Sl path {
    /* CHANNELS LIST -> CHANNEL -> ICONS -> CREATE/INVITE */
    /* CHANNELS LIST -> CHANNEL -> ICONS -> EDIT CHANNEL */ }
    .iconItem-1EjiK0 .actionIcon-2sw4Sl path[d="M14 2H16V3H14V5H13V3H11V2H13V0H14V2Z"] {
      d: path("M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0-6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4zm-6 4c.22-.72 3.31-2 6-2 2.7 0 5.8 1.29 6 2H9zm-3-3v-3h3v-2H6V7H4v3H1v2h3v3z") !important; }
      .iconItem-1EjiK0 .actionIcon-2sw4Sl path[d="M14 2H16V3H14V5H13V3H11V2H13V0H14V2Z"] ~ path {
        display: none; }
    .iconItem-1EjiK0 .actionIcon-2sw4Sl path[d="M14 7V9C14 9 12.5867 9 12.5733 9.00667C12.42 9.58667 12.1733 10.1267 11.84 10.6067L12.74 11.5067L11.4933 12.7533L10.5933 11.8533C10.1133 12.1867 9.57334 12.44 8.99334 12.5867V14H6.99334V12.58C6.41334 12.4333 5.87334 12.18 5.39334 11.8467L4.49333 12.7467L3.24667 11.5L4.14667 10.6C3.81333 10.1267 3.56 9.58 3.41333 9H2V7H3.41333C3.56 6.42 3.81333 5.88 4.14667 5.4L3.24667 4.5L4.5 3.24667L5.4 4.14667C5.87334 3.81333 6.42 3.56 7 3.41333V2H9V3.41333C9.58 3.56667 10.12 3.81333 10.6 4.14667L11.5067 3.25333L12.7533 4.5L11.8533 5.4C12.1867 5.87334 12.44 6.42 12.5867 7H14ZM8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"] {
      d: path("M19.43 12.98c.04-.32.07-.64.07-.98 0-.34-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.09-.16-.26-.25-.44-.25-.06 0-.12.01-.17.03l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.06-.02-.12-.03-.18-.03-.17 0-.34.09-.43.25l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98 0 .33.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.09.16.26.25.44.25.06 0 .12-.01.17-.03l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.06.02.12.03.18.03.17 0 .34-.09.43-.25l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zm-1.98-1.71c.04.31.05.52.05.73 0 .21-.02.43-.05.73l-.14 1.13.89.7 1.08.84-.7 1.21-1.27-.51-1.04-.42-.9.68c-.43.32-.84.56-1.25.73l-1.06.43-.16 1.13-.2 1.35h-1.4l-.19-1.35-.16-1.13-1.06-.43c-.43-.18-.83-.41-1.23-.71l-.91-.7-1.06.43-1.27.51-.7-1.21 1.08-.84.89-.7-.14-1.13c-.03-.31-.05-.54-.05-.74s.02-.43.05-.73l.14-1.13-.89-.7-1.08-.84.7-1.21 1.27.51 1.04.42.9-.68c.43-.32.84-.56 1.25-.73l1.06-.43.16-1.13.2-1.35h1.39l.19 1.35.16 1.13 1.06.43c.43.18.83.41 1.23.71l.91.7 1.06-.43 1.27-.51.7 1.21-1.07.85-.89.7.14 1.13zM12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z") !important; }

.mainContent-20q_Hp .icon-2W8DHg path {
  /* CHANNELS LIST -> CHANNEL -> ICONS -> ACTIVE THREADS */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> VOICE CHANNEL */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> ANNOUNCEMENTS */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> RULES */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> BIG LOCK */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> SMALL LOCK */
  /* CHANNELS LIST -> CHANNEL -> ICONS -> NSFW */ }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M4.79805 3C3.80445 3 2.99805 3.8055 2.99805 4.8V15.6C2.99805 16.5936 3.80445 17.4 4.79805 17.4H7.49805V21L11.098 17.4H19.198C20.1925 17.4 20.998 16.5936 20.998 15.6V4.8C20.998 3.8055 20.1925 3 19.198 3H4.79805Z"] {
    d: path("M4 4h16v12H5.17L4 17.17V4m0-2c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2H4zm2 10h8v2H6v-2zm0-3h12v2H6V9zm0-3h12v2H6V6z"); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"], .mainContent-20q_Hp .icon-2W8DHg path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"] {
    d: path("M3 9v6h4l5 5V4L7 9H3zm7-.17v6.34L7.83 13H5v-2h2.83L10 8.83zM16.5 12c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77 0-4.28-2.99-7.86-7-8.77z"); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M3.9 8.26H2V15.2941H3.9V8.26Z"], .mainContent-20q_Hp .icon-2W8DHg path[d="M4.85 8.26429L15.84 5.84426V10.5599C15.84 11.6202 16.6996 12.4799 17.76 12.4799H21V19.0586H19.1V17.9302L12.7065 16.524L10.36 19.6233C10.1776 19.8633 9.89545 19.9998 9.6 19.9998C9.524 19.9998 9.4461 19.9904 9.3701 19.9725L5.5701 19.0313C5.1464 18.925 4.85 18.5495 4.85 18.1175V8.26429ZM9.2181 17.9942L6.75 17.3824V15.2111L10.6706 16.0751L9.2181 17.9942Z"] {
    d: path("M12,8H4A2,2 0 0,0 2,10V14A2,2 0 0,0 4,16H5V20A1,1 0 0,0 6,21H8A1,1 0 0,0 9,20V16H12L17,20V4L12,8M15,15.6L13,14H4V10H13L15,8.4V15.6M21.5,12C21.5,13.71 20.54,15.26 19,16V8C20.53,8.75 21.5,10.3 21.5,12Z"); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M3.9 8.26H2V15.2941H3.9V8.26Z"] ~ path {
    display: none; }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"] {
    d: path("M19,3H14.82C14.4,1.84 13.3,1 12,1C10.7,1 9.6,1.84 9.18,3H5A2,2 0 0,0 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5A2,2 0 0,0 19,3M12,3A1,1 0 0,1 13,4A1,1 0 0,1 12,5A1,1 0 0,1 11,4A1,1 0 0,1 12,3M7,7H17V5H19V19H5V5H7V7M7.5,13.5L9,12L11,14L15.5,9.5L17,11L11,17L7.5,13.5Z");
    transform: scale(1.6); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M17 11V7C17 4.243 14.756 2 12 2C9.242 2 7 4.243 7 7V11C5.897 11 5 11.896 5 13V20C5 21.103 5.897 22 7 22H17C18.103 22 19 21.103 19 20V13C19 11.896 18.103 11 17 11ZM12 18C11.172 18 10.5 17.328 10.5 16.5C10.5 15.672 11.172 15 12 15C12.828 15 13.5 15.672 13.5 16.5C13.5 17.328 12.828 18 12 18ZM15 11H9V7C9 5.346 10.346 4 12 4C13.654 4 15 5.346 15 7V11Z"] {
    d: path("M12,17C10.89,17 10,16.1 10,15C10,13.89 10.89,13 12,13A2,2 0 0,1 14,15A2,2 0 0,1 12,17M18,20V10H6V20H18M18,8A2,2 0 0,1 20,10V20A2,2 0 0,1 18,22H6C4.89,22 4,21.1 4,20V10C4,8.89 4.89,8 6,8H7V6A5,5 0 0,1 12,1A5,5 0 0,1 17,6V8H18M12,3A3,3 0 0,0 9,6V8H15V6A3,3 0 0,0 12,3Z"); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"], .mainContent-20q_Hp .icon-2W8DHg path[d="M22.545 4.91992V3.91992C22.545 2.79992 21.57 1.91992 20.52 1.91992C19.47 1.91992 18.52 2.79992 18.52 3.91992V4.91992H17.76C17.6275 4.91992 17.52 5.02737 17.52 5.15992V9.67992C17.52 9.81247 17.6275 9.91992 17.76 9.91992H23.28C23.4126 9.91992 23.52 9.81247 23.52 9.67992V5.15992C23.52 5.02737 23.4126 4.91992 23.28 4.91992H22.545ZM21.52 4.91992H19.52V3.91992C19.52 3.34849 19.9867 2.91992 20.52 2.91992C21.0533 2.91992 21.52 3.34849 21.52 3.91992V4.91992Z"], .mainContent-20q_Hp .icon-2W8DHg path[d="M22.025 2V3C22.5635 3 23 3.43652 23 3.975V7C23 7.55228 22.5523 8 22 8H18C17.4477 8 17 7.55228 17 7V4C17 3.44772 17.4477 3 18 3V2C18 0.88 18.95 0 20 0C21.05 0 22.025 0.88 22.025 2ZM19 3H21V2C21 1.42857 20.5333 1 20 1C19.4667 1 19 1.42857 19 2V3Z"] {
    transform: translate(-7px, -2px) scale(1.35);
    fill: var(--interactive-normal);
    opacity: 1; }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M22.545 4.91992V3.91992C22.545 2.79992 21.57 1.91992 20.52 1.91992C19.47 1.91992 18.52 2.79992 18.52 3.91992V4.91992H17.76C17.6275 4.91992 17.52 5.02737 17.52 5.15992V9.67992C17.52 9.81247 17.6275 9.91992 17.76 9.91992H23.28C23.4126 9.91992 23.52 9.81247 23.52 9.67992V5.15992C23.52 5.02737 23.4126 4.91992 23.28 4.91992H22.545ZM21.52 4.91992H19.52V3.91992C19.52 3.34849 19.9867 2.91992 20.52 2.91992C21.0533 2.91992 21.52 3.34849 21.52 3.91992V4.91992Z"] {
    transform: translate(-8px, -2px) scale(1.35); }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M3.9 8.25981H2V15.2939H3.9V8.25981Z"] {
    d: path("M22.545 4.87988V5.87988H23.28C23.4126 5.87988 23.52 5.98733 23.52 6.11988V10.6399C23.52 10.7724 23.4126 10.8799 23.28 10.8799H17.76C17.6275 10.8799 17.52 10.7724 17.52 10.6399V6.11988C17.52 5.98733 17.6275 5.87988 17.76 5.87988H18.52V4.87988C18.52 3.75988 19.47 2.87988 20.52 2.87988C21.57 2.87988 22.545 3.75988 22.545 4.87988ZM19.52 5.87988H21.52V4.87988C21.52 4.30845 21.0534 3.87988 20.52 3.87988C19.9867 3.87988 19.52 4.30845 19.52 4.87988V5.87988Z");
    transform: translate(-8px, -2px) scale(1.35);
    fill: var(--interactive-normal);
    opacity: 1; }
  .mainContent-20q_Hp .icon-2W8DHg path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"] {
    transform: translateX(-6px) scale(1.35);
    fill: var(--interactive-normal);
    opacity: 1; }

/* CHANNELS LIST -> CHANNEL -> LISTENING TO SPOTIFY */
.container-8Futzw {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .container-8Futzw .headerText-3g1XK9 {
    font-size: 14px;
    text-transform: none;
    font-weight: 500; }
  .container-8Futzw .assetsLargeImage-8U5dlz {
    border-radius: 50%; }
  .container-8Futzw .buttonSize-dIiz43 {
    height: 36px;
    min-height: 36px;
    padding: 0 !important; }
  .container-8Futzw .button-f2h6uQ {
    background-color: rgba(var(--button-link-color), 0.075) !important;
    box-shadow: none !important;
    color: var(--button-link-text-color) !important;
    transition: var(--default-time) var(--default-animation) background-color !important; }
    .container-8Futzw .button-f2h6uQ:hover {
      background-color: rgba(var(--button-link-color), 0.125) !important; }

/* CHANNELS LIST -> CHANNEL -> CREATE INVITE */
.header-1J9IaL .container-1SX9VC {
  background-color: var(--input-color);
  border-radius: 16px; }
  .header-1J9IaL .container-1SX9VC .inner-1NoIT5 {
    padding: 0; }
    .header-1J9IaL .container-1SX9VC .inner-1NoIT5 .input-2FSSDe {
      height: 32px;
      line-height: 32px;
      margin: 0;
      padding: 0 8px 0 12px; }
    .header-1J9IaL .container-1SX9VC .inner-1NoIT5 .iconLayout-SqV3nb {
      width: 32px;
      height: 32px; }

.scroller-3nFW5p {
  padding-left: 0; }

.inviteRow-3vmB7i {
  margin-right: 0;
  padding: 7px 12px;
  border-radius: 0;
  transition: var(--default-time) var(--default-animation) background-color; }
  .inviteRow-3vmB7i:hover {
    background-color: var(--menu-item-hover); }

/* CHANNELS LIST -> CHANNEL -> EDIT CHANNEL */
.inputMaxLength-3n06SD textarea.input-2g-os5 {
  height: unset;
  min-height: 32px;
  max-height: 96px; }
.inputMaxLength-3n06SD .maxLength-IdVNmX {
  right: 0; }

/* CHANNELS LIST -> CHANNEL -> EDIT CHANNEL -> PERMISSIONS */
.settingCard-xZSDjS {
  margin-bottom: 32px;
  border-radius: var(--card-radius-big);
  border: 1px solid var(--card-border-color); }
  .settingCard-xZSDjS, .settingCard-xZSDjS.active-3EK-ed,
  .settingCard-xZSDjS .cardFolder-3H4uH4 {
    background-color: transparent; }
  .settingCard-xZSDjS .cardContent-1-5hym {
    border-bottom: 1px solid var(--card-border-color); }
  .settingCard-xZSDjS .folderHeader-2FpErk {
    position: relative;
    border-bottom: none; }
    .settingCard-xZSDjS .folderHeader-2FpErk:after {
      position: absolute;
      content: " ";
      width: 100%;
      height: 1px;
      bottom: 0;
      left: 0;
      background-color: var(--card-border-color); }
  .settingCard-xZSDjS .roleMemberList-ub4EsQ {
    padding: 16px; }
    .settingCard-xZSDjS .roleMemberList-ub4EsQ .content-28mbXd {
      height: auto !important; }
      .settingCard-xZSDjS .roleMemberList-ub4EsQ .content-28mbXd .memberRow-1p7Jls {
        padding: 0 4px;
        margin-bottom: 16px; }
        .settingCard-xZSDjS .roleMemberList-ub4EsQ .content-28mbXd .memberRow-1p7Jls:last-child {
          margin-bottom: 0; }
      .settingCard-xZSDjS .roleMemberList-ub4EsQ .content-28mbXd .divider-3LgWDL {
        display: none; }
  .settingCard-xZSDjS + .divider-3LgWDL {
    display: none; }

.easyModeLayoutStyle-11J5S7 .card-16VQ8C {
  margin-bottom: 24px; }

/* CHANNELS LIST -> THREADS POPOUT */
.popout-TdhJ6Z {
  padding: 8px 0 0;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .popout-TdhJ6Z .title-1yq5kT {
    padding: 0 12px;
    font-size: 14px;
    text-transform: none; }
  .popout-TdhJ6Z .row-1qtctT {
    border-radius: 0;
    color: var(--menu-item-text-color);
    transition: var(--default-time) var(--default-animation); }
    .popout-TdhJ6Z .row-1qtctT:hover {
      background-color: var(--menu-item-hover);
      color: var(--menu-item-text-color); }
  .popout-TdhJ6Z .more-2c3Z-T {
    color: hsl(var(--accent-hsl)); }
    .popout-TdhJ6Z .more-2c3Z-T .size14-3fJ-ot {
      margin-left: auto; }

/*
 *
 *	MEMBERS LIST
 *
 */
.container-2o3qEW {
  background-color: var(--main-color); }

.members-3WRCEx, .members-3WRCEx > div {
  background-color: var(--main-color); }
.members-3WRCEx .container-1oeRFJ {
  width: 100%;
  height: 42px;
  margin: 0; }
  .members-3WRCEx .container-1oeRFJ,
  .members-3WRCEx .container-1oeRFJ .layout-1qmrhw {
    border-radius: 21px 0 0 21px; }
  .members-3WRCEx .container-1oeRFJ .layout-1qmrhw {
    width: calc(100% - 18px);
    margin-left: 8px;
    padding: 0 8px 0 8px;
    transition: 200ms ease all; }
  .members-3WRCEx .container-1oeRFJ:hover .layout-1qmrhw {
    background-color: var(--menu-item-hover); }
  .members-3WRCEx .container-1oeRFJ.selected-1-Z6gm .layout-1qmrhw {
    background-color: var(--menu-item-select-accent); }
.members-3WRCEx .container-q97qHp {
  margin: 0 0 4px 0;
  padding: 20px 8px 0 16px;
  font-size: 14px;
  text-transform: none; }

.botTag-7aX5WZ {
  border-radius: 8px !important; }
  .botTag-7aX5WZ.botTagRegular-kpctgU {
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color); }
    .botTag-7aX5WZ.botTagRegular-kpctgU .botTagVerified-2KCPMa {
      z-index: 2; }

/* MEMBERS LIST -> CHANNEL BANNER */
.bannerPlaceholder-edbQI2 {
  width: calc(100% - 32px);
  margin: 16px 16px 0;
  border-radius: var(--card-radius-big); }

.contentWrapper-3wXY8L {
  padding: 16px;
  background-color: var(--main-color);
  border-bottom: 1px solid var(--card-border-color); }
  .contentWrapper-3wXY8L .contentWrapperInner-17OxmC {
    padding: 8px;
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }
  .contentWrapper-3wXY8L .button-f2h6uQ {
    --button-padding: 0 8px; }

.container-2Oqvgx {
  background-color: var(--main-color); }

.tabs-1RhQha {
  padding: 0 16px;
  background-color: transparent;
  border-bottom: 1px solid var(--card-border-color); }
  .tabs-1RhQha .item-3XjbnG {
    height: 56px;
    line-height: 56px;
    margin-right: 24px;
    padding: 0;
    border-radius: 0; }
    .tabs-1RhQha .item-3XjbnG:last-of-type {
      margin-right: 0; }
    .tabs-1RhQha .item-3XjbnG:hover {
      background-color: transparent !important; }
    .tabs-1RhQha .item-3XjbnG.selected-g-kMVV {
      position: relative;
      background-color: transparent !important; }
      .tabs-1RhQha .item-3XjbnG.selected-g-kMVV:after {
        position: absolute;
        content: " ";
        width: 90%;
        height: 3px;
        left: 0;
        right: 0;
        bottom: 0;
        margin: 0 auto;
        background: var(--tab-border-color);
        border-radius: 3px 3px 0 0;
        transition: var(--default-time) ease all; }

.container-NkLXgf {
  background-color: transparent;
  overflow-y: auto; }
  .container-NkLXgf .header-2tOrk6 {
    font-size: 14px;
    text-transform: none; }
  .container-NkLXgf .divider-2vPjtn {
    background-color: var(--card-border-color); }

/* MEMBERS LIST -> ROLES */
.role-2TIOKu {
  position: relative;
  min-width: 24px;
  height: 24px;
  padding: 0;
  background-color: transparent;
  border-radius: 16px;
  border: 1px solid var(--card-border-color); }
  .role-2TIOKu .roleCircle-1EgnFN:before {
    position: absolute;
    content: " ";
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: inherit;
    border-radius: 12px;
    opacity: 0.2;
    pointer-events: none; }
  .role-2TIOKu .roleCircle-1EgnFN,
  .role-2TIOKu .perm-circle {
    width: 16px;
    height: 16px;
    margin-left: 3px;
    margin-right: 0; }
    .role-2TIOKu .roleCircle-1EgnFN:not(:empty),
    .role-2TIOKu .perm-circle:not(:empty) {
      position: static; }
      .role-2TIOKu .roleCircle-1EgnFN:not(:empty):after,
      .role-2TIOKu .perm-circle:not(:empty):after {
        position: absolute;
        content: 'Remove role';
        width: 70px;
        max-width: 200px;
        height: auto;
        top: 0;
        left: 0;
        line-height: 16px;
        padding: var(--tooltip-padding);
        background-color: var(--tooltip-color);
        box-shadow: var(--tooltip-shadow);
        border-radius: var(--card-radius);
        transform: translate(-4px, -38px);
        pointer-events: none;
        color: var(--tooltip-text-color);
        font-size: var(--tooltip-font-size);
        font-weight: 500;
        text-align: center;
        transition: var(--default-time) var(--default-animation) all;
        z-index: 3;
        opacity: 0; }
      .role-2TIOKu .roleCircle-1EgnFN:not(:empty):hover:after,
      .role-2TIOKu .perm-circle:not(:empty):hover:after {
        opacity: 1; }
  .role-2TIOKu .perm-circle {
    width: 16px !important;
    height: 16px !important;
    margin-right: 0 !important; }
  .role-2TIOKu .roleRemoveIcon-387wKV {
    width: 24px;
    height: 24px;
    display: block;
    transition: var(--default-time) var(--default-animation) opacity, var(--default-time) var(--default-animation) transform;
    transform: scale(0.25);
    opacity: 0;
    cursor: pointer; }
  .role-2TIOKu:hover .roleRemoveIcon-387wKV {
    transform: scale(0.75) rotate(90deg);
    opacity: 1; }
  .role-2TIOKu .roleName-2ZJJYR {
    margin: 0 8px 0 4px;
    z-index: 2; }
  .role-2TIOKu.addButton-1_dZYu {
    background-color: transparent !important;
    position: relative; }
    .role-2TIOKu.addButton-1_dZYu:after {
      position: absolute;
      content: 'Add role';
      width: calc(100% + 32px);
      max-width: 200px;
      height: auto;
      top: 0;
      left: 0;
      line-height: 16px;
      padding: var(--tooltip-padding);
      background-color: var(--tooltip-color);
      box-shadow: var(--tooltip-shadow);
      border-radius: var(--card-radius);
      transform: translate(-4px, -38px);
      pointer-events: none;
      color: var(--tooltip-text-color);
      font-size: var(--tooltip-font-size);
      font-weight: 500;
      text-align: center;
      transition: var(--default-time) var(--default-animation) all;
      z-index: 3;
      opacity: 0; }
    .role-2TIOKu.addButton-1_dZYu:hover:after {
      opacity: 1; }
    .role-2TIOKu.addButton-1_dZYu .addButtonIcon-3HZ_2f {
      width: 18px;
      height: 18px; }

/*
 *
 *	CUSTOMIZABLE AVATAR & SERVER RADIUS
 *
 */
/*.wrapper-1VLyxH,
.avatarHint-k7pYop {
	border-radius: var(--avatar-radius);

	foreignObject {
		&[mask*="round-80"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="80" height="80"/><circle fill="black" cx="0.85" cy="0.85" r="0.175"/></mask>');
		}

		&[mask*="mobile-80"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="80" height="80"/><rect fill="black" x="0.675" y="0.575" width="0.35" height="0.45" rx="0.09" ry="0.09"/></mask>');
		}
	}
}

.wrapper-1VLyxH {
	.avatar-b5OQ1N {
		border-radius: var(--avatar-radius);
	}

	foreignObject {
		&[width="32"]:not([mask*="32"]),
		&[width="32"]:not([mask*="mobile"]) {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><circle fill="black" cx="0.84375" cy="0.84375" r="0.25"/></mask>');
		}

		&[mask*="avatar-default"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/></mask>') !important;
		}

		&[mask*="round-32"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><circle fill="black" cx="0.84375" cy="0.84375" r="0.25"/></mask>');
		}

		&[mask*="mobile-32"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><rect fill="black" x="0.59375" y="0.4375" width="0.5" height="0.65625" rx="0.13125" ry="0.13125"/></mask>');
		}

		&[mask*="round-40"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><circle fill="black" cx="0.85" cy="0.85" r="0.25"/></mask>');
		}

		&[mask*="mobile-40"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><rect fill="black" x="0.6" y="0.45" width="0.5" height="0.65" rx="0.13" ry="0.13"/></mask>');
		}

		&[mask*="round-120"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="120" height="120"/><circle fill="black" cx="0.8333333333333334" cy="0.8333333333333334" r="0.16666666666666666"/></mask>');
		}

		&[mask*="mobile-120"] {
			-webkit-mask: url('data:image/svg+xml;utf8,<mask xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="120" height="120"/><rect fill="black" x="0.6666666666666666" y="0.5666666666666667" width="0.3333333333333333" height="0.43333333333333335" rx="0.08666666666666667" ry="0.08666666666666667"/></mask>');
		}
	}
}

.voiceSectionGuildImage-TctMOd,
.voiceSectionNoGuildImageWrapper-17kLyh {
	border-radius: var(--avatar-radius);
	-webkit-mask: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" maskContentUnits="objectBoundingBox" viewBox="0 0 1 1"><rect fill="white" x="0" y="0" width="32" height="32"/><circle fill="black" cx="0.84375" cy="0.84375" r="0.25"/></svg>');
}

.avatar-3FKimL,
.avatarContainer-3tBLDx,
.avatar-2EVtgZ {
	border-radius: var(--avatar-radius);
}

.avatar-3FKimL,
.avatar-2EVtgZ {
	transition: var(--default-time) var(--default-animation) box-shadow;
}*/
/*
 *
 *	CHAT AREA
 *
 */
.chat-2ZfjoI,
.threadSidebar-1o3BTy {
  background-color: var(--chat-color); }

.chat-2ZfjoI.threadSidebarOpen-1LSXvU {
  border-radius: 0 16px 16px 0; }

.threadSidebar-1o3BTy {
  border-radius: 16px 0 0 16px; }

/* CHAT AREA -> PLACEHOLDER */
.wrapper-3HVHpV {
  background-color: var(--chat-color); }

.wrapper-22ayhK,
.wrapper-15CKyy {
  background-color: transparent; }

.attachment-16cAbS,
.avatar-l9Txm5,
.blob-1uHjdp {
  background-color: #fff; }

/* CHAT AREA -> MESSAGES */
.messagesWrapper-RpOMA3.group-spacing-0 .groupStart-3Mlgv1 {
  --group-spacing: 0.125rem; }
.messagesWrapper-RpOMA3.group-spacing-0 .divider-2rZFJK.beforeGroup-1BvJAt {
  top: 1px; }
.messagesWrapper-RpOMA3.group-spacing-4 .groupStart-3Mlgv1 {
  --group-spacing: 0.3125rem; }
.messagesWrapper-RpOMA3.group-spacing-4 .divider-2rZFJK.beforeGroup-1BvJAt {
  top: 2px; }
.messagesWrapper-RpOMA3.group-spacing-8 .groupStart-3Mlgv1 {
  --group-spacing: 0.5625rem; }
.messagesWrapper-RpOMA3.group-spacing-8 .divider-2rZFJK.beforeGroup-1BvJAt {
  top: 4px; }
.messagesWrapper-RpOMA3.group-spacing-16 .groupStart-3Mlgv1 {
  --group-spacing: 1.0625rem; }
.messagesWrapper-RpOMA3.group-spacing-16 .divider-2rZFJK.beforeGroup-1BvJAt {
  top: 8px; }
.messagesWrapper-RpOMA3.group-spacing-24 .groupStart-3Mlgv1 {
  --group-spacing: 1.5625rem; }
.messagesWrapper-RpOMA3.group-spacing-24 .divider-2rZFJK.beforeGroup-1BvJAt {
  top: 12px; }
.messagesWrapper-RpOMA3[class*="group-spacing"] .groupStart-3Mlgv1 {
  margin-top: var(--group-spacing) !important; }
.messagesWrapper-RpOMA3[class*="group-spacing"] .divider-2rZFJK:not(.beforeGroup-1BvJAt) {
  top: -4px; }

.messageListItem-ZZ7v6g {
  margin-left: 68px;
  margin-right: 26px; }

.quotedChatMessage-PxNsZi {
  margin-left: 68px;
  margin-right: 26px; }

.wrapper-30-Nkg {
  background-color: var(--message-color) !important;
  transition: var(--default-time) var(--default-animation) background-color; }
  .wrapper-30-Nkg:hover {
    background-color: var(--message-color-hover) !important; }
    .wrapper-30-Nkg:hover + .wrapper-30-Nkg:not(.groupStart-3Mlgv1):before {
      border-left-color: var(--message-color-hover); }
    .wrapper-30-Nkg:hover + .wrapper-30-Nkg:not(.groupStart-3Mlgv1):after {
      border-bottom-color: var(--message-color-hover); }
  .wrapper-30-Nkg.hasThread-3h-KJV:after {
    display: none; }
  .wrapper-30-Nkg.hasThread-3h-KJV .messageContent-2t3eCI {
    overflow: visible; }
  .wrapper-30-Nkg.hasThread-3h-KJV .container-x059i8 {
    padding: 0; }
  .wrapper-30-Nkg.hasThread-3h-KJV .iconContainer-2rPbqG {
    position: absolute;
    width: 40px !important;
    height: 40px;
    top: -8px;
    left: -62px;
    margin-right: 0;
    padding-top: 0;
    background-color: var(--message-color-hover);
    border-radius: var(--avatar-radius); }
  .wrapper-30-Nkg.hasThread-3h-KJV .container-3i3IzO {
    width: 100%;
    padding: 12px;
    background-color: var(--attachment-color);
    border-radius: var(--media-radius);
    box-sizing: border-box; }
  .wrapper-30-Nkg.hasThread-3h-KJV .cta-1XhfrG {
    color: hsl(var(--accent-hsl)); }
  .wrapper-30-Nkg.groupStart-3Mlgv1 {
    position: relative;
    border-radius: var(--message-radius); }
    .wrapper-30-Nkg.groupStart-3Mlgv1 .avatar-2e8lTP {
      width: 40px;
      height: 40px;
      top: 0;
      left: -50px;
      margin-top: 0;
      border-radius: var(--avatar-radius); }
  .wrapper-30-Nkg.ephemeral-2nDdnn:before, .wrapper-30-Nkg.replying-eZ7p5z:before {
    display: none; }
  .wrapper-30-Nkg.ephemeral-2nDdnn a, .wrapper-30-Nkg.replying-eZ7p5z a {
    color: hsl(var(--accent-hsl)); }
  .wrapper-30-Nkg:not(.groupStart-3Mlgv1) {
    border-radius: 0 0 var(--message-radius) var(--message-radius); }
    .wrapper-30-Nkg:not(.groupStart-3Mlgv1):before, .wrapper-30-Nkg:not(.groupStart-3Mlgv1):after {
      content: " ";
      position: absolute;
      width: 0;
      height: 0;
      top: 2px;
      background-color: transparent;
      border: 16px solid transparent;
      border-color: transparent;
      pointer-events: none; }
    .wrapper-30-Nkg:not(.groupStart-3Mlgv1):before {
      left: 0;
      border-left-color: var(--message-color);
      transition: var(--default-time) var(--default-animation) border-left-color; }
    .wrapper-30-Nkg:not(.groupStart-3Mlgv1):after {
      right: 0;
      border-bottom-color: var(--message-color);
      transition: var(--default-time) var(--default-animation) border-bottom-color; }
  .wrapper-30-Nkg.cozy-VmLDNB {
    padding: var(--message-padding) !important; }
    .wrapper-30-Nkg.cozy-VmLDNB.groupStart-3Mlgv1 {
      margin-left: 0;
      margin-right: 0;
      margin-bottom: 0; }
      .wrapper-30-Nkg.cozy-VmLDNB.groupStart-3Mlgv1.mentioned-Tre-dv:before {
        display: none; }
    .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1) {
      margin: -8px 0 0 0;
      padding: var(--message-padding-alt) !important; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1):before, .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1):after {
        margin: -16px 0 0 0; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1):before {
        border-width: 14px 0 0 6px; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1):after {
        border-width: 0 0 14px 6px; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1) + .divider-2rZFJK:not(.beforeGroup-1BvJAt) {
        top: -4px; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1).mentioned-Tre-dv:before {
        content: " ";
        position: absolute;
        width: 0;
        height: 0;
        top: 3px;
        background-color: transparent;
        border: 16px solid transparent;
        border-color: transparent;
        pointer-events: none;
        transform: rotate(360deg);
        left: 0;
        border-left-color: var(--message-color); }
    .wrapper-30-Nkg.cozy-VmLDNB .header-2jRmjb {
      margin-bottom: 4px; }
    .wrapper-30-Nkg.cozy-VmLDNB .messageContent-2t3eCI {
      margin-left: 0;
      padding-left: 0; }
    .wrapper-30-Nkg.cozy-VmLDNB:hover .timestamp-p1Df1m.alt-1dvXnH {
      opacity: 1;
      transition: var(--default-time) ease opacity 750ms; }
    .wrapper-30-Nkg.cozy-VmLDNB .timestamp-p1Df1m.alt-1dvXnH {
      opacity: 0;
      left: -72px;
      color: var(--text-muted);
      font-weight: 600;
      transition: var(--default-time) ease opacity 0ms; }
    .wrapper-30-Nkg.cozy-VmLDNB:not(.message-2CShn3) {
      margin: 16px 26px 0 68px;
      padding: 8px 12px !important;
      border-radius: var(--message-radius); }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.message-2CShn3):before, .wrapper-30-Nkg.cozy-VmLDNB:not(.message-2CShn3):after {
        display: none; }
      .wrapper-30-Nkg.cozy-VmLDNB:not(.message-2CShn3) .avatar-2e8lTP {
        top: 0;
        left: -63px; }
    .wrapper-30-Nkg.cozy-VmLDNB .repliedMessage-3Z6XBG:before {
      transform: translateX(42px); }
    .wrapper-30-Nkg.cozy-VmLDNB .repliedMessage-3Z6XBG .replyAvatar-sHd2sU,
    .wrapper-30-Nkg.cozy-VmLDNB .repliedMessage-3Z6XBG .replyBadge-LMm_Ic,
    .wrapper-30-Nkg.cozy-VmLDNB .repliedMessage-3Z6XBG .executedCommandAvatar-3oOnb1,
    .wrapper-30-Nkg.cozy-VmLDNB .repliedMessage-3Z6XBG .userJoinSystemMessageIcon-3FQ_Mo {
      margin-left: 42px; }
  .wrapper-30-Nkg.compact-2Nkcau {
    margin-bottom: 0;
    padding-right: 8px !important; }
    .wrapper-30-Nkg.compact-2Nkcau.groupStart-3Mlgv1 {
      padding: 8px; }
      .wrapper-30-Nkg.compact-2Nkcau.groupStart-3Mlgv1.mentioned-Tre-dv:before {
        display: none; }
      .wrapper-30-Nkg.compact-2Nkcau.groupStart-3Mlgv1 + .divider-2rZFJK {
        margin-bottom: -1px; }
    .wrapper-30-Nkg.compact-2Nkcau:not(.groupStart-3Mlgv1) {
      padding: 0 8px 8px 8px; }
      .wrapper-30-Nkg.compact-2Nkcau:not(.groupStart-3Mlgv1):before, .wrapper-30-Nkg.compact-2Nkcau:not(.groupStart-3Mlgv1):after {
        margin: -18px 0 0 0; }
      .wrapper-30-Nkg.compact-2Nkcau:not(.groupStart-3Mlgv1):before {
        border-width: 16px 0 0 14px; }
      .wrapper-30-Nkg.compact-2Nkcau:not(.groupStart-3Mlgv1):after {
        border-width: 0 0 16px 14px; }
    .wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .contents-2MsGLg:before {
      display: none; }
    .wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .content-vSHmMD {
      margin-left: 44px; }
    .wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .spine-2vt3pM {
      display: none; }
    .wrapper-30-Nkg.compact-2Nkcau .header-2jRmjb {
      position: relative;
      left: -8px; }
    .wrapper-30-Nkg.compact-2Nkcau .timestamp-p1Df1m {
      width: 52px;
      margin-right: 16px;
      color: var(--text-muted); }
    .wrapper-30-Nkg.compact-2Nkcau + .divider-2rZFJK {
      margin-left: 80px; }
      .wrapper-30-Nkg.compact-2Nkcau + .divider-2rZFJK:not(.beforeGroup-1BvJAt) {
        top: -11px; }
    .wrapper-30-Nkg.compact-2Nkcau .repliedMessage-3Z6XBG {
      margin-left: calc(var(--timestamp-width) + 3.1rem + var(--text-indent)); }
    .wrapper-30-Nkg.compact-2Nkcau + .wrapper-30-Nkg.compact-2Nkcau:not(.message-2CShn3) {
      margin: 16px 20px 0 70px; }
    .wrapper-30-Nkg.compact-2Nkcau .iconContainer-2rPbqG {
      margin-left: 4.5ch; }
  .wrapper-30-Nkg.mentioned-Tre-dv .messageContent-2t3eCI {
    position: relative;
    background-color: hsla(var(--accent-hsl), 0.2);
    border-radius: var(--card-radius); }
    .wrapper-30-Nkg.mentioned-Tre-dv .messageContent-2t3eCI a {
      color: var(--accent-text-color); }
    .wrapper-30-Nkg.mentioned-Tre-dv .messageContent-2t3eCI .wrapper-1ZcZW-:before {
      display: none; }
    .wrapper-30-Nkg.mentioned-Tre-dv .messageContent-2t3eCI .wrapper-1ZcZW-:hover {
      color: var(--accent-text-color); }
  .wrapper-30-Nkg .iconContainer-2rPbqG {
    position: relative;
    width: auto !important;
    right: auto;
    margin-right: 12px; }
    .wrapper-30-Nkg .iconContainer-2rPbqG .icon-JRJzJz[style*='/assets/c30220457097b064286a8759a9b6c4af.svg'] {
      background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/phone_called.svg) !important; }
    .wrapper-30-Nkg .iconContainer-2rPbqG .icon-JRJzJz[style*='/assets/d80d1fdc43a3c42134a31a39581160ac.svg'] {
      background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/phone_missed.svg) !important; }
  .wrapper-30-Nkg .channelTextArea-1VQBuV .scrollableContainer-15eg7h {
    background-color: var(--main-textarea-color-alt);
    border-radius: var(--main-textarea-radius); }

.operations-3q3u6E > a {
  color: hsl(var(--accent-hsl)); }

/* CHAT AREA -> MESSAGES -> ACTIONS */
.message-2CShn3 .buttons-3dF5Kd {
  max-width: 32px;
  opacity: 0;
  visibility: visible;
  pointer-events: none;
  transition: opacity var(--default-time) var(--default-animation), max-width var(--default-time) var(--default-animation) var(--default-time); }
.message-2CShn3.selected-2LX7Jy .buttons-3dF5Kd, .message-2CShn3:hover .buttons-3dF5Kd {
  max-width: 380px;
  opacity: 1;
  pointer-events: all; }

.wrapper-2vIMkT {
  background-color: var(--main-textarea-color);
  border-radius: 16px;
  box-shadow: var(--shadow-2dp);
  border: none;
  overflow: hidden; }
  .wrapper-2vIMkT:hover {
    box-shadow: var(--shadow-3dp); }
  .wrapper-2vIMkT .button-3bklZh {
    transition: var(--default-time) ease all;
    /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS */ }
    .wrapper-2vIMkT .button-3bklZh:hover {
      background-color: var(--menu-item-hover); }
    .wrapper-2vIMkT .button-3bklZh:active {
      padding: 4px; }
    .wrapper-2vIMkT .button-3bklZh .selected-69H4ua {
      background-color: var(--menu-item-select); }
    .wrapper-2vIMkT .button-3bklZh svg {
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> ADD REACTION */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> START THREAD */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> REPLY */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> EDIT MESSAGE */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> RETRY */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> DELETE MESSAGE */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> MARK READ */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> PIN MESSAGE */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> COPY LINK */
      /* CHAT AREA -> MESSAGES -> ACTIONS -> ICONS -> COPY ID */ }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M12.2512 2.00309C12.1677 2.00104 12.084 2 12 2C6.477 2 2 6.477 2 12C2 17.522 6.477 22 12 22C17.523 22 22 17.522 22 12C22 11.916 21.999 11.8323 21.9969 11.7488C21.3586 11.9128 20.6895 12 20 12C15.5817 12 12 8.41828 12 4C12 3.31052 12.0872 2.6414 12.2512 2.00309ZM10 8C10 6.896 9.104 6 8 6C6.896 6 6 6.896 6 8C6 9.105 6.896 10 8 10C9.104 10 10 9.105 10 8ZM12 19C15.14 19 18 16.617 18 14V13H6V14C6 16.617 8.86 19 12 19Z"] {
        d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm3.5-9c.83 0 1.5-.67 1.5-1.5S16.33 8 15.5 8 14 8.67 14 9.5s.67 1.5 1.5 1.5zm-7 0c.83 0 1.5-.67 1.5-1.5S9.33 8 8.5 8 7 8.67 7 9.5 7.67 11 8.5 11zm3.5 6.5c2.33 0 4.31-1.46 5.11-3.5H6.89c.8 2.04 2.78 3.5 5.11 3.5z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M12.2512 2.00309C12.1677 2.00104 12.084 2 12 2C6.477 2 2 6.477 2 12C2 17.522 6.477 22 12 22C17.523 22 22 17.522 22 12C22 11.916 21.999 11.8323 21.9969 11.7488C21.3586 11.9128 20.6895 12 20 12C15.5817 12 12 8.41828 12 4C12 3.31052 12.0872 2.6414 12.2512 2.00309ZM10 8C10 6.896 9.104 6 8 6C6.896 6 6 6.896 6 8C6 9.105 6.896 10 8 10C9.104 10 10 9.105 10 8ZM12 19C15.14 19 18 16.617 18 14V13H6V14C6 16.617 8.86 19 12 19Z"] ~ path {
        display: none; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M4.79805 3C3.80445 3 2.99805 3.8055 2.99805 4.8V15.6C2.99805 16.5936 3.80445 17.4 4.79805 17.4H7.49805V21L11.098 17.4H19.198C20.1925 17.4 20.998 16.5936 20.998 15.6V4.8C20.998 3.8055 20.1925 3 19.198 3H4.79805Z"] {
        d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H6l-2 2V4h16v12z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M10 8.26667V4L3 11.4667L10 18.9333V14.56C15 14.56 18.5 16.2667 21 20C20 14.6667 17 9.33333 10 8.26667Z"] {
        d: path("M8,9.8V10.7L9.7,11C12.3,11.4 14.2,12.4 15.6,13.7C13.9,13.2 12.1,12.9 10,12.9H8V14.2L5.8,12L8,9.8M10,5L3,12L10,19V14.9C15,14.9 18.5,16.5 21,20C20,15 17,10 10,9") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M19.2929 9.8299L19.9409 9.18278C21.353 7.77064 21.353 5.47197 19.9409 4.05892C18.5287 2.64678 16.2292 2.64678 14.817 4.05892L14.1699 4.70694L19.2929 9.8299ZM12.8962 5.97688L5.18469 13.6906L10.3085 18.813L18.0201 11.0992L12.8962 5.97688ZM4.11851 20.9704L8.75906 19.8112L4.18692 15.239L3.02678 19.8796C2.95028 20.1856 3.04028 20.5105 3.26349 20.7337C3.48669 20.9569 3.8116 21.046 4.11851 20.9704Z"] {
        d: path("M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM5.92 19H5v-.92l9.06-9.06.92.92L5.92 19zM20.71 5.63l-2.34-2.34c-.2-.2-.45-.29-.71-.29s-.51.1-.7.29l-1.83 1.83 3.75 3.75 1.83-1.83c.39-.39.39-1.02 0-1.41z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M12 2C6.485 2 2 6.485 2 12H5.33333C5.33333 8.32333 8.32333 5.33333 12 5.33333C15.6767 5.33333 18.6667 8.32333 18.6667 12C18.6667 15.6767 15.6767 18.6667 12 18.6667C10.2033 18.6667 8.55833 17.9333 7.315 16.6867L10.3333 13.6667H2V22L4.935 19.065C6.79833 20.94 9.30167 22 12 22C17.515 22 22 17.515 22 12C22 6.48667 17.515 2 12 2Z"] {
        d: path("M17.65 6.35C16.2 4.9 14.21 4 12 4c-4.42 0-7.99 3.58-7.99 8s3.57 8 7.99 8c3.73 0 6.84-2.55 7.73-6h-2.08c-.82 2.33-3.04 4-5.65 4-3.31 0-6-2.69-6-6s2.69-6 6-6c1.66 0 3.14.69 4.22 1.78L13 11h7V4l-2.35 2.35z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M15 3.999V2H9V3.999H3V5.999H21V3.999H15Z"] {
        d: path("M16 9v10H8V9h8m-1.5-6h-5l-1 1H5v2h14V4h-3.5l-1-1zM18 7H6v12c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M15 3.999V2H9V3.999H3V5.999H21V3.999H15Z"] ~ path {
        display: none; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M14 3H20C21 3 22.0001 4 22.0001 5V19.0003C22.0001 20 21 21 20 21H14C13 21 6 13 6 13H2V11H6C6 11 13 3 14 3Z"] {
        d: path("M22,6.98V16c0,1.1-0.9,2-2,2H6l-4,4V4c0-1.1,0.9-2,2-2h10.1C14.04,2.32,14,2.66,14,3s0.04,0.68,0.1,1H4v12h16V7.9 C20.74,7.75,21.42,7.42,22,6.98z M16,3c0,1.66,1.34,3,3,3s3-1.34,3-3s-1.34-3-3-3S16,1.34,16,3z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M22 12L12.101 2.10101L10.686 3.51401L12.101 4.92901L7.15096 9.87801V9.88001L5.73596 8.46501L4.32196 9.88001L8.56496 14.122L2.90796 19.778L4.32196 21.192L9.97896 15.536L14.222 19.778L15.636 18.364L14.222 16.95L19.171 12H19.172L20.586 13.414L22 12Z"] {
        d: path("M16,12V4H17V2H7V4H8V12L6,14V16H11.2V22H12.8V16H18V14L16,12M8.8,14L10,12.8V4H14V12.8L15.2,14H8.8Z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M10.59 13.41c.41.39.41 1.03 0 1.42-.39.39-1.03.39-1.42 0a5.003 5.003 0 0 1 0-7.07l3.54-3.54a5.003 5.003 0 0 1 7.07 0 5.003 5.003 0 0 1 0 7.07l-1.49 1.49c.01-.82-.12-1.64-.4-2.42l.47-.48a2.982 2.982 0 0 0 0-4.24 2.982 2.982 0 0 0-4.24 0l-3.53 3.53a2.982 2.982 0 0 0 0 4.24zm2.82-4.24c.39-.39 1.03-.39 1.42 0a5.003 5.003 0 0 1 0 7.07l-3.54 3.54a5.003 5.003 0 0 1-7.07 0 5.003 5.003 0 0 1 0-7.07l1.49-1.49c-.01.82.12 1.64.4 2.43l-.47.47a2.982 2.982 0 0 0 0 4.24 2.982 2.982 0 0 0 4.24 0l3.53-3.53a2.982 2.982 0 0 0 0-4.24.973.973 0 0 1 0-1.42z"] {
        d: path("M17 7h-4v2h4c1.65 0 3 1.35 3 3s-1.35 3-3 3h-4v2h4c2.76 0 5-2.24 5-5s-2.24-5-5-5zm-6 8H7c-1.65 0-3-1.35-3-3s1.35-3 3-3h4V7H7c-2.76 0-5 2.24-5 5s2.24 5 5 5h4v-2zm-3-4h8v2H8z") !important; }
      .wrapper-2vIMkT .button-3bklZh svg path[d="M5 2C3.34315 2 2 3.34315 2 5V19C2 20.6569 3.34315 22 5 22H19C20.6569 22 22 20.6569 22 19V5C22 3.34315 20.6569 2 19 2H5ZM8.79741 7.72V16H6.74541V7.72H8.79741ZM13.2097 7.72C16.0897 7.72 17.5897 9.388 17.5897 11.848C17.5897 14.308 16.0537 16 13.2577 16H10.3537V7.72H13.2097ZM13.1497 14.404C14.6137 14.404 15.5257 13.636 15.5257 11.86C15.5257 10.12 14.5537 9.316 13.1497 9.316H12.4057V14.404H13.1497Z"] {
        d: path("M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 16H8V7h11v14z") !important; }

/* CHAT AREA -> MESSAGES -> ACTIONS -> DELETE MESSAGE */
.message-G6O-Wv {
  padding: 0;
  background-color: transparent !important;
  box-shadow: none !important; }
  .message-G6O-Wv .wrapper-30-Nkg {
    margin: 0 0 0 52px !important;
    background-color: var(--message-color-alt) !important; }
    .message-G6O-Wv .wrapper-30-Nkg .avatar-2e8lTP {
      left: -52px !important; }

.container-1zDvAE .control-1fl03- {
  position: relative;
  top: 5px; }

/* CHAT AREA -> MESSAGES -> NEW MESSAGES */
.barBase-3xxDXu {
  left: 0;
  right: 0;
  background-color: hsl(var(--accent-hsl));
  border-radius: 0;
  box-shadow: var(--shadow-1dp); }
  .barBase-3xxDXu .barButtonBase-Sk2mdB {
    color: var(--accent-text-color); }

.divider-2rZFJK.isUnread-3Lojb- {
  margin: 0 .875rem 0 80px;
  border-color: hsl(var(--accent-hsl)); }
  .divider-2rZFJK.isUnread-3Lojb- .unreadPill-3nEWYM {
    height: 28px;
    top: -15px;
    padding: 0 16px;
    background-color: hsl(var(--accent-hsl));
    border-radius: 14px;
    box-shadow: var(--shadow-3dp);
    font-size: 14px;
    font-weight: 500;
    text-transform: capitalize;
    color: var(--accent-text-color); }
    .divider-2rZFJK.isUnread-3Lojb- .unreadPill-3nEWYM .unreadPillCap-2-iI4h {
      display: none; }
  .divider-2rZFJK.isUnread-3Lojb-.hasContent-31hcsn .content-3spvdd {
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color); }
.divider-2rZFJK.hasContent-31hcsn {
  margin-left: 1rem; }

/* CHAT AREA -> MESSAGES -> JUMP TO BUTTON */
.jumpToPresentBar-1cEnH0 {
  width: 48px;
  height: 48px;
  border-radius: 30%;
  left: auto;
  right: 20px;
  bottom: 20px;
  padding: 0;
  background: hsl(var(--accent-hsl)) !important;
  box-shadow: var(--shadow-3dp); }
  .jumpToPresentBar-1cEnH0:active {
    margin: 0 !important; }
  .jumpToPresentBar-1cEnH0:after {
    content: " ";
    position: absolute;
    width: 48px;
    height: 48px;
    bottom: 0;
    right: 0;
    background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGRkZGRiIgZD0iTTcuNDEsOC41OEwxMiwxMy4xN0wxNi41OSw4LjU4TDE4LDEwTDEyLDE2TDYsMTBMNy40MSw4LjU4WiIgLz48L3N2Zz4=);
    background-repeat: no-repeat;
    background-size: 75%;
    background-color: transparent;
    background-position: 7px 7px;
    border-radius: 50%; }
  .jumpToPresentBar-1cEnH0 .barButtonBase-Sk2mdB {
    width: inherit;
    height: inherit;
    padding: inherit; }
    .jumpToPresentBar-1cEnH0 .barButtonBase-Sk2mdB.barButtonMain-2GIx4o {
      opacity: 0;
      z-index: 2; }
    .jumpToPresentBar-1cEnH0 .barButtonBase-Sk2mdB.barButtonAlt-TQoCdZ {
      display: none; }
  .jumpToPresentBar-1cEnH0 .spinner-2RT7ZC {
    position: absolute;
    width: inherit;
    height: inherit;
    padding: inherit;
    background-color: hsl(var(--accent-hsl));
    border-radius: 50%;
    z-index: 3; }
    .jumpToPresentBar-1cEnH0 .spinner-2RT7ZC .pulsingEllipsis-10G8Z6 {
      vertical-align: middle; }

.messagesErrorBar-1IQ1rH {
  width: auto;
  height: 36px;
  left: auto;
  right: 16px;
  bottom: 12px;
  padding: 0;
  border-radius: 18px;
  box-shadow: var(--shadow-2dp);
  transition: var(--default-time) var(--default-animation) box-shadow; }
  .messagesErrorBar-1IQ1rH:hover {
    box-shadow: var(--shadow-3dp); }
  .messagesErrorBar-1IQ1rH .barButtonMain-2GIx4o {
    min-width: 36px;
    padding: 0 18px 0 12px;
    flex: 0 1 auto; }
    .messagesErrorBar-1IQ1rH .barButtonMain-2GIx4o:after {
      position: absolute;
      content: "|";
      width: 4px;
      height: 100%;
      top: 0;
      right: 0; }

/* CHAT AREA -> MESSAGES -> MARKUP */
.markup-eYLPri a {
  color: hsl(var(--accent-hsl)); }
.markup-eYLPri .wrapper-1ZcZW- {
  position: relative;
  background-color: hsla(var(--accent-hsl), 0.1);
  border-radius: var(--card-radius);
  color: hsl(var(--accent-hsl)); }
  .markup-eYLPri .wrapper-1ZcZW-:hover {
    background-color: hsla(var(--accent-hsl), 0.3); }
.markup-eYLPri pre, .markup-eYLPri pre *, .markup-eYLPri pre code, .markup-eYLPri pre code *, .markup-eYLPri code.inline, .markup-eYLPri .codeBlockText-311wOq, .markup-eYLPri .codeBlockText-311wOq *, .markup-eYLPri .codeLine-3a3dbd, .markup-eYLPri .codeLine-3a3dbd *, .markup-eYLPri .codeBlockLang-3OMn-4, .markup-eYLPri .codeBlockLang-3OMn-4 *, .markup-eYLPri .codeBlockSyntax-2MZ-Qy, .markup-eYLPri .codeBlockSyntax-2MZ-Qy *, .markup-eYLPri .syntaxAfter-OxiKEl, .markup-eYLPri .syntaxAfter-OxiKEl *, .markup-eYLPri .syntaxBefore-3pDAmR, .markup-eYLPri .syntaxBefore-3pDAmR {
  font-family: var(--code-font) !important; }
.markup-eYLPri pre,
.markup-eYLPri pre code,
.markup-eYLPri code.inline {
  background-color: var(--attachment-color);
  border-radius: var(--card-radius);
  border: none; }
  .markup-eYLPri pre code,
  .markup-eYLPri pre code code,
  .markup-eYLPri code.inline code {
    background-color: transparent; }
.markup-eYLPri pre,
.markup-eYLPri code.inline {
  margin: 4px 0; }

.textContainer-36wgKK,
.footer-GXWBBp {
  background-color: var(--attachment-color);
  border: none; }

.textContainer-36wgKK {
  border-radius: var(--card-radius) var(--card-radius) 0 0; }

.footer-GXWBBp {
  border-radius: 0 0 var(--card-radius) var(--card-radius);
  border-top: 1px solid var(--separator-color); }

.codeView-12LUIl, .codeView-12LUIl * {
  font-family: var(--code-font) !important; }

/* CHAT AREA -> MESSAGES -> SPOILERS */
.spoilerText-27bIiA, .spoilerText-27bIiA.hidden-3B-Rum {
  background-color: var(--attachment-color) !important; }

/* CHAT AREA -> MESSAGES -> REACTIONS */
.reactions-1BUEKl {
  margin: 8px 0 0 0; }
  .reactions-1BUEKl .reaction-2A2y9y {
    background-color: var(--menu-item-hover);
    border-radius: 12px;
    border: none; }
    .reactions-1BUEKl .reaction-2A2y9y:hover {
      background-color: var(--menu-item-select); }
    .reactions-1BUEKl .reaction-2A2y9y.reactionMe-3I9gFK {
      background-color: hsla(var(--accent-hsl), 0.3); }
      .reactions-1BUEKl .reaction-2A2y9y.reactionMe-3I9gFK .reactionCount-1zkLcN {
        color: var(--accent-text-color);
        font-weight: 400; }

/* CHAT AREA -> MESSAGES -> ATTACHMENTS */
.attachment-1PZZB2 {
  background-color: var(--attachment-color);
  border-radius: var(--message-radius);
  border: none; }
  .attachment-1PZZB2 .downloadWrapper-1Cy2Fi {
    position: relative; }
    .attachment-1PZZB2 .downloadWrapper-1Cy2Fi:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .attachment-1PZZB2 .downloadWrapper-1Cy2Fi:hover:after {
      opacity: 1;
      transform: scale(1.4);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .attachment-1PZZB2 .downloadWrapper-1Cy2Fi:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
  .attachment-1PZZB2 .downloadButton-2HLFWN {
    margin-left: 0; }
    .attachment-1PZZB2 .downloadButton-2HLFWN path {
      d: path("M13 5v6h1.17L12 13.17 9.83 11H11V5h2m2-2H9v6H5l7 7 7-7h-4V3zm4 15H5v2h14v-2z") !important; }

.progress-xNqAjK {
  background-color: hsla(var(--accent-hsl), 0.3) !important; }
  .progress-xNqAjK .progressBar-1T6LYX {
    background-color: hsl(var(--accent-hsl)) !important; }

.embed-hKpSrO {
  border-radius: var(--media-radius); }
  .embed-hKpSrO.embedFull-1HGV2S {
    background-color: var(--attachment-color); }

.wrapper-1HIH0j {
  background-color: var(--attachment-color);
  border-radius: var(--message-radius); }
  .wrapper-1HIH0j .header-3anOjb {
    font-size: 14px;
    text-transform: none; }
  .wrapper-1HIH0j .guildIcon-3ZfRfI {
    border-radius: 50%; }

/* CHAT AREA -> MESSAGES -> ATTACHMENTS -> AUDIO FILE */
.wrapperAudio-1Bzv_Z {
  padding: 0;
  background-color: var(--attachment-color) !important;
  border-radius: var(--media-radius);
  border: none; }
  .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T {
    padding: 8px; }
    .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T .anchor-1MIwyf {
      position: relative; }
      .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T .anchor-1MIwyf:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T .anchor-1MIwyf:hover:after {
        opacity: 1;
        transform: scale(1.4);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T .anchor-1MIwyf:active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
    .wrapperAudio-1Bzv_Z .audioMetadata-1Hrt8T .metadataIcon-3QMhu9 path[d="M16.293 9.293L17.707 10.707L12 16.414L6.29297 10.707L7.70697 9.293L11 12.586V2H13V12.586L16.293 9.293ZM18 20V18H20V20C20 21.102 19.104 22 18 22H6C4.896 22 4 21.102 4 20V18H6V20H18Z"] {
      d: path("M13 5v6h1.17L12 13.17 9.83 11H11V5h2m2-2H9v6H5l7 7 7-7h-4V3zm4 15H5v2h14v-2z"); }
  .wrapperAudio-1Bzv_Z .audioControls-3fmemK {
    margin-top: 0;
    background-color: transparent;
    border-radius: 0;
    border-top: 1px solid var(--card-border-color); }
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .controlIcon-1grhw_ {
      padding: 8px; }
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarGrabber-FvJKJg, .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarGrabber-FvJKJg:before, .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarGrabber-FvJKJg:after,
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarProgress-38I317,
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarProgress-38I317:before,
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .mediaBarProgress-38I317:after {
      background-color: hsl(var(--accent-hsl)); }
    .wrapperAudio-1Bzv_Z .audioControls-3fmemK .fakeEdges-18N907:before, .wrapperAudio-1Bzv_Z .audioControls-3fmemK .fakeEdges-18N907:after {
      border-radius: 0; }

/* CHAT AREA -> MESSAGES -> ATTACHMENTS -> EMOJI SELLUP */
.popoutContainer-2wbmiM {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .popoutContainer-2wbmiM .emojiSection-3QtaWO,
  .popoutContainer-2wbmiM .guildSection-2Zyzy8 {
    background-color: transparent; }
  .popoutContainer-2wbmiM .guildSection-2Zyzy8 {
    border-top: 1px solid var(--card-border-color); }

.container-1ZA19X {
  z-index: 2; }
  .container-1ZA19X .stickerResults-cD_yeI {
    padding: 16px 16px 8px; }
  .container-1ZA19X .bottomInformationTextContainer-3xmddX {
    padding: 8px 16px 8px;
    border-top: 1px solid var(--card-border-color); }
    .container-1ZA19X .bottomInformationTextContainer-3xmddX .textDivider-34kVsR {
      display: none; }
  .container-1ZA19X .containerBackground-Ang24O {
    background-color: var(--popout-color) ;
    border-radius: var(--popout-radius-big) ;
    box-shadow: var(--shadow-3dp) ;
    border: none; }
    .container-1ZA19X .containerBackground-Ang24O:after {
      border-top-color: var(--popout-color); }

/* CHAT AREA -> MESSAGES -> ATTACHMENTS -> IMAGES */
.imageWrapper-oMkQl4.embedWrapper-1MtIDg {
  border-radius: var(--media-radius); }

.embedMedia-1mdWSP {
  border-radius: var(--media-radius); }

.spoilerContainer-3wsC0k {
  border-radius: var(--message-radius);
  box-shadow: none !important; }

/* CHAT AREA -> MAIN TEXTAREA */
.form-3gdLxP,
.form-3uUEen {
  margin-top: 0;
  background-color: var(--chat-color); }
  .form-3gdLxP:before,
  .form-3uUEen:before {
    display: none; }
  .form-3gdLxP .channelTextArea-1FufC0,
  .form-3gdLxP .channelTextArea-2ZBawt,
  .form-3uUEen .channelTextArea-1FufC0,
  .form-3uUEen .channelTextArea-2ZBawt {
    margin: 12px 0;
    background-color: transparent;
    border-radius: var(--main-textarea-radius); }
    .form-3gdLxP .channelTextArea-1FufC0.channelTextAreaDisabled-1p2fQv,
    .form-3gdLxP .channelTextArea-2ZBawt.channelTextAreaDisabled-1p2fQv,
    .form-3uUEen .channelTextArea-1FufC0.channelTextAreaDisabled-1p2fQv,
    .form-3uUEen .channelTextArea-2ZBawt.channelTextAreaDisabled-1p2fQv {
      opacity: 0.8; }
    .form-3gdLxP .channelTextArea-1FufC0 .scrollableContainer-15eg7h,
    .form-3gdLxP .channelTextArea-2ZBawt .scrollableContainer-15eg7h,
    .form-3uUEen .channelTextArea-1FufC0 .scrollableContainer-15eg7h,
    .form-3uUEen .channelTextArea-2ZBawt .scrollableContainer-15eg7h {
      background-color: var(--main-textarea-color);
      border-radius: var(--main-textarea-radius);
      border: 1px solid var(--main-textarea-border);
      opacity: 1; }
      .form-3gdLxP .channelTextArea-1FufC0 .scrollableContainer-15eg7h.hasConnectedBar-1vN2JH,
      .form-3gdLxP .channelTextArea-2ZBawt .scrollableContainer-15eg7h.hasConnectedBar-1vN2JH,
      .form-3uUEen .channelTextArea-1FufC0 .scrollableContainer-15eg7h.hasConnectedBar-1vN2JH,
      .form-3uUEen .channelTextArea-2ZBawt .scrollableContainer-15eg7h.hasConnectedBar-1vN2JH {
        border-radius: 0 0 var(--main-textarea-radius) var(--main-textarea-radius); }
    .form-3gdLxP .channelTextArea-1FufC0 .clipContainer-31nYlH,
    .form-3gdLxP .channelTextArea-2ZBawt .clipContainer-31nYlH,
    .form-3uUEen .channelTextArea-1FufC0 .clipContainer-31nYlH,
    .form-3uUEen .channelTextArea-2ZBawt .clipContainer-31nYlH {
      margin-top: 0;
      padding-top: 0; }
    .form-3gdLxP .channelTextArea-1FufC0 .attachedBars-2BCP3l,
    .form-3gdLxP .channelTextArea-2ZBawt .attachedBars-2BCP3l,
    .form-3uUEen .channelTextArea-1FufC0 .attachedBars-2BCP3l,
    .form-3uUEen .channelTextArea-2ZBawt .attachedBars-2BCP3l {
      background-color: var(--main-textarea-color);
      border-radius: var(--main-textarea-radius) var(--main-textarea-radius) 0 0;
      border: 1px solid var(--main-textarea-border);
      border-bottom: none; }
      .form-3gdLxP .channelTextArea-1FufC0 .attachedBars-2BCP3l .replyBar-1oi75v,
      .form-3gdLxP .channelTextArea-2ZBawt .attachedBars-2BCP3l .replyBar-1oi75v,
      .form-3uUEen .channelTextArea-1FufC0 .attachedBars-2BCP3l .replyBar-1oi75v,
      .form-3uUEen .channelTextArea-2ZBawt .attachedBars-2BCP3l .replyBar-1oi75v {
        background-color: transparent;
        border-radius: 0; }
      .form-3gdLxP .channelTextArea-1FufC0 .attachedBars-2BCP3l .colorBrand-21Le_q,
      .form-3gdLxP .channelTextArea-1FufC0 .attachedBars-2BCP3l .colorLink-2apWfY,
      .form-3gdLxP .channelTextArea-2ZBawt .attachedBars-2BCP3l .colorBrand-21Le_q,
      .form-3gdLxP .channelTextArea-2ZBawt .attachedBars-2BCP3l .colorLink-2apWfY,
      .form-3uUEen .channelTextArea-1FufC0 .attachedBars-2BCP3l .colorBrand-21Le_q,
      .form-3uUEen .channelTextArea-1FufC0 .attachedBars-2BCP3l .colorLink-2apWfY,
      .form-3uUEen .channelTextArea-2ZBawt .attachedBars-2BCP3l .colorBrand-21Le_q,
      .form-3uUEen .channelTextArea-2ZBawt .attachedBars-2BCP3l .colorLink-2apWfY {
        color: hsl(var(--accent-hsl)); }
  .form-3gdLxP .attachButtonPlus-3IYelE,
  .form-3uUEen .attachButtonPlus-3IYelE {
    d: path("M7.5,18A5.5,5.5 0 0,1 2,12.5A5.5,5.5 0 0,1 7.5,7H18A4,4 0 0,1 22,11A4,4 0 0,1 18,15H9.5A2.5,2.5 0 0,1 7,12.5A2.5,2.5 0 0,1 9.5,10H17V11.5H9.5A1,1 0 0,0 8.5,12.5A1,1 0 0,0 9.5,13.5H18A2.5,2.5 0 0,0 20.5,11A2.5,2.5 0 0,0 18,8.5H7.5A4,4 0 0,0 3.5,12.5A4,4 0 0,0 7.5,16.5H17V18H7.5Z") !important; }
  .form-3gdLxP .typing-2J1mQU,
  .form-3uUEen .typing-2J1mQU {
    width: 100%;
    top: -24px;
    left: 0;
    background-color: var(--typing-color);
    transition: 200ms ease-in-out; }
    .form-3gdLxP .typing-2J1mQU .slowModeIcon-35Psjn,
    .form-3uUEen .typing-2J1mQU .slowModeIcon-35Psjn {
      margin-right: 8px; }
  .form-3gdLxP .button-f2h6uQ.lookBlank-21BCro,
  .form-3uUEen .button-f2h6uQ.lookBlank-21BCro {
    background-color: transparent !important; }

.applicationCommandEducation-1stoia {
  position: relative;
  left: unset;
  right: unset;
  margin-top: -11px;
  border-top: none; }

.wrapper-2SplAX {
  height: 44px;
  margin: 12px 0;
  padding: 0;
  background-color: var(--main-textarea-color);
  border: 1px solid var(--main-textarea-border);
  border-radius: var(--main-textarea-radius); }
  .wrapper-2SplAX .buttonContainer-KMz3Ex {
    margin-right: 4px; }

.fakeLink-2FvUR7 {
  color: hsl(var(--accent-hsl)); }

.characterCount-8yNPfb {
  margin-top: 24px; }

.root-3PVcjb {
  background-color: var(--attachment-color);
  border-radius: var(--card-radius-big); }

/* CHAT AREA -> SPAM FILTER */
.spamBanner-1auiob {
  display: grid;
  grid-template-columns: 1fr auto;
  margin: 12px 16px;
  padding: 4px 8px;
  background-color: var(--main-textarea-color);
  border: 1px solid var(--main-textarea-border);
  border-radius: 28px; }
  .spamBanner-1auiob .bannerTextContainer-TbC9W4 {
    margin: 0 8px 0 0; }
  .spamBanner-1auiob .actionButtons-2SAg-Q {
    width: auto;
    margin: 0; }

/*
 *
 *	THREADS
 *
 */
.container-3GP6AV {
  background-color: transparent; }
  .container-3GP6AV .header-3cSJjT {
    padding: 4px 16px;
    background-color: transparent;
    border-bottom: 1px solid var(--popout-header-border); }

.container-2rzKKA {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  transition: var(--default-time) var(--default-animation); }
  .container-2rzKKA:hover {
    background-color: var(--background-modifier-hover);
    border-color: var(--card-border-color); }

/* THREADS -> POPOUT THREAD */
.container-3XgAHv {
  background-color: var(--chat-color);
  border-radius: 16px 0 0 16px; }
  .container-3XgAHv .scrollerInner-2PPAp2 {
    padding-top: 36px; }

.channelTextArea-3TZH74 {
  background-color: transparent; }

.channelTextAreaInner-ITp5kW {
  max-height: 200px;
  background-color: var(--main-textarea-color);
  border-radius: var(--main-textarea-radius);
  border: 1px solid var(--main-textarea-border); }

/* THREADS -> POPOUT THREAD -> PERKS */
.perks-26lTSw {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .perks-26lTSw .perkRow-10K6XE {
    margin: 0;
    position: relative;
    border-bottom: none; }
    .perks-26lTSw .perkRow-10K6XE:after {
      position: absolute;
      content: " ";
      width: calc(100% - 56px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .perks-26lTSw .perkRow-10K6XE:last-of-type:after {
      display: none; }
  .perks-26lTSw .perkIconContainer-25jfLV {
    margin-left: 16px; }

/* THREADS -> CHAT AREA */
.chatHeaderBar-2fUORh {
  position: absolute;
  width: calc(100% - 32px);
  background-color: var(--typing-color);
  z-index: 2; }
  .chatHeaderBar-2fUORh .chatHeaderBarText-1yrbqv {
    font-weight: 500; }

.container-18GwIk {
  min-height: 200px;
  max-height: 80vh;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ;
  animation: top-pop-out 400ms var(--default-animation); }
  .container-18GwIk .header-3_zmOb {
    padding: 0 16px;
    background-color: transparent;
    border-bottom: 1px solid var(--popout-header-border); }
    .container-18GwIk .header-3_zmOb .tabBar-2WhZ9G {
      height: 100%; }
    .container-18GwIk .header-3_zmOb .createButton-oruGBs {
      --button-padding: 0 12px; }
  .container-18GwIk .container-2c4_8A {
    min-height: 200px;
    padding: 16px; }
  .container-18GwIk .activeThreadsList-c8qlqZ {
    padding-bottom: 16px; }
  .container-18GwIk .content-28mbXd {
    height: auto !important; }
  .container-18GwIk .container-2rzKKA {
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }
    .container-18GwIk .container-2rzKKA:hover {
      background-color: var(--card-color-hover); }
    .container-18GwIk .container-2rzKKA:last-of-type {
      margin-bottom: 0; }

body:active .container-18GwIk:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/* THREADS -> MORE ACTIVE THREADS */
.title-1yq5kT.size12-oc4dx4 {
  margin-top: -8px;
  padding: 12px; }
  .title-1yq5kT.size12-oc4dx4 + .more-2c3Z-T {
    margin-top: 0; }
  .title-1yq5kT.size12-oc4dx4 + .row-1qtctT {
    border-top: 1px solid var(--popout-header-border); }

.row-1qtctT {
  margin: 0; }

.more-2c3Z-T {
  padding: 8px 12px;
  border-top-color: var(--popout-header-border); }

/*
 *
 *	EVENTS
 *
 */
.eventCard-2ZL9GD {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

/*
 *
 *	USER STATUS
 *
 */
.layer-2aCOJ3[style*="left: 88px"] {
  left: 80px !important; }

.panels-3wFtMD {
  position: relative;
  margin: -12px 8px 8px;
  background-color: transparent; }
  .panels-3wFtMD:before {
    position: absolute;
    content: " ";
    width: calc(100% + 16px);
    height: 40px;
    top: -28px;
    left: -8px;
    background: linear-gradient(0deg, var(--main-color) 0%, transparent 50%);
    z-index: -1;
    pointer-events: none; }
  .panels-3wFtMD .container-1zzFcN .button-12Fmur,
  .panels-3wFtMD .container-6sXIoE .button-12Fmur,
  .panels-3wFtMD .listeningAlong-6YvYsc .button-12Fmur {
    background-color: transparent !important;
    position: relative; }
    .panels-3wFtMD .container-1zzFcN .button-12Fmur:after,
    .panels-3wFtMD .container-6sXIoE .button-12Fmur:after,
    .panels-3wFtMD .listeningAlong-6YvYsc .button-12Fmur:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .panels-3wFtMD .container-1zzFcN .button-12Fmur:hover:after,
    .panels-3wFtMD .container-6sXIoE .button-12Fmur:hover:after,
    .panels-3wFtMD .listeningAlong-6YvYsc .button-12Fmur:hover:after {
      opacity: 1;
      transform: scale(1.1);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .panels-3wFtMD .container-1zzFcN .button-12Fmur:active:after,
    .panels-3wFtMD .container-6sXIoE .button-12Fmur:active:after,
    .panels-3wFtMD .listeningAlong-6YvYsc .button-12Fmur:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
  .panels-3wFtMD .container-1zzFcN .button-1EGGcP {
    --button-padding: 0 12px; }
  .panels-3wFtMD .container-1zzFcN,
  .panels-3wFtMD .container-6sXIoE,
  .panels-3wFtMD .panel-2ZFCRb,
  .panels-3wFtMD .listeningAlong-6YvYsc {
    margin-bottom: 8px;
    background-color: var(--sidebar-panel-color);
    border-radius: var(--card-radius-big); }
  .panels-3wFtMD .container-6sXIoE,
  .panels-3wFtMD .container-1zzFcN,
  .panels-3wFtMD .activityPanel-9icbyU,
  .panels-3wFtMD .listeningAlong-6YvYsc {
    border-bottom: none; }
  .panels-3wFtMD .container-6sXIoE.withTimeline-824fT_ .bar-g2ZMIm {
    background-color: var(--slider-color); }
  .panels-3wFtMD .container-6sXIoE.withTimeline-824fT_ .barText-lmqc5O {
    padding: 0 4px; }
  .panels-3wFtMD .container-6sXIoE.maximized-vv2Wr0 .coverWrapper-YAplwJ {
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0; }
  .panels-3wFtMD .container-6sXIoE .interpret-F93iqP {
    color: var(--text-normal); }
  .panels-3wFtMD .container-YkUktl {
    height: 52px;
    background-color: var(--status-picker-color);
    border-radius: var(--card-radius-big);
    box-sizing: border-box;
    /* USER STATUS -> ICONS */ }
    .panels-3wFtMD .container-YkUktl .button-12Fmur {
      background-color: transparent !important;
      border-radius: 50%;
      position: relative;
      color: var(--interactive-normal) !important; }
      .panels-3wFtMD .container-YkUktl .button-12Fmur:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      .panels-3wFtMD .container-YkUktl .button-12Fmur:hover:after {
        opacity: 1;
        transform: scale(1.1);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      .panels-3wFtMD .container-YkUktl .button-12Fmur:active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
      .panels-3wFtMD .container-YkUktl .button-12Fmur:hover {
        color: var(--interactive-hover) !important; }
      .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path {
        /* USER STATUS -> ICONS -> DISABLE GAME ACTIVITY */
        /* USER STATUS -> ICONS -> ENABLE GAME ACTIVITY */
        /* USER STATUS -> ICONS -> MUTE */
        /* USER STATUS -> ICONS -> UNMUTE */
        /* USER STATUS -> ICONS -> DEAFEN */
        /* USER STATUS -> ICONS -> UNDEAFEN */
        /* USER STATUS -> ICONS -> SETTINGS */ }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M 5.7066445,4.9022473 H 18.293275 c 1.595895,0 2.92046,1.2333283 3.034163,2.8251676 l 0.667683,9.3475611 c 0.0743,1.040197 -0.708715,1.943677 -1.748914,2.017977 -0.04477,0.0032 -0.08964,0.0048 -0.134531,0.0048 -1.191828,0 -2.230714,-0.811138 -2.519775,-1.96738 l -0.522119,-2.08848 H 6.930137 l -0.5221194,2.088478 c -0.2890608,1.156242 -1.3279463,1.96738 -2.5197742,1.96738 -1.0428481,0 -1.8882436,-0.845396 -1.8882436,-1.888243 0,-0.04488 0.0016,-0.08976 0.0048,-0.134532 L 2.6724812,7.7274149 C 2.7861841,6.1355756 4.1107494,4.9022473 5.7066445,4.9022473 Z m 8.8282265,5.0698223 c 0.839995,0 1.520947,-0.680951 1.520947,-1.5209465 0,-0.8399957 -0.680952,-1.5209468 -1.520947,-1.5209468 -0.839996,0 -1.520947,0.6809511 -1.520947,1.5209468 0,0.8399955 0.680951,1.5209465 1.520947,1.5209465 z m 4.055858,3.0418944 c 0.839996,0 1.520947,-0.680952 1.520947,-1.520947 0,-0.839995 -0.680951,-1.5209474 -1.520947,-1.5209474 -0.839996,0 -1.520947,0.6809524 -1.520947,1.5209474 0,0.839995 0.680951,1.520947 1.520947,1.520947 z M 5.9161725,8.9581056 H 3.8882434 v 2.0279294 h 2.0279291 v 2.027929 H 7.9441016 V 10.986035 H 9.9720304 V 8.9581056 H 7.9441016 V 6.9301763 H 5.9161725 Z"] {
          d: path("M7.97,16L5,19C4.67,19.3 4.23,19.5 3.75,19.5A1.75,1.75 0 0,1 2,17.75V17.5L3,10.12C3.21,7.81 5.14,6 7.5,6H16.5C18.86,6 20.79,7.81 21,10.12L22,17.5V17.75A1.75,1.75 0 0,1 20.25,19.5C19.77,19.5 19.33,19.3 19,19L16.03,16H7.97M7,8V10H5V11H7V13H8V11H10V10H8V8H7M16.5,8A0.75,0.75 0 0,0 15.75,8.75A0.75,0.75 0 0,0 16.5,9.5A0.75,0.75 0 0,0 17.25,8.75A0.75,0.75 0 0,0 16.5,8M14.75,9.75A0.75,0.75 0 0,0 14,10.5A0.75,0.75 0 0,0 14.75,11.25A0.75,0.75 0 0,0 15.5,10.5A0.75,0.75 0 0,0 14.75,9.75M18.25,9.75A0.75,0.75 0 0,0 17.5,10.5A0.75,0.75 0 0,0 18.25,11.25A0.75,0.75 0 0,0 19,10.5A0.75,0.75 0 0,0 18.25,9.75M16.5,11.5A0.75,0.75 0 0,0 15.75,12.25A0.75,0.75 0 0,0 16.5,13A0.75,0.75 0 0,0 17.25,12.25A0.75,0.75 0 0,0 16.5,11.5Z") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="m 5.707493,4.903746 c -1.5957556,0 -2.921198,1.232272 -3.0348909,2.823972 l -0.6679103,9.346058 c -0.0032,0.04477 -0.00469,0.09105 -0.00469,0.135925 0,0.286145 0.068875,0.553783 0.1827966,0.796805 L 7.1745522,13.014755 H 5.9160685 v -2.02951 H 3.8889021 V 8.958078 H 5.9160685 V 6.930913 H 7.943235 v 2.027165 h 2.0295102 v 1.258484 L 15.285561,4.903746 Z m 15.366625,1.832652 -4.813642,4.813642 -3.491882,3.491882 h 4.300405 l 0.522611,2.088099 c 0.289036,1.156141 1.327587,1.966233 2.519311,1.966233 0.04489,0 0.08882,-0.0014 0.133582,-0.0047 1.040108,-0.0743 1.824922,-0.977685 1.750628,-2.01779 l -0.66791,-9.346079 c -0.02519,-0.352659 -0.11926,-0.683371 -0.253103,-0.99132 z m -2.484157,3.236436 c 0.839921,0 1.52096,0.681039 1.52096,1.52096 0,0.839923 -0.681039,1.520961 -1.52096,1.520961 -0.839923,0 -1.520962,-0.681038 -1.520962,-1.520961 0,-0.839921 0.681039,-1.52096 1.520962,-1.52096 z M 7.943235,10.985245 v 1.260827 l 1.2608277,-1.260827 z"] {
          d: path("M2,5.27L3.28,4L20,20.72L18.73,22L12.73,16H7.97L5,19C4.67,19.3 4.23,19.5 3.75,19.5A1.75,1.75 0 0,1 2,17.75V17.5L3,10.12C3.1,9.09 3.53,8.17 4.19,7.46L2,5.27M5,10V11H7V13H8V11.27L6.73,10H5M16.5,6C18.86,6 20.79,7.81 21,10.12L22,17.5V17.75C22,18.41 21.64,19 21.1,19.28L7.82,6H16.5M16.5,8A0.75,0.75 0 0,0 15.75,8.75A0.75,0.75 0 0,0 16.5,9.5A0.75,0.75 0 0,0 17.25,8.75A0.75,0.75 0 0,0 16.5,8M14.75,9.75A0.75,0.75 0 0,0 14,10.5A0.75,0.75 0 0,0 14.75,11.25A0.75,0.75 0 0,0 15.5,10.5A0.75,0.75 0 0,0 14.75,9.75M18.25,9.75A0.75,0.75 0 0,0 17.5,10.5A0.75,0.75 0 0,0 18.25,11.25A0.75,0.75 0 0,0 19,10.5A0.75,0.75 0 0,0 18.25,9.75M16.5,11.5A0.75,0.75 0 0,0 15.75,12.25A0.75,0.75 0 0,0 16.5,13A0.75,0.75 0 0,0 17.25,12.25A0.75,0.75 0 0,0 16.5,11.5Z") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="m 5.707493,4.903746 c -1.5957556,0 -2.921198,1.232272 -3.0348909,2.823972 l -0.6679103,9.346058 c -0.0032,0.04477 -0.00469,0.09105 -0.00469,0.135925 0,0.286145 0.068875,0.553783 0.1827966,0.796805 L 7.1745522,13.014755 H 5.9160685 v -2.02951 H 3.8889021 V 8.958078 H 5.9160685 V 6.930913 H 7.943235 v 2.027165 h 2.0295102 v 1.258484 L 15.285561,4.903746 Z m 15.366625,1.832652 -4.813642,4.813642 -3.491882,3.491882 h 4.300405 l 0.522611,2.088099 c 0.289036,1.156141 1.327587,1.966233 2.519311,1.966233 0.04489,0 0.08882,-0.0014 0.133582,-0.0047 1.040108,-0.0743 1.824922,-0.977685 1.750628,-2.01779 l -0.66791,-9.346079 c -0.02519,-0.352659 -0.11926,-0.683371 -0.253103,-0.99132 z m -2.484157,3.236436 c 0.839921,0 1.52096,0.681039 1.52096,1.52096 0,0.839923 -0.681039,1.520961 -1.52096,1.520961 -0.839923,0 -1.520962,-0.681038 -1.520962,-1.520961 0,-0.839921 0.681039,-1.52096 1.520962,-1.52096 z M 7.943235,10.985245 v 1.260827 l 1.2608277,-1.260827 z"] ~ path {
          display: none; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"] {
          d: path("M12 14c1.66 0 3-1.34 3-3V5c0-1.66-1.34-3-3-3S9 3.34 9 5v6c0 1.66 1.34 3 3 3zm-1-9c0-.55.45-1 1-1s1 .45 1 1v6c0 .55-.45 1-1 1s-1-.45-1-1V5zm6 6c0 2.76-2.24 5-5 5s-5-2.24-5-5H5c0 3.53 2.61 6.43 6 6.92V21h2v-3.08c3.39-.49 6-3.39 6-6.92h-2z") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"] ~ path {
          display: none; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] {
          d: path("M10.8 4.9c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2l-.01 3.91L15 10.6V5c0-1.66-1.34-3-3-3-1.54 0-2.79 1.16-2.96 2.65l1.76 1.76V4.9zM19 11h-1.7c0 .58-.1 1.13-.27 1.64l1.27 1.27c.44-.88.7-1.87.7-2.91zM4.41 2.86L3 4.27l6 6V11c0 1.66 1.34 3 3 3 .23 0 .44-.03.65-.08l1.66 1.66c-.71.33-1.5.52-2.31.52-2.76 0-5.3-2.1-5.3-5.1H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c.91-.13 1.77-.45 2.55-.9l4.2 4.2 1.41-1.41L4.41 2.86") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] ~ path {
          display: none; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M12 2.00305C6.486 2.00305 2 6.48805 2 12.0031V20.0031C2 21.1071 2.895 22.0031 4 22.0031H6C7.104 22.0031 8 21.1071 8 20.0031V17.0031C8 15.8991 7.104 15.0031 6 15.0031H4V12.0031C4 7.59105 7.589 4.00305 12 4.00305C16.411 4.00305 20 7.59105 20 12.0031V15.0031H18C16.896 15.0031 16 15.8991 16 17.0031V20.0031C16 21.1071 16.896 22.0031 18 22.0031H20C21.104 22.0031 22 21.1071 22 20.0031V12.0031C22 6.48805 17.514 2.00305 12 2.00305Z"] {
          d: path("M3 9v6h4l5 5V4L7 9H3zm7-.17v6.34L7.83 13H5v-2h2.83L10 8.83zM16.5 12c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77 0-4.28-2.99-7.86-7-8.77z") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] {
          d: path("M4.34 2.93L2.93 4.34 7.29 8.7 7 9H3v6h4l5 5v-6.59l4.18 4.18c-.65.49-1.38.88-2.18 1.11v2.06c1.34-.3 2.57-.92 3.61-1.75l2.05 2.05 1.41-1.41L4.34 2.93zM10 15.17L7.83 13H5v-2h2.83l.88-.88L10 11.41v3.76zM19 12c0 .82-.15 1.61-.41 2.34l1.53 1.53c.56-1.17.88-2.48.88-3.87 0-4.28-2.99-7.86-7-8.77v2.06c2.89.86 5 3.54 5 6.71zm-7-8l-1.88 1.88L12 7.76zm4.5 8c0-1.77-1.02-3.29-2.5-4.03v1.79l2.48 2.48c.01-.08.02-.16.02-.24z") !important; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] ~ path {
          display: none; }
        .panels-3wFtMD .container-YkUktl .button-12Fmur .contents-3ca1mk path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
          d: path("M19.43 12.98c.04-.32.07-.64.07-.98 0-.34-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.09-.16-.26-.25-.44-.25-.06 0-.12.01-.17.03l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.06-.02-.12-.03-.18-.03-.17 0-.34.09-.43.25l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98 0 .33.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.09.16.26.25.44.25.06 0 .12-.01.17-.03l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.06.02.12.03.18.03.17 0 .34-.09.43-.25l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zm-1.98-1.71c.04.31.05.52.05.73 0 .21-.02.43-.05.73l-.14 1.13.89.7 1.08.84-.7 1.21-1.27-.51-1.04-.42-.9.68c-.43.32-.84.56-1.25.73l-1.06.43-.16 1.13-.2 1.35h-1.4l-.19-1.35-.16-1.13-1.06-.43c-.43-.18-.83-.41-1.23-.71l-.91-.7-1.06.43-1.27.51-.7-1.21 1.08-.84.89-.7-.14-1.13c-.03-.31-.05-.54-.05-.74s.02-.43.05-.73l.14-1.13-.89-.7-1.08-.84.7-1.21 1.27.51 1.04.42.9-.68c.43-.32.84-.56 1.25-.73l1.06-.43.16-1.13.2-1.35h1.39l.19 1.35.16 1.13 1.06.43c.43.18.83.41 1.23.71l.91.7 1.06-.43 1.27-.51.7 1.21-1.07.85-.89.7.14 1.13zM12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z") !important; }

.container-JMJRDf {
  width: calc(100% - 16px);
  margin: 8px 8px 0;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ;
  overflow: hidden; }
  .container-JMJRDf .content-PlPs77 {
    padding: 0 0 8px; }
  .container-JMJRDf .video-31SuuY {
    border-radius: 0; }

/* USER STATUS -> STATUS PICKER */
.layer-2aCOJ3[style*="left: 80px; bottom: 6"] {
  top: initial !important;
  left: 82px !important;
  bottom: 78px !important; }

.menu-1QACrS#status-picker {
  width: 224px;
  min-height: 68px;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius-big);
  box-shadow: var(--shadow-3dp);
  animation: show-status var(--default-time) var(--default-animation);
  overflow: hidden; }
  .menu-1QACrS#status-picker .scroller-1bVxF5 {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    padding: 0; }
    .menu-1QACrS#status-picker .scroller-1bVxF5::-webkit-scrollbar {
      width: 0 !important; }
  .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status) {
    position: relative;
    width: unset;
    height: 68px;
    margin: 0;
    border-radius: 0;
    font-size: 0;
    overflow: hidden;
    animation: status 300ms var(--default-animation) backwards; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status):active {
      background-color: transparent !important; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-online {
      animation-delay: 100ms; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-online .statusItem-2hiCNB {
        background-color: #43b581; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-online .status-2DiCMd {
        background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/check_dark.svg); }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-idle {
      animation-delay: 140ms; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-idle .statusItem-2hiCNB {
        background-color: #faa61a; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-idle .status-2DiCMd {
        background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/alarm_dark.svg); }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-dnd {
      animation-delay: 180ms; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-dnd .statusItem-2hiCNB {
        background-color: #f04747; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-dnd .status-2DiCMd {
        background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/remove_dark.svg); }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-invisible {
      animation-delay: 220ms; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-invisible .statusItem-2hiCNB {
        background-color: #747f8d; }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status)#status-picker-invisible .status-2DiCMd {
        background-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/visibility_off_dark.svg); }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status) .statusItem-2hiCNB {
      position: absolute;
      display: block;
      width: 34px;
      height: 34px;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      margin: auto;
      padding: 0;
      border-radius: var(--avatar-radius);
      transition: var(--default-time) var(--default-animation); }
      .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status) .statusItem-2hiCNB .description-3Cwkxk {
        display: none; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status):hover .statusItem-2hiCNB {
      transform: scale(1.425); }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status):hover .status-2DiCMd {
      opacity: 0.65; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status).focused-3qFvc8 {
      background-color: transparent; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status) .icon-Lz4Y-_ {
      display: none; }
    .menu-1QACrS#status-picker .item-1OdjEX:not(#status-picker-custom-status) .status-2DiCMd {
      display: block;
      position: absolute;
      width: 20px;
      height: 20px;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      margin: auto;
      background-size: 100%;
      background-position: center;
      background-repeat: no-repeat;
      opacity: 0;
      transition: var(--default-time) var(--default-animation);
      font-size: 0; }
  .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status, .menu-1QACrS#status-picker .item-1OdjEX#status-picker-switch-account {
    grid-column: 1/6;
    margin-top: 0;
    margin-bottom: 0;
    background-color: transparent;
    border-radius: 0;
    border-top: 1px solid var(--popout-header-border);
    transition: var(--default-time) var(--default-animation) background-color; }
    .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status.focused-3qFvc8, .menu-1QACrS#status-picker .item-1OdjEX#status-picker-switch-account.focused-3qFvc8 {
      background-color: var(--menu-item-hover);
      color: var(--interactive-normal); }
    .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .statusItem-2hiCNB, .menu-1QACrS#status-picker .item-1OdjEX#status-picker-switch-account .statusItem-2hiCNB {
      display: grid;
      position: unset;
      min-height: 28px;
      padding: 4px 12px;
      grid-template-rows: 28px 1fr; }
  .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .statusItem-2hiCNB {
    grid-template-columns: 28px 1fr; }
    .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .statusItem-2hiCNB.customStatusItem-1qQzss {
      grid-template-columns: 1fr 32px; }
    .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .statusItem-2hiCNB .customEmoji-1nCP1t {
      margin-left: 0; }
  .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .clearStatusButton-GXA1lF {
    width: 32px !important;
    height: 32px !important; }
  .menu-1QACrS#status-picker .item-1OdjEX#status-picker-custom-status .clearStatusIcon-9SeHGZ {
    margin-left: 0; }
  .menu-1QACrS#status-picker .item-1OdjEX#status-picker-switch-account .statusItem-2hiCNB {
    grid-template-columns: 28px 1fr; }
  .menu-1QACrS#status-picker .submenuContainer-3EVTeH {
    width: auto;
    height: auto;
    grid-column: 1/6; }
    .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account {
      height: 36px;
      padding: 0;
      font-size: 14px;
      animation: none; }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account:hover .statusItem-2hiCNB {
        transform: none; }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account.focused-3qFvc8 {
        background-color: var(--menu-item-hover); }
        .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account.focused-3qFvc8 .switchAccountsItem-1neGS_ path {
          fill: currentColor !important; }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account .statusItem-2hiCNB {
        width: auto;
        height: auto; }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account .status-2DiCMd {
        display: unset;
        position: unset;
        width: unset;
        height: unset;
        margin: unset;
        font-size: inherit;
        opacity: 1 !important; }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account .betaTag-3pnIxA {
        position: absolute;
        top: 0;
        bottom: 0;
        right: 24px;
        margin: auto 0;
        background-color: hsl(var(--accent-hsl)) !important;
        color: var(--accent-text-color); }
      .menu-1QACrS#status-picker .submenuContainer-3EVTeH #status-picker-switch-account .iconContainer-1-SsTR {
        margin-right: 8px; }
  .menu-1QACrS#status-picker .submenuContainer-3EVTeH {
    grid-column: 1/6; }
    .menu-1QACrS#status-picker .submenuContainer-3EVTeH .layer-2aCOJ3 {
      transform: translateX(-4px); }
    .menu-1QACrS#status-picker .submenuContainer-3EVTeH .scroller-1bVxF5 {
      display: block; }
  .menu-1QACrS#status-picker .separator-1So4YB {
    display: none; }
  .menu-1QACrS#status-picker .layer-2aCOJ3[style*="left: 316px"] {
    left: 312px !important; }
  .menu-1QACrS#status-picker .submenu-1apzyU {
    padding: 8px 0;
    background-color: var(--popout-color);
    overflow: hidden;
    animation: opacity 100ms ease, open-context-menu 300ms var(--default-animation);
    transform-origin: top; }
  .menu-1QACrS#status-picker [aria-activedescendant*="status-picker-switch-account"] .item-1OdjEX {
    height: auto !important;
    padding: 9px 12px !important;
    font-size: 14px !important;
    line-height: 18px;
    transition: var(--default-time) var(--default-animation) background-color;
    animation: none !important; }
    .menu-1QACrS#status-picker [aria-activedescendant*="status-picker-switch-account"] .item-1OdjEX:hover {
      background-color: var(--menu-item-hover) !important; }
    .menu-1QACrS#status-picker [aria-activedescendant*="status-picker-switch-account"] .item-1OdjEX#status-picker-switch-account--manage-accounts {
      position: relative;
      margin-top: 16px;
      overflow: visible; }
      .menu-1QACrS#status-picker [aria-activedescendant*="status-picker-switch-account"] .item-1OdjEX#status-picker-switch-account--manage-accounts:after {
        position: absolute;
        content: " ";
        width: 100%;
        height: 1px;
        top: -8px;
        left: 0;
        background-color: var(--popout-header-border); }

body:active .menu-1QACrS#status-picker:not(:active) {
  opacity: 0;
  transform: translateY(15%);
  transition: 200ms var(--default-animation) !important; }

.emojiButtonContainer-1cdx-p {
  margin: 0;
  z-index: 2; }
  .emojiButtonContainer-1cdx-p + .inputWrapper-1YNMmM .input-2g-os5 {
    padding-left: 32px;
    padding-right: 36px; }

.formDivider-6eSaij {
  margin-top: 16px; }

.menu-1QACrS#activity-popout {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--shadow-3dp); }
  .menu-1QACrS#activity-popout .scroller-1bVxF5 {
    padding: 8px 0;
    padding-right: 0 !important; }
    .menu-1QACrS#activity-popout .scroller-1bVxF5::-webkit-scrollbar {
      width: 0 !important; }
    .menu-1QACrS#activity-popout .scroller-1bVxF5 .activityItem-3_4A5- {
      margin: 0;
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .menu-1QACrS#activity-popout .scroller-1bVxF5 .activityItem-3_4A5-:hover {
        background-color: var(--menu-item-hover); }
    .menu-1QACrS#activity-popout .scroller-1bVxF5 .separator-1So4YB {
      margin: 8px 0;
      border-bottom-color: var(--separator-color); }
  .menu-1QACrS#activity-popout .betaTag-3mHD-Y {
    padding: 0 6px;
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color);
    font-size: 13px;
    text-transform: none; }

/*
 *
 *	VOICE CONNECTED
 *
 */
.avatarSpeaking-2pCGrZ,
.avatarSpeaking-33RRJU,
.speaking-3K28iH,
.border-2Vy6FN.speaking-7QZEkv {
  box-shadow: inset 0 0 0 2px hsl(var(--accent-hsl)), inset 0 0 0 3px var(--background-secondary); }

.border-2Vy6FN {
  border-radius: var(--card-radius-big); }

.rtcConnectionStatusConnected-1c73OK {
  background-color: transparent !important;
  color: var(--success-color) !important; }

/* VOICE CONNECTED -> SHOW VOICE USERS */
.avatarIconOverlay-ZVSfbr {
  /* VOICE CONNECTED -> SHOW VOICE USERS -> MUTED */
  /* VOICE CONNECTED -> SHOW VOICE USERS -> DEAFENED */ }
  .avatarIconOverlay-ZVSfbr path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] {
    d: path("M10.8 4.9c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2l-.01 3.91L15 10.6V5c0-1.66-1.34-3-3-3-1.54 0-2.79 1.16-2.96 2.65l1.76 1.76V4.9zM19 11h-1.7c0 .58-.1 1.13-.27 1.64l1.27 1.27c.44-.88.7-1.87.7-2.91zM4.41 2.86L3 4.27l6 6V11c0 1.66 1.34 3 3 3 .23 0 .44-.03.65-.08l1.66 1.66c-.71.33-1.5.52-2.31.52-2.76 0-5.3-2.1-5.3-5.1H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c.91-.13 1.77-.45 2.55-.9l4.2 4.2 1.41-1.41L4.41 2.86z"); }
  .avatarIconOverlay-ZVSfbr path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"] ~ path {
    display: none; }
  .avatarIconOverlay-ZVSfbr path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] {
    d: path("M4.34 2.93L2.93 4.34 7.29 8.7 7 9H3v6h4l5 5v-6.59l4.18 4.18c-.65.49-1.38.88-2.18 1.11v2.06c1.34-.3 2.57-.92 3.61-1.75l2.05 2.05 1.41-1.41L4.34 2.93zM10 15.17L7.83 13H5v-2h2.83l.88-.88L10 11.41v3.76zM19 12c0 .82-.15 1.61-.41 2.34l1.53 1.53c.56-1.17.88-2.48.88-3.87 0-4.28-2.99-7.86-7-8.77v2.06c2.89.86 5 3.54 5 6.71zm-7-8l-1.88 1.88L12 7.76zm4.5 8c0-1.77-1.02-3.29-2.5-4.03v1.79l2.48 2.48c.01-.08.02-.16.02-.24z"); }
  .avatarIconOverlay-ZVSfbr path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] ~ path {
    display: none; }

/* VOICE CONNECTED -> RTC CONNECTION */
.container-1ILvLB {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .container-1ILvLB .header-2C89wJ,
  .container-1ILvLB section {
    background-color: transparent !important; }
  .container-1ILvLB .header-2C89wJ {
    border-bottom: 1px solid var(--popout-header-border);
    text-transform: none;
    justify-content: left; }

/* VOICE CONNECTED -> NOISE SUPPRESSION */
.noiseCancellationPopout-2-e5Xz {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .noiseCancellationPopout-2-e5Xz .micTestButton-2Ct97k {
    width: auto; }

/* VOICE CONNECTED -> BUTTONS */
.actionButtons-2vEOUh .button-f2h6uQ .buttonIcon-2Zsrs2 path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
  d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z"); }
.actionButtons-2vEOUh .button-f2h6uQ .buttonIcon-2Zsrs2 path[d="M2 4.5C2 3.397 2.897 2.5 4 2.5H20C21.103 2.5 22 3.397 22 4.5V15.5C22 16.604 21.103 17.5 20 17.5H13V19.5H17V21.5H7V19.5H11V17.5H4C2.897 17.5 2 16.604 2 15.5V4.5ZM13.2 14.3375V11.6C9.864 11.6 7.668 12.6625 6 15C6.672 11.6625 8.532 8.3375 13.2 7.6625V5L18 9.6625L13.2 14.3375Z"] {
  d: path("M20 18c1.1 0 1.99-.9 1.99-2L22 6c0-1.11-.9-2-2-2H4c-1.11 0-2 .89-2 2v10c0 1.1.89 2 2 2H0v2h24v-2h-4zM4 16V6h16v10.01L4 16zm9-6.87c-3.89.54-5.44 3.2-6 5.87 1.39-1.87 3.22-2.72 6-2.72v2.19l4-3.74L13 7v2.13z"); }

/*
 *
 *	STAGE CHANNEL
 *
 */
.content-3uvxCf {
  margin: 16px; }

.container-a_NK-C {
  padding: 4px;
  background-color: var(--menu-item-select);
  border-radius: 32px; }
  .container-a_NK-C .button-f2h6uQ {
    height: unset !important;
    max-height: unset;
    padding: 16px !important;
    box-shadow: none !important;
    transition: var(--default-time) var(--default-animation) !important; }

.raiseHandButton-1TZpXJ {
  margin: 0;
  background-color: transparent !important; }
  .raiseHandButton-1TZpXJ:not([disabled]):hover {
    background-color: rgba(var(--button-link-color), 0.1) !important; }

.leaveQuietlyButton-3Vhswc {
  height: unset !important;
  max-height: unset;
  padding: 16px !important;
  border-radius: 28px !important; }
  .leaveQuietlyButton-3Vhswc:after {
    display: none; }

/*
 *
 *	SCREEN SHARE
 *
 */
.modalSize-22vimZ .segmentContainer-2dq0ta {
  border-bottom: 1px solid var(--card-border-color); }
  .modalSize-22vimZ .segmentContainer-2dq0ta .divider-2_Eu47 {
    display: none; }
  .modalSize-22vimZ .segmentContainer-2dq0ta .segmentControlOption-2LyihQ.selected-2xa993 {
    border-bottom: none !important;
    position: relative;
    background-color: transparent !important; }
    .modalSize-22vimZ .segmentContainer-2dq0ta .segmentControlOption-2LyihQ.selected-2xa993:after {
      position: absolute;
      content: " ";
      width: 100%;
      height: 3px;
      left: 0;
      right: 0;
      bottom: 0;
      margin: 0 auto;
      background: var(--tab-border-color);
      border-radius: 3px 3px 0 0;
      transition: var(--default-time) ease all; }
.modalSize-22vimZ .tile-38DNjt:hover .sourceThumbnail-3n4cjJ {
  box-shadow: inset 0 0 0 2px hsl(var(--accent-hsl)); }
.modalSize-22vimZ .card-1SdQ2- {
  padding: 6px 4px 6px 8px;
  background-color: var(--input-color);
  border-radius: 22px;
  border: none; }
  .modalSize-22vimZ .card-1SdQ2- .changeButton-3QdaoH, .modalSize-22vimZ .card-1SdQ2- .changeButton-3QdaoH:after {
    border-radius: 18px !important; }
.modalSize-22vimZ .group-1_ptLP {
  border-radius: 16px;
  border: 1px solid var(--card-border-color);
  overflow: hidden; }
  .modalSize-22vimZ .group-1_ptLP .selectorButton-3sW6Qm {
    border: none !important;
    transition: var(--default-time) var(--default-animation) background-color; }
    .modalSize-22vimZ .group-1_ptLP .selectorButton-3sW6Qm:hover {
      background-color: var(--menu-item-hover); }
    .modalSize-22vimZ .group-1_ptLP .selectorButton-3sW6Qm.selectorButtonSelected-3Z0WNU {
      background-color: var(--menu-item-select); }
    .modalSize-22vimZ .group-1_ptLP .selectorButton-3sW6Qm .selectorText-2PqieX {
      color: var(--menu-item-text-color); }

/*
 *
 *	PICTURE IN PICTURE
 *
 */
.elevationHigh-3KUiqj,
.pictureInPictureWindow-3ms5Zy {
  border-radius: var(--popout-radius-big);
  box-shadow: var(--shadow-3dp) !important; }

.pictureInPictureVideo-2puO2Q {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ;
  /* PiP -> CONTROLS */ }
  .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 {
    /* PiP -> CONTROLS -> VIEWERS */ }
    .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 .controlIcon-10O-4h path {
      /* PiP -> CONTROLS -> TURN ON CAMERA */
      /* PiP -> CONTROLS -> SETTINGS */
      /* PiP -> CONTROLS -> STOP SCREEN SHARE */ }
      .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 .controlIcon-10O-4h path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
        d: path("M15 8v8H5V8h10m1-2H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1z"); }
      .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 .controlIcon-10O-4h path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
        d: path("M19.43 12.98c.04-.32.07-.64.07-.98 0-.34-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.09-.16-.26-.25-.44-.25-.06 0-.12.01-.17.03l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.06-.02-.12-.03-.18-.03-.17 0-.34.09-.43.25l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98 0 .33.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.09.16.26.25.44.25.06 0 .12-.01.17-.03l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.06.02.12.03.18.03.17 0 .34-.09.43-.25l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zm-1.98-1.71c.04.31.05.52.05.73 0 .21-.02.43-.05.73l-.14 1.13.89.7 1.08.84-.7 1.21-1.27-.51-1.04-.42-.9.68c-.43.32-.84.56-1.25.73l-1.06.43-.16 1.13-.2 1.35h-1.4l-.19-1.35-.16-1.13-1.06-.43c-.43-.18-.83-.41-1.23-.71l-.91-.7-1.06.43-1.27.51-.7-1.21 1.08-.84.89-.7-.14-1.13c-.03-.31-.05-.54-.05-.74s.02-.43.05-.73l.14-1.13-.89-.7-1.08-.84.7-1.21 1.27.51 1.04.42.9-.68c.43-.32.84-.56 1.25-.73l1.06-.43.16-1.13.2-1.35h1.39l.19 1.35.16 1.13 1.06.43c.43.18.83.41 1.23.71l.91.7 1.06-.43 1.27-.51.7 1.21-1.07.85-.89.7.14 1.13zM12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"); }
      .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 .controlIcon-10O-4h path[d="M4 2.5C2.897 2.5 2 3.397 2 4.5V15.5C2 16.604 2.897 17.5 4 17.5H11V19.5H7V21.5H17V19.5H13V17.5H20C21.103 17.5 22 16.604 22 15.5V4.5C22 3.397 21.103 2.5 20 2.5H4ZM14.5483 6L16 7.45174L13.4466 9.99485L16 12.5483L14.5483 14L12.0051 11.4466L9.45174 14L8 12.5483L10.5534 9.99485L8 7.45174L9.45174 6L12.0051 8.55341L14.5483 6Z"] {
        d: path("M21.79 18l2 2H24v-2h-2.21zM1.11 2.98l1.55 1.56c-.41.37-.66.89-.66 1.48V16c0 1.1.9 2 2.01 2H0v2h18.13l2.71 2.71 1.41-1.41L2.52 1.57 1.11 2.98zM4 6.02h.13l4.95 4.93C7.94 12.07 7.31 13.52 7 15c.96-1.29 2.13-2.08 3.67-2.46l3.46 3.48H4v-10zm16 0v10.19l1.3 1.3c.42-.37.7-.89.7-1.49v-10c0-1.11-.9-2-2-2H7.8l2 2H20zm-7.07 3.13l2.79 2.78 1.28-1.2L13 7v2.13l-.07.02z"); }
    .pictureInPictureVideo-2puO2Q .videoControls-e2Ogs3 .viewersIcon-F76mss path {
      d: path("M12 6.5c3.79 0 7.17 2.13 8.82 5.5-1.65 3.37-5.02 5.5-8.82 5.5S4.83 15.37 3.18 12C4.83 8.63 8.21 6.5 12 6.5m0-2C7 4.5 2.73 7.61 1 12c1.73 4.39 6 7.5 11 7.5s9.27-3.11 11-7.5c-1.73-4.39-6-7.5-11-7.5zm0 5c1.38 0 2.5 1.12 2.5 2.5s-1.12 2.5-2.5 2.5-2.5-1.12-2.5-2.5 1.12-2.5 2.5-2.5m0-2c-2.48 0-4.5 2.02-4.5 4.5s2.02 4.5 4.5 4.5 4.5-2.02 4.5-4.5-2.02-4.5-4.5-4.5z"); }

/*
 *
 *	USER SETTINGS
 *
 */
.layer-86YKbF,
.standardSidebarView-E9Pc3j {
  background-color: transparent; }

.sidebarRegionScroller-FXiQOh {
  background-color: var(--main-alt); }

.contentRegion-3HkfJJ {
  background-color: var(--main-color);
  border-top-left-radius: var(--card-radius-big); }
  .contentRegion-3HkfJJ .contentRegionScroller-2_GT_N {
    background-color: transparent; }

.h2-1EaYVL {
  text-transform: none;
  font-weight: 500; }

.divider-3LgWDL {
  border-top-color: var(--card-border-color); }

.layer-86YKbF.animating {
  pointer-events: initial !important;
  will-change: transform, opacity; }

[class*="theme-"] .standardSidebarView-E9Pc3j {
  backface-visibility: hidden; }

.layer-86YKbF {
  transform: none !important;
  transition: 300ms var(--default-animation) all;
  backface-visibility: hidden; }

.layer-86YKbF.animating-1rIrGV {
  transform: none !important; }

.layer-86YKbF.stop-animations:first-of-type {
  transform: scale(0.95) !important;
  opacity: 0 !important; }

.layer-86YKbF + .layer-86YKbF {
  transform: scale(1.1) !important;
  opacity: 0 !important;
  pointer-events: none !important;
  transition: 300ms var(--default-animation) all, 150ms ease opacity; }

.layer-86YKbF.stop-animations ~ .layer-86YKbF {
  pointer-events: initial !important;
  transform: none !important;
  opacity: 1 !important;
  animation: opensettings 300ms var(--default-animation); }

@keyframes opensettings {
  0% {
    transform: scale(1.1);
    opacity: 0; } }
.closeButton-PCZcma {
  position: relative;
  border: none; }
  .closeButton-PCZcma:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--md-ripple-color), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .closeButton-PCZcma:hover:after {
    opacity: 1;
    transform: scale(1.2);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .closeButton-PCZcma:active:after {
    background-color: hsla(var(--md-ripple-color), 0.2); }
  .closeButton-PCZcma:hover {
    background-color: transparent !important; }
  .closeButton-PCZcma:active {
    transform: translateX(0px); }

.keybind-13vtq8 {
  color: var(--text-muted) !important; }

/* USER SETTINGS -> MY ACCOUNT */
.contentColumnDefault-3eyv5o > div:not([class]):first-child > div:not([class]):first-child + .divider-3LgWDL {
  display: none; }

.accountProfileCard-lbN7n- {
  background-color: var(--card-color);
  border-radius: var(--card-radius-big); }
  .accountProfileCard-lbN7n- .userInfo-regn9W {
    height: 88px;
    padding: 16px 16px 16px 120px;
    border-left: 1px solid var(--card-border-color);
    border-right: 1px solid var(--card-border-color); }
    .accountProfileCard-lbN7n- .userInfo-regn9W .avatar-3mTjvZ {
      background-color: transparent;
      border: none;
      box-shadow: var(--shadow-3dp); }
  .accountProfileCard-lbN7n- .background-3d_SjE {
    margin: 0;
    padding: 0;
    background-color: transparent;
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border: 1px solid var(--card-border-color); }
    .accountProfileCard-lbN7n- .background-3d_SjE .fieldList-in8WkP {
      margin-top: 0;
      padding: 16px; }
      .accountProfileCard-lbN7n- .background-3d_SjE .fieldList-in8WkP .constrainedRow-3y91Xf .button-f2h6uQ {
        margin-left: 8px; }

.fieldList-in8WkP {
  padding: 0;
  background-color: transparent;
  border-radius: 0; }

/* USER SETTINGS -> MY ACCOUNT -> EDIT */
.inputPrefix-1VU7MB {
  height: 32px;
  padding-top: 0;
  padding-left: 16px;
  line-height: 32px;
  color: var(--text-normal); }

/* USER SETTINGS -> USER PROFILE */
.notice-1Qe0b_ {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.nitroUpsellButtonInner-zjGzQV {
  display: grid;
  grid-template-columns: 30px 1fr; }

.customizationSection-IGy2fS .inputWrapper-1YNMmM {
  height: auto;
  min-height: 32px;
  max-height: unset; }
.customizationSection-IGy2fS:not(.preview-yzOwK1) {
  margin-bottom: 16px;
  padding: 16px;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .customizationSection-IGy2fS:not(.preview-yzOwK1) .title-3hptVQ {
    width: calc(100% + 32px);
    margin-top: -16px;
    margin-left: -16px;
    margin-bottom: 16px;
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
.customizationSection-IGy2fS.preview-yzOwK1 .title-3hptVQ {
  display: none; }
.customizationSection-IGy2fS .buttonsContainer-3rygH4 {
  height: auto !important;
  background-color: unset;
  border-radius: 0 !important;
  border: none; }

.profileBannerPreview-3mLIdO {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .profileBannerPreview-3mLIdO .avatarUploaderInner-p38nm2 {
    background-color: transparent;
    border: none;
    box-shadow: var(--shadow-3dp); }
    .profileBannerPreview-3mLIdO .avatarUploaderInner-p38nm2:focus-within .avatarUploaderHint-2ZdBlc, .profileBannerPreview-3mLIdO .avatarUploaderInner-p38nm2:hover .avatarUploaderHint-2ZdBlc {
      background-color: rgba(0, 0, 0, 0.5);
      border-radius: 50%; }
  .profileBannerPreview-3mLIdO .headerTop-3GPUSF {
    padding: 64px 12px 12px;
    border-bottom: 1px solid var(--card-border-color); }
  .profileBannerPreview-3mLIdO .popoutInfo-16MuYF {
    padding: 12px; }
  .profileBannerPreview-3mLIdO .divider-1wtgZ3 {
    display: none; }
  .profileBannerPreview-3mLIdO .aboutMeTitle-3pjiS7,
  .profileBannerPreview-3mLIdO .fakeActivityTitle-3Yf28p,
  .profileBannerPreview-3mLIdO .fakeActivityTitle-3-_pB_ {
    font-size: 14px;
    text-transform: none; }
  .profileBannerPreview-3mLIdO .fakeActivityIcon-KeXVoI {
    background-color: hsl(var(--accent-hsl));
    border-radius: 50%; }

/* USER SETTINGS -> AUTHORIZED APPS */
.formNotice-2nS8ey {
  padding: 0; }
  .formNotice-2nS8ey .formNoticeTitle-2qYdGw {
    margin: 0;
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500;
    text-transform: none; }
  .formNotice-2nS8ey .formNoticeBody-1GTGJa {
    padding: 16px; }

.authedApp-1tw-eT {
  padding: 0;
  margin-bottom: 16px; }
  .authedApp-1tw-eT .marginBottom20-315RVT {
    margin: 0;
    padding: 16px;
    border-bottom: 1px solid var(--card-border-color); }
  .authedApp-1tw-eT div:not([class]) {
    padding: 16px 16px 0; }
  .authedApp-1tw-eT .marginTop20-2T8ZJx {
    margin: 0;
    padding: 16px; }

.permission-5MTkHz .permissionCheckmark-2XFmCt {
  background-image: none;
  background-color: var(--success-color);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/check_box.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/check_box.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }

/* USER SETTINGS -> CONNECTIONS */
.accountList-305sx3 {
  padding: 0;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .accountList-305sx3 .title-3hptVQ {
    margin-bottom: 0;
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500;
    opacity: 1; }
  .accountList-305sx3 .modeDefault-2fEh7a {
    padding: 8px 16px 0; }
  .accountList-305sx3 .connectedAccounts-26X_gr {
    padding: 0 16px 16px 16px; }
    .accountList-305sx3 .connectedAccounts-26X_gr .accountBtn-1YkMgV {
      margin-bottom: 0; }
      .accountList-305sx3 .connectedAccounts-26X_gr .accountBtn-1YkMgV .accountBtnInner-3XK70s {
        background-color: var(--menu-item-hover);
        border-radius: 50%;
        transition: var(--default-time) var(--default-animation) background-color; }
        .accountList-305sx3 .connectedAccounts-26X_gr .accountBtn-1YkMgV .accountBtnInner-3XK70s:hover {
          background-color: var(--menu-item-select); }

.connectionList-1NoxUk {
  grid-gap: 16px; }
  .connectionList-1NoxUk .connection-107AGH {
    margin-bottom: 0;
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }
    .connectionList-1NoxUk .connection-107AGH .connectionHeader-2rV1ze {
      padding: 16px ;
      background-color: transparent;
      border-bottom: 1px solid var(--card-border-color);
      font-size: 1em;
      color: var(--card-header-text-color);
      font-weight: 500; }
      .connectionList-1NoxUk .connection-107AGH .connectionHeader-2rV1ze .connectionAccountValue-3gVX0m,
      .connectionList-1NoxUk .connection-107AGH .connectionHeader-2rV1ze .connectionAccountLabel-HkwS6X {
        font-weight: 500; }
    .connectionList-1NoxUk .connection-107AGH .connectionOptionsWrapper-1ipqUo {
      padding: 16px; }
      .connectionList-1NoxUk .connection-107AGH .connectionOptionsWrapper-1ipqUo .connectionOptionSwitch-FwkEHS {
        padding-left: 0;
        padding-right: 0; }
        .connectionList-1NoxUk .connection-107AGH .connectionOptionsWrapper-1ipqUo .connectionOptionSwitch-FwkEHS.marginBottom20-315RVT:last-child {
          margin-bottom: 0; }
    .connectionList-1NoxUk .connection-107AGH .connectedAccountSeparator-2gWsUP {
      margin-left: 0;
      margin-right: 0; }

.integrationsWrapper-3a2pGd {
  padding: 0; }
  .integrationsWrapper-3a2pGd .h5-2RwDNl {
    margin: 0;
    padding: 16px 16px 8px; }
  .integrationsWrapper-3a2pGd .integration-1f5IUi {
    position: relative;
    margin-top: 0;
    padding: 16px;
    background-color: transparent;
    border-radius: 0; }
    .integrationsWrapper-3a2pGd .integration-1f5IUi:after {
      position: absolute;
      content: " ";
      width: calc(100% - 56px);
      height: 1px;
      bottom: 0;
      right: 0;
      background-color: var(--card-border-color); }
    .integrationsWrapper-3a2pGd .integration-1f5IUi:last-child:after, .integrationsWrapper-3a2pGd .integration-1f5IUi:only-child:after {
      display: none; }
    .integrationsWrapper-3a2pGd .integration-1f5IUi .button-f2h6uQ {
      background-color: hsla(var(--accent-hsl), 0.1);
      color: hsl(var(--accent-hsl)); }

/* USER SETTINGS -> DISCORD NITRO */
.holidayHeroContainer-11fdxG {
  width: 100%;
  border-radius: var(--card-radius-big); }

.giftContainer-1X7m0c {
  padding: 16px;
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }

/* USER SETTINGS -> SERVER BOOST */
.feature-1Q4U_R {
  padding: 16px;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.guild-Hq0WWA {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .guild-Hq0WWA .guildHeader-3nh5RK {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
    .guild-Hq0WWA .guildHeader-3nh5RK .guildIcon-c10VUR {
      top: 0;
      bottom: 0;
      margin: auto 0; }
    .guild-Hq0WWA .guildHeader-3nh5RK .guildHeaderContent-1vpxhX {
      padding: 0 16px; }
    .guild-Hq0WWA .guildHeader-3nh5RK .guildGemIndicatorContainer-3Ie0ga {
      margin: 0; }
  .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN {
    padding: 0;
    background-color: transparent; }
    .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI {
      padding: 16px;
      border-bottom: none;
      position: relative;
      border-bottom: none; }
      .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI:after {
        position: absolute;
        content: " ";
        width: calc(100% - 42px);
        height: 1px;
        right: 0;
        bottom: 0;
        background-color: var(--card-border-color); }
      .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI:last-of-type:after {
        display: none; }
      .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI .guildSubscriptionSlotMenuIcon-uzNhjL {
        position: relative; }
        .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI .guildSubscriptionSlotMenuIcon-uzNhjL:after {
          content: " ";
          position: absolute;
          width: 100%;
          height: 100%;
          top: 0;
          left: 0;
          background-color: hsla(var(--md-ripple-color), 0.1);
          border-radius: 50%;
          opacity: 0;
          pointer-events: none;
          transform: scale(1.2);
          transition: 300ms ease;
          z-index: 4; }
        .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI .guildSubscriptionSlotMenuIcon-uzNhjL:hover:after {
          opacity: 1;
          transform: scale(1.5);
          animation: scale 150ms var(--default-animation), opacity 150ms ease; }
        .guild-Hq0WWA .guildSubscriptionSlots-JPXXvN .guildSubscriptionSlot-1XGRPI .guildSubscriptionSlotMenuIcon-uzNhjL:active:after {
          background-color: hsla(var(--md-ripple-color), 0.2); }

.cardWrapper-CyvwQv {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  transition: var(--default-time) var(--default-animation) background-color; }
  .cardWrapper-CyvwQv:hover {
    background-color: transparent; }

.menu-1QACrS#subscription-context {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--shadow-3dp); }
  .menu-1QACrS#subscription-context .scroller-1bVxF5 {
    padding: 8px 0; }
    .menu-1QACrS#subscription-context .scroller-1bVxF5::-webkit-scrollbar {
      width: 0px !important; }
  .menu-1QACrS#subscription-context .item-1OdjEX {
    margin: 0;
    padding: 9px 12px;
    border-radius: 0;
    color: var(--menu-item-text-color);
    transition: var(--default-time) var(--default-animation) background-color; }
    .menu-1QACrS#subscription-context .item-1OdjEX.focused-3qFvc8 {
      background-color: var(--menu-item-hover);
      color: var(--menu-item-text-color); }

/* USER SETTINGS -> BILLING */
.card-2aHs8C {
  padding: 0; }
  .card-2aHs8C form > div:not([class]):first-child {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
    .card-2aHs8C form > div:not([class]):first-child .subText-3FNUOd {
      margin-top: 16px; }
  .card-2aHs8C form .addressSection-3-7v_3 {
    margin-top: 0;
    padding: 16px; }
    .card-2aHs8C form .addressSection-3-7v_3 + .defaultSection-319Lgg {
      margin: 0;
      padding: 8px 16px 16px; }
  .card-2aHs8C form .formActions-5CiFNE {
    margin-top: 0;
    padding: 8px; }
    .card-2aHs8C form .formActions-5CiFNE .lookLink-15mFoz.colorPrimary-2AuQVo {
      margin-right: 8px; }

.codeRedemptionRedirect-3SBiCp {
  padding: 16px;
  background-color: transparent !important;
  border-color: var(--card-border-color) !important; }

.button-3WZC0G {
  margin: 0; }
  .button-3WZC0G:nth-of-type(odd) {
    margin-right: 6px; }

.cardNumberWrapper-3JnfVP .hiddenDiv-2qTqSF {
  height: 0; }

.cardInput-33x7OF {
  padding: 6px 0;
  background-color: transparent;
  border-radius: 0;
  border: none;
  border-bottom: 1px solid var(--input-border-color); }
  .cardInput-33x7OF.cardNumberInput-1Ly6Gn {
    padding-left: 40px; }

.cardIcon-1rZ5-N {
  top: 6px;
  left: 0; }

/* USER SETTINGS -> APPEARANCE */
.preview-rua1rr .wrapper-30-Nkg.cozy-VmLDNB {
  margin-left: 62px;
  margin-right: 16px; }

/* USER SETTINGS -> ACCESSIBILITY */
.previewMessage-2uxBrA {
  padding: 16px;
  background-color: var(--chat-color);
  border-radius: var(--card-radius-big); }
  .previewMessage-2uxBrA .wrapper-30-Nkg {
    margin: 0 0 0 52px !important;
    border-radius: var(--message-radius); }
    .previewMessage-2uxBrA .wrapper-30-Nkg:before, .previewMessage-2uxBrA .wrapper-30-Nkg:after {
      display: none; }
    .previewMessage-2uxBrA .wrapper-30-Nkg .avatar-2e8lTP {
      top: 0;
      left: -50px; }

/* USER SETTINGS -> VOICE & VIDEO */
.userSettingsVoice-1_dzjw .media-engine-video {
  border-radius: var(--card-radius-big); }
.userSettingsVoice-1_dzjw .previewOverlay-2reuWf {
  background-color: var(--main-color) !important;
  border-radius: var(--card-radius-big);
  border-color: var(--card-border-color) !important; }

.formNotice-2nS8ey .icon-1fWS75 {
  margin-left: 16px !important; }

.micTestButton-1Qz8Oq {
  width: auto; }

/* USER SETTINGS -> KEYBINDS */
.warning-RBGtx2 {
  background-color: transparent;
  border-color: var(--alert-color); }
  .warning-RBGtx2 .icon-2fP4ae {
    color: var(--alert-color); }

.container-3jbRo5 {
  border-radius: var(--card-radius-big); }

.children-1xdcWE .marginBottom20-315RVT + .divider-3LgWDL {
  display: none; }

.row-1Tg75B {
  padding: 16px;
  border: 1px solid var(--card-border-color);
  border-bottom: none;
  box-shadow: none !important; }
  .row-1Tg75B:first-child {
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0; }
  .row-1Tg75B:last-child {
    margin-bottom: 40px;
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border-bottom: 1px solid var(--card-border-color); }
  .row-1Tg75B:only-child {
    border-radius: var(--card-radius-big); }
  .row-1Tg75B .keybindGroup-eTTYMW {
    margin: 0;
    padding: 0; }
    .row-1Tg75B .keybindGroup-eTTYMW:before {
      display: none; }
  .row-1Tg75B .removeKeybind-2YVgVG {
    right: -12px; }

.defaultKeybindGroup-3IVc_- {
  margin: 32px 0 0 0;
  border-radius: var(--card-radius-big);
  border: 1px solid var(--card-border-color); }
  .defaultKeybindGroup-3IVc_- .defaultKeybindGroupHeader-2dEFA2 {
    margin-bottom: 0;
    padding: 16px;
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500;
    text-transform: capitalize; }
    .defaultKeybindGroup-3IVc_- .defaultKeybindGroupHeader-2dEFA2.defaultKeybindGroupWithDescription-2W4JbJ {
      margin-bottom: 6px;
      padding: 16px 16px 0; }
  .defaultKeybindGroup-3IVc_- .defaultKeybindGroupDescription-3mKcYJ {
    margin-bottom: 0;
    padding: 0 16px 16px; }
    .defaultKeybindGroup-3IVc_- .defaultKeybindGroupDescription-3mKcYJ + .divider-3LgWDL {
      display: none; }
  .defaultKeybindGroup-3IVc_- .defaultKeybind-OJ0CKH {
    padding: 16px;
    border-top: 1px solid var(--card-border-color);
    font-weight: 400; }
    .defaultKeybindGroup-3IVc_- .defaultKeybind-OJ0CKH:nth-child(3) {
      border-top: none; }
    .defaultKeybindGroup-3IVc_- .defaultKeybind-OJ0CKH + .divider-3LgWDL {
      display: none; }

/* USER SETTINGS -> ACTIVITY STATUS */
.activeGame-3ncS55 {
  border-radius: var(--card-radius-big);
  border: 1px solid var(--card-border-color); }
  .activeGame-3ncS55.notDetected-2HEmAp, .activeGame-3ncS55.nowPlaying-zBamm2 {
    background-color: transparent !important; }
  .activeGame-3ncS55 .gameName-Uw4dbt,
  .activeGame-3ncS55 .lastPlayed-3aHvxk {
    color: var(--text-normal) !important; }

.nowPlayingAdd-3lvnXJ {
  color: var(--text-normal) !important; }
  .nowPlayingAdd-3lvnXJ .button-f2h6uQ {
    margin-left: 8px; }

.addGamePopout-3yePJc {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .addGamePopout-3yePJc .lookLink-15mFoz.colorGrey-2iAG-B {
    margin-right: 8px; }

/* USER SETTINGS -> ACTIVITY STATUS -> GAME LIST */
.nowPlayingAdd-3lvnXJ {
  margin: 16px 0; }
  .nowPlayingAdd-3lvnXJ + .container-1zDvAE {
    margin-bottom: 0; }
  .nowPlayingAdd-3lvnXJ + .marginTop40-Q4o1tS {
    margin-top: 0;
    border-radius: var(--card-radius-big);
    border: 1px solid var(--card-border-color); }
    .nowPlayingAdd-3lvnXJ + .marginTop40-Q4o1tS .h5-2RwDNl {
      margin-bottom: 0;
      padding: 16px;
      border-bottom: 1px solid var(--card-border-color);
      font-size: 1em;
      color: var(--card-header-text-color);
      font-weight: 500; }

.game-3x3aDt {
  padding: 16px;
  border-bottom: 1px solid var(--card-border-color);
  box-shadow: none !important; }
  .game-3x3aDt:before {
    display: none; }
  .game-3x3aDt:last-child {
    border-bottom: none; }
  .game-3x3aDt .gameNameInput-3TuPuA {
    height: 24px;
    border-radius: 12px;
    border: none; }
    .game-3x3aDt .gameNameInput-3TuPuA:focus {
      background-color: var(--input-color); }
  .game-3x3aDt .lastPlayed-3aHvxk {
    margin-top: 4px; }
  .game-3x3aDt .overlayStatusText-AHDYB3 {
    color: var(--text-muted);
    transition: var(--default-time) var(--default-animation) opacity; }
  .game-3x3aDt .overlayToggleIcon-2NLk4w {
    width: 24px;
    height: 24px;
    position: relative; }
    .game-3x3aDt .overlayToggleIcon-2NLk4w:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .game-3x3aDt .overlayToggleIcon-2NLk4w:hover:after {
      opacity: 1;
      transform: scale(1.6);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .game-3x3aDt .overlayToggleIcon-2NLk4w:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
  .game-3x3aDt .overlayToggleIconOn-3_-nGm .fill-MYciTJ {
    fill: var(--text-muted); }
  .game-3x3aDt .overlayToggleIconOn-3_-nGm path {
    d: path("M21 2H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h7v2H8v2h8v-2h-2v-2h7c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H3V4h18v12z"); }
  .game-3x3aDt .overlayToggleIconOff-3hGOmN path {
    d: path("M1.41 1.69L0 3.1l1 .99V16c0 1.1.89 2 1.99 2H10v2H8v2h8v-2h-2v-2h.9l6 6 1.41-1.41-20.9-20.9zM2.99 16V6.09L12.9 16H2.99zM4.55 2l2 2H21v12h-2.45l2 2h.44c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2H4.55z"); }
    .game-3x3aDt .overlayToggleIconOff-3hGOmN path ~ rect {
      display: none; }
  .game-3x3aDt .removeGame-3Le1LJ {
    top: -12px;
    right: -12px; }

/* USER SETTINGS -> GAME OVERLAY */
.container-1_EVMa .base-ddxxyL {
  padding: 10px 0; }

.container-30qY7E {
  --input-border-color: transparent;
  height: var(--input-height) !important;
  max-height: var(--input-height) !important;
  padding: var(--input-padding) !important;
  background-color: var(--input-color) !important;
  border-radius: calc(var(--input-height) / 2) !important; }
  .container-30qY7E:before, .container-30qY7E:after {
    display: none; }
  .container-30qY7E:hover .button-ZJ9ZzX, .container-30qY7E:focus-within .button-ZJ9ZzX {
    width: 154px !important; }
  .container-30qY7E .input-3MU9bJ {
    padding-left: 12px; }
  .container-30qY7E .button-ZJ9ZzX {
    --button-height: 30px;
    margin: 4px;
    transition: var(--default-time) var(--default-animation) width, var(--default-time) var(--default-animation) box-shadow !important; }
  .container-30qY7E.recording-3ny5_E {
    border-radius: calc(var(--input-height) / 2); }

.wrapper-SdcMKg {
  border-radius: var(--card-radius-big);
  border-color: hsl(var(--accent-hsl)); }
  .wrapper-SdcMKg .option-1QI4c9 {
    border-radius: var(--card-radius-big); }
    .wrapper-SdcMKg .option-1QI4c9:hover {
      background-color: hsl(var(--accent-hsl));
      opacity: 0.6; }
    .wrapper-SdcMKg .option-1QI4c9.selected-18Wszc {
      background-color: hsl(var(--accent-hsl));
      border-color: hsl(var(--accent-hsl));
      box-shadow: var(--shadow-1dp); }

/* USER SETTINGS -> BETTERDISCORD */
#bd-settings-sidebar .ui-tab-bar-separator {
  background-color: transparent !important; }

.bd-search-wrapper {
  height: 32px;
  padding: 0;
  line-height: 32px;
  background-color: var(--input-color);
  border-radius: 16px; }
  .bd-search-wrapper .bd-search {
    height: 100%;
    padding: 0 4px 0 12px;
    font-size: 14px; }
  .bd-search-wrapper > svg {
    margin-right: 12px; }

.bd-addon-list {
  margin-top: 24px !important; }
  .bd-addon-list a {
    color: hsl(var(--accent-hsl)); }
  .bd-addon-list .bd-addon-card {
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }
  .bd-addon-list .bd-addon-header {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
    .bd-addon-list .bd-addon-header .gifFavoriteButton-2IttKp {
      color: var(--text-muted); }
      .bd-addon-list .bd-addon-header .gifFavoriteButton-2IttKp.selected-7JJuv5 {
        color: #faa61a; }
  .bd-addon-list .bd-controls {
    border-radius: 14px;
    border: 1px solid var(--card-border-color);
    overflow: hidden; }
    .bd-addon-list .bd-controls .bd-button {
      padding: 3px 8px;
      background-color: transparent; }
      .bd-addon-list .bd-controls .bd-button:hover {
        background-color: var(--menu-item-hover); }
      .bd-addon-list .bd-controls .bd-button svg {
        fill: var(--menu-item-text-color); }

.repoHeader-2KfNvH > * {
  min-width: 350px;
  max-width: 1200px; }
.repoHeader-2KfNvH .top-K_jibn .item-3XjbnG {
  border: none; }
  .repoHeader-2KfNvH .top-K_jibn .item-3XjbnG.selected-g-kMVV {
    position: relative;
    background-color: transparent !important; }
    .repoHeader-2KfNvH .top-K_jibn .item-3XjbnG.selected-g-kMVV:after {
      position: absolute;
      content: " ";
      width: 90%;
      height: 3px;
      left: 0;
      right: 0;
      bottom: 0;
      margin: 0 auto;
      background: var(--tab-border-color);
      border-radius: 3px 3px 0 0;
      transition: var(--default-time) ease all; }
.repoHeader-2KfNvH .tabBarContainer-1s1u-z.bottom-b8sdfs {
  border-bottom-color: var(--card-border-color); }

.bd-button {
  background-color: hsl(var(--accent-hsl));
  border-radius: var(--card-radius);
  color: var(--accent-text-color); }

.bd-addon-views .bd-view-button.selected {
  background-color: hsl(var(--accent-hsl));
  color: var(--accent-text-color); }

.bd-select .bd-select-options {
  padding: 8px 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--shadow-3dp);
  border: none; }
  .bd-select .bd-select-options .bd-select-option {
    padding: 8px 12px;
    font-weight: 500;
    color: var(--menu-item-text-color);
    transition: var(--default-time) var(--default-animation) background-color; }
    .bd-select .bd-select-options .bd-select-option:hover {
      background-color: var(--menu-item-hover); }
    .bd-select .bd-select-options .bd-select-option.selected {
      background-color: var(--menu-item-select); }

.monaco-editor *,
.ace_editor *,
.line-numbers * {
  font-family: var(--code-font) !important; }
.monaco-editor .codicon[class*=codicon-],
.ace_editor .codicon[class*=codicon-],
.line-numbers .codicon[class*=codicon-] {
  font-family: codicon !important; }

/* USER SETTINGS -> SIDEBAR */
.sidebarRegion-1VBisG {
  flex: 0; }

.sidebar-nqHbhN {
  width: 240px;
  margin: 0 6px 0 0;
  padding: 60px 6px 40px 0; }

.side-2ur1Qk .header-2Kx1US,
.side-2ur1Qk .ui-tab-bar-header,
#bd-settings-sidebar .header-2Kx1US,
#bd-settings-sidebar .ui-tab-bar-header {
  margin-top: 4px;
  margin-bottom: 8px;
  padding: 0 12px 0 26px;
  font-size: 0.8em;
  font-weight: 700;
  text-transform: none;
  color: var(--channels-default) !important; }
.side-2ur1Qk .separator-2wx7h6,
.side-2ur1Qk .ui-tab-bar-separator,
#bd-settings-sidebar .separator-2wx7h6,
#bd-settings-sidebar .ui-tab-bar-separator {
  position: relative;
  height: 1px;
  margin: 8px 0;
  background: transparent; }
  .side-2ur1Qk .separator-2wx7h6:before,
  .side-2ur1Qk .ui-tab-bar-separator:before,
  #bd-settings-sidebar .separator-2wx7h6:before,
  #bd-settings-sidebar .ui-tab-bar-separator:before {
    position: absolute;
    content: " ";
    width: calc(100% + 12px);
    height: 1px;
    background: rgba(114, 118, 125, 0.3); }

.contentRegion-3HkfJJ div[role="tabpanel"] {
  width: 100%;
  height: 100%; }

.contentColumnDefault-3eyv5o,
.contentColumnMinimal-32PuDO,
.customColumn-2n-oKU,
.customScroller-m1-jZn > div {
  flex: 1 1 auto;
  min-width: 350px;
  max-width: 1200px;
  left: 0;
  right: 0;
  margin: 0 auto; }

.contentColumnDefault-3eyv5o {
  padding: 60px; }

.customHeader-f9DEJ_ {
  padding-top: 0; }

.customContainer-dK1ozq {
  width: auto; }
  .customContainer-dK1ozq .auto-2K3UW5 {
    background-color: var(--main-color) !important;
    border-top-left-radius: var(--card-radius-big); }
  .customContainer-dK1ozq .customScroller-m1-jZn {
    padding-right: 0 !important; }
    .customContainer-dK1ozq .customScroller-m1-jZn .content-28mbXd div:not([class])[style="height: 60px;"] {
      height: 0 !important; }
    .customContainer-dK1ozq .customScroller-m1-jZn > div {
      position: relative;
      min-width: 350px;
      max-width: 1200px;
      margin: 0 auto;
      padding: 60px 97px 60px 60px !important; }
    .customContainer-dK1ozq .customScroller-m1-jZn > .customHeader-3mDgmH {
      padding: 0; }

.card-2ART2V:before {
  margin: 0 60px; }

.customColumn-2n-oKU + .toolsContainer-25FL6V,
.contentRegion-3HkfJJ div[role="tabpanel"] + .toolsContainer-25FL6V {
  position: absolute;
  width: 60px;
  height: 60px;
  right: 0; }
  .customColumn-2n-oKU + .toolsContainer-25FL6V .tools-kIrEGr,
  .contentRegion-3HkfJJ div[role="tabpanel"] + .toolsContainer-25FL6V .tools-kIrEGr {
    position: absolute;
    width: 36px;
    right: -8px; }

.contentColumnMinimal-32PuDO {
  padding: 60px 80px 80px; }

.sidebarScrollable-2mW9Ls .flexChild-3PzYmX[style*='padding: 60px 15px 80px 20px;'] {
  padding: 60px 8px 40px 0 !important; }

.sidebarScrollable-2mW9Ls + .content-2ssVKB[style*='padding: 60px 0px 80px 20px;'] {
  padding: 0 0 0 20px !important; }

.sidebarScrollable-2mW9Ls + .content-2ssVKB {
  position: relative;
  width: calc(100% - 232px);
  left: 232px;
  right: 0;
  margin-left: 0;
  padding: 0 !important; }

.sidebarScrollable-2mW9Ls .side-2ur1Qk .header-2Kx1US:first-child {
  margin: 0 0 8px 0;
  padding: 0 0 0 10px !important; }

.socialLinks-2DELRE,
.info-1sUqUG {
  padding: 8px 12px 8px 26px; }

/* USER SETTINGS -> SIDEBAR -> ICONS */
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG,
#bd-settings-sidebar .ui-tab-bar-item {
  width: 240px;
  height: 32px;
  margin: 0;
  padding: 0 12px 0 54px;
  line-height: 32px;
  border-radius: 0 16px 16px 0;
  transition: var(--default-time) ease background-color; }
  .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG:before,
  #bd-settings-sidebar .ui-tab-bar-item:before {
    position: absolute;
    content: " ";
    width: 20px;
    height: 20px;
    top: 0;
    left: 26px;
    bottom: 0;
    margin: auto 0;
    background-repeat: no-repeat;
    background-position: center;
    opacity: 0.8; }
  .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG svg,
  #bd-settings-sidebar .ui-tab-bar-item svg {
    display: none; }
  .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.selected-g-kMVV, .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.selected,
  #bd-settings-sidebar .ui-tab-bar-item.selected-g-kMVV,
  #bd-settings-sidebar .ui-tab-bar-item.selected {
    background-color: var(--menu-item-select-accent) !important; }
    .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.selected-g-kMVV:before, .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.selected:before,
    #bd-settings-sidebar .ui-tab-bar-item.selected-g-kMVV:before,
    #bd-settings-sidebar .ui-tab-bar-item.selected:before {
      opacity: 1; }
  .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG .selectedBackground-1qyzak,
  #bd-settings-sidebar .ui-tab-bar-item .selectedBackground-1qyzak {
    display: none; }

.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="my-account-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/person.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/person.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="profile-customization-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/edit.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/edit.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="privacy-&-safety-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/security.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/security.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="authorized-apps-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/apps.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/apps.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="connections-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/link.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/link.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="subscriptions-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/subscription.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/subscription.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="discord-nitro-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/nitro.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/nitro.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="nitro-server-boost-tab"]:before {
  left: 27px;
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/server_boost.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/server_boost.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="library-inventory-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/gift.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/gift.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="billing-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/payment.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/payment.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="appearance-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/chat.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/chat.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="accessibility-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/accessibility.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/accessibility.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="voice-&-video-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/mic.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/mic.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="text-&-images-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/keyboard.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/keyboard.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="notifications-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/notifications.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/notifications.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="keybinds-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/space_bar.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/space_bar.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="language-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/translate.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/translate.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="windows-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/windows.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/windows.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="linux-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/linux.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/linux.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="streamer-mode-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/live_tv.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/live_tv.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="advanced-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/integrations.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/integrations.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="game-activity-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/gamepad.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/gamepad.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="overlay-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/picture_in_picture.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/picture_in_picture.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.bd-settings-tab:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.bd-emotes-tab:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.bd-customcss-tab:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.bd-plugins-tab:before, .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="pluginrepo-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG.bd-themes-tab:before, .sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="themerepo-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="changelog-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/list.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/list.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="hypesquad-online-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/hypesquad.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/hypesquad.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="experiments-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="developer-options-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="hotspot-options-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="logout-tab"]:before {
  background-color: var(--alert-color);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/exit_to_app.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/exit_to_app.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="pc-general-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="pc-modulemanager-plugins-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="pc-modulemanager-themes-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.sidebar-nqHbhN .side-2ur1Qk .item-3XjbnG[aria-controls="pc-updater-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/update.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/update.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }

#bd-settings-sidebar div:not([class]) .ui-tab-bar-item:nth-child(3):before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/settings.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
#bd-settings-sidebar div:not([class]) .ui-tab-bar-item:nth-child(4):before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
#bd-settings-sidebar div:not([class]) .ui-tab-bar-item:nth-child(5):before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/plugins.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
#bd-settings-sidebar div:not([class]) .ui-tab-bar-item:nth-child(6):before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/themes.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
#bd-settings-sidebar div:not([class]) .ui-tab-bar-item:nth-child(7):before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/code.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }

/*
 *
 *	SERVER SETTINGS
 *
 */
.container-1s4HBn {
  background-color: transparent !important;
  border-radius: 0;
  border: none;
  border-bottom: 1px solid var(--input-border-color) !important; }
  .container-1s4HBn .input-1dRteR {
    padding: 0; }
  .container-1s4HBn .button-3og7GZ {
    margin: 4px 0; }

.regionSelectModal-12e-57 {
  padding: 0; }
  .regionSelectModal-12e-57 .regionSelectModalHeader-21khC1 {
    margin-bottom: 0;
    padding: 16px;
    border-bottom: 1px solid var(--popout-header-border);
    font-size: 16px;
    text-transform: none;
    font-weight: 600;
    color: var(--card-header-text-color);
    text-align: left; }
  .regionSelectModal-12e-57 .regionSelectModalOptions-2TWQOB {
    padding: 16px;
    overflow-y: auto; }
    .regionSelectModal-12e-57 .regionSelectModalOptions-2TWQOB .regionSelectModalOption-2DSIZ3 {
      background-color: var(--card-color-alt);
      border-radius: var(--card-radius-big);
      border: 1px solid var(--card-border-color);
      transition: var(--default-time) var(--default-animation) box-shadow, var(--default-time) var(--default-animation) transform; }
      .regionSelectModal-12e-57 .regionSelectModalOptions-2TWQOB .regionSelectModalOption-2DSIZ3:hover {
        transform: translateY(-2px);
        box-shadow: var(--shadow-3dp); }
  .regionSelectModal-12e-57 .regionSelectModalFooter-20C5iA {
    margin-top: 0;
    padding: 16px;
    border-top: 1px solid var(--popout-header-border);
    text-align: left; }

.noticeRegion-qjyUVg {
  left: 0;
  right: 0;
  margin: 0 auto;
  padding: 0 16px 16px; }

.container-20TyK0 {
  background-color: var(--popout-color) !important;
  border-radius: 29px;
  box-shadow: var(--shadow-3dp) !important; }

.title-2CL_z0,
.text-27cdrj {
  color: var(--text-normal) !important; }

.description-30xx7u + .button-f2h6uQ.sizeMedium-2bFIHr {
  max-width: auto; }

/* SERVER SETTINGS -> ROLES */
.sidebarScrollable-2mW9Ls .side-2ur1Qk .item-3XjbnG {
  width: auto;
  border-radius: 16px; }

.colorPickerSwatch-RTUGRR {
  border-radius: 10px; }
  .colorPickerSwatch-RTUGRR.custom-1Up2lr, .colorPickerSwatch-RTUGRR.default-3ISV7m {
    width: 50px;
    border-radius: 50%;
    overflow: visible !important; }
  .colorPickerSwatch-RTUGRR.custom-1Up2lr:not(.default-3ISV7m):after {
    display: none; }

.container-1S70rv {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .container-1S70rv .autocompleteShadow-2nfsSy {
    display: none; }
  .container-1S70rv .autocompleteArrow-jJE9TQ {
    background-color: var(--popout-color) !important; }
  .container-1S70rv .header-3i_Csh {
    padding: 0 16px;
    background-color: transparent !important;
    border-bottom: 1px solid var(--popout-header-border); }
    .container-1S70rv .header-3i_Csh .input-2lpFVz {
      width: calc(100% - 32px); }
  .container-1S70rv .sectionTag-28mLyE {
    background-color: transparent !important; }
  .container-1S70rv .section-3PvCGN {
    padding: 0 16px;
    text-transform: none;
    font-size: 14px; }
  .container-1S70rv .row-1Ib2uD {
    padding: 0; }
    .container-1S70rv .row-1Ib2uD .rowInner-3uonq8 {
      padding: 12px 16px;
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
    .container-1S70rv .row-1Ib2uD.selected-1IWCoj .rowInner-3uonq8 {
      background-color: var(--menu-item-hover);
      color: var(--menu-item-text-color); }

/* SERVER SETTINGS -> ROLES -> NEW */
.container-3EtAkD {
  padding: 16px;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.searchContainer-16qhPt .container-2oNtJn {
  height: var(--input-height);
  border-radius: var(--input-radius); }
  .searchContainer-16qhPt .container-2oNtJn .inner-2pOSmK .input-2m5SfJ {
    height: var(--input-height); }
  .searchContainer-16qhPt .container-2oNtJn .inner-2pOSmK .iconLayout-3Bjizv {
    width: 36px;
    height: 36px; }

/* SERVER SETTINGS -> ROLES -> NEW -> ROLES LIST */
.rolesTable-2Z8MuS {
  padding: 16px;
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
  border: 1px solid var(--card-border-color); }
  .rolesTable-2Z8MuS .tableHeader-2h-wc8 {
    margin-left: 0;
    margin-bottom: 0; }
    .rolesTable-2Z8MuS .tableHeader-2h-wc8 .dragSpacing-2GB_1h {
      display: none; }
  .rolesTable-2Z8MuS .tableTitle-3zdrSx {
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500;
    text-transform: none; }
    .rolesTable-2Z8MuS .tableTitle-3zdrSx.memberSpacing-1RRW7k {
      margin-left: 64px; }

.roleRow-3LoHQ6 {
  margin-left: 0;
  margin-right: 0;
  padding-right: 16px;
  position: relative;
  border-bottom: none;
  border-radius: 0;
  border-left: 1px solid var(--card-border-color);
  border-right: 1px solid var(--card-border-color);
  transition: var(--default-time) var(--default-animation); }
  .roleRow-3LoHQ6:after {
    position: absolute;
    content: " ";
    width: calc(100% - 62px);
    height: 1px;
    right: 0;
    bottom: 0;
    background-color: var(--card-border-color); }
  .roleRow-3LoHQ6:last-of-type:after {
    display: none; }
  .roleRow-3LoHQ6:hover {
    background-color: var(--card-color-hover); }
    .roleRow-3LoHQ6:hover:after {
      background-color: var(--card-border-color); }
  .roleRow-3LoHQ6:before {
    display: none; }
  .roleRow-3LoHQ6:last-of-type {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border-bottom: 1px solid var(--card-border-color); }
  .roleRow-3LoHQ6 .secondary-2bzKEX {
    background-color: transparent !important;
    position: relative; }
    .roleRow-3LoHQ6 .secondary-2bzKEX:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .roleRow-3LoHQ6 .secondary-2bzKEX:hover:after {
      opacity: 1;
      transform: scale(1);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .roleRow-3LoHQ6 .secondary-2bzKEX:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
  .roleRow-3LoHQ6 .dragIcon-kQZ0Jv,
  .roleRow-3LoHQ6 .editButton-2P76Jg {
    opacity: 0;
    transition: var(--default-time) var(--default-animation); }
  .roleRow-3LoHQ6:hover .dragIcon-kQZ0Jv,
  .roleRow-3LoHQ6:hover .editButton-2P76Jg {
    opacity: 1; }

/* SERVER SETTINGS -> ROLES -> NEW -> EDIT ROLE */
.page-15bX59 {
  width: 100%;
  min-width: 100%; }
  .page-15bX59 .sidebar-3K3Z4C,
  .page-15bX59 .contentContainer-3hXFtK {
    position: relative; }
  .page-15bX59 .sidebar-3K3Z4C {
    margin-left: 40px;
    border-right-color: var(--card-border-color); }
    .page-15bX59 .sidebar-3K3Z4C .list-1AJFv_ {
      padding: 0 16px 96px 16px;
      background-color: transparent;
      border: none; }
    .page-15bX59 .sidebar-3K3Z4C .titleContainer-3fPic2 {
      margin-left: 0;
      margin-right: 0;
      padding: 0 8px 16px;
      background-color: var(--main-color); }
      .page-15bX59 .sidebar-3K3Z4C .titleContainer-3fPic2 .titleText-3LapIU {
        font-size: 16px;
        text-transform: none; }
    .page-15bX59 .sidebar-3K3Z4C .item-3XjbnG {
      width: auto;
      padding: 0 12px;
      border-radius: 16px; }
      .page-15bX59 .sidebar-3K3Z4C .item-3XjbnG:before {
        display: none; }
    .page-15bX59 .sidebar-3K3Z4C .roleDot-2a4Pv7 {
      border: none; }
  .page-15bX59 .contentContainer-3hXFtK {
    left: 0;
    flex: 1; }
  .page-15bX59 .contentWidth-3aWel5 {
    width: auto;
    min-width: auto;
    max-width: none;
    padding-right: 82px; }
  .page-15bX59 .header-JUTO-g {
    margin-left: 0;
    margin-right: 0;
    padding: 0;
    background-color: var(--main-color);
    transition: var(--default-time) var(--default-animation) border-bottom-color; }
    .page-15bX59 .header-JUTO-g.stickyHeaderElevated-dNSSrJ {
      box-shadow: none; }
    .page-15bX59 .header-JUTO-g .titleText-35PD5k {
      font-size: 16px;
      text-transform: none; }
    .page-15bX59 .header-JUTO-g + div + .divider-5Xhahz {
      display: none; }
  .page-15bX59 .tabBar-3DfKkN {
    margin-left: 0;
    border-bottom: 1px solid var(--card-border-color); }
    .page-15bX59 .tabBar-3DfKkN .item-3XjbnG {
      margin: 0 8px;
      padding: 16px 0;
      background-color: transparent !important;
      border-radius: 0;
      border-bottom: none; }
      .page-15bX59 .tabBar-3DfKkN .item-3XjbnG:first-of-type {
        margin: 0 8px 0 0; }
      .page-15bX59 .tabBar-3DfKkN .item-3XjbnG.selected-g-kMVV {
        position: relative;
        background-color: transparent !important; }
        .page-15bX59 .tabBar-3DfKkN .item-3XjbnG.selected-g-kMVV:after {
          position: absolute;
          content: " ";
          width: 100%;
          height: 3px;
          left: 0;
          right: 0;
          bottom: 0;
          margin: 0 auto;
          background: var(--tab-border-color);
          border-radius: 3px 3px 0 0;
          transition: var(--default-time) ease all; }
  .page-15bX59 .searchContainer-2kJ46v,
  .page-15bX59 .searchContainer-23hFke {
    margin-top: 16px;
    padding-bottom: 16px;
    border-bottom: 1px solid var(--card-border-color); }
  .page-15bX59 .previewContainer-1xQAsw {
    background-color: transparent;
    border-radius: var(--card-radius-big);
    border: none; }
    .page-15bX59 .previewContainer-1xQAsw .messageContainer-3a6gLR {
      background-color: var(--chat-color); }
  .page-15bX59 .permissionsForm-xrzuUy .container-1zDvAE {
    margin-bottom: 20px; }
  .page-15bX59 + .toolsContainer-25FL6V {
    position: absolute;
    top: 0;
    right: 0;
    z-index: 2; }

.list-1AJFv_ {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

/* SERVER SETTINGS -> ROLES -> VIEW AS ROLE */
.container-3LUQwT {
  padding: 0;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .container-3LUQwT .container-2oNtJn {
    height: auto;
    padding: 8px;
    background-color: transparent;
    border-radius: 0;
    border-bottom: 1px solid var(--popout-header-border); }
    .container-3LUQwT .container-2oNtJn .inner-2pOSmK {
      border-radius: 16px;
      background-color: var(--input-color); }
  .container-3LUQwT .list-1MBHYC {
    margin-top: 0;
    padding: 0; }
    .container-3LUQwT .list-1MBHYC .item-1BCeuB {
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .container-3LUQwT .list-1MBHYC .item-1BCeuB:hover {
        background-color: var(--menu-item-hover); }

/* SERVER SETTINGS -> EMOJI */
.emojiRow-1aPaM- {
  padding: 0 16px; }
  .emojiRow-1aPaM-:after {
    width: calc(100% - 56px); }
  .emojiRow-1aPaM-:hover .emojiAliasPlaceholder-3oShSx {
    opacity: 0; }
  .emojiRow-1aPaM-:nth-child(2):last-of-type {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big); }
  .emojiRow-1aPaM- .emojiAliasInput-3ZhdKx {
    border-bottom: none !important; }
    .emojiRow-1aPaM- .emojiAliasInput-3ZhdKx:before, .emojiRow-1aPaM- .emojiAliasInput-3ZhdKx:after {
      display: none; }
    .emojiRow-1aPaM- .emojiAliasInput-3ZhdKx:focus-within + .emojiAliasPlaceholder-3oShSx {
      opacity: 0; }
    .emojiRow-1aPaM- .emojiAliasInput-3ZhdKx .emojiInput-B8MGXq {
      padding: 0 8px;
      border-radius: var(--input-radius);
      font-size: 16px;
      background-color: var(--input-color); }
  .emojiRow-1aPaM- .emojiAliasPlaceholder-3oShSx {
    height: auto;
    margin-left: 8px;
    padding: 0;
    line-height: var(--input-height);
    color: var(--text-normal);
    transition: var(--default-time) var(--default-animation);
    overflow: visible; }
  .emojiRow-1aPaM- .emojiRemove-D9w3jo {
    right: -12px; }

.title-3hptVQ + .marginBottom40-fvAlAV .marginBottom4-1fdMNe {
  margin-bottom: 0;
  padding: 16px;
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
  border: 1px solid var(--card-border-color); }
  .title-3hptVQ + .marginBottom40-fvAlAV .marginBottom4-1fdMNe .description-30xx7u {
    font-weight: 600; }

/* SERVER SETTINGS -> STICKERS */
.upsellContainer-3UlEOE .colorWhite-rEQuAQ {
  --accent-button-action: #000;
  background-color: #fff !important; }

.tierHeader-3q9jIw {
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0; }
  .tierHeader-3q9jIw.tierHeaderUnlocked-1OpOLf, .tierHeader-3q9jIw.tierHeaderLocked-30MLlO {
    background-color: var(--card-color) !important;
    border: 1px solid var(--card-border-color); }
  .tierHeader-3q9jIw.tierHeaderWithoutCardBody-1iT8o_ {
    border-radius: var(--card-radius-big); }

.tierBody-1d3UiS {
  background-color: var(--card-color) !important;
  border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
  border: 1px solid var(--card-border-color);
  border-top: none; }

.tierLock-1eabw6 {
  color: var(--interactive-normal); }

.wrapper-24fR1R {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

/* SERVER SETTINGS -> STICKERS -> UPLOAD */
.modalHeader-2KRhe7 + .formItem-1Vab1c {
  margin-top: 16px; }

.preview-x-26h- {
  border-radius: var(--card-radius-big);
  border: none; }
  .preview-x-26h- .previewDark-3Xp3UB {
    background-color: #202225; }
  .preview-x-26h- .previewLight-IOzFhi {
    background-color: #fff; }

.fileUpload-MFkgW2 {
  height: 33px;
  background-color: transparent !important;
  border-radius: 0;
  border: none !important;
  border-bottom: 1px solid var(--input-border-color) !important; }
  .fileUpload-MFkgW2 .fileUploadInput-tCSo4C {
    height: 32px;
    padding: 0; }
  .fileUpload-MFkgW2 .fileUploadButton-2rwYk6 {
    min-width: 88px !important;
    height: 30px !important;
    min-height: 30px !important;
    max-height: 30px !important;
    margin: 0; }

.emojiInputContainer-iEFcAP .emojiButton-2pmTD2 {
  margin-left: 0; }
.emojiInputContainer-iEFcAP .emojiText-R_5fDP {
  padding-left: 32px; }

/* SERVER SETTINGS -> AUDIT LOG */
.auditLog-1NVAY0 {
  margin-bottom: 0;
  border: none; }
  .auditLog-1NVAY0 .header-2pgFQm {
    position: relative;
    background-color: transparent;
    border-left: 1px solid var(--card-border-color);
    border-right: 1px solid var(--card-border-color); }
    .auditLog-1NVAY0 .header-2pgFQm:after {
      position: absolute;
      content: " ";
      width: 100%;
      height: 1px;
      right: 0;
      top: 0;
      background-color: var(--card-border-color); }
  .auditLog-1NVAY0 .divider-M3saWq {
    display: none; }
  .auditLog-1NVAY0 .changeDetails-1kMZqI {
    background-color: transparent !important;
    border-left: 1px solid var(--card-border-color);
    border-right: 1px solid var(--card-border-color); }
  .auditLog-1NVAY0:first-of-type .header-2pgFQm {
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
    border-top: 1px solid var(--card-border-color); }
    .auditLog-1NVAY0:first-of-type .header-2pgFQm:after {
      display: none; }
  .auditLog-1NVAY0:last-of-type .header-2pgFQm {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border-bottom: 1px solid var(--card-border-color); }
    .auditLog-1NVAY0:last-of-type .header-2pgFQm.headerExpanded-CUEwZ5 {
      border-radius: 0;
      border-bottom: none; }
  .auditLog-1NVAY0:last-of-type .changeDetails-1kMZqI:last-of-type {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border-bottom: 1px solid var(--card-border-color); }

.icon-2PiQ65:after {
  width: 9px;
  height: 9px;
  top: unset;
  left: unset;
  right: 2px;
  bottom: 2px;
  border-radius: 50%; }
.icon-2PiQ65.typeCreate--o_pRH:after {
  background: #389c59; }
.icon-2PiQ65.typeUpdate-34INPr:after {
  background: #ec9d1a; }
.icon-2PiQ65.typeDelete-1AYMTg:after {
  background: #9d3235; }

/* SERVER SETTINGS -> INTEGRATIONS */
.iconWrapper-lS1uig {
  background-color: var(--menu-item-select); }

.footerPlaceholder-3sjNqI .card-16VQ8C.card-o7rAq- {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }

.card-3IImnr {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }
  .card-3IImnr .header-146Xl5 {
    border-bottom: 1px solid var(--card-border-color); }
    .card-3IImnr .header-146Xl5:only-child {
      border-bottom: none; }
  .card-3IImnr .body-1zRX82 {
    padding: 16px; }
    .card-3IImnr .body-1zRX82 .divider-3LgWDL {
      display: none; }

.card-1o0mns {
  padding: 0;
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }
  .card-1o0mns > .flex-2S1XBF > .flex-2S1XBF:first-child {
    padding: 16px;
    border-bottom: 1px solid var(--card-border-color); }
  .card-1o0mns .divider-3LgWDL {
    display: none; }
  .card-1o0mns .permissionHeader-asGFgR {
    margin-top: 16px;
    padding: 0 16px; }
    .card-1o0mns .permissionHeader-asGFgR + .flex-2S1XBF {
      padding: 8px 16px 16px; }
  .card-1o0mns .rolePills-32B_DQ {
    margin-top: 8px;
    padding: 0 16px; }
  .card-1o0mns .permission-23FtuH {
    height: 24px;
    margin-top: 0; }
    .card-1o0mns .permission-23FtuH .check-2-1yhI, .card-1o0mns .permission-23FtuH .cross-22YsmA {
      top: 0;
      bottom: 0;
      margin: auto 8px auto 0; }
    .card-1o0mns .permission-23FtuH .colorStandard-21JIj7 {
      line-height: 24px; }

/* SERVER SETTINGS -> SERVER TEMPLATE */
.descriptionBox-1EKQKL {
  background-color: transparent;
  border-radius: var(--card-radius-big);
  border: 1px solid var(--card-border-color); }

/* SERVER SETTINGS -> COMMUNITY -> OVERVIEW */
.upsellContainer-2a5eMP {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .upsellContainer-2a5eMP .upsellFooter-3M1V33 {
    padding: 8px;
    background-color: transparent;
    border-top: 1px solid var(--card-border-color); }

/* SERVER SETTINGS -> COMMUNITY -> SERVER INSIGHTS */
.backgroundAccent-2YeFtZ {
  padding: 16px;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  color: var(--header-secondary); }

.developerPortalCtaWrapper-2PniQs {
  padding-bottom: 16px;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

/* SERVER SETTINGS -> COMMUNITY -> PARTNER PROGRAM */
.featureCard-3XHbjy {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.checklistContainer-12xGp5 {
  width: 100%;
  margin: 0;
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .checklistContainer-12xGp5 .checklistHeader-3liG7E {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
  .checklistContainer-12xGp5 .checklistItem-1gWPPD {
    position: relative;
    border-bottom: none; }
    .checklistContainer-12xGp5 .checklistItem-1gWPPD:after {
      position: absolute;
      content: " ";
      width: calc(100% - 52px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .checklistContainer-12xGp5 .checklistItem-1gWPPD:last-of-type:after {
      display: none; }
    .checklistContainer-12xGp5 .checklistItem-1gWPPD + .separator-2qVfIV {
      display: none; }

/* SERVER SETTINGS -> COMMUNITY -> DISCOVERY */
.checklist-Asy_56 {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .checklist-Asy_56 .header-Wl8ec- {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500; }
  .checklist-Asy_56 .checklistItem-1gWPPD {
    position: relative;
    border-bottom: none; }
    .checklist-Asy_56 .checklistItem-1gWPPD:after {
      position: absolute;
      content: " ";
      width: calc(100% - 52px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .checklist-Asy_56 .checklistItem-1gWPPD:last-of-type:after {
      display: none; }
    .checklist-Asy_56 .checklistItem-1gWPPD + .separator-1py8Bj {
      display: none; }

.card-3_CqkU {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  box-shadow: none !important; }

/* SERVER SETTINGS -> COMMUNITY -> MEMBERSHIP SCREENING */
.enableContainer-1J91Aq {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }

.previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 {
  width: auto; }
  .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t {
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ;
    padding: 0; }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .settingsFormFieldWrapper-U99c9i.flex-2S1XBF {
      margin: 16px; }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .settingsFormFieldWrapper-U99c9i:not(.flex-2S1XBF) {
      padding: 0;
      background-color: transparent;
      border: none; }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .settingsLink-2BmKpa {
      padding: 8px;
      background-color: transparent;
      border-top: 1px solid var(--card-border-color); }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .h5-2RwDNl {
      padding: 16px ;
      background-color: transparent;
      border-bottom: 1px solid var(--card-border-color);
      font-size: 1em;
      color: var(--card-header-text-color);
      font-weight: 500; }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .termsRow-dZXIM3 {
      padding: 16px;
      position: relative;
      border-bottom: none; }
      .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .termsRow-dZXIM3:after {
        position: absolute;
        content: " ";
        width: calc(100% - 44px);
        height: 1px;
        right: 0;
        bottom: 0;
        background-color: var(--card-border-color); }
      .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .termsRow-dZXIM3:last-of-type:after {
        display: none; }
      .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .termsRow-dZXIM3 .termsRowContent-2Qx-E5 {
        padding-left: 16px; }
    .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .checkbox-1unEG1 {
      margin-top: 0;
      padding: 8px;
      background-color: transparent;
      border-top: 1px solid var(--card-border-color); }
      .previewContainer-1L7bG- .editableFieldsContainer-1p_q_4 .settingsFormItem-25zW3t .checkbox-1unEG1.checkboxWrapperDisabled-2lYviP {
        opacity: 1; }

/* SERVER SETTINGS -> COMMUNITY -> WELCOME SCREEN */
.enableContainer-2MEsKV {
  padding: 16px ;
  background-color: transparent;
  border-bottom: 1px solid var(--card-border-color);
  font-size: 1em;
  color: var(--card-header-text-color);
  font-weight: 500;
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
  border: 1px solid var(--card-border-color); }

.previewContainer-29oeA6 {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ;
  border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
  border-top: none; }
  .previewContainer-29oeA6 .descriptionWrapper-Maz2Cn .inputWrapper-1YNMmM {
    --input-height: 64px; }
  .previewContainer-29oeA6 .descriptionInput-2-jF56 {
    line-height: 32px; }
    .previewContainer-29oeA6 .descriptionInput-2-jF56[placeholder] {
      text-align: left; }
  .previewContainer-29oeA6 .welcomeChannel-_Q4qAA {
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }

.iconActiveLarger-2EZc1b {
  border-radius: 50%; }

.options-3Wncp7 {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .options-3Wncp7 .optionContainer-yOpaLq {
    margin-top: 0;
    border-radius: 0;
    background-color: transparent;
    position: relative;
    border-bottom: none; }
    .options-3Wncp7 .optionContainer-yOpaLq:after {
      position: absolute;
      content: " ";
      width: calc(100% - 48px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    .options-3Wncp7 .optionContainer-yOpaLq:last-of-type:after {
      display: none; }

.close-6m8kzT {
  background-color: transparent !important;
  position: relative;
  position: absolute; }
  .close-6m8kzT:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--md-ripple-color), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .close-6m8kzT:hover:after {
    opacity: 1;
    transform: scale(1.6);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .close-6m8kzT:active:after {
    background-color: hsla(var(--md-ripple-color), 0.2); }

.modalContents-CkPqoE {
  padding: 0; }
  .modalContents-CkPqoE .headerText-2VPbLb {
    margin: 0;
    padding: 16px 16px 0; }
    .modalContents-CkPqoE .headerText-2VPbLb + .formDescription-1gW_br {
      margin: 0;
      padding: 0 16px 16px;
      border-bottom: 1px solid var(--popout-header-border); }
  .modalContents-CkPqoE > div:not([class]) {
    padding: 16px 16px 0; }
    .modalContents-CkPqoE > div:not([class]) + div:not([class]) {
      padding: 0 16px 16px; }
  .modalContents-CkPqoE .emojiButtonContainer-1n1BNw {
    margin-top: 4px;
    padding: 0; }
  .modalContents-CkPqoE .channelDescriptionWrapper-1IPt5G .inputWrapper-1YNMmM {
    margin-left: 32px; }

/* SERVER SETTINGS -> COMMUNITY -> THREADS */
.info-1Vr1AV {
  padding: 16px;
  background-color: hsla(var(--accent-hsl), 0.1);
  border-radius: var(--card-radius-big);
  border-color: hsl(var(--accent-hsl)); }
  .info-1Vr1AV .infoIcon-3aR3CI {
    color: hsl(var(--accent-hsl)); }

.banner-2G2Kv6 {
  border-radius: var(--card-radius-big); }

.boxes-2F9BmS {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  grid-gap: 0 16px; }
  .boxes-2F9BmS .box-J4N4jE {
    width: auto;
    background-color: var(--card-color) ;
    border-radius: var(--card-radius-big) ;
    border: 1px solid var(--card-border-color) ; }

/* SERVER SETTINGS -> SERVER BOOST STATUS */
.tier-3H4BXk .tierHeader-rlkkJd {
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0; }
  .tier-3H4BXk .tierHeader-rlkkJd.tierHeaderLocked-1a2opw {
    padding: 16px ;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color);
    font-size: 1em;
    color: var(--card-header-text-color);
    font-weight: 500;
    border: 1px solid var(--card-border-color); }
  .tier-3H4BXk .tierHeader-rlkkJd.tierHeaderUnlocked-2RhWqn {
    padding: 16px; }
  .tier-3H4BXk .tierHeader-rlkkJd .tierHeaderContent-2-YfvN {
    padding: 0; }
    .tier-3H4BXk .tierHeader-rlkkJd .tierHeaderContent-2-YfvN .tierLock-1oFMOZ path {
      d: path("M18 8h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2zM9 6c0-1.66 1.34-3 3-3s3 1.34 3 3v2H9V6zm9 14H6V10h12v10zm-6-3c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2z") !important; }
.tier-3H4BXk .tierBody-x9kBBp {
  background-color: transparent !important;
  border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
  border: 1px solid var(--card-border-color);
  border-top: none; }

/* SERVER SETTINGS -> USER MANAGEMENT -> MEMBERS */
.content-28mbXd div:not([class]):nth-child(2) .divider-3LgWDL[style="margin-bottom: -1px;"] {
  display: none; }

.container-2oNtJn {
  height: 32px;
  background-color: var(--input-color);
  border-radius: 16px; }
  .container-2oNtJn .inner-2pOSmK {
    padding: 0; }
    .container-2oNtJn .inner-2pOSmK .input-2m5SfJ {
      height: 32px;
      margin: 0;
      padding: 0 4px 0 12px; }
    .container-2oNtJn .inner-2pOSmK .iconLayout-3Bjizv {
      width: 32px;
      height: 32px;
      margin-right: 8px; }

.container-2O1UgZ {
  padding: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  border: none;
  box-shadow: var(--shadow-3dp);
  animation: top-pop-out 400ms var(--default-animation); }
  .container-2O1UgZ .container-2oNtJn {
    margin: 12px 8px; }
  .container-2O1UgZ .list-3cyRKU {
    margin-top: 0;
    border-top: 1px solid var(--card-border-color); }
    .container-2O1UgZ .list-3cyRKU .content-28mbXd {
      height: auto !important; }
    .container-2O1UgZ .list-3cyRKU .item-1BCeuB {
      margin-bottom: 0;
      border-radius: 0;
      color: var(--menu-item-text-color);
      transition: var(--default-time) var(--default-animation) background-color; }
      .container-2O1UgZ .list-3cyRKU .item-1BCeuB:hover {
        background-color: var(--menu-item-hover); }
      .container-2O1UgZ .list-3cyRKU .item-1BCeuB.selected-22ukbQ, .container-2O1UgZ .list-3cyRKU .item-1BCeuB.selectedBrand-1AtwYE {
        background-color: var(--menu-item-select); }

body:active .container-2O1UgZ:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

.member-2cj2PI {
  padding: 16px; }
  .member-2cj2PI:after {
    width: calc(100% - 66px); }
  .member-2cj2PI:nth-child(3) {
    margin-top: 24px;
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
    border-top: 1px solid var(--card-border-color); }
    .member-2cj2PI:nth-child(3):last-of-type {
      border-radius: var(--card-radius-big); }
  .member-2cj2PI:last-of-type {
    margin-bottom: 32px; }
  .member-2cj2PI .roleWrapper-2IhvNd {
    overflow: visible; }
  .member-2cj2PI .button-f2h6uQ {
    height: 32px;
    background-color: transparent !important;
    position: relative; }
    .member-2cj2PI .button-f2h6uQ:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .member-2cj2PI .button-f2h6uQ:hover:after {
      opacity: 1;
      transform: scale(1.1);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .member-2cj2PI .button-f2h6uQ:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }

.overflowRolesPopout-1Puiuq {
  width: 240px;
  padding: 0;
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .overflowRolesPopout-1Puiuq .overflowRolesPopoutHeader-1JoWg7 {
    margin-bottom: 0;
    padding: 16px;
    border-bottom: 1px solid var(--popout-header-border); }
  .overflowRolesPopout-1Puiuq .overflowRolesPopoutHeaderText-3HyHGv {
    font-size: 14px;
    text-transform: none; }
  .overflowRolesPopout-1Puiuq .root-jbEB5E {
    padding: 8px; }

/* SERVER SETTINGS -> USER MANAGEMENT -> INVITES */
.headerSection-2X_FUZ {
  padding-bottom: 0; }
  .headerSection-2X_FUZ .divider-3LgWDL {
    display: none; }
  .headerSection-2X_FUZ .horizontal-112GEH {
    padding: 16px;
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
    border: 1px solid var(--card-border-color); }

.inviteSettingsInviteRow-1rZeIM {
  height: 68px;
  padding: 16px; }
  .inviteSettingsInviteRow-1rZeIM:after {
    width: calc(100% - 64px); }
  .inviteSettingsInviteRow-1rZeIM .text-3t4Eyu .user-32vk-K .avatar-29vZjw {
    position: absolute;
    width: 34px !important;
    height: 34px !important;
    top: 0;
    bottom: 0;
    margin: auto 0; }
  .inviteSettingsInviteRow-1rZeIM .text-3t4Eyu .user-32vk-K .username-MRMnpj {
    margin-left: 48px; }
  .inviteSettingsInviteRow-1rZeIM .text-3t4Eyu .colorHeaderSecondary-g5teka {
    margin-left: 48px; }
  .inviteSettingsInviteRow-1rZeIM .revokeInvite-XuVwn4 {
    right: -16px; }

/* SERVER SETTINGS -> USER MANAGEMENT -> BANS */
.bannedUser-1IalTM {
  padding: 16px; }
  .bannedUser-1IalTM:after {
    width: calc(100% - 64px); }
  .bannedUser-1IalTM:nth-child(3) {
    border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
    border-top: 1px solid var(--card-border-color); }
    .bannedUser-1IalTM:nth-child(3):last-of-type {
      border-radius: var(--card-radius-big); }
  .bannedUser-1IalTM:last-of-type {
    margin-bottom: 32px; }

.bannedUserModal-3RJCOV {
  min-height: 180px; }
  .bannedUserModal-3RJCOV .content-1x7qW2 {
    padding: 0 !important; }
    .bannedUserModal-3RJCOV .content-1x7qW2::-webkit-scrollbar {
      width: 0px !important; }
    .bannedUserModal-3RJCOV .content-1x7qW2 .horizontal-112GEH {
      padding: 16px;
      justify-content: left;
      border-bottom: 1px solid var(--card-border-color); }
    .bannedUserModal-3RJCOV .content-1x7qW2 .reasonHeader-2etdjy {
      margin-top: 0;
      padding: 16px;
      font-size: 14px;
      text-transform: none; }
      .bannedUserModal-3RJCOV .content-1x7qW2 .reasonHeader-2etdjy + .size14-3fJ-ot {
        padding: 0 16px 16px; }

/* SERVER SETTINGS -> LISTS */
.emojiRow-1aPaM-,
.member-2cj2PI,
.inviteSettingsInviteRow-1rZeIM,
.bannedUser-1IalTM {
  border-left: 1px solid var(--card-border-color);
  border-right: 1px solid var(--card-border-color);
  box-shadow: none !important; }
  .emojiRow-1aPaM-:before,
  .member-2cj2PI:before,
  .inviteSettingsInviteRow-1rZeIM:before,
  .bannedUser-1IalTM:before {
    display: none; }
  .emojiRow-1aPaM-:after,
  .member-2cj2PI:after,
  .inviteSettingsInviteRow-1rZeIM:after,
  .bannedUser-1IalTM:after {
    position: absolute;
    content: " ";
    height: 1px;
    bottom: 0;
    right: 0;
    background-color: var(--card-border-color); }
  .emojiRow-1aPaM-:last-of-type,
  .member-2cj2PI:last-of-type,
  .inviteSettingsInviteRow-1rZeIM:last-of-type,
  .bannedUser-1IalTM:last-of-type {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border-bottom: 1px solid var(--card-border-color); }
    .emojiRow-1aPaM-:last-of-type:after,
    .member-2cj2PI:last-of-type:after,
    .inviteSettingsInviteRow-1rZeIM:last-of-type:after,
    .bannedUser-1IalTM:last-of-type:after {
      display: none; }

/* SERVER SETTINGS -> SIDEBAR ICONS */
.side-2ur1Qk .item-3XjbnG[aria-controls="overview-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/dashboard.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/dashboard.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="permissions-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/lock_open.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/lock_open.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="roles-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/people.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/people.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="emoji-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/emoji.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="stickers-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/sticker-emoji.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/sticker-emoji.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="moderation-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/security.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/security.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="audit_log-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/audit_log.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/audit_log.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="integrations-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/integrations.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/integrations.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="widget-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/widgets.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/widgets.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="guild_templates-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/template.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/template.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="vanity_url-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/link.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/link.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="community-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/dashboard.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/dashboard.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="analytics-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/analytics.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/analytics.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="partner-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/partner_program.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/partner_program.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="discovery-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/discovery.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/discovery.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="member_verification-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/verified_user.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/verified_user.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="community_welcome-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/partner_program.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/partner_program.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="threads-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/chat.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/chat.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="guild_premium-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/server_boost.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/server_boost.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="members-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/people.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/people.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="instant_invites-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/person_add.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/person_add.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="bans-tab"]:before {
  background-color: var(--text-normal);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/hammer.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/hammer.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }
.side-2ur1Qk .item-3XjbnG[aria-controls="delete-tab"]:before {
  background-color: var(--alert-color);
  -webkit-mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/delete.svg);
  mask-image: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/outline/delete.svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat; }

/* SERVER SETTINGS -> ROLES */
.scroller-3_YDR2 {
  background-color: transparent; }

@media (min-width: 1148px) {
  .sidebarScrollable-2mW9Ls + .content-2ssVKB {
    /*max-width: 100%;*/
    max-width: calc(100% - 232px);
    margin-left: 16px; } }
.role-3pGE29 {
  padding: 0 10px !important; }

/*
 *
 *	PINNED MESSAGES
 *
 */
.iconBadge-3Mmg92 {
  top: -2px;
  right: 4px;
  background-color: hsl(var(--accent-hsl));
  box-shadow: var(--shadow-1dp); }

.messagesPopoutWrap-3zryHW {
  max-height: 80vh !important;
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ;
  animation: top-pop-out 400ms var(--default-animation); }
  .messagesPopoutWrap-3zryHW .header-1w9Q93 {
    padding: 0 16px;
    background-color: transparent;
    border-bottom: 1px solid var(--popout-header-border);
    box-shadow: none; }
    .messagesPopoutWrap-3zryHW .header-1w9Q93 .wrapper-1HSdhi {
      height: 52px;
      line-height: 52px; }
  .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI {
    padding: 0 8px 20px 8px; }
    .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C {
      margin: 0;
      background-color: transparent;
      border: none; }
      .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN {
        margin: 16px 8px 0 52px;
        padding: 12px !important;
        background-color: var(--message-color-alt) !important;
        border-radius: var(--message-radius); }
        .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN:before, .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN:after {
          display: none; }
        .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN .avatar-2e8lTP {
          top: 0;
          left: -50px; }
        .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN .container-2sjPya {
          overflow: hidden;
          border-radius: var(--message-radius); }
      .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .actionButtons-2mNSAB {
        top: 22px;
        right: 12px; }
        .messagesPopoutWrap-3zryHW .messagesPopout-eVzQcI .messageGroupWrapper-1jf_7C .actionButtons-2mNSAB .jumpButton-1ZwI_j {
          border-radius: 9px; }

body:active .messagesPopoutWrap-3zryHW:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/*
 *
 *	COLOR PICKER
 *
 */
.colorPickerCustom-1swUKF {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important;
  border: none; }

/*
 *
 *	CREATE GROUP DM
 *
 */
.popout-3gby1q .header-1zd7se .marginTop20-2T8ZJx {
  margin-top: 8px; }
.popout-3gby1q .header-1zd7se .container-1SX9VC {
  background-color: var(--input-color);
  border-radius: 18px; }
  .popout-3gby1q .header-1zd7se .container-1SX9VC .inner-1NoIT5 {
    padding: 0; }
  .popout-3gby1q .header-1zd7se .container-1SX9VC .input-2FSSDe {
    margin: 0;
    padding: 0 12px;
    min-height: 36px; }
  .popout-3gby1q .header-1zd7se .container-1SX9VC .tag-15zcD_ {
    height: 28px;
    margin: 4px 0 0 4px;
    /*background-color: var(--menu-item-hover);*/
    border-radius: 14px;
    background-color: transparent;
    border: 1px solid var(--text-muted);
    color: var(--text-normal); }
    .popout-3gby1q .header-1zd7se .container-1SX9VC .tag-15zcD_ .close-3-lUJg {
      width: 18px;
      height: 18px;
      margin-left: 8px; }
      .popout-3gby1q .header-1zd7se .container-1SX9VC .tag-15zcD_ .close-3-lUJg path {
        d: path("M12,2C17.53,2 22,6.47 22,12C22,17.53 17.53,22 12,22C6.47,22 2,17.53 2,12C2,6.47 6.47,2 12,2M15.59,7L12,10.59L8.41,7L7,8.41L10.59,12L7,15.59L8.41,17L12,13.41L15.59,17L17,15.59L13.41,12L17,8.41L15.59,7Z"); }
.popout-3gby1q .friendWrapper-2x5j0A {
  margin: 0;
  padding: 0; }
  .popout-3gby1q .friendWrapper-2x5j0A .friend-8ZraY7 {
    padding: 6px 12px;
    border-radius: 0;
    transition: var(--default-time) var(--default-animation) background-color; }
    .popout-3gby1q .friendWrapper-2x5j0A .friend-8ZraY7.friendSelected-3cwmD7 {
      background-color: var(--menu-item-hover);
      color: var(--menu-item-text-color); }
.popout-3gby1q .footerSeparator-b6VH1V {
  margin: 0;
  background-color: var(--popout-header-border);
  box-shadow: none !important; }
.popout-3gby1q .footer-C9oLp9 {
  padding: 8px; }

/*
 *
 *	INBOX
 *
 */
.container-2ebMPP {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }

/* MENTIONS -> HEADER */
.header-145e10,
.header-1w9Q93 {
  height: 52px;
  padding: 0 16px;
  background-color: var(--popout-color);
  border-bottom: 1px solid var(--popout-header-border); }
  .header-145e10 .tab-TRrPC8,
  .header-1w9Q93 .tab-TRrPC8 {
    height: 100%;
    margin: 0;
    padding: 0 8px; }
    .header-145e10 .tab-TRrPC8:hover, .header-145e10 .tab-TRrPC8.active-1grPyy,
    .header-1w9Q93 .tab-TRrPC8:hover,
    .header-1w9Q93 .tab-TRrPC8.active-1grPyy {
      background-color: transparent !important; }
    .header-145e10 .tab-TRrPC8.active-1grPyy,
    .header-1w9Q93 .tab-TRrPC8.active-1grPyy {
      position: relative;
      background-color: transparent !important; }
      .header-145e10 .tab-TRrPC8.active-1grPyy:after,
      .header-1w9Q93 .tab-TRrPC8.active-1grPyy:after {
        position: absolute;
        content: " ";
        width: 90%;
        height: 3px;
        left: 0;
        right: 0;
        bottom: 0;
        margin: 0 auto;
        background: var(--tab-border-color);
        border-radius: 3px 3px 0 0;
        transition: var(--default-time) ease all; }
    .header-145e10 .tab-TRrPC8:first-child,
    .header-1w9Q93 .tab-TRrPC8:first-child {
      margin-right: 8px; }
  .header-145e10 .secondary-2bzKEX,
  .header-1w9Q93 .secondary-2bzKEX {
    margin-top: 10px; }

/* INBOX -> MENTIONS */
.container-iA3Qrz {
  padding-left: 8px;
  padding-right: 8px; }
  .container-iA3Qrz:first-child {
    margin-top: 16px; }
  .container-iA3Qrz .channelHeader-DFRX8q {
    padding: 12px 16px;
    background-color: var(--message-color-alt);
    border-radius: var(--message-radius) var(--message-radius) 0 0;
    border-bottom: 1px solid var(--card-border-color); }
  .container-iA3Qrz .messageContainer-3VTXBC {
    background-color: var(--message-color-alt);
    border-radius: 0 0 var(--message-radius) var(--message-radius); }
    .container-iA3Qrz .messageContainer-3VTXBC .wrapper-30-Nkg.cozy-VmLDNB {
      margin: 0 0 0 80px;
      border-radius: var(--message-radius);
      overflow: visible; }
      .container-iA3Qrz .messageContainer-3VTXBC .wrapper-30-Nkg.cozy-VmLDNB:before, .container-iA3Qrz .messageContainer-3VTXBC .wrapper-30-Nkg.cozy-VmLDNB:after {
        display: none; }
      .container-iA3Qrz .messageContainer-3VTXBC .wrapper-30-Nkg.cozy-VmLDNB .avatar-2e8lTP {
        top: 0;
        left: -50px; }
    .container-iA3Qrz .messageContainer-3VTXBC .wrapper-30-Nkg .container-2sjPya {
      overflow: hidden; }

/* INBOX -> UNREADS */
.channel-3NJZ1V {
  padding-top: 16px; }
  .channel-3NJZ1V .channelHeader-DFRX8q {
    padding: 12px 16px 12px 42px;
    background-color: var(--message-color-alt);
    border-radius: var(--message-radius) var(--message-radius) 0 0;
    border-bottom: 1px solid var(--card-border-color); }
    .channel-3NJZ1V .channelHeader-DFRX8q:only-child {
      border-radius: var(--message-radius);
      border-bottom: none; }
    .channel-3NJZ1V .channelHeader-DFRX8q .collapseButton-39-IRc {
      left: 12px;
      cursor: pointer; }
    .channel-3NJZ1V .channelHeader-DFRX8q .button-1_oXub {
      background-color: var(--menu-item-hover); }
      .channel-3NJZ1V .channelHeader-DFRX8q .button-1_oXub:hover {
        background-color: var(--menu-item-select); }
  .channel-3NJZ1V .messages-23can0 {
    padding: 16px;
    background-color: var(--message-color-alt);
    border-radius: 0 0 var(--message-radius) var(--message-radius); }
    .channel-3NJZ1V .messages-23can0 .wrapper-30-Nkg.cozy-VmLDNB {
      overflow: visible; }
      .channel-3NJZ1V .messages-23can0 .wrapper-30-Nkg.cozy-VmLDNB .avatar-2e8lTP {
        left: -50px; }
      .channel-3NJZ1V .messages-23can0 .wrapper-30-Nkg.cozy-VmLDNB.groupStart-3Mlgv1 {
        margin: 16px 0 0 48px; }
      .channel-3NJZ1V .messages-23can0 .wrapper-30-Nkg.cozy-VmLDNB:not(.groupStart-3Mlgv1) {
        margin: -8px 0 0 48px; }

/*
 *
 *	SEARCH
 *
 */
.container-2McqkF {
  max-height: 80vh;
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important;
  overflow-y: auto;
  transform: translate(0, -4px);
  animation: top-pop-out 400ms var(--default-animation); }
  .container-2McqkF .resultsGroup-1BPR25:before {
    display: none; }
  .container-2McqkF .resultsGroup-1BPR25 .header-3A13BX {
    color: var(--text-normal);
    font-size: 14px;
    text-transform: none; }
  .container-2McqkF .resultsGroup-1BPR25 .searchLearnMore-7__o_n a,
  .container-2McqkF .resultsGroup-1BPR25 .searchClearHistory-2Be-92 {
    color: var(--text-normal); }
  .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO {
    margin: 0 !important;
    padding: 0 20px !important;
    border-radius: 0 !important; }
    .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO:after {
      background: transparent !important; }
    .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO:hover {
      background: var(--menu-item-hover) !important; }
    .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO.selected-rZcOL- {
      background: var(--menu-item-select) !important; }
      .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO.selected-rZcOL-:after {
        width: 70px;
        background: linear-gradient(90deg, rgba(35, 38, 42, 0), var(--menu-item-hover) 50%) !important; }
    .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO .filter-5YbOzJ {
      color: var(--text-normal); }
    .container-2McqkF .resultsGroup-1BPR25 .option-2KkUJO .answer-2fBfuP {
      color: var(--text-muted); }
  .container-2McqkF .queryContainer-ZunrLZ {
    border-bottom-color: var(--popout-header-border) !important; }
    .container-2McqkF .queryContainer-ZunrLZ.focused-2FU0YH {
      background-color: transparent !important; }

.keybindShortcut-3zF1P9 {
  height: 24px; }
  .keybindShortcut-3zF1P9 span, .keybindShortcut-3zF1P9 span:active {
    height: 100%;
    padding: 0 6px;
    line-height: 24px;
    border-radius: 12px;
    box-shadow: none !important;
    border: none !important; }

body:active .container-2McqkF:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/* SEARCH -> RESULTS */
.searchResultsWrap-5RVOkx {
  background-color: var(--main-color);
  /* SEARCH -> RESULTS -> HEADER */
  /* SEARCH -> RESULTS -> MESSAGES */ }
  .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh {
    padding: 0 16px;
    background-color: transparent;
    border-bottom: 1px solid var(--separator-color); }
    .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh .tab-2j5AEF {
      height: 100%;
      line-height: 100%;
      border-radius: 0; }
      .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh .tab-2j5AEF:hover, .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh .tab-2j5AEF.selected-2LAck8 {
        background-color: transparent; }
      .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh .tab-2j5AEF.selected-2LAck8 {
        position: relative;
        background-color: transparent !important; }
        .searchResultsWrap-5RVOkx .searchHeader-1r_ZSh .tab-2j5AEF.selected-2LAck8:after {
          position: absolute;
          content: " ";
          width: 90%;
          height: 3px;
          left: 0;
          right: 0;
          bottom: 0;
          margin: 0 auto;
          background: var(--tab-border-color);
          border-radius: 3px 3px 0 0;
          transition: var(--default-time) ease all; }
  .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB {
    height: 100%; }
    .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB .item-3XjbnG {
      height: 100%;
      margin: 0 0 0 8px;
      padding: 0 8px;
      line-height: 55px;
      border-radius: 0; }
      .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB .item-3XjbnG:hover:not(.disabled-1nofHP), .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB .item-3XjbnG.selected-g-kMVV {
        background-color: transparent; }
      .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB .item-3XjbnG.selected-g-kMVV {
        position: relative;
        background-color: transparent !important; }
        .searchResultsWrap-5RVOkx .searchHeaderTabList-3CZMQB .item-3XjbnG.selected-g-kMVV:after {
          position: absolute;
          content: " ";
          width: 80%;
          height: 3px;
          left: 0;
          right: 0;
          bottom: 0;
          margin: 0 auto;
          background: var(--tab-border-color);
          border-radius: 3px 3px 0 0;
          transition: var(--default-time) ease all; }
  .searchResultsWrap-5RVOkx .scroller-3iiyhZ {
    padding: 8px; }
  .searchResultsWrap-5RVOkx .channelName-3w2Y3c {
    padding: 8px 8px 8px 12px;
    background-color: transparent;
    color: var(--card-header-text-color); }
  .searchResultsWrap-5RVOkx .searchResult-O9NDji {
    background-color: transparent;
    border-radius: 0; }
    .searchResultsWrap-5RVOkx .searchResult-O9NDji .wrapper-30-Nkg {
      margin: 0 8px 0 60px;
      padding: 12px !important;
      border-radius: var(--message-radius); }
      .searchResultsWrap-5RVOkx .searchResult-O9NDji .wrapper-30-Nkg:before, .searchResultsWrap-5RVOkx .searchResult-O9NDji .wrapper-30-Nkg:after {
        display: none; }
      .searchResultsWrap-5RVOkx .searchResult-O9NDji .wrapper-30-Nkg .avatar-2e8lTP {
        top: 0;
        left: -50px; }
  .searchResultsWrap-5RVOkx .buttonsContainer-Nmgy7x {
    top: 16px;
    right: 18px; }
    .searchResultsWrap-5RVOkx .buttonsContainer-Nmgy7x .button-cfOvv- {
      padding: 4px 8px;
      border-radius: 12px; }

/*
 *
 *	USER POPOUT
 *
 */
.userPopout-2j1gM4 {
  position: relative;
  width: 280px;
  max-height: 90vh;
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .userPopout-2j1gM4 .headerNormal-1mX3KY {
    background-color: var(--popout-color-alt); }
  .userPopout-2j1gM4 .banner-1YaD3N {
    border-radius: var(--popout-radius-big) var(--popout-radius-big) 0 0; }
  .userPopout-2j1gM4 .avatar-2Vndt_ {
    background-color: transparent;
    border: none;
    /*box-shadow: var(--shadow-3dp);*/ }
  .userPopout-2j1gM4 .avatarHint-k7pYop {
    top: 0;
    left: 0; }
  .userPopout-2j1gM4 .avatarWrapper-eenWra {
    left: 12px; }
  .userPopout-2j1gM4 .headerTop-3GPUSF {
    padding: 54px 12px 12px;
    background-color: transparent;
    border-bottom: 1px solid var(--card-border-color); }
    .userPopout-2j1gM4 .headerTop-3GPUSF .headerTagUsernameBase-12nwcw {
      overflow-y: hidden; }
    .userPopout-2j1gM4 .headerTop-3GPUSF .discrimBase-1PEDoA {
      margin-left: 2px;
      font-weight: 400; }
    .userPopout-2j1gM4 .headerTop-3GPUSF .colorLink-2apWfY {
      color: hsl(var(--accent-hsl)); }
  .userPopout-2j1gM4 .customStatus-3XAoF9 {
    margin-bottom: 0;
    padding: 16px 12px 12px; }
  .userPopout-2j1gM4 .applicationInstallButton-taCWKH {
    width: calc(100% - 24px);
    margin: 12px 12px 0; }
  .userPopout-2j1gM4 .aboutMeSection-PUghFQ {
    margin-bottom: 0;
    padding: 12px;
    border-bottom: 1px solid var(--card-border-color); }
    .userPopout-2j1gM4 .aboutMeSection-PUghFQ .aboutMeTitle-3pjiS7 {
      font-size: 14px;
      text-transform: none; }
    .userPopout-2j1gM4 .aboutMeSection-PUghFQ .aboutMeBody-1J8rhz {
      display: block; }
  .userPopout-2j1gM4 .activity-fViXj7 {
    padding: 16px; }
    .userPopout-2j1gM4 .activity-fViXj7 .iconButton-1li_a3 {
      padding: 0; }
  .userPopout-2j1gM4 .activity-3v9l4T {
    padding: 12px;
    background-color: transparent; }
    .userPopout-2j1gM4 .activity-3v9l4T .iconButton-1li_a3 {
      padding: 0 !important; }
  .userPopout-2j1gM4 .assetsLargeImage-8U5dlz,
  .userPopout-2j1gM4 .gameIcon-1mDo1J {
    border-radius: var(--avatar-radius); }
  .userPopout-2j1gM4 .body-2wLx-E {
    padding: 0;
    padding-right: 0 !important; }
    .userPopout-2j1gM4 .body-2wLx-E.scrollerSeparator-CHLxyV {
      box-shadow: none; }
    .userPopout-2j1gM4 .body-2wLx-E .divider-1wtgZ3 {
      display: none; }
    .userPopout-2j1gM4 .body-2wLx-E .bodyTitle-2Az3VQ,
    .userPopout-2j1gM4 .body-2wLx-E .headerText-3g1XK9,
    .userPopout-2j1gM4 .body-2wLx-E .PronounDB-style-header {
      font-size: 14px;
      text-transform: none; }
    .userPopout-2j1gM4 .body-2wLx-E .PronounDB-style-container {
      margin-bottom: 16px;
      flex-direction: column;
      align-items: flex-start; }
      .userPopout-2j1gM4 .body-2wLx-E .PronounDB-style-container .PronounDB-style-header {
        margin-bottom: 8px; }
      .userPopout-2j1gM4 .body-2wLx-E .PronounDB-style-container .PronounDB-style-tag {
        margin-left: 0;
        font-weight: 500; }
  .userPopout-2j1gM4 .bodyInnerWrapper-2bQs1k {
    padding: 12px;
    background-color: transparent; }
  .userPopout-2j1gM4 .activity-1gTu-L .iconButton-1li_a3 {
    padding: 0 !important; }
  .userPopout-2j1gM4 .footer-3naVBw {
    margin-top: 0;
    padding: 8px;
    background-color: transparent;
    border-top: 1px solid var(--card-border-color); }
    .userPopout-2j1gM4 .footer-3naVBw .inputWrapper-1YNMmM {
      border-bottom: none !important; }
      .userPopout-2j1gM4 .footer-3naVBw .inputWrapper-1YNMmM.quickMessage-3jDbBs {
        margin-top: 0; }
      .userPopout-2j1gM4 .footer-3naVBw .inputWrapper-1YNMmM:before, .userPopout-2j1gM4 .footer-3naVBw .inputWrapper-1YNMmM:after {
        display: none; }
      .userPopout-2j1gM4 .footer-3naVBw .inputWrapper-1YNMmM .input-2g-os5 {
        padding: 0 12px;
        background-color: var(--input-color);
        border-radius: 16px; }

.allactivities-right .button-f2h6uQ,
.allactivities-left .button-f2h6uQ {
  padding: 0 !important; }

body:active .userPopout-3XzG_A:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/*
 *
 *	USER PROFILE
 *
 */
.swatch-35F5kl {
  min-height: 50px !important;
  height: 50px !important;
  border-radius: var(--button-radius); }
  .swatch-35F5kl:after {
    display: none; }

.root-8LYsGj {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .root-8LYsGj .topSection-13QKHs {
    background-color: transparent; }
    .root-8LYsGj .topSection-13QKHs .avatar-3QF_VA {
      background-color: transparent;
      border: none; }
    .root-8LYsGj .topSection-13QKHs .nameTagNoCustomStatus-3ocqoK {
      margin-bottom: 8px; }
  .root-8LYsGj .header-QKLPzZ {
    padding: 16px;
    background: rgba(0, 0, 0, 0.1); }
  .root-8LYsGj .headerFill-adLl4x {
    background-color: transparent; }
  .root-8LYsGj .activity-1ythUs {
    padding: 16px; }
  .root-8LYsGj .assetsLargeImage-8U5dlz,
  .root-8LYsGj .gameIcon-1mDo1J {
    border-radius: 50%; }
  .root-8LYsGj .assetsLargeImageProfileTwitch-1SbNkP {
    border-radius: var(--card-radius-big); }
  .root-8LYsGj .tabBarContainer-sCZC4w {
    padding-left: 16px;
    border-top: none;
    border-bottom-color: var(--card-border-color); }
    .root-8LYsGj .tabBarContainer-sCZC4w .tabBar-2hXqzU {
      height: 48px; }
      .root-8LYsGj .tabBarContainer-sCZC4w .tabBar-2hXqzU .tabBarItem-30Te4- {
        margin-right: 32px;
        border: none; }
        .root-8LYsGj .tabBarContainer-sCZC4w .tabBar-2hXqzU .tabBarItem-30Te4-[aria-selected="true"] {
          position: relative;
          background-color: transparent !important; }
          .root-8LYsGj .tabBarContainer-sCZC4w .tabBar-2hXqzU .tabBarItem-30Te4-[aria-selected="true"]:after {
            position: absolute;
            content: " ";
            width: 100%;
            height: 3px;
            left: 0;
            right: 0;
            bottom: 0;
            margin: 0 auto;
            background: var(--tab-border-color);
            border-radius: 3px 3px 0 0;
            transition: var(--default-time) ease all; }
  .root-8LYsGj .body-1Ukv50 {
    background-color: transparent; }
    .root-8LYsGj .body-1Ukv50 .infoScroller-1QMpon {
      padding: 0 16px; }
    .root-8LYsGj .body-1Ukv50 .headerText-3g1XK9 {
      font-size: 14px;
      text-transform: none;
      font-weight: 500; }
    .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir {
      padding: 16px 0 8px;
      border-top: none; }
      .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir:nth-child(2) {
        padding: 8px 0 16px; }
      .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir .userInfoSectionHeader-2mYYun {
        font-size: 14px;
        text-transform: none;
        font-weight: 500; }
      .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir .note-3M15gE .textarea-_59yqs {
        padding: 0; }
      .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir .connectedAccounts-1YaT2t {
        margin-top: -16px; }
        .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir .connectedAccounts-1YaT2t .connectedAccount-1xKpli {
          margin-top: 16px;
          background-color: transparent;
          border-radius: var(--card-radius);
          border-color: var(--card-border-color);
          transition: var(--default-time) var(--default-animation) background-color; }
          .root-8LYsGj .body-1Ukv50 .userInfoSection-2u2hir .connectedAccounts-1YaT2t .connectedAccount-1xKpli:hover {
            background-color: var(--card-color-alt); }
  .root-8LYsGj .userProfileActivity-sal5no .iconButton-1li_a3 {
    padding: 0 !important; }
  .root-8LYsGj .iconActiveMedium-27_R5B {
    border-radius: var(--avatar-radius); }

/*
 *
 *	EMOJI PICKER
 *
 */
.contentWrapper-3vHNP2,
.emojiPicker-6YCk8a {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ;
  animation: bottom-pop-out 400ms var(--default-animation);
  /* EMOJI PICKER -> HEADER */
  /* EMOJI PICKER -> HEADER -> SEARCH BAR */
  /* EMOJI PICKER -> HEADER -> DIVERSITY PICKER */
  /* EMOJI PICKER -> EMOJIS */
  /* EMOJI PICKER -> CATEGORIES */ }
  .contentWrapper-3vHNP2 .navList-YSb9UB .navButton-1XuvI-,
  .emojiPicker-6YCk8a .navList-YSb9UB .navButton-1XuvI- {
    border-radius: 12px;
    color: var(--menu-item-text-color) !important; }
    .contentWrapper-3vHNP2 .navList-YSb9UB .navButton-1XuvI-:hover,
    .emojiPicker-6YCk8a .navList-YSb9UB .navButton-1XuvI-:hover {
      background-color: var(--menu-item-hover) !important; }
    .contentWrapper-3vHNP2 .navList-YSb9UB .navButton-1XuvI-.navButtonActive-1EqC5l,
    .emojiPicker-6YCk8a .navList-YSb9UB .navButton-1XuvI-.navButtonActive-1EqC5l {
      background-color: var(--menu-item-select) !important; }
  .contentWrapper-3vHNP2 .header-11eigE,
  .contentWrapper-3vHNP2 .header-uVCAlo,
  .contentWrapper-3vHNP2 .header-JHwfVI,
  .emojiPicker-6YCk8a .header-11eigE,
  .emojiPicker-6YCk8a .header-uVCAlo,
  .emojiPicker-6YCk8a .header-JHwfVI {
    border-bottom: 1px solid var(--card-border-color);
    box-shadow: none; }
  .contentWrapper-3vHNP2 .diversitySelectorPopout-3FiGaM,
  .emojiPicker-6YCk8a .diversitySelectorPopout-3FiGaM {
    background-color: var(--popout-color);
    border-radius: 16px;
    border: none;
    box-shadow: var(--shadow-3dp); }
    .contentWrapper-3vHNP2 .diversitySelectorPopout-3FiGaM .diversityEmojiItem-2bgZKv,
    .emojiPicker-6YCk8a .diversitySelectorPopout-3FiGaM .diversityEmojiItem-2bgZKv {
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .contentWrapper-3vHNP2 .diversitySelectorPopout-3FiGaM .diversityEmojiItem-2bgZKv:hover,
      .emojiPicker-6YCk8a .diversitySelectorPopout-3FiGaM .diversityEmojiItem-2bgZKv:hover {
        background-color: var(--menu-item-hover); }
  .contentWrapper-3vHNP2 .container-1SX9VC,
  .emojiPicker-6YCk8a .container-1SX9VC {
    background-color: var(--input-color);
    border-radius: 16px; }
    .contentWrapper-3vHNP2 .container-1SX9VC .inner-1NoIT5,
    .emojiPicker-6YCk8a .container-1SX9VC .inner-1NoIT5 {
      padding: 0; }
    .contentWrapper-3vHNP2 .container-1SX9VC .input-2FSSDe,
    .emojiPicker-6YCk8a .container-1SX9VC .input-2FSSDe {
      height: 32px;
      margin: 0;
      padding: 0 12px; }
  .contentWrapper-3vHNP2 .diversitySelectorOptions-3DhNYs,
  .emojiPicker-6YCk8a .diversitySelectorOptions-3DhNYs {
    background-color: var(--popout-color);
    border-radius: 17px;
    border: none;
    box-shadow: var(--shadow-3dp);
    overflow: hidden; }
    .contentWrapper-3vHNP2 .diversitySelectorOptions-3DhNYs .diversityEmojiItem-2bgZKv:hover,
    .emojiPicker-6YCk8a .diversitySelectorOptions-3DhNYs .diversityEmojiItem-2bgZKv:hover {
      background-color: var(--menu-item-hover); }
  .contentWrapper-3vHNP2 .wrapper-1NNaWG,
  .emojiPicker-6YCk8a .wrapper-1NNaWG {
    background-color: var(--emoji-category-header); }
    .contentWrapper-3vHNP2 .wrapper-1NNaWG .headerLabel-1g790w,
    .emojiPicker-6YCk8a .wrapper-1NNaWG .headerLabel-1g790w {
      font-size: 14px;
      text-transform: none; }
  .contentWrapper-3vHNP2 .inspector-DFKXwB,
  .emojiPicker-6YCk8a .inspector-DFKXwB {
    background-color: var(--popout-color);
    border-top: 1px solid var(--card-border-color); }
    .contentWrapper-3vHNP2 .inspector-DFKXwB .graphicSecondary-37AA_Y foreignObject,
    .emojiPicker-6YCk8a .inspector-DFKXwB .graphicSecondary-37AA_Y foreignObject {
      mask: none !important; }
    .contentWrapper-3vHNP2 .inspector-DFKXwB .graphicSecondary-37AA_Y .guildIcon-2SUGiq,
    .emojiPicker-6YCk8a .inspector-DFKXwB .graphicSecondary-37AA_Y .guildIcon-2SUGiq {
      border-radius: 50%; }
  .contentWrapper-3vHNP2 .wrapper-22rqw6,
  .emojiPicker-6YCk8a .wrapper-22rqw6 {
    margin-top: -1px;
    background-color: var(--attachment-color);
    /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES */ }
    .contentWrapper-3vHNP2 .wrapper-22rqw6 .scroller-2MALzE::-webkit-scrollbar,
    .emojiPicker-6YCk8a .wrapper-22rqw6 .scroller-2MALzE::-webkit-scrollbar {
      width: 0px !important; }
    .contentWrapper-3vHNP2 .wrapper-22rqw6 .unicodeShortcut-3N8oDe,
    .emojiPicker-6YCk8a .wrapper-22rqw6 .unicodeShortcut-3N8oDe {
      height: 47px;
      background-color: var(--popout-color);
      border-top: 1px solid var(--card-border-color); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .unicodeShortcut-3N8oDe path,
      .emojiPicker-6YCk8a .wrapper-22rqw6 .unicodeShortcut-3N8oDe path {
        d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm3.5-9c.83 0 1.5-.67 1.5-1.5S16.33 8 15.5 8 14 8.67 14 9.5s.67 1.5 1.5 1.5zm-7 0c.83 0 1.5-.67 1.5-1.5S9.33 8 8.5 8 7 8.67 7 9.5 7.67 11 8.5 11zm3.5 6.5c2.33 0 4.31-1.46 5.11-3.5H6.89c.8 2.04 2.78 3.5 5.11 3.5z"); }
    .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq,
    .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq {
      border-radius: 50%;
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> PEOPLE */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> NATURE */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> FOOD */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> ACTIVITIES */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> TRAVEL */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> OBJECTS */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> SYMBOLS */
      /* EMOJI PICKER -> CATEGORIES -> DEFAULT CATEGORIES -> FLAGS */ }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq:hover,
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq:hover {
        background-color: var(--menu-item-hover); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq.categoryItemRecentEmoji-Rk8CU1 path,
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq.categoryItemRecentEmoji-Rk8CU1 path {
        d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm.5-13H11v6l5.25 3.15.75-1.23-4.5-2.67z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M12 2C6.477 2 2 6.477 2 12C2 17.522 6.477 22 12 22C17.523 22 22 17.522 22 12C22 6.477 17.522 2 12 2ZM16.293 6.293L17.707 7.706L16.414 9L17.707 10.293L16.293 11.706L13.586 9L16.293 6.293ZM6.293 7.707L7.707 6.294L10.414 9L7.707 11.707L6.293 10.294L7.586 9L6.293 7.707ZM12 19C9.609 19 7.412 17.868 6 16.043L7.559 14.486C8.555 15.92 10.196 16.831 12 16.831C13.809 16.831 15.447 15.92 16.443 14.481L18 16.04C16.59 17.867 14.396 19 12 19Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M12 2C6.477 2 2 6.477 2 12C2 17.522 6.477 22 12 22C17.523 22 22 17.522 22 12C22 6.477 17.522 2 12 2ZM16.293 6.293L17.707 7.706L16.414 9L17.707 10.293L16.293 11.706L13.586 9L16.293 6.293ZM6.293 7.707L7.707 6.294L10.414 9L7.707 11.707L6.293 10.294L7.586 9L6.293 7.707ZM12 19C9.609 19 7.412 17.868 6 16.043L7.559 14.486C8.555 15.92 10.196 16.831 12 16.831C13.809 16.831 15.447 15.92 16.443 14.481L18 16.04C16.59 17.867 14.396 19 12 19Z"] {
        d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm3.5-9c.83 0 1.5-.67 1.5-1.5S16.33 8 15.5 8 14 8.67 14 9.5s.67 1.5 1.5 1.5zm-7 0c.83 0 1.5-.67 1.5-1.5S9.33 8 8.5 8 7 8.67 7 9.5 7.67 11 8.5 11zm3.5 6.5c2.33 0 4.31-1.46 5.11-3.5H6.89c.8 2.04 2.78 3.5 5.11 3.5z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M6.814 8.982C4.539 11.674 4.656 15.591 6.931 18.153L4.034 21.579L5.561 22.87L8.463 19.437C9.569 20.127 10.846 20.513 12.161 20.513C14.231 20.513 16.183 19.607 17.516 18.027C20.069 15.01 20.771 6.945 21 3C17.765 3.876 9.032 6.356 6.814 8.982V8.982ZM8.935 17.331C6.826 15.548 6.56 12.382 8.342 10.272C9.592 8.793 14.904 6.845 18.764 5.698L8.935 17.331V17.331Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M6.814 8.982C4.539 11.674 4.656 15.591 6.931 18.153L4.034 21.579L5.561 22.87L8.463 19.437C9.569 20.127 10.846 20.513 12.161 20.513C14.231 20.513 16.183 19.607 17.516 18.027C20.069 15.01 20.771 6.945 21 3C17.765 3.876 9.032 6.356 6.814 8.982V8.982ZM8.935 17.331C6.826 15.548 6.56 12.382 8.342 10.272C9.592 8.793 14.904 6.845 18.764 5.698L8.935 17.331V17.331Z"] {
        d: path("M8.66 13.07c.15 0 .29-.01.43-.03C9.56 14.19 10.69 15 12 15s2.44-.81 2.91-1.96c.14.02.29.03.43.03 1.73 0 3.14-1.41 3.14-3.14 0-.71-.25-1.39-.67-1.93.43-.54.67-1.22.67-1.93 0-1.73-1.41-3.14-3.14-3.14-.15 0-.29.01-.43.03C14.44 1.81 13.31 1 12 1s-2.44.81-2.91 1.96c-.14-.02-.29-.03-.43-.03-1.73 0-3.14 1.41-3.14 3.14 0 .71.25 1.39.67 1.93-.43.54-.68 1.22-.68 1.93 0 1.73 1.41 3.14 3.15 3.14zM12 13c-.62 0-1.12-.49-1.14-1.1l.12-1.09c.32.12.66.19 1.02.19s.71-.07 1.03-.19l.11 1.09c-.02.61-.52 1.1-1.14 1.1zm3.34-1.93c-.24 0-.46-.07-.64-.2l-.81-.57c.55-.45.94-1.09 1.06-1.83l.88.42c.4.19.66.59.66 1.03 0 .64-.52 1.15-1.15 1.15zm-.65-5.94c.2-.13.42-.2.65-.2.63 0 1.14.51 1.14 1.14 0 .44-.25.83-.66 1.03l-.88.42c-.12-.74-.51-1.38-1.07-1.83l.82-.56zM12 3c.62 0 1.12.49 1.14 1.1l-.11 1.09C12.71 5.07 12.36 5 12 5s-.7.07-1.02.19l-.12-1.09c.02-.61.52-1.1 1.14-1.1zM8.66 4.93c.24 0 .46.07.64.2l.81.56c-.55.45-.94 1.09-1.06 1.83l-.88-.42c-.4-.2-.66-.59-.66-1.03 0-.63.52-1.14 1.15-1.14zM8.17 8.9l.88-.42c.12.74.51 1.38 1.07 1.83l-.81.55c-.2.13-.42.2-.65.2-.63 0-1.14-.51-1.14-1.14-.01-.43.25-.82.65-1.02zM12 22c4.97 0 9-4.03 9-9-4.97 0-9 4.03-9 9zm2.44-2.44c.71-1.9 2.22-3.42 4.12-4.12-.71 1.9-2.22 3.41-4.12 4.12zM3 13c0 4.97 4.03 9 9 9 0-4.97-4.03-9-9-9zm2.44 2.44c1.9.71 3.42 2.22 4.12 4.12-1.9-.71-3.41-2.22-4.12-4.12z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M11 18H13V22H11V18Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M11 18H13V22H11V18Z"] {
        d: path("M12 6c1.11 0 2-.9 2-2 0-.38-.1-.73-.29-1.03L12 0l-1.71 2.97c-.19.3-.29.65-.29 1.03 0 1.1.9 2 2 2zm6 3h-5V7h-2v2H6c-1.66 0-3 1.34-3 3v9c0 .55.45 1 1 1h16c.55 0 1-.45 1-1v-9c0-1.66-1.34-3-3-3zm1 11H5v-3c.9-.01 1.76-.37 2.4-1.01l1.09-1.07 1.07 1.07c1.31 1.31 3.59 1.3 4.89 0l1.08-1.07 1.07 1.07c.64.64 1.5 1 2.4 1.01v3zm0-4.5c-.51-.01-.99-.2-1.35-.57l-2.13-2.13-2.14 2.13c-.74.74-2.03.74-2.77 0L8.48 12.8l-2.14 2.13c-.35.36-.83.56-1.34.57V12c0-.55.45-1 1-1h12c.55 0 1 .45 1 1v3.5z"); }
        .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M11 18H13V22H11V18Z"] ~ path,
        .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M11 18H13V22H11V18Z"] ~ path {
          display: none; }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M5.66487 5H18.3351C19.9078 5 21.2136 6.21463 21.3272 7.78329L21.9931 16.9774C22.0684 18.0165 21.287 18.9198 20.248 18.9951C20.2026 18.9984 20.1572 19 20.1117 19C18.919 19 17.8785 18.1904 17.5855 17.0342L17.0698 15H6.93015L6.41449 17.0342C6.12142 18.1904 5.08094 19 3.88826 19C2.84645 19 2.00189 18.1554 2.00189 17.1136C2.00189 17.0682 2.00354 17.0227 2.00682 16.9774L2.67271 7.78329C2.78632 6.21463 4.0921 5 5.66487 5ZM14.5 10C15.3284 10 16 9.32843 16 8.5C16 7.67157 15.3284 7 14.5 7C13.6716 7 13 7.67157 13 8.5C13 9.32843 13.6716 10 14.5 10ZM18.5 13C19.3284 13 20 12.3284 20 11.5C20 10.6716 19.3284 10 18.5 10C17.6716 10 17 10.6716 17 11.5C17 12.3284 17.6716 13 18.5 13ZM6.00001 9H4.00001V11H6.00001V13H8.00001V11H10V9H8.00001V7H6.00001V9Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M5.66487 5H18.3351C19.9078 5 21.2136 6.21463 21.3272 7.78329L21.9931 16.9774C22.0684 18.0165 21.287 18.9198 20.248 18.9951C20.2026 18.9984 20.1572 19 20.1117 19C18.919 19 17.8785 18.1904 17.5855 17.0342L17.0698 15H6.93015L6.41449 17.0342C6.12142 18.1904 5.08094 19 3.88826 19C2.84645 19 2.00189 18.1554 2.00189 17.1136C2.00189 17.0682 2.00354 17.0227 2.00682 16.9774L2.67271 7.78329C2.78632 6.21463 4.0921 5 5.66487 5ZM14.5 10C15.3284 10 16 9.32843 16 8.5C16 7.67157 15.3284 7 14.5 7C13.6716 7 13 7.67157 13 8.5C13 9.32843 13.6716 10 14.5 10ZM18.5 13C19.3284 13 20 12.3284 20 11.5C20 10.6716 19.3284 10 18.5 10C17.6716 10 17 10.6716 17 11.5C17 12.3284 17.6716 13 18.5 13ZM6.00001 9H4.00001V11H6.00001V13H8.00001V11H10V9H8.00001V7H6.00001V9Z"] {
        d: path("M21 6H3c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-10 7H8v3H6v-3H3v-2h3V8h2v3h3v2zm4.5 2c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm4-3c-.83 0-1.5-.67-1.5-1.5S18.67 9 19.5 9s1.5.67 1.5 1.5-.67 1.5-1.5 1.5z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M22 17H19.725C19.892 16.529 20 16.029 20 15.5C20 13.015 17.985 11 15.5 11H13.5L12.276 8.553C12.107 8.214 11.761 8 11.382 8H7C6.448 8 6 8.447 6 9V11.051C3.753 11.302 2 13.186 2 15.5C2 17.986 4.015 20 6.5 20H15.5C16.563 20 17.527 19.616 18.297 19H22V17ZM6.5 16.75C5.81 16.75 5.25 16.19 5.25 15.5C5.25 14.81 5.81 14.25 6.5 14.25C7.19 14.25 7.75 14.81 7.75 15.5C7.75 16.19 7.19 16.75 6.5 16.75ZM11.5 16.75C10.81 16.75 10.25 16.19 10.25 15.5C10.25 14.81 10.81 14.25 11.5 14.25C12.19 14.25 12.75 14.81 12.75 15.5C12.75 16.19 12.19 16.75 11.5 16.75ZM16.5 16.75C15.81 16.75 15.25 16.19 15.25 15.5C15.25 14.81 15.81 14.25 16.5 14.25C17.19 14.25 17.75 14.81 17.75 15.5C17.75 16.19 17.19 16.75 16.5 16.75Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M22 17H19.725C19.892 16.529 20 16.029 20 15.5C20 13.015 17.985 11 15.5 11H13.5L12.276 8.553C12.107 8.214 11.761 8 11.382 8H7C6.448 8 6 8.447 6 9V11.051C3.753 11.302 2 13.186 2 15.5C2 17.986 4.015 20 6.5 20H15.5C16.563 20 17.527 19.616 18.297 19H22V17ZM6.5 16.75C5.81 16.75 5.25 16.19 5.25 15.5C5.25 14.81 5.81 14.25 6.5 14.25C7.19 14.25 7.75 14.81 7.75 15.5C7.75 16.19 7.19 16.75 6.5 16.75ZM11.5 16.75C10.81 16.75 10.25 16.19 10.25 15.5C10.25 14.81 10.81 14.25 11.5 14.25C12.19 14.25 12.75 14.81 12.75 15.5C12.75 16.19 12.19 16.75 11.5 16.75ZM16.5 16.75C15.81 16.75 15.25 16.19 15.25 15.5C15.25 14.81 15.81 14.25 16.5 14.25C17.19 14.25 17.75 14.81 17.75 15.5C17.75 16.19 17.19 16.75 16.5 16.75Z"] {
        d: path("M12 4H5C3.34 4 2 5.34 2 7v8c0 1.66 1.34 3 3 3l-1 1v1h1l2-2h2v-5H4V6h9v2h2V7c0-1.66-1.34-3-3-3zM5 14c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm15.57-4.34c-.14-.4-.52-.66-.97-.66h-7.19c-.46 0-.83.26-.98.66l-1.42 4.11v5.51c0 .38.31.72.69.72h.62c.38 0 .68-.38.68-.76V18h8v1.24c0 .38.31.76.69.76h.61c.38 0 .69-.34.69-.72l.01-1.37v-4.14l-1.43-4.11zm-8.16.34h7.19l1.03 3h-9.25l1.03-3zM12 16c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm8 0c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M18 5.999H17V4.999C17 4.448 16.553 3.999 16 3.999H4C3.447 3.999 3 4.448 3 4.999V12.999C3 14.488 3.47 15.865 4.265 16.999H15.722C16.335 16.122 16.761 15.105 16.92 13.999H18C20.205 13.999 22 12.205 22 9.999C22 7.794 20.205 5.999 18 5.999V5.999ZM18 12H17V8H18C19.104 8 20 8.897 20 10C20 11.102 19.104 12 18 12Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M18 5.999H17V4.999C17 4.448 16.553 3.999 16 3.999H4C3.447 3.999 3 4.448 3 4.999V12.999C3 14.488 3.47 15.865 4.265 16.999H15.722C16.335 16.122 16.761 15.105 16.92 13.999H18C20.205 13.999 22 12.205 22 9.999C22 7.794 20.205 5.999 18 5.999V5.999ZM18 12H17V8H18C19.104 8 20 8.897 20 10C20 11.102 19.104 12 18 12Z"] {
        d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5v6z"); }
        .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M18 5.999H17V4.999C17 4.448 16.553 3.999 16 3.999H4C3.447 3.999 3 4.448 3 4.999V12.999C3 14.488 3.47 15.865 4.265 16.999H15.722C16.335 16.122 16.761 15.105 16.92 13.999H18C20.205 13.999 22 12.205 22 9.999C22 7.794 20.205 5.999 18 5.999V5.999ZM18 12H17V8H18C19.104 8 20 8.897 20 10C20 11.102 19.104 12 18 12Z"] ~ path,
        .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M18 5.999H17V4.999C17 4.448 16.553 3.999 16 3.999H4C3.447 3.999 3 4.448 3 4.999V12.999C3 14.488 3.47 15.865 4.265 16.999H15.722C16.335 16.122 16.761 15.105 16.92 13.999H18C20.205 13.999 22 12.205 22 9.999C22 7.794 20.205 5.999 18 5.999V5.999ZM18 12H17V8H18C19.104 8 20 8.897 20 10C20 11.102 19.104 12 18 12Z"] ~ path {
          display: none; }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M16 4.001C14.406 4.001 12.93 4.838 12 6.081C11.07 4.838 9.594 4.001 8 4.001C5.243 4.001 3 6.244 3 9.001C3 14.492 11.124 19.633 11.471 19.849C11.633 19.95 11.817 20.001 12 20.001C12.183 20.001 12.367 19.95 12.529 19.849C12.876 19.633 21 14.492 21 9.001C21 6.244 18.757 4.001 16 4.001V4.001Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M16 4.001C14.406 4.001 12.93 4.838 12 6.081C11.07 4.838 9.594 4.001 8 4.001C5.243 4.001 3 6.244 3 9.001C3 14.492 11.124 19.633 11.471 19.849C11.633 19.95 11.817 20.001 12 20.001C12.183 20.001 12.367 19.95 12.529 19.849C12.876 19.633 21 14.492 21 9.001C21 6.244 18.757 4.001 16 4.001V4.001Z"] {
        d: path("M12.1,18.55L12,18.65L11.89,18.55C7.14,14.24 4,11.39 4,8.5C4,6.5 5.5,5 7.5,5C9.04,5 10.54,6 11.07,7.36H12.93C13.46,6 14.96,5 16.5,5C18.5,5 20,6.5 20,8.5C20,11.39 16.86,14.24 12.1,18.55M16.5,3C14.76,3 13.09,3.81 12,5.08C10.91,3.81 9.24,3 7.5,3C4.42,3 2,5.41 2,8.5C2,12.27 5.4,15.36 10.55,20.03L12,21.35L13.45,20.03C18.6,15.36 22,12.27 22,8.5C22,5.41 19.58,3 16.5,3Z"); }
      .contentWrapper-3vHNP2 .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M20 6.002H14V3.002C14 2.45 13.553 2.002 13 2.002H4C3.447 2.002 3 2.45 3 3.002V22.002H5V14.002H10.586L8.293 16.295C8.007 16.581 7.922 17.011 8.076 17.385C8.23 17.759 8.596 18.002 9 18.002H20C20.553 18.002 21 17.554 21 17.002V7.002C21 6.45 20.553 6.002 20 6.002Z"],
      .emojiPicker-6YCk8a .wrapper-22rqw6 .categoryItemDefaultCategory-3haEDq path[d="M20 6.002H14V3.002C14 2.45 13.553 2.002 13 2.002H4C3.447 2.002 3 2.45 3 3.002V22.002H5V14.002H10.586L8.293 16.295C8.007 16.581 7.922 17.011 8.076 17.385C8.23 17.759 8.596 18.002 9 18.002H20C20.553 18.002 21 17.554 21 17.002V7.002C21 6.45 20.553 6.002 20 6.002Z"] {
        d: path("M14 6l-1-2H5v17h2v-7h5l1 2h7V6h-6zm4 8h-4l-1-2H7V6h5l1 2h5v6z"); }

.emojiPicker-6YCk8a + .wrapper-22rqw6 .scroller-2MALzE::-webkit-scrollbar {
  width: 0px !important; }

body:active .contentWrapper-3vHNP2:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/* EMOJI PICKER -> GIFS */
.result-3OpoO7 {
  border-radius: var(--media-radius); }
  .result-3OpoO7:after,
  .result-3OpoO7 .gif-1EWTs-,
  .result-3OpoO7 .categoryFade-2EGqIh,
  .result-3OpoO7 .categoryFadeBlurple-1HuV1x {
    border-radius: inherit; }
  .result-3OpoO7 .categoryFadeBlurple-1HuV1x {
    background-color: hsla(var(--accent-hsl), 0.8) !important; }
  .result-3OpoO7:hover {
    box-shadow: var(--shadow-2dp) !important; }
    .result-3OpoO7:hover:after {
      box-shadow: inset 0 0 0 2px hsl(var(--accent-hsl)), inset 0 0 1px 3px #2f3136 !important; }

/* EMOJI PICKER -> STICKERS */
.row-2mBMW2 {
  column-gap: 6px !important; }

/*
 *
 *	UPLOAD
 *
 */
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .bgScale-1iWuPF {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .inner-rBP-MS {
  border: none; }
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .title-3ChJ_v,
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .title-3ChJ_v strong {
  color: var(--text-normal) !important; }
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .instructions-272j2A {
  color: var(--text-normal) !important; }
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20.error-3lNz4C .title-3ChJ_v,
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20.error-3lNz4C .title-3ChJ_v strong {
  color: #eee !important; }
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20.error-3lNz4C .instructions-272j2A {
  color: #eee !important; }

.colorDefault-CDqZdO .subtext-2GlkbE {
  color: var(--text-muted) !important; }

/* UPLOAD -> MODAL */
.uploadModal-2ie9O_ {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .uploadModal-2ie9O_ .inner-rBP-MS {
    margin: 0;
    padding: 16px; }
    .uploadModal-2ie9O_ .inner-rBP-MS .file-163EuR .icon-HW4tZ-.image-2ssF8k {
      margin-left: 0 !important;
      border-radius: var(--popout-radius-big);
      box-shadow: var(--shadow-3dp); }
    .uploadModal-2ie9O_ .inner-rBP-MS .file-163EuR .description-2AJi-V {
      padding-left: 0 !important; }
    .uploadModal-2ie9O_ .inner-rBP-MS .comment-1kpwc5 {
      margin: 0; }
      .uploadModal-2ie9O_ .inner-rBP-MS .comment-1kpwc5 .label-21vOgf {
        font-size: 14px;
        text-transform: none; }
      .uploadModal-2ie9O_ .inner-rBP-MS .comment-1kpwc5 .channelTextArea-1VQBuV {
        margin-bottom: 0; }
        .uploadModal-2ie9O_ .inner-rBP-MS .comment-1kpwc5 .channelTextArea-1VQBuV .scrollableContainer-15eg7h {
          background-color: var(--main-textarea-color);
          border-radius: var(--main-textarea-radius);
          border: 1px solid var(--main-textarea-border); }
  .uploadModal-2ie9O_ .footer-VCsJQY {
    padding: 8px;
    background-color: transparent !important;
    border-top: 1px solid var(--card-border-color);
    box-shadow: none !important; }
    .uploadModal-2ie9O_ .footer-VCsJQY .button-f2h6uQ.lookLink-15mFoz {
      margin-right: 8px; }

/* UPLOAD -> IMAGE INSERT */
.upload-3GTSF9 {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .upload-3GTSF9 .image-2dAEjD {
    border-radius: var(--card-radius-big); }
  .upload-3GTSF9 .wrapper-2vIMkT:hover {
    box-shadow: var(--shadow-3dp); }
  .upload-3GTSF9 .altTag-2Bi3uP {
    border-radius: 10px; }

/*
 *
 *	REACTIONS
 *
 */
.container-KM8BU6 .scroller-2GkvCq,
.container-KM8BU6 .reactors-1VXca7 {
  background-color: transparent; }
.container-KM8BU6 .scroller-2GkvCq {
  border-right: 1px solid var(--card-border-color); }
.container-KM8BU6 .reactionDefault-1Sjj1f,
.container-KM8BU6 .reactionSelected-1aMb2K {
  margin-bottom: 4px;
  border-radius: 14px; }
.container-KM8BU6 .reactionDefault-1Sjj1f:hover {
  background-color: var(--menu-item-hover); }
.container-KM8BU6 .reactionSelected-1aMb2K {
  background-color: var(--menu-item-select); }
.container-KM8BU6 .reactors-1VXca7 .reactor-1J25Qp {
  margin-left: 0;
  margin-right: 0;
  padding-left: 16px;
  box-shadow: none !important;
  position: relative;
  border-bottom: none; }
  .container-KM8BU6 .reactors-1VXca7 .reactor-1J25Qp:after {
    position: absolute;
    content: " ";
    width: calc(100% - 50px);
    height: 1px;
    right: 0;
    bottom: 0;
    background-color: var(--card-border-color); }
  .container-KM8BU6 .reactors-1VXca7 .reactor-1J25Qp:last-of-type:after {
    display: none; }

/*
 *
 *	AUTOCOMPLETE
 *
 */
.autocomplete-3NRXG8 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important; }
  .autocomplete-3NRXG8 .autocompleteRow-14iwvH {
    padding: 0; }
    .autocomplete-3NRXG8 .autocompleteRow-14iwvH .base-2v-uc0 {
      padding: 8px 12px;
      border-radius: 0;
      transition: var(--default-time) var(--default-animation) background-color; }
      .autocomplete-3NRXG8 .autocompleteRow-14iwvH .base-2v-uc0.selected-3H3-RC {
        background-color: var(--menu-item-hover) !important; }
      .autocomplete-3NRXG8 .autocompleteRow-14iwvH .base-2v-uc0:not(.selectable-1MM9tu) {
        border-bottom: 1px solid var(--card-border-color); }
        .autocomplete-3NRXG8 .autocompleteRow-14iwvH .base-2v-uc0:not(.selectable-1MM9tu) .contentTitle-3CylD3 {
          font-size: 14px;
          text-transform: none; }
  .autocomplete-3NRXG8 .divider-1bJsnZ {
    padding: 8px 0; }
    .autocomplete-3NRXG8 .divider-1bJsnZ:after {
      background-color: var(--card-border-color); }
  .autocomplete-3NRXG8 .wrapper-3z7DuG {
    background-color: var(--attachment-color); }
    .autocomplete-3NRXG8 .wrapper-3z7DuG .wrapper-22rqw6 {
      background-color: transparent; }
      .autocomplete-3NRXG8 .wrapper-3z7DuG .wrapper-22rqw6 .listItems-6eZzQ1 {
        left: 12px !important;
        right: 12px !important; }
      .autocomplete-3NRXG8 .wrapper-3z7DuG .wrapper-22rqw6 .wrapper-1wwiGV {
        border-radius: 50%; }
  .autocomplete-3NRXG8 .listItems-6eZzQ1 {
    left: 0 !important;
    right: 0 !important; }
  .autocomplete-3NRXG8 .categorySectionLast-C-_pSG .categoryHeader-OpJ1Ly {
    background-color: var(--emoji-category-header); }

/*
 *
 *	ACCEPT RULES
 *
 */
.guildSidebar-UHnQqs {
  padding: 0;
  background-color: transparent;
  border-right: 1px solid var(--card-border-color); }
  .guildSidebar-UHnQqs > div:not([class]):first-child {
    padding: 16px; }
  .guildSidebar-UHnQqs > div:not([class]):last-child {
    display: flex;
    position: relative;
    padding: 9px 8px;
    border-top: 1px solid var(--popout-header-border); }
    .guildSidebar-UHnQqs > div:not([class]):last-child:after {
      position: absolute;
      content: " ";
      width: 1px;
      height: 52px;
      top: 0;
      right: -1px;
      background-color: var(--popout-color); }
    .guildSidebar-UHnQqs > div:not([class]):last-child .flex-2S1XBF {
      height: 36px;
      margin-right: 8px;
      margin-bottom: 0; }
  .guildSidebar-UHnQqs .iconSizeLarge-_r2zCK {
    border-radius: 50%; }
  .guildSidebar-UHnQqs .divider-1zHRlg {
    border-bottom-color: var(--card-border-color); }

.modal-2TOYtq {
  background-color: transparent; }
  .modal-2TOYtq .divider-1zHRlg {
    border-bottom-color: var(--card-border-color); }
  .modal-2TOYtq .formFieldWrapper-2LV3S6 {
    padding: 8px 6px 8px 12px; }
    .modal-2TOYtq .formFieldWrapper-2LV3S6.flex-2S1XBF {
      background-color: var(--input-color);
      border-radius: 24px;
      border: none; }
      .modal-2TOYtq .formFieldWrapper-2LV3S6.flex-2S1XBF .button-f2h6uQ {
        margin-top: -3px; }
    .modal-2TOYtq .formFieldWrapper-2LV3S6:not(.flex-2S1XBF) {
      background-color: var(--card-color) ;
      border-radius: var(--card-radius-big) ;
      border: 1px solid var(--card-border-color) ;
      padding: 0; }
    .modal-2TOYtq .formFieldWrapper-2LV3S6 .termsRow-dZXIM3 {
      padding: 16px;
      position: relative;
      border-bottom: none; }
      .modal-2TOYtq .formFieldWrapper-2LV3S6 .termsRow-dZXIM3:after {
        position: absolute;
        content: " ";
        width: calc(100% - 44px);
        height: 1px;
        right: 0;
        bottom: 0;
        background-color: var(--card-border-color); }
      .modal-2TOYtq .formFieldWrapper-2LV3S6 .termsRow-dZXIM3:last-of-type:after {
        display: none; }
      .modal-2TOYtq .formFieldWrapper-2LV3S6 .termsRow-dZXIM3 .termsRowContent-2Qx-E5 {
        padding-left: 16px; }

/*
 *
 *	VIDEO PLAYER
 *
 */
.metadata-3IncIG {
  height: auto;
  top: 0;
  padding: 0;
  background: -webkit-linear-gradient(bottom, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0) 1%, rgba(0, 0, 0, 0.4) 67%, rgba(0, 0, 0, 0.4) 100%);
  z-index: 2; }
  .metadata-3IncIG .metadataContent-lalfZ3 {
    padding: 12px 12px 0; }
  .metadata-3IncIG .anchor-1MIwyf {
    width: 25px;
    height: 25px;
    margin: 6px 6px 0 0;
    padding: 6px;
    opacity: 1;
    position: relative; }
    .metadata-3IncIG .anchor-1MIwyf:after {
      content: " ";
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      background-color: hsla(var(--md-ripple-color), 0.1);
      border-radius: 50%;
      opacity: 0;
      pointer-events: none;
      transform: scale(1.2);
      transition: 300ms ease;
      z-index: 4; }
    .metadata-3IncIG .anchor-1MIwyf:hover:after {
      opacity: 1;
      transform: scale(1);
      animation: scale 150ms var(--default-animation), opacity 150ms ease; }
    .metadata-3IncIG .anchor-1MIwyf:active:after {
      background-color: hsla(var(--md-ripple-color), 0.2); }
  .metadata-3IncIG .metadataIcon-3QMhu9 path[d="M16.293 9.293L17.707 10.707L12 16.414L6.29297 10.707L7.70697 9.293L11 12.586V2H13V12.586L16.293 9.293ZM18 20V18H20V20C20 21.102 19.104 22 18 22H6C4.896 22 4 21.102 4 20V18H6V20H18Z"] {
    d: path("M13 5v6h1.17L12 13.17 9.83 11H11V5h2m2-2H9v6H5l7 7 7-7h-4V3zm4 15H5v2h14v-2z"); }

.playCenter-APe1JX .wrapper-x4po40 {
  width: 100%;
  height: 100%;
  background-color: transparent;
  border-radius: var(--media-radius); }
  .playCenter-APe1JX .wrapper-x4po40 .iconWrapper-1lfhOx {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: rgba(0, 0, 0, 0.5);
    transition: var(--default-time) var(--default-animation) all;
    opacity: 0.6; }
    .playCenter-APe1JX .wrapper-x4po40 .iconWrapper-1lfhOx:hover {
      opacity: 1;
      transform: scale(1.25); }
    .playCenter-APe1JX .wrapper-x4po40 .iconWrapper-1lfhOx:active {
      transform: scale(1.25), translateY(0); }
  .playCenter-APe1JX .wrapper-x4po40 .iconPlay-3weMmb {
    width: 100%;
    height: 100%;
    margin: 0;
    background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiB3aWR0aD0iNzIiIGhlaWdodD0iNzIiIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGRkZGRiIgZD0iTTEwLDE2LjVWNy41TDE2LDEyTTEyLDJBMTAsMTAgMCAwLDAgMiwxMkExMCwxMCAwIDAsMCAxMiwyMkExMCwxMCAwIDAsMCAyMiwxMkExMCwxMCAwIDAsMCAxMiwyWiIgLz48L3N2Zz4=);
    background-repeat: no-repeat;
    background-size: 20%;
    background-position: 50%;
    pointer-events: none; }
    .playCenter-APe1JX .wrapper-x4po40 .iconPlay-3weMmb polygon {
      display: none; }

/* VIDEO PLAYER -> CONTROLS */
.videoControls-2NzHnF .mediaBarWrapper-33h1oY {
  box-shadow: none !important; }
  .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarGrabber-FvJKJg, .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarGrabber-FvJKJg:before, .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarGrabber-FvJKJg:after,
  .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarProgress-38I317,
  .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarProgress-38I317:before,
  .videoControls-2NzHnF .mediaBarWrapper-33h1oY .mediaBarProgress-38I317:after {
    background-color: hsl(var(--accent-hsl)); }
  .videoControls-2NzHnF .mediaBarWrapper-33h1oY .fakeEdges-18N907:before, .videoControls-2NzHnF .mediaBarWrapper-33h1oY .fakeEdges-18N907:after {
    border-radius: 0; }
.videoControls-2NzHnF .bubble-3XikHF {
  background-color: rgba(97, 97, 97, 0.9);
  color: #ddd; }
  .videoControls-2NzHnF .bubble-3XikHF:before {
    border-top-color: rgba(97, 97, 97, 0.9); }

/*
 *
 *	FORMAT TOOLBAR
 *
 */
.toolbar-37BrJ5 {
  background-color: var(--popout-color);
  border-radius: 16px;
  box-shadow: var(--shadow-3dp);
  overflow: hidden; }
  .toolbar-37BrJ5 .button-lA2rvH {
    border-radius: 0 !important;
    box-shadow: none !important;
    transition: var(--default-time) var(--default-animation) background-color !important; }
    .toolbar-37BrJ5 .button-lA2rvH:hover {
      background-color: var(--menu-item-hover); }
    .toolbar-37BrJ5 .button-lA2rvH .icon-3g7qdA {
      color: var(--menu-item-text-color) !important; }
  .toolbar-37BrJ5 .divider-3NY7PF {
    border-left-color: var(--card-border-color); }

/*
 *
 *	CONTEXT/RIGHT CLICK MENU
 *
 */
.styleFlexible-x0_sIC {
  animation: opacity 100ms ease, open-context-menu 300ms var(--default-animation);
  transform-origin: top; }
  .styleFlexible-x0_sIC .scroller-1bVxF5 {
    padding: 8px 0;
    background-color: var(--popout-color);
    border-radius: var(--popout-radius);
    box-shadow: var(--shadow-3dp); }
    .styleFlexible-x0_sIC .scroller-1bVxF5::-webkit-scrollbar {
      width: 0 !important; }
  .styleFlexible-x0_sIC .item-1OdjEX {
    min-height: 32px;
    margin: 0;
    padding: 9px 12px;
    line-height: 18px;
    border-radius: 0;
    color: var(--menu-item-text-color) !important;
    transition: var(--default-time) var(--default-animation);
    /* CONTEXT/RIGHT CLICK MENU -> ICONS */ }
    .styleFlexible-x0_sIC .item-1OdjEX.focused-3qFvc8 {
      background-color: var(--menu-item-hover); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-reply path {
      d: path("M8,9.8V10.7L9.7,11C12.3,11.4 14.2,12.4 15.6,13.7C13.9,13.2 12.1,12.9 10,12.9H8V14.2L5.8,12L8,9.8M10,5L3,12L10,19V14.9C15,14.9 18.5,16.5 21,20C20,15 17,10 10,9"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-edit path {
      d: path("M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM5.92 19H5v-.92l9.06-9.06.92.92L5.92 19zM20.71 5.63l-2.34-2.34c-.2-.2-.45-.29-.71-.29s-.51.1-.7.29l-1.83 1.83 3.75 3.75 1.83-1.83c.39-.39.39-1.02 0-1.41z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-pin path {
      d: path("M16,12V4H17V2H7V4H8V12L6,14V16H11.2V22H12.8V16H18V14L16,12M8.8,14L10,12.8V4H14V12.8L15.2,14H8.8Z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-thread path {
      d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H6l-2 2V4h16v12z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-mark-unread path {
      d: path("M2,5.27L3.28,4L20,20.72L18.73,22L15.65,18.92C14.5,19.3 13.28,19.5 12,19.5C7,19.5 2.73,16.39 1,12C1.69,10.24 2.79,8.69 4.19,7.46L2,5.27M12,9A3,3 0 0,1 15,12C15,12.35 14.94,12.69 14.83,13L11,9.17C11.31,9.06 11.65,9 12,9M12,4.5C17,4.5 21.27,7.61 23,12C22.18,14.08 20.79,15.88 19,17.19L17.58,15.76C18.94,14.82 20.06,13.54 20.82,12C19.17,8.64 15.76,6.5 12,6.5C10.91,6.5 9.84,6.68 8.84,7L7.3,5.47C8.74,4.85 10.33,4.5 12,4.5M3.18,12C4.83,15.36 8.24,17.5 12,17.5C12.69,17.5 13.37,17.43 14,17.29L11.72,15C10.29,14.85 9.15,13.71 9,12.28L5.6,8.87C4.61,9.72 3.78,10.78 3.18,12Z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-reactions path {
      d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm3.5-9c.83 0 1.5-.67 1.5-1.5S16.33 8 15.5 8 14 8.67 14 9.5s.67 1.5 1.5 1.5zm-7 0c.83 0 1.5-.67 1.5-1.5S9.33 8 8.5 8 7 8.67 7 9.5 7.67 11 8.5 11zm3.5 6.5c2.33 0 4.31-1.46 5.11-3.5H6.89c.8 2.04 2.78 3.5 5.11 3.5z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-copy-link path {
      d: path("M17 7h-4v2h4c1.65 0 3 1.35 3 3s-1.35 3-3 3h-4v2h4c2.76 0 5-2.24 5-5s-2.24-5-5-5zm-6 8H7c-1.65 0-3-1.35-3-3s1.35-3 3-3h4V7H7c-2.76 0-5 2.24-5 5s2.24 5 5 5h4v-2zm-3-4h8v2H8z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-tts path {
      d: path("M9 13c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0-6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4zm-6 4c.22-.72 3.31-2 6-2 2.7 0 5.8 1.29 6 2H3zM15.08 7.05c.84 1.18.84 2.71 0 3.89l1.68 1.69c2.02-2.02 2.02-5.07 0-7.27l-1.68 1.69zM20.07 2l-1.63 1.63c2.77 3.02 2.77 7.56 0 10.74L20.07 16c3.9-3.89 3.91-9.95 0-14z"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-delete path {
      display: block;
      d: path("M16 9v10H8V9h8m-1.5-6h-5l-1 1H5v2h14V4h-3.5l-1-1zM18 7H6v12c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7z"); }
      .styleFlexible-x0_sIC .item-1OdjEX#message-actions-delete path ~ path {
        display: none; }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-report path {
      d: path("M12.36,6L12.76,8H18V14H14.64L14.24,12H7V6H12.36M14,4H5V21H7V14H12.6L13,16H20V6H14.4"); }
    .styleFlexible-x0_sIC .item-1OdjEX#message-actions-copy-id path {
      d: path("M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 16H8V7h11v14z"); }
  .styleFlexible-x0_sIC .submenuContainer-3EVTeH .submenuPaddingContainer-_k62dJ {
    margin-left: -4px;
    margin-right: -4px;
    animation: opacity 100ms ease, open-context-menu 300ms var(--default-animation);
    transform-origin: top; }
  .styleFlexible-x0_sIC .separator-1So4YB {
    width: 100%;
    margin: 8px 0;
    border-color: var(--separator-color); }

/*
 *
 *	POPOUT MENUS
 *
 */
/* POPOUT MENUS -> SERVER OPTIONS */
.menu-1QACrS {
  background-color: transparent;
  border-radius: var(--popout-radius); }
  .menu-1QACrS#guild-header-popout {
    padding: 8px 0;
    background-color: var(--popout-color) ;
    border-radius: var(--popout-radius-big) ;
    box-shadow: var(--shadow-3dp) ;
    animation: top-pop-out 400ms var(--default-animation);
    overflow: hidden; }
    .menu-1QACrS#guild-header-popout .scroller-1bVxF5 {
      padding: 0; }
      .menu-1QACrS#guild-header-popout .scroller-1bVxF5::-webkit-scrollbar {
        width: 0 !important; }
    .menu-1QACrS#guild-header-popout .item-1OdjEX {
      margin: 0;
      padding: 9px 12px;
      border-radius: 0;
      color: var(--menu-item-text-color);
      transition: var(--default-time) var(--default-animation);
      /* POPOUT MENUS -> SERVER OPTIONS -> INVITE */
      /* POPOUT MENUS -> SERVER OPTIONS -> SERVER SETTINGS */
      /* POPOUT MENUS -> SERVER OPTIONS -> CREATE CHANNEL */
      /* POPOUT MENUS -> SERVER OPTIONS -> CREATE CATEGORY */
      /* POPOUT MENUS -> SERVER OPTIONS -> NOTIFICATION SETTINGS */
      /* POPOUT MENUS -> SERVER OPTIONS -> PRIVACY SETTINGS */
      /* POPOUT MENUS -> SERVER OPTIONS -> CHANGE NICKNAME */
      /* POPOUT MENUS -> SERVER OPTIONS -> HIDE MUTED CHANNELS */
      /*&#guild-header-popout-hide-muted-channels[aria-checked="true"] .check-3HZJs4 {
      	transform: scale(0.7) translate(5px, 4px);
      }*/
      /* POPOUT MENUS -> SERVER OPTIONS -> LEAVE SERVER */ }
      .menu-1QACrS#guild-header-popout .item-1OdjEX.focused-3qFvc8 {
        background-color: var(--menu-item-hover); }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-invite-people svg path {
        d: path("M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0-6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4zm-6 4c.22-.72 3.31-2 6-2 2.7 0 5.8 1.29 6 2H9zm-3-3v-3h3v-2H6V7H4v3H1v2h3v3z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-settings svg path {
        d: path("M19.43 12.98c.04-.32.07-.64.07-.98 0-.34-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.09-.16-.26-.25-.44-.25-.06 0-.12.01-.17.03l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.06-.02-.12-.03-.18-.03-.17 0-.34.09-.43.25l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98 0 .33.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.09.16.26.25.44.25.06 0 .12-.01.17-.03l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.06.02.12.03.18.03.17 0 .34-.09.43-.25l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zm-1.98-1.71c.04.31.05.52.05.73 0 .21-.02.43-.05.73l-.14 1.13.89.7 1.08.84-.7 1.21-1.27-.51-1.04-.42-.9.68c-.43.32-.84.56-1.25.73l-1.06.43-.16 1.13-.2 1.35h-1.4l-.19-1.35-.16-1.13-1.06-.43c-.43-.18-.83-.41-1.23-.71l-.91-.7-1.06.43-1.27.51-.7-1.21 1.08-.84.89-.7-.14-1.13c-.03-.31-.05-.54-.05-.74s.02-.43.05-.73l.14-1.13-.89-.7-1.08-.84.7-1.21 1.27.51 1.04.42.9-.68c.43-.32.84-.56 1.25-.73l1.06-.43.16-1.13.2-1.35h1.39l.19 1.35.16 1.13 1.06.43c.43.18.83.41 1.23.71l.91.7 1.06-.43 1.27-.51.7 1.21-1.07.85-.89.7.14 1.13zM12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-create-channel svg path {
        d: path("M13 7h-2v4H7v2h4v4h2v-4h4v-2h-4V7zm-1-5C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-create-category svg path {
        d: path("M14 10H2v2h12v-2zm0-4H2v2h12V6zm4 8v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zM2 16h8v-2H2v2z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-notifications svg path {
        d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5v6z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-privacy svg path {
        d: path("M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm7 10c0 4.52-2.98 8.69-7 9.93-4.02-1.24-7-5.41-7-9.93V6.3l7-3.11 7 3.11V11zm-11.59.59L6 13l4 4 8-8-1.41-1.42L10 14.17z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-change-nickname svg path {
        d: path("M14.06 9.02l.92.92L5.92 19H5v-.92l9.06-9.06M17.66 3c-.25 0-.51.1-.7.29l-1.83 1.83 3.75 3.75 1.83-1.83c.39-.39.39-1.02 0-1.41l-2.34-2.34c-.2-.2-.45-.29-.71-.29zm-3.6 3.19L3 17.25V21h3.75L17.81 9.94l-3.75-3.75z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-hide-muted-channels[aria-checked="false"] path {
        d: path("M19 5v14H5V5h14m0-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-hide-muted-channels[aria-checked="true"] .checkbox-hADx5o {
        d: path("M19 3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.11 0 2-.9 2-2V5c0-1.1-.89-2-2-2zm-9 14l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z") !important; }
      .menu-1QACrS#guild-header-popout .item-1OdjEX#guild-header-popout-leave svg path {
        d: path("M10.09 15.59L11.5 17l5-5-5-5-1.41 1.41L12.67 11H3v2h9.67l-2.58 2.59zM19 3H5c-1.11 0-2 .9-2 2v4h2V5h14v14H5v-4H3v4c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2z") !important; }
    .menu-1QACrS#guild-header-popout .separator-1So4YB {
      width: 100%;
      margin: 8px 0;
      border-color: var(--separator-color); }

body:active .menu-1QACrS#guild-header-popout:not(:active) {
  opacity: 0;
  transition: 150ms ease all; }

/* POPOUT MENUS -> INCOMING CALL */
.wrapper-3X0c60 {
  z-index: 99; }

.root-1e2tfc {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .root-1e2tfc .colorable-3rVGna {
    border-radius: 50% !important; }
    .root-1e2tfc .colorable-3rVGna.red-3T8maV.active-3D763s, .root-1e2tfc .colorable-3rVGna.red-3T8maV:hover {
      background: #f04747 !important; }
    .root-1e2tfc .colorable-3rVGna.green-3wkLbx.active-3D763s, .root-1e2tfc .colorable-3rVGna.green-3wkLbx:hover {
      background: #43b581 !important; }

/*
 *
 *	MODALS
 *
 */
.root-g14mjS,
.modal-1ocm0B {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important;
  /* MODALS -> HEADER */
  /* MODALS -> BODY */
  /* MODALS -> FOOTER */ }
  .root-g14mjS > form:not([class]),
  .modal-1ocm0B > form:not([class]) {
    height: 100%;
    overflow-y: scroll; }
  .root-g14mjS.modal-3Crloo,
  .modal-1ocm0B.modal-3Crloo {
    background-color: transparent !important;
    border-radius: 0 !important;
    box-shadow: none !important; }
  .root-g14mjS.modal-3O0aXp,
  .modal-1ocm0B.modal-3O0aXp {
    max-height: 90vh; }
  .root-g14mjS.small-23Atuv,
  .modal-1ocm0B.small-23Atuv {
    min-height: 75px; }
  .root-g14mjS .authBox-1HR6Ha,
  .modal-1ocm0B .authBox-1HR6Ha {
    box-shadow: none; }
    .root-g14mjS .authBox-1HR6Ha .sizeTiny-EgeIrh,
    .modal-1ocm0B .authBox-1HR6Ha .sizeTiny-EgeIrh {
      padding: 0;
      background-color: transparent !important;
      font-weight: 400;
      font-size: 16px; }
      .root-g14mjS .authBox-1HR6Ha .sizeTiny-EgeIrh:hover,
      .modal-1ocm0B .authBox-1HR6Ha .sizeTiny-EgeIrh:hover {
        text-decoration: underline !important; }
  .root-g14mjS .header-1zd7se,
  .modal-1ocm0B .header-1zd7se {
    padding: 16px;
    background-color: transparent;
    border-radius: var(--popout-radius-big) var(--popout-radius-big) 0 0;
    border-bottom: 1px solid var(--popout-header-border);
    box-shadow: none !important; }
    .root-g14mjS .header-1zd7se.header-o8wV_s,
    .modal-1ocm0B .header-1zd7se.header-o8wV_s {
      margin-top: 0;
      align-items: flex-start; }
      .root-g14mjS .header-1zd7se.header-o8wV_s .closeButton-32emop,
      .modal-1ocm0B .header-1zd7se.header-o8wV_s .closeButton-32emop {
        top: auto; }
    .root-g14mjS .header-1zd7se .close-1mLglB,
    .modal-1ocm0B .header-1zd7se .close-1mLglB {
      width: 32px;
      height: 32px;
      right: 12px;
      margin: 0;
      padding: 0;
      background-color: transparent !important;
      position: relative;
      position: absolute; }
      .root-g14mjS .header-1zd7se .close-1mLglB:after,
      .modal-1ocm0B .header-1zd7se .close-1mLglB:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      .root-g14mjS .header-1zd7se .close-1mLglB:hover:after,
      .modal-1ocm0B .header-1zd7se .close-1mLglB:hover:after {
        opacity: 1;
        transform: scale(1.1);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      .root-g14mjS .header-1zd7se .close-1mLglB:active:after,
      .modal-1ocm0B .header-1zd7se .close-1mLglB:active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
      .root-g14mjS .header-1zd7se .close-1mLglB .contents-3ca1mk,
      .modal-1ocm0B .header-1zd7se .close-1mLglB .contents-3ca1mk {
        height: 24px; }
      .root-g14mjS .header-1zd7se .close-1mLglB svg,
      .modal-1ocm0B .header-1zd7se .close-1mLglB svg {
        transform: scale(0.85); }
    .root-g14mjS .header-1zd7se.headerContainer-SNQkF2 .art-2p0nYa,
    .modal-1ocm0B .header-1zd7se.headerContainer-SNQkF2 .art-2p0nYa {
      display: none; }
    .root-g14mjS .header-1zd7se.headerContainer-SNQkF2 .header-2zHCAk,
    .modal-1ocm0B .header-1zd7se.headerContainer-SNQkF2 .header-2zHCAk {
      padding-top: 0;
      align-items: stretch; }
      .root-g14mjS .header-1zd7se.headerContainer-SNQkF2 .header-2zHCAk .headerText-3OXA-J,
      .modal-1ocm0B .header-1zd7se.headerContainer-SNQkF2 .header-2zHCAk .headerText-3OXA-J {
        line-height: 20px;
        font-size: 16px;
        font-weight: 600; }
  .root-g14mjS .header-1R3myj .title-3VYtQS,
  .root-g14mjS .header-1R3myj .subtitle-3Kkhfr,
  .modal-1ocm0B .header-1R3myj .title-3VYtQS,
  .modal-1ocm0B .header-1R3myj .subtitle-3Kkhfr {
    text-align: left; }
  .root-g14mjS .content-2hZxGK,
  .modal-1ocm0B .content-2hZxGK {
    padding: 16px;
    background-color: transparent;
    border-radius: 0 0 var(--popout-radius-big) var(--popout-radius-big); }
    .root-g14mjS .content-2hZxGK .content-1G6Z6z,
    .modal-1ocm0B .content-2hZxGK .content-1G6Z6z {
      padding-bottom: 0; }
    .root-g14mjS .content-2hZxGK .formGroup-3b6DOC,
    .modal-1ocm0B .content-2hZxGK .formGroup-3b6DOC {
      margin-bottom: 16px; }
      .root-g14mjS .content-2hZxGK .formGroup-3b6DOC:nth-child(2),
      .modal-1ocm0B .content-2hZxGK .formGroup-3b6DOC:nth-child(2) {
        margin-bottom: 0; }
    .root-g14mjS .content-2hZxGK .reset-2ikQ30,
    .modal-1ocm0B .content-2hZxGK .reset-2ikQ30 {
      margin-bottom: 0;
      background-color: transparent !important; }
    .root-g14mjS .content-2hZxGK a,
    .modal-1ocm0B .content-2hZxGK a {
      color: hsl(var(--accent-hsl)); }
  .root-g14mjS .footer-31IekZ,
  .modal-1ocm0B .footer-31IekZ {
    padding: 8px;
    background-color: transparent !important;
    border-radius: 0 0 var(--popout-radius-big) var(--popout-radius-big);
    border-top: 1px solid var(--popout-header-border);
    box-shadow: none !important; }
    .root-g14mjS .footer-31IekZ .button-f2h6uQ.lookLink-15mFoz,
    .modal-1ocm0B .footer-31IekZ .button-f2h6uQ.lookLink-15mFoz {
      margin-right: 8px; }

.video-1j0A3v {
  padding: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius-big) var(--popout-radius-big) 0 0;
  border-bottom: 1px solid var(--popout-header-border); }

.content-gjD8J2 {
  padding: 16px; }
  .content-gjD8J2 .features-1tMYEH {
    width: 100%; }
    .content-gjD8J2 .features-1tMYEH .icon-1HfuQI {
      background-color: var(--menu-item-hover); }

.footer-2sB7av {
  margin: 0;
  padding: 16px; }

/*
 *
 *	INPUTS
 *
 */
.input-2g-os5 {
  height: var(--input-height);
  padding: 0;
  background-color: transparent;
  border-radius: 0;
  border: none; }

.inputWrapper-1YNMmM,
.note-1MiCN7,
.note-3M15gE,
.note-Go5ZP2,
.container-1_EVMa {
  position: relative;
  height: var(--input-height);
  max-height: var(--input-height);
  padding: 0;
  background-color: transparent;
  border-radius: 0;
  border: none;
  border-bottom: 1px solid var(--input-border-color) !important; }
  .inputWrapper-1YNMmM:before, .inputWrapper-1YNMmM:after,
  .note-1MiCN7:before,
  .note-1MiCN7:after,
  .note-3M15gE:before,
  .note-3M15gE:after,
  .note-Go5ZP2:before,
  .note-Go5ZP2:after,
  .container-1_EVMa:before,
  .container-1_EVMa:after {
    position: absolute;
    content: " ";
    height: 2px;
    width: 0;
    bottom: -1px;
    background: hsla(var(--accent-hsl));
    transition: 300ms ease all;
    z-index: 2; }
  .inputWrapper-1YNMmM:before,
  .note-1MiCN7:before,
  .note-3M15gE:before,
  .note-Go5ZP2:before,
  .container-1_EVMa:before {
    left: 50%; }
  .inputWrapper-1YNMmM:after,
  .note-1MiCN7:after,
  .note-3M15gE:after,
  .note-Go5ZP2:after,
  .container-1_EVMa:after {
    right: 50%; }
  .inputWrapper-1YNMmM:focus-within:before, .inputWrapper-1YNMmM:focus-within:after,
  .note-1MiCN7:focus-within:before,
  .note-1MiCN7:focus-within:after,
  .note-3M15gE:focus-within:before,
  .note-3M15gE:focus-within:after,
  .note-Go5ZP2:focus-within:before,
  .note-Go5ZP2:focus-within:after,
  .container-1_EVMa:focus-within:before,
  .container-1_EVMa:focus-within:after {
    width: 50%; }

.multiInputLast-35zVz0:before {
  border: none;
  opacity: 1; }

.copyInput-3AbKWB {
  height: var(--input-height);
  background-color: var(--input-color) !important;
  border-radius: var(--input-radius);
  border: none !important; }
  .copyInput-3AbKWB .input-2QVoG3 {
    padding: 8px 8px 8px 12px; }
  .copyInput-3AbKWB .button-f2h6uQ {
    --button-height: 32px;
    margin: 3px; }

.note-1MiCN7,
.note-3M15gE,
.note-Go5ZP2 {
  margin: 0; }
  .note-1MiCN7 textarea,
  .note-3M15gE textarea,
  .note-Go5ZP2 textarea {
    font-size: 15px; }
    .note-1MiCN7 textarea:focus,
    .note-3M15gE textarea:focus,
    .note-Go5ZP2 textarea:focus {
      background-color: transparent; }

.note-3M15gE {
  height: unset;
  min-height: unset;
  max-height: unset; }

.input-m1-Y7Q {
  background-color: transparent; }

/*
 *
 *	SELECT MENUS
 *
 */
[class^="css-"][class*="-control"] {
  background-color: var(--input-color);
  border-radius: var(--card-radius);
  border: none; }
[class^="css-"][class*="-menu"] {
  background-color: var(--popout-color);
  border-radius: 0 0 var(--popout-radius) var(--popout-radius);
  border: none;
  box-shadow: var(--shadow-3dp); }
  [class^="css-"][class*="-menu"] .css-1ye7vu0 {
    overflow-x: hidden; }
  [class^="css-"][class*="-menu"] .css-rzbxvl-option, [class^="css-"][class*="-menu"] .css-pkcurw-option {
    background-color: var(--menu-item-hover);
    overflow: hidden;
    text-overflow: ellipsis; }
  [class^="css-"][class*="-menu"] .css-1ba14n5-option, [class^="css-"][class*="-menu"] .css-1gxgi19-option {
    background-color: var(--menu-item-select);
    overflow: hidden;
    text-overflow: ellipsis; }

.select-1Ia3hD {
  border-radius: var(--input-radius);
  border: none; }
  .select-1Ia3hD, .select-1Ia3hD.lookFilled-1GseHa {
    background-color: var(--input-color); }

.popout-1KHNAq {
  margin: 4px 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  border: none;
  box-shadow: var(--shadow-3dp); }
  .popout-1KHNAq .option-2eIyOn {
    color: var(--menu-item-text-color);
    transition: var(--default-time) var(--default-animation) background-color; }
    .popout-1KHNAq .option-2eIyOn:hover {
      background-color: var(--menu-item-hover); }
    .popout-1KHNAq .option-2eIyOn[aria-selected=true] {
      background-color: var(--menu-item-select); }
      .popout-1KHNAq .option-2eIyOn[aria-selected=true] .selectedIcon-19TbzU {
        color: hsl(var(--accent-hsl)); }

/*
 *
 *	RADIO BUTTONS
 *
 */
div[role="radiogroup"] {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  div[role="radiogroup"] .item-2idW98 {
    margin: 0;
    padding: 4px 16px;
    background-color: transparent;
    border-radius: 0;
    position: relative;
    border-bottom: none; }
    div[role="radiogroup"] .item-2idW98:after {
      position: absolute;
      content: " ";
      width: calc(100% - 48px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    div[role="radiogroup"] .item-2idW98:last-of-type:after {
      display: none; }
    div[role="radiogroup"] .item-2idW98:hover, div[role="radiogroup"] .item-2idW98[aria-checked=true] {
      background-color: transparent; }
    div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY- {
      position: relative; }
      div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY-:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--accent-hsl), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY-:hover:after {
        opacity: 1;
        transform: scale(1.15);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY-:active:after {
        background-color: hsla(var(--accent-hsl), 0.2); }
      div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY-:after {
        width: 32px;
        height: 32px;
        top: -4px;
        left: -4px; }
      div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioBar-3w9XY- path {
        fill: hsl(var(--accent-hsl)) !important; }
    div[role="radiogroup"] .item-2idW98[aria-checked=true] .radioIconForeground-2BMavi {
      color: hsl(var(--accent-hsl)); }
    div[role="radiogroup"] .item-2idW98 .radioBar-3w9XY- {
      margin-bottom: 0;
      padding: 8px 0 8px 0 !important;
      border-left: none;
      position: relative; }
      div[role="radiogroup"] .item-2idW98 .radioBar-3w9XY-:after {
        content: " ";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-color: hsla(var(--md-ripple-color), 0.1);
        border-radius: 50%;
        opacity: 0;
        pointer-events: none;
        transform: scale(1.2);
        transition: 300ms ease;
        z-index: 4; }
      div[role="radiogroup"] .item-2idW98 .radioBar-3w9XY-:hover:after {
        opacity: 1;
        transform: scale(1.15);
        animation: scale 150ms var(--default-animation), opacity 150ms ease; }
      div[role="radiogroup"] .item-2idW98 .radioBar-3w9XY-:active:after {
        background-color: hsla(var(--md-ripple-color), 0.2); }
      div[role="radiogroup"] .item-2idW98 .radioBar-3w9XY-:after {
        width: 32px;
        height: 32px;
        top: -3px;
        left: -4px;
        bottom: 0;
        margin: auto 0; }
    div[role="radiogroup"] .item-2idW98.disabled-3tqE8r {
      opacity: 1; }
      div[role="radiogroup"] .item-2idW98.disabled-3tqE8r .radioBar-3w9XY- {
        opacity: 0.3; }
  div[role="radiogroup"][aria-orientation="horizontal"] {
    height: 34px;
    border-radius: 17px;
    overflow: hidden; }
    div[role="radiogroup"][aria-orientation="horizontal"] .item-4m-12I {
      height: 32px;
      background-color: transparent;
      cursor: pointer;
      transition: var(--default-time) var(--default-animation) background-color; }
      div[role="radiogroup"][aria-orientation="horizontal"] .item-4m-12I:hover {
        background-color: var(--menu-item-hover); }
      div[role="radiogroup"][aria-orientation="horizontal"] .item-4m-12I.selected-3jieYB {
        background-color: var(--menu-item-select); }
  div[role="radiogroup"] .tooltipWrapper-Z59cgW {
    margin: 0;
    position: relative;
    border-bottom: none; }
    div[role="radiogroup"] .tooltipWrapper-Z59cgW:after {
      position: absolute;
      content: " ";
      width: calc(100% - 48px);
      height: 1px;
      right: 0;
      bottom: 0;
      background-color: var(--card-border-color); }
    div[role="radiogroup"] .tooltipWrapper-Z59cgW:last-of-type:after {
      display: none; }
    div[role="radiogroup"] .tooltipWrapper-Z59cgW:last-child {
      border-bottom: none; }

/*
 *
 *	SWITCHES
 *
 */
.container-2nx-BQ {
  width: 32px;
  height: 14px;
  background-color: hsl(var(--switch-slider-color)) !important;
  overflow: visible; }
  .container-2nx-BQ[style*="43.9%"] {
    background-color: hsla(var(--accent-hsl), 0.3) !important; }
    .container-2nx-BQ[style*="43.9%"] .slider-32CRPX {
      background-color: hsl(var(--accent-hsl)); }
  .container-2nx-BQ .slider-32CRPX {
    width: 20px;
    height: 20px;
    top: -3px;
    margin: 0;
    background-color: hsl(var(--switch-knob-color));
    border-radius: 50%;
    box-shadow: var(--shadow-1dp); }
    .container-2nx-BQ .slider-32CRPX rect,
    .container-2nx-BQ .slider-32CRPX svg {
      display: none; }

.bd-switch {
  width: 32px;
  height: 14px;
  overflow: visible; }
  .bd-switch .bd-switch-body {
    --switch-color: hsl(var(--switch-slider-color));
    width: 32px;
    height: 14px;
    overflow: visible; }
    .bd-switch .bd-switch-body .bd-switch-slider {
      height: 20px;
      top: -3px;
      left: -7px;
      margin: 0;
      overflow: visible; }
      .bd-switch .bd-switch-body .bd-switch-slider .bd-switch-handle {
        fill: hsl(var(--switch-knob-color));
        filter: drop-shadow(0 2px 2px rgba(0, 0, 0, 0.2)); }
      .bd-switch .bd-switch-body .bd-switch-slider .bd-switch-symbol {
        display: none; }
  .bd-switch input:active + .bd-switch-body {
    --switch-color: hsl(var(--switch-slider-color)); }
  .bd-switch input:checked + .bd-switch-body {
    --switch-color: hsla(var(--accent-hsl),0.3); }
    .bd-switch input:checked + .bd-switch-body .bd-switch-slider {
      left: 8px; }
      .bd-switch input:checked + .bd-switch-body .bd-switch-slider .bd-switch-handle {
        fill: hsl(var(--accent-hsl)); }
  .bd-switch input:checked:active + .bd-switch-body {
    --switch-color: hsla(var(--accent-hsl),0.3); }

/*
 *
 *	CHECKBOXES
 *
 */
.checkbox-f1HnKB {
  border-width: 2px;
  transition: var(--default-time) var(--default-animation) border-color, var(--default-time) var(--default-animation) background-color; }
  .checkbox-f1HnKB.box-BHImcZ {
    border-radius: 4px; }
  .checkbox-f1HnKB:not(.checked-1pZh2h) path {
    transition: var(--default-time) var(--default-animation) fill; }
  .checkbox-f1HnKB.checked-1pZh2h {
    background-color: hsl(var(--accent-hsl)) !important;
    border-color: hsl(var(--accent-hsl)) !important; }
    .checkbox-f1HnKB.checked-1pZh2h path {
      fill: var(--accent-text-color);
      transition: var(--default-time) var(--default-animation) fill; }

.colorDefault-CDqZdO .checkbox-hADx5o {
  color: hsl(var(--accent-hsl)); }
.colorDefault-CDqZdO .check-3HZJs4 {
  color: var(--accent-text-color); }
.colorDefault-CDqZdO.focused-3qFvc8 .checkbox-hADx5o {
  color: hsl(var(--accent-hsl)); }
.colorDefault-CDqZdO.focused-3qFvc8 .check-3HZJs4 {
  color: var(--accent-text-color); }

/*
 *
 *	SLIDER BARS
 *
 */
.slider-1NC-Gf .markAbove-21dc11 {
  top: -8px; }
.slider-1NC-Gf .bar-1Bhnl9 {
  height: 4px;
  background-color: hsla(var(--accent-hsl), 0.3) !important;
  border-radius: 2px; }
  .slider-1NC-Gf .bar-1Bhnl9 .barFill-2Bh7CX {
    background-color: hsl(var(--accent-hsl)) !important; }
.slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM {
  width: 16px;
  height: 16px;
  background-color: hsl(var(--accent-hsl));
  border-radius: 50%;
  border: none;
  box-shadow: var(--shadow-1dp);
  transform: translate(-3px, calc(50% - 5px));
  transition: var(--default-time) var(--default-animation) box-shadow;
  position: relative; }
  .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:after {
    content: " ";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: hsla(var(--accent-hsl), 0.1);
    border-radius: 50%;
    opacity: 0;
    pointer-events: none;
    transform: scale(1.2);
    transition: 300ms ease;
    z-index: 4; }
  .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:hover:after, .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:active:after {
    opacity: 1;
    transform: scale(2.5);
    animation: scale 150ms var(--default-animation), opacity 150ms ease; }
  .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:active:after {
    background-color: hsla(var(--accent-hsl), 0.2); }
  .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:hover {
    box-shadow: var(--shadow-2dp); }
  .slider-1NC-Gf .track-1BI4CA .grabber-2GQyvM:active {
    box-shadow: var(--shadow-3dp); }
.slider-1NC-Gf.slider-BEB8u7 .track-1BI4CA .grabber-2GQyvM {
  top: calc(50% - 5px); }

.markValue-2U_-UG {
  color: var(--text-muted) !important; }

.themedPopout-1TrfdI .volumeSlider-sR5g00 {
  margin: 8px; }
  .themedPopout-1TrfdI .volumeSlider-sR5g00 .track-1BI4CA .grabber-2GQyvM {
    top: 1px; }

.wrapper-UvA17F {
  height: 4px;
  border-radius: 2px;
  overflow: hidden; }
  .wrapper-UvA17F .container-3NTP7o {
    width: 100% !important; }
    .wrapper-UvA17F .container-3NTP7o[style*='background: linear-gradient(to right, rgb(251, 184, 72), rgb(67, 181, 129));'] {
      background: var(--success-color) !important; }
  .wrapper-UvA17F .progress-1S-TDF {
    background-color: var(--slider-color); }
  .wrapper-UvA17F .notches-2w7UZJ {
    display: none; }

/*
 *
 *	CARDS
 *
 */
.card-16VQ8C {
  background-color: var(--card-color) ;
  border-radius: var(--card-radius-big) ;
  border: 1px solid var(--card-border-color) ; }
  .card-16VQ8C a {
    color: hsl(var(--accent-hsl)); }

/* CARDS -> HEADER */
.formNoticeTitle-2qYdGw.colorStandard-21JIj7,
.labelBold-199Hd8.colorStandard-21JIj7 {
  font-size: 1em;
  font-weight: 500;
  color: var(--card-header-text-color);
  text-transform: none;
  opacity: 1; }

.h4-1_f8j1,
.h5-2RwDNl {
  text-transform: none; }

.h5-2RwDNl {
  font-size: 14px; }

/*
 *
 *	BUTTONS
 *
 */
.button-f2h6uQ.lookFilled-yCfaCM, .button-f2h6uQ.lookOutlined-3yKVGo, .button-f2h6uQ.lookInverted-2mDUMi {
  border-radius: var(--button-radius);
  border: none;
  font-size: 1em; }
  .button-f2h6uQ.lookFilled-yCfaCM:not([disabled]), .button-f2h6uQ.lookOutlined-3yKVGo:not([disabled]), .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]) {
    box-shadow: var(--shadow-1dp);
    transition: var(--default-time) var(--default-animation) box-shadow; }
    .button-f2h6uQ.lookFilled-yCfaCM:not([disabled]):hover, .button-f2h6uQ.lookOutlined-3yKVGo:not([disabled]):hover, .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]):hover {
      box-shadow: var(--shadow-2dp); }
    .button-f2h6uQ.lookFilled-yCfaCM:not([disabled]):active, .button-f2h6uQ.lookOutlined-3yKVGo:not([disabled]):active, .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]):active {
      box-shadow: var(--shadow-3dp); }
    .button-f2h6uQ.lookFilled-yCfaCM:not([disabled]):after, .button-f2h6uQ.lookOutlined-3yKVGo:not([disabled]):after, .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]):after {
      position: absolute;
      content: " ";
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      border-radius: var(--button-radius);
      opacity: 0;
      pointer-events: none;
      transition: var(--default-time) var(--default-animation) opacity; }
  .button-f2h6uQ.lookFilled-yCfaCM:disabled, .button-f2h6uQ.lookOutlined-3yKVGo:disabled, .button-f2h6uQ.lookInverted-2mDUMi:disabled {
    background-color: rgba(var(--button-link-color), 0.15) !important;
    color: var(--button-link-text-color) !important; }
  .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79 {
    background-color: hsl(var(--accent-hsl));
    color: var(--accent-text-color); }
    .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ:after, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B:after, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79:after, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ:after, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B:after, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79:after {
      background-color: var(--accent-button-action); }
    .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ:hover, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo:hover, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B:hover, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ:hover, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79:hover, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ:hover, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo:hover, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B:hover, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ:hover, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79:hover, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ:hover, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo:hover, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B:hover, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ:hover, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79:hover {
      background-color: hsl(var(--accent-hsl)); }
      .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ:hover:after, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo:hover:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B:hover:after, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ:hover:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79:hover:after {
        opacity: var(--accent-button-action-hover); }
    .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ:active, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo:active, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B:active, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ:active, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79:active, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ:active, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo:active, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B:active, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ:active, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79:active, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ:active, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo:active, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B:active, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ:active, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79:active {
      background-color: hsl(var(--accent-hsl)); }
      .button-f2h6uQ.lookFilled-yCfaCM.colorBrand-I6CyqQ:active:after, .button-f2h6uQ.lookFilled-yCfaCM.colorPrimary-2AuQVo:active:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGrey-2iAG-B:active:after, .button-f2h6uQ.lookFilled-yCfaCM.colorWhite-rEQuAQ:active:after, .button-f2h6uQ.lookFilled-yCfaCM.colorGreen-3y-Z79:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorBrand-I6CyqQ:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorPrimary-2AuQVo:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGrey-2iAG-B:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorWhite-rEQuAQ:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorGreen-3y-Z79:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorBrand-I6CyqQ:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorPrimary-2AuQVo:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGrey-2iAG-B:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorWhite-rEQuAQ:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorGreen-3y-Z79:active:after {
        opacity: var(--accent-button-action-active); }
  .button-f2h6uQ.lookFilled-yCfaCM.colorRed-rQXKgM, .button-f2h6uQ.lookOutlined-3yKVGo.colorRed-rQXKgM, .button-f2h6uQ.lookInverted-2mDUMi.colorRed-rQXKgM {
    background-color: var(--alert-color);
    color: var(--alert-text-color);
    border: none; }
    .button-f2h6uQ.lookFilled-yCfaCM.colorRed-rQXKgM:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorRed-rQXKgM:after, .button-f2h6uQ.lookInverted-2mDUMi.colorRed-rQXKgM:after {
      background-color: var(--alert-button-action); }
    .button-f2h6uQ.lookFilled-yCfaCM.colorRed-rQXKgM:hover:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorRed-rQXKgM:hover:after, .button-f2h6uQ.lookInverted-2mDUMi.colorRed-rQXKgM:hover:after {
      opacity: var(--alert-button-action-hover); }
    .button-f2h6uQ.lookFilled-yCfaCM.colorRed-rQXKgM:active:after, .button-f2h6uQ.lookOutlined-3yKVGo.colorRed-rQXKgM:active:after, .button-f2h6uQ.lookInverted-2mDUMi.colorRed-rQXKgM:active:after {
      opacity: var(--alert-button-action-active); }
.button-f2h6uQ.lookLink-15mFoz, .button-f2h6uQ.lookBlank-21BCro {
  border-radius: var(--button-radius);
  font-size: 1em; }
  .button-f2h6uQ.lookLink-15mFoz:not([disabled]), .button-f2h6uQ.lookBlank-21BCro:not([disabled]) {
    color: var(--button-link-text-color);
    transition: var(--default-time) var(--default-animation) background-color; }
    .button-f2h6uQ.lookLink-15mFoz:not([disabled]):hover, .button-f2h6uQ.lookBlank-21BCro:not([disabled]):hover {
      background-color: rgba(var(--button-link-color), 0.075);
      text-decoration: none; }
      .button-f2h6uQ.lookLink-15mFoz:not([disabled]):hover .contents-3ca1mk, .button-f2h6uQ.lookBlank-21BCro:not([disabled]):hover .contents-3ca1mk {
        background-image: none; }
    .button-f2h6uQ.lookLink-15mFoz:not([disabled]):active, .button-f2h6uQ.lookBlank-21BCro:not([disabled]):active {
      background-color: rgba(var(--button-link-color), 0.125); }
.button-f2h6uQ.lookInverted-2mDUMi {
  border-radius: var(--button-radius);
  font-size: 0.9em; }
  .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]) {
    box-shadow: var(--shadow-1dp);
    transition: var(--default-time) var(--default-animation) box-shadow; }
    .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]):hover {
      box-shadow: var(--shadow-2dp); }
    .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]):active {
      box-shadow: var(--shadow-3dp); }
    .button-f2h6uQ.lookInverted-2mDUMi:not([disabled]).colorBrand-I6CyqQ {
      background-color: hsl(var(--accent-hsl));
      color: var(--accent-text-color); }
.button-f2h6uQ.sizeMin-DfpWCE, .button-f2h6uQ.sizeSmall-wU2dO-, .button-f2h6uQ.sizeMedium-2bFIHr, .button-f2h6uQ.sizeLarge-1vSeWK, .button-f2h6uQ.sizeXlarge-2yFAlZ, .button-f2h6uQ.buttonSize-dIiz43, .button-f2h6uQ.buttonSize-3QlBTl {
  min-width: var(--button-height);
  height: var(--button-height);
  min-height: var(--button-height);
  padding: var(--button-padding);
  border-radius: var(--button-radius); }
.button-f2h6uQ.followButton-1N-GGp {
  min-width: 80px; }
.button-f2h6uQ.backButton-2Ps-B8 {
  margin-right: 0; }
.button-f2h6uQ .buttonIcon-2Zsrs2.withText-2iJppd {
  margin-right: 6px; }

.disabledButtonWrapper-3wH6-b .button-f2h6uQ {
  background-color: rgba(var(--button-link-color), 0.15);
  box-shadow: none; }

/*
 *
 *	TAB BARS
 *
 */
.tabBar-2WhZ9G .item-3XjbnG {
  height: inherit;
  border-radius: 0; }
  .tabBar-2WhZ9G .item-3XjbnG, .tabBar-2WhZ9G .item-3XjbnG:hover, .tabBar-2WhZ9G .item-3XjbnG.selected-g-kMVV {
    background-color: transparent !important; }
  .tabBar-2WhZ9G .item-3XjbnG.selected-g-kMVV {
    position: relative;
    background-color: transparent !important; }
    .tabBar-2WhZ9G .item-3XjbnG.selected-g-kMVV:after {
      position: absolute;
      content: " ";
      width: 90%;
      height: 3px;
      left: 0;
      right: 0;
      bottom: 0;
      margin: 0 auto;
      background: var(--tab-border-color);
      border-radius: 3px 3px 0 0;
      transition: var(--default-time) ease all; }
  .tabBar-2WhZ9G .item-3XjbnG:last-of-type {
    margin-right: 0; }

.tabBar-3N44FC {
  height: 52px; }
  .tabBar-3N44FC .item-3XjbnG {
    border-radius: 12px; }
    .tabBar-3N44FC .item-3XjbnG:hover {
      background-color: var(--menu-item-hover) !important; }
    .tabBar-3N44FC .item-3XjbnG.selected-g-kMVV {
      background-color: var(--menu-item-select) !important; }

/*
 *
 *	TOOLTIPS
 *
 */
.tooltip-14MtrL {
  padding: var(--tooltip-padding);
  background-color: var(--tooltip-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--tooltip-shadow) !important;
  font-size: var(--tooltip-font-size);
  font-weight: 500; }
  .tooltip-14MtrL {
    z-index: 99999999999999;
    animation: opacity var(--default-time) ease; }
  .tooltip-14MtrL .tooltipPointer-3L49xb {
    display: none; }
  .tooltip-14MtrL .tooltipContent-Nejnvh,
  .tooltip-14MtrL .guildNameText-jBFbNC {
    padding: 0;
    font-size: var(--tooltip-font-size);
    color: var(--tooltip-text-color); }
  .tooltip-14MtrL .bodyInnerWrapper-2bQs1k {
    background-color: transparent; }
  .tooltip-14MtrL .note-Go5ZP2 {
    border-bottom: 1px solid #999 !important; }
  .tooltip-14MtrL .rolesList-3uZoaa:last-of-type {
    margin-bottom: 0; }
  .tooltip-14MtrL .activityIcon-vfIBet path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"] {
    d: path("M3 9v6h4l5 5V4L7 9H3zm7-.17v6.34L7.83 13H5v-2h2.83L10 8.83zM16.5 12c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77 0-4.28-2.99-7.86-7-8.77z"); }
  .tooltip-14MtrL .colorMuted-20987_ {
    color: #ddd; }

.subscribeTooltipWrapper-3ipXtC {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .subscribeTooltipWrapper-3ipXtC:after {
    border-bottom-color: var(--popout-color); }
  .subscribeTooltipWrapper-3ipXtC .subscribeTooltipHeader-15pGbG {
    color: var(--header-primary); }
  .subscribeTooltipWrapper-3ipXtC .subscribeTooltipText-2A8MMi {
    color: var(--header-secondary); }

.container-3-AQTb {
  background-color: var(--popout-color) ;
  border-radius: var(--popout-radius-big) ;
  box-shadow: var(--shadow-3dp) ; }
  .container-3-AQTb .text-3Zs7a0 {
    color: var(--text-normal); }
  .container-3-AQTb .pointer-12wKfh {
    border-top-color: var(--popout-color); }

/*
 *
 *	TOASTS
 *
 */
.toast,
.bd-toast {
  padding: 12px 16px;
  background-color: rgba(70, 70, 70, 0.8);
  border-radius: 20px;
  box-shadow: none;
  font-size: 1em;
  font-weight: 400;
  color: #fff; }

/*
 *
 *	VERIFIED/PARTNER ICONS
 *
 */
.flowerStarContainer-1QeD-L.verified-1Jv_7P, .flowerStarContainer-1QeD-L.partnered-23cXFN {
  color: hsl(var(--accent-hsl)); }
  .flowerStarContainer-1QeD-L.verified-1Jv_7P .icon-3BYlXK, .flowerStarContainer-1QeD-L.partnered-23cXFN .icon-3BYlXK {
    color: var(--accent-text-color); }
.flowerStarContainer-1QeD-L .flowerStar-2tNFCR path {
  fill: hsl(var(--accent-hsl)); }
.flowerStarContainer-1QeD-L .childContainer-U_a6Yh path {
  fill: var(--accent-text-color); }

/*
 *
 *	BETTERDISCORD
 *
 */
.bd-settings-title {
  margin-bottom: 20px;
  line-height: 24px;
  font-size: 20px;
  font-weight: 600;
  color: var(--header-primary); }

#bd-editor-panel {
  border-radius: var(--card-radius-big);
  overflow: hidden; }

#bd-editor-controls {
  background-color: var(--main-color);
  border-radius: var(--card-radius-big) var(--card-radius-big) 0 0;
  border: 1px solid var(--card-border-color); }

.monaco-editor {
  background-color: var(--main-color); }
  .monaco-editor, .monaco-editor-background,
  .monaco-editor .inputarea.ime-input,
  .monaco-editor .margin {
    background-color: inherit !important; }
  .monaco-editor .overflow-guard {
    border-radius: 0 0 var(--card-radius-big) var(--card-radius-big);
    border: 1px solid var(--card-border-color);
    border-top: none; }
  .monaco-editor .minimap {
    right: 7px;
    background-color: inherit !important; }
    .monaco-editor .minimap-shadow-visible {
      box-shadow: none !important; }
  .monaco-editor .scroll-decoration {
    box-shadow: none !important; }

/* BETTERDISCORD -> ADDON ERROR */
.bd-addon-error {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color) !important; }
  .bd-addon-error .bd-addon-error-body {
    padding: 0;
    border-top: 1px solid var(--card-border-color); }
    .bd-addon-error .bd-addon-error-body .divider-3LgWDL {
      display: none; }
  .bd-addon-error .bd-addon-error-stack {
    margin: 16px; }
    .bd-addon-error .bd-addon-error-stack code {
      background-color: var(--attachment-color);
      border-radius: var(--card-radius-big);
      border: none; }

/*
 *
 *	POWERCORD
 *
 */
.powercord-product {
  padding: 0 !important; }
  .powercord-product .divider-3LgWDL {
    margin-top: 0; }

.powercord-product-header {
  margin-bottom: 0 !important;
  padding: 16px; }
  .powercord-product-header .container-2nx-BQ {
    margin-top: 4px; }

.powercord-product-details {
  padding: 0 16px 16px; }

/*
 *
 *	GOOSEMOD
 *
 */
#gm-settings-inject {
  background-color: transparent !important; }

.gm-store-category {
  position: relative; }
  .gm-store-category:before, .gm-store-category:after {
    position: absolute;
    content: " ";
    width: 10px;
    height: 100%;
    top: 0;
    z-index: 2; }
  .gm-store-category:before {
    left: 0;
    background: linear-gradient(90deg, var(--chat-color) 0%, transparent 100%); }
  .gm-store-category:after {
    right: 0;
    background: linear-gradient(90deg, transparent 0%, var(--chat-color) 100%); }

.gm-store-card {
  background-color: var(--card-color-alt) !important;
  border-radius: var(--card-radius-big) !important;
  border: 1px solid var(--card-border-color);
  box-shadow: none !important;
  overflow: hidden;
  transition: var(--default-time) var(--default-animation) transform, var(--default-time) var(--default-animation) box-shadow, var(--default-time) var(--default-animation) border-color; }
  .gm-store-card:hover {
    box-shadow: var(--shadow-3dp) !important;
    border-color: transparent !important;
    transform: translateY(-1px); }
    .gm-store-card:hover > :nth-child(1) {
      transform: scale(1.01) translateZ(0); }
  .gm-store-card > :nth-child(1) {
    height: 150px !important;
    background-color: var(--attachment-color) !important;
    border-bottom: 1px solid var(--card-border-color);
    transition: var(--default-time) var(--default-animation) transform; }
  .gm-store-card > :nth-child(2) {
    top: 108px !important;
    right: 8px !important; }
    .gm-store-card > :nth-child(2) .author {
      color: var(--status-positive-text) !important; }
  .gm-store-card > :nth-child(3),
  .gm-store-card > :nth-child(4) {
    width: calc(100% - 56px) !important; }
  .gm-store-card > :nth-child(5) {
    top: 154px !important; }

.loadingPopout-1feYe_ {
  background-color: var(--popout-color);
  box-shadow: var(--shadow-3dp);
  border-radius: 24px; }

.path3-3tVOpU {
  stroke: hsl(var(--accent-hsl)) !important; }

/*
 *
 *	SUPPORTED PLUGINS
 *
 */
/* SUPPORTED PLUGINS -> BetterFormattingRedux */
.bf-toolbar {
  z-index: 2; }

/* SUPPORTED PLUGINS -> CharCounter */
.charCounterAdded-zz9O4t .channelTextArea-1FufC0 {
  margin-bottom: 0; }
  .charCounterAdded-zz9O4t .channelTextArea-1FufC0 .scrollableContainer-15eg7h {
    border-radius: var(--main-textarea-radius) var(--main-textarea-radius) 0 0; }
    .charCounterAdded-zz9O4t .channelTextArea-1FufC0 .scrollableContainer-15eg7h.hasReply-16cIUP {
      border-radius: 0; }

.counter-uAzbKp {
  height: var(--main-textarea-radius);
  padding: 0 12px;
  line-height: var(--main-textarea-radius);
  background-color: var(--main-textarea-color);
  border-radius: 0 0 var(--main-textarea-radius) var(--main-textarea-radius);
  border: 1px solid var(--main-textarea-border);
  border-top: none;
  box-sizing: border-box;
  text-align: right;
  font-weight: 500; }
  .counter-uAzbKp.chatCounter-XOMPsh {
    position: relative;
    bottom: auto;
    margin-bottom: 12px; }

/* SUPPORTED PLUGINS -> HideChannels */
.sidebar-1tnWFu.hideElement .container-YkUktl {
  height: 70px !important;
  margin-bottom: 0 !important;
  background-color: var(--chat-color) !important; }
.sidebar-1tnWFu.hideElement + .chat-2ZfjoI .typing-2J1mQU {
  width: calc(100% + 240px);
  left: -240px; }

/* SUPPORTED PLUGINS -> MemberCounter */
#MemberCount {
  margin-top: 0 !important;
  background-color: var(--main-color) !important; }
  #MemberCount .membersGroup-2eiWxl {
    padding: 16px; }

/* SUPPORTED PLUGINS -> PermissionsViewer */
#permissions-modal-wrapper #permissions-modal {
  border-radius: var(--popout-radius-big) !important;
  box-shadow: var(--shadow-3dp) !important;
  border: none !important; }
#permissions-modal-wrapper .header {
  background-color: var(--popout-color) !important;
  padding: 16px !important;
  box-shadow: none !important;
  border-bottom: 1px solid var(--popout-header-border);
  line-height: 20px !important;
  font-size: 16px !important;
  font-weight: 600 !important;
  color: var(--header-primary) !important; }
#permissions-modal-wrapper .modal-body {
  background-color: var(--popout-color) !important; }
#permissions-modal-wrapper .role-side {
  padding: 0 0 16px 16px !important;
  background-color: transparent !important;
  border-right: 1px solid var(--popout-header-border); }
#permissions-modal-wrapper .perm-side {
  padding: 0 0 16px 16px !important;
  background-color: transparent !important; }
#permissions-modal-wrapper .role-item {
  margin-bottom: 2px !important;
  border-radius: 14px !important; }
  #permissions-modal-wrapper .role-item:hover {
    background-color: var(--menu-item-hover) !important; }
  #permissions-modal-wrapper .role-item.selected {
    background-color: var(--menu-item-select) !important; }
#permissions-modal-wrapper .perm-item {
  position: relative;
  border-bottom: none;
  box-shadow: none !important; }
  #permissions-modal-wrapper .perm-item:after {
    position: absolute;
    content: " ";
    width: calc(100% - 34px);
    height: 1px;
    right: 0;
    bottom: 0;
    background-color: var(--card-border-color); }
  #permissions-modal-wrapper .perm-item:last-of-type:after {
    display: none; }

/* SUPPORTED PLUGINS -> PersonalPins */
.themedPopout-1TrfdI {
  border-radius: var(--popout-radius-big);
  box-shadow: var(--shadow-3dp); }
  .themedPopout-1TrfdI .header-145e10 {
    padding-bottom: 0 !important; }
  .themedPopout-1TrfdI .title-3OGHA5 {
    margin-top: 16px;
    line-height: 36px;
    font-weight: 500;
    font-size: 16px; }
  .themedPopout-1TrfdI .container-2oNtJn {
    margin-top: 16px; }
  .themedPopout-1TrfdI .tab-TRrPC8 {
    height: 32px;
    margin-right: 16px;
    padding: 0; }
    .themedPopout-1TrfdI .tab-TRrPC8:first-child {
      margin-right: 16px; }
  .themedPopout-1TrfdI .quickSelectWrapper-UCfTKz {
    margin-right: 16px;
    font-weight: 500; }

/* SUPPORTED PLUGINS -> StatusEverywhere */
.StatusEverywhere-avatar-chatAvatar.accountSettingsAvatar {
  width: 80px !important;
  height: 80px !important;
  top: 76px; }

.StatusEverywhere-avatar-userPopout {
  background-color: var(--popout-color) !important;
  border: none !important; }
  .StatusEverywhere-avatar-userPopout + .avatarHint-k7pYop {
    border-radius: var(--avatar-radius); }
    .StatusEverywhere-avatar-userPopout + .avatarHint-k7pYop foreignObject {
      border-radius: var(--avatar-radius) !important; }

/*
 *
 *	ANIMATIONS
 *
 */
@keyframes top-pop-out {
  from {
    transform: translate(0, -20px);
    opacity: 0; } }
@keyframes bottom-pop-out {
  from {
    transform: translate(0, 20px);
    opacity: 0; } }
@keyframes show-user-status-right {
  from {
    transform: translateX(-3%) translateY(0%) translateZ(0px);
    opacity: 0; } }
@keyframes show-user-status-left {
  from {
    transform: translateX(3%) translateY(0%) translateZ(0px);
    opacity: 0; } }
@keyframes show-status {
  from {
    transform: translateY(15%) translateX(0%) translateZ(0px); } }
@keyframes status {
  from {
    transform: scale(0);
    opacity: 0; } }
@keyframes opacity {
  from {
    opacity: 0; } }
@keyframes open-context-menu {
  from {
    transform: scale(1, 0.5); } }
@keyframes scale {
  from {
    transform: scale(0); } }
@keyframes streaming-flash {
  0% {
    box-shadow: 0 0 0 0px rgba(var(--stream-flash), 0.4); }
  50% {
    box-shadow: 0 0 0 4px rgba(var(--stream-flash), 0.65); }
  100% {
    box-shadow: 0 0 0 8px rgba(var(--stream-flash), 0); } }
@keyframes audio-flash {
  0% {
    box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2), 0 0 0 0px hsla(var(--accent-hsl), 0.4); }
  25% {
    box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2), 0 0 0 6px hsla(var(--accent-hsl), 0.65); }
  50% {
    box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2), 0 0 0 12px hsla(var(--accent-hsl), 0); } }
@keyframes shadowPulse-AwLIHr {
  0% {
    box-shadow: 0 0 6px hsla(var(--accent-hsla), 0.3); }
  50% {
    box-shadow: 0 0 10px hsla(var(--accent-hsl), 0.6); }
  to {
    box-shadow: 0 0 6px hsla(var(--accent-hsl), 0.3); } }
/*
 *
 *	SCROLLBARS
 *
 */
::-webkit-scrollbar {
  width: 10px !important;
  height: 10px !important; }
  ::-webkit-scrollbar-track {
    margin: 0 !important;
    background: transparent !important;
    border-radius: 0 !important; }
    ::-webkit-scrollbar-track-piece {
      border: 0 solid transparent !important;
      background-color: transparent !important;
      margin: 0; }
  ::-webkit-scrollbar-thumb {
    display: initial;
    background-color: rgba(var(--scrollbar-color), 0.15) !important;
    border: 0 solid transparent !important;
    border-radius: 0 !important; }
    ::-webkit-scrollbar-thumb:hover {
      background-color: rgba(var(--scrollbar-color), 0.25) !important; }
    ::-webkit-scrollbar-thumb:active {
      background-color: rgba(var(--scrollbar-color), 0.3) !important; }

.wrapper-1_HaEi [class*="scroller"]::-webkit-scrollbar {
  width: 0px !important; }

/*
 *
 *	FONTS
 *
 */
/* FONTS -> GOOGLE SANS */
/* FONTS -> GOOGLE SANS -> 400 */
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Regular"), local("GoogleSans-Regular"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Regular-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Regular"), local("GoogleSans-Regular"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Regular-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Regular"), local("GoogleSans-Regular"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Regular-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Regular"), local("GoogleSans-Regular"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Regular-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }
/* FONTS -> GOOGLE SANS -> 500 */
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium"), local("GoogleSans-Medium"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Medium-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium"), local("GoogleSans-Medium"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Medium-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium"), local("GoogleSans-Medium"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Medium-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium"), local("GoogleSans-Medium"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Medium-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }
/* FONTS -> GOOGLE SANS -> 700 */
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold"), local("GoogleSans-Bold"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Bold-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold"), local("GoogleSans-Bold"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Bold-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold"), local("GoogleSans-Bold"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Bold-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold"), local("GoogleSans-Bold"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-Bold-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }
/* FONTS -> GOOGLE SANS -> ITALIC */
/* FONTS -> GOOGLE SANS -> ITALIC -> 400 */
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Italic"), local("GoogleSans-Italic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-RegularItalic-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Italic"), local("GoogleSans-Italic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-RegularItalic-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Italic"), local("GoogleSans-Italic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-RegularItalic-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 400;
  font-display: swap;
  src: local("Google Sans Italic"), local("GoogleSans-Italic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-RegularItalic-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }
/* FONTS -> GOOGLE SANS -> ITALIC -> 500 */
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium Italic"), local("GoogleSans-MediumItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-MediumItalic-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium Italic"), local("GoogleSans-MediumItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-MediumItalic-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium Italic"), local("GoogleSans-MediumItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-MediumItalic-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: local("Google Sans Medium Italic"), local("GoogleSans-MediumItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-MediumItalic-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }
/* FONTS -> GOOGLE SANS -> ITALIC -> 700 */
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold Italic"), local("GoogleSans-BoldItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-BoldItalic-cyrillic.woff2) format("woff2");
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold Italic"), local("GoogleSans-BoldItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-BoldItalic-greek.woff2) format("woff2");
  unicode-range: U+0370-03FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold Italic"), local("GoogleSans-BoldItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-BoldItalic-latinext.woff2) format("woff2");
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF; }
@font-face {
  font-family: 'Google Sans';
  font-style: italic;
  font-weight: 700;
  font-display: swap;
  src: local("Google Sans Bold Italic"), local("GoogleSans-BoldItalic"), url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/fonts/GoogleSans-BoldItalic-latin.woff2) format("woff2");
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD; }

/*# sourceMappingURL=Material-Discord.theme.css.map */
