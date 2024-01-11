.odometer.odometer-auto-theme,.odometer.odometer-auto-theme .odometer-digit,.odometer.odometer-theme-minimal,.odometer.odometer-theme-minimal .odometer-digit {
    display: inline-block;
    *zoom:1;*display: inline;
    position: relative
}

.odometer.odometer-auto-theme .odometer-digit .odometer-digit-spacer,.odometer.odometer-theme-minimal .odometer-digit .odometer-digit-spacer {
    display: inline-block;
    *zoom:1;*display: inline;
    visibility: hidden
}

.odometer.odometer-auto-theme .odometer-digit .odometer-digit-inner,.odometer.odometer-theme-minimal .odometer-digit .odometer-digit-inner {
    text-align: left;
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    overflow: hidden
}

.odometer.odometer-auto-theme .odometer-digit .odometer-ribbon,.odometer.odometer-theme-minimal .odometer-digit .odometer-ribbon {
    display: block
}

.odometer.odometer-auto-theme .odometer-digit .odometer-ribbon-inner,.odometer.odometer-theme-minimal .odometer-digit .odometer-ribbon-inner {
    display: block;
    -webkit-backface-visibility: hidden;
}

.odometer.odometer-auto-theme .odometer-digit .odometer-value,.odometer.odometer-theme-minimal .odometer-digit .odometer-value {
    display: block;
    transform: translateZ(0)
}

.odometer.odometer-auto-theme .odometer-digit .odometer-value.odometer-last-value,.odometer.odometer-theme-minimal .odometer-digit .odometer-value.odometer-last-value {
    position: absolute
}

.odometer.odometer-auto-theme.odometer-animating-up .odometer-ribbon-inner,.odometer.odometer-theme-minimal.odometer-animating-up .odometer-ribbon-inner {
    transition: transform 3s
}

.odometer.odometer-auto-theme.odometer-animating-down .odometer-ribbon-inner,.odometer.odometer-auto-theme.odometer-animating-up.odometer-animating .odometer-ribbon-inner,.odometer.odometer-theme-minimal.odometer-animating-down .odometer-ribbon-inner,.odometer.odometer-theme-minimal.odometer-animating-up.odometer-animating .odometer-ribbon-inner {
    transform: translate3d(0,-100%,0)
}

.odometer.odometer-auto-theme.odometer-animating-down.odometer-animating .odometer-ribbon-inner,.odometer.odometer-theme-minimal.odometer-animating-down.odometer-animating .odometer-ribbon-inner {
    transform: translateZ(0);
    transition: transform 3s
}

.a11y-skip-link,.a11y-sr-only {
    border: 0;
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px,1px,1px,1px);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px
}

.a11y-skip-link:active,.a11y-skip-link:focus,.a11y-sr-only-focusable:active,.a11y-sr-only-focusable:focus {
    clip: auto;
    height: auto;
    margin: 0;
    overflow: visible;
    width: auto
}

.a11y-skip-link {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    display: block;
    font-weight: 700;
    padding: 20px;
    position: absolute;
    z-index: 9999
}

.a11y-skip-link,[data-whatinput=keyboard] .a11y-skip-link:focus {
    background-color: #0050a2;
    color: #fff
}

.a11y-focuser {
    border: 2px solid #e6ad00;
    border-radius: 4px;
    box-shadow: 0 0 10px 2px #e6ad00;
    pointer-events: none;
    position: absolute;
    visibility: hidden;
    z-index: 9999
}

[data-whatinput=keyboard] .a11y-focuser.-focus {
    transition: height .2s ease,left .2s ease,top .2s ease,width .2s ease;
    visibility: visible
}

[data-scroll=false] .a11y-focuser {
    display: none
}

.content-effectiveness {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #5e717d
}

.content-effectiveness strong {
    font-size: 1.8rem;
    line-height: 2.6rem
}

.content-effectiveness-yesno {
    width: 100%
}

.content-effectiveness-yesno button,.content-effectiveness-yesno input[type=submit] {
    min-width: 0!important;
    width: 100%
}

.content-effectiveness-yesno-text {
    margin-left: 0;
    margin-right: 0;
    text-align: center
}

.content-effectiveness-yesno-buttons {
    margin-left: auto;
    margin-right: auto;
    max-width: 40rem
}

.content-effectiveness-yesno-buttons:after {
    clear: both;
    content: "";
    display: table
}

.content-effectiveness-yesno-buttons li {
    padding-left: 0
}

.content-effectiveness-yesno-buttons li:before {
    display: none
}

.content-effectiveness-yesno-buttons li {
    float: left;
    margin: 0;
    width: 50%
}

.content-effectiveness-yesno-buttons li+li {
    padding-left: 1.8rem
}

.site-footer {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #5e717d
}

.site-footer a {
    color: #5e717d;
    font-weight: 400
}

.site-footer a:focus,.site-footer a:hover {
    background-color: transparent;
    text-decoration: underline
}

.site-footer-nav li {
    margin: 0;
    padding-left: 0
}

.site-footer-nav li:before {
    display: none
}

.site-footer-nav.-language-switcher {
    margin-top: -1.8rem;
    margin-bottom: -1.8rem
}

.site-footer-legal {
    font-size: 1.2rem;
    line-height: 2.4rem
}

.site-footer-legal a {
    padding: 0 .3rem;
    text-decoration: underline
}

.site-footer-social {
    display: flex;
    justify-content: center
}

.site-footer-social:after {
    clear: both;
    content: "";
    display: table
}

.site-footer-social li {
    padding-left: 0
}

.site-footer-social li:before {
    display: none
}

.site-footer-social a {
    display: block;
    line-height: 0;
    padding: 0 1rem .6rem
}

.site-footer-social a:focus img,.site-footer-social a:hover img {
    filter: unset
}

.site-footer-social img {
    height: 24px;
    filter: grayscale(100%) contrast(0) brightness(1.2) sepia(20%) hue-rotate(150deg);
    transition: all .3s ease;
    width: auto
}

.site-footer-social li {
    margin: 0
}

.site-header {
    background-color: #fff;
    box-shadow: 0 0 30px rgba(0,0,0,.2);
    position: relative;
    z-index: 100
}

.site-header-container {
    height: 6rem;
    line-height: 1;
    margin: 0 auto;
    max-width: 110rem;
    padding: 1rem 0 0;
    text-align: center
}

.site-header-logo,[data-mobile=navigation] .site-header-container {
    position: relative;
    z-index: 2
}

.site-header-logo {
    display: inline-block;
    line-height: 0;
    margin: 0;
    vertical-align: middle
}

.site-header-logo a,.site-header-logo span {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    background: none;
    background-size: 10.8rem 4rem;
    display: block;
    height: 4rem;
    transition: none;
    width: 10.8rem;
    text-indent: 0
}

.site-header-logo a:hover,.site-header-logo span:hover,[data-whatinput=keyboard] .site-header-logo a:focus,[data-whatinput=keyboard] .site-header-logo span:focus {
    background-color: transparent
}

.site-nav-toggle-mobile,.site-nav-toggle-search,.site-nav-toggle-search-desktop {
    font-size: 1rem;
    line-height: 2.4rem;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: transparent;
    border: none;
    color: #019fcb;
    font-weight: 700;
    height: 6rem;
    line-height: 1rem;
    margin: 0;
    padding: 2.4rem 0 0;
    position: absolute;
    text-transform: uppercase;
    top: 0;
    width: 6rem
}

.site-nav-toggle-search-desktop {
    width: auto
}

.site-nav-toggle-search {
    border-left: 1px solid #e8ebee;
    right: 0;
    transition: color .2s ease
}

[data-mobile=search] .site-nav-toggle-search {
    color: #39424a
}

.site-nav-toggle-search-icon {
    display: block;
    height: 18px;
    left: 50%;
    margin: -9px 0 0 -9px;
    position: absolute;
    top: 20px;
    width: 18px
}

.site-nav-toggle-search-icon:after,.site-nav-toggle-search-icon:before {
    content: "";
    display: block;
    position: absolute;
    transform-origin: center center;
    transition: all .2s ease-in
}

[data-mobile=search] .site-nav-toggle-search-icon:after,[data-mobile=search] .site-nav-toggle-search-icon:before {
    transition-timing-function: ease-out
}

.site-nav-toggle-search-icon:before {
    border: 2px solid #019fcb;
    border-radius: 50%;
    height: 12px;
    top: 1px;
    left: 1px;
    width: 12px
}

[data-mobile=search] .site-nav-toggle-search-icon:before {
    border-color: #39424a;
    border-radius: 0;
    border-width: 2px 0 0;
    height: 2px;
    left: 50%;
    margin: -1px 0 0 -12px;
    top: 50%;
    transform: rotate(-45deg);
    width: 24px
}

.site-nav-toggle-search-icon:after {
    background-color: #019fcb;
    border-radius: 0 2px 2px 0;
    height: 3px;
    left: 50%;
    margin-top: 3px;
    top: 50%;
    transform: rotate(45deg);
    width: 9px
}

[data-mobile=search] .site-nav-toggle-search-icon:after {
    background-color: #39424a;
    height: 2px;
    margin: -1px 0 0 -12px;
    width: 24px
}

.site-nav-toggle-mobile {
    border-right: 1px solid #e8ebee;
    left: 0;
    transition: color .1s ease .2s
}

[data-mobile=navigation] .site-nav-toggle-mobile {
    color: #39424a
}

.site-nav-toggle-mobile-icon {
    display: block;
    height: 14px;
    left: 50%;
    margin: -7px 0 0 -12px;
    position: absolute;
    top: 20px;
    transform-origin: center center;
    transition: transform .3s cubic-bezier(.55,.055,.675,.19) 0s;
    width: 24px
}

[data-mobile=navigation] .site-nav-toggle-mobile-icon {
    transform: rotate(180deg);
    transition: transform .3s cubic-bezier(.215,.61,.355,1) .1s
}

.site-nav-toggle-mobile-icon:after,.site-nav-toggle-mobile-icon:before {
    content: "";
    display: block;
    left: 50%;
    margin-left: -12px;
    position: absolute;
    top: 50%;
    transform-origin: center center;
    width: 24px
}

.site-nav-toggle-mobile-icon:before {
    border-bottom: 2px solid #019fcb;
    border-top: 2px solid #019fcb;
    height: 14px;
    margin-top: -7px;
    transition: border-color .2s ease-in .1s,border-width 0s ease-in .3s,height .1s ease-in .3s,margin .1s ease-in .3s,transform .2s ease-in .1s
}

[data-mobile=navigation] .site-nav-toggle-mobile-icon:before {
    border-color: #39424a;
    border-width: 1px 0;
    height: 0;
    margin-top: -1px;
    transition: border-color .3s ease-out .1s,border-width 0s ease-out .1s,height .1s ease-out,margin .1s ease-out,transform .3s ease-out .1s;
    transform: rotate(45deg)
}

.site-nav-toggle-mobile-icon:after {
    background-color: #019fcb;
    height: 2px;
    margin-top: -1px;
    transition: background .2s ease-in .1s,transform .2s ease-in .1s
}

[data-mobile=navigation] .site-nav-toggle-mobile-icon:after {
    background-color: #39424a;
    transform: rotate(-45deg);
    transition: background .3s ease-in .1s,transform .3s ease-out .1s
}

.header-message-wrapper {
    background-color: #fff;
    position: relative;
    z-index: 101
}

body[data-mobile=navigation] .header-message-wrapper {
    display: none
}

.header-message {
    font-size: 1.3rem;
    line-height: 1.8rem;
    padding: 1.8rem 1.5rem;
    position: relative;
    z-index: 101
}

.header-message p {
    margin: 0;
    max-width: none
}

.header-message p+p {
    margin-top: 1.2rem
}

.header-message strong {
    font-size: 1.2rem;
    text-transform: uppercase
}

.header-message.-with-button {
    padding-right: 12rem
}

.header-message.-alert {
    background-color: #fff5f5;
    color: #a4133b
}

.header-message.-alert a {
    color: #a4133b;
    text-decoration: underline
}

.header-message.-alert a:hover,[data-whatinput=keyboard] .header-message.-alert a:focus {
    text-decoration: none;
    background-color: #fcc
}

.header-message.-alert.theme-blue {
    background-color: #f5f7ff;
    color: #000
}

.header-message.-alert.theme-blue a {
    color: #17458f
}

.header-message.-alert.theme-blue a:hover,[data-whatinput=keyboard] .header-message.-alert.theme-blue a:focus {
    background-color: #e5f5fa
}

.header-message.-information {
    background-color: #019fcb;
    color: #fff
}

.header-message.-information a {
    color: #fff;
    text-decoration: underline
}

.header-message-button,.header-message.-information a:hover,[data-whatinput=keyboard] .header-message.-information a:focus {
    background-color: transparent
}

.header-message-button {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border: none;
    font-size: 1.2rem;
    font-weight: 700;
    height: 100%;
    margin: 0;
    padding: 0 3rem 0 1.5rem;
    position: absolute;
    right: 0;
    text-transform: uppercase;
    top: 0;
    transition: all .3s ease
}

.header-message-button:after,.header-message-button:before {
    content: "";
    display: block;
    height: 1.2rem;
    margin-top: -.6rem;
    position: absolute;
    right: 1.5rem;
    top: 50%;
    width: .2rem
}

.header-message-button:before {
    transform: rotate(45deg)
}

.header-message-button:after {
    transform: rotate(-45deg)
}

.-alert .header-message-button {
    color: #a4133b
}

.-alert .header-message-button:focus,.-alert .header-message-button:hover {
    background-color: #fcc
}

.-alert .header-message-button:after,.-alert .header-message-button:before {
    background-color: #a4133b
}

.-information .header-message-button {
    color: #fff
}

.-information .header-message-button:after,.-information .header-message-button:before {
    background-color: #fff
}

.-information .header-message-button:focus,.-information .header-message-button:hover {
    background-color: #017fa2
}

*,:after,:before {
    box-sizing: border-box
}

a {
    color: #019fcb;
    font-weight: 700;
    -webkit-tap-highlight-color: transparent;
    text-decoration: none;
    transition: background .3s ease,color .3s ease
}

a:active {
    background-color: transparent
}

[data-whatinput=keyboard] a:focus,a:hover {
    background-color: #e5f5fa
}

.u-link-small {
    font-size: 1.4rem;
    line-height: 2.4rem;
    font-weight: 400
}

a,button,input,select,textarea {
    outline: none
}

body {
    background-color: #fff;
    color: #39424a;
    -webkit-text-size-adjust: none;
    -ms-text-size-adjust: none;
    text-size-adjust: none;
    margin: 0;
    overflow-x: hidden;
    overflow-wrap: break-word;
    padding: 0;
    width: 100%;
    word-wrap: break-word;
    word-break: break-word
}

[data-scroll=false] body,body[data-mobile=navigation] {
    height: 100%;
    overflow: hidden;
    position: fixed
}

[data-whatinput=touch] body {
    cursor: pointer;
    -webkit-tap-highlight-color: rgba(255,255,255,0)
}

button {
    -webkit-tap-highlight-color: transparent
}

button,input[type=submit],label,select {
    cursor: pointer
}

div[tabindex="-1"],form[tabindex="-1"],main[tabindex="-1"] {
    outline: none
}

ol,p,ul {
    max-width: 80rem;
    margin: 2.4rem auto
}

.template-story .site-main ol,.template-story .site-main p,.template-story .site-main ul {
    max-width: 70rem
}

dl {
    max-width: 80rem;
    margin: 6rem auto
}

.template-story .site-main dl {
    max-width: 70rem
}

dt {
    font-size: 1.8rem;
    line-height: 3rem;
    font-weight: 700;
    margin: 0 0 .6rem
}

dd {
    margin: 0
}

dd>:first-child {
    margin-top: 0!important
}

dd>:last-child {
    margin-bottom: 0!important
}

dd+dt {
    margin-top: 3.6rem
}

em {
    font-style: italic
}

figure {
    margin: 0;
    padding: 0
}

hr {
    max-width: 80rem;
    border: 0;
    border-top: 1px solid #c7ced9;
    height: 0;
    margin: 4.8rem auto
}

.template-story .site-main hr {
    max-width: 70rem
}

.hr-rotary-wheel hr {
    margin: 0;
    max-width: none
}

.hero hr,.image-callout hr {
    border-color: hsla(0,0%,100%,.3);
    margin: 3.6rem auto
}

.hr-rotary-wheel {
    max-width: 80rem;
    display: block;
    height: 1px;
    margin: 4.8rem auto;
    text-align: center
}

.template-story .site-main .hr-rotary-wheel {
    max-width: 70rem
}

.hr-rotary-wheel:after {
    background: #fff url(Img/WhatsApp\ Image\ 2024-01-09\ at\ 4.19.14\ PM.jpeg) no-repeat 50% 50%;
    background-size: 22px 22px;
    content: "";
    display: inline-block;
    height: 22px;
    position: relative;
    top: -12px;
    width: 50px
}

.hero .hr-rotary-wheel,.image-callout .hr-rotary-wheel {
    margin: 3.6rem auto
}

img {
    border: none;
    -ms-interpolation-mode: bicubic;
    image-rendering: optimizeQuality
}

ol,ul {
    padding: 0
}

ol li,ul li {
    padding-left: 2.4rem
}

ol li {
    counter-increment: list;
    list-style-type: none
}

ol li:before {
    content: counter(list) ".";
    float: left;
    font-weight: 700;
    margin-left: -2.4rem;
    width: 2.4rem
}

ul {
    list-style: none
}

ul li:before {
    content: "\2022";
    display: block;
    float: left;
    margin-left: -1.8rem
}

li+li {
    margin-top: 1.2rem
}

pre {
    font-family: monospace
}

small {
    font-size: 1.4rem;
    line-height: 2.4rem
}

strong {
    font-weight: 700
}

.table-wrapper {
    max-width: 80rem;
    margin: 6rem auto;
    overflow-x: auto;
    overflow-y: hidden
}

.template-story .site-main .table-wrapper {
    max-width: 70rem
}

.table-wrapper[min-width~="700px"] table {
    white-space: normal
}

.table-wrapper[min-width~="700px"] td,.table-wrapper[min-width~="700px"] th {
    padding-bottom: 1.8rem;
    padding-top: 1.8rem
}

.table-wrapper table {
    border-collapse: collapse;
    border-spacing: 0;
    white-space: nowrap
}

.table-wrapper table>tr:first-child,.table-wrapper table thead tr:first-child {
    border-top: none
}

.table-wrapper thead {
    background-color: #f4f4f4;
    text-align: left;
    white-space: nowrap
}

.table-wrapper tr {
    border-top: 1px solid #bcc0c3
}

.table-wrapper td,.table-wrapper th {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding: 1.2rem 2rem;
    vertical-align: top
}

.site-main {
    max-width: 192rem;
    margin: 0 auto
}

main {
    display: block
}

.site-nav-container {
    background-color: hsla(0,0%,100%,0);
    height: 0;
    left: 0;
    position: absolute;
    top: 6rem;
    transition: background .3s ease,height 0s linear .3s;
    width: 100%;
    z-index: 1
}

[data-mobile=navigation] .site-nav-container {
    background-color: #fff;
    border-top: 1px solid #e8ebee;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: touch;
    overflow-x: hidden;
    overflow-y: auto;
    transform: translateZ(0);
    transition: background .3s ease,height 0s linear 0s
}

.site-nav {
    opacity: 0;
    transition: opacity .3s ease,visibility 0s linear .3s;
    visibility: collapse;
    position: relative
}

.site-nav:after {
    clear: both;
    content: "";
    display: table
}

[data-mobile=navigation] .site-nav {
    opacity: 1;
    transition: opacity .3s ease,visibility 0s linear 0s;
    visibility: visible
}

.site-nav-list {
    margin: 0 auto;
    max-width: none;
    padding: 2rem 0
}

.site-nav-list li {
    margin: 0;
    padding-left: 0
}

.site-nav-list li:before {
    display: none
}

.site-nav-list a {
    color: #5e717d;
    display: block
}

.site-nav-list a:focus,.site-nav-list a:hover {
    background-color: transparent;
    color: #0197c1
}

.site-nav-item {
    margin: 0;
    text-align: center
}

.site-nav-item-heading {
    font-size: 1.8rem;
    margin: 1.4rem 0
}

.site-nav-item-heading a {
    display: inline-block;
    position: relative
}

.site-nav-item-heading a:focus {
    color: #5e717d
}

.site-nav-item-heading a:after {
    background-color: #e8ebee;
    content: "";
    display: block;
    height: 4px;
    left: 50%;
    margin-left: -50%;
    position: absolute;
    top: 100%;
    transform: scaleX(0);
    transition: transform .3s ease;
    width: 100%
}

.site-nav-item-heading a[aria-expanded=true]:after {
    transform: scaleX(1)
}

.site-nav-item-heading .site-nav-a11y-helper {
    display: none
}

.site-nav-sublist {
    margin: 0;
    max-width: none;
    overflow: hidden
}

.site-nav-sublist[data-is=close] {
    max-height: 0;
    opacity: 0;
    transition: max-height .3s ease-out,opacity .3s ease-out,visibility 0s linear .3s;
    visibility: hidden
}

.site-nav-sublist[data-is=open] {
    max-height: 60rem;
    opacity: 1;
    transition: max-height .3s ease-in,opacity .3s ease-in,visibility 0s linear 0s;
    visibility: visible
}

.site-nav-sublist a {
    display: inline-block;
    font-size: 1.6rem;
    font-weight: 400;
    padding: .8rem 0
}

.site-nav-subitem {
    margin: 0;
    position: relative
}

.site-nav-subitem.-article a:focus img,.site-nav-subitem.-article a:hover img {
    box-shadow: 0 0 8px rgba(0,0,0,.2)
}

.site-nav-subitem.-article img {
    height: auto;
    max-width: 100%;
    transition: all .3s ease
}

.site-nav-subitem.-article .site-nav-article-date {
    color: #39424a
}

.site-nav-article-heading {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0
}

.site-nav-article-date {
    font-size: 1.2rem;
    line-height: 2.4rem
}

.site-nav-utility-links li {
    margin: 0;
    padding-left: 0
}

.site-nav-utility-links li:before {
    display: none
}

.site-nav-utility-links.-small {
    margin-top: 0;
    max-width: 60rem;
    opacity: 0;
    transition: opacity .3s ease,visibility 0s linear .3s;
    visibility: collapse
}

.site-nav-utility-links.-small:after {
    clear: both;
    content: "";
    display: table
}

[data-mobile=navigation] .site-nav-utility-links.-small {
    opacity: 1;
    transition: opacity .3s ease,visibility 0s linear 0s;
    visibility: visible;
    margin: 0 7rem;
    border-top: 1px groove #e8ebee
}

.site-nav-utility-links.-small a {
    font-size: 1.5rem;
    line-height: 2.4rem;
    display: block;
    padding: 1.2rem 0;
    text-align: center
}

.site-nav-utility-links.-large {
    display: none;
    margin: 0
}

.site-nav-utility-links.-large .site-nav-toggle-search-icon {
    top: 10px;
    left: -10px;
    margin-left: -5.5px
}

.site-nav-utility-links.-large .site-nav-toggle-search-icon:after {
    width: 6px
}

.site-nav-utility-links.-large .site-nav-toggle-search-icon:before {
    height: 11px;
    width: 11px;
    top: 3px
}

.site-nav-utility-links.-large a {
    font-size: 1.4rem;
    line-height: 2.4rem;
    display: block
}

.site-nav-utility-links.-large li {
    display: inline-block;
    line-height: 3.6rem;
    margin: 0
}

.site-nav-utility-links.-large li+li {
    margin-left: 2.1rem
}

.site-nav-utility-links.-large li+li a:before {
    left: -1.1rem
}

.site-nav-utility-links.-large li+li+li button:before,.site-nav-utility-links.-large li+li a:before {
    background-color: #c7ced9;
    content: "";
    display: block;
    height: 12px;
    margin-top: -6px;
    top: 50%;
    position: absolute;
    width: 1px
}

.site-nav-utility-links.-large li+li+li button:before {
    left: -2.5rem
}

.site-nav-utility-links a {
    color: #019fcb;
    font-weight: 700;
    position: relative;
    text-transform: uppercase
}

.site-nav-utility-links a:focus,.site-nav-utility-links a:hover {
    background-color: transparent;
    text-decoration: underline;
    color: #019fcb
}

.site-nav-utility-links a:focus path,.site-nav-utility-links a:hover path {
    fill: #019fcb
}

.site-nav-utility-links path {
    fill: #bbc1c6;
    transition: all .3s ease
}

.site-nav-utility-search {
    border-top: 1px solid #e8ebee;
    display: inline-block;
    left: 0;
    opacity: 1;
    overflow: hidden;
    padding-bottom: 18px;
    position: absolute;
    top: 100%;
    transition: opacity .3s ease,visibility 0s linear 0s;
    visibility: collapse;
    width: 100%
}

[data-mobile=search] .site-nav-utility-search {
    top: 0;
    opacity: 1;
    transition: opacity .3s ease,visibility 0s linear 0s;
    visibility: visible
}

.site-nav-utility-search form {
    background-color: #fff;
    box-shadow: 0 0 30px rgba(0,0,0,.2);
    padding: 2rem
}

.site-nav-utility-search button,.site-nav-utility-search input[type=submit] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: transparent;
    border: none;
    height: 3rem;
    margin: 0;
    padding: 0;
    position: absolute;
    right: 2.3rem;
    top: 2.3rem;
    width: 3rem
}

.site-nav-utility-search button path,.site-nav-utility-search input[type=submit] path {
    fill: #019fcb
}

.site-nav-utility-search button svg,.site-nav-utility-search input[type=submit] svg {
    height: 1.4rem;
    left: 50%;
    margin: -.7rem 0 0 -.7rem;
    position: absolute;
    top: 50%;
    width: 1.4rem
}

.site-nav-utility-search input[type=search],.site-nav-utility-search input[type=text] {
    height: 3.6rem;
    padding: 0 3.6rem 0 .6rem
}

.site-nav-utility-search input[type=search]::-ms-clear,.site-nav-utility-search input[type=text]::-ms-clear {
    display: none
}

.site-nav-utility-ctas {
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-color: #f8f9fa;
    margin: 0;
    max-width: none;
    opacity: 0;
    text-align: center;
    text-transform: uppercase;
    transition: opacity .3s ease,visibility 0s linear .3s;
    visibility: collapse;
    width: 100%;
    z-index: 10
}

.site-nav-utility-ctas:after {
    clear: both;
    content: "";
    display: table
}

.site-nav-utility-ctas li {
    padding-left: 0
}

.site-nav-utility-ctas li:before {
    display: none
}

[data-mobile=navigation] .site-nav-utility-ctas {
    opacity: 1;
    transition: opacity .3s ease,visibility 0s linear 0s;
    visibility: visible
}

[data-mobile=navigation] .site-nav-utility-ctas .u-button.-slim {
    border-radius: 0
}

[data-mobile=navigation] .site-nav-utility-ctas .site-nav .u-button,[data-mobile=navigation] .site-nav-utility-ctas .u-button {
    border: 1px solid #d7dae0!important
}

.site-nav-utility-ctas a {
    display: block;
    line-height: normal;
    min-width: 13rem
}

.site-nav-utility-ctas li {
    display: block;
    float: left;
    margin: 0;
    width: 50%
}

html {
    font-size: 62.5%
}

body {
    font-size: 1.8rem;
    line-height: 2.6rem;
    font-family: HelveticaNeue-Light,Helvetica Neue Light,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif
}

.wf-active body {
    font-family: Open Sans,HelveticaNeue-Light,Helvetica Neue Light,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif
}

[lang=ja] body {
    font-family: Noto Sans JP,Meiryo,ãƒ¡ã‚¤ãƒªã‚ª,Hiragino Kaku Gothic Pro,MS PGothic,Arial Unicode MS,sans-serif
}

[lang=ko] body {
    font-family: Nanum Gothic,Malgun Gothic,Gulim,Dotum,Arial Unicode MS,sans-serif
}

button,input,select,textarea {
    font-family: HelveticaNeue-Light,Helvetica Neue Light,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif
}

.wf-active button,.wf-active input,.wf-active select,.wf-active textarea {
    font-family: Open Sans,HelveticaNeue-Light,Helvetica Neue Light,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif
}

[lang=ja] button,[lang=ja] input,[lang=ja] select,[lang=ja] textarea {
    font-family: Noto Sans JP,Meiryo,ãƒ¡ã‚¤ãƒªã‚ª,Hiragino Kaku Gothic Pro,MS PGothic,Arial Unicode MS,sans-serif
}

[lang=ko] button,[lang=ko] input,[lang=ko] select,[lang=ko] textarea {
    font-family: Nanum Gothic,Malgun Gothic,Gulim,Dotum,Arial Unicode MS,sans-serif
}

.breadcrumbs {
    font-size: 1.5rem;
    line-height: 2.4rem;
    text-align: center;
    text-transform: uppercase
}

.breadcrumbs a {
    display: inline-block;
    padding: 0 .6rem
}

.lede {
    font-size: 1.8rem;
    line-height: 2.6rem;
    margin: 3rem auto;
    max-width: 80rem
}

.heading-h1 {
    font-weight: 400;
    line-height: 4.2rem;
    text-align: center;
    font-size: 3.6rem;
    margin: 0 auto 3rem;
    max-width: 100rem
}

.heading-h1.-basic {
    margin-bottom: 1.2rem;
    text-align: left
}

.heading-h1.-basic+ol,.heading-h1.-basic+p,.heading-h1.-basic+ul {
    margin-top: 0
}

.heading-h1.-banner {
    font-size: 3.6rem;
    margin-bottom: 3rem;
    max-width: 120rem
}

.heading-h1.-feature {
    font-size: 6.6rem;
    line-height: 7.2rem
}

.hero .heading-h1.-feature {
    margin-bottom: 0
}

.heading-h2,.wysiwyg h2 {
    display: block;
    margin-bottom: 1.2rem;
    margin-top: 4.2rem;
    font-size: 2.4rem;
    line-height: 3rem;
    font-weight: 700
}

.heading-h2+ol,.heading-h2+p,.heading-h2+ul,.wysiwyg h2+ol,.wysiwyg h2+p,.wysiwyg h2+ul {
    margin-top: 0
}

.heading-h2.u-text-centered,.wysiwyg h2.u-text-centered {
    margin-bottom: 4.2rem
}

.heading-h2.-alternate,.wysiwyg h2.-alternate {
    font-size: 2.6rem;
    line-height: 3.6rem;
    font-weight: 400
}

.heading-h2.-alternate-light,.wysiwyg h2.-alternate-light {
    font-size: 4.8rem;
    line-height: 6.6rem;
    font-weight: 300
}

.heading-callout {
    display: block;
    margin-bottom: .9rem;
    font-size: 2.4rem;
    line-height: 3rem;
    font-weight: 400
}

.heading-callout+ol,.heading-callout+p,.heading-callout+ul {
    margin-top: 0
}

.heading-callout.-alternate {
    font-weight: 700
}

.heading-h3,.wysiwyg h3 {
    display: block;
    margin-bottom: .9rem;
    font-weight: 700;
    margin-top: 2.4rem;
    font-size: 2rem;
    line-height: 3rem
}

.heading-h3+ol,.heading-h3+p,.heading-h3+ul,.wysiwyg h3+ol,.wysiwyg h3+p,.wysiwyg h3+ul {
    margin-top: 0
}

.heading-h3.-alternate,.wysiwyg h3.-alternate {
    font-size: 1.7rem;
    line-height: 2.4rem;
    text-transform: uppercase
}

.heading-h3.-weight-normal,.wysiwyg h3.-weight-normal {
    font-weight: 400
}

.heading-section {
    display: block;
    font-weight: 700;
    margin-top: 2.4rem;
    font-size: 1.7rem;
    line-height: 2.4rem;
    text-transform: uppercase;
    margin-bottom: 3rem;
    text-align: center
}

.heading-section+ol,.heading-section+p,.heading-section+ul {
    margin-top: 0
}

.heading-h4,.wysiwyg h4 {
    font-size: 1.8rem;
    line-height: 2.6rem;
    display: block;
    margin-bottom: .9rem;
    font-weight: 700;
    margin-top: 2.4rem
}

.heading-h4+ol,.heading-h4+p,.heading-h4+ul,.wysiwyg h4+ol,.wysiwyg h4+p,.wysiwyg h4+ul {
    margin-top: 0
}

.heading-h4.-alternate,.wysiwyg h4.-alternate {
    font-weight: 400
}

.heading-h5,.wysiwyg h5 {
    display: block;
    margin-bottom: .9rem;
    font-size: 1.5rem;
    font-weight: 700;
    line-height: 3rem;
    margin-top: 2.4rem;
    text-transform: uppercase
}

.heading-h5+ol,.heading-h5+p,.heading-h5+ul,.wysiwyg h5+ol,.wysiwyg h5+p,.wysiwyg h5+ul {
    margin-top: 0
}

.heading-h5.-alternate,.wysiwyg h5.-alternate {
    font-weight: 400
}

.heading-h2,.heading-h3,.heading-h4,.heading-h5,.wysiwyg h2,.wysiwyg h3,.wysiwyg h4,.wysiwyg h5,.wysiwyg h6,h5 {
    max-width: 80rem;
    margin-left: auto;
    margin-right: auto
}

.template-story .site-main .heading-h2,.template-story .site-main .heading-h3,.template-story .site-main .heading-h4,.template-story .site-main .heading-h5,.template-story .site-main .wysiwyg h2,.template-story .site-main .wysiwyg h3,.template-story .site-main .wysiwyg h4,.template-story .site-main .wysiwyg h5,.template-story .site-main .wysiwyg h6,.template-story .site-main h5 {
    max-width: 70rem
}

[class*=heading-] [class*=heading-] {
    margin-top: .6rem!important
}

.heading-tag {
    display: block;
    font-size: 1.7rem;
    font-weight: 700;
    line-height: 2.4rem;
    text-transform: uppercase
}

.quote-block-quote {
    quotes: "\201c" "\201d" "\2018" "\2019"
}

[lang=de] .quote-block-quote {
    quotes: "\201e" "\201c" "\201a" "\2018"
}

[lang=fr] .quote-block-quote {
    quotes: "\00ab" "\00bb" "\00ab" "\00bb"
}

[lang=es] .quote-block-quote,[lang=it] .quote-block-quote {
    quotes: "\00ab" "\00bb" "\201c" "\201d"
}

[lang=ja] .quote-block-quote {
    quotes: "\300c" "\300d" "\300e" "\300f"
}

.quote-block-quote:after,.quote-block-quote:before {
    font-size: 1.2em
}

.quote-block-quote:before {
    content: open-quote
}

.quote-block-quote:after {
    content: close-quote
}

.quote-inline {
    quotes: none
}

.quote-inline:after,.quote-inline:before {
    display: none
}

.quote-block {
    font-size: 2.4rem;
    line-height: 3rem;
    margin: 3rem auto;
    max-width: 90rem
}

.quote-block-quote p {
    display: inline
}

.quote-block-quote p+p:before {
    content: "\a\a";
    white-space: pre
}

.quote-block-attribution {
    align-items: center;
    display: flex;
    margin-bottom: 0;
    max-width: none;
    width: 100%
}

.no-flexbox .quote-block-attribution {
    display: block
}

.no-flexbox .quote-block-attribution:after {
    clear: both;
    content: "";
    display: table
}

.quote-block-attribution img {
    border-radius: 50%;
    height: 4rem;
    margin-right: 1.2rem;
    min-width: 4rem;
    width: 4rem
}

.no-flexbox .quote-block-attribution img {
    float: left;
    margin-top: .45rem
}

.quote-block-attribution-text {
    font-size: 1.4rem;
    line-height: 2.4rem
}

.no-flexbox .quote-block-attribution-text {
    display: block
}

.quote-inline {
    display: block;
    font-size: 2.4rem;
    font-weight: 700;
    line-height: 3.6rem;
    margin-bottom: 2.4rem
}

ol li:before {
    text-align: right;
    margin-left: -4.4rem;
    width: 3.8rem
}

.number-list,.people-list,.thumbnail-list {
    margin: 6rem auto;
    padding: 0
}

.number-list li:after,.people-list li:after,.thumbnail-list li:after {
    clear: both;
    content: "";
    display: table
}

.number-list li>:first-child,.people-list li>:first-child,.thumbnail-list li>:first-child {
    margin-top: 0!important
}

.number-list li>:last-child,.people-list li>:last-child,.thumbnail-list li>:last-child {
    margin-bottom: 0!important
}

.number-list li+li,.people-list li+li,.thumbnail-list li+li {
    margin-top: 4.8rem
}

.number-list li *,.people-list li *,.thumbnail-list li * {
    max-width: 100%
}

.number-list li {
    padding-left: 4.4rem
}

.number-list li:before {
    font-size: 2.4rem;
    line-height: 3rem;
    text-align: right;
    margin-left: -4.4rem;
    width: 3.8rem
}

.thumbnail-list li {
    margin: 0;
    padding-left: 0
}

.thumbnail-list img,.thumbnail-list li:before {
    display: none
}

.people-list li {
    margin: 0;
    padding-left: 0
}

.people-list li:before {
    display: none
}

.people-list li {
    border-top: 1px solid #c7ced9;
    padding-top: 6rem
}

.people-list li+li {
    margin-top: 6rem
}

.people-list-image img {
    display: block;
    height: auto;
    margin: 0 auto;
    max-width: 100%
}

.people-list-text {
    font-size: 1.6rem
}

.people-list-text>:last-child {
    margin-bottom: 0
}

[lang=de] .u-drop-cap p:first-of-type:first-letter,[lang=en] .u-drop-cap p:first-of-type:first-letter,[lang=es] .u-drop-cap p:first-of-type:first-letter,[lang=fr] .u-drop-cap p:first-of-type:first-letter,[lang=it] .u-drop-cap p:first-of-type:first-letter,[lang=pt] .u-drop-cap p:first-of-type:first-letter {
    float: left;
    font-size: 6rem;
    font-weight: 700;
    line-height: 6rem;
    padding-right: .6rem
}

.u-text-centered {
    text-align: center!important
}

.u-text-left {
    text-align: left!important
}

.u-text-right {
    text-align: right!important
}

.u-list-unstyled li {
    margin: 0;
    padding-left: 0
}

.u-list-unstyled li:before {
    display: none
}

.u-centered {
    margin-left: auto!important;
    margin-right: auto!important
}

.u-nowrap {
    white-space: nowrap!important
}

.u-color-blue {
    color: #019fcb!important
}

.u-background-blue {
    background-color: #019fcb!important
}

.u-border-blue {
    border-color: #019fcb!important
}

.u-color-darkblue {
    color: #263b4c!important
}

.u-background-darkblue {
    background-color: #263b4c!important
}

.u-border-darkblue {
    border-color: #263b4c!important
}

.u-background-royalblue {
    background-color: #0c3c7c!important
}

.u-color-green {
    color: #018d8d!important
}

.u-background-green {
    background-color: #018d8d!important
}

.u-border-green {
    border-color: #018d8d!important
}

.u-color-purple {
    color: #872175!important
}

.u-background-purple {
    background-color: #872175!important
}

.u-border-purple {
    border-color: #872175!important
}

.u-color-red {
    color: #9b1238!important
}

.u-background-red {
    background-color: #9b1238!important
}

.u-border-red {
    border-color: #9b1238!important
}

.u-background-triangles {
    background-position: 50% 0;
    background-repeat: repeat;
    background-size: 71px 85px
}

.u-background-triangles.u-background-blue {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-blue.png)
}

.u-background-triangles.u-background-darkblue {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-darkblue.png)
}

.u-background-triangles.u-background-green {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-green.png)
}

.u-background-triangles.u-background-purple {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-purple.png)
}

.u-background-triangles.u-background-red {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-red.png)
}

.u-container {
    margin: 0 auto;
    position: relative;
    z-index: 2
}

.u-container>:first-child {
    margin-top: 0!important
}

.u-container>:last-child {
    margin-bottom: 0!important
}

.u-container ol,.u-container p,.u-container ul {
    max-width: none
}

.u-container+.u-container {
    margin-top: 6rem
}

.u-container-bordered {
    border: 1px solid #c7ced9;
    padding: 2.4rem
}

.u-container-bordered>:first-child {
    margin-top: 0!important
}

.u-container-bordered>:last-child {
    margin-bottom: 0!important
}

.u-width-1 {
    max-width: 10rem
}

.u-width-1.u-pull-left,.u-width-1.u-pull-right {
    max-width: 15rem
}

.u-width-2 {
    max-width: 20rem
}

.u-width-2.u-pull-left,.u-width-2.u-pull-right {
    max-width: 25rem
}

.u-width-3 {
    max-width: 30rem
}

.u-width-3.u-pull-left,.u-width-3.u-pull-right {
    max-width: 35rem
}

.u-width-4 {
    max-width: 40rem
}

.u-width-4.u-pull-left,.u-width-4.u-pull-right {
    max-width: 45rem
}

.u-width-5 {
    max-width: 50rem
}

.u-width-6 {
    max-width: 60rem
}

.u-width-7 {
    max-width: 70rem
}

.u-width-8 {
    max-width: 80rem
}

.u-width-9 {
    max-width: 90rem
}

.u-width-10 {
    max-width: 100rem
}

.u-width-11 {
    max-width: 110rem
}

.u-width-12 {
    max-width: 120rem
}

.u-width-full {
    margin-left: -1.8rem;
    width: calc(100% + 3.6rem)
}

.u-pull-container {
    max-width: 80rem;
    margin: 0 auto
}

.template-story .site-main .u-pull-container {
    max-width: 70rem
}

.u-pull-container.-sidebar {
    max-width: 120rem
}

.u-pull-container>div:before {
    display: block;
    width: 2000px;
    content: ""
}

.u-pull-1,.u-pull-2,.u-pull-3,.u-pull-4 {
    margin-left: auto;
    margin-right: auto
}

.u-sidebar {
    display: none
}

.u-sidebar a {
    color: #872175;
    font-weight: 400
}

.u-sidebar a:focus,.u-sidebar a:hover {
    background-color: transparent;
    text-decoration: underline
}

.u-sidebar hr {
    margin: 1.2rem 0
}

.u-sidebar p {
    margin: .6rem 0
}

.u-display-none {
    display: none!important
}

.site-nav .u-button,.u-button {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: #019fcb;
    border: 1px solid #019fcb;
    border-radius: 28px;
    color: #fff;
    display: inline-block;
    font-size: 1.5rem;
    font-weight: 700;
    line-height: 1.62rem;
    margin: 0;
    min-width: 25rem;
    padding: 2.1rem 3rem;
    text-align: center;
    text-shadow: none;
    text-transform: uppercase;
    transition: background .3s ease,border .3s ease,color .3s ease
}

.site-nav .u-button.-slim,.u-button.-slim {
    padding: 1.2rem 3rem
}

.site-nav .u-button.-width-auto,.u-button.-width-auto {
    min-width: 0;
    width: auto
}

.site-nav .u-button.-fluid,.u-button.-fluid {
    min-width: 0;
    width: 100%
}

.site-nav .u-button.-fluid-max-20rem,.u-button.-fluid-max-20rem {
    max-width: 100%;
    min-width: 0;
    width: 20rem
}

.site-nav .u-button.-fluid-max-25rem,.u-button.-fluid-max-25rem {
    max-width: 100%;
    min-width: 0;
    width: 25rem
}

.site-nav .u-button:hover,.u-button:hover,[data-whatinput=keyboard] .site-nav .u-button:focus,[data-whatinput=keyboard] .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #019fcb
}

.site-nav .u-button.-fluid-small,.u-button.-fluid-small {
    min-width: 0;
    width: 100%
}

.u-collapsible-toggle {
    border-color: #019fcb;
    border-radius: 6px;
    border-width: 2px;
    color: #019fcb;
    max-width: 100%;
    width: 33rem
}

.u-collapsible-toggle:hover,[data-whatinput=keyboard] .u-collapsible-toggle:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #019fcb;
    color: #fff
}

.u-collapsible-toggle:hover:after,[data-whatinput=keyboard] .u-collapsible-toggle:focus:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-white.svg)
}

.u-collapsible-toggle[aria-expanded=true]:after {
    transform: rotate(180deg);
    transition: transform .3s ease-out
}

.u-collapsible-toggle:after {
    background: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-blue.svg) no-repeat 50% 50%;
    background-size: 14px 8px;
    content: "";
    display: inline-block;
    height: 8px;
    margin: -.1rem 0 0 .7rem;
    transition: transform .3s ease-in;
    transform-origin: center center;
    width: 14px
}

.u-button-hero {
    background-color: #fff;
    color: #9b1238
}

.u-button-hero:hover,.u-button-reversed-hero,[data-whatinput=keyboard] .u-button-hero:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #9b1238;
    border-color: #9b1238;
    color: #fff
}

.u-button-reversed-hero:hover,[data-whatinput=keyboard] .u-button-reversed-hero:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    border-color: #fff;
    color: #9b1238
}

.site-nav .u-button-red,.u-button-red {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #c10042;
    border-color: #c10042
}

.site-nav .u-button-red:hover,.u-button-red:hover,[data-whatinput=keyboard] .site-nav .u-button-red:focus,[data-whatinput=keyboard] .u-button-red:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #c10042
}

.site-nav .u-button-reversed-red,.u-button-reversed-red {
    background-color: transparent;
    border-color: #c10042;
    color: #c10042
}

.site-nav .u-button-reversed-red:hover,.u-button-reversed-red:hover,[data-whatinput=keyboard] .site-nav .u-button-reversed-red:focus,[data-whatinput=keyboard] .u-button-reversed-red:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #c10042;
    color: #fff
}

.u-background-red .u-button {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.u-background-red .u-button:hover,[data-whatinput=keyboard] .u-background-red .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    color: #9b1238
}

.u-background-red .u-button-reversed {
    background-color: #fff;
    color: #9b1238;
    border: 1px solid #fff
}

.u-background-red .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-red .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.site-nav .u-button-green,.u-button-green {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #018d8d;
    border-color: #018d8d
}

.site-nav .u-button-green:hover,.u-button-green:hover,[data-whatinput=keyboard] .site-nav .u-button-green:focus,[data-whatinput=keyboard] .u-button-green:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #018d8d
}

.site-nav .u-button-reversed-green,.u-button-reversed-green {
    background-color: transparent;
    border-color: #018d8d;
    color: #018d8d
}

.site-nav .u-button-reversed-green:hover,.u-button-reversed-green:hover,[data-whatinput=keyboard] .site-nav .u-button-reversed-green:focus,[data-whatinput=keyboard] .u-button-reversed-green:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #018d8d;
    color: #fff
}

.u-background-green .u-button {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.u-background-green .u-button:hover,[data-whatinput=keyboard] .u-background-green .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    color: #018d8d
}

.u-background-green .u-button-reversed {
    background-color: #fff;
    color: #018d8d;
    border: 1px solid #fff
}

.u-background-green .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-green .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.site-nav .u-button-blue,.u-button-blue {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #019fcb;
    border-color: #019fcb
}

.site-nav .u-button-blue:hover,.u-button-blue:hover,[data-whatinput=keyboard] .site-nav .u-button-blue:focus,[data-whatinput=keyboard] .u-button-blue:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #019fcb
}

.site-nav .u-button-reversed-blue,.u-button-reversed-blue {
    background-color: transparent;
    border-color: #019fcb;
    color: #019fcb
}

.site-nav .u-button-reversed-blue:hover,.u-button-reversed-blue:hover,[data-whatinput=keyboard] .site-nav .u-button-reversed-blue:focus,[data-whatinput=keyboard] .u-button-reversed-blue:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #019fcb;
    color: #fff
}

.u-background-blue .u-button {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.u-background-blue .u-button:hover,[data-whatinput=keyboard] .u-background-blue .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    color: #019fcb
}

.u-background-blue .u-button-reversed {
    background-color: #fff;
    color: #019fcb;
    border: 1px solid #fff
}

.u-background-blue .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-blue .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.site-nav .u-button-purple,.u-button-purple {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #872175;
    border-color: #872175
}

.site-nav .u-button-purple:hover,.u-button-purple:hover,[data-whatinput=keyboard] .site-nav .u-button-purple:focus,[data-whatinput=keyboard] .u-button-purple:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #872175
}

.site-nav .u-button-reversed-purple,.u-button-reversed-purple {
    background-color: transparent;
    border-color: #872175;
    color: #872175
}

.site-nav .u-button-reversed-purple:hover,.u-button-reversed-purple:hover,[data-whatinput=keyboard] .site-nav .u-button-reversed-purple:focus,[data-whatinput=keyboard] .u-button-reversed-purple:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #872175;
    color: #fff
}

.u-background-purple .u-button {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.u-background-purple .u-button:hover,[data-whatinput=keyboard] .u-background-purple .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    color: #872175
}

.u-background-purple .u-button-reversed {
    background-color: #fff;
    color: #872175;
    border: 1px solid #fff
}

.u-background-purple .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-purple .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.site-nav .u-button-poliored,.u-button-poliored {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #eb2036;
    border-color: #eb2036
}

.site-nav .u-button-poliored:hover,.u-button-poliored:hover,[data-whatinput=keyboard] .site-nav .u-button-poliored:focus,[data-whatinput=keyboard] .u-button-poliored:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    color: #eb2036
}

.site-nav .u-button-reversed-poliored,.u-button-reversed-poliored {
    background-color: transparent;
    border-color: #eb2036;
    color: #eb2036
}

.site-nav .u-button-reversed-poliored:hover,.u-button-reversed-poliored:hover,[data-whatinput=keyboard] .site-nav .u-button-reversed-poliored:focus,[data-whatinput=keyboard] .u-button-reversed-poliored:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #eb2036;
    color: #fff
}

.u-background-poliored .u-button {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.u-background-poliored .u-button:hover,[data-whatinput=keyboard] .u-background-poliored .u-button:focus {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: #fff;
    color: #eb2036
}

.u-background-poliored .u-button-reversed {
    background-color: #fff;
    color: #eb2036;
    border: 1px solid #fff
}

.u-background-poliored .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-poliored .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.u-button-white {
    background-color: #fff;
    border: none;
    color: #5e717d
}

.u-button-white:hover,[data-whatinput=keyboard] .u-button-white:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #5e717d;
    color: #fff
}

.u-button-reversed-white {
    background-color: transparent;
    border-color: #fff;
    color: #fff
}

.u-button-reversed-white:hover,[data-whatinput=keyboard] .u-button-reversed-white:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #fff;
    color: #000
}

.u-button-black {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #000;
    border-color: #000;
    color: #fff
}

.u-button-black:hover,.u-button-reversed-black,[data-whatinput=keyboard] .u-button-black:focus {
    background-color: transparent;
    color: #000
}

.u-button-reversed-black {
    border-color: #000
}

.u-button-reversed-black:hover,[data-whatinput=keyboard] .u-button-reversed-black:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #000;
    color: #fff
}

.u-background-darkblue .u-button-reversed,.u-background-darkblue .u-button:hover,[data-whatinput=keyboard] .u-background-darkblue .u-button:focus {
    background-color: #fff;
    color: #263b4c
}

.u-background-darkblue .u-button-reversed:hover,[data-whatinput=keyboard] .u-background-darkblue .u-button-reversed:focus {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: transparent;
    color: #fff
}

.u-button.-disabled,.u-button[disabled] {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #c1c4c7;
    border-color: #c1c4c7;
    color: #fff;
    cursor: not-allowed
}

[class*=u-button-reversed].-disabled,[class*=u-button-reversed][disabled] {
    -webkit-font-smoothing: subpixel-antialiased;
    -moz-osx-font-smoothing: auto;
    background-color: transparent;
    border-color: #c1c4c7;
    color: #c1c4c7;
    cursor: not-allowed
}

.u-button-group {
    animation: .1s element-queries
}

.u-button-group:after {
    clear: both;
    content: "";
    display: table
}

.u-button-group .u-button {
    max-width: none;
    min-width: 0;
    width: 100%
}

.u-button-group .u-button+.u-button {
    margin-top: 20px
}

fieldset {
    border: none;
    margin: 0!important;
    padding: 0
}

legend {
    font-size: 1.3rem;
    line-height: 2.4rem;
    font-weight: 700;
    margin: 0 0 .3rem;
    padding: 0;
    text-transform: uppercase
}

legend+.u-grid-row {
    margin-top: 0
}

label {
    font-size: 1.4rem;
    line-height: 2.4rem;
    display: block;
    font-weight: 700;
    margin-bottom: .3rem
}

label .required {
    color: #bb0043
}

input[type=color],input[type=date],input[type=datetime],input[type=email],input[type=file],input[type=number],input[type=password],input[type=search],input[type=tel],input[type=text],input[type=url],textarea {
    background-color: #fff;
    border: 1px solid #bbc3d1;
    border-radius: 0;
    color: #39424a;
    display: block;
    font-size: 1.6rem;
    margin: 0;
    transition: all .3s ease;
    width: 100%
}

input[type=color]:focus,input[type=date]:focus,input[type=datetime]:focus,input[type=email]:focus,input[type=file]:focus,input[type=number]:focus,input[type=password]:focus,input[type=search]:focus,input[type=tel]:focus,input[type=text]:focus,input[type=url]:focus,textarea:focus {
    border-color: #019fcb
}

input[type=color][aria-invalid=true],input[type=date][aria-invalid=true],input[type=datetime][aria-invalid=true],input[type=email][aria-invalid=true],input[type=file][aria-invalid=true],input[type=number][aria-invalid=true],input[type=password][aria-invalid=true],input[type=search][aria-invalid=true],input[type=tel][aria-invalid=true],input[type=text][aria-invalid=true],input[type=url][aria-invalid=true],textarea[aria-invalid=true] {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/icon-error.svg);
    background-position: calc(100% - 10px) 1rem;
    background-repeat: no-repeat;
    background-size: 22.5px 20px;
    padding-right: 4rem
}

input[type=color],input[type=date],input[type=datetime],input[type=email],input[type=file],input[type=number],input[type=password],input[type=search],input[type=tel],input[type=text],input[type=url] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    height: 4.2rem;
    padding: 0 1.4rem
}

input[type=color]::-webkit-input-placeholder,input[type=date]::-webkit-input-placeholder,input[type=datetime]::-webkit-input-placeholder,input[type=email]::-webkit-input-placeholder,input[type=file]::-webkit-input-placeholder,input[type=number]::-webkit-input-placeholder,input[type=password]::-webkit-input-placeholder,input[type=search]::-webkit-input-placeholder,input[type=tel]::-webkit-input-placeholder,input[type=text]::-webkit-input-placeholder,input[type=url]::-webkit-input-placeholder {
    color: #019fcb;
    font-weight: 700;
    opacity: 1;
    transition: all .3s ease
}

input[type=color]::-moz-placeholder,input[type=date]::-moz-placeholder,input[type=datetime]::-moz-placeholder,input[type=email]::-moz-placeholder,input[type=file]::-moz-placeholder,input[type=number]::-moz-placeholder,input[type=password]::-moz-placeholder,input[type=search]::-moz-placeholder,input[type=tel]::-moz-placeholder,input[type=text]::-moz-placeholder,input[type=url]::-moz-placeholder {
    color: #019fcb;
    font-weight: 700;
    opacity: 1;
    transition: all .3s ease
}

input[type=color]:-ms-input-placeholder,input[type=date]:-ms-input-placeholder,input[type=datetime]:-ms-input-placeholder,input[type=email]:-ms-input-placeholder,input[type=file]:-ms-input-placeholder,input[type=number]:-ms-input-placeholder,input[type=password]:-ms-input-placeholder,input[type=search]:-ms-input-placeholder,input[type=tel]:-ms-input-placeholder,input[type=text]:-ms-input-placeholder,input[type=url]:-ms-input-placeholder {
    color: #019fcb;
    font-weight: 700;
    opacity: 1;
    transition: all .3s ease
}

input[type=color]:-moz-placeholder,input[type=date]:-moz-placeholder,input[type=datetime]:-moz-placeholder,input[type=email]:-moz-placeholder,input[type=file]:-moz-placeholder,input[type=number]:-moz-placeholder,input[type=password]:-moz-placeholder,input[type=search]:-moz-placeholder,input[type=tel]:-moz-placeholder,input[type=text]:-moz-placeholder,input[type=url]:-moz-placeholder {
    color: #019fcb;
    font-weight: 700;
    opacity: 1;
    transition: all .3s ease
}

input[type=color]:focus::-webkit-input-placeholder,input[type=date]:focus::-webkit-input-placeholder,input[type=datetime]:focus::-webkit-input-placeholder,input[type=email]:focus::-webkit-input-placeholder,input[type=file]:focus::-webkit-input-placeholder,input[type=number]:focus::-webkit-input-placeholder,input[type=password]:focus::-webkit-input-placeholder,input[type=search]:focus::-webkit-input-placeholder,input[type=tel]:focus::-webkit-input-placeholder,input[type=text]:focus::-webkit-input-placeholder,input[type=url]:focus::-webkit-input-placeholder {
    color: #5e717d;
    opacity: .3
}

input[type=color]:focus::-moz-placeholder,input[type=date]:focus::-moz-placeholder,input[type=datetime]:focus::-moz-placeholder,input[type=email]:focus::-moz-placeholder,input[type=file]:focus::-moz-placeholder,input[type=number]:focus::-moz-placeholder,input[type=password]:focus::-moz-placeholder,input[type=search]:focus::-moz-placeholder,input[type=tel]:focus::-moz-placeholder,input[type=text]:focus::-moz-placeholder,input[type=url]:focus::-moz-placeholder {
    color: #5e717d;
    opacity: .3
}

input[type=color]:focus:-ms-input-placeholder,input[type=date]:focus:-ms-input-placeholder,input[type=datetime]:focus:-ms-input-placeholder,input[type=email]:focus:-ms-input-placeholder,input[type=file]:focus:-ms-input-placeholder,input[type=number]:focus:-ms-input-placeholder,input[type=password]:focus:-ms-input-placeholder,input[type=search]:focus:-ms-input-placeholder,input[type=tel]:focus:-ms-input-placeholder,input[type=text]:focus:-ms-input-placeholder,input[type=url]:focus:-ms-input-placeholder {
    color: #5e717d;
    opacity: .3
}

input[type=color]:focus:-moz-placeholder,input[type=date]:focus:-moz-placeholder,input[type=datetime]:focus:-moz-placeholder,input[type=email]:focus:-moz-placeholder,input[type=file]:focus:-moz-placeholder,input[type=number]:focus:-moz-placeholder,input[type=password]:focus:-moz-placeholder,input[type=search]:focus:-moz-placeholder,input[type=tel]:focus:-moz-placeholder,input[type=text]:focus:-moz-placeholder,input[type=url]:focus:-moz-placeholder {
    color: #5e717d;
    opacity: .3
}

textarea {
    overflow: auto;
    padding: 1.2rem 1.4rem;
    resize: vertical
}

.u-checkbox+label,.u-radio+label {
    display: inline;
    font-weight: 400;
    margin: 0
}

[data-whatinput=initial] .u-checkbox,[data-whatinput=initial] .u-radio,[data-whatinput=mouse] .u-checkbox,[data-whatinput=mouse] .u-radio {
    border: 0;
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px,1px,1px,1px);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px
}

[data-whatinput=initial] .u-checkbox+label,[data-whatinput=initial] .u-radio+label,[data-whatinput=mouse] .u-checkbox+label,[data-whatinput=mouse] .u-radio+label {
    display: block;
    padding-left: 3rem;
    position: relative
}

[data-whatinput=initial] .u-checkbox+label:after,[data-whatinput=initial] .u-checkbox+label:before,[data-whatinput=initial] .u-radio+label:after,[data-whatinput=initial] .u-radio+label:before,[data-whatinput=mouse] .u-checkbox+label:after,[data-whatinput=mouse] .u-checkbox+label:before,[data-whatinput=mouse] .u-radio+label:after,[data-whatinput=mouse] .u-radio+label:before {
    content: "";
    display: block;
    position: absolute;
    top: 50%
}

[data-whatinput=initial] .u-checkbox+label:before,[data-whatinput=initial] .u-radio+label:before,[data-whatinput=mouse] .u-checkbox+label:before,[data-whatinput=mouse] .u-radio+label:before {
    background-color: #fff;
    border: 1px solid #bbc3d1;
    border-radius: 3px;
    height: 2rem;
    left: 0;
    margin-top: -1rem;
    transition: box-shadow .3s ease;
    width: 2rem
}

[data-whatinput=initial] .u-checkbox+label:after,[data-whatinput=mouse] .u-checkbox+label:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/check.png);
    background-position: 50% 50%;
    background-repeat: no-repeat;
    background-size: 20px 20px;
    height: 2rem;
    left: 0;
    margin-top: -1rem;
    opacity: 0;
    transform: scale(.5);
    transition: all .3s ease;
    width: 2rem
}

[data-whatinput=initial] .u-checkbox:checked+label:after,[data-whatinput=mouse] .u-checkbox:checked+label:after {
    opacity: 1;
    transform: scale(1)
}

[data-whatinput=initial] .u-radio+label:before,[data-whatinput=mouse] .u-radio+label:before {
    border-radius: 50%
}

[data-whatinput=initial] .u-radio+label:after,[data-whatinput=mouse] .u-radio+label:after {
    background-color: #019fcb;
    border-radius: 50%;
    height: 1.4rem;
    left: .3rem;
    margin-top: -.7rem;
    opacity: 0;
    transform: scale(.5);
    transition: all .3s ease;
    width: 1.4rem
}

[data-whatinput=initial] .u-radio:checked+label:before,[data-whatinput=mouse] .u-radio:checked+label:before {
    background-image: none
}

[data-whatinput=initial] .u-radio:checked+label:after,[data-whatinput=mouse] .u-radio:checked+label:after {
    background-image: none;
    opacity: 1;
    transform: scale(1)
}

.u-input-list {
    display: inline-block;
    margin: 2.4rem 0
}

.u-input-list ol,.u-input-list ul {
    margin: 0
}

.u-input-list ol li,.u-input-list ul li {
    margin: 0;
    padding-left: 0
}

.u-input-list ol li:before,.u-input-list ul li:before {
    display: none
}

.u-input-list li+li {
    margin-top: .6rem
}

.select {
    background-color: #fff;
    border: 1px solid #bbc3d1;
    border-radius: 0;
    color: #39424a;
    display: block;
    font-size: 1.6rem;
    margin: 0;
    transition: all .3s ease;
    width: 100%;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-blue.svg);
    background-position: calc(100% - 1.4rem) calc(50% + .2rem);
    background-repeat: no-repeat;
    background-size: 14px 8px;
    height: 4.2rem;
    padding: 0 4rem 0 1.4rem
}

.select:focus {
    border-color: #019fcb
}

.select.-fitted {
    max-width: 100%;
    width: auto
}

.select[aria-invalid=true] {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-error.svg)
}

.select::-ms-expand {
    display: none
}

.select+small,fieldset+small,input+small,select+small,textarea+small {
    display: block;
    margin-top: .3rem;
    padding-left: 1.5rem
}

.select[aria-invalid=true]+small,fieldset[aria-invalid=true]+small,input[aria-invalid=true]+small,select[aria-invalid=true]+small,textarea[aria-invalid=true]+small {
    color: #bb0043
}

input[aria-invalid=true],select[aria-invalid=true],textarea[aria-invalid=true] {
    background-color: #fee0eb;
    border-color: #bb0043;
    box-shadow: 0 0 0 1px #bb0043;
    color: #bb0043
}

input[aria-invalid=true]:focus,select[aria-invalid=true]:focus,textarea[aria-invalid=true]:focus {
    border-color: #bb0043
}

.form-functionality-toggles {
    display: flex
}

.form-functionality-toggle {
    font-size: 1.5rem;
    line-height: 2.4rem;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: transparent;
    border: none;
    color: #657584;
    font-weight: 700;
    margin: 0;
    overflow: visible;
    padding: 0;
    position: relative;
    text-transform: uppercase;
    transition: all .3s ease
}

.form-functionality-toggle:focus,.form-functionality-toggle:hover {
    color: #39424a
}

.form-functionality-toggle:after {
    background-color: #39424a;
    bottom: -4px;
    content: "";
    display: block;
    height: 2px;
    left: 0;
    position: absolute;
    transform: scaleX(0);
    transition: transform .3s ease;
    width: 100%
}

.form-functionality-toggle.-selected {
    color: #39424a;
    cursor: default
}

.form-functionality-toggle.-selected:after {
    transform: scaleX(1)
}

.form-functionality-toggle+.form-functionality-toggle {
    margin-left: 3rem
}

.u-disabled {
    color: #c1c4c7
}

.u-disabled input,.u-disabled label,.u-disabled legend,.u-disabled select,.u-disabled textarea {
    color: #c1c4c7;
    cursor: not-allowed
}

.u-disabled select {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-grey.svg)
}

.u-disabled label .required {
    color: #c1c4c7
}

.u-disabled input[type=color]::-webkit-input-placeholder,.u-disabled input[type=date]::-webkit-input-placeholder,.u-disabled input[type=datetime]::-webkit-input-placeholder,.u-disabled input[type=email]::-webkit-input-placeholder,.u-disabled input[type=file]::-webkit-input-placeholder,.u-disabled input[type=number]::-webkit-input-placeholder,.u-disabled input[type=password]::-webkit-input-placeholder,.u-disabled input[type=search]::-webkit-input-placeholder,.u-disabled input[type=tel]::-webkit-input-placeholder,.u-disabled input[type=text]::-webkit-input-placeholder,.u-disabled input[type=url]::-webkit-input-placeholder {
    color: #c1c4c7
}

.u-disabled input[type=color]::-moz-placeholder,.u-disabled input[type=date]::-moz-placeholder,.u-disabled input[type=datetime]::-moz-placeholder,.u-disabled input[type=email]::-moz-placeholder,.u-disabled input[type=file]::-moz-placeholder,.u-disabled input[type=number]::-moz-placeholder,.u-disabled input[type=password]::-moz-placeholder,.u-disabled input[type=search]::-moz-placeholder,.u-disabled input[type=tel]::-moz-placeholder,.u-disabled input[type=text]::-moz-placeholder,.u-disabled input[type=url]::-moz-placeholder {
    color: #c1c4c7
}

.u-disabled input[type=color]:-ms-input-placeholder,.u-disabled input[type=date]:-ms-input-placeholder,.u-disabled input[type=datetime]:-ms-input-placeholder,.u-disabled input[type=email]:-ms-input-placeholder,.u-disabled input[type=file]:-ms-input-placeholder,.u-disabled input[type=number]:-ms-input-placeholder,.u-disabled input[type=password]:-ms-input-placeholder,.u-disabled input[type=search]:-ms-input-placeholder,.u-disabled input[type=tel]:-ms-input-placeholder,.u-disabled input[type=text]:-ms-input-placeholder,.u-disabled input[type=url]:-ms-input-placeholder {
    color: #c1c4c7
}

.u-disabled input[type=color]:-moz-placeholder,.u-disabled input[type=date]:-moz-placeholder,.u-disabled input[type=datetime]:-moz-placeholder,.u-disabled input[type=email]:-moz-placeholder,.u-disabled input[type=file]:-moz-placeholder,.u-disabled input[type=number]:-moz-placeholder,.u-disabled input[type=password]:-moz-placeholder,.u-disabled input[type=search]:-moz-placeholder,.u-disabled input[type=tel]:-moz-placeholder,.u-disabled input[type=text]:-moz-placeholder,.u-disabled input[type=url]:-moz-placeholder {
    color: #c1c4c7
}

fieldset.u-disabled+small {
    color: #c1c4c7
}

[data-whatinput=initial] .u-disabled .u-radio+label:after,[data-whatinput=mouse] .u-disabled .u-radio+label:after {
    background-color: #c1c4c7
}

.layout-container {
    background-color: #fff;
    padding: 4.2rem 1.8rem;
    position: relative;
    z-index: 2
}

.layout-container:after {
    clear: both;
    content: "";
    display: table
}

.layout-container>:first-child {
    margin-top: 0!important
}

.layout-container>:last-child {
    margin-bottom: 0!important
}

.layout-container+:not(.-lightgray):not(.-gray):not(.-dark) {
    padding-top: 0
}

.layout-container+:not(.-lightgray):not(.-gray):not(.-dark):before {
    display: table;
    content: ""
}

.layout-container.-padding-reduced {
    padding-bottom: 3.6rem;
    padding-top: 3.6rem
}

.layout-container.-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-padding-small {
    padding-bottom: 2.4rem;
    padding-top: 2.4rem
}

.layout-container.-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-padding-small-bottom {
    padding-bottom: 2.4rem
}

.layout-container.-padding-none {
    padding-bottom: 0;
    padding-top: 0
}

.layout-container.-padding-none-top {
    padding-top: 0
}

.layout-container.-padding-none-bottom {
    padding-bottom: 0
}

.layout-container.-lightgray {
    background-color: #f8f9fa
}

.layout-container.-lightgray+.layout-container:not(.-lightgray) {
    padding-top: 4.2rem
}

.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-small,.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-lightgray+.-lightgray {
    padding-top: 0
}

.layout-container.-lightgray+.-lightgray:before {
    display: table;
    content: ""
}

.layout-container.-green {
    background-color: #01a2a2
}

.layout-container.-green+.layout-container:not(.-green) {
    padding-top: 4.2rem
}

.layout-container.-green+.layout-container:not(.-green).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-green+.layout-container:not(.-green).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-green+.layout-container:not(.-green).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-green+.layout-container:not(.-green).-padding-small,.layout-container.-green+.layout-container:not(.-green).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-green+.-green {
    padding-top: 0
}

.layout-container.-green+.-green:before {
    display: table;
    content: ""
}

.layout-container.-blue {
    background-color: #019fcb
}

.layout-container.-blue+.layout-container:not(.-blue) {
    padding-top: 4.2rem
}

.layout-container.-blue+.layout-container:not(.-blue).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-blue+.layout-container:not(.-blue).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-blue+.layout-container:not(.-blue).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-blue+.layout-container:not(.-blue).-padding-small,.layout-container.-blue+.layout-container:not(.-blue).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-blue+.-blue {
    padding-top: 0
}

.layout-container.-blue+.-blue:before {
    display: table;
    content: ""
}

.layout-container.-purple {
    background-color: #963a86
}

.layout-container.-purple+.layout-container:not(.-purple) {
    padding-top: 4.2rem
}

.layout-container.-purple+.layout-container:not(.-purple).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-purple+.layout-container:not(.-purple).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-purple+.layout-container:not(.-purple).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-purple+.layout-container:not(.-purple).-padding-small,.layout-container.-purple+.layout-container:not(.-purple).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-purple+.-purple {
    padding-top: 0
}

.layout-container.-purple+.-purple:before {
    display: table;
    content: ""
}

.layout-container.-red {
    background-color: #a4123b
}

.layout-container.-red+.layout-container:not(.-red) {
    padding-top: 4.2rem
}

.layout-container.-red+.layout-container:not(.-red).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-red+.layout-container:not(.-red).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-red+.layout-container:not(.-red).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-red+.layout-container:not(.-red).-padding-small,.layout-container.-red+.layout-container:not(.-red).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-red+.-red {
    padding-top: 0
}

.layout-container.-red+.-red:before {
    display: table;
    content: ""
}

.layout-container.-royalblue {
    background-color: #4169e1
}

.layout-container.-royalblue+.layout-container:not(.-royalblue) {
    padding-top: 4.2rem
}

.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-small,.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-royalblue+.-royalblue {
    padding-top: 0
}

.layout-container.-royalblue+.-royalblue:before {
    display: table;
    content: ""
}

.layout-container.-gray {
    background: #f8f9fa url(/sites/all/themes/rotary_rotaryorg/images/concrete_seamless.jpg) 50% 0
}

.layout-container.-gray+.layout-container:not(.-gray) {
    padding-top: 4.2rem
}

.layout-container.-gray+.layout-container:not(.-gray).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-gray+.layout-container:not(.-gray).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-gray+.layout-container:not(.-gray).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-gray+.layout-container:not(.-gray).-padding-small,.layout-container.-gray+.layout-container:not(.-gray).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-gray+.-gray {
    padding-top: 0
}

.layout-container.-gray+.-gray:before {
    display: table;
    content: ""
}

.layout-container.-dark {
    background-position: 50% 0;
    background-repeat: repeat;
    background-size: 71px 85px;
    background-color: #263b4c;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-darkblue.png);
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff
}

.layout-container.-dark+.layout-container:not(.-dark) {
    padding-top: 4.2rem
}

.layout-container.-dark+.layout-container:not(.-dark).-padding-reduced {
    padding: 3.6rem 1.8rem
}

.layout-container.-dark+.layout-container:not(.-dark).-padding-reduced-top {
    padding-top: 3.6rem
}

.layout-container.-dark+.layout-container:not(.-dark).-padding-reduced-bottom {
    padding-bottom: 3.6rem
}

.layout-container.-dark+.layout-container:not(.-dark).-padding-small,.layout-container.-dark+.layout-container:not(.-dark).-padding-small-top {
    padding-top: 2.4rem
}

.layout-container.-dark+.-dark {
    padding-top: 0
}

.layout-container.-dark+.-dark:before {
    display: table;
    content: ""
}

.layout-container>.u-pull-container:first-child+* {
    margin-top: 0
}

.layout-container.-image-callout {
    padding-bottom: 0!important
}

.layout-container.-image-callout+.layout-container {
    padding-top: 4.2rem!important
}

.layout-container.-image-callout+.layout-container.-padding-small,.layout-container.-image-callout+.layout-container.-padding-small-top {
    padding-top: 2.4rem!important
}

.layout-container.-image-callout .image-callout {
    margin-left: -1.8rem;
    margin-right: -1.8rem
}

.u-grid-row {
    margin-bottom: 2.4rem;
    margin-top: 2.4rem
}

.u-grid-row+.u-grid-row {
    margin-top: 2rem
}

.u-grid-row.-no-gutter {
    margin-bottom: 0;
    margin-top: 0
}

.u-grid-row [class*=u-grid-]>:first-child {
    margin-top: 0!important
}

.u-grid-row [class*=u-grid-]>:last-child {
    margin-bottom: 0!important
}

.u-grid-row [class*=u-grid-]+[class*=u-grid-] {
    margin-bottom: 2.4rem;
    margin-top: 2.4rem
}

.accordion [role=tabpanel] {
    overflow: hidden;
    transition: height .3s ease-out,visibility 0s linear 0s;
    visibility: visible
}

.accordion [role=tabpanel][aria-hidden=true] {
    transition: height .3s ease-out,visibility 0s linear .3s;
    visibility: hidden
}

.accordion [data-accordion-content]>:first-child {
    margin-top: 0!important
}

.accordion [data-accordion-content]>:last-child {
    margin-bottom: 0!important
}

.form-accordion {
    max-width: 80rem;
    margin: 6rem auto
}

.template-story .site-main .form-accordion {
    max-width: 70rem
}

.form-accordion-tab {
    font-size: 1.8rem;
    line-height: 3rem;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #263b4c;
    border-top: 1px solid #39424a;
    font-weight: 700;
    margin: 0
}

.form-accordion-tab:first-of-type {
    border: none
}

.form-accordion-tab a {
    color: #fff;
    display: block;
    padding: .6rem 2rem;
    position: relative
}

.form-accordion-tab a:focus,.form-accordion-tab a:hover {
    background: transparent
}

.form-accordion-tab a:after,.form-accordion-tab a:before {
    content: "";
    display: block;
    height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    width: 3.6rem
}

.form-accordion-tab a:after {
    background-color: rgba(0,0,0,.2);
    z-index: 1
}

.form-accordion-tab a:before {
    background: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-white.svg) no-repeat 50% 50%;
    background-size: 14px 8px;
    transition: all .3s ease;
    z-index: 2
}

.form-accordion-tab a[aria-selected=true]:before {
    transform: rotate(180deg)
}

.form-accordion-tabpanel {
    background-color: #f2f4f6
}

.form-accordion-tabcontent {
    padding: 3rem 2rem
}

[data-animate=fade-in] {
    transition: opacity .6s ease
}

[data-animate=fade-in][data-is=ready] {
    opacity: 0
}

[data-animate=fade-in][data-is=visible] {
    opacity: 1
}

[data-animate=fade-up] {
    transition: all .6s ease
}

[data-animate=fade-up][data-is=ready] {
    opacity: 0;
    transform: translateY(5.4rem)
}

[data-animate=fade-up][data-is=visible] {
    opacity: 1;
    transform: translateY(0)
}

[data-animate=fade-down] {
    transition: all .6s ease
}

[data-animate=fade-down][data-is=ready] {
    opacity: 0;
    transform: translateY(-5.4rem)
}

[data-animate=fade-down][data-is=visible] {
    opacity: 1;
    transform: translateY(0)
}

[data-animate=blur-in] {
    transition: filter .6s ease,opacity .6s ease
}

[data-animate=blur-in][data-is=ready] {
    filter: blur(10px);
    opacity: 0
}

[data-animate=blur-in][data-is=visible] {
    filter: blur(0);
    opacity: 1
}

.article-grid {
    margin: 6rem auto
}

.article-grid:after {
    clear: both;
    content: "";
    display: table
}

.article-grid-list {
    margin: 0;
    max-width: none
}

.article-grid-list li {
    padding-left: 0
}

.article-grid-list li:before {
    display: none
}

.article-grid-list li {
    margin: 0;
    padding: 1.2rem 0
}

.article-grid-item a {
    background-color: #fff;
    border-style: solid;
    border-width: 2px 0 0;
    color: #39424a;
    display: block;
    font-weight: 400;
    height: 100%;
    overflow: hidden;
    padding: 3rem 3rem 2.4rem;
    transition: all .3s ease
}

.article-grid-item a:focus,.article-grid-item a:hover {
    box-shadow: 0 4px 18px 1px rgba(0,0,0,.2);
    transform: translateY(-4px)
}

.article-grid-item.-story a>* {
    display: block
}

.article-grid-item.-feature a {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    align-items: center;
    background-position: 50% 50%;
    background-repeat: no-repeat;
    background-size: cover;
    border: none;
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 3rem 7.2rem;
    position: relative;
    text-align: center
}

.article-grid-item.-feature a:before {
    background: linear-gradient(180deg,transparent 0,#000);
    content: "";
    display: block;
    height: 100%;
    left: 0;
    opacity: .8;
    position: absolute;
    top: 30%;
    transition: all .3s ease;
    width: 100%;
    z-index: 1
}

.article-grid-item.-feature a * {
    position: relative;
    z-index: 2
}

.article-grid-item.-news a {
    border-color: #018d8d
}

.article-grid-item.-news .article-grid-tag {
    color: #018d8d
}

.article-grid-item.-press a {
    border-color: #872175
}

.article-grid-item.-press .article-grid-tag {
    color: #872175
}

.article-grid-tag {
    font-size: 1.2rem;
    line-height: 2.4rem;
    display: block;
    font-weight: 700;
    text-transform: uppercase;
    transition: all .3s ease
}

.-feature a .article-grid-tag {
    background-color: #39424a;
    bottom: 0;
    color: #fff;
    left: 0;
    line-height: 4.8rem;
    position: absolute;
    text-align: center;
    width: 100%;
    z-index: 2
}

.article-grid-title {
    font-size: 2rem;
    line-height: 3rem;
    font-weight: 400
}

.-feature .article-grid-title {
    font-size: 2.4rem;
    line-height: 3.6rem;
    font-weight: 300;
    margin: 0;
    max-width: 100%;
    transition: all .3s ease
}

.article-grid-date {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #6a7b89
}

.article-grid-published {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: .6rem 0 0
}

.-feature .article-grid-published {
    transition: all .3s ease
}

.article-filters {
    margin-top: 6rem
}

.article-filters+.article-grid {
    margin-top: 2.4rem
}

.article-filters-search {
    position: relative
}

.article-filters-search input[type=search],.article-filters-search input[type=text] {
    border-right: none;
    width: calc(100% - 4.2rem)
}

.article-filters-search button,.article-filters-search input[type=submit] {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background: #019fcb url(/sites/all/themes/rotary_rotaryorg/images/icon-magnify-white.svg) no-repeat 50% 50%;
    background-size: 18px 18px;
    border: none;
    border-radius: 0;
    height: 4.2rem;
    margin: 0;
    padding: 0;
    position: absolute;
    right: 0;
    top: 0;
    transition: all .3s ease;
    width: 4.2rem
}

.article-filters-search button:focus,.article-filters-search button:hover,.article-filters-search input[type=submit]:focus,.article-filters-search input[type=submit]:hover {
    background-color: #018fb7
}

.story-attribution {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding-bottom: 2.4rem;
    position: relative
}

.story-attribution:after {
    background-color: #c7ced9;
    bottom: 0;
    content: "";
    display: block;
    height: 1px;
    left: 0;
    position: absolute;
    width: 50px
}

.story-attribution-author {
    display: block
}

.story-attribution-date {
    font-size: 1.2rem;
    line-height: 2.4rem;
    display: block;
    margin-top: .6rem
}

.audio {
    cursor: pointer;
    display: inline-block;
    position: relative
}

.audio button {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border: none;
    margin: 0;
    padding: 0;
    transition: all .3s ease
}

.audio[data-features=inline] {
    font-weight: 700;
    padding: 0 .6rem 0 3rem;
    text-decoration: none
}

.audio[data-features=inline]:before {
    background: url(/sites/all/themes/rotary_rotaryorg/images/audio-blue.svg) no-repeat 50% 50%;
    background-size: 18px 16px;
    content: "";
    display: block;
    height: 100%;
    left: .6rem;
    position: absolute;
    top: 0;
    width: 1.8rem
}

.audio[data-features=inline][data-is=playing]:before {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/audio-pause-blue.svg);
    background-size: 16px 16px
}

.audio[data-features=inline][data-is=paused]:before {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/audio-play-blue.svg);
    background-size: 12px 16px
}

.audio[data-features=block] {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-color: #019fcb;
    color: #fff;
    font-weight: 700;
    padding: .6rem 1rem .6rem 4.6rem;
    text-decoration: none;
    width: 100%
}

.caption .audio[data-features=block] {
    margin-top: .6rem
}

.audio[data-features=block] button {
    background: rgba(0,124,175,.4) url(/sites/all/themes/rotary_rotaryorg/images/audio-white.svg) no-repeat 50% 50%;
    background-size: 16px 14px;
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    width: 3.6rem
}

.audio[data-features=block][data-is=playing] button {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/audio-pause-white.svg);
    background-size: 14px 14px
}

.audio[data-features=block][data-is=paused] button {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/audio-play-white.svg);
    background-size: 11px 14px
}

.audio[data-features=block][min-width~="480px"] {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding: 1.8rem 2rem 1.8rem 7rem
}

.audio[data-features=block][min-width~="480px"] button {
    background-size: 25px 21px;
    width: 6rem
}

.audio[data-features=block][min-width~="480px"][data-is=playing] button {
    background-size: 21px 21px
}

.audio[data-features=block][min-width~="480px"][data-is=paused] button {
    background-size: 16px 21px
}

.audio[data-features=block]:not([data-is=playing]):not([data-is=paused]):focus button,.audio[data-features=block]:not([data-is=playing]):not([data-is=paused]):hover button {
    background-color: #007caf
}

.image-block[min-width~="700px"] .audio button {
    margin: 0
}

.callout-section {
    position: relative;
    padding: 8.5rem 0 10.5rem;
    z-index: 3;
    width: 100%;
    background-color: #fff;
    display: block;
    display: -ms-flexbox;
    overflow: hidden
}

.callout-section .callout-section-left {
    flex: 1
}

.callout-section .callout-section-left-content {
    height: 100%;
    color: #fff;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center
}

.callout-section .callout-section-left-content-holder {
    width: 100%
}

.callout-section .callout-section-left .callout-section-left-content-holder {
    margin: 6rem
}

.callout-section .callout-section-left .callout-section-left-content-holder a.u-button {
    border-radius: 50px
}

.callout-section .callout-section-left .callout-section-left-content-holder .callout-section-title {
    font-style: normal;
    font-weight: 300;
    text-align: center
}

.callout-section .callout-section-left .callout-section-left-content-holder .callout-section-description {
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 150%;
    text-align: left;
    margin: 40px 0
}

.callout-section .callout-section-right {
    position: relative
}

.callout-section .callout-section-right .homecontent-stripe {
    line-height: 0;
    height: 26rem;
    background-position: 50%;
    background-repeat: no-repeat;
    background-size: cover
}

.callout-section .callout-section-right-text {
    width: 100%;
    padding: 20px;
    background-color: #fff
}

.callout {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff;
    margin: 6rem auto
}

.callout-text {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0 2.4rem;
    padding: 3.6rem 0
}

.callout-text>:first-child {
    margin-top: 0!important
}

.callout-text>:last-child {
    margin-bottom: 0!important
}

.callout-text+.callout-text {
    border-top: 1px solid hsla(0,0%,100%,.5)
}

.callout-text * {
    width: 100%
}

.callout-text a:not(.u-button):not(.share-link) {
    color: #fff;
    text-decoration: underline
}

.callout-text a:not(.u-button):not(.share-link):focus,.callout-text a:not(.u-button):not(.share-link):hover {
    background: none
}

.callout-text [class*=heading-]+ol,.callout-text [class*=heading-]+p,.callout-text [class*=heading-]+ul {
    margin-top: 1.8rem
}

.callout-image {
    background-position: 50% 50%;
    background-repeat: no-repeat;
    background-size: cover;
    padding-bottom: 66.66667%
}

.callout-vertical {
    display: flex;
    flex-direction: column
}

.no-flexbox .callout-vertical {
    display: block
}

.no-flexbox .callout-vertical:after {
    clear: both;
    content: "";
    display: table
}

.callout-vertical-item-content {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding: 3rem 2rem
}

.callout-vertical-item-content>:first-child {
    margin-top: 0!important
}

.callout-vertical-item-content>:last-child {
    margin-bottom: 0!important
}

.callout-vertical-item-content hr {
    display: none
}

.callout-vertical-item-heading {
    font-size: 2rem;
    line-height: 3rem;
    font-weight: 400
}

.callout-vertical-item-heading a {
    font-weight: inherit
}

.callout-vertical-item-intro {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0 0 3.6rem
}

.callout-vertical-item-cta {
    margin-top: 4.8rem
}

.callout-vertical-item img {
    height: auto;
    margin: 0 0 0 -2rem;
    width: calc(100% + 4rem)
}

.callout-vertical-item picture {
    width: 100%
}

.callout-vertical-item+.callout-vertical-item {
    margin-top: 2.4rem
}

.callout-vertical-item[min-width~="480px"] .callout-vertical-item-content {
    padding: 3.6rem 6rem;
    text-align: center
}

.callout-vertical-item[min-width~="480px"] .callout-vertical-item-content hr {
    display: block;
    width: 5rem
}

.callout-vertical-item[min-width~="480px"] .callout-vertical-item-content img {
    margin: 0 0 0 -6rem;
    width: calc(100% + 12rem)
}

.callout-vertical-item[min-width~="480px"] .callout-vertical-item-content .callout-vertical-item-heading {
    margin-left: 10%;
    margin-right: 10%
}

.callout-vertical-item[min-width~="480px"] .callout-vertical-item-content .callout-vertical-item-intro {
    margin: 0 20% 5.4rem
}

.no-flexbox .callout-vertical-item {
    display: block
}

.callout-vertical-item-bordered {
    border: 10px solid #e8ebee
}

.callout-vertical-item-photo {
    color: #fff
}

.callout-vertical-item-photo .callout-vertical-item-content {
    padding-top: 0!important
}

.carousel {
    margin-left: -1.8rem;
    margin-right: -1.8rem;
    -webkit-overflow-scrolling: touch;
    overflow-x: auto;
    overflow-y: scroll;
    padding: 1rem 0;
    -ms-scroll-snap-type: mandatory;
    scroll-snap-type: mandatory;
    -ms-scroll-snap-destination: 50% 0;
    scroll-snap-destination: 50% 0;
    width: calc(100% + 3.6rem)
}

.carousel-list {
    display: flex;
    margin: 0;
    max-width: none;
    padding: 0 10vw
}

.carousel-list li {
    margin: 0;
    padding-left: 0
}

.carousel-list li:before {
    display: none
}

.carousel-item {
    line-height: 0;
    padding: 0;
    -ms-scroll-snap-coordinate: 50% 0;
    scroll-snap-coordinate: 50% 0;
    width: 80vw
}

.carousel-item-inner {
    background-color: #fff;
    margin: 0 1px
}

.carousel-item-image {
    height: 0;
    line-height: 0;
    padding-bottom: 100%;
    position: relative;
    width: 100%
}

.carousel-item-image img {
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%
}

.carousel-item-heading {
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-position: 50% 0;
    background-repeat: repeat;
    background-size: 71px 85px;
    color: #fff;
    margin: 0;
    padding: 1.2rem 0;
    text-align: center;
    text-transform: uppercase
}

.carousel-item:nth-child(4n+1) .carousel-item-heading {
    background-color: #019fcb;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-blue.png)
}

.carousel-item:nth-child(4n+2) .carousel-item-heading {
    background-color: #018d8d;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-green.png)
}

.carousel-item:nth-child(4n+3) .carousel-item-heading {
    background-color: #9b1238;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-red.png)
}

.carousel-item:nth-child(4n+4) .carousel-item-heading {
    background-color: #872175;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/geo-purple.png)
}

.carousel-item-text {
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-color: #fff;
    padding: 2.4rem 3rem
}

.carousel-item-text a {
    font-size: 1.4rem;
    line-height: 2.4rem;
    text-transform: uppercase
}

.carousel-item-text a:focus,.carousel-item-text a:hover {
    background-color: transparent;
    text-decoration: underline
}

.carousel-item-text p {
    margin: 0
}

.carousel-item-text p+p {
    margin-top: 2.4rem
}

.carousel-button-next,.carousel-button-prev {
    display: none
}

.carousel-button-next:hover,.carousel-button-prev:hover {
    background-color: rgba(0,0,0,.05);
    background-position: 50% 40%
}

.carousel-button-next {
    transform: rotate(90deg);
    margin-right: -400px;
    right: 50%
}

.carousel-button-prev {
    transform: rotate(-90deg);
    left: 50%;
    margin-left: -400px
}

.cause-navigation {
    background-color: #000;
    position: relative;
    z-index: 2
}

.cause-navigation-list {
    margin: -2.4rem 0 0;
    max-width: none;
    padding-bottom: 4.8rem;
    position: relative;
    text-align: center;
    z-index: 2
}

.cause-navigation-list li {
    margin: 0;
    padding-left: 0
}

.cause-navigation-list li:before {
    display: none
}

.cause-navigation-item+.cause-navigation-item {
    margin-top: 1.2rem
}

.cause-navigation-item a {
    font-weight: 400
}

.cause-navigation-item a:focus,.cause-navigation-item a:hover {
    background-color: rgba(0,0,0,.7);
    text-decoration: underline
}

.home-causes-image {
    display: none
}

.causes-text {
    font-weight: 300;
    font-size: 36px;
    line-height: 49px;
    letter-spacing: -.03em
}

.causes-description,.causes-text {
    font-style: normal;
    display: block;
    text-align: center;
    color: #fff
}

.causes-description {
    font-weight: 400;
    font-size: 1.8rem;
    line-height: 30px
}

.desktop-view {
    display: none
}

.desktop-view .home-causes-lists {
    width: 100%;
    margin: 0 auto;
    display: flex
}

.desktop-view .aof {
    flex: 33.33%
}

.desktop-view .aof-list {
    padding: 0 2%;
    margin: 12% 0
}

.desktop-view .aof-middle {
    padding: 0 2%
}

.desktop-view .home-causes-image {
    height: 28rem!important;
    min-height: 0!important
}

.desktop-view .home-causes-image:hover {
    transform: scale(1.1)
}

.mobile-view {
    display: none
}

.mobile-view .AOF-mobile-heading {
    padding: 1.8rem 1.8rem 5rem;
    position: relative;
    transform: translateZ(0);
    transition: all .9s ease;
    z-index: 4
}

a.causes-link {
    position: relative;
    z-index: 1
}

.desktop-view .hero-text {
    padding-bottom: 8.2rem
}

[data-collapsible-target] {
    overflow: hidden;
    transition: height .3s ease-in,visibility 0s linear 0s;
    visibility: visible
}

[data-collapsible-target][aria-hidden=true] {
    transition: height .3s ease-out,visibility 0s linear .3s;
    visibility: hidden
}

.final-call-section-container .final-call-section-image img {
    width: 100%;
    height: 440px
}

.final-call-section-content {
    width: 100%;
    z-index: 10;
    padding-top: 6rem!important;
    position: relative
}

.final-call-section-content .final-call-section-stripe {
    margin-top: -8px
}

.final-call-section-content h2 {
    font-weight: 300px;
    font-size: 36px;
    line-height: 49px;
    text-align: left
}

.final-call-section-content p {
    font-size: 20px;
    line-height: 32px
}

.final-call-section-content a.u-button {
    border-radius: 50px;
    float: left
}

li.search-results-item ul {
    margin-top: .5rem
}

li.search-results-item li.search-result-meta {
    display: inline-block
}

li.search-results-item li.search-result-meta+li:before {
    display: inline;
    content: "|";
    margin: 0 1rem
}

.hero-type {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    align-items: center;
    color: #fff;
    display: flex;
    justify-content: center;
    min-height: 17rem;
    overflow: hidden;
    position: relative;
    text-align: left;
    text-shadow: 0 0 4px rgba(0,0,0,.45);
    z-index: 1
}

.hero-type:after {
    clear: both;
    content: "";
    display: table
}

body.front .hero-type {
    height: auto
}

.hero-type .home-hero-logo {
    height: 61px;
    width: 160px
}

.hero-type .title-color-yellow {
    color: #ffc000
}

.hero-type .home-hero-title {
    font-size: 4.3rem;
    font-weight: 300;
    line-height: 4.3rem;
    margin: 1.8rem 0;
    text-shadow: 0 0 25px #000;
    text-align: left
}

.hero-type .home-hero-title>span {
    display: inline-block;
    font-size: 1.8rem;
    font-weight: 400;
    line-height: 4.3rem;
    vertical-align: middle
}

.hero-type .home-hero-title.-yellow {
    color: #f7a81b;
    text-shadow: 0 1px 0 rgba(0,0,0,.55)
}

.hero-type .home-hero-title.-white {
    color: #fff;
    text-shadow: 0 1px 0 rgba(0,0,0,.55)
}

.hero-type .hero-scroll-prompt {
    background-color: #ffc000;
    border-radius: 50%
}

.hero-type .hero-scroll-prompt:before {
    border-color: #000
}

.hero-type .hero-scroll-prompt:hover,[data-whatinput=keyboard] .hero-type .hero-scroll-prompt:focus {
    background-color: #ffc000
}

.hero-type .overlay_image {
    max-height: 200px;
    width: auto;
    z-index: 10;
    position: relative
}

.hero-type .overlay_image img {
    max-height: 200px
}

.hero-type.-title,.no-flexbox .hero-type {
    height: auto;
    min-height: 0
}

.hero-type.-slim {
    padding-bottom: 3.6rem;
    padding-top: 3.6rem
}

.hero-type.-overflow-visible {
    overflow: visible
}

.hero-type.-background-blue {
    background-color: #0050a2;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/texture-blue.png);
    background-size: 100px 100px;
    height: auto;
    text-shadow: none;
    z-index: 99
}

.hero-type.-layout-padding {
    padding: 4.2rem 1.8rem
}

.hero-type.-tall {
    align-items: flex-end;
    height: calc(100vh - 6rem)
}

.no-flexbox .hero-type.-tall {
    display: table;
    height: 100%;
    width: 100%
}

.hero-type.-tall:after {
    background: rgba(0,0,0,.4);
    bottom: 0;
    content: "";
    display: block;
    height: 100%;
    left: 0;
    position: absolute;
    width: 100%;
    z-index: 3
}

.hero-type .hero-type-bottom-space {
    width: 100%;
    height: 20px
}

.hero-type .hero-type-text {
    padding: 1.8rem;
    position: relative;
    transform: translateZ(0);
    transition: all .9s ease;
    z-index: 4
}

.hero-type .hero-type-text>:first-child {
    margin-top: 0!important
}

.hero-type .hero-type-text>:last-child {
    margin-bottom: 0!important
}

.no-flexbox .-tall .hero-type .hero-type-text {
    display: table-cell;
    vertical-align: bottom
}

.hero-type .hero-type-text>:first-child {
    transition: opacity .6s ease .9s,transform .6s ease .9s
}

.hero-type .hero-type-text>:nth-child(2) {
    transition: opacity .6s ease 1.2s,transform .6s ease 1.2s
}

.hero-type .hero-type-text>:nth-child(3) {
    transition: opacity .6s ease 1.5s,transform .6s ease 1.5s
}

.hero-type .hero-type-text>:nth-child(4) {
    transition: opacity .6s ease 1.8s,transform .6s ease 1.8s
}

.hero-type .hero-type-text>:nth-child(5) {
    transition: opacity .6s ease 2.1s,transform .6s ease 2.1s
}

.hero-type .hero-type-text>:nth-child(6) {
    transition: opacity .6s ease 2.4s,transform .6s ease 2.4s
}

.hero-type .hero-type-text>:nth-child(7) {
    transition: opacity .6s ease 2.7s,transform .6s ease 2.7s
}

.hero-type .hero-type-text>:nth-child(8) {
    transition: opacity .6s ease 3s,transform .6s ease 3s
}

.hero-type .hero-type-text>:nth-child(9) {
    transition: opacity .6s ease 3.3s,transform .6s ease 3.3s
}

.hero-type .hero-type-text>:nth-child(10) {
    transition: opacity .6s ease 3.6s,transform .6s ease 3.6s
}

.hero-type .hero-type-text a,.hero-type .hero-type-text button {
    transition: visibility 0s linear 0s;
    border-radius: 30px;
    line-height: 1rem
}

.hero-type .hero-type-text .u-link-small {
    padding: 20px;
    background: none;
    border-radius: 30px;
    border: 1px solid #fff;
    text-transform: uppercase;
    color: #fff;
    display: inline-block;
    min-width: 25rem
}

.hero-type .hero-type-text .u-link-small:hover {
    padding: 20px;
    background: none
}

.hero-type .hero-type-text.-scrolled {
    opacity: 0
}

.hero-type .hero-type-text.-scrolled a,.hero-type .hero-type-text.-scrolled button {
    transition: visibility 0s linear .9s;
    visibility: hidden
}

html.js .hero-type .hero-type-text>* {
    opacity: 0;
    transform: translateY(6%)
}

html.js .hero-type[data-is=loaded] .hero-type-text>* {
    opacity: 1;
    transform: translateY(0)
}

.hero-type .hero-type-video {
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    position: absolute;
    transform: translateX(-50%) translateY(0);
    top: 0;
    z-index: 2
}

.hero-type .hero-type-pause {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: rgba(0,0,0,.4);
    bottom: 1.8rem;
    border: none;
    color: #fff;
    display: none;
    font-size: 1.2rem;
    padding: 0 1.2rem;
    line-height: 3.6rem;
    position: absolute;
    right: 1.8rem;
    text-transform: uppercase;
    transition: opacity .3s ease,visibility 0s linear 0s;
    z-index: 4
}

[data-slideshow] .hero-type .hero-type-pause,[data-video] .hero-type .hero-type-pause {
    display: inline-block
}

[data-scroll-pause] .hero-type .hero-type-pause {
    opacity: 0;
    transition: opacity .3s ease,visibility 0s linear .3s;
    visibility: hidden
}

.hero-type .hero-type-background,.hero-type .hero-type-background-placeholder,.hero-type [data-hero-type-slide] {
    background-position-x: 30%;
    background-position-y: 30%;
    background-repeat: no-repeat;
    background-size: cover;
    display: block;
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
    max-width: 192rem;
    margin: 0 auto;
    right: 0
}

.hero-type.hero-type-mobile-display-center .hero-type-background,.hero-type.hero-type-mobile-display-center .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-center [data-hero-type-slide],.hero-type.hero-type-mobile-display-full-width .hero-type-background,.hero-type.hero-type-mobile-display-full-width .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-full-width [data-hero-type-slide] {
    background-position-x: 50%
}

.hero-type.hero-type-mobile-display-left .hero-type-background,.hero-type.hero-type-mobile-display-left .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-left [data-hero-type-slide] {
    background-position-x: 0
}

.hero-type.hero-type-mobile-display-right .hero-type-background,.hero-type.hero-type-mobile-display-right .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-right [data-hero-type-slide] {
    background-position-x: 100%
}

.hero-type .hero-type-background {
    z-index: 1
}

.hero-type .hero-type-scroll-prompt {
    animation: bouncing-arrow 2s infinite;
    animation-timing-function: ease-in-out;
    display: inline-block;
    height: 4rem;
    margin-bottom: -1.5rem;
    position: relative;
    width: 4rem
}

.hero-type .hero-type-scroll-prompt:before {
    border-color: #fff;
    border-style: solid;
    border-width: 2px 2px 0 0;
    content: "";
    display: block;
    height: 2rem;
    left: 50%;
    margin: -1.4rem 0 0 -1rem;
    position: absolute;
    top: 50%;
    transform: rotate(135deg);
    width: 2rem
}

.hero-type .hero-type-scroll-prompt:hover,[data-whatinput=keyboard] .hero-type .hero-type-scroll-prompt:focus {
    animation-play-state: paused;
    background-color: transparent
}

.hero-type [data-hero-type-slide=ready] {
    opacity: 0;
    transform: scale(1);
    transform-origin: 50%;
    z-index: 1
}

.hero-type [data-hero-type-slide=ready][data-is=current] {
    animation: scale-slide-1 5s;
    animation-timing-function: linear;
    opacity: 1;
    transform: scale(1.125);
    z-index: 3
}

.hero-type [data-hero-type-slide=ready][data-is=previous] {
    animation: scale-slide-2 3s;
    animation-timing-function: linear;
    opacity: 1;
    transform: scale(1.2);
    z-index: 2
}

.hero {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    align-items: center;
    color: #fff;
    display: flex;
    justify-content: center;
    min-height: 17rem;
    overflow: hidden;
    position: relative;
    text-align: center;
    text-shadow: 0 0 4px rgba(0,0,0,.45);
    z-index: 1
}

.hero:after {
    clear: both;
    content: "";
    display: table
}

.hero.-title,.no-flexbox .hero {
    height: auto;
    min-height: 0
}

.hero.-slim {
    padding-bottom: 3.6rem;
    padding-top: 3.6rem
}

.hero.-overflow-visible {
    overflow: visible
}

.hero.-background-blue {
    background-color: #0050a2;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/texture-blue.png);
    background-size: 100px 100px;
    height: auto;
    text-shadow: none;
    z-index: 99
}

.hero.-layout-padding {
    padding: 4.2rem 1.8rem
}

.hero.-tall {
    align-items: flex-end;
    height: calc(100vh - 6rem)
}

.no-flexbox .hero.-tall {
    display: table;
    height: 100%;
    width: 100%
}

.hero.-tall:after {
    background: rgba(0,0,0,.4);
    bottom: 0;
    content: "";
    display: block;
    height: 100%;
    left: 0;
    position: absolute;
    width: 100%;
    z-index: 3
}

body.front .hero {
    height: auto
}

.hero-text {
    padding: 1.8rem;
    position: relative;
    transform: translateZ(0);
    transition: all .9s ease;
    z-index: 4
}

.hero-text>:first-child {
    margin-top: 0!important
}

.hero-text>:last-child {
    margin-bottom: 0!important
}

.no-flexbox .-tall .hero-text {
    display: table-cell;
    vertical-align: bottom
}

.hero-text>:first-child {
    transition: opacity .6s ease .9s,transform .6s ease .9s
}

.hero-text>:nth-child(2) {
    transition: opacity .6s ease 1.2s,transform .6s ease 1.2s
}

.hero-text>:nth-child(3) {
    transition: opacity .6s ease 1.5s,transform .6s ease 1.5s
}

.hero-text>:nth-child(4) {
    transition: opacity .6s ease 1.8s,transform .6s ease 1.8s
}

.hero-text>:nth-child(5) {
    transition: opacity .6s ease 2.1s,transform .6s ease 2.1s
}

.hero-text>:nth-child(6) {
    transition: opacity .6s ease 2.4s,transform .6s ease 2.4s
}

.hero-text>:nth-child(7) {
    transition: opacity .6s ease 2.7s,transform .6s ease 2.7s
}

.hero-text>:nth-child(8) {
    transition: opacity .6s ease 3s,transform .6s ease 3s
}

.hero-text>:nth-child(9) {
    transition: opacity .6s ease 3.3s,transform .6s ease 3.3s
}

.hero-text>:nth-child(10) {
    transition: opacity .6s ease 3.6s,transform .6s ease 3.6s
}

.js .hero-text>* {
    opacity: 0;
    transform: translateY(6%)
}

[data-is=loaded] .hero-text>* {
    opacity: 1;
    transform: translateY(0)
}

.hero-text a,.hero-text button {
    transition: visibility 0s linear 0s
}

.hero-text.-scrolled {
    opacity: 0
}

.hero-text.-scrolled a,.hero-text.-scrolled button {
    transition: visibility 0s linear .9s;
    visibility: hidden
}

.messages {
    display: none
}

.hero-video {
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    position: absolute;
    transform: translateX(-50%) translateY(0);
    top: 0;
    z-index: 2
}

.hero-pause {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: rgba(0,0,0,.4);
    bottom: 1.8rem;
    border: none;
    color: #fff;
    display: none;
    font-size: 1.2rem;
    padding: 0 1.2rem;
    line-height: 3.6rem;
    position: absolute;
    right: 1.8rem;
    text-transform: uppercase;
    transition: opacity .3s ease,visibility 0s linear 0s;
    z-index: 4
}

[data-slideshow] .hero-pause,[data-video] .hero-pause {
    display: inline-block
}

[data-scroll-pause] .hero-pause {
    opacity: 0;
    transition: opacity .3s ease,visibility 0s linear .3s;
    visibility: hidden
}

.hero-background,.hero-background-placeholder,[data-hero-slide] {
    background-position: 50% 50%;
    background-repeat: no-repeat;
    background-size: cover;
    display: block;
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
    max-width: 192rem;
    margin: 0 auto;
    right: 0
}

.-tall .hero-background,.-tall .hero-background-placeholder,.-tall [data-hero-slide] {
    position: absolute
}

.hero-background-placeholder {
    background-color: #39424a;
    z-index: 0
}

.hero-background {
    z-index: 1
}

@keyframes bouncing-arrow {
    0%,20%,50%,80%,to {
        transform: translateZ(0)
    }

    40% {
        transform: translate3d(0,-10px,0)
    }

    60% {
        transform: translate3d(0,-5px,0)
    }
}

.hero-scroll-prompt {
    animation: bouncing-arrow 2s infinite;
    animation-timing-function: ease-in-out;
    display: inline-block;
    height: 4rem;
    margin-bottom: -1.5rem;
    position: relative;
    width: 4rem
}

.hero-scroll-prompt:before {
    border-color: #fff;
    border-style: solid;
    border-width: 2px 2px 0 0;
    content: "";
    display: block;
    height: 2rem;
    left: 50%;
    margin: -1.4rem 0 0 -1rem;
    position: absolute;
    top: 50%;
    transform: rotate(135deg);
    width: 2rem
}

.hero-scroll-prompt:hover,[data-whatinput=keyboard] .hero-scroll-prompt:focus {
    animation-play-state: paused;
    background-color: transparent
}

@keyframes scale-slide-1 {
    0% {
        opacity: 0;
        transform: scale(1)
    }

    60% {
        opacity: 1
    }

    to {
        transform: scale(1.125)
    }
}

@keyframes scale-slide-2 {
    0% {
        transform: scale(1.125)
    }

    to {
        transform: scale(1.2)
    }
}

[data-hero-slide=ready] {
    opacity: 0;
    transform: scale(1);
    transform-origin: 50%;
    z-index: 1
}

[data-hero-slide=ready][data-is=current] {
    animation: scale-slide-1 5s;
    animation-timing-function: linear;
    opacity: 1;
    transform: scale(1.125);
    z-index: 3
}

[data-hero-slide=ready][data-is=previous] {
    animation: scale-slide-2 3s;
    animation-timing-function: linear;
    opacity: 1;
    transform: scale(1.2);
    z-index: 2
}

@keyframes mosaicTransition {
    0% {
        opacity: 0;
        transform: translateY(2.4rem)
    }

    to {
        opacity: 1;
        transform: translateY(0)
    }
}

.hero-mosaic:after {
    clear: both;
    content: "";
    display: table
}

.hero-mosaic-item {
    font-size: 1.4rem;
    line-height: 2.4rem;
    overflow: hidden;
    position: relative
}

.hero-mosaic-item.-feature a {
    padding-top: 12rem;
    text-shadow: 0 0 4px rgba(0,0,0,.45)
}

.hero-mosaic-item .hero-background,.hero-mosaic-item .hero-background-placeholder {
    transform: scale(1.01) translateZ(0);
    transition: transform 1.5s ease
}

.hero-mosaic-item:hover .hero-background,.hero-mosaic-item:hover .hero-background-placeholder {
    transform: scale(1.1)
}

.hero-mosaic-item a {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff;
    display: block;
    font-weight: 400;
    padding: 6rem 2.4rem 2.4rem;
    position: relative;
    text-decoration: none;
    z-index: 5
}

.hero-mosaic-item a:focus,.hero-mosaic-item a:hover {
    background-color: transparent
}

[data-whatinput=keyboard] .hero-mosaic-item a:focus {
    text-decoration: underline
}

.hero-mosaic-item a:before {
    background: linear-gradient(0deg,#000 0,transparent);
    content: "";
    display: block;
    height: 100%;
    left: 0;
    opacity: .7;
    position: absolute;
    top: 0;
    transition: all .3s ease;
    width: 100%;
    z-index: 1
}

.hero-mosaic-item a p {
    margin: 0
}

.hero-mosaic-item a p+p {
    margin-top: 2.4rem
}

.hero-mosaic-item a>* {
    animation: mosaicTransition .6s forwards;
    animation-timing-function: ease-out;
    opacity: 0;
    position: relative;
    width: 100%;
    z-index: 2
}

.hero-mosaic-item:first-of-type a > * {
    animation-delay: 1.2s
}

.hero-mosaic-item:nth-of-type(2) a>* {
    animation-delay: 1.5s
}

.hero-mosaic-item:nth-of-type(3) a>* {
    animation-delay: 1.8s
}

.hero-mosaic-title {
    font-size: 2.4rem;
    line-height: 3.6rem;
    font-weight: 400;
    margin: 0
}

.hero-mosaic-dateline {
    font-size: 1.3rem;
    line-height: 2.4rem;
    margin: 0
}

.hero-callout {
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-color: hsla(0,0%,100%,.5);
    padding: 4.8rem 2rem
}

.hero-callout>:first-child {
    margin-top: 0!important
}

.hero-callout>:last-child {
    margin-bottom: 0!important
}

.hero-callout a:not(.u-button):focus,.hero-callout a:not(.u-button):hover {
    background-color: transparent;
    text-decoration: underline
}

.hero-callout p:last-of-type {
    margin-bottom: 0
}

.hero-callout[min-width~="400px"] {
    padding-left: 4rem;
    padding-right: 4rem
}

.hero-callout[min-width~="580px"] {
    padding-left: 15%;
    padding-right: 15%
}

.homecontent-stripe {
    border: 0 solid #fff
}

.homecontent-stripe-top {
    border-top-width: 6px
}

.homecontent-stripe-bottom {
    border-bottom-width: 6px
}

.homecontent-stripe-blue {
    border-color: #019fcb
}

.homecontent-stripe-green {
    border-color: #01a2a2
}

.homecontent-stripe-purple {
    border-color: #963a86
}

.homecontent-stripe-red {
    border-color: #a4123b
}

.homecontent-stripe-darkblue {
    border-color: #263b4c
}

.homecontent-stripe-orange {
    border-color: #f6be5a
}

.image-callout {
    background-color: transparent;
    position: relative;
    z-index: 2
}

.image-callout[data-init] {
    overflow: hidden
}

.image-callout[data-init] img {
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translateX(-50%) translateY(-50%);
    z-index: 1
}

.image-callout[data-features*=text-]:after {
    background: rgba(0,0,0,.35);
    content: "";
    display: block;
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    transition: opacity .6s ease;
    width: 100%;
    z-index: 2
}

.image-callout[data-caption-visible=true]:after {
    opacity: 0
}

.image-callout[data-features*=text-none]:after {
    background: linear-gradient(180deg,#fff 0,hsla(0,0%,100%,0) 35%)
}

.image-callout[data-features*=overlay-none]:after {
    display: none!important
}

.image-callout .u-container {
    z-index: 5
}

.image-callout-text-container {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    align-items: center;
    color: #fff;
    display: flex;
    height: 100%;
    justify-content: center;
    left: 0;
    position: absolute;
    text-align: left;
    top: 0;
    width: 100%;
    z-index: 5
}

a.image-callout-text-container:focus,a.image-callout-text-container:hover {
    background-color: transparent
}

.image-callout-article,.image-callout-cta,.image-callout-quote,.image-callout-text {
    padding: 4.8rem 2.4rem;
    max-width: 90rem;
    transition: all .6s ease
}

.image-callout-article>:first-child,.image-callout-cta>:first-child,.image-callout-quote>:first-child,.image-callout-text>:first-child {
    margin-top: 0!important
}

.image-callout-article>:last-child,.image-callout-cta>:last-child,.image-callout-quote>:last-child,.image-callout-text>:last-child {
    margin-bottom: 0!important
}

.image-callout[data-init] .image-callout-article,.image-callout[data-init] .image-callout-cta,.image-callout[data-init] .image-callout-quote,.image-callout[data-init] .image-callout-text {
    opacity: 0;
    transform: translateY(10%)
}

.image-callout[data-in-view] .image-callout-article,.image-callout[data-in-view] .image-callout-cta,.image-callout[data-in-view] .image-callout-quote,.image-callout[data-in-view] .image-callout-text {
    opacity: 1;
    transform: translateY(0)
}

.image-callout[data-caption-visible=true] .image-callout-article,.image-callout[data-caption-visible=true] .image-callout-cta,.image-callout[data-caption-visible=true] .image-callout-quote,.image-callout[data-caption-visible=true] .image-callout-text {
    opacity: 0;
    transform: translateY(-50%)
}

.no-flexbox .image-callout-article,.no-flexbox .image-callout-cta,.no-flexbox .image-callout-quote,.no-flexbox .image-callout-text {
    display: table-cell;
    vertical-align: middle
}

.image-callout[data-features*=text-left] .image-callout-article,.image-callout[data-features*=text-left] .image-callout-cta,.image-callout[data-features*=text-left] .image-callout-quote,.image-callout[data-features*=text-left] .image-callout-text,.image-callout[data-features*=text-right] .image-callout-article,.image-callout[data-features*=text-right] .image-callout-cta,.image-callout[data-features*=text-right] .image-callout-quote,.image-callout[data-features*=text-right] .image-callout-text {
    max-width: none
}

.image-callout[data-features*=text-heading] .image-callout-article,.image-callout[data-features*=text-heading] .image-callout-cta,.image-callout[data-features*=text-heading] .image-callout-quote,.image-callout[data-features*=text-heading] .image-callout-text {
    padding: 9.6rem 4.8rem
}

.image-callout-article {
    font-size: 1.2rem;
    line-height: 2.4rem;
    padding-bottom: 1.8rem;
    padding-top: 1.8rem
}

.image-callout-article p {
    margin: 0
}

.image-callout-article-heading {
    font-size: 2.4rem;
    line-height: 3.6rem;
    font-weight: 300;
    margin: 0 auto;
    max-width: 55rem
}

.image-callout-cta {
    font-size: 2rem;
    line-height: 3rem
}

.image-callout-cta p {
    margin-left: 2rem;
    margin-right: 2rem
}

.image-callout-quote {
    font-size: 2.4rem;
    line-height: 3.6rem
}

.image-callout-quote-attribution {
    font-size: 2rem;
    line-height: 3rem;
    margin-top: 3.6rem
}

.image-callout-img-container {
    margin: 0;
    padding: 0
}

.image-callout-caption {
    font-size: 1.4rem;
    line-height: 2.4rem;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: rgba(57,66,74,.9);
    bottom: 0;
    color: #fff;
    left: 0;
    padding: 1.8rem 1.8rem 1.8rem 5.4rem;
    position: absolute;
    transition: all .3s ease;
    width: 100%;
    z-index: 5
}

.image-callout-caption p {
    margin: 0;
    max-width: none
}

.image-callout[data-caption-visible=false] .image-callout-caption {
    transform: translateY(100%);
    transition: all .3s ease
}

.image-callout-attribution {
    font-size: 1.4rem;
    line-height: 2.4rem
}

.image-callout-caption-toggle {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background: transparent url(/sites/all/themes/rotary_rotaryorg/images/icon-info.svg) no-repeat 50% 50%;
    background-size: 20px 20px;
    border: none;
    border-radius: 50%;
    height: 20px;
    left: 2.4rem;
    margin: 0;
    opacity: .6;
    padding: 0;
    position: absolute;
    top: 2.4rem;
    transition: top .3s ease,opacity .3s ease;
    width: 20px;
    z-index: 10
}

.image-callout-caption-toggle:focus,.image-callout-caption-toggle:hover {
    opacity: 1
}

.image-callout[data-caption-visible=false] .image-callout-caption-toggle {
    top: calc(-10px - 2.4rem);
    transition: all .3s ease,opacity .3s ease
}

.image-block {
    display: block;
    line-height: 0;
    margin: 6rem auto
}

.image-block img {
    height: auto;
    width: 100%
}

.image-block img+img {
    margin-top: 1.2rem
}

.image-block p {
    max-width: none
}

.image-block *+.image-block-row {
    margin-top: 1.2rem
}

.image-block .image-block-row>img {
    float: left;
    margin-top: 0;
    max-width: calc(50% - .6rem)
}

.image-block .image-block-row>img:first-child {
    margin-right: .6rem
}

.image-block .image-block-row>img:nth-child(2) {
    margin-left: .6rem
}

.image-block[min-width~="700px"] *+:not(.caption) {
    margin-top: 2.4rem
}

.image-block[min-width~="700px"] .image-block-row>img {
    margin-top: 0;
    max-width: calc(50% - 1.2rem)
}

.image-block[min-width~="700px"] .image-block-row>img:first-child {
    margin-right: 1.2rem
}

.image-block[min-width~="700px"] .image-block-row>img:nth-child(2) {
    margin-left: 1.2rem
}

.image-block-row {
    display: block
}

.image-block-row:after {
    clear: both;
    content: "";
    display: table
}

.image-block-container {
    margin: 6rem auto
}

.image-block-container:after {
    clear: both;
    content: "";
    display: table
}

.image-block-container .image-block {
    margin-bottom: 0;
    margin-top: 0
}

.image-block-container .image-block+.image-block {
    margin-top: 6rem
}

.image-block-container[min-width~="480px"] {
    display: flex
}

.image-block-container[min-width~="480px"] .caption-text {
    border-bottom: none
}

.image-block-container[min-width~="480px"] .image-block {
    border-bottom: 1px solid #c7ced9;
    margin-bottom: 0;
    margin-top: 0;
    max-width: calc(50% - .9rem)
}

.image-block-container[min-width~="480px"] .image-block:first-child {
    margin-right: 1.8rem
}

.image-block-container[min-width~="700px"] .image-block {
    max-width: calc(50% - 1.5rem)
}

.image-block-container[min-width~="700px"] .image-block:first-child {
    margin-right: 3rem
}

.caption-text {
    font-size: 1.4rem;
    line-height: 2.4rem;
    border-bottom: 1px solid #c7ced9;
    display: block;
    padding-bottom: 1.2rem;
    padding-top: 1.2rem
}

.caption-text:after {
    clear: both;
    content: "";
    display: table
}

.caption-text.rotary-identifier {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/rotary-logo.svg);
    background-position: 0 1.5rem;
    background-repeat: no-repeat;
    background-size: 18px 18px;
    padding-left: 2.4rem
}

.-info-graphic .caption-text {
    font-size: 1.4rem;
    line-height: 2.4rem;
    border-bottom: none;
    text-align: center
}

.caption-text p {
    margin: 0
}

.caption-text p+p {
    margin-top: .6rem
}

.caption-text .caption-attribution {
    font-size: 1.2rem;
    line-height: 2.4rem
}

.caption-text[min-width~="700px"] {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding-bottom: 2.4rem;
    padding-top: 2.4rem
}

.caption-text[min-width~="700px"] p+p {
    margin-top: 1.2rem
}

.caption-text[min-width~="700px"] .caption-attribution {
    font-size: 1.4rem;
    line-height: 2.4rem
}

.impact-narrative-image {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    display: flex;
    width: 100%;
    justify-content: center;
    min-height: 840px;
    overflow: hidden;
    position: relative;
    object-fit: none;
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover
}

.impact-narrative-image:after {
    clear: both;
    content: "";
    display: table
}

.final-call-container .final-call-content {
    margin-top: 10rem;
    max-width: 50rem;
    text-align: center
}

.final-call-container .final-call-content p {
    font-style: italic
}

.final-call-container .final-call-content a {
    color: #39424a;
    font-weight: 300;
    -webkit-tap-highlight-color: transparent;
    text-decoration: none;
    border-bottom: 2px solid #bec4c9;
    transition: background .3s ease,color .3s ease;
    line-height: 5.23rem
}

.final-call-container .final-call-content a .arrow {
    border: solid #019fcb;
    border-width: 0 2px 2px 0;
    display: inline-block;
    padding: 2px;
    margin-bottom: 2px
}

.final-call-container .final-call-content a .right {
    transform: rotate(-45deg);
    -webkit-transform: rotate(-45deg)
}

.final-call-container .final-call-content a:hover {
    background: none
}

.stat-background-img {
    background-attachment: fixed
}

.impact-stat-list .fadeInBottom {
    opacity: 0;
    transition: opacity .6s ease,transform .6s ease
}

.impact-stat-list .fadeOutBottom {
    opacity: 1;
    transform: translateY(0)
}

#statset-description,div#statset {
    color: #018d8d
}

#statset-description--2,div#statset--2 {
    color: #872175
}

#statset-description--3,div#statset--3 {
    color: #dd9400
}

.title-text {
    text-align: right
}

.title-img {
    text-align: left
}

.text-stat-title {
    font-style: normal;
    font-weight: 700;
    line-height: 2.2rem;
    text-align: center;
    letter-spacing: .01em;
    text-transform: uppercase;
    margin-bottom: 0
}

.stat-set {
    padding: 0 1%;
    margin: 0 3% 2.5rem;
    flex-basis: 33.33%
}

.stat-suffix {
    font-weight: 700;
    white-space: nowrap
}

.impact-stat-description,.stat-suffix {
    font-style: normal;
    text-align: center;
    letter-spacing: .01em
}

.impact-stat-description {
    font-weight: 400;
    font-size: 1.8px;
    line-height: 2.5rem;
    overflow-y: hidden;
    color: #39424a
}

.impact-stat-description p {
    margin-top: .8rem;
    margin-left: 2.5rem;
    margin-right: 2.5rem
}

.stat-wrapper-description {
    padding: .1rem 4% 1rem;
    width: 100%;
    background: #fff
}

.title-text .impact-stat-number {
    font-style: normal;
    font-weight: 700;
    font-size: 4.5rem;
    line-height: 6.13rem;
    text-align: right;
    letter-spacing: .01em
}

.impact-stat-number {
    margin-bottom: 0;
    margin-top: 0;
    display: block;
    white-space: nowrap
}

.custom-u-width {
    width: 100%;
    margin: 0 auto
}

.link-dropdown {
    background-color: #fff;
    position: relative
}

p+.link-dropdown {
    margin-top: -1.2rem
}

.link-dropdown-toggle {
    font-size: 1.8rem;
    line-height: 2.6rem;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: #fff;
    border: none;
    color: #019fcb;
    font-weight: 700;
    height: 6rem;
    padding: 0 2rem;
    position: relative;
    text-align: left;
    transition: color .3s ease;
    width: 100%;
    z-index: 10001
}

.link-dropdown-toggle:after {
    background: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-blue.svg) no-repeat 50% 50%;
    background-size: 14px 8px;
    content: "";
    display: block;
    height: 8px;
    margin-top: -4px;
    position: absolute;
    right: 20px;
    top: 50%;
    width: 14px
}

.site-footer .link-dropdown-toggle {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #5e717d;
    height: 4.8rem;
    text-align: center
}

.site-footer .link-dropdown-toggle:after {
    display: none
}

[data-is=open] .link-dropdown-toggle {
    color: #c7ced9
}

[data-is=open] .link-dropdown-toggle:before {
    background-color: #c7ced9;
    bottom: 0;
    content: "";
    display: block;
    height: 1px;
    left: 0;
    position: absolute;
    width: 100%
}

[data-is=open] .link-dropdown-toggle:after {
    transform: rotate(180deg)
}

[data-features=position-up][data-is=open] .link-dropdown-toggle:before {
    bottom: auto;
    top: 0
}

.link-dropdown-list {
    left: 0;
    margin: 0;
    position: absolute;
    padding-top: 6rem;
    top: 0;
    transform: translateY(-.6rem);
    transition: opacity .3s ease,transform .15s ease,visibility 0s linear .3s;
    width: 100%;
    z-index: 10000
}

.link-dropdown-list li {
    margin: 0;
    padding-left: 0
}

.link-dropdown-list li:before {
    display: none
}

.js .link-dropdown-list {
    opacity: 0;
    visibility: hidden
}

.site-footer .link-dropdown-list {
    padding-top: 4.8rem
}

[data-features=position-up] .link-dropdown-list {
    bottom: 0;
    padding-top: 0;
    padding-bottom: 6rem;
    top: auto;
    transform: translateY(.6rem)
}

.site-footer [data-features=position-up] .link-dropdown-list {
    padding-bottom: 4.8rem
}

[data-is=open] .link-dropdown-list {
    box-shadow: 0 3px 16px rgba(0,0,0,.15);
    opacity: 1;
    transform: translateY(0);
    transition: opacity .3s ease,transform .15s ease,visibility 0s linear 0s;
    visibility: visible
}

.link-dropdown-item {
    margin: 0
}

.link-dropdown-item a {
    background-color: #fff;
    color: #39424a;
    display: block;
    font-weight: 400;
    padding: .9rem 2rem
}

.link-dropdown-item a:focus,.link-dropdown-item a:hover {
    background-color: #f8f9fa;
    color: #019fcb
}

.modal-trigger.-inline {
    background-position: .6rem .36rem;
    background-repeat: no-repeat;
    display: inline-block;
    padding: 0 .6rem;
    transition: background-color .3s ease,color .3s ease
}

.modal-trigger.-inline.-hover {
    background-color: #e5f5fa
}

.modal-trigger.-inline.-image {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/icon-magnify-blue.svg);
    background-size: 18px 18px;
    padding-left: calc(18px + 1.2rem)
}

.modal-trigger.-inline.-slideshow {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/slideshow-blue.svg);
    background-size: 20px 18px;
    padding-left: calc(20px + 1.2rem)
}

.modal-trigger.-inline.-video {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/video-play-blue.svg);
    background-position: .6rem 0.46rem;
    background-size: 18px 18px;
    padding-left: calc(18px + 1.2rem)
}

.modal-trigger.-inline.-launch {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/launch-white.svg);
    background-size: 18px 18px;
    padding-left: calc(20px + 1.2rem)
}

.modal-trigger.-block {
    display: block;
    position: relative
}

.modal-trigger.-block:after {
    background-color: rgba(57,66,74,.4);
    background-position: 50% 50%;
    background-repeat: no-repeat;
    bottom: 0;
    content: "";
    display: block;
    height: 4rem;
    left: 0;
    position: absolute;
    transition: all .3s ease;
    width: 4rem;
    z-index: 2
}

.modal-trigger.-block.-image:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/icon-magnify-white.svg);
    background-size: 25px 25px
}

.modal-trigger.-block.-slideshow:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/slideshow-white.svg);
    background-size: 25px 22px
}

.modal-trigger.-block.-video:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/video-play-white.svg);
    background-size: 25px 25px
}

.modal-trigger.-block.-launch:after {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/launch-white.svg);
    background-size: 25px 25px
}

.modal-trigger.-block.-hover:after {
    background-color: rgba(57,66,74,.9)
}

.modal-trigger-caption {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-size: 1.4rem;
    line-height: 2.4rem;
    background-color: rgba(57,66,74,.4);
    bottom: 0;
    color: #fff;
    font-weight: 400;
    left: 40px;
    line-height: 40px;
    opacity: 0;
    overflow: hidden;
    padding: 0 .5rem;
    position: absolute;
    text-indent: -100%;
    text-overflow: ellipsis;
    transition: all .3s ease;
    white-space: nowrap;
    width: calc(100% - 40px)
}

.-hover .modal-trigger-caption {
    background-color: rgba(57,66,74,.9);
    opacity: 1;
    text-indent: 0
}

.modal-container {
    background-color: hsla(0,0%,100%,0);
    height: 0;
    left: 0;
    overflow-x: hidden;
    overflow-y: hidden;
    position: fixed;
    top: 0;
    transition: background .3s ease,height 0s linear .3s,overflow 0s linear 0s,visibility 0s linear .3s,width 0s linear .3s;
    visibility: hidden;
    width: 0;
    z-index: 10000
}

.modal-container.-modal-open {
    background-color: hsla(0,0%,100%,.95);
    height: 100%;
    -webkit-overflow-scrolling: touch;
    overflow-y: auto;
    transition: background .3s ease,height 0s linear 0s,overflow 0s linear .3s,visibility 0s linear 0s,width 0s linear 0s;
    visibility: visible;
    width: 100%
}

.modal-content {
    margin: 0 auto;
    opacity: 0;
    padding-top: 7.2rem;
    transition: opacity .6s ease;
    width: calc(100% - 1.8rem)
}

.-modal-open .modal-content {
    opacity: 1;
    transition: opacity .6s ease
}

.modal-content .image-block,.modal-content .responsive-video {
    margin: 0
}

.modal-content .slideshow {
    margin-top: 0
}

.modal-content .slideshow-caption-container {
    margin-bottom: 0
}

.modal-close {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: transparent;
    border: none;
    border-radius: 50%;
    display: none;
    height: 4.2rem;
    position: absolute;
    right: 1.5rem;
    top: 1.5rem;
    transition: all .3s ease;
    width: 4.2rem
}

.-modal-open .modal-close {
    display: block
}

.modal-close:after,.modal-close:before {
    background-color: #39424a;
    content: "";
    display: block;
    height: 3rem;
    left: 50%;
    margin: -1.5rem 0 0 -1px;
    position: absolute;
    top: 50%;
    transform-origin: center center;
    transition: all .3s ease;
    width: 2px
}

.modal-close:before {
    transform: rotate(45deg)
}

.modal-close:after {
    transform: rotate(-45deg)
}

.modal-close:focus,.modal-close:hover {
    background-color: #e5f5fa
}

.modal-close:focus:after,.modal-close:focus:before,.modal-close:hover:after,.modal-close:hover:before {
    background-color: #019fcb
}

[data-whatinput=keyboard] .modal-close:focus {
    box-shadow: 0 0 10px 6px #e6ad00
}

.modal-close-alt {
    display: none
}

.modal-close-alt button {
    background-color: transparent;
    text-decoration: underline;
    font-size: 1.3rem;
    line-height: 2.4rem;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border: none;
    color: #019fcb;
    display: inline-block;
    font-weight: 700;
    margin: 0;
    padding: 0 .6rem;
    text-transform: uppercase;
    transition: all .3s ease
}

.modal-close-alt button:focus,.modal-close-alt button:hover {
    background-color: #e5f5fa;
    text-decoration: none
}

[data-whatinput=keyboard] .modal-close-alt button:focus {
    box-shadow: 0 0 10px 6px #e6ad00
}

.-modal-open .modal-close-alt {
    display: block
}

.news-features {
    background-color: #fff;
    position: relative;
    z-index: 2;
    padding: 6rem 0!important
}

.news-features-container {
    height: auto
}

.news-features-container h2,.news-features-container h3,.news-features-container h4,.news-features-container h5 {
    padding: 0;
    margin: 0
}

.news-features-container .hero-mosaic-item {
    width: 100%;
    height: auto
}

.news-features-container .-feature {
    transition-delay: .6s!important
}

.news-features-container h2 {
    font-weight: 100!important;
    margin: 0 0 .99rem;
    line-height: 1.1
}

h2.news-features-title {
    font-weight: 300!important;
    padding: .3rem 0 6rem;
    text-align: center;
    font-size: 3.6rem
}

.page-cards {
    margin: 6rem auto;
    max-width: 110rem;
    padding: 0
}

.page-cards li {
    margin: 0;
    padding-left: 0
}

.page-cards li:before {
    display: none
}

.page-card {
    font-size: 1.4rem;
    line-height: 2.4rem;
    padding: 0;
    text-align: center
}

.page-card[data-module=in-view] {
    opacity: 0;
    transform: translateY(1.8rem);
    transition: all .6s ease
}

.page-card[data-is=visible] {
    opacity: 1;
    transform: translateY(0)
}

.page-card+.page-card {
    margin-top: 1.2rem
}

.page-card-text {
    background-color: #fff;
    border-bottom-style: solid;
    border-bottom-width: 4px;
    color: #39424a;
    display: block;
    padding: 0 3rem 2.4rem;
    text-align: left
}

.page-card-text:last-child {
    margin-bottom: 0
}

.-blue .page-card-text {
    border-bottom-color: #019fcb
}

.-green .page-card-text {
    border-bottom-color: #01a2a2
}

.-purple .page-card-text {
    border-bottom-color: #963a86
}

.-red .page-card-text {
    border-bottom-color: #a4123b
}

.-darkblue .page-card-text {
    border-bottom-color: #263b4c
}

.page-card-text-heading {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff;
    max-width: none;
    margin: 0 -3rem 3.6rem;
    padding: 3.6rem 3rem;
    text-align: center
}

.-blue .page-card-text-heading {
    background-color: #019fcb
}

.-green .page-card-text-heading {
    background-color: #01a2a2
}

.-purple .page-card-text-heading {
    background-color: #963a86
}

.-red .page-card-text-heading {
    background-color: #a4123b
}

.-darkblue .page-card-text-heading {
    background-color: #263b4c
}

.page-card-content {
    background-color: #fff;
    color: #39424a;
    display: block;
    font-weight: 400;
    padding: 2.4rem;
    transform: translateZ(0);
    transition: all .3s ease
}

.page-card-content>:first-child {
    margin-top: 0!important
}

.page-card-content>:last-child {
    margin-bottom: 0!important
}

.page-card-content:focus,.page-card-content:hover {
    background-color: #fff;
    box-shadow: 0 4px 18px 1px rgba(0,0,0,.2);
    text-decoration: none;
    transform: translateY(-4px)
}

.page-card-content p {
    max-width: none;
    padding: 0 1.8rem
}

.page-card-image {
    display: none
}

.page-card-heading {
    margin-top: 0;
    max-width: none;
    padding: 0 1.8rem
}

.pagination {
    align-items: center;
    color: #5e717d;
    display: flex;
    height: 3rem;
    justify-content: center
}

.pagination li {
    padding-left: 0
}

.pagination li:before {
    display: none
}

.pagination li {
    margin: 0
}

.pagination li.current a {
    background-color: #019fcb;
    border-color: #019fcb;
    color: #fff
}

.pagination li+li {
    margin-left: .4rem
}

.pagination li>span,.pagination li a {
    background-color: transparent;
    border: 1px solid transparent;
    box-sizing: content-box;
    display: block;
    font-weight: 400;
    line-height: 2.8rem;
    text-align: center;
    min-width: 2.8rem
}

.pagination li a {
    color: #019fcb;
    transition: all .3s ease
}

.pagination li a:focus,.pagination li a:hover {
    border-color: #019fcb
}

.related {
    border-top: 1px solid #c7ced9;
    margin: 6rem auto;
    max-width: 100rem;
    padding-top: 3.6rem
}

.related:after {
    clear: both;
    content: "";
    display: table
}

.related * {
    max-width: none
}

.related a {
    color: #0050a2;
    font-weight: 400
}

.related a:focus,.related a:hover {
    background-color: transparent;
    text-decoration: underline
}

.related ul {
    font-size: 1.4rem;
    line-height: 2.4rem
}

.related [class*=heading-] {
    margin-bottom: 1.8rem
}

.related-resources>:first-child,.related-stories-feature>:first-child,.related-stories>:first-child {
    margin-top: 0!important
}

.related-resources>:last-child,.related-stories-feature>:last-child,.related-stories>:last-child {
    margin-bottom: 0!important
}

.related-stories-feature img {
    display: block;
    height: auto;
    margin: 0 0 1.8rem;
    width: 100%
}

.related-resources {
    margin-top: 3.6rem
}

.responsive-video {
    margin-bottom: 6rem;
    margin-top: 6rem
}

.responsive-video figcaption {
    font-weight: 700;
    padding: 1.2rem 0 0;
    text-align: center
}

.responsive-video figcaption>:first-child {
    margin-top: 0!important
}

.responsive-video figcaption>:last-child {
    margin-bottom: 0!important
}

.responsive-video figcaption p {
    margin-bottom: 1.2rem;
    margin-top: 1.2rem
}

.responsive-video.u-width-full figcaption {
    padding-left: 1.8rem;
    padding-right: 1.8rem
}

.responsive-video.u-width-full figcaption p {
    max-width: 80rem
}

.template-story .site-main .responsive-video.u-width-full figcaption p {
    max-width: 70rem
}

.responsive-video-wrapper {
    height: 0;
    line-height: 0;
    padding: 0;
    position: relative;
    width: 100%
}

.responsive-video-media {
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%
}

body.page-content-search #page-title {
    float: left;
    padding-left: calc((100vw - 95rem) / 3)
}

.rotary-federated-solr-client {
    border-top: 2px solid hsla(207,9%,77%,.6)
}

.rotary-federated-solr-client .search-form-container,.rotary-federated-solr-client .search-results-container {
    padding-top: 3rem;
    padding-bottom: 3rem
}

.rotary-federated-solr-client .search-form-container {
    background-color: #edeeef;
    border-right-width: 1px;
    padding: 3rem
}

.rotary-federated-solr-client .search-form-container form {
    margin-bottom: 1rem
}

.rotary-federated-solr-client .search-form-container label {
    margin-bottom: .75rem
}

.rotary-federated-solr-client .search-results-container {
    opacity: 1;
    position: relative;
    padding: 3rem 1.5rem
}

.rotary-federated-solr-client.loading .search-results-container {
    opacity: .5
}

.rotary-federated-solr-client.loading .search-results-container:after {
    position: absolute;
    top: 20px;
    left: 50%;
    width: 200px;
    height: 200px;
    content: "loading..."
}

.rotary-federated-solr-client .no-query-message,.rotary-federated-solr-client .results-count {
    padding-top: .75rem;
    padding-bottom: .75rem;
    margin: 0;
    font-size: 1.4rem
}

.rotary-federated-solr-client .no-query-message {
    display: block
}

.rotary-federated-solr-client.has-search-active .no-query-message,.rotary-federated-solr-client .results-count {
    display: none
}

.rotary-federated-solr-client.has-search-active .results-count {
    display: block
}

.rotary-federated-solr-client input[name=query] {
    padding-top: .75rem;
    padding-left: 3rem;
    padding-bottom: .75rem;
    margin-bottom: 2.4rem
}

.rotary-federated-solr-client input[name=query]::-webkit-input-placeholder {
    color: #39424a;
    font-size: 1.5rem;
    font-weight: 200;
    opacity: 1
}

.rotary-federated-solr-client input[name=query]::-moz-placeholder {
    color: #39424a;
    font-size: 1.5rem;
    font-weight: 200;
    opacity: 1
}

.rotary-federated-solr-client input[name=query]:-ms-input-placeholder {
    color: #39424a;
    font-size: 1.5rem;
    font-weight: 200;
    opacity: 1
}

.rotary-federated-solr-client input[name=query]::-ms-input-placeholder {
    opacity: 1
}

.rotary-federated-solr-client input[name=query]::placeholder {
    color: #39424a;
    font-size: 1.5rem;
    font-weight: 200;
    opacity: 1
}

.rotary-federated-solr-client input[name=query]:-ms-input-placeholder {
    color: #39424a!important;
    font-size: 1.5rem!important;
    font-weight: 200!important
}

.rotary-federated-solr-client input[name=query]::-ms-input-placeholder {
    color: #39424a;
    font-size: 1.5rem;
    font-weight: 200
}

.rotary-federated-solr-client .submit-button {
    min-width: 100%;
    margin-bottom: 1rem
}

.rotary-federated-solr-client .facets {
    display: none;
    margin: 2.4rem 0
}

.rotary-federated-solr-client.has-search-active .facets {
    display: block
}

.rotary-federated-solr-client .reset-button-container {
    text-align: center
}

.rotary-federated-solr-client .search-results,.rotary-federated-solr-client .search-results>li {
    margin: 0;
    padding: 0;
    list-style: none
}

.rotary-federated-solr-client .search-results {
    border-top-width: 3px;
    display: none
}

.rotary-federated-solr-client .search-results h3 {
    margin: 0
}

.rotary-federated-solr-client .search-results li:before {
    content: none
}

.rotary-federated-solr-client.has-search-active .search-results {
    display: block
}

.rotary-federated-solr-client ul.search-results {
    font-size: 1.5rem;
    border-top: 3px solid #bec4c9
}

.rotary-federated-solr-client ul.search-results>li {
    padding-top: 1rem;
    border-bottom: 1px solid #bec4c9
}

.rotary-federated-solr-client ul.search-results>li a.link {
    font-weight: 400
}

.rotary-federated-solr-client ul.search-results .metadata {
    opacity: .65
}

.rotary-federated-solr-client ul.cda-links,.rotary-federated-solr-client ul.cda-links>li {
    list-style: none;
    padding: 0;
    margin: 0
}

.rotary-federated-solr-client ul.cda-links>li a {
    font-weight: 400
}

.rotary-federated-solr-client .pagination {
    flex-wrap: wrap
}

.rotary-federated-solr-client .content-type-select,.rotary-federated-solr-client .document-select,.rotary-federated-solr-client .language-select {
    min-width: 350px;
    min-height: 38px;
    border: 1px solid #c7ced9;
    position: relative;
    padding: .1875rem .5rem;
    background: #fff;
    margin-top: 10px;
    margin-bottom: 13px
}

.rotary-federated-solr-client .content-type-select:after,.rotary-federated-solr-client .document-select:after,.rotary-federated-solr-client .language-select:after {
    border-color: #019fcb;
    border-style: solid;
    border-width: 0 3px 3px 0;
    padding: 3px;
    transform: rotate(45deg);
    position: absolute;
    top: 32%;
    right: 16px;
    content: "";
    pointer-events: none
}

.rotary-federated-solr-client .content-type-select select,.rotary-federated-solr-client .document-select select,.rotary-federated-solr-client .language-select select {
    width: 100%;
    border: 0;
    background: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    appearance: none
}

.rotary-federated-solr-client .search-icon {
    display: block;
    position: absolute;
    padding-top: 10px;
    padding-left: 6px
}

.rotary-federated-solr-client .search-icon:after,.rotary-federated-solr-client .search-icon:before {
    content: "";
    display: block;
    position: absolute;
    transform-origin: center center
}

.rotary-federated-solr-client .search-icon:before {
    border: 2px solid #019fcb;
    border-radius: 50%;
    left: 1rem;
    top: 12px;
    height: 12px;
    width: 12px
}

.rotary-federated-solr-client .search-icon:after {
    background-color: #019fcb;
    border-radius: 0 2px 2px 0;
    height: 3px;
    margin-left: 12px;
    margin-top: 13px;
    transform: rotate(45deg);
    width: 8px
}

.share {
    font-size: 1.2rem;
    align-items: center;
    color: #5e717d;
    display: flex;
    font-weight: 400;
    line-height: 2.4rem;
    text-transform: uppercase
}

.share.-share-big,figcaption .share {
    justify-content: center
}

.story-attribution .share {
    margin-bottom: 2.4rem
}

.share-link {
    display: block;
    height: 2.4rem;
    margin-left: 1.4rem;
    position: relative;
    text-align: center;
    width: 2.4rem
}

.no-cssfilters .share-link {
    background-color: #fff
}

.share-link img {
    height: 23px;
    filter: grayscale(100%) contrast(0) brightness(1.2) sepia(20%) hue-rotate(150deg);
    transition: all .3s ease;
    width: auto
}

.share-link:focus,.share-link:hover {
    background-color: transparent
}

.share-link:focus img,.share-link:hover img {
    filter: unset
}

.-share-big .share-link {
    border: 2px solid #fff;
    border-radius: 50%;
    height: 6rem;
    margin: 0;
    position: relative;
    width: 6rem
}

.-share-big .share-link+.share-link {
    margin-left: 2.6rem
}

.-share-big .share-link img {
    height: 30px;
    filter: grayscale(100%) contrast(0) brightness(2);
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translate3d(-50%,-50%,0);
    width: auto
}

.-share-big .share-link:focus,.-share-big .share-link:hover {
    background-color: #fff
}

.-share-big .share-link:focus img,.-share-big .share-link:hover img {
    filter: unset
}

.slideshow {
    margin: 6rem auto;
    overflow: hidden;
    position: relative
}

.slideshow-scroll-track {
    -webkit-overflow-scrolling: touch;
    overflow-x: auto;
    overflow-y: hidden;
    padding-bottom: 500px;
    -ms-scroll-snap-points-x: repeat(100%);
    scroll-snap-points-x: repeat(100%);
    -ms-scroll-snap-type: mandatory;
    scroll-snap-type: mandatory;
    width: 100%
}

span[data-slide-caption] {
    display: none
}

.slideshow-caption-container {
    max-width: 80rem;
    background-color: #fff;
    margin: -6rem auto 6rem;
    padding-left: 12rem;
    padding-right: 2.4rem;
    position: relative;
    transform: translateZ(0)
}

.template-story .site-main .slideshow-caption-container {
    max-width: 70rem
}

.slideshow[min-width~="836px"]+.slideshow-caption-container,.template-story .slideshow[min-width~="736px"]+.slideshow-caption-container {
    margin-top: -10.2rem
}

.slideshow-caption-controls {
    float: left;
    margin-left: -9.6rem;
    width: 7.2rem
}

.slideshow-caption-controls p+p {
    margin-top: .6rem
}

.slideshow-caption-prev-next:after {
    clear: both;
    content: "";
    display: table
}

.caption-next,.caption-previous {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: transparent;
    border: none;
    height: 3.6rem;
    margin: 0;
    padding: 0;
    position: relative;
    transition: all .3s ease;
    width: 3.6rem
}

.caption-next:after,.caption-next:before,.caption-previous:after,.caption-previous:before {
    content: "";
    display: block;
    left: 50%;
    position: absolute;
    top: 50%;
    transition: all .3s ease
}

.caption-next:before,.caption-previous:before {
    border-right: 2px solid #019fcb;
    border-top: 2px solid #019fcb;
    height: 12px;
    transform: rotate(45deg);
    width: 12px
}

.caption-next:after,.caption-previous:after {
    background-color: #019fcb;
    height: 2px;
    margin: -1px 0 0 -8px;
    width: 16px
}

.caption-next:hover,.caption-previous:hover,[data-whatinput=keyboard] .caption-next:focus,[data-whatinput=keyboard] .caption-previous:focus {
    background-color: #019fcb
}

.caption-next:hover:before,.caption-previous:hover:before,[data-whatinput=keyboard] .caption-next:focus:before,[data-whatinput=keyboard] .caption-previous:focus:before {
    border-right-color: #fff;
    border-top-color: #fff
}

.caption-next:hover:after,.caption-previous:hover:after,[data-whatinput=keyboard] .caption-next:focus:after,[data-whatinput=keyboard] .caption-previous:focus:after {
    background-color: #fff
}

.caption-next {
    float: right
}

.caption-next:before {
    margin: -6px 0 0 -4px;
    transform: rotate(45deg)
}

.caption-previous {
    float: left
}

.caption-previous:before {
    margin: -6px 0 0 -8px;
    transform: rotate(-135deg)
}

.slideshow-counter {
    font-size: 1.4rem;
    line-height: 2.4rem;
    text-align: center
}

[data-module=slideshow][data-init] .slideshow-slide-caption {
    display: none
}

.slideshow-list {
    margin: 0;
    max-width: none!important;
    padding: 0
}

.slideshow-list li {
    margin: 0;
    padding-left: 0
}

.slideshow-list li:before {
    display: none
}

.slideshow-slide {
    margin: 0;
    padding: 0
}

.slideshow[data-init] .slideshow-slide {
    float: left
}

.slideshow-slide img {
    display: block;
    height: auto;
    width: 100%
}

.slideshow-next,.slideshow-previous {
    overflow: hidden;
    text-align: left;
    text-indent: 150%;
    white-space: nowrap;
    word-break: normal;
    word-wrap: normal;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-color: rgba(57,66,74,.6);
    background-repeat: no-repeat;
    background-size: 32px 72px;
    border: none;
    display: none;
    height: 12rem;
    margin: -6rem 0 0;
    outline: none;
    padding: 0;
    position: absolute;
    top: 50%;
    transition: all .3s ease;
    width: 9.6rem
}

.slideshow-next:hover,.slideshow-previous:hover {
    background-color: #019fcb
}

.slideshow[min-width~="600px"] .slideshow-next,.slideshow[min-width~="600px"] .slideshow-previous {
    display: block
}

.slideshow-next {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/slideshow-next.svg);
    background-position: 27px 50%;
    right: -9.6rem
}

.slideshow-previous {
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/slideshow-prev.svg);
    background-position: 39px 50%;
    left: -9.6rem
}

[data-whatintent=mouse] .slideshow:hover .slideshow-next {
    right: -1.2rem
}

[data-whatintent=mouse] .slideshow:hover .slideshow-next:hover {
    right: 0
}

[data-whatintent=mouse] .slideshow:hover .slideshow-previous {
    left: -1.2rem
}

[data-whatintent=mouse] .slideshow:hover .slideshow-previous:hover {
    left: 0
}

.text-stat {
    margin: 6rem auto
}

.text-stat:after {
    clear: both;
    content: "";
    display: table
}

.text-stat-list {
    max-width: none;
    margin: 0;
    position: relative
}

.text-stat-list li {
    padding-left: 0
}

.text-stat-list li:before {
    display: none
}

.text-stat-list li {
    line-height: 2.6rem;
    margin: 0;
    padding: 2.4rem 0;
    text-align: center;
    width: 100%
}

.text-stat-list li>span {
    display: inline-block;
    opacity: 0;
    transition: all .9s ease
}

[data-waypoint=visible] .text-stat-list li>span {
    opacity: 1
}

.text-stat-list li:nth-child(2)>span {
    transition-delay: .3s
}

.text-stat-list li:nth-child(3)>span {
    transition-delay: .6s
}

.text-stat-list li:nth-child(4)>span {
    transition-delay: .9s
}

.text-stat-number {
    display: block;
    font-size: 4.8rem;
    font-weight: 300;
    line-height: 6rem;
    margin-bottom: 0;
    margin-top: 0
}

.text-stat-list li:first-child {
    color: #872175
}

.text-stat-list li:nth-child(2) {
    color: #018d8d
}

.text-stat-list li:nth-child(3) {
    color: #9b1238
}

.text-stat-list li:last-child {
    color: #0050a2
}

.text-stat .text-stat-list li:last-child:first-child {
    border-top: none;
    margin: 0;
    width: 100%
}

.timeline {
    margin: 6rem auto
}

.timeline ol {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0 auto
}

.u-pull-container .timeline ol {
    margin: 0
}

.timeline .timeline-heading {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0
}

.timeline .timeline-heading+p {
    margin-top: .6rem
}

.timeline li {
    margin: 0;
    overflow: hidden;
    padding: 0 0 2.4rem 3rem;
    position: relative
}

.timeline li>:first-child {
    margin-top: 0!important
}

.timeline li>:last-child {
    margin-bottom: 0!important
}

.timeline li:last-child {
    padding-bottom: 0
}

.timeline li:last-child:after {
    display: none
}

.timeline li:before {
    background-color: #fff;
    border-style: solid;
    border-width: 2px;
    border-radius: 50%;
    height: 1.8rem;
    left: 0;
    margin: 0;
    opacity: 0;
    top: .3rem;
    transition: opacity .3s ease,transform .3s ease;
    transform: scale(.5);
    transform-origin: center center;
    width: 1.8rem;
    z-index: 2
}

.timeline li:after,.timeline li:before {
    content: "";
    display: block;
    position: absolute
}

.timeline li:after {
    height: 0;
    left: .75rem;
    top: 2.55rem;
    transition: height .6s ease;
    width: 2px;
    z-index: 1
}

.js .timeline li>* {
    opacity: 0;
    transform: translateY(15%);
    transition: opacity .6s ease,transform .6s ease
}

.timeline[min-width~="480px"] ol {
    font-size: 1.8rem;
    line-height: 3.6rem
}

.timeline[min-width~="480px"] .timeline-heading {
    font-size: 2.4rem;
    line-height: 3rem
}

.timeline[min-width~="480px"] li {
    padding: 0 0 3.6rem 4.2rem
}

.timeline[min-width~="480px"] li:last-child {
    padding-bottom: 0
}

.timeline[min-width~="480px"] li:before {
    height: 2.4rem;
    width: 2.4rem
}

.timeline[min-width~="480px"] li:after {
    left: 1.11rem;
    top: 3.15rem
}

.timeline[data-is=visible] li>*,.timeline li:first-child>* {
    opacity: 1;
    transform: translateX(0)
}

.timeline[data-is=visible] li:before,.timeline li:first-child:before {
    opacity: 1;
    transform: scale(1)
}

.timeline[data-is=visible] li:after {
    height: 100%
}

.timeline[data-is=visible] li:nth-child(2):before,.timeline[data-is=visible] li:nth-child(2)>* {
    transition-delay: .3s
}

.timeline[data-is=visible] li:nth-child(2):after {
    transition-delay: .9s
}

.timeline[data-is=visible] li:nth-child(3):before,.timeline[data-is=visible] li:nth-child(3)>* {
    transition-delay: 1.2s
}

.timeline[data-is=visible] li:nth-child(3):after {
    transition-delay: 1.8s
}

.timeline[data-is=visible] li:nth-child(4):before,.timeline[data-is=visible] li:nth-child(4)>* {
    transition-delay: 2.1s
}

.timeline[data-is=visible] li:nth-child(4):after {
    transition-delay: 2.7s
}

.timeline[data-is=visible] li:nth-child(5):before,.timeline[data-is=visible] li:nth-child(5)>* {
    transition-delay: 3s
}

.timeline[data-is=visible] li:nth-child(5):after {
    transition-delay: 3.6s
}

.timeline[data-is=visible] li:nth-child(6):before,.timeline[data-is=visible] li:nth-child(6)>* {
    transition-delay: 3.9s
}

.timeline[data-is=visible] li:nth-child(6):after {
    transition-delay: 4.5s
}

.timeline[data-is=visible] li:nth-child(7):before,.timeline[data-is=visible] li:nth-child(7)>* {
    transition-delay: 4.8s
}

.timeline[data-is=visible] li:nth-child(7):after {
    transition-delay: 5.4s
}

.timeline[data-is=visible] li:nth-child(8):before,.timeline[data-is=visible] li:nth-child(8)>* {
    transition-delay: 5.7s
}

.timeline[data-is=visible] li:nth-child(8):after {
    transition-delay: 6.3s
}

.timeline[data-is=visible] li:nth-child(9):before,.timeline[data-is=visible] li:nth-child(9)>* {
    transition-delay: 6.6s
}

.timeline[data-is=visible] li:nth-child(9):after {
    transition-delay: 7.2s
}

.timeline[data-is=visible] li:nth-child(10):before,.timeline[data-is=visible] li:nth-child(10)>* {
    transition-delay: 7.5s
}

.timeline[data-is=visible] li:nth-child(10):after {
    transition-delay: 8.1s
}

.timeline[data-is=visible] li:nth-child(11):before,.timeline[data-is=visible] li:nth-child(11)>* {
    transition-delay: 8.4s
}

.timeline[data-is=visible] li:nth-child(11):after {
    transition-delay: 9s
}

.timeline[data-is=visible] li:nth-child(12):before,.timeline[data-is=visible] li:nth-child(12)>* {
    transition-delay: 9.3s
}

.timeline[data-is=visible] li:nth-child(12):after {
    transition-delay: 9.9s
}

.timeline[data-is=visible] li:nth-child(13):before,.timeline[data-is=visible] li:nth-child(13)>* {
    transition-delay: 10.2s
}

.timeline[data-is=visible] li:nth-child(13):after {
    transition-delay: 10.8s
}

.timeline[data-is=visible] li:nth-child(14):before,.timeline[data-is=visible] li:nth-child(14)>* {
    transition-delay: 11.1s
}

.timeline[data-is=visible] li:nth-child(14):after {
    transition-delay: 11.7s
}

.timeline[data-is=visible] li:nth-child(15):before,.timeline[data-is=visible] li:nth-child(15)>* {
    transition-delay: 12s
}

.timeline[data-is=visible] li:nth-child(15):after {
    transition-delay: 12.6s
}

.timeline[data-is=visible] li:nth-child(16):before,.timeline[data-is=visible] li:nth-child(16)>* {
    transition-delay: 12.9s
}

.timeline[data-is=visible] li:nth-child(16):after {
    transition-delay: 13.5s
}

.timeline[data-is=visible] li:nth-child(17):before,.timeline[data-is=visible] li:nth-child(17)>* {
    transition-delay: 13.8s
}

.timeline[data-is=visible] li:nth-child(17):after {
    transition-delay: 14.4s
}

.timeline[data-is=visible] li:nth-child(18):before,.timeline[data-is=visible] li:nth-child(18)>* {
    transition-delay: 14.7s
}

.timeline[data-is=visible] li:nth-child(18):after {
    transition-delay: 15.3s
}

.timeline[data-is=visible] li:nth-child(19):before,.timeline[data-is=visible] li:nth-child(19)>* {
    transition-delay: 15.6s
}

.timeline[data-is=visible] li:nth-child(19):after {
    transition-delay: 16.2s
}

.timeline[data-is=visible] li:nth-child(20):before,.timeline[data-is=visible] li:nth-child(20)>* {
    transition-delay: 16.5s
}

.timeline[data-is=visible] li:nth-child(20):after {
    transition-delay: 17.1s
}

.timeline.-blue li:before {
    border-color: #019fcb
}

.timeline.-blue li:after {
    background: repeating-linear-gradient(180deg,#019fcb,#019fcb 2px,transparent 0,transparent 6px)
}

.timeline.-green li:before {
    border-color: #018d8d
}

.timeline.-green li:after {
    background: repeating-linear-gradient(180deg,#018d8d,#018d8d 2px,transparent 0,transparent 6px)
}

.timeline.-purple li:before {
    border-color: #872175
}

.timeline.-purple li:after {
    background: repeating-linear-gradient(180deg,#872175,#872175 2px,transparent 0,transparent 6px)
}

.timeline.-red li:before {
    border-color: #9b1238
}

.timeline.-red li:after {
    background: repeating-linear-gradient(180deg,#9b1238,#9b1238 2px,transparent 0,transparent 6px)
}

.timeline-header {
    font-size: 1.4rem;
    line-height: 2.4rem;
    margin: 0 0 1.8rem 3rem
}

.topic-banner {
    background-color: #fff;
    margin: 6rem auto
}

.topic-banner+.topic-banner {
    margin-top: -2.4rem
}

.topic-banner-header {
    font-size: 1.4rem;
    line-height: 2.4rem;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff;
    padding: 2.4rem 3rem
}

.topic-banner-header>:first-child {
    margin-top: 0!important
}

.topic-banner-header>:last-child {
    margin-bottom: 0!important
}

.topic-banner-list {
    margin: 0;
    max-width: none;
    padding: 1.2rem 0
}

.topic-banner-list li {
    margin: 0;
    padding-left: 0
}

.topic-banner-list li:before {
    display: none
}

li.topic-banner-item {
    margin: 0;
    padding: 0 2rem
}

li.topic-banner-item+.topic-banner-item a {
    border-top: 1px solid #c7ced9
}

li.topic-banner-item a {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #39424a;
    display: block;
    font-weight: 400;
    padding: 1.2rem 0
}

li.topic-banner-item a>:first-child {
    margin-top: 0!important
}

li.topic-banner-item a>:last-child {
    margin-bottom: 0!important
}

li.topic-banner-item a:focus,li.topic-banner-item a:hover {
    background-color: #fff
}

li.topic-banner-item a:focus .topic-banner-heading,li.topic-banner-item a:hover .topic-banner-heading {
    background-color: #e5f5fa
}

.topic-banner-heading {
    display: inline-block;
    margin: 0
}

.topic-banner-header .topic-banner-heading {
    font-size: 2rem;
    line-height: 3rem
}

.topic-banner-header .topic-banner-heading+p {
    margin-top: 1.2rem
}

.topic-banner-item .topic-banner-heading {
    font-size: 1.8rem;
    line-height: 2.6rem;
    color: #019fcb
}

.topic-banner-item .topic-banner-heading+p {
    margin-top: .6rem
}

.topic-bundle {
    margin: 6rem auto
}

.topic-bundle li {
    margin: 0;
    padding-left: 0
}

.topic-bundle li:before {
    display: none
}

li.topic-bundle-item {
    font-size: 1.4rem;
    line-height: 2.4rem;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background: #019fcb url(/sites/all/themes/rotary_rotaryorg/images/texture-lighter-blue.png) 50% 50%;
    background-size: 100px 100px;
    color: #fff;
    margin: 0;
    padding: 3.6rem 2rem;
    text-align: center
}

li.topic-bundle-item>:first-child {
    margin-top: 0!important
}

li.topic-bundle-item>:last-child {
    margin-bottom: 0!important
}

li.topic-bundle-item:nth-child(2n) {
    background-color: #0197c1;
    background-image: url(/sites/all/themes/rotary_rotaryorg/images/texture-darker-blue.png)
}

.topic-bundle-heading {
    font-size: 2rem;
    line-height: 3rem;
    font-weight: 400
}

.topic-bundle-learnmore {
    font-size: 1.4rem;
    line-height: 2.4rem;
    color: #fff;
    font-weight: 400
}

.topic-bundle-learnmore:hover,[data-whatinput=keyboard] .topic-bundle-learnmore:focus {
    background-color: transparent;
    text-decoration: underline
}

#functionality-tabs ul.primary {
    border-bottom: none;
    border-collapse: inherit;
    height: auto;
    line-height: normal;
    list-style: none;
    margin: inherit;
    padding: inherit;
    white-space: inherit
}

#functionality-tabs ul.primary li a {
    background-color: inherit;
    border: inherit;
    height: auto;
    margin-right: inherit;
    padding: 0;
    text-decoration: none
}

#functionality-tabs ul.primary li a:hover {
    background-color: inherit;
    border-color: inherit;
    border-bottom-color: inherit
}

#functionality-tabs ul.primary li.active a {
    background-color: inherit;
    border: inherit;
    border-bottom: inherit
}

#functionality-tabs ul.primary li:before {
    content: none
}

#functionality-tabs ul.primary li:first-child {
    padding-left: 0
}

#hero-2 .hero-mosaic-description,#hero-3 .hero-mosaic-description,.article-filters .article-filters-search {
    display: none
}

.article-filters .article-filters-search input.form-autocomplete {
    background-image: none
}

.article-filters #edit-submit-featured-content {
    display: none
}

ul.pager li:before {
    content: ""
}

section.home-causes.layout-container.-gray:before {
    display: block
}

.node-type-legacy .region-content {
    padding-top: 10rem
}

.node-type-legacy .region-content .field-name-field-byline {
    margin: 2.6rem auto;
    max-width: 80rem
}

.node-type-legacy .region-content .field-name-field-add-new-translation,.node-type-legacy .region-content .field-name-field-aggregate-display,.node-type-legacy .region-content .field-name-field-bus-review-req,.node-type-legacy .region-content .field-name-field-byline .field-label,.node-type-legacy .region-content .field-name-field-feature-member-news,.node-type-legacy .region-content .field-name-field-feature-news-type,.node-type-legacy .region-content .field-name-field-featured-story-content,.node-type-legacy .region-content .field-name-field-featured-story-head,.node-type-legacy .region-content .field-name-field-featured-story-module,.node-type-legacy .region-content .field-name-field-placement-location,.node-type-legacy .region-content .field-name-field-publish-date,.node-type-legacy .region-content .field-name-field-short-description,.node-type-legacy .region-content .field-name-field-source-name,.node-type-legacy .region-content .field-name-field-top-story,.node-type-legacy .region-content .field-name-field-topic,.node-type-legacy .region-content .form-item,.node-type-legacy .region-content .user-picture,.node-type-legacy .region-content div.submitted,.node-type-legacy .region-content ul.contextual-links,.node-type-legacy .region-content ul.links.inline {
    display: none
}

.node-type-legacy .region-content h2,.node-type-legacy .region-content h3,.node-type-legacy .region-content h4 {
    text-align: center!important
}

.join-button {
    display: block;
    margin: 0 auto
}

ol.number-list,ul.people-list,ul.thumbnail-list {
    max-width: 80rem
}

.callout-text .text-stat * {
    width: auto
}

.callout-text .text-stat .text-stat-list>li {
    width: 100%
}

body.page-search #search-form {
    padding-top: 0;
    padding-bottom: 0
}

body.page-search #search-form .u-grid-row .u-grid-9 {
    padding-left: 0
}

body.page-search #search-form .u-grid-row input[type=submit].u-button {
    min-width: 100%;
    padding: 0;
    height: 4.2rem
}

body.page-search #search-form .google-appliance-keymatch-results li {
    padding: 10px;
    border-radius: 0;
    -webkit-border-radius: 0;
    -moz-border-radius: 0
}

body.page-search #search-form .google-appliance-keymatch-results .heading-h3 {
    color: #39424a
}

.site-nav-utility-search form p {
    margin: 0
}

@media (min-width: 250px) {
    .text-stat-number {
        font-size:6.6rem;
        line-height: 7.2rem
    }
}

@media (min-width: 300px) {
    .text-stat-number {
        font-size:8rem;
        line-height: 9rem
    }
}

@media only screen and (min-width: 320px) and (max-width:568px) and (orientation:landscape) {
    span.home-causes-image {
        height:100%;
        min-height: 230px;
        width: 84%;
        margin: 0 8%;
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        transition: all .3s ease;
        border-radius: 50%
    }

    .mobile-view {
        display: block!important
    }

    .desktop-view {
        display: none!important
    }

    .layout-container {
        padding: 6rem 1.8rem!important
    }
}

@media only screen and (min-width: 320px) and (max-width:359px) and (orientation:portrait) {
    ul.home-causes-list {
        float:left;
        width: 100%;
        margin: 0 auto
    }

    .home-causes-item-list {
        width: 50%;
        float: left;
        margin: 0;
        padding: 0
    }

    .home-causes-item-list:before {
        content: "";
        display: block;
        height: 0;
        width: 100%
    }

    span.home-causes-image {
        height: 100%;
        min-height: 130px;
        width: 90%;
        margin: 0 8%;
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        transition: all .3s ease;
        border-radius: 50%
    }
}

@media (min-width: 20em) {
    .callout-section .callout-section-left .callout-section-left-content-holder {
        margin-left:1rem;
        margin-right: 1rem
    }

    .callout-section .callout-section-left .callout-section-left-content-holder .callout-section-title {
        font-size: 30px;
        line-height: 40px
    }

    .callout-section .callout-section-left .callout-section-left-content-holder .callout-section-description {
        font-weight: 300;
        font-size: 17px;
        text-align: left
    }

    .causes-link div {
        padding: 12px 0 25px;
        height: 75px;
        width: 92%;
        margin: 0 4%;
        top: 0;
        font-style: normal;
        font-weight: 700;
        font-size: 16px;
        line-height: 22px;
        letter-spacing: .02em;
        color: #fff;
        text-align: center
    }

    .mobile-view {
        display: block
    }

    .mobile-view .layout-container {
        padding: 6rem 1.8rem!important
    }

    .mobile-view li#cause--7 {
        text-align: center;
        width: 75%;
        padding-left: 24%
    }

    .title-info {
        display: flex;
        padding: 5%
    }

    .stat-suffix {
        font-size: 2.3rem;
        line-height: 0
    }

    .title-text {
        flex-basis: 60%;
        padding-bottom: 2%
    }

    .title-img {
        flex-basis: 40%;
        height: 7rem;
        width: 7rem;
        display: inline-block
    }

    img.stat-icon {
        width: 8rem;
        padding: 12px 19px 7px 0;
        height: 9rem
    }

    .title-text .impact-stat-number {
        font-size: 5.1rem
    }

    strong.impact-stat-number span {
        margin-right: .1rem
    }

    .text-stat-title {
        font-size: 1.5rem
    }

    .impact-stat-description {
        font-size: 1.7rem
    }

    .impact-stat-set [data-animate=fade-up][data-is=ready] {
        opacity: 1;
        transform: translateY(0)
    }

    .impact-stat-set [data-animate=fade-up] {
        transition: none
    }

    .news-features-container .hero-mosaic-item {
        height: auto;
        float: left
    }

    .news-features-container .hero-mosaic-item a {
        min-height: 27rem;
        padding-top: 16.38rem;
        height: inherit
    }

    .news-features-container .-feature {
        width: 100%;
        height: 35.5rem;
        margin-left: 0;
        border-bottom: .4rem solid #ffc000
    }

    .news-features-container .-feature a {
        padding-top: 22rem
    }

    .news-features-container .special-feature {
        margin-top: 0
    }

    .news-features-container .from-right {
        width: 100%
    }
}

@media (min-width: 340px) and (max-width:398px) {
    .mobile-view {
        display:block
    }

    .mobile-view li.home-causes-item-list {
        width: 50%;
        margin: 0 auto;
        padding: 0;
        float: left
    }

    .mobile-view li.home-causes-item-list:before {
        content: "";
        display: block;
        height: 0;
        width: 100%
    }

    .mobile-view ul.home-causes-list {
        float: left;
        width: 100%;
        margin: 0 auto
    }

    .mobile-view .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        font-size: 22px;
        height: 100%;
        margin: 0 6%;
        top: 0;
        transition: all .3s ease;
        width: 90%;
        padding-top: 90%;
        z-index: 10;
        border-radius: 50%
    }

    .mobile-view li#cause--7 {
        text-align: center;
        width: 75%;
        padding-left: 24%
    }

    .desktop-view {
        display: none!important
    }

    .layout-container {
        padding: 6rem 1.8rem!important
    }
}

@media (min-width: 350px) {
    .text-stat .text-stat-description {
        display:inline-block;
        max-width: 35rem
    }
}

@media (min-width: 400px) and (max-width:479px) {
    .mobile-view {
        display:block
    }

    .mobile-view li.home-causes-item-list {
        width: 50%;
        margin: 0 auto;
        padding: 0;
        float: left
    }

    .mobile-view li.home-causes-item-list:before {
        content: "";
        display: block;
        height: 0;
        width: 100%
    }

    .mobile-view ul.home-causes-list {
        float: left;
        width: 100%;
        margin: 0 auto
    }

    .mobile-view .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        font-size: 22px;
        height: 100%;
        min-height: 14.5rem;
        margin: 0 6%;
        top: 0;
        transition: all .3s ease;
        width: 90%;
        padding-top: 90%;
        z-index: 10;
        border-radius: 50%
    }

    .mobile-view li#cause--7 {
        text-align: center;
        width: 75%;
        padding-left: 24%
    }

    .desktop-view {
        display: none!important
    }

    .layout-container {
        padding: 6rem 1.8rem!important
    }
}

@media (min-width: 400px) {
    .u-width-8 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-8 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-9 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-9 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-10 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-10 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-11 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-11 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-12 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-12 .u-button-group .u-button:nth-last-child(3):first-child~.u-button {
        float:left;
        width: calc(50% - 10px)
    }

    .u-width-8 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-9 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-10 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-11 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-12 .u-button-group .u-button:nth-last-child(3):first-child~.u-button {
        margin-left: 20px;
        margin-top: 0
    }

    .u-width-6 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-6 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-7 .u-button-group .u-button:nth-last-child(3):first-child,.u-width-7 .u-button-group .u-button:nth-last-child(3):first-child~.u-button {
        float: left;
        width: calc(50% - 10px)
    }

    .u-width-6 .u-button-group .u-button:nth-last-child(3):first-child~.u-button,.u-width-7 .u-button-group .u-button:nth-last-child(3):first-child~.u-button {
        margin-left: 20px;
        margin-top: 0
    }
}

@media (min-width: 30em) {
    .content-effectiveness strong {
        line-height:3rem
    }

    .site-footer-nav-item {
        display: inline-block
    }

    .site-footer-nav-item+.site-footer-nav-item {
        margin-left: 4rem
    }

    .site-footer-nav-item+.site-footer-nav-item.-margin-reduced {
        margin-left: 2rem
    }

    .site-footer-social a {
        padding-left: 1.5rem;
        padding-right: 1.5rem
    }

    .lede,body {
        line-height: 3rem
    }

    .lede {
        text-align: center
    }

    .heading-h1 {
        font-weight: 300;
        font-size: 6.6rem;
        line-height: 7.2rem
    }

    .heading-h1.-basic {
        font-size: 3.6rem;
        line-height: 4.2rem
    }

    .heading-h1.-banner,.heading-h1.-feature {
        font-size: 6.6rem;
        line-height: 7.2rem
    }

    .heading-h2,.wysiwyg h2 {
        margin-bottom: 1.8rem;
        font-size: 2.6rem;
        line-height: 3.6rem
    }

    .heading-h2.-alternate,.wysiwyg h2.-alternate {
        font-size: 3rem;
        line-height: 4.2rem
    }

    .heading-h2.-alternate-light,.wysiwyg h2.-alternate-light {
        font-size: 2.6rem;
        line-height: 3.6rem
    }

    .heading-h3.-alternate,.heading-h4,.heading-section,.wysiwyg h3.-alternate,.wysiwyg h4 {
        line-height: 3rem
    }

    .number-list li {
        padding-left: 13rem
    }

    .number-list li:before {
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #9b1238;
        content: counter(list);
        font-size: 10rem;
        font-weight: 300;
        height: 8.4rem;
        line-height: 8.4rem;
        margin-left: -14rem;
        width: 12rem
    }

    .thumbnail-list img {
        display: block;
        float: left;
        height: auto;
        margin-bottom: 0;
        margin-left: -15rem;
        max-width: none;
        width: 13rem
    }

    .thumbnail-list li {
        padding-left: 15rem
    }

    .u-pull-0 {
        margin-bottom: 1.2rem;
        margin-top: 0
    }

    .u-pull-0.image-block,.u-pull-0.slideshow,.u-pull-0.u-container-bordered {
        margin-top: 1.2rem
    }

    .u-pull-0.u-pull-left {
        float: left;
        margin-right: 2.4rem
    }

    .u-pull-0.u-pull-right {
        float: right;
        margin-left: 2.4rem
    }

    .u-sidebar {
        font-size: 1.4rem;
        line-height: 2.4rem;
        display: block;
        float: right;
        margin: 0 auto 1.2rem 3.6rem;
        width: 20rem
    }

    .u-sidebar>:first-child {
        margin-top: 0!important
    }

    .u-sidebar>:last-child {
        margin-bottom: 0!important
    }

    .site-nav .u-button.-fluid-small,.u-button.-fluid-small {
        min-width: 25rem;
        width: auto
    }

    .article-grid {
        margin-bottom: 3.6rem;
        margin-top: 3.6rem
    }

    .article-grid-list {
        margin-left: -2.4rem
    }

    .article-grid-list li {
        padding: 1.2rem 0 1.2rem 2.4rem
    }

    .article-grid-item {
        float: left;
        width: 50%
    }

    .article-grid-item.-last {
        float: right
    }

    .carousel-list {
        padding: 0 20vw
    }

    .carousel-item {
        width: 60vw
    }

    .carousel-item-inner {
        box-shadow: 0 0 10px rgba(0,0,0,.2);
        margin: 0 10px
    }

    .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        font-size: 22px;
        height: 100%;
        min-height: 24.8rem;
        margin: 0 9%;
        top: 0;
        transition: all .3s ease;
        width: 82%;
        padding-top: 82%;
        z-index: 10;
        border-radius: 50%
    }

    .mobile-view .layout-container {
        padding: 6rem 1.8rem!important
    }

    .mobile-view li#cause--7 {
        text-align: center;
        width: 75%;
        padding-left: 24%
    }

    .hero-mosaic-item.-feature a {
        padding-top: 24rem
    }

    .hero-mosaic-item a {
        padding: 12rem 2.4rem 2.4rem
    }

    .hero-callout {
        margin-top: 4.8rem!important
    }

    .image-callout-article,.image-callout-cta,.image-callout-quote,.image-callout-text {
        padding: 6rem 3.6rem
    }

    .image-callout-article {
        padding-bottom: 1.8rem;
        padding-top: 1.8rem
    }

    .image-callout[data-caption-visible=false] .image-callout-caption-toggle {
        top: calc(-20px - 2.4rem)
    }

    .title-info {
        display: flex;
        padding: 2%
    }

    .stat-suffix {
        font-size: 2.625rem;
        line-height: 0
    }

    .title-text {
        flex-basis: 55%;
        padding-bottom: 2%
    }

    .title-img {
        flex-basis: 45%
    }

    img.stat-icon {
        width: 7.7rem;
        padding: 10px 17px 12px 0;
        height: 9rem
    }

    .title-text .impact-stat-number {
        font-size: 5.2rem
    }

    strong.impact-stat-number span {
        margin-right: .4rem
    }

    .text-stat-title {
        font-size: 1.5rem
    }

    .impact-stat-description {
        font-size: 1.7rem
    }

    .impact-stat-set [data-animate=fade-up][data-is=ready] {
        opacity: 1;
        transform: translateY(0)
    }

    .impact-stat-set [data-animate=fade-up] {
        transition: none
    }

    .link-dropdown-toggle {
        line-height: 3rem
    }

    .modal-trigger.-inline {
        background-position: .6rem .6rem
    }

    .modal-trigger.-inline.-video {
        background-position: .6rem 0.7rem
    }

    .related-stories:after {
        clear: both;
        content: "";
        display: table
    }

    .related-stories-feature {
        font-size: 1.4rem;
        line-height: 2.4rem;
        float: left;
        margin: 0;
        width: 40%
    }

    .related-stories-list {
        float: left;
        margin: 0;
        padding-left: 5rem;
        width: 60%
    }

    .related-stories-list li {
        margin: 0;
        padding-left: 0
    }

    .related-stories-list li:before {
        display: none
    }

    .related-stories-list li+li {
        margin-top: 2.4rem
    }

    .story-attribution .share {
        float: right;
        margin: 0
    }

    .topic-banner-header {
        padding: 4.2rem 3rem
    }

    .topic-banner-list {
        display: flex;
        flex-wrap: wrap;
        padding: 2.4rem 0
    }

    li.topic-banner-item {
        width: 50%
    }

    li.topic-banner-item:nth-child(odd) {
        padding: 0 2rem 0 4rem
    }

    li.topic-banner-item:nth-child(2n) {
        padding: 0 4rem 0 2rem
    }

    li.topic-banner-item:first-child,li.topic-banner-item:nth-child(2) {
        padding-bottom: .1rem;
        position: relative
    }

    li.topic-banner-item:first-child::after,li.topic-banner-item:nth-child(2):after {
        background-color: #c7ced9;
        bottom: 0;
        content: "";
        display: block;
        height: 1px;
        position: absolute
    }

    li.topic-banner-item:first-child::after {
        left: 4rem;
        right: 2rem
    }

    li.topic-banner-item:nth-child(2):after {
        left: 2rem;
        right: 4rem
    }

    li.topic-banner-item+.topic-banner-item a {
        border-top: none
    }

    .topic-banner-item .topic-banner-heading {
        line-height: 3rem
    }

    li.topic-bundle-item {
        padding-left: 20%;
        padding-right: 20%
    }
}

@media (min-width: 480px) {
    .text-stat .text-stat-list {
        display:flex;
        flex-wrap: wrap
    }

    .text-stat .text-stat-list li:nth-last-child(2):first-child,.text-stat .text-stat-list li:nth-last-child(2):first-child~li {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 22rem;
        border-top: none;
        margin: 0;
        padding: 0 4.8rem;
        width: 50%
    }

    .text-stat .text-stat-list li:nth-last-child(2):first-child .text-stat-number,.text-stat .text-stat-list li:nth-last-child(2):first-child~li .text-stat-number {
        margin: 0 -4.8rem
    }

    .text-stat .text-stat-list li:nth-last-child(2):first-child~li {
        border-left: 1px solid #c7ced9;
        width: calc(percentage0.5 - 1px)
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child,.text-stat .text-stat-list li:nth-last-child(3):first-child~li {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 22rem;
        border-top: none;
        margin: 0;
        padding: 0 4.8rem;
        width: 50%
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child .text-stat-wrapper,.text-stat .text-stat-list li:nth-last-child(3):first-child~li .text-stat-wrapper {
        padding: 0 1.2rem;
        width: 100%
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child .text-stat-number,.text-stat .text-stat-list li:nth-last-child(3):first-child~li .text-stat-number {
        margin: 0 -4.8rem
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child:first-child,.text-stat .text-stat-list li:nth-last-child(3):first-child~li:first-child {
        margin-bottom: -220px
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child~li {
        width: calc(percentage0.5 - 1px)
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child~li:last-child {
        margin-left: auto;
        border-top: 1px solid #c7ced9
    }

    .text-stat .text-stat-list li:nth-child(3):after,.text-stat .text-stat-list li:nth-last-child(3):first-child:after {
        background-color: #c7ced9;
        content: "";
        display: block;
        position: absolute
    }

    .text-stat .text-stat-list li:nth-child(3):after {
        left: 50%;
        height: 100%;
        top: 0;
        width: 1px
    }

    .text-stat .text-stat-list li:nth-last-child(4):first-child,.text-stat .text-stat-list li:nth-last-child(4):first-child~li {
        align-items: flex-start;
        border-top: none;
        display: flex;
        justify-content: center;
        margin: 0;
        min-height: 22rem;
        padding: 4.8rem 0;
        width: 50%
    }

    .text-stat .text-stat-list li:nth-last-child(4):first-child .text-stat-wrapper,.text-stat .text-stat-list li:nth-last-child(4):first-child~li .text-stat-wrapper {
        padding: 0 4.8rem;
        width: 100%
    }

    .text-stat .text-stat-list li:nth-last-child(4):first-child .text-stat-number,.text-stat .text-stat-list li:nth-last-child(4):first-child~li .text-stat-number {
        margin: 0 -4.8rem
    }

    .text-stat .text-stat-list li:nth-last-child(4):first-child {
        position: relative
    }

    .text-stat .text-stat-list li:nth-last-child(4):first-child:after {
        bottom: 0;
        height: 1px;
        left: 0;
        width: 200%
    }

    .text-stat .text-stat-list li:nth-child(4):after,.text-stat .text-stat-list li:nth-last-child(4):first-child:after {
        background-color: #c7ced9;
        content: "";
        display: block;
        position: absolute
    }

    .text-stat .text-stat-list li:nth-child(4):after {
        height: 100%;
        left: 50%;
        top: 0;
        width: 1px
    }
}

@media (min-width: 480px) and (max-width:767px) {
    .home-causes-item-list {
        width:50%;
        float: left;
        margin: 0;
        padding: 0
    }

    .home-causes-item-list:before {
        content: "";
        display: block;
        height: 0;
        width: 100%
    }

    .mobile-view {
        display: block!important
    }

    .desktop-view {
        display: none!important
    }

    .layout-container {
        padding: 6rem 1.8rem!important
    }
}

@media (min-width: 600px) {
    .text-stat .text-stat-list li:nth-last-child(3):first-child:first-child,.text-stat .text-stat-list li:nth-last-child(3):first-child~li:first-child {
        margin-bottom:-320px
    }

    .text-stat .text-stat-list li:nth-last-child(3):first-child,.text-stat .text-stat-list li:nth-last-child(3):first-child~li,.text-stat .text-stat-list li:nth-last-child(4):first-child,.text-stat .text-stat-list li:nth-last-child(4):first-child~li {
        min-height: 32rem;
        align-items: center
    }
}

@media (min-width: 715px) {
    .u-width-8 .u-button-group .u-button:nth-last-child(4):first-child,.u-width-8 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-9 .u-button-group .u-button:nth-last-child(4):first-child,.u-width-9 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-10 .u-button-group .u-button:nth-last-child(4):first-child,.u-width-10 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-11 .u-button-group .u-button:nth-last-child(4):first-child,.u-width-11 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-12 .u-button-group .u-button:nth-last-child(4):first-child,.u-width-12 .u-button-group .u-button:nth-last-child(4):first-child~.u-button {
        float:left;
        width: calc(33.3334% - 13.3334px)
    }

    .u-width-8 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-9 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-10 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-11 .u-button-group .u-button:nth-last-child(4):first-child~.u-button,.u-width-12 .u-button-group .u-button:nth-last-child(4):first-child~.u-button {
        margin-left: 20px;
        margin-top: 0
    }
}

@media only screen and (min-width: 732px) and (orientation:landscape) {
    .mobile-view .home-causes-image {
        width:80%;
        padding-top: 80%;
        margin: 0 8%
    }
}

@media (min-width: 30em) and (min-width:47.5em) {
    .related-stories-feature {
        font-size:1.6rem
    }
}

@media (min-width: 47.5em) {
    .content-effectiveness {
        font-size:1.6rem
    }

    .content-effectiveness-yesno {
        align-items: center;
        display: table
    }

    .content-effectiveness-yesno-text {
        display: table-cell;
        text-align: left;
        vertical-align: middle;
        white-space: nowrap
    }

    .content-effectiveness-yesno-buttons {
        display: table-cell;
        margin-left: 0;
        margin-right: 0;
        max-width: none;
        padding-left: 3rem;
        vertical-align: middle;
        width: 100%
    }

    .content-effectiveness-yesno-buttons li+li {
        padding-left: 2rem
    }

    .site-footer,.site-nav-utility-ctas,.table-wrapper td,.table-wrapper th {
        font-size: 1.6rem
    }

    .lede {
        font-size: 2rem;
        line-height: 3.6rem
    }

    .lede.-banner {
        font-size: 2.4rem;
        line-height: 3.6rem
    }

    .heading-h1.-basic {
        font-size: 4.8rem;
        line-height: 6rem
    }

    .quote-block {
        font-size: 3.6rem;
        line-height: 4.8rem;
        margin: 4.2rem auto
    }

    .people-list-image img {
        margin: 0;
        max-width: none;
        width: 100%
    }

    .people-list-text>* {
        margin-left: 3rem
    }

    label {
        font-size: 1.6rem
    }

    .u-input-list.-inline:after {
        clear: both;
        content: "";
        display: table
    }

    .u-input-list.-inline label {
        line-height: 4.2rem
    }

    .u-input-list.-inline .u-input-list-legend,.u-input-list.-inline legend {
        float: left;
        line-height: 4.2rem;
        margin-bottom: 0;
        padding-right: 2rem
    }

    .u-input-list.-inline li {
        float: left;
        margin: 0
    }

    .u-input-list.-inline li+li {
        margin-left: 2rem
    }

    .u-input-list.-inline ol,.u-input-list.-inline ul {
        float: left;
        margin: 0
    }

    .layout-container {
        padding: 6rem 1.8rem
    }

    .layout-container.-padding-reduced {
        padding-bottom: 6rem;
        padding-top: 6rem
    }

    .layout-container.-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-lightgray+.layout-container:not(.-lightgray),.layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-lightgray+.layout-container:not(.-lightgray).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-green+.layout-container:not(.-green),.layout-container.-green+.layout-container:not(.-green).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-green+.layout-container:not(.-green).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-green+.layout-container:not(.-green).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-blue+.layout-container:not(.-blue),.layout-container.-blue+.layout-container:not(.-blue).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-blue+.layout-container:not(.-blue).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-blue+.layout-container:not(.-blue).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-purple+.layout-container:not(.-purple),.layout-container.-purple+.layout-container:not(.-purple).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-purple+.layout-container:not(.-purple).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-purple+.layout-container:not(.-purple).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-red+.layout-container:not(.-red),.layout-container.-red+.layout-container:not(.-red).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-red+.layout-container:not(.-red).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-red+.layout-container:not(.-red).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-royalblue+.layout-container:not(.-royalblue),.layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-royalblue+.layout-container:not(.-royalblue).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-gray+.layout-container:not(.-gray),.layout-container.-gray+.layout-container:not(.-gray).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-gray+.layout-container:not(.-gray).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-gray+.layout-container:not(.-gray).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-dark+.layout-container:not(.-dark),.layout-container.-dark+.layout-container:not(.-dark).-padding-reduced {
        padding: 6rem 1.8rem
    }

    .layout-container.-dark+.layout-container:not(.-dark).-padding-reduced-top {
        padding-top: 6rem
    }

    .layout-container.-dark+.layout-container:not(.-dark).-padding-reduced-bottom {
        padding-bottom: 6rem
    }

    .layout-container.-image-callout+.layout-container {
        padding-top: 6rem!important
    }

    .u-grid-1,.u-grid-2,.u-grid-3,.u-grid-4,.u-grid-5,.u-grid-6,.u-grid-7,.u-grid-8,.u-grid-9,.u-grid-10,.u-grid-11,.u-grid-12 {
        display: block;
        float: left;
        margin: 0;
        min-height: 1px;
        padding-left: 2rem
    }

    .-no-gutter .u-grid-1,.-no-gutter .u-grid-2,.-no-gutter .u-grid-3,.-no-gutter .u-grid-4,.-no-gutter .u-grid-5,.-no-gutter .u-grid-6,.-no-gutter .u-grid-7,.-no-gutter .u-grid-8,.-no-gutter .u-grid-9,.-no-gutter .u-grid-10,.-no-gutter .u-grid-11,.-no-gutter .u-grid-12 {
        padding-left: 0
    }

    .u-grid-row [class*=u-grid-]+[class*=u-grid-] {
        margin-bottom: 0;
        margin-top: 0
    }

    .u-grid-row {
        margin-left: -2rem
    }

    .u-grid-row:after {
        clear: both;
        content: "";
        display: table
    }

    .u-grid-row.-no-gutter {
        margin-left: 0
    }

    .u-grid-1 {
        width: 8.33333%
    }

    .u-grid-offset-1 {
        margin-left: 8.33333%
    }

    .u-grid-2 {
        width: 16.66667%
    }

    .u-grid-offset-2 {
        margin-left: 16.66667%
    }

    .u-grid-3 {
        width: 25%
    }

    .u-grid-offset-3 {
        margin-left: 25%
    }

    .u-grid-4 {
        width: 33.33333%
    }

    .u-grid-offset-4 {
        margin-left: 33.33333%
    }

    .u-grid-5 {
        width: 41.66667%
    }

    .u-grid-offset-5 {
        margin-left: 41.66667%
    }

    .u-grid-6 {
        width: 50%
    }

    .u-grid-offset-6 {
        margin-left: 50%
    }

    .u-grid-7 {
        width: 58.33333%
    }

    .u-grid-offset-7 {
        margin-left: 58.33333%
    }

    .u-grid-8 {
        width: 66.66667%
    }

    .u-grid-offset-8 {
        margin-left: 66.66667%
    }

    .u-grid-9 {
        width: 75%
    }

    .u-grid-offset-9 {
        margin-left: 75%
    }

    .u-grid-10 {
        width: 83.33333%
    }

    .u-grid-offset-10 {
        margin-left: 83.33333%
    }

    .u-grid-11 {
        width: 91.66667%
    }

    .u-grid-offset-11 {
        margin-left: 91.66667%
    }

    .u-grid-12 {
        width: 100%
    }

    .u-grid-offset-12 {
        margin-left: 100%
    }

    .article-grid-item {
        width: 33.33333%
    }

    .audio[data-features=block][min-width~="480px"],.story-attribution {
        font-size: 1.6rem
    }

    .callout-section .callout-section-right .homecontent-stripe {
        height: 34rem
    }

    .callout {
        display: flex;
        min-height: 31.2rem
    }

    .callout-text {
        font-size: 1.6rem;
        flex-direction: column;
        justify-content: center
    }

    .callout-text+.callout-text {
        border-top: none
    }

    .callout [class*=callout-] {
        display: flex
    }

    .callout [class*=callout-] p+p {
        margin-top: 0
    }

    .callout-image {
        padding-bottom: 0
    }

    .callout [class*=callout-]:last-child:first-child {
        min-height: 31.2rem;
        padding: 5.4rem 2.4rem;
        width: calc(100% - 4.8rem)
    }

    .callout [class*=callout-]:nth-last-child(2):first-child,.callout [class*=callout-]:nth-last-child(2):first-child~[class*=callout-] {
        min-height: 31.2rem;
        width: 50%
    }

    .callout .callout-image:nth-last-child(2):first-child~.callout-text,.callout .callout-text:nth-last-child(2):first-child,.callout .callout-text:nth-last-child(2):first-child~.callout-text {
        margin: 3.6rem 0;
        min-height: 31.2rem;
        padding: 1.8rem 6rem
    }

    .callout .callout-text:nth-last-child(2):first-child~.callout-text {
        border-left: 1px solid hsla(0,0%,100%,.5);
        width: calc(50% - 1px)
    }

    .callout.no-separator .callout-text:nth-last-child(2):first-child~.callout-text {
        border-left: none
    }

    .callout-vertical {
        flex-direction: row;
        justify-content: space-between
    }

    .callout-vertical-item-content,.callout-vertical-item-intro {
        font-size: 1.6rem
    }

    .callout-vertical-item {
        align-items: center;
        display: flex;
        justify-content: center;
        width: calc(50% - 2rem)
    }

    .callout-vertical-item+.callout-vertical-item {
        margin-top: 0
    }

    .no-flexbox .callout-vertical-item-bordered {
        float: left
    }

    .no-flexbox .callout-vertical-item-photo {
        float: right
    }

    .carousel {
        margin: 6rem 0;
        overflow: visible;
        -ms-scroll-snap-type: none;
        scroll-snap-type: none;
        -ms-scroll-snap-destination: 0 0;
        scroll-snap-destination: 0 0;
        width: 100%
    }

    .carousel,.carousel-list {
        padding: 0;
        position: relative
    }

    .carousel-list {
        display: block
    }

    .carousel-item {
        transform: scale(.85714) translate3d(-50%,0,0);
        box-shadow: 0 0 32px rgba(0,0,0,.2);
        left: 50%;
        position: absolute;
        -ms-scroll-snap-coordinate: none;
        scroll-snap-coordinate: none;
        top: 0;
        transform-origin: left center;
        transition: transform .6s ease 0s,z-index 0s linear 0s;
        width: 35rem;
        z-index: 1
    }

    .carousel-item[data-item=first] {
        transform: scale(1) translate3d(-50%,0,0);
        transition: transform .6s ease 0s,z-index 0s linear .3s;
        z-index: 3
    }

    .carousel-item[data-item=first][data-direction=next]:before,.carousel-item[data-item=first][data-direction=prev]:before {
        transition: opacity .15s ease 0s
    }

    .carousel-item[data-item=first][data-direction=next]:before {
        background: linear-gradient(90deg,rgba(0,0,0,.6) 0,transparent 50%)
    }

    .carousel-item[data-item=first][data-direction=prev]:before {
        background: linear-gradient(270deg,rgba(0,0,0,.6) 0,transparent 50%)
    }

    .carousel-item[data-item=last],.carousel-item[data-item=second] {
        transition: transform .6s ease 0s,z-index 0s linear .3s;
        z-index: 2
    }

    .carousel-item[data-item=last]:after,.carousel-item[data-item=last]:before,.carousel-item[data-item=second]:after,.carousel-item[data-item=second]:before {
        opacity: 1
    }

    .carousel-item[data-item=second] {
        transform: scale(.85714) translateZ(0)
    }

    .carousel-item[data-item=second]:before {
        background: linear-gradient(90deg,rgba(0,0,0,.6) 0,transparent 50%)
    }

    .carousel-item[data-item=last] {
        transform: scale(.85714) translate3d(-100%,0,0)
    }

    .carousel-item[data-item=last]:before {
        background: linear-gradient(270deg,rgba(0,0,0,.6) 0,transparent 50%)
    }

    .carousel-item:after,.carousel-item:before {
        content: "";
        display: block;
        height: 100%;
        left: 0;
        margin: 0;
        opacity: 0;
        pointer-events: none;
        position: absolute;
        top: 0;
        transform: translateZ(0);
        transition: opacity .15s ease .15s;
        width: 100%;
        z-index: 10
    }

    .carousel-item:before {
        background: linear-gradient(270deg,transparent 20%,transparent 60%)
    }

    .carousel-item:after {
        background-color: rgba(0,0,0,.2)
    }

    .carousel-item-inner {
        box-shadow: none;
        margin: 0;
        transform: translateZ(0)
    }

    .carousel-item-heading,.carousel-item-text {
        font-size: 1.6rem
    }

    .carousel-button-next,.carousel-button-prev {
        overflow: hidden;
        text-align: left;
        text-indent: 150%;
        white-space: nowrap;
        word-break: normal;
        word-wrap: normal;
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background: transparent url(/sites/all/themes/rotary_rotaryorg/images/carousel-arrow.svg) no-repeat 50% 50%;
        background-size: 72px 31px;
        border: none;
        display: block;
        height: 7.1rem;
        margin-top: -3.5rem;
        padding: 0;
        position: absolute;
        top: 50%;
        transition: all .3s ease;
        width: 11.2rem;
        z-index: 100
    }

    .cause-navigation-list {
        margin-top: -3.6rem;
        padding-bottom: 6.6rem
    }

    .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        font-size: 22px;
        height: 100%;
        min-height: 290px;
        margin: 0 8%;
        top: 0;
        transition: all .3s ease;
        width: 83%;
        z-index: 10;
        border-radius: 50%
    }

    .home-causes-item-list {
        padding: 0 13px 6px;
        position: relative;
        width: 50%;
        float: left;
        list-style-type: none;
        margin: 0;
        overflow: hidden
    }

    .home-causes-item-list:before {
        content: "";
        display: block;
        padding-bottom: 85%;
        height: 0;
        width: 100%
    }

    .mobile-view {
        display: block
    }

    .mobile-view .layout-container {
        padding: 6rem 1.8rem!important
    }

    .mobile-view li#cause--7 {
        text-align: center;
        width: 78%;
        padding-left: 29%
    }

    .mobile-view .desktop-view {
        display: none
    }

    .hero-type,.hero-type .home-hero-title {
        text-align: center
    }

    .hero-type {
        min-height: 30rem
    }

    .hero-type.-layout-padding {
        padding: 6rem 1.8rem
    }

    .hero-type.-tall:after {
        height: 60%;
        background: linear-gradient(0deg,rgba(0,0,0,.7) 0,transparent)
    }

    .hero-type .hero-type-text {
        padding-top: 3rem;
        padding-bottom: 3rem
    }

    .hero-type.hero-type-mobile-display-center .hero-type-background,.hero-type.hero-type-mobile-display-center .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-center [data-hero-type-slide],.hero-type.hero-type-mobile-display-full-width .hero-type-background,.hero-type.hero-type-mobile-display-full-width .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-full-width [data-hero-type-slide],.hero-type.hero-type-mobile-display-left .hero-type-background,.hero-type.hero-type-mobile-display-left .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-left [data-hero-type-slide],.hero-type.hero-type-mobile-display-right .hero-type-background,.hero-type.hero-type-mobile-display-right .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-right [data-hero-type-slide] {
        background-position-x: 30%
    }

    .hero {
        min-height: 30rem
    }

    .hero.-layout-padding {
        padding: 6rem 1.8rem
    }

    .hero.-tall:after {
        height: 60%;
        background: linear-gradient(0deg,rgba(0,0,0,.7) 0,transparent)
    }

    .hero-text {
        padding-top: 3rem;
        padding-bottom: 3rem
    }

    .hero-mosaic {
        height: 50vh;
        min-height: 45rem
    }

    .hero-mosaic-item {
        font-size: 1.6rem;
        float: left;
        height: 50%;
        width: 50%
    }

    .hero-mosaic-item.-feature {
        height: 100%
    }

    .hero-mosaic-item.-feature a {
        padding-top: 4.2rem
    }

    .hero-mosaic-item a {
        display: flex;
        flex-direction: column;
        height: 100%;
        padding: 4.2rem;
        text-align: left;
        justify-content: flex-end
    }

    .hero-callout {
        font-size: 1.6rem
    }

    .image-callout[data-features*=text-bottom] .image-callout-text-container {
        align-items: flex-end;
        text-align: center
    }

    .image-callout[data-features*=text-center] .image-callout-text-container {
        text-align: center
    }

    .image-callout[data-features*=text-left] .image-callout-text-container {
        text-align: left
    }

    .image-callout[data-features*=text-right] .image-callout-text-container {
        text-align: right
    }

    .image-callout-article,.image-callout-cta,.image-callout-quote,.image-callout-text {
        padding: 6rem 4.8rem
    }

    .image-callout-article {
        padding-bottom: 3rem;
        padding-top: 3rem
    }

    .-info-graphic .caption-text,.caption-text[min-width~="700px"],.image-callout-caption {
        font-size: 1.6rem
    }

    .impact-stat-list {
        flex-direction: column
    }

    img.stat-icon {
        width: 8rem;
        padding: 2px 3px 8px 1px;
        height: 9.7rem
    }

    .title-text .impact-stat-number {
        font-size: 5.2rem
    }

    .text-stat-title {
        font-size: 1.6rem
    }

    .impact-stat-description {
        font-size: 1.7rem
    }

    .impact-stat-set [data-animate=fade-up][data-is=ready] {
        opacity: 1;
        transform: translateY(0)
    }

    .impact-stat-set [data-animate=fade-up] {
        transition: none
    }

    .site-footer .link-dropdown-toggle {
        font-size: 1.6rem
    }

    .modal-content {
        padding-top: 6rem;
        width: calc(100% - 12rem)
    }

    .news-features-container {
        width: 100%
    }

    .news-features-container .hero-mosaic-item {
        width: 50%;
        height: 36rem
    }

    .news-features-container .hero-mosaic-item a {
        padding-top: 10rem
    }

    .news-features-container .-feature {
        height: 38.5rem;
        width: 100%;
        border-bottom: .4rem solid #ffc000
    }

    .news-features-container .-feature a {
        padding-top: 16rem
    }

    .fade-in {
        opacity: 0;
        transition: opacity .25s ease-in
    }

    .fade-in.appear {
        opacity: 1
    }

    .from-left {
        grid-column: 2/3;
        transform: translateX(-50%)
    }

    .from-right {
        grid-column: 3/4;
        transform: translateX(50%);
        width: 50%
    }

    .from-left,.from-right {
        transition: opacity .25s ease-in,transform .4s ease-in;
        opacity: 0
    }

    .from-left.appear,.from-right.appear {
        transform: translateX(0);
        opacity: 1
    }

    .page-cards {
        display: flex;
        flex-wrap: wrap;
        justify-content: center
    }

    .no-flexbox .page-cards {
        display: block;
        max-width: 60rem
    }

    .page-card {
        font-size: 1.6rem;
        display: flex;
        box-sizing: content-box;
        margin: 0!important;
        padding: 3.6rem 0 0;
        width: calc(50% - 1.6rem)
    }

    .page-card:nth-child(odd) {
        padding-right: 1.2rem
    }

    .page-card:nth-child(2n) {
        padding-left: 1.2rem
    }

    .page-card:nth-child(-n+2) {
        padding-top: 0
    }

    .page-card:last-child {
        padding-right: 0
    }

    .no-flexbox .page-card {
        display: block;
        padding-left: 0!important;
        padding-right: 0!important;
        width: 100%
    }

    .no-flexbox .page-card+.page-card {
        padding-top: 2.4rem
    }

    .page-card-content {
        padding: 0 0 2.4rem;
        width: 100%
    }

    .page-card-image {
        background-color: #39424a;
        display: block;
        height: 0;
        line-height: 0;
        margin-bottom: 2.4rem;
        overflow: hidden;
        padding-bottom: 71.42857%;
        position: relative;
        width: 100%
    }

    .page-card-image img {
        display: block;
        height: 100%;
        left: 0;
        position: absolute;
        top: 0;
        transition: all .3s ease;
        width: 100%
    }

    .related ul {
        font-size: 1.6rem
    }

    .rotary-federated-solr-client {
        display: flex
    }

    .rotary-federated-solr-client .search-form-container {
        flex: 1 1 0%;
        padding-left: calc((100vw - 74rem) / 4);
        padding-right: 4rem
    }

    .rotary-federated-solr-client .search-results-container {
        flex: 2 2 0%;
        padding-right: calc((100vw - 74rem) / 6);
        padding-left: 4rem
    }

    .timeline-header,.timeline .timeline-heading {
        font-size: 1.6rem
    }

    .topic-banner {
        display: flex
    }

    .topic-banner-header {
        font-size: 1.6rem;
        width: 33.33333%
    }

    .topic-banner-list {
        width: 66.66667%
    }

    li.topic-banner-item:nth-child(odd) {
        padding: 0 2rem 0 4rem
    }

    li.topic-banner-item:nth-child(2n) {
        padding: 0 4rem 0 2rem
    }

    li.topic-banner-item a {
        font-size: 1.6rem
    }

    .topic-bundle {
        display: flex
    }

    li.topic-bundle-item {
        font-size: 1.6rem;
        padding-left: 2rem;
        padding-right: 2rem;
        width: 33.33333%
    }

    .columns-n-callouts>:only-child {
        margin: 0 2.4rem
    }
}

@media (min-width: 47.5em) and (min-width:47.5em) {
    .columns-n-callouts .callout-text.u-grid-1 {
        width:8.33333%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-1,.columns-n-callouts .callout-text.u-grid-1:only-child {
        width: 8.33333%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-2 {
        width: 16.66667%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-2,.columns-n-callouts .callout-text.u-grid-2:only-child {
        width: 16.66667%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-3 {
        width: 25%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-3,.columns-n-callouts .callout-text.u-grid-3:only-child {
        width: 25%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-4 {
        width: 33.33333%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-4,.columns-n-callouts .callout-text.u-grid-4:only-child {
        width: 33.33333%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-5 {
        width: 41.66667%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-5,.columns-n-callouts .callout-text.u-grid-5:only-child {
        width: 41.66667%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-6 {
        width: 50%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-6,.columns-n-callouts .callout-text.u-grid-6:only-child {
        width: 50%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-7 {
        width: 58.33333%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-7,.columns-n-callouts .callout-text.u-grid-7:only-child {
        width: 58.33333%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-8 {
        width: 66.66667%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-8,.columns-n-callouts .callout-text.u-grid-8:only-child {
        width: 66.66667%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-9 {
        width: 75%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-9,.columns-n-callouts .callout-text.u-grid-9:only-child {
        width: 75%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-10 {
        width: 83.33333%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-10,.columns-n-callouts .callout-text.u-grid-10:only-child {
        width: 83.33333%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-11 {
        width: 91.66667%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-11,.columns-n-callouts .callout-text.u-grid-11:only-child {
        width: 91.66667%!important;
        margin: 0 auto
    }

    .columns-n-callouts .callout-text.u-grid-12 {
        width: 100%!important;
        margin: 3.6rem auto
    }

    .columns-n-callouts .callout-image.u-grid-12,.columns-n-callouts .callout-text.u-grid-12:only-child {
        width: 100%!important;
        margin: 0 auto
    }
}

@media (min-width: 840px) {
    .text-stat .text-stat-list li:nth-last-child(3):first-child:first-child,.text-stat .text-stat-list li:nth-last-child(3):first-child~li:first-child {
        margin-bottom:-350px
    }
}

@media (min-width: 56.25em) {
    .carousel-item[data-item=second] {
        transform:scale(.85714) translate3d(15%,0,0)
    }

    .carousel-item[data-item=last] {
        transform: scale(.85714) translate3d(-115%,0,0)
    }

    .carousel-button-next {
        margin-right: -470px
    }

    .carousel-button-prev {
        margin-left: -470px
    }
}

@media (min-width: 58.5em) {
    .template-story .u-pull-1 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .template-story .u-pull-1.image-block,.template-story .u-pull-1.slideshow,.template-story .u-pull-1.u-container-bordered {
        margin-top: 1.2rem
    }

    .template-story .u-pull-1.u-pull-left {
        float: left;
        margin-left: -10rem;
        margin-right: 2.4rem
    }

    .template-story .u-pull-1.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -10rem
    }
}

@media (min-width: 62.5em) and (-ms-high-contrast:active),(min-width:62.5em) and (-ms-high-contrast:none) {
    .stat-set {
        width:31%
    }
}

@media (min-width: 62.5em) {
    .site-header {
        box-shadow:none;
        margin-bottom: 5rem;
        padding: 0 1.8rem
    }

    .site-header-container {
        height: 8rem;
        padding-top: 2rem;
        text-align: left;
        max-width: 154rem
    }

    .site-header-logo {
        margin: 0
    }

    .site-nav-toggle-mobile,.site-nav-toggle-search,.site-nav-toggle-search-desktop {
        font-size: 1.4rem;
        line-height: 2.4rem;
        position: absolute;
        right: unset
    }

    .site-nav-toggle-search-icon {
        top: 44px;
        left: 0
    }

    .-alert .header-message-button {
        background-color: #ffe1e1
    }

    .-information .header-message-button {
        background-color: #018fb7
    }

    .site-nav-container {
        background-color: #fff;
        height: auto;
        padding: -1px 1.8rem 0;
        top: 8rem
    }

    .js .site-nav-container,[data-nav-is=open] .site-nav-container {
        box-shadow: 0 0 18px rgba(0,0,0,.3)
    }

    [data-nav-is=close] .site-nav-container {
        box-shadow: none
    }

    .site-nav {
        opacity: 1;
        overflow: hidden;
        visibility: visible;
        padding: 0 1.8rem
    }

    .site-nav:after {
        width: 100%;
        height: 1px;
        background-color: #e8ebee;
        position: absolute;
        content: "";
        top: 49px;
        left: 0
    }

    .site-nav-list {
        padding: 0;
        margin-left: auto;
        margin-right: auto;
        border-bottom: 1px solid transparent;
        height: 50px;
        max-width: 154rem
    }

    .site-nav-item {
        float: left;
        padding-right: 4rem;
        position: relative;
        text-align: left
    }

    .site-nav-item:nth-last-child(5):first-child,.site-nav-item:nth-last-child(5):first-child~.site-nav-item {
        width: 20%
    }

    .site-nav-item:nth-last-child(6):first-child,.site-nav-item:nth-last-child(6):first-child~.site-nav-item {
        width: 16.66667%
    }

    .site-nav-item:last-child {
        padding-right: 0
    }

    .site-nav-item-heading {
        font-size: 1.3rem;
        line-height: 2.4rem;
        margin: 0
    }

    .site-nav-item-heading a {
        font-weight: 400;
        display: block;
        line-height: 5rem;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap
    }

    [data-whatinput=touch] .site-nav-item-heading a {
        color: #5e717d
    }

    .site-nav-item-heading .site-nav-a11y-helper {
        border: 0;
        clip: rect(1px 1px 1px 1px);
        clip: rect(1px,1px,1px,1px);
        height: 1px;
        overflow: hidden;
        position: absolute;
        white-space: nowrap;
        width: 1px;
        display: inline
    }

    .site-nav-sublist a {
        display: block;
        font-size: 1.4rem;
        line-height: 2rem
    }

    [data-whatinput=keyboard] .site-nav-sublist a:focus {
        background-color: #e5f5fa;
        outline: none
    }

    .site-nav-sublist {
        overflow: visible
    }

    .js .site-nav-sublist,[data-nav-is=close] .site-nav-sublist {
        max-height: 0;
        opacity: 0;
        transition: max-height .3s ease-out .2s,opacity .3s ease-out .2s,visibility 0s linear .5s;
        visibility: hidden
    }

    [data-nav-is=open] .site-nav-sublist {
        max-height: 60rem;
        opacity: 1;
        transition: max-height .3s ease-in .2s,opacity .3s ease-in .2s,visibility 0s linear .2s;
        visibility: visible
    }

    .site-nav-item-heading,.site-nav-sublist a {
        position: relative
    }

    .site-nav-item-heading:after,.site-nav-sublist a:after {
        background: url(/sites/all/themes/rotary_rotaryorg/images/arrow-down-blue.svg) no-repeat 50% 50%;
        background-size: 10px 6px;
        content: "";
        display: block;
        height: 6px;
        left: -1.8rem;
        margin-top: -3px;
        opacity: 0;
        position: absolute;
        top: 50%;
        transform: rotate(-90deg);
        transition: all .3s ease .2s;
        width: 10px
    }

    [data-whatinput=touch] .site-nav-item-heading:after,[data-whatinput=touch] .site-nav-sublist a:after {
        display: none
    }

    .site-nav-item-heading:focus:after,.site-nav-item-heading:hover:after,.site-nav-sublist a:focus:after,.site-nav-sublist a:hover:after {
        opacity: 1;
        left: -1.5rem
    }

    [data-whatinput=touch] [data-is=open] .site-nav-item-heading a {
        overflow: visible;
        position: relative
    }

    [data-whatinput=touch] [data-is=open] .site-nav-item-heading a:after {
        background-color: transparent;
        content: "Ã—";
        color: #bb0043;
        display: block;
        font-size: 2rem;
        left: auto;
        line-height: 2rem;
        margin: -.9rem 0 0;
        position: absolute;
        right: -1rem;
        text-align: center;
        top: 50%;
        width: 2rem
    }

    .site-nav-subitem {
        opacity: 0;
        transition: .15s ease .2s
    }

    [data-nav-is=open] .site-nav-subitem {
        opacity: 1;
        transition: .15s ease
    }

    .site-nav-subitem:last-child {
        padding-bottom: 3.6rem
    }

    .site-nav-subitem.-article {
        margin-top: 1.2rem
    }

    .site-nav-subitem.-article a:after {
        display: none
    }

    .site-nav-utility {
        background-color: #fff;
        height: 8rem;
        left: 0;
        padding: 2.2rem 1.8rem 0;
        position: absolute;
        right: 0;
        text-align: right;
        top: -8rem;
        z-index: 1
    }

    .site-nav-utility-container {
        display: flex;
        justify-content: flex-end;
        margin: 0 auto;
        max-width: 153rem
    }

    .site-nav-utility-links.-small {
        display: none
    }

    .site-nav-utility-links.-large {
        display: block;
        padding-top: 2px
    }

    .site-nav-utility-links.-large button {
        position: relative;
        height: auto;
        padding-top: 0;
        margin-right: 1rem;
        margin-left: 1rem;
        overflow: visible
    }

    .site-nav-utility-search {
        width: 20%;
        margin-top: .2%;
        margin-right: 1%;
        position: relative;
        visibility: visible;
        display: none
    }

    .site-nav-utility-search form {
        box-shadow: none;
        padding: 0
    }

    .site-nav-utility-search button,.site-nav-utility-search input[type=submit] {
        right: .3rem;
        top: .1rem
    }

    .site-nav-utility-search input[type=search],.site-nav-utility-search input[type=text] {
        height: 3rem
    }

    .site-nav-utility-ctas {
        background-color: transparent;
        display: inline-block;
        height: auto;
        opacity: 1;
        position: static;
        visibility: visible;
        width: auto
    }

    .site-nav-utility-ctas .u-button.-slim {
        padding: .8rem 2rem;
        margin-top: 2px;
        border-radius: 2rem
    }

    .site-nav-utility-ctas li {
        display: inline-block;
        float: none;
        width: auto
    }

    .site-nav-utility-ctas li .u-button.-slim {
        padding: .5rem 3rem;
        margin-top: 2px;
        border-radius: 2rem
    }

    .site-nav-utility-ctas li+li {
        border: none;
        margin-left: 2.1rem
    }

    .heading-h1.-banner {
        font-size: 10rem;
        line-height: 12rem
    }

    .heading-h2.-alternate-light,.wysiwyg h2.-alternate-light {
        font-size: 4.8rem;
        line-height: 6.6rem
    }

    .callout-section {
        padding: 8.5rem 0 18.5rem;
        display: flex
    }

    .callout-section .callout-section-left,.callout-section .callout-section-left-content {
        height: 62.94rem
    }

    .callout-section .callout-section-left[data-module=in-view] {
        opacity: 0;
        transform: translateY(0)
    }

    .callout-section .callout-section-left[data-is=visible] {
        opacity: 1;
        transform: translateY(1.8rem);
        transition: all .9s ease
    }

    .callout-section .callout-section-left .callout-section-left-content-holder .callout-section-title {
        font-size: 36px;
        line-height: 49px
    }

    .callout-section .callout-section-left .callout-section-left-content-holder .callout-section-description {
        text-align: center;
        margin: 37px 15px
    }

    .callout-section .callout-section-right {
        flex: 1;
        height: 64.34rem;
        margin-top: 63px;
        overflow: hidden
    }

    .callout-section .callout-section-right[data-module=in-view] {
        opacity: 0;
        transform: translateY(1.8rem);
        transition: all .9s ease
    }

    .callout-section .callout-section-right[data-is=visible] {
        opacity: 1;
        transform: translateY(0)
    }

    .callout-section .callout-section-right .homecontent-stripe {
        height: 100%
    }

    .carousel-item[data-item=second] {
        transform: scale(.85714) translate3d(30%,0,0)
    }

    .carousel-item[data-item=last] {
        transform: scale(.85714) translate3d(-130%,0,0)
    }

    .carousel-button-next {
        margin-right: -515px
    }

    .carousel-button-prev {
        margin-left: -515px
    }

    .cause-navigation-list {
        display: flex;
        margin-top: 0;
        max-width: none;
        padding-bottom: 0;
        width: 100%
    }

    .cause-navigation-item+.cause-navigation-item {
        margin: 0
    }

    .cause-navigation-item {
        flex-basis: 0;
        flex-grow: 1;
        height: 35vh;
        min-height: 30rem;
        overflow: hidden;
        position: relative
    }

    .cause-navigation-item:hover .cause-navigation-image {
        transform: scale(1.1) translateZ(0)
    }

    .cause-navigation-item a {
        align-items: center;
        color: #fff;
        display: flex;
        height: 100%;
        justify-content: center;
        padding: 1.2rem;
        position: relative;
        text-shadow: 0 0 4px rgba(0,0,0,.45);
        z-index: 2
    }

    .cause-navigation-item a:focus,.cause-navigation-item a:hover {
        text-decoration: none
    }

    .cause-navigation-image {
        background-color: #000;
        height: 100%;
        left: 0;
        position: absolute;
        transition: transform .3s ease;
        transform: translateZ(0);
        width: 100%;
        z-index: 1
    }

    .cause-navigation-image,.home-causes-image {
        background-position: 50% 50%;
        background-repeat: no-repeat;
        background-size: cover;
        display: block;
        top: 0
    }

    .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        border: none;
        font-size: 22px;
        height: calc(100% - 10px);
        left: 5px;
        margin: 0;
        transition: all .3s ease;
        width: calc(100% - 10px);
        z-index: 10;
        border-radius: 50%
    }

    .home-causes-list {
        display: flex;
        flex: 0 1 auto;
        flex-direction: row;
        flex-wrap: wrap;
        margin-left: -5px;
        margin-right: -5px;
        width: calc(100% + 10px)
    }

    .home-causes-list:after {
        clear: both;
        content: "";
        display: table
    }

    .home-causes-item-list {
        padding: 0 25px 65px;
        position: relative;
        width: 33.33333%
    }

    .home-causes-item-list:before {
        content: "";
        display: block;
        padding-bottom: 85%;
        height: 0;
        width: 100%
    }

    .home-causes-item-list[data-hidden] {
        opacity: 0;
        visibility: hidden
    }

    .home-causes-item-list.doppelganger {
        transition: top .3s ease,left .3s ease,width .3s ease;
        position: fixed;
        z-index: 1000
    }

    .causes-link div {
        padding: 11px 0 10px 12px;
        width: 87.333333%;
        top: 0;
        font-style: normal;
        font-weight: 700;
        font-size: 16px;
        line-height: 22px;
        letter-spacing: .02em;
        color: #fff;
        text-align: center
    }

    .desktop-view {
        display: block
    }

    .mobile-view {
        display: none
    }

    .hero-type .home-hero-title {
        font-size: 7.2rem;
        line-height: 7.2rem
    }

    .hero-type .home-hero-title>span {
        font-size: 3rem;
        line-height: 7.2rem
    }

    .hero-type.-tall,.hero.-tall {
        height: calc(100vh - 13rem)
    }

    .stat-background-img[data-module=in-view] {
        opacity: 0;
        transform: translateY(1.8rem);
        transition: all .6s ease
    }

    @supports (-moz-appearance: none) {
        .stat-background-img[data-module=in-view] {
            transform:none
        }
    }

    .stat-background-img[data-is=visible] {
        opacity: 1;
        transform: translateY(0)
    }

    @supports (-moz-appearance: none) {
        .stat-background-img[data-is=visible] {
            transform:none
        }
    }

    .impact-stat-list {
        margin: 0 auto;
        width: 100%;
        display: flex;
        flex-direction: unset
    }

    .impact-stat-list li {
        margin: 0;
        padding-left: 0
    }

    .impact-stat-list li:before {
        display: none
    }

    .title-info {
        display: flex;
        padding: 0 5%
    }

    .stat-suffix {
        font-size: 2.625rem;
        line-height: 0
    }

    .title-text {
        flex-basis: 70%;
        padding-bottom: 8%
    }

    .title-img {
        flex-basis: 30%;
        height: 10rem;
        width: 10rem;
        display: inline-block
    }

    img.stat-icon {
        width: 7.5rem;
        padding: 1px 2px 3px 0;
        height: 9rem
    }

    .title-text .impact-stat-number {
        font-size: 5.1rem
    }

    .text-stat-title {
        font-size: 1.5rem
    }

    .stat-set {
        padding: 0 1%;
        margin: 0 1%;
        flex-basis: 32.5%;
        max-width: 32.5%
    }

    .impact-stat-description {
        font-size: 1.7rem
    }

    .fade-in {
        opacity: 0;
        transition: opacity .25s ease-in
    }

    .fade-in.appear {
        opacity: 1
    }

    .from-left {
        grid-column: 2/3;
        transform: translateX(-50%);
        transition: opacity .25s ease-in,transform .4s ease-in;
        opacity: 0
    }

    .from-left.appear {
        transform: translateX(0);
        opacity: 1
    }

    .custom-u-width {
        width: 100%;
        margin: 0 auto
    }

    .news-features-container .hero-mosaic-item a {
        padding: 3rem 2.44rem
    }

    .news-features-container .hero-mosaic-item a:before {
        background: linear-gradient(180deg,rgba(0,0,0,.1) 33.85%,rgba(0,0,0,.8) 82.29%);
        opacity: 1
    }

    .news-features-container .-feature {
        height: 72rem;
        width: 63.5%;
        border-bottom: .6rem solid #ffc000
    }

    .news-features-container .-feature a:before {
        background: linear-gradient(0deg,#000,transparent 51.29%);
        opacity: 1
    }

    .news-features-container .-feature .hero-background {
        background-size: initial!important
    }

    .news-features-container {
        height: 76rem
    }

    .news-features-container .hero-mosaic {
        width: calc(100% - 200px);
        margin-left: auto;
        margin-right: auto
    }

    .news-features-container .from-right {
        width: 36.5%
    }

    .news-features-container .special-feature {
        margin-top: 3rem
    }

    h2.news-features-title {
        padding: 3.5rem 0 6rem
    }

    .related-stories {
        float: left;
        width: 68%
    }

    .related-resources {
        float: right;
        margin-top: 0;
        width: 26%
    }

    .related-resources li {
        padding-bottom: 1.8rem
    }

    .related-resources li+li {
        border-top: 1px solid #e8ebee;
        padding-top: 1.8rem
    }

    .related-resources ul {
        margin: 0
    }

    .related-resources ul li {
        margin: 0;
        padding-left: 0
    }

    .related-resources ul li:before {
        display: none
    }
}

@media (min-width: 64.75em) {
    .u-pull-1 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .u-pull-1.image-block,.u-pull-1.slideshow,.u-pull-1.u-container-bordered {
        margin-top: 1.2rem
    }

    .u-pull-1.u-pull-left {
        float: left;
        margin-left: -10rem;
        margin-right: 2.4rem
    }

    .u-pull-1.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -10rem
    }
}

@media (min-width: 68.75em) {
    .carousel-item[data-item=second] {
        transform:scale(.85714) translate3d(50%,0,0)
    }

    .carousel-item[data-item=last] {
        transform: scale(.85714) translate3d(-150%,0,0)
    }

    .carousel-button-next {
        margin-right: -575px
    }

    .carousel-button-prev {
        margin-left: -575px
    }
}

@media (min-width: 71em) {
    .template-story .u-pull-2 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .template-story .u-pull-2.image-block,.template-story .u-pull-2.slideshow,.template-story .u-pull-2.u-container-bordered {
        margin-top: 1.2rem
    }

    .template-story .u-pull-2.u-pull-left {
        float: left;
        margin-left: -20rem;
        margin-right: 2.4rem
    }

    .template-story .u-pull-2.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -20rem
    }
}

@media (min-width: 75em) {
    dt {
        font-size:2rem;
        line-height: 3.6rem
    }

    .site-nav-item-heading {
        font-size: 1.5rem;
        line-height: 2.4rem
    }

    .lede {
        font-size: 2.2rem
    }

    .lede.-banner {
        font-size: 3rem;
        line-height: 4.2rem
    }

    .heading-callout {
        font-size: 2.6rem
    }

    .quote-inline {
        font-size: 3.6rem;
        line-height: 5.4rem
    }

    .number-list li {
        padding-left: 0
    }

    .number-list li:before {
        font-size: 14rem;
        height: 10.8rem;
        line-height: 10.8rem;
        margin-left: -19rem;
        width: 17rem;
        text-align: right
    }

    .thumbnail-list img {
        margin-left: -15rem
    }

    .thumbnail-list li {
        padding-left: 0
    }

    .layout-container,.layout-container.-blue+.layout-container:not(.-blue),.layout-container.-dark+.layout-container:not(.-dark),.layout-container.-gray+.layout-container:not(.-gray),.layout-container.-green+.layout-container:not(.-green),.layout-container.-lightgray+.layout-container:not(.-lightgray),.layout-container.-purple+.layout-container:not(.-purple),.layout-container.-red+.layout-container:not(.-red),.layout-container.-royalblue+.layout-container:not(.-royalblue) {
        padding: 9rem 1.8rem
    }

    .layout-container.-image-callout+.layout-container {
        padding-top: 9rem!important
    }

    .form-accordion-tab {
        font-size: 2rem;
        line-height: 3.6rem
    }

    .form-accordion-tab a:after,.form-accordion-tab a:before {
        width: 4.8rem
    }

    .article-grid-title {
        font-size: 2.4rem;
        line-height: 3.6rem
    }

    .-feature .article-grid-title {
        font-size: 3.2rem;
        line-height: 4.2rem
    }

    .story-attribution-author {
        display: inline
    }

    .story-attribution-author:after {
        content: " | "
    }

    .story-attribution-author:last-of-type:after {
        content: ""
    }

    .story-attribution-date {
        margin-top: 1.2rem
    }

    .callout-vertical-item-heading {
        font-size: 2.4rem;
        line-height: 3.6rem
    }

    .home-causes-image {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
        background-position: 50% 50%;
        background-repeat: no-repeat;
        background-size: cover;
        border: none;
        display: block;
        font-size: 22px;
        height: calc(100% - 10px);
        left: 5px;
        margin: 0;
        top: 0;
        transition: all .3s ease;
        width: calc(100% - 10px);
        z-index: 10;
        border-radius: 50%
    }

    .desktop-view {
        display: block
    }

    .hero-type .home-hero-title {
        margin: 1.8rem auto;
        max-width: 80rem
    }

    .hero-type.-layout-padding {
        padding: 9rem 1.8rem
    }

    .hero-type .hero-type-text {
        padding-top: 4.2rem;
        padding-bottom: 4.2rem
    }

    .hero.-layout-padding {
        padding: 9rem 1.8rem
    }

    .hero-text {
        padding-top: 4.2rem;
        padding-bottom: 4.2rem
    }

    .-tall .hero-background,.-tall .hero-background-placeholder,.-tall [data-hero-slide] {
        position: fixed
    }

    .hero-mosaic-title {
        font-size: 3.6rem;
        line-height: 4.8rem
    }

    .image-callout[data-features*=text-left]:after {
        background: linear-gradient(90deg,rgba(0,0,0,.6) 20%,transparent)
    }

    .image-callout[data-features*=text-right]:after {
        background: linear-gradient(90deg,transparent 20%,rgba(0,0,0,.6))
    }

    .image-callout[data-features*=text-bottom]:after {
        background: linear-gradient(180deg,transparent 30%,rgba(0,0,0,.7))
    }

    .image-callout[data-features*=text-left] .image-callout-text-container,.image-callout[data-features*=text-right] .image-callout-text-container {
        width: 50%
    }

    .image-callout[data-features*=text-right] .image-callout-text-container {
        left: auto;
        right: 0
    }

    .image-callout-article,.image-callout-cta,.image-callout-quote,.image-callout-text {
        max-width: 100rem
    }

    .image-callout[data-features*=text-center] .image-callout-article,.image-callout[data-features*=text-center] .image-callout-cta,.image-callout[data-features*=text-center] .image-callout-quote,.image-callout[data-features*=text-center] .image-callout-text {
        padding: 9.6rem 4.8rem
    }

    .image-callout[data-features*=text-heading] .image-callout-article,.image-callout[data-features*=text-heading] .image-callout-cta,.image-callout[data-features*=text-heading] .image-callout-quote,.image-callout[data-features*=text-heading] .image-callout-text {
        padding: 18rem 4.8rem
    }

    .image-callout[data-features*=text-left] .image-callout-article,.image-callout[data-features*=text-left] .image-callout-cta,.image-callout[data-features*=text-left] .image-callout-quote,.image-callout[data-features*=text-left] .image-callout-text {
        padding: 4.8rem 0 4.8rem 9.6rem
    }

    .image-callout[data-features*=text-right] .image-callout-article,.image-callout[data-features*=text-right] .image-callout-cta,.image-callout[data-features*=text-right] .image-callout-quote,.image-callout[data-features*=text-right] .image-callout-text {
        padding: 4.8rem 9.6rem 4.8rem 0
    }

    .image-callout-article-heading {
        font-size: 3.2rem;
        line-height: 4.2rem
    }

    .image-callout-cta {
        font-size: 2.4rem;
        line-height: 3.6rem
    }

    .image-callout-cta hr {
        margin: 7.2rem 0
    }

    .image-callout-cta p {
        margin: 4.8rem 4rem
    }

    .image-callout[data-features*=text-left] .image-callout-cta {
        padding: 9.6rem 0 9.6rem 9.6rem
    }

    .image-callout[data-features*=text-right] .image-callout-cta {
        padding: 9.6rem 9.6rem 9.6rem 0
    }

    .image-callout-quote {
        font-size: 3.6rem;
        line-height: 4.8rem
    }

    .image-callout-quote-attribution {
        font-size: 2.4rem;
        line-height: 3.6rem;
        margin-top: 4.8rem
    }

    .title-text {
        flex-basis: 60%;
        padding-bottom: 8%
    }

    .title-img {
        flex-basis: 40%
    }

    img.stat-icon {
        width: 7.7rem;
        padding: 5px 8px 12px 0;
        height: 10rem
    }

    .text-stat-title {
        font-size: 1.6rem
    }

    .stat-set {
        padding: 0 1%;
        margin: 0 3% 1.2rem;
        flex-basis: 33.33%;
        max-width: 33.33%
    }

    .impact-stat-description {
        font-size: 1.7rem
    }

    .impact-stat-description p {
        margin-left: 1.5rem;
        margin-right: 1.5rem
    }

    .stat-wrapper-description {
        margin-left: 2rem;
        width: 95%
    }

    .custom-u-width {
        width: 95%;
        margin: 0 auto
    }

    .page-card {
        display: flex;
        box-sizing: content-box;
        padding: 3.6rem 0 0;
        width: calc(33.3333% - 1.6rem)
    }

    .page-card:nth-child(3n+1) {
        transition-delay: 0
    }

    .page-card:nth-child(3n+2) {
        transition-delay: .3s
    }

    .page-card:nth-child(3n+3) {
        transition-delay: .6s
    }

    .page-card:nth-child(3n+1),.page-card:nth-child(3n+3) {
        padding-left: 0;
        padding-right: 0
    }

    .page-card:nth-child(-n+3) {
        padding-top: 0
    }

    .page-card:nth-child(3n+2) {
        padding-left: 2.4rem;
        padding-right: 2.4rem
    }

    .page-card:last-child {
        padding-right: 0
    }

    .topic-banner-header .topic-banner-heading,.topic-bundle-heading {
        font-size: 2.4rem;
        line-height: 3.6rem
    }
}

@media (min-width: 75em) and (-ms-high-contrast:active),(min-width:75em) and (-ms-high-contrast:none) {
    .stat-set {
        width:26.5%
    }
}

@media (min-width: 77.25em) {
    .u-pull-2 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .u-pull-2.image-block,.u-pull-2.slideshow,.u-pull-2.u-container-bordered {
        margin-top: 1.2rem
    }

    .u-pull-2.u-pull-left {
        float: left;
        margin-left: -20rem;
        margin-right: 2.4rem
    }

    .u-pull-2.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -20rem
    }
}

@media (min-width: 83.5em) {
    .template-story .u-pull-3 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .template-story .u-pull-3.image-block,.template-story .u-pull-3.slideshow,.template-story .u-pull-3.u-container-bordered {
        margin-top: 1.2rem
    }

    .template-story .u-pull-3.u-pull-left {
        float: left;
        margin-left: -30rem;
        margin-right: 2.4rem
    }

    .template-story .u-pull-3.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -30rem
    }
}

@media (min-width: 89.75em) {
    .u-pull-3 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .u-pull-3.image-block,.u-pull-3.slideshow,.u-pull-3.u-container-bordered {
        margin-top: 1.2rem
    }

    .u-pull-3.u-pull-left {
        float: left;
        margin-left: -30rem;
        margin-right: 2.4rem
    }

    .u-pull-3.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -30rem
    }
}

@media (min-width: 1440px) {
    .rotary-federated-solr-client .search-form-container {
        min-width:38rem
    }

    .rotary-federated-solr-client .search-results-container {
        padding-right: calc((100 vw - 74rem) / 2)
    }
}

@media (min-width: 96em) {
    .template-story .u-pull-4 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .template-story .u-pull-4.image-block,.template-story .u-pull-4.slideshow,.template-story .u-pull-4.u-container-bordered {
        margin-top: 1.2rem
    }

    .template-story .u-pull-4.u-pull-left {
        float: left;
        margin-left: -40rem;
        margin-right: 2.4rem
    }

    .template-story .u-pull-4.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -40rem
    }
}

@media (min-width: 102.25em) {
    .u-pull-4 {
        margin-bottom:1.2rem;
        margin-top: 0
    }

    .u-pull-4.image-block,.u-pull-4.slideshow,.u-pull-4.u-container-bordered {
        margin-top: 1.2rem
    }

    .u-pull-4.u-pull-left {
        float: left;
        margin-left: -40rem;
        margin-right: 2.4rem
    }

    .u-pull-4.u-pull-right {
        float: right;
        margin-left: 2.4rem;
        margin-right: -40rem
    }
}

@media (-ms-high-contrast:active),(-ms-high-contrast:none) {
    .hero,.hero-type {
        height: 10rem
    }

    .impact-stat-list {
        display: inline
    }

    .stat-set {
        float: left
    }
}

@media (max-width: 768px) {
    .impact-narrative-image {
        -webkit-font-smoothing:antialiased;
        -moz-osx-font-smoothing: grayscale;
        display: flex;
        width: 100%;
        justify-content: center;
        min-height: 680px;
        overflow: hidden;
        position: relative;
        background-repeat: no-repeat;
        background-size: cover
    }

    .impact-narrative-image:after {
        clear: both;
        content: "";
        display: table
    }

    .image--bottom-center {
        background-position: 50% 50%
    }

    .image--bottom-right {
        background-position: 100% 0
    }

    .image--bottom-left {
        background-position: -15px 100%
    }

    .final-call-container .final-call-content {
        margin-top: 0;
        max-width: 70rem;
        text-align: left
    }

    .final-call-container .final-call-content a {
        border-bottom: none;
        line-height: 4.23rem
    }
}

@media screen and (max-width: 47.4375em) {
    .hero-type.hero-type-mobile-display-full-width {
        height:auto!important;
        display: block;
        text-shadow: none;
        color: inherit
    }

    .hero-type.hero-type-mobile-display-full-width .hero-type-image {
        position: relative;
        width: 100%;
        padding-top: 75%
    }

    .hero-type.hero-type-mobile-display-full-width .home-hero-title,.hero-type.hero-type-mobile-display-full-width .home-hero-title.-white,.hero-type.hero-type-mobile-display-full-width .home-hero-title.-yellow {
        text-shadow: none;
        color: inherit
    }

    .hero-type.hero-type-mobile-display-full-width .hero-type-background,.hero-type.hero-type-mobile-display-full-width .hero-type-background-placeholder,.hero-type.hero-type-mobile-display-full-width [data-hero-type-slide] {
        height: 100%!important
    }

    .hero-type.hero-type-mobile-display-full-width.-tall:after {
        display: none
    }

    .hero-type.hero-type-mobile-display-full-width .u-button-reversed-white {
        background-color: #019fcb;
        border-color: #019fcb;
        color: #fff
    }

    .hero-type.hero-type-mobile-display-full-width .u-button-reversed-white:hover,[data-whatinput=keyboard] .hero-type.hero-type-mobile-display-full-width .u-button-reversed-white:focus {
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        background-color: transparent;
        color: #019fcb
    }
}

@media (max-width: 760px) {
    .final-call-section-container {
        max-width:110rem;
        display: block
    }

    .final-call-section-content {
        width: 100%;
        padding-top: 20px
    }

    .final-call-section-content .final-call-btn {
        float: none;
        padding-top: 15px
    }
}
