<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>dlnd_language_translation</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
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
    color: #000 !important;
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
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
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
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
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
.fa-gittip:before {
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
.fa-pied-piper:before {
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
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
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
span#login_widget {
  float: right;
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
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
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
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
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
  vertical-align: baseline;
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
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
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
[dir="rtl"] #new-menu {
  text-align: right;
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
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
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
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
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
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
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
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
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
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
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
  padding: 0;
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
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
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
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
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
.text_cell.unrendered .text_cell_render {
  display: none;
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
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
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
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
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
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
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
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
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
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
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
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
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
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

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
}

@media print {
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
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
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

<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Language-Translation">Language Translation<a class="anchor-link" href="#Language-Translation">&#182;</a></h1><p>In this project, you’re going to take a peek into the realm of neural network machine translation.  You’ll be training a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French.</p>
<h2 id="Get-the-Data">Get the Data<a class="anchor-link" href="#Get-the-Data">&#182;</a></h2><p>Since translating the whole language of English to French will take lots of time to train, we have provided you with a small portion of the English corpus.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">import</span> <span class="nn">helper</span>
<span class="kn">import</span> <span class="nn">problem_unittests</span> <span class="k">as</span> <span class="nn">tests</span>

<span class="n">source_path</span> <span class="o">=</span> <span class="s1">&#39;data/small_vocab_en&#39;</span>
<span class="n">target_path</span> <span class="o">=</span> <span class="s1">&#39;data/small_vocab_fr&#39;</span>
<span class="n">source_text</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_data</span><span class="p">(</span><span class="n">source_path</span><span class="p">)</span>
<span class="n">target_text</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_data</span><span class="p">(</span><span class="n">target_path</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Explore-the-Data">Explore the Data<a class="anchor-link" href="#Explore-the-Data">&#182;</a></h2><p>Play around with view_sentence_range to view different parts of the data.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[2]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">view_sentence_range</span> <span class="o">=</span> <span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">10</span><span class="p">)</span>

<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Dataset Stats&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Roughly the number of unique words: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="nb">len</span><span class="p">({</span><span class="n">word</span><span class="p">:</span> <span class="kc">None</span> <span class="k">for</span> <span class="n">word</span> <span class="ow">in</span> <span class="n">source_text</span><span class="o">.</span><span class="n">split</span><span class="p">()})))</span>

<span class="n">sentences</span> <span class="o">=</span> <span class="n">source_text</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="p">)</span>
<span class="n">word_counts</span> <span class="o">=</span> <span class="p">[</span><span class="nb">len</span><span class="p">(</span><span class="n">sentence</span><span class="o">.</span><span class="n">split</span><span class="p">())</span> <span class="k">for</span> <span class="n">sentence</span> <span class="ow">in</span> <span class="n">sentences</span><span class="p">]</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Number of sentences: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">sentences</span><span class="p">)))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Average number of words in a sentence: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">average</span><span class="p">(</span><span class="n">word_counts</span><span class="p">)))</span>

<span class="nb">print</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;English sentences </span><span class="si">{}</span><span class="s1"> to </span><span class="si">{}</span><span class="s1">:&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="o">*</span><span class="n">view_sentence_range</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">source_text</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="p">)[</span><span class="n">view_sentence_range</span><span class="p">[</span><span class="mi">0</span><span class="p">]:</span><span class="n">view_sentence_range</span><span class="p">[</span><span class="mi">1</span><span class="p">]]))</span>
<span class="nb">print</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;French sentences </span><span class="si">{}</span><span class="s1"> to </span><span class="si">{}</span><span class="s1">:&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="o">*</span><span class="n">view_sentence_range</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">target_text</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="p">)[</span><span class="n">view_sentence_range</span><span class="p">[</span><span class="mi">0</span><span class="p">]:</span><span class="n">view_sentence_range</span><span class="p">[</span><span class="mi">1</span><span class="p">]]))</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Dataset Stats
Roughly the number of unique words: 227
Number of sentences: 137861
Average number of words in a sentence: 13.225277634719028

English sentences 0 to 10:
new jersey is sometimes quiet during autumn , and it is snowy in april .
the united states is usually chilly during july , and it is usually freezing in november .
california is usually quiet during march , and it is usually hot in june .
the united states is sometimes mild during june , and it is cold in september .
your least liked fruit is the grape , but my least liked is the apple .
his favorite fruit is the orange , but my favorite is the grape .
paris is relaxing during december , but it is usually chilly in july .
new jersey is busy during spring , and it is never hot in march .
our least liked fruit is the lemon , but my least liked is the grape .
the united states is sometimes busy during january , and it is sometimes warm in november .

French sentences 0 to 10:
new jersey est parfois calme pendant l&#39; automne , et il est neigeux en avril .
les états-unis est généralement froid en juillet , et il gèle habituellement en novembre .
california est généralement calme en mars , et il est généralement chaud en juin .
les états-unis est parfois légère en juin , et il fait froid en septembre .
votre moins aimé fruit est le raisin , mais mon moins aimé est la pomme .
son fruit préféré est l&#39;orange , mais mon préféré est le raisin .
paris est relaxant en décembre , mais il est généralement froid en juillet .
new jersey est occupé au printemps , et il est jamais chaude en mars .
notre fruit est moins aimé le citron , mais mon moins aimé est le raisin .
les états-unis est parfois occupé en janvier , et il est parfois chaud en novembre .
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Implement-Preprocessing-Function">Implement Preprocessing Function<a class="anchor-link" href="#Implement-Preprocessing-Function">&#182;</a></h2><h3 id="Text-to-Word-Ids">Text to Word Ids<a class="anchor-link" href="#Text-to-Word-Ids">&#182;</a></h3><p>As you did with other RNNs, you must turn the text into a number so the computer can understand it. In the function <code>text_to_ids()</code>, you'll turn <code>source_text</code> and <code>target_text</code> from words to ids.  However, you need to add the <code>&lt;EOS&gt;</code> word id at the end of each sentence from <code>target_text</code>.  This will help the neural network predict when the sentence should end.</p>
<p>You can get the <code>&lt;EOS&gt;</code> word id by doing:</p>
<div class="highlight"><pre><span></span><span class="n">target_vocab_to_int</span><span class="p">[</span><span class="s1">&#39;&lt;EOS&gt;&#39;</span><span class="p">]</span>
</pre></div>
<p>You can get other word ids using <code>source_vocab_to_int</code> and <code>target_vocab_to_int</code>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">text_to_ids</span><span class="p">(</span><span class="n">source_text</span><span class="p">,</span> <span class="n">target_text</span><span class="p">,</span> <span class="n">source_vocab_to_int</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Convert source and target text to proper word ids</span>
<span class="sd">    :param source_text: String that contains all the source text.</span>
<span class="sd">    :param target_text: String that contains all the target text.</span>
<span class="sd">    :param source_vocab_to_int: Dictionary to go from the source words to an id</span>
<span class="sd">    :param target_vocab_to_int: Dictionary to go from the target words to an id</span>
<span class="sd">    :return: A tuple of lists (source_id_text, target_id_text)</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">source_lines</span> <span class="o">=</span> <span class="n">source_text</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="p">)</span>
    <span class="n">target_lines</span> <span class="o">=</span> <span class="p">[</span><span class="n">line</span> <span class="o">+</span> <span class="s1">&#39; &lt;EOS&gt;&#39;</span> <span class="k">for</span> <span class="n">line</span> <span class="ow">in</span> <span class="n">target_text</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">&#39;</span><span class="p">)]</span>

    <span class="n">source_ids</span> <span class="o">=</span> <span class="nb">list</span><span class="p">(</span><span class="nb">map</span><span class="p">(</span><span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="p">[</span><span class="n">source_vocab_to_int</span><span class="p">[</span><span class="n">word</span><span class="p">]</span> <span class="k">for</span> <span class="n">word</span> <span class="ow">in</span> <span class="n">x</span><span class="o">.</span><span class="n">split</span><span class="p">()],</span> <span class="n">source_lines</span><span class="p">))</span>
    <span class="n">target_ids</span> <span class="o">=</span> <span class="nb">list</span><span class="p">(</span><span class="nb">map</span><span class="p">(</span><span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="p">[</span><span class="n">target_vocab_to_int</span><span class="p">[</span><span class="n">word</span><span class="p">]</span> <span class="k">for</span> <span class="n">word</span> <span class="ow">in</span> <span class="n">x</span><span class="o">.</span><span class="n">split</span><span class="p">()],</span> <span class="n">target_lines</span><span class="p">))</span>

    <span class="k">return</span> <span class="n">source_ids</span><span class="p">,</span> <span class="n">target_ids</span>

<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_text_to_ids</span><span class="p">(</span><span class="n">text_to_ids</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Preprocess-all-the-data-and-save-it">Preprocess all the data and save it<a class="anchor-link" href="#Preprocess-all-the-data-and-save-it">&#182;</a></h3><p>Running the code cell below will preprocess all the data and save it to file.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">helper</span><span class="o">.</span><span class="n">preprocess_and_save_data</span><span class="p">(</span><span class="n">source_path</span><span class="p">,</span> <span class="n">target_path</span><span class="p">,</span> <span class="n">text_to_ids</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Check-Point">Check Point<a class="anchor-link" href="#Check-Point">&#182;</a></h1><p>This is your first checkpoint. If you ever decide to come back to this notebook or have to restart the notebook, you can start from here. The preprocessed data has been saved to disk.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">helper</span>

<span class="p">(</span><span class="n">source_int_text</span><span class="p">,</span> <span class="n">target_int_text</span><span class="p">),</span> <span class="p">(</span><span class="n">source_vocab_to_int</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">),</span> <span class="n">_</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_preprocess</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Check-the-Version-of-TensorFlow-and-Access-to-GPU">Check the Version of TensorFlow and Access to GPU<a class="anchor-link" href="#Check-the-Version-of-TensorFlow-and-Access-to-GPU">&#182;</a></h3><p>This will check to make sure you have the correct version of TensorFlow and access to a GPU</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">from</span> <span class="nn">distutils.version</span> <span class="k">import</span> <span class="n">LooseVersion</span>
<span class="kn">import</span> <span class="nn">warnings</span>
<span class="kn">import</span> <span class="nn">tensorflow</span> <span class="k">as</span> <span class="nn">tf</span>

<span class="c1"># Check TensorFlow Version</span>
<span class="k">assert</span> <span class="n">LooseVersion</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">__version__</span><span class="p">)</span> <span class="ow">in</span> <span class="p">[</span><span class="n">LooseVersion</span><span class="p">(</span><span class="s1">&#39;1.0.0&#39;</span><span class="p">),</span> <span class="n">LooseVersion</span><span class="p">(</span><span class="s1">&#39;1.0.1&#39;</span><span class="p">)],</span> <span class="s1">&#39;This project requires TensorFlow version 1.0  You are using </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">__version__</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;TensorFlow Version: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">__version__</span><span class="p">))</span>

<span class="c1"># Check for a GPU</span>
<span class="k">if</span> <span class="ow">not</span> <span class="n">tf</span><span class="o">.</span><span class="n">test</span><span class="o">.</span><span class="n">gpu_device_name</span><span class="p">():</span>
    <span class="n">warnings</span><span class="o">.</span><span class="n">warn</span><span class="p">(</span><span class="s1">&#39;No GPU found. Please use a GPU to train your neural network.&#39;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Default GPU Device: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">test</span><span class="o">.</span><span class="n">gpu_device_name</span><span class="p">()))</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>TensorFlow Version: 1.0.0
Default GPU Device: /gpu:0
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Build-the-Neural-Network">Build the Neural Network<a class="anchor-link" href="#Build-the-Neural-Network">&#182;</a></h2><p>You'll build the components necessary to build a Sequence-to-Sequence model by implementing the following functions below:</p>
<ul>
<li><code>model_inputs</code></li>
<li><code>process_decoding_input</code></li>
<li><code>encoding_layer</code></li>
<li><code>decoding_layer_train</code></li>
<li><code>decoding_layer_infer</code></li>
<li><code>decoding_layer</code></li>
<li><code>seq2seq_model</code></li>
</ul>
<h3 id="Input">Input<a class="anchor-link" href="#Input">&#182;</a></h3><p>Implement the <code>model_inputs()</code> function to create TF Placeholders for the Neural Network. It should create the following placeholders:</p>
<ul>
<li>Input text placeholder named "input" using the TF Placeholder name parameter with rank 2.</li>
<li>Targets placeholder with rank 2.</li>
<li>Learning rate placeholder with rank 0.</li>
<li>Keep probability placeholder named "keep_prob" using the TF Placeholder name parameter with rank 0.</li>
</ul>
<p>Return the placeholders in the following the tuple (Input, Targets, Learing Rate, Keep Probability)</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">model_inputs</span><span class="p">():</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Create TF Placeholders for input, targets, and learning rate.</span>
<span class="sd">    :return: Tuple (input, targets, learning rate, keep probability)</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">ph_input</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">placeholder</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">int32</span><span class="p">,</span> <span class="n">shape</span><span class="o">=</span><span class="p">(</span><span class="kc">None</span><span class="p">,</span> <span class="kc">None</span><span class="p">),</span> <span class="n">name</span><span class="o">=</span><span class="s1">&#39;input&#39;</span><span class="p">)</span>
    <span class="n">ph_targets</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">placeholder</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">int32</span><span class="p">,</span> <span class="n">shape</span><span class="o">=</span><span class="p">(</span><span class="kc">None</span><span class="p">,</span> <span class="kc">None</span><span class="p">))</span>
    <span class="n">ph_lrate</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">placeholder</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">float32</span><span class="p">)</span>
    <span class="n">ph_keep_prob</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">placeholder</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">float32</span><span class="p">,</span> <span class="n">name</span><span class="o">=</span><span class="s1">&#39;keep_prob&#39;</span><span class="p">)</span>

    <span class="k">return</span> <span class="n">ph_input</span><span class="p">,</span> <span class="n">ph_targets</span><span class="p">,</span> <span class="n">ph_lrate</span><span class="p">,</span> <span class="n">ph_keep_prob</span>

<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_model_inputs</span><span class="p">(</span><span class="n">model_inputs</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Process-Decoding-Input">Process Decoding Input<a class="anchor-link" href="#Process-Decoding-Input">&#182;</a></h3><p>Implement <code>process_decoding_input</code> using TensorFlow to remove the last word id from each batch in <code>target_data</code> and concat the GO ID to the begining of each batch.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[18]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">process_decoding_input</span><span class="p">(</span><span class="n">target_data</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">,</span> <span class="n">batch_size</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Preprocess target data for dencoding</span>
<span class="sd">    :param target_data: Target Placehoder</span>
<span class="sd">    :param target_vocab_to_int: Dictionary to go from the target words to an id</span>
<span class="sd">    :param batch_size: Batch Size</span>
<span class="sd">    :return: Preprocessed target data</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">go_id</span> <span class="o">=</span> <span class="n">target_vocab_to_int</span><span class="p">[</span><span class="s1">&#39;&lt;GO&gt;&#39;</span><span class="p">]</span>
    <span class="n">length</span> <span class="o">=</span> <span class="n">target_data</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
    
    <span class="n">ends</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">strided_slice</span><span class="p">(</span><span class="n">target_data</span><span class="p">,</span> <span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">],</span> <span class="p">[</span><span class="n">batch_size</span><span class="p">,</span> <span class="o">-</span><span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">])</span>
    <span class="n">finals</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">tf</span><span class="o">.</span><span class="n">fill</span><span class="p">([</span><span class="n">batch_size</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="n">go_id</span><span class="p">),</span> <span class="n">ends</span><span class="p">],</span> <span class="mi">1</span><span class="p">)</span>
    
    <span class="k">return</span> <span class="n">finals</span>

<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_process_decoding_input</span><span class="p">(</span><span class="n">process_decoding_input</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Encoding">Encoding<a class="anchor-link" href="#Encoding">&#182;</a></h3><p>Implement <code>encoding_layer()</code> to create a Encoder RNN layer using <a href="https://www.tensorflow.org/api_docs/python/tf/nn/dynamic_rnn"><code>tf.nn.dynamic_rnn()</code></a>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">encoding_layer</span><span class="p">(</span><span class="n">rnn_inputs</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span> <span class="n">num_layers</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Create encoding layer</span>
<span class="sd">    :param rnn_inputs: Inputs for the RNN</span>
<span class="sd">    :param rnn_size: RNN Size</span>
<span class="sd">    :param num_layers: Number of layers</span>
<span class="sd">    :param keep_prob: Dropout keep probability</span>
<span class="sd">    :return: RNN state</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">lstm</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">rnn</span><span class="o">.</span><span class="n">BasicLSTMCell</span><span class="p">(</span><span class="n">num_units</span><span class="o">=</span><span class="n">rnn_size</span><span class="p">)</span>
    <span class="n">cell</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">rnn</span><span class="o">.</span><span class="n">MultiRNNCell</span><span class="p">([</span><span class="n">lstm</span><span class="p">]</span> <span class="o">*</span> <span class="n">num_layers</span><span class="p">)</span>
    <span class="n">_</span><span class="p">,</span> <span class="n">state</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">nn</span><span class="o">.</span><span class="n">dynamic_rnn</span><span class="p">(</span><span class="n">cell</span><span class="p">,</span> <span class="n">rnn_inputs</span><span class="p">,</span> <span class="n">dtype</span><span class="o">=</span><span class="n">tf</span><span class="o">.</span><span class="n">float32</span><span class="p">)</span><span class="c1">#, initial_state=initial_state)</span>
    <span class="k">return</span> <span class="n">state</span>

<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_encoding_layer</span><span class="p">(</span><span class="n">encoding_layer</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Decoding---Training">Decoding - Training<a class="anchor-link" href="#Decoding---Training">&#182;</a></h3><p>Create training logits using <a href="https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/simple_decoder_fn_train"><code>tf.contrib.seq2seq.simple_decoder_fn_train()</code></a> and <a href="https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/dynamic_rnn_decoder"><code>tf.contrib.seq2seq.dynamic_rnn_decoder()</code></a>.  Apply the <code>output_fn</code> to the <a href="https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/dynamic_rnn_decoder"><code>tf.contrib.seq2seq.dynamic_rnn_decoder()</code></a> outputs.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[20]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">decoding_layer_train</span><span class="p">(</span><span class="n">encoder_state</span><span class="p">,</span> <span class="n">dec_cell</span><span class="p">,</span> <span class="n">dec_embed_input</span><span class="p">,</span> <span class="n">sequence_length</span><span class="p">,</span> <span class="n">decoding_scope</span><span class="p">,</span>
                         <span class="n">output_fn</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Create a decoding layer for training</span>
<span class="sd">    :param encoder_state: Encoder State</span>
<span class="sd">    :param dec_cell: Decoder RNN Cell</span>
<span class="sd">    :param dec_embed_input: Decoder embedded input</span>
<span class="sd">    :param sequence_length: Sequence Length</span>
<span class="sd">    :param decoding_scope: TenorFlow Variable Scope for decoding</span>
<span class="sd">    :param output_fn: Function to apply the output layer</span>
<span class="sd">    :param keep_prob: Dropout keep probability</span>
<span class="sd">    :return: Train Logits</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">decoder_fn</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">seq2seq</span><span class="o">.</span><span class="n">simple_decoder_fn_train</span><span class="p">(</span><span class="n">encoder_state</span><span class="p">,</span> <span class="n">name</span><span class="o">=</span><span class="s1">&#39;decoder_fn_train&#39;</span><span class="p">)</span>
    <span class="n">decoder_drop</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">rnn</span><span class="o">.</span><span class="n">DropoutWrapper</span><span class="p">(</span><span class="n">dec_cell</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">)</span>
    <span class="n">decoder_outputs</span><span class="p">,</span><span class="n">_</span><span class="p">,</span><span class="n">__</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">seq2seq</span><span class="o">.</span><span class="n">dynamic_rnn_decoder</span><span class="p">(</span>
        <span class="n">decoder_drop</span><span class="p">,</span> 
        <span class="n">decoder_fn</span><span class="p">,</span> 
        <span class="n">inputs</span><span class="o">=</span><span class="n">dec_embed_input</span><span class="p">,</span>
        <span class="n">sequence_length</span><span class="o">=</span><span class="n">sequence_length</span><span class="p">,</span>
        <span class="n">scope</span><span class="o">=</span><span class="n">decoding_scope</span>
    <span class="p">)</span>
    <span class="k">return</span> <span class="n">output_fn</span><span class="p">(</span><span class="n">decoder_outputs</span><span class="p">)</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_decoding_layer_train</span><span class="p">(</span><span class="n">decoding_layer_train</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Decoding---Inference">Decoding - Inference<a class="anchor-link" href="#Decoding---Inference">&#182;</a></h3><p>Create inference logits using <a href="https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/simple_decoder_fn_inference"><code>tf.contrib.seq2seq.simple_decoder_fn_inference()</code></a> and <a href="https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/dynamic_rnn_decoder"><code>tf.contrib.seq2seq.dynamic_rnn_decoder()</code></a>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[21]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">decoding_layer_infer</span><span class="p">(</span><span class="n">encoder_state</span><span class="p">,</span> <span class="n">dec_cell</span><span class="p">,</span> <span class="n">dec_embeddings</span><span class="p">,</span> <span class="n">start_of_sequence_id</span><span class="p">,</span> <span class="n">end_of_sequence_id</span><span class="p">,</span>
                         <span class="n">maximum_length</span><span class="p">,</span> <span class="n">vocab_size</span><span class="p">,</span> <span class="n">decoding_scope</span><span class="p">,</span> <span class="n">output_fn</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Create a decoding layer for inference</span>
<span class="sd">    :param encoder_state: Encoder state</span>
<span class="sd">    :param dec_cell: Decoder RNN Cell</span>
<span class="sd">    :param dec_embeddings: Decoder embeddings</span>
<span class="sd">    :param start_of_sequence_id: GO ID</span>
<span class="sd">    :param end_of_sequence_id: EOS Id</span>
<span class="sd">    :param maximum_length: The maximum allowed time steps to decode</span>
<span class="sd">    :param vocab_size: Size of vocabulary</span>
<span class="sd">    :param decoding_scope: TensorFlow Variable Scope for decoding</span>
<span class="sd">    :param output_fn: Function to apply the output layer</span>
<span class="sd">    :param keep_prob: Dropout keep probability</span>
<span class="sd">    :return: Inference Logits</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">decoder_fn</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">seq2seq</span><span class="o">.</span><span class="n">simple_decoder_fn_inference</span><span class="p">(</span>
        <span class="n">output_fn</span><span class="o">=</span><span class="n">output_fn</span><span class="p">,</span>
        <span class="n">encoder_state</span><span class="o">=</span><span class="n">encoder_state</span><span class="p">,</span>
        <span class="n">embeddings</span><span class="o">=</span><span class="n">dec_embeddings</span><span class="p">,</span>
        <span class="n">start_of_sequence_id</span><span class="o">=</span><span class="n">start_of_sequence_id</span><span class="p">,</span>
        <span class="n">end_of_sequence_id</span><span class="o">=</span><span class="n">end_of_sequence_id</span><span class="p">,</span>
        <span class="n">maximum_length</span><span class="o">=</span><span class="n">maximum_length</span><span class="p">,</span>
        <span class="n">num_decoder_symbols</span><span class="o">=</span><span class="n">vocab_size</span><span class="p">,</span>
        <span class="n">name</span><span class="o">=</span><span class="s1">&#39;inference_decoder_fn&#39;</span>
    <span class="p">)</span>
    
    <span class="n">outputs</span><span class="p">,</span><span class="n">_</span><span class="p">,</span><span class="n">__</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">seq2seq</span><span class="o">.</span><span class="n">dynamic_rnn_decoder</span><span class="p">(</span>
        <span class="n">cell</span><span class="o">=</span><span class="n">dec_cell</span><span class="p">,</span>
        <span class="n">decoder_fn</span><span class="o">=</span><span class="n">decoder_fn</span><span class="p">,</span>
        <span class="n">scope</span><span class="o">=</span><span class="n">decoding_scope</span><span class="p">,</span>
        <span class="n">name</span><span class="o">=</span><span class="s1">&#39;inference_decoder_rnn&#39;</span>
    <span class="p">)</span>
    <span class="k">return</span> <span class="n">outputs</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_decoding_layer_infer</span><span class="p">(</span><span class="n">decoding_layer_infer</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Build-the-Decoding-Layer">Build the Decoding Layer<a class="anchor-link" href="#Build-the-Decoding-Layer">&#182;</a></h3><p>Implement <code>decoding_layer()</code> to create a Decoder RNN layer.</p>
<ul>
<li>Create RNN cell for decoding using <code>rnn_size</code> and <code>num_layers</code>.</li>
<li>Create the output fuction using <a href="https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions"><code>lambda</code></a> to transform it's input, logits, to class logits.</li>
<li>Use the your <code>decoding_layer_train(encoder_state, dec_cell, dec_embed_input, sequence_length, decoding_scope, output_fn, keep_prob)</code> function to get the training logits.</li>
<li>Use your <code>decoding_layer_infer(encoder_state, dec_cell, dec_embeddings, start_of_sequence_id, end_of_sequence_id, maximum_length, vocab_size, decoding_scope, output_fn, keep_prob)</code> function to get the inference logits.</li>
</ul>
<p>Note: You'll need to use <a href="https://www.tensorflow.org/api_docs/python/tf/variable_scope">tf.variable_scope</a> to share variables between training and inference.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">decoding_layer</span><span class="p">(</span><span class="n">dec_embed_input</span><span class="p">,</span> <span class="n">dec_embeddings</span><span class="p">,</span> <span class="n">encoder_state</span><span class="p">,</span> <span class="n">vocab_size</span><span class="p">,</span> <span class="n">sequence_length</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span>
                   <span class="n">num_layers</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Create decoding layer</span>
<span class="sd">    :param dec_embed_input: Decoder embedded input</span>
<span class="sd">    :param dec_embeddings: Decoder embeddings</span>
<span class="sd">    :param encoder_state: The encoded state</span>
<span class="sd">    :param vocab_size: Size of vocabulary</span>
<span class="sd">    :param sequence_length: Sequence Length</span>
<span class="sd">    :param rnn_size: RNN Size</span>
<span class="sd">    :param num_layers: Number of layers</span>
<span class="sd">    :param target_vocab_to_int: Dictionary to go from the target words to an id</span>
<span class="sd">    :param keep_prob: Dropout keep probability</span>
<span class="sd">    :return: Tuple of (Training Logits, Inference Logits)</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">lstm</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">rnn</span><span class="o">.</span><span class="n">BasicLSTMCell</span><span class="p">(</span><span class="n">rnn_size</span><span class="p">)</span>
    <span class="n">dec_cell</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">rnn</span><span class="o">.</span><span class="n">MultiRNNCell</span><span class="p">([</span><span class="n">lstm</span><span class="p">]</span> <span class="o">*</span> <span class="n">num_layers</span><span class="p">)</span>
    <span class="n">output_fn</span> <span class="o">=</span> <span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">fully_connected</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">vocab_size</span><span class="p">,</span> <span class="kc">None</span><span class="p">,</span> <span class="n">scope</span><span class="o">=</span><span class="n">dec_scope</span><span class="p">)</span>
    <span class="n">start_of_sequence_id</span> <span class="o">=</span> <span class="n">target_vocab_to_int</span><span class="p">[</span><span class="s1">&#39;&lt;GO&gt;&#39;</span><span class="p">]</span>
    <span class="n">end_of_sequence_id</span> <span class="o">=</span> <span class="n">target_vocab_to_int</span><span class="p">[</span><span class="s1">&#39;&lt;EOS&gt;&#39;</span><span class="p">]</span>
    <span class="n">maximum_length</span> <span class="o">=</span> <span class="n">sequence_length</span>
        
    <span class="k">with</span> <span class="n">tf</span><span class="o">.</span><span class="n">variable_scope</span><span class="p">(</span><span class="s1">&#39;training&#39;</span><span class="p">)</span> <span class="k">as</span> <span class="n">dec_scope</span><span class="p">:</span>
        <span class="n">train_logits</span> <span class="o">=</span> <span class="n">decoding_layer_train</span><span class="p">(</span><span class="n">encoder_state</span><span class="p">,</span> <span class="n">dec_cell</span><span class="p">,</span> <span class="n">dec_embed_input</span><span class="p">,</span>
                                            <span class="n">sequence_length</span><span class="p">,</span> <span class="n">dec_scope</span><span class="p">,</span> <span class="n">output_fn</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">)</span>
        <span class="n">dec_scope</span><span class="o">.</span><span class="n">reuse_variables</span><span class="p">()</span>
        <span class="n">inf_logits</span> <span class="o">=</span> <span class="n">decoding_layer_infer</span><span class="p">(</span><span class="n">encoder_state</span><span class="p">,</span> <span class="n">dec_cell</span><span class="p">,</span> <span class="n">dec_embeddings</span><span class="p">,</span> <span class="n">start_of_sequence_id</span><span class="p">,</span>
                                          <span class="n">end_of_sequence_id</span><span class="p">,</span> <span class="n">maximum_length</span><span class="p">,</span> <span class="n">vocab_size</span><span class="p">,</span> <span class="n">dec_scope</span><span class="p">,</span> <span class="n">output_fn</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">)</span>

        <span class="k">return</span> <span class="n">train_logits</span><span class="p">,</span> <span class="n">inf_logits</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_decoding_layer</span><span class="p">(</span><span class="n">decoding_layer</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Build-the-Neural-Network">Build the Neural Network<a class="anchor-link" href="#Build-the-Neural-Network">&#182;</a></h3><p>Apply the functions you implemented above to:</p>
<ul>
<li>Apply embedding to the input data for the encoder.</li>
<li>Encode the input using your <code>encoding_layer(rnn_inputs, rnn_size, num_layers, keep_prob)</code>.</li>
<li>Process target data using your <code>process_decoding_input(target_data, target_vocab_to_int, batch_size)</code> function.</li>
<li>Apply embedding to the target data for the decoder.</li>
<li>Decode the encoded input using your <code>decoding_layer(dec_embed_input, dec_embeddings, encoder_state, vocab_size, sequence_length, rnn_size, num_layers, target_vocab_to_int, keep_prob)</code>.</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">seq2seq_model</span><span class="p">(</span><span class="n">input_data</span><span class="p">,</span> <span class="n">target_data</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">,</span> <span class="n">batch_size</span><span class="p">,</span> <span class="n">sequence_length</span><span class="p">,</span> <span class="n">source_vocab_size</span><span class="p">,</span> <span class="n">target_vocab_size</span><span class="p">,</span>
                  <span class="n">enc_embedding_size</span><span class="p">,</span> <span class="n">dec_embedding_size</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span> <span class="n">num_layers</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Build the Sequence-to-Sequence part of the neural network</span>
<span class="sd">    :param input_data: Input placeholder</span>
<span class="sd">    :param target_data: Target placeholder</span>
<span class="sd">    :param keep_prob: Dropout keep probability placeholder</span>
<span class="sd">    :param batch_size: Batch Size</span>
<span class="sd">    :param sequence_length: Sequence Length</span>
<span class="sd">    :param source_vocab_size: Source vocabulary size</span>
<span class="sd">    :param target_vocab_size: Target vocabulary size</span>
<span class="sd">    :param enc_embedding_size: Decoder embedding size</span>
<span class="sd">    :param dec_embedding_size: Encoder embedding size</span>
<span class="sd">    :param rnn_size: RNN Size</span>
<span class="sd">    :param num_layers: Number of layers</span>
<span class="sd">    :param target_vocab_to_int: Dictionary to go from the target words to an id</span>
<span class="sd">    :return: Tuple of (Training Logits, Inference Logits)</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">enc_input</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">embed_sequence</span><span class="p">(</span><span class="n">input_data</span><span class="p">,</span> <span class="n">source_vocab_size</span><span class="p">,</span> <span class="n">enc_embedding_size</span><span class="p">)</span>
    <span class="n">enc_layer</span> <span class="o">=</span> <span class="n">encoding_layer</span><span class="p">(</span><span class="n">enc_input</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span> <span class="n">num_layers</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">)</span>    
    <span class="n">dec_input</span> <span class="o">=</span> <span class="n">process_decoding_input</span><span class="p">(</span><span class="n">target_data</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">,</span> <span class="n">batch_size</span><span class="p">)</span>
    
    <span class="n">dec_embed</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">Variable</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">random_uniform</span><span class="p">([</span><span class="n">target_vocab_size</span><span class="p">,</span> <span class="n">dec_embedding_size</span><span class="p">],</span> <span class="n">minval</span><span class="o">=</span><span class="mi">0</span><span class="p">))</span>
    <span class="n">target_embed</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">nn</span><span class="o">.</span><span class="n">embedding_lookup</span><span class="p">(</span><span class="n">dec_embed</span><span class="p">,</span> <span class="n">dec_input</span><span class="p">)</span>
    
    <span class="n">train_logits</span><span class="p">,</span> <span class="n">inf_logits</span> <span class="o">=</span> <span class="n">decoding_layer</span><span class="p">(</span><span class="n">target_embed</span><span class="p">,</span> <span class="n">dec_embed</span><span class="p">,</span> <span class="n">enc_layer</span><span class="p">,</span> <span class="n">target_vocab_size</span><span class="p">,</span>
                                              <span class="n">sequence_length</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span> <span class="n">num_layers</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">train_logits</span><span class="p">,</span> <span class="n">inf_logits</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_seq2seq_model</span><span class="p">(</span><span class="n">seq2seq_model</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Neural-Network-Training">Neural Network Training<a class="anchor-link" href="#Neural-Network-Training">&#182;</a></h2><h3 id="Hyperparameters">Hyperparameters<a class="anchor-link" href="#Hyperparameters">&#182;</a></h3><p>Tune the following parameters:</p>
<ul>
<li>Set <code>epochs</code> to the number of epochs.</li>
<li>Set <code>batch_size</code> to the batch size.</li>
<li>Set <code>rnn_size</code> to the size of the RNNs.</li>
<li>Set <code>num_layers</code> to the number of layers.</li>
<li>Set <code>encoding_embedding_size</code> to the size of the embedding for the encoder.</li>
<li>Set <code>decoding_embedding_size</code> to the size of the embedding for the decoder.</li>
<li>Set <code>learning_rate</code> to the learning rate.</li>
<li>Set <code>keep_probability</code> to the Dropout keep probability</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[24]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Number of Epochs</span>
<span class="n">epochs</span> <span class="o">=</span> <span class="mi">10</span>
<span class="c1"># Batch Size</span>
<span class="n">batch_size</span> <span class="o">=</span> <span class="mi">512</span>
<span class="c1"># RNN Size</span>
<span class="n">rnn_size</span> <span class="o">=</span> <span class="mi">128</span>
<span class="c1"># Number of Layers</span>
<span class="n">num_layers</span> <span class="o">=</span> <span class="mi">2</span>
<span class="c1"># Embedding Size</span>
<span class="n">encoding_embedding_size</span> <span class="o">=</span> <span class="mi">256</span>
<span class="n">decoding_embedding_size</span> <span class="o">=</span> <span class="mi">256</span>
<span class="c1"># Learning Rate</span>
<span class="n">learning_rate</span> <span class="o">=</span> <span class="mf">0.001</span>
<span class="c1"># Dropout Keep Probability</span>
<span class="n">keep_probability</span> <span class="o">=</span> <span class="mf">0.75</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Build-the-Graph">Build the Graph<a class="anchor-link" href="#Build-the-Graph">&#182;</a></h3><p>Build the graph using the neural network you implemented.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[25]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">save_path</span> <span class="o">=</span> <span class="s1">&#39;checkpoints/dev&#39;</span>
<span class="p">(</span><span class="n">source_int_text</span><span class="p">,</span> <span class="n">target_int_text</span><span class="p">),</span> <span class="p">(</span><span class="n">source_vocab_to_int</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">),</span> <span class="n">_</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_preprocess</span><span class="p">()</span>
<span class="n">max_source_sentence_length</span> <span class="o">=</span> <span class="nb">max</span><span class="p">([</span><span class="nb">len</span><span class="p">(</span><span class="n">sentence</span><span class="p">)</span> <span class="k">for</span> <span class="n">sentence</span> <span class="ow">in</span> <span class="n">source_int_text</span><span class="p">])</span>

<span class="n">train_graph</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">Graph</span><span class="p">()</span>
<span class="k">with</span> <span class="n">train_graph</span><span class="o">.</span><span class="n">as_default</span><span class="p">():</span>
    <span class="n">input_data</span><span class="p">,</span> <span class="n">targets</span><span class="p">,</span> <span class="n">lr</span><span class="p">,</span> <span class="n">keep_prob</span> <span class="o">=</span> <span class="n">model_inputs</span><span class="p">()</span>
    <span class="n">sequence_length</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">placeholder_with_default</span><span class="p">(</span><span class="n">max_source_sentence_length</span><span class="p">,</span> <span class="kc">None</span><span class="p">,</span> <span class="n">name</span><span class="o">=</span><span class="s1">&#39;sequence_length&#39;</span><span class="p">)</span>
    <span class="n">input_shape</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">shape</span><span class="p">(</span><span class="n">input_data</span><span class="p">)</span>
    
    <span class="n">train_logits</span><span class="p">,</span> <span class="n">inference_logits</span> <span class="o">=</span> <span class="n">seq2seq_model</span><span class="p">(</span>
        <span class="n">tf</span><span class="o">.</span><span class="n">reverse</span><span class="p">(</span><span class="n">input_data</span><span class="p">,</span> <span class="p">[</span><span class="o">-</span><span class="mi">1</span><span class="p">]),</span> <span class="n">targets</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">,</span> <span class="n">batch_size</span><span class="p">,</span> <span class="n">sequence_length</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">source_vocab_to_int</span><span class="p">),</span> <span class="nb">len</span><span class="p">(</span><span class="n">target_vocab_to_int</span><span class="p">),</span>
        <span class="n">encoding_embedding_size</span><span class="p">,</span> <span class="n">decoding_embedding_size</span><span class="p">,</span> <span class="n">rnn_size</span><span class="p">,</span> <span class="n">num_layers</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">)</span>

    <span class="n">tf</span><span class="o">.</span><span class="n">identity</span><span class="p">(</span><span class="n">inference_logits</span><span class="p">,</span> <span class="s1">&#39;logits&#39;</span><span class="p">)</span>
    <span class="k">with</span> <span class="n">tf</span><span class="o">.</span><span class="n">name_scope</span><span class="p">(</span><span class="s2">&quot;optimization&quot;</span><span class="p">):</span>
        <span class="c1"># Loss function</span>
        <span class="n">cost</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">contrib</span><span class="o">.</span><span class="n">seq2seq</span><span class="o">.</span><span class="n">sequence_loss</span><span class="p">(</span>
            <span class="n">train_logits</span><span class="p">,</span>
            <span class="n">targets</span><span class="p">,</span>
            <span class="n">tf</span><span class="o">.</span><span class="n">ones</span><span class="p">([</span><span class="n">input_shape</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span> <span class="n">sequence_length</span><span class="p">]))</span>

        <span class="c1"># Optimizer</span>
        <span class="n">optimizer</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">train</span><span class="o">.</span><span class="n">AdamOptimizer</span><span class="p">(</span><span class="n">lr</span><span class="p">)</span>

        <span class="c1"># Gradient Clipping</span>
        <span class="n">gradients</span> <span class="o">=</span> <span class="n">optimizer</span><span class="o">.</span><span class="n">compute_gradients</span><span class="p">(</span><span class="n">cost</span><span class="p">)</span>
        <span class="n">capped_gradients</span> <span class="o">=</span> <span class="p">[(</span><span class="n">tf</span><span class="o">.</span><span class="n">clip_by_value</span><span class="p">(</span><span class="n">grad</span><span class="p">,</span> <span class="o">-</span><span class="mf">1.</span><span class="p">,</span> <span class="mf">1.</span><span class="p">),</span> <span class="n">var</span><span class="p">)</span> <span class="k">for</span> <span class="n">grad</span><span class="p">,</span> <span class="n">var</span> <span class="ow">in</span> <span class="n">gradients</span> <span class="k">if</span> <span class="n">grad</span> <span class="ow">is</span> <span class="ow">not</span> <span class="kc">None</span><span class="p">]</span>
        <span class="n">train_op</span> <span class="o">=</span> <span class="n">optimizer</span><span class="o">.</span><span class="n">apply_gradients</span><span class="p">(</span><span class="n">capped_gradients</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Train">Train<a class="anchor-link" href="#Train">&#182;</a></h3><p>Train the neural network on the preprocessed data. If you have a hard time getting a good loss, check the forms to see if anyone is having the same problem.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[26]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">import</span> <span class="nn">time</span>

<span class="k">def</span> <span class="nf">get_accuracy</span><span class="p">(</span><span class="n">target</span><span class="p">,</span> <span class="n">logits</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Calculate accuracy</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">max_seq</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">target</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">],</span> <span class="n">logits</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">])</span>
    <span class="k">if</span> <span class="n">max_seq</span> <span class="o">-</span> <span class="n">target</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">]:</span>
        <span class="n">target</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">pad</span><span class="p">(</span>
            <span class="n">target</span><span class="p">,</span>
            <span class="p">[(</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">),(</span><span class="mi">0</span><span class="p">,</span><span class="n">max_seq</span> <span class="o">-</span> <span class="n">target</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">])],</span>
            <span class="s1">&#39;constant&#39;</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">max_seq</span> <span class="o">-</span> <span class="n">logits</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">]:</span>
        <span class="n">logits</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">pad</span><span class="p">(</span>
            <span class="n">logits</span><span class="p">,</span>
            <span class="p">[(</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">),(</span><span class="mi">0</span><span class="p">,</span><span class="n">max_seq</span> <span class="o">-</span> <span class="n">logits</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">]),</span> <span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">)],</span>
            <span class="s1">&#39;constant&#39;</span><span class="p">)</span>

    <span class="k">return</span> <span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">equal</span><span class="p">(</span><span class="n">target</span><span class="p">,</span> <span class="n">np</span><span class="o">.</span><span class="n">argmax</span><span class="p">(</span><span class="n">logits</span><span class="p">,</span> <span class="mi">2</span><span class="p">)))</span>

<span class="n">train_source</span> <span class="o">=</span> <span class="n">source_int_text</span><span class="p">[</span><span class="n">batch_size</span><span class="p">:]</span>
<span class="n">train_target</span> <span class="o">=</span> <span class="n">target_int_text</span><span class="p">[</span><span class="n">batch_size</span><span class="p">:]</span>

<span class="n">valid_source</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">pad_sentence_batch</span><span class="p">(</span><span class="n">source_int_text</span><span class="p">[:</span><span class="n">batch_size</span><span class="p">])</span>
<span class="n">valid_target</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">pad_sentence_batch</span><span class="p">(</span><span class="n">target_int_text</span><span class="p">[:</span><span class="n">batch_size</span><span class="p">])</span>

<span class="k">with</span> <span class="n">tf</span><span class="o">.</span><span class="n">Session</span><span class="p">(</span><span class="n">graph</span><span class="o">=</span><span class="n">train_graph</span><span class="p">)</span> <span class="k">as</span> <span class="n">sess</span><span class="p">:</span>
    <span class="n">sess</span><span class="o">.</span><span class="n">run</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">global_variables_initializer</span><span class="p">())</span>

    <span class="k">for</span> <span class="n">epoch_i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="n">epochs</span><span class="p">):</span>
        <span class="k">for</span> <span class="n">batch_i</span><span class="p">,</span> <span class="p">(</span><span class="n">source_batch</span><span class="p">,</span> <span class="n">target_batch</span><span class="p">)</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span>
                <span class="n">helper</span><span class="o">.</span><span class="n">batch_data</span><span class="p">(</span><span class="n">train_source</span><span class="p">,</span> <span class="n">train_target</span><span class="p">,</span> <span class="n">batch_size</span><span class="p">)):</span>
            <span class="n">start_time</span> <span class="o">=</span> <span class="n">time</span><span class="o">.</span><span class="n">time</span><span class="p">()</span>
            
            <span class="n">_</span><span class="p">,</span> <span class="n">loss</span> <span class="o">=</span> <span class="n">sess</span><span class="o">.</span><span class="n">run</span><span class="p">(</span>
                <span class="p">[</span><span class="n">train_op</span><span class="p">,</span> <span class="n">cost</span><span class="p">],</span>
                <span class="p">{</span><span class="n">input_data</span><span class="p">:</span> <span class="n">source_batch</span><span class="p">,</span>
                 <span class="n">targets</span><span class="p">:</span> <span class="n">target_batch</span><span class="p">,</span>
                 <span class="n">lr</span><span class="p">:</span> <span class="n">learning_rate</span><span class="p">,</span>
                 <span class="n">sequence_length</span><span class="p">:</span> <span class="n">target_batch</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">1</span><span class="p">],</span>
                 <span class="n">keep_prob</span><span class="p">:</span> <span class="n">keep_probability</span><span class="p">})</span>
            
            <span class="n">batch_train_logits</span> <span class="o">=</span> <span class="n">sess</span><span class="o">.</span><span class="n">run</span><span class="p">(</span>
                <span class="n">inference_logits</span><span class="p">,</span>
                <span class="p">{</span><span class="n">input_data</span><span class="p">:</span> <span class="n">source_batch</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">:</span> <span class="mf">1.0</span><span class="p">})</span>
            <span class="n">batch_valid_logits</span> <span class="o">=</span> <span class="n">sess</span><span class="o">.</span><span class="n">run</span><span class="p">(</span>
                <span class="n">inference_logits</span><span class="p">,</span>
                <span class="p">{</span><span class="n">input_data</span><span class="p">:</span> <span class="n">valid_source</span><span class="p">,</span> <span class="n">keep_prob</span><span class="p">:</span> <span class="mf">1.0</span><span class="p">})</span>
                
            <span class="n">train_acc</span> <span class="o">=</span> <span class="n">get_accuracy</span><span class="p">(</span><span class="n">target_batch</span><span class="p">,</span> <span class="n">batch_train_logits</span><span class="p">)</span>
            <span class="n">valid_acc</span> <span class="o">=</span> <span class="n">get_accuracy</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">valid_target</span><span class="p">),</span> <span class="n">batch_valid_logits</span><span class="p">)</span>
            <span class="n">end_time</span> <span class="o">=</span> <span class="n">time</span><span class="o">.</span><span class="n">time</span><span class="p">()</span>
            <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Epoch </span><span class="si">{:&gt;3}</span><span class="s1"> Batch </span><span class="si">{:&gt;4}</span><span class="s1">/</span><span class="si">{}</span><span class="s1"> - Train Accuracy: </span><span class="si">{:&gt;6.3f}</span><span class="s1">, Validation Accuracy: </span><span class="si">{:&gt;6.3f}</span><span class="s1">, Loss: </span><span class="si">{:&gt;6.3f}</span><span class="s1">&#39;</span>
                  <span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">epoch_i</span><span class="p">,</span> <span class="n">batch_i</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">source_int_text</span><span class="p">)</span> <span class="o">//</span> <span class="n">batch_size</span><span class="p">,</span> <span class="n">train_acc</span><span class="p">,</span> <span class="n">valid_acc</span><span class="p">,</span> <span class="n">loss</span><span class="p">))</span>

    <span class="c1"># Save Model</span>
    <span class="n">saver</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">train</span><span class="o">.</span><span class="n">Saver</span><span class="p">()</span>
    <span class="n">saver</span><span class="o">.</span><span class="n">save</span><span class="p">(</span><span class="n">sess</span><span class="p">,</span> <span class="n">save_path</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Model Trained and Saved&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Epoch   0 Batch    0/269 - Train Accuracy:  0.251, Validation Accuracy:  0.317, Loss:  5.869
Epoch   0 Batch    1/269 - Train Accuracy:  0.234, Validation Accuracy:  0.311, Loss:  5.700
Epoch   0 Batch    2/269 - Train Accuracy:  0.266, Validation Accuracy:  0.310, Loss:  5.503
Epoch   0 Batch    3/269 - Train Accuracy:  0.244, Validation Accuracy:  0.310, Loss:  5.353
Epoch   0 Batch    4/269 - Train Accuracy:  0.232, Validation Accuracy:  0.310, Loss:  5.205
Epoch   0 Batch    5/269 - Train Accuracy:  0.233, Validation Accuracy:  0.310, Loss:  5.036
Epoch   0 Batch    6/269 - Train Accuracy:  0.279, Validation Accuracy:  0.310, Loss:  4.748
Epoch   0 Batch    7/269 - Train Accuracy:  0.276, Validation Accuracy:  0.310, Loss:  4.582
Epoch   0 Batch    8/269 - Train Accuracy:  0.253, Validation Accuracy:  0.321, Loss:  4.528
Epoch   0 Batch    9/269 - Train Accuracy:  0.280, Validation Accuracy:  0.322, Loss:  4.277
Epoch   0 Batch   10/269 - Train Accuracy:  0.258, Validation Accuracy:  0.333, Loss:  4.250
Epoch   0 Batch   11/269 - Train Accuracy:  0.304, Validation Accuracy:  0.341, Loss:  3.989
Epoch   0 Batch   12/269 - Train Accuracy:  0.278, Validation Accuracy:  0.341, Loss:  3.987
Epoch   0 Batch   13/269 - Train Accuracy:  0.343, Validation Accuracy:  0.341, Loss:  3.603
Epoch   0 Batch   14/269 - Train Accuracy:  0.304, Validation Accuracy:  0.342, Loss:  3.685
Epoch   0 Batch   15/269 - Train Accuracy:  0.295, Validation Accuracy:  0.342, Loss:  3.624
Epoch   0 Batch   16/269 - Train Accuracy:  0.310, Validation Accuracy:  0.342, Loss:  3.503
Epoch   0 Batch   17/269 - Train Accuracy:  0.301, Validation Accuracy:  0.342, Loss:  3.459
Epoch   0 Batch   18/269 - Train Accuracy:  0.273, Validation Accuracy:  0.344, Loss:  3.529
Epoch   0 Batch   19/269 - Train Accuracy:  0.350, Validation Accuracy:  0.354, Loss:  3.186
Epoch   0 Batch   20/269 - Train Accuracy:  0.289, Validation Accuracy:  0.356, Loss:  3.390
Epoch   0 Batch   21/269 - Train Accuracy:  0.309, Validation Accuracy:  0.374, Loss:  3.357
Epoch   0 Batch   22/269 - Train Accuracy:  0.359, Validation Accuracy:  0.385, Loss:  3.162
Epoch   0 Batch   23/269 - Train Accuracy:  0.370, Validation Accuracy:  0.387, Loss:  3.116
Epoch   0 Batch   24/269 - Train Accuracy:  0.322, Validation Accuracy:  0.388, Loss:  3.264
Epoch   0 Batch   25/269 - Train Accuracy:  0.325, Validation Accuracy:  0.387, Loss:  3.227
Epoch   0 Batch   26/269 - Train Accuracy:  0.384, Validation Accuracy:  0.383, Loss:  2.933
Epoch   0 Batch   27/269 - Train Accuracy:  0.349, Validation Accuracy:  0.383, Loss:  3.056
Epoch   0 Batch   28/269 - Train Accuracy:  0.306, Validation Accuracy:  0.382, Loss:  3.204
Epoch   0 Batch   29/269 - Train Accuracy:  0.319, Validation Accuracy:  0.386, Loss:  3.137
Epoch   0 Batch   30/269 - Train Accuracy:  0.348, Validation Accuracy:  0.386, Loss:  2.995
Epoch   0 Batch   31/269 - Train Accuracy:  0.365, Validation Accuracy:  0.389, Loss:  2.950
Epoch   0 Batch   32/269 - Train Accuracy:  0.354, Validation Accuracy:  0.389, Loss:  2.969
Epoch   0 Batch   33/269 - Train Accuracy:  0.363, Validation Accuracy:  0.391, Loss:  2.883
Epoch   0 Batch   34/269 - Train Accuracy:  0.361, Validation Accuracy:  0.390, Loss:  2.898
Epoch   0 Batch   35/269 - Train Accuracy:  0.360, Validation Accuracy:  0.389, Loss:  2.875
Epoch   0 Batch   36/269 - Train Accuracy:  0.359, Validation Accuracy:  0.388, Loss:  2.874
Epoch   0 Batch   37/269 - Train Accuracy:  0.365, Validation Accuracy:  0.393, Loss:  2.860
Epoch   0 Batch   38/269 - Train Accuracy:  0.366, Validation Accuracy:  0.399, Loss:  2.849
Epoch   0 Batch   39/269 - Train Accuracy:  0.366, Validation Accuracy:  0.400, Loss:  2.823
Epoch   0 Batch   40/269 - Train Accuracy:  0.344, Validation Accuracy:  0.406, Loss:  2.934
Epoch   0 Batch   41/269 - Train Accuracy:  0.372, Validation Accuracy:  0.406, Loss:  2.811
Epoch   0 Batch   42/269 - Train Accuracy:  0.407, Validation Accuracy:  0.411, Loss:  2.683
Epoch   0 Batch   43/269 - Train Accuracy:  0.363, Validation Accuracy:  0.415, Loss:  2.876
Epoch   0 Batch   44/269 - Train Accuracy:  0.387, Validation Accuracy:  0.412, Loss:  2.749
Epoch   0 Batch   45/269 - Train Accuracy:  0.357, Validation Accuracy:  0.417, Loss:  2.872
Epoch   0 Batch   46/269 - Train Accuracy:  0.344, Validation Accuracy:  0.414, Loss:  2.895
Epoch   0 Batch   47/269 - Train Accuracy:  0.422, Validation Accuracy:  0.424, Loss:  2.595
Epoch   0 Batch   48/269 - Train Accuracy:  0.394, Validation Accuracy:  0.420, Loss:  2.684
Epoch   0 Batch   49/269 - Train Accuracy:  0.362, Validation Accuracy:  0.415, Loss:  2.810
Epoch   0 Batch   50/269 - Train Accuracy:  0.377, Validation Accuracy:  0.428, Loss:  2.807
Epoch   0 Batch   51/269 - Train Accuracy:  0.389, Validation Accuracy:  0.423, Loss:  2.717
Epoch   0 Batch   52/269 - Train Accuracy:  0.400, Validation Accuracy:  0.425, Loss:  2.656
Epoch   0 Batch   53/269 - Train Accuracy:  0.382, Validation Accuracy:  0.439, Loss:  2.773
Epoch   0 Batch   54/269 - Train Accuracy:  0.376, Validation Accuracy:  0.430, Loss:  2.762
Epoch   0 Batch   55/269 - Train Accuracy:  0.408, Validation Accuracy:  0.437, Loss:  2.644
Epoch   0 Batch   56/269 - Train Accuracy:  0.409, Validation Accuracy:  0.434, Loss:  2.627
Epoch   0 Batch   57/269 - Train Accuracy:  0.417, Validation Accuracy:  0.443, Loss:  2.624
Epoch   0 Batch   58/269 - Train Accuracy:  0.418, Validation Accuracy:  0.440, Loss:  2.610
Epoch   0 Batch   59/269 - Train Accuracy:  0.412, Validation Accuracy:  0.443, Loss:  2.588
Epoch   0 Batch   60/269 - Train Accuracy:  0.424, Validation Accuracy:  0.440, Loss:  2.539
Epoch   0 Batch   61/269 - Train Accuracy:  0.448, Validation Accuracy:  0.448, Loss:  2.473
Epoch   0 Batch   62/269 - Train Accuracy:  0.446, Validation Accuracy:  0.449, Loss:  2.483
Epoch   0 Batch   63/269 - Train Accuracy:  0.424, Validation Accuracy:  0.449, Loss:  2.552
Epoch   0 Batch   64/269 - Train Accuracy:  0.422, Validation Accuracy:  0.453, Loss:  2.576
Epoch   0 Batch   65/269 - Train Accuracy:  0.430, Validation Accuracy:  0.455, Loss:  2.540
Epoch   0 Batch   66/269 - Train Accuracy:  0.447, Validation Accuracy:  0.453, Loss:  2.476
Epoch   0 Batch   67/269 - Train Accuracy:  0.423, Validation Accuracy:  0.455, Loss:  2.560
Epoch   0 Batch   68/269 - Train Accuracy:  0.420, Validation Accuracy:  0.444, Loss:  2.553
Epoch   0 Batch   69/269 - Train Accuracy:  0.393, Validation Accuracy:  0.455, Loss:  2.701
Epoch   0 Batch   70/269 - Train Accuracy:  0.441, Validation Accuracy:  0.460, Loss:  2.517
Epoch   0 Batch   71/269 - Train Accuracy:  0.398, Validation Accuracy:  0.452, Loss:  2.641
Epoch   0 Batch   72/269 - Train Accuracy:  0.453, Validation Accuracy:  0.462, Loss:  2.432
Epoch   0 Batch   73/269 - Train Accuracy:  0.439, Validation Accuracy:  0.464, Loss:  2.502
Epoch   0 Batch   74/269 - Train Accuracy:  0.409, Validation Accuracy:  0.453, Loss:  2.577
Epoch   0 Batch   75/269 - Train Accuracy:  0.435, Validation Accuracy:  0.465, Loss:  2.490
Epoch   0 Batch   76/269 - Train Accuracy:  0.424, Validation Accuracy:  0.464, Loss:  2.545
Epoch   0 Batch   77/269 - Train Accuracy:  0.449, Validation Accuracy:  0.469, Loss:  2.474
Epoch   0 Batch   78/269 - Train Accuracy:  0.440, Validation Accuracy:  0.467, Loss:  2.495
Epoch   0 Batch   79/269 - Train Accuracy:  0.432, Validation Accuracy:  0.464, Loss:  2.479
Epoch   0 Batch   80/269 - Train Accuracy:  0.454, Validation Accuracy:  0.470, Loss:  2.411
Epoch   0 Batch   81/269 - Train Accuracy:  0.441, Validation Accuracy:  0.462, Loss:  2.471
Epoch   0 Batch   82/269 - Train Accuracy:  0.456, Validation Accuracy:  0.471, Loss:  2.397
Epoch   0 Batch   83/269 - Train Accuracy:  0.448, Validation Accuracy:  0.471, Loss:  2.407
Epoch   0 Batch   84/269 - Train Accuracy:  0.449, Validation Accuracy:  0.475, Loss:  2.432
Epoch   0 Batch   85/269 - Train Accuracy:  0.443, Validation Accuracy:  0.475, Loss:  2.447
Epoch   0 Batch   86/269 - Train Accuracy:  0.428, Validation Accuracy:  0.455, Loss:  2.441
Epoch   0 Batch   87/269 - Train Accuracy:  0.405, Validation Accuracy:  0.471, Loss:  2.597
Epoch   0 Batch   88/269 - Train Accuracy:  0.440, Validation Accuracy:  0.457, Loss:  2.416
Epoch   0 Batch   89/269 - Train Accuracy:  0.460, Validation Accuracy:  0.479, Loss:  2.410
Epoch   0 Batch   90/269 - Train Accuracy:  0.414, Validation Accuracy:  0.473, Loss:  2.549
Epoch   0 Batch   91/269 - Train Accuracy:  0.453, Validation Accuracy:  0.479, Loss:  2.390
Epoch   0 Batch   92/269 - Train Accuracy:  0.451, Validation Accuracy:  0.476, Loss:  2.389
Epoch   0 Batch   93/269 - Train Accuracy:  0.455, Validation Accuracy:  0.456, Loss:  2.310
Epoch   0 Batch   94/269 - Train Accuracy:  0.454, Validation Accuracy:  0.477, Loss:  2.395
Epoch   0 Batch   95/269 - Train Accuracy:  0.457, Validation Accuracy:  0.481, Loss:  2.384
Epoch   0 Batch   96/269 - Train Accuracy:  0.450, Validation Accuracy:  0.477, Loss:  2.370
Epoch   0 Batch   97/269 - Train Accuracy:  0.454, Validation Accuracy:  0.477, Loss:  2.358
Epoch   0 Batch   98/269 - Train Accuracy:  0.464, Validation Accuracy:  0.477, Loss:  2.323
Epoch   0 Batch   99/269 - Train Accuracy:  0.423, Validation Accuracy:  0.475, Loss:  2.471
Epoch   0 Batch  100/269 - Train Accuracy:  0.469, Validation Accuracy:  0.475, Loss:  2.287
Epoch   0 Batch  101/269 - Train Accuracy:  0.423, Validation Accuracy:  0.478, Loss:  2.456
Epoch   0 Batch  102/269 - Train Accuracy:  0.463, Validation Accuracy:  0.485, Loss:  2.328
Epoch   0 Batch  103/269 - Train Accuracy:  0.463, Validation Accuracy:  0.482, Loss:  2.307
Epoch   0 Batch  104/269 - Train Accuracy:  0.450, Validation Accuracy:  0.476, Loss:  2.327
Epoch   0 Batch  105/269 - Train Accuracy:  0.454, Validation Accuracy:  0.480, Loss:  2.334
Epoch   0 Batch  106/269 - Train Accuracy:  0.451, Validation Accuracy:  0.479, Loss:  2.335
Epoch   0 Batch  107/269 - Train Accuracy:  0.426, Validation Accuracy:  0.486, Loss:  2.441
Epoch   0 Batch  108/269 - Train Accuracy:  0.460, Validation Accuracy:  0.486, Loss:  2.303
Epoch   0 Batch  109/269 - Train Accuracy:  0.447, Validation Accuracy:  0.478, Loss:  2.297
Epoch   0 Batch  110/269 - Train Accuracy:  0.460, Validation Accuracy:  0.486, Loss:  2.288
Epoch   0 Batch  111/269 - Train Accuracy:  0.438, Validation Accuracy:  0.494, Loss:  2.416
Epoch   0 Batch  112/269 - Train Accuracy:  0.473, Validation Accuracy:  0.493, Loss:  2.255
Epoch   0 Batch  113/269 - Train Accuracy:  0.491, Validation Accuracy:  0.496, Loss:  2.165
Epoch   0 Batch  114/269 - Train Accuracy:  0.473, Validation Accuracy:  0.496, Loss:  2.249
Epoch   0 Batch  115/269 - Train Accuracy:  0.449, Validation Accuracy:  0.494, Loss:  2.349
Epoch   0 Batch  116/269 - Train Accuracy:  0.477, Validation Accuracy:  0.496, Loss:  2.245
Epoch   0 Batch  117/269 - Train Accuracy:  0.468, Validation Accuracy:  0.494, Loss:  2.245
Epoch   0 Batch  118/269 - Train Accuracy:  0.498, Validation Accuracy:  0.501, Loss:  2.168
Epoch   0 Batch  119/269 - Train Accuracy:  0.462, Validation Accuracy:  0.498, Loss:  2.304
Epoch   0 Batch  120/269 - Train Accuracy:  0.460, Validation Accuracy:  0.503, Loss:  2.312
Epoch   0 Batch  121/269 - Train Accuracy:  0.479, Validation Accuracy:  0.499, Loss:  2.203
Epoch   0 Batch  122/269 - Train Accuracy:  0.485, Validation Accuracy:  0.503, Loss:  2.170
Epoch   0 Batch  123/269 - Train Accuracy:  0.457, Validation Accuracy:  0.507, Loss:  2.309
Epoch   0 Batch  124/269 - Train Accuracy:  0.469, Validation Accuracy:  0.494, Loss:  2.187
Epoch   0 Batch  125/269 - Train Accuracy:  0.479, Validation Accuracy:  0.498, Loss:  2.177
Epoch   0 Batch  126/269 - Train Accuracy:  0.482, Validation Accuracy:  0.500, Loss:  2.153
Epoch   0 Batch  127/269 - Train Accuracy:  0.456, Validation Accuracy:  0.504, Loss:  2.263
Epoch   0 Batch  128/269 - Train Accuracy:  0.494, Validation Accuracy:  0.505, Loss:  2.145
Epoch   0 Batch  129/269 - Train Accuracy:  0.471, Validation Accuracy:  0.496, Loss:  2.177
Epoch   0 Batch  130/269 - Train Accuracy:  0.446, Validation Accuracy:  0.502, Loss:  2.298
Epoch   0 Batch  131/269 - Train Accuracy:  0.460, Validation Accuracy:  0.499, Loss:  2.237
Epoch   0 Batch  132/269 - Train Accuracy:  0.472, Validation Accuracy:  0.502, Loss:  2.162
Epoch   0 Batch  133/269 - Train Accuracy:  0.479, Validation Accuracy:  0.500, Loss:  2.126
Epoch   0 Batch  134/269 - Train Accuracy:  0.438, Validation Accuracy:  0.491, Loss:  2.217
Epoch   0 Batch  135/269 - Train Accuracy:  0.456, Validation Accuracy:  0.511, Loss:  2.284
Epoch   0 Batch  136/269 - Train Accuracy:  0.462, Validation Accuracy:  0.512, Loss:  2.234
Epoch   0 Batch  137/269 - Train Accuracy:  0.462, Validation Accuracy:  0.504, Loss:  2.212
Epoch   0 Batch  138/269 - Train Accuracy:  0.480, Validation Accuracy:  0.512, Loss:  2.172
Epoch   0 Batch  139/269 - Train Accuracy:  0.488, Validation Accuracy:  0.506, Loss:  2.074
Epoch   0 Batch  140/269 - Train Accuracy:  0.487, Validation Accuracy:  0.506, Loss:  2.089
Epoch   0 Batch  141/269 - Train Accuracy:  0.472, Validation Accuracy:  0.506, Loss:  2.132
Epoch   0 Batch  142/269 - Train Accuracy:  0.479, Validation Accuracy:  0.493, Loss:  2.063
Epoch   0 Batch  143/269 - Train Accuracy:  0.484, Validation Accuracy:  0.502, Loss:  2.081
Epoch   0 Batch  144/269 - Train Accuracy:  0.491, Validation Accuracy:  0.510, Loss:  2.048
Epoch   0 Batch  145/269 - Train Accuracy:  0.474, Validation Accuracy:  0.501, Loss:  2.075
Epoch   0 Batch  146/269 - Train Accuracy:  0.481, Validation Accuracy:  0.500, Loss:  2.036
Epoch   0 Batch  147/269 - Train Accuracy:  0.514, Validation Accuracy:  0.511, Loss:  1.965
Epoch   0 Batch  148/269 - Train Accuracy:  0.473, Validation Accuracy:  0.507, Loss:  2.086
Epoch   0 Batch  149/269 - Train Accuracy:  0.489, Validation Accuracy:  0.510, Loss:  2.025
Epoch   0 Batch  150/269 - Train Accuracy:  0.500, Validation Accuracy:  0.516, Loss:  2.032
Epoch   0 Batch  151/269 - Train Accuracy:  0.525, Validation Accuracy:  0.516, Loss:  1.942
Epoch   0 Batch  152/269 - Train Accuracy:  0.480, Validation Accuracy:  0.511, Loss:  2.029
Epoch   0 Batch  153/269 - Train Accuracy:  0.502, Validation Accuracy:  0.515, Loss:  2.014
Epoch   0 Batch  154/269 - Train Accuracy:  0.462, Validation Accuracy:  0.512, Loss:  2.122
Epoch   0 Batch  155/269 - Train Accuracy:  0.519, Validation Accuracy:  0.508, Loss:  1.895
Epoch   0 Batch  156/269 - Train Accuracy:  0.483, Validation Accuracy:  0.515, Loss:  2.054
Epoch   0 Batch  157/269 - Train Accuracy:  0.495, Validation Accuracy:  0.517, Loss:  2.003
Epoch   0 Batch  158/269 - Train Accuracy:  0.485, Validation Accuracy:  0.509, Loss:  1.970
Epoch   0 Batch  159/269 - Train Accuracy:  0.508, Validation Accuracy:  0.528, Loss:  1.988
Epoch   0 Batch  160/269 - Train Accuracy:  0.503, Validation Accuracy:  0.523, Loss:  1.980
Epoch   0 Batch  161/269 - Train Accuracy:  0.483, Validation Accuracy:  0.515, Loss:  1.986
Epoch   0 Batch  162/269 - Train Accuracy:  0.505, Validation Accuracy:  0.525, Loss:  1.964
Epoch   0 Batch  163/269 - Train Accuracy:  0.501, Validation Accuracy:  0.521, Loss:  1.961
Epoch   0 Batch  164/269 - Train Accuracy:  0.501, Validation Accuracy:  0.521, Loss:  1.944
Epoch   0 Batch  165/269 - Train Accuracy:  0.476, Validation Accuracy:  0.525, Loss:  2.020
Epoch   0 Batch  166/269 - Train Accuracy:  0.530, Validation Accuracy:  0.524, Loss:  1.828
Epoch   0 Batch  167/269 - Train Accuracy:  0.506, Validation Accuracy:  0.523, Loss:  1.925
Epoch   0 Batch  168/269 - Train Accuracy:  0.495, Validation Accuracy:  0.520, Loss:  1.937
Epoch   0 Batch  169/269 - Train Accuracy:  0.482, Validation Accuracy:  0.511, Loss:  1.932
Epoch   0 Batch  170/269 - Train Accuracy:  0.501, Validation Accuracy:  0.524, Loss:  1.912
Epoch   0 Batch  171/269 - Train Accuracy:  0.490, Validation Accuracy:  0.528, Loss:  1.981
Epoch   0 Batch  172/269 - Train Accuracy:  0.495, Validation Accuracy:  0.519, Loss:  1.917
Epoch   0 Batch  173/269 - Train Accuracy:  0.506, Validation Accuracy:  0.524, Loss:  1.900
Epoch   0 Batch  174/269 - Train Accuracy:  0.500, Validation Accuracy:  0.528, Loss:  1.900
Epoch   0 Batch  175/269 - Train Accuracy:  0.494, Validation Accuracy:  0.518, Loss:  1.903
Epoch   0 Batch  176/269 - Train Accuracy:  0.482, Validation Accuracy:  0.527, Loss:  1.975
Epoch   0 Batch  177/269 - Train Accuracy:  0.524, Validation Accuracy:  0.529, Loss:  1.820
Epoch   0 Batch  178/269 - Train Accuracy:  0.479, Validation Accuracy:  0.517, Loss:  1.935
Epoch   0 Batch  179/269 - Train Accuracy:  0.514, Validation Accuracy:  0.534, Loss:  1.876
Epoch   0 Batch  180/269 - Train Accuracy:  0.507, Validation Accuracy:  0.527, Loss:  1.853
Epoch   0 Batch  181/269 - Train Accuracy:  0.493, Validation Accuracy:  0.514, Loss:  1.849
Epoch   0 Batch  182/269 - Train Accuracy:  0.511, Validation Accuracy:  0.530, Loss:  1.865
Epoch   0 Batch  183/269 - Train Accuracy:  0.569, Validation Accuracy:  0.527, Loss:  1.626
Epoch   0 Batch  184/269 - Train Accuracy:  0.465, Validation Accuracy:  0.509, Loss:  1.924
Epoch   0 Batch  185/269 - Train Accuracy:  0.524, Validation Accuracy:  0.534, Loss:  1.815
Epoch   0 Batch  186/269 - Train Accuracy:  0.483, Validation Accuracy:  0.533, Loss:  1.915
Epoch   0 Batch  187/269 - Train Accuracy:  0.495, Validation Accuracy:  0.517, Loss:  1.790
Epoch   0 Batch  188/269 - Train Accuracy:  0.527, Validation Accuracy:  0.532, Loss:  1.773
Epoch   0 Batch  189/269 - Train Accuracy:  0.517, Validation Accuracy:  0.533, Loss:  1.789
Epoch   0 Batch  190/269 - Train Accuracy:  0.500, Validation Accuracy:  0.523, Loss:  1.796
Epoch   0 Batch  191/269 - Train Accuracy:  0.514, Validation Accuracy:  0.528, Loss:  1.801
Epoch   0 Batch  192/269 - Train Accuracy:  0.516, Validation Accuracy:  0.532, Loss:  1.796
Epoch   0 Batch  193/269 - Train Accuracy:  0.493, Validation Accuracy:  0.519, Loss:  1.799
Epoch   0 Batch  194/269 - Train Accuracy:  0.509, Validation Accuracy:  0.527, Loss:  1.797
Epoch   0 Batch  195/269 - Train Accuracy:  0.512, Validation Accuracy:  0.538, Loss:  1.812
Epoch   0 Batch  196/269 - Train Accuracy:  0.496, Validation Accuracy:  0.528, Loss:  1.782
Epoch   0 Batch  197/269 - Train Accuracy:  0.469, Validation Accuracy:  0.523, Loss:  1.851
Epoch   0 Batch  198/269 - Train Accuracy:  0.497, Validation Accuracy:  0.543, Loss:  1.880
Epoch   0 Batch  199/269 - Train Accuracy:  0.506, Validation Accuracy:  0.533, Loss:  1.801
Epoch   0 Batch  200/269 - Train Accuracy:  0.487, Validation Accuracy:  0.526, Loss:  1.819
Epoch   0 Batch  201/269 - Train Accuracy:  0.514, Validation Accuracy:  0.538, Loss:  1.757
Epoch   0 Batch  202/269 - Train Accuracy:  0.511, Validation Accuracy:  0.540, Loss:  1.768
Epoch   0 Batch  203/269 - Train Accuracy:  0.488, Validation Accuracy:  0.534, Loss:  1.817
Epoch   0 Batch  204/269 - Train Accuracy:  0.497, Validation Accuracy:  0.539, Loss:  1.815
Epoch   0 Batch  205/269 - Train Accuracy:  0.506, Validation Accuracy:  0.537, Loss:  1.733
Epoch   0 Batch  206/269 - Train Accuracy:  0.479, Validation Accuracy:  0.525, Loss:  1.822
Epoch   0 Batch  207/269 - Train Accuracy:  0.537, Validation Accuracy:  0.538, Loss:  1.671
Epoch   0 Batch  208/269 - Train Accuracy:  0.491, Validation Accuracy:  0.541, Loss:  1.813
Epoch   0 Batch  209/269 - Train Accuracy:  0.483, Validation Accuracy:  0.525, Loss:  1.775
Epoch   0 Batch  210/269 - Train Accuracy:  0.521, Validation Accuracy:  0.538, Loss:  1.700
Epoch   0 Batch  211/269 - Train Accuracy:  0.521, Validation Accuracy:  0.543, Loss:  1.706
Epoch   0 Batch  212/269 - Train Accuracy:  0.525, Validation Accuracy:  0.534, Loss:  1.666
Epoch   0 Batch  213/269 - Train Accuracy:  0.521, Validation Accuracy:  0.539, Loss:  1.686
Epoch   0 Batch  214/269 - Train Accuracy:  0.527, Validation Accuracy:  0.541, Loss:  1.676
Epoch   0 Batch  215/269 - Train Accuracy:  0.540, Validation Accuracy:  0.532, Loss:  1.581
Epoch   0 Batch  216/269 - Train Accuracy:  0.493, Validation Accuracy:  0.545, Loss:  1.792
Epoch   0 Batch  217/269 - Train Accuracy:  0.498, Validation Accuracy:  0.544, Loss:  1.759
Epoch   0 Batch  218/269 - Train Accuracy:  0.504, Validation Accuracy:  0.540, Loss:  1.744
Epoch   0 Batch  219/269 - Train Accuracy:  0.513, Validation Accuracy:  0.542, Loss:  1.718
Epoch   0 Batch  220/269 - Train Accuracy:  0.538, Validation Accuracy:  0.544, Loss:  1.604
Epoch   0 Batch  221/269 - Train Accuracy:  0.532, Validation Accuracy:  0.539, Loss:  1.641
Epoch   0 Batch  222/269 - Train Accuracy:  0.536, Validation Accuracy:  0.544, Loss:  1.606
Epoch   0 Batch  223/269 - Train Accuracy:  0.529, Validation Accuracy:  0.542, Loss:  1.614
Epoch   0 Batch  224/269 - Train Accuracy:  0.519, Validation Accuracy:  0.537, Loss:  1.647
Epoch   0 Batch  225/269 - Train Accuracy:  0.512, Validation Accuracy:  0.544, Loss:  1.704
Epoch   0 Batch  226/269 - Train Accuracy:  0.517, Validation Accuracy:  0.539, Loss:  1.628
Epoch   0 Batch  227/269 - Train Accuracy:  0.579, Validation Accuracy:  0.530, Loss:  1.418
Epoch   0 Batch  228/269 - Train Accuracy:  0.509, Validation Accuracy:  0.540, Loss:  1.645
Epoch   0 Batch  229/269 - Train Accuracy:  0.526, Validation Accuracy:  0.540, Loss:  1.606
Epoch   0 Batch  230/269 - Train Accuracy:  0.503, Validation Accuracy:  0.532, Loss:  1.634
Epoch   0 Batch  231/269 - Train Accuracy:  0.495, Validation Accuracy:  0.540, Loss:  1.694
Epoch   0 Batch  232/269 - Train Accuracy:  0.484, Validation Accuracy:  0.538, Loss:  1.703
Epoch   0 Batch  233/269 - Train Accuracy:  0.513, Validation Accuracy:  0.534, Loss:  1.619
Epoch   0 Batch  234/269 - Train Accuracy:  0.518, Validation Accuracy:  0.537, Loss:  1.609
Epoch   0 Batch  235/269 - Train Accuracy:  0.525, Validation Accuracy:  0.542, Loss:  1.595
Epoch   0 Batch  236/269 - Train Accuracy:  0.509, Validation Accuracy:  0.533, Loss:  1.593
Epoch   0 Batch  237/269 - Train Accuracy:  0.516, Validation Accuracy:  0.539, Loss:  1.581
Epoch   0 Batch  238/269 - Train Accuracy:  0.525, Validation Accuracy:  0.541, Loss:  1.577
Epoch   0 Batch  239/269 - Train Accuracy:  0.517, Validation Accuracy:  0.534, Loss:  1.567
Epoch   0 Batch  240/269 - Train Accuracy:  0.546, Validation Accuracy:  0.535, Loss:  1.461
Epoch   0 Batch  241/269 - Train Accuracy:  0.529, Validation Accuracy:  0.546, Loss:  1.553
Epoch   0 Batch  242/269 - Train Accuracy:  0.499, Validation Accuracy:  0.534, Loss:  1.570
Epoch   0 Batch  243/269 - Train Accuracy:  0.526, Validation Accuracy:  0.533, Loss:  1.522
Epoch   0 Batch  244/269 - Train Accuracy:  0.537, Validation Accuracy:  0.560, Loss:  1.558
Epoch   0 Batch  245/269 - Train Accuracy:  0.481, Validation Accuracy:  0.526, Loss:  1.637
Epoch   0 Batch  246/269 - Train Accuracy:  0.510, Validation Accuracy:  0.539, Loss:  1.557
Epoch   0 Batch  247/269 - Train Accuracy:  0.520, Validation Accuracy:  0.553, Loss:  1.601
Epoch   0 Batch  248/269 - Train Accuracy:  0.500, Validation Accuracy:  0.529, Loss:  1.544
Epoch   0 Batch  249/269 - Train Accuracy:  0.543, Validation Accuracy:  0.539, Loss:  1.472
Epoch   0 Batch  250/269 - Train Accuracy:  0.511, Validation Accuracy:  0.543, Loss:  1.574
Epoch   0 Batch  251/269 - Train Accuracy:  0.511, Validation Accuracy:  0.531, Loss:  1.515
Epoch   0 Batch  252/269 - Train Accuracy:  0.492, Validation Accuracy:  0.532, Loss:  1.549
Epoch   0 Batch  253/269 - Train Accuracy:  0.502, Validation Accuracy:  0.534, Loss:  1.528
Epoch   0 Batch  254/269 - Train Accuracy:  0.510, Validation Accuracy:  0.532, Loss:  1.497
Epoch   0 Batch  255/269 - Train Accuracy:  0.539, Validation Accuracy:  0.538, Loss:  1.446
Epoch   0 Batch  256/269 - Train Accuracy:  0.487, Validation Accuracy:  0.530, Loss:  1.537
Epoch   0 Batch  257/269 - Train Accuracy:  0.497, Validation Accuracy:  0.527, Loss:  1.513
Epoch   0 Batch  258/269 - Train Accuracy:  0.510, Validation Accuracy:  0.543, Loss:  1.509
Epoch   0 Batch  259/269 - Train Accuracy:  0.504, Validation Accuracy:  0.521, Loss:  1.486
Epoch   0 Batch  260/269 - Train Accuracy:  0.496, Validation Accuracy:  0.534, Loss:  1.556
Epoch   0 Batch  261/269 - Train Accuracy:  0.471, Validation Accuracy:  0.537, Loss:  1.580
Epoch   0 Batch  262/269 - Train Accuracy:  0.515, Validation Accuracy:  0.535, Loss:  1.484
Epoch   0 Batch  263/269 - Train Accuracy:  0.483, Validation Accuracy:  0.521, Loss:  1.528
Epoch   0 Batch  264/269 - Train Accuracy:  0.485, Validation Accuracy:  0.530, Loss:  1.540
Epoch   0 Batch  265/269 - Train Accuracy:  0.477, Validation Accuracy:  0.529, Loss:  1.515
Epoch   0 Batch  266/269 - Train Accuracy:  0.501, Validation Accuracy:  0.527, Loss:  1.446
Epoch   0 Batch  267/269 - Train Accuracy:  0.491, Validation Accuracy:  0.525, Loss:  1.477
Epoch   1 Batch    0/269 - Train Accuracy:  0.476, Validation Accuracy:  0.524, Loss:  1.527
Epoch   1 Batch    1/269 - Train Accuracy:  0.464, Validation Accuracy:  0.518, Loss:  1.507
Epoch   1 Batch    2/269 - Train Accuracy:  0.481, Validation Accuracy:  0.526, Loss:  1.472
Epoch   1 Batch    3/269 - Train Accuracy:  0.468, Validation Accuracy:  0.516, Loss:  1.494
Epoch   1 Batch    4/269 - Train Accuracy:  0.465, Validation Accuracy:  0.525, Loss:  1.498
Epoch   1 Batch    5/269 - Train Accuracy:  0.460, Validation Accuracy:  0.514, Loss:  1.507
Epoch   1 Batch    6/269 - Train Accuracy:  0.478, Validation Accuracy:  0.503, Loss:  1.381
Epoch   1 Batch    7/269 - Train Accuracy:  0.494, Validation Accuracy:  0.513, Loss:  1.412
Epoch   1 Batch    8/269 - Train Accuracy:  0.465, Validation Accuracy:  0.516, Loss:  1.478
Epoch   1 Batch    9/269 - Train Accuracy:  0.472, Validation Accuracy:  0.512, Loss:  1.428
Epoch   1 Batch   10/269 - Train Accuracy:  0.446, Validation Accuracy:  0.505, Loss:  1.452
Epoch   1 Batch   11/269 - Train Accuracy:  0.484, Validation Accuracy:  0.509, Loss:  1.413
Epoch   1 Batch   12/269 - Train Accuracy:  0.445, Validation Accuracy:  0.501, Loss:  1.460
Epoch   1 Batch   13/269 - Train Accuracy:  0.514, Validation Accuracy:  0.510, Loss:  1.306
Epoch   1 Batch   14/269 - Train Accuracy:  0.453, Validation Accuracy:  0.493, Loss:  1.390
Epoch   1 Batch   15/269 - Train Accuracy:  0.460, Validation Accuracy:  0.501, Loss:  1.393
Epoch   1 Batch   16/269 - Train Accuracy:  0.487, Validation Accuracy:  0.505, Loss:  1.375
Epoch   1 Batch   17/269 - Train Accuracy:  0.469, Validation Accuracy:  0.498, Loss:  1.361
Epoch   1 Batch   18/269 - Train Accuracy:  0.444, Validation Accuracy:  0.492, Loss:  1.417
Epoch   1 Batch   19/269 - Train Accuracy:  0.500, Validation Accuracy:  0.502, Loss:  1.295
Epoch   1 Batch   20/269 - Train Accuracy:  0.465, Validation Accuracy:  0.507, Loss:  1.414
Epoch   1 Batch   21/269 - Train Accuracy:  0.448, Validation Accuracy:  0.497, Loss:  1.437
Epoch   1 Batch   22/269 - Train Accuracy:  0.476, Validation Accuracy:  0.497, Loss:  1.336
Epoch   1 Batch   23/269 - Train Accuracy:  0.498, Validation Accuracy:  0.502, Loss:  1.340
Epoch   1 Batch   24/269 - Train Accuracy:  0.444, Validation Accuracy:  0.503, Loss:  1.401
Epoch   1 Batch   25/269 - Train Accuracy:  0.440, Validation Accuracy:  0.494, Loss:  1.404
Epoch   1 Batch   26/269 - Train Accuracy:  0.513, Validation Accuracy:  0.509, Loss:  1.257
Epoch   1 Batch   27/269 - Train Accuracy:  0.475, Validation Accuracy:  0.504, Loss:  1.331
Epoch   1 Batch   28/269 - Train Accuracy:  0.417, Validation Accuracy:  0.489, Loss:  1.418
Epoch   1 Batch   29/269 - Train Accuracy:  0.451, Validation Accuracy:  0.507, Loss:  1.367
Epoch   1 Batch   30/269 - Train Accuracy:  0.477, Validation Accuracy:  0.502, Loss:  1.314
Epoch   1 Batch   31/269 - Train Accuracy:  0.469, Validation Accuracy:  0.490, Loss:  1.293
Epoch   1 Batch   32/269 - Train Accuracy:  0.482, Validation Accuracy:  0.516, Loss:  1.305
Epoch   1 Batch   33/269 - Train Accuracy:  0.463, Validation Accuracy:  0.489, Loss:  1.271
Epoch   1 Batch   34/269 - Train Accuracy:  0.465, Validation Accuracy:  0.489, Loss:  1.285
Epoch   1 Batch   35/269 - Train Accuracy:  0.515, Validation Accuracy:  0.522, Loss:  1.286
Epoch   1 Batch   36/269 - Train Accuracy:  0.483, Validation Accuracy:  0.502, Loss:  1.293
Epoch   1 Batch   37/269 - Train Accuracy:  0.470, Validation Accuracy:  0.492, Loss:  1.282
Epoch   1 Batch   38/269 - Train Accuracy:  0.492, Validation Accuracy:  0.513, Loss:  1.287
Epoch   1 Batch   39/269 - Train Accuracy:  0.481, Validation Accuracy:  0.502, Loss:  1.272
Epoch   1 Batch   40/269 - Train Accuracy:  0.419, Validation Accuracy:  0.481, Loss:  1.315
Epoch   1 Batch   41/269 - Train Accuracy:  0.488, Validation Accuracy:  0.511, Loss:  1.275
Epoch   1 Batch   42/269 - Train Accuracy:  0.506, Validation Accuracy:  0.513, Loss:  1.200
Epoch   1 Batch   43/269 - Train Accuracy:  0.432, Validation Accuracy:  0.478, Loss:  1.293
Epoch   1 Batch   44/269 - Train Accuracy:  0.477, Validation Accuracy:  0.501, Loss:  1.247
Epoch   1 Batch   45/269 - Train Accuracy:  0.479, Validation Accuracy:  0.521, Loss:  1.298
Epoch   1 Batch   46/269 - Train Accuracy:  0.430, Validation Accuracy:  0.486, Loss:  1.299
Epoch   1 Batch   47/269 - Train Accuracy:  0.472, Validation Accuracy:  0.478, Loss:  1.163
Epoch   1 Batch   48/269 - Train Accuracy:  0.493, Validation Accuracy:  0.512, Loss:  1.204
Epoch   1 Batch   49/269 - Train Accuracy:  0.472, Validation Accuracy:  0.515, Loss:  1.266
Epoch   1 Batch   50/269 - Train Accuracy:  0.451, Validation Accuracy:  0.496, Loss:  1.267
Epoch   1 Batch   51/269 - Train Accuracy:  0.467, Validation Accuracy:  0.502, Loss:  1.237
Epoch   1 Batch   52/269 - Train Accuracy:  0.496, Validation Accuracy:  0.521, Loss:  1.197
Epoch   1 Batch   53/269 - Train Accuracy:  0.484, Validation Accuracy:  0.524, Loss:  1.265
Epoch   1 Batch   54/269 - Train Accuracy:  0.463, Validation Accuracy:  0.504, Loss:  1.251
Epoch   1 Batch   55/269 - Train Accuracy:  0.481, Validation Accuracy:  0.506, Loss:  1.188
Epoch   1 Batch   56/269 - Train Accuracy:  0.495, Validation Accuracy:  0.514, Loss:  1.191
Epoch   1 Batch   57/269 - Train Accuracy:  0.482, Validation Accuracy:  0.509, Loss:  1.193
Epoch   1 Batch   58/269 - Train Accuracy:  0.499, Validation Accuracy:  0.512, Loss:  1.179
Epoch   1 Batch   59/269 - Train Accuracy:  0.497, Validation Accuracy:  0.515, Loss:  1.153
Epoch   1 Batch   60/269 - Train Accuracy:  0.489, Validation Accuracy:  0.511, Loss:  1.136
Epoch   1 Batch   61/269 - Train Accuracy:  0.497, Validation Accuracy:  0.500, Loss:  1.106
Epoch   1 Batch   62/269 - Train Accuracy:  0.510, Validation Accuracy:  0.514, Loss:  1.129
Epoch   1 Batch   63/269 - Train Accuracy:  0.495, Validation Accuracy:  0.518, Loss:  1.164
Epoch   1 Batch   64/269 - Train Accuracy:  0.477, Validation Accuracy:  0.513, Loss:  1.152
Epoch   1 Batch   65/269 - Train Accuracy:  0.491, Validation Accuracy:  0.515, Loss:  1.137
Epoch   1 Batch   66/269 - Train Accuracy:  0.518, Validation Accuracy:  0.526, Loss:  1.112
Epoch   1 Batch   67/269 - Train Accuracy:  0.502, Validation Accuracy:  0.530, Loss:  1.155
Epoch   1 Batch   68/269 - Train Accuracy:  0.514, Validation Accuracy:  0.538, Loss:  1.152
Epoch   1 Batch   69/269 - Train Accuracy:  0.489, Validation Accuracy:  0.535, Loss:  1.226
Epoch   1 Batch   70/269 - Train Accuracy:  0.512, Validation Accuracy:  0.521, Loss:  1.127
Epoch   1 Batch   71/269 - Train Accuracy:  0.479, Validation Accuracy:  0.514, Loss:  1.181
Epoch   1 Batch   72/269 - Train Accuracy:  0.540, Validation Accuracy:  0.536, Loss:  1.098
Epoch   1 Batch   73/269 - Train Accuracy:  0.512, Validation Accuracy:  0.540, Loss:  1.141
Epoch   1 Batch   74/269 - Train Accuracy:  0.470, Validation Accuracy:  0.513, Loss:  1.144
Epoch   1 Batch   75/269 - Train Accuracy:  0.501, Validation Accuracy:  0.523, Loss:  1.110
Epoch   1 Batch   76/269 - Train Accuracy:  0.519, Validation Accuracy:  0.551, Loss:  1.136
Epoch   1 Batch   77/269 - Train Accuracy:  0.531, Validation Accuracy:  0.538, Loss:  1.105
Epoch   1 Batch   78/269 - Train Accuracy:  0.509, Validation Accuracy:  0.531, Loss:  1.106
Epoch   1 Batch   79/269 - Train Accuracy:  0.527, Validation Accuracy:  0.547, Loss:  1.095
Epoch   1 Batch   80/269 - Train Accuracy:  0.533, Validation Accuracy:  0.537, Loss:  1.073
Epoch   1 Batch   81/269 - Train Accuracy:  0.513, Validation Accuracy:  0.528, Loss:  1.109
Epoch   1 Batch   82/269 - Train Accuracy:  0.526, Validation Accuracy:  0.546, Loss:  1.059
Epoch   1 Batch   83/269 - Train Accuracy:  0.543, Validation Accuracy:  0.549, Loss:  1.069
Epoch   1 Batch   84/269 - Train Accuracy:  0.524, Validation Accuracy:  0.544, Loss:  1.059
Epoch   1 Batch   85/269 - Train Accuracy:  0.507, Validation Accuracy:  0.533, Loss:  1.079
Epoch   1 Batch   86/269 - Train Accuracy:  0.514, Validation Accuracy:  0.552, Loss:  1.084
Epoch   1 Batch   87/269 - Train Accuracy:  0.503, Validation Accuracy:  0.551, Loss:  1.143
Epoch   1 Batch   88/269 - Train Accuracy:  0.528, Validation Accuracy:  0.545, Loss:  1.067
Epoch   1 Batch   89/269 - Train Accuracy:  0.526, Validation Accuracy:  0.540, Loss:  1.057
Epoch   1 Batch   90/269 - Train Accuracy:  0.501, Validation Accuracy:  0.556, Loss:  1.123
Epoch   1 Batch   91/269 - Train Accuracy:  0.527, Validation Accuracy:  0.550, Loss:  1.044
Epoch   1 Batch   92/269 - Train Accuracy:  0.517, Validation Accuracy:  0.528, Loss:  1.047
Epoch   1 Batch   93/269 - Train Accuracy:  0.554, Validation Accuracy:  0.555, Loss:  1.007
Epoch   1 Batch   94/269 - Train Accuracy:  0.545, Validation Accuracy:  0.552, Loss:  1.061
Epoch   1 Batch   95/269 - Train Accuracy:  0.530, Validation Accuracy:  0.543, Loss:  1.051
Epoch   1 Batch   96/269 - Train Accuracy:  0.504, Validation Accuracy:  0.514, Loss:  1.031
Epoch   1 Batch   97/269 - Train Accuracy:  0.526, Validation Accuracy:  0.546, Loss:  1.046
Epoch   1 Batch   98/269 - Train Accuracy:  0.551, Validation Accuracy:  0.543, Loss:  1.020
Epoch   1 Batch   99/269 - Train Accuracy:  0.495, Validation Accuracy:  0.544, Loss:  1.081
Epoch   1 Batch  100/269 - Train Accuracy:  0.547, Validation Accuracy:  0.544, Loss:  1.001
Epoch   1 Batch  101/269 - Train Accuracy:  0.493, Validation Accuracy:  0.543, Loss:  1.077
Epoch   1 Batch  102/269 - Train Accuracy:  0.529, Validation Accuracy:  0.546, Loss:  1.017
Epoch   1 Batch  103/269 - Train Accuracy:  0.523, Validation Accuracy:  0.541, Loss:  1.009
Epoch   1 Batch  104/269 - Train Accuracy:  0.522, Validation Accuracy:  0.538, Loss:  1.017
Epoch   1 Batch  105/269 - Train Accuracy:  0.528, Validation Accuracy:  0.538, Loss:  1.028
Epoch   1 Batch  106/269 - Train Accuracy:  0.531, Validation Accuracy:  0.541, Loss:  1.012
Epoch   1 Batch  107/269 - Train Accuracy:  0.498, Validation Accuracy:  0.540, Loss:  1.059
Epoch   1 Batch  108/269 - Train Accuracy:  0.529, Validation Accuracy:  0.545, Loss:  1.001
Epoch   1 Batch  109/269 - Train Accuracy:  0.513, Validation Accuracy:  0.539, Loss:  1.019
Epoch   1 Batch  110/269 - Train Accuracy:  0.521, Validation Accuracy:  0.538, Loss:  0.987
Epoch   1 Batch  111/269 - Train Accuracy:  0.514, Validation Accuracy:  0.542, Loss:  1.062
Epoch   1 Batch  112/269 - Train Accuracy:  0.532, Validation Accuracy:  0.543, Loss:  0.987
Epoch   1 Batch  113/269 - Train Accuracy:  0.560, Validation Accuracy:  0.550, Loss:  0.949
Epoch   1 Batch  114/269 - Train Accuracy:  0.535, Validation Accuracy:  0.550, Loss:  0.984
Epoch   1 Batch  115/269 - Train Accuracy:  0.521, Validation Accuracy:  0.547, Loss:  1.011
Epoch   1 Batch  116/269 - Train Accuracy:  0.549, Validation Accuracy:  0.544, Loss:  0.989
Epoch   1 Batch  117/269 - Train Accuracy:  0.547, Validation Accuracy:  0.547, Loss:  0.975
Epoch   1 Batch  118/269 - Train Accuracy:  0.560, Validation Accuracy:  0.543, Loss:  0.947
Epoch   1 Batch  119/269 - Train Accuracy:  0.517, Validation Accuracy:  0.546, Loss:  1.023
Epoch   1 Batch  120/269 - Train Accuracy:  0.533, Validation Accuracy:  0.562, Loss:  1.007
Epoch   1 Batch  121/269 - Train Accuracy:  0.551, Validation Accuracy:  0.566, Loss:  0.963
Epoch   1 Batch  122/269 - Train Accuracy:  0.545, Validation Accuracy:  0.557, Loss:  0.957
Epoch   1 Batch  123/269 - Train Accuracy:  0.530, Validation Accuracy:  0.548, Loss:  1.006
Epoch   1 Batch  124/269 - Train Accuracy:  0.554, Validation Accuracy:  0.566, Loss:  0.943
Epoch   1 Batch  125/269 - Train Accuracy:  0.551, Validation Accuracy:  0.565, Loss:  0.937
Epoch   1 Batch  126/269 - Train Accuracy:  0.569, Validation Accuracy:  0.563, Loss:  0.939
Epoch   1 Batch  127/269 - Train Accuracy:  0.547, Validation Accuracy:  0.569, Loss:  0.996
Epoch   1 Batch  128/269 - Train Accuracy:  0.569, Validation Accuracy:  0.575, Loss:  0.944
Epoch   1 Batch  129/269 - Train Accuracy:  0.550, Validation Accuracy:  0.576, Loss:  0.959
Epoch   1 Batch  130/269 - Train Accuracy:  0.530, Validation Accuracy:  0.573, Loss:  0.999
Epoch   1 Batch  131/269 - Train Accuracy:  0.545, Validation Accuracy:  0.570, Loss:  0.970
Epoch   1 Batch  132/269 - Train Accuracy:  0.562, Validation Accuracy:  0.571, Loss:  0.952
Epoch   1 Batch  133/269 - Train Accuracy:  0.563, Validation Accuracy:  0.569, Loss:  0.917
Epoch   1 Batch  134/269 - Train Accuracy:  0.528, Validation Accuracy:  0.570, Loss:  0.967
Epoch   1 Batch  135/269 - Train Accuracy:  0.526, Validation Accuracy:  0.571, Loss:  1.007
Epoch   1 Batch  136/269 - Train Accuracy:  0.522, Validation Accuracy:  0.568, Loss:  0.989
Epoch   1 Batch  137/269 - Train Accuracy:  0.549, Validation Accuracy:  0.564, Loss:  0.974
Epoch   1 Batch  138/269 - Train Accuracy:  0.546, Validation Accuracy:  0.564, Loss:  0.950
Epoch   1 Batch  139/269 - Train Accuracy:  0.574, Validation Accuracy:  0.565, Loss:  0.900
Epoch   1 Batch  140/269 - Train Accuracy:  0.564, Validation Accuracy:  0.570, Loss:  0.929
Epoch   1 Batch  141/269 - Train Accuracy:  0.553, Validation Accuracy:  0.568, Loss:  0.939
Epoch   1 Batch  142/269 - Train Accuracy:  0.556, Validation Accuracy:  0.566, Loss:  0.903
Epoch   1 Batch  143/269 - Train Accuracy:  0.557, Validation Accuracy:  0.569, Loss:  0.919
Epoch   1 Batch  144/269 - Train Accuracy:  0.569, Validation Accuracy:  0.570, Loss:  0.891
Epoch   1 Batch  145/269 - Train Accuracy:  0.558, Validation Accuracy:  0.583, Loss:  0.909
Epoch   1 Batch  146/269 - Train Accuracy:  0.559, Validation Accuracy:  0.570, Loss:  0.900
Epoch   1 Batch  147/269 - Train Accuracy:  0.582, Validation Accuracy:  0.571, Loss:  0.868
Epoch   1 Batch  148/269 - Train Accuracy:  0.552, Validation Accuracy:  0.568, Loss:  0.926
Epoch   1 Batch  149/269 - Train Accuracy:  0.567, Validation Accuracy:  0.571, Loss:  0.902
Epoch   1 Batch  150/269 - Train Accuracy:  0.569, Validation Accuracy:  0.580, Loss:  0.911
Epoch   1 Batch  151/269 - Train Accuracy:  0.603, Validation Accuracy:  0.576, Loss:  0.864
Epoch   1 Batch  152/269 - Train Accuracy:  0.566, Validation Accuracy:  0.577, Loss:  0.899
Epoch   1 Batch  153/269 - Train Accuracy:  0.578, Validation Accuracy:  0.579, Loss:  0.885
Epoch   1 Batch  154/269 - Train Accuracy:  0.541, Validation Accuracy:  0.579, Loss:  0.919
Epoch   1 Batch  155/269 - Train Accuracy:  0.598, Validation Accuracy:  0.578, Loss:  0.842
Epoch   1 Batch  156/269 - Train Accuracy:  0.554, Validation Accuracy:  0.577, Loss:  0.924
Epoch   1 Batch  157/269 - Train Accuracy:  0.559, Validation Accuracy:  0.582, Loss:  0.889
Epoch   1 Batch  158/269 - Train Accuracy:  0.580, Validation Accuracy:  0.580, Loss:  0.877
Epoch   1 Batch  159/269 - Train Accuracy:  0.564, Validation Accuracy:  0.582, Loss:  0.889
Epoch   1 Batch  160/269 - Train Accuracy:  0.563, Validation Accuracy:  0.575, Loss:  0.880
Epoch   1 Batch  161/269 - Train Accuracy:  0.563, Validation Accuracy:  0.578, Loss:  0.887
Epoch   1 Batch  162/269 - Train Accuracy:  0.571, Validation Accuracy:  0.584, Loss:  0.869
Epoch   1 Batch  163/269 - Train Accuracy:  0.581, Validation Accuracy:  0.584, Loss:  0.864
Epoch   1 Batch  164/269 - Train Accuracy:  0.580, Validation Accuracy:  0.578, Loss:  0.866
Epoch   1 Batch  165/269 - Train Accuracy:  0.551, Validation Accuracy:  0.584, Loss:  0.892
Epoch   1 Batch  166/269 - Train Accuracy:  0.596, Validation Accuracy:  0.585, Loss:  0.819
Epoch   1 Batch  167/269 - Train Accuracy:  0.573, Validation Accuracy:  0.583, Loss:  0.869
Epoch   1 Batch  168/269 - Train Accuracy:  0.569, Validation Accuracy:  0.581, Loss:  0.871
Epoch   1 Batch  169/269 - Train Accuracy:  0.582, Validation Accuracy:  0.587, Loss:  0.864
Epoch   1 Batch  170/269 - Train Accuracy:  0.574, Validation Accuracy:  0.589, Loss:  0.856
Epoch   1 Batch  171/269 - Train Accuracy:  0.562, Validation Accuracy:  0.582, Loss:  0.891
Epoch   1 Batch  172/269 - Train Accuracy:  0.577, Validation Accuracy:  0.582, Loss:  0.862
Epoch   1 Batch  173/269 - Train Accuracy:  0.579, Validation Accuracy:  0.584, Loss:  0.844
Epoch   1 Batch  174/269 - Train Accuracy:  0.580, Validation Accuracy:  0.587, Loss:  0.854
Epoch   1 Batch  175/269 - Train Accuracy:  0.592, Validation Accuracy:  0.591, Loss:  0.864
Epoch   1 Batch  176/269 - Train Accuracy:  0.572, Validation Accuracy:  0.591, Loss:  0.899
Epoch   1 Batch  177/269 - Train Accuracy:  0.596, Validation Accuracy:  0.590, Loss:  0.816
Epoch   1 Batch  178/269 - Train Accuracy:  0.572, Validation Accuracy:  0.587, Loss:  0.868
Epoch   1 Batch  179/269 - Train Accuracy:  0.581, Validation Accuracy:  0.583, Loss:  0.846
Epoch   1 Batch  180/269 - Train Accuracy:  0.578, Validation Accuracy:  0.582, Loss:  0.830
Epoch   1 Batch  181/269 - Train Accuracy:  0.572, Validation Accuracy:  0.585, Loss:  0.842
Epoch   1 Batch  182/269 - Train Accuracy:  0.586, Validation Accuracy:  0.580, Loss:  0.848
Epoch   1 Batch  183/269 - Train Accuracy:  0.633, Validation Accuracy:  0.584, Loss:  0.734
Epoch   1 Batch  184/269 - Train Accuracy:  0.559, Validation Accuracy:  0.588, Loss:  0.866
Epoch   1 Batch  185/269 - Train Accuracy:  0.596, Validation Accuracy:  0.589, Loss:  0.833
Epoch   1 Batch  186/269 - Train Accuracy:  0.571, Validation Accuracy:  0.590, Loss:  0.858
Epoch   1 Batch  187/269 - Train Accuracy:  0.595, Validation Accuracy:  0.591, Loss:  0.816
Epoch   1 Batch  188/269 - Train Accuracy:  0.602, Validation Accuracy:  0.596, Loss:  0.804
Epoch   1 Batch  189/269 - Train Accuracy:  0.600, Validation Accuracy:  0.597, Loss:  0.813
Epoch   1 Batch  190/269 - Train Accuracy:  0.586, Validation Accuracy:  0.599, Loss:  0.809
Epoch   1 Batch  191/269 - Train Accuracy:  0.605, Validation Accuracy:  0.599, Loss:  0.817
Epoch   1 Batch  192/269 - Train Accuracy:  0.602, Validation Accuracy:  0.600, Loss:  0.820
Epoch   1 Batch  193/269 - Train Accuracy:  0.594, Validation Accuracy:  0.601, Loss:  0.818
Epoch   1 Batch  194/269 - Train Accuracy:  0.604, Validation Accuracy:  0.603, Loss:  0.823
Epoch   1 Batch  195/269 - Train Accuracy:  0.589, Validation Accuracy:  0.612, Loss:  0.819
Epoch   1 Batch  196/269 - Train Accuracy:  0.586, Validation Accuracy:  0.609, Loss:  0.813
Epoch   1 Batch  197/269 - Train Accuracy:  0.582, Validation Accuracy:  0.611, Loss:  0.849
Epoch   1 Batch  198/269 - Train Accuracy:  0.592, Validation Accuracy:  0.613, Loss:  0.860
Epoch   1 Batch  199/269 - Train Accuracy:  0.595, Validation Accuracy:  0.613, Loss:  0.825
Epoch   1 Batch  200/269 - Train Accuracy:  0.591, Validation Accuracy:  0.609, Loss:  0.834
Epoch   1 Batch  201/269 - Train Accuracy:  0.596, Validation Accuracy:  0.608, Loss:  0.806
Epoch   1 Batch  202/269 - Train Accuracy:  0.603, Validation Accuracy:  0.609, Loss:  0.807
Epoch   1 Batch  203/269 - Train Accuracy:  0.588, Validation Accuracy:  0.608, Loss:  0.852
Epoch   1 Batch  204/269 - Train Accuracy:  0.586, Validation Accuracy:  0.613, Loss:  0.833
Epoch   1 Batch  205/269 - Train Accuracy:  0.596, Validation Accuracy:  0.607, Loss:  0.792
Epoch   1 Batch  206/269 - Train Accuracy:  0.593, Validation Accuracy:  0.605, Loss:  0.835
Epoch   1 Batch  207/269 - Train Accuracy:  0.630, Validation Accuracy:  0.610, Loss:  0.775
Epoch   1 Batch  208/269 - Train Accuracy:  0.592, Validation Accuracy:  0.611, Loss:  0.839
Epoch   1 Batch  209/269 - Train Accuracy:  0.607, Validation Accuracy:  0.609, Loss:  0.808
Epoch   1 Batch  210/269 - Train Accuracy:  0.615, Validation Accuracy:  0.607, Loss:  0.781
Epoch   1 Batch  211/269 - Train Accuracy:  0.604, Validation Accuracy:  0.609, Loss:  0.802
Epoch   1 Batch  212/269 - Train Accuracy:  0.621, Validation Accuracy:  0.616, Loss:  0.777
Epoch   1 Batch  213/269 - Train Accuracy:  0.608, Validation Accuracy:  0.616, Loss:  0.784
Epoch   1 Batch  214/269 - Train Accuracy:  0.615, Validation Accuracy:  0.615, Loss:  0.781
Epoch   1 Batch  215/269 - Train Accuracy:  0.628, Validation Accuracy:  0.610, Loss:  0.740
Epoch   1 Batch  216/269 - Train Accuracy:  0.579, Validation Accuracy:  0.615, Loss:  0.842
Epoch   1 Batch  217/269 - Train Accuracy:  0.581, Validation Accuracy:  0.612, Loss:  0.814
Epoch   1 Batch  218/269 - Train Accuracy:  0.594, Validation Accuracy:  0.617, Loss:  0.818
Epoch   1 Batch  219/269 - Train Accuracy:  0.603, Validation Accuracy:  0.622, Loss:  0.810
Epoch   1 Batch  220/269 - Train Accuracy:  0.618, Validation Accuracy:  0.619, Loss:  0.748
Epoch   1 Batch  221/269 - Train Accuracy:  0.619, Validation Accuracy:  0.615, Loss:  0.773
Epoch   1 Batch  222/269 - Train Accuracy:  0.616, Validation Accuracy:  0.613, Loss:  0.745
Epoch   1 Batch  223/269 - Train Accuracy:  0.603, Validation Accuracy:  0.615, Loss:  0.753
Epoch   1 Batch  224/269 - Train Accuracy:  0.619, Validation Accuracy:  0.618, Loss:  0.791
Epoch   1 Batch  225/269 - Train Accuracy:  0.604, Validation Accuracy:  0.623, Loss:  0.788
Epoch   1 Batch  226/269 - Train Accuracy:  0.597, Validation Accuracy:  0.619, Loss:  0.771
Epoch   1 Batch  227/269 - Train Accuracy:  0.661, Validation Accuracy:  0.616, Loss:  0.679
Epoch   1 Batch  228/269 - Train Accuracy:  0.601, Validation Accuracy:  0.619, Loss:  0.772
Epoch   1 Batch  229/269 - Train Accuracy:  0.609, Validation Accuracy:  0.618, Loss:  0.756
Epoch   1 Batch  230/269 - Train Accuracy:  0.603, Validation Accuracy:  0.625, Loss:  0.771
Epoch   1 Batch  231/269 - Train Accuracy:  0.591, Validation Accuracy:  0.620, Loss:  0.803
Epoch   1 Batch  232/269 - Train Accuracy:  0.589, Validation Accuracy:  0.627, Loss:  0.798
Epoch   1 Batch  233/269 - Train Accuracy:  0.627, Validation Accuracy:  0.627, Loss:  0.769
Epoch   1 Batch  234/269 - Train Accuracy:  0.621, Validation Accuracy:  0.626, Loss:  0.765
Epoch   1 Batch  235/269 - Train Accuracy:  0.628, Validation Accuracy:  0.626, Loss:  0.751
Epoch   1 Batch  236/269 - Train Accuracy:  0.611, Validation Accuracy:  0.628, Loss:  0.755
Epoch   1 Batch  237/269 - Train Accuracy:  0.608, Validation Accuracy:  0.627, Loss:  0.755
Epoch   1 Batch  238/269 - Train Accuracy:  0.638, Validation Accuracy:  0.626, Loss:  0.748
Epoch   1 Batch  239/269 - Train Accuracy:  0.623, Validation Accuracy:  0.630, Loss:  0.750
Epoch   1 Batch  240/269 - Train Accuracy:  0.650, Validation Accuracy:  0.627, Loss:  0.692
Epoch   1 Batch  241/269 - Train Accuracy:  0.622, Validation Accuracy:  0.626, Loss:  0.753
Epoch   1 Batch  242/269 - Train Accuracy:  0.610, Validation Accuracy:  0.624, Loss:  0.747
Epoch   1 Batch  243/269 - Train Accuracy:  0.638, Validation Accuracy:  0.621, Loss:  0.722
Epoch   1 Batch  244/269 - Train Accuracy:  0.606, Validation Accuracy:  0.623, Loss:  0.750
Epoch   1 Batch  245/269 - Train Accuracy:  0.605, Validation Accuracy:  0.628, Loss:  0.787
Epoch   1 Batch  246/269 - Train Accuracy:  0.606, Validation Accuracy:  0.627, Loss:  0.754
Epoch   1 Batch  247/269 - Train Accuracy:  0.606, Validation Accuracy:  0.628, Loss:  0.774
Epoch   1 Batch  248/269 - Train Accuracy:  0.618, Validation Accuracy:  0.630, Loss:  0.735
Epoch   1 Batch  249/269 - Train Accuracy:  0.647, Validation Accuracy:  0.630, Loss:  0.709
Epoch   1 Batch  250/269 - Train Accuracy:  0.608, Validation Accuracy:  0.631, Loss:  0.763
Epoch   1 Batch  251/269 - Train Accuracy:  0.646, Validation Accuracy:  0.631, Loss:  0.726
Epoch   1 Batch  252/269 - Train Accuracy:  0.617, Validation Accuracy:  0.631, Loss:  0.748
Epoch   1 Batch  253/269 - Train Accuracy:  0.615, Validation Accuracy:  0.634, Loss:  0.746
Epoch   1 Batch  254/269 - Train Accuracy:  0.624, Validation Accuracy:  0.633, Loss:  0.731
Epoch   1 Batch  255/269 - Train Accuracy:  0.644, Validation Accuracy:  0.630, Loss:  0.706
Epoch   1 Batch  256/269 - Train Accuracy:  0.608, Validation Accuracy:  0.632, Loss:  0.745
Epoch   1 Batch  257/269 - Train Accuracy:  0.603, Validation Accuracy:  0.635, Loss:  0.744
Epoch   1 Batch  258/269 - Train Accuracy:  0.624, Validation Accuracy:  0.632, Loss:  0.736
Epoch   1 Batch  259/269 - Train Accuracy:  0.633, Validation Accuracy:  0.635, Loss:  0.729
Epoch   1 Batch  260/269 - Train Accuracy:  0.609, Validation Accuracy:  0.631, Loss:  0.763
Epoch   1 Batch  261/269 - Train Accuracy:  0.594, Validation Accuracy:  0.631, Loss:  0.773
Epoch   1 Batch  262/269 - Train Accuracy:  0.625, Validation Accuracy:  0.630, Loss:  0.730
Epoch   1 Batch  263/269 - Train Accuracy:  0.627, Validation Accuracy:  0.628, Loss:  0.756
Epoch   1 Batch  264/269 - Train Accuracy:  0.597, Validation Accuracy:  0.630, Loss:  0.759
Epoch   1 Batch  265/269 - Train Accuracy:  0.611, Validation Accuracy:  0.632, Loss:  0.749
Epoch   1 Batch  266/269 - Train Accuracy:  0.626, Validation Accuracy:  0.628, Loss:  0.712
Epoch   1 Batch  267/269 - Train Accuracy:  0.615, Validation Accuracy:  0.626, Loss:  0.737
Epoch   2 Batch    0/269 - Train Accuracy:  0.608, Validation Accuracy:  0.629, Loss:  0.762
Epoch   2 Batch    1/269 - Train Accuracy:  0.601, Validation Accuracy:  0.630, Loss:  0.740
Epoch   2 Batch    2/269 - Train Accuracy:  0.603, Validation Accuracy:  0.634, Loss:  0.730
Epoch   2 Batch    3/269 - Train Accuracy:  0.619, Validation Accuracy:  0.633, Loss:  0.739
Epoch   2 Batch    4/269 - Train Accuracy:  0.594, Validation Accuracy:  0.633, Loss:  0.751
Epoch   2 Batch    5/269 - Train Accuracy:  0.587, Validation Accuracy:  0.634, Loss:  0.752
Epoch   2 Batch    6/269 - Train Accuracy:  0.626, Validation Accuracy:  0.637, Loss:  0.692
Epoch   2 Batch    7/269 - Train Accuracy:  0.631, Validation Accuracy:  0.638, Loss:  0.705
Epoch   2 Batch    8/269 - Train Accuracy:  0.606, Validation Accuracy:  0.637, Loss:  0.746
Epoch   2 Batch    9/269 - Train Accuracy:  0.614, Validation Accuracy:  0.636, Loss:  0.726
Epoch   2 Batch   10/269 - Train Accuracy:  0.612, Validation Accuracy:  0.635, Loss:  0.731
Epoch   2 Batch   11/269 - Train Accuracy:  0.624, Validation Accuracy:  0.637, Loss:  0.722
Epoch   2 Batch   12/269 - Train Accuracy:  0.602, Validation Accuracy:  0.638, Loss:  0.743
Epoch   2 Batch   13/269 - Train Accuracy:  0.642, Validation Accuracy:  0.639, Loss:  0.661
Epoch   2 Batch   14/269 - Train Accuracy:  0.618, Validation Accuracy:  0.640, Loss:  0.709
Epoch   2 Batch   15/269 - Train Accuracy:  0.612, Validation Accuracy:  0.640, Loss:  0.703
Epoch   2 Batch   16/269 - Train Accuracy:  0.646, Validation Accuracy:  0.639, Loss:  0.701
Epoch   2 Batch   17/269 - Train Accuracy:  0.622, Validation Accuracy:  0.634, Loss:  0.693
Epoch   2 Batch   18/269 - Train Accuracy:  0.602, Validation Accuracy:  0.632, Loss:  0.718
Epoch   2 Batch   19/269 - Train Accuracy:  0.648, Validation Accuracy:  0.630, Loss:  0.658
Epoch   2 Batch   20/269 - Train Accuracy:  0.615, Validation Accuracy:  0.637, Loss:  0.726
Epoch   2 Batch   21/269 - Train Accuracy:  0.619, Validation Accuracy:  0.637, Loss:  0.746
Epoch   2 Batch   22/269 - Train Accuracy:  0.642, Validation Accuracy:  0.637, Loss:  0.679
Epoch   2 Batch   23/269 - Train Accuracy:  0.626, Validation Accuracy:  0.637, Loss:  0.696
Epoch   2 Batch   24/269 - Train Accuracy:  0.613, Validation Accuracy:  0.638, Loss:  0.737
Epoch   2 Batch   25/269 - Train Accuracy:  0.599, Validation Accuracy:  0.640, Loss:  0.739
Epoch   2 Batch   26/269 - Train Accuracy:  0.647, Validation Accuracy:  0.639, Loss:  0.659
Epoch   2 Batch   27/269 - Train Accuracy:  0.613, Validation Accuracy:  0.635, Loss:  0.691
Epoch   2 Batch   28/269 - Train Accuracy:  0.583, Validation Accuracy:  0.638, Loss:  0.746
Epoch   2 Batch   29/269 - Train Accuracy:  0.617, Validation Accuracy:  0.639, Loss:  0.715
Epoch   2 Batch   30/269 - Train Accuracy:  0.639, Validation Accuracy:  0.641, Loss:  0.686
Epoch   2 Batch   31/269 - Train Accuracy:  0.640, Validation Accuracy:  0.643, Loss:  0.675
Epoch   2 Batch   32/269 - Train Accuracy:  0.618, Validation Accuracy:  0.638, Loss:  0.682
Epoch   2 Batch   33/269 - Train Accuracy:  0.638, Validation Accuracy:  0.637, Loss:  0.665
Epoch   2 Batch   34/269 - Train Accuracy:  0.633, Validation Accuracy:  0.640, Loss:  0.681
Epoch   2 Batch   35/269 - Train Accuracy:  0.638, Validation Accuracy:  0.642, Loss:  0.694
Epoch   2 Batch   36/269 - Train Accuracy:  0.627, Validation Accuracy:  0.642, Loss:  0.690
Epoch   2 Batch   37/269 - Train Accuracy:  0.629, Validation Accuracy:  0.637, Loss:  0.679
Epoch   2 Batch   38/269 - Train Accuracy:  0.629, Validation Accuracy:  0.640, Loss:  0.684
Epoch   2 Batch   39/269 - Train Accuracy:  0.630, Validation Accuracy:  0.644, Loss:  0.678
Epoch   2 Batch   40/269 - Train Accuracy:  0.616, Validation Accuracy:  0.646, Loss:  0.711
Epoch   2 Batch   41/269 - Train Accuracy:  0.629, Validation Accuracy:  0.646, Loss:  0.692
Epoch   2 Batch   42/269 - Train Accuracy:  0.647, Validation Accuracy:  0.647, Loss:  0.650
Epoch   2 Batch   43/269 - Train Accuracy:  0.624, Validation Accuracy:  0.647, Loss:  0.703
Epoch   2 Batch   44/269 - Train Accuracy:  0.636, Validation Accuracy:  0.644, Loss:  0.680
Epoch   2 Batch   45/269 - Train Accuracy:  0.616, Validation Accuracy:  0.643, Loss:  0.712
Epoch   2 Batch   46/269 - Train Accuracy:  0.618, Validation Accuracy:  0.642, Loss:  0.702
Epoch   2 Batch   47/269 - Train Accuracy:  0.653, Validation Accuracy:  0.640, Loss:  0.633
Epoch   2 Batch   48/269 - Train Accuracy:  0.624, Validation Accuracy:  0.643, Loss:  0.664
Epoch   2 Batch   49/269 - Train Accuracy:  0.606, Validation Accuracy:  0.645, Loss:  0.696
Epoch   2 Batch   50/269 - Train Accuracy:  0.616, Validation Accuracy:  0.644, Loss:  0.702
Epoch   2 Batch   51/269 - Train Accuracy:  0.626, Validation Accuracy:  0.639, Loss:  0.676
Epoch   2 Batch   52/269 - Train Accuracy:  0.620, Validation Accuracy:  0.640, Loss:  0.656
Epoch   2 Batch   53/269 - Train Accuracy:  0.612, Validation Accuracy:  0.645, Loss:  0.706
Epoch   2 Batch   54/269 - Train Accuracy:  0.632, Validation Accuracy:  0.647, Loss:  0.691
Epoch   2 Batch   55/269 - Train Accuracy:  0.642, Validation Accuracy:  0.642, Loss:  0.661
Epoch   2 Batch   56/269 - Train Accuracy:  0.638, Validation Accuracy:  0.644, Loss:  0.669
Epoch   2 Batch   57/269 - Train Accuracy:  0.630, Validation Accuracy:  0.646, Loss:  0.680
Epoch   2 Batch   58/269 - Train Accuracy:  0.634, Validation Accuracy:  0.645, Loss:  0.659
Epoch   2 Batch   59/269 - Train Accuracy:  0.639, Validation Accuracy:  0.643, Loss:  0.638
Epoch   2 Batch   60/269 - Train Accuracy:  0.634, Validation Accuracy:  0.645, Loss:  0.640
Epoch   2 Batch   61/269 - Train Accuracy:  0.651, Validation Accuracy:  0.644, Loss:  0.621
Epoch   2 Batch   62/269 - Train Accuracy:  0.642, Validation Accuracy:  0.646, Loss:  0.638
Epoch   2 Batch   63/269 - Train Accuracy:  0.623, Validation Accuracy:  0.644, Loss:  0.668
Epoch   2 Batch   64/269 - Train Accuracy:  0.622, Validation Accuracy:  0.647, Loss:  0.654
Epoch   2 Batch   65/269 - Train Accuracy:  0.636, Validation Accuracy:  0.647, Loss:  0.655
Epoch   2 Batch   66/269 - Train Accuracy:  0.639, Validation Accuracy:  0.649, Loss:  0.640
Epoch   2 Batch   67/269 - Train Accuracy:  0.633, Validation Accuracy:  0.649, Loss:  0.669
Epoch   2 Batch   68/269 - Train Accuracy:  0.620, Validation Accuracy:  0.646, Loss:  0.661
Epoch   2 Batch   69/269 - Train Accuracy:  0.612, Validation Accuracy:  0.649, Loss:  0.718
Epoch   2 Batch   70/269 - Train Accuracy:  0.657, Validation Accuracy:  0.653, Loss:  0.660
Epoch   2 Batch   71/269 - Train Accuracy:  0.625, Validation Accuracy:  0.652, Loss:  0.687
Epoch   2 Batch   72/269 - Train Accuracy:  0.638, Validation Accuracy:  0.648, Loss:  0.648
Epoch   2 Batch   73/269 - Train Accuracy:  0.633, Validation Accuracy:  0.645, Loss:  0.668
Epoch   2 Batch   74/269 - Train Accuracy:  0.631, Validation Accuracy:  0.649, Loss:  0.672
Epoch   2 Batch   75/269 - Train Accuracy:  0.638, Validation Accuracy:  0.648, Loss:  0.649
Epoch   2 Batch   76/269 - Train Accuracy:  0.623, Validation Accuracy:  0.652, Loss:  0.670
Epoch   2 Batch   77/269 - Train Accuracy:  0.642, Validation Accuracy:  0.651, Loss:  0.650
Epoch   2 Batch   78/269 - Train Accuracy:  0.641, Validation Accuracy:  0.651, Loss:  0.644
Epoch   2 Batch   79/269 - Train Accuracy:  0.633, Validation Accuracy:  0.651, Loss:  0.645
Epoch   2 Batch   80/269 - Train Accuracy:  0.642, Validation Accuracy:  0.650, Loss:  0.643
Epoch   2 Batch   81/269 - Train Accuracy:  0.644, Validation Accuracy:  0.650, Loss:  0.663
Epoch   2 Batch   82/269 - Train Accuracy:  0.650, Validation Accuracy:  0.649, Loss:  0.623
Epoch   2 Batch   83/269 - Train Accuracy:  0.634, Validation Accuracy:  0.650, Loss:  0.652
Epoch   2 Batch   84/269 - Train Accuracy:  0.636, Validation Accuracy:  0.658, Loss:  0.634
Epoch   2 Batch   85/269 - Train Accuracy:  0.640, Validation Accuracy:  0.658, Loss:  0.646
Epoch   2 Batch   86/269 - Train Accuracy:  0.613, Validation Accuracy:  0.657, Loss:  0.643
Epoch   2 Batch   87/269 - Train Accuracy:  0.614, Validation Accuracy:  0.652, Loss:  0.687
Epoch   2 Batch   88/269 - Train Accuracy:  0.629, Validation Accuracy:  0.655, Loss:  0.643
Epoch   2 Batch   89/269 - Train Accuracy:  0.646, Validation Accuracy:  0.660, Loss:  0.641
Epoch   2 Batch   90/269 - Train Accuracy:  0.607, Validation Accuracy:  0.655, Loss:  0.678
Epoch   2 Batch   91/269 - Train Accuracy:  0.640, Validation Accuracy:  0.651, Loss:  0.624
Epoch   2 Batch   92/269 - Train Accuracy:  0.636, Validation Accuracy:  0.653, Loss:  0.636
Epoch   2 Batch   93/269 - Train Accuracy:  0.659, Validation Accuracy:  0.658, Loss:  0.607
Epoch   2 Batch   94/269 - Train Accuracy:  0.640, Validation Accuracy:  0.656, Loss:  0.650
Epoch   2 Batch   95/269 - Train Accuracy:  0.634, Validation Accuracy:  0.655, Loss:  0.641
Epoch   2 Batch   96/269 - Train Accuracy:  0.638, Validation Accuracy:  0.654, Loss:  0.638
Epoch   2 Batch   97/269 - Train Accuracy:  0.634, Validation Accuracy:  0.652, Loss:  0.636
Epoch   2 Batch   98/269 - Train Accuracy:  0.644, Validation Accuracy:  0.661, Loss:  0.637
Epoch   2 Batch   99/269 - Train Accuracy:  0.634, Validation Accuracy:  0.660, Loss:  0.661
Epoch   2 Batch  100/269 - Train Accuracy:  0.665, Validation Accuracy:  0.658, Loss:  0.626
Epoch   2 Batch  101/269 - Train Accuracy:  0.613, Validation Accuracy:  0.657, Loss:  0.668
Epoch   2 Batch  102/269 - Train Accuracy:  0.640, Validation Accuracy:  0.657, Loss:  0.635
Epoch   2 Batch  103/269 - Train Accuracy:  0.635, Validation Accuracy:  0.659, Loss:  0.621
Epoch   2 Batch  104/269 - Train Accuracy:  0.642, Validation Accuracy:  0.659, Loss:  0.626
Epoch   2 Batch  105/269 - Train Accuracy:  0.636, Validation Accuracy:  0.659, Loss:  0.643
Epoch   2 Batch  106/269 - Train Accuracy:  0.630, Validation Accuracy:  0.654, Loss:  0.628
Epoch   2 Batch  107/269 - Train Accuracy:  0.609, Validation Accuracy:  0.655, Loss:  0.665
Epoch   2 Batch  108/269 - Train Accuracy:  0.637, Validation Accuracy:  0.658, Loss:  0.634
Epoch   2 Batch  109/269 - Train Accuracy:  0.612, Validation Accuracy:  0.659, Loss:  0.639
Epoch   2 Batch  110/269 - Train Accuracy:  0.636, Validation Accuracy:  0.658, Loss:  0.621
Epoch   2 Batch  111/269 - Train Accuracy:  0.609, Validation Accuracy:  0.653, Loss:  0.662
Epoch   2 Batch  112/269 - Train Accuracy:  0.641, Validation Accuracy:  0.654, Loss:  0.625
Epoch   2 Batch  113/269 - Train Accuracy:  0.647, Validation Accuracy:  0.657, Loss:  0.603
Epoch   2 Batch  114/269 - Train Accuracy:  0.643, Validation Accuracy:  0.657, Loss:  0.623
Epoch   2 Batch  115/269 - Train Accuracy:  0.636, Validation Accuracy:  0.660, Loss:  0.649
Epoch   2 Batch  116/269 - Train Accuracy:  0.642, Validation Accuracy:  0.656, Loss:  0.633
Epoch   2 Batch  117/269 - Train Accuracy:  0.642, Validation Accuracy:  0.656, Loss:  0.623
Epoch   2 Batch  118/269 - Train Accuracy:  0.675, Validation Accuracy:  0.659, Loss:  0.606
Epoch   2 Batch  119/269 - Train Accuracy:  0.643, Validation Accuracy:  0.661, Loss:  0.649
Epoch   2 Batch  120/269 - Train Accuracy:  0.632, Validation Accuracy:  0.662, Loss:  0.641
Epoch   2 Batch  121/269 - Train Accuracy:  0.637, Validation Accuracy:  0.661, Loss:  0.617
Epoch   2 Batch  122/269 - Train Accuracy:  0.651, Validation Accuracy:  0.660, Loss:  0.612
Epoch   2 Batch  123/269 - Train Accuracy:  0.625, Validation Accuracy:  0.661, Loss:  0.643
Epoch   2 Batch  124/269 - Train Accuracy:  0.630, Validation Accuracy:  0.656, Loss:  0.611
Epoch   2 Batch  125/269 - Train Accuracy:  0.643, Validation Accuracy:  0.655, Loss:  0.612
Epoch   2 Batch  126/269 - Train Accuracy:  0.634, Validation Accuracy:  0.656, Loss:  0.610
Epoch   2 Batch  127/269 - Train Accuracy:  0.617, Validation Accuracy:  0.656, Loss:  0.642
Epoch   2 Batch  128/269 - Train Accuracy:  0.656, Validation Accuracy:  0.659, Loss:  0.617
Epoch   2 Batch  129/269 - Train Accuracy:  0.641, Validation Accuracy:  0.658, Loss:  0.614
Epoch   2 Batch  130/269 - Train Accuracy:  0.619, Validation Accuracy:  0.657, Loss:  0.643
Epoch   2 Batch  131/269 - Train Accuracy:  0.624, Validation Accuracy:  0.653, Loss:  0.633
Epoch   2 Batch  132/269 - Train Accuracy:  0.635, Validation Accuracy:  0.656, Loss:  0.626
Epoch   2 Batch  133/269 - Train Accuracy:  0.648, Validation Accuracy:  0.657, Loss:  0.597
Epoch   2 Batch  134/269 - Train Accuracy:  0.635, Validation Accuracy:  0.658, Loss:  0.627
Epoch   2 Batch  135/269 - Train Accuracy:  0.610, Validation Accuracy:  0.658, Loss:  0.661
Epoch   2 Batch  136/269 - Train Accuracy:  0.619, Validation Accuracy:  0.660, Loss:  0.652
Epoch   2 Batch  137/269 - Train Accuracy:  0.638, Validation Accuracy:  0.664, Loss:  0.644
Epoch   2 Batch  138/269 - Train Accuracy:  0.640, Validation Accuracy:  0.660, Loss:  0.630
Epoch   2 Batch  139/269 - Train Accuracy:  0.656, Validation Accuracy:  0.659, Loss:  0.591
Epoch   2 Batch  140/269 - Train Accuracy:  0.653, Validation Accuracy:  0.658, Loss:  0.620
Epoch   2 Batch  141/269 - Train Accuracy:  0.637, Validation Accuracy:  0.662, Loss:  0.629
Epoch   2 Batch  142/269 - Train Accuracy:  0.652, Validation Accuracy:  0.663, Loss:  0.593
Epoch   2 Batch  143/269 - Train Accuracy:  0.637, Validation Accuracy:  0.662, Loss:  0.610
Epoch   2 Batch  144/269 - Train Accuracy:  0.646, Validation Accuracy:  0.659, Loss:  0.581
Epoch   2 Batch  145/269 - Train Accuracy:  0.646, Validation Accuracy:  0.659, Loss:  0.604
Epoch   2 Batch  146/269 - Train Accuracy:  0.641, Validation Accuracy:  0.662, Loss:  0.597
Epoch   2 Batch  147/269 - Train Accuracy:  0.661, Validation Accuracy:  0.663, Loss:  0.579
Epoch   2 Batch  148/269 - Train Accuracy:  0.642, Validation Accuracy:  0.660, Loss:  0.611
Epoch   2 Batch  149/269 - Train Accuracy:  0.648, Validation Accuracy:  0.664, Loss:  0.610
Epoch   2 Batch  150/269 - Train Accuracy:  0.650, Validation Accuracy:  0.662, Loss:  0.608
Epoch   2 Batch  151/269 - Train Accuracy:  0.675, Validation Accuracy:  0.661, Loss:  0.580
Epoch   2 Batch  152/269 - Train Accuracy:  0.643, Validation Accuracy:  0.661, Loss:  0.604
Epoch   2 Batch  153/269 - Train Accuracy:  0.643, Validation Accuracy:  0.660, Loss:  0.594
Epoch   2 Batch  154/269 - Train Accuracy:  0.633, Validation Accuracy:  0.662, Loss:  0.616
Epoch   2 Batch  155/269 - Train Accuracy:  0.672, Validation Accuracy:  0.665, Loss:  0.570
Epoch   2 Batch  156/269 - Train Accuracy:  0.630, Validation Accuracy:  0.663, Loss:  0.630
Epoch   2 Batch  157/269 - Train Accuracy:  0.637, Validation Accuracy:  0.663, Loss:  0.598
Epoch   2 Batch  158/269 - Train Accuracy:  0.646, Validation Accuracy:  0.664, Loss:  0.598
Epoch   2 Batch  159/269 - Train Accuracy:  0.646, Validation Accuracy:  0.665, Loss:  0.602
Epoch   2 Batch  160/269 - Train Accuracy:  0.655, Validation Accuracy:  0.667, Loss:  0.594
Epoch   2 Batch  161/269 - Train Accuracy:  0.642, Validation Accuracy:  0.664, Loss:  0.600
Epoch   2 Batch  162/269 - Train Accuracy:  0.646, Validation Accuracy:  0.661, Loss:  0.591
Epoch   2 Batch  163/269 - Train Accuracy:  0.649, Validation Accuracy:  0.664, Loss:  0.590
Epoch   2 Batch  164/269 - Train Accuracy:  0.655, Validation Accuracy:  0.663, Loss:  0.589
Epoch   2 Batch  165/269 - Train Accuracy:  0.628, Validation Accuracy:  0.665, Loss:  0.612
Epoch   2 Batch  166/269 - Train Accuracy:  0.661, Validation Accuracy:  0.669, Loss:  0.564
Epoch   2 Batch  167/269 - Train Accuracy:  0.649, Validation Accuracy:  0.667, Loss:  0.591
Epoch   2 Batch  168/269 - Train Accuracy:  0.643, Validation Accuracy:  0.669, Loss:  0.596
Epoch   2 Batch  169/269 - Train Accuracy:  0.648, Validation Accuracy:  0.670, Loss:  0.592
Epoch   2 Batch  170/269 - Train Accuracy:  0.653, Validation Accuracy:  0.668, Loss:  0.586
Epoch   2 Batch  171/269 - Train Accuracy:  0.648, Validation Accuracy:  0.665, Loss:  0.614
Epoch   2 Batch  172/269 - Train Accuracy:  0.643, Validation Accuracy:  0.664, Loss:  0.596
Epoch   2 Batch  173/269 - Train Accuracy:  0.655, Validation Accuracy:  0.664, Loss:  0.575
Epoch   2 Batch  174/269 - Train Accuracy:  0.638, Validation Accuracy:  0.668, Loss:  0.588
Epoch   2 Batch  175/269 - Train Accuracy:  0.649, Validation Accuracy:  0.670, Loss:  0.604
Epoch   2 Batch  176/269 - Train Accuracy:  0.629, Validation Accuracy:  0.670, Loss:  0.627
Epoch   2 Batch  177/269 - Train Accuracy:  0.667, Validation Accuracy:  0.670, Loss:  0.560
Epoch   2 Batch  178/269 - Train Accuracy:  0.642, Validation Accuracy:  0.668, Loss:  0.599
Epoch   2 Batch  179/269 - Train Accuracy:  0.660, Validation Accuracy:  0.670, Loss:  0.586
Epoch   2 Batch  180/269 - Train Accuracy:  0.652, Validation Accuracy:  0.675, Loss:  0.579
Epoch   2 Batch  181/269 - Train Accuracy:  0.637, Validation Accuracy:  0.672, Loss:  0.585
Epoch   2 Batch  182/269 - Train Accuracy:  0.660, Validation Accuracy:  0.670, Loss:  0.585
Epoch   2 Batch  183/269 - Train Accuracy:  0.697, Validation Accuracy:  0.669, Loss:  0.513
Epoch   2 Batch  184/269 - Train Accuracy:  0.635, Validation Accuracy:  0.672, Loss:  0.607
Epoch   2 Batch  185/269 - Train Accuracy:  0.659, Validation Accuracy:  0.671, Loss:  0.578
Epoch   2 Batch  186/269 - Train Accuracy:  0.638, Validation Accuracy:  0.674, Loss:  0.599
Epoch   2 Batch  187/269 - Train Accuracy:  0.649, Validation Accuracy:  0.672, Loss:  0.571
Epoch   2 Batch  188/269 - Train Accuracy:  0.661, Validation Accuracy:  0.670, Loss:  0.563
Epoch   2 Batch  189/269 - Train Accuracy:  0.652, Validation Accuracy:  0.666, Loss:  0.564
Epoch   2 Batch  190/269 - Train Accuracy:  0.653, Validation Accuracy:  0.671, Loss:  0.567
Epoch   2 Batch  191/269 - Train Accuracy:  0.662, Validation Accuracy:  0.672, Loss:  0.574
Epoch   2 Batch  192/269 - Train Accuracy:  0.655, Validation Accuracy:  0.669, Loss:  0.577
Epoch   2 Batch  193/269 - Train Accuracy:  0.652, Validation Accuracy:  0.672, Loss:  0.572
Epoch   2 Batch  194/269 - Train Accuracy:  0.667, Validation Accuracy:  0.673, Loss:  0.579
Epoch   2 Batch  195/269 - Train Accuracy:  0.653, Validation Accuracy:  0.674, Loss:  0.574
Epoch   2 Batch  196/269 - Train Accuracy:  0.635, Validation Accuracy:  0.670, Loss:  0.573
Epoch   2 Batch  197/269 - Train Accuracy:  0.628, Validation Accuracy:  0.670, Loss:  0.599
Epoch   2 Batch  198/269 - Train Accuracy:  0.638, Validation Accuracy:  0.671, Loss:  0.603
Epoch   2 Batch  199/269 - Train Accuracy:  0.652, Validation Accuracy:  0.675, Loss:  0.582
Epoch   2 Batch  200/269 - Train Accuracy:  0.658, Validation Accuracy:  0.672, Loss:  0.590
Epoch   2 Batch  201/269 - Train Accuracy:  0.651, Validation Accuracy:  0.673, Loss:  0.571
Epoch   2 Batch  202/269 - Train Accuracy:  0.654, Validation Accuracy:  0.674, Loss:  0.569
Epoch   2 Batch  203/269 - Train Accuracy:  0.644, Validation Accuracy:  0.675, Loss:  0.603
Epoch   2 Batch  204/269 - Train Accuracy:  0.628, Validation Accuracy:  0.669, Loss:  0.597
Epoch   2 Batch  205/269 - Train Accuracy:  0.653, Validation Accuracy:  0.671, Loss:  0.559
Epoch   2 Batch  206/269 - Train Accuracy:  0.650, Validation Accuracy:  0.673, Loss:  0.589
Epoch   2 Batch  207/269 - Train Accuracy:  0.670, Validation Accuracy:  0.673, Loss:  0.553
Epoch   2 Batch  208/269 - Train Accuracy:  0.643, Validation Accuracy:  0.667, Loss:  0.591
Epoch   2 Batch  209/269 - Train Accuracy:  0.657, Validation Accuracy:  0.663, Loss:  0.575
Epoch   2 Batch  210/269 - Train Accuracy:  0.661, Validation Accuracy:  0.667, Loss:  0.557
Epoch   2 Batch  211/269 - Train Accuracy:  0.643, Validation Accuracy:  0.669, Loss:  0.577
Epoch   2 Batch  212/269 - Train Accuracy:  0.664, Validation Accuracy:  0.664, Loss:  0.562
Epoch   2 Batch  213/269 - Train Accuracy:  0.654, Validation Accuracy:  0.674, Loss:  0.577
Epoch   2 Batch  214/269 - Train Accuracy:  0.666, Validation Accuracy:  0.665, Loss:  0.562
Epoch   2 Batch  215/269 - Train Accuracy:  0.676, Validation Accuracy:  0.666, Loss:  0.543
Epoch   2 Batch  216/269 - Train Accuracy:  0.636, Validation Accuracy:  0.671, Loss:  0.605
Epoch   2 Batch  217/269 - Train Accuracy:  0.630, Validation Accuracy:  0.670, Loss:  0.594
Epoch   2 Batch  218/269 - Train Accuracy:  0.635, Validation Accuracy:  0.668, Loss:  0.587
Epoch   2 Batch  219/269 - Train Accuracy:  0.660, Validation Accuracy:  0.668, Loss:  0.599
Epoch   2 Batch  220/269 - Train Accuracy:  0.655, Validation Accuracy:  0.662, Loss:  0.537
Epoch   2 Batch  221/269 - Train Accuracy:  0.685, Validation Accuracy:  0.662, Loss:  0.577
Epoch   2 Batch  222/269 - Train Accuracy:  0.678, Validation Accuracy:  0.664, Loss:  0.546
Epoch   2 Batch  223/269 - Train Accuracy:  0.648, Validation Accuracy:  0.669, Loss:  0.559
Epoch   2 Batch  224/269 - Train Accuracy:  0.663, Validation Accuracy:  0.670, Loss:  0.582
Epoch   2 Batch  225/269 - Train Accuracy:  0.655, Validation Accuracy:  0.672, Loss:  0.578
Epoch   2 Batch  226/269 - Train Accuracy:  0.652, Validation Accuracy:  0.667, Loss:  0.561
Epoch   2 Batch  227/269 - Train Accuracy:  0.693, Validation Accuracy:  0.658, Loss:  0.498
Epoch   2 Batch  228/269 - Train Accuracy:  0.652, Validation Accuracy:  0.666, Loss:  0.567
Epoch   2 Batch  229/269 - Train Accuracy:  0.653, Validation Accuracy:  0.665, Loss:  0.547
Epoch   2 Batch  230/269 - Train Accuracy:  0.650, Validation Accuracy:  0.666, Loss:  0.558
Epoch   2 Batch  231/269 - Train Accuracy:  0.635, Validation Accuracy:  0.667, Loss:  0.591
Epoch   2 Batch  232/269 - Train Accuracy:  0.630, Validation Accuracy:  0.657, Loss:  0.587
Epoch   2 Batch  233/269 - Train Accuracy:  0.664, Validation Accuracy:  0.660, Loss:  0.566
Epoch   2 Batch  234/269 - Train Accuracy:  0.658, Validation Accuracy:  0.667, Loss:  0.556
Epoch   2 Batch  235/269 - Train Accuracy:  0.668, Validation Accuracy:  0.669, Loss:  0.544
Epoch   2 Batch  236/269 - Train Accuracy:  0.653, Validation Accuracy:  0.675, Loss:  0.550
Epoch   2 Batch  237/269 - Train Accuracy:  0.647, Validation Accuracy:  0.675, Loss:  0.557
Epoch   2 Batch  238/269 - Train Accuracy:  0.676, Validation Accuracy:  0.673, Loss:  0.544
Epoch   2 Batch  239/269 - Train Accuracy:  0.668, Validation Accuracy:  0.671, Loss:  0.553
Epoch   2 Batch  240/269 - Train Accuracy:  0.677, Validation Accuracy:  0.673, Loss:  0.502
Epoch   2 Batch  241/269 - Train Accuracy:  0.656, Validation Accuracy:  0.673, Loss:  0.556
Epoch   2 Batch  242/269 - Train Accuracy:  0.652, Validation Accuracy:  0.674, Loss:  0.552
Epoch   2 Batch  243/269 - Train Accuracy:  0.671, Validation Accuracy:  0.674, Loss:  0.530
Epoch   2 Batch  244/269 - Train Accuracy:  0.654, Validation Accuracy:  0.676, Loss:  0.557
Epoch   2 Batch  245/269 - Train Accuracy:  0.645, Validation Accuracy:  0.676, Loss:  0.580
Epoch   2 Batch  246/269 - Train Accuracy:  0.639, Validation Accuracy:  0.678, Loss:  0.549
Epoch   2 Batch  247/269 - Train Accuracy:  0.654, Validation Accuracy:  0.679, Loss:  0.569
Epoch   2 Batch  248/269 - Train Accuracy:  0.663, Validation Accuracy:  0.680, Loss:  0.539
Epoch   2 Batch  249/269 - Train Accuracy:  0.691, Validation Accuracy:  0.677, Loss:  0.520
Epoch   2 Batch  250/269 - Train Accuracy:  0.653, Validation Accuracy:  0.675, Loss:  0.561
Epoch   2 Batch  251/269 - Train Accuracy:  0.684, Validation Accuracy:  0.676, Loss:  0.534
Epoch   2 Batch  252/269 - Train Accuracy:  0.657, Validation Accuracy:  0.675, Loss:  0.550
Epoch   2 Batch  253/269 - Train Accuracy:  0.661, Validation Accuracy:  0.675, Loss:  0.554
Epoch   2 Batch  254/269 - Train Accuracy:  0.664, Validation Accuracy:  0.680, Loss:  0.539
Epoch   2 Batch  255/269 - Train Accuracy:  0.679, Validation Accuracy:  0.677, Loss:  0.523
Epoch   2 Batch  256/269 - Train Accuracy:  0.656, Validation Accuracy:  0.677, Loss:  0.551
Epoch   2 Batch  257/269 - Train Accuracy:  0.645, Validation Accuracy:  0.678, Loss:  0.550
Epoch   2 Batch  258/269 - Train Accuracy:  0.663, Validation Accuracy:  0.681, Loss:  0.541
Epoch   2 Batch  259/269 - Train Accuracy:  0.683, Validation Accuracy:  0.680, Loss:  0.534
Epoch   2 Batch  260/269 - Train Accuracy:  0.647, Validation Accuracy:  0.679, Loss:  0.561
Epoch   2 Batch  261/269 - Train Accuracy:  0.645, Validation Accuracy:  0.678, Loss:  0.568
Epoch   2 Batch  262/269 - Train Accuracy:  0.668, Validation Accuracy:  0.679, Loss:  0.538
Epoch   2 Batch  263/269 - Train Accuracy:  0.665, Validation Accuracy:  0.680, Loss:  0.557
Epoch   2 Batch  264/269 - Train Accuracy:  0.643, Validation Accuracy:  0.681, Loss:  0.561
Epoch   2 Batch  265/269 - Train Accuracy:  0.655, Validation Accuracy:  0.680, Loss:  0.556
Epoch   2 Batch  266/269 - Train Accuracy:  0.672, Validation Accuracy:  0.678, Loss:  0.527
Epoch   2 Batch  267/269 - Train Accuracy:  0.674, Validation Accuracy:  0.679, Loss:  0.541
Epoch   3 Batch    0/269 - Train Accuracy:  0.658, Validation Accuracy:  0.682, Loss:  0.562
Epoch   3 Batch    1/269 - Train Accuracy:  0.649, Validation Accuracy:  0.682, Loss:  0.552
Epoch   3 Batch    2/269 - Train Accuracy:  0.660, Validation Accuracy:  0.680, Loss:  0.540
Epoch   3 Batch    3/269 - Train Accuracy:  0.676, Validation Accuracy:  0.682, Loss:  0.547
Epoch   3 Batch    4/269 - Train Accuracy:  0.647, Validation Accuracy:  0.680, Loss:  0.557
Epoch   3 Batch    5/269 - Train Accuracy:  0.650, Validation Accuracy:  0.681, Loss:  0.555
Epoch   3 Batch    6/269 - Train Accuracy:  0.664, Validation Accuracy:  0.684, Loss:  0.520
Epoch   3 Batch    7/269 - Train Accuracy:  0.669, Validation Accuracy:  0.688, Loss:  0.526
Epoch   3 Batch    8/269 - Train Accuracy:  0.658, Validation Accuracy:  0.687, Loss:  0.556
Epoch   3 Batch    9/269 - Train Accuracy:  0.668, Validation Accuracy:  0.686, Loss:  0.543
Epoch   3 Batch   10/269 - Train Accuracy:  0.678, Validation Accuracy:  0.682, Loss:  0.549
Epoch   3 Batch   11/269 - Train Accuracy:  0.676, Validation Accuracy:  0.684, Loss:  0.538
Epoch   3 Batch   12/269 - Train Accuracy:  0.663, Validation Accuracy:  0.685, Loss:  0.559
Epoch   3 Batch   13/269 - Train Accuracy:  0.692, Validation Accuracy:  0.687, Loss:  0.495
Epoch   3 Batch   14/269 - Train Accuracy:  0.674, Validation Accuracy:  0.687, Loss:  0.530
Epoch   3 Batch   15/269 - Train Accuracy:  0.662, Validation Accuracy:  0.687, Loss:  0.521
Epoch   3 Batch   16/269 - Train Accuracy:  0.692, Validation Accuracy:  0.687, Loss:  0.525
Epoch   3 Batch   17/269 - Train Accuracy:  0.682, Validation Accuracy:  0.688, Loss:  0.518
Epoch   3 Batch   18/269 - Train Accuracy:  0.659, Validation Accuracy:  0.690, Loss:  0.537
Epoch   3 Batch   19/269 - Train Accuracy:  0.706, Validation Accuracy:  0.686, Loss:  0.488
Epoch   3 Batch   20/269 - Train Accuracy:  0.671, Validation Accuracy:  0.688, Loss:  0.542
Epoch   3 Batch   21/269 - Train Accuracy:  0.661, Validation Accuracy:  0.689, Loss:  0.556
Epoch   3 Batch   22/269 - Train Accuracy:  0.686, Validation Accuracy:  0.688, Loss:  0.506
Epoch   3 Batch   23/269 - Train Accuracy:  0.674, Validation Accuracy:  0.684, Loss:  0.513
Epoch   3 Batch   24/269 - Train Accuracy:  0.671, Validation Accuracy:  0.686, Loss:  0.552
Epoch   3 Batch   25/269 - Train Accuracy:  0.651, Validation Accuracy:  0.690, Loss:  0.553
Epoch   3 Batch   26/269 - Train Accuracy:  0.692, Validation Accuracy:  0.687, Loss:  0.490
Epoch   3 Batch   27/269 - Train Accuracy:  0.662, Validation Accuracy:  0.686, Loss:  0.514
Epoch   3 Batch   28/269 - Train Accuracy:  0.633, Validation Accuracy:  0.685, Loss:  0.559
Epoch   3 Batch   29/269 - Train Accuracy:  0.665, Validation Accuracy:  0.684, Loss:  0.538
Epoch   3 Batch   30/269 - Train Accuracy:  0.683, Validation Accuracy:  0.689, Loss:  0.514
Epoch   3 Batch   31/269 - Train Accuracy:  0.686, Validation Accuracy:  0.691, Loss:  0.503
Epoch   3 Batch   32/269 - Train Accuracy:  0.667, Validation Accuracy:  0.690, Loss:  0.507
Epoch   3 Batch   33/269 - Train Accuracy:  0.687, Validation Accuracy:  0.686, Loss:  0.501
Epoch   3 Batch   34/269 - Train Accuracy:  0.671, Validation Accuracy:  0.686, Loss:  0.508
Epoch   3 Batch   35/269 - Train Accuracy:  0.682, Validation Accuracy:  0.684, Loss:  0.526
Epoch   3 Batch   36/269 - Train Accuracy:  0.674, Validation Accuracy:  0.691, Loss:  0.515
Epoch   3 Batch   37/269 - Train Accuracy:  0.688, Validation Accuracy:  0.695, Loss:  0.503
Epoch   3 Batch   38/269 - Train Accuracy:  0.681, Validation Accuracy:  0.690, Loss:  0.511
Epoch   3 Batch   39/269 - Train Accuracy:  0.683, Validation Accuracy:  0.685, Loss:  0.509
Epoch   3 Batch   40/269 - Train Accuracy:  0.664, Validation Accuracy:  0.684, Loss:  0.535
Epoch   3 Batch   41/269 - Train Accuracy:  0.673, Validation Accuracy:  0.686, Loss:  0.518
Epoch   3 Batch   42/269 - Train Accuracy:  0.693, Validation Accuracy:  0.688, Loss:  0.485
Epoch   3 Batch   43/269 - Train Accuracy:  0.669, Validation Accuracy:  0.688, Loss:  0.526
Epoch   3 Batch   44/269 - Train Accuracy:  0.682, Validation Accuracy:  0.691, Loss:  0.510
Epoch   3 Batch   45/269 - Train Accuracy:  0.670, Validation Accuracy:  0.689, Loss:  0.534
Epoch   3 Batch   46/269 - Train Accuracy:  0.660, Validation Accuracy:  0.689, Loss:  0.527
Epoch   3 Batch   47/269 - Train Accuracy:  0.691, Validation Accuracy:  0.689, Loss:  0.472
Epoch   3 Batch   48/269 - Train Accuracy:  0.693, Validation Accuracy:  0.693, Loss:  0.498
Epoch   3 Batch   49/269 - Train Accuracy:  0.667, Validation Accuracy:  0.693, Loss:  0.518
Epoch   3 Batch   50/269 - Train Accuracy:  0.668, Validation Accuracy:  0.691, Loss:  0.525
Epoch   3 Batch   51/269 - Train Accuracy:  0.678, Validation Accuracy:  0.687, Loss:  0.502
Epoch   3 Batch   52/269 - Train Accuracy:  0.670, Validation Accuracy:  0.688, Loss:  0.489
Epoch   3 Batch   53/269 - Train Accuracy:  0.676, Validation Accuracy:  0.688, Loss:  0.527
Epoch   3 Batch   54/269 - Train Accuracy:  0.688, Validation Accuracy:  0.692, Loss:  0.517
Epoch   3 Batch   55/269 - Train Accuracy:  0.694, Validation Accuracy:  0.692, Loss:  0.494
Epoch   3 Batch   56/269 - Train Accuracy:  0.693, Validation Accuracy:  0.690, Loss:  0.500
Epoch   3 Batch   57/269 - Train Accuracy:  0.675, Validation Accuracy:  0.692, Loss:  0.512
Epoch   3 Batch   58/269 - Train Accuracy:  0.696, Validation Accuracy:  0.694, Loss:  0.490
Epoch   3 Batch   59/269 - Train Accuracy:  0.700, Validation Accuracy:  0.693, Loss:  0.479
Epoch   3 Batch   60/269 - Train Accuracy:  0.682, Validation Accuracy:  0.694, Loss:  0.480
Epoch   3 Batch   61/269 - Train Accuracy:  0.697, Validation Accuracy:  0.691, Loss:  0.463
Epoch   3 Batch   62/269 - Train Accuracy:  0.696, Validation Accuracy:  0.694, Loss:  0.476
Epoch   3 Batch   63/269 - Train Accuracy:  0.690, Validation Accuracy:  0.697, Loss:  0.501
Epoch   3 Batch   64/269 - Train Accuracy:  0.678, Validation Accuracy:  0.693, Loss:  0.485
Epoch   3 Batch   65/269 - Train Accuracy:  0.683, Validation Accuracy:  0.692, Loss:  0.492
Epoch   3 Batch   66/269 - Train Accuracy:  0.682, Validation Accuracy:  0.694, Loss:  0.479
Epoch   3 Batch   67/269 - Train Accuracy:  0.694, Validation Accuracy:  0.697, Loss:  0.498
Epoch   3 Batch   68/269 - Train Accuracy:  0.668, Validation Accuracy:  0.694, Loss:  0.495
Epoch   3 Batch   69/269 - Train Accuracy:  0.648, Validation Accuracy:  0.696, Loss:  0.537
Epoch   3 Batch   70/269 - Train Accuracy:  0.705, Validation Accuracy:  0.693, Loss:  0.493
Epoch   3 Batch   71/269 - Train Accuracy:  0.689, Validation Accuracy:  0.699, Loss:  0.519
Epoch   3 Batch   72/269 - Train Accuracy:  0.691, Validation Accuracy:  0.696, Loss:  0.487
Epoch   3 Batch   73/269 - Train Accuracy:  0.690, Validation Accuracy:  0.696, Loss:  0.498
Epoch   3 Batch   74/269 - Train Accuracy:  0.679, Validation Accuracy:  0.696, Loss:  0.503
Epoch   3 Batch   75/269 - Train Accuracy:  0.675, Validation Accuracy:  0.701, Loss:  0.489
Epoch   3 Batch   76/269 - Train Accuracy:  0.670, Validation Accuracy:  0.701, Loss:  0.498
Epoch   3 Batch   77/269 - Train Accuracy:  0.700, Validation Accuracy:  0.699, Loss:  0.484
Epoch   3 Batch   78/269 - Train Accuracy:  0.701, Validation Accuracy:  0.695, Loss:  0.481
Epoch   3 Batch   79/269 - Train Accuracy:  0.684, Validation Accuracy:  0.702, Loss:  0.485
Epoch   3 Batch   80/269 - Train Accuracy:  0.696, Validation Accuracy:  0.701, Loss:  0.483
Epoch   3 Batch   81/269 - Train Accuracy:  0.693, Validation Accuracy:  0.695, Loss:  0.497
Epoch   3 Batch   82/269 - Train Accuracy:  0.702, Validation Accuracy:  0.699, Loss:  0.471
Epoch   3 Batch   83/269 - Train Accuracy:  0.694, Validation Accuracy:  0.699, Loss:  0.493
Epoch   3 Batch   84/269 - Train Accuracy:  0.694, Validation Accuracy:  0.698, Loss:  0.477
Epoch   3 Batch   85/269 - Train Accuracy:  0.702, Validation Accuracy:  0.702, Loss:  0.480
Epoch   3 Batch   86/269 - Train Accuracy:  0.676, Validation Accuracy:  0.700, Loss:  0.477
Epoch   3 Batch   87/269 - Train Accuracy:  0.667, Validation Accuracy:  0.702, Loss:  0.513
Epoch   3 Batch   88/269 - Train Accuracy:  0.695, Validation Accuracy:  0.700, Loss:  0.479
Epoch   3 Batch   89/269 - Train Accuracy:  0.701, Validation Accuracy:  0.698, Loss:  0.477
Epoch   3 Batch   90/269 - Train Accuracy:  0.668, Validation Accuracy:  0.696, Loss:  0.507
Epoch   3 Batch   91/269 - Train Accuracy:  0.711, Validation Accuracy:  0.700, Loss:  0.467
Epoch   3 Batch   92/269 - Train Accuracy:  0.690, Validation Accuracy:  0.703, Loss:  0.474
Epoch   3 Batch   93/269 - Train Accuracy:  0.697, Validation Accuracy:  0.703, Loss:  0.458
Epoch   3 Batch   94/269 - Train Accuracy:  0.708, Validation Accuracy:  0.707, Loss:  0.488
Epoch   3 Batch   95/269 - Train Accuracy:  0.697, Validation Accuracy:  0.704, Loss:  0.477
Epoch   3 Batch   96/269 - Train Accuracy:  0.691, Validation Accuracy:  0.699, Loss:  0.479
Epoch   3 Batch   97/269 - Train Accuracy:  0.686, Validation Accuracy:  0.708, Loss:  0.480
Epoch   3 Batch   98/269 - Train Accuracy:  0.694, Validation Accuracy:  0.705, Loss:  0.476
Epoch   3 Batch   99/269 - Train Accuracy:  0.664, Validation Accuracy:  0.696, Loss:  0.502
Epoch   3 Batch  100/269 - Train Accuracy:  0.720, Validation Accuracy:  0.704, Loss:  0.475
Epoch   3 Batch  101/269 - Train Accuracy:  0.685, Validation Accuracy:  0.705, Loss:  0.502
Epoch   3 Batch  102/269 - Train Accuracy:  0.698, Validation Accuracy:  0.700, Loss:  0.486
Epoch   3 Batch  103/269 - Train Accuracy:  0.685, Validation Accuracy:  0.695, Loss:  0.466
Epoch   3 Batch  104/269 - Train Accuracy:  0.706, Validation Accuracy:  0.706, Loss:  0.474
Epoch   3 Batch  105/269 - Train Accuracy:  0.690, Validation Accuracy:  0.707, Loss:  0.479
Epoch   3 Batch  106/269 - Train Accuracy:  0.678, Validation Accuracy:  0.701, Loss:  0.466
Epoch   3 Batch  107/269 - Train Accuracy:  0.678, Validation Accuracy:  0.704, Loss:  0.497
Epoch   3 Batch  108/269 - Train Accuracy:  0.696, Validation Accuracy:  0.713, Loss:  0.478
Epoch   3 Batch  109/269 - Train Accuracy:  0.680, Validation Accuracy:  0.717, Loss:  0.479
Epoch   3 Batch  110/269 - Train Accuracy:  0.694, Validation Accuracy:  0.705, Loss:  0.466
Epoch   3 Batch  111/269 - Train Accuracy:  0.679, Validation Accuracy:  0.707, Loss:  0.494
Epoch   3 Batch  112/269 - Train Accuracy:  0.704, Validation Accuracy:  0.710, Loss:  0.466
Epoch   3 Batch  113/269 - Train Accuracy:  0.700, Validation Accuracy:  0.708, Loss:  0.454
Epoch   3 Batch  114/269 - Train Accuracy:  0.701, Validation Accuracy:  0.703, Loss:  0.468
Epoch   3 Batch  115/269 - Train Accuracy:  0.696, Validation Accuracy:  0.711, Loss:  0.488
Epoch   3 Batch  116/269 - Train Accuracy:  0.708, Validation Accuracy:  0.711, Loss:  0.473
Epoch   3 Batch  117/269 - Train Accuracy:  0.700, Validation Accuracy:  0.710, Loss:  0.466
Epoch   3 Batch  118/269 - Train Accuracy:  0.726, Validation Accuracy:  0.706, Loss:  0.454
Epoch   3 Batch  119/269 - Train Accuracy:  0.699, Validation Accuracy:  0.709, Loss:  0.484
Epoch   3 Batch  120/269 - Train Accuracy:  0.695, Validation Accuracy:  0.711, Loss:  0.478
Epoch   3 Batch  121/269 - Train Accuracy:  0.698, Validation Accuracy:  0.710, Loss:  0.461
Epoch   3 Batch  122/269 - Train Accuracy:  0.714, Validation Accuracy:  0.709, Loss:  0.452
Epoch   3 Batch  123/269 - Train Accuracy:  0.690, Validation Accuracy:  0.712, Loss:  0.478
Epoch   3 Batch  124/269 - Train Accuracy:  0.705, Validation Accuracy:  0.710, Loss:  0.457
Epoch   3 Batch  125/269 - Train Accuracy:  0.701, Validation Accuracy:  0.708, Loss:  0.456
Epoch   3 Batch  126/269 - Train Accuracy:  0.703, Validation Accuracy:  0.708, Loss:  0.457
Epoch   3 Batch  127/269 - Train Accuracy:  0.689, Validation Accuracy:  0.706, Loss:  0.473
Epoch   3 Batch  128/269 - Train Accuracy:  0.714, Validation Accuracy:  0.710, Loss:  0.460
Epoch   3 Batch  129/269 - Train Accuracy:  0.714, Validation Accuracy:  0.708, Loss:  0.452
Epoch   3 Batch  130/269 - Train Accuracy:  0.687, Validation Accuracy:  0.710, Loss:  0.479
Epoch   3 Batch  131/269 - Train Accuracy:  0.692, Validation Accuracy:  0.703, Loss:  0.471
Epoch   3 Batch  132/269 - Train Accuracy:  0.711, Validation Accuracy:  0.710, Loss:  0.468
Epoch   3 Batch  133/269 - Train Accuracy:  0.722, Validation Accuracy:  0.718, Loss:  0.442
Epoch   3 Batch  134/269 - Train Accuracy:  0.694, Validation Accuracy:  0.713, Loss:  0.463
Epoch   3 Batch  135/269 - Train Accuracy:  0.685, Validation Accuracy:  0.718, Loss:  0.489
Epoch   3 Batch  136/269 - Train Accuracy:  0.694, Validation Accuracy:  0.720, Loss:  0.486
Epoch   3 Batch  137/269 - Train Accuracy:  0.696, Validation Accuracy:  0.710, Loss:  0.483
Epoch   3 Batch  138/269 - Train Accuracy:  0.705, Validation Accuracy:  0.710, Loss:  0.468
Epoch   3 Batch  139/269 - Train Accuracy:  0.733, Validation Accuracy:  0.715, Loss:  0.438
Epoch   3 Batch  140/269 - Train Accuracy:  0.699, Validation Accuracy:  0.713, Loss:  0.465
Epoch   3 Batch  141/269 - Train Accuracy:  0.692, Validation Accuracy:  0.713, Loss:  0.472
Epoch   3 Batch  142/269 - Train Accuracy:  0.713, Validation Accuracy:  0.717, Loss:  0.445
Epoch   3 Batch  143/269 - Train Accuracy:  0.703, Validation Accuracy:  0.716, Loss:  0.454
Epoch   3 Batch  144/269 - Train Accuracy:  0.716, Validation Accuracy:  0.712, Loss:  0.431
Epoch   3 Batch  145/269 - Train Accuracy:  0.716, Validation Accuracy:  0.721, Loss:  0.447
Epoch   3 Batch  146/269 - Train Accuracy:  0.719, Validation Accuracy:  0.722, Loss:  0.440
Epoch   3 Batch  147/269 - Train Accuracy:  0.723, Validation Accuracy:  0.717, Loss:  0.429
Epoch   3 Batch  148/269 - Train Accuracy:  0.704, Validation Accuracy:  0.718, Loss:  0.454
Epoch   3 Batch  149/269 - Train Accuracy:  0.709, Validation Accuracy:  0.723, Loss:  0.454
Epoch   3 Batch  150/269 - Train Accuracy:  0.726, Validation Accuracy:  0.720, Loss:  0.445
Epoch   3 Batch  151/269 - Train Accuracy:  0.734, Validation Accuracy:  0.718, Loss:  0.427
Epoch   3 Batch  152/269 - Train Accuracy:  0.714, Validation Accuracy:  0.717, Loss:  0.448
Epoch   3 Batch  153/269 - Train Accuracy:  0.714, Validation Accuracy:  0.724, Loss:  0.442
Epoch   3 Batch  154/269 - Train Accuracy:  0.707, Validation Accuracy:  0.721, Loss:  0.458
Epoch   3 Batch  155/269 - Train Accuracy:  0.729, Validation Accuracy:  0.718, Loss:  0.423
Epoch   3 Batch  156/269 - Train Accuracy:  0.707, Validation Accuracy:  0.723, Loss:  0.458
Epoch   3 Batch  157/269 - Train Accuracy:  0.714, Validation Accuracy:  0.724, Loss:  0.441
Epoch   3 Batch  158/269 - Train Accuracy:  0.720, Validation Accuracy:  0.722, Loss:  0.440
Epoch   3 Batch  159/269 - Train Accuracy:  0.717, Validation Accuracy:  0.722, Loss:  0.443
Epoch   3 Batch  160/269 - Train Accuracy:  0.722, Validation Accuracy:  0.720, Loss:  0.438
Epoch   3 Batch  161/269 - Train Accuracy:  0.706, Validation Accuracy:  0.724, Loss:  0.444
Epoch   3 Batch  162/269 - Train Accuracy:  0.718, Validation Accuracy:  0.726, Loss:  0.434
Epoch   3 Batch  163/269 - Train Accuracy:  0.716, Validation Accuracy:  0.724, Loss:  0.435
Epoch   3 Batch  164/269 - Train Accuracy:  0.727, Validation Accuracy:  0.723, Loss:  0.434
Epoch   3 Batch  165/269 - Train Accuracy:  0.705, Validation Accuracy:  0.724, Loss:  0.450
Epoch   3 Batch  166/269 - Train Accuracy:  0.732, Validation Accuracy:  0.728, Loss:  0.416
Epoch   3 Batch  167/269 - Train Accuracy:  0.713, Validation Accuracy:  0.731, Loss:  0.434
Epoch   3 Batch  168/269 - Train Accuracy:  0.703, Validation Accuracy:  0.728, Loss:  0.441
Epoch   3 Batch  169/269 - Train Accuracy:  0.725, Validation Accuracy:  0.729, Loss:  0.433
Epoch   3 Batch  170/269 - Train Accuracy:  0.718, Validation Accuracy:  0.732, Loss:  0.431
Epoch   3 Batch  171/269 - Train Accuracy:  0.713, Validation Accuracy:  0.727, Loss:  0.452
Epoch   3 Batch  172/269 - Train Accuracy:  0.721, Validation Accuracy:  0.737, Loss:  0.441
Epoch   3 Batch  173/269 - Train Accuracy:  0.730, Validation Accuracy:  0.734, Loss:  0.422
Epoch   3 Batch  174/269 - Train Accuracy:  0.716, Validation Accuracy:  0.722, Loss:  0.432
Epoch   3 Batch  175/269 - Train Accuracy:  0.733, Validation Accuracy:  0.729, Loss:  0.446
Epoch   3 Batch  176/269 - Train Accuracy:  0.701, Validation Accuracy:  0.731, Loss:  0.458
Epoch   3 Batch  177/269 - Train Accuracy:  0.732, Validation Accuracy:  0.733, Loss:  0.409
Epoch   3 Batch  178/269 - Train Accuracy:  0.721, Validation Accuracy:  0.730, Loss:  0.441
Epoch   3 Batch  179/269 - Train Accuracy:  0.725, Validation Accuracy:  0.725, Loss:  0.429
Epoch   3 Batch  180/269 - Train Accuracy:  0.734, Validation Accuracy:  0.732, Loss:  0.422
Epoch   3 Batch  181/269 - Train Accuracy:  0.727, Validation Accuracy:  0.731, Loss:  0.426
Epoch   3 Batch  182/269 - Train Accuracy:  0.736, Validation Accuracy:  0.733, Loss:  0.427
Epoch   3 Batch  183/269 - Train Accuracy:  0.764, Validation Accuracy:  0.735, Loss:  0.374
Epoch   3 Batch  184/269 - Train Accuracy:  0.711, Validation Accuracy:  0.731, Loss:  0.437
Epoch   3 Batch  185/269 - Train Accuracy:  0.727, Validation Accuracy:  0.731, Loss:  0.420
Epoch   3 Batch  186/269 - Train Accuracy:  0.716, Validation Accuracy:  0.730, Loss:  0.436
Epoch   3 Batch  187/269 - Train Accuracy:  0.733, Validation Accuracy:  0.726, Loss:  0.411
Epoch   3 Batch  188/269 - Train Accuracy:  0.741, Validation Accuracy:  0.729, Loss:  0.410
Epoch   3 Batch  189/269 - Train Accuracy:  0.738, Validation Accuracy:  0.732, Loss:  0.409
Epoch   3 Batch  190/269 - Train Accuracy:  0.733, Validation Accuracy:  0.731, Loss:  0.409
Epoch   3 Batch  191/269 - Train Accuracy:  0.735, Validation Accuracy:  0.739, Loss:  0.419
Epoch   3 Batch  192/269 - Train Accuracy:  0.732, Validation Accuracy:  0.737, Loss:  0.419
Epoch   3 Batch  193/269 - Train Accuracy:  0.742, Validation Accuracy:  0.736, Loss:  0.415
Epoch   3 Batch  194/269 - Train Accuracy:  0.747, Validation Accuracy:  0.737, Loss:  0.421
Epoch   3 Batch  195/269 - Train Accuracy:  0.733, Validation Accuracy:  0.738, Loss:  0.414
Epoch   3 Batch  196/269 - Train Accuracy:  0.735, Validation Accuracy:  0.732, Loss:  0.411
Epoch   3 Batch  197/269 - Train Accuracy:  0.712, Validation Accuracy:  0.734, Loss:  0.433
Epoch   3 Batch  198/269 - Train Accuracy:  0.715, Validation Accuracy:  0.739, Loss:  0.438
Epoch   3 Batch  199/269 - Train Accuracy:  0.720, Validation Accuracy:  0.742, Loss:  0.424
Epoch   3 Batch  200/269 - Train Accuracy:  0.731, Validation Accuracy:  0.748, Loss:  0.431
Epoch   3 Batch  201/269 - Train Accuracy:  0.730, Validation Accuracy:  0.744, Loss:  0.414
Epoch   3 Batch  202/269 - Train Accuracy:  0.733, Validation Accuracy:  0.741, Loss:  0.413
Epoch   3 Batch  203/269 - Train Accuracy:  0.731, Validation Accuracy:  0.740, Loss:  0.440
Epoch   3 Batch  204/269 - Train Accuracy:  0.718, Validation Accuracy:  0.732, Loss:  0.434
Epoch   3 Batch  205/269 - Train Accuracy:  0.734, Validation Accuracy:  0.725, Loss:  0.403
Epoch   3 Batch  206/269 - Train Accuracy:  0.715, Validation Accuracy:  0.739, Loss:  0.432
Epoch   3 Batch  207/269 - Train Accuracy:  0.738, Validation Accuracy:  0.746, Loss:  0.401
Epoch   3 Batch  208/269 - Train Accuracy:  0.732, Validation Accuracy:  0.739, Loss:  0.425
Epoch   3 Batch  209/269 - Train Accuracy:  0.749, Validation Accuracy:  0.742, Loss:  0.417
Epoch   3 Batch  210/269 - Train Accuracy:  0.739, Validation Accuracy:  0.746, Loss:  0.403
Epoch   3 Batch  211/269 - Train Accuracy:  0.735, Validation Accuracy:  0.740, Loss:  0.412
Epoch   3 Batch  212/269 - Train Accuracy:  0.743, Validation Accuracy:  0.739, Loss:  0.406
Epoch   3 Batch  213/269 - Train Accuracy:  0.746, Validation Accuracy:  0.740, Loss:  0.410
Epoch   3 Batch  214/269 - Train Accuracy:  0.736, Validation Accuracy:  0.743, Loss:  0.407
Epoch   3 Batch  215/269 - Train Accuracy:  0.758, Validation Accuracy:  0.740, Loss:  0.378
Epoch   3 Batch  216/269 - Train Accuracy:  0.724, Validation Accuracy:  0.743, Loss:  0.427
Epoch   3 Batch  217/269 - Train Accuracy:  0.714, Validation Accuracy:  0.745, Loss:  0.422
Epoch   3 Batch  218/269 - Train Accuracy:  0.726, Validation Accuracy:  0.736, Loss:  0.419
Epoch   3 Batch  219/269 - Train Accuracy:  0.753, Validation Accuracy:  0.740, Loss:  0.423
Epoch   3 Batch  220/269 - Train Accuracy:  0.744, Validation Accuracy:  0.745, Loss:  0.384
Epoch   3 Batch  221/269 - Train Accuracy:  0.750, Validation Accuracy:  0.737, Loss:  0.403
Epoch   3 Batch  222/269 - Train Accuracy:  0.763, Validation Accuracy:  0.746, Loss:  0.389
Epoch   3 Batch  223/269 - Train Accuracy:  0.724, Validation Accuracy:  0.750, Loss:  0.393
Epoch   3 Batch  224/269 - Train Accuracy:  0.744, Validation Accuracy:  0.748, Loss:  0.411
Epoch   3 Batch  225/269 - Train Accuracy:  0.730, Validation Accuracy:  0.749, Loss:  0.404
Epoch   3 Batch  226/269 - Train Accuracy:  0.754, Validation Accuracy:  0.748, Loss:  0.400
Epoch   3 Batch  227/269 - Train Accuracy:  0.773, Validation Accuracy:  0.751, Loss:  0.357
Epoch   3 Batch  228/269 - Train Accuracy:  0.730, Validation Accuracy:  0.753, Loss:  0.399
Epoch   3 Batch  229/269 - Train Accuracy:  0.744, Validation Accuracy:  0.748, Loss:  0.393
Epoch   3 Batch  230/269 - Train Accuracy:  0.742, Validation Accuracy:  0.743, Loss:  0.396
Epoch   3 Batch  231/269 - Train Accuracy:  0.731, Validation Accuracy:  0.747, Loss:  0.414
Epoch   3 Batch  232/269 - Train Accuracy:  0.731, Validation Accuracy:  0.744, Loss:  0.413
Epoch   3 Batch  233/269 - Train Accuracy:  0.753, Validation Accuracy:  0.748, Loss:  0.401
Epoch   3 Batch  234/269 - Train Accuracy:  0.746, Validation Accuracy:  0.746, Loss:  0.391
Epoch   3 Batch  235/269 - Train Accuracy:  0.756, Validation Accuracy:  0.751, Loss:  0.385
Epoch   3 Batch  236/269 - Train Accuracy:  0.735, Validation Accuracy:  0.746, Loss:  0.387
Epoch   3 Batch  237/269 - Train Accuracy:  0.745, Validation Accuracy:  0.745, Loss:  0.394
Epoch   3 Batch  238/269 - Train Accuracy:  0.761, Validation Accuracy:  0.739, Loss:  0.387
Epoch   3 Batch  239/269 - Train Accuracy:  0.755, Validation Accuracy:  0.748, Loss:  0.390
Epoch   3 Batch  240/269 - Train Accuracy:  0.763, Validation Accuracy:  0.750, Loss:  0.356
Epoch   3 Batch  241/269 - Train Accuracy:  0.749, Validation Accuracy:  0.750, Loss:  0.397
Epoch   3 Batch  242/269 - Train Accuracy:  0.742, Validation Accuracy:  0.750, Loss:  0.385
Epoch   3 Batch  243/269 - Train Accuracy:  0.758, Validation Accuracy:  0.756, Loss:  0.372
Epoch   3 Batch  244/269 - Train Accuracy:  0.728, Validation Accuracy:  0.753, Loss:  0.393
Epoch   3 Batch  245/269 - Train Accuracy:  0.742, Validation Accuracy:  0.756, Loss:  0.411
Epoch   3 Batch  246/269 - Train Accuracy:  0.748, Validation Accuracy:  0.755, Loss:  0.383
Epoch   3 Batch  247/269 - Train Accuracy:  0.743, Validation Accuracy:  0.747, Loss:  0.397
Epoch   3 Batch  248/269 - Train Accuracy:  0.765, Validation Accuracy:  0.746, Loss:  0.384
Epoch   3 Batch  249/269 - Train Accuracy:  0.764, Validation Accuracy:  0.751, Loss:  0.368
Epoch   3 Batch  250/269 - Train Accuracy:  0.747, Validation Accuracy:  0.751, Loss:  0.395
Epoch   3 Batch  251/269 - Train Accuracy:  0.769, Validation Accuracy:  0.753, Loss:  0.377
Epoch   3 Batch  252/269 - Train Accuracy:  0.745, Validation Accuracy:  0.755, Loss:  0.385
Epoch   3 Batch  253/269 - Train Accuracy:  0.727, Validation Accuracy:  0.754, Loss:  0.392
Epoch   3 Batch  254/269 - Train Accuracy:  0.745, Validation Accuracy:  0.754, Loss:  0.378
Epoch   3 Batch  255/269 - Train Accuracy:  0.757, Validation Accuracy:  0.757, Loss:  0.374
Epoch   3 Batch  256/269 - Train Accuracy:  0.730, Validation Accuracy:  0.754, Loss:  0.386
Epoch   3 Batch  257/269 - Train Accuracy:  0.736, Validation Accuracy:  0.753, Loss:  0.389
Epoch   3 Batch  258/269 - Train Accuracy:  0.752, Validation Accuracy:  0.748, Loss:  0.381
Epoch   3 Batch  259/269 - Train Accuracy:  0.738, Validation Accuracy:  0.747, Loss:  0.378
Epoch   3 Batch  260/269 - Train Accuracy:  0.733, Validation Accuracy:  0.754, Loss:  0.395
Epoch   3 Batch  261/269 - Train Accuracy:  0.733, Validation Accuracy:  0.756, Loss:  0.398
Epoch   3 Batch  262/269 - Train Accuracy:  0.756, Validation Accuracy:  0.753, Loss:  0.380
Epoch   3 Batch  263/269 - Train Accuracy:  0.761, Validation Accuracy:  0.751, Loss:  0.395
Epoch   3 Batch  264/269 - Train Accuracy:  0.744, Validation Accuracy:  0.752, Loss:  0.394
Epoch   3 Batch  265/269 - Train Accuracy:  0.732, Validation Accuracy:  0.761, Loss:  0.393
Epoch   3 Batch  266/269 - Train Accuracy:  0.763, Validation Accuracy:  0.766, Loss:  0.370
Epoch   3 Batch  267/269 - Train Accuracy:  0.759, Validation Accuracy:  0.759, Loss:  0.379
Epoch   4 Batch    0/269 - Train Accuracy:  0.745, Validation Accuracy:  0.751, Loss:  0.397
Epoch   4 Batch    1/269 - Train Accuracy:  0.752, Validation Accuracy:  0.756, Loss:  0.387
Epoch   4 Batch    2/269 - Train Accuracy:  0.735, Validation Accuracy:  0.751, Loss:  0.378
Epoch   4 Batch    3/269 - Train Accuracy:  0.763, Validation Accuracy:  0.757, Loss:  0.383
Epoch   4 Batch    4/269 - Train Accuracy:  0.734, Validation Accuracy:  0.747, Loss:  0.391
Epoch   4 Batch    5/269 - Train Accuracy:  0.718, Validation Accuracy:  0.745, Loss:  0.386
Epoch   4 Batch    6/269 - Train Accuracy:  0.756, Validation Accuracy:  0.751, Loss:  0.365
Epoch   4 Batch    7/269 - Train Accuracy:  0.754, Validation Accuracy:  0.753, Loss:  0.366
Epoch   4 Batch    8/269 - Train Accuracy:  0.737, Validation Accuracy:  0.749, Loss:  0.388
Epoch   4 Batch    9/269 - Train Accuracy:  0.757, Validation Accuracy:  0.751, Loss:  0.380
Epoch   4 Batch   10/269 - Train Accuracy:  0.764, Validation Accuracy:  0.763, Loss:  0.380
Epoch   4 Batch   11/269 - Train Accuracy:  0.771, Validation Accuracy:  0.762, Loss:  0.375
Epoch   4 Batch   12/269 - Train Accuracy:  0.744, Validation Accuracy:  0.743, Loss:  0.393
Epoch   4 Batch   13/269 - Train Accuracy:  0.770, Validation Accuracy:  0.751, Loss:  0.347
Epoch   4 Batch   14/269 - Train Accuracy:  0.743, Validation Accuracy:  0.760, Loss:  0.368
Epoch   4 Batch   15/269 - Train Accuracy:  0.762, Validation Accuracy:  0.764, Loss:  0.357
Epoch   4 Batch   16/269 - Train Accuracy:  0.762, Validation Accuracy:  0.765, Loss:  0.369
Epoch   4 Batch   17/269 - Train Accuracy:  0.768, Validation Accuracy:  0.765, Loss:  0.356
Epoch   4 Batch   18/269 - Train Accuracy:  0.763, Validation Accuracy:  0.763, Loss:  0.371
Epoch   4 Batch   19/269 - Train Accuracy:  0.778, Validation Accuracy:  0.765, Loss:  0.338
Epoch   4 Batch   20/269 - Train Accuracy:  0.775, Validation Accuracy:  0.765, Loss:  0.375
Epoch   4 Batch   21/269 - Train Accuracy:  0.746, Validation Accuracy:  0.767, Loss:  0.388
Epoch   4 Batch   22/269 - Train Accuracy:  0.785, Validation Accuracy:  0.767, Loss:  0.349
Epoch   4 Batch   23/269 - Train Accuracy:  0.767, Validation Accuracy:  0.770, Loss:  0.356
Epoch   4 Batch   24/269 - Train Accuracy:  0.774, Validation Accuracy:  0.769, Loss:  0.378
Epoch   4 Batch   25/269 - Train Accuracy:  0.757, Validation Accuracy:  0.757, Loss:  0.381
Epoch   4 Batch   26/269 - Train Accuracy:  0.768, Validation Accuracy:  0.769, Loss:  0.341
Epoch   4 Batch   27/269 - Train Accuracy:  0.764, Validation Accuracy:  0.771, Loss:  0.353
Epoch   4 Batch   28/269 - Train Accuracy:  0.728, Validation Accuracy:  0.764, Loss:  0.387
Epoch   4 Batch   29/269 - Train Accuracy:  0.752, Validation Accuracy:  0.761, Loss:  0.376
Epoch   4 Batch   30/269 - Train Accuracy:  0.764, Validation Accuracy:  0.767, Loss:  0.360
Epoch   4 Batch   31/269 - Train Accuracy:  0.775, Validation Accuracy:  0.761, Loss:  0.348
Epoch   4 Batch   32/269 - Train Accuracy:  0.764, Validation Accuracy:  0.761, Loss:  0.352
Epoch   4 Batch   33/269 - Train Accuracy:  0.772, Validation Accuracy:  0.754, Loss:  0.344
Epoch   4 Batch   34/269 - Train Accuracy:  0.766, Validation Accuracy:  0.756, Loss:  0.350
Epoch   4 Batch   35/269 - Train Accuracy:  0.768, Validation Accuracy:  0.764, Loss:  0.366
Epoch   4 Batch   36/269 - Train Accuracy:  0.748, Validation Accuracy:  0.763, Loss:  0.356
Epoch   4 Batch   37/269 - Train Accuracy:  0.760, Validation Accuracy:  0.755, Loss:  0.347
Epoch   4 Batch   38/269 - Train Accuracy:  0.760, Validation Accuracy:  0.760, Loss:  0.352
Epoch   4 Batch   39/269 - Train Accuracy:  0.770, Validation Accuracy:  0.767, Loss:  0.352
Epoch   4 Batch   40/269 - Train Accuracy:  0.741, Validation Accuracy:  0.765, Loss:  0.366
Epoch   4 Batch   41/269 - Train Accuracy:  0.757, Validation Accuracy:  0.770, Loss:  0.356
Epoch   4 Batch   42/269 - Train Accuracy:  0.776, Validation Accuracy:  0.764, Loss:  0.331
Epoch   4 Batch   43/269 - Train Accuracy:  0.759, Validation Accuracy:  0.776, Loss:  0.359
Epoch   4 Batch   44/269 - Train Accuracy:  0.765, Validation Accuracy:  0.779, Loss:  0.350
Epoch   4 Batch   45/269 - Train Accuracy:  0.753, Validation Accuracy:  0.773, Loss:  0.366
Epoch   4 Batch   46/269 - Train Accuracy:  0.770, Validation Accuracy:  0.763, Loss:  0.362
Epoch   4 Batch   47/269 - Train Accuracy:  0.779, Validation Accuracy:  0.773, Loss:  0.324
Epoch   4 Batch   48/269 - Train Accuracy:  0.785, Validation Accuracy:  0.777, Loss:  0.340
Epoch   4 Batch   49/269 - Train Accuracy:  0.754, Validation Accuracy:  0.778, Loss:  0.353
Epoch   4 Batch   50/269 - Train Accuracy:  0.747, Validation Accuracy:  0.773, Loss:  0.364
Epoch   4 Batch   51/269 - Train Accuracy:  0.772, Validation Accuracy:  0.769, Loss:  0.340
Epoch   4 Batch   52/269 - Train Accuracy:  0.749, Validation Accuracy:  0.770, Loss:  0.329
Epoch   4 Batch   53/269 - Train Accuracy:  0.768, Validation Accuracy:  0.773, Loss:  0.362
Epoch   4 Batch   54/269 - Train Accuracy:  0.774, Validation Accuracy:  0.771, Loss:  0.357
Epoch   4 Batch   55/269 - Train Accuracy:  0.786, Validation Accuracy:  0.774, Loss:  0.337
Epoch   4 Batch   56/269 - Train Accuracy:  0.757, Validation Accuracy:  0.774, Loss:  0.342
Epoch   4 Batch   57/269 - Train Accuracy:  0.763, Validation Accuracy:  0.773, Loss:  0.352
Epoch   4 Batch   58/269 - Train Accuracy:  0.784, Validation Accuracy:  0.777, Loss:  0.332
Epoch   4 Batch   59/269 - Train Accuracy:  0.799, Validation Accuracy:  0.779, Loss:  0.319
Epoch   4 Batch   60/269 - Train Accuracy:  0.776, Validation Accuracy:  0.771, Loss:  0.323
Epoch   4 Batch   61/269 - Train Accuracy:  0.783, Validation Accuracy:  0.773, Loss:  0.315
Epoch   4 Batch   62/269 - Train Accuracy:  0.781, Validation Accuracy:  0.768, Loss:  0.327
Epoch   4 Batch   63/269 - Train Accuracy:  0.780, Validation Accuracy:  0.771, Loss:  0.345
Epoch   4 Batch   64/269 - Train Accuracy:  0.779, Validation Accuracy:  0.774, Loss:  0.328
Epoch   4 Batch   65/269 - Train Accuracy:  0.768, Validation Accuracy:  0.774, Loss:  0.335
Epoch   4 Batch   66/269 - Train Accuracy:  0.786, Validation Accuracy:  0.769, Loss:  0.326
Epoch   4 Batch   67/269 - Train Accuracy:  0.771, Validation Accuracy:  0.775, Loss:  0.340
Epoch   4 Batch   68/269 - Train Accuracy:  0.742, Validation Accuracy:  0.771, Loss:  0.340
Epoch   4 Batch   69/269 - Train Accuracy:  0.753, Validation Accuracy:  0.779, Loss:  0.367
Epoch   4 Batch   70/269 - Train Accuracy:  0.788, Validation Accuracy:  0.780, Loss:  0.335
Epoch   4 Batch   71/269 - Train Accuracy:  0.772, Validation Accuracy:  0.782, Loss:  0.356
Epoch   4 Batch   72/269 - Train Accuracy:  0.779, Validation Accuracy:  0.770, Loss:  0.331
Epoch   4 Batch   73/269 - Train Accuracy:  0.752, Validation Accuracy:  0.773, Loss:  0.340
Epoch   4 Batch   74/269 - Train Accuracy:  0.776, Validation Accuracy:  0.780, Loss:  0.340
Epoch   4 Batch   75/269 - Train Accuracy:  0.768, Validation Accuracy:  0.777, Loss:  0.331
Epoch   4 Batch   76/269 - Train Accuracy:  0.753, Validation Accuracy:  0.778, Loss:  0.334
Epoch   4 Batch   77/269 - Train Accuracy:  0.782, Validation Accuracy:  0.777, Loss:  0.325
Epoch   4 Batch   78/269 - Train Accuracy:  0.784, Validation Accuracy:  0.774, Loss:  0.328
Epoch   4 Batch   79/269 - Train Accuracy:  0.768, Validation Accuracy:  0.777, Loss:  0.328
Epoch   4 Batch   80/269 - Train Accuracy:  0.781, Validation Accuracy:  0.778, Loss:  0.326
Epoch   4 Batch   81/269 - Train Accuracy:  0.768, Validation Accuracy:  0.772, Loss:  0.341
Epoch   4 Batch   82/269 - Train Accuracy:  0.792, Validation Accuracy:  0.770, Loss:  0.318
Epoch   4 Batch   83/269 - Train Accuracy:  0.764, Validation Accuracy:  0.776, Loss:  0.335
Epoch   4 Batch   84/269 - Train Accuracy:  0.789, Validation Accuracy:  0.780, Loss:  0.322
Epoch   4 Batch   85/269 - Train Accuracy:  0.793, Validation Accuracy:  0.781, Loss:  0.324
Epoch   4 Batch   86/269 - Train Accuracy:  0.780, Validation Accuracy:  0.780, Loss:  0.322
Epoch   4 Batch   87/269 - Train Accuracy:  0.761, Validation Accuracy:  0.788, Loss:  0.350
Epoch   4 Batch   88/269 - Train Accuracy:  0.763, Validation Accuracy:  0.782, Loss:  0.327
Epoch   4 Batch   89/269 - Train Accuracy:  0.787, Validation Accuracy:  0.779, Loss:  0.322
Epoch   4 Batch   90/269 - Train Accuracy:  0.752, Validation Accuracy:  0.777, Loss:  0.336
Epoch   4 Batch   91/269 - Train Accuracy:  0.787, Validation Accuracy:  0.780, Loss:  0.312
Epoch   4 Batch   92/269 - Train Accuracy:  0.796, Validation Accuracy:  0.779, Loss:  0.314
Epoch   4 Batch   93/269 - Train Accuracy:  0.778, Validation Accuracy:  0.779, Loss:  0.308
Epoch   4 Batch   94/269 - Train Accuracy:  0.783, Validation Accuracy:  0.785, Loss:  0.326
Epoch   4 Batch   95/269 - Train Accuracy:  0.783, Validation Accuracy:  0.779, Loss:  0.314
Epoch   4 Batch   96/269 - Train Accuracy:  0.757, Validation Accuracy:  0.773, Loss:  0.321
Epoch   4 Batch   97/269 - Train Accuracy:  0.769, Validation Accuracy:  0.779, Loss:  0.320
Epoch   4 Batch   98/269 - Train Accuracy:  0.794, Validation Accuracy:  0.777, Loss:  0.318
Epoch   4 Batch   99/269 - Train Accuracy:  0.781, Validation Accuracy:  0.784, Loss:  0.329
Epoch   4 Batch  100/269 - Train Accuracy:  0.800, Validation Accuracy:  0.788, Loss:  0.312
Epoch   4 Batch  101/269 - Train Accuracy:  0.763, Validation Accuracy:  0.785, Loss:  0.336
Epoch   4 Batch  102/269 - Train Accuracy:  0.780, Validation Accuracy:  0.790, Loss:  0.317
Epoch   4 Batch  103/269 - Train Accuracy:  0.796, Validation Accuracy:  0.788, Loss:  0.313
Epoch   4 Batch  104/269 - Train Accuracy:  0.789, Validation Accuracy:  0.788, Loss:  0.313
Epoch   4 Batch  105/269 - Train Accuracy:  0.773, Validation Accuracy:  0.786, Loss:  0.316
Epoch   4 Batch  106/269 - Train Accuracy:  0.772, Validation Accuracy:  0.789, Loss:  0.307
Epoch   4 Batch  107/269 - Train Accuracy:  0.789, Validation Accuracy:  0.787, Loss:  0.328
Epoch   4 Batch  108/269 - Train Accuracy:  0.784, Validation Accuracy:  0.786, Loss:  0.318
Epoch   4 Batch  109/269 - Train Accuracy:  0.774, Validation Accuracy:  0.785, Loss:  0.318
Epoch   4 Batch  110/269 - Train Accuracy:  0.787, Validation Accuracy:  0.786, Loss:  0.313
Epoch   4 Batch  111/269 - Train Accuracy:  0.770, Validation Accuracy:  0.785, Loss:  0.331
Epoch   4 Batch  112/269 - Train Accuracy:  0.776, Validation Accuracy:  0.787, Loss:  0.309
Epoch   4 Batch  113/269 - Train Accuracy:  0.777, Validation Accuracy:  0.778, Loss:  0.301
Epoch   4 Batch  114/269 - Train Accuracy:  0.787, Validation Accuracy:  0.785, Loss:  0.311
Epoch   4 Batch  115/269 - Train Accuracy:  0.778, Validation Accuracy:  0.788, Loss:  0.323
Epoch   4 Batch  116/269 - Train Accuracy:  0.803, Validation Accuracy:  0.788, Loss:  0.319
Epoch   4 Batch  117/269 - Train Accuracy:  0.788, Validation Accuracy:  0.779, Loss:  0.308
Epoch   4 Batch  118/269 - Train Accuracy:  0.803, Validation Accuracy:  0.778, Loss:  0.300
Epoch   4 Batch  119/269 - Train Accuracy:  0.779, Validation Accuracy:  0.789, Loss:  0.326
Epoch   4 Batch  120/269 - Train Accuracy:  0.774, Validation Accuracy:  0.790, Loss:  0.317
Epoch   4 Batch  121/269 - Train Accuracy:  0.793, Validation Accuracy:  0.789, Loss:  0.304
Epoch   4 Batch  122/269 - Train Accuracy:  0.794, Validation Accuracy:  0.787, Loss:  0.300
Epoch   4 Batch  123/269 - Train Accuracy:  0.782, Validation Accuracy:  0.789, Loss:  0.314
Epoch   4 Batch  124/269 - Train Accuracy:  0.790, Validation Accuracy:  0.786, Loss:  0.301
Epoch   4 Batch  125/269 - Train Accuracy:  0.800, Validation Accuracy:  0.789, Loss:  0.299
Epoch   4 Batch  126/269 - Train Accuracy:  0.780, Validation Accuracy:  0.778, Loss:  0.304
Epoch   4 Batch  127/269 - Train Accuracy:  0.776, Validation Accuracy:  0.789, Loss:  0.313
Epoch   4 Batch  128/269 - Train Accuracy:  0.797, Validation Accuracy:  0.787, Loss:  0.303
Epoch   4 Batch  129/269 - Train Accuracy:  0.787, Validation Accuracy:  0.789, Loss:  0.300
Epoch   4 Batch  130/269 - Train Accuracy:  0.782, Validation Accuracy:  0.791, Loss:  0.316
Epoch   4 Batch  131/269 - Train Accuracy:  0.770, Validation Accuracy:  0.790, Loss:  0.312
Epoch   4 Batch  132/269 - Train Accuracy:  0.775, Validation Accuracy:  0.789, Loss:  0.310
Epoch   4 Batch  133/269 - Train Accuracy:  0.817, Validation Accuracy:  0.788, Loss:  0.288
Epoch   4 Batch  134/269 - Train Accuracy:  0.780, Validation Accuracy:  0.788, Loss:  0.305
Epoch   4 Batch  135/269 - Train Accuracy:  0.779, Validation Accuracy:  0.790, Loss:  0.321
Epoch   4 Batch  136/269 - Train Accuracy:  0.770, Validation Accuracy:  0.791, Loss:  0.320
Epoch   4 Batch  137/269 - Train Accuracy:  0.785, Validation Accuracy:  0.789, Loss:  0.319
Epoch   4 Batch  138/269 - Train Accuracy:  0.799, Validation Accuracy:  0.793, Loss:  0.302
Epoch   4 Batch  139/269 - Train Accuracy:  0.799, Validation Accuracy:  0.797, Loss:  0.288
Epoch   4 Batch  140/269 - Train Accuracy:  0.798, Validation Accuracy:  0.797, Loss:  0.307
Epoch   4 Batch  141/269 - Train Accuracy:  0.789, Validation Accuracy:  0.798, Loss:  0.308
Epoch   4 Batch  142/269 - Train Accuracy:  0.785, Validation Accuracy:  0.804, Loss:  0.293
Epoch   4 Batch  143/269 - Train Accuracy:  0.789, Validation Accuracy:  0.802, Loss:  0.295
Epoch   4 Batch  144/269 - Train Accuracy:  0.806, Validation Accuracy:  0.797, Loss:  0.278
Epoch   4 Batch  145/269 - Train Accuracy:  0.801, Validation Accuracy:  0.798, Loss:  0.292
Epoch   4 Batch  146/269 - Train Accuracy:  0.791, Validation Accuracy:  0.795, Loss:  0.291
Epoch   4 Batch  147/269 - Train Accuracy:  0.806, Validation Accuracy:  0.804, Loss:  0.283
Epoch   4 Batch  148/269 - Train Accuracy:  0.795, Validation Accuracy:  0.804, Loss:  0.303
Epoch   4 Batch  149/269 - Train Accuracy:  0.776, Validation Accuracy:  0.798, Loss:  0.301
Epoch   4 Batch  150/269 - Train Accuracy:  0.812, Validation Accuracy:  0.789, Loss:  0.287
Epoch   4 Batch  151/269 - Train Accuracy:  0.815, Validation Accuracy:  0.799, Loss:  0.279
Epoch   4 Batch  152/269 - Train Accuracy:  0.799, Validation Accuracy:  0.804, Loss:  0.293
Epoch   4 Batch  153/269 - Train Accuracy:  0.809, Validation Accuracy:  0.799, Loss:  0.291
Epoch   4 Batch  154/269 - Train Accuracy:  0.812, Validation Accuracy:  0.803, Loss:  0.299
Epoch   4 Batch  155/269 - Train Accuracy:  0.803, Validation Accuracy:  0.807, Loss:  0.279
Epoch   4 Batch  156/269 - Train Accuracy:  0.793, Validation Accuracy:  0.810, Loss:  0.298
Epoch   4 Batch  157/269 - Train Accuracy:  0.799, Validation Accuracy:  0.809, Loss:  0.281
Epoch   4 Batch  158/269 - Train Accuracy:  0.797, Validation Accuracy:  0.812, Loss:  0.286
Epoch   4 Batch  159/269 - Train Accuracy:  0.795, Validation Accuracy:  0.805, Loss:  0.290
Epoch   4 Batch  160/269 - Train Accuracy:  0.796, Validation Accuracy:  0.802, Loss:  0.289
Epoch   4 Batch  161/269 - Train Accuracy:  0.792, Validation Accuracy:  0.802, Loss:  0.288
Epoch   4 Batch  162/269 - Train Accuracy:  0.813, Validation Accuracy:  0.807, Loss:  0.282
Epoch   4 Batch  163/269 - Train Accuracy:  0.808, Validation Accuracy:  0.803, Loss:  0.285
Epoch   4 Batch  164/269 - Train Accuracy:  0.805, Validation Accuracy:  0.809, Loss:  0.283
Epoch   4 Batch  165/269 - Train Accuracy:  0.807, Validation Accuracy:  0.805, Loss:  0.292
Epoch   4 Batch  166/269 - Train Accuracy:  0.817, Validation Accuracy:  0.802, Loss:  0.274
Epoch   4 Batch  167/269 - Train Accuracy:  0.811, Validation Accuracy:  0.807, Loss:  0.281
Epoch   4 Batch  168/269 - Train Accuracy:  0.805, Validation Accuracy:  0.813, Loss:  0.288
Epoch   4 Batch  169/269 - Train Accuracy:  0.811, Validation Accuracy:  0.808, Loss:  0.280
Epoch   4 Batch  170/269 - Train Accuracy:  0.803, Validation Accuracy:  0.811, Loss:  0.283
Epoch   4 Batch  171/269 - Train Accuracy:  0.801, Validation Accuracy:  0.810, Loss:  0.291
Epoch   4 Batch  172/269 - Train Accuracy:  0.794, Validation Accuracy:  0.808, Loss:  0.292
Epoch   4 Batch  173/269 - Train Accuracy:  0.810, Validation Accuracy:  0.805, Loss:  0.274
Epoch   4 Batch  174/269 - Train Accuracy:  0.809, Validation Accuracy:  0.808, Loss:  0.281
Epoch   4 Batch  175/269 - Train Accuracy:  0.811, Validation Accuracy:  0.807, Loss:  0.293
Epoch   4 Batch  176/269 - Train Accuracy:  0.801, Validation Accuracy:  0.807, Loss:  0.300
Epoch   4 Batch  177/269 - Train Accuracy:  0.808, Validation Accuracy:  0.809, Loss:  0.266
Epoch   4 Batch  178/269 - Train Accuracy:  0.815, Validation Accuracy:  0.809, Loss:  0.284
Epoch   4 Batch  179/269 - Train Accuracy:  0.794, Validation Accuracy:  0.811, Loss:  0.278
Epoch   4 Batch  180/269 - Train Accuracy:  0.826, Validation Accuracy:  0.814, Loss:  0.274
Epoch   4 Batch  181/269 - Train Accuracy:  0.811, Validation Accuracy:  0.817, Loss:  0.278
Epoch   4 Batch  182/269 - Train Accuracy:  0.817, Validation Accuracy:  0.818, Loss:  0.279
Epoch   4 Batch  183/269 - Train Accuracy:  0.834, Validation Accuracy:  0.814, Loss:  0.243
Epoch   4 Batch  184/269 - Train Accuracy:  0.800, Validation Accuracy:  0.814, Loss:  0.283
Epoch   4 Batch  185/269 - Train Accuracy:  0.818, Validation Accuracy:  0.809, Loss:  0.276
Epoch   4 Batch  186/269 - Train Accuracy:  0.797, Validation Accuracy:  0.806, Loss:  0.279
Epoch   4 Batch  187/269 - Train Accuracy:  0.813, Validation Accuracy:  0.813, Loss:  0.268
Epoch   4 Batch  188/269 - Train Accuracy:  0.816, Validation Accuracy:  0.813, Loss:  0.265
Epoch   4 Batch  189/269 - Train Accuracy:  0.817, Validation Accuracy:  0.814, Loss:  0.264
Epoch   4 Batch  190/269 - Train Accuracy:  0.821, Validation Accuracy:  0.816, Loss:  0.264
Epoch   4 Batch  191/269 - Train Accuracy:  0.797, Validation Accuracy:  0.821, Loss:  0.273
Epoch   4 Batch  192/269 - Train Accuracy:  0.818, Validation Accuracy:  0.813, Loss:  0.274
Epoch   4 Batch  193/269 - Train Accuracy:  0.835, Validation Accuracy:  0.816, Loss:  0.267
Epoch   4 Batch  194/269 - Train Accuracy:  0.823, Validation Accuracy:  0.814, Loss:  0.270
Epoch   4 Batch  195/269 - Train Accuracy:  0.820, Validation Accuracy:  0.814, Loss:  0.264
Epoch   4 Batch  196/269 - Train Accuracy:  0.816, Validation Accuracy:  0.814, Loss:  0.263
Epoch   4 Batch  197/269 - Train Accuracy:  0.799, Validation Accuracy:  0.819, Loss:  0.279
Epoch   4 Batch  198/269 - Train Accuracy:  0.807, Validation Accuracy:  0.821, Loss:  0.281
Epoch   4 Batch  199/269 - Train Accuracy:  0.802, Validation Accuracy:  0.815, Loss:  0.274
Epoch   4 Batch  200/269 - Train Accuracy:  0.807, Validation Accuracy:  0.814, Loss:  0.279
Epoch   4 Batch  201/269 - Train Accuracy:  0.818, Validation Accuracy:  0.821, Loss:  0.270
Epoch   4 Batch  202/269 - Train Accuracy:  0.799, Validation Accuracy:  0.815, Loss:  0.266
Epoch   4 Batch  203/269 - Train Accuracy:  0.799, Validation Accuracy:  0.816, Loss:  0.284
Epoch   4 Batch  204/269 - Train Accuracy:  0.819, Validation Accuracy:  0.813, Loss:  0.279
Epoch   4 Batch  205/269 - Train Accuracy:  0.823, Validation Accuracy:  0.817, Loss:  0.260
Epoch   4 Batch  206/269 - Train Accuracy:  0.800, Validation Accuracy:  0.815, Loss:  0.278
Epoch   4 Batch  207/269 - Train Accuracy:  0.813, Validation Accuracy:  0.817, Loss:  0.257
Epoch   4 Batch  208/269 - Train Accuracy:  0.829, Validation Accuracy:  0.817, Loss:  0.275
Epoch   4 Batch  209/269 - Train Accuracy:  0.820, Validation Accuracy:  0.813, Loss:  0.266
Epoch   4 Batch  210/269 - Train Accuracy:  0.820, Validation Accuracy:  0.810, Loss:  0.257
Epoch   4 Batch  211/269 - Train Accuracy:  0.827, Validation Accuracy:  0.821, Loss:  0.261
Epoch   4 Batch  212/269 - Train Accuracy:  0.814, Validation Accuracy:  0.817, Loss:  0.261
Epoch   4 Batch  213/269 - Train Accuracy:  0.818, Validation Accuracy:  0.817, Loss:  0.262
Epoch   4 Batch  214/269 - Train Accuracy:  0.810, Validation Accuracy:  0.821, Loss:  0.263
Epoch   4 Batch  215/269 - Train Accuracy:  0.830, Validation Accuracy:  0.812, Loss:  0.245
Epoch   4 Batch  216/269 - Train Accuracy:  0.799, Validation Accuracy:  0.813, Loss:  0.279
Epoch   4 Batch  217/269 - Train Accuracy:  0.809, Validation Accuracy:  0.811, Loss:  0.270
Epoch   4 Batch  218/269 - Train Accuracy:  0.823, Validation Accuracy:  0.822, Loss:  0.267
Epoch   4 Batch  219/269 - Train Accuracy:  0.835, Validation Accuracy:  0.824, Loss:  0.273
Epoch   4 Batch  220/269 - Train Accuracy:  0.824, Validation Accuracy:  0.821, Loss:  0.244
Epoch   4 Batch  221/269 - Train Accuracy:  0.828, Validation Accuracy:  0.813, Loss:  0.260
Epoch   4 Batch  222/269 - Train Accuracy:  0.856, Validation Accuracy:  0.829, Loss:  0.249
Epoch   4 Batch  223/269 - Train Accuracy:  0.816, Validation Accuracy:  0.832, Loss:  0.251
Epoch   4 Batch  224/269 - Train Accuracy:  0.838, Validation Accuracy:  0.825, Loss:  0.266
Epoch   4 Batch  225/269 - Train Accuracy:  0.804, Validation Accuracy:  0.813, Loss:  0.255
Epoch   4 Batch  226/269 - Train Accuracy:  0.838, Validation Accuracy:  0.818, Loss:  0.257
Epoch   4 Batch  227/269 - Train Accuracy:  0.844, Validation Accuracy:  0.822, Loss:  0.234
Epoch   4 Batch  228/269 - Train Accuracy:  0.818, Validation Accuracy:  0.829, Loss:  0.253
Epoch   4 Batch  229/269 - Train Accuracy:  0.812, Validation Accuracy:  0.818, Loss:  0.252
Epoch   4 Batch  230/269 - Train Accuracy:  0.818, Validation Accuracy:  0.827, Loss:  0.251
Epoch   4 Batch  231/269 - Train Accuracy:  0.806, Validation Accuracy:  0.820, Loss:  0.261
Epoch   4 Batch  232/269 - Train Accuracy:  0.812, Validation Accuracy:  0.813, Loss:  0.264
Epoch   4 Batch  233/269 - Train Accuracy:  0.826, Validation Accuracy:  0.816, Loss:  0.255
Epoch   4 Batch  234/269 - Train Accuracy:  0.829, Validation Accuracy:  0.818, Loss:  0.247
Epoch   4 Batch  235/269 - Train Accuracy:  0.837, Validation Accuracy:  0.820, Loss:  0.242
Epoch   4 Batch  236/269 - Train Accuracy:  0.824, Validation Accuracy:  0.823, Loss:  0.241
Epoch   4 Batch  237/269 - Train Accuracy:  0.824, Validation Accuracy:  0.820, Loss:  0.251
Epoch   4 Batch  238/269 - Train Accuracy:  0.831, Validation Accuracy:  0.824, Loss:  0.247
Epoch   4 Batch  239/269 - Train Accuracy:  0.831, Validation Accuracy:  0.827, Loss:  0.248
Epoch   4 Batch  240/269 - Train Accuracy:  0.843, Validation Accuracy:  0.830, Loss:  0.229
Epoch   4 Batch  241/269 - Train Accuracy:  0.829, Validation Accuracy:  0.825, Loss:  0.257
Epoch   4 Batch  242/269 - Train Accuracy:  0.816, Validation Accuracy:  0.828, Loss:  0.245
Epoch   4 Batch  243/269 - Train Accuracy:  0.837, Validation Accuracy:  0.833, Loss:  0.237
Epoch   4 Batch  244/269 - Train Accuracy:  0.830, Validation Accuracy:  0.828, Loss:  0.251
Epoch   4 Batch  245/269 - Train Accuracy:  0.811, Validation Accuracy:  0.826, Loss:  0.260
Epoch   4 Batch  246/269 - Train Accuracy:  0.815, Validation Accuracy:  0.819, Loss:  0.241
Epoch   4 Batch  247/269 - Train Accuracy:  0.813, Validation Accuracy:  0.825, Loss:  0.252
Epoch   4 Batch  248/269 - Train Accuracy:  0.833, Validation Accuracy:  0.826, Loss:  0.239
Epoch   4 Batch  249/269 - Train Accuracy:  0.843, Validation Accuracy:  0.825, Loss:  0.232
Epoch   4 Batch  250/269 - Train Accuracy:  0.832, Validation Accuracy:  0.819, Loss:  0.250
Epoch   4 Batch  251/269 - Train Accuracy:  0.844, Validation Accuracy:  0.826, Loss:  0.239
Epoch   4 Batch  252/269 - Train Accuracy:  0.829, Validation Accuracy:  0.834, Loss:  0.239
Epoch   4 Batch  253/269 - Train Accuracy:  0.813, Validation Accuracy:  0.832, Loss:  0.251
Epoch   4 Batch  254/269 - Train Accuracy:  0.838, Validation Accuracy:  0.835, Loss:  0.239
Epoch   4 Batch  255/269 - Train Accuracy:  0.838, Validation Accuracy:  0.834, Loss:  0.238
Epoch   4 Batch  256/269 - Train Accuracy:  0.829, Validation Accuracy:  0.827, Loss:  0.240
Epoch   4 Batch  257/269 - Train Accuracy:  0.810, Validation Accuracy:  0.824, Loss:  0.251
Epoch   4 Batch  258/269 - Train Accuracy:  0.851, Validation Accuracy:  0.824, Loss:  0.241
Epoch   4 Batch  259/269 - Train Accuracy:  0.831, Validation Accuracy:  0.824, Loss:  0.237
Epoch   4 Batch  260/269 - Train Accuracy:  0.825, Validation Accuracy:  0.827, Loss:  0.249
Epoch   4 Batch  261/269 - Train Accuracy:  0.822, Validation Accuracy:  0.831, Loss:  0.249
Epoch   4 Batch  262/269 - Train Accuracy:  0.845, Validation Accuracy:  0.829, Loss:  0.238
Epoch   4 Batch  263/269 - Train Accuracy:  0.852, Validation Accuracy:  0.831, Loss:  0.249
Epoch   4 Batch  264/269 - Train Accuracy:  0.815, Validation Accuracy:  0.830, Loss:  0.249
Epoch   4 Batch  265/269 - Train Accuracy:  0.828, Validation Accuracy:  0.831, Loss:  0.246
Epoch   4 Batch  266/269 - Train Accuracy:  0.851, Validation Accuracy:  0.831, Loss:  0.231
Epoch   4 Batch  267/269 - Train Accuracy:  0.838, Validation Accuracy:  0.829, Loss:  0.239
Epoch   5 Batch    0/269 - Train Accuracy:  0.831, Validation Accuracy:  0.835, Loss:  0.252
Epoch   5 Batch    1/269 - Train Accuracy:  0.826, Validation Accuracy:  0.833, Loss:  0.245
Epoch   5 Batch    2/269 - Train Accuracy:  0.831, Validation Accuracy:  0.828, Loss:  0.238
Epoch   5 Batch    3/269 - Train Accuracy:  0.828, Validation Accuracy:  0.839, Loss:  0.243
Epoch   5 Batch    4/269 - Train Accuracy:  0.816, Validation Accuracy:  0.833, Loss:  0.244
Epoch   5 Batch    5/269 - Train Accuracy:  0.822, Validation Accuracy:  0.838, Loss:  0.244
Epoch   5 Batch    6/269 - Train Accuracy:  0.833, Validation Accuracy:  0.832, Loss:  0.227
Epoch   5 Batch    7/269 - Train Accuracy:  0.836, Validation Accuracy:  0.833, Loss:  0.232
Epoch   5 Batch    8/269 - Train Accuracy:  0.831, Validation Accuracy:  0.827, Loss:  0.239
Epoch   5 Batch    9/269 - Train Accuracy:  0.833, Validation Accuracy:  0.837, Loss:  0.243
Epoch   5 Batch   10/269 - Train Accuracy:  0.851, Validation Accuracy:  0.841, Loss:  0.234
Epoch   5 Batch   11/269 - Train Accuracy:  0.839, Validation Accuracy:  0.844, Loss:  0.240
Epoch   5 Batch   12/269 - Train Accuracy:  0.830, Validation Accuracy:  0.835, Loss:  0.248
Epoch   5 Batch   13/269 - Train Accuracy:  0.839, Validation Accuracy:  0.834, Loss:  0.216
Epoch   5 Batch   14/269 - Train Accuracy:  0.834, Validation Accuracy:  0.836, Loss:  0.230
Epoch   5 Batch   15/269 - Train Accuracy:  0.842, Validation Accuracy:  0.837, Loss:  0.220
Epoch   5 Batch   16/269 - Train Accuracy:  0.826, Validation Accuracy:  0.837, Loss:  0.235
Epoch   5 Batch   17/269 - Train Accuracy:  0.842, Validation Accuracy:  0.844, Loss:  0.220
Epoch   5 Batch   18/269 - Train Accuracy:  0.837, Validation Accuracy:  0.840, Loss:  0.231
Epoch   5 Batch   19/269 - Train Accuracy:  0.855, Validation Accuracy:  0.838, Loss:  0.210
Epoch   5 Batch   20/269 - Train Accuracy:  0.844, Validation Accuracy:  0.836, Loss:  0.232
Epoch   5 Batch   21/269 - Train Accuracy:  0.824, Validation Accuracy:  0.841, Loss:  0.247
Epoch   5 Batch   22/269 - Train Accuracy:  0.865, Validation Accuracy:  0.842, Loss:  0.217
Epoch   5 Batch   23/269 - Train Accuracy:  0.839, Validation Accuracy:  0.845, Loss:  0.226
Epoch   5 Batch   24/269 - Train Accuracy:  0.844, Validation Accuracy:  0.838, Loss:  0.234
Epoch   5 Batch   25/269 - Train Accuracy:  0.849, Validation Accuracy:  0.838, Loss:  0.243
Epoch   5 Batch   26/269 - Train Accuracy:  0.852, Validation Accuracy:  0.850, Loss:  0.214
Epoch   5 Batch   27/269 - Train Accuracy:  0.848, Validation Accuracy:  0.851, Loss:  0.220
Epoch   5 Batch   28/269 - Train Accuracy:  0.811, Validation Accuracy:  0.842, Loss:  0.242
Epoch   5 Batch   29/269 - Train Accuracy:  0.854, Validation Accuracy:  0.849, Loss:  0.237
Epoch   5 Batch   30/269 - Train Accuracy:  0.848, Validation Accuracy:  0.845, Loss:  0.224
Epoch   5 Batch   31/269 - Train Accuracy:  0.863, Validation Accuracy:  0.836, Loss:  0.216
Epoch   5 Batch   32/269 - Train Accuracy:  0.842, Validation Accuracy:  0.836, Loss:  0.219
Epoch   5 Batch   33/269 - Train Accuracy:  0.853, Validation Accuracy:  0.841, Loss:  0.214
Epoch   5 Batch   34/269 - Train Accuracy:  0.857, Validation Accuracy:  0.843, Loss:  0.220
Epoch   5 Batch   35/269 - Train Accuracy:  0.844, Validation Accuracy:  0.845, Loss:  0.230
Epoch   5 Batch   36/269 - Train Accuracy:  0.824, Validation Accuracy:  0.843, Loss:  0.223
Epoch   5 Batch   37/269 - Train Accuracy:  0.839, Validation Accuracy:  0.844, Loss:  0.220
Epoch   5 Batch   38/269 - Train Accuracy:  0.847, Validation Accuracy:  0.840, Loss:  0.221
Epoch   5 Batch   39/269 - Train Accuracy:  0.853, Validation Accuracy:  0.846, Loss:  0.222
Epoch   5 Batch   40/269 - Train Accuracy:  0.828, Validation Accuracy:  0.852, Loss:  0.229
Epoch   5 Batch   41/269 - Train Accuracy:  0.834, Validation Accuracy:  0.845, Loss:  0.222
Epoch   5 Batch   42/269 - Train Accuracy:  0.863, Validation Accuracy:  0.853, Loss:  0.204
Epoch   5 Batch   43/269 - Train Accuracy:  0.852, Validation Accuracy:  0.854, Loss:  0.223
Epoch   5 Batch   44/269 - Train Accuracy:  0.850, Validation Accuracy:  0.846, Loss:  0.218
Epoch   5 Batch   45/269 - Train Accuracy:  0.841, Validation Accuracy:  0.849, Loss:  0.227
Epoch   5 Batch   46/269 - Train Accuracy:  0.846, Validation Accuracy:  0.848, Loss:  0.222
Epoch   5 Batch   47/269 - Train Accuracy:  0.863, Validation Accuracy:  0.845, Loss:  0.201
Epoch   5 Batch   48/269 - Train Accuracy:  0.862, Validation Accuracy:  0.844, Loss:  0.213
Epoch   5 Batch   49/269 - Train Accuracy:  0.836, Validation Accuracy:  0.846, Loss:  0.216
Epoch   5 Batch   50/269 - Train Accuracy:  0.838, Validation Accuracy:  0.851, Loss:  0.227
Epoch   5 Batch   51/269 - Train Accuracy:  0.865, Validation Accuracy:  0.853, Loss:  0.212
Epoch   5 Batch   52/269 - Train Accuracy:  0.850, Validation Accuracy:  0.849, Loss:  0.202
Epoch   5 Batch   53/269 - Train Accuracy:  0.860, Validation Accuracy:  0.850, Loss:  0.228
Epoch   5 Batch   54/269 - Train Accuracy:  0.844, Validation Accuracy:  0.848, Loss:  0.218
Epoch   5 Batch   55/269 - Train Accuracy:  0.862, Validation Accuracy:  0.847, Loss:  0.210
Epoch   5 Batch   56/269 - Train Accuracy:  0.843, Validation Accuracy:  0.844, Loss:  0.214
Epoch   5 Batch   57/269 - Train Accuracy:  0.847, Validation Accuracy:  0.841, Loss:  0.223
Epoch   5 Batch   58/269 - Train Accuracy:  0.859, Validation Accuracy:  0.844, Loss:  0.208
Epoch   5 Batch   59/269 - Train Accuracy:  0.875, Validation Accuracy:  0.852, Loss:  0.193
Epoch   5 Batch   60/269 - Train Accuracy:  0.850, Validation Accuracy:  0.851, Loss:  0.203
Epoch   5 Batch   61/269 - Train Accuracy:  0.873, Validation Accuracy:  0.852, Loss:  0.195
Epoch   5 Batch   62/269 - Train Accuracy:  0.859, Validation Accuracy:  0.851, Loss:  0.208
Epoch   5 Batch   63/269 - Train Accuracy:  0.856, Validation Accuracy:  0.853, Loss:  0.217
Epoch   5 Batch   64/269 - Train Accuracy:  0.853, Validation Accuracy:  0.850, Loss:  0.202
Epoch   5 Batch   65/269 - Train Accuracy:  0.848, Validation Accuracy:  0.850, Loss:  0.208
Epoch   5 Batch   66/269 - Train Accuracy:  0.858, Validation Accuracy:  0.851, Loss:  0.206
Epoch   5 Batch   67/269 - Train Accuracy:  0.853, Validation Accuracy:  0.853, Loss:  0.216
Epoch   5 Batch   68/269 - Train Accuracy:  0.843, Validation Accuracy:  0.848, Loss:  0.217
Epoch   5 Batch   69/269 - Train Accuracy:  0.837, Validation Accuracy:  0.853, Loss:  0.231
Epoch   5 Batch   70/269 - Train Accuracy:  0.864, Validation Accuracy:  0.855, Loss:  0.206
Epoch   5 Batch   71/269 - Train Accuracy:  0.854, Validation Accuracy:  0.852, Loss:  0.222
Epoch   5 Batch   72/269 - Train Accuracy:  0.855, Validation Accuracy:  0.849, Loss:  0.209
Epoch   5 Batch   73/269 - Train Accuracy:  0.851, Validation Accuracy:  0.851, Loss:  0.214
Epoch   5 Batch   74/269 - Train Accuracy:  0.864, Validation Accuracy:  0.856, Loss:  0.207
Epoch   5 Batch   75/269 - Train Accuracy:  0.864, Validation Accuracy:  0.861, Loss:  0.205
Epoch   5 Batch   76/269 - Train Accuracy:  0.839, Validation Accuracy:  0.859, Loss:  0.206
Epoch   5 Batch   77/269 - Train Accuracy:  0.851, Validation Accuracy:  0.854, Loss:  0.204
Epoch   5 Batch   78/269 - Train Accuracy:  0.863, Validation Accuracy:  0.843, Loss:  0.204
Epoch   5 Batch   79/269 - Train Accuracy:  0.838, Validation Accuracy:  0.847, Loss:  0.205
Epoch   5 Batch   80/269 - Train Accuracy:  0.855, Validation Accuracy:  0.849, Loss:  0.201
Epoch   5 Batch   81/269 - Train Accuracy:  0.849, Validation Accuracy:  0.851, Loss:  0.216
Epoch   5 Batch   82/269 - Train Accuracy:  0.860, Validation Accuracy:  0.850, Loss:  0.198
Epoch   5 Batch   83/269 - Train Accuracy:  0.859, Validation Accuracy:  0.853, Loss:  0.211
Epoch   5 Batch   84/269 - Train Accuracy:  0.863, Validation Accuracy:  0.853, Loss:  0.201
Epoch   5 Batch   85/269 - Train Accuracy:  0.851, Validation Accuracy:  0.852, Loss:  0.203
Epoch   5 Batch   86/269 - Train Accuracy:  0.857, Validation Accuracy:  0.846, Loss:  0.195
Epoch   5 Batch   87/269 - Train Accuracy:  0.848, Validation Accuracy:  0.850, Loss:  0.219
Epoch   5 Batch   88/269 - Train Accuracy:  0.843, Validation Accuracy:  0.857, Loss:  0.206
Epoch   5 Batch   89/269 - Train Accuracy:  0.867, Validation Accuracy:  0.858, Loss:  0.198
Epoch   5 Batch   90/269 - Train Accuracy:  0.849, Validation Accuracy:  0.860, Loss:  0.211
Epoch   5 Batch   91/269 - Train Accuracy:  0.872, Validation Accuracy:  0.859, Loss:  0.193
Epoch   5 Batch   92/269 - Train Accuracy:  0.880, Validation Accuracy:  0.858, Loss:  0.193
Epoch   5 Batch   93/269 - Train Accuracy:  0.871, Validation Accuracy:  0.861, Loss:  0.190
Epoch   5 Batch   94/269 - Train Accuracy:  0.864, Validation Accuracy:  0.864, Loss:  0.205
Epoch   5 Batch   95/269 - Train Accuracy:  0.855, Validation Accuracy:  0.860, Loss:  0.193
Epoch   5 Batch   96/269 - Train Accuracy:  0.857, Validation Accuracy:  0.861, Loss:  0.199
Epoch   5 Batch   97/269 - Train Accuracy:  0.864, Validation Accuracy:  0.861, Loss:  0.197
Epoch   5 Batch   98/269 - Train Accuracy:  0.873, Validation Accuracy:  0.863, Loss:  0.195
Epoch   5 Batch   99/269 - Train Accuracy:  0.860, Validation Accuracy:  0.865, Loss:  0.201
Epoch   5 Batch  100/269 - Train Accuracy:  0.876, Validation Accuracy:  0.865, Loss:  0.194
Epoch   5 Batch  101/269 - Train Accuracy:  0.860, Validation Accuracy:  0.867, Loss:  0.212
Epoch   5 Batch  102/269 - Train Accuracy:  0.866, Validation Accuracy:  0.865, Loss:  0.194
Epoch   5 Batch  103/269 - Train Accuracy:  0.884, Validation Accuracy:  0.863, Loss:  0.199
Epoch   5 Batch  104/269 - Train Accuracy:  0.857, Validation Accuracy:  0.858, Loss:  0.193
Epoch   5 Batch  105/269 - Train Accuracy:  0.864, Validation Accuracy:  0.866, Loss:  0.196
Epoch   5 Batch  106/269 - Train Accuracy:  0.870, Validation Accuracy:  0.872, Loss:  0.186
Epoch   5 Batch  107/269 - Train Accuracy:  0.866, Validation Accuracy:  0.871, Loss:  0.201
Epoch   5 Batch  108/269 - Train Accuracy:  0.865, Validation Accuracy:  0.865, Loss:  0.196
Epoch   5 Batch  109/269 - Train Accuracy:  0.848, Validation Accuracy:  0.863, Loss:  0.198
Epoch   5 Batch  110/269 - Train Accuracy:  0.856, Validation Accuracy:  0.870, Loss:  0.190
Epoch   5 Batch  111/269 - Train Accuracy:  0.856, Validation Accuracy:  0.870, Loss:  0.204
Epoch   5 Batch  112/269 - Train Accuracy:  0.862, Validation Accuracy:  0.867, Loss:  0.191
Epoch   5 Batch  113/269 - Train Accuracy:  0.858, Validation Accuracy:  0.864, Loss:  0.187
Epoch   5 Batch  114/269 - Train Accuracy:  0.872, Validation Accuracy:  0.864, Loss:  0.193
Epoch   5 Batch  115/269 - Train Accuracy:  0.871, Validation Accuracy:  0.862, Loss:  0.194
Epoch   5 Batch  116/269 - Train Accuracy:  0.876, Validation Accuracy:  0.863, Loss:  0.197
Epoch   5 Batch  117/269 - Train Accuracy:  0.876, Validation Accuracy:  0.872, Loss:  0.188
Epoch   5 Batch  118/269 - Train Accuracy:  0.878, Validation Accuracy:  0.868, Loss:  0.182
Epoch   5 Batch  119/269 - Train Accuracy:  0.858, Validation Accuracy:  0.863, Loss:  0.202
Epoch   5 Batch  120/269 - Train Accuracy:  0.860, Validation Accuracy:  0.860, Loss:  0.191
Epoch   5 Batch  121/269 - Train Accuracy:  0.867, Validation Accuracy:  0.863, Loss:  0.186
Epoch   5 Batch  122/269 - Train Accuracy:  0.871, Validation Accuracy:  0.865, Loss:  0.183
Epoch   5 Batch  123/269 - Train Accuracy:  0.867, Validation Accuracy:  0.868, Loss:  0.190
Epoch   5 Batch  124/269 - Train Accuracy:  0.866, Validation Accuracy:  0.865, Loss:  0.181
Epoch   5 Batch  125/269 - Train Accuracy:  0.873, Validation Accuracy:  0.866, Loss:  0.180
Epoch   5 Batch  126/269 - Train Accuracy:  0.860, Validation Accuracy:  0.862, Loss:  0.186
Epoch   5 Batch  127/269 - Train Accuracy:  0.864, Validation Accuracy:  0.867, Loss:  0.188
Epoch   5 Batch  128/269 - Train Accuracy:  0.869, Validation Accuracy:  0.864, Loss:  0.185
Epoch   5 Batch  129/269 - Train Accuracy:  0.869, Validation Accuracy:  0.862, Loss:  0.185
Epoch   5 Batch  130/269 - Train Accuracy:  0.872, Validation Accuracy:  0.864, Loss:  0.193
Epoch   5 Batch  131/269 - Train Accuracy:  0.863, Validation Accuracy:  0.864, Loss:  0.189
Epoch   5 Batch  132/269 - Train Accuracy:  0.859, Validation Accuracy:  0.863, Loss:  0.191
Epoch   5 Batch  133/269 - Train Accuracy:  0.887, Validation Accuracy:  0.862, Loss:  0.176
Epoch   5 Batch  134/269 - Train Accuracy:  0.866, Validation Accuracy:  0.858, Loss:  0.185
Epoch   5 Batch  135/269 - Train Accuracy:  0.871, Validation Accuracy:  0.867, Loss:  0.196
Epoch   5 Batch  136/269 - Train Accuracy:  0.853, Validation Accuracy:  0.874, Loss:  0.194
Epoch   5 Batch  137/269 - Train Accuracy:  0.849, Validation Accuracy:  0.870, Loss:  0.197
Epoch   5 Batch  138/269 - Train Accuracy:  0.875, Validation Accuracy:  0.871, Loss:  0.183
Epoch   5 Batch  139/269 - Train Accuracy:  0.874, Validation Accuracy:  0.872, Loss:  0.172
Epoch   5 Batch  140/269 - Train Accuracy:  0.869, Validation Accuracy:  0.869, Loss:  0.188
Epoch   5 Batch  141/269 - Train Accuracy:  0.869, Validation Accuracy:  0.868, Loss:  0.188
Epoch   5 Batch  142/269 - Train Accuracy:  0.873, Validation Accuracy:  0.872, Loss:  0.175
Epoch   5 Batch  143/269 - Train Accuracy:  0.873, Validation Accuracy:  0.870, Loss:  0.178
Epoch   5 Batch  144/269 - Train Accuracy:  0.900, Validation Accuracy:  0.870, Loss:  0.165
Epoch   5 Batch  145/269 - Train Accuracy:  0.873, Validation Accuracy:  0.872, Loss:  0.175
Epoch   5 Batch  146/269 - Train Accuracy:  0.860, Validation Accuracy:  0.869, Loss:  0.179
Epoch   5 Batch  147/269 - Train Accuracy:  0.879, Validation Accuracy:  0.869, Loss:  0.173
Epoch   5 Batch  148/269 - Train Accuracy:  0.862, Validation Accuracy:  0.872, Loss:  0.184
Epoch   5 Batch  149/269 - Train Accuracy:  0.852, Validation Accuracy:  0.871, Loss:  0.187
Epoch   5 Batch  150/269 - Train Accuracy:  0.871, Validation Accuracy:  0.869, Loss:  0.174
Epoch   5 Batch  151/269 - Train Accuracy:  0.872, Validation Accuracy:  0.869, Loss:  0.172
Epoch   5 Batch  152/269 - Train Accuracy:  0.876, Validation Accuracy:  0.875, Loss:  0.178
Epoch   5 Batch  153/269 - Train Accuracy:  0.881, Validation Accuracy:  0.878, Loss:  0.178
Epoch   5 Batch  154/269 - Train Accuracy:  0.891, Validation Accuracy:  0.879, Loss:  0.182
Epoch   5 Batch  155/269 - Train Accuracy:  0.870, Validation Accuracy:  0.877, Loss:  0.172
Epoch   5 Batch  156/269 - Train Accuracy:  0.865, Validation Accuracy:  0.875, Loss:  0.182
Epoch   5 Batch  157/269 - Train Accuracy:  0.878, Validation Accuracy:  0.869, Loss:  0.171
Epoch   5 Batch  158/269 - Train Accuracy:  0.870, Validation Accuracy:  0.872, Loss:  0.176
Epoch   5 Batch  159/269 - Train Accuracy:  0.872, Validation Accuracy:  0.877, Loss:  0.180
Epoch   5 Batch  160/269 - Train Accuracy:  0.883, Validation Accuracy:  0.868, Loss:  0.179
Epoch   5 Batch  161/269 - Train Accuracy:  0.873, Validation Accuracy:  0.870, Loss:  0.175
Epoch   5 Batch  162/269 - Train Accuracy:  0.894, Validation Accuracy:  0.873, Loss:  0.176
Epoch   5 Batch  163/269 - Train Accuracy:  0.882, Validation Accuracy:  0.875, Loss:  0.173
Epoch   5 Batch  164/269 - Train Accuracy:  0.878, Validation Accuracy:  0.870, Loss:  0.172
Epoch   5 Batch  165/269 - Train Accuracy:  0.881, Validation Accuracy:  0.873, Loss:  0.176
Epoch   5 Batch  166/269 - Train Accuracy:  0.877, Validation Accuracy:  0.878, Loss:  0.169
Epoch   5 Batch  167/269 - Train Accuracy:  0.884, Validation Accuracy:  0.877, Loss:  0.168
Epoch   5 Batch  168/269 - Train Accuracy:  0.881, Validation Accuracy:  0.878, Loss:  0.177
Epoch   5 Batch  169/269 - Train Accuracy:  0.874, Validation Accuracy:  0.876, Loss:  0.169
Epoch   5 Batch  170/269 - Train Accuracy:  0.874, Validation Accuracy:  0.876, Loss:  0.169
Epoch   5 Batch  171/269 - Train Accuracy:  0.884, Validation Accuracy:  0.882, Loss:  0.175
Epoch   5 Batch  172/269 - Train Accuracy:  0.870, Validation Accuracy:  0.873, Loss:  0.181
Epoch   5 Batch  173/269 - Train Accuracy:  0.886, Validation Accuracy:  0.868, Loss:  0.163
Epoch   5 Batch  174/269 - Train Accuracy:  0.884, Validation Accuracy:  0.867, Loss:  0.169
Epoch   5 Batch  175/269 - Train Accuracy:  0.870, Validation Accuracy:  0.866, Loss:  0.185
Epoch   5 Batch  176/269 - Train Accuracy:  0.869, Validation Accuracy:  0.866, Loss:  0.181
Epoch   5 Batch  177/269 - Train Accuracy:  0.880, Validation Accuracy:  0.870, Loss:  0.163
Epoch   5 Batch  178/269 - Train Accuracy:  0.896, Validation Accuracy:  0.875, Loss:  0.167
Epoch   5 Batch  179/269 - Train Accuracy:  0.869, Validation Accuracy:  0.883, Loss:  0.169
Epoch   5 Batch  180/269 - Train Accuracy:  0.900, Validation Accuracy:  0.883, Loss:  0.164
Epoch   5 Batch  181/269 - Train Accuracy:  0.878, Validation Accuracy:  0.888, Loss:  0.170
Epoch   5 Batch  182/269 - Train Accuracy:  0.877, Validation Accuracy:  0.890, Loss:  0.169
Epoch   5 Batch  183/269 - Train Accuracy:  0.905, Validation Accuracy:  0.883, Loss:  0.149
Epoch   5 Batch  184/269 - Train Accuracy:  0.877, Validation Accuracy:  0.880, Loss:  0.167
Epoch   5 Batch  185/269 - Train Accuracy:  0.880, Validation Accuracy:  0.877, Loss:  0.164
Epoch   5 Batch  186/269 - Train Accuracy:  0.875, Validation Accuracy:  0.876, Loss:  0.168
Epoch   5 Batch  187/269 - Train Accuracy:  0.875, Validation Accuracy:  0.882, Loss:  0.162
Epoch   5 Batch  188/269 - Train Accuracy:  0.884, Validation Accuracy:  0.882, Loss:  0.159
Epoch   5 Batch  189/269 - Train Accuracy:  0.890, Validation Accuracy:  0.880, Loss:  0.156
Epoch   5 Batch  190/269 - Train Accuracy:  0.890, Validation Accuracy:  0.876, Loss:  0.159
Epoch   5 Batch  191/269 - Train Accuracy:  0.858, Validation Accuracy:  0.881, Loss:  0.166
Epoch   5 Batch  192/269 - Train Accuracy:  0.881, Validation Accuracy:  0.882, Loss:  0.169
Epoch   5 Batch  193/269 - Train Accuracy:  0.886, Validation Accuracy:  0.881, Loss:  0.163
Epoch   5 Batch  194/269 - Train Accuracy:  0.884, Validation Accuracy:  0.879, Loss:  0.164
Epoch   5 Batch  195/269 - Train Accuracy:  0.877, Validation Accuracy:  0.883, Loss:  0.160
Epoch   5 Batch  196/269 - Train Accuracy:  0.872, Validation Accuracy:  0.888, Loss:  0.158
Epoch   5 Batch  197/269 - Train Accuracy:  0.873, Validation Accuracy:  0.888, Loss:  0.168
Epoch   5 Batch  198/269 - Train Accuracy:  0.881, Validation Accuracy:  0.893, Loss:  0.169
Epoch   5 Batch  199/269 - Train Accuracy:  0.875, Validation Accuracy:  0.887, Loss:  0.169
Epoch   5 Batch  200/269 - Train Accuracy:  0.879, Validation Accuracy:  0.891, Loss:  0.166
Epoch   5 Batch  201/269 - Train Accuracy:  0.881, Validation Accuracy:  0.887, Loss:  0.164
Epoch   5 Batch  202/269 - Train Accuracy:  0.879, Validation Accuracy:  0.887, Loss:  0.160
Epoch   5 Batch  203/269 - Train Accuracy:  0.886, Validation Accuracy:  0.880, Loss:  0.174
Epoch   5 Batch  204/269 - Train Accuracy:  0.891, Validation Accuracy:  0.880, Loss:  0.168
Epoch   5 Batch  205/269 - Train Accuracy:  0.882, Validation Accuracy:  0.884, Loss:  0.155
Epoch   5 Batch  206/269 - Train Accuracy:  0.880, Validation Accuracy:  0.885, Loss:  0.169
Epoch   5 Batch  207/269 - Train Accuracy:  0.885, Validation Accuracy:  0.885, Loss:  0.156
Epoch   5 Batch  208/269 - Train Accuracy:  0.885, Validation Accuracy:  0.878, Loss:  0.167
Epoch   5 Batch  209/269 - Train Accuracy:  0.890, Validation Accuracy:  0.884, Loss:  0.158
Epoch   5 Batch  210/269 - Train Accuracy:  0.889, Validation Accuracy:  0.886, Loss:  0.151
Epoch   5 Batch  211/269 - Train Accuracy:  0.895, Validation Accuracy:  0.886, Loss:  0.159
Epoch   5 Batch  212/269 - Train Accuracy:  0.887, Validation Accuracy:  0.886, Loss:  0.162
Epoch   5 Batch  213/269 - Train Accuracy:  0.878, Validation Accuracy:  0.886, Loss:  0.157
Epoch   5 Batch  214/269 - Train Accuracy:  0.871, Validation Accuracy:  0.887, Loss:  0.160
Epoch   5 Batch  215/269 - Train Accuracy:  0.892, Validation Accuracy:  0.880, Loss:  0.148
Epoch   5 Batch  216/269 - Train Accuracy:  0.877, Validation Accuracy:  0.881, Loss:  0.169
Epoch   5 Batch  217/269 - Train Accuracy:  0.880, Validation Accuracy:  0.881, Loss:  0.161
Epoch   5 Batch  218/269 - Train Accuracy:  0.886, Validation Accuracy:  0.885, Loss:  0.159
Epoch   5 Batch  219/269 - Train Accuracy:  0.898, Validation Accuracy:  0.891, Loss:  0.164
Epoch   5 Batch  220/269 - Train Accuracy:  0.883, Validation Accuracy:  0.892, Loss:  0.147
Epoch   5 Batch  221/269 - Train Accuracy:  0.888, Validation Accuracy:  0.896, Loss:  0.159
Epoch   5 Batch  222/269 - Train Accuracy:  0.909, Validation Accuracy:  0.894, Loss:  0.147
Epoch   5 Batch  223/269 - Train Accuracy:  0.897, Validation Accuracy:  0.892, Loss:  0.150
Epoch   5 Batch  224/269 - Train Accuracy:  0.889, Validation Accuracy:  0.891, Loss:  0.164
Epoch   5 Batch  225/269 - Train Accuracy:  0.876, Validation Accuracy:  0.886, Loss:  0.150
Epoch   5 Batch  226/269 - Train Accuracy:  0.896, Validation Accuracy:  0.885, Loss:  0.157
Epoch   5 Batch  227/269 - Train Accuracy:  0.909, Validation Accuracy:  0.885, Loss:  0.146
Epoch   5 Batch  228/269 - Train Accuracy:  0.886, Validation Accuracy:  0.889, Loss:  0.152
Epoch   5 Batch  229/269 - Train Accuracy:  0.881, Validation Accuracy:  0.889, Loss:  0.152
Epoch   5 Batch  230/269 - Train Accuracy:  0.901, Validation Accuracy:  0.892, Loss:  0.150
Epoch   5 Batch  231/269 - Train Accuracy:  0.880, Validation Accuracy:  0.890, Loss:  0.157
Epoch   5 Batch  232/269 - Train Accuracy:  0.878, Validation Accuracy:  0.885, Loss:  0.156
Epoch   5 Batch  233/269 - Train Accuracy:  0.894, Validation Accuracy:  0.888, Loss:  0.155
Epoch   5 Batch  234/269 - Train Accuracy:  0.886, Validation Accuracy:  0.888, Loss:  0.147
Epoch   5 Batch  235/269 - Train Accuracy:  0.905, Validation Accuracy:  0.896, Loss:  0.143
Epoch   5 Batch  236/269 - Train Accuracy:  0.885, Validation Accuracy:  0.891, Loss:  0.141
Epoch   5 Batch  237/269 - Train Accuracy:  0.892, Validation Accuracy:  0.883, Loss:  0.150
Epoch   5 Batch  238/269 - Train Accuracy:  0.890, Validation Accuracy:  0.885, Loss:  0.149
Epoch   5 Batch  239/269 - Train Accuracy:  0.895, Validation Accuracy:  0.886, Loss:  0.150
Epoch   5 Batch  240/269 - Train Accuracy:  0.903, Validation Accuracy:  0.883, Loss:  0.140
Epoch   5 Batch  241/269 - Train Accuracy:  0.889, Validation Accuracy:  0.887, Loss:  0.158
Epoch   5 Batch  242/269 - Train Accuracy:  0.896, Validation Accuracy:  0.892, Loss:  0.148
Epoch   5 Batch  243/269 - Train Accuracy:  0.892, Validation Accuracy:  0.895, Loss:  0.139
Epoch   5 Batch  244/269 - Train Accuracy:  0.890, Validation Accuracy:  0.891, Loss:  0.153
Epoch   5 Batch  245/269 - Train Accuracy:  0.880, Validation Accuracy:  0.894, Loss:  0.156
Epoch   5 Batch  246/269 - Train Accuracy:  0.883, Validation Accuracy:  0.890, Loss:  0.146
Epoch   5 Batch  247/269 - Train Accuracy:  0.882, Validation Accuracy:  0.891, Loss:  0.149
Epoch   5 Batch  248/269 - Train Accuracy:  0.902, Validation Accuracy:  0.884, Loss:  0.143
Epoch   5 Batch  249/269 - Train Accuracy:  0.902, Validation Accuracy:  0.883, Loss:  0.138
Epoch   5 Batch  250/269 - Train Accuracy:  0.897, Validation Accuracy:  0.894, Loss:  0.149
Epoch   5 Batch  251/269 - Train Accuracy:  0.905, Validation Accuracy:  0.899, Loss:  0.143
Epoch   5 Batch  252/269 - Train Accuracy:  0.902, Validation Accuracy:  0.903, Loss:  0.139
Epoch   5 Batch  253/269 - Train Accuracy:  0.878, Validation Accuracy:  0.903, Loss:  0.152
Epoch   5 Batch  254/269 - Train Accuracy:  0.893, Validation Accuracy:  0.904, Loss:  0.144
Epoch   5 Batch  255/269 - Train Accuracy:  0.896, Validation Accuracy:  0.902, Loss:  0.141
Epoch   5 Batch  256/269 - Train Accuracy:  0.884, Validation Accuracy:  0.898, Loss:  0.142
Epoch   5 Batch  257/269 - Train Accuracy:  0.870, Validation Accuracy:  0.895, Loss:  0.152
Epoch   5 Batch  258/269 - Train Accuracy:  0.892, Validation Accuracy:  0.892, Loss:  0.146
Epoch   5 Batch  259/269 - Train Accuracy:  0.886, Validation Accuracy:  0.891, Loss:  0.141
Epoch   5 Batch  260/269 - Train Accuracy:  0.887, Validation Accuracy:  0.892, Loss:  0.148
Epoch   5 Batch  261/269 - Train Accuracy:  0.889, Validation Accuracy:  0.888, Loss:  0.145
Epoch   5 Batch  262/269 - Train Accuracy:  0.899, Validation Accuracy:  0.904, Loss:  0.141
Epoch   5 Batch  263/269 - Train Accuracy:  0.906, Validation Accuracy:  0.906, Loss:  0.146
Epoch   5 Batch  264/269 - Train Accuracy:  0.870, Validation Accuracy:  0.907, Loss:  0.151
Epoch   5 Batch  265/269 - Train Accuracy:  0.885, Validation Accuracy:  0.906, Loss:  0.145
Epoch   5 Batch  266/269 - Train Accuracy:  0.901, Validation Accuracy:  0.903, Loss:  0.136
Epoch   5 Batch  267/269 - Train Accuracy:  0.907, Validation Accuracy:  0.900, Loss:  0.145
Epoch   6 Batch    0/269 - Train Accuracy:  0.905, Validation Accuracy:  0.899, Loss:  0.151
Epoch   6 Batch    1/269 - Train Accuracy:  0.881, Validation Accuracy:  0.899, Loss:  0.144
Epoch   6 Batch    2/269 - Train Accuracy:  0.891, Validation Accuracy:  0.899, Loss:  0.146
Epoch   6 Batch    3/269 - Train Accuracy:  0.891, Validation Accuracy:  0.900, Loss:  0.144
Epoch   6 Batch    4/269 - Train Accuracy:  0.882, Validation Accuracy:  0.904, Loss:  0.144
Epoch   6 Batch    5/269 - Train Accuracy:  0.905, Validation Accuracy:  0.902, Loss:  0.141
Epoch   6 Batch    6/269 - Train Accuracy:  0.913, Validation Accuracy:  0.899, Loss:  0.134
Epoch   6 Batch    7/269 - Train Accuracy:  0.900, Validation Accuracy:  0.899, Loss:  0.135
Epoch   6 Batch    8/269 - Train Accuracy:  0.906, Validation Accuracy:  0.901, Loss:  0.143
Epoch   6 Batch    9/269 - Train Accuracy:  0.889, Validation Accuracy:  0.900, Loss:  0.145
Epoch   6 Batch   10/269 - Train Accuracy:  0.905, Validation Accuracy:  0.894, Loss:  0.135
Epoch   6 Batch   11/269 - Train Accuracy:  0.895, Validation Accuracy:  0.898, Loss:  0.145
Epoch   6 Batch   12/269 - Train Accuracy:  0.889, Validation Accuracy:  0.898, Loss:  0.150
Epoch   6 Batch   13/269 - Train Accuracy:  0.909, Validation Accuracy:  0.902, Loss:  0.124
Epoch   6 Batch   14/269 - Train Accuracy:  0.898, Validation Accuracy:  0.902, Loss:  0.137
Epoch   6 Batch   15/269 - Train Accuracy:  0.900, Validation Accuracy:  0.904, Loss:  0.125
Epoch   6 Batch   16/269 - Train Accuracy:  0.899, Validation Accuracy:  0.902, Loss:  0.143
Epoch   6 Batch   17/269 - Train Accuracy:  0.910, Validation Accuracy:  0.898, Loss:  0.126
Epoch   6 Batch   18/269 - Train Accuracy:  0.891, Validation Accuracy:  0.902, Loss:  0.137
Epoch   6 Batch   19/269 - Train Accuracy:  0.913, Validation Accuracy:  0.910, Loss:  0.120
Epoch   6 Batch   20/269 - Train Accuracy:  0.914, Validation Accuracy:  0.904, Loss:  0.135
Epoch   6 Batch   21/269 - Train Accuracy:  0.885, Validation Accuracy:  0.903, Loss:  0.151
Epoch   6 Batch   22/269 - Train Accuracy:  0.910, Validation Accuracy:  0.908, Loss:  0.129
Epoch   6 Batch   23/269 - Train Accuracy:  0.896, Validation Accuracy:  0.907, Loss:  0.138
Epoch   6 Batch   24/269 - Train Accuracy:  0.901, Validation Accuracy:  0.900, Loss:  0.136
Epoch   6 Batch   25/269 - Train Accuracy:  0.885, Validation Accuracy:  0.901, Loss:  0.145
Epoch   6 Batch   26/269 - Train Accuracy:  0.907, Validation Accuracy:  0.904, Loss:  0.125
Epoch   6 Batch   27/269 - Train Accuracy:  0.894, Validation Accuracy:  0.910, Loss:  0.129
Epoch   6 Batch   28/269 - Train Accuracy:  0.883, Validation Accuracy:  0.905, Loss:  0.141
Epoch   6 Batch   29/269 - Train Accuracy:  0.903, Validation Accuracy:  0.905, Loss:  0.140
Epoch   6 Batch   30/269 - Train Accuracy:  0.905, Validation Accuracy:  0.904, Loss:  0.129
Epoch   6 Batch   31/269 - Train Accuracy:  0.914, Validation Accuracy:  0.888, Loss:  0.124
Epoch   6 Batch   32/269 - Train Accuracy:  0.896, Validation Accuracy:  0.895, Loss:  0.129
Epoch   6 Batch   33/269 - Train Accuracy:  0.909, Validation Accuracy:  0.901, Loss:  0.123
Epoch   6 Batch   34/269 - Train Accuracy:  0.906, Validation Accuracy:  0.903, Loss:  0.129
Epoch   6 Batch   35/269 - Train Accuracy:  0.903, Validation Accuracy:  0.901, Loss:  0.140
Epoch   6 Batch   36/269 - Train Accuracy:  0.882, Validation Accuracy:  0.899, Loss:  0.133
Epoch   6 Batch   37/269 - Train Accuracy:  0.896, Validation Accuracy:  0.907, Loss:  0.131
Epoch   6 Batch   38/269 - Train Accuracy:  0.897, Validation Accuracy:  0.904, Loss:  0.130
Epoch   6 Batch   39/269 - Train Accuracy:  0.901, Validation Accuracy:  0.907, Loss:  0.129
Epoch   6 Batch   40/269 - Train Accuracy:  0.891, Validation Accuracy:  0.910, Loss:  0.136
Epoch   6 Batch   41/269 - Train Accuracy:  0.896, Validation Accuracy:  0.911, Loss:  0.133
Epoch   6 Batch   42/269 - Train Accuracy:  0.913, Validation Accuracy:  0.906, Loss:  0.118
Epoch   6 Batch   43/269 - Train Accuracy:  0.895, Validation Accuracy:  0.913, Loss:  0.131
Epoch   6 Batch   44/269 - Train Accuracy:  0.907, Validation Accuracy:  0.912, Loss:  0.130
Epoch   6 Batch   45/269 - Train Accuracy:  0.904, Validation Accuracy:  0.911, Loss:  0.132
Epoch   6 Batch   46/269 - Train Accuracy:  0.897, Validation Accuracy:  0.912, Loss:  0.131
Epoch   6 Batch   47/269 - Train Accuracy:  0.923, Validation Accuracy:  0.915, Loss:  0.116
Epoch   6 Batch   48/269 - Train Accuracy:  0.920, Validation Accuracy:  0.907, Loss:  0.123
Epoch   6 Batch   49/269 - Train Accuracy:  0.899, Validation Accuracy:  0.905, Loss:  0.125
Epoch   6 Batch   50/269 - Train Accuracy:  0.894, Validation Accuracy:  0.904, Loss:  0.137
Epoch   6 Batch   51/269 - Train Accuracy:  0.913, Validation Accuracy:  0.910, Loss:  0.124
Epoch   6 Batch   52/269 - Train Accuracy:  0.903, Validation Accuracy:  0.908, Loss:  0.119
Epoch   6 Batch   53/269 - Train Accuracy:  0.900, Validation Accuracy:  0.911, Loss:  0.136
Epoch   6 Batch   54/269 - Train Accuracy:  0.902, Validation Accuracy:  0.909, Loss:  0.128
Epoch   6 Batch   55/269 - Train Accuracy:  0.918, Validation Accuracy:  0.908, Loss:  0.125
Epoch   6 Batch   56/269 - Train Accuracy:  0.888, Validation Accuracy:  0.905, Loss:  0.129
Epoch   6 Batch   57/269 - Train Accuracy:  0.900, Validation Accuracy:  0.902, Loss:  0.135
Epoch   6 Batch   58/269 - Train Accuracy:  0.921, Validation Accuracy:  0.909, Loss:  0.124
Epoch   6 Batch   59/269 - Train Accuracy:  0.930, Validation Accuracy:  0.910, Loss:  0.110
Epoch   6 Batch   60/269 - Train Accuracy:  0.907, Validation Accuracy:  0.913, Loss:  0.119
Epoch   6 Batch   61/269 - Train Accuracy:  0.912, Validation Accuracy:  0.913, Loss:  0.114
Epoch   6 Batch   62/269 - Train Accuracy:  0.896, Validation Accuracy:  0.915, Loss:  0.126
Epoch   6 Batch   63/269 - Train Accuracy:  0.903, Validation Accuracy:  0.913, Loss:  0.132
Epoch   6 Batch   64/269 - Train Accuracy:  0.906, Validation Accuracy:  0.910, Loss:  0.119
Epoch   6 Batch   65/269 - Train Accuracy:  0.894, Validation Accuracy:  0.910, Loss:  0.123
Epoch   6 Batch   66/269 - Train Accuracy:  0.898, Validation Accuracy:  0.913, Loss:  0.124
Epoch   6 Batch   67/269 - Train Accuracy:  0.908, Validation Accuracy:  0.910, Loss:  0.129
Epoch   6 Batch   68/269 - Train Accuracy:  0.894, Validation Accuracy:  0.910, Loss:  0.130
Epoch   6 Batch   69/269 - Train Accuracy:  0.884, Validation Accuracy:  0.917, Loss:  0.140
Epoch   6 Batch   70/269 - Train Accuracy:  0.921, Validation Accuracy:  0.914, Loss:  0.123
Epoch   6 Batch   71/269 - Train Accuracy:  0.900, Validation Accuracy:  0.913, Loss:  0.134
Epoch   6 Batch   72/269 - Train Accuracy:  0.900, Validation Accuracy:  0.909, Loss:  0.127
Epoch   6 Batch   73/269 - Train Accuracy:  0.901, Validation Accuracy:  0.911, Loss:  0.128
Epoch   6 Batch   74/269 - Train Accuracy:  0.907, Validation Accuracy:  0.910, Loss:  0.121
Epoch   6 Batch   75/269 - Train Accuracy:  0.919, Validation Accuracy:  0.913, Loss:  0.121
Epoch   6 Batch   76/269 - Train Accuracy:  0.910, Validation Accuracy:  0.916, Loss:  0.118
Epoch   6 Batch   77/269 - Train Accuracy:  0.904, Validation Accuracy:  0.910, Loss:  0.118
Epoch   6 Batch   78/269 - Train Accuracy:  0.916, Validation Accuracy:  0.911, Loss:  0.122
Epoch   6 Batch   79/269 - Train Accuracy:  0.889, Validation Accuracy:  0.917, Loss:  0.119
Epoch   6 Batch   80/269 - Train Accuracy:  0.908, Validation Accuracy:  0.915, Loss:  0.115
Epoch   6 Batch   81/269 - Train Accuracy:  0.903, Validation Accuracy:  0.908, Loss:  0.132
Epoch   6 Batch   82/269 - Train Accuracy:  0.911, Validation Accuracy:  0.902, Loss:  0.112
Epoch   6 Batch   83/269 - Train Accuracy:  0.902, Validation Accuracy:  0.905, Loss:  0.130
Epoch   6 Batch   84/269 - Train Accuracy:  0.915, Validation Accuracy:  0.907, Loss:  0.119
Epoch   6 Batch   85/269 - Train Accuracy:  0.908, Validation Accuracy:  0.908, Loss:  0.119
Epoch   6 Batch   86/269 - Train Accuracy:  0.908, Validation Accuracy:  0.909, Loss:  0.114
Epoch   6 Batch   87/269 - Train Accuracy:  0.889, Validation Accuracy:  0.908, Loss:  0.128
Epoch   6 Batch   88/269 - Train Accuracy:  0.895, Validation Accuracy:  0.914, Loss:  0.122
Epoch   6 Batch   89/269 - Train Accuracy:  0.916, Validation Accuracy:  0.920, Loss:  0.115
Epoch   6 Batch   90/269 - Train Accuracy:  0.905, Validation Accuracy:  0.916, Loss:  0.122
Epoch   6 Batch   91/269 - Train Accuracy:  0.916, Validation Accuracy:  0.915, Loss:  0.110
Epoch   6 Batch   92/269 - Train Accuracy:  0.926, Validation Accuracy:  0.919, Loss:  0.110
Epoch   6 Batch   93/269 - Train Accuracy:  0.923, Validation Accuracy:  0.911, Loss:  0.111
Epoch   6 Batch   94/269 - Train Accuracy:  0.914, Validation Accuracy:  0.918, Loss:  0.125
Epoch   6 Batch   95/269 - Train Accuracy:  0.904, Validation Accuracy:  0.913, Loss:  0.115
Epoch   6 Batch   96/269 - Train Accuracy:  0.902, Validation Accuracy:  0.913, Loss:  0.118
Epoch   6 Batch   97/269 - Train Accuracy:  0.904, Validation Accuracy:  0.910, Loss:  0.118
Epoch   6 Batch   98/269 - Train Accuracy:  0.910, Validation Accuracy:  0.918, Loss:  0.115
Epoch   6 Batch   99/269 - Train Accuracy:  0.918, Validation Accuracy:  0.914, Loss:  0.118
Epoch   6 Batch  100/269 - Train Accuracy:  0.920, Validation Accuracy:  0.915, Loss:  0.114
Epoch   6 Batch  101/269 - Train Accuracy:  0.909, Validation Accuracy:  0.916, Loss:  0.126
Epoch   6 Batch  102/269 - Train Accuracy:  0.911, Validation Accuracy:  0.916, Loss:  0.115
Epoch   6 Batch  103/269 - Train Accuracy:  0.910, Validation Accuracy:  0.913, Loss:  0.119
Epoch   6 Batch  104/269 - Train Accuracy:  0.908, Validation Accuracy:  0.916, Loss:  0.113
Epoch   6 Batch  105/269 - Train Accuracy:  0.905, Validation Accuracy:  0.917, Loss:  0.115
Epoch   6 Batch  106/269 - Train Accuracy:  0.926, Validation Accuracy:  0.916, Loss:  0.107
Epoch   6 Batch  107/269 - Train Accuracy:  0.918, Validation Accuracy:  0.911, Loss:  0.117
Epoch   6 Batch  108/269 - Train Accuracy:  0.915, Validation Accuracy:  0.913, Loss:  0.113
Epoch   6 Batch  109/269 - Train Accuracy:  0.896, Validation Accuracy:  0.916, Loss:  0.119
Epoch   6 Batch  110/269 - Train Accuracy:  0.900, Validation Accuracy:  0.920, Loss:  0.110
Epoch   6 Batch  111/269 - Train Accuracy:  0.901, Validation Accuracy:  0.918, Loss:  0.118
Epoch   6 Batch  112/269 - Train Accuracy:  0.907, Validation Accuracy:  0.917, Loss:  0.115
Epoch   6 Batch  113/269 - Train Accuracy:  0.904, Validation Accuracy:  0.915, Loss:  0.112
Epoch   6 Batch  114/269 - Train Accuracy:  0.913, Validation Accuracy:  0.917, Loss:  0.115
Epoch   6 Batch  115/269 - Train Accuracy:  0.905, Validation Accuracy:  0.914, Loss:  0.113
Epoch   6 Batch  116/269 - Train Accuracy:  0.921, Validation Accuracy:  0.914, Loss:  0.118
Epoch   6 Batch  117/269 - Train Accuracy:  0.915, Validation Accuracy:  0.917, Loss:  0.108
Epoch   6 Batch  118/269 - Train Accuracy:  0.921, Validation Accuracy:  0.913, Loss:  0.106
Epoch   6 Batch  119/269 - Train Accuracy:  0.896, Validation Accuracy:  0.918, Loss:  0.119
Epoch   6 Batch  120/269 - Train Accuracy:  0.924, Validation Accuracy:  0.919, Loss:  0.113
Epoch   6 Batch  121/269 - Train Accuracy:  0.908, Validation Accuracy:  0.912, Loss:  0.110
Epoch   6 Batch  122/269 - Train Accuracy:  0.917, Validation Accuracy:  0.915, Loss:  0.108
Epoch   6 Batch  123/269 - Train Accuracy:  0.904, Validation Accuracy:  0.909, Loss:  0.110
Epoch   6 Batch  124/269 - Train Accuracy:  0.915, Validation Accuracy:  0.910, Loss:  0.105
Epoch   6 Batch  125/269 - Train Accuracy:  0.916, Validation Accuracy:  0.915, Loss:  0.104
Epoch   6 Batch  126/269 - Train Accuracy:  0.897, Validation Accuracy:  0.914, Loss:  0.112
Epoch   6 Batch  127/269 - Train Accuracy:  0.896, Validation Accuracy:  0.913, Loss:  0.110
Epoch   6 Batch  128/269 - Train Accuracy:  0.907, Validation Accuracy:  0.920, Loss:  0.109
Epoch   6 Batch  129/269 - Train Accuracy:  0.908, Validation Accuracy:  0.922, Loss:  0.109
Epoch   6 Batch  130/269 - Train Accuracy:  0.914, Validation Accuracy:  0.919, Loss:  0.116
Epoch   6 Batch  131/269 - Train Accuracy:  0.893, Validation Accuracy:  0.914, Loss:  0.111
Epoch   6 Batch  132/269 - Train Accuracy:  0.899, Validation Accuracy:  0.911, Loss:  0.116
Epoch   6 Batch  133/269 - Train Accuracy:  0.921, Validation Accuracy:  0.908, Loss:  0.102
Epoch   6 Batch  134/269 - Train Accuracy:  0.904, Validation Accuracy:  0.915, Loss:  0.110
Epoch   6 Batch  135/269 - Train Accuracy:  0.912, Validation Accuracy:  0.914, Loss:  0.117
Epoch   6 Batch  136/269 - Train Accuracy:  0.895, Validation Accuracy:  0.906, Loss:  0.115
Epoch   6 Batch  137/269 - Train Accuracy:  0.905, Validation Accuracy:  0.914, Loss:  0.120
Epoch   6 Batch  138/269 - Train Accuracy:  0.914, Validation Accuracy:  0.919, Loss:  0.106
Epoch   6 Batch  139/269 - Train Accuracy:  0.911, Validation Accuracy:  0.923, Loss:  0.101
Epoch   6 Batch  140/269 - Train Accuracy:  0.902, Validation Accuracy:  0.925, Loss:  0.116
Epoch   6 Batch  141/269 - Train Accuracy:  0.907, Validation Accuracy:  0.924, Loss:  0.113
Epoch   6 Batch  142/269 - Train Accuracy:  0.913, Validation Accuracy:  0.924, Loss:  0.103
Epoch   6 Batch  143/269 - Train Accuracy:  0.921, Validation Accuracy:  0.917, Loss:  0.103
Epoch   6 Batch  144/269 - Train Accuracy:  0.934, Validation Accuracy:  0.915, Loss:  0.093
Epoch   6 Batch  145/269 - Train Accuracy:  0.909, Validation Accuracy:  0.911, Loss:  0.104
Epoch   6 Batch  146/269 - Train Accuracy:  0.907, Validation Accuracy:  0.912, Loss:  0.109
Epoch   6 Batch  147/269 - Train Accuracy:  0.917, Validation Accuracy:  0.913, Loss:  0.105
Epoch   6 Batch  148/269 - Train Accuracy:  0.914, Validation Accuracy:  0.922, Loss:  0.109
Epoch   6 Batch  149/269 - Train Accuracy:  0.899, Validation Accuracy:  0.919, Loss:  0.114
Epoch   6 Batch  150/269 - Train Accuracy:  0.911, Validation Accuracy:  0.920, Loss:  0.105
Epoch   6 Batch  151/269 - Train Accuracy:  0.907, Validation Accuracy:  0.916, Loss:  0.102
Epoch   6 Batch  152/269 - Train Accuracy:  0.908, Validation Accuracy:  0.921, Loss:  0.108
Epoch   6 Batch  153/269 - Train Accuracy:  0.919, Validation Accuracy:  0.923, Loss:  0.105
Epoch   6 Batch  154/269 - Train Accuracy:  0.926, Validation Accuracy:  0.924, Loss:  0.107
Epoch   6 Batch  155/269 - Train Accuracy:  0.910, Validation Accuracy:  0.925, Loss:  0.103
Epoch   6 Batch  156/269 - Train Accuracy:  0.911, Validation Accuracy:  0.926, Loss:  0.109
Epoch   6 Batch  157/269 - Train Accuracy:  0.901, Validation Accuracy:  0.922, Loss:  0.098
Epoch   6 Batch  158/269 - Train Accuracy:  0.915, Validation Accuracy:  0.921, Loss:  0.106
Epoch   6 Batch  159/269 - Train Accuracy:  0.912, Validation Accuracy:  0.920, Loss:  0.105
Epoch   6 Batch  160/269 - Train Accuracy:  0.919, Validation Accuracy:  0.916, Loss:  0.106
Epoch   6 Batch  161/269 - Train Accuracy:  0.910, Validation Accuracy:  0.916, Loss:  0.103
Epoch   6 Batch  162/269 - Train Accuracy:  0.931, Validation Accuracy:  0.915, Loss:  0.101
Epoch   6 Batch  163/269 - Train Accuracy:  0.915, Validation Accuracy:  0.919, Loss:  0.101
Epoch   6 Batch  164/269 - Train Accuracy:  0.914, Validation Accuracy:  0.913, Loss:  0.102
Epoch   6 Batch  165/269 - Train Accuracy:  0.927, Validation Accuracy:  0.912, Loss:  0.102
Epoch   6 Batch  166/269 - Train Accuracy:  0.906, Validation Accuracy:  0.915, Loss:  0.102
Epoch   6 Batch  167/269 - Train Accuracy:  0.919, Validation Accuracy:  0.923, Loss:  0.102
Epoch   6 Batch  168/269 - Train Accuracy:  0.918, Validation Accuracy:  0.921, Loss:  0.105
Epoch   6 Batch  169/269 - Train Accuracy:  0.906, Validation Accuracy:  0.923, Loss:  0.101
Epoch   6 Batch  170/269 - Train Accuracy:  0.910, Validation Accuracy:  0.922, Loss:  0.101
Epoch   6 Batch  171/269 - Train Accuracy:  0.918, Validation Accuracy:  0.928, Loss:  0.103
Epoch   6 Batch  172/269 - Train Accuracy:  0.905, Validation Accuracy:  0.922, Loss:  0.111
Epoch   6 Batch  173/269 - Train Accuracy:  0.918, Validation Accuracy:  0.914, Loss:  0.094
Epoch   6 Batch  174/269 - Train Accuracy:  0.922, Validation Accuracy:  0.919, Loss:  0.100
Epoch   6 Batch  175/269 - Train Accuracy:  0.899, Validation Accuracy:  0.919, Loss:  0.118
Epoch   6 Batch  176/269 - Train Accuracy:  0.905, Validation Accuracy:  0.922, Loss:  0.110
Epoch   6 Batch  177/269 - Train Accuracy:  0.923, Validation Accuracy:  0.926, Loss:  0.095
Epoch   6 Batch  178/269 - Train Accuracy:  0.924, Validation Accuracy:  0.927, Loss:  0.098
Epoch   6 Batch  179/269 - Train Accuracy:  0.905, Validation Accuracy:  0.929, Loss:  0.100
Epoch   6 Batch  180/269 - Train Accuracy:  0.929, Validation Accuracy:  0.931, Loss:  0.098
Epoch   6 Batch  181/269 - Train Accuracy:  0.915, Validation Accuracy:  0.930, Loss:  0.103
Epoch   6 Batch  182/269 - Train Accuracy:  0.914, Validation Accuracy:  0.930, Loss:  0.101
Epoch   6 Batch  183/269 - Train Accuracy:  0.930, Validation Accuracy:  0.928, Loss:  0.087
Epoch   6 Batch  184/269 - Train Accuracy:  0.916, Validation Accuracy:  0.930, Loss:  0.097
Epoch   6 Batch  185/269 - Train Accuracy:  0.921, Validation Accuracy:  0.926, Loss:  0.099
Epoch   6 Batch  186/269 - Train Accuracy:  0.915, Validation Accuracy:  0.924, Loss:  0.098
Epoch   6 Batch  187/269 - Train Accuracy:  0.912, Validation Accuracy:  0.926, Loss:  0.095
Epoch   6 Batch  188/269 - Train Accuracy:  0.919, Validation Accuracy:  0.924, Loss:  0.096
Epoch   6 Batch  189/269 - Train Accuracy:  0.922, Validation Accuracy:  0.929, Loss:  0.094
Epoch   6 Batch  190/269 - Train Accuracy:  0.920, Validation Accuracy:  0.925, Loss:  0.095
Epoch   6 Batch  191/269 - Train Accuracy:  0.899, Validation Accuracy:  0.923, Loss:  0.101
Epoch   6 Batch  192/269 - Train Accuracy:  0.911, Validation Accuracy:  0.921, Loss:  0.103
Epoch   6 Batch  193/269 - Train Accuracy:  0.925, Validation Accuracy:  0.927, Loss:  0.098
Epoch   6 Batch  194/269 - Train Accuracy:  0.905, Validation Accuracy:  0.925, Loss:  0.101
Epoch   6 Batch  195/269 - Train Accuracy:  0.905, Validation Accuracy:  0.925, Loss:  0.096
Epoch   6 Batch  196/269 - Train Accuracy:  0.909, Validation Accuracy:  0.924, Loss:  0.095
Epoch   6 Batch  197/269 - Train Accuracy:  0.907, Validation Accuracy:  0.927, Loss:  0.103
Epoch   6 Batch  198/269 - Train Accuracy:  0.920, Validation Accuracy:  0.930, Loss:  0.100
Epoch   6 Batch  199/269 - Train Accuracy:  0.916, Validation Accuracy:  0.924, Loss:  0.104
Epoch   6 Batch  200/269 - Train Accuracy:  0.911, Validation Accuracy:  0.926, Loss:  0.100
Epoch   6 Batch  201/269 - Train Accuracy:  0.916, Validation Accuracy:  0.931, Loss:  0.100
Epoch   6 Batch  202/269 - Train Accuracy:  0.915, Validation Accuracy:  0.919, Loss:  0.095
Epoch   6 Batch  203/269 - Train Accuracy:  0.923, Validation Accuracy:  0.925, Loss:  0.106
Epoch   6 Batch  204/269 - Train Accuracy:  0.914, Validation Accuracy:  0.931, Loss:  0.103
Epoch   6 Batch  205/269 - Train Accuracy:  0.926, Validation Accuracy:  0.925, Loss:  0.092
Epoch   6 Batch  206/269 - Train Accuracy:  0.909, Validation Accuracy:  0.927, Loss:  0.103
Epoch   6 Batch  207/269 - Train Accuracy:  0.907, Validation Accuracy:  0.923, Loss:  0.096
Epoch   6 Batch  208/269 - Train Accuracy:  0.910, Validation Accuracy:  0.924, Loss:  0.102
Epoch   6 Batch  209/269 - Train Accuracy:  0.917, Validation Accuracy:  0.924, Loss:  0.093
Epoch   6 Batch  210/269 - Train Accuracy:  0.919, Validation Accuracy:  0.922, Loss:  0.090
Epoch   6 Batch  211/269 - Train Accuracy:  0.921, Validation Accuracy:  0.925, Loss:  0.098
Epoch   6 Batch  212/269 - Train Accuracy:  0.911, Validation Accuracy:  0.923, Loss:  0.102
Epoch   6 Batch  213/269 - Train Accuracy:  0.909, Validation Accuracy:  0.921, Loss:  0.097
Epoch   6 Batch  214/269 - Train Accuracy:  0.917, Validation Accuracy:  0.914, Loss:  0.097
Epoch   6 Batch  215/269 - Train Accuracy:  0.924, Validation Accuracy:  0.913, Loss:  0.091
Epoch   6 Batch  216/269 - Train Accuracy:  0.908, Validation Accuracy:  0.917, Loss:  0.107
Epoch   6 Batch  217/269 - Train Accuracy:  0.912, Validation Accuracy:  0.921, Loss:  0.100
Epoch   6 Batch  218/269 - Train Accuracy:  0.924, Validation Accuracy:  0.924, Loss:  0.094
Epoch   6 Batch  219/269 - Train Accuracy:  0.924, Validation Accuracy:  0.923, Loss:  0.099
Epoch   6 Batch  220/269 - Train Accuracy:  0.911, Validation Accuracy:  0.925, Loss:  0.090
Epoch   6 Batch  221/269 - Train Accuracy:  0.912, Validation Accuracy:  0.925, Loss:  0.099
Epoch   6 Batch  222/269 - Train Accuracy:  0.937, Validation Accuracy:  0.922, Loss:  0.089
Epoch   6 Batch  223/269 - Train Accuracy:  0.911, Validation Accuracy:  0.927, Loss:  0.091
Epoch   6 Batch  224/269 - Train Accuracy:  0.920, Validation Accuracy:  0.923, Loss:  0.103
Epoch   6 Batch  225/269 - Train Accuracy:  0.913, Validation Accuracy:  0.925, Loss:  0.089
Epoch   6 Batch  226/269 - Train Accuracy:  0.921, Validation Accuracy:  0.917, Loss:  0.098
Epoch   6 Batch  227/269 - Train Accuracy:  0.922, Validation Accuracy:  0.919, Loss:  0.096
Epoch   6 Batch  228/269 - Train Accuracy:  0.918, Validation Accuracy:  0.924, Loss:  0.091
Epoch   6 Batch  229/269 - Train Accuracy:  0.913, Validation Accuracy:  0.922, Loss:  0.093
Epoch   6 Batch  230/269 - Train Accuracy:  0.919, Validation Accuracy:  0.926, Loss:  0.094
Epoch   6 Batch  231/269 - Train Accuracy:  0.911, Validation Accuracy:  0.926, Loss:  0.096
Epoch   6 Batch  232/269 - Train Accuracy:  0.915, Validation Accuracy:  0.921, Loss:  0.095
Epoch   6 Batch  233/269 - Train Accuracy:  0.923, Validation Accuracy:  0.916, Loss:  0.097
Epoch   6 Batch  234/269 - Train Accuracy:  0.921, Validation Accuracy:  0.919, Loss:  0.091
Epoch   6 Batch  235/269 - Train Accuracy:  0.938, Validation Accuracy:  0.915, Loss:  0.085
Epoch   6 Batch  236/269 - Train Accuracy:  0.918, Validation Accuracy:  0.918, Loss:  0.084
Epoch   6 Batch  237/269 - Train Accuracy:  0.919, Validation Accuracy:  0.921, Loss:  0.091
Epoch   6 Batch  238/269 - Train Accuracy:  0.921, Validation Accuracy:  0.923, Loss:  0.092
Epoch   6 Batch  239/269 - Train Accuracy:  0.929, Validation Accuracy:  0.923, Loss:  0.091
Epoch   6 Batch  240/269 - Train Accuracy:  0.933, Validation Accuracy:  0.920, Loss:  0.085
Epoch   6 Batch  241/269 - Train Accuracy:  0.910, Validation Accuracy:  0.919, Loss:  0.102
Epoch   6 Batch  242/269 - Train Accuracy:  0.921, Validation Accuracy:  0.920, Loss:  0.093
Epoch   6 Batch  243/269 - Train Accuracy:  0.917, Validation Accuracy:  0.926, Loss:  0.084
Epoch   6 Batch  244/269 - Train Accuracy:  0.920, Validation Accuracy:  0.928, Loss:  0.094
Epoch   6 Batch  245/269 - Train Accuracy:  0.907, Validation Accuracy:  0.926, Loss:  0.096
Epoch   6 Batch  246/269 - Train Accuracy:  0.916, Validation Accuracy:  0.924, Loss:  0.093
Epoch   6 Batch  247/269 - Train Accuracy:  0.916, Validation Accuracy:  0.923, Loss:  0.090
Epoch   6 Batch  248/269 - Train Accuracy:  0.933, Validation Accuracy:  0.924, Loss:  0.087
Epoch   6 Batch  249/269 - Train Accuracy:  0.925, Validation Accuracy:  0.926, Loss:  0.085
Epoch   6 Batch  250/269 - Train Accuracy:  0.929, Validation Accuracy:  0.927, Loss:  0.092
Epoch   6 Batch  251/269 - Train Accuracy:  0.938, Validation Accuracy:  0.930, Loss:  0.087
Epoch   6 Batch  252/269 - Train Accuracy:  0.940, Validation Accuracy:  0.922, Loss:  0.079
Epoch   6 Batch  253/269 - Train Accuracy:  0.911, Validation Accuracy:  0.923, Loss:  0.093
Epoch   6 Batch  254/269 - Train Accuracy:  0.923, Validation Accuracy:  0.927, Loss:  0.090
Epoch   6 Batch  255/269 - Train Accuracy:  0.919, Validation Accuracy:  0.925, Loss:  0.089
Epoch   6 Batch  256/269 - Train Accuracy:  0.914, Validation Accuracy:  0.926, Loss:  0.086
Epoch   6 Batch  257/269 - Train Accuracy:  0.901, Validation Accuracy:  0.917, Loss:  0.098
Epoch   6 Batch  258/269 - Train Accuracy:  0.917, Validation Accuracy:  0.918, Loss:  0.090
Epoch   6 Batch  259/269 - Train Accuracy:  0.917, Validation Accuracy:  0.923, Loss:  0.089
Epoch   6 Batch  260/269 - Train Accuracy:  0.913, Validation Accuracy:  0.929, Loss:  0.092
Epoch   6 Batch  261/269 - Train Accuracy:  0.922, Validation Accuracy:  0.931, Loss:  0.090
Epoch   6 Batch  262/269 - Train Accuracy:  0.926, Validation Accuracy:  0.928, Loss:  0.089
Epoch   6 Batch  263/269 - Train Accuracy:  0.913, Validation Accuracy:  0.930, Loss:  0.092
Epoch   6 Batch  264/269 - Train Accuracy:  0.897, Validation Accuracy:  0.930, Loss:  0.094
Epoch   6 Batch  265/269 - Train Accuracy:  0.913, Validation Accuracy:  0.931, Loss:  0.090
Epoch   6 Batch  266/269 - Train Accuracy:  0.917, Validation Accuracy:  0.924, Loss:  0.082
Epoch   6 Batch  267/269 - Train Accuracy:  0.928, Validation Accuracy:  0.926, Loss:  0.092
Epoch   7 Batch    0/269 - Train Accuracy:  0.934, Validation Accuracy:  0.930, Loss:  0.096
Epoch   7 Batch    1/269 - Train Accuracy:  0.922, Validation Accuracy:  0.927, Loss:  0.090
Epoch   7 Batch    2/269 - Train Accuracy:  0.925, Validation Accuracy:  0.928, Loss:  0.089
Epoch   7 Batch    3/269 - Train Accuracy:  0.918, Validation Accuracy:  0.929, Loss:  0.091
Epoch   7 Batch    4/269 - Train Accuracy:  0.905, Validation Accuracy:  0.923, Loss:  0.090
Epoch   7 Batch    5/269 - Train Accuracy:  0.931, Validation Accuracy:  0.913, Loss:  0.087
Epoch   7 Batch    6/269 - Train Accuracy:  0.934, Validation Accuracy:  0.922, Loss:  0.082
Epoch   7 Batch    7/269 - Train Accuracy:  0.933, Validation Accuracy:  0.925, Loss:  0.083
Epoch   7 Batch    8/269 - Train Accuracy:  0.928, Validation Accuracy:  0.928, Loss:  0.088
Epoch   7 Batch    9/269 - Train Accuracy:  0.916, Validation Accuracy:  0.927, Loss:  0.093
Epoch   7 Batch   10/269 - Train Accuracy:  0.930, Validation Accuracy:  0.922, Loss:  0.081
Epoch   7 Batch   11/269 - Train Accuracy:  0.919, Validation Accuracy:  0.924, Loss:  0.093
Epoch   7 Batch   12/269 - Train Accuracy:  0.917, Validation Accuracy:  0.926, Loss:  0.094
Epoch   7 Batch   13/269 - Train Accuracy:  0.935, Validation Accuracy:  0.930, Loss:  0.076
Epoch   7 Batch   14/269 - Train Accuracy:  0.922, Validation Accuracy:  0.927, Loss:  0.084
Epoch   7 Batch   15/269 - Train Accuracy:  0.932, Validation Accuracy:  0.933, Loss:  0.075
Epoch   7 Batch   16/269 - Train Accuracy:  0.921, Validation Accuracy:  0.932, Loss:  0.092
Epoch   7 Batch   17/269 - Train Accuracy:  0.936, Validation Accuracy:  0.932, Loss:  0.077
Epoch   7 Batch   18/269 - Train Accuracy:  0.913, Validation Accuracy:  0.934, Loss:  0.086
Epoch   7 Batch   19/269 - Train Accuracy:  0.929, Validation Accuracy:  0.928, Loss:  0.074
Epoch   7 Batch   20/269 - Train Accuracy:  0.934, Validation Accuracy:  0.934, Loss:  0.084
Epoch   7 Batch   21/269 - Train Accuracy:  0.912, Validation Accuracy:  0.935, Loss:  0.095
Epoch   7 Batch   22/269 - Train Accuracy:  0.927, Validation Accuracy:  0.933, Loss:  0.079
Epoch   7 Batch   23/269 - Train Accuracy:  0.925, Validation Accuracy:  0.933, Loss:  0.087
Epoch   7 Batch   24/269 - Train Accuracy:  0.921, Validation Accuracy:  0.937, Loss:  0.084
Epoch   7 Batch   25/269 - Train Accuracy:  0.914, Validation Accuracy:  0.931, Loss:  0.091
Epoch   7 Batch   26/269 - Train Accuracy:  0.923, Validation Accuracy:  0.929, Loss:  0.079
Epoch   7 Batch   27/269 - Train Accuracy:  0.920, Validation Accuracy:  0.929, Loss:  0.080
Epoch   7 Batch   28/269 - Train Accuracy:  0.898, Validation Accuracy:  0.931, Loss:  0.088
Epoch   7 Batch   29/269 - Train Accuracy:  0.923, Validation Accuracy:  0.931, Loss:  0.089
Epoch   7 Batch   30/269 - Train Accuracy:  0.922, Validation Accuracy:  0.925, Loss:  0.082
Epoch   7 Batch   31/269 - Train Accuracy:  0.938, Validation Accuracy:  0.920, Loss:  0.078
Epoch   7 Batch   32/269 - Train Accuracy:  0.924, Validation Accuracy:  0.921, Loss:  0.079
Epoch   7 Batch   33/269 - Train Accuracy:  0.931, Validation Accuracy:  0.923, Loss:  0.075
Epoch   7 Batch   34/269 - Train Accuracy:  0.916, Validation Accuracy:  0.929, Loss:  0.080
Epoch   7 Batch   35/269 - Train Accuracy:  0.921, Validation Accuracy:  0.931, Loss:  0.094
Epoch   7 Batch   36/269 - Train Accuracy:  0.912, Validation Accuracy:  0.928, Loss:  0.085
Epoch   7 Batch   37/269 - Train Accuracy:  0.913, Validation Accuracy:  0.928, Loss:  0.082
Epoch   7 Batch   38/269 - Train Accuracy:  0.921, Validation Accuracy:  0.933, Loss:  0.082
Epoch   7 Batch   39/269 - Train Accuracy:  0.930, Validation Accuracy:  0.935, Loss:  0.079
Epoch   7 Batch   40/269 - Train Accuracy:  0.913, Validation Accuracy:  0.934, Loss:  0.088
Epoch   7 Batch   41/269 - Train Accuracy:  0.920, Validation Accuracy:  0.936, Loss:  0.085
Epoch   7 Batch   42/269 - Train Accuracy:  0.934, Validation Accuracy:  0.935, Loss:  0.074
Epoch   7 Batch   43/269 - Train Accuracy:  0.917, Validation Accuracy:  0.936, Loss:  0.083
Epoch   7 Batch   44/269 - Train Accuracy:  0.923, Validation Accuracy:  0.934, Loss:  0.085
Epoch   7 Batch   45/269 - Train Accuracy:  0.922, Validation Accuracy:  0.935, Loss:  0.083
Epoch   7 Batch   46/269 - Train Accuracy:  0.926, Validation Accuracy:  0.934, Loss:  0.080
Epoch   7 Batch   47/269 - Train Accuracy:  0.934, Validation Accuracy:  0.934, Loss:  0.073
Epoch   7 Batch   48/269 - Train Accuracy:  0.932, Validation Accuracy:  0.939, Loss:  0.078
Epoch   7 Batch   49/269 - Train Accuracy:  0.925, Validation Accuracy:  0.938, Loss:  0.077
Epoch   7 Batch   50/269 - Train Accuracy:  0.908, Validation Accuracy:  0.934, Loss:  0.090
Epoch   7 Batch   51/269 - Train Accuracy:  0.925, Validation Accuracy:  0.934, Loss:  0.080
Epoch   7 Batch   52/269 - Train Accuracy:  0.929, Validation Accuracy:  0.933, Loss:  0.072
Epoch   7 Batch   53/269 - Train Accuracy:  0.923, Validation Accuracy:  0.928, Loss:  0.089
Epoch   7 Batch   54/269 - Train Accuracy:  0.927, Validation Accuracy:  0.928, Loss:  0.078
Epoch   7 Batch   55/269 - Train Accuracy:  0.932, Validation Accuracy:  0.928, Loss:  0.078
Epoch   7 Batch   56/269 - Train Accuracy:  0.910, Validation Accuracy:  0.927, Loss:  0.080
Epoch   7 Batch   57/269 - Train Accuracy:  0.919, Validation Accuracy:  0.928, Loss:  0.089
Epoch   7 Batch   58/269 - Train Accuracy:  0.932, Validation Accuracy:  0.936, Loss:  0.082
Epoch   7 Batch   59/269 - Train Accuracy:  0.942, Validation Accuracy:  0.937, Loss:  0.067
Epoch   7 Batch   60/269 - Train Accuracy:  0.925, Validation Accuracy:  0.936, Loss:  0.075
Epoch   7 Batch   61/269 - Train Accuracy:  0.930, Validation Accuracy:  0.933, Loss:  0.073
Epoch   7 Batch   62/269 - Train Accuracy:  0.915, Validation Accuracy:  0.938, Loss:  0.084
Epoch   7 Batch   63/269 - Train Accuracy:  0.920, Validation Accuracy:  0.935, Loss:  0.087
Epoch   7 Batch   64/269 - Train Accuracy:  0.933, Validation Accuracy:  0.937, Loss:  0.074
Epoch   7 Batch   65/269 - Train Accuracy:  0.916, Validation Accuracy:  0.932, Loss:  0.079
Epoch   7 Batch   66/269 - Train Accuracy:  0.924, Validation Accuracy:  0.929, Loss:  0.080
Epoch   7 Batch   67/269 - Train Accuracy:  0.927, Validation Accuracy:  0.925, Loss:  0.085
Epoch   7 Batch   68/269 - Train Accuracy:  0.927, Validation Accuracy:  0.919, Loss:  0.083
Epoch   7 Batch   69/269 - Train Accuracy:  0.907, Validation Accuracy:  0.931, Loss:  0.093
Epoch   7 Batch   70/269 - Train Accuracy:  0.936, Validation Accuracy:  0.930, Loss:  0.081
Epoch   7 Batch   71/269 - Train Accuracy:  0.928, Validation Accuracy:  0.933, Loss:  0.090
Epoch   7 Batch   72/269 - Train Accuracy:  0.925, Validation Accuracy:  0.931, Loss:  0.087
Epoch   7 Batch   73/269 - Train Accuracy:  0.915, Validation Accuracy:  0.925, Loss:  0.083
Epoch   7 Batch   74/269 - Train Accuracy:  0.924, Validation Accuracy:  0.932, Loss:  0.078
Epoch   7 Batch   75/269 - Train Accuracy:  0.941, Validation Accuracy:  0.934, Loss:  0.079
Epoch   7 Batch   76/269 - Train Accuracy:  0.923, Validation Accuracy:  0.933, Loss:  0.076
Epoch   7 Batch   77/269 - Train Accuracy:  0.925, Validation Accuracy:  0.932, Loss:  0.077
Epoch   7 Batch   78/269 - Train Accuracy:  0.934, Validation Accuracy:  0.929, Loss:  0.079
Epoch   7 Batch   79/269 - Train Accuracy:  0.922, Validation Accuracy:  0.927, Loss:  0.078
Epoch   7 Batch   80/269 - Train Accuracy:  0.927, Validation Accuracy:  0.925, Loss:  0.075
Epoch   7 Batch   81/269 - Train Accuracy:  0.923, Validation Accuracy:  0.924, Loss:  0.087
Epoch   7 Batch   82/269 - Train Accuracy:  0.940, Validation Accuracy:  0.922, Loss:  0.070
Epoch   7 Batch   83/269 - Train Accuracy:  0.909, Validation Accuracy:  0.929, Loss:  0.088
Epoch   7 Batch   84/269 - Train Accuracy:  0.929, Validation Accuracy:  0.932, Loss:  0.077
Epoch   7 Batch   85/269 - Train Accuracy:  0.926, Validation Accuracy:  0.932, Loss:  0.077
Epoch   7 Batch   86/269 - Train Accuracy:  0.933, Validation Accuracy:  0.932, Loss:  0.073
Epoch   7 Batch   87/269 - Train Accuracy:  0.917, Validation Accuracy:  0.928, Loss:  0.084
Epoch   7 Batch   88/269 - Train Accuracy:  0.912, Validation Accuracy:  0.928, Loss:  0.080
Epoch   7 Batch   89/269 - Train Accuracy:  0.938, Validation Accuracy:  0.932, Loss:  0.075
Epoch   7 Batch   90/269 - Train Accuracy:  0.931, Validation Accuracy:  0.932, Loss:  0.080
Epoch   7 Batch   91/269 - Train Accuracy:  0.940, Validation Accuracy:  0.932, Loss:  0.070
Epoch   7 Batch   92/269 - Train Accuracy:  0.938, Validation Accuracy:  0.933, Loss:  0.070
Epoch   7 Batch   93/269 - Train Accuracy:  0.935, Validation Accuracy:  0.933, Loss:  0.073
Epoch   7 Batch   94/269 - Train Accuracy:  0.923, Validation Accuracy:  0.933, Loss:  0.083
Epoch   7 Batch   95/269 - Train Accuracy:  0.931, Validation Accuracy:  0.934, Loss:  0.076
Epoch   7 Batch   96/269 - Train Accuracy:  0.914, Validation Accuracy:  0.930, Loss:  0.078
Epoch   7 Batch   97/269 - Train Accuracy:  0.927, Validation Accuracy:  0.927, Loss:  0.080
Epoch   7 Batch   98/269 - Train Accuracy:  0.927, Validation Accuracy:  0.926, Loss:  0.074
Epoch   7 Batch   99/269 - Train Accuracy:  0.931, Validation Accuracy:  0.930, Loss:  0.078
Epoch   7 Batch  100/269 - Train Accuracy:  0.925, Validation Accuracy:  0.936, Loss:  0.075
Epoch   7 Batch  101/269 - Train Accuracy:  0.926, Validation Accuracy:  0.939, Loss:  0.087
Epoch   7 Batch  102/269 - Train Accuracy:  0.933, Validation Accuracy:  0.932, Loss:  0.075
Epoch   7 Batch  103/269 - Train Accuracy:  0.931, Validation Accuracy:  0.936, Loss:  0.082
Epoch   7 Batch  104/269 - Train Accuracy:  0.924, Validation Accuracy:  0.933, Loss:  0.075
Epoch   7 Batch  105/269 - Train Accuracy:  0.927, Validation Accuracy:  0.934, Loss:  0.076
Epoch   7 Batch  106/269 - Train Accuracy:  0.937, Validation Accuracy:  0.937, Loss:  0.070
Epoch   7 Batch  107/269 - Train Accuracy:  0.934, Validation Accuracy:  0.936, Loss:  0.078
Epoch   7 Batch  108/269 - Train Accuracy:  0.943, Validation Accuracy:  0.935, Loss:  0.075
Epoch   7 Batch  109/269 - Train Accuracy:  0.914, Validation Accuracy:  0.932, Loss:  0.081
Epoch   7 Batch  110/269 - Train Accuracy:  0.937, Validation Accuracy:  0.933, Loss:  0.070
Epoch   7 Batch  111/269 - Train Accuracy:  0.928, Validation Accuracy:  0.934, Loss:  0.079
Epoch   7 Batch  112/269 - Train Accuracy:  0.926, Validation Accuracy:  0.929, Loss:  0.078
Epoch   7 Batch  113/269 - Train Accuracy:  0.923, Validation Accuracy:  0.931, Loss:  0.075
Epoch   7 Batch  114/269 - Train Accuracy:  0.925, Validation Accuracy:  0.934, Loss:  0.076
Epoch   7 Batch  115/269 - Train Accuracy:  0.931, Validation Accuracy:  0.936, Loss:  0.073
Epoch   7 Batch  116/269 - Train Accuracy:  0.941, Validation Accuracy:  0.933, Loss:  0.078
Epoch   7 Batch  117/269 - Train Accuracy:  0.934, Validation Accuracy:  0.937, Loss:  0.069
Epoch   7 Batch  118/269 - Train Accuracy:  0.929, Validation Accuracy:  0.936, Loss:  0.068
Epoch   7 Batch  119/269 - Train Accuracy:  0.918, Validation Accuracy:  0.935, Loss:  0.080
Epoch   7 Batch  120/269 - Train Accuracy:  0.940, Validation Accuracy:  0.934, Loss:  0.074
Epoch   7 Batch  121/269 - Train Accuracy:  0.935, Validation Accuracy:  0.931, Loss:  0.071
Epoch   7 Batch  122/269 - Train Accuracy:  0.936, Validation Accuracy:  0.929, Loss:  0.070
Epoch   7 Batch  123/269 - Train Accuracy:  0.926, Validation Accuracy:  0.932, Loss:  0.072
Epoch   7 Batch  124/269 - Train Accuracy:  0.935, Validation Accuracy:  0.929, Loss:  0.067
Epoch   7 Batch  125/269 - Train Accuracy:  0.938, Validation Accuracy:  0.936, Loss:  0.067
Epoch   7 Batch  126/269 - Train Accuracy:  0.910, Validation Accuracy:  0.937, Loss:  0.074
Epoch   7 Batch  127/269 - Train Accuracy:  0.928, Validation Accuracy:  0.936, Loss:  0.073
Epoch   7 Batch  128/269 - Train Accuracy:  0.936, Validation Accuracy:  0.930, Loss:  0.070
Epoch   7 Batch  129/269 - Train Accuracy:  0.924, Validation Accuracy:  0.929, Loss:  0.073
Epoch   7 Batch  130/269 - Train Accuracy:  0.933, Validation Accuracy:  0.935, Loss:  0.079
Epoch   7 Batch  131/269 - Train Accuracy:  0.921, Validation Accuracy:  0.935, Loss:  0.074
Epoch   7 Batch  132/269 - Train Accuracy:  0.911, Validation Accuracy:  0.929, Loss:  0.079
Epoch   7 Batch  133/269 - Train Accuracy:  0.937, Validation Accuracy:  0.926, Loss:  0.068
Epoch   7 Batch  134/269 - Train Accuracy:  0.923, Validation Accuracy:  0.928, Loss:  0.072
Epoch   7 Batch  135/269 - Train Accuracy:  0.921, Validation Accuracy:  0.929, Loss:  0.079
Epoch   7 Batch  136/269 - Train Accuracy:  0.909, Validation Accuracy:  0.928, Loss:  0.079
Epoch   7 Batch  137/269 - Train Accuracy:  0.920, Validation Accuracy:  0.933, Loss:  0.081
Epoch   7 Batch  138/269 - Train Accuracy:  0.931, Validation Accuracy:  0.933, Loss:  0.069
Epoch   7 Batch  139/269 - Train Accuracy:  0.936, Validation Accuracy:  0.935, Loss:  0.066
Epoch   7 Batch  140/269 - Train Accuracy:  0.929, Validation Accuracy:  0.935, Loss:  0.078
Epoch   7 Batch  141/269 - Train Accuracy:  0.924, Validation Accuracy:  0.936, Loss:  0.076
Epoch   7 Batch  142/269 - Train Accuracy:  0.927, Validation Accuracy:  0.936, Loss:  0.069
Epoch   7 Batch  143/269 - Train Accuracy:  0.936, Validation Accuracy:  0.936, Loss:  0.067
Epoch   7 Batch  144/269 - Train Accuracy:  0.947, Validation Accuracy:  0.934, Loss:  0.060
Epoch   7 Batch  145/269 - Train Accuracy:  0.933, Validation Accuracy:  0.941, Loss:  0.068
Epoch   7 Batch  146/269 - Train Accuracy:  0.926, Validation Accuracy:  0.934, Loss:  0.073
Epoch   7 Batch  147/269 - Train Accuracy:  0.939, Validation Accuracy:  0.930, Loss:  0.074
Epoch   7 Batch  148/269 - Train Accuracy:  0.932, Validation Accuracy:  0.926, Loss:  0.074
Epoch   7 Batch  149/269 - Train Accuracy:  0.916, Validation Accuracy:  0.930, Loss:  0.080
Epoch   7 Batch  150/269 - Train Accuracy:  0.931, Validation Accuracy:  0.937, Loss:  0.072
Epoch   7 Batch  151/269 - Train Accuracy:  0.929, Validation Accuracy:  0.937, Loss:  0.070
Epoch   7 Batch  152/269 - Train Accuracy:  0.918, Validation Accuracy:  0.935, Loss:  0.074
Epoch   7 Batch  153/269 - Train Accuracy:  0.942, Validation Accuracy:  0.933, Loss:  0.071
Epoch   7 Batch  154/269 - Train Accuracy:  0.941, Validation Accuracy:  0.935, Loss:  0.072
Epoch   7 Batch  155/269 - Train Accuracy:  0.928, Validation Accuracy:  0.941, Loss:  0.070
Epoch   7 Batch  156/269 - Train Accuracy:  0.930, Validation Accuracy:  0.941, Loss:  0.072
Epoch   7 Batch  157/269 - Train Accuracy:  0.919, Validation Accuracy:  0.937, Loss:  0.065
Epoch   7 Batch  158/269 - Train Accuracy:  0.932, Validation Accuracy:  0.938, Loss:  0.071
Epoch   7 Batch  159/269 - Train Accuracy:  0.931, Validation Accuracy:  0.927, Loss:  0.074
Epoch   7 Batch  160/269 - Train Accuracy:  0.935, Validation Accuracy:  0.930, Loss:  0.071
Epoch   7 Batch  161/269 - Train Accuracy:  0.929, Validation Accuracy:  0.938, Loss:  0.069
Epoch   7 Batch  162/269 - Train Accuracy:  0.941, Validation Accuracy:  0.940, Loss:  0.068
Epoch   7 Batch  163/269 - Train Accuracy:  0.940, Validation Accuracy:  0.938, Loss:  0.066
Epoch   7 Batch  164/269 - Train Accuracy:  0.938, Validation Accuracy:  0.937, Loss:  0.069
Epoch   7 Batch  165/269 - Train Accuracy:  0.937, Validation Accuracy:  0.929, Loss:  0.067
Epoch   7 Batch  166/269 - Train Accuracy:  0.933, Validation Accuracy:  0.925, Loss:  0.071
Epoch   7 Batch  167/269 - Train Accuracy:  0.937, Validation Accuracy:  0.934, Loss:  0.068
Epoch   7 Batch  168/269 - Train Accuracy:  0.941, Validation Accuracy:  0.934, Loss:  0.071
Epoch   7 Batch  169/269 - Train Accuracy:  0.921, Validation Accuracy:  0.937, Loss:  0.068
Epoch   7 Batch  170/269 - Train Accuracy:  0.928, Validation Accuracy:  0.937, Loss:  0.066
Epoch   7 Batch  171/269 - Train Accuracy:  0.933, Validation Accuracy:  0.937, Loss:  0.070
Epoch   7 Batch  172/269 - Train Accuracy:  0.928, Validation Accuracy:  0.942, Loss:  0.077
Epoch   7 Batch  173/269 - Train Accuracy:  0.934, Validation Accuracy:  0.943, Loss:  0.064
Epoch   7 Batch  174/269 - Train Accuracy:  0.939, Validation Accuracy:  0.934, Loss:  0.068
Epoch   7 Batch  175/269 - Train Accuracy:  0.923, Validation Accuracy:  0.939, Loss:  0.084
Epoch   7 Batch  176/269 - Train Accuracy:  0.918, Validation Accuracy:  0.927, Loss:  0.076
Epoch   7 Batch  177/269 - Train Accuracy:  0.935, Validation Accuracy:  0.929, Loss:  0.064
Epoch   7 Batch  178/269 - Train Accuracy:  0.947, Validation Accuracy:  0.938, Loss:  0.065
Epoch   7 Batch  179/269 - Train Accuracy:  0.922, Validation Accuracy:  0.940, Loss:  0.068
Epoch   7 Batch  180/269 - Train Accuracy:  0.939, Validation Accuracy:  0.942, Loss:  0.066
Epoch   7 Batch  181/269 - Train Accuracy:  0.927, Validation Accuracy:  0.944, Loss:  0.071
Epoch   7 Batch  182/269 - Train Accuracy:  0.929, Validation Accuracy:  0.934, Loss:  0.068
Epoch   7 Batch  183/269 - Train Accuracy:  0.934, Validation Accuracy:  0.935, Loss:  0.059
Epoch   7 Batch  184/269 - Train Accuracy:  0.930, Validation Accuracy:  0.940, Loss:  0.065
Epoch   7 Batch  185/269 - Train Accuracy:  0.937, Validation Accuracy:  0.943, Loss:  0.069
Epoch   7 Batch  186/269 - Train Accuracy:  0.938, Validation Accuracy:  0.939, Loss:  0.066
Epoch   7 Batch  187/269 - Train Accuracy:  0.933, Validation Accuracy:  0.936, Loss:  0.066
Epoch   7 Batch  188/269 - Train Accuracy:  0.925, Validation Accuracy:  0.941, Loss:  0.065
Epoch   7 Batch  189/269 - Train Accuracy:  0.940, Validation Accuracy:  0.937, Loss:  0.064
Epoch   7 Batch  190/269 - Train Accuracy:  0.938, Validation Accuracy:  0.937, Loss:  0.064
Epoch   7 Batch  191/269 - Train Accuracy:  0.922, Validation Accuracy:  0.941, Loss:  0.067
Epoch   7 Batch  192/269 - Train Accuracy:  0.929, Validation Accuracy:  0.937, Loss:  0.070
Epoch   7 Batch  193/269 - Train Accuracy:  0.935, Validation Accuracy:  0.944, Loss:  0.066
Epoch   7 Batch  194/269 - Train Accuracy:  0.922, Validation Accuracy:  0.948, Loss:  0.069
Epoch   7 Batch  195/269 - Train Accuracy:  0.929, Validation Accuracy:  0.939, Loss:  0.065
Epoch   7 Batch  196/269 - Train Accuracy:  0.923, Validation Accuracy:  0.935, Loss:  0.064
Epoch   7 Batch  197/269 - Train Accuracy:  0.921, Validation Accuracy:  0.938, Loss:  0.070
Epoch   7 Batch  198/269 - Train Accuracy:  0.939, Validation Accuracy:  0.941, Loss:  0.070
Epoch   7 Batch  199/269 - Train Accuracy:  0.924, Validation Accuracy:  0.938, Loss:  0.071
Epoch   7 Batch  200/269 - Train Accuracy:  0.936, Validation Accuracy:  0.939, Loss:  0.070
Epoch   7 Batch  201/269 - Train Accuracy:  0.936, Validation Accuracy:  0.936, Loss:  0.068
Epoch   7 Batch  202/269 - Train Accuracy:  0.934, Validation Accuracy:  0.932, Loss:  0.066
Epoch   7 Batch  203/269 - Train Accuracy:  0.929, Validation Accuracy:  0.931, Loss:  0.072
Epoch   7 Batch  204/269 - Train Accuracy:  0.935, Validation Accuracy:  0.939, Loss:  0.071
Epoch   7 Batch  205/269 - Train Accuracy:  0.947, Validation Accuracy:  0.944, Loss:  0.061
Epoch   7 Batch  206/269 - Train Accuracy:  0.930, Validation Accuracy:  0.939, Loss:  0.071
Epoch   7 Batch  207/269 - Train Accuracy:  0.934, Validation Accuracy:  0.940, Loss:  0.068
Epoch   7 Batch  208/269 - Train Accuracy:  0.937, Validation Accuracy:  0.938, Loss:  0.069
Epoch   7 Batch  209/269 - Train Accuracy:  0.944, Validation Accuracy:  0.937, Loss:  0.062
Epoch   7 Batch  210/269 - Train Accuracy:  0.941, Validation Accuracy:  0.936, Loss:  0.062
Epoch   7 Batch  211/269 - Train Accuracy:  0.935, Validation Accuracy:  0.938, Loss:  0.069
Epoch   7 Batch  212/269 - Train Accuracy:  0.925, Validation Accuracy:  0.940, Loss:  0.072
Epoch   7 Batch  213/269 - Train Accuracy:  0.920, Validation Accuracy:  0.939, Loss:  0.067
Epoch   7 Batch  214/269 - Train Accuracy:  0.935, Validation Accuracy:  0.937, Loss:  0.067
Epoch   7 Batch  215/269 - Train Accuracy:  0.938, Validation Accuracy:  0.938, Loss:  0.062
Epoch   7 Batch  216/269 - Train Accuracy:  0.918, Validation Accuracy:  0.936, Loss:  0.076
Epoch   7 Batch  217/269 - Train Accuracy:  0.928, Validation Accuracy:  0.936, Loss:  0.068
Epoch   7 Batch  218/269 - Train Accuracy:  0.938, Validation Accuracy:  0.943, Loss:  0.064
Epoch   7 Batch  219/269 - Train Accuracy:  0.935, Validation Accuracy:  0.943, Loss:  0.067
Epoch   7 Batch  220/269 - Train Accuracy:  0.926, Validation Accuracy:  0.939, Loss:  0.063
Epoch   7 Batch  221/269 - Train Accuracy:  0.935, Validation Accuracy:  0.936, Loss:  0.070
Epoch   7 Batch  222/269 - Train Accuracy:  0.952, Validation Accuracy:  0.929, Loss:  0.062
Epoch   7 Batch  223/269 - Train Accuracy:  0.933, Validation Accuracy:  0.928, Loss:  0.063
Epoch   7 Batch  224/269 - Train Accuracy:  0.935, Validation Accuracy:  0.940, Loss:  0.074
Epoch   7 Batch  225/269 - Train Accuracy:  0.923, Validation Accuracy:  0.944, Loss:  0.061
Epoch   7 Batch  226/269 - Train Accuracy:  0.935, Validation Accuracy:  0.938, Loss:  0.069
Epoch   7 Batch  227/269 - Train Accuracy:  0.947, Validation Accuracy:  0.931, Loss:  0.070
Epoch   7 Batch  228/269 - Train Accuracy:  0.931, Validation Accuracy:  0.938, Loss:  0.062
Epoch   7 Batch  229/269 - Train Accuracy:  0.929, Validation Accuracy:  0.945, Loss:  0.065
Epoch   7 Batch  230/269 - Train Accuracy:  0.940, Validation Accuracy:  0.945, Loss:  0.064
Epoch   7 Batch  231/269 - Train Accuracy:  0.927, Validation Accuracy:  0.945, Loss:  0.066
Epoch   7 Batch  232/269 - Train Accuracy:  0.931, Validation Accuracy:  0.943, Loss:  0.065
Epoch   7 Batch  233/269 - Train Accuracy:  0.938, Validation Accuracy:  0.939, Loss:  0.069
Epoch   7 Batch  234/269 - Train Accuracy:  0.938, Validation Accuracy:  0.943, Loss:  0.064
Epoch   7 Batch  235/269 - Train Accuracy:  0.951, Validation Accuracy:  0.934, Loss:  0.058
Epoch   7 Batch  236/269 - Train Accuracy:  0.943, Validation Accuracy:  0.936, Loss:  0.060
Epoch   7 Batch  237/269 - Train Accuracy:  0.937, Validation Accuracy:  0.937, Loss:  0.062
Epoch   7 Batch  238/269 - Train Accuracy:  0.942, Validation Accuracy:  0.940, Loss:  0.064
Epoch   7 Batch  239/269 - Train Accuracy:  0.933, Validation Accuracy:  0.938, Loss:  0.064
Epoch   7 Batch  240/269 - Train Accuracy:  0.943, Validation Accuracy:  0.937, Loss:  0.059
Epoch   7 Batch  241/269 - Train Accuracy:  0.931, Validation Accuracy:  0.936, Loss:  0.074
Epoch   7 Batch  242/269 - Train Accuracy:  0.942, Validation Accuracy:  0.936, Loss:  0.063
Epoch   7 Batch  243/269 - Train Accuracy:  0.942, Validation Accuracy:  0.940, Loss:  0.056
Epoch   7 Batch  244/269 - Train Accuracy:  0.932, Validation Accuracy:  0.942, Loss:  0.067
Epoch   7 Batch  245/269 - Train Accuracy:  0.924, Validation Accuracy:  0.944, Loss:  0.066
Epoch   7 Batch  246/269 - Train Accuracy:  0.932, Validation Accuracy:  0.940, Loss:  0.065
Epoch   7 Batch  247/269 - Train Accuracy:  0.941, Validation Accuracy:  0.939, Loss:  0.062
Epoch   7 Batch  248/269 - Train Accuracy:  0.948, Validation Accuracy:  0.933, Loss:  0.058
Epoch   7 Batch  249/269 - Train Accuracy:  0.939, Validation Accuracy:  0.929, Loss:  0.058
Epoch   7 Batch  250/269 - Train Accuracy:  0.941, Validation Accuracy:  0.942, Loss:  0.064
Epoch   7 Batch  251/269 - Train Accuracy:  0.952, Validation Accuracy:  0.941, Loss:  0.059
Epoch   7 Batch  252/269 - Train Accuracy:  0.955, Validation Accuracy:  0.941, Loss:  0.053
Epoch   7 Batch  253/269 - Train Accuracy:  0.927, Validation Accuracy:  0.940, Loss:  0.067
Epoch   7 Batch  254/269 - Train Accuracy:  0.932, Validation Accuracy:  0.933, Loss:  0.063
Epoch   7 Batch  255/269 - Train Accuracy:  0.933, Validation Accuracy:  0.944, Loss:  0.063
Epoch   7 Batch  256/269 - Train Accuracy:  0.932, Validation Accuracy:  0.942, Loss:  0.060
Epoch   7 Batch  257/269 - Train Accuracy:  0.924, Validation Accuracy:  0.937, Loss:  0.069
Epoch   7 Batch  258/269 - Train Accuracy:  0.933, Validation Accuracy:  0.933, Loss:  0.064
Epoch   7 Batch  259/269 - Train Accuracy:  0.934, Validation Accuracy:  0.932, Loss:  0.062
Epoch   7 Batch  260/269 - Train Accuracy:  0.930, Validation Accuracy:  0.936, Loss:  0.065
Epoch   7 Batch  261/269 - Train Accuracy:  0.942, Validation Accuracy:  0.945, Loss:  0.062
Epoch   7 Batch  262/269 - Train Accuracy:  0.936, Validation Accuracy:  0.943, Loss:  0.063
Epoch   7 Batch  263/269 - Train Accuracy:  0.934, Validation Accuracy:  0.940, Loss:  0.064
Epoch   7 Batch  264/269 - Train Accuracy:  0.918, Validation Accuracy:  0.940, Loss:  0.067
Epoch   7 Batch  265/269 - Train Accuracy:  0.926, Validation Accuracy:  0.939, Loss:  0.064
Epoch   7 Batch  266/269 - Train Accuracy:  0.935, Validation Accuracy:  0.944, Loss:  0.056
Epoch   7 Batch  267/269 - Train Accuracy:  0.945, Validation Accuracy:  0.947, Loss:  0.066
Epoch   8 Batch    0/269 - Train Accuracy:  0.943, Validation Accuracy:  0.949, Loss:  0.068
Epoch   8 Batch    1/269 - Train Accuracy:  0.934, Validation Accuracy:  0.943, Loss:  0.062
Epoch   8 Batch    2/269 - Train Accuracy:  0.939, Validation Accuracy:  0.943, Loss:  0.062
Epoch   8 Batch    3/269 - Train Accuracy:  0.936, Validation Accuracy:  0.944, Loss:  0.062
Epoch   8 Batch    4/269 - Train Accuracy:  0.924, Validation Accuracy:  0.944, Loss:  0.062
Epoch   8 Batch    5/269 - Train Accuracy:  0.951, Validation Accuracy:  0.935, Loss:  0.059
Epoch   8 Batch    6/269 - Train Accuracy:  0.943, Validation Accuracy:  0.930, Loss:  0.056
Epoch   8 Batch    7/269 - Train Accuracy:  0.939, Validation Accuracy:  0.936, Loss:  0.059
Epoch   8 Batch    8/269 - Train Accuracy:  0.943, Validation Accuracy:  0.944, Loss:  0.062
Epoch   8 Batch    9/269 - Train Accuracy:  0.929, Validation Accuracy:  0.939, Loss:  0.066
Epoch   8 Batch   10/269 - Train Accuracy:  0.942, Validation Accuracy:  0.938, Loss:  0.056
Epoch   8 Batch   11/269 - Train Accuracy:  0.938, Validation Accuracy:  0.940, Loss:  0.065
Epoch   8 Batch   12/269 - Train Accuracy:  0.931, Validation Accuracy:  0.936, Loss:  0.066
Epoch   8 Batch   13/269 - Train Accuracy:  0.946, Validation Accuracy:  0.938, Loss:  0.053
Epoch   8 Batch   14/269 - Train Accuracy:  0.935, Validation Accuracy:  0.941, Loss:  0.059
Epoch   8 Batch   15/269 - Train Accuracy:  0.946, Validation Accuracy:  0.941, Loss:  0.051
Epoch   8 Batch   16/269 - Train Accuracy:  0.936, Validation Accuracy:  0.945, Loss:  0.066
Epoch   8 Batch   17/269 - Train Accuracy:  0.943, Validation Accuracy:  0.940, Loss:  0.053
Epoch   8 Batch   18/269 - Train Accuracy:  0.935, Validation Accuracy:  0.934, Loss:  0.062
Epoch   8 Batch   19/269 - Train Accuracy:  0.941, Validation Accuracy:  0.932, Loss:  0.052
Epoch   8 Batch   20/269 - Train Accuracy:  0.948, Validation Accuracy:  0.941, Loss:  0.059
Epoch   8 Batch   21/269 - Train Accuracy:  0.925, Validation Accuracy:  0.945, Loss:  0.067
Epoch   8 Batch   22/269 - Train Accuracy:  0.937, Validation Accuracy:  0.942, Loss:  0.056
Epoch   8 Batch   23/269 - Train Accuracy:  0.932, Validation Accuracy:  0.944, Loss:  0.063
Epoch   8 Batch   24/269 - Train Accuracy:  0.934, Validation Accuracy:  0.944, Loss:  0.061
Epoch   8 Batch   25/269 - Train Accuracy:  0.932, Validation Accuracy:  0.932, Loss:  0.065
Epoch   8 Batch   26/269 - Train Accuracy:  0.930, Validation Accuracy:  0.934, Loss:  0.057
Epoch   8 Batch   27/269 - Train Accuracy:  0.937, Validation Accuracy:  0.944, Loss:  0.057
Epoch   8 Batch   28/269 - Train Accuracy:  0.914, Validation Accuracy:  0.934, Loss:  0.064
Epoch   8 Batch   29/269 - Train Accuracy:  0.931, Validation Accuracy:  0.935, Loss:  0.063
Epoch   8 Batch   30/269 - Train Accuracy:  0.943, Validation Accuracy:  0.936, Loss:  0.060
Epoch   8 Batch   31/269 - Train Accuracy:  0.954, Validation Accuracy:  0.930, Loss:  0.056
Epoch   8 Batch   32/269 - Train Accuracy:  0.941, Validation Accuracy:  0.919, Loss:  0.056
Epoch   8 Batch   33/269 - Train Accuracy:  0.941, Validation Accuracy:  0.936, Loss:  0.055
Epoch   8 Batch   34/269 - Train Accuracy:  0.935, Validation Accuracy:  0.946, Loss:  0.057
Epoch   8 Batch   35/269 - Train Accuracy:  0.934, Validation Accuracy:  0.945, Loss:  0.069
Epoch   8 Batch   36/269 - Train Accuracy:  0.929, Validation Accuracy:  0.940, Loss:  0.061
Epoch   8 Batch   37/269 - Train Accuracy:  0.925, Validation Accuracy:  0.939, Loss:  0.062
Epoch   8 Batch   38/269 - Train Accuracy:  0.934, Validation Accuracy:  0.941, Loss:  0.059
Epoch   8 Batch   39/269 - Train Accuracy:  0.938, Validation Accuracy:  0.942, Loss:  0.057
Epoch   8 Batch   40/269 - Train Accuracy:  0.927, Validation Accuracy:  0.942, Loss:  0.063
Epoch   8 Batch   41/269 - Train Accuracy:  0.929, Validation Accuracy:  0.943, Loss:  0.061
Epoch   8 Batch   42/269 - Train Accuracy:  0.947, Validation Accuracy:  0.945, Loss:  0.053
Epoch   8 Batch   43/269 - Train Accuracy:  0.931, Validation Accuracy:  0.940, Loss:  0.059
Epoch   8 Batch   44/269 - Train Accuracy:  0.940, Validation Accuracy:  0.937, Loss:  0.060
Epoch   8 Batch   45/269 - Train Accuracy:  0.930, Validation Accuracy:  0.941, Loss:  0.060
Epoch   8 Batch   46/269 - Train Accuracy:  0.938, Validation Accuracy:  0.942, Loss:  0.056
Epoch   8 Batch   47/269 - Train Accuracy:  0.946, Validation Accuracy:  0.945, Loss:  0.052
Epoch   8 Batch   48/269 - Train Accuracy:  0.942, Validation Accuracy:  0.947, Loss:  0.055
Epoch   8 Batch   49/269 - Train Accuracy:  0.944, Validation Accuracy:  0.943, Loss:  0.055
Epoch   8 Batch   50/269 - Train Accuracy:  0.925, Validation Accuracy:  0.941, Loss:  0.067
Epoch   8 Batch   51/269 - Train Accuracy:  0.935, Validation Accuracy:  0.942, Loss:  0.056
Epoch   8 Batch   52/269 - Train Accuracy:  0.948, Validation Accuracy:  0.942, Loss:  0.049
Epoch   8 Batch   53/269 - Train Accuracy:  0.940, Validation Accuracy:  0.946, Loss:  0.063
Epoch   8 Batch   54/269 - Train Accuracy:  0.939, Validation Accuracy:  0.946, Loss:  0.055
Epoch   8 Batch   55/269 - Train Accuracy:  0.940, Validation Accuracy:  0.943, Loss:  0.056
Epoch   8 Batch   56/269 - Train Accuracy:  0.926, Validation Accuracy:  0.939, Loss:  0.058
Epoch   8 Batch   57/269 - Train Accuracy:  0.939, Validation Accuracy:  0.936, Loss:  0.063
Epoch   8 Batch   58/269 - Train Accuracy:  0.939, Validation Accuracy:  0.934, Loss:  0.060
Epoch   8 Batch   59/269 - Train Accuracy:  0.953, Validation Accuracy:  0.946, Loss:  0.047
Epoch   8 Batch   60/269 - Train Accuracy:  0.939, Validation Accuracy:  0.946, Loss:  0.055
Epoch   8 Batch   61/269 - Train Accuracy:  0.941, Validation Accuracy:  0.946, Loss:  0.053
Epoch   8 Batch   62/269 - Train Accuracy:  0.928, Validation Accuracy:  0.948, Loss:  0.060
Epoch   8 Batch   63/269 - Train Accuracy:  0.933, Validation Accuracy:  0.946, Loss:  0.064
Epoch   8 Batch   64/269 - Train Accuracy:  0.941, Validation Accuracy:  0.945, Loss:  0.053
Epoch   8 Batch   65/269 - Train Accuracy:  0.930, Validation Accuracy:  0.944, Loss:  0.057
Epoch   8 Batch   66/269 - Train Accuracy:  0.934, Validation Accuracy:  0.942, Loss:  0.058
Epoch   8 Batch   67/269 - Train Accuracy:  0.933, Validation Accuracy:  0.936, Loss:  0.064
Epoch   8 Batch   68/269 - Train Accuracy:  0.940, Validation Accuracy:  0.937, Loss:  0.061
Epoch   8 Batch   69/269 - Train Accuracy:  0.925, Validation Accuracy:  0.933, Loss:  0.068
Epoch   8 Batch   70/269 - Train Accuracy:  0.939, Validation Accuracy:  0.939, Loss:  0.059
Epoch   8 Batch   71/269 - Train Accuracy:  0.944, Validation Accuracy:  0.942, Loss:  0.065
Epoch   8 Batch   72/269 - Train Accuracy:  0.935, Validation Accuracy:  0.944, Loss:  0.065
Epoch   8 Batch   73/269 - Train Accuracy:  0.932, Validation Accuracy:  0.944, Loss:  0.060
Epoch   8 Batch   74/269 - Train Accuracy:  0.948, Validation Accuracy:  0.940, Loss:  0.056
Epoch   8 Batch   75/269 - Train Accuracy:  0.944, Validation Accuracy:  0.938, Loss:  0.059
Epoch   8 Batch   76/269 - Train Accuracy:  0.926, Validation Accuracy:  0.938, Loss:  0.056
Epoch   8 Batch   77/269 - Train Accuracy:  0.942, Validation Accuracy:  0.945, Loss:  0.057
Epoch   8 Batch   78/269 - Train Accuracy:  0.941, Validation Accuracy:  0.945, Loss:  0.057
Epoch   8 Batch   79/269 - Train Accuracy:  0.932, Validation Accuracy:  0.942, Loss:  0.057
Epoch   8 Batch   80/269 - Train Accuracy:  0.940, Validation Accuracy:  0.942, Loss:  0.054
Epoch   8 Batch   81/269 - Train Accuracy:  0.940, Validation Accuracy:  0.934, Loss:  0.064
Epoch   8 Batch   82/269 - Train Accuracy:  0.946, Validation Accuracy:  0.930, Loss:  0.051
Epoch   8 Batch   83/269 - Train Accuracy:  0.925, Validation Accuracy:  0.931, Loss:  0.068
Epoch   8 Batch   84/269 - Train Accuracy:  0.943, Validation Accuracy:  0.941, Loss:  0.056
Epoch   8 Batch   85/269 - Train Accuracy:  0.939, Validation Accuracy:  0.936, Loss:  0.055
Epoch   8 Batch   86/269 - Train Accuracy:  0.945, Validation Accuracy:  0.940, Loss:  0.051
Epoch   8 Batch   87/269 - Train Accuracy:  0.940, Validation Accuracy:  0.934, Loss:  0.062
Epoch   8 Batch   88/269 - Train Accuracy:  0.933, Validation Accuracy:  0.931, Loss:  0.060
Epoch   8 Batch   89/269 - Train Accuracy:  0.945, Validation Accuracy:  0.938, Loss:  0.054
Epoch   8 Batch   90/269 - Train Accuracy:  0.946, Validation Accuracy:  0.951, Loss:  0.058
Epoch   8 Batch   91/269 - Train Accuracy:  0.953, Validation Accuracy:  0.947, Loss:  0.050
Epoch   8 Batch   92/269 - Train Accuracy:  0.953, Validation Accuracy:  0.950, Loss:  0.050
Epoch   8 Batch   93/269 - Train Accuracy:  0.948, Validation Accuracy:  0.941, Loss:  0.053
Epoch   8 Batch   94/269 - Train Accuracy:  0.940, Validation Accuracy:  0.941, Loss:  0.062
Epoch   8 Batch   95/269 - Train Accuracy:  0.942, Validation Accuracy:  0.940, Loss:  0.055
Epoch   8 Batch   96/269 - Train Accuracy:  0.927, Validation Accuracy:  0.945, Loss:  0.058
Epoch   8 Batch   97/269 - Train Accuracy:  0.941, Validation Accuracy:  0.949, Loss:  0.058
Epoch   8 Batch   98/269 - Train Accuracy:  0.940, Validation Accuracy:  0.947, Loss:  0.055
Epoch   8 Batch   99/269 - Train Accuracy:  0.942, Validation Accuracy:  0.946, Loss:  0.057
Epoch   8 Batch  100/269 - Train Accuracy:  0.943, Validation Accuracy:  0.948, Loss:  0.057
Epoch   8 Batch  101/269 - Train Accuracy:  0.940, Validation Accuracy:  0.947, Loss:  0.064
Epoch   8 Batch  102/269 - Train Accuracy:  0.939, Validation Accuracy:  0.949, Loss:  0.054
Epoch   8 Batch  103/269 - Train Accuracy:  0.949, Validation Accuracy:  0.946, Loss:  0.062
Epoch   8 Batch  104/269 - Train Accuracy:  0.939, Validation Accuracy:  0.945, Loss:  0.055
Epoch   8 Batch  105/269 - Train Accuracy:  0.933, Validation Accuracy:  0.948, Loss:  0.056
Epoch   8 Batch  106/269 - Train Accuracy:  0.950, Validation Accuracy:  0.950, Loss:  0.050
Epoch   8 Batch  107/269 - Train Accuracy:  0.946, Validation Accuracy:  0.949, Loss:  0.056
Epoch   8 Batch  108/269 - Train Accuracy:  0.957, Validation Accuracy:  0.950, Loss:  0.055
Epoch   8 Batch  109/269 - Train Accuracy:  0.929, Validation Accuracy:  0.946, Loss:  0.059
Epoch   8 Batch  110/269 - Train Accuracy:  0.942, Validation Accuracy:  0.944, Loss:  0.051
Epoch   8 Batch  111/269 - Train Accuracy:  0.938, Validation Accuracy:  0.942, Loss:  0.058
Epoch   8 Batch  112/269 - Train Accuracy:  0.943, Validation Accuracy:  0.947, Loss:  0.058
Epoch   8 Batch  113/269 - Train Accuracy:  0.932, Validation Accuracy:  0.948, Loss:  0.055
Epoch   8 Batch  114/269 - Train Accuracy:  0.934, Validation Accuracy:  0.948, Loss:  0.056
Epoch   8 Batch  115/269 - Train Accuracy:  0.944, Validation Accuracy:  0.947, Loss:  0.054
Epoch   8 Batch  116/269 - Train Accuracy:  0.952, Validation Accuracy:  0.938, Loss:  0.058
Epoch   8 Batch  117/269 - Train Accuracy:  0.948, Validation Accuracy:  0.939, Loss:  0.050
Epoch   8 Batch  118/269 - Train Accuracy:  0.941, Validation Accuracy:  0.940, Loss:  0.051
Epoch   8 Batch  119/269 - Train Accuracy:  0.929, Validation Accuracy:  0.945, Loss:  0.058
Epoch   8 Batch  120/269 - Train Accuracy:  0.944, Validation Accuracy:  0.945, Loss:  0.056
Epoch   8 Batch  121/269 - Train Accuracy:  0.944, Validation Accuracy:  0.941, Loss:  0.053
Epoch   8 Batch  122/269 - Train Accuracy:  0.944, Validation Accuracy:  0.943, Loss:  0.053
Epoch   8 Batch  123/269 - Train Accuracy:  0.935, Validation Accuracy:  0.938, Loss:  0.052
Epoch   8 Batch  124/269 - Train Accuracy:  0.939, Validation Accuracy:  0.940, Loss:  0.050
Epoch   8 Batch  125/269 - Train Accuracy:  0.946, Validation Accuracy:  0.947, Loss:  0.049
Epoch   8 Batch  126/269 - Train Accuracy:  0.932, Validation Accuracy:  0.945, Loss:  0.054
Epoch   8 Batch  127/269 - Train Accuracy:  0.946, Validation Accuracy:  0.943, Loss:  0.054
Epoch   8 Batch  128/269 - Train Accuracy:  0.944, Validation Accuracy:  0.947, Loss:  0.054
Epoch   8 Batch  129/269 - Train Accuracy:  0.938, Validation Accuracy:  0.940, Loss:  0.053
Epoch   8 Batch  130/269 - Train Accuracy:  0.934, Validation Accuracy:  0.935, Loss:  0.061
Epoch   8 Batch  131/269 - Train Accuracy:  0.932, Validation Accuracy:  0.945, Loss:  0.056
Epoch   8 Batch  132/269 - Train Accuracy:  0.924, Validation Accuracy:  0.948, Loss:  0.059
Epoch   8 Batch  133/269 - Train Accuracy:  0.951, Validation Accuracy:  0.943, Loss:  0.048
Epoch   8 Batch  134/269 - Train Accuracy:  0.929, Validation Accuracy:  0.943, Loss:  0.055
Epoch   8 Batch  135/269 - Train Accuracy:  0.941, Validation Accuracy:  0.944, Loss:  0.056
Epoch   8 Batch  136/269 - Train Accuracy:  0.929, Validation Accuracy:  0.935, Loss:  0.058
Epoch   8 Batch  137/269 - Train Accuracy:  0.930, Validation Accuracy:  0.939, Loss:  0.060
Epoch   8 Batch  138/269 - Train Accuracy:  0.943, Validation Accuracy:  0.949, Loss:  0.050
Epoch   8 Batch  139/269 - Train Accuracy:  0.950, Validation Accuracy:  0.949, Loss:  0.048
Epoch   8 Batch  140/269 - Train Accuracy:  0.945, Validation Accuracy:  0.951, Loss:  0.060
Epoch   8 Batch  141/269 - Train Accuracy:  0.941, Validation Accuracy:  0.949, Loss:  0.056
Epoch   8 Batch  142/269 - Train Accuracy:  0.941, Validation Accuracy:  0.945, Loss:  0.052
Epoch   8 Batch  143/269 - Train Accuracy:  0.950, Validation Accuracy:  0.939, Loss:  0.047
Epoch   8 Batch  144/269 - Train Accuracy:  0.951, Validation Accuracy:  0.943, Loss:  0.044
Epoch   8 Batch  145/269 - Train Accuracy:  0.945, Validation Accuracy:  0.945, Loss:  0.051
Epoch   8 Batch  146/269 - Train Accuracy:  0.941, Validation Accuracy:  0.946, Loss:  0.055
Epoch   8 Batch  147/269 - Train Accuracy:  0.951, Validation Accuracy:  0.942, Loss:  0.056
Epoch   8 Batch  148/269 - Train Accuracy:  0.947, Validation Accuracy:  0.941, Loss:  0.054
Epoch   8 Batch  149/269 - Train Accuracy:  0.935, Validation Accuracy:  0.939, Loss:  0.061
Epoch   8 Batch  150/269 - Train Accuracy:  0.941, Validation Accuracy:  0.946, Loss:  0.055
Epoch   8 Batch  151/269 - Train Accuracy:  0.945, Validation Accuracy:  0.952, Loss:  0.052
Epoch   8 Batch  152/269 - Train Accuracy:  0.941, Validation Accuracy:  0.953, Loss:  0.055
Epoch   8 Batch  153/269 - Train Accuracy:  0.949, Validation Accuracy:  0.950, Loss:  0.053
Epoch   8 Batch  154/269 - Train Accuracy:  0.953, Validation Accuracy:  0.948, Loss:  0.053
Epoch   8 Batch  155/269 - Train Accuracy:  0.937, Validation Accuracy:  0.946, Loss:  0.051
Epoch   8 Batch  156/269 - Train Accuracy:  0.946, Validation Accuracy:  0.949, Loss:  0.053
Epoch   8 Batch  157/269 - Train Accuracy:  0.938, Validation Accuracy:  0.951, Loss:  0.046
Epoch   8 Batch  158/269 - Train Accuracy:  0.938, Validation Accuracy:  0.949, Loss:  0.054
Epoch   8 Batch  159/269 - Train Accuracy:  0.949, Validation Accuracy:  0.950, Loss:  0.054
Epoch   8 Batch  160/269 - Train Accuracy:  0.948, Validation Accuracy:  0.947, Loss:  0.052
Epoch   8 Batch  161/269 - Train Accuracy:  0.945, Validation Accuracy:  0.949, Loss:  0.051
Epoch   8 Batch  162/269 - Train Accuracy:  0.953, Validation Accuracy:  0.949, Loss:  0.051
Epoch   8 Batch  163/269 - Train Accuracy:  0.950, Validation Accuracy:  0.947, Loss:  0.049
Epoch   8 Batch  164/269 - Train Accuracy:  0.953, Validation Accuracy:  0.948, Loss:  0.051
Epoch   8 Batch  165/269 - Train Accuracy:  0.942, Validation Accuracy:  0.946, Loss:  0.050
Epoch   8 Batch  166/269 - Train Accuracy:  0.942, Validation Accuracy:  0.944, Loss:  0.053
Epoch   8 Batch  167/269 - Train Accuracy:  0.944, Validation Accuracy:  0.944, Loss:  0.050
Epoch   8 Batch  168/269 - Train Accuracy:  0.956, Validation Accuracy:  0.947, Loss:  0.052
Epoch   8 Batch  169/269 - Train Accuracy:  0.942, Validation Accuracy:  0.949, Loss:  0.050
Epoch   8 Batch  170/269 - Train Accuracy:  0.940, Validation Accuracy:  0.950, Loss:  0.049
Epoch   8 Batch  171/269 - Train Accuracy:  0.951, Validation Accuracy:  0.950, Loss:  0.052
Epoch   8 Batch  172/269 - Train Accuracy:  0.940, Validation Accuracy:  0.949, Loss:  0.057
Epoch   8 Batch  173/269 - Train Accuracy:  0.946, Validation Accuracy:  0.951, Loss:  0.047
Epoch   8 Batch  174/269 - Train Accuracy:  0.946, Validation Accuracy:  0.950, Loss:  0.052
Epoch   8 Batch  175/269 - Train Accuracy:  0.937, Validation Accuracy:  0.953, Loss:  0.066
Epoch   8 Batch  176/269 - Train Accuracy:  0.929, Validation Accuracy:  0.954, Loss:  0.059
Epoch   8 Batch  177/269 - Train Accuracy:  0.950, Validation Accuracy:  0.952, Loss:  0.048
Epoch   8 Batch  178/269 - Train Accuracy:  0.955, Validation Accuracy:  0.948, Loss:  0.046
Epoch   8 Batch  179/269 - Train Accuracy:  0.930, Validation Accuracy:  0.948, Loss:  0.052
Epoch   8 Batch  180/269 - Train Accuracy:  0.950, Validation Accuracy:  0.953, Loss:  0.051
Epoch   8 Batch  181/269 - Train Accuracy:  0.941, Validation Accuracy:  0.952, Loss:  0.055
Epoch   8 Batch  182/269 - Train Accuracy:  0.940, Validation Accuracy:  0.947, Loss:  0.051
Epoch   8 Batch  183/269 - Train Accuracy:  0.949, Validation Accuracy:  0.948, Loss:  0.043
Epoch   8 Batch  184/269 - Train Accuracy:  0.943, Validation Accuracy:  0.952, Loss:  0.048
Epoch   8 Batch  185/269 - Train Accuracy:  0.952, Validation Accuracy:  0.954, Loss:  0.051
Epoch   8 Batch  186/269 - Train Accuracy:  0.943, Validation Accuracy:  0.953, Loss:  0.048
Epoch   8 Batch  187/269 - Train Accuracy:  0.947, Validation Accuracy:  0.954, Loss:  0.048
Epoch   8 Batch  188/269 - Train Accuracy:  0.941, Validation Accuracy:  0.956, Loss:  0.048
Epoch   8 Batch  189/269 - Train Accuracy:  0.949, Validation Accuracy:  0.954, Loss:  0.048
Epoch   8 Batch  190/269 - Train Accuracy:  0.951, Validation Accuracy:  0.953, Loss:  0.050
Epoch   8 Batch  191/269 - Train Accuracy:  0.936, Validation Accuracy:  0.955, Loss:  0.051
Epoch   8 Batch  192/269 - Train Accuracy:  0.937, Validation Accuracy:  0.957, Loss:  0.054
Epoch   8 Batch  193/269 - Train Accuracy:  0.949, Validation Accuracy:  0.956, Loss:  0.048
Epoch   8 Batch  194/269 - Train Accuracy:  0.940, Validation Accuracy:  0.957, Loss:  0.052
Epoch   8 Batch  195/269 - Train Accuracy:  0.944, Validation Accuracy:  0.953, Loss:  0.048
Epoch   8 Batch  196/269 - Train Accuracy:  0.934, Validation Accuracy:  0.949, Loss:  0.049
Epoch   8 Batch  197/269 - Train Accuracy:  0.934, Validation Accuracy:  0.947, Loss:  0.052
Epoch   8 Batch  198/269 - Train Accuracy:  0.950, Validation Accuracy:  0.955, Loss:  0.052
Epoch   8 Batch  199/269 - Train Accuracy:  0.941, Validation Accuracy:  0.947, Loss:  0.053
Epoch   8 Batch  200/269 - Train Accuracy:  0.946, Validation Accuracy:  0.946, Loss:  0.051
Epoch   8 Batch  201/269 - Train Accuracy:  0.941, Validation Accuracy:  0.946, Loss:  0.053
Epoch   8 Batch  202/269 - Train Accuracy:  0.941, Validation Accuracy:  0.943, Loss:  0.049
Epoch   8 Batch  203/269 - Train Accuracy:  0.938, Validation Accuracy:  0.942, Loss:  0.055
Epoch   8 Batch  204/269 - Train Accuracy:  0.941, Validation Accuracy:  0.948, Loss:  0.053
Epoch   8 Batch  205/269 - Train Accuracy:  0.955, Validation Accuracy:  0.951, Loss:  0.047
Epoch   8 Batch  206/269 - Train Accuracy:  0.941, Validation Accuracy:  0.945, Loss:  0.055
Epoch   8 Batch  207/269 - Train Accuracy:  0.944, Validation Accuracy:  0.949, Loss:  0.050
Epoch   8 Batch  208/269 - Train Accuracy:  0.956, Validation Accuracy:  0.949, Loss:  0.052
Epoch   8 Batch  209/269 - Train Accuracy:  0.953, Validation Accuracy:  0.943, Loss:  0.048
Epoch   8 Batch  210/269 - Train Accuracy:  0.942, Validation Accuracy:  0.942, Loss:  0.048
Epoch   8 Batch  211/269 - Train Accuracy:  0.941, Validation Accuracy:  0.952, Loss:  0.052
Epoch   8 Batch  212/269 - Train Accuracy:  0.942, Validation Accuracy:  0.954, Loss:  0.058
Epoch   8 Batch  213/269 - Train Accuracy:  0.934, Validation Accuracy:  0.952, Loss:  0.050
Epoch   8 Batch  214/269 - Train Accuracy:  0.945, Validation Accuracy:  0.951, Loss:  0.051
Epoch   8 Batch  215/269 - Train Accuracy:  0.948, Validation Accuracy:  0.948, Loss:  0.048
Epoch   8 Batch  216/269 - Train Accuracy:  0.939, Validation Accuracy:  0.948, Loss:  0.059
Epoch   8 Batch  217/269 - Train Accuracy:  0.937, Validation Accuracy:  0.945, Loss:  0.054
Epoch   8 Batch  218/269 - Train Accuracy:  0.951, Validation Accuracy:  0.946, Loss:  0.049
Epoch   8 Batch  219/269 - Train Accuracy:  0.950, Validation Accuracy:  0.951, Loss:  0.052
Epoch   8 Batch  220/269 - Train Accuracy:  0.939, Validation Accuracy:  0.947, Loss:  0.048
Epoch   8 Batch  221/269 - Train Accuracy:  0.935, Validation Accuracy:  0.944, Loss:  0.053
Epoch   8 Batch  222/269 - Train Accuracy:  0.959, Validation Accuracy:  0.944, Loss:  0.046
Epoch   8 Batch  223/269 - Train Accuracy:  0.939, Validation Accuracy:  0.940, Loss:  0.047
Epoch   8 Batch  224/269 - Train Accuracy:  0.943, Validation Accuracy:  0.942, Loss:  0.057
Epoch   8 Batch  225/269 - Train Accuracy:  0.947, Validation Accuracy:  0.949, Loss:  0.045
Epoch   8 Batch  226/269 - Train Accuracy:  0.950, Validation Accuracy:  0.947, Loss:  0.053
Epoch   8 Batch  227/269 - Train Accuracy:  0.953, Validation Accuracy:  0.948, Loss:  0.056
Epoch   8 Batch  228/269 - Train Accuracy:  0.946, Validation Accuracy:  0.946, Loss:  0.047
Epoch   8 Batch  229/269 - Train Accuracy:  0.942, Validation Accuracy:  0.953, Loss:  0.049
Epoch   8 Batch  230/269 - Train Accuracy:  0.954, Validation Accuracy:  0.955, Loss:  0.049
Epoch   8 Batch  231/269 - Train Accuracy:  0.937, Validation Accuracy:  0.956, Loss:  0.050
Epoch   8 Batch  232/269 - Train Accuracy:  0.947, Validation Accuracy:  0.956, Loss:  0.048
Epoch   8 Batch  233/269 - Train Accuracy:  0.952, Validation Accuracy:  0.956, Loss:  0.054
Epoch   8 Batch  234/269 - Train Accuracy:  0.947, Validation Accuracy:  0.954, Loss:  0.047
Epoch   8 Batch  235/269 - Train Accuracy:  0.960, Validation Accuracy:  0.952, Loss:  0.042
Epoch   8 Batch  236/269 - Train Accuracy:  0.953, Validation Accuracy:  0.947, Loss:  0.044
Epoch   8 Batch  237/269 - Train Accuracy:  0.948, Validation Accuracy:  0.947, Loss:  0.048
Epoch   8 Batch  238/269 - Train Accuracy:  0.949, Validation Accuracy:  0.947, Loss:  0.049
Epoch   8 Batch  239/269 - Train Accuracy:  0.947, Validation Accuracy:  0.945, Loss:  0.049
Epoch   8 Batch  240/269 - Train Accuracy:  0.952, Validation Accuracy:  0.950, Loss:  0.045
Epoch   8 Batch  241/269 - Train Accuracy:  0.936, Validation Accuracy:  0.950, Loss:  0.057
Epoch   8 Batch  242/269 - Train Accuracy:  0.951, Validation Accuracy:  0.953, Loss:  0.050
Epoch   8 Batch  243/269 - Train Accuracy:  0.955, Validation Accuracy:  0.952, Loss:  0.041
Epoch   8 Batch  244/269 - Train Accuracy:  0.940, Validation Accuracy:  0.955, Loss:  0.049
Epoch   8 Batch  245/269 - Train Accuracy:  0.947, Validation Accuracy:  0.954, Loss:  0.052
Epoch   8 Batch  246/269 - Train Accuracy:  0.944, Validation Accuracy:  0.947, Loss:  0.051
Epoch   8 Batch  247/269 - Train Accuracy:  0.946, Validation Accuracy:  0.948, Loss:  0.047
Epoch   8 Batch  248/269 - Train Accuracy:  0.957, Validation Accuracy:  0.941, Loss:  0.045
Epoch   8 Batch  249/269 - Train Accuracy:  0.953, Validation Accuracy:  0.947, Loss:  0.043
Epoch   8 Batch  250/269 - Train Accuracy:  0.947, Validation Accuracy:  0.949, Loss:  0.049
Epoch   8 Batch  251/269 - Train Accuracy:  0.957, Validation Accuracy:  0.949, Loss:  0.045
Epoch   8 Batch  252/269 - Train Accuracy:  0.964, Validation Accuracy:  0.948, Loss:  0.040
Epoch   8 Batch  253/269 - Train Accuracy:  0.932, Validation Accuracy:  0.948, Loss:  0.051
Epoch   8 Batch  254/269 - Train Accuracy:  0.948, Validation Accuracy:  0.943, Loss:  0.049
Epoch   8 Batch  255/269 - Train Accuracy:  0.940, Validation Accuracy:  0.949, Loss:  0.049
Epoch   8 Batch  256/269 - Train Accuracy:  0.942, Validation Accuracy:  0.951, Loss:  0.047
Epoch   8 Batch  257/269 - Train Accuracy:  0.936, Validation Accuracy:  0.948, Loss:  0.054
Epoch   8 Batch  258/269 - Train Accuracy:  0.944, Validation Accuracy:  0.944, Loss:  0.048
Epoch   8 Batch  259/269 - Train Accuracy:  0.943, Validation Accuracy:  0.946, Loss:  0.048
Epoch   8 Batch  260/269 - Train Accuracy:  0.945, Validation Accuracy:  0.950, Loss:  0.049
Epoch   8 Batch  261/269 - Train Accuracy:  0.951, Validation Accuracy:  0.953, Loss:  0.047
Epoch   8 Batch  262/269 - Train Accuracy:  0.946, Validation Accuracy:  0.956, Loss:  0.048
Epoch   8 Batch  263/269 - Train Accuracy:  0.947, Validation Accuracy:  0.956, Loss:  0.050
Epoch   8 Batch  264/269 - Train Accuracy:  0.930, Validation Accuracy:  0.956, Loss:  0.051
Epoch   8 Batch  265/269 - Train Accuracy:  0.930, Validation Accuracy:  0.956, Loss:  0.049
Epoch   8 Batch  266/269 - Train Accuracy:  0.947, Validation Accuracy:  0.955, Loss:  0.042
Epoch   8 Batch  267/269 - Train Accuracy:  0.956, Validation Accuracy:  0.951, Loss:  0.052
Epoch   9 Batch    0/269 - Train Accuracy:  0.954, Validation Accuracy:  0.954, Loss:  0.053
Epoch   9 Batch    1/269 - Train Accuracy:  0.950, Validation Accuracy:  0.950, Loss:  0.048
Epoch   9 Batch    2/269 - Train Accuracy:  0.949, Validation Accuracy:  0.952, Loss:  0.047
Epoch   9 Batch    3/269 - Train Accuracy:  0.950, Validation Accuracy:  0.955, Loss:  0.048
Epoch   9 Batch    4/269 - Train Accuracy:  0.931, Validation Accuracy:  0.953, Loss:  0.048
Epoch   9 Batch    5/269 - Train Accuracy:  0.956, Validation Accuracy:  0.952, Loss:  0.046
Epoch   9 Batch    6/269 - Train Accuracy:  0.951, Validation Accuracy:  0.949, Loss:  0.043
Epoch   9 Batch    7/269 - Train Accuracy:  0.943, Validation Accuracy:  0.950, Loss:  0.045
Epoch   9 Batch    8/269 - Train Accuracy:  0.951, Validation Accuracy:  0.949, Loss:  0.051
Epoch   9 Batch    9/269 - Train Accuracy:  0.935, Validation Accuracy:  0.951, Loss:  0.051
Epoch   9 Batch   10/269 - Train Accuracy:  0.955, Validation Accuracy:  0.952, Loss:  0.043
Epoch   9 Batch   11/269 - Train Accuracy:  0.947, Validation Accuracy:  0.950, Loss:  0.051
Epoch   9 Batch   12/269 - Train Accuracy:  0.942, Validation Accuracy:  0.951, Loss:  0.053
Epoch   9 Batch   13/269 - Train Accuracy:  0.954, Validation Accuracy:  0.952, Loss:  0.040
Epoch   9 Batch   14/269 - Train Accuracy:  0.949, Validation Accuracy:  0.954, Loss:  0.045
Epoch   9 Batch   15/269 - Train Accuracy:  0.960, Validation Accuracy:  0.954, Loss:  0.038
Epoch   9 Batch   16/269 - Train Accuracy:  0.949, Validation Accuracy:  0.951, Loss:  0.050
Epoch   9 Batch   17/269 - Train Accuracy:  0.955, Validation Accuracy:  0.953, Loss:  0.041
Epoch   9 Batch   18/269 - Train Accuracy:  0.948, Validation Accuracy:  0.949, Loss:  0.047
Epoch   9 Batch   19/269 - Train Accuracy:  0.951, Validation Accuracy:  0.950, Loss:  0.040
Epoch   9 Batch   20/269 - Train Accuracy:  0.956, Validation Accuracy:  0.952, Loss:  0.045
Epoch   9 Batch   21/269 - Train Accuracy:  0.936, Validation Accuracy:  0.951, Loss:  0.051
Epoch   9 Batch   22/269 - Train Accuracy:  0.949, Validation Accuracy:  0.945, Loss:  0.043
Epoch   9 Batch   23/269 - Train Accuracy:  0.945, Validation Accuracy:  0.948, Loss:  0.048
Epoch   9 Batch   24/269 - Train Accuracy:  0.943, Validation Accuracy:  0.956, Loss:  0.045
Epoch   9 Batch   25/269 - Train Accuracy:  0.942, Validation Accuracy:  0.940, Loss:  0.050
Epoch   9 Batch   26/269 - Train Accuracy:  0.935, Validation Accuracy:  0.940, Loss:  0.044
Epoch   9 Batch   27/269 - Train Accuracy:  0.950, Validation Accuracy:  0.952, Loss:  0.043
Epoch   9 Batch   28/269 - Train Accuracy:  0.933, Validation Accuracy:  0.956, Loss:  0.048
Epoch   9 Batch   29/269 - Train Accuracy:  0.949, Validation Accuracy:  0.950, Loss:  0.047
Epoch   9 Batch   30/269 - Train Accuracy:  0.944, Validation Accuracy:  0.947, Loss:  0.047
Epoch   9 Batch   31/269 - Train Accuracy:  0.962, Validation Accuracy:  0.942, Loss:  0.043
Epoch   9 Batch   32/269 - Train Accuracy:  0.952, Validation Accuracy:  0.937, Loss:  0.043
Epoch   9 Batch   33/269 - Train Accuracy:  0.957, Validation Accuracy:  0.941, Loss:  0.041
Epoch   9 Batch   34/269 - Train Accuracy:  0.946, Validation Accuracy:  0.955, Loss:  0.044
Epoch   9 Batch   35/269 - Train Accuracy:  0.944, Validation Accuracy:  0.952, Loss:  0.054
Epoch   9 Batch   36/269 - Train Accuracy:  0.941, Validation Accuracy:  0.954, Loss:  0.047
Epoch   9 Batch   37/269 - Train Accuracy:  0.936, Validation Accuracy:  0.956, Loss:  0.047
Epoch   9 Batch   38/269 - Train Accuracy:  0.945, Validation Accuracy:  0.959, Loss:  0.045
Epoch   9 Batch   39/269 - Train Accuracy:  0.953, Validation Accuracy:  0.954, Loss:  0.044
Epoch   9 Batch   40/269 - Train Accuracy:  0.939, Validation Accuracy:  0.952, Loss:  0.048
Epoch   9 Batch   41/269 - Train Accuracy:  0.948, Validation Accuracy:  0.953, Loss:  0.048
Epoch   9 Batch   42/269 - Train Accuracy:  0.953, Validation Accuracy:  0.948, Loss:  0.040
Epoch   9 Batch   43/269 - Train Accuracy:  0.947, Validation Accuracy:  0.949, Loss:  0.046
Epoch   9 Batch   44/269 - Train Accuracy:  0.946, Validation Accuracy:  0.949, Loss:  0.047
Epoch   9 Batch   45/269 - Train Accuracy:  0.945, Validation Accuracy:  0.952, Loss:  0.047
Epoch   9 Batch   46/269 - Train Accuracy:  0.942, Validation Accuracy:  0.955, Loss:  0.042
Epoch   9 Batch   47/269 - Train Accuracy:  0.949, Validation Accuracy:  0.959, Loss:  0.040
Epoch   9 Batch   48/269 - Train Accuracy:  0.952, Validation Accuracy:  0.958, Loss:  0.042
Epoch   9 Batch   49/269 - Train Accuracy:  0.959, Validation Accuracy:  0.957, Loss:  0.042
Epoch   9 Batch   50/269 - Train Accuracy:  0.937, Validation Accuracy:  0.953, Loss:  0.054
Epoch   9 Batch   51/269 - Train Accuracy:  0.949, Validation Accuracy:  0.951, Loss:  0.044
Epoch   9 Batch   52/269 - Train Accuracy:  0.954, Validation Accuracy:  0.953, Loss:  0.038
Epoch   9 Batch   53/269 - Train Accuracy:  0.948, Validation Accuracy:  0.948, Loss:  0.048
Epoch   9 Batch   54/269 - Train Accuracy:  0.953, Validation Accuracy:  0.954, Loss:  0.043
Epoch   9 Batch   55/269 - Train Accuracy:  0.949, Validation Accuracy:  0.951, Loss:  0.044
Epoch   9 Batch   56/269 - Train Accuracy:  0.940, Validation Accuracy:  0.948, Loss:  0.045
Epoch   9 Batch   57/269 - Train Accuracy:  0.951, Validation Accuracy:  0.949, Loss:  0.051
Epoch   9 Batch   58/269 - Train Accuracy:  0.953, Validation Accuracy:  0.949, Loss:  0.047
Epoch   9 Batch   59/269 - Train Accuracy:  0.962, Validation Accuracy:  0.953, Loss:  0.036
Epoch   9 Batch   60/269 - Train Accuracy:  0.950, Validation Accuracy:  0.955, Loss:  0.042
Epoch   9 Batch   61/269 - Train Accuracy:  0.949, Validation Accuracy:  0.957, Loss:  0.041
Epoch   9 Batch   62/269 - Train Accuracy:  0.938, Validation Accuracy:  0.957, Loss:  0.048
Epoch   9 Batch   63/269 - Train Accuracy:  0.945, Validation Accuracy:  0.954, Loss:  0.052
Epoch   9 Batch   64/269 - Train Accuracy:  0.950, Validation Accuracy:  0.955, Loss:  0.042
Epoch   9 Batch   65/269 - Train Accuracy:  0.945, Validation Accuracy:  0.958, Loss:  0.044
Epoch   9 Batch   66/269 - Train Accuracy:  0.943, Validation Accuracy:  0.952, Loss:  0.046
Epoch   9 Batch   67/269 - Train Accuracy:  0.947, Validation Accuracy:  0.950, Loss:  0.050
Epoch   9 Batch   68/269 - Train Accuracy:  0.946, Validation Accuracy:  0.944, Loss:  0.048
Epoch   9 Batch   69/269 - Train Accuracy:  0.936, Validation Accuracy:  0.940, Loss:  0.055
Epoch   9 Batch   70/269 - Train Accuracy:  0.948, Validation Accuracy:  0.946, Loss:  0.047
Epoch   9 Batch   71/269 - Train Accuracy:  0.954, Validation Accuracy:  0.951, Loss:  0.052
Epoch   9 Batch   72/269 - Train Accuracy:  0.946, Validation Accuracy:  0.952, Loss:  0.052
Epoch   9 Batch   73/269 - Train Accuracy:  0.943, Validation Accuracy:  0.955, Loss:  0.047
Epoch   9 Batch   74/269 - Train Accuracy:  0.952, Validation Accuracy:  0.952, Loss:  0.044
Epoch   9 Batch   75/269 - Train Accuracy:  0.951, Validation Accuracy:  0.945, Loss:  0.046
Epoch   9 Batch   76/269 - Train Accuracy:  0.945, Validation Accuracy:  0.945, Loss:  0.045
Epoch   9 Batch   77/269 - Train Accuracy:  0.948, Validation Accuracy:  0.953, Loss:  0.045
Epoch   9 Batch   78/269 - Train Accuracy:  0.957, Validation Accuracy:  0.955, Loss:  0.045
Epoch   9 Batch   79/269 - Train Accuracy:  0.935, Validation Accuracy:  0.957, Loss:  0.045
Epoch   9 Batch   80/269 - Train Accuracy:  0.944, Validation Accuracy:  0.957, Loss:  0.043
Epoch   9 Batch   81/269 - Train Accuracy:  0.946, Validation Accuracy:  0.947, Loss:  0.051
Epoch   9 Batch   82/269 - Train Accuracy:  0.956, Validation Accuracy:  0.937, Loss:  0.039
Epoch   9 Batch   83/269 - Train Accuracy:  0.938, Validation Accuracy:  0.946, Loss:  0.055
Epoch   9 Batch   84/269 - Train Accuracy:  0.954, Validation Accuracy:  0.954, Loss:  0.045
Epoch   9 Batch   85/269 - Train Accuracy:  0.945, Validation Accuracy:  0.950, Loss:  0.043
Epoch   9 Batch   86/269 - Train Accuracy:  0.954, Validation Accuracy:  0.951, Loss:  0.040
Epoch   9 Batch   87/269 - Train Accuracy:  0.943, Validation Accuracy:  0.948, Loss:  0.049
Epoch   9 Batch   88/269 - Train Accuracy:  0.943, Validation Accuracy:  0.941, Loss:  0.047
Epoch   9 Batch   89/269 - Train Accuracy:  0.947, Validation Accuracy:  0.944, Loss:  0.041
Epoch   9 Batch   90/269 - Train Accuracy:  0.946, Validation Accuracy:  0.952, Loss:  0.046
Epoch   9 Batch   91/269 - Train Accuracy:  0.962, Validation Accuracy:  0.959, Loss:  0.039
Epoch   9 Batch   92/269 - Train Accuracy:  0.954, Validation Accuracy:  0.960, Loss:  0.040
Epoch   9 Batch   93/269 - Train Accuracy:  0.957, Validation Accuracy:  0.955, Loss:  0.043
Epoch   9 Batch   94/269 - Train Accuracy:  0.946, Validation Accuracy:  0.953, Loss:  0.049
Epoch   9 Batch   95/269 - Train Accuracy:  0.949, Validation Accuracy:  0.944, Loss:  0.043
Epoch   9 Batch   96/269 - Train Accuracy:  0.941, Validation Accuracy:  0.944, Loss:  0.047
Epoch   9 Batch   97/269 - Train Accuracy:  0.950, Validation Accuracy:  0.952, Loss:  0.047
Epoch   9 Batch   98/269 - Train Accuracy:  0.947, Validation Accuracy:  0.953, Loss:  0.043
Epoch   9 Batch   99/269 - Train Accuracy:  0.947, Validation Accuracy:  0.953, Loss:  0.043
Epoch   9 Batch  100/269 - Train Accuracy:  0.958, Validation Accuracy:  0.949, Loss:  0.045
Epoch   9 Batch  101/269 - Train Accuracy:  0.943, Validation Accuracy:  0.951, Loss:  0.054
Epoch   9 Batch  102/269 - Train Accuracy:  0.956, Validation Accuracy:  0.947, Loss:  0.042
Epoch   9 Batch  103/269 - Train Accuracy:  0.952, Validation Accuracy:  0.944, Loss:  0.048
Epoch   9 Batch  104/269 - Train Accuracy:  0.953, Validation Accuracy:  0.949, Loss:  0.043
Epoch   9 Batch  105/269 - Train Accuracy:  0.941, Validation Accuracy:  0.951, Loss:  0.044
Epoch   9 Batch  106/269 - Train Accuracy:  0.960, Validation Accuracy:  0.959, Loss:  0.038
Epoch   9 Batch  107/269 - Train Accuracy:  0.952, Validation Accuracy:  0.960, Loss:  0.045
Epoch   9 Batch  108/269 - Train Accuracy:  0.959, Validation Accuracy:  0.958, Loss:  0.044
Epoch   9 Batch  109/269 - Train Accuracy:  0.936, Validation Accuracy:  0.955, Loss:  0.046
Epoch   9 Batch  110/269 - Train Accuracy:  0.953, Validation Accuracy:  0.951, Loss:  0.039
Epoch   9 Batch  111/269 - Train Accuracy:  0.949, Validation Accuracy:  0.953, Loss:  0.045
Epoch   9 Batch  112/269 - Train Accuracy:  0.949, Validation Accuracy:  0.956, Loss:  0.047
Epoch   9 Batch  113/269 - Train Accuracy:  0.944, Validation Accuracy:  0.956, Loss:  0.043
Epoch   9 Batch  114/269 - Train Accuracy:  0.940, Validation Accuracy:  0.956, Loss:  0.045
Epoch   9 Batch  115/269 - Train Accuracy:  0.953, Validation Accuracy:  0.959, Loss:  0.042
Epoch   9 Batch  116/269 - Train Accuracy:  0.958, Validation Accuracy:  0.944, Loss:  0.046
Epoch   9 Batch  117/269 - Train Accuracy:  0.952, Validation Accuracy:  0.945, Loss:  0.039
Epoch   9 Batch  118/269 - Train Accuracy:  0.952, Validation Accuracy:  0.947, Loss:  0.040
Epoch   9 Batch  119/269 - Train Accuracy:  0.941, Validation Accuracy:  0.953, Loss:  0.046
Epoch   9 Batch  120/269 - Train Accuracy:  0.951, Validation Accuracy:  0.954, Loss:  0.045
Epoch   9 Batch  121/269 - Train Accuracy:  0.949, Validation Accuracy:  0.954, Loss:  0.042
Epoch   9 Batch  122/269 - Train Accuracy:  0.952, Validation Accuracy:  0.955, Loss:  0.042
Epoch   9 Batch  123/269 - Train Accuracy:  0.948, Validation Accuracy:  0.950, Loss:  0.041
Epoch   9 Batch  124/269 - Train Accuracy:  0.952, Validation Accuracy:  0.945, Loss:  0.038
Epoch   9 Batch  125/269 - Train Accuracy:  0.960, Validation Accuracy:  0.953, Loss:  0.039
Epoch   9 Batch  126/269 - Train Accuracy:  0.938, Validation Accuracy:  0.956, Loss:  0.043
Epoch   9 Batch  127/269 - Train Accuracy:  0.953, Validation Accuracy:  0.958, Loss:  0.042
Epoch   9 Batch  128/269 - Train Accuracy:  0.950, Validation Accuracy:  0.956, Loss:  0.041
Epoch   9 Batch  129/269 - Train Accuracy:  0.946, Validation Accuracy:  0.952, Loss:  0.042
Epoch   9 Batch  130/269 - Train Accuracy:  0.950, Validation Accuracy:  0.949, Loss:  0.048
Epoch   9 Batch  131/269 - Train Accuracy:  0.944, Validation Accuracy:  0.952, Loss:  0.044
Epoch   9 Batch  132/269 - Train Accuracy:  0.935, Validation Accuracy:  0.957, Loss:  0.047
Epoch   9 Batch  133/269 - Train Accuracy:  0.963, Validation Accuracy:  0.955, Loss:  0.037
Epoch   9 Batch  134/269 - Train Accuracy:  0.941, Validation Accuracy:  0.954, Loss:  0.042
Epoch   9 Batch  135/269 - Train Accuracy:  0.954, Validation Accuracy:  0.952, Loss:  0.044
Epoch   9 Batch  136/269 - Train Accuracy:  0.941, Validation Accuracy:  0.943, Loss:  0.046
Epoch   9 Batch  137/269 - Train Accuracy:  0.940, Validation Accuracy:  0.939, Loss:  0.048
Epoch   9 Batch  138/269 - Train Accuracy:  0.957, Validation Accuracy:  0.942, Loss:  0.040
Epoch   9 Batch  139/269 - Train Accuracy:  0.962, Validation Accuracy:  0.948, Loss:  0.038
Epoch   9 Batch  140/269 - Train Accuracy:  0.952, Validation Accuracy:  0.953, Loss:  0.048
Epoch   9 Batch  141/269 - Train Accuracy:  0.941, Validation Accuracy:  0.954, Loss:  0.044
Epoch   9 Batch  142/269 - Train Accuracy:  0.954, Validation Accuracy:  0.956, Loss:  0.041
Epoch   9 Batch  143/269 - Train Accuracy:  0.955, Validation Accuracy:  0.948, Loss:  0.037
Epoch   9 Batch  144/269 - Train Accuracy:  0.956, Validation Accuracy:  0.946, Loss:  0.034
Epoch   9 Batch  145/269 - Train Accuracy:  0.953, Validation Accuracy:  0.951, Loss:  0.040
Epoch   9 Batch  146/269 - Train Accuracy:  0.950, Validation Accuracy:  0.959, Loss:  0.043
Epoch   9 Batch  147/269 - Train Accuracy:  0.960, Validation Accuracy:  0.961, Loss:  0.046
Epoch   9 Batch  148/269 - Train Accuracy:  0.951, Validation Accuracy:  0.957, Loss:  0.042
Epoch   9 Batch  149/269 - Train Accuracy:  0.937, Validation Accuracy:  0.953, Loss:  0.050
Epoch   9 Batch  150/269 - Train Accuracy:  0.953, Validation Accuracy:  0.952, Loss:  0.044
Epoch   9 Batch  151/269 - Train Accuracy:  0.950, Validation Accuracy:  0.949, Loss:  0.043
Epoch   9 Batch  152/269 - Train Accuracy:  0.946, Validation Accuracy:  0.954, Loss:  0.044
Epoch   9 Batch  153/269 - Train Accuracy:  0.956, Validation Accuracy:  0.957, Loss:  0.041
Epoch   9 Batch  154/269 - Train Accuracy:  0.962, Validation Accuracy:  0.958, Loss:  0.043
Epoch   9 Batch  155/269 - Train Accuracy:  0.947, Validation Accuracy:  0.960, Loss:  0.040
Epoch   9 Batch  156/269 - Train Accuracy:  0.949, Validation Accuracy:  0.960, Loss:  0.042
Epoch   9 Batch  157/269 - Train Accuracy:  0.947, Validation Accuracy:  0.962, Loss:  0.037
Epoch   9 Batch  158/269 - Train Accuracy:  0.949, Validation Accuracy:  0.954, Loss:  0.044
Epoch   9 Batch  159/269 - Train Accuracy:  0.953, Validation Accuracy:  0.954, Loss:  0.043
Epoch   9 Batch  160/269 - Train Accuracy:  0.953, Validation Accuracy:  0.959, Loss:  0.041
Epoch   9 Batch  161/269 - Train Accuracy:  0.954, Validation Accuracy:  0.963, Loss:  0.042
Epoch   9 Batch  162/269 - Train Accuracy:  0.957, Validation Accuracy:  0.962, Loss:  0.041
Epoch   9 Batch  163/269 - Train Accuracy:  0.960, Validation Accuracy:  0.960, Loss:  0.039
Epoch   9 Batch  164/269 - Train Accuracy:  0.962, Validation Accuracy:  0.960, Loss:  0.041
Epoch   9 Batch  165/269 - Train Accuracy:  0.944, Validation Accuracy:  0.953, Loss:  0.040
Epoch   9 Batch  166/269 - Train Accuracy:  0.949, Validation Accuracy:  0.954, Loss:  0.042
Epoch   9 Batch  167/269 - Train Accuracy:  0.950, Validation Accuracy:  0.953, Loss:  0.042
Epoch   9 Batch  168/269 - Train Accuracy:  0.960, Validation Accuracy:  0.956, Loss:  0.042
Epoch   9 Batch  169/269 - Train Accuracy:  0.947, Validation Accuracy:  0.961, Loss:  0.040
Epoch   9 Batch  170/269 - Train Accuracy:  0.952, Validation Accuracy:  0.963, Loss:  0.039
Epoch   9 Batch  171/269 - Train Accuracy:  0.957, Validation Accuracy:  0.959, Loss:  0.042
Epoch   9 Batch  172/269 - Train Accuracy:  0.952, Validation Accuracy:  0.958, Loss:  0.046
Epoch   9 Batch  173/269 - Train Accuracy:  0.951, Validation Accuracy:  0.959, Loss:  0.037
Epoch   9 Batch  174/269 - Train Accuracy:  0.952, Validation Accuracy:  0.956, Loss:  0.041
Epoch   9 Batch  175/269 - Train Accuracy:  0.942, Validation Accuracy:  0.957, Loss:  0.054
Epoch   9 Batch  176/269 - Train Accuracy:  0.933, Validation Accuracy:  0.957, Loss:  0.047
Epoch   9 Batch  177/269 - Train Accuracy:  0.957, Validation Accuracy:  0.958, Loss:  0.038
Epoch   9 Batch  178/269 - Train Accuracy:  0.962, Validation Accuracy:  0.956, Loss:  0.037
Epoch   9 Batch  179/269 - Train Accuracy:  0.937, Validation Accuracy:  0.955, Loss:  0.042
Epoch   9 Batch  180/269 - Train Accuracy:  0.954, Validation Accuracy:  0.958, Loss:  0.040
Epoch   9 Batch  181/269 - Train Accuracy:  0.946, Validation Accuracy:  0.959, Loss:  0.044
Epoch   9 Batch  182/269 - Train Accuracy:  0.949, Validation Accuracy:  0.953, Loss:  0.041
Epoch   9 Batch  183/269 - Train Accuracy:  0.957, Validation Accuracy:  0.953, Loss:  0.034
Epoch   9 Batch  184/269 - Train Accuracy:  0.948, Validation Accuracy:  0.953, Loss:  0.038
Epoch   9 Batch  185/269 - Train Accuracy:  0.957, Validation Accuracy:  0.960, Loss:  0.041
Epoch   9 Batch  186/269 - Train Accuracy:  0.953, Validation Accuracy:  0.958, Loss:  0.038
Epoch   9 Batch  187/269 - Train Accuracy:  0.947, Validation Accuracy:  0.958, Loss:  0.038
Epoch   9 Batch  188/269 - Train Accuracy:  0.952, Validation Accuracy:  0.958, Loss:  0.038
Epoch   9 Batch  189/269 - Train Accuracy:  0.958, Validation Accuracy:  0.960, Loss:  0.038
Epoch   9 Batch  190/269 - Train Accuracy:  0.958, Validation Accuracy:  0.961, Loss:  0.039
Epoch   9 Batch  191/269 - Train Accuracy:  0.941, Validation Accuracy:  0.961, Loss:  0.041
Epoch   9 Batch  192/269 - Train Accuracy:  0.947, Validation Accuracy:  0.962, Loss:  0.043
Epoch   9 Batch  193/269 - Train Accuracy:  0.953, Validation Accuracy:  0.962, Loss:  0.038
Epoch   9 Batch  194/269 - Train Accuracy:  0.947, Validation Accuracy:  0.958, Loss:  0.042
Epoch   9 Batch  195/269 - Train Accuracy:  0.958, Validation Accuracy:  0.961, Loss:  0.038
Epoch   9 Batch  196/269 - Train Accuracy:  0.946, Validation Accuracy:  0.950, Loss:  0.039
Epoch   9 Batch  197/269 - Train Accuracy:  0.942, Validation Accuracy:  0.946, Loss:  0.042
Epoch   9 Batch  198/269 - Train Accuracy:  0.954, Validation Accuracy:  0.957, Loss:  0.043
Epoch   9 Batch  199/269 - Train Accuracy:  0.951, Validation Accuracy:  0.958, Loss:  0.042
Epoch   9 Batch  200/269 - Train Accuracy:  0.953, Validation Accuracy:  0.955, Loss:  0.039
Epoch   9 Batch  201/269 - Train Accuracy:  0.950, Validation Accuracy:  0.957, Loss:  0.043
Epoch   9 Batch  202/269 - Train Accuracy:  0.949, Validation Accuracy:  0.960, Loss:  0.040
Epoch   9 Batch  203/269 - Train Accuracy:  0.945, Validation Accuracy:  0.951, Loss:  0.043
Epoch   9 Batch  204/269 - Train Accuracy:  0.945, Validation Accuracy:  0.954, Loss:  0.043
Epoch   9 Batch  205/269 - Train Accuracy:  0.961, Validation Accuracy:  0.953, Loss:  0.038
Epoch   9 Batch  206/269 - Train Accuracy:  0.950, Validation Accuracy:  0.960, Loss:  0.045
Epoch   9 Batch  207/269 - Train Accuracy:  0.950, Validation Accuracy:  0.959, Loss:  0.040
Epoch   9 Batch  208/269 - Train Accuracy:  0.956, Validation Accuracy:  0.956, Loss:  0.042
Epoch   9 Batch  209/269 - Train Accuracy:  0.953, Validation Accuracy:  0.958, Loss:  0.039
Epoch   9 Batch  210/269 - Train Accuracy:  0.947, Validation Accuracy:  0.955, Loss:  0.038
Epoch   9 Batch  211/269 - Train Accuracy:  0.948, Validation Accuracy:  0.952, Loss:  0.043
Epoch   9 Batch  212/269 - Train Accuracy:  0.951, Validation Accuracy:  0.958, Loss:  0.048
Epoch   9 Batch  213/269 - Train Accuracy:  0.947, Validation Accuracy:  0.962, Loss:  0.041
Epoch   9 Batch  214/269 - Train Accuracy:  0.951, Validation Accuracy:  0.959, Loss:  0.040
Epoch   9 Batch  215/269 - Train Accuracy:  0.951, Validation Accuracy:  0.956, Loss:  0.038
Epoch   9 Batch  216/269 - Train Accuracy:  0.946, Validation Accuracy:  0.960, Loss:  0.050
Epoch   9 Batch  217/269 - Train Accuracy:  0.943, Validation Accuracy:  0.952, Loss:  0.042
Epoch   9 Batch  218/269 - Train Accuracy:  0.955, Validation Accuracy:  0.947, Loss:  0.038
Epoch   9 Batch  219/269 - Train Accuracy:  0.959, Validation Accuracy:  0.949, Loss:  0.040
Epoch   9 Batch  220/269 - Train Accuracy:  0.950, Validation Accuracy:  0.952, Loss:  0.039
Epoch   9 Batch  221/269 - Train Accuracy:  0.948, Validation Accuracy:  0.956, Loss:  0.042
Epoch   9 Batch  222/269 - Train Accuracy:  0.960, Validation Accuracy:  0.957, Loss:  0.037
Epoch   9 Batch  223/269 - Train Accuracy:  0.951, Validation Accuracy:  0.953, Loss:  0.038
Epoch   9 Batch  224/269 - Train Accuracy:  0.951, Validation Accuracy:  0.948, Loss:  0.047
Epoch   9 Batch  225/269 - Train Accuracy:  0.957, Validation Accuracy:  0.945, Loss:  0.036
Epoch   9 Batch  226/269 - Train Accuracy:  0.956, Validation Accuracy:  0.951, Loss:  0.043
Epoch   9 Batch  227/269 - Train Accuracy:  0.959, Validation Accuracy:  0.953, Loss:  0.047
Epoch   9 Batch  228/269 - Train Accuracy:  0.956, Validation Accuracy:  0.957, Loss:  0.037
Epoch   9 Batch  229/269 - Train Accuracy:  0.955, Validation Accuracy:  0.960, Loss:  0.038
Epoch   9 Batch  230/269 - Train Accuracy:  0.959, Validation Accuracy:  0.957, Loss:  0.039
Epoch   9 Batch  231/269 - Train Accuracy:  0.946, Validation Accuracy:  0.959, Loss:  0.041
Epoch   9 Batch  232/269 - Train Accuracy:  0.954, Validation Accuracy:  0.958, Loss:  0.038
Epoch   9 Batch  233/269 - Train Accuracy:  0.963, Validation Accuracy:  0.960, Loss:  0.045
Epoch   9 Batch  234/269 - Train Accuracy:  0.952, Validation Accuracy:  0.958, Loss:  0.037
Epoch   9 Batch  235/269 - Train Accuracy:  0.972, Validation Accuracy:  0.958, Loss:  0.033
Epoch   9 Batch  236/269 - Train Accuracy:  0.961, Validation Accuracy:  0.961, Loss:  0.035
Epoch   9 Batch  237/269 - Train Accuracy:  0.961, Validation Accuracy:  0.960, Loss:  0.038
Epoch   9 Batch  238/269 - Train Accuracy:  0.957, Validation Accuracy:  0.953, Loss:  0.039
Epoch   9 Batch  239/269 - Train Accuracy:  0.949, Validation Accuracy:  0.951, Loss:  0.039
Epoch   9 Batch  240/269 - Train Accuracy:  0.956, Validation Accuracy:  0.954, Loss:  0.037
Epoch   9 Batch  241/269 - Train Accuracy:  0.944, Validation Accuracy:  0.953, Loss:  0.048
Epoch   9 Batch  242/269 - Train Accuracy:  0.962, Validation Accuracy:  0.953, Loss:  0.039
Epoch   9 Batch  243/269 - Train Accuracy:  0.966, Validation Accuracy:  0.955, Loss:  0.034
Epoch   9 Batch  244/269 - Train Accuracy:  0.956, Validation Accuracy:  0.959, Loss:  0.040
Epoch   9 Batch  245/269 - Train Accuracy:  0.953, Validation Accuracy:  0.959, Loss:  0.041
Epoch   9 Batch  246/269 - Train Accuracy:  0.943, Validation Accuracy:  0.956, Loss:  0.042
Epoch   9 Batch  247/269 - Train Accuracy:  0.950, Validation Accuracy:  0.948, Loss:  0.037
Epoch   9 Batch  248/269 - Train Accuracy:  0.965, Validation Accuracy:  0.949, Loss:  0.035
Epoch   9 Batch  249/269 - Train Accuracy:  0.958, Validation Accuracy:  0.948, Loss:  0.035
Epoch   9 Batch  250/269 - Train Accuracy:  0.951, Validation Accuracy:  0.953, Loss:  0.039
Epoch   9 Batch  251/269 - Train Accuracy:  0.966, Validation Accuracy:  0.960, Loss:  0.037
Epoch   9 Batch  252/269 - Train Accuracy:  0.971, Validation Accuracy:  0.954, Loss:  0.032
Epoch   9 Batch  253/269 - Train Accuracy:  0.943, Validation Accuracy:  0.948, Loss:  0.042
Epoch   9 Batch  254/269 - Train Accuracy:  0.953, Validation Accuracy:  0.947, Loss:  0.039
Epoch   9 Batch  255/269 - Train Accuracy:  0.940, Validation Accuracy:  0.951, Loss:  0.041
Epoch   9 Batch  256/269 - Train Accuracy:  0.947, Validation Accuracy:  0.959, Loss:  0.037
Epoch   9 Batch  257/269 - Train Accuracy:  0.941, Validation Accuracy:  0.955, Loss:  0.044
Epoch   9 Batch  258/269 - Train Accuracy:  0.948, Validation Accuracy:  0.956, Loss:  0.040
Epoch   9 Batch  259/269 - Train Accuracy:  0.953, Validation Accuracy:  0.955, Loss:  0.038
Epoch   9 Batch  260/269 - Train Accuracy:  0.955, Validation Accuracy:  0.954, Loss:  0.039
Epoch   9 Batch  261/269 - Train Accuracy:  0.958, Validation Accuracy:  0.956, Loss:  0.037
Epoch   9 Batch  262/269 - Train Accuracy:  0.950, Validation Accuracy:  0.956, Loss:  0.039
Epoch   9 Batch  263/269 - Train Accuracy:  0.954, Validation Accuracy:  0.959, Loss:  0.041
Epoch   9 Batch  264/269 - Train Accuracy:  0.938, Validation Accuracy:  0.961, Loss:  0.043
Epoch   9 Batch  265/269 - Train Accuracy:  0.947, Validation Accuracy:  0.960, Loss:  0.040
Epoch   9 Batch  266/269 - Train Accuracy:  0.956, Validation Accuracy:  0.960, Loss:  0.034
Epoch   9 Batch  267/269 - Train Accuracy:  0.961, Validation Accuracy:  0.962, Loss:  0.043
Model Trained and Saved
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Save-Parameters">Save Parameters<a class="anchor-link" href="#Save-Parameters">&#182;</a></h3><p>Save the <code>batch_size</code> and <code>save_path</code> parameters for inference.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[27]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="c1"># Save parameters for checkpoint</span>
<span class="n">helper</span><span class="o">.</span><span class="n">save_params</span><span class="p">(</span><span class="n">save_path</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Checkpoint">Checkpoint<a class="anchor-link" href="#Checkpoint">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[28]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="kn">import</span> <span class="nn">tensorflow</span> <span class="k">as</span> <span class="nn">tf</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">helper</span>
<span class="kn">import</span> <span class="nn">problem_unittests</span> <span class="k">as</span> <span class="nn">tests</span>

<span class="n">_</span><span class="p">,</span> <span class="p">(</span><span class="n">source_vocab_to_int</span><span class="p">,</span> <span class="n">target_vocab_to_int</span><span class="p">),</span> <span class="p">(</span><span class="n">source_int_to_vocab</span><span class="p">,</span> <span class="n">target_int_to_vocab</span><span class="p">)</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_preprocess</span><span class="p">()</span>
<span class="n">load_path</span> <span class="o">=</span> <span class="n">helper</span><span class="o">.</span><span class="n">load_params</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Sentence-to-Sequence">Sentence to Sequence<a class="anchor-link" href="#Sentence-to-Sequence">&#182;</a></h2><p>To feed a sentence into the model for translation, you first need to preprocess it.  Implement the function <code>sentence_to_seq()</code> to preprocess new sentences.</p>
<ul>
<li>Convert the sentence to lowercase</li>
<li>Convert words into ids using <code>vocab_to_int</code><ul>
<li>Convert words not in the vocabulary, to the <code>&lt;UNK&gt;</code> word id.</li>
</ul>
</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[29]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">sentence_to_seq</span><span class="p">(</span><span class="n">sentence</span><span class="p">,</span> <span class="n">vocab_to_int</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    Convert a sentence to a sequence of ids</span>
<span class="sd">    :param sentence: String</span>
<span class="sd">    :param vocab_to_int: Dictionary to go from the words to an id</span>
<span class="sd">    :return: List of word ids</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">word_ids</span> <span class="o">=</span> <span class="p">[]</span>
    
    <span class="k">for</span> <span class="n">word</span> <span class="ow">in</span> <span class="n">sentence</span><span class="o">.</span><span class="n">lower</span><span class="p">()</span><span class="o">.</span><span class="n">split</span><span class="p">():</span>
        <span class="k">try</span><span class="p">:</span>
            <span class="n">word_ids</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">vocab_to_int</span><span class="p">[</span><span class="n">word</span><span class="p">])</span>
        <span class="k">except</span> <span class="ne">KeyError</span><span class="p">:</span>
            <span class="n">word_ids</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">vocab_to_int</span><span class="p">[</span><span class="s1">&#39;&lt;UNK&gt;&#39;</span><span class="p">])</span>
    <span class="k">return</span> <span class="n">word_ids</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL THAT IS BELOW THIS LINE</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">tests</span><span class="o">.</span><span class="n">test_sentence_to_seq</span><span class="p">(</span><span class="n">sentence_to_seq</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Tests Passed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Translate">Translate<a class="anchor-link" href="#Translate">&#182;</a></h2><p>This will translate <code>translate_sentence</code> from English to French.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[30]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">translate_sentence</span> <span class="o">=</span> <span class="s1">&#39;he saw a old yellow truck .&#39;</span>


<span class="sd">&quot;&quot;&quot;</span>
<span class="sd">DON&#39;T MODIFY ANYTHING IN THIS CELL</span>
<span class="sd">&quot;&quot;&quot;</span>
<span class="n">translate_sentence</span> <span class="o">=</span> <span class="n">sentence_to_seq</span><span class="p">(</span><span class="n">translate_sentence</span><span class="p">,</span> <span class="n">source_vocab_to_int</span><span class="p">)</span>

<span class="n">loaded_graph</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">Graph</span><span class="p">()</span>
<span class="k">with</span> <span class="n">tf</span><span class="o">.</span><span class="n">Session</span><span class="p">(</span><span class="n">graph</span><span class="o">=</span><span class="n">loaded_graph</span><span class="p">)</span> <span class="k">as</span> <span class="n">sess</span><span class="p">:</span>
    <span class="c1"># Load saved model</span>
    <span class="n">loader</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">train</span><span class="o">.</span><span class="n">import_meta_graph</span><span class="p">(</span><span class="n">load_path</span> <span class="o">+</span> <span class="s1">&#39;.meta&#39;</span><span class="p">)</span>
    <span class="n">loader</span><span class="o">.</span><span class="n">restore</span><span class="p">(</span><span class="n">sess</span><span class="p">,</span> <span class="n">load_path</span><span class="p">)</span>

    <span class="n">input_data</span> <span class="o">=</span> <span class="n">loaded_graph</span><span class="o">.</span><span class="n">get_tensor_by_name</span><span class="p">(</span><span class="s1">&#39;input:0&#39;</span><span class="p">)</span>
    <span class="n">logits</span> <span class="o">=</span> <span class="n">loaded_graph</span><span class="o">.</span><span class="n">get_tensor_by_name</span><span class="p">(</span><span class="s1">&#39;logits:0&#39;</span><span class="p">)</span>
    <span class="n">keep_prob</span> <span class="o">=</span> <span class="n">loaded_graph</span><span class="o">.</span><span class="n">get_tensor_by_name</span><span class="p">(</span><span class="s1">&#39;keep_prob:0&#39;</span><span class="p">)</span>

    <span class="n">translate_logits</span> <span class="o">=</span> <span class="n">sess</span><span class="o">.</span><span class="n">run</span><span class="p">(</span><span class="n">logits</span><span class="p">,</span> <span class="p">{</span><span class="n">input_data</span><span class="p">:</span> <span class="p">[</span><span class="n">translate_sentence</span><span class="p">],</span> <span class="n">keep_prob</span><span class="p">:</span> <span class="mf">1.0</span><span class="p">})[</span><span class="mi">0</span><span class="p">]</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Input&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;  Word Ids:      </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">([</span><span class="n">i</span> <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">translate_sentence</span><span class="p">]))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;  English Words: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">([</span><span class="n">source_int_to_vocab</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">translate_sentence</span><span class="p">]))</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Prediction&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;  Word Ids:      </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">([</span><span class="n">i</span> <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">np</span><span class="o">.</span><span class="n">argmax</span><span class="p">(</span><span class="n">translate_logits</span><span class="p">,</span> <span class="mi">1</span><span class="p">)]))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;  French Words: </span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">([</span><span class="n">target_int_to_vocab</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">np</span><span class="o">.</span><span class="n">argmax</span><span class="p">(</span><span class="n">translate_logits</span><span class="p">,</span> <span class="mi">1</span><span class="p">)]))</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>Input
  Word Ids:      [120, 99, 179, 83, 66, 164, 93]
  English Words: [&#39;he&#39;, &#39;saw&#39;, &#39;a&#39;, &#39;old&#39;, &#39;yellow&#39;, &#39;truck&#39;, &#39;.&#39;]

Prediction
  Word Ids:      [100, 337, 112, 283, 53, 210, 1]
  French Words: [&#39;il&#39;, &#39;vu&#39;, &#39;un&#39;, &#39;vieux&#39;, &#39;camion&#39;, &#39;.&#39;, &#39;&lt;EOS&gt;&#39;]
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Imperfect-Translation">Imperfect Translation<a class="anchor-link" href="#Imperfect-Translation">&#182;</a></h2><p>You might notice that some sentences translate better than others.  Since the dataset you're using only has a vocabulary of 227 English words of the thousands that you use, you're only going to see good results using these words.  For this project, you don't need a perfect translation. However, if you want to create a better translation model, you'll need better data.</p>
<p>You can train on the <a href="http://www.statmt.org/wmt10/training-giga-fren.tar">WMT10 French-English corpus</a>.  This dataset has more vocabulary and richer in topics discussed.  However, this will take you days to train, so make sure you've a GPU and the neural network is performing well on dataset we provided.  Just make sure you play with the WMT10 corpus after you've submitted this project.</p>
<h2 id="Submitting-This-Project">Submitting This Project<a class="anchor-link" href="#Submitting-This-Project">&#182;</a></h2><p>When submitting this project, make sure to run all the cells before saving the notebook. Save the notebook file as "dlnd_language_translation.ipynb" and save it as a HTML file under "File" -&gt; "Download as". Include the "helper.py" and "problem_unittests.py" files in your submission.</p>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>