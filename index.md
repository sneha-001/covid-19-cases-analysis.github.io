<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Final_Project_Amanda_Le_Sneha_Narayanan</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="A-Pandemic:-An-Analysis-of-COVID-19">A Pandemic: An Analysis of COVID-19<a class="anchor-link" href="#A-Pandemic:-An-Analysis-of-COVID-19">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Amanda-Le-and-Sneha-Narayanan">Amanda Le and Sneha Narayanan<a class="anchor-link" href="#Amanda-Le-and-Sneha-Narayanan">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Introduction">Introduction<a class="anchor-link" href="#Introduction">&#182;</a></h3><p>COVID-19 has been a prevalent part of the past several months of our lives and as vaccines have come in order to help the future of all invdividuals it is important to look back and analyze the rollercoaster of a ride its been especially when picking apart the cases, not only specifically in North America but throughout the world over the period of the pandemic so far. Furthermore, consideration of other factors that are influencing the difference in COVID-19 cases in different places are also investigated. Delving into the specifics of this data is crucial at a time where a vaccine is used to help prevent the spread of the virus as well as learning more about the virus itself and what can help stop it.</p>
<p>What is our end goal? We need to work together to make the number of cases go to 0 and the only way to make this pivotal change is to understand where a majority of the cases are coming from not only at the current moment but over time and how to prevent spikes in cases. The strict guidelines with social distancing rules must continue to stay strong. We predict that earlier start dates as well as longer lockdown durations allowed for lower amount of total cases. Not only that but we believe that locations with higher poverty rates or population densities are key factors in having a higher positivity rate. There are also many other factors that we consider that could be affecting the spread of the virus.</p>
<p>In our analysis, we will be visualizing the data of COVID-19 cases worldwide, then going specifically into North America where there are many cases. We will not only look at the total cases, but also discuss the amount of new cases over time. Here, we use different sklearn regression models in order to see which ML predicting method was the most accurate. After that, we analyze the different factors that could be potentially affecting the number of cases in an attempt to help reduce the number of cases in North America.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="o">!</span>pip install folium
<span class="o">!</span>pip install plotly
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">datetime</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">linear_model</span> <span class="k">as</span> <span class="n">lm</span> 
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">ensemble</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">svm</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">tree</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">neighbors</span>
<span class="kn">import</span> <span class="nn">folium</span>
<span class="kn">from</span> <span class="nn">folium</span> <span class="kn">import</span> <span class="n">plugins</span> <span class="k">as</span> <span class="n">plugins</span>
<span class="kn">import</span> <span class="nn">plotly.express</span> <span class="k">as</span> <span class="nn">px</span>
<span class="kn">import</span> <span class="nn">warnings</span> 
<span class="n">warnings</span><span class="o">.</span><span class="n">filterwarnings</span><span class="p">(</span><span class="s1">&#39;ignore&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Requirement already satisfied: folium in /opt/conda/lib/python3.8/site-packages (0.11.0)
Requirement already satisfied: jinja2&gt;=2.9 in /opt/conda/lib/python3.8/site-packages (from folium) (2.11.2)
Requirement already satisfied: branca&gt;=0.3.0 in /opt/conda/lib/python3.8/site-packages (from folium) (0.4.1)
Requirement already satisfied: numpy in /opt/conda/lib/python3.8/site-packages (from folium) (1.19.1)
Requirement already satisfied: requests in /opt/conda/lib/python3.8/site-packages (from folium) (2.24.0)
Requirement already satisfied: MarkupSafe&gt;=0.23 in /opt/conda/lib/python3.8/site-packages (from jinja2&gt;=2.9-&gt;folium) (1.1.1)
Requirement already satisfied: urllib3!=1.25.0,!=1.25.1,&lt;1.26,&gt;=1.21.1 in /opt/conda/lib/python3.8/site-packages (from requests-&gt;folium) (1.25.10)
Requirement already satisfied: idna&lt;3,&gt;=2.5 in /opt/conda/lib/python3.8/site-packages (from requests-&gt;folium) (2.10)
Requirement already satisfied: chardet&lt;4,&gt;=3.0.2 in /opt/conda/lib/python3.8/site-packages (from requests-&gt;folium) (3.0.4)
Requirement already satisfied: certifi&gt;=2017.4.17 in /opt/conda/lib/python3.8/site-packages (from requests-&gt;folium) (2020.6.20)
Requirement already satisfied: plotly in /opt/conda/lib/python3.8/site-packages (4.14.1)
Requirement already satisfied: six in /opt/conda/lib/python3.8/site-packages (from plotly) (1.15.0)
Requirement already satisfied: retrying&gt;=1.3.3 in /opt/conda/lib/python3.8/site-packages (from plotly) (1.3.3)
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Data-Scraping">Data Scraping<a class="anchor-link" href="#Data-Scraping">&#182;</a></h3><p>To analyze the data over time for North America, we will scrape the data and get it daily beginning April 12th. Since the data was for every state (including U.S. territories) we will get the data per day and then concatenate it for each month and save them into separate dataframes. We will use data sourced from github and received COVID-19 cases from a reputable source by the Center of Systems Science and Engineering at Johns Hopkins University: <a href="https://github.com/CSSEGISandData/COVID-19">https://github.com/CSSEGISandData/COVID-19</a> where even more data could be found. Not only that, but there were many sources that had used this data in order to provide a great interactive view of data throughout the world such as: <a href="https://ourworldindata.org/coronavirus">https://ourworldindata.org/coronavirus</a>. We will scrape the latest data that has been documented so far.</p>
<p>This is how we scrape the data for North America (using daily COVID data by state/territories and save them by month):</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[89]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of April (data only begins from April 12th onwards)</span>
<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">12</span><span class="p">,</span> <span class="mi">31</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;04&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_april</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_april</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[89]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-04-12 23:18:15</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>3667</td>
      <td>93</td>
      <td>NaN</td>
      <td>3470.0</td>
      <td>1.0</td>
      <td>75.988020</td>
      <td>21583.0</td>
      <td>437.0</td>
      <td>2.610160</td>
      <td>84000001</td>
      <td>USA</td>
      <td>460.300152</td>
      <td>12.264945</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-04-12 23:18:15</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>272</td>
      <td>8</td>
      <td>66.0</td>
      <td>264.0</td>
      <td>2.0</td>
      <td>45.504049</td>
      <td>8038.0</td>
      <td>31.0</td>
      <td>2.941176</td>
      <td>84000002</td>
      <td>USA</td>
      <td>1344.711576</td>
      <td>11.397059</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-04-12 23:18:15</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>3542</td>
      <td>115</td>
      <td>NaN</td>
      <td>3427.0</td>
      <td>4.0</td>
      <td>48.662422</td>
      <td>42109.0</td>
      <td>NaN</td>
      <td>3.246753</td>
      <td>84000004</td>
      <td>USA</td>
      <td>578.522286</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-04-12 23:18:15</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>1280</td>
      <td>27</td>
      <td>367.0</td>
      <td>1253.0</td>
      <td>5.0</td>
      <td>49.439423</td>
      <td>19722.0</td>
      <td>130.0</td>
      <td>2.109375</td>
      <td>84000005</td>
      <td>USA</td>
      <td>761.753354</td>
      <td>10.156250</td>
    </tr>
    <tr>
      <th>4</th>
      <td>California</td>
      <td>US</td>
      <td>2020-04-12 23:18:15</td>
      <td>36.1162</td>
      <td>-119.6816</td>
      <td>22795</td>
      <td>640</td>
      <td>NaN</td>
      <td>22155.0</td>
      <td>6.0</td>
      <td>58.137726</td>
      <td>190328.0</td>
      <td>5234.0</td>
      <td>2.812020</td>
      <td>84000006</td>
      <td>USA</td>
      <td>485.423868</td>
      <td>22.961176</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>15847</td>
      <td>552</td>
      <td>2104.0</td>
      <td>13191.0</td>
      <td>51.0</td>
      <td>200.411522</td>
      <td>91509.0</td>
      <td>3654.0</td>
      <td>3.483309</td>
      <td>84000051</td>
      <td>USA</td>
      <td>1157.282639</td>
      <td>23.057992</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>14327</td>
      <td>836</td>
      <td>0.0</td>
      <td>13513.0</td>
      <td>53.0</td>
      <td>189.776596</td>
      <td>187800.0</td>
      <td>NaN</td>
      <td>5.681580</td>
      <td>84000053</td>
      <td>USA</td>
      <td>2487.613921</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>1125</td>
      <td>41</td>
      <td>545.0</td>
      <td>539.0</td>
      <td>54.0</td>
      <td>85.034142</td>
      <td>44541.0</td>
      <td>NaN</td>
      <td>3.644444</td>
      <td>84000054</td>
      <td>USA</td>
      <td>3366.671756</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>6854</td>
      <td>316</td>
      <td>3352.0</td>
      <td>3186.0</td>
      <td>55.0</td>
      <td>132.455425</td>
      <td>76248.0</td>
      <td>1512.0</td>
      <td>4.610446</td>
      <td>84000055</td>
      <td>USA</td>
      <td>1473.513456</td>
      <td>22.060111</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>559</td>
      <td>7</td>
      <td>371.0</td>
      <td>181.0</td>
      <td>56.0</td>
      <td>112.420561</td>
      <td>9446.0</td>
      <td>56.0</td>
      <td>1.252236</td>
      <td>84000056</td>
      <td>USA</td>
      <td>1899.686268</td>
      <td>10.017889</td>
    </tr>
  </tbody>
</table>
<p>1120 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[90]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of May </span>
<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;05&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">32</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;05&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_may</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_may</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[90]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-05-02 02:32:31</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>7440</td>
      <td>289</td>
      <td>0.0</td>
      <td>7005.0</td>
      <td>1</td>
      <td>155.558973</td>
      <td>91933.0</td>
      <td>1008.0</td>
      <td>3.962161</td>
      <td>84000001</td>
      <td>USA</td>
      <td>1960.653006</td>
      <td>13.819578</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-05-02 02:32:31</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>364</td>
      <td>9</td>
      <td>254.0</td>
      <td>101.0</td>
      <td>2</td>
      <td>60.895125</td>
      <td>20325.0</td>
      <td>NaN</td>
      <td>2.472527</td>
      <td>84000002</td>
      <td>USA</td>
      <td>3400.256629</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-05-02 02:32:31</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>60</td>
      <td>0.000000</td>
      <td>57.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>102.442444</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-05-02 02:32:31</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>7969</td>
      <td>330</td>
      <td>1528.0</td>
      <td>6111.0</td>
      <td>4</td>
      <td>109.483581</td>
      <td>74879.0</td>
      <td>1203.0</td>
      <td>4.141047</td>
      <td>84000004</td>
      <td>USA</td>
      <td>1028.738993</td>
      <td>15.095997</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-05-02 02:32:31</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>3337</td>
      <td>64</td>
      <td>1973.0</td>
      <td>1300.0</td>
      <td>5</td>
      <td>128.890120</td>
      <td>49676.0</td>
      <td>414.0</td>
      <td>1.917890</td>
      <td>84000005</td>
      <td>USA</td>
      <td>1918.713092</td>
      <td>12.406353</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-06-01 02:32:54</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>44607</td>
      <td>1375</td>
      <td>5868.0</td>
      <td>37364.0</td>
      <td>51</td>
      <td>522.604425</td>
      <td>315391.0</td>
      <td>7326.0</td>
      <td>3.082476</td>
      <td>84000051</td>
      <td>USA</td>
      <td>3695.041860</td>
      <td>16.423431</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-06-01 02:32:54</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>21702</td>
      <td>1123</td>
      <td>NaN</td>
      <td>20584.0</td>
      <td>53</td>
      <td>284.994156</td>
      <td>354354.0</td>
      <td>3480.0</td>
      <td>5.151599</td>
      <td>84000053</td>
      <td>USA</td>
      <td>4653.433738</td>
      <td>16.035388</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-06-01 02:32:54</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>2010</td>
      <td>75</td>
      <td>1303.0</td>
      <td>632.0</td>
      <td>54</td>
      <td>112.155978</td>
      <td>97622.0</td>
      <td>NaN</td>
      <td>3.731343</td>
      <td>84000054</td>
      <td>USA</td>
      <td>5447.209409</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-06-01 02:32:54</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>18403</td>
      <td>592</td>
      <td>11646.0</td>
      <td>6165.0</td>
      <td>55</td>
      <td>316.070564</td>
      <td>268506.0</td>
      <td>2583.0</td>
      <td>3.216867</td>
      <td>84000055</td>
      <td>USA</td>
      <td>4611.576533</td>
      <td>14.035755</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-06-01 02:32:54</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>903</td>
      <td>16</td>
      <td>658.0</td>
      <td>229.0</td>
      <td>56</td>
      <td>156.023492</td>
      <td>24393.0</td>
      <td>85.0</td>
      <td>1.771872</td>
      <td>84000056</td>
      <td>USA</td>
      <td>4214.707676</td>
      <td>9.413068</td>
    </tr>
  </tbody>
</table>
<p>1798 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[91]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of June </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;06&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">31</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;06&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_june</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_june</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[91]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-06-02 02:33:16</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>18525</td>
      <td>646</td>
      <td>9355.0</td>
      <td>8629.0</td>
      <td>1</td>
      <td>379.957110</td>
      <td>223523.0</td>
      <td>1856.0</td>
      <td>3.467525</td>
      <td>84000001.0</td>
      <td>USA</td>
      <td>4558.730703</td>
      <td>9.962426</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-06-02 02:33:16</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>466</td>
      <td>10</td>
      <td>368.0</td>
      <td>88.0</td>
      <td>2</td>
      <td>63.700798</td>
      <td>54190.0</td>
      <td>NaN</td>
      <td>2.145923</td>
      <td>84000002.0</td>
      <td>USA</td>
      <td>7407.609921</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-06-02 02:33:16</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60</td>
      <td>0.000000</td>
      <td>174.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16.0</td>
      <td>ASM</td>
      <td>312.719038</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-06-02 02:33:16</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>20129</td>
      <td>918</td>
      <td>4869.0</td>
      <td>14342.0</td>
      <td>4</td>
      <td>276.545990</td>
      <td>228070.0</td>
      <td>3018.0</td>
      <td>4.560584</td>
      <td>84000004.0</td>
      <td>USA</td>
      <td>3133.381886</td>
      <td>14.993293</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-06-02 02:33:16</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>7443</td>
      <td>133</td>
      <td>5401.0</td>
      <td>1909.0</td>
      <td>5</td>
      <td>246.636296</td>
      <td>133236.0</td>
      <td>711.0</td>
      <td>1.786914</td>
      <td>84000005.0</td>
      <td>USA</td>
      <td>4414.998456</td>
      <td>9.552600</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-07-01 04:34:05</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>62787</td>
      <td>1763</td>
      <td>8080.0</td>
      <td>52944.0</td>
      <td>51</td>
      <td>735.596746</td>
      <td>645034.0</td>
      <td>8982.0</td>
      <td>2.807906</td>
      <td>84000051.0</td>
      <td>USA</td>
      <td>7557.056577</td>
      <td>14.305509</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-07-01 04:34:05</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>33439</td>
      <td>1303</td>
      <td>NaN</td>
      <td>31492.0</td>
      <td>53</td>
      <td>431.050049</td>
      <td>548220.0</td>
      <td>4323.0</td>
      <td>4.058006</td>
      <td>84000053.0</td>
      <td>USA</td>
      <td>7199.313241</td>
      <td>13.170241</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-07-01 04:34:05</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>2905</td>
      <td>93</td>
      <td>2272.0</td>
      <td>540.0</td>
      <td>54</td>
      <td>162.096078</td>
      <td>171764.0</td>
      <td>NaN</td>
      <td>3.201377</td>
      <td>84000054.0</td>
      <td>USA</td>
      <td>9584.258434</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-07-01 04:34:05</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>28659</td>
      <td>784</td>
      <td>22587.0</td>
      <td>5288.0</td>
      <td>55</td>
      <td>492.216829</td>
      <td>571201.0</td>
      <td>3446.0</td>
      <td>2.735615</td>
      <td>84000055.0</td>
      <td>USA</td>
      <td>9810.347356</td>
      <td>12.024146</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-07-01 04:34:05</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>1487</td>
      <td>20</td>
      <td>1097.0</td>
      <td>370.0</td>
      <td>56</td>
      <td>256.929050</td>
      <td>33672.0</td>
      <td>117.0</td>
      <td>1.344990</td>
      <td>84000056.0</td>
      <td>USA</td>
      <td>5817.965682</td>
      <td>7.868191</td>
    </tr>
  </tbody>
</table>
<p>1740 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[92]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of July </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;07&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">32</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;07&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_july</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_july</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[92]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-07-02 04:33:59</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>39647</td>
      <td>972</td>
      <td>18866.0</td>
      <td>19124.0</td>
      <td>1</td>
      <td>794.626350</td>
      <td>413953.0</td>
      <td>2803.0</td>
      <td>2.494738</td>
      <td>84000001</td>
      <td>USA</td>
      <td>8442.532762</td>
      <td>7.194189</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-07-02 04:33:59</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>975</td>
      <td>14</td>
      <td>528.0</td>
      <td>433.0</td>
      <td>2</td>
      <td>133.279566</td>
      <td>114400.0</td>
      <td>NaN</td>
      <td>1.435897</td>
      <td>84000002</td>
      <td>USA</td>
      <td>15638.135726</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-07-02 04:33:59</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60</td>
      <td>0.000000</td>
      <td>696.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>1250.876152</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-07-02 04:33:59</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>84105</td>
      <td>1725</td>
      <td>9715.0</td>
      <td>72665.0</td>
      <td>4</td>
      <td>1155.492101</td>
      <td>549596.0</td>
      <td>4837.0</td>
      <td>2.051008</td>
      <td>84000004</td>
      <td>USA</td>
      <td>7550.726316</td>
      <td>5.751144</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-07-02 04:33:59</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>21197</td>
      <td>277</td>
      <td>15163.0</td>
      <td>5757.0</td>
      <td>5</td>
      <td>702.398168</td>
      <td>314858.0</td>
      <td>1448.0</td>
      <td>1.306789</td>
      <td>84000005</td>
      <td>USA</td>
      <td>10433.348223</td>
      <td>6.831155</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-08-01 04:36:46</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>89888</td>
      <td>2174</td>
      <td>11937.0</td>
      <td>75777.0</td>
      <td>51</td>
      <td>1053.105265</td>
      <td>1110747.0</td>
      <td>13271.0</td>
      <td>2.418565</td>
      <td>84000051</td>
      <td>USA</td>
      <td>13013.233290</td>
      <td>14.763928</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-08-01 04:36:46</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>57586</td>
      <td>1603</td>
      <td>NaN</td>
      <td>54239.0</td>
      <td>53</td>
      <td>732.813974</td>
      <td>973654.0</td>
      <td>5568.0</td>
      <td>2.802717</td>
      <td>84000053</td>
      <td>USA</td>
      <td>12786.180975</td>
      <td>9.977958</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-08-01 04:36:46</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>6579</td>
      <td>116</td>
      <td>4815.0</td>
      <td>1648.0</td>
      <td>54</td>
      <td>367.101583</td>
      <td>283988.0</td>
      <td>NaN</td>
      <td>1.763186</td>
      <td>84000054</td>
      <td>USA</td>
      <td>15846.244756</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-08-01 04:36:46</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>52940</td>
      <td>934</td>
      <td>42317.0</td>
      <td>9689.0</td>
      <td>55</td>
      <td>909.241736</td>
      <td>939083.0</td>
      <td>4637.0</td>
      <td>1.764261</td>
      <td>84000055</td>
      <td>USA</td>
      <td>16128.701502</td>
      <td>8.758972</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-08-01 04:36:46</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>2726</td>
      <td>26</td>
      <td>2123.0</td>
      <td>577.0</td>
      <td>56</td>
      <td>471.007794</td>
      <td>53299.0</td>
      <td>166.0</td>
      <td>0.953778</td>
      <td>84000056</td>
      <td>USA</td>
      <td>9209.187244</td>
      <td>6.089508</td>
    </tr>
  </tbody>
</table>
<p>1798 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[93]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of August </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;08&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">32</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;08&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_aug</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_aug</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[93]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-08-02 04:35:05</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>90299</td>
      <td>1603</td>
      <td>35401.0</td>
      <td>52345.0</td>
      <td>1.0</td>
      <td>1822.264508</td>
      <td>697371.0</td>
      <td>10521.0</td>
      <td>1.794088</td>
      <td>84000001</td>
      <td>USA</td>
      <td>14222.816394</td>
      <td>11.775174</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-08-02 04:35:05</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>3136</td>
      <td>24</td>
      <td>930.0</td>
      <td>2182.0</td>
      <td>2.0</td>
      <td>428.681763</td>
      <td>238633.0</td>
      <td>NaN</td>
      <td>0.765306</td>
      <td>84000002</td>
      <td>USA</td>
      <td>32620.412962</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-08-02 04:35:05</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>1267.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>2277.097824</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-08-02 04:35:05</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>177002</td>
      <td>3747</td>
      <td>23064.0</td>
      <td>150191.0</td>
      <td>4.0</td>
      <td>2431.774721</td>
      <td>948650.0</td>
      <td>11346.0</td>
      <td>2.116925</td>
      <td>84000004</td>
      <td>USA</td>
      <td>13033.203516</td>
      <td>6.410097</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-08-02 04:35:05</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>43173</td>
      <td>458</td>
      <td>36034.0</td>
      <td>6681.0</td>
      <td>5.0</td>
      <td>1430.609808</td>
      <td>514581.0</td>
      <td>2852.0</td>
      <td>1.060848</td>
      <td>84000005</td>
      <td>USA</td>
      <td>17051.505002</td>
      <td>6.605981</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-09-01 04:30:22</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>120594</td>
      <td>2580</td>
      <td>15085.0</td>
      <td>102910.0</td>
      <td>51.0</td>
      <td>1412.626461</td>
      <td>1586551.0</td>
      <td>NaN</td>
      <td>2.139747</td>
      <td>84000051</td>
      <td>USA</td>
      <td>18587.633628</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-09-01 04:30:22</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>75502</td>
      <td>1912</td>
      <td>NaN</td>
      <td>72720.0</td>
      <td>53.0</td>
      <td>980.118828</td>
      <td>1461354.0</td>
      <td>NaN</td>
      <td>2.565820</td>
      <td>84000053</td>
      <td>USA</td>
      <td>19190.735838</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-09-01 04:30:22</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>10249</td>
      <td>215</td>
      <td>8017.0</td>
      <td>2017.0</td>
      <td>54.0</td>
      <td>571.883891</td>
      <td>436047.0</td>
      <td>NaN</td>
      <td>2.097766</td>
      <td>84000054</td>
      <td>USA</td>
      <td>24330.984010</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-09-01 04:30:22</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>75603</td>
      <td>1122</td>
      <td>67234.0</td>
      <td>7247.0</td>
      <td>55.0</td>
      <td>1298.477578</td>
      <td>1253422.0</td>
      <td>NaN</td>
      <td>1.484068</td>
      <td>84000055</td>
      <td>USA</td>
      <td>21527.457417</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-09-01 04:30:22</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>3850</td>
      <td>37</td>
      <td>3181.0</td>
      <td>632.0</td>
      <td>56.0</td>
      <td>665.216437</td>
      <td>76273.0</td>
      <td>NaN</td>
      <td>0.961039</td>
      <td>84000056</td>
      <td>USA</td>
      <td>13178.715147</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>1798 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[94]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of September </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;09&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">31</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;09&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_sept</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_sept</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[94]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-09-02 04:30:23</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>127234</td>
      <td>2200</td>
      <td>48028.0</td>
      <td>77388.0</td>
      <td>1.0</td>
      <td>2602.716398</td>
      <td>958920.0</td>
      <td>NaN</td>
      <td>1.723922</td>
      <td>84000001</td>
      <td>USA</td>
      <td>19557.083814</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-09-02 04:30:23</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>5297</td>
      <td>39</td>
      <td>2246.0</td>
      <td>3012.0</td>
      <td>2.0</td>
      <td>724.083959</td>
      <td>374255.0</td>
      <td>NaN</td>
      <td>0.736266</td>
      <td>84000002</td>
      <td>USA</td>
      <td>51159.532223</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-09-02 04:30:23</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>1514.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>2721.015079</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-09-02 04:30:23</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>202342</td>
      <td>5044</td>
      <td>30841.0</td>
      <td>166457.0</td>
      <td>4.0</td>
      <td>2779.912998</td>
      <td>1208990.0</td>
      <td>NaN</td>
      <td>2.492809</td>
      <td>84000004</td>
      <td>USA</td>
      <td>16609.932767</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-09-02 04:30:23</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>61497</td>
      <td>814</td>
      <td>55647.0</td>
      <td>5036.0</td>
      <td>5.0</td>
      <td>2037.806299</td>
      <td>731025.0</td>
      <td>NaN</td>
      <td>1.323642</td>
      <td>84000005</td>
      <td>USA</td>
      <td>24223.740177</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-10-01 04:30:28</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>148271</td>
      <td>3208</td>
      <td>17633.0</td>
      <td>127254.0</td>
      <td>51.0</td>
      <td>1735.008732</td>
      <td>2049988.0</td>
      <td>NaN</td>
      <td>2.164195</td>
      <td>84000051</td>
      <td>USA</td>
      <td>24017.145296</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-10-01 04:30:28</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>89463</td>
      <td>2100</td>
      <td>NaN</td>
      <td>85396.0</td>
      <td>53.0</td>
      <td>1149.352985</td>
      <td>1854399.0</td>
      <td>NaN</td>
      <td>2.429104</td>
      <td>84000053</td>
      <td>USA</td>
      <td>24352.266013</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-10-01 04:30:28</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>15850</td>
      <td>355</td>
      <td>11507.0</td>
      <td>3988.0</td>
      <td>54.0</td>
      <td>884.414058</td>
      <td>561568.0</td>
      <td>NaN</td>
      <td>2.239748</td>
      <td>84000054</td>
      <td>USA</td>
      <td>31334.929557</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-10-01 04:30:28</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>122274</td>
      <td>1327</td>
      <td>99925.0</td>
      <td>21022.0</td>
      <td>55.0</td>
      <td>2100.049567</td>
      <td>1552370.0</td>
      <td>NaN</td>
      <td>1.085268</td>
      <td>84000055</td>
      <td>USA</td>
      <td>26661.873711</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-10-01 04:30:28</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>5948</td>
      <td>50</td>
      <td>4791.0</td>
      <td>1107.0</td>
      <td>56.0</td>
      <td>1027.716200</td>
      <td>101160.0</td>
      <td>NaN</td>
      <td>0.840619</td>
      <td>84000056</td>
      <td>USA</td>
      <td>17478.777868</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>1740 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[95]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of October </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;10&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">32</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;10&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_oct</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_oct</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[95]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-10-02 04:30:36</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>155727</td>
      <td>2548</td>
      <td>67948.0</td>
      <td>85248.0</td>
      <td>1.0</td>
      <td>3176.384330</td>
      <td>1138732.0</td>
      <td>NaN</td>
      <td>1.636018</td>
      <td>84000001</td>
      <td>USA</td>
      <td>23224.332755</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-10-02 04:30:36</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>7948</td>
      <td>57</td>
      <td>4838.0</td>
      <td>3053.0</td>
      <td>2.0</td>
      <td>1086.467681</td>
      <td>462323.0</td>
      <td>NaN</td>
      <td>0.717162</td>
      <td>84000002</td>
      <td>USA</td>
      <td>63198.162792</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-10-02 04:30:36</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>1571.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>2823.457522</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-10-02 04:30:36</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>219212</td>
      <td>5674</td>
      <td>35411.0</td>
      <td>178127.0</td>
      <td>4.0</td>
      <td>3011.684614</td>
      <td>1471368.0</td>
      <td>NaN</td>
      <td>2.588362</td>
      <td>84000004</td>
      <td>USA</td>
      <td>20214.661458</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-10-02 04:30:36</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>84821</td>
      <td>1384</td>
      <td>76186.0</td>
      <td>7251.0</td>
      <td>5.0</td>
      <td>2810.686181</td>
      <td>1042616.0</td>
      <td>NaN</td>
      <td>1.631671</td>
      <td>84000005</td>
      <td>USA</td>
      <td>34548.830872</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-11-01 04:39:05</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>181190</td>
      <td>3654</td>
      <td>20008.0</td>
      <td>157528.0</td>
      <td>51.0</td>
      <td>2122.776600</td>
      <td>2626052.0</td>
      <td>NaN</td>
      <td>2.016668</td>
      <td>84000051</td>
      <td>USA</td>
      <td>30766.166650</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-11-01 04:39:05</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>110808</td>
      <td>2345</td>
      <td>NaN</td>
      <td>105135.0</td>
      <td>53.0</td>
      <td>1411.720427</td>
      <td>2426385.0</td>
      <td>NaN</td>
      <td>2.200910</td>
      <td>84000053</td>
      <td>USA</td>
      <td>31863.678190</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-11-01 04:39:05</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>24460</td>
      <td>459</td>
      <td>18827.0</td>
      <td>5174.0</td>
      <td>54.0</td>
      <td>1364.843397</td>
      <td>778494.0</td>
      <td>NaN</td>
      <td>1.876533</td>
      <td>84000054</td>
      <td>USA</td>
      <td>43439.182165</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-11-01 04:39:05</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>237869</td>
      <td>2031</td>
      <td>175096.0</td>
      <td>48242.0</td>
      <td>55.0</td>
      <td>3870.700810</td>
      <td>3289120.0</td>
      <td>NaN</td>
      <td>0.901189</td>
      <td>84000055</td>
      <td>USA</td>
      <td>56490.464297</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-11-01 04:39:05</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>13298</td>
      <td>87</td>
      <td>8541.0</td>
      <td>4670.0</td>
      <td>56.0</td>
      <td>2297.674853</td>
      <td>130560.0</td>
      <td>NaN</td>
      <td>0.654234</td>
      <td>84000056</td>
      <td>USA</td>
      <td>22558.612479</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>1798 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[96]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of November </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;11&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
              
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">31</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;11&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_nov</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_nov</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[96]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
      <th>Total_Test_Results</th>
      <th>Case_Fatality_Ratio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-11-02 05:30:37</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>194458</td>
      <td>2973</td>
      <td>81005.0</td>
      <td>110007.0</td>
      <td>1.0</td>
      <td>3956.305952</td>
      <td>1352580.0</td>
      <td>NaN</td>
      <td>1.532593</td>
      <td>84000001.0</td>
      <td>USA</td>
      <td>27585.742737</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-11-02 05:30:37</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>16705</td>
      <td>83</td>
      <td>7104.0</td>
      <td>9518.0</td>
      <td>2.0</td>
      <td>2283.523228</td>
      <td>604207.0</td>
      <td>NaN</td>
      <td>0.496857</td>
      <td>84000002.0</td>
      <td>USA</td>
      <td>82593.278609</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-11-02 05:30:37</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>1616.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16.0</td>
      <td>ASM</td>
      <td>2904.333136</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-11-02 05:30:37</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>247473</td>
      <td>5979</td>
      <td>41398.0</td>
      <td>200096.0</td>
      <td>4.0</td>
      <td>3399.953591</td>
      <td>1785767.0</td>
      <td>NaN</td>
      <td>2.416021</td>
      <td>84000004.0</td>
      <td>USA</td>
      <td>24534.090280</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-11-02 05:30:37</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>113057</td>
      <td>1958</td>
      <td>100067.0</td>
      <td>11032.0</td>
      <td>5.0</td>
      <td>3746.333427</td>
      <td>1346972.0</td>
      <td>NaN</td>
      <td>1.731870</td>
      <td>84000005.0</td>
      <td>USA</td>
      <td>44634.177700</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-12-01 05:30:26</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>237835</td>
      <td>4062</td>
      <td>24199.0</td>
      <td>209574.0</td>
      <td>51.0</td>
      <td>2786.415214</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84000051.0</td>
      <td>USA</td>
      <td>38970.412930</td>
      <td>NaN</td>
      <td>3326327.0</td>
      <td>1.707907</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-12-01 05:30:26</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>171962</td>
      <td>2762</td>
      <td>NaN</td>
      <td>162245.0</td>
      <td>53.0</td>
      <td>2167.056057</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84000053.0</td>
      <td>USA</td>
      <td>38009.293105</td>
      <td>NaN</td>
      <td>2894367.0</td>
      <td>1.681019</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-12-01 05:30:26</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>47842</td>
      <td>735</td>
      <td>30320.0</td>
      <td>16787.0</td>
      <td>54.0</td>
      <td>2669.535479</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84000054.0</td>
      <td>USA</td>
      <td>63496.521212</td>
      <td>NaN</td>
      <td>1137951.0</td>
      <td>1.536307</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-12-01 05:30:26</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>411730</td>
      <td>3494</td>
      <td>315086.0</td>
      <td>93150.0</td>
      <td>55.0</td>
      <td>7071.441256</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84000055.0</td>
      <td>USA</td>
      <td>76016.834197</td>
      <td>NaN</td>
      <td>4426030.0</td>
      <td>0.848614</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-12-01 05:30:26</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>33305</td>
      <td>215</td>
      <td>24478.0</td>
      <td>8612.0</td>
      <td>56.0</td>
      <td>5754.554141</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84000056.0</td>
      <td>USA</td>
      <td>72497.706299</td>
      <td>NaN</td>
      <td>419587.0</td>
      <td>0.645549</td>
    </tr>
  </tbody>
</table>
<p>1740 rows × 20 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[101]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># This is for the month of December </span>

<span class="n">li</span><span class="o">=</span><span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;12&#39;</span><span class="o">+</span><span class="s1">&#39;-0&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">20</span><span class="p">):</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/&#39;</span>
    <span class="n">string</span> <span class="o">=</span> <span class="s1">&#39;12&#39;</span><span class="o">+</span><span class="s1">&#39;-&#39;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">i</span><span class="p">)</span><span class="o">+</span><span class="s1">&#39;-2020.csv&#39;</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">url</span> <span class="o">+</span> <span class="n">string</span>
    <span class="n">li</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">url</span><span class="p">)</span>

<span class="n">data_america_dec</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">url</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span> <span class="k">for</span> <span class="n">url</span> <span class="ow">in</span> <span class="n">li</span><span class="p">])</span>
<span class="n">data_america_dec</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[101]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>Total_Test_Results</th>
      <th>People_Hospitalized</th>
      <th>Case_Fatality_Ratio</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-12-02 05:30:41</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>252900</td>
      <td>3638</td>
      <td>161946.0</td>
      <td>87316.0</td>
      <td>1.0</td>
      <td>5157.871873</td>
      <td>1593842.0</td>
      <td>NaN</td>
      <td>1.438513</td>
      <td>84000001.0</td>
      <td>USA</td>
      <td>32506.258687</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-12-02 05:30:41</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>33115</td>
      <td>122</td>
      <td>7165.0</td>
      <td>25274.0</td>
      <td>2.0</td>
      <td>4450.990711</td>
      <td>1018628.0</td>
      <td>NaN</td>
      <td>0.374681</td>
      <td>84000002.0</td>
      <td>USA</td>
      <td>139243.382157</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-12-02 05:30:41</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>1988.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16.0</td>
      <td>ASM</td>
      <td>3572.904872</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-12-02 05:30:41</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>337139</td>
      <td>6687</td>
      <td>53026.0</td>
      <td>277426.0</td>
      <td>4.0</td>
      <td>4631.846519</td>
      <td>2271914.0</td>
      <td>NaN</td>
      <td>1.983455</td>
      <td>84000004.0</td>
      <td>USA</td>
      <td>31213.110772</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-12-02 05:30:41</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>159309</td>
      <td>2512</td>
      <td>140682.0</td>
      <td>16115.0</td>
      <td>5.0</td>
      <td>5278.971066</td>
      <td>1691453.0</td>
      <td>NaN</td>
      <td>1.576810</td>
      <td>84000005.0</td>
      <td>USA</td>
      <td>56049.133741</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-12-20 05:30:33</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>302972</td>
      <td>4643</td>
      <td>27633.0</td>
      <td>270696.0</td>
      <td>51.0</td>
      <td>3549.543970</td>
      <td>3888669.0</td>
      <td>NaN</td>
      <td>1.532485</td>
      <td>84000051.0</td>
      <td>USA</td>
      <td>45558.670773</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-12-20 05:30:33</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>222600</td>
      <td>3104</td>
      <td>NaN</td>
      <td>219496.0</td>
      <td>53.0</td>
      <td>2923.219013</td>
      <td>3478628.0</td>
      <td>NaN</td>
      <td>1.394429</td>
      <td>84000053.0</td>
      <td>USA</td>
      <td>45681.902556</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-12-20 05:30:33</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>71215</td>
      <td>1122</td>
      <td>47844.0</td>
      <td>22249.0</td>
      <td>54.0</td>
      <td>3973.725370</td>
      <td>1390401.0</td>
      <td>NaN</td>
      <td>1.575511</td>
      <td>84000054.0</td>
      <td>USA</td>
      <td>77582.977289</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-12-20 05:30:33</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>490679</td>
      <td>4722</td>
      <td>412499.0</td>
      <td>73458.0</td>
      <td>55.0</td>
      <td>8427.386210</td>
      <td>5040107.0</td>
      <td>NaN</td>
      <td>0.962340</td>
      <td>84000055.0</td>
      <td>USA</td>
      <td>86563.574615</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-12-20 05:30:33</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>41488</td>
      <td>351</td>
      <td>38620.0</td>
      <td>2517.0</td>
      <td>56.0</td>
      <td>7168.441441</td>
      <td>463753.0</td>
      <td>NaN</td>
      <td>0.846028</td>
      <td>84000056.0</td>
      <td>USA</td>
      <td>80128.861927</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>1102 rows × 18 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now, we will grab data for worldwide COVID-19 cases. This will be scraped by having a tsv file from <a href="https://github.com/owid/covid-19-data/tree/master/public/data">https://github.com/owid/covid-19-data/tree/master/public/data</a> which is data maintained by Our World in Data and is updated daily. This data will be taken as a tsv file and there will be minor modifications done to the data such as converting the date columns into datetime types as well as adding a column for months. This is how we will scrape the worldwide data:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[102]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">read_tsv</span> <span class="o">=</span> <span class="s1">&#39;worldwide-covid-data.tsv&#39;</span>
<span class="n">data_worldwide</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">read_tsv</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;</span><span class="se">\t</span><span class="s1">&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;datetime&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;date&#39;</span><span class="p">])</span>
<span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DatetimeIndex</span><span class="p">(</span><span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;datetime&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">month</span>
<span class="n">data_worldwide</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[102]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>iso_code</th>
      <th>continent</th>
      <th>location</th>
      <th>date</th>
      <th>total_cases</th>
      <th>new_cases</th>
      <th>new_cases_smoothed</th>
      <th>total_deaths</th>
      <th>new_deaths</th>
      <th>new_deaths_smoothed</th>
      <th>...</th>
      <th>cardiovasc_death_rate</th>
      <th>diabetes_prevalence</th>
      <th>female_smokers</th>
      <th>male_smokers</th>
      <th>handwashing_facilities</th>
      <th>hospital_beds_per_thousand</th>
      <th>life_expectancy</th>
      <th>human_development_index</th>
      <th>datetime</th>
      <th>month</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>AFG</td>
      <td>Asia</td>
      <td>Afghanistan</td>
      <td>2020-01-23</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>597.029</td>
      <td>9.59</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>37.746</td>
      <td>0.5</td>
      <td>64.83</td>
      <td>0.498</td>
      <td>2020-01-23</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>AFG</td>
      <td>Asia</td>
      <td>Afghanistan</td>
      <td>2020-01-24</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>597.029</td>
      <td>9.59</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>37.746</td>
      <td>0.5</td>
      <td>64.83</td>
      <td>0.498</td>
      <td>2020-01-24</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>AFG</td>
      <td>Asia</td>
      <td>Afghanistan</td>
      <td>2020-01-25</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>597.029</td>
      <td>9.59</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>37.746</td>
      <td>0.5</td>
      <td>64.83</td>
      <td>0.498</td>
      <td>2020-01-25</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>AFG</td>
      <td>Asia</td>
      <td>Afghanistan</td>
      <td>2020-01-26</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>597.029</td>
      <td>9.59</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>37.746</td>
      <td>0.5</td>
      <td>64.83</td>
      <td>0.498</td>
      <td>2020-01-26</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>AFG</td>
      <td>Asia</td>
      <td>Afghanistan</td>
      <td>2020-01-27</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>597.029</td>
      <td>9.59</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>37.746</td>
      <td>0.5</td>
      <td>64.83</td>
      <td>0.498</td>
      <td>2020-01-27</td>
      <td>1</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>60857</th>
      <td>ZWE</td>
      <td>Africa</td>
      <td>Zimbabwe</td>
      <td>2020-12-01</td>
      <td>10129.0</td>
      <td>179.0</td>
      <td>104.429</td>
      <td>277.0</td>
      <td>1.0</td>
      <td>0.429</td>
      <td>...</td>
      <td>307.846</td>
      <td>1.82</td>
      <td>1.6</td>
      <td>30.7</td>
      <td>36.791</td>
      <td>1.7</td>
      <td>61.49</td>
      <td>0.535</td>
      <td>2020-12-01</td>
      <td>12</td>
    </tr>
    <tr>
      <th>60858</th>
      <td>ZWE</td>
      <td>Africa</td>
      <td>Zimbabwe</td>
      <td>2020-12-02</td>
      <td>10129.0</td>
      <td>0.0</td>
      <td>88.714</td>
      <td>277.0</td>
      <td>0.0</td>
      <td>0.429</td>
      <td>...</td>
      <td>307.846</td>
      <td>1.82</td>
      <td>1.6</td>
      <td>30.7</td>
      <td>36.791</td>
      <td>1.7</td>
      <td>61.49</td>
      <td>0.535</td>
      <td>2020-12-02</td>
      <td>12</td>
    </tr>
    <tr>
      <th>60859</th>
      <td>ZWE</td>
      <td>Africa</td>
      <td>Zimbabwe</td>
      <td>2020-12-03</td>
      <td>10424.0</td>
      <td>295.0</td>
      <td>114.429</td>
      <td>280.0</td>
      <td>3.0</td>
      <td>0.857</td>
      <td>...</td>
      <td>307.846</td>
      <td>1.82</td>
      <td>1.6</td>
      <td>30.7</td>
      <td>36.791</td>
      <td>1.7</td>
      <td>61.49</td>
      <td>0.535</td>
      <td>2020-12-03</td>
      <td>12</td>
    </tr>
    <tr>
      <th>60860</th>
      <td>ZWE</td>
      <td>Africa</td>
      <td>Zimbabwe</td>
      <td>2020-12-04</td>
      <td>10547.0</td>
      <td>123.0</td>
      <td>119.000</td>
      <td>281.0</td>
      <td>1.0</td>
      <td>0.857</td>
      <td>...</td>
      <td>307.846</td>
      <td>1.82</td>
      <td>1.6</td>
      <td>30.7</td>
      <td>36.791</td>
      <td>1.7</td>
      <td>61.49</td>
      <td>0.535</td>
      <td>2020-12-04</td>
      <td>12</td>
    </tr>
    <tr>
      <th>60861</th>
      <td>ZWE</td>
      <td>Africa</td>
      <td>Zimbabwe</td>
      <td>2020-12-05</td>
      <td>10617.0</td>
      <td>70.0</td>
      <td>113.571</td>
      <td>291.0</td>
      <td>10.0</td>
      <td>2.286</td>
      <td>...</td>
      <td>307.846</td>
      <td>1.82</td>
      <td>1.6</td>
      <td>30.7</td>
      <td>36.791</td>
      <td>1.7</td>
      <td>61.49</td>
      <td>0.535</td>
      <td>2020-12-05</td>
      <td>12</td>
    </tr>
  </tbody>
</table>
<p>60862 rows × 52 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>This is how the COVID-19 data would be taken with total cases around the world by location. In this, we are receiving data from <a href="https://coronavirus.jhu.edu/map.html">https://coronavirus.jhu.edu/map.html</a> which also provides a dashboard for COVID-19 data throughout the world with the most up to date information. In this, we will only receive the data at the most updated date and get the total cases up to that point for all the locations. This data would be used in order to correlate different factors such as lockdown dates with the total cases by location. We will import a csv file and read in the data for this. This is how we will scrape this data:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[103]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">read_tsv</span> <span class="o">=</span> <span class="s1">&#39;covid-all-data.csv&#39;</span>
<span class="n">covid_all_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">read_tsv</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">covid_all_data</span> <span class="o">=</span> <span class="n">covid_all_data</span><span class="p">[</span><span class="n">covid_all_data</span><span class="p">[</span><span class="s1">&#39;date&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;2020-12-18&#39;</span><span class="p">]</span>
<span class="n">covid_all_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">covid_all_data</span><span class="o">.</span><span class="n">columns</span><span class="o">.</span><span class="n">difference</span><span class="p">([</span><span class="s1">&#39;location&#39;</span><span class="p">,</span> <span class="s1">&#39;total_cases&#39;</span><span class="p">]),</span> <span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">covid_all_data</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s1">&#39;location&#39;</span><span class="p">:</span> <span class="s1">&#39;Country&#39;</span><span class="p">},</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">covid_all_data</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">drop</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">covid_all_data</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[103]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>total_cases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Afghanistan</td>
      <td>49621.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Albania</td>
      <td>52004.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Algeria</td>
      <td>94371.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Andorra</td>
      <td>7519.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Angola</td>
      <td>16562.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>186</th>
      <td>Vietnam</td>
      <td>1410.0</td>
    </tr>
    <tr>
      <th>187</th>
      <td>World</td>
      <td>75672814.0</td>
    </tr>
    <tr>
      <th>188</th>
      <td>Yemen</td>
      <td>2087.0</td>
    </tr>
    <tr>
      <th>189</th>
      <td>Zambia</td>
      <td>18575.0</td>
    </tr>
    <tr>
      <th>190</th>
      <td>Zimbabwe</td>
      <td>12047.0</td>
    </tr>
  </tbody>
</table>
<p>191 rows × 2 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here, we will be looking at the lockdown dates (specifically the start and end times) by location. We will be using a tsv file and reading that in. We modify the data slightly by not using certain columns and converting the date columns into datetime objects. This data will be got from <a href="https://auravision.ai/covid19-lockdown-tracker/">https://auravision.ai/covid19-lockdown-tracker/</a> which is also a great resource in order to look at the lockdowns throughout the world and different ways it could be visualized. This is how we scrape this data:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[104]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">read_tsv</span> <span class="o">=</span> <span class="s1">&#39;lockdown_dates.tsv&#39;</span>
<span class="n">data_worldwide_lockdown</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">read_tsv</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;</span><span class="se">\t</span><span class="s1">&#39;</span><span class="p">,</span> <span class="n">error_bad_lines</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">data_worldwide_lockdown</span> <span class="o">=</span> <span class="n">data_worldwide_lockdown</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;url&#39;</span><span class="p">])</span>
<span class="n">data_worldwide_lockdown</span><span class="p">[</span><span class="s1">&#39;Start date&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">data_worldwide_lockdown</span><span class="p">[</span><span class="s1">&#39;Start date&#39;</span><span class="p">])</span>
<span class="n">data_worldwide_lockdown</span><span class="p">[</span><span class="s1">&#39;End date&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">data_worldwide_lockdown</span><span class="p">[</span><span class="s1">&#39;End date&#39;</span><span class="p">])</span>
<span class="n">data_worldwide_lockdown</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[104]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Place</th>
      <th>Start date</th>
      <th>End date</th>
      <th>Level</th>
      <th>update</th>
      <th>Confirmed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>China</td>
      <td>Xiangyang</td>
      <td>2020-01-28</td>
      <td>2020-03-25</td>
      <td>City</td>
      <td>2020-02-04</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Philippines</td>
      <td>Soccsksargen</td>
      <td>2020-03-23</td>
      <td>2020-04-30</td>
      <td>Region</td>
      <td>2020-03-12</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>China</td>
      <td>Huangshi</td>
      <td>2020-01-24</td>
      <td>2020-03-13</td>
      <td>City</td>
      <td>2020-03-14</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Montenegro</td>
      <td>Tuzi</td>
      <td>2020-03-24</td>
      <td>NaT</td>
      <td>Municipality</td>
      <td>2020-03-16</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>China</td>
      <td>Jingzhou</td>
      <td>2020-01-24</td>
      <td>2020-03-17</td>
      <td>City</td>
      <td>2020-03-16</td>
      <td>True</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>213</th>
      <td>Bangladesh</td>
      <td>NaN</td>
      <td>2020-03-26</td>
      <td>2020-04-29</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
    </tr>
    <tr>
      <th>214</th>
      <td>Algeria</td>
      <td>NaN</td>
      <td>2020-03-23</td>
      <td>2020-04-26</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
    </tr>
    <tr>
      <th>215</th>
      <td>Albania</td>
      <td>NaN</td>
      <td>2020-03-10</td>
      <td>2020-04-19</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
    </tr>
    <tr>
      <th>216</th>
      <td>Jamaica</td>
      <td>NaN</td>
      <td>2020-04-15</td>
      <td>2020-04-29</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
    </tr>
    <tr>
      <th>217</th>
      <td>Zimbabwe</td>
      <td>NaN</td>
      <td>2020-03-30</td>
      <td>2020-07-02</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
<p>218 rows × 7 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>At this point, we will merge the two dataframes we have which will merge the total cases based on location with the start and end lockdown dates using pandas functions.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[105]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">combined_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">data_worldwide_lockdown</span><span class="p">,</span> <span class="n">covid_all_data</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">combined_data</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[105]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Place</th>
      <th>Start date</th>
      <th>End date</th>
      <th>Level</th>
      <th>update</th>
      <th>Confirmed</th>
      <th>total_cases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>China</td>
      <td>Xiangyang</td>
      <td>2020-01-28</td>
      <td>2020-03-25</td>
      <td>City</td>
      <td>2020-02-04</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>China</td>
      <td>Huangshi</td>
      <td>2020-01-24</td>
      <td>2020-03-13</td>
      <td>City</td>
      <td>2020-03-14</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>China</td>
      <td>Jingzhou</td>
      <td>2020-01-24</td>
      <td>2020-03-17</td>
      <td>City</td>
      <td>2020-03-16</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>China</td>
      <td>Ezhou</td>
      <td>2020-01-23</td>
      <td>2020-03-25</td>
      <td>City</td>
      <td>2020-03-24</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>China</td>
      <td>Xianning</td>
      <td>2020-01-24</td>
      <td>2020-03-25</td>
      <td>City</td>
      <td>2020-03-24</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>205</th>
      <td>Cuba</td>
      <td>NaN</td>
      <td>2020-03-23</td>
      <td>2020-07-20</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>9893.0</td>
    </tr>
    <tr>
      <th>206</th>
      <td>Costa Rica</td>
      <td>NaN</td>
      <td>2020-03-23</td>
      <td>2020-08-01</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>157472.0</td>
    </tr>
    <tr>
      <th>207</th>
      <td>Bangladesh</td>
      <td>NaN</td>
      <td>2020-03-26</td>
      <td>2020-04-29</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>498293.0</td>
    </tr>
    <tr>
      <th>208</th>
      <td>Albania</td>
      <td>NaN</td>
      <td>2020-03-10</td>
      <td>2020-04-19</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>52004.0</td>
    </tr>
    <tr>
      <th>209</th>
      <td>Zimbabwe</td>
      <td>NaN</td>
      <td>2020-03-30</td>
      <td>2020-07-02</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>12047.0</td>
    </tr>
  </tbody>
</table>
<p>210 rows × 8 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Data-Visualization-and-Analysis:">Data Visualization and Analysis:<a class="anchor-link" href="#Data-Visualization-and-Analysis:">&#182;</a></h3><p>Now that we have our data, we will firstly look at it on a large scale. Let’s compare the amount of average cases for each country in a continent. First, to do this, we can find the average amount of cases for each continent based on the worldwide data using the groupby function. This will give us a table that we can then use to plot and see visually where each continent differs in comparison to the rest.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[106]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#so here we find the average of the new cases in each continent</span>
<span class="n">data_worldwide_avg</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;continent&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">reset_index</span><span class="p">()</span>

<span class="c1">#but what does it look like? let&#39;s plot it.</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">data_worldwide_avg</span><span class="p">[</span><span class="s1">&#39;continent&#39;</span><span class="p">],</span> <span class="n">data_worldwide_avg</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">])</span>

<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;continent&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;# of total cases&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;average total case across continents&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[106]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0.5, 1.0, &#39;average total case across continents&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>So using this, we can compare that the amount of total cases there are currently for each continent. From this we can see that Africa and Oceania both have significantly low levels of total cases in each county compared to the other continents. We can also see that North America and South America has higher total amount of cases, probably due to higher amount of interactions among individuals who tested positive.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Next, we will also look at the rate at which the amount of cases grew in each continent. We will do this by plotting time on the x-axis as a factor of months. In order to acheive this, we need to seperate each continent from the worldwide data and find the means of each per month. We can then plot this information.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#splitting the data by continent</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;continent&#39;</span><span class="p">],</span> <span class="n">as_index</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>

<span class="c1">#setting the months as numerical values such that January corresponds to 1 and December to 12</span>
<span class="n">months</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">6</span><span class="p">,</span> <span class="mi">7</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">9</span><span class="p">,</span> <span class="mi">10</span><span class="p">,</span> <span class="mi">11</span><span class="p">,</span> <span class="mi">12</span><span class="p">]</span>

<span class="c1">#for each continent we will find the mean per month and plot it</span>
<span class="n">Africa</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;Africa&#39;</span><span class="p">)</span>
<span class="n">Africa_means</span> <span class="o">=</span> <span class="n">Africa</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">Africa_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">Africa_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">Africa_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Africa&quot;</span><span class="p">)</span>


<span class="n">Asia</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;Asia&#39;</span><span class="p">)</span>
<span class="n">Asia_means</span> <span class="o">=</span> <span class="n">Asia</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">Asia_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">Asia_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">Asia_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Asia&quot;</span><span class="p">)</span>

<span class="n">Europe</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;Europe&#39;</span><span class="p">)</span>
<span class="n">Europe_means</span> <span class="o">=</span> <span class="n">Europe</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">Europe_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">Europe_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">Europe_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Europe&quot;</span><span class="p">)</span>

<span class="n">North_America</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;North America&#39;</span><span class="p">)</span>
<span class="n">North_America_means</span> <span class="o">=</span> <span class="n">North_America</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;North_America&quot;</span><span class="p">)</span>

<span class="n">Oceania</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;Oceania&#39;</span><span class="p">)</span>
<span class="n">Oceania_means</span> <span class="o">=</span> <span class="n">Oceania</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">Oceania_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">Oceania_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">Oceania_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Oceania&quot;</span><span class="p">)</span>

<span class="n">South_America</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;South America&#39;</span><span class="p">)</span>
<span class="n">South_America_means</span> <span class="o">=</span> <span class="n">South_America</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">South_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">months</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">South_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">South_America_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">],</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;South_America&quot;</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;month&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;# of total cases&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;average total case across time&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[16]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.legend.Legend at 0x7f438252bee0&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From this line graph, we can see how the continents compare over time with respect to total cases. We can see that over time, both Africa and Oceania don't increase drastically, which supports the fact that we saw these two continents with the lowest amount of total average cases. Same with the vice versa of North America and South America. This is also interesting because we can see when cases started to pick up for certain countries. For example, cases started to increase in May-June for the Americas, while for Europe, we see it drastically increasing after October.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Next, we will be visualizing data of total cases throughout the world and this can be best visualized using a chloropleth map which should easily be a way in order to look at the data worldwide and see the number of COVID-19 cases. This can be done with a time slider as well in order to better ensure the fact that there can be a visualization of the daily change in COVID-19 cases throughout the world.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[114]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Legend updates as the number of cases change</span>
<span class="n">fig</span> <span class="o">=</span> <span class="n">px</span><span class="o">.</span><span class="n">choropleth</span><span class="p">(</span><span class="n">data_frame</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">,</span> 
                    <span class="n">locations</span><span class="o">=</span> <span class="s2">&quot;iso_code&quot;</span><span class="p">,</span>
                    <span class="n">color</span><span class="o">=</span> <span class="s2">&quot;total_cases&quot;</span><span class="p">,</span>
                    <span class="n">hover_name</span><span class="o">=</span> <span class="s2">&quot;location&quot;</span><span class="p">,</span>
                    <span class="n">color_continuous_scale</span><span class="o">=</span> <span class="s1">&#39;sunset&#39;</span><span class="p">,</span> 
                    <span class="n">animation_frame</span><span class="o">=</span> <span class="s2">&quot;date&quot;</span><span class="p">)</span>
<span class="n">fig</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<div>                            <div id="e78f72c9-a015-456b-b859-5ddb35909af4" class="plotly-graph-div" style="height:525px; width:100%;"></div>            <script type="text/javascript">                require(["plotly"], function(Plotly) {                    window.PLOTLYENV=window.PLOTLYENV || {};                                    if (document.getElementById("e78f72c9-a015-456b-b859-5ddb35909af4")) {                    Plotly.newPlot(                        "e78f72c9-a015-456b-b859-5ddb35909af4",                        [{"coloraxis": "coloraxis", "geo": "geo", "hovertemplate": "<b>%{hovertext}</b><br><br>date=2020-01-23<br>iso_code=%{location}<br>total_cases=%{z}<extra></extra>", "hovertext": ["Afghanistan", "Albania", "Algeria", "Andorra", "Angola", "Antigua and Barbuda", "Argentina", "Armenia", "Australia", "Austria", "Azerbaijan", "Bahamas", "Bahrain", "Bangladesh", "Barbados", "Belarus", "Belgium", "Belize", "Benin", "Bhutan", "Bolivia", "Bosnia and Herzegovina", "Botswana", "Brazil", "Brunei", "Bulgaria", "Burkina Faso", "Burundi", "Cambodia", "Cameroon", "Canada", "Cape Verde", "Central African Republic", "Chad", "Chile", "China", "Colombia", "Comoros", "Congo", "Costa Rica", "Cote d'Ivoire", "Croatia", "Cuba", "Cyprus", "Czech Republic", "Democratic Republic of Congo", "Denmark", "Djibouti", "Dominica", "Dominican Republic", "Ecuador", "Egypt", "El Salvador", "Equatorial Guinea", "Eritrea", "Estonia", "Ethiopia", "Fiji", "Finland", "France", "Gabon", "Gambia", "Georgia", "Germany", "Ghana", "Greece", "Grenada", "Guatemala", "Guinea", "Guinea-Bissau", "Guyana", "Haiti", "Honduras", "Hungary", "Iceland", "India", "Indonesia", "International", "Iran", "Iraq", "Ireland", "Israel", "Italy", "Jamaica", "Japan", "Jordan", "Kazakhstan", "Kenya", "Kosovo", "Kuwait", "Kyrgyzstan", "Laos", "Latvia", "Lebanon", "Lesotho", "Liberia", "Libya", "Liechtenstein", "Lithuania", "Luxembourg", "Macedonia", "Madagascar", "Malawi", "Malaysia", "Maldives", "Mali", "Malta", "Marshall Islands", "Mauritania", "Mauritius", "Mexico", "Moldova", "Monaco", "Mongolia", "Montenegro", "Morocco", "Mozambique", "Myanmar", "Namibia", "Nepal", "Netherlands", "New Zealand", "Nicaragua", "Niger", "Nigeria", "Norway", "Oman", "Pakistan", "Palestine", "Panama", "Papua New Guinea", "Paraguay", "Peru", "Philippines", "Poland", "Portugal", "Qatar", "Romania", "Russia", "Rwanda", "Saint Kitts and Nevis", "Saint Lucia", "Saint Vincent and the Grenadines", "San Marino", "Sao Tome and Principe", "Saudi Arabia", "Senegal", "Serbia", "Seychelles", "Sierra Leone", "Singapore", "Slovakia", "Slovenia", "Solomon Islands", "Somalia", "South Africa", "South Korea", "South Sudan", "Spain", "Sri Lanka", "Sudan", "Suriname", "Swaziland", "Sweden", "Switzerland", "Syria", "Taiwan", "Tajikistan", "Tanzania", "Thailand", "Timor", "Togo", "Trinidad and Tobago", "Tunisia", "Turkey", "Uganda", "Ukraine", "United Arab Emirates", "United Kingdom", "United States", "Uruguay", "Uzbekistan", "Vanuatu", "Vatican", "Venezuela", "Vietnam", "Western Sahara", "World", "Yemen", "Zambia", "Zimbabwe"], "locations": ["AFG", "ALB", "DZA", "AND", "AGO", "ATG", "ARG", "ARM", "AUS", "AUT", "AZE", "BHS", "BHR", "BGD", "BRB", "BLR", "BEL", "BLZ", "BEN", "BTN", "BOL", "BIH", "BWA", "BRA", "BRN", "BGR", "BFA", "BDI", "KHM", "CMR", "CAN", "CPV", "CAF", "TCD", "CHL", "CHN", "COL", "COM", "COG", "CRI", "CIV", "HRV", "CUB", "CYP", "CZE", "COD", "DNK", "DJI", "DMA", "DOM", "ECU", "EGY", "SLV", "GNQ", "ERI", "EST", "ETH", "FJI", "FIN", "FRA", "GAB", "GMB", "GEO", "DEU", "GHA", "GRC", "GRD", "GTM", "GIN", "GNB", "GUY", "HTI", "HND", "HUN", "ISL", "IND", "IDN", null, "IRN", "IRQ", "IRL", "ISR", "ITA", "JAM", "JPN", "JOR", "KAZ", "KEN", "OWID_KOS", "KWT", "KGZ", "LAO", "LVA", "LBN", "LSO", "LBR", "LBY", "LIE", "LTU", "LUX", "MKD", "MDG", "MWI", "MYS", "MDV", "MLI", "MLT", "MHL", "MRT", "MUS", "MEX", "MDA", "MCO", "MNG", "MNE", "MAR", "MOZ", "MMR", "NAM", "NPL", "NLD", "NZL", "NIC", "NER", "NGA", "NOR", "OMN", "PAK", "PSE", "PAN", "PNG", "PRY", "PER", "PHL", "POL", "PRT", "QAT", "ROU", "RUS", "RWA", "KNA", "LCA", "VCT", "SMR", "STP", "SAU", "SEN", "SRB", "SYC", "SLE", "SGP", "SVK", "SVN", "SLB", "SOM", "ZAF", "KOR", "SSD", "ESP", "LKA", "SDN", "SUR", "SWZ", "SWE", "CHE", "SYR", "TWN", "TJK", "TZA", "THA", "TLS", "TGO", "TTO", "TUN", "TUR", "UGA", "UKR", "ARE", "GBR", "USA", "URY", "UZB", "VUT", "VAT", "VEN", "VNM", "ESH", "OWID_WRL", "YEM", "ZMB", "ZWE"], "name": "", "type": "choropleth", "z": [null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, 643.0, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, 2.0, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, 1.0, null, null, null, null, null, 1.0, null, null, null, null, null, null, null, null, null, 1.0, null, null, 3.0, null, null, null, null, null, null, null, null, null, 1.0, null, null, null, null, null, 2.0, null, 654.0, null, null, null]}],                        {"coloraxis": {"colorbar": {"title": {"text": "total_cases"}}, "colorscale": [[0.0, "rgb(243, 231, 155)"], [0.16666666666666666, "rgb(250, 196, 132)"], [0.3333333333333333, "rgb(248, 160, 126)"], [0.5, "rgb(235, 127, 134)"], [0.6666666666666666, "rgb(206, 102, 147)"], [0.8333333333333334, "rgb(160, 89, 160)"], [1.0, "rgb(92, 83, 165)"]]}, "geo": {"center": {}, "domain": {"x": [0.0, 1.0], "y": [0.0, 1.0]}}, "legend": {"tracegroupgap": 0}, "margin": {"t": 60}, "sliders": [{"active": 0, "currentvalue": {"prefix": "date="}, "len": 0.9, "pad": {"b": 10, "t": 60}, "steps": [{"args": [["2020-01-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-23", "method": "animate"}, {"args": [["2020-01-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-24", "method": "animate"}, {"args": [["2020-01-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-25", "method": "animate"}, {"args": [["2020-01-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-26", "method": "animate"}, {"args": [["2020-01-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-27", "method": "animate"}, {"args": [["2020-01-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-28", "method": "animate"}, {"args": [["2020-01-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-29", "method": "animate"}, {"args": [["2020-01-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-30", "method": "animate"}, {"args": [["2020-01-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-31", "method": "animate"}, {"args": [["2020-02-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-01", "method": "animate"}, {"args": [["2020-02-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-02", "method": "animate"}, {"args": [["2020-02-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-03", "method": "animate"}, {"args": [["2020-02-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-04", "method": "animate"}, {"args": [["2020-02-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-05", "method": "animate"}, {"args": [["2020-02-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-06", "method": "animate"}, {"args": [["2020-02-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-07", "method": "animate"}, {"args": [["2020-02-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-08", "method": "animate"}, {"args": [["2020-02-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-09", "method": "animate"}, {"args": [["2020-02-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-10", "method": "animate"}, {"args": [["2020-02-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-11", "method": "animate"}, {"args": [["2020-02-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-12", "method": "animate"}, {"args": [["2020-02-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-13", "method": "animate"}, {"args": [["2020-02-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-14", "method": "animate"}, {"args": [["2020-02-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-15", "method": "animate"}, {"args": [["2020-02-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-16", "method": "animate"}, {"args": [["2020-02-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-17", "method": "animate"}, {"args": [["2020-02-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-18", "method": "animate"}, {"args": [["2020-02-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-19", "method": "animate"}, {"args": [["2020-02-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-20", "method": "animate"}, {"args": [["2020-02-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-21", "method": "animate"}, {"args": [["2020-02-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-22", "method": "animate"}, {"args": [["2020-02-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-23", "method": "animate"}, {"args": [["2020-02-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-24", "method": "animate"}, {"args": [["2020-02-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-25", "method": "animate"}, {"args": [["2020-02-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-26", "method": "animate"}, {"args": [["2020-02-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-27", "method": "animate"}, {"args": [["2020-02-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-28", "method": "animate"}, {"args": [["2020-02-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-02-29", "method": "animate"}, {"args": [["2020-03-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-01", "method": "animate"}, {"args": [["2020-03-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-02", "method": "animate"}, {"args": [["2020-03-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-03", "method": "animate"}, {"args": [["2020-03-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-04", "method": "animate"}, {"args": [["2020-03-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-05", "method": "animate"}, {"args": [["2020-03-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-06", "method": "animate"}, {"args": [["2020-03-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-07", "method": "animate"}, {"args": [["2020-03-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-08", "method": "animate"}, {"args": [["2020-03-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-09", "method": "animate"}, {"args": [["2020-03-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-10", "method": "animate"}, {"args": [["2020-03-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-11", "method": "animate"}, {"args": [["2020-03-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-12", "method": "animate"}, {"args": [["2020-03-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-13", "method": "animate"}, {"args": [["2020-03-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-14", "method": "animate"}, {"args": [["2020-03-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-15", "method": "animate"}, {"args": [["2020-03-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-16", "method": "animate"}, {"args": [["2020-03-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-17", "method": "animate"}, {"args": [["2020-03-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-18", "method": "animate"}, {"args": [["2020-03-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-19", "method": "animate"}, {"args": [["2020-03-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-20", "method": "animate"}, {"args": [["2020-03-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-21", "method": "animate"}, {"args": [["2020-03-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-22", "method": "animate"}, {"args": [["2020-03-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-23", "method": "animate"}, {"args": [["2020-03-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-24", "method": "animate"}, {"args": [["2020-03-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-25", "method": "animate"}, {"args": [["2020-03-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-26", "method": "animate"}, {"args": [["2020-03-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-27", "method": "animate"}, {"args": [["2020-03-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-28", "method": "animate"}, {"args": [["2020-03-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-29", "method": "animate"}, {"args": [["2020-03-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-30", "method": "animate"}, {"args": [["2020-03-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-03-31", "method": "animate"}, {"args": [["2020-04-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-01", "method": "animate"}, {"args": [["2020-04-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-02", "method": "animate"}, {"args": [["2020-04-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-03", "method": "animate"}, {"args": [["2020-04-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-04", "method": "animate"}, {"args": [["2020-04-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-05", "method": "animate"}, {"args": [["2020-04-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-06", "method": "animate"}, {"args": [["2020-04-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-07", "method": "animate"}, {"args": [["2020-04-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-08", "method": "animate"}, {"args": [["2020-04-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-09", "method": "animate"}, {"args": [["2020-04-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-10", "method": "animate"}, {"args": [["2020-04-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-11", "method": "animate"}, {"args": [["2020-04-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-12", "method": "animate"}, {"args": [["2020-04-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-13", "method": "animate"}, {"args": [["2020-04-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-14", "method": "animate"}, {"args": [["2020-04-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-15", "method": "animate"}, {"args": [["2020-04-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-16", "method": "animate"}, {"args": [["2020-04-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-17", "method": "animate"}, {"args": [["2020-04-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-18", "method": "animate"}, {"args": [["2020-04-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-19", "method": "animate"}, {"args": [["2020-04-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-20", "method": "animate"}, {"args": [["2020-04-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-21", "method": "animate"}, {"args": [["2020-04-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-22", "method": "animate"}, {"args": [["2020-04-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-23", "method": "animate"}, {"args": [["2020-04-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-24", "method": "animate"}, {"args": [["2020-04-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-25", "method": "animate"}, {"args": [["2020-04-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-26", "method": "animate"}, {"args": [["2020-04-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-27", "method": "animate"}, {"args": [["2020-04-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-28", "method": "animate"}, {"args": [["2020-04-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-29", "method": "animate"}, {"args": [["2020-04-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-04-30", "method": "animate"}, {"args": [["2020-05-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-01", "method": "animate"}, {"args": [["2020-05-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-02", "method": "animate"}, {"args": [["2020-05-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-03", "method": "animate"}, {"args": [["2020-05-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-04", "method": "animate"}, {"args": [["2020-05-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-05", "method": "animate"}, {"args": [["2020-05-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-06", "method": "animate"}, {"args": [["2020-05-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-07", "method": "animate"}, {"args": [["2020-05-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-08", "method": "animate"}, {"args": [["2020-05-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-09", "method": "animate"}, {"args": [["2020-05-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-10", "method": "animate"}, {"args": [["2020-05-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-11", "method": "animate"}, {"args": [["2020-05-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-12", "method": "animate"}, {"args": [["2020-05-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-13", "method": "animate"}, {"args": [["2020-05-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-14", "method": "animate"}, {"args": [["2020-05-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-15", "method": "animate"}, {"args": [["2020-05-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-16", "method": "animate"}, {"args": [["2020-05-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-17", "method": "animate"}, {"args": [["2020-05-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-18", "method": "animate"}, {"args": [["2020-05-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-19", "method": "animate"}, {"args": [["2020-05-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-20", "method": "animate"}, {"args": [["2020-05-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-21", "method": "animate"}, {"args": [["2020-05-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-22", "method": "animate"}, {"args": [["2020-05-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-23", "method": "animate"}, {"args": [["2020-05-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-24", "method": "animate"}, {"args": [["2020-05-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-25", "method": "animate"}, {"args": [["2020-05-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-26", "method": "animate"}, {"args": [["2020-05-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-27", "method": "animate"}, {"args": [["2020-05-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-28", "method": "animate"}, {"args": [["2020-05-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-29", "method": "animate"}, {"args": [["2020-05-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-30", "method": "animate"}, {"args": [["2020-05-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-05-31", "method": "animate"}, {"args": [["2020-06-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-01", "method": "animate"}, {"args": [["2020-06-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-02", "method": "animate"}, {"args": [["2020-06-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-03", "method": "animate"}, {"args": [["2020-06-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-04", "method": "animate"}, {"args": [["2020-06-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-05", "method": "animate"}, {"args": [["2020-06-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-06", "method": "animate"}, {"args": [["2020-06-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-07", "method": "animate"}, {"args": [["2020-06-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-08", "method": "animate"}, {"args": [["2020-06-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-09", "method": "animate"}, {"args": [["2020-06-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-10", "method": "animate"}, {"args": [["2020-06-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-11", "method": "animate"}, {"args": [["2020-06-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-12", "method": "animate"}, {"args": [["2020-06-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-13", "method": "animate"}, {"args": [["2020-06-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-14", "method": "animate"}, {"args": [["2020-06-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-15", "method": "animate"}, {"args": [["2020-06-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-16", "method": "animate"}, {"args": [["2020-06-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-17", "method": "animate"}, {"args": [["2020-06-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-18", "method": "animate"}, {"args": [["2020-06-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-19", "method": "animate"}, {"args": [["2020-06-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-20", "method": "animate"}, {"args": [["2020-06-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-21", "method": "animate"}, {"args": [["2020-06-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-22", "method": "animate"}, {"args": [["2020-06-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-23", "method": "animate"}, {"args": [["2020-06-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-24", "method": "animate"}, {"args": [["2020-06-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-25", "method": "animate"}, {"args": [["2020-06-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-26", "method": "animate"}, {"args": [["2020-06-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-27", "method": "animate"}, {"args": [["2020-06-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-28", "method": "animate"}, {"args": [["2020-06-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-29", "method": "animate"}, {"args": [["2020-06-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-06-30", "method": "animate"}, {"args": [["2020-07-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-01", "method": "animate"}, {"args": [["2020-07-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-02", "method": "animate"}, {"args": [["2020-07-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-03", "method": "animate"}, {"args": [["2020-07-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-04", "method": "animate"}, {"args": [["2020-07-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-05", "method": "animate"}, {"args": [["2020-07-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-06", "method": "animate"}, {"args": [["2020-07-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-07", "method": "animate"}, {"args": [["2020-07-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-08", "method": "animate"}, {"args": [["2020-07-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-09", "method": "animate"}, {"args": [["2020-07-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-10", "method": "animate"}, {"args": [["2020-07-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-11", "method": "animate"}, {"args": [["2020-07-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-12", "method": "animate"}, {"args": [["2020-07-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-13", "method": "animate"}, {"args": [["2020-07-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-14", "method": "animate"}, {"args": [["2020-07-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-15", "method": "animate"}, {"args": [["2020-07-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-16", "method": "animate"}, {"args": [["2020-07-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-17", "method": "animate"}, {"args": [["2020-07-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-18", "method": "animate"}, {"args": [["2020-07-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-19", "method": "animate"}, {"args": [["2020-07-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-20", "method": "animate"}, {"args": [["2020-07-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-21", "method": "animate"}, {"args": [["2020-07-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-22", "method": "animate"}, {"args": [["2020-07-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-23", "method": "animate"}, {"args": [["2020-07-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-24", "method": "animate"}, {"args": [["2020-07-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-25", "method": "animate"}, {"args": [["2020-07-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-26", "method": "animate"}, {"args": [["2020-07-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-27", "method": "animate"}, {"args": [["2020-07-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-28", "method": "animate"}, {"args": [["2020-07-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-29", "method": "animate"}, {"args": [["2020-07-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-30", "method": "animate"}, {"args": [["2020-07-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-07-31", "method": "animate"}, {"args": [["2020-08-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-01", "method": "animate"}, {"args": [["2020-08-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-02", "method": "animate"}, {"args": [["2020-08-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-03", "method": "animate"}, {"args": [["2020-08-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-04", "method": "animate"}, {"args": [["2020-08-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-05", "method": "animate"}, {"args": [["2020-08-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-06", "method": "animate"}, {"args": [["2020-08-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-07", "method": "animate"}, {"args": [["2020-08-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-08", "method": "animate"}, {"args": [["2020-08-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-09", "method": "animate"}, {"args": [["2020-08-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-10", "method": "animate"}, {"args": [["2020-08-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-11", "method": "animate"}, {"args": [["2020-08-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-12", "method": "animate"}, {"args": [["2020-08-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-13", "method": "animate"}, {"args": [["2020-08-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-14", "method": "animate"}, {"args": [["2020-08-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-15", "method": "animate"}, {"args": [["2020-08-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-16", "method": "animate"}, {"args": [["2020-08-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-17", "method": "animate"}, {"args": [["2020-08-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-18", "method": "animate"}, {"args": [["2020-08-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-19", "method": "animate"}, {"args": [["2020-08-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-20", "method": "animate"}, {"args": [["2020-08-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-21", "method": "animate"}, {"args": [["2020-08-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-22", "method": "animate"}, {"args": [["2020-08-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-23", "method": "animate"}, {"args": [["2020-08-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-24", "method": "animate"}, {"args": [["2020-08-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-25", "method": "animate"}, {"args": [["2020-08-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-26", "method": "animate"}, {"args": [["2020-08-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-27", "method": "animate"}, {"args": [["2020-08-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-28", "method": "animate"}, {"args": [["2020-08-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-29", "method": "animate"}, {"args": [["2020-08-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-30", "method": "animate"}, {"args": [["2020-08-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-08-31", "method": "animate"}, {"args": [["2020-09-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-01", "method": "animate"}, {"args": [["2020-09-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-02", "method": "animate"}, {"args": [["2020-09-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-03", "method": "animate"}, {"args": [["2020-09-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-04", "method": "animate"}, {"args": [["2020-09-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-05", "method": "animate"}, {"args": [["2020-09-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-06", "method": "animate"}, {"args": [["2020-09-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-07", "method": "animate"}, {"args": [["2020-09-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-08", "method": "animate"}, {"args": [["2020-09-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-09", "method": "animate"}, {"args": [["2020-09-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-10", "method": "animate"}, {"args": [["2020-09-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-11", "method": "animate"}, {"args": [["2020-09-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-12", "method": "animate"}, {"args": [["2020-09-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-13", "method": "animate"}, {"args": [["2020-09-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-14", "method": "animate"}, {"args": [["2020-09-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-15", "method": "animate"}, {"args": [["2020-09-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-16", "method": "animate"}, {"args": [["2020-09-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-17", "method": "animate"}, {"args": [["2020-09-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-18", "method": "animate"}, {"args": [["2020-09-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-19", "method": "animate"}, {"args": [["2020-09-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-20", "method": "animate"}, {"args": [["2020-09-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-21", "method": "animate"}, {"args": [["2020-09-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-22", "method": "animate"}, {"args": [["2020-09-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-23", "method": "animate"}, {"args": [["2020-09-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-24", "method": "animate"}, {"args": [["2020-09-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-25", "method": "animate"}, {"args": [["2020-09-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-26", "method": "animate"}, {"args": [["2020-09-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-27", "method": "animate"}, {"args": [["2020-09-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-28", "method": "animate"}, {"args": [["2020-09-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-29", "method": "animate"}, {"args": [["2020-09-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-09-30", "method": "animate"}, {"args": [["2020-10-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-01", "method": "animate"}, {"args": [["2020-10-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-02", "method": "animate"}, {"args": [["2020-10-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-03", "method": "animate"}, {"args": [["2020-10-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-04", "method": "animate"}, {"args": [["2020-10-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-05", "method": "animate"}, {"args": [["2020-10-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-06", "method": "animate"}, {"args": [["2020-10-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-07", "method": "animate"}, {"args": [["2020-10-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-08", "method": "animate"}, {"args": [["2020-10-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-09", "method": "animate"}, {"args": [["2020-10-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-10", "method": "animate"}, {"args": [["2020-10-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-11", "method": "animate"}, {"args": [["2020-10-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-12", "method": "animate"}, {"args": [["2020-10-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-13", "method": "animate"}, {"args": [["2020-10-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-14", "method": "animate"}, {"args": [["2020-10-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-15", "method": "animate"}, {"args": [["2020-10-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-16", "method": "animate"}, {"args": [["2020-10-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-17", "method": "animate"}, {"args": [["2020-10-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-18", "method": "animate"}, {"args": [["2020-10-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-19", "method": "animate"}, {"args": [["2020-10-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-20", "method": "animate"}, {"args": [["2020-10-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-21", "method": "animate"}, {"args": [["2020-10-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-22", "method": "animate"}, {"args": [["2020-10-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-23", "method": "animate"}, {"args": [["2020-10-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-24", "method": "animate"}, {"args": [["2020-10-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-25", "method": "animate"}, {"args": [["2020-10-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-26", "method": "animate"}, {"args": [["2020-10-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-27", "method": "animate"}, {"args": [["2020-10-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-28", "method": "animate"}, {"args": [["2020-10-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-29", "method": "animate"}, {"args": [["2020-10-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-30", "method": "animate"}, {"args": [["2020-10-31"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-10-31", "method": "animate"}, {"args": [["2020-11-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-01", "method": "animate"}, {"args": [["2020-11-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-02", "method": "animate"}, {"args": [["2020-11-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-03", "method": "animate"}, {"args": [["2020-11-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-04", "method": "animate"}, {"args": [["2020-11-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-05", "method": "animate"}, {"args": [["2020-11-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-06", "method": "animate"}, {"args": [["2020-11-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-07", "method": "animate"}, {"args": [["2020-11-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-08", "method": "animate"}, {"args": [["2020-11-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-09", "method": "animate"}, {"args": [["2020-11-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-10", "method": "animate"}, {"args": [["2020-11-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-11", "method": "animate"}, {"args": [["2020-11-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-12", "method": "animate"}, {"args": [["2020-11-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-13", "method": "animate"}, {"args": [["2020-11-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-14", "method": "animate"}, {"args": [["2020-11-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-15", "method": "animate"}, {"args": [["2020-11-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-16", "method": "animate"}, {"args": [["2020-11-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-17", "method": "animate"}, {"args": [["2020-11-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-18", "method": "animate"}, {"args": [["2020-11-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-19", "method": "animate"}, {"args": [["2020-11-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-20", "method": "animate"}, {"args": [["2020-11-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-21", "method": "animate"}, {"args": [["2020-11-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-22", "method": "animate"}, {"args": [["2020-11-23"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-23", "method": "animate"}, {"args": [["2020-11-24"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-24", "method": "animate"}, {"args": [["2020-11-25"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-25", "method": "animate"}, {"args": [["2020-11-26"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-26", "method": "animate"}, {"args": [["2020-11-27"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-27", "method": "animate"}, {"args": [["2020-11-28"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-28", "method": "animate"}, {"args": [["2020-11-29"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-29", "method": "animate"}, {"args": [["2020-11-30"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-11-30", "method": "animate"}, {"args": [["2020-12-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-12-01", "method": "animate"}, {"args": [["2020-12-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-12-02", "method": "animate"}, {"args": [["2020-12-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-12-03", "method": "animate"}, {"args": [["2020-12-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-12-04", "method": "animate"}, {"args": [["2020-12-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-12-05", "method": "animate"}, {"args": [["2020-01-22"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-22", "method": "animate"}, {"args": [["2020-01-01"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-01", "method": "animate"}, {"args": [["2020-01-02"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-02", "method": "animate"}, {"args": [["2020-01-03"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-03", "method": "animate"}, {"args": [["2020-01-04"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-04", "method": "animate"}, {"args": [["2020-01-05"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-05", "method": "animate"}, {"args": [["2020-01-06"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-06", "method": "animate"}, {"args": [["2020-01-07"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-07", "method": "animate"}, {"args": [["2020-01-08"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-08", "method": "animate"}, {"args": [["2020-01-09"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-09", "method": "animate"}, {"args": [["2020-01-10"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-10", "method": "animate"}, {"args": [["2020-01-11"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-11", "method": "animate"}, {"args": [["2020-01-12"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-12", "method": "animate"}, {"args": [["2020-01-13"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-13", "method": "animate"}, {"args": [["2020-01-14"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-14", "method": "animate"}, {"args": [["2020-01-15"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-15", "method": "animate"}, {"args": [["2020-01-16"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-16", "method": "animate"}, {"args": [["2020-01-17"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-17", "method": "animate"}, {"args": [["2020-01-18"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-18", "method": "animate"}, {"args": [["2020-01-19"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-19", "method": "animate"}, {"args": [["2020-01-20"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-20", "method": "animate"}, {"args": [["2020-01-21"], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "2020-01-21", "method": "animate"}], "x": 0.1, "xanchor": "left", "y": 0, "yanchor": "top"}], "template": {"data": {"bar": [{"error_x": {"color": "#2a3f5f"}, "error_y": {"color": "#2a3f5f"}, "marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "bar"}], "barpolar": [{"marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "barpolar"}], "carpet": [{"aaxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "baxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "type": "carpet"}], "choropleth": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "choropleth"}], "contour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "contour"}], "contourcarpet": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "contourcarpet"}], "heatmap": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmap"}], "heatmapgl": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmapgl"}], "histogram": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "histogram"}], "histogram2d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2d"}], "histogram2dcontour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2dcontour"}], "mesh3d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "mesh3d"}], "parcoords": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "parcoords"}], "pie": [{"automargin": true, "type": "pie"}], "scatter": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter"}], "scatter3d": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter3d"}], "scattercarpet": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattercarpet"}], "scattergeo": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergeo"}], "scattergl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergl"}], "scattermapbox": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattermapbox"}], "scatterpolar": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolar"}], "scatterpolargl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolargl"}], "scatterternary": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterternary"}], "surface": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "surface"}], "table": [{"cells": {"fill": {"color": "#EBF0F8"}, "line": {"color": "white"}}, "header": {"fill": {"color": "#C8D4E3"}, "line": {"color": "white"}}, "type": "table"}]}, "layout": {"annotationdefaults": {"arrowcolor": "#2a3f5f", "arrowhead": 0, "arrowwidth": 1}, "autotypenumbers": "strict", "coloraxis": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "colorscale": {"diverging": [[0, "#8e0152"], [0.1, "#c51b7d"], [0.2, "#de77ae"], [0.3, "#f1b6da"], [0.4, "#fde0ef"], [0.5, "#f7f7f7"], [0.6, "#e6f5d0"], [0.7, "#b8e186"], [0.8, "#7fbc41"], [0.9, "#4d9221"], [1, "#276419"]], "sequential": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "sequentialminus": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]]}, "colorway": ["#636efa", "#EF553B", "#00cc96", "#ab63fa", "#FFA15A", "#19d3f3", "#FF6692", "#B6E880", "#FF97FF", "#FECB52"], "font": {"color": "#2a3f5f"}, "geo": {"bgcolor": "white", "lakecolor": "white", "landcolor": "#E5ECF6", "showlakes": true, "showland": true, "subunitcolor": "white"}, "hoverlabel": {"align": "left"}, "hovermode": "closest", "mapbox": {"style": "light"}, "paper_bgcolor": "white", "plot_bgcolor": "#E5ECF6", "polar": {"angularaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "radialaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "scene": {"xaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "yaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "zaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}}, "shapedefaults": {"line": {"color": "#2a3f5f"}}, "ternary": {"aaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "baxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "caxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "title": {"x": 0.05}, "xaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}, "yaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}}}, "updatemenus": [{"buttons": [{"args": [null, {"frame": {"duration": 500, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 500, "easing": "linear"}}], "label": "&#9654;", "method": "animate"}, {"args": [[null], {"frame": {"duration": 0, "redraw": true}, "fromcurrent": true, "mode": "immediate", "transition": {"duration": 0, "easing": "linear"}}], "label": "&#9724;", "method": "animate"}], "direction": "left", "pad": {"r": 10, "t": 70}, "showactive": false, "type": "buttons", "x": 0.1, "xanchor": "right", "y": 0, "yanchor": "top"}]},                        {"responsive": true}                    ).then(function(){
                        }).then(function(){
                            
var gd = document.getElementById('e78f72c9-a015-456b-b859-5ddb35909af4');
var x = new MutationObserver(function (mutations, observer) {{
        var display = window.getComputedStyle(gd).display;
        if (!display || display === 'none') {{
            console.log([gd, 'removed!']);
            Plotly.purge(gd);
            observer.disconnect();
        }}
}});

// Listen for the removal of the full notebook cells
var notebookContainer = gd.closest('#notebook-container');
if (notebookContainer) {{
    x.observe(notebookContainer, {childList: true});
}}

// Listen for the clearing of the current output cell
var outputEl = gd.closest('.output');
if (outputEl) {{
    x.observe(outputEl, {childList: true});
}}

                        })                };                });            </script>        </div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>It is clear that though China starts off as the highest number of cases, over time it significantly decreases quickly posssibly because they were in lockdown for awhile. Next, America, Brazil, and India definitely slowly begin to increase and then around April it begins to increase quite rapidly everywhere and it stays quite high with a total number of cases everywhere. America definitely seems to be on the higher part of the spectrum.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>So now we have seen how the continents compare. Let's be more specific and look at a smaller (yet still big) sample: North America. So to begin with, we will look at North America's timeline. Using this timeline, we will run regression models on it to see which fits the best.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#extracting data for north america from the worldwide data</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;continent&#39;</span><span class="p">],</span> <span class="n">as_index</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">North_America</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="s1">&#39;North America&#39;</span><span class="p">)</span>

<span class="c1">#so let&#39;s plot the average monthly total cases</span>
<span class="n">North_America_means</span> <span class="o">=</span> <span class="n">North_America</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">6</span><span class="p">,</span> <span class="mi">7</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">9</span><span class="p">,</span> <span class="mi">10</span><span class="p">,</span> <span class="mi">11</span><span class="p">,</span> <span class="mi">12</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">],</span> <span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">])</span>

<span class="c1">#now, using this, we can find a regression curve to predict.</span>
<span class="c1">#Except how do we know which regression to use?</span>
<span class="c1">#let&#39;s try a couple:</span>

<span class="c1">#first we define our variables, x as the month, y as the total cases</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">])</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="p">(</span><span class="n">x</span><span class="o">.</span><span class="n">size</span><span class="p">,</span> <span class="mi">1</span><span class="p">))</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">North_America_means</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">])</span>

<span class="c1">#Random Forest regression model</span>
<span class="n">reg</span> <span class="o">=</span> <span class="n">ensemble</span><span class="o">.</span><span class="n">RandomForestRegressor</span><span class="p">()</span>
<span class="n">reg</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span> 
<span class="n">curve</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">curve</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Random Forest&quot;</span><span class="p">)</span>

<span class="c1">#Linear SVM regression model</span>
<span class="n">reg</span> <span class="o">=</span> <span class="n">svm</span><span class="o">.</span><span class="n">LinearSVR</span><span class="p">()</span>
<span class="n">reg</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span> 
<span class="n">curve</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">curve</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Linear SVM&quot;</span><span class="p">)</span>

<span class="c1">#Linear regression model</span>
<span class="n">reg</span> <span class="o">=</span> <span class="n">lm</span><span class="o">.</span><span class="n">LinearRegression</span><span class="p">()</span>
<span class="n">reg</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">curve</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">curve</span><span class="p">,</span><span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Linear&quot;</span><span class="p">)</span>

<span class="c1">#Decision tree regression model</span>
<span class="n">reg</span> <span class="o">=</span> <span class="n">tree</span><span class="o">.</span><span class="n">DecisionTreeRegressor</span><span class="p">()</span>
<span class="n">reg</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">curve</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">curve</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;Tree&quot;</span><span class="p">)</span>

<span class="c1">#then we will plot each and see which is the best predictor</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;month&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;# of total cases&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;average total case across time in North America&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[19]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.legend.Legend at 0x7f438037ecd0&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAZgAAAEWCAYAAABbgYH9AAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOzdd3xP1//A8dc7QxIziJnYe4SE2K0qSgeqSku1aLWKFq1N2x/V2lqrRmtXlX67KJ1U0apaFVRTqw0ykEQm2Tm/P+5NfETGJ5JPBuf5eOSRz+fcde5nve+959zzFqUUmqZpmpbX7Aq6ApqmadrdSQcYTdM0zSZ0gNE0TdNsQgcYTdM0zSZ0gNE0TdNsQgcYTdM0zSZ0gNEKJRHpJCIBBV2Pu5GIxIhI7XzYzkoRecvW28kNEfEXka4FXQ9r5dd7l1d0gNHuiIhMF5FPbDW/ljdEZI+IvGhZppQqqZT619bbVkoNV0q9cyfLmvWOE5FqFmVdRcT/TusjIutF5N07Xd5iPZ1ERInIxNyuK6fy673LKzrA3CVExKGg66DljH7PsnUdyJMzIBGxz4v1mAYD18z/+aLIflaUUvrPxn/AZOA8EA38DTxhljsBEUBTi3krALFARfN5D8DXnO93oJnFvP7AJOAEEA84ZLYtc3574D0gFPgPeBVQgIM5vQywBggGAoF3AfsM9udhIAFIBGKA42Z5VeAbjC/fOeClbOZ/HvAz6/ov8LLFNjoBAVm8pk2Anea2rgBTzfLWwAHz9QoGPgCKmdMEWAhcBSLN162pxXuxALhorm8l4JLJtusAu4Ew87XcBLhaTK8GfAWEmPN8YJYPAfabdbhmvr5lgI/NeS8AbwJ25vx1gb1mXUOBz7Lbj3T1nAkkA3Hm655aDwXUNR+vB5YD35vz7AcqA4uAcOAfwNtinVWBL836/geMzuI9Wg+8a/l+AuPMegcDz2ex7B5gmvnZSK1rV8DfYp5G5nwRwCmgV7ptrwC+wwhUwzA+fwnmfm63+A6NN1/DSOAzwDmLehU369TfXJePxbSa5mv7PHDJfP2GA63M9UekvgcWy7yA8R0IB34EalhMU8ArwFngvwzeOxeM7/MFs+6/YX5mgc+By2b5PqBJgfz2FcRG77U/oJ/5xbQDnjY/8FXMaWuBmRbzvgL8YD5uYX4Z22AEh8HmF8LJnO6PEXyqWXywstrWcIyg4wGUBXZxa4DZCnwIlAAqAoew+NFPt0/TgU/Sle3F+LFyBrwwfoS6ZDH/Yxg/1gI8ANwAWpjTOpFJgAFKYfxAjTO3VQpoY05rCbTFCLY1zS/va+a07sBRwNXcZiOL12YRRnAsZ65vOzA7k+3XBR7CCEoVzC/wInOaPXAcIwCUMOt3nzltCJAEjDLr54IRXLaZ26wJnAGGmvNvBt4w30vL9WS6HxnUdQ/wYrqy9AEm1HzdnDEC53/AIHNf3gV+Mee1M7f7f0AxoDbGgUH3TLa9nlsDTBIwA3AEHjXf77JZ1Rt4P/Vzg0WAMddxDphq1qUzxg9/A4ttRwIdLF6/tPpYbMcf43Ne1Xzv/YDhWXyXn8P47Nmbn5ElFtNqmq/tSnN73TCC+1aM75M7xvf5AXP+3uY+NDI/D28Cv6d7n3aa9XJRt793y8zXyd2sT3tu/ja8gPGZcsL4bPsWyG9fQWz0Xv/DCAqPm4+7Av9aTNsPDDIfrwDeSbfsaYsPqD/wQg62tZtbzxK6mh9YB6ASxlmQi8X0AZg/LhmsdzoWAQMjyCUDpSzKZgPrM5o/k3VuBcaYjzuReYAZAByz8rV+DfjafNwZ4we8LeZZglkuGIG4jkVZO8yjRiu20Tu1PuZyIZhBO918Q4CLFs/tzde8sUXZy8Ae8/HHwEeAR7r1ZLgfmdRtD9kHmFUW00YBfhbPPYEI83Eby/qbZVOAdZlsez23BphYy9cF48e2bVb1xgjgkRhnrJYB5n6MI3TL93EzMN1i2x9nVh+LMn/gWYvn84CVWbyeu7h5MDHAfK8dzec1zdfW3WL+MOBpi+dfcvOA53vMgwnzuR1G0K1h8T51zui9M+eNBZpb8fl0NZcrY83nOS//dBtMPhCRQSLiKyIRIhIBNAXczMm7ARcRaSMiNTCO/L82p9UAxqUuZy5bDeNoK9WlHGyrarr5LR/XwDgqDLZY9kOMIy9rVAWuKaWiLcouYBxdZUhEHhGRP0Tkmrm9Ry3qmpVqGJcBM1pnfRHZISKXRSQKmJW6TqXUboxLZsuAKyLykYiUxvgRKw4ctdj3H8zyjLZRUUS2iEiguY1PLOpdDbiglErKpO6Wr7kbxtH3BYsyy9dsIkbwOyQip0TkhWz2405dsXgcm8HzkubjGkDVdJ/HqRgHJ9YIS/e63LBYd4aUUiEY+zoj3aSqwCWlVIpFWfrP2yWsc9maOpkdDh7EuCQKxpmnM8aZuKWcvJ6LLV7LaxjvtzX74GZu+7bvgYjYi8gcETlvfj79LZbJVzrA2JgZNFZhtHeUV0q5An9hfJAwvyD/wzgaegbYYfEjfQnj8pmrxV9xpdRmi00oa7eFcWrvYbFsNYvHlzCOpt0stlVaKdUkk11T6Z4HAeVEpJRFWXWMtpzb5hcRJ4yjuQVAJbOu31nUNSuXMC6tZWQFRrtBPaVUaYwfwLR1KqWWKKVaYhwR1wcmYFwiisW4Tp2672WUUpn9+M0296eZuY1nLbZxCaieRaOs5esQitEuUMOiLO01U0pdVkq9pJSqinFms1xE6maxH9ltL7cuYZzVWX4eSymlHs3DbWRkPsYPe0uLsiCgmohY/oZZft7g9n3P7WvxHMZv5nYRuYxxedAZ43LinbiEcUXB8vV0UUr9bjFPZnUOxbj8ltH34BngcYwzvjIYZ1Zg3XcrT+kAY3slMD4kIQAi8jzGWYWlTzHaSwaaj1OtAoabZzciIiVE5LF0P+I52db/gDEi4i4irhgdBABQSgUDPwHviUhpEbETkToi8kAm27oC1Ez9giulLmF0QpgtIs4i0gwYys2jvVvmxzhydzLrmiQij2Bcs7bGDqCyiLwmIk4iUkpE2pjTSgFRQIyINARGpC4kIq3M19IR45JYHJBsBvlVwEIRqWjO6y4i3TPZfimMhuIIEXHn1h/3QxiBfI75fjmLSIeMVqKUSsZ4T2aa+1ADGItxRoSI9BOR1AOCcIz3Njmz/cikrlcw2krywiEgSkQmiYiLeaTcVERa5dH6M6SUisBozLbsFnwQY98nioijiHQCegJbslhVbl+LQcDbGFcZUv+eBB4TkfJ3sL6VwBQRaQIgImVEpJ81C5qf2bXA+yJS1Xwv2pkHbqUwDhbDMM7MZ91B3fKEDjA2ppT6G+PLcQDjA+6J0c5iOU/ql6UqxnXZ1PIjwEsYlwjCMRoEh+RiW6swgsgJ4BjGGUMSN3+cBmH88P9tbu8LoEomm/vc/B8mIn+ajwdgHC0FYVzmm6aU2pnR/OZZ2miMH9hwjKOubzLbt3T7GY3RyN4T4/LGWYwjXDB6BD2D0eC7CqNXUKrSZlk4xuWUMIwzKDCC7TngD/Oywi6gQSZVeBujA0Yk8C1Gj7HUuiWb9aqL0SMtAOPgITOjMN77fzF6AX2K8cMBRu+jgyISg/HajFFK/ZfNfqS3GOgrIuEisiSLemTLYt+8MDoChAKrMY6SbW0xFkFUKZUA9AIeMeuxHKPt8p8s1rEGaGxektqak42LSFuMz/Yy88wy9e8bjM/NgBztjbEPXwNzgS3mZ+4vc3+sNR44CRzGuLw2F+M3/WOMz0Ugxnf5j5zWLa+I2Qik3YPMs4aVSqka2c6saZqWQ/oM5h5iXtZ4VEQczEs707jZoUDTNC1P6TOYe4iIFMe4V6UhRqP2txiXXaIKtGKapt2VdIDRNE3TbEJfItM0TdNsomgOoGYDbm5uqmbNmgVdDU3TtCLl6NGjoUqpDG9K1gHGVLNmTY4cOVLQ1dA0TStSRORCZtP0JTJN0zTNJnSA0TRN02xCBxhN0zTNJnQbTBYSExMJCAggLi6uoKui5YCzszMeHh44OjoWdFU07Z6mA0wWAgICKFWqFDVr1kQk3wci1e6AUoqwsDACAgKoVatWQVdH0+5pOsBkIS4uTgeXIkZEKF++PCEhIQVdFU0r9LYeC2T+j6cJioilqqsLE7o3oLd3pimcckwHmGzo4FL06PdM07K39VggU746SWyiMUh1YEQsU746CZBnQUY38muaphVCKiWFK/Pmk3DJ2sScOTP/x9NpwSVVbGIy8388nWfb0AGmkLO3t8fLy4umTZvSs2dPIiIi8mS969ev59VXX82TdVnq1KkTDRo0wMvLCy8vL7744os83waAv78/n376afYzaloRFfbRR1xbu5br+3/PfuY7EBQRm6PyO6EDTCHn4uKCr68vf/31F+XKlWPZsmUFXaVsbdq0CV9fX3x9fenbt69VyyQlZZbCPmM6wGh3s+sHDhCyZCmle/TA9emnbLKNqq4uOSq/EzrAFCHt2rUjMNBIOX7o0CHat2+Pt7c37du35/Rp47R2/fr19OnTh4cffph69eoxceLNLLPr1q2jfv36PPDAA+zffzPR5YULF+jSpQvNmjWjS5cuXLx4EYAhQ4YwYsQIHnzwQWrXrs3evXt54YUXaNSoEUOGDLG63teuXaN37940a9aMtm3bcuLECQCmT5/OsGHD6NatG4MGDSIkJIQnn3ySVq1a0apVq7Q67t27N+2MyNvbm+joaCZPnsyvv/6Kl5cXCxcuzNXrqmmFSeKVKwSOG0+x2rWoMuNtm7UpTujeABdH+1vKXBztmdA9s0SuOacb+a309vZT/B2Ut2lTGlctzbSeTayaNzk5mZ9//pmhQ4cC0LBhQ/bt24eDgwO7du1i6tSpfPnllwD4+vpy7NgxnJycaNCgAaNGjcLBwYFp06Zx9OhRypQpw4MPPoi3tzcAr776KoMGDWLw4MGsXbuW0aNHs3WrkVE2PDyc3bt3880339CzZ0/279/P6tWradWqFb6+vnh5ed1W14EDB+LiYhwF/fzzz0yfPh1vb2+2bt3K7t27GTRoEL6+vgAcPXqU3377DRcXF5555hlef/117rvvPi5evEj37t3x8/NjwYIFLFu2jA4dOhATE4OzszNz5sxhwYIF7NixI3dvgqYVIioxkcDXXkfFxeGxZAl2xYvbbFupDfm6F9k9LDY2Fi8vL/z9/WnZsiUPPfQQAJGRkQwePJizZ88iIiQmJqYt06VLF8qUMdKkN27cmAsXLhAaGkqnTp2oUMEY9PTpp5/mzJkzABw4cICvvjLSyj/33HO3nPX07NkTEcHT05NKlSrh6ekJQJMmTfD3988wwGzatAkfH5+057/99lta8OvcuTNhYWFERkYC0KtXr7RgtGvXLv7++++05aKiooiOjqZDhw6MHTuWgQMH0qdPHzw8PHLzkmpaoXV1wQJijx3DfeH7ONWubfPt9fZ2z9OAkp4OMFay9kwjr6W2wURGRtKjRw+WLVvG6NGjeeutt3jwwQf5+uuv8ff3p1OnTmnLODk5pT22t7dPa9+w9lTbcr7UddnZ2d2yXjs7O6vbTTJKape6jRIlSqSVpaSkcODAgbSAk2ry5Mk89thjfPfdd7Rt25Zdu3ZZtV1NK0qifviBaxs+puxzz1H6kUcKujp5QrfBFBFlypRhyZIlLFiwgMTERCIjI3F3N4481q9fn+3ybdq0Yc+ePYSFhZGYmMjnn3+eNq19+/Zs2bIFMM4+7rvvvjyte8eOHdm0aRMAe/bswc3NjdKlS982X7du3fjggw/SnqdeRjt//jyenp5MmjQJHx8f/vnnH0qVKkV0dHSe1lPTCkr8v/8RPPUNXLy8qDRhfEFXJ8/oAFOEeHt707x5c7Zs2cLEiROZMmUKHTp0IDk5Odtlq1SpwvTp02nXrh1du3alRYsWadOWLFnCunXraNasGRs3bmTx4sV5Wu/p06dz5MgRmjVrxuTJk9mwYUOG8y1ZsiRtvsaNG7Ny5UoAFi1aRNOmTWnevDkuLi488sgjNGvWDAcHB5o3b64b+bUiLeXGDQLHjEacnHBftBApVqygq5RnJKPLF/ciHx8flT7hmJ+fH40aNSqgGmm5od87rShQShE0aRJR23dQbfUqSnboUNBVyjEROaqU8slomj6D0TRNKyARn31G1DfbcRv1apEMLtnRAUbTNK0AxJ78iyszZ1Gi4/24DR9e0NWxCR1gNE3T8llSeDiBY8ZgX8GNqnPnInZ350/x3blXmqZphZRKSSFo0iSSQkLwWLwYh7JlM53304MXiYpLzHR6YacDjKZpWj4KXbmS6/t+pdLUKbiYNy5nZMPv/kz9+iSf/HEhH2uXt3SA0TRNyycx+/cTuvQDSvfsiWv//pnO97PfFd7efoqujSrxcsc6+VjDvKUDTCFXsmTJ28pWrlzJxx9/nK/12LFjR9p9OI0bN+bDDz9kz549tGvX7pb5kpKSqFSpEsHBwQwZMoTixYvfckPkmDFjEBFCQ0Pztf6aVtASg4MJGj8Bp7p1qPL29ExH1vgrMJJRm4/RuGpplgzwwt6u6CbQ00PFFEHDbdzjRCmFUgo7s+ExMTGRYcOGcejQITw8PIiPj8ff35969eoREBCAv78/NWvWBIzxxJo2bUqVKlUAqFu3Ltu2bePZZ58lJSWFX375JW0EAk27V6iEBGMQy/h43BdnPohlcGQsQzccxtXFkbWDW1G8WNH+idZnMEXQ9OnTWbBgAWAk+Jo0aRKtW7emfv36/Prrr4Ax+vKECRNo1aoVzZo148MPPwQgJiaGLl260KJFCzw9Pdm2bRtg5Fdp1KgRI0eOpEWLFlyyyKIXHR1NUlIS5cuXB0gbpdnOzo5+/frx2Wefpc27ZcsWBgwYkPZ8wIABadP37NlDhw4dcHAo2l8aTcupK/MXEHv8OFVmzcSpdq0M54mJT+L5dYe5Hp/M2udbUbG0cz7XMu/pb7q1vp8Ml0/m7Tore8Ijc3K9mqSkJA4dOsR3333H22+/za5du1izZg1lypTh8OHDxMfH06FDB7p160a1atX4+uuvKV26NKGhobRt25ZevXoBcPr0adatW8fy5ctvWX+5cuXo1asXNWrUoEuXLvTo0YMBAwZgZ2fHgAEDGDZsGJMmTSI+Pp7vvvvulqFb6tWrx7Zt2wgPD2fz5s08++yzfP/997neZ00rKqK++47wjRspO+g5Sj/8cIbzJCWn8MqmPzl7NYZ1Q1rRsPLtY/UVRTrA3AX69OkDQMuWLfH39wfgp59+4sSJE2kpiyMjIzl79iweHh5MnTqVffv2YWdnR2BgIFeuXAGgRo0atG3bNsNtrF69mpMnT7Jr1y4WLFjAzp07Wb9+Pa1atSImJobTp0/j5+dH27ZtKZuu22WfPn3YsmULBw8eTDuT0rR7Qfy//xL85lu4eHtTaXzGg1gqpZj2zSn2nglhdh9POtavkM+1tB0dYKyVB2catpI6jL7l0PxKKZYuXUr37t1vmXf9+vWEhIRw9OhRHB0dqVmzJnFxccCtQ+dnxNPTE09PT5577jlq1aqVNopz//792bJlC35+frdcHkvVv39/WrRoweDBg9PadTTtbpdy/ToBo0cjzs5ZDmK5+tf/2HTwIsMfqMOA1tXzuZa2pb/td6nu3buzYsWKtERkZ86c4fr160RGRlKxYkUcHR355ZdfuHAh+z72MTEx7NmzJ+25r68vNWrUSHs+YMAAPvnkE3bv3p12uc1S9erVmTlzJiNHjsz9jmlaEaCUInjadBL+/Q/39xbgWKlShvN9fzKYWd/78ZhnFSbmYariwkKfwRRyN27cuCWD49ixY61a7sUXX8Tf358WLVqglKJChQps3bqVgQMH0rNnT3x8fPDy8qJhw4bZrkspxbx583j55ZdxcXGhRIkSt+Sgady4McWLF6dly5aZngW9/PLLVtVb0+4G4Zs3E7VjBxVeG0OJdF35Ux27GM5rn/niVc2V955qjl0R7o6cGT1cv0kP13930e+dVlBiT5zAf+CzlGzfHo8VyzMcZ+zStRs8sXw/LsXs+XpkB9xKOmWwpqIhq+H69RmMpmlaHkkKDyfgtddwrFiRqnPnZBhcImMTeX79YRKTFVuGtC7SwSU7Nm2DERFXEflCRP4RET8RaSci5URkp4icNf+XtZh/ioicE5HTItLdoryliJw0py0R8xZYEXESkc/M8oMiUtNimcHmNs6KyGBb7qemaZpKSSFo4iSSQ0JxX7QIe1fX2+ZJSEphxCdHuRB2nZXPtqRuxdtH6rib2LqRfzHwg1KqIdAc8AMmAz8rpeoBP5vPEZHGQH+gCfAwsFxE7M31rACGAfXMv9TO5EOBcKVUXWAhMNdcVzlgGtAGaA1MswxkmqZpeS10xQqu//orld54AxfPprdNV0rxxtcn+f18GHP6NKNdnfIFUMv8ZbMAIyKlgY7AGgClVIJSKgJ4HEhNyr4B6G0+fhzYopSKV0r9B5wDWotIFaC0UuqAMhqMPk63TOq6vgC6mGc33YGdSqlrSqlwYCc3g5KmaVqeivltP6EfLKPM471wffqpDOdZ9ss5Pj8awJgu9XiypUeG89xtbHkGUxsIAdaJyDERWS0iJYBKSqlgAPN/RXN+d+CSxfIBZpm7+Th9+S3LKKWSgEigfBbruoWIDBORIyJyJCQkJDf7qmnaPSoxKIig8eNxqluXytMzHsRym28gC346wxPe7rzWtV4B1LJg2DLAOAAtgBVKKW/gOublsExk1EdPZVF+p8vcLFDqI6WUj1LKp0KFu+fuWU3T8odKSCDg9ddRiYm4L1mMnYvLbfMc9r/GhM9P0LpWOeY86ZnpKMp3I1sGmAAgQCl10Hz+BUbAuWJe9sL8f9Vi/moWy3sAQWa5RwbltywjIg5AGeBaFusqcgrLcP2apt3uytx5xB0/QZWZM3Gqdfsglv+FXmfYx0fwKOvCR8+1xMnBPoO1ZGzrsUA6zNlNrcnf0mHObrYeC8zLqucLmwUYpdRl4JKIpN6e2gX4G/gGSO3VNRjYZj7+Buhv9gyrhdGYf8i8jBYtIm3N9pVB6ZZJXVdfYLfZTvMj0E1EypqN+93MsrvC8OHDGTRokM3Wr5QiJSXFZuvXtLtB5LffEr5pE+UGD6b0w91vmx5+PYEX1h9GRFj3fCtci2c8VExGth4LZMpXJwmOPY+SRAIjYpny1ckiF2Rs3YtsFLBJRE4AXsAsYA7wkIicBR4yn6OUOgX8DyMI/QC8opRKNtczAliN0fB/HkgdjncNUF5EzgFjMS/BKaWuAe8Ah82/GWbZXSG/h+vXNO1W8efPE/zW/+HSogUVx4+7fXpSMsM2HiEwIpZVg1pSo3zW4/ylN++nP0kp/yXFay2lWNnfAYhNTGb+j6fzpP75xaY3WiqlfIGM7vDsksn8M4GZGZQfAW7r96eUigP6ZbKutcDanNQ3K3MPzeWfa//k1eoAaFiuIZNaT8r1emw9XL+maTephAQCx0/AzskJ94XvI46Ot05XiolfnOCwfzgfPONNyxrlrF53ckoyX579kii393C0jyMxvB0JEa3TpgdFxObZfuQHfSf/XSA/huvXNM0QsnQp8X5+eCxfluEglu/vPMM23yAmPtyAHs2qWr1e36u+zDo4C79rfjgk1yXqYg9S4ivfMk9V19s7ERRmOsBYKS/ONGwlv4br17R73Y3DhwlbvQbXfv0o1bnzbdM/P3KJpbvP8bRPNUY8UMeqdYbGhrLo6CK2nd9GRZeKzOs4j7hwT6Ze+otYktPmc3G0Z0IRG3FZB5i7VOpw/Z07d8bR0ZEzZ87g7u5+R8P1a5oGydHRBE6ahGP1alSafPsB5+/nQpny1Unur+fGu080zbY7cmJKIlv+2cJy3+XEJccxtOlQhjUbRnHH4lALRIT5P54mKCKWqq4uTOjegN7et93OV6jpAFPIFYbh+jVNgyvvvkvSlavU3PQJdunO9s9djeblT45Su0IJlg1sgaN91v2nDgUfYvah2ZyLOEcH9w5MbjWZmmVq3jJPb2/3IhdQ0tPD9Zv0cP13F/3eaXkp6vvvCXx9LG6vvEKFUa/eMi0kOp4nlu8nPimFr0e2x6Ns8UzXc/n6ZRYcWcCP/j/iXtKdSa0m0alapyJ986Uerl/TNO0OJV6+TPD0t3Fu3gy34bcmzotNSObFj48QGhPP/15ul2lwSUhOYMOpDaw6uYoUlcIrXq8wpMkQnB2c82MXCowOMJqmaZlQKSkETZmCSkjAfe7cW7okp6Qoxv7PlxMBEXz4bEuaedw+PD/AvoB9zD00l4vRF+lavSvjW43HvWTRvvRlLR1gNE3TMhG+cSM3DvxB5RlvU6xmzVumzf3hH77/6zJv9WhMtyaVb1v2UtQl5h6ey96AvdQqU4sPH/qQ9lXb51PNCwcdYDRN0zIQd+YMV997n5KdO+Pa79b7uTce8OfDff8yuF0NXuhQ85ZpNxJvsPrkatafWo+jnSPjWo5jYKOBONrfekPmvUAHGE3TtHRSEhIImjARu1KlqPLOjFsa4b85HsT/fXOKro0q8VaPxmnTlFLsvLCT+Ufmc/n6ZXrU7sHrLV+nYvGKmW3mrqcDjKZpWjohixYTf/o0HitX4FD+ZubJPaevMvYzX1rXLMcHz3jjYHZHPh9xntmHZnMw+CANyjZgzv1zaFmpZUFVv9DQAaYQCwsLo0sXY9i2y5cvY29vT2remkOHDlGsmPWjs2qaZp3rfxzk2rp1uPZ/mlKdOqWVH70QzohP/qR+pVKsGuyDs6M9MQkxrDi+gk/9PsXF0YU32rxB3/p9cbDTP62gA0yhVr58eXx9fQFjBOWSJUsyfvz4tOlJSUk4OOi3UNPySnJUFEFTplCsenUqTZyYVn7mSjQvrD9MpdJObHihNaWcHNh+fjvvHXmPa3HX6FOvD6NbjKacs/UDW94L9K9TETNkyBDKlSvHsWPHaNGiBSNHjuSVV14hJCSE4sWLs2rVKho2bEhISAjDhw/n4sWLACxatIgOHToUcO01rXC7POMdkq5epeaWzdgVN+5puXTtBs+tOYizox0bh7YhNOFfxn4/C98QX5q5NWNZl2U0cWtSwDUvnHSAsX36Y4UAACAASURBVNLlWbOI98vb4fqdGjWk8tSpOV7uzJkz7Nq1C3t7e7p06cLKlSupV68eBw8eZOTIkezevZsxY8bw+uuvc99993Hx4kW6d++On59fntZf0+4mkTu+JWrHDtxGj8LF0xMw7tJ/bs1B4hJTWPN8Y9affo/Pz3xOWeeyzGg/g8frPo6d2DqtVtGlA0wR1K9fP+zt7YmJieH333+nn0UXyvj4eAB27drF33//nVYeFRVFdHQ0pUqVyvf6alphlxgUxOW338bFywu3YcMAiIpLZMi6Q1yJimXoo1d57fcZxCTEMLDRQEZ4jaB0sdIFXOvCTwcYK93JmYatpA6rn5KSgqura1o7jaWUlBQOHDiAi0vRyh+haflNpaQQNHkKJCdTdd5cxMGBuMRkXtpwhLMRf1G3+U42nDmLTyUfprSZQv2y9Qu6ykWGPrcrwkqXLk2tWrX4/PPPAaMf/vHjxwHo1q0bH3zwQdq8GQUhTdPg2rr13Dh0iEpvTKVY9eokJafw8qd7OB6/Eqcay4lXkczvOJ+13dfq4JJDOsAUcZs2bWLNmjU0b96cJk2asG3bNgCWLFnCkSNHaNasGY0bN2blypUFXFNNK3zi/vmHkEWLKNm1C2X69CEhOYH+n83jaPIknMqcYGjToWzvvZ2Haz1cpEc8Lih6uH6THq7/7qLfOy07KfHx+PftS1JEBLW/+YajcWcY+/N0opID8HDyZsUjM27L0aLdTg/Xr2malk7I+wuJP3uOkkvmMOn4u/x04SdSEsrRvuw4PuwzCDs7fYEnt3SA0TTtnnP999+5tmEDQd2bMyVkJonJycSHPMRDVZ9maZ/W2Nnpy2F5QQeYbCil9LXXIkZf9tWykhwRwX8TxxFawZGJnn9Rv+T9HDranvtqNmDhUz46uOQhfQ6YBWdnZ8LCwvQPVhGilCIsLAxn57s7U6B2Zy5GXuTbkY+jrkXw2dOVGeG1gKOHetG8cm1WPNuCYg76JzEv6TOYLHh4eBAQEEBISEhBV0XLAWdnZzw8PAq6Glohkpqj5eyW1Yz8M5FLAzryUq93eW71UWq5lWDtkFYUL6Z/DvOafkWz4OjoSK1atQq6Gpqm3SHLHC1JQcEs2ik4eHlS++V5PLXqEGVLFOPjoa1xLa5HJrcFHWA0TbsrWeZoaVimPtP2l8TR7hIu/zeLp9YdwU5g49A2VCqtL6faig4wmqbdVWISYlh5fCWb/Dal5WjpvC+SsOOLKDn9HQZ9H0B0XBKbh7WllluJgq7uXS3bFi0RGSMipcWwRkT+FJFu+VE5TdM0a6WoFL45/w09t/bk478/5vG6j7PjiR30TmlG2NJluHR9iJGhlbkUHsuqwT40dS9T0FW+61lzBvOCUmqxiHQHKgDPA+uAn2xaM03TNCv5hfkx66CRo8XTzZOlnZfS1K0pKXFx/DdhIvaursxq+Dh/BUWx8tmWtK1dPvuVarlmTYBJ7RT+KLBOKXVc9I0hmqYVAhFxESw9tjTTHC1X33ufhPPn2fbMJH4KiGNBv+Y81LhSAdf63mFNgDkqIj8BtYApIlIKSLFttTRN0zKXnJLMl2e/ZMmxJZnmaIn5bT/hGzfi1/4RVt6owJuPNaJvS919PT9ZE2CGAl7Av0qpGyJSHuMymaZpWr7zverLrIOz8Lvml2mOlqTwcIKnTCG6cjUml+/IiE51ePH+2nmy/a3HApn/42mCImKp6urChO4N6O3tnifrvttYE2AU0BjoAcwASgC6X5+mafkqNDaUhUcX8s35b6hYvCLzO86ne83utw3lpJTi8rTpJFwLZ8r9o+jTtjYTuzfIkzpsPRbIlK9OEpuYDEBgRCxTvjoJoINMBqwJMMsxLol1xggw0cCXQCsb1kvTNA2AxJRENvttZsXxFcQlxzG06VCGNRtGccfiGc4f+dVXRP/0E+sbP0q9Di2Z+YRnno0nOP/H02nBJVVsYjLzfzytA0wGrAkwbZRSLUTkGIBSKlxE9G2vmqbZ3MHgg8w+OJvzkefp4N6Bya0mZ5qjRSUmEvLBMkI/+oi/3OoQ1P1J1g7wwj4PB68MiojNUfm9zpoAkygi9hiXyhCRCuhGfk3TbOjy9cvMPzyfny78hHtJd5Y8uIRO1TpleiaSEBBA4NhxxJ04wU81WvPrw4PYMKQ1Tg72eVqvqq4uBGYQTKq6uuTpdu4W1gSYJcDXQEURmQn0Bd60aa00TbsnJSQnsOHUBladXEWKSuEVr1cY0mQIzg6ZN/tGfvstQf83nbjEZBb6PItbr8fY8HhTSjrl/UAlE7o3uKUNBsDF0Z4JedTGc7fJ9h1QSm0SkaNAF4x7Ynorpfys3YB59nMECFRK9RCRcsBnQE3AH3hKKRVuzjsFo9daMjBaKfWjWd4SWA+4AN8BY5RSSkScgI+BlkAY8LRSyt9cZjA3A+G7SqkN1tZZ07T8ty9gH3MPzeVi9EW6Vu/K+FbjcS+ZebtGyvXrXJ45i8ivvuKMW03e7/Qco5/pyJM27Iqc2s6ie5FZJ9sAIyJ1gP+UUstEpBPwkIgEK6UirNzGGMAPSO2gPhn4WSk1R0Qmm88niUhjoD/QBKgK7BKR+kqpZGAFMAz4AyPAPAx8jxGMwpVSdUWkPzAXeNoMYtMAH4xLe0dF5JvUQKZpWuFxKeoScw/PZW/AXmqVqcWHD31I+6rts1wm9tQpAseNJ+HCBTbX78qxB59k3bM+1K5Q0ub17e3trgOKlazJrvMlkCwidYHVGDdcfmrNykXEA3jMXC7V40Dq2cQGoLdF+RalVLxS6j/gHNBaRKoApZVSB5SR+evjdMukrusLoIs5ykB3YKdS6poZVHZiBCVN0wqJG4k3WPLnEh7f9jiHLx9mXMtxfNnzyyyDi0pJIWz9evyf7k9ISAST2r+M/YvD+XLU/fkSXLScseYiZYpSKklE+gCLlVJLU3uUWWERMBEoZVFWSSkVDKCUChaRima5O8YZSqoAsyzRfJy+PHWZS+a6kkQkEihvWZ7BMmlEZBjGmRHVq1e3cpc0TcsNpRQ/XfiJBUcWcPn6ZXrU7sHrLV+nYvGKWS6XFBZG0JQpXN/3K4eqNmVVu2eYNrC9HvqlELO2F9kAYBDQ0yxzzG4hEekBXFVKHTUvrWW7SAZlKovyO13mZoFSHwEfAfj4+Oi8yJpmY+cjzjP74GwOXj5Ig7INmHv/XFpUapHtcjG/7Sdw0iQSIqNY2ewJQh7swefPeFOljO69VZhZE2CeB4YDM5VS/4lILeATK5brAPQSkUcx7vwvLSKfAFdEpIp59lIFuGrOHwBUs1jeAwgyyz0yKLdcJkBEHIAywDWzvFO6ZfZYUWdN02wgOiGaFcdXsNlvM8Udi/NGmzfoV78f9nZZdyNWCQlcXbyYa2vWEuRahXc7jqbnEx1Z3LkuDvbWXOHXCpIYzRo23ohxBjPe7EU2HwizaOQvp5SaKCJNMNp2WmM08v8M1FNKJYvIYWAUcBCjkX+pUuo7EXkF8FRKDTcb+fsopZ4yG/mPAqmHRn8CLZVS1zKro4+Pjzpy5IhN9l/T7lUpKoUd/+7g/SPvcy3uGn3q9WFMizGUdS6b7bIJ/v4Ejp9A3F9/8X2t9nzd7knmDWxDuzp6qP3CRESOKqV8MppmTS+yesBsjPHI0jqjK6XudOS4OcD/RGQocBHoZ67vlIj8D/gbSAJeMXuQAYzgZjfl780/gDXARhE5h3Hm0t9c1zUReQc4bM43I6vgomla3vs77G9mHZzF8ZDjNHNrxrIuy2ji1sSqZSO3bSP47RncSBEWtB6Mc+cubOvXnHIl9CAiRUm2ZzAi8htGl9+FGG0wz5vLTbN99fKPPoPRtLyRPkfL6y1fp1edXmk5WrKSHBPD5RkziPpmO6cr1mFuywG8+GR7XuhQM8/GE9PyVq7OYAAXpdTPIiJKqQvAdBH5FSPoaJqmAdblaMlK7MmTBI4dR0JAIJsadWN/2158NNAHTw+d2riosibAxImIHXBWRF4FAoGs+xNqmnZPsczR0qpyK6a0nkK9svWsWlalpHBt7VquLlxMRPEyvHvfCOp26cD23k0p5Zxth1WtELMmwLwGFAdGA+8ADwKDbVkpTdOKBmtztGQm8epVgidP5vrvBzhY3YsPvPsxqV8r+rb00JfE7gLWjEWW2lAeg85kqWkaN3O0LD++nPjkeF70fJGXPF/KNEdLRmL27iVw8hQSYq6zzKsv/m26smVgS+pW1Hfk3y2s6UW2E+iXOvaYiJTFGNKlu60rp2la4fNH8B/MOTjHqhwtGUlJSODqggWEf7yR4PLuTL9/KJ26t2HRo41wdszd8Po6nXHhYs0lMjfLgS3NhGO6DUbT7jHBMcEsOLLA6hwtGYn/9z8Cx40j3s+P7+rez6fevZj5tA8PN62c6/rpdMaFj1VjkYlIdaXURQARqUEGw65omnZ3ik+OZ8OpDaw+udrqHC3pqeRkrm3cSMiiJcTaOTCnzfMktb2Pbf298Chr/WW1rOh0xoWPNQHmDeA3EdlrPu+IOUCkpml3t72X9jL38FwuRV+yKkdLRuL8/Ah+6/+I++sv/qrWlLlNnqD/Iy15rWu9PB3uRaczLnysaeT/QURaAG0xBpF8XSkVavOaaZpWYC5GXWTu4bnsC9hndY6W9FJiYwldtoywdetJKVWaxe0HcaRmS5Y+04IOdd3yvM46nXHhY1VOUTOg7LBxXTRNK2A3Em+w+uRq1p9aj6OdI+NajmNgo4E42ufsfpTrBw4QPG06iRcvEnJ/N0aVuZ/K7hXZNtiHauXy5pJYejqdceGT90mrNU0rclJztMw/PJ8rN65YnaMlvaTwcK7OnUfk1q04Vq/Orpem8V5IKbo0rMjiAd6UdLLdT45OZ1z46ACjafe4c+HnmHNozs0cLR3n0rJSyxytQylF1I5vuTJ7NslRUZR8fihvlm7N3gvRvNyxNhMfboi9ne1vnNTpjAuXTAOMOeR9pvToxJpWtKXmaPnU71OKOxZnapup9KvfDwe7nB13JgYGEvz221zf9yvOnp7YvfcBg/dHcikghnl9m/GUT7XsV6LdlbL6JB0l6+yQdzpcv6ZpBShFpbD9/HYWHl2YlqNldIvRlHPO8pjyNio5mfBPPuHq4iUAVJo6Bb823Rmx2RcHezs2vdiW1rVytk7t7pJpgFFK1crPimiaZnu5ydFiKe6ff4yuxydPUuKBjlT5v/9jy6Ukpm84Sp0KJVgzuJXNGvO1osOqc2FzeJh63JpwbJ+tKqVpWt6KiItgybElfHHmC8o6l+WdDu9YnaPFUkpcHKHLlhO2di32rq64v/8eLt268863fnx84AIPNqjAkgHeehRkDbBuLLIXgTEYee19Me6HOQB0tm3VNE3LrdzmaLF0/Y8/CJ42jcQLFynzZB8qTZhAjFMJXthwhF/PhvLifbWY8mijfGnM14oGa85gxgCtgD+UUg+KSEPgbdtWS9O03MpNjhZLyRERXJk3n8ivvsKxRnWqr19PibZt+C/0OkPX7OfStRvMfdKTp1tVt8FeaEWZVQnHlFJxIoKIOCml/hERfeeSphVSuc3RkkopRdR333Fl1mySIyMpP2wYbiNHYOfszO/nQhmx6U/sBD4Z2oY2tcvbaG+0osyaABMgIq7AVmCniIQDQbatlqZpOZWYksinfp+y4viKO87RkrauoCCj6/HefTh7elJ97RqcGxjHlZsOXmDatlPUcjMa86uX1435WsasGYvsCfPhdBH5BSgDfG/TWmmaliN/BP/B7IOz+TfyX+5zv4/JrSdTo3SNHK9HJScTvmkTVxctBoyux2UHDkTs7UlKTuHdb/1Y/7s/nczG/NI5aMzXuVruPdY08m9USj0HoJTam1oGPGfjummalg3LHC0eJT1Y2nkpD3g8cEfphuNOnza6Hp84kdb12NHdCACRsYmM2nyMfWdCGHpfLabmsDFf52q5N1lzieyWTvIiYg/kbBwJTdPylGWOFqUUr3q9ypCmQ3Cyd8rxupRSXFu7lqsLF2FfpgxV31tA6UcfTQtS/qHXGbrhMBfCbjCnjyf9W+e8MV/nark3ZTVUzBRgKuAiIlHcvKM/AfgoH+qmaVoG9gXsY86hOVyKvsRDNR5ivM94qpasekfrUomJXJ4xg4jPv6DUww9TZfo07F1d06YfOB/GiE1HAdg4tA3t6txZY77O1XJvyupO/tnAbBGZrZSako910jQtA+lztHz00Ee0q9rujteXHB1N4JgxXP/9AG4jR+A2atQtl9Y2H7rIW1v/okb54qwZ3IqabiXueFs6V8u9yZpG/iki0gsjkyXAHqWUzg2jafnEMkdLMftijPcZzzMNn8lxjhZLCQGBXBr+MgkXLlJl9mxcn+idNi0pOYVZ3/3D2v3/0bF+BT54JmeN+RnRuVruTdY08s8GWgObzKIxItJBn9Vomm2l5mhZcGQBl69fpmftnrze8nUqFK+Qq/XGnjjBpREjUYmJVF+1ihJt26RNi4pLZNSnx9h7JoTnO9TkjUcb5UlaY52r5d4kSqmsZxA5AXgppVLM5/bAMaVUs3yoX77x8fFRR44cKehqaBoA5yPOM/vgbA5ePkjDcg2Z0noKLSq1yPV6o378iaCJE3GoUIFqH32IU+2bg6JfCLvO0A1H8A+9ztuPN2Fgm5x3c9buPSJyVCnlk9E0axM/uAKp+V/K5EmtNE27TWqOls1+mynuWJw327xJ3/p9sbezz9V603qKLXgPl+bN8Vi+DIdyN4fS//1cKK98+icpCj4e2pr2ddxyuyuaZlWAmQ0cM2+yFIy2mKk2rZWm3WPS52h5sv6TjPYeTVnnsrlet0pM5PI77xLxv/9R6pGHqTp7NnbOxsDoickpLNp1huV7zlPbrQSrB7eiVi4a8zXNkjWN/JtFZA/GgJcCTFJKXbZ1xTTtXnFLjpYKzVjWdRlNyuc8R0tGkqOjCXztda7v30/5YcOo8NoYxM5oU7l07QZjthzjz4sRPOXjwfReTSheTGdR1/KONY38PyulugDfZFCmadodyqscLZlJDAri0svDif/vP6rMfBfXJ59Mm/btiWAmf3UCFCwZ4E2v5nd2H42mZSWrGy2dgeKAm5lwLLWDfGlAfxo17Q5llKNlpNdIShUrlWfbiD35F5dGjkDFxVN91UeUaGfcLxObkMyMHafYfOgSXtVcWdLfWw9WqdlMVmcwLwOvYQSTo9wMMFHAMhvXS9PuSpY5WlpXbs3k1pPvKEdLVqJ37SJw/AQcypen2rp1ONWtC4BfcBSjNh/j3NUYhj9Qh3Hd6uOYB12QNS0zWd3JvxhYLCKjlFJL87FOmnbXsczRUql4JeY/MJ/uNXKeoyUrSimubdjA1bnzcPb0pNryZTi4uaGUYuMfF3j3Wz/KuDiycWhr7q+Xu3tpNM0a1jTy6+CiaXfIMkdLQnJCrnK0ZEUlJXFl1izCP91MqW7dqDp3DnYuLkTcSGDiFyf46e8rdGpQgQX9muNWMucDYmrandBdRjTNRvIqR0t2kmNiCBw7luv7fqX8i0OpMHYsYmfHwX/DeO0zX0Jj4nnzsUa80KEWdjkYYl/TciurRv4OSqn9Zprk+PyslKYVZcExwcw/Mp+dF3bmOkdLdhKDg7k0fATx585R+e23Kfv0UyQlp7B05xmW7j5L9XLF+WpEBzw99P3RWv7LqoVvifn/wJ2sWESqicgvIuInIqdEZIxZXk5EdorIWfN/WYtlpojIORE5LSLdLcpbishJc9oSMb+pIuIkIp+Z5QdFpKbFMoPNbZwVkcF3sg+alhPxyfF8dOIjem3txa8Bv/Kq16ts7b2VTtU62SS4xJ46hf9TT5MYEEC1Dz+k7NNPERQRyzOrDrL457P09nJnx+j7dXDRCkxWl8gSRWQd4C4iS9JPVEqNzmbdScA4pdSfIlIKOCoiO4EhwM9KqTkiMhmYDEwSkcZAf4wEZ1WBXSJSXymVDKwAhgF/AN8BD2OkbR4KhCul6opIf2Au8LSIlAOmAT6AMrf9jVIq3JoXRdNyau+lvcw5NIeAmIBc52ixRvTuXwgcNw77sq7U2PwpzvXr8+Opy0z84gRJySm8/1Rz+rTwsNn2Nc0aWQWYHkBXoDNGN+UcUUoFA8Hm42gR8QPcgceBTuZsG4A9wCSzfIt5Oe4/ETkHtBYRf6C0UuoAgIh8DPTGCDCPA9PNdX0BfGCe3XQHdiqlrpnL7MQISptzuh+alpW8ztFijWsfb+TK7Nk4N2mCx/JlJJctz1tb/2LjHxfwdC/D0gHeucrdoml5JatuyqHAFhHxU0odz81GzEtX3sBBoJIZfFBKBYtIRXM2d4wzlFQBZlmi+Th9eeoyl8x1JYlIJFDesjyDZSzrNQzjzIjq1XOeBla7d9kiR0t2VFISV2bPIXzTJkp27YL7vHmcj05m1LL9/HM5mpfur8WE7g0p5qDvbdEKB2t6kYWJyNdAB4zLTb8BY5RSAVkvZhCRksCXwGtKqagsrkVnNEFlUX6ny9wsUOojzPTPPj4+Wect0DRu5miZf3g+V25coUftHoxtOTbXOVqyk3L9OoFjxxGzdy/lnn+eCuPGsuVoEDN2nKJEMQfWPd+KBxtUzH5FGdh6LFDnadFswpoAsw74FOhnPn/WLHsouwVFxBEjuGxSSn1lFl8RkSrm2UsV4KpZHgBUs1jcAwgyyz0yKLdcJkBEHDBSCVwzyzulW2ZPdvXVtKycCz/H7EOzOXT5EA3LNWT+A/Pxruht8+0mXrli9BQ7fZrK0/4Pu959GfXZCb49Gcx9dd14/+nmVCzlfEfr3nos8JZMk4ERsUz56iSADjJarllzLl1RKbVOKZVk/q0Hsj1cM9tC1gB+Sqn3LSZ9A6T26hoMbLMo72/2DKsF1AMOmZfTokWkrbnOQemWSV1XX2C3MjKo/Qh0E5GyZi+1bmaZpuVYdEI08w7Po+/2vvxz7R/ebPMmWx7bki/BJWbvXv7r25fECxeotnIF/7bvzqOLf+XHU5eZ/EhDPn6h9R0HFzAyTFqmMQaITUxm/o+nc1t1TbPqDCZERJ7lZgP5ACDMiuU6AM8BJ0XE1yybCswB/iciQ4GLmGdGSqlTIvI/4G+MHmivmD3IAEYA6wEXjMb9783yNcBGs0PANYxeaCilronIO8Bhc74ZqQ3+mmYtW+ZoyXbb169zZd58Ij77DKd69ai8ajVrg+xY+OEfVHV15vPh7fCunvt6BEXE5qhc03LCmgDzAvABsBCjHeN3syxLSqnfyLgtBCDDof6VUjOBmRmUHwGaZlAex81Ld+mnrQXWZldPTcuILXO0ZOfGsWMETZpM4qVLlBv6Aur5lxn61d8c+DeMXs2r8u4TTSntnDedCaq6uhCYQTCp6uqSJ+vX7m3WjEV2EeiVD3XRtAJn6xwtWVEJCYQsX07YR6twrFyZ6uvX861dFWYu+4OEpBTm9W1Gv5YeeXrT5oTuDW5pgwFwcbRnQvcGebYN7d6lxyLTNPInR0tW4s+dI2jiJOL+/psyTzzBjZdHM/Sn//jj3xO0rlmO2U96UqdCyTzfbmpDvu5FptmCDjDaPS8/crRkRqWkEL5xI1ffex+7EiWotGgRGx1qs2zVMZwd7ZjTx5OnfKrZdJDK3t7uOqBoNqEDjHbPyo8cLVlJDAoiaOob3PjjD0p26sSVl8cx8pdAzl09Q8/mVXmrR6Nc9RDTtIKWbYARkTeVUu+aj/XIylqRlz5Hy0ueL/Gi54t5nqMlM0oporZv5/I776KSkynz1jSWOjdm82encXd1ydVNk5pWmGQ1XP9E4FeM+0veNYsPAC3yoV6aZhOWOVrud7+fya0nU710/g0TlBQezuW3ZxD9ww+4eHvjN2Qsbx2OIPxGAMM61ua1rvUoXkxfWNDuDll9kk9jdAGuLSK/An5AeRFpoJTSd2FpRUr6HC0fdP6AB6o9kK91iPn1V4KnvkFSRATFRrzKjJIt2f3LFTzdy7D++VY0ddfD6mt3l6wCTDjGjZGdzL9GGKMUTzaDTHub107Tcik+OZ4Npzaw6sQqAF71epUhTYfgZJ9/aYNTbtzgyvz5RGzeQrG6dfEd/hYz/klGwiJ4q0djBrergYO9HqBSu/tkFWAexsipUgd4HzgOXFdKPZ8fFdO03Eqfo2WCzwSqlKySr3WIPX6coImTSLh4kZR+zzCuXAd8T8bSpWFFZvRuiru+oVG7i2U1XP9UABE5DnyCMdx+BRH5DSPJV8/8qaKm5YxljpbaZWqzqtsq2lZpm691UImJhK5YQeiHH2FfsSJ7X57OvCslKH8jheUDW/BI08r51ltN0wqKNa2JPyqlDgOHRWSEUuo+EXGzdcU0LacyzNHS6Bkc7WyXoyUj8efPGzdNnjrFjQe7M6nKQ5y7DAPbVGfiww0p45K/9dG0gmLNUDETLZ4OMctCbVUhTcup9DlaetXpxWstXrN5jpbb6pGSQvgnm7j63nvg7MJ3/V5jaaIH9UqW5ItBnvjULJev9dG0gpaj/pC5zWypaXmtoHK0pJcYHEzQ1KncOPAHkc1bM75mD66qkozvVpdhHevccZZJnQxMK8p0h3utSIpOiGa573I2/7OZEo4leLPNm/St3xd7O/t8rYdSiqgd33J5xgxSkpLY1nkQK0t50q6OGx8/0ZTauRg/TCcD04o6HWC0IiU1R8v7R98nPC6cvvX7Msp7VL7kaLGklCL+9GlCP/yQ6O9/ILxmAyY16EN0+crMf7QRffNg1OOskoHpAKMVBTrAaEXGqbBTzDo4ixMhJ2heoTnLuy7PtxwtqRICAoja8S2RO7aTcO48ysGB7T69+LBqB3q3rM4bjzWifMm8ucdGJwPTijodYLRCzzJHSznncsy8byY9avfIlxwtAElhYUT98ANR23cQ62skZ42q35SfOw1ki0t9XKtUYMMTTbm/Xt52KtDJwLSiTgcYrdBKTknmizNfsOTYCMtpngAAEXlJREFUEq4nXufZxs8yovmIfMnRkhxznZjdPxO5fQfXf/8dkpNJqFGbgw8+zTqnugQ7l6VxldKMbuHOwDY1cCmW920/OhmYVtTpAKMVSseuHmPWwVn8c+0f2lRuw+TWk6lbtq5Nt6kSEoj5bT9RO7YTvfsXVFwcKZUq8/f9PVnv0oBTThWoWMqJ3t7uPOHtTqMqpW1aH50MTCvqdIDRCpWQGyEsPLqQ7f9up1LxSix4YAHdanSz2V3vKiWF2KNHidy+g6gffyQlMhJcXbnYqjOflWnEL/aVcCrmwMNNKjOphQcd6rphb8PkX+npZGBaUaYDjFYo5GeOltQeYJHbtxP17XckXb6MuLgQ5t2O7yo0Y4uqQoq9PW1rlWdeC3ce8axCSSf9VdG0nNLfGq3AHQg6wJxDc/g38l86enRkUqtJNsnRYvQA20Hkjh0knDsPDg7EebVib/snWZPiQTSO1KlQgrEtPOjt7Z7lQJT6BkhNy54OMFqBCYoJYsGRBey8sJNqparZJEdLUlgYUd//QNSOmz3AlKcXf/Z5iVVSiwvJxSjr7Eif5lXp08KDZh5lsr0cp2+A1DTr6ACj5bv45HjW/7We1SdXAzDKexSDmwzOsxwtKbGxRP9/e3ceHGWd53H8/c0FCVe4TEISAQGVUyJBGHHEVUF0LLzKXZ3ZXbfW0dpy1RnLc3bHKmt2d8ARHXW02GJQRx12rPXYgKAyCuMFImB0OWQBFSPBA3BiAkTSnfR3/+hWA5NAp488SfN5VaWSp/Mc31+n05/up5/n+b7yCvVLnv/2CLCskaP48JJ/4Mn8Ubzd2IM8y+Kc0cfx81PLmH7i4A5dykUnQIrERwEjncbdea32Ne5eeze1+2uZOXQmt1TekpIeLR6J0Lh+PfVVi9n30ktEGhvJHjKEvT+4nOf6j6OqoSfuMGlwf/69opQLJ5RQWJCX0LZ0AqRIfBQw0ilqGmq4e+3dvLHrjZT2aAnV1FC/eDH1i5cQ3rULKyhg39QzWXH8ZJ48UMiBsFOenc8NZ5dxSUUpwwf1SnqbOgFSJD4KGEmrxnAjv934Wx7f/Dh52XncWnkrV46+MqkeLS379tHw4ovUVy3m6+pqMOPghEmsmnIRj9lQvmzJpjCUy+yKYi49tYzKof1TepizToAUiY8CRtLC3Vn+8XLmrZ/3bY+WmybdxKD8xHrVeXMzB1avpr6qin0rVuJNTYRLj6f63Ct4NP9kPsnuTb8eucwaW8wFE0o4fcRActPU514nQIrERwEjKbe9bjtz1s5h3efrGD1gNPOmz2PicRMTWtfBrduor6qifunztOzZS6R3X7acMp3f9x3He71K6FeQx3lji/i3CUPSGiqH0wmQIkengJGUad2jpXdeb+6ceieXjbqswz1amr/8koZly/iqqoqm97fg2dnUjKrg6RNn88aAEynonc95Y4v46fgSpo0c1GmhIiIdo4CRpEU8wpIPl/Drd35N3cE6Lj/xcm6ouIHCnoXxryMUYv+fXqW+qor9b7wBzc3sGTKcpadewvKiU/B+hZw3tpgFE0qYNmJQwh0iRaTzKGAkKYf3aJl/7nzGDBwT17LuzsENG/iqqoqGZS8QaWjgQJ/+vDLyTF4cUkHdceXMHFvM/R0MFZ1lL9I1KGAkIXUH63jw3Qd5dtuzHe7REt61i/ql0V1g4R07aM7JZc2Q8bw4dhIflp/MjPGl3BXb/dXRdyo6y16k61DASIe0RFp4etvT/Obd38Tdo6W5ro7Gt9/mwJo1NKxeQ+STGgC2DD6B5RMv590TTuX7E4dz/YRizhjZsbPqD6ez7EW6DgWMxC3eHi0t+/fTuG4de15fxb631pD38YcAfJ3Tgw0DT2DD2AvZMGwiE6aM5W8mlPDgyEH0yElNwy6dZS/SdShg5KiO1qOl5euv2bXqbT5b+SYt1evpV7OdLI8Qysrh/QHD2DBmFntHTaDvKeMZe/xArijtx5zyfikLldZ0lr1I16GAkXa11aPl6nFXU9fQwqvPraB+9Vv03PguJbXbyYs008uy2Na/nLUTz6P5lFMZNHUy44YN5qIhfSnI65yHms6yF+k6FDDSptY9Wsb0OY0pe6aTtWAHS7b9PSd98QHFLSGKgdqB5Wydeh55k0+j/KzvMWtEyRHDJN1HeOkse5Guw9w96BrSxsxmAQ8A2cBCd5/b3ryVlZW+fv36TqutI5J9UnZ3Qi0RQs2xr5YI4WYn1NJCU+y2lVt2819rP+HPTV/Qq3gZpaGNjPuwgNHbBjL+8930DTcC8NWgIYTGV9DvjNMZee6Z9C6K/9Ivhx/hBdF3F3MuHa8AEOmmzOwdd69s83eZGjBmlg1sA2YAtcA64Ep3f7+t+RMNmP1Nzfzi+c3JlHpENV82sv7jOlpa/Z2ycMYcV8CgnllEmkJEmkK0hEJ4OAThMB4KQziEh8NYOAzNzeRGvvlqiX5vaSbHW6LfIy3keoieuTX091rG7GxhwP7otpoGDCa7cjLFZ51B4bTTyS0qSngs0+aubPPzkdLCfFbdcXZ0or3HY7uP0yM8fttcpo3bUj1fu/MmukxHx5jINtpZJt7nh6Tuw3bmTXSZQO/7NDxuCgZAz37t1xGwIwVMJu8iOw34wN0/AjCzp4CLgDYDJlGhTz7g6l/8dSpX2S6PgEcMIqm7MjCA4zTnGOFsiOQ6hQOaGHByE/lFIfL7fIHZJtj4KGxsbwXx/XOuAujZxmwHgbsSrV4kw10wD067JugqEpLJAVMK7Gw1XQtMaT2DmV0LXAtw/PGJ9YDvN7A/oamjEiyxPd8FyKZP61s9TRuRbMOzsohkGVNGDcKys7CcbCwnK/r1zXRuduzn776ycnIOmW8njcw7sInXQp9TGMpn2p4yyr7ug8e2b8D13291GPIRL3nfzu9aLfPomzvY19QMHBo9fXrkcvUZw+PYztG3Edcybc7e1nxtzRjvfO1uKLFlkrzv45q/3WXScd/Eu+0jrPuIywR436f6cVM66Qjb79oyOWDa+usd8pLa3RcACyC6iyyRjWQPKKJ4wdJEFo3LZfHsVuqgw3u09Nh3CTt3TeYpDj1suLQwn+vPSWwbbRlQuIt72voM5sLxoM9gRDJOJl8xsBYobzVdBnwaUC0Ju/W8k8jPPfSJP9HDbt2dl3a8xOyq2SzcuJDzh5/P0kuW8vMz/on83EPbB6fj0N6LK0qZc+l4SgvzMaIBpg/4RTJXJr+DWQeMMrPhwC7gCuCHwZbUcak67PZIPVouriAl24iH+qiIHDsy9igyADO7ALif6GHKj7r7f7Q3b1c+TDkZh/doubHixoR6tIiItOVYPYoMd38BeCHoOoKQih4tIiLJyOiAOVYl06NFRCRVFDAZJJkeLSIiqaaAyQCJ9GgREUk3BUw3V/1FNXPWzjlqjxYRkc6mgOmm9jTu4b537mPpR0sp7lXMvdPvZcbQGd/2aBERCZoCppsJt4RZtGUR8/93PuFImGvGX8OPx/+YgtyCoEsTETmEAqYbWf3pauauncuO+h1ML5vObZNv4/i+iV1DTUQk3RQw3cCn+z9l3vp5vFzzMuV9ynno7IeYXj496LJERI5IAdOFNbU08dimx3hk4yMA3FBxA1eNvYoe2T0CrkxE5OgUMF2Qu/Pqzlf51bpfUbu/lplDZ3JL5S2U9C4JujQRkbgpYLqYmoYa5q6dy5u73mREvxEsnLmQKSVTjr6giEgXo4DpIhrDjSzYsIAn3n+CvOw8bq28lStHX0luVm7QpYmIJEQBEzB3Z/nHy7ln/T3sbtzN7BGzuWnSTQzKHxR0aSIiSVHABOjwHi33Tr/32x4tIiLdnQImAA2hBua/N//bHi13Tr1TPVpEJOMoYDpRxCMs/mAx91ffrx4tIpLxFDCdZPPeWI+WverRIiLHBgVMmtUdrOOB6gd4bvtz6tEiIscUBUyaqEeLiBzrFDBpUP1FNb98+5dsrduqHi0icsxSwKTQ7sbd3PfOfSz7aBlFBUXMmz6PmUNnqkeLiByTFDApoB4tIiJ/SQGTpNp9tVy34jp21O/gzLIzuX3y7erRIiKCAiZpRQVFlPcp5+ZJN6tHi4hIKwqYJOVm5/LwOQ8HXYaISJejkzFERCQtFDAiIpIWChgREUkLBYyIiKSFAkZERNJCASMiImmhgBERkbRQwIiISFqYuwddQ5dgZnuAmiRWMQjYm6JygpQp4wCNpavKlLFkyjggubEMdffBbf1CAZMiZrbe3SuDriNZmTIO0Fi6qkwZS6aMA9I3Fu0iExGRtFDAiIhIWihgUmdB0AWkSKaMAzSWripTxpIp44A0jUWfwYiISFroHYyIiKSFAkZERNJCAZMkM5tlZlvN7AMzuyPoehJlZuVm9icz22Jmm83sJ0HXlAwzyzazd81sadC1JMPMCs3sGTP7v9jf5ntB15QoM7sp9tjaZGZ/MLOeQdcULzN71Mx2m9mmVrcNMLOXzWx77Hv/IGuMVztjuSf2GNtgZv9jZoWp2JYCJglmlg08DJwPjAGuNLMxwVaVsGbgZncfDUwF/rkbjwXgJ8CWoItIgQeAl9z9ZOAUuumYzKwUuBGodPdxQDZwRbBVdcjvgFmH3XYHsMLdRwErYtPdwe/4y7G8DIxz9wnANuBnqdiQAiY5pwEfuPtH7h4CngIuCrimhLj7Z+5eHft5H9EnstJgq0qMmZUBPwAWBl1LMsysL3Am8AiAu4fc/atgq0pKDpBvZjlAAfBpwPXEzd1fB/582M0XAY/Hfn4cuLhTi0pQW2Nx9z+6e3Nscg1QloptKWCSUwrsbDVdSzd9Um7NzIYBFcDbwVaSsPuB24BI0IUk6QRgD/BYbHffQjPrFXRRiXD3XcA84BPgM6De3f8YbFVJK3L3zyD6Ag04LuB6UuUfgRdTsSIFTHKsjdu69XHfZtYbeBb4qbs3BF1PR5nZhcBud38n6FpSIAc4FZjv7hXAAbrPbphDxD6fuAgYDgwBepnZ3wZblRzOzP6V6O7yRalYnwImObVAeavpMrrR2/7DmVku0XBZ5O7PBV1PgqYBs83sY6K7LM82s98HW1LCaoFad//mneQzRAOnOzoX2OHue9w9DDwHnB5wTcn6wsxKAGLfdwdcT1LM7CrgQuBHnqITJBUwyVkHjDKz4WaWR/RDyyUB15QQMzOi+/q3uPt9QdeTKHf/mbuXufswon+Ple7eLV8pu/vnwE4zOyl20znA+wGWlIxPgKlmVhB7rJ1DNz1goZUlwFWxn68CFgdYS1LMbBZwOzDb3RtTtV4FTBJiH4pdDywn+s/y3+6+OdiqEjYN+Duir/jfi31dEHRRwg3AIjPbAEwEfhlwPQmJvQt7BqgGNhJ97uk2l1oxsz8AbwEnmVmtmV0NzAVmmNl2YEZsustrZywPAX2Al2P/+/+Zkm3pUjEiIpIOegcjIiJpoYAREZG0UMCIiEhaKGBERCQtFDAiIpIWChiRbix2teXrWk2f1d2vIC2ZQwEj0r0VAtcddS6RAChgRDqJmQ2L9dxYGOuJssjMzjWzVbGeIqfFeoxUxfpyrDGzCbFl74r18XjVzD4ysxtjq50LjIidHHdP7LberXrILIqdOS/S6XKCLkDkGDMSuBy4luilhn4InAHMBv6F6NW533X3i83sbOAJomfwA5wM/BXRM663mtl8ohe/HOfuEyG6i4zolbDHEr0u3iqiV2l4szMGJ9Ka3sGIdK4d7r7R3SPAZqINq5zo5VOGEQ2bJwHcfSUw0Mz6xZZd5u5N7r6X6IUVi9rZxlp3r41t473YekU6nQJGpHM1tfo50mo6QnSPwpFaQLRetoX290DEO59IWilgRLqW14Efwbe7u/YepS/PPqK7zES6HL2yEela7iLawXID0Mh3l4Nvk7t/GTtIYBPRLoTL0l+iSHx0NWUREUkL7SITEZG0UMCIiEhaKGBERCQtFDAiIpIWChgREUkLBYyIiKSFAkZERNLi/wEwDeH4qQTWWAAAAABJRU5ErkJggg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>So, now we have some regression models for total cases over time in North America. For Linear SVM, we can clearly see that the prediction does not nearly match the actual scattered data points, as it remains at zero thoughout the year. For Linear, we see that it starts at the actual data and ends at the actual data, however, in the middle months, it does not accurately represent the actual data. We then have Tree and Random Forest left, which both seems to be an accurate representation. However, the blue line representing Random Forest still follows closer to the actual data than the Decision Tree regression. Thus, we can see that the Random Forest model best predicts our data.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#drops duplicates, but keeps last occurence in the table, which represents the latest updated one</span>
<span class="n">data_amer_april</span> <span class="o">=</span> <span class="n">data_america_april</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_may</span> <span class="o">=</span> <span class="n">data_america_may</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_june</span> <span class="o">=</span> <span class="n">data_america_june</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_july</span> <span class="o">=</span> <span class="n">data_america_july</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_aug</span> <span class="o">=</span> <span class="n">data_america_aug</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_sept</span> <span class="o">=</span> <span class="n">data_america_sept</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_oct</span> <span class="o">=</span>  <span class="n">data_america_oct</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_nov</span> <span class="o">=</span> <span class="n">data_america_nov</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_dec</span> <span class="o">=</span> <span class="n">data_america_dec</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Province_State&#39;</span><span class="p">],</span><span class="n">keep</span><span class="o">=</span><span class="s1">&#39;last&#39;</span><span class="p">)</span>
<span class="n">data_amer_april</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[22]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>People_Tested</th>
      <th>People_Hospitalized</th>
      <th>Mortality_Rate</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>58</th>
      <td>Recovered</td>
      <td>US</td>
      <td>2020-04-30 02:32:31</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0</td>
      <td>0</td>
      <td>120720.0</td>
      <td>-120720.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>84070001</td>
      <td>USA</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>7187</td>
      <td>272</td>
      <td>0.0</td>
      <td>6816.0</td>
      <td>1.0</td>
      <td>151.165615</td>
      <td>87196.0</td>
      <td>978.0</td>
      <td>3.837472</td>
      <td>84000001</td>
      <td>USA</td>
      <td>1859.627115</td>
      <td>13.797968</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>355</td>
      <td>9</td>
      <td>252.0</td>
      <td>94.0</td>
      <td>2.0</td>
      <td>59.389476</td>
      <td>19119.0</td>
      <td>NaN</td>
      <td>2.535211</td>
      <td>84000002</td>
      <td>USA</td>
      <td>3198.499705</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>3.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16</td>
      <td>ASM</td>
      <td>5.391708</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>7655</td>
      <td>320</td>
      <td>1499.0</td>
      <td>5836.0</td>
      <td>4.0</td>
      <td>105.169634</td>
      <td>71786.0</td>
      <td>1169.0</td>
      <td>4.180274</td>
      <td>84000004</td>
      <td>USA</td>
      <td>986.245241</td>
      <td>15.271065</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>3281</td>
      <td>61</td>
      <td>1305.0</td>
      <td>1915.0</td>
      <td>5.0</td>
      <td>126.727145</td>
      <td>48379.0</td>
      <td>402.0</td>
      <td>1.859189</td>
      <td>84000005</td>
      <td>USA</td>
      <td>1868.617052</td>
      <td>12.252362</td>
    </tr>
    <tr>
      <th>5</th>
      <td>California</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>36.1162</td>
      <td>-119.6816</td>
      <td>50130</td>
      <td>2031</td>
      <td>0.0</td>
      <td>48099.0</td>
      <td>6.0</td>
      <td>127.854538</td>
      <td>625337.0</td>
      <td>NaN</td>
      <td>4.051466</td>
      <td>84000006</td>
      <td>USA</td>
      <td>1594.896734</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Colorado</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>39.0598</td>
      <td>-105.3111</td>
      <td>15284</td>
      <td>777</td>
      <td>2415.0</td>
      <td>12092.0</td>
      <td>8.0</td>
      <td>269.710682</td>
      <td>71059.0</td>
      <td>2621.0</td>
      <td>5.083748</td>
      <td>84000008</td>
      <td>USA</td>
      <td>1253.949972</td>
      <td>17.148652</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Connecticut</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>41.5978</td>
      <td>-72.7554</td>
      <td>27700</td>
      <td>2257</td>
      <td>0.0</td>
      <td>25443.0</td>
      <td>9.0</td>
      <td>776.936050</td>
      <td>97133.0</td>
      <td>NaN</td>
      <td>8.148014</td>
      <td>84000009</td>
      <td>USA</td>
      <td>2724.409003</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Delaware</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>39.3185</td>
      <td>-75.5071</td>
      <td>4734</td>
      <td>152</td>
      <td>1275.0</td>
      <td>3307.0</td>
      <td>10.0</td>
      <td>486.154756</td>
      <td>21820.0</td>
      <td>NaN</td>
      <td>3.210815</td>
      <td>84000010</td>
      <td>USA</td>
      <td>2240.789349</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Diamond Princess</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>49</td>
      <td>0</td>
      <td>0.0</td>
      <td>49.0</td>
      <td>88888.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.000000</td>
      <td>84088888</td>
      <td>USA</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>10</th>
      <td>District of Columbia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.8974</td>
      <td>-77.0268</td>
      <td>4323</td>
      <td>224</td>
      <td>660.0</td>
      <td>3439.0</td>
      <td>11.0</td>
      <td>612.540719</td>
      <td>20079.0</td>
      <td>NaN</td>
      <td>5.181587</td>
      <td>84000011</td>
      <td>USA</td>
      <td>2845.062480</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Florida</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>27.7663</td>
      <td>-81.6868</td>
      <td>33690</td>
      <td>1268</td>
      <td>0.0</td>
      <td>32422.0</td>
      <td>12.0</td>
      <td>158.671055</td>
      <td>382405.0</td>
      <td>5795.0</td>
      <td>3.763728</td>
      <td>84000012</td>
      <td>USA</td>
      <td>1801.027156</td>
      <td>17.200950</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Georgia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>33.0406</td>
      <td>-83.6431</td>
      <td>26264</td>
      <td>1132</td>
      <td>0.0</td>
      <td>25132.0</td>
      <td>13.0</td>
      <td>259.029313</td>
      <td>149044.0</td>
      <td>5156.0</td>
      <td>4.310082</td>
      <td>84000013</td>
      <td>USA</td>
      <td>1469.949927</td>
      <td>19.631435</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Grand Princess</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>103</td>
      <td>3</td>
      <td>0.0</td>
      <td>100.0</td>
      <td>99999.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.912621</td>
      <td>84099999</td>
      <td>USA</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Guam</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>13.4443</td>
      <td>144.7937</td>
      <td>145</td>
      <td>5</td>
      <td>131.0</td>
      <td>9.0</td>
      <td>66.0</td>
      <td>88.291349</td>
      <td>2108.0</td>
      <td>NaN</td>
      <td>3.448276</td>
      <td>316</td>
      <td>GUM</td>
      <td>1283.573547</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Hawaii</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>21.0943</td>
      <td>-157.4983</td>
      <td>618</td>
      <td>16</td>
      <td>516.0</td>
      <td>86.0</td>
      <td>15.0</td>
      <td>43.650665</td>
      <td>30640.0</td>
      <td>69.0</td>
      <td>2.588997</td>
      <td>84000015</td>
      <td>USA</td>
      <td>2164.168879</td>
      <td>11.165049</td>
    </tr>
    <tr>
      <th>16</th>
      <td>Idaho</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.2405</td>
      <td>-114.4788</td>
      <td>1984</td>
      <td>60</td>
      <td>1121.0</td>
      <td>803.0</td>
      <td>16.0</td>
      <td>123.191785</td>
      <td>28693.0</td>
      <td>175.0</td>
      <td>3.024194</td>
      <td>84000016</td>
      <td>USA</td>
      <td>1781.623933</td>
      <td>8.820565</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Illinois</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>40.3495</td>
      <td>-88.9861</td>
      <td>52918</td>
      <td>2355</td>
      <td>0.0</td>
      <td>50563.0</td>
      <td>17.0</td>
      <td>450.916536</td>
      <td>269867.0</td>
      <td>NaN</td>
      <td>4.450282</td>
      <td>84000017</td>
      <td>USA</td>
      <td>2299.548223</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Indiana</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>39.8494</td>
      <td>-86.2583</td>
      <td>17835</td>
      <td>1114</td>
      <td>0.0</td>
      <td>16721.0</td>
      <td>18.0</td>
      <td>272.539981</td>
      <td>94998.0</td>
      <td>NaN</td>
      <td>6.246145</td>
      <td>84000018</td>
      <td>USA</td>
      <td>1451.682260</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Iowa</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>42.0115</td>
      <td>-93.2105</td>
      <td>7145</td>
      <td>162</td>
      <td>2697.0</td>
      <td>4286.0</td>
      <td>19.0</td>
      <td>272.635729</td>
      <td>42667.0</td>
      <td>NaN</td>
      <td>2.267320</td>
      <td>84000019</td>
      <td>USA</td>
      <td>1628.068392</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Kansas</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.5266</td>
      <td>-96.7265</td>
      <td>4413</td>
      <td>134</td>
      <td>272.0</td>
      <td>4007.0</td>
      <td>20.0</td>
      <td>180.972800</td>
      <td>31626.0</td>
      <td>523.0</td>
      <td>3.036483</td>
      <td>84000020</td>
      <td>USA</td>
      <td>1296.951226</td>
      <td>11.851348</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Kentucky</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>37.6681</td>
      <td>-84.6701</td>
      <td>4708</td>
      <td>240</td>
      <td>1668.0</td>
      <td>2800.0</td>
      <td>21.0</td>
      <td>137.527996</td>
      <td>54101.0</td>
      <td>1359.0</td>
      <td>5.097706</td>
      <td>84000021</td>
      <td>USA</td>
      <td>1580.374276</td>
      <td>28.865760</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Louisiana</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>31.1695</td>
      <td>-91.8678</td>
      <td>28001</td>
      <td>1905</td>
      <td>17303.0</td>
      <td>8793.0</td>
      <td>22.0</td>
      <td>609.079396</td>
      <td>161309.0</td>
      <td>NaN</td>
      <td>6.803328</td>
      <td>84000022</td>
      <td>USA</td>
      <td>3508.802841</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Maine</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.6939</td>
      <td>-69.3819</td>
      <td>1095</td>
      <td>53</td>
      <td>631.0</td>
      <td>411.0</td>
      <td>23.0</td>
      <td>93.270392</td>
      <td>20641.0</td>
      <td>170.0</td>
      <td>4.840183</td>
      <td>84000023</td>
      <td>USA</td>
      <td>1758.168187</td>
      <td>15.525114</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Maryland</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>39.0639</td>
      <td>-76.8021</td>
      <td>21742</td>
      <td>1140</td>
      <td>1432.0</td>
      <td>19170.0</td>
      <td>24.0</td>
      <td>365.821546</td>
      <td>114359.0</td>
      <td>4559.0</td>
      <td>5.243308</td>
      <td>84000024</td>
      <td>USA</td>
      <td>1924.155377</td>
      <td>20.968632</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Massachusetts</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>42.2302</td>
      <td>-71.5301</td>
      <td>62205</td>
      <td>3562</td>
      <td>0.0</td>
      <td>58643.0</td>
      <td>25.0</td>
      <td>906.280104</td>
      <td>275647.0</td>
      <td>5942.0</td>
      <td>5.726228</td>
      <td>84000025</td>
      <td>USA</td>
      <td>4015.969645</td>
      <td>9.552287</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Michigan</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>43.3266</td>
      <td>-84.5361</td>
      <td>41379</td>
      <td>3789</td>
      <td>8342.0</td>
      <td>29248.0</td>
      <td>26.0</td>
      <td>519.363058</td>
      <td>180267.0</td>
      <td>NaN</td>
      <td>9.156819</td>
      <td>84000026</td>
      <td>USA</td>
      <td>2262.597463</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Minnesota</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>45.6945</td>
      <td>-93.9002</td>
      <td>5136</td>
      <td>343</td>
      <td>2172.0</td>
      <td>2621.0</td>
      <td>27.0</td>
      <td>103.832125</td>
      <td>70276.0</td>
      <td>1044.0</td>
      <td>6.678349</td>
      <td>84000027</td>
      <td>USA</td>
      <td>1420.737232</td>
      <td>20.327103</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Mississippi</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>32.7416</td>
      <td>-89.6787</td>
      <td>6815</td>
      <td>261</td>
      <td>3413.0</td>
      <td>3141.0</td>
      <td>28.0</td>
      <td>235.389123</td>
      <td>66340.0</td>
      <td>1175.0</td>
      <td>3.829787</td>
      <td>84000028</td>
      <td>USA</td>
      <td>2291.374085</td>
      <td>17.241379</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Missouri</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.4561</td>
      <td>-92.2884</td>
      <td>7818</td>
      <td>350</td>
      <td>0.0</td>
      <td>7468.0</td>
      <td>29.0</td>
      <td>133.425356</td>
      <td>80687.0</td>
      <td>NaN</td>
      <td>4.476848</td>
      <td>84000029</td>
      <td>USA</td>
      <td>1377.039097</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Montana</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>46.9219</td>
      <td>-110.4544</td>
      <td>453</td>
      <td>16</td>
      <td>392.0</td>
      <td>45.0</td>
      <td>30.0</td>
      <td>52.310254</td>
      <td>13914.0</td>
      <td>61.0</td>
      <td>3.532009</td>
      <td>84000030</td>
      <td>USA</td>
      <td>1606.721579</td>
      <td>13.465784</td>
    </tr>
    <tr>
      <th>31</th>
      <td>Nebraska</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>41.1254</td>
      <td>-98.2681</td>
      <td>4281</td>
      <td>70</td>
      <td>0.0</td>
      <td>4211.0</td>
      <td>31.0</td>
      <td>280.671251</td>
      <td>25321.0</td>
      <td>NaN</td>
      <td>1.635132</td>
      <td>84000031</td>
      <td>USA</td>
      <td>1660.097347</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Nevada</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.3135</td>
      <td>-117.0554</td>
      <td>5053</td>
      <td>243</td>
      <td>158.0</td>
      <td>4652.0</td>
      <td>32.0</td>
      <td>167.501078</td>
      <td>41986.0</td>
      <td>NaN</td>
      <td>4.809024</td>
      <td>84000032</td>
      <td>USA</td>
      <td>1391.787110</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>33</th>
      <td>New Hampshire</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>43.4525</td>
      <td>-71.5639</td>
      <td>2146</td>
      <td>72</td>
      <td>980.0</td>
      <td>1094.0</td>
      <td>33.0</td>
      <td>161.578378</td>
      <td>21921.0</td>
      <td>259.0</td>
      <td>3.355079</td>
      <td>84000033</td>
      <td>USA</td>
      <td>1650.493770</td>
      <td>12.068966</td>
    </tr>
    <tr>
      <th>34</th>
      <td>New Jersey</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>40.2989</td>
      <td>-74.5210</td>
      <td>118652</td>
      <td>7228</td>
      <td>15642.0</td>
      <td>95782.0</td>
      <td>34.0</td>
      <td>1335.841724</td>
      <td>247918.0</td>
      <td>NaN</td>
      <td>6.091764</td>
      <td>84000034</td>
      <td>USA</td>
      <td>2791.181004</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>35</th>
      <td>New Mexico</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>34.8405</td>
      <td>-106.2485</td>
      <td>3411</td>
      <td>123</td>
      <td>734.0</td>
      <td>2554.0</td>
      <td>35.0</td>
      <td>204.553673</td>
      <td>65085.0</td>
      <td>536.0</td>
      <td>3.605981</td>
      <td>84000035</td>
      <td>USA</td>
      <td>3903.071184</td>
      <td>15.713867</td>
    </tr>
    <tr>
      <th>36</th>
      <td>New York</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>42.1657</td>
      <td>-74.9481</td>
      <td>304372</td>
      <td>23587</td>
      <td>54771.0</td>
      <td>226014.0</td>
      <td>36.0</td>
      <td>1805.180883</td>
      <td>900636.0</td>
      <td>66369.0</td>
      <td>7.749399</td>
      <td>84000036</td>
      <td>USA</td>
      <td>5341.525797</td>
      <td>21.805225</td>
    </tr>
    <tr>
      <th>37</th>
      <td>North Carolina</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>35.6301</td>
      <td>-79.8064</td>
      <td>10754</td>
      <td>406</td>
      <td>0.0</td>
      <td>10348.0</td>
      <td>37.0</td>
      <td>108.430485</td>
      <td>128036.0</td>
      <td>NaN</td>
      <td>3.775339</td>
      <td>84000037</td>
      <td>USA</td>
      <td>1290.962026</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>38</th>
      <td>North Dakota</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>47.5289</td>
      <td>-99.7840</td>
      <td>1067</td>
      <td>19</td>
      <td>458.0</td>
      <td>590.0</td>
      <td>38.0</td>
      <td>175.951242</td>
      <td>27460.0</td>
      <td>85.0</td>
      <td>1.780694</td>
      <td>84000038</td>
      <td>USA</td>
      <td>4528.229703</td>
      <td>7.966261</td>
    </tr>
    <tr>
      <th>39</th>
      <td>Northern Mariana Islands</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>15.0979</td>
      <td>145.6739</td>
      <td>14</td>
      <td>2</td>
      <td>12.0</td>
      <td>0.0</td>
      <td>69.0</td>
      <td>25.388075</td>
      <td>599.0</td>
      <td>NaN</td>
      <td>14.285714</td>
      <td>580</td>
      <td>MNP</td>
      <td>1086.246917</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>40</th>
      <td>Ohio</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>40.3888</td>
      <td>-82.7649</td>
      <td>18027</td>
      <td>976</td>
      <td>0.0</td>
      <td>17051.0</td>
      <td>39.0</td>
      <td>161.331894</td>
      <td>133890.0</td>
      <td>3533.0</td>
      <td>5.414101</td>
      <td>84000039</td>
      <td>USA</td>
      <td>1198.243042</td>
      <td>19.598380</td>
    </tr>
    <tr>
      <th>41</th>
      <td>Oklahoma</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>35.5653</td>
      <td>-96.9289</td>
      <td>3618</td>
      <td>222</td>
      <td>2401.0</td>
      <td>995.0</td>
      <td>40.0</td>
      <td>98.916403</td>
      <td>63422.0</td>
      <td>703.0</td>
      <td>6.135987</td>
      <td>84000040</td>
      <td>USA</td>
      <td>1733.962447</td>
      <td>19.430625</td>
    </tr>
    <tr>
      <th>42</th>
      <td>Oregon</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.5720</td>
      <td>-122.0709</td>
      <td>2510</td>
      <td>103</td>
      <td>0.0</td>
      <td>2407.0</td>
      <td>41.0</td>
      <td>62.639223</td>
      <td>56032.0</td>
      <td>578.0</td>
      <td>4.103586</td>
      <td>84000041</td>
      <td>USA</td>
      <td>1398.327059</td>
      <td>23.027888</td>
    </tr>
    <tr>
      <th>43</th>
      <td>Pennsylvania</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>40.5908</td>
      <td>-77.2098</td>
      <td>47971</td>
      <td>2475</td>
      <td>0.0</td>
      <td>45496.0</td>
      <td>42.0</td>
      <td>381.100389</td>
      <td>221365.0</td>
      <td>NaN</td>
      <td>5.159367</td>
      <td>84000042</td>
      <td>USA</td>
      <td>1758.610151</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>44</th>
      <td>Puerto Rico</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>18.2208</td>
      <td>-66.5901</td>
      <td>1539</td>
      <td>92</td>
      <td>0.0</td>
      <td>1447.0</td>
      <td>72.0</td>
      <td>52.464574</td>
      <td>10852.0</td>
      <td>NaN</td>
      <td>5.977908</td>
      <td>630</td>
      <td>PRI</td>
      <td>369.945129</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>45</th>
      <td>Rhode Island</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>41.6809</td>
      <td>-71.5118</td>
      <td>8621</td>
      <td>266</td>
      <td>461.0</td>
      <td>7894.0</td>
      <td>44.0</td>
      <td>813.792465</td>
      <td>63710.0</td>
      <td>896.0</td>
      <td>3.085489</td>
      <td>84000044</td>
      <td>USA</td>
      <td>6014.002781</td>
      <td>10.393226</td>
    </tr>
    <tr>
      <th>46</th>
      <td>South Carolina</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>33.8569</td>
      <td>-80.9450</td>
      <td>6095</td>
      <td>244</td>
      <td>3252.0</td>
      <td>2599.0</td>
      <td>45.0</td>
      <td>120.933140</td>
      <td>56512.0</td>
      <td>1000.0</td>
      <td>4.003281</td>
      <td>84000045</td>
      <td>USA</td>
      <td>1121.275403</td>
      <td>16.406891</td>
    </tr>
    <tr>
      <th>47</th>
      <td>South Dakota</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.2998</td>
      <td>-99.4388</td>
      <td>2449</td>
      <td>17</td>
      <td>1573.0</td>
      <td>859.0</td>
      <td>46.0</td>
      <td>332.793399</td>
      <td>17028.0</td>
      <td>173.0</td>
      <td>0.694161</td>
      <td>84000046</td>
      <td>USA</td>
      <td>2313.926500</td>
      <td>7.064108</td>
    </tr>
    <tr>
      <th>48</th>
      <td>Tennessee</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>35.7478</td>
      <td>-86.6923</td>
      <td>10735</td>
      <td>199</td>
      <td>5140.0</td>
      <td>5396.0</td>
      <td>47.0</td>
      <td>163.520428</td>
      <td>168549.0</td>
      <td>1013.0</td>
      <td>1.853749</td>
      <td>84000047</td>
      <td>USA</td>
      <td>2567.415428</td>
      <td>9.436423</td>
    </tr>
    <tr>
      <th>49</th>
      <td>Texas</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>31.0545</td>
      <td>-97.5635</td>
      <td>28748</td>
      <td>835</td>
      <td>12507.0</td>
      <td>15408.0</td>
      <td>48.0</td>
      <td>124.983897</td>
      <td>314790.0</td>
      <td>NaN</td>
      <td>2.826609</td>
      <td>84000048</td>
      <td>USA</td>
      <td>1369.571514</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>50</th>
      <td>Utah</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>40.1500</td>
      <td>-111.8624</td>
      <td>4672</td>
      <td>46</td>
      <td>1939.0</td>
      <td>2687.0</td>
      <td>49.0</td>
      <td>163.021367</td>
      <td>108501.0</td>
      <td>390.0</td>
      <td>0.984589</td>
      <td>84000049</td>
      <td>USA</td>
      <td>3785.954900</td>
      <td>8.347603</td>
    </tr>
    <tr>
      <th>51</th>
      <td>Vermont</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.0459</td>
      <td>-72.7107</td>
      <td>866</td>
      <td>49</td>
      <td>0.0</td>
      <td>817.0</td>
      <td>50.0</td>
      <td>141.829801</td>
      <td>15652.0</td>
      <td>NaN</td>
      <td>5.658199</td>
      <td>84000050</td>
      <td>USA</td>
      <td>2563.418065</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>52</th>
      <td>Virgin Islands</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>18.3358</td>
      <td>-64.8963</td>
      <td>66</td>
      <td>4</td>
      <td>51.0</td>
      <td>11.0</td>
      <td>78.0</td>
      <td>61.528135</td>
      <td>873.0</td>
      <td>NaN</td>
      <td>6.060606</td>
      <td>850</td>
      <td>VIR</td>
      <td>813.849424</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>15847</td>
      <td>552</td>
      <td>2104.0</td>
      <td>13191.0</td>
      <td>51.0</td>
      <td>200.411522</td>
      <td>91509.0</td>
      <td>3654.0</td>
      <td>3.483309</td>
      <td>84000051</td>
      <td>USA</td>
      <td>1157.282639</td>
      <td>23.057992</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>14327</td>
      <td>836</td>
      <td>0.0</td>
      <td>13513.0</td>
      <td>53.0</td>
      <td>189.776596</td>
      <td>187800.0</td>
      <td>NaN</td>
      <td>5.681580</td>
      <td>84000053</td>
      <td>USA</td>
      <td>2487.613921</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>1125</td>
      <td>41</td>
      <td>545.0</td>
      <td>539.0</td>
      <td>54.0</td>
      <td>85.034142</td>
      <td>44541.0</td>
      <td>NaN</td>
      <td>3.644444</td>
      <td>84000054</td>
      <td>USA</td>
      <td>3366.671756</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>6854</td>
      <td>316</td>
      <td>3352.0</td>
      <td>3186.0</td>
      <td>55.0</td>
      <td>132.455425</td>
      <td>76248.0</td>
      <td>1512.0</td>
      <td>4.610446</td>
      <td>84000055</td>
      <td>USA</td>
      <td>1473.513456</td>
      <td>22.060111</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-05-01 02:32:32</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>559</td>
      <td>7</td>
      <td>371.0</td>
      <td>181.0</td>
      <td>56.0</td>
      <td>112.420561</td>
      <td>9446.0</td>
      <td>56.0</td>
      <td>1.252236</td>
      <td>84000056</td>
      <td>USA</td>
      <td>1899.686268</td>
      <td>10.017889</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">monthly_map</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">Map</span><span class="p">(</span><span class="n">location</span><span class="o">=</span><span class="p">[</span><span class="mi">48</span><span class="p">,</span> <span class="o">-</span><span class="mi">102</span><span class="p">],</span> <span class="n">zoom_start</span><span class="o">=</span><span class="mi">3</span><span class="p">)</span>
<span class="n">monthly_map3</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">Map</span><span class="p">(</span><span class="n">location</span><span class="o">=</span><span class="p">[</span><span class="mi">48</span><span class="p">,</span> <span class="o">-</span><span class="mi">102</span><span class="p">],</span> <span class="n">zoom_start</span><span class="o">=</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[24]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">folium.plugins</span> <span class="kn">import</span> <span class="n">FastMarkerCluster</span>

<span class="n">april</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;april&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_april</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;orange&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">april</span><span class="p">)</span>

<span class="n">may</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;may&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_may</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">may</span><span class="p">)</span>

<span class="n">june</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;june&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_june</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;white&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">june</span><span class="p">)</span>
<span class="n">july</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;july&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_july</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;purple&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">july</span><span class="p">)</span>
<span class="n">aug</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;aug&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_aug</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;pink&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">aug</span><span class="p">)</span>
<span class="n">sept</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;sept&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_sept</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;gray&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">sept</span><span class="p">)</span>
        
<span class="n">octo</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;oct&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_oct</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;crimson&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">octo</span><span class="p">)</span>
        
<span class="n">nov</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;nov&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_nov</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;#3186cc&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">nov</span><span class="p">)</span>
<span class="n">dec</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;dec&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_dec</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;green&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">dec</span><span class="p">)</span>

<span class="n">folium</span><span class="o">.</span><span class="n">LayerControl</span><span class="p">()</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[24]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;folium.map.LayerControl at 0x7f43802ecc10&gt;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[25]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">monthly_map</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[25]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[28]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">data_amer_april</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_april</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_may</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_may</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_april</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_june</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_june</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_may</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_july</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_july</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_june</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_aug</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_aug</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_july</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_sept</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_sept</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_aug</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_oct</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_oct</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_sept</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_nov</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_nov</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_oct</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_dec</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_amer_dec</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">data_amer_nov</span><span class="p">[</span><span class="s1">&#39;Confirmed&#39;</span><span class="p">]</span>
<span class="n">data_amer_dec</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[28]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Country_Region</th>
      <th>Last_Update</th>
      <th>Lat</th>
      <th>Long_</th>
      <th>Confirmed</th>
      <th>Deaths</th>
      <th>Recovered</th>
      <th>Active</th>
      <th>FIPS</th>
      <th>Incident_Rate</th>
      <th>Total_Test_Results</th>
      <th>People_Hospitalized</th>
      <th>Case_Fatality_Ratio</th>
      <th>UID</th>
      <th>ISO3</th>
      <th>Testing_Rate</th>
      <th>Hospitalization_Rate</th>
      <th>new cases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alabama</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>32.3182</td>
      <td>-86.9023</td>
      <td>267589</td>
      <td>3877</td>
      <td>168387.0</td>
      <td>95325.0</td>
      <td>1.0</td>
      <td>5457.452656</td>
      <td>1637161.0</td>
      <td>NaN</td>
      <td>1.448864</td>
      <td>84000001.0</td>
      <td>USA</td>
      <td>33389.745645</td>
      <td>NaN</td>
      <td>18065</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Alaska</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>61.3707</td>
      <td>-152.4044</td>
      <td>36271</td>
      <td>143</td>
      <td>7165.0</td>
      <td>28963.0</td>
      <td>2.0</td>
      <td>4958.136547</td>
      <td>1067231.0</td>
      <td>NaN</td>
      <td>0.394254</td>
      <td>84000002.0</td>
      <td>USA</td>
      <td>145887.265992</td>
      <td>NaN</td>
      <td>3695</td>
    </tr>
    <tr>
      <th>2</th>
      <td>American Samoa</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>-14.2710</td>
      <td>-170.1320</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>60.0</td>
      <td>0.000000</td>
      <td>2140.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>16.0</td>
      <td>ASM</td>
      <td>3846.084722</td>
      <td>NaN</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Arizona</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>33.7298</td>
      <td>-111.4312</td>
      <td>358900</td>
      <td>6925</td>
      <td>55640.0</td>
      <td>296335.0</td>
      <td>4.0</td>
      <td>4930.814043</td>
      <td>2349913.0</td>
      <td>NaN</td>
      <td>1.929507</td>
      <td>84000004.0</td>
      <td>USA</td>
      <td>32284.714463</td>
      <td>NaN</td>
      <td>32083</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Arkansas</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>34.9697</td>
      <td>-92.3731</td>
      <td>169382</td>
      <td>2620</td>
      <td>148131.0</td>
      <td>18631.0</td>
      <td>5.0</td>
      <td>5612.756826</td>
      <td>1748446.0</td>
      <td>NaN</td>
      <td>1.546800</td>
      <td>84000005.0</td>
      <td>USA</td>
      <td>57937.692441</td>
      <td>NaN</td>
      <td>12023</td>
    </tr>
    <tr>
      <th>5</th>
      <td>California</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>36.1162</td>
      <td>-119.6816</td>
      <td>1337941</td>
      <td>19870</td>
      <td>NaN</td>
      <td>1318071.0</td>
      <td>6.0</td>
      <td>3386.144586</td>
      <td>24901975.0</td>
      <td>NaN</td>
      <td>1.485118</td>
      <td>84000006.0</td>
      <td>USA</td>
      <td>63023.472509</td>
      <td>NaN</td>
      <td>107677</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Colorado</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>39.0598</td>
      <td>-105.3111</td>
      <td>257347</td>
      <td>3357</td>
      <td>13760.0</td>
      <td>240230.0</td>
      <td>8.0</td>
      <td>4468.810517</td>
      <td>3442114.0</td>
      <td>NaN</td>
      <td>1.304464</td>
      <td>84000008.0</td>
      <td>USA</td>
      <td>59772.040253</td>
      <td>NaN</td>
      <td>24442</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Connecticut</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>41.5978</td>
      <td>-72.7554</td>
      <td>127715</td>
      <td>5146</td>
      <td>9800.0</td>
      <td>112769.0</td>
      <td>9.0</td>
      <td>3582.180060</td>
      <td>3422098.0</td>
      <td>NaN</td>
      <td>4.029284</td>
      <td>84000009.0</td>
      <td>USA</td>
      <td>95983.801585</td>
      <td>NaN</td>
      <td>10420</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Delaware</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>39.3185</td>
      <td>-75.5071</td>
      <td>39096</td>
      <td>782</td>
      <td>18605.0</td>
      <td>19709.0</td>
      <td>10.0</td>
      <td>4014.935857</td>
      <td>769818.0</td>
      <td>NaN</td>
      <td>2.000205</td>
      <td>84000010.0</td>
      <td>USA</td>
      <td>79055.910878</td>
      <td>NaN</td>
      <td>3442</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Diamond Princess</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>49</td>
      <td>0</td>
      <td>NaN</td>
      <td>49.0</td>
      <td>88888.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.000000</td>
      <td>84088888.0</td>
      <td>USA</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0</td>
    </tr>
    <tr>
      <th>10</th>
      <td>District of Columbia</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>38.8974</td>
      <td>-77.0268</td>
      <td>22872</td>
      <td>695</td>
      <td>16596.0</td>
      <td>5581.0</td>
      <td>11.0</td>
      <td>3240.812243</td>
      <td>727387.0</td>
      <td>NaN</td>
      <td>3.038650</td>
      <td>84000011.0</td>
      <td>USA</td>
      <td>103065.962545</td>
      <td>NaN</td>
      <td>1320</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Florida</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>27.7663</td>
      <td>-81.6868</td>
      <td>1049638</td>
      <td>19084</td>
      <td>NaN</td>
      <td>1030554.0</td>
      <td>12.0</td>
      <td>4887.097742</td>
      <td>12986939.0</td>
      <td>NaN</td>
      <td>1.818151</td>
      <td>84000012.0</td>
      <td>USA</td>
      <td>60466.980297</td>
      <td>NaN</td>
      <td>50319</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Georgia</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>33.0406</td>
      <td>-83.6431</td>
      <td>499371</td>
      <td>9793</td>
      <td>NaN</td>
      <td>489578.0</td>
      <td>13.0</td>
      <td>4703.316426</td>
      <td>4466200.0</td>
      <td>NaN</td>
      <td>1.961067</td>
      <td>84000013.0</td>
      <td>USA</td>
      <td>42064.821191</td>
      <td>NaN</td>
      <td>27808</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Grand Princess</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>103</td>
      <td>3</td>
      <td>NaN</td>
      <td>100.0</td>
      <td>99999.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.912621</td>
      <td>84099999.0</td>
      <td>USA</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Guam</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>13.4443</td>
      <td>144.7937</td>
      <td>6959</td>
      <td>113</td>
      <td>6056.0</td>
      <td>790.0</td>
      <td>66.0</td>
      <td>4237.375859</td>
      <td>86548.0</td>
      <td>NaN</td>
      <td>1.623797</td>
      <td>316.0</td>
      <td>GUM</td>
      <td>52699.584117</td>
      <td>NaN</td>
      <td>107</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Hawaii</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>21.0943</td>
      <td>-157.4983</td>
      <td>18738</td>
      <td>261</td>
      <td>11958.0</td>
      <td>6519.0</td>
      <td>15.0</td>
      <td>1323.424716</td>
      <td>695177.0</td>
      <td>NaN</td>
      <td>1.392891</td>
      <td>84000015.0</td>
      <td>USA</td>
      <td>49098.859219</td>
      <td>NaN</td>
      <td>515</td>
    </tr>
    <tr>
      <th>16</th>
      <td>Idaho</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.2405</td>
      <td>-114.4788</td>
      <td>109705</td>
      <td>1032</td>
      <td>42671.0</td>
      <td>66002.0</td>
      <td>16.0</td>
      <td>6138.836584</td>
      <td>487460.0</td>
      <td>NaN</td>
      <td>0.940705</td>
      <td>84000016.0</td>
      <td>USA</td>
      <td>27277.127581</td>
      <td>NaN</td>
      <td>8007</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Illinois</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>40.3495</td>
      <td>-88.9861</td>
      <td>779975</td>
      <td>14016</td>
      <td>NaN</td>
      <td>765959.0</td>
      <td>17.0</td>
      <td>6155.192691</td>
      <td>11021676.0</td>
      <td>NaN</td>
      <td>1.796981</td>
      <td>84000017.0</td>
      <td>USA</td>
      <td>86977.838465</td>
      <td>NaN</td>
      <td>53671</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Indiana</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>39.8494</td>
      <td>-86.2583</td>
      <td>375019</td>
      <td>6207</td>
      <td>222022.0</td>
      <td>146790.0</td>
      <td>18.0</td>
      <td>5570.511001</td>
      <td>4525760.0</td>
      <td>NaN</td>
      <td>1.655116</td>
      <td>84000018.0</td>
      <td>USA</td>
      <td>67225.382894</td>
      <td>NaN</td>
      <td>36042</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Iowa</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>42.0115</td>
      <td>-93.2105</td>
      <td>243385</td>
      <td>2682</td>
      <td>157026.0</td>
      <td>83677.0</td>
      <td>19.0</td>
      <td>7714.091922</td>
      <td>1094502.0</td>
      <td>NaN</td>
      <td>1.101958</td>
      <td>84000019.0</td>
      <td>USA</td>
      <td>34690.260438</td>
      <td>NaN</td>
      <td>12754</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Kansas</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>38.5266</td>
      <td>-96.7265</td>
      <td>171363</td>
      <td>1786</td>
      <td>3615.0</td>
      <td>165962.0</td>
      <td>20.0</td>
      <td>5882.064206</td>
      <td>845186.0</td>
      <td>NaN</td>
      <td>1.042232</td>
      <td>84000020.0</td>
      <td>USA</td>
      <td>29011.153621</td>
      <td>NaN</td>
      <td>11448</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Kentucky</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>37.6681</td>
      <td>-84.6701</td>
      <td>198064</td>
      <td>2062</td>
      <td>30161.0</td>
      <td>165841.0</td>
      <td>21.0</td>
      <td>4433.269848</td>
      <td>2732005.0</td>
      <td>NaN</td>
      <td>1.041078</td>
      <td>84000021.0</td>
      <td>USA</td>
      <td>61150.513925</td>
      <td>NaN</td>
      <td>19023</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Louisiana</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>31.1695</td>
      <td>-91.8678</td>
      <td>247177</td>
      <td>6548</td>
      <td>202891.0</td>
      <td>37738.0</td>
      <td>22.0</td>
      <td>5317.013402</td>
      <td>3566534.0</td>
      <td>NaN</td>
      <td>2.649114</td>
      <td>84000022.0</td>
      <td>USA</td>
      <td>76719.553501</td>
      <td>NaN</td>
      <td>14763</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Maine</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.6939</td>
      <td>-69.3819</td>
      <td>13127</td>
      <td>227</td>
      <td>9993.0</td>
      <td>2907.0</td>
      <td>23.0</td>
      <td>976.557269</td>
      <td>913959.0</td>
      <td>NaN</td>
      <td>1.729260</td>
      <td>84000023.0</td>
      <td>USA</td>
      <td>67992.176829</td>
      <td>NaN</td>
      <td>1370</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Maryland</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>39.0639</td>
      <td>-76.8021</td>
      <td>212384</td>
      <td>4820</td>
      <td>8780.0</td>
      <td>198784.0</td>
      <td>24.0</td>
      <td>3512.987786</td>
      <td>4637128.0</td>
      <td>NaN</td>
      <td>2.269474</td>
      <td>84000024.0</td>
      <td>USA</td>
      <td>76701.512485</td>
      <td>NaN</td>
      <td>14014</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Massachusetts</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>42.2302</td>
      <td>-71.5301</td>
      <td>252017</td>
      <td>10953</td>
      <td>169809.0</td>
      <td>71255.0</td>
      <td>25.0</td>
      <td>3656.393040</td>
      <td>8880813.0</td>
      <td>NaN</td>
      <td>4.346135</td>
      <td>84000025.0</td>
      <td>USA</td>
      <td>128847.430317</td>
      <td>NaN</td>
      <td>25885</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Michigan</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>43.3266</td>
      <td>-84.5361</td>
      <td>426576</td>
      <td>10321</td>
      <td>197750.0</td>
      <td>218505.0</td>
      <td>26.0</td>
      <td>4271.373867</td>
      <td>6965058.0</td>
      <td>NaN</td>
      <td>2.419499</td>
      <td>84000026.0</td>
      <td>USA</td>
      <td>69742.242229</td>
      <td>NaN</td>
      <td>37634</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Minnesota</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>45.6945</td>
      <td>-93.9002</td>
      <td>345281</td>
      <td>3979</td>
      <td>301081.0</td>
      <td>40221.0</td>
      <td>27.0</td>
      <td>6122.403022</td>
      <td>4370635.0</td>
      <td>NaN</td>
      <td>1.152395</td>
      <td>84000027.0</td>
      <td>USA</td>
      <td>77498.585014</td>
      <td>NaN</td>
      <td>26518</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Mississippi</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>32.7416</td>
      <td>-89.6787</td>
      <td>163458</td>
      <td>3949</td>
      <td>128746.0</td>
      <td>30763.0</td>
      <td>28.0</td>
      <td>5492.265340</td>
      <td>1145853.0</td>
      <td>NaN</td>
      <td>2.415911</td>
      <td>84000028.0</td>
      <td>USA</td>
      <td>38501.197353</td>
      <td>NaN</td>
      <td>10188</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Missouri</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>38.4561</td>
      <td>-92.2884</td>
      <td>325588</td>
      <td>4276</td>
      <td>NaN</td>
      <td>321312.0</td>
      <td>29.0</td>
      <td>5304.958364</td>
      <td>3173989.0</td>
      <td>NaN</td>
      <td>1.313316</td>
      <td>84000029.0</td>
      <td>USA</td>
      <td>51715.295071</td>
      <td>NaN</td>
      <td>19382</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Montana</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>46.9219</td>
      <td>-110.4544</td>
      <td>67069</td>
      <td>734</td>
      <td>49910.0</td>
      <td>16425.0</td>
      <td>30.0</td>
      <td>6275.297583</td>
      <td>682583.0</td>
      <td>NaN</td>
      <td>1.094395</td>
      <td>84000030.0</td>
      <td>USA</td>
      <td>63865.741997</td>
      <td>NaN</td>
      <td>4871</td>
    </tr>
    <tr>
      <th>31</th>
      <td>Nebraska</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>41.1254</td>
      <td>-98.2681</td>
      <td>138568</td>
      <td>1194</td>
      <td>68355.0</td>
      <td>69019.0</td>
      <td>31.0</td>
      <td>7163.328522</td>
      <td>1435777.0</td>
      <td>NaN</td>
      <td>0.861671</td>
      <td>84000031.0</td>
      <td>USA</td>
      <td>74223.069797</td>
      <td>NaN</td>
      <td>10161</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Nevada</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>38.3135</td>
      <td>-117.0554</td>
      <td>165628</td>
      <td>2301</td>
      <td>NaN</td>
      <td>163327.0</td>
      <td>32.0</td>
      <td>5377.260113</td>
      <td>1718547.0</td>
      <td>NaN</td>
      <td>1.389258</td>
      <td>84000032.0</td>
      <td>USA</td>
      <td>55794.154582</td>
      <td>NaN</td>
      <td>13457</td>
    </tr>
    <tr>
      <th>33</th>
      <td>New Hampshire</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>43.4525</td>
      <td>-71.5639</td>
      <td>24138</td>
      <td>559</td>
      <td>19034.0</td>
      <td>4639.0</td>
      <td>33.0</td>
      <td>1782.143411</td>
      <td>854085.0</td>
      <td>NaN</td>
      <td>2.306867</td>
      <td>84000033.0</td>
      <td>USA</td>
      <td>62813.715562</td>
      <td>NaN</td>
      <td>3144</td>
    </tr>
    <tr>
      <th>34</th>
      <td>New Jersey</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>40.2989</td>
      <td>-74.5210</td>
      <td>361986</td>
      <td>17306</td>
      <td>45562.0</td>
      <td>299118.0</td>
      <td>34.0</td>
      <td>4075.413834</td>
      <td>6280783.0</td>
      <td>NaN</td>
      <td>4.780848</td>
      <td>84000034.0</td>
      <td>USA</td>
      <td>70712.099156</td>
      <td>NaN</td>
      <td>24682</td>
    </tr>
    <tr>
      <th>35</th>
      <td>New Mexico</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>34.8405</td>
      <td>-106.2485</td>
      <td>106856</td>
      <td>1738</td>
      <td>36388.0</td>
      <td>68730.0</td>
      <td>35.0</td>
      <td>5096.076027</td>
      <td>1634917.0</td>
      <td>NaN</td>
      <td>1.626488</td>
      <td>84000035.0</td>
      <td>USA</td>
      <td>77970.926575</td>
      <td>NaN</td>
      <td>9761</td>
    </tr>
    <tr>
      <th>36</th>
      <td>New York</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>42.1657</td>
      <td>-74.9481</td>
      <td>695947</td>
      <td>34939</td>
      <td>87473.0</td>
      <td>573752.0</td>
      <td>36.0</td>
      <td>3578.393694</td>
      <td>20388862.0</td>
      <td>NaN</td>
      <td>5.013467</td>
      <td>84000036.0</td>
      <td>USA</td>
      <td>104807.865254</td>
      <td>NaN</td>
      <td>47904</td>
    </tr>
    <tr>
      <th>37</th>
      <td>North Carolina</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>35.6301</td>
      <td>-79.8064</td>
      <td>388552</td>
      <td>5516</td>
      <td>315979.0</td>
      <td>67057.0</td>
      <td>37.0</td>
      <td>3704.699543</td>
      <td>5546614.0</td>
      <td>NaN</td>
      <td>1.419630</td>
      <td>84000037.0</td>
      <td>USA</td>
      <td>52884.912058</td>
      <td>NaN</td>
      <td>24040</td>
    </tr>
    <tr>
      <th>38</th>
      <td>North Dakota</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>47.5289</td>
      <td>-99.7840</td>
      <td>82504</td>
      <td>1013</td>
      <td>76476.0</td>
      <td>5015.0</td>
      <td>38.0</td>
      <td>10826.415698</td>
      <td>1125121.0</td>
      <td>NaN</td>
      <td>1.227819</td>
      <td>84000038.0</td>
      <td>USA</td>
      <td>147641.661702</td>
      <td>NaN</td>
      <td>3252</td>
    </tr>
    <tr>
      <th>39</th>
      <td>Northern Mariana Islands</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>15.0979</td>
      <td>145.6739</td>
      <td>106</td>
      <td>2</td>
      <td>29.0</td>
      <td>75.0</td>
      <td>69.0</td>
      <td>192.223995</td>
      <td>17116.0</td>
      <td>NaN</td>
      <td>1.886792</td>
      <td>580.0</td>
      <td>MNP</td>
      <td>31038.734948</td>
      <td>NaN</td>
      <td>0</td>
    </tr>
    <tr>
      <th>40</th>
      <td>Ohio</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>40.3888</td>
      <td>-82.7649</td>
      <td>467432</td>
      <td>6946</td>
      <td>315453.0</td>
      <td>145033.0</td>
      <td>39.0</td>
      <td>3998.870743</td>
      <td>6416665.0</td>
      <td>NaN</td>
      <td>1.485992</td>
      <td>84000039.0</td>
      <td>USA</td>
      <td>54894.431564</td>
      <td>NaN</td>
      <td>46369</td>
    </tr>
    <tr>
      <th>41</th>
      <td>Oklahoma</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>35.5653</td>
      <td>-96.9289</td>
      <td>213245</td>
      <td>1874</td>
      <td>180810.0</td>
      <td>30561.0</td>
      <td>40.0</td>
      <td>5389.096862</td>
      <td>2222074.0</td>
      <td>NaN</td>
      <td>0.878801</td>
      <td>84000040.0</td>
      <td>USA</td>
      <td>56155.933415</td>
      <td>NaN</td>
      <td>15500</td>
    </tr>
    <tr>
      <th>42</th>
      <td>Oregon</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.5720</td>
      <td>-122.0709</td>
      <td>83243</td>
      <td>1027</td>
      <td>5870.0</td>
      <td>76346.0</td>
      <td>41.0</td>
      <td>1973.641315</td>
      <td>2088860.0</td>
      <td>NaN</td>
      <td>1.233737</td>
      <td>84000041.0</td>
      <td>USA</td>
      <td>49525.610535</td>
      <td>NaN</td>
      <td>7812</td>
    </tr>
    <tr>
      <th>43</th>
      <td>Pennsylvania</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>40.5908</td>
      <td>-77.2098</td>
      <td>415635</td>
      <td>11191</td>
      <td>238660.0</td>
      <td>165784.0</td>
      <td>42.0</td>
      <td>3246.643939</td>
      <td>3323124.0</td>
      <td>NaN</td>
      <td>2.692507</td>
      <td>84000042.0</td>
      <td>USA</td>
      <td>25957.872640</td>
      <td>NaN</td>
      <td>48800</td>
    </tr>
    <tr>
      <th>44</th>
      <td>Puerto Rico</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>18.2208</td>
      <td>-66.5901</td>
      <td>55532</td>
      <td>1185</td>
      <td>47406.0</td>
      <td>6941.0</td>
      <td>72.0</td>
      <td>1738.801526</td>
      <td>361504.0</td>
      <td>NaN</td>
      <td>2.133905</td>
      <td>630.0</td>
      <td>PRI</td>
      <td>11319.306108</td>
      <td>NaN</td>
      <td>2987</td>
    </tr>
    <tr>
      <th>45</th>
      <td>Rhode Island</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>41.6809</td>
      <td>-71.5118</td>
      <td>62137</td>
      <td>1413</td>
      <td>3939.0</td>
      <td>56785.0</td>
      <td>44.0</td>
      <td>5865.517043</td>
      <td>1608848.0</td>
      <td>NaN</td>
      <td>2.274007</td>
      <td>84000044.0</td>
      <td>USA</td>
      <td>151869.664826</td>
      <td>NaN</td>
      <td>5414</td>
    </tr>
    <tr>
      <th>46</th>
      <td>South Carolina</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>33.8569</td>
      <td>-80.9450</td>
      <td>229235</td>
      <td>4517</td>
      <td>118984.0</td>
      <td>105734.0</td>
      <td>45.0</td>
      <td>4452.276821</td>
      <td>2503921.0</td>
      <td>NaN</td>
      <td>1.970467</td>
      <td>84000045.0</td>
      <td>USA</td>
      <td>48631.969070</td>
      <td>NaN</td>
      <td>11748</td>
    </tr>
    <tr>
      <th>47</th>
      <td>South Dakota</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.2998</td>
      <td>-99.4388</td>
      <td>85304</td>
      <td>1091</td>
      <td>68011.0</td>
      <td>16202.0</td>
      <td>46.0</td>
      <td>9642.585448</td>
      <td>338369.0</td>
      <td>NaN</td>
      <td>1.278955</td>
      <td>84000046.0</td>
      <td>USA</td>
      <td>38248.522877</td>
      <td>NaN</td>
      <td>4840</td>
    </tr>
    <tr>
      <th>48</th>
      <td>Tennessee</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>35.7478</td>
      <td>-86.6923</td>
      <td>397522</td>
      <td>4905</td>
      <td>357347.0</td>
      <td>35270.0</td>
      <td>47.0</td>
      <td>5820.938228</td>
      <td>4675056.0</td>
      <td>NaN</td>
      <td>1.233894</td>
      <td>84000047.0</td>
      <td>USA</td>
      <td>68457.122340</td>
      <td>NaN</td>
      <td>23029</td>
    </tr>
    <tr>
      <th>49</th>
      <td>Texas</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>31.0545</td>
      <td>-97.5635</td>
      <td>1373354</td>
      <td>23110</td>
      <td>1022297.0</td>
      <td>266291.0</td>
      <td>48.0</td>
      <td>4523.549397</td>
      <td>11242753.0</td>
      <td>NaN</td>
      <td>1.757719</td>
      <td>84000048.0</td>
      <td>USA</td>
      <td>38773.620984</td>
      <td>NaN</td>
      <td>83297</td>
    </tr>
    <tr>
      <th>50</th>
      <td>Utah</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>40.1500</td>
      <td>-111.8624</td>
      <td>212844</td>
      <td>939</td>
      <td>150405.0</td>
      <td>61500.0</td>
      <td>49.0</td>
      <td>6639.013986</td>
      <td>1907788.0</td>
      <td>NaN</td>
      <td>0.441168</td>
      <td>84000049.0</td>
      <td>USA</td>
      <td>59507.579326</td>
      <td>NaN</td>
      <td>17138</td>
    </tr>
    <tr>
      <th>51</th>
      <td>Vermont</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.0459</td>
      <td>-72.7107</td>
      <td>4894</td>
      <td>79</td>
      <td>2899.0</td>
      <td>1916.0</td>
      <td>50.0</td>
      <td>784.308698</td>
      <td>578009.0</td>
      <td>NaN</td>
      <td>1.614221</td>
      <td>84000050.0</td>
      <td>USA</td>
      <td>92631.280359</td>
      <td>NaN</td>
      <td>722</td>
    </tr>
    <tr>
      <th>52</th>
      <td>Virgin Islands</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>18.3358</td>
      <td>-64.8963</td>
      <td>1633</td>
      <td>23</td>
      <td>1513.0</td>
      <td>97.0</td>
      <td>78.0</td>
      <td>1522.355222</td>
      <td>29293.0</td>
      <td>NaN</td>
      <td>1.408451</td>
      <td>850.0</td>
      <td>VIR</td>
      <td>27308.237312</td>
      <td>NaN</td>
      <td>89</td>
    </tr>
    <tr>
      <th>53</th>
      <td>Virginia</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>37.7693</td>
      <td>-78.1700</td>
      <td>251173</td>
      <td>4197</td>
      <td>25115.0</td>
      <td>221861.0</td>
      <td>51.0</td>
      <td>2942.679877</td>
      <td>3436348.0</td>
      <td>NaN</td>
      <td>1.670960</td>
      <td>84000051.0</td>
      <td>USA</td>
      <td>40259.391374</td>
      <td>NaN</td>
      <td>13338</td>
    </tr>
    <tr>
      <th>54</th>
      <td>Washington</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>47.4009</td>
      <td>-121.4905</td>
      <td>183081</td>
      <td>2867</td>
      <td>NaN</td>
      <td>172868.0</td>
      <td>53.0</td>
      <td>2308.541959</td>
      <td>3120146.0</td>
      <td>NaN</td>
      <td>1.663889</td>
      <td>84000053.0</td>
      <td>USA</td>
      <td>40974.259257</td>
      <td>NaN</td>
      <td>11119</td>
    </tr>
    <tr>
      <th>55</th>
      <td>West Virginia</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>38.4912</td>
      <td>-80.9545</td>
      <td>53572</td>
      <td>829</td>
      <td>34454.0</td>
      <td>18289.0</td>
      <td>54.0</td>
      <td>2989.263716</td>
      <td>1215319.0</td>
      <td>NaN</td>
      <td>1.547450</td>
      <td>84000054.0</td>
      <td>USA</td>
      <td>67813.577792</td>
      <td>NaN</td>
      <td>5730</td>
    </tr>
    <tr>
      <th>56</th>
      <td>Wisconsin</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>44.2685</td>
      <td>-89.6165</td>
      <td>437918</td>
      <td>3934</td>
      <td>343481.0</td>
      <td>90503.0</td>
      <td>55.0</td>
      <td>7521.218789</td>
      <td>4595523.0</td>
      <td>NaN</td>
      <td>0.898342</td>
      <td>84000055.0</td>
      <td>USA</td>
      <td>78927.867624</td>
      <td>NaN</td>
      <td>26188</td>
    </tr>
    <tr>
      <th>57</th>
      <td>Wyoming</td>
      <td>US</td>
      <td>2020-12-06 05:30:26</td>
      <td>42.7560</td>
      <td>-107.3025</td>
      <td>35941</td>
      <td>266</td>
      <td>29533.0</td>
      <td>6067.0</td>
      <td>56.0</td>
      <td>6197.052659</td>
      <td>417627.0</td>
      <td>NaN</td>
      <td>0.741649</td>
      <td>84000056.0</td>
      <td>USA</td>
      <td>72159.050658</td>
      <td>NaN</td>
      <td>2636</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[29]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">folium.plugins</span> <span class="kn">import</span> <span class="n">FastMarkerCluster</span>
<span class="c1">#Active or Confirmed?</span>
<span class="c1">#or should we do new cases by subtracting prev total month and new total</span>
<span class="n">april</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;april&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_april</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;orange&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">april</span><span class="p">)</span>
<span class="n">may</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;may&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_may</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">may</span><span class="p">)</span>
<span class="n">june</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;june&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_june</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;white&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">june</span><span class="p">)</span>
<span class="n">july</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;july&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_july</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;purple&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">july</span><span class="p">)</span>
<span class="n">aug</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;aug&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_aug</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;pink&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">aug</span><span class="p">)</span>
<span class="n">sept</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;sept&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_sept</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;gray&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">sept</span><span class="p">)</span>
<span class="n">octo</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;oct&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_oct</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;crimson&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">octo</span><span class="p">)</span>
<span class="n">nov</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;nov&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_nov</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;#3186cc&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">nov</span><span class="p">)</span>
<span class="n">dec</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">FeatureGroup</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;dec&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">data_amer_dec</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">])</span> <span class="ow">and</span> <span class="n">pd</span><span class="o">.</span><span class="n">notna</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">]):</span>
        <span class="n">folium</span><span class="o">.</span><span class="n">Circle</span><span class="p">(</span>
                <span class="n">location</span><span class="o">=</span> <span class="p">[</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Lat&#39;</span><span class="p">],</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;Long_&#39;</span><span class="p">]],</span>
                <span class="n">radius</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">popup</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;new cases&#39;</span><span class="p">],</span>
                <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
                <span class="n">color</span><span class="o">=</span><span class="s1">&#39;green&#39;</span><span class="p">,</span>
                <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.05</span>
        <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">dec</span><span class="p">)</span>

<span class="n">folium</span><span class="o">.</span><span class="n">LayerControl</span><span class="p">()</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">monthly_map3</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[29]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;folium.map.LayerControl at 0x7f437e65ff70&gt;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[30]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">monthly_map3</span>
<span class="c1">#with the new cases, we can see that it gets smaller over time suggesting that it is curbing. </span>
<span class="c1">#we can also see when there were spikes in cases</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[30]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[34]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#adding interaction terms for worldwide based on time </span>
<span class="c1">#adding dummies for continents(bc we saw earlier that the continents have different data)</span>
<span class="c1">#first for worldwide, let&#39;s look at the most up to date one so let&#39;s drop the duplicates</span>
<span class="c1">#data_worldwide_latest = data_worldwide.drop_duplicates(subset = [&#39;location&#39;],keep=&#39;last&#39;)</span>
<span class="n">terms</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">get_dummies</span><span class="p">(</span><span class="n">data_worldwide</span><span class="p">,</span> <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;continent&#39;</span><span class="p">])</span>

<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_Africa&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_Africa&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_Asia&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_Asia&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_Europe&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_Europe&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_North America&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_North America&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_Oceania&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_Oceania&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;term_South America&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;continent_South America&#39;</span><span class="p">]</span><span class="o">*</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">]</span>
<span class="c1">#terms[&#39;continent&#39;] = data_worldwide[&#39;continent&#39;]</span>
<span class="n">terms</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[34]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>iso_code</th>
      <th>location</th>
      <th>date</th>
      <th>total_cases</th>
      <th>new_cases</th>
      <th>new_cases_smoothed</th>
      <th>total_deaths</th>
      <th>new_deaths</th>
      <th>new_deaths_smoothed</th>
      <th>total_cases_per_million</th>
      <th>...</th>
      <th>continent_Europe</th>
      <th>continent_North America</th>
      <th>continent_Oceania</th>
      <th>continent_South America</th>
      <th>term_Africa</th>
      <th>term_Asia</th>
      <th>term_Europe</th>
      <th>term_North America</th>
      <th>term_Oceania</th>
      <th>term_South America</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>AFG</td>
      <td>Afghanistan</td>
      <td>2020-01-23</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>AFG</td>
      <td>Afghanistan</td>
      <td>2020-01-24</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>AFG</td>
      <td>Afghanistan</td>
      <td>2020-01-25</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>AFG</td>
      <td>Afghanistan</td>
      <td>2020-01-26</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>AFG</td>
      <td>Afghanistan</td>
      <td>2020-01-27</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>60857</th>
      <td>ZWE</td>
      <td>Zimbabwe</td>
      <td>2020-12-01</td>
      <td>10129.0</td>
      <td>179.0</td>
      <td>104.429</td>
      <td>277.0</td>
      <td>1.0</td>
      <td>0.429</td>
      <td>681.494</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>60858</th>
      <td>ZWE</td>
      <td>Zimbabwe</td>
      <td>2020-12-02</td>
      <td>10129.0</td>
      <td>0.0</td>
      <td>88.714</td>
      <td>277.0</td>
      <td>0.0</td>
      <td>0.429</td>
      <td>681.494</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>60859</th>
      <td>ZWE</td>
      <td>Zimbabwe</td>
      <td>2020-12-03</td>
      <td>10424.0</td>
      <td>295.0</td>
      <td>114.429</td>
      <td>280.0</td>
      <td>3.0</td>
      <td>0.857</td>
      <td>701.342</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>60860</th>
      <td>ZWE</td>
      <td>Zimbabwe</td>
      <td>2020-12-04</td>
      <td>10547.0</td>
      <td>123.0</td>
      <td>119.000</td>
      <td>281.0</td>
      <td>1.0</td>
      <td>0.857</td>
      <td>709.618</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>60861</th>
      <td>ZWE</td>
      <td>Zimbabwe</td>
      <td>2020-12-05</td>
      <td>10617.0</td>
      <td>70.0</td>
      <td>113.571</td>
      <td>291.0</td>
      <td>10.0</td>
      <td>2.286</td>
      <td>714.328</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>60862 rows × 63 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[35]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#let&#39;s first see if the interaction terms have an effect on cases (then later do deaths)</span>
<span class="c1">#let&#39;s do a random forest fit since earlier we saw that it was the best fit</span>
<span class="c1">#terms = terms.fillna()</span>
<span class="c1">#print(terms)</span>
<span class="c1">#terms = terms.dropna()</span>
<span class="n">terms</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="n">terms</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">notna</span><span class="p">()]</span>
<span class="n">term</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;month&#39;</span><span class="p">,</span> <span class="s1">&#39;term_Africa&#39;</span><span class="p">,</span> <span class="s1">&#39;term_North America&#39;</span><span class="p">,</span><span class="s1">&#39;term_South America&#39;</span><span class="p">,</span><span class="s1">&#39;term_Asia&#39;</span><span class="p">,</span>
        <span class="s1">&#39;term_Europe&#39;</span><span class="p">,</span> <span class="s1">&#39;term_Oceania&#39;</span><span class="p">,</span> <span class="s1">&#39;continent_Africa&#39;</span><span class="p">,</span> <span class="s1">&#39;continent_North America&#39;</span><span class="p">,</span>
        <span class="s1">&#39;continent_South America&#39;</span><span class="p">,</span><span class="s1">&#39;continent_Asia&#39;</span><span class="p">,</span> <span class="s1">&#39;continent_Europe&#39;</span><span class="p">,</span> <span class="s1">&#39;continent_Oceania&#39;</span><span class="p">]</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="n">term</span><span class="p">]</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">terms</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">]</span>

<span class="n">reg</span> <span class="o">=</span> <span class="n">lm</span><span class="o">.</span><span class="n">LinearRegression</span><span class="p">()</span>
<span class="n">reg</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span> 

<span class="c1">#months = terms[&#39;month&#39;]</span>
<span class="c1">#terms = reg.predict(terms[months])</span>
<span class="n">prediction</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">terms</span><span class="p">[</span><span class="n">term</span><span class="p">])</span>
<span class="n">terms</span><span class="p">[</span><span class="s1">&#39;pred&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">prediction</span>
<span class="c1">#plt.scatter(terms[&#39;month&#39;], terms[&#39;total_cases&#39;], label = &quot;actual&quot;)</span>
<span class="c1">#plt.scatter(terms[&#39;month&#39;], terms[&#39;pred&#39;], label = &quot;predicted&quot;)</span>
<span class="c1">#sns.violinplot(terms[&#39;continent&#39;], terms[&#39;total_cases&#39;])</span>
<span class="c1">#plt.legend()</span>

<span class="n">coef</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">coef_</span>
<span class="n">intercept</span> <span class="o">=</span> <span class="n">reg</span><span class="o">.</span><span class="n">intercept_</span>

<span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s1">&#39;total cases = </span><span class="si">{</span><span class="n">intercept</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="se">\</span>
<span class="s1">        </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="se">\</span>
<span class="s1">        </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">4</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">4</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">5</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">5</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">6</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">6</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="se">\</span>
<span class="s1">        </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">7</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">7</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">8</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">8</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">9</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">9</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="se">\</span>
<span class="s1">        </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">10</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">10</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">11</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">11</span><span class="p">]</span><span class="si">}</span><span class="s1"> + </span><span class="si">{</span><span class="n">coef</span><span class="p">[</span><span class="mi">12</span><span class="p">]</span><span class="si">}{</span><span class="n">term</span><span class="p">[</span><span class="mi">12</span><span class="p">]</span><span class="si">}</span><span class="s1">&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>total cases = -10254568.833417684 + 2951367.84519253month +         -2946254.333301725term_Africa + -2879607.558967636term_North America + -2831780.498426022term_South America +         -2911233.505744149term_Asia + -2921517.9141034term_Europe + -2950757.2817984014term_Oceania +         10232844.02824028continent_Africa + 9977439.729240108continent_North America + 9757729.012541993continent_South America +         10094610.549450697continent_Asia + 10136855.957843516continent_Europe + 10253948.31146027continent_Oceania
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[36]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#starting to look at death rates</span>
<span class="c1">#data_worldwide</span>
<span class="n">total_cases</span> <span class="o">=</span> <span class="n">terms</span><span class="o">.</span><span class="n">groupby</span><span class="p">([</span><span class="s1">&#39;month&#39;</span><span class="p">])[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="c1">#total_deaths = terms.groupby([&#39;month&#39;])[&#39;total_deaths&#39;].mean()</span>

<span class="n">pred_cases</span> <span class="o">=</span> <span class="n">terms</span><span class="o">.</span><span class="n">groupby</span><span class="p">([</span><span class="s1">&#39;month&#39;</span><span class="p">])[</span><span class="s1">&#39;pred&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
<span class="c1">#new_deaths = data_worldwide_latest.groupby([&#39;month&#39;])[&#39;new_deaths&#39;].mean()</span>

<span class="c1">#months = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]</span>
<span class="c1">#plt.plot(months, total_deaths, label = &#39;total deaths&#39;)</span>
<span class="c1">#plt.plot(months, total_cases, label = &#39;total cases&#39;)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span> <span class="n">total_cases</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s1">&#39;actual&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">pred_cases</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s1">&#39;pred&#39;</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;month&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;# total&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;actual vs predicted based on interaction terms&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>
<span class="c1">#data = {</span>
<span class="c1">#    &#39;month&#39;: months,</span>
<span class="c1">#    &#39;cases&#39;: cases,</span>
<span class="c1">#    &#39;deaths&#39;: deaths</span>
<span class="c1">#}</span>
<span class="c1">#df = pd.DataFrame(data)</span>
<span class="c1">#df</span>
<span class="c1">#now we can see that the new deaths compared to the new cases are quite low. WAIT IS THIS CORRECT BC IS IT THIS LOW??</span>
<span class="c1">#but what other factors are there? we can add interaction terms for the things in the table </span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[36]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.legend.Legend at 0x7f437d6d2d90&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[37]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">combined_data</span> <span class="o">=</span> <span class="n">combined_data</span><span class="o">.</span><span class="n">drop_duplicates</span><span class="p">(</span><span class="n">subset</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">])</span>
<span class="n">combined_data</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[37]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Place</th>
      <th>Start date</th>
      <th>End date</th>
      <th>Level</th>
      <th>update</th>
      <th>Confirmed</th>
      <th>total_cases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>China</td>
      <td>Xiangyang</td>
      <td>2020-01-28</td>
      <td>2020-03-25</td>
      <td>City</td>
      <td>2020-02-04</td>
      <td>True</td>
      <td>94821.0</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Philippines</td>
      <td>Soccsksargen</td>
      <td>2020-03-23</td>
      <td>2020-04-30</td>
      <td>Region</td>
      <td>2020-03-12</td>
      <td>False</td>
      <td>456562.0</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Montenegro</td>
      <td>Tuzi</td>
      <td>2020-03-24</td>
      <td>NaT</td>
      <td>Municipality</td>
      <td>2020-03-16</td>
      <td>False</td>
      <td>43390.0</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Fiji</td>
      <td>Lautoka</td>
      <td>2020-03-20</td>
      <td>2020-04-07</td>
      <td>City</td>
      <td>2020-03-19</td>
      <td>False</td>
      <td>46.0</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Liberia</td>
      <td>Margibi</td>
      <td>2020-03-23</td>
      <td>2020-04-11</td>
      <td>County</td>
      <td>2020-03-21</td>
      <td>False</td>
      <td>1779.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>205</th>
      <td>Cuba</td>
      <td>NaN</td>
      <td>2020-03-23</td>
      <td>2020-07-20</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>9893.0</td>
    </tr>
    <tr>
      <th>206</th>
      <td>Costa Rica</td>
      <td>NaN</td>
      <td>2020-03-23</td>
      <td>2020-08-01</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>157472.0</td>
    </tr>
    <tr>
      <th>207</th>
      <td>Bangladesh</td>
      <td>NaN</td>
      <td>2020-03-26</td>
      <td>2020-04-29</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>498293.0</td>
    </tr>
    <tr>
      <th>208</th>
      <td>Albania</td>
      <td>NaN</td>
      <td>2020-03-10</td>
      <td>2020-04-19</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>52004.0</td>
    </tr>
    <tr>
      <th>209</th>
      <td>Zimbabwe</td>
      <td>NaN</td>
      <td>2020-03-30</td>
      <td>2020-07-02</td>
      <td>National</td>
      <td>2020-09-01</td>
      <td>True</td>
      <td>12047.0</td>
    </tr>
  </tbody>
</table>
<p>98 rows × 8 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[38]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">colors</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">random</span><span class="o">.</span><span class="n">rand</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">combined_data</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">combined_data</span><span class="p">[</span><span class="s1">&#39;Start date&#39;</span><span class="p">],</span> <span class="n">combined_data</span><span class="p">[</span><span class="s1">&#39;End date&#39;</span><span class="p">],</span> <span class="n">s</span><span class="o">=</span><span class="p">(</span><span class="n">combined_data</span><span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">])</span><span class="o">/</span><span class="mi">5000</span><span class="p">,</span>  <span class="n">c</span><span class="o">=</span><span class="n">colors</span><span class="p">)</span>
<span class="c1">#for index, row in combined_data.iterrows():</span>
<span class="c1">#    plt.annotate(row[&#39;Country&#39;], (row[&#39;Start date&#39;], row[&#39;End date&#39;]),size=10)</span>
    
    
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;start date&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">90</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;end date&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;total cases with respect to start lockdown date&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[38]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0.5, 1.0, &#39;total cases with respect to start lockdown date&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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Q0e8wHEmmaGwLWTWnHyFzPdegEwQXw9sJzOU99msu78A7E/mNfwO8GHn3DZv3gVkNqBfRCZU/YXMDh4dvibe/dq/9u3rfYNMYFnutRlLZo1jHfAamR0aXvam5ZLzdfXmXQvc4fX7ETI7C5R7j+954JGOnscsPwU+bJm9d3+WR/tzyWzHtx74O5ltPx/z5v2IzA+jf5L54XCbV8/bnHOryQS+q8zsU865rWTW+H2PTIDan93f178hs9fwf4AVQCuZMNem/XvwGTIhLOd7Mk/nkdnWbjuZwHxn1ry9fbZvAw70XpN7vcB5Bpmh5hVkXptbyawRFOkR232zFBGRgc3MLiKz0f+xpa5FRKQQtGZPRERExMcU9kRERER8TMO4IiIiIj6mNXsiIiIiPqawJyIiIuJjOqhyB4YPH+4mTZpU6jJERERE9mrevHlbnXMjcs1T2OvApEmTqKurK3UZIiIiIntlZqs6mqdhXBEREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPRHpV5YvWseCF5aRTqdLXYqISL8QKnUBIiL5+uuvnuB3P3gQCwSY8+5pfPNXnyx1SSIifZ7Cnoj0G/f/5iliLQkAnn/0deKtCSJl4RJXJSLSt2kYV0T6jSkH7UM4EiIQNIaOqiEc1e9VEZG90TeliPQbX/npx7j754/RsKuFj3z2BMys1CWJiPR5Cnsi0m+UVUS58MrTS12GiEi/omFcERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxMYU9ERERER9T2BMRERHxsaKFPTPbx8yeMLPFZrbQzD7vTR9qZo+Z2Vve3yHe9JPMbJ6Zve79fW9WX4d605ea2c/MzDpYZs52ZjbBq2W+mb1mZqcV63GLiOQrmUzx1srNbN7WUOpSRMTHQkXsOwlc4Zx72cyqgXlm9hhwEfC4c+57ZvZV4KvAVcBW4Azn3Hozmwk8Cozz+roZuBR4HngIOBV4OMcyO2r3DeAe59zNZnagN29S4R+yiEh+nqlbxvW/eJhUKk0ylebg6eO48Yr3U1UR7fA+zjkW1q/mr2ueY1XTJkIWZNaQyXxon6MZXTakF6sXkf6kaGHPObcB2OBdbzCzxWTC25nA8V6zO4Angaucc/Oz7r4QKDOzKDAUGOScmwtgZncCH6Bd2DOzMZ20c8Agr2kNsL6Qj1VEpCs2bKnnmz95gFg8+fa0Vxev48abH+XGK96f8z5bY/V8Zf5vWNO8hVg6icMB8FbDev685llOHjWLrxxwFqFAsFceg4j0H8Vcs/c2M5sEzAZeAEZ5QRDn3AYzG5njLmcB851zMTMbB6zNmreWd9b4Zeus3bXAP83sMqASOLHbD0ZEpIf+9exi0un0btMSyRTPzFtGLJ4kGtn9q7k+0cylL/4v2+INpFy7+7kUOPjXpldpSsW4/qCP0cGWLiIyQBV9Bw0zqwL+CnzBOVefR/sZwE3Ap9sm5Wjmct21k3bnArc758YDpwG/M7M9HruZXWpmdWZWt2XLlr2VKiLSLa2xJKnUnl9jzkGqXQgE+PWyR9geb9wj6GWLpRO8sO1NXti2pKC1ikj/V9SwZ2ZhMkHvD865v3mTN3lDrm1Dr5uz2o8H/g5c4Jxb5k1eC4zP6nY8sN7Mgmb2ine5rqN23vVPAvcAeMO8ZcDw9vU6537lnKt1ztWOGDGiJw9dRKRD7z58CuHw7sOtZsb0yaOoKIvsNr0lFefh9fNIutRe+21JxfnjqicLWaqI+EAx98Y14DZgsXPuR1mz7gcu9K5fCNzntR8MPAhc7Zx7tq2xN+TbYGZHen1eANznnEs552Z5l2s6aud1sxo4wVvOAWTCnlbdiUhJTNt3FB878zAi4SBl0TAV5RGGDCrnW5f91x5tX9+5kuCeAxEdmr9jeadrAEVk4CnmNnvHAB8HXjezV7xpXwO+B9xjZp8kE8LO9ub9DzAF+KaZfdObdrJzbjPwGeB2oJzMDhe59sSlk3ZXAL82sy+SGdq9yDmXayhYRKRXfPLsozntuBnULVhNTXU5R83el3Boz50rmpOxLvUbMCOWilMRKitUqSLSzxVzb9xnyL0dHXhr2dq1vwG4oYO+6oCZeSwzZzvn3CIy4VNEpM8YM7KGM957UKdtBoXLc26k3JmyYGTvjURkwNAZNERE+rCDBk/Ke+9awzh6+AEEujDsKyL+p28EEZE+LBwI8aHxRxEJ7H0gJhoIce7E43qhKhHpTxT2RET6uIv2PZF9KkYQsY4DX1kgzJnjjuDgwZN6rzAR6RcU9kRE+rhoMMzNtZ/liOHTiARChO2dHTnKgxHKAmE+Pum9/M/UM0pYpYj0Vb1yBg0REemZilCU7x5yIZtad/LguhdZ0bSZcCDIIYP35eQxcyjXThki0gGFPRGRfmRU2WAu3u/kUpchIv2IhnFFREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0RERMTHFPZEREREfExhT0SkhFKpNM65UpchIj6msCciUiJvvLmBU9//Q7545Z9KXYqI+JjCnohIiazfsAMzY8WKLaUuRUR8LFTqAkREBqrj330A0WiYiROGlboUEfExhT0RkRIJBIxjjtq/1GWIiM9pGFdERETExxT2RERERHxMYU9ERETExxT2RERERHxMO2iIiPQRLckEczeuoj4eY3C0nKNGTyAa1Ne0iPSMvkVEREqsJZngppef5O6lrxE0wzmHmeGAj0+d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eqNDk0YM4YGvXFScokRECszM5jnnanPNK9pGKc65Z8i9HR3ACTna3wDc0EFfdcDMPJbZYTvn3LV7u7+I+M8/Xl789nBwV2za1cCCNRuZuc/oIlQlItJ7dMAqEfG1BWs30pJIduOextJN2wpej4hIb1PYExFfa4l3J+hBOu1o7VZIFBHpWxT2RMTXhldXdLg9SWdCQaOmvKzg9YiI9DaFPRHxtZNm7k95JNzl+yVSaY7aX8fbFJH+T2FPRHztsP3GU13etUO2BMx474H7MbiyvEhViYj0HoU9EfE1M+PyU46hrAtnxIiEglxywuFFrEpEpPco7ImI751ZeyAfPfLgvAJfNBziOx85hWljdBYdEfEHnfxRRAaEr5xxHGMGV/Ozfz4HDprbnTatIhKmsizCdz5yCkdPnViiKkVECk9hT0QGjI+9aw4fOepg/vnaW9zz/GtsaWgiGAgwcfhgzj9mNkdOmUAg0J19d0VE+i6FPREZUCKhEKfPOYDT5xxQ6lJERHqFttkTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8TGFPREREREfU9gTERER8bFQqQsQERGIxxKseG0VKxeuIdYcp6wyyuSDJzJxxnjCkXCpyxORfkxhT0SkhFYsWM1dN93L0395nnAkRDqdJp12BIMBMCOVTPHe847lo185k/FTx5a6XBHph8w5V+oa+qTa2lpXV1dX6jJExKcS8QS3f/Mu7vv5IyTiSdKpdIdtA8EA4UiIc776Ac69+kMEQ8FerFRE+gMzm+ecq801T2v2RER6WWtzjKtOuo5lr6wk1hLfa/t0Kk2sJc5dN93Hwufe5Lr7rtLQrojkTTtoiIj0Iucc137o/7F0/oq8gl62WHOM1/+zmJsu+HmRqhMRP1LYExHpRY/e/gQLn32DeGuiW/ePtcR54YF5PHffSwWuTET8SmFPRKSXxGMJbv7i7bQ2xXrUT2tzjB9/+hZSqVSBKhMRP1PY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SpiaPREREZESpmZPREREpISp2RMREREpYWr2REREREqYmj0RERGREqZmT0RERKSEqdkTERERKWFq9kRERERKmJo9ERERkRKmZk9ERESkhKnZExERESlhavZERERESpiaPREREZESpmZPREREpIT5811Af7R9Yx0//uxv2LBiC4dNH8/nfjyHqkEV+S5LRERESpCavT4WaY1w41n/wc7Nu0nEE+zYtIsta3fwk2e/iZnluzwREREpMbqM28feWbqJxvpmEvEEALFIjFUL17FnV1OeKxMREZFSpGavj5VVhInHEvstcwlHMBzIU0UiIiJSytTs9bFRE4cz+8JphCtCmBnh8hBX3Hgh4fJQvksTERGREqR79vqYmXHzHTfw3ANz2bR6GxOmjmX2BdPyXZaIiIiUKDV7eeB5HmdccUK+yxAREZF+QJdxRUREREqYmj0RERGREqZmT0RERKSEqdkTERERKWFq9kRERERKmJo9ERERkRKmZk9ERESkhKnZExERESlhavZERERESpiaPREREZESpmZPREREpISp2RMREREpYWr2REREREqYmj0RERGREqZmT0RERKSEqdkTERERKWFq9kRERERKmJo9ERERkRKmZk9ERESkhKnZExERESlhavZERERESpg55/JdQ0Eys+3AO/muoxuGAjvyXUQBUA7pKZck5ZAd5ZekHDKnrJL6IoexzrmadCvU7JUIM5vnnJuR7zryTTmkp1ySlEN2lF+ScsicskrKdw66jCsiIiJSwtTsiYiIiJQwNXul47Z8F1AglEN6yiVJOWRH+SUph8wpq6S85qB79kRERERKmM7siYiIiJQwNXsiIiIiJUzNnoiIiEgJU7NXYszsnHzXkC9mNt7MLjWzw/NdS6HS8aHjIxd0HOk46q7+eswUyvGiZq/03J7vAvqKmT3U7vdLgKeBi4CHzWxOvuoqcDo+dHzkgo4jHUfd1S+OmUI9Xvz5emPpOTN7pKNVwJC+rCXPxrb7/SbgTOfcGjMbCjwF/DYvVeWZjo99dHxkQcfRPjqOMqRjBijQ40XNXnE6BbgaaDxguQHH9305edN+3iC/c24NgHNuh5kl8lRTIdDxkaTjIzs6jpJ0HGVOx0yBHi9q9orTK0Czc+65A1eY2bI81JMvU82sgeQXScjMap1zW8wsCPjyXFs+6fhI0vGRHR1HSTqOMqdj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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here, we can discuss the correlation of different factors such as population density, older individuals (70 or older), extreme poverty, cardiovascular death rate, smokers, as well as handwashing facilities and their correlation with total and new cases as well as deaths. This allows for an understand to see where it seems to be strongly correlated whereas others where it is not. Without having this, there are many who have incorrect assumptions of correlations that may not exist and having data to see it would definitely be beneficial.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[111]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Have the x-values with the heatmap dataframe</span>
<span class="n">heatmap_x</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;total_cases&#39;</span><span class="p">,</span> <span class="s1">&#39;new_cases&#39;</span><span class="p">,</span> <span class="s1">&#39;total_deaths&#39;</span><span class="p">,</span> <span class="s1">&#39;new_deaths&#39;</span><span class="p">,</span> <span class="s1">&#39;new_tests&#39;</span><span class="p">,</span> <span class="s1">&#39;positive_rate&#39;</span><span class="p">,</span> <span class="s1">&#39;tests_units&#39;</span><span class="p">]</span>
<span class="n">data_worldwide_x</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="n">heatmap_x</span><span class="p">]</span>
<span class="n">data_worldwide_x</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[111]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>total_cases</th>
      <th>new_cases</th>
      <th>total_deaths</th>
      <th>new_deaths</th>
      <th>new_tests</th>
      <th>positive_rate</th>
      <th>tests_units</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>60857</th>
      <td>10129.0</td>
      <td>179.0</td>
      <td>277.0</td>
      <td>1.0</td>
      <td>1029.0</td>
      <td>0.088</td>
      <td>tests performed</td>
    </tr>
    <tr>
      <th>60858</th>
      <td>10129.0</td>
      <td>0.0</td>
      <td>277.0</td>
      <td>0.0</td>
      <td>1862.0</td>
      <td>0.069</td>
      <td>tests performed</td>
    </tr>
    <tr>
      <th>60859</th>
      <td>10424.0</td>
      <td>295.0</td>
      <td>280.0</td>
      <td>3.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>60860</th>
      <td>10547.0</td>
      <td>123.0</td>
      <td>281.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>60861</th>
      <td>10617.0</td>
      <td>70.0</td>
      <td>291.0</td>
      <td>10.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>60862 rows × 7 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[112]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Have the y-values with the heatmap dataframe</span>
<span class="n">heatmap_y</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;population_density&#39;</span><span class="p">,</span> <span class="s1">&#39;aged_70_older&#39;</span><span class="p">,</span> <span class="s1">&#39;extreme_poverty&#39;</span><span class="p">,</span> <span class="s1">&#39;cardiovasc_death_rate&#39;</span><span class="p">,</span> <span class="s1">&#39;handwashing_facilities&#39;</span><span class="p">]</span>
<span class="n">data_worldwide_y</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="n">heatmap_y</span><span class="p">]</span>
<span class="n">data_worldwide_y</span><span class="p">[</span><span class="s1">&#39;smokers&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;female_smokers&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">data_worldwide</span><span class="p">[</span><span class="s1">&#39;male_smokers&#39;</span><span class="p">]</span>
<span class="n">data_worldwide_y</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>&lt;ipython-input-112-7a567ceb2565&gt;:4: SettingWithCopyWarning:


A value is trying to be set on a copy of a slice from a DataFrame.
Try using .loc[row_indexer,col_indexer] = value instead

See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy

</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt output_prompt">Out[112]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>population_density</th>
      <th>aged_70_older</th>
      <th>extreme_poverty</th>
      <th>cardiovasc_death_rate</th>
      <th>handwashing_facilities</th>
      <th>smokers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>54.422</td>
      <td>1.337</td>
      <td>NaN</td>
      <td>597.029</td>
      <td>37.746</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>54.422</td>
      <td>1.337</td>
      <td>NaN</td>
      <td>597.029</td>
      <td>37.746</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>54.422</td>
      <td>1.337</td>
      <td>NaN</td>
      <td>597.029</td>
      <td>37.746</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>54.422</td>
      <td>1.337</td>
      <td>NaN</td>
      <td>597.029</td>
      <td>37.746</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>54.422</td>
      <td>1.337</td>
      <td>NaN</td>
      <td>597.029</td>
      <td>37.746</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>60857</th>
      <td>42.729</td>
      <td>1.882</td>
      <td>21.4</td>
      <td>307.846</td>
      <td>36.791</td>
      <td>32.3</td>
    </tr>
    <tr>
      <th>60858</th>
      <td>42.729</td>
      <td>1.882</td>
      <td>21.4</td>
      <td>307.846</td>
      <td>36.791</td>
      <td>32.3</td>
    </tr>
    <tr>
      <th>60859</th>
      <td>42.729</td>
      <td>1.882</td>
      <td>21.4</td>
      <td>307.846</td>
      <td>36.791</td>
      <td>32.3</td>
    </tr>
    <tr>
      <th>60860</th>
      <td>42.729</td>
      <td>1.882</td>
      <td>21.4</td>
      <td>307.846</td>
      <td>36.791</td>
      <td>32.3</td>
    </tr>
    <tr>
      <th>60861</th>
      <td>42.729</td>
      <td>1.882</td>
      <td>21.4</td>
      <td>307.846</td>
      <td>36.791</td>
      <td>32.3</td>
    </tr>
  </tbody>
</table>
<p>60862 rows × 6 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[113]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Correlation map with x and y respective values</span>
<span class="n">corrx</span> <span class="o">=</span> <span class="n">data_worldwide_x</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
<span class="n">corry</span> <span class="o">=</span> <span class="n">data_worldwide_y</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">corrx</span><span class="p">,</span> <span class="n">xticklabels</span><span class="o">=</span><span class="n">corrx</span><span class="o">.</span><span class="n">columns</span><span class="p">,</span> <span class="n">yticklabels</span><span class="o">=</span><span class="n">corry</span><span class="o">.</span><span class="n">columns</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[113]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7f88cff36580&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From this, it is clear to see analyze that there is a high correlation with population density with number of cases, deaths, but not positivity rate. Not only that, but there is a high correlation with older individuals (70 or older), extreme poverty, cardiovascular death rate, and handwashing facilities with everything but positivity rate. Areas with many smokers do not have a high correlation rate with cases except do have a high correlation with positivity rates which is very interesting. This shows that more focus needs to go onto areas with high population density, extreme poverty, older individuals, especially with the vaccine and preventing spikes.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Conclusion">Conclusion<a class="anchor-link" href="#Conclusion">&#182;</a></h3><p>After looking more into detail of the specifics of COVID-19 cases, it is clear that America had many COVID-19 cases, and not only that but worldwide, the start lockdown dates do not seem to have a direct correlation with a higher amount of total cases as we initially predicted. However, another one of our initial predictions regarding population density, poverty, older inviduals, and handwashing facilities all seemed to have a high amount of correlation to total cases.</p>
<p>What can really be seen is that looking at the worldwide map of COVID-19 cases over time, there seemed to be a high amount of cases in China, however they had quickly come down compared to America which rose up and consistently stayed high. Then it start going lower and then spiked up again recently. Our goal with this analysis is to figure out how to lower the amount of COVID-19 cases and eventually bring it to 0- so what did China do in order to lower their cases and what can America do to attempt to implement a similar thing? Definitely a lockdown seems to be a valuable option though an earlier start for a lockdown did not seem to have a high correlation with a low amount of total cases, it may allow for a better situation with new cases.</p>
<p>Analyzing COVID-19 data first throughout the world based on continents and then based on time we feel as though gave a great visualization in order to really understand what was happening and at what time periods certain places had a spike and why. This will also help gauge when to release the vaccine in those locations and before what time it would be important to do so. Not only that, but looking at America per month and seeing the new cases allowed to see for what reasons there would be spikes and it is clear that during holiday seasons when family and friends are visiting it spikes. There are many factors that cause for spikes, and though there is a vaccine, it may not get to everyone soon enough and before losing more lives it is important to understand the pattern and see where we can improve, happy holidays everyone!</p>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>