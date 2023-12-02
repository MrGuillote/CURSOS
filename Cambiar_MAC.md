<html><head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0, user-scalable=no">
    <!-- for img-src, we are allowing all the images from http:/https: and data: only as other URI schemes-,
             1. Filesystem: is not being used.
             2. Mediastream is no longer supported by browser.
             3. Blob URL is temporary URL that only exist for original page's lifetime and hence not valid for reading view -->
    <!--
         for default-src, add the url for translation because if they are not added the translation feature would not be available on iOS.
    -->
    <meta http-equiv="Content-Security-Policy" content="
          frame-src https://youtube.com https://www.youtube.com;
          default-src https://*.microsoft.com https://api.cognitive.microsofttranslator.com;
          img-src * data:;
          form-action 'none';
          style-src 'nonce-b570329a-ca68-4a23-98c0-985f195e5cc8';
          base-uri 'none'
          ">
    <meta property="csp-nonce" content="b570329a-ca68-4a23-98c0-985f195e5cc8">
    <!-- place holder for css -->
    <style nonce="">
        :root {
--sepia-color:#F9F5E9;
--sepia_default-link-color:#0072C9;
--sepia_active-link-color:#097DD5;
--light-color:#FCFCFC;
--light_default-link-color:#0075CF;
--light_active-link-color:#0D7FD6;
--light-yellow-color:#eceb8b;
--light-yellow_default-link-color:#0069B9;
--light-yellow_active-link-color:#0075CF;
--lime-color:#b8d686;
--lime_default-link-color:#005699;
--lime_active-link-color:#0063AE;
--light-green-color:#a5da90;
--light-green_default-link-color:#005699;
--light-green_active-link-color:#0063AE;
--light-teal-color:#94e2be;
--light-teal_default-link-color:#005CA3;
--light-teal_active-link-color:#0069B9;
--turquoise-color:#89e1dd;
--turquoise_default-link-color:#005CA3;
--turquoise_active-link-color:#0069B9;
--teal-color:#8ed5de;
--teal_default-link-color:#005699;
--teal_active-link-color:#0063AE;
--sky-blue-color:#a3cfe4;
--sky-blue_default-link-color:#005699;
--sky-blue_active-link-color:#0063AE;
--light-blue-color:#b3caec;
--light-blue_default-link-color:#005699;
--light-blue_active-link-color:#0063AE;
--lavender-color:#d1bfeb;
--lavender_default-link-color:#005393;
--lavender_active-link-color:#0060A9;
--orchid-color:#edb5f3;
--orchid_default-link-color:#005393;
--orchid_active-link-color:#0060A9;
--grey-color:#E6E6E6;
--grey_default-link-color:#0069B9;
--grey_active-link-color:#0075CF;
--pink-color:#f6b6d9;
--pink_default-link-color:#005699;
--pink_active-link-color:#0063AE;
--carnation-color:#fdacc3;
--carnation_default-link-color:#00508E;
--carnation_active-link-color:#005CA3;
--dark-grey-color:#242424;
--dark-grey_default-link-color:#3091DC;
--dark-grey_active-link-color:#1E88D9;
--black-color:#000000;
--black_default-link-color:#0078D4;
--black_active-link-color:#006CBE;
--green-color:#91ffa6;
--green_default-link-color:#0069B9;
--green_active-link-color:#0075CF;
--blue-color:#87faff;
--blue_default-link-color:#0069B9;
--blue_active-link-color:#0075CF;
--yellow-color:#feff5c;
--yellow_default-link-color:#0072C9;
--yellow_active-link-color:#097DD5;
--rose-color:#febaba;
--rose_default-link-color:#005699;
--rose_active-link-color:#0063AE;
--apricot-color:#f1bfa9;
--apricot_default-link-color:#005699;
--apricot_active-link-color:#0063AE;
--light-orange-color:#f0d592;
--light-orange_default-link-color:#0060A9;
--light-orange_active-link-color:#006CBE;
}
 body {
            background-color: var(--sepia-color),
            transition: "background .5s cubic-bezier(0.25,0.10,0.25,1.00)"
        }
    </style>

    <title id="title">Qué es la dirección MAC, cómo cambiarla y riesgos del filtrado MAC</title>
    <base id="content_base" target="_top">
<style id="main_style_sheet">html {
  margin: 0px  !important;
  touch-action: pan-x pan-y;
}
body {
  margin: 0px  !important;
  height: 100vh;
  display: flex;
  overflow-y: hidden;
  flex-direction: column;
}
iframe {
  margin: 0px  !important;
  border: none;
  display: block;
}
#main_container {
  flex: 1;
  display: flex;
  position: relative;
}
#main_container #__reading__mode__toc__root__container__id {
  width: 0px;
}
.__reading__mode__screen_reader_only {
  clip: rect(0 0 0 0);
  width: 1px;
  border: 0;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  position: absolute;
}
@media print {
  .noPrint {
    display: none !important;
  }
}
@media screen {
  .forPrint {
    display: none !important;
  }
}
@viewport {
  width: device-width;
}
.c001 {
  margin-top: 41px;
}
.c002 {
  transition-property: width;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.25,0.10,0.25,1.00);
}
.c003 {
  pointer-events: none;
}
@media print { 
html {
  margin: 0 !important;
  height: 100%;
  padding: 0;
}
body {
  width: 100%;
  height: 100%;
  margin: 0 !important;
  padding: 0 !important;
  position: relative;
  overflow-wrap: break-word;
  transition-property: background, color;
  transition-duration: .8s;
  transition-timing-function: cubic-bezier(0.25,0.10,0.25,1.00);
}
.__reading_mode_caption_container {
  width: 12.555rem;
  margin-left: 1.096rem;
  font-weight: 400;
}
.__reading_mode_caption_container .__reading_mode_collapse_button {
  padding: initial;
  padding-top: 0.219rem;
}
.__reading_mode_image_and_caption_container {
  display: flex;
  margin-top: 1.0964rem;
}
.__reading_mode_image_and_caption_container p, .__reading_mode_image_and_caption_container img {
  margin: 0px !important;
}
.__reading_mode_image_and_caption_container img {
  width: 11.404rem;
  height: auto;
  max-width: 100%;
  max-height: 100%;
  background: white;
}
.__reading_mode_gallery {
  padding: initial;
  list-style: none;
}
.__reading_mode_gallery li {
  text-align: start;
}
.__reading__mode__mainbody {
  margin: 0;
  padding: 0;
}
.__reading__mode__extracted__article__body p, .__reading__mode__extracted__article__body dl {
  padding: 0;
  hyphens: manual;
  margin-top: 1.096rem;
}
.header_container {
  position: relative;
  margin-left: auto;
  margin-right: auto;
}
.contentBody {
  width: auto;
  color: #333333;
  padding-top: 1.973rem !important;
  margin-left: auto;
  padding-left: 2.444rem;
  margin-right: auto;
  padding-right: 2.444rem;
  padding-bottom: 2.444rem;
}
.progress_pages_pending {
  color: #000002;
  margin-left: calc(50% - 10px);
  margin-right: auto;
}
.__reading__mode__bylineentries {
  margin: 0 0 36px 0;
  font-size: .66rem;
}
.__reading__mode__extracted__bylineentry {
  margin: 0;
  padding: 0;
  position: relative;
  line-height: 160%;
}
#metaDivider {
  top: -1px;
  color: #333;
  position: relative;
  font-size: 0.8rem;
}
#source a {
  text-decoration: none;
}
body * {
  margin-block-end: 0;
  margin-inline-end: 0;
  margin-block-start: 0;
  margin-inline-start: 0;
}
blockquote {
  margin: 1.3rem 0;
  padding: 0 2rem 0 1.3rem;
  font-size: 0.9868rem;
  font-style: italic;
}
ol {
  margin: 1rem 2rem 1.3rem 0;
}
ul {
  margin: 1rem 2rem 1.3rem 0;
}
.__reading_mode_collapse_button {
  fill: #0078D4;
  color: #0078D4 !important;
  border: none;
  display: flex;
  font-size: 0.768rem;
  background: transparent;
  align-items: center;
  line-height: 1.25rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI";
  justify-content: center;
}
.__reading_mode_collapse_button .__reading_mode_collapse_button_chevron_up {
  transform: rotate(180deg);
}
.__reading_mode_collapse_button svg {
  width: 1.1rem;
  height: 1.1rem;
  display: flex;
  margin-left: 6px;
  align-items: center;
  margin-right: 6px;
  justify-content: center;
  forced-color-adjust: auto;
}
.__reading_mode_collapse_button:hover {
  fill: #0066B4;
  color: #0066B4 !important;
  cursor: pointer;
  text-decoration: underline;
}
sup {
  line-height: 1;
  font-variant-numeric: lining-nums;
}
td {
  text-align: start;
  vertical-align: top;
}
th {
  text-align: start;
  vertical-align: top;
}
table {
  line-height: 1.3157rem;
  font-variant-numeric: tabular-nums lining-nums;
}
table img {
  width: auto;
  margin: 0px !important;
  display: initial !important;
}
table ol, table ul {
  margin: 0px;
  padding-inline-start: 1rem;
}
table p {
  margin-top: 0px;
  margin-bottom: 0px;
}
.__reading_mode_data_table_class {
  border-spacing: 0px;
  border-collapse: collapse !important;
}
.__reading_mode_data_table_class td:first-child, .__reading_mode_data_table_class th:first-child {
  border-inline-start: 0px;
}
.__reading_mode_data_table_class td:last-child, .__reading_mode_data_table_class th:last-child {
  border-inline-end: 0px;
}
.__reading_mode_data_table_class td, .__reading_mode_data_table_class th {
  border: 1px solid;
  padding: 10px;
}
.__reading_mode_data_table_class table td, .__reading_mode_data_table_class table th {
  border: 0px;
  padding: 0px;
}
.__reading_mode_data_table_class tr:last-child td, .__reading_mode_data_table_class tr:last-child th {
  border-bottom: 0px;
}
.__reading_mode_data_table_class tr:first-child td, .__reading_mode_data_table_class tr:first-child th {
  border-top: 0px;
}
.__reading_mode_wiki_infobox {
  box-sizing: border-box;
  margin-left: 24px;
  margin-right: 24px;
}
.__reading_mode_wiki_infobox th {
  width: 50%;
  border: none !important;
  padding-inline-end: 12px;
}
.__reading_mode_wiki_infobox td {
  width: 50%;
  border: none !important;
  padding-inline-start: 12px;
}
.__reading_mode_wiki_infobox th[colspan], .__reading_mode_wiki_infobox td[colspan], .__reading_mode_wiki_infobox td:first-child {
  padding-inline-end: 0px;
  padding-inline-start: 0px;
}
.__reading_mode_wiki_infobox .__reading_mode_image_section_table_data_parent {
  padding-top: 0px;
  padding-bottom: 0px;
}
.__reading_mode_wiki_infobox .__reading_mode_infobox_header {
  font-weight: bold;
  padding-top: 0px !important;
  padding-bottom: 12px;
}
.__reading_mode_wiki_infobox .__reading_mode_infobox_segment_header {
  padding-top: 32px;
  font-weight: bold;
}
.__reading_mode_wiki_infobox table {
  border-collapse: collapse;
}
.__reading_mode_wiki_infobox table td, .__reading_mode_wiki_infobox tableth {
  padding: 0px;
}
.__reading_mode_table_and_collapse_button_container {
  box-sizing: border-box;
  margin-top: 1.0964rem;
  border-radius: 4px;
}
.__reading_mode_table_and_collapse_button_container .__reading_mode_collapse_button {
  padding-top: 10px !important;
  padding-bottom: 10px !important;
}
.__reading_mode_table_and_collapse_button_container .__reading_mode_table_collapsed_class, .__reading_mode_table_and_collapse_button_container .__reading_mode_table_expanded_table_class {
  box-sizing: border-box;
  border-color: inherit !important;
  border-bottom: 1px solid;
}
.__reading_mode_table_and_collapse_button_container caption {
  padding: 10px;
  border-bottom: 1px solid;
}
div::-webkit-scrollbar {
  height: 12px;
}
div::-webkit-scrollbar-thumb {
  border: 4px solid transparent;
  box-sizing: border-box;
  border-radius: 11px;
  background-clip: padding-box !important;
}
@media (-ms-high-contrast:active) {
  div::-webkit-scrollbar-thumb {
    background: ButtonText;
    forced-color-adjust: none;
  }
}
.__reading_mode_infobox_and_collapse_button_container {
  border-top: 4px solid;
  margin-top: 1.0964rem;
  padding-top: 24px;
  border-left: 1px solid;
  border-right: 1px solid;
  border-bottom: 1px solid;
  margin-bottom: 2.631rem;
  border-radius: 4px;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_collapse_button {
  margin-top: 10px !important;
  margin-left: 24px;
  margin-bottom: 10px !important;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_infobox_image_container {
  gap: 1.3157rem;
  display: flex;
  font-size: 0.8771rem;
  line-height: 1.0964rem;
  margin-bottom: 16px;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_table_collapsed_class {
  border-color: inherit !important;
  border-bottom: 1px solid;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_table_expanded_table_class {
  border-color: inherit !important;
  border-bottom: 1px solid;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_table_expanded_table_class .__reading_mode_infobox_image_container img {
  width: 14.418rem;
  max-width: 14.418rem;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_table_collapsed_class .__reading_mode_infobox_image_container img {
  width: 6.5789rem;
}
.__reading_mode_infobox_and_collapse_button_container .__reading_mode_infobox_image_container img {
  max-width: 6.578rem;
  max-height: 100% !important;
}
button:focus {
  outline: none;
}
button:focus-visible {
  outline: -webkit-focus-ring-color auto 1px;
}
#copyright {
  font-size: 0.8rem;
  margin-top: 2rem;
}
#__reading__mode__content_container {
  position: relative;
  min-height: 100vh;
}
#__reading__mode__sendfeedback {
  width: 100%;
  height: auto;
  bottom: 0px;
  position: absolute;
}
#__reading__mode__feedback__message__id {
  height: 60px;
  display: flex;
  align-items: center;
}
#__reading__mode__feedback__inner__message__id {
  margin: auto ! important;
  display: inline-flex;
  font-size: 14px;
  align-items: center;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI";
}
.__reading__mode__feedback__text {
  margin: auto 8px ! important;
}
.__reading__mode__feedback__button {
  width: 40px;
  border: none;
  margin: auto;
  height: 32px;
  display: flex;
  background: transparent;
  align-items: center;
  border-radius: 2px;
  justify-content: center;
}
.__reading__mode__feedback__button svg {
  display: flex;
  align-items: center;
  justify-content: center;
}
.__reading__mode__feedback__separator {
  height: 0;
  margin: 0;
  border: none;
  box-sizing: content-box;
  transition: all 0.2s ease-in-out;
}
h1 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
h2 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
h3 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
h4 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
h5 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
h6 {
  padding: 0;
  margin-top: 2.192rem;
  font-weight: bold;
  line-height: normal;
}
#mainContentTitle {
  margin-top: 0px !important;
  font-weight: bold;
  margin-bottom: 1.535rem;
}
#subtitle:lang(en) {
  line-height: 1.2;
}
#subtitle {
  margin: 0 0 .4rem 0;
  line-height: 1.2rem;
}
#content_end_mark_icon_id {
  display: none;
}
#content_end_mark_icon_id:before {
  content: "\25FC";
  font-size: 1rem;
  font-style: normal;
  font-family: Segoe MDL2 Assets;
}
#__reading__mode__content_end_mark_container_id {
  margin-bottom: 25px;
}
figure {
  margin: 1rem 0;
  text-align: center;
}
a {
  color: #0072C9;
  text-decoration: none;
}
a:visited {
  color: #0072C9;
  text-decoration: none;
}
a:hover {
  color: #0072C9;
  text-decoration: underline;
}
a:active {
  color: #097DD5;
  text-decoration: underline;
}
#author {
  color: #666666;
}
@media print {
  .__reading_mode_collapse_button {
    display: none !important;
  }
}
.c004 {
  opacity: 0;
  transform: translateY(80px);
}
.c005 {
  margin-top: 41px;
}
.c006 {
  transition-property: opacity, transform;
  transition-duration: .5s;
  transition-timing-function: cubic-bezier(0.25,0.10,0.25,1.00);
}
.c007 {
  display: block;
  min-width: 100px;
  font-size: 0.667rem;
  margin-top: 0.45rem;
  font-style: italic;
  text-align: left;
  line-height: 160%;
  break-before: avoid-column;
}
.c008 {
  height: auto;
  display: block;
  max-width: 100%;
  margin-top: 1.0964rem;
  max-height: 50%;
  break-inside: avoid-column;
}
.c009 {
  width: auto;
  height: auto;
  display: inherit;
}
.c0010 {
  display: none;
}
.c0011 {
  display: block ! important;
}
.c0012 {
  opacity: 0;
  visibility: hidden;
  transition: visibility 300ms, opacity 300ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c0013:focus {
  outline: none;
}
@media screen and (max-width: 42rem) {
  .c0014 {
    screen and (max-width: 42rem);
  }
  .c0015 {
    width: auto;
    padding: 0.667rem;
  }
  .c0016 {
    font-size: 1.667rem;
  }
  .c0017 {
    font-size: 1.333rem;
  }
}
@media screen and (max-width: 801px) {
  .c0014 {
    screen and (max-width: 801px);
  }
  .c0018 {
    background: #faf7ee;
  }
}
 }</style><style data-jss="" data-meta="MSFTFlipper" nonce="">
.c11109 {
  cursor: pointer;
  margin: 0;
  border: none;
  display: inline-flex;
  padding: 0;
  position: relative;
  background: transparent;
  align-items: center;
  justify-content: center;
  width: 32px;
  height: 32px;
  fill: #FFFFFF;
  color: #FFFFFF;
}
.c11109::before {
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  content: '';
  opacity: 0.8;
  position: absolute;
  transition: all 0.1s ease-in-out;
  border-radius: 50%;
  background: #4D4D4D;
  border: 1px solid #8D8D8D;
}
.c11109:active {
}
.c11109:hover {
}
.c11109:focus {
  outline: none;
}
.c11109:focus-visible {
}
.c11109::-moz-focus-inner {
  border: 0;
}
@media (-ms-high-contrast:active) {
  .c11109 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonText;
    -ms-high-contrast-adjust: none;
  }
}
.c11109:focus-visible::before {
  box-shadow: 0 0 0 1px #A7A7A7 inset;
  border: #A7A7A7;
}
.c11109:hover::before {
  background: #5A5A5A;
  border-color: #B4B4B4;
}
.c11109:hover .c11110 {
}
@media (-ms-high-contrast:active) {
  .c11109:hover .c11110 {
    fill: HighlightText !important;
    color: HighlightText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c11109:hover::before {
    background: Highlight;
  }
}
.c11109:active::before {
  background: #545454;
  border-color: #767676;
}
@media (-ms-high-contrast:active) {
  .c11109::before {
    background: Window;
  }
}
.c11110 {
  position: relative;
  transform: none;
  width: 16px;
  height: 16px;
}
.c11111 {
}
.c11112 {
}
</style><style data-jss="" data-meta="Vc" nonce="">
.c11106 {
  width: auto;
  position: absolute;
  height: 40px;
  right: 12px;
  bottom: 16px;
}
.c11107 {
  transform: rotate(270deg);
}
.c11108 {
  transform: rotate(90deg);
}
</style><style data-jss="" data-meta="MSFTFlipper - jssStyleSheet" nonce="">
.c11113 {
  width: 40px;
  height: 40px;
  margin-left: 4px;
  margin-right: 4px;
}
.c11113:focus:enabled {
  outline-style: solid;
  outline-width: 2px;
  outline-color: #A7A7A7;
}
.c11113::before {
  border-color: #FFFFFF;
}
</style><style data-jss="" data-meta="MSFTButton" nonce="">
.c1189 {
  cursor: pointer;
  display: inline-flex;
  overflow: hidden;
  max-width: 374px;
  box-sizing: border-box;
  transition: all 0.1s ease-in-out;
  line-height: 1;
  font-family: inherit;
  align-items: center;
  white-space: nowrap;
  justify-content: center;
  text-decoration: none;
  font-size: 14px;
  min-width: 32px;
  padding: 0 8px;
  height: 32px;
  border: 2px solid transparent;
  border-radius: 2px;
  color: #FFFFFF;
  fill: #FFFFFF;
  background: #4D4D4D;
}
.c1189:hover:enabled, a.c1189:not(.c1196):hover {
  background: #545454;
}
.c1189:active:enabled, a.c1189:not(.c1196):active {
  background: #484848;
}
.c1189:focus {
  outline: none;
}
.c1189:focus-visible {
  border-color: #909090;
}
.c1189:disabled {
}
.c1189::-moz-focus-inner {
  border: 0;
}
@media (-ms-high-contrast:active) {
  .c1189 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonText;
    -ms-high-contrast-adjust: none;
  }
}
a.c1189:not(.c1196) {
}
@media (-ms-high-contrast:active) {
  a.c1189:not(.c1196) {
    fill: LinkText !important;
    color: LinkText !important;
    background: Window;
    border-color: LinkText !important;
  }
}
a.c1189:not(.c1196):not(.c1196):hover {
}
a.c1189:not(.c1196).c1196 {
}
@media (-ms-high-contrast:active) {
  a.c1189:not(.c1196).c1196 {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
    background: ButtonFace !important;
    border-color: GrayText !important;
  }
}
a.c1189:not(.c1196).c1196:hover {
}
@media (-ms-high-contrast:active) {
  a.c1189:not(.c1196).c1196:hover {
    box-shadow: none !important;
  }
}
@media (-ms-high-contrast:active) {
  a.c1189:not(.c1196):not(.c1196):hover {
    background: ButtonFace;
    box-shadow: 0 0 0 1px inset LinkText !important;
  }
}
a.c1189:not(.c1196):not(.c1196):hover .c11100, a.c1189:not(.c1196):not(.c1196):hover .c11101 {
}
@media (-ms-high-contrast:active) {
  a.c1189:not(.c1196):not(.c1196):hover .c11100, a.c1189:not(.c1196):not(.c1196):hover .c11101 {
    fill: LinkText !important;
    color: LinkText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1189:disabled {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
    background: ButtonFace !important;
    border-color: GrayText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1189:focus-visible {
    border-color: ButtonText;
    box-shadow: 0 0 0 1px inset ButtonText;
  }
}
@media (-ms-high-contrast:active) {
  .c1189:hover:enabled, a.c1189:not(.c1196):hover {
    fill: HighlightText;
    color: HighlightText;
    background: Highlight;
  }
}
.c1189:hover:enabled .c11100, .c1189:hover:enabled .c11101, a.c1189:not(.c1196):hover .c11100, a.c1189:not(.c1196):hover .c11101 {
}
@media (-ms-high-contrast:active) {
  .c1189:hover:enabled .c11100, .c1189:hover:enabled .c11101, a.c1189:not(.c1196):hover .c11100, a.c1189:not(.c1196):hover .c11101 {
    fill: HighlightText !important;
    color: HighlightText !important;
  }
}
.c1190 {
  color: #FFFFFF;
  fill: #FFFFFF;
  background: #006CBE;
}
.c1190:hover:enabled, a.c1190:not(.c1196):hover {
  background: #0078D4;
}
.c1190:active:enabled, a.c1190:not(.c1196):active {
  background: #005CA3;
}
.c1190:focus {
  outline: none;
}
.c1190:focus-visible {
  border-color: #909090;
  box-shadow: 0 0 0 2px inset #003B68;
}
.c1190 .c11100, .c1190 .c11101 {
  fill: #FFFFFF;
}
@media (-ms-high-contrast:active) {
  .c1190 {
    fill: HighlightText;
    color: HighlightText;
    background: Highlight;
    border-color: Highlight;
    -ms-high-contrast-adjust: none;
  }
}
a.c1190:not(.c1196) {
}
a.c1190:not(.c1196) .c11100, a.c1190:not(.c1196) .c11101 {
}
@media (-ms-high-contrast:active) {
  a.c1190:not(.c1196) .c11100, a.c1190:not(.c1196) .c11101 {
    fill: LinkText !important;
    color: LinkText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1190:focus-visible {
    border-color: ButtonText !important;
    box-shadow: 0 0 0 2px inset ButtonFace;
  }
}
@media (-ms-high-contrast:active) {
  .c1190:hover:enabled, a.c1190:not(.c1196):hover {
    fill: Highlight;
    color: Highlight;
    background: HighlightText;
    border-color: Highlight;
  }
}
.c1191 {
  background: transparent;
  border: 1px solid #7B7B7B;
  padding: 0 9px;
}
.c1191:hover:enabled, a.c1191:not(.c1196):hover {
  background: transparent;
  border: 1px solid #A2A2A2;
}
.c1191:active:enabled, a.c1191:not(.c1196):active {
  background: transparent;
  border: 1px solid #646464;
}
.c1191:focus {
  outline: none;
}
.c1191:focus-visible {
  box-shadow: 0 0 0 1px #909090 inset;
  border-color: #909090;
}
@media (-ms-high-contrast:active) {
  .c1191 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonText;
    -ms-high-contrast-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1191:focus-visible {
    border-color: ButtonText;
    box-shadow: 0 0 0 1px inset ButtonText;
  }
}
@media (-ms-high-contrast:active) {
  .c1191:hover:enabled, a.c1191:not(.c1196):hover {
    fill: HighlightText;
    color: HighlightText;
    background: Highlight;
  }
}
.c1192 {
  background-color: transparent;
  color: #63ADE5;
  fill: #63ADE5;
}
.c1192:focus {
  outline: none;
}
.c1192:focus-visible {
  box-shadow: none;
  border-color: transparent;
}
.c1192 .c1195::before {
}
.c1192:hover .c1195::before {
  background: #7DBAE9;
}
.c1192:hover.c1196 .c1195::before {
  display: none;
}
.c1192:active .c1195::before {
  background: #52A3E2;
}
.c1192.c1196, .c1192.c1196 .c1195::before {
  background-color: transparent;
}
.c1192:hover:enabled, a.c1192:not(.c1196):hover {
  background-color: transparent;
  color: #7DBAE9;
}
.c1192:active:enabled, a.c1192:not(.c1196):active {
  background-color: transparent;
  color: #52A3E2;
  fill: #52A3E2;
}
@media (-ms-high-contrast:active) {
  .c1192 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonFace;
    -ms-high-contrast-adjust: none;
  }
}
a.c1192:not(.c1196) {
}
a.c1192:not(.c1196):not(.c1196):hover {
}
a.c1192:not(.c1196).c1196 {
}
a.c1192:not(.c1196) .c1195::before {
}
@media (-ms-high-contrast:active) {
  a.c1192:not(.c1196) .c1195::before {
    background: transparent;
  }
}
@media (-ms-high-contrast:active) {
  a.c1192:not(.c1196).c1196 {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
    background: ButtonFace !important;
    border-color: GrayText !important;
  }
}
@media (-ms-high-contrast:active) {
  a.c1192:not(.c1196):not(.c1196):hover {
    fill: LinkText !important;
    color: LinkText !important;
    box-shadow: none !important;
  }
}
a.c1192:not(.c1196):not(.c1196):hover .c1195::before {
}
@media (-ms-high-contrast:active) {
  a.c1192:not(.c1196):not(.c1196):hover .c1195::before {
    background: LinkText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1192:hover:enabled, a.c1192:not(.c1196):hover {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
.c1192:hover:enabled .c11100, .c1192:hover:enabled .c11101, a.c1192:not(.c1196):hover .c11100, a.c1192:not(.c1196):hover .c11101 {
  fill: #7DBAE9;
}
@media (-ms-high-contrast:active) {
  .c1192:hover:enabled .c11100, .c1192:hover:enabled .c11101, a.c1192:not(.c1196):hover .c11100, a.c1192:not(.c1196):hover .c11101 {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1192:hover .c1195::before {
    background: Highlight;
  }
}
@media (-ms-high-contrast:active) {
  .c1192 .c1195::before {
    background: ButtonText;
  }
}
@media (-ms-high-contrast:active) {
  .c1192:focus-visible {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
.c1192:focus-visible .c1195::before {
  background: #FFFFFF;
  height: 2px;
}
@media (-ms-high-contrast:active) {
  .c1192:focus-visible .c1195::before {
    background: Highlight;
  }
}
.c1193 {
  min-width: 74px;
  padding-left: 0;
  border-width: 0;
  padding-right: 0;
  justify-content: flex-start;
  background-color: transparent;
  color: #63ADE5;
  fill: #63ADE5;
}
.c1193:focus {
  outline: none;
}
.c1193:focus-visible {
  box-shadow: none;
  border-color: transparent;
}
.c1193 .c1195::before {
}
.c1193:hover .c1195::before {
  background: #7DBAE9;
}
.c1193:hover.c1196 .c1195::before {
  display: none;
}
.c1193:active .c1195::before {
  background: #52A3E2;
}
.c1193.c1196, .c1193.c1196 .c1195::before {
  background-color: transparent;
}
.c1193:hover:enabled, a.c1193:not(.c1196):hover {
  background-color: transparent;
  color: #7DBAE9;
}
.c1193:active:enabled, a.c1193:not(.c1196):active {
  background-color: transparent;
  color: #52A3E2;
  fill: #52A3E2;
}
@media (-ms-high-contrast:active) {
  .c1193 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonFace;
    -ms-high-contrast-adjust: none;
  }
}
a.c1193:not(.c1196) {
}
a.c1193:not(.c1196):not(.c1196):hover {
}
a.c1193:not(.c1196).c1196 {
}
@media (-ms-high-contrast:active) {
  a.c1193:not(.c1196).c1196 {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
    background: ButtonFace !important;
    border-color: GrayText !important;
  }
}
@media (-ms-high-contrast:active) {
  a.c1193:not(.c1196):not(.c1196):hover {
    fill: LinkText !important;
    color: LinkText !important;
    box-shadow: none !important;
  }
}
a.c1193:not(.c1196):not(.c1196):hover .c1195::before {
}
@media (-ms-high-contrast:active) {
  a.c1193:not(.c1196):not(.c1196):hover .c1195::before {
    background: LinkText !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1193:hover:enabled, a.c1193:not(.c1196):hover {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
.c1193:hover:enabled .c11100, .c1193:hover:enabled .c11101, a.c1193:not(.c1196):hover .c11100, a.c1193:not(.c1196):hover .c11101 {
  fill: #7DBAE9;
}
@media (-ms-high-contrast:active) {
  .c1193:hover:enabled .c11100, .c1193:hover:enabled .c11101, a.c1193:not(.c1196):hover .c11100, a.c1193:not(.c1196):hover .c11101 {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1193:hover .c1195::before {
    background: Highlight;
  }
}
@media (-ms-high-contrast:active) {
  .c1193 .c1195::before {
    background: ButtonText;
  }
}
@media (-ms-high-contrast:active) {
  .c1193:focus-visible {
    fill: Highlight !important;
    color: Highlight !important;
  }
}
.c1193:focus-visible .c1195::before {
  background: #FFFFFF;
  height: 2px;
}
@media (-ms-high-contrast:active) {
  .c1193:focus-visible .c1195::before {
    background: Highlight;
  }
}
.c1194 {
  background: #3B3B3B;
}
.c1194:hover:enabled, a.c1194:not(.c1196):hover {
  background-color: #484848;
}
.c1194:active:enabled, a.c1194:not(.c1196):active {
  background-color: #424242;
}
.c1194:focus {
  outline: none;
}
.c1194:focus-visible {
  border-color: #909090;
}
@media (-ms-high-contrast:active) {
  .c1194 {
    fill: ButtonText;
    color: ButtonText;
    background: ButtonFace;
    border-color: ButtonFace;
    -ms-high-contrast-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1194:focus-visible {
    border-color: ButtonText;
    box-shadow: 0 0 0 1px inset ButtonText;
  }
}
@media (-ms-high-contrast:active) {
  .c1194:hover:enabled, a.c1194:not(.c1196):hover {
    fill: HighlightText;
    color: HighlightText;
    background: Highlight;
  }
}
.c1195 {
  position: relative;
}
.c1195::before {
  width: 100%;
  bottom: -3px;
  content: '';
  display: block;
  position: absolute;
  height: 1px;
  left: 0;
}
.c1195 svg {
}
.c1196 {
  cursor: not-allowed !important;
  opacity: 0.3;
}
@media (-ms-high-contrast:active) {
  .c1196 {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
    background: ButtonFace !important;
    border-color: GrayText !important;
  }
}
.c1196 .c11100, .c1196 .c11101 {
}
@media (-ms-high-contrast:active) {
  .c1196 .c11100, .c1196 .c11101 {
    fill: GrayText !important;
    color: GrayText !important;
    opacity: 1;
  }
}
.c1197 {
  display: flex;
  min-width: 20px;
  min-height: 20px;
  align-items: center;
  justify-content: center;
}
.c1198 {
}
.c1199 {
}
.c11100 {
}
.c11101 {
}
.c11102 {
}
.c11102 .c1198 {
  margin-right: 10px;
}
.c11102 .c1199 {
  margin-left: 10px;
}
</style><style data-jss="" data-meta="dd" nonce="">
.c1187 {
  background-color: #E5E5E5 !important;
}
.c1187:hover:enabled {
  background-color: #E5E5E5 !important;
}
@media (prefers-color-scheme: dark) {
  .c1187 {
    background-color: #4D4D4D !important;
  }
  .c1187:hover:enabled {
    background-color: #4D4D4D !important;
  }
}
@media (-ms-high-contrast:active) {
  .c1187 {
    fill: HighlightText !important;
    color: HighlightText !important;
    background-color: Highlight !important;
  }
  .c1187:hover:enabled {
    fill: HighlightText !important;
    color: HighlightText !important;
    background-color: Highlight !important;
  }
}
.c1188 {
  fill: none;
  position: absolute;
  border-radius: 50%;
  margin-left: -7px;
  direction: ltr;
  border: 1px solid #3B3B3B;
}
.c1188 .redDot {
  r: 2.5;
  cx: 3;
  cy: 3;
  fill: #EB7D7D;
  stroke: #E00404;
}
@media (-ms-high-contrast:active) {
  .c1188 {
    border: 1px solid ButtonFace;
  }
}
@media (prefers-color-scheme: dark) {
  .c1188 .redDot {
    fill: #8D2020;
  }
}
@media (-ms-high-contrast:active) {
  .c1188 .redDot {
    fill: ButtonText;
    stroke: ButtonText;
  }
}
</style><style data-jss="" data-meta="MSFTButton - jssStyleSheet" nonce="">
.c11103 {
  min-width: unset;
  margin-top: 4px;
  margin-bottom: 4px;
}
.c11104 {
  cursor: default;
}
.c11104:disabled {
  cursor: default !important;
}
.c11104 .innerContainer {
  display: flex;
  align-items: center;
  justify-content: center;
}
.c11104 .icon {
  width: 20px;
  height: 20px;
}
.c11104 .label {
  white-space: nowrap;
  font-weight: 400;
  margin-left: 6px;
  direction: ltr;
}
.c11105 {
  cursor: default !important;
}
</style><style data-jss="" data-meta="Toolbar" nonce="">
.c1178 {
  width: 100%;
  display: flex;
  padding: 0 8px;
  position: relative;
  box-sizing: border-box;
  align-items: center;
  justify-content: space-between;
  height: 41px;
  border-bottom: 1px solid #4F4F4F;
  box-shadow: 0px 4.8px 10.8px rgba(0,0,0,0.26), 0px 0px 4.7px rgba(0,0,0,0.22);
}
@media (max-width: 1470px) {
  .c1178 {
    justify-content: unset;
  }
}
@media (-ms-high-contrast:active) {
  .c1178 {
    border: 1px solid WindowText;
    background: Background;
  }
}
.c1179 {
  top: 0;
  position: fixed;
  box-shadow: none;
}
.c1180 {
  display: flex;
  align-items: center;
}
.c1181 {
  width: 100%;
  display: grid;
  align-items: center;
  grid-template-columns: auto 420px;
}
@media (max-width: 1470px) {
  .c1181 {
    grid-template-columns: auto;
  }
}
@media (max-width: 790px) {
  .c1181 {
    display: none;
  }
}
.c1182 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media (max-width: 1470px) {
  .c1182 {
    margin: 0 auto;
  }
}
.c1183 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
}
@media (max-width: 790px) {
  .c1183 {
    display: none;
  }
}
</style><style data-jss="" data-meta="ArrowKeyNavigator(undefined)" nonce="">
.c1144 {
  height: none;
  position: fixed;
  transition: transform .5s cubic-bezier(0.25,0.10,0.25,1.00);
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  padding-right: 4px;
  direction: ltr;
}
.c1145 {
  position: static;
}
.c1146 {
  display: flex;
}
.c1147 {
  display: flex;
}
.c1148 {
  display: flex;
  align-items: center;
}
.c1149 {
  visibility: hidden;
}
.c1150 {
  box-shadow: none;
  border-bottom: 0;
  background-color: transparent !important;
}
.c1151 {
  z-index: 1;
}
.c1152 {
  z-index: 2;
}
.c1153 {
  background-color: #EDEDED;
}
@media (-ms-high-contrast:active) {
  .c1153 {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  .c1153:hover:enabled {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
}
@-webkit-keyframes button_blink {
  0% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  4% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  8% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  12% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  16% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  20% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  100% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
}
@-webkit-keyframes button_blink_high_contrast {
  0% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  4% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  8% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  12% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  16% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  20% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  100% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
}
@-webkit-keyframes pulsating_animation {
  0% {
    r: 0;
    opacity: 100;
    stroke-width: 8;
  }
  30% {
    stroke-width: 8;
  }
  80% {
    opacity: 100;
  }
  91% {
    r: 18.75;
    opacity: 0;
    stroke-width: 0;
  }
  100% {
    r: 18.75;
    opacity: 0;
  }
}
@-webkit-keyframes hide_read_aloud_pulse {
  0% {
    opacity: 100;
  }
  100% {
    opacity: 0;
  }
}
.c1154 {
  z-index: 1;
  animation: hide_read_aloud_pulse 0s ease-in 60s forwards;
  pointer-events: none;
  margin-top: 20px;
  margin-left: -30px;
  margin-right: -18px;
  direction: ltr;
}
.c1155 {
  r: 0;
  cx: 24;
  cy: 24;
  animation: pulsating_animation 1.1s cubic-bezier(0.33, 1, 0.68, 1) 1s 2 forwards, scale 1.1s cubic-bezier(0.33, 1, 0.68, 1) 1s 2 forwards;
  stroke-width: 8;
  stroke-linecap: round;
  animation-delay: 500ms;
  stroke: #0078D4;
}
@media (-ms-high-contrast:active) {
  .c1155 {
    stroke: ButtonText;
  }
}
@media (prefers-color-scheme: dark) {
  .c1155 {
    stroke: #006CBE;
  }
@media (-ms-high-contrast:active) {
  .c1155 {
    stroke: ButtonText;
  }
}
}
.c1156 {
  r: 3;
  cx: 24;
  cy: 24;
  stroke-linecap: round;
  fill: #0078D4;
}
@media (-ms-high-contrast:active) {
  .c1156 {
    fill: ButtonText;
  }
}
@media (prefers-color-scheme: dark) {
  .c1156 {
    fill: #006CBE;
  }
@media (-ms-high-contrast:active) {
  .c1156 {
    fill: ButtonText;
  }
}
}
.c1157 {
  top: 30px;
  right: -50px;
  z-index: 1;
  position: relative;
}
.c1158 {
  color: #ffffff;
  padding: 6px 12px 6px 12px;
  font-size: 14px;
  background: #222222;
  margin-top: 7px;
  white-space: nowrap;
  border-radius: 4px;
}
.c1159 {
  float: right;
  margin-right: 24px;
}
.c1160 {
  overflow: visible;
  background-color: transparent;
}
.c1160 .tooltiptext {
  position: absolute;
  visibility: hidden;
  box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.14);
  color: #2B2B2B;
  background: #FFFFFF;
  font-weight: 400;
  min-width: 156px;
  line-height: 20px;
  border: 2px solid #BEBEBE;
  top: 26px;
  padding: 16px;
  border-radius: 2px;
  right: -10px;
  direction: ltr;
}
.c1160:hover {
}
.c1160:focus {
}
@media (prefers-color-scheme: light) {
  .c1160 {
  }
  .c1160 .tooltiptext {
    color: #262626;
    background: #F7F7F7;
  }
}
@media (prefers-color-scheme: dark) {
  .c1160 {
  }
  .c1160 .tooltiptext {
    color: #FFFFFF;
    background: #3B3B3B;
  }
}
.c1160:focus .tooltiptext {
  visibility: visible;
}
.c1160:hover .tooltiptext {
  visibility: visible;
}
@media (-ms-high-contrast:active) {
  .c1160 .tooltiptext {
    color: WindowText;
    border: 1px solid WindowText;
    background: Window;
    -ms-high-contrast-adjust: none;
  }
}
.c1161 {
  animation: button_blink 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
  animation-delay: 500ms;
}
@media (-ms-high-contrast:active) {
  .c1161 {
    animation: button_blink_high_contrast 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
  }
}
@media (prefers-color-scheme: dark) {
  .c1161 {
    fill: #FFFFFF;
    color: #FFFFFF;
    animation: button_blink_dark 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
    animation-delay: 500ms;
  }
@media (-ms-high-contrast:active) {
  .c1161 {
    animation: button_blink_high_contrast 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
  }
}
}
.c1162 {
  width: 280px;
  z-index: 1;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  max-height: calc(100vh - 60px);
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  background-color: inherit;
  box-shadow: 0px 12.8px 28.8px rgba(0,0,0,0.13), 0px 0px 9.2px rgba(0,0,0,0.11);
  padding-top: 8px;
  padding-bottom: 8px;
  direction: ltr;
}
@media not all and (prefers-reduced-motion: reduce) {
  .c1162 {
    border-radius: 4px;
  }
}
@media (-ms-high-contrast:active) {
  .c1162 {
    border: 1px solid WindowText;
    background-color: Window;
  }
}
.c1162::-webkit-scrollbar {
  width: 4px;
  height: 4px;
}
.c1162::-webkit-scrollbar-track {
  opacity: 0;
}
.c1162::-webkit-scrollbar-thumb {
  border-radius: 2px;
  background: #929292;
}
.c1162::-webkit-scrollbar-thumb:hover {
  background: #ACACAC;
}
.c1162::-webkit-scrollbar-thumb:active {
  background: #9F9F9F;
}
.c1162::-webkit-scrollbar-corner {
  background: none;
}
@media (-ms-high-contrast:active) {
  .c1162::-webkit-scrollbar-thumb:active {
    background: Highlight;
    forced-color-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1162::-webkit-scrollbar-thumb:hover {
    background: Highlight;
    forced-color-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1162::-webkit-scrollbar-thumb {
    background: ButtonText;
    forced-color-adjust: none;
  }
}
.c1163 {
  transform: translateY(-100%);
  box-shadow: none;
}
.c1164 {
  height: 100%;
}
.c1165 {
}
@media not all and (-ms-high-contrast:active) {
  .c1165 {
    fill: #F29900;
  }
@media (prefers-color-scheme: dark) {
  .c1165 {
    fill: #FDD663;
  }
}
}
.c1166 {
}
.c1166 .shouldAnimate {
  opacity: 0;
}
.c1167 {
}
.c1167 .shouldAnimate {
  opacity: 100;
  transition: opacity 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
  transition-delay: 300ms;
}
.c1168 {
}
.c1168 .shouldAnimate {
  opacity: 100;
}
.c1169 {
}
.c1169 .shouldAnimate {
  opacity: 0;
  transition: opacity 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1170 {
}
.c1170 .shouldAnimate {
  transform: translateY(-100%);
}
.c1171 {
}
.c1171 .shouldAnimate {
  transform: translate(0px, 0px);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
  transition-delay: 300ms;
}
.c1172 {
}
.c1172 .shouldAnimate {
  transform: translate(0px, 0px);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1173 {
}
.c1173 .shouldAnimate {
  transform: translate(0px, 0px);
}
.c1174 {
}
.c1174 .shouldAnimate {
  transform: translateY(-100%);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1175 {
}
.c1176 {
  width: unset;
  height: unset;
}
.c1177 {
  width: 1px;
  height: 16px;
  background: #BEBEBE;
  margin-left: 4px;
  margin-right: 4px;
}
@media (-ms-high-contrast:active) {
  .c1177 {
    background-color: ButtonText;
    -ms-high-contrast-adjust: none;
  }
}
@-webkit-keyframes button_blink_dark {
  0% {
    background-color: transparent;
  }
  4% {
    background-color: #006CBE;
  }
  8% {
    background-color: transparent;
  }
  12% {
    background-color: #006CBE;
  }
  16% {
    background-color: transparent;
  }
  20% {
    background-color: #006CBE;
  }
  100% {
    background-color: #006CBE;
  }
}
</style><style data-jss="" data-meta="Toolbar - jssStyleSheet" nonce="">
.c1184 {
  height: none;
  z-index: 2;
  position: fixed;
  transition: transform .5s cubic-bezier(0.25,0.10,0.25,1.00);
  box-shadow: none;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  border-bottom: 0;
  background-color: transparent !important;
  padding-right: 4px;
  direction: ltr;
}
.c1185 {
  display: flex;
}
.c1186 {
  display: flex;
}
</style><style data-jss="" data-meta="kc" nonce="">
.c1142 {
  position: absolute;
  top: 41px;
}
.c1143 {
  position: absolute;
  top: 0px;
}
</style><style data-jss="" data-meta="Toolbar" nonce="">
.c1134 {
  width: 100%;
  display: flex;
  padding: 0 8px;
  position: relative;
  box-sizing: border-box;
  align-items: center;
  justify-content: space-between;
  height: 41px;
  border-bottom: 1px solid #4F4F4F;
  box-shadow: 0px 4.8px 10.8px rgba(0,0,0,0.26), 0px 0px 4.7px rgba(0,0,0,0.22);
}
@media (max-width: 1470px) {
  .c1134 {
    justify-content: unset;
  }
}
@media (-ms-high-contrast:active) {
  .c1134 {
    border: 1px solid WindowText;
    background: Background;
  }
}
.c1135 {
  top: 0;
  position: fixed;
  box-shadow: none;
}
.c1136 {
  display: flex;
  align-items: center;
}
.c1137 {
  width: 100%;
  display: grid;
  align-items: center;
  grid-template-columns: auto 420px;
}
@media (max-width: 1470px) {
  .c1137 {
    grid-template-columns: auto;
  }
}
@media (max-width: 790px) {
  .c1137 {
    display: none;
  }
}
.c1138 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media (max-width: 1470px) {
  .c1138 {
    margin: 0 auto;
  }
}
.c1139 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
}
@media (max-width: 790px) {
  .c1139 {
    display: none;
  }
}
</style><style data-jss="" data-meta="Rc" nonce="">
.c111 {
  height: none;
  position: fixed;
  transition: transform .5s cubic-bezier(0.25,0.10,0.25,1.00);
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  padding-right: 4px;
  direction: ltr;
}
.c112 {
  position: static;
}
.c113 {
  display: flex;
}
.c114 {
  display: flex;
}
.c115 {
  display: flex;
  align-items: center;
}
.c116 {
  visibility: hidden;
}
.c117 {
  box-shadow: none;
  border-bottom: 0;
  background-color: transparent !important;
}
.c118 {
  z-index: 1;
}
.c119 {
  z-index: 2;
}
.c1110 {
  background-color: #EDEDED;
}
@media (-ms-high-contrast:active) {
  .c1110 {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  .c1110:hover:enabled {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
}
@-webkit-keyframes button_blink {
  0% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  4% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  8% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  12% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  16% {
    background-color: transparent;
    color: #2B2B2B;
    fill: #2B2B2B;
  }
  20% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
  100% {
    background-color: #0078D4;
    color: #FFFFFF;
    fill: #FFFFFF;
  }
}
@-webkit-keyframes button_blink_high_contrast {
  0% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  4% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  8% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  12% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  16% {
    fill: ButtonText;
    color: ButtonText;
    background-color: ButtonFace;
  }
  20% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
  100% {
    fill: HighlightText;
    color: HighlightText;
    background-color: Highlight;
  }
}
@-webkit-keyframes pulsating_animation {
  0% {
    r: 0;
    opacity: 100;
    stroke-width: 8;
  }
  30% {
    stroke-width: 8;
  }
  80% {
    opacity: 100;
  }
  91% {
    r: 18.75;
    opacity: 0;
    stroke-width: 0;
  }
  100% {
    r: 18.75;
    opacity: 0;
  }
}
@-webkit-keyframes hide_read_aloud_pulse {
  0% {
    opacity: 100;
  }
  100% {
    opacity: 0;
  }
}
.c1111 {
  z-index: 1;
  animation: hide_read_aloud_pulse 0s ease-in 60s forwards;
  pointer-events: none;
  margin-top: 20px;
  margin-left: -30px;
  margin-right: -18px;
  direction: ltr;
}
.c1112 {
  r: 0;
  cx: 24;
  cy: 24;
  animation: pulsating_animation 1.1s cubic-bezier(0.33, 1, 0.68, 1) 1s 2 forwards, scale 1.1s cubic-bezier(0.33, 1, 0.68, 1) 1s 2 forwards;
  stroke-width: 8;
  stroke-linecap: round;
  animation-delay: 500ms;
  stroke: #0078D4;
}
@media (-ms-high-contrast:active) {
  .c1112 {
    stroke: ButtonText;
  }
}
.c1113 {
  r: 3;
  cx: 24;
  cy: 24;
  stroke-linecap: round;
  fill: #0078D4;
}
@media (-ms-high-contrast:active) {
  .c1113 {
    fill: ButtonText;
  }
}
.c1114 {
  top: 30px;
  right: -50px;
  z-index: 1;
  position: relative;
}
.c1115 {
  color: #ffffff;
  padding: 6px 12px 6px 12px;
  font-size: 14px;
  background: #222222;
  margin-top: 7px;
  white-space: nowrap;
  border-radius: 4px;
}
.c1116 {
  float: right;
  margin-right: 24px;
}
.c1117 {
  overflow: visible;
  background-color: transparent;
}
.c1117 .tooltiptext {
  position: absolute;
  visibility: hidden;
  box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.14);
  color: #2B2B2B;
  background: #FFFFFF;
  font-weight: 400;
  min-width: 156px;
  line-height: 20px;
  border: 2px solid #BEBEBE;
  top: 26px;
  padding: 16px;
  border-radius: 2px;
  right: -10px;
  direction: ltr;
}
.c1117:hover {
}
.c1117:focus {
}
.c1117:focus .tooltiptext {
  visibility: visible;
}
.c1117:hover .tooltiptext {
  visibility: visible;
}
@media (-ms-high-contrast:active) {
  .c1117 .tooltiptext {
    color: WindowText;
    border: 1px solid WindowText;
    background: Window;
    -ms-high-contrast-adjust: none;
  }
}
.c1118 {
  animation: button_blink 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
  animation-delay: 500ms;
}
@media (-ms-high-contrast:active) {
  .c1118 {
    animation: button_blink_high_contrast 10s cubic-bezier(.25,.1,.25,1) 1s alternate;
  }
}
.c1119 {
  width: 280px;
  z-index: 1;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  max-height: calc(100vh - 60px);
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  background-color: inherit;
  box-shadow: 0px 12.8px 28.8px rgba(0,0,0,0.13), 0px 0px 9.2px rgba(0,0,0,0.11);
  padding-top: 8px;
  padding-bottom: 8px;
  direction: ltr;
}
@media not all and (prefers-reduced-motion: reduce) {
  .c1119 {
    border-radius: 4px;
  }
}
@media (-ms-high-contrast:active) {
  .c1119 {
    border: 1px solid WindowText;
    background-color: Window;
  }
}
.c1119::-webkit-scrollbar {
  width: 4px;
  height: 4px;
}
.c1119::-webkit-scrollbar-track {
  opacity: 0;
}
.c1119::-webkit-scrollbar-thumb {
  border-radius: 2px;
  background: #929292;
}
.c1119::-webkit-scrollbar-thumb:hover {
  background: #ACACAC;
}
.c1119::-webkit-scrollbar-thumb:active {
  background: #9F9F9F;
}
.c1119::-webkit-scrollbar-corner {
  background: none;
}
@media (-ms-high-contrast:active) {
  .c1119::-webkit-scrollbar-thumb:active {
    background: Highlight;
    forced-color-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1119::-webkit-scrollbar-thumb:hover {
    background: Highlight;
    forced-color-adjust: none;
  }
}
@media (-ms-high-contrast:active) {
  .c1119::-webkit-scrollbar-thumb {
    background: ButtonText;
    forced-color-adjust: none;
  }
}
.c1120 {
  transform: translateY(-100%);
  box-shadow: none;
}
.c1121 {
  height: 100%;
}
.c1122 {
}
@media not all and (-ms-high-contrast:active) {
  .c1122 {
    fill: #F29900;
  }
@media (prefers-color-scheme: dark) {
  .c1122 {
    fill: #FDD663;
  }
}
}
.c1123 {
}
.c1123 .shouldAnimate {
  opacity: 0;
}
.c1124 {
}
.c1124 .shouldAnimate {
  opacity: 100;
  transition: opacity 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
  transition-delay: 300ms;
}
.c1125 {
}
.c1125 .shouldAnimate {
  opacity: 100;
}
.c1126 {
}
.c1126 .shouldAnimate {
  opacity: 0;
  transition: opacity 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1127 {
}
.c1127 .shouldAnimate {
  transform: translateY(-100%);
}
.c1128 {
}
.c1128 .shouldAnimate {
  transform: translate(0px, 0px);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
  transition-delay: 300ms;
}
.c1129 {
}
.c1129 .shouldAnimate {
  transform: translate(0px, 0px);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1130 {
}
.c1130 .shouldAnimate {
  transform: translate(0px, 0px);
}
.c1131 {
}
.c1131 .shouldAnimate {
  transform: translateY(-100%);
  transition: transform 500ms cubic-bezier(0.25, 0.10, 0.25, 1.00);
}
.c1132 {
}
.c1133 {
  width: unset;
  height: unset;
}
</style><style data-jss="" data-meta="Toolbar - jssStyleSheet" nonce="">
.c1140 {
  height: none;
  z-index: 1;
  position: fixed;
  transition: transform .5s cubic-bezier(0.25,0.10,0.25,1.00);
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI';
  padding-right: 4px;
  direction: ltr;
}
.c1141 {
  position: static;
}
</style></head>

<body class="ms-theme-sepia js-focus-visible">
    <!-- the class name notranslate has to be in sync with MsNoTranslateClass variable from /src/scripts/TranslatorConstants.ts -->
    <div class="notranslate noPrint" id="reading-bar-container"><div style="background-color: rgb(0, 0, 0);"><div class="c1134 c1140 c1135 c1141" style="background-color: rgb(59, 59, 59);"></div></div><div style="background-color: rgb(0, 0, 0);"><div class="c1178 c1184 c1179 shouldAnimate" role="region" aria-label="Barra de herramientas" style="background-color: rgb(59, 59, 59);"><div class="c1181 c1185"></div><div class="c1182"></div><div class="c1183 c1186"><div class="c1148 "><button class="c1189 c11104 c1194 c11103 c1180" id="readAloudButton" data-element-focusable="true"><span class="c1195"><div class="innerContainer"><div aria-hidden="true" class="icon"><svg width="20" height="20" viewBox="0 0 20 20" class="c1176"><path d="M7.5 4c.18 0 .34.1.43.25l.04.08 4 11a.5.5 0 01-.9.42l-.04-.08L9.7 12H5.3l-1.33 3.67a.5.5 0 01-.96-.25l.02-.1 4-11A.5.5 0 017.5 4zm0 1.96L5.67 11h3.66L7.5 5.96zm5.24-3.9l.39.22a9.5 9.5 0 014.84 7.36l.03.31a.5.5 0 01-1 .1l-.03-.32a8.5 8.5 0 00-4.33-6.58l-.38-.21a.5.5 0 01.48-.88zm-1.17 2.68a.5.5 0 01.6-.2l.09.03.12.08a6.5 6.5 0 013.02 4.23l.05.27.04.27a.5.5 0 01-.96.25l-.02-.09-.05-.26a5.5 5.5 0 00-2.37-3.67l-.22-.15-.13-.07a.5.5 0 01-.17-.69z" fill-rule="nonzero"></path></svg></div><div class="label">Lectura en voz alta</div></div></span></button><button class="c1189 c11104 c1194 c11103 c1180" data-element-focusable="true"><span class="c1195"><div class="innerContainer"><div aria-hidden="true" class="icon"><svg width="20" height="20" viewBox="0 0 20 20" class="c1176"><path d="M6 2c.2 0 .4.13.47.32L8.9 8.57v.02l.18.44-.53 1.4-.46-1.17H3.91l-.94 2.42a.5.5 0 11-.94-.36L3.1 8.59l.01-.02 2.43-6.25A.5.5 0 016 2zM4.3 8.26h3.4L6 3.88 4.3 8.26zm8.17-2.94a.5.5 0 00-.94 0L7.15 17H6.5a.5.5 0 000 1h2a.5.5 0 000-1h-.28l1.13-3h5.37l1.15 3h-.37a.5.5 0 100 1h2a.5.5 0 100-1h-.56L12.47 5.32zM14.34 13H9.72L12 6.91 14.34 13z" fill-rule="nonzero"></path></svg></div><div class="label">Preferencias de texto</div></div></span></button><button class="c1189 c11104 c1194 c11103 c1180" id="ReadingPreferences" data-element-focusable="true"><span class="c1195"><div class="innerContainer"><div aria-hidden="true" class="icon"><svg width="20" height="20" viewBox="0 0 20 20" class="c1176"><path d="M2 3.5c0-.28.22-.5.5-.5h15a.5.5 0 010 1h-15a.5.5 0 01-.5-.5z"></path><path d="M2 9.5c0-.28.22-.5.5-.5h15a.5.5 0 010 1h-15a.5.5 0 01-.5-.5z"></path><path d="M2.5 6a.5.5 0 000 1h15a.5.5 0 000-1h-15z"></path><path d="M2 12.5c0-.28.22-.5.5-.5h15a.5.5 0 010 1h-15a.5.5 0 01-.5-.5z"></path><path d="M2.5 15a.5.5 0 000 1h15a.5.5 0 000-1h-15z"></path></svg></div><div class="label">Preferencias de lectura</div></div></span></button><div class="c1177" aria-hidden="true"></div><button class="c1189 c11104 c1194 c11103 c1180 c1187" title="Desanclar barra de herramientas" data-element-focusable="true"><span class="c1195"><div class="innerContainer"><div aria-hidden="true" class="icon"><svg width="20" height="20" viewBox="0 0 20 20" class="c1175 c1176"><path d="M10.6 2.38a1.5 1.5 0 012.43-.44l5.03 5.03c.74.74.52 2-.44 2.43l-4.51 2.05a.5.5 0 00-.27.3l-1.56 4.67a.5.5 0 01-.82.2l-3.19-3.19L3.71 17H3v-.7H3l3.57-3.57-3.18-3.18a.5.5 0 01.2-.83l4.67-1.56a.5.5 0 00.3-.27l2.05-4.5z"></path></svg></div></div></span></button></div></div></div></div></div>
    <div class="notranslate" id="modal-root"><div id="reading_bar_modal"></div></div>
    <div id="full_page_progress_container" class="contentBody" style="display: none;">
        <!-- <progress class="progress_pages_pending full_page_progress_indicator" /> -->
    </div>
    <div class="__reading__mode__screen_reader_only" id="__reading__mode__screen_reader_info" aria-live="assertive" aria-atomic="true" hidden="true">Presiona Alt+Mayús+R para acceder a las herramientas de lector inmersivo</div>
    <!-- Main container containing extracted content -->
    <div id="main_container" class="regionScrollContainer noPrint" dir="ltr">
      <div id="__reading__mode__toc__root__container__id" class=""></div>
      <div id="lineFocusContainer" hidden="true" role="navigation">
          <div id="lineFocusTopOverlayContainer"></div>
          <div id="lineFocusView"></div>
          <div id="lineFocusViewAnimationOverlay"></div>
          <div id="lineFocusBottomOverlayContainer">
              <div id="lineFocusArrowButtonsContainer"><div class="c11106"><div><button id="lineFocusUpButton" class="c11109 c11113 c11111 c11107" title="Anterior" direction="next"><svg viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" class="c11110"><path d="M4.023 15.273L11.29 8 4.023.727l.704-.704L12.71 8l-7.984 7.977-.704-.704z"></path></svg></button><button id="lineFocusDownButton" title="Siguiente" class="c11109 c11113 c11111 c11108" direction="next"><svg viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" class="c11110"><path d="M4.023 15.273L11.29 8 4.023.727l.704-.704L12.71 8l-7.984 7.977-.704-.704z"></path></svg></button></div></div></div>
          </div>
      </div>
      <div class="multicolview noPrint" id="regionContainer">
      </div>
    <iframe id="__rv_dataSource" tabindex="0" allowfullscreen="allowFullscreen" height="100%" width="100%"></iframe></div>
    <div id="pictureDictionaryPopup"></div>
    <div id="print_container" class="forPrint">
    </div>


</body></html>
