---
layout: ws
title: A space.
back: index.html
css: "#load{position:absolute; height:1px; width:1px; font-size:0; opacity:0;} #abt:hover,#abt:focus,#abt:active{background:url(assets/img/ws-omori.gif);} #lnk:hover,#lnk:focus,#lnk:active{background:url(assets/img/ws-lightbulb.gif);} #clg:hover,#clg:focus,#clg:active{background:url(assets/img/ws-laptop.gif);} #art:hover,#art:focus,#art:active{background:url(assets/img/ws-sketchbook.gif);} #hlp:hover,#hlp:focus,#hlp:active{background:url(assets/img/ws-tissues.gif);} summary:hover #mwo,summary:focus #mwo,summary:active #mwo,details[open] summary{background:url(assets/img/ws-mewo.gif) no-repeat;} details[open] summary img{opacity:0;} details>summary{list-style:none;} details>summary::marker,details>summary::-webkit-details-marker{display:none;} summary,details .box{display:inline-block;}"
---
<div id="load">(upfront background-gif-loader)<img src="{%include url.html%}/assets/img/ws-omori.gif" alt=""><img src="{%include url.html%}/assets/img/ws-lightbulb.gif" alt=""><img src="{%include url.html%}/assets/img/ws-laptop.gif" alt=""><img src="{%include url.html%}/assets/img/ws-sketchbook.gif" alt=""><img src="{%include url.html%}/assets/img/ws-tissues.gif" alt=""><img src="{%include url.html%}/assets/img/ws-mewo.gif" alt=""></div>

<header>
<h1 class="box">A space.</h1>
<div class="box"><p>a-space, if you will.</p></div>
</header>

<main markdown="1">
<div class="gif" id="abt"><a href="{%include url.html%}/about"><img src="{%include url.html%}/assets/img/ws-omori.png" alt="Omori. (link to About page)" title="Omori. (link to About page)"></a></div>

<div class="gif" id="lnk"><a href="{%include url.html%}/links"><img src="{%include url.html%}/assets/img/ws-lightbulb.png" alt="A lightbulb. (link to Links page)" title="A lightbulb. (link to Links page)"></a></div>

<div class="gif" id="clg"><a href="{%include url.html%}/changelog"><img src="{%include url.html%}/assets/img/ws-laptop.png" alt="A laptop. (link to Changelog page)" title="A laptop. (link to Changelog page)"></a></div>

<div class="gif" id="art"><a href="{%include url.html%}/art"><img src="{%include url.html%}/assets/img/ws-sketchbook.png" alt="A sketchook. (link to Art page)" title="A sketchbook. (link to Art page)"></a></div>

<div class="gif" id="hlp"><a href="{%include url.html%}/help"><img src="{%include url.html%}/assets/img/ws-tissues.png" alt="A tissue box. (link to ???)" title="A tissue box. (link to ???)"></a></div>

<details><summary><div class="gif" id="mwo"><img src="{%include url.html%}/assets/img/ws-mewo.png" alt="A cat." title="A cat."></div></summary><div class="box"><p>Waiting for something to happen?</p></div></details><!-- https://stackoverflow.com/questions/61292792/css-selector-for-details-element-when-opened + https://stackoverflow.com/questions/6195329/how-can-you-hide-the-arrow-that-is-displayed-by-default-on-the-html5-details-e/66814239#66814239 -->
</main>