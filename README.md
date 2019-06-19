# libra-css
/* If you edit something, please leave a comment */

/* Answered posts */

/* This creates a red notification from ordered lists in the sidebar. If this is used, only unordered lists can be used in the sidebar */

.flair {
    background: url(%%spritesheet%%) no-repeat -9999px;
    border: 0;
    padding: 0;
}

.flair-lilflag {
    width: 17px;
    height: 11px;
    background-position: -5px -5px;
}

.flair-uyu {
    width: 16px;
    height: 12px;
    background-position: -5px -26px;
}


.titlebox .usertext-body .md ol {
    top: 125px;
    left: -30px;
    background: #FFE0E0;
    border: 1px solid #EEB2B2;
    padding: 5px 10px;
    position: absolute;
    list-style-type: none;
    border-radius: 2px;
    width: calc(100% - 349px);
    min-width: 498px;
}

body.submit-page .titlebox .usertext-body .md ol {
    width: 498px;
}

/* Creates Guidelines Box on submission page */
body.submit-page .titlebox .md>blockquote:nth-of-type(4) 
{
    position: absolute;
    top: 208px;
    left: 8px;
    width: 530px;
    background-color: #FFE0E0;
    border: 1px solid #FFD3D3;
    overflow: hidden;
}

body.submit-page .titlebox .md>blockquote:nth-of-type(4) h3 {
    background: #FFD3D3;
    border-top: none;
    border-bottom: none;
}

.submit_text.enabled {
    margin-bottom: -2px;
}

/*** BODY ***/

body {
    background: #f0f0f0;
}

html {
    min-width: 848px;
}

a {
    color: #0645AD;
}

a:hover {
    text-decoration: none !important;
    color: #ffd046;
}

#mail {
    position: relative
    display: inline-block;
    top: 2px;
    text-indent: -9999px;
    overflow: hidden;
    width: 16px;
    height: 16px;
}

#mail.havemail {
    background:url(%%mail-lib%%);
    vertical-align: top;
}

#mail.nohavemail {
    background:url(%%nomail-lib%%);
    vertical-align: top;
}


/*** FLAIRS ***/


.linkflair-Discussion .linkflairlabel {
    background-color: #0000ff;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #0000ff;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}


.linkflair-Meme .linkflairlabel {
    background-color: #ff00ff;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #ff00ff;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Announcement .linkflairlabel {
    background-color: #ffa500;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #ffa500;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Other .linkflairlabel {
    background-color: #008000;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #008000;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Election .linkflairlabel {
    background-color: #00548f;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #00548f;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Trade .linkflairlabel {
    background-color: #800000;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #800000;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-DOMA .linkflairlabel {
    background-color: #003300;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #003300;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Autism .linkflairlabel {
    background-color: #800080;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #800080;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Session .linkflairlabel {
    background-color: #7f6b00;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #7f6b00;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflair-Important .linkflairlabel {
    background-color: #ff0000;
    font-size: 11px;
    font-weight: bold;
    color: #fff;
    border-color: #ff0000;
    border-width: 1px;
    border-radius: 3px;
    text-indent: 0px !important;
    float: right;
}

.linkflairlabel {
    clear: both !important;
} 

.flairoptionpane {
    width: 290px !important;
}



/*** SELECTION ***/


::selection {
    background-color: #ffd046;
    color: white;
    font-weight: bold;
}


/*** HEADER ***/

#sr-header-area .sr-list .separator {
    visibility: hidden;
}

#sr-header-area {
    border-bottom: none !important;
    background: none !important;
}

#sr-more-link {
    background-color: #00548f;
    padding: 8px 15px 8px 15px;
    color: white;
    text-decoration: none !important;
}

#sr-more-link:hover {
    color: #ffd046;
}

#sr-header-area .srdrop.dropdown {
    width: 35px;
    height: 35px;
    position: absolute;
    background: url(%%icons2%%) no-repeat 11px 12px transparent;
    line-height: 23px;
    text-indent: -999em;
    opacity: 0.8;
    cursor: pointer;
}

#sr-header-area .srdrop.dropdown:hover {
    opacity: 0;
}

#sr-header-area .drop-choices.srdrop {
    margin-left: 0;  
}

.drop-choices {
    padding: 6px;
    font-size: 12px;
    border: 1px solid #e2e2e2;
    z-index: 1000;
}

.drop-choices a.choice:hover {
    background: #ffd046;
    color: #fff;
}

#sr-header-area .sr-list {
    margin-top: 8px;
    margin-left: 40px;
}

.sr-bar a {
    color: #000;
    text-decoration: none !important;
}

.sr-bar a:hover {
    color: #ffffff;
}

#header {
    background-color: #00548f;
    border: 0px;
    border-bottom: none;
    height: 200px;
    position: relative;
}

#header-bottom-left .tabmenu {
    text-align: center !important;
    top: 168px !important;
    text-transform: uppercase;
}

#header-bottom-left .tabmenu a {
    font-size: x-small;
}

#header-img {
    display: inline-block;
    vertical-align: middle;
    position: absolute;
    top: 150px;
    left: 8px;
    opacity: 1;
    transition: 200ms;
    z-index: 100
}

#header-img:hover, .pagename a:hover {
    opacity: 1;
}

.pagename a {
    background:url(%%omega%%) no-repeat;
    /*width: 400px;*/
    width: 400px;
    height: 133px;
    display: block;
    transition: 200ms;
    text-indent: 100%;
    overflow: hidden;
    margin: 24px auto 0px auto !important;
    opacity: 1;
}

#header:after {
    background: url(%%stripes%%) no-repeat;
    content: "";
    position: absolute;
    width: 46px; /*adjust the rest as necessary*/
    height: 182px;
    left: 0px;
    top: 18px
}

span.hover.pagename.redditname {
    display: block;
    margin-top: -14px;
    margin-left: -5px;
    font-size: 0px;
}

#header-bottom-right {
    background: none;
    z-index: 11;
    height: 20px;
    line-height: 20px;  
    margin-right: 8px;
    border-radius: 0px;
    background: #2e2e2e;
    padding: 5px 10px;
    border: 1px solid #131313;
    border-bottom: 0px;
    font-size: 8px;
    width: 25%;
    text-align: center;
}

#header-bottom-right a {
    color: #ccc;
    text-transform: uppercase;
    text-decoration: none;
}

#header-bottom-right a:hover {
    color: #fcfcfc;
}

#header-bottom-right .user {
    color: #2e2e2e;

}

#header-bottom-right .user .userkarma {
    color: #e2e2e2;
    border: none;
}

.separator {
    visibility: hidden;
}

#header .tabmenu {
    position: absolute;
    top: 100px;
    bottom: 0px;
    left: 0px;
    right: 0px;
    z-index: 10;
    margin: 0px;
    background: transparent;
    height: 30px;
    line-height: 30px;
}

#header .tabmenu>li>a {
    background: none;
    font-weight: normal;
    color: #ccc;
    padding: 8px 13px;
    border: none;
}

#header .tabmenu>li>a:hover {
    color: #ffffff;
}

.tabmenu li {
    display: inline;
    margin-top: 100px;
}

.tabmenu li.selected a {
    color: #ffd046 !important;
    font-weight: bold !important;
}


/*** LINKS ***/


.pretty-button {
    border-radius: 2px;
    padding: 2px 6px;
}

.pretty-button:hover {
    background: #2e2e2e!important;
    border: 1px solid black !important;
    color: white;
}

.pretty-button.neutral {
    background-image: none;
    background: #ddd;
    border: 1px solid #CECECE;
}

.pretty-button.neutral.pressed {
    background-image: none;
    background: #ccc;
    border: 1px solid #CECECE;
}

.pretty-button.positive {
    background-image: none;
    background: #abffae;
    border: 1px solid #91da93;
}

.pretty-button.negative {
    background-image: none;
    background: #ffabab;
    border: 1px solid #d68d8d;
}

.entry .buttons li.reported-stamp {
    border-radius: 2px;
    padding: 0 6px;
    background: #ffd046;
    border: 0px solid #008000!important;
}

.entry .buttons li a {
    font-weight: normal;
}

.entry .buttons a:hover {
    text-decoration: none;
    color: #ffd046;
}

.tagline, .link .flat-list {
    margin-left: 40px;
}

.tagline .submitter {
    color: #00548f;
}

.noncollapsed .tagline {
    margin-left: 0;
}

.tagline .submitter {
    color: #131313;
    font-weight: bold;
}

.tagline a {
    color: #131313;
    font-weight: bold;
}

.tagline a:hover {
    text-decoration: none;
    color: #ffd046;
}

.thing .title.loggedin.click:hover, .thing .title.click:hover, .thing .title.loggedin:hover, .thing .title:hover {
    text-decoration: none !important;
}

.thing .title {
    margin-left: 40px;
    text-indent: -40px;
    margin-bottom: 2px;
    color: #00548f;
}

.domain {
    color: #ccc;
    text-decoration: none;
}

.domain a {
    padding-bottom: 3px;
    padding-left: 43px;
    padding-right: 3px;
    text-decoration: none;
    color: #ccc;
}

.domain a:hover {
    text-decoration: none;
    color: #aaa;
}

.link .title {
    color: #000000 !important;
}

.link .title:hover {
    color: #ffd046 !important;
}

.thing .title.loggedin:visited, .thing .title:visited {
    color: #8A8888;
}

.link {
    padding: 15px;
    border: 0px solid #008000;
    background: #fff;
    border-radius: 0px;
    margin-right: 308px;
    position: relative;
}

.link:hover {
    border: 0px solid #ffd046;
}

.link .rank {
    display: none;
}

.trending-subreddits .trending-subreddits-content, .organic-listing {
    display: none;
}

.menuarea {
    border-bottom: none;
}

.menuarea .dropdown.lightdrop .selected {
    text-decoration: none;
    color: #2e2e2e;
}

.content {
    margin: 8px 8px 0px 8px;
}

.content .spacer {
    margin-bottom: 4px;
}

.link.last-clicked {
    overflow: visible !important;
    border: 1px solid #00548f !important;
}

.link.last-clicked:hover {
    overflow: visible !important;
    border: 0px solid #ffd046 !important;
}

.link.stickied {
    border: 3px solid #005931 !important;
}

.expando-button {
    height: 20px;
    width: 20px;
    border-radius: 2px;
    cursor: pointer;
    position: absolute;
    top: 34px;
}

.expando-button.selftext.collapsed {
    background-image: url(%%icons2%%);
    background-position: 0px -38px;
}	
			
.expando-button.selftext.collapsed:hover {
    background-image: url(%%icons2%%);
    background-position: -20px -38px;
}

.expando-button.selftext.expanded {
    background-image: url(%%icons2%%);
    background-position: 0px -58px;
}				
	
.expando-button.selftext.expanded:hover {
    background-image: url(%%icons2%%);
    background-position: -20px -58px;
}

.link .usertext .md {
    border-radius: 2px;
    background: white;
    border: 1px solid #cacaca;
    padding: 0px 8px !important;
    margin-left: 40px;
}

.expando .md {

}

.arrow {
    width: 15px;
    height: 14px;
    background-image: url(%%icons2%%)!important;
    background-position: center center;
    border: none !important;
}

.arrow.up {
    background-position: 0px -24px !important;
}

.arrow.down {
    background-position: -30px -24px !important;
}
 .arrow.upmod { 
    background-position: -15px -24px;
 }
 .arrow.downmod { 
    background-position: -45px -24px;
 }

.link .score {
    margin-bottom: 0px;
    color: #999;
}

.link .midcol {
    margin-top: 6px;
}

body:not(.search-page) #search {
    background: #2e2e2e;
    border: 0px solid #008000;
}

body:not(.search-page) #search:hover {
    border: 0px solid #ffd046;
}

#searchexpando {
    border-radius: 0px;
    margin: 0px 8px 8px 8px;
}

#moresearchinfo {
    border: 0 solid #ddd;
}

.infobar {
    background: #f1f1f1;
    border: 1px solid #d5d5d5;
}

.linkinfo {
    border-radius: 0px;
    background: #fff;
    border: 0px solid #008000;
    padding: 10px;
}

.linkinfo:hover {
    border: 0px solid #ffd046;
}

.linkinfo .shortlink {
    margin-top: -8px;
    color: white;
}

.linkinfo .shortlink input {
    border: 1px solid #e2e2e2;
    padding: 6px 12px;
    width: 252px;
    text-align: center;
    margin-bottom: -5px;
}

.linkinfo .date {
    font-variant: small-caps;
    color: #2e2e2e;
    text-align: center;
}

.linkinfo .score {
    font-variant: small-caps;
    text-align: center;
}

.nav-buttons {
    margin: 16px 0;
    font-size: 0px;
}

.nextprev a, .next-suggestions a {
    padding: 8px 16px;
    background: #fff;
    border: 1px solid #e2e2e2;
    border-radius: 0;
    text-transform: uppercase;
    font-size: 12px;
}

.nextprev a:hover, .next-suggestions a:hover {
    background: #fff;
    border: 1px solid #cacaca;
    color: #00548f;
}


/*** COMMENTS ***/


.commentarea {
    margin-top: 5px;
    margin-right: 308px;
    margin-bottom: 30px;
    padding: 10px 10px 10px 10px;
    background-color: #fff;
    border: 1px solid #e2e2e2;
    color: #000000;
}

.commentarea:hover {
    border: 1px solid #cacaca;
}

.panestack-title {
    border-bottom: 1px solid #ececec;
    width: 507px;
    padding-bottom: 5px;
    margin-bottom: 5px;
}

/* GREENTEXT and SPOILER */

a[href$="/greentext"] {  
color: #789922; 
}
  
a[href$="/spoiler"] {  
background: #000 !important;  
color: #000 !important  
}  

a[href$="/spoiler"]:hover {  
color: #FFF !important  
}  

/*** SIDEBAR ***/


.side {
    background-color: transparent;
    margin: 8px 8px 10px 8px;
    border-radius: 0px;
    padding: 0;
    width: 300px;
}

.side .spacer {
    margin: 0 0 8px 0;
}

.side .md blockquote {
    border-left: 0;
    border: none;
    padding: 0px;
    background: #ffffff;
    color: #3d3d3d;
    line-height: 16px;
}

.side .md p {
    padding: 0px 6px;
}

.side .md blockquote h3 {
    padding: 10px;
    color: #2e2e2e;
    text-align: center;
    font-weight: normal;
    font-size: medium;
    font-family: sans-serif;
    border-top: 1px solid #e2e2e2;
    border-bottom: 1px solid #e2e2e2;
}
.side .md blockquote h3 ~ * {
    padding: 0 6px;
}
.side .md blockquote a {
    color: #00548f;
}

.side .md blockquote a:hover {
    color: #ffd046;
}

.md blockquote, .help blockquote {
    margin-right: 0px;
    margin-left: 0px;
}

.sidecontentbox .content {
    border: 0px solid #008000;
    background: #fff;
    padding: 10px 15px;
    margin-top: 4px;
}

.sidecontentbox .content:hover {
    border: 0px solid #ffd046;
}

#search input[type=text] {
    border: 1px solid #E2E2E2;
    font-size: 15px;
    width: 260px;
    padding: 10px;
    margin: 8px 0 8px 8px;
}

#search input[type=text]:focus {
    outline: none;
    border: 0px solid #ffd046 !important;
}

.login-form-side {
    border: 0px solid #008000;
}

.login-form-side input[type=text], .login-form-side input[type=password] {
    border: 0px solid #008000;
    width: 119px;
    height: 17px;
    margin: 5px 0px 0px 5px;
    top: 5px;
    padding: 5px 10px;
}

.sponsorshipbox iframe {
    margin-bottom: -2px;
}

div.sidebox.submit {
    padding: 0px;
    background: #fff;
}

div.sidebox.submit:hover {
    border: 0px solid #ffd046;
}

.morelink {
    position: relative;
    z-index: 97;
    height: 35px;
    padding: 4px 0px;
    background-color: #2e2e2e;
    background-image: none !important;
    border: #008000;
}

.morelink:hover {
    background-color: #ffd046 !important;
    background-image: none !important;
}

.morelink a {
    color: #fff;
    letter-spacing: 0px;
    font-weight: bold;
    font-size: 15px;
    font-family: arial,sans-serif;
    cursor: pointer;
    line-height: 37px;
}

.morelink .nub {
    display: none;
}

.submit.submit-text .morelink:hover:before, .sidecontentbox>a.helplink:hover:before, .comment .report-button .option.main a:hover:before, ul.flat-list.buttons li a[onclick="return reply(this)"]:hover:before {
    display: block;
    position: absolute;
    background: #ffd046;
    border: 1px solid #d23f3f;
    border-radius: 0;
    font-family: Arial,sans-serif;
    font-size: 12px;
    font-weight: normal;
    line-height: normal;
    text-align: center;
    text-transform: none;
    color: #FFF;
    z-index: 1000;
    opacity: 1;
}

.titlebox {
    background: white;
    border: 0px solid #008000;
    padding: 15px;
}

.titlebox:hover {
    border: 0px solid #ffd046;
}

.titlebox h1 a {
    display: block;
    text-transform: small-caps;
    letter-spacing: 1px;
    padding-top: 8px;
    margin-bottom: 10px;
    text-align: center;
}

.titlebox h1 a:hover {
    text-decoration: none;
    color: #ffd046;
}

.users-online:before {
    background: none;
}

div.titlebox span.word {
    display: none;
}

span.subscribers {
    margin-left: 4px;
}

div.titlebox span.number:after {
    content: " Librans";
}

.titlebox .users-online .number:before {
    content: "(";
}

.titlebox .users-online .number:after {
    content: " here)";
}

.titlebox .users-online {
    display: inline;
}

.hover-bubble.multi-selector {
    display: none !important;
}

.help blockquote {
    margin: 0px;
    border: 1px solid #ccc;
    padding: 4px 12px;
    background: white;
}

.md hr {
    margin: 2px;
    height: 1px;
    border: none;
    background: transparent;
}

.titlebox form.toggle, .leavemoderator {
    padding: 5px;
}

.titlebox .bottom {
    border-top: none;
    padding-left: 25px;
}

.titlebox .age {
    float: left;
}

#ad-frame, #ad_main {
    background: #fff;
    border: 0px solid #008000;
}

#ad-frame:hover, #ad_main:hover {
    border: 0px solid #ffd046;
}

/*** FOOTER ***/

.footer-parent {
    padding-bottom: 40px;
    background-color: #00548f;
}

.footer {
    border: none;
}

.footer .title {
    text-transform: uppercase;
    font-size: 14px;
    border-bottom: 1px solid #3D3D3D;
    text-align: center;
    padding-bottom: 10px;
    margin-bottom: 10px;
}

.footer a {
    color: #888;
    text-decoration: none !important;
}

.footer a:hover {
    color: #e2e2e2;
}

.buygold {
    color: #D5AC3D !important;
    font-weight: normal;
}

.footer .col {
    border-left: none;
}

.debuginfo {
    margin-top: -30px;
}

/*** SUBMISSION PAGE ***/


.content h1 {
    display: none
}

.formtabs-content {
    border-top: none;
    padding-top: 0px;
    margin-left: -8px;
    margin-top: 10px;
}

.roundfield {
    border-radius: 0px;
    background: #fff;
    border: 1px solid #e2e2e2;
    padding: 15px;
    font-size: medium;
    color: #2e2e2e;
}

.roundfield textarea, .roundfield input[type=text], .roundfield input[type=url], .roundfield input[type=password], .roundfield input[type=number], .usertext-edit textarea {
    border: 1px solid #e2e2e2;
    outline: none;
}

textarea:focus, input#sr-autocomplete:focus, .usertext-edit textarea:focus {
    border: 1px solid #cacaca;
}

.roundfield span.title {
    text-transform: capitalize;
}

.roundfield .usertext-edit {
    padding-left: 0px;
}

div#title-field {
    padding-bottom: 12px;
}

.roundfield span.gray {
    visibility: hidden;
}

.roundfield:nth-of-type(5) {
    margin: 3px 0;
}

.content.submit .info-notice {
    background: #f0f0f0;
    border: 1px solid #00800;
    border-radius: 0px;
    margin-bottom: 5px;
    margin-left: -8px;
    width: 512px;
}

.content.submit .spacer button.btn {
    width: 532px;
    height: 40px;
    margin-left: -8px;
    margin-top: 3px;
    background: #2e2e2e;
    border: none;
    color: white;
    text-transform: uppercase;
    font-weight: bold;
}

.content.submit .spacer button.btn:hover {
    background: #ffd046;
}

.spacer button.btn:hover {
    opacity: .9;
}

#suggested-reddits {
    display: none;
}

ul.tabmenu.formtab {
    display: none;
}

form .spacer+.spacer {
    margin: 8px 0;
}


/*** ADDS SUBMISSION PAGE TEXT ***/


#link-desc, #text-desc {
    font-size: 0px;
    display: none !important;
} /*Hides default text*/

#link-desc:after, #text-desc:after {
    display: none;
/* display: block; */
    font-weight: bold; 
    color: black; 
    content: "Please add a [TAG] to your post, follow our submission guidelines below!";
    font-size: 16px;
/* padding: 5px 10px; */
} 

#sr-header-area * {font-family:verdana,arial,helvetica,sans-serif!important;}
#sr-header-area {
    background:#f0f0f0!important;
    text-transform:uppercase!important;
    border-bottom:1px solid #808080!important;
    font-size:90%!important;
    height:18px!important;
    line-height:18px!important;
    padding:0!important;
}



.res-nightmode.listing-page > .content,.res-nightmode.comments-page .link,.res-nightmode .res .commentarea>.usertext,.res-nightmode .account-activity-box,.res-nightmode .side .linkinfo,.res-nightmode .side .titlebox,.res-nightmode .sidecontentbox,.res-nightmode body .content,.res-nightmode .icon-menu a,.res-nightmode .side .titlebox form.flairtoggle,.res-nightmode .side .titlebox h1.redditname:before{background:#444;border-color:#444}.res-nightmode body.listing-page>.content,.res-nightmode body.other-discussions-page>.content,.res-nightmode .comments-page .link,.res-nightmode .commentarea>.sitetable>.comment,.res-nightmode #images,.res-nightmode .combined-search-page>.content,.res-nightmode .sponsorshipbox,.res-nightmode .commentarea>.usertext,.res-nightmode .stylesheet-customize-container .pretty-form,.res-nightmode .side .sidecontentbox,.res-nightmode .account-activity-box,.res-nightmode .side .titlebox,.res-nightmode #previoussearch #moresearchinfo,.res-nightmode #ad-frame,.res-nightmode #ad_main,.res-nightmode .wiki-page .wiki-page-content,.res-nightmode .linefield,.res-nightmode .submit-page .roundfield,.res-nightmode .login-form-side{background-color:#333}.res-nightmode .side .linkinfo .score,.res-nightmode .titlebox:before,.res-nightmode .titlebox .md *,.res-nightmode .content textarea:focus,.res-nightmode .side .titlebox h1.redditname a{color:#ccc}.res-nightmode .wiki-page .pageactions,.res-nightmode .wiki-page .wikititle{background-color:#333}.res-nightmode.res input[type=text]{background:#444;border-color:#444}.res-nightmode #sr-header-area[id]{background:#333;border-color:#333}.res-nightmode #header .tabmenu a{background:none}.res-nightmode .arrow.up{background-position:-0 -80px !important}.res-nightmode .arrow.upmod,.res-nightmode .arrow.up:hover{background-position:-32px -80px !important}.res-nightmode .arrow.down{background-position:-64px -80px !important}.res-nightmode .arrow.downmod,.res-nightmode .arrow.down:hover{background-position:-0 -100px !important}.res-nightmode .link .entry .tagline a{color:rgb(130, 130, 130)}.res-nightmode .c-btn-primary{border-bottom:2px solid #777777}.res-nightmode .morelink,.res-nightmode .morelink a,.res-nightmode .sidebox.create .morelink a,.res-nightmode .side .titlebox .md h3 a,.res-nightmode .drop-choices a.choice:hover,.res-nightmode .submit-page #newlink.submit.content ul.tabmenu.formtab,.res-nightmode .submit_text.enabled.roundfield,.res-nightmode body .btn,.res-nightmode body button,.res-nightmode .content .infobar,.res-nightmode .c-btn-primary{background-color:#666666;color:#fff}.res-nightmode .morelink:hover,.res-nightmode .morelink:hover a,.res-nightmode .side .titlebox .md h3 a:hover,.res-nightmode .btn:hover,.res-nightmode body button:hover,.res-nightmode .c-btn-primary:hover{background-color:#777777;color:#fff}.res-nightmode .morelink:active,.res-nightmode .side .titlebox .md h3 a:active,.res-nightmode .btn:active,.res-nightmode body button:active{background-color:#0066b2}.res-nightmode .commentarea>.usertext{background:#323232 !important;border-color:#666666 !important}.res-nightmode .link,.res-nightmode .sitetable{background-color:#333}.res-nightmode #search input[type=submit]{background-position:-64px -97px}.res-nightmode #search input[type=text]{background-color:#444}.res-nightmode #search #searchexpando{background-color:#555}.res-nightmode .side .titlebox .md h5{background-color:#555;color:#DEDEDE;border-bottom:1px solid #444}.res-nightmode .titlebox .fancy-toggle-button .active.add{background-color:#777777}.res-nightmode .titlebox .fancy-toggle-button .active.add:hover{background-color:#888888}.res-nightmode .titlebox .fancy-toggle-button .active.remove{background-color:#555555}.res-nightmode .titlebox .fancy-toggle-button .active.remove:hover{background-color:#666666}




/* by doingstuffcarl */
