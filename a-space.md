---
layout: ws
title: A space.
back: index.html
css: "/*images+functionality*/ #load{position:absolute; height:1px; width:1px; font-size:0; opacity:0;} #abt .gif:hover,#abt .gif:focus,#abt .gif:active{background:url(assets/img/ws-omori.gif);} #lnk .gif:hover,#lnk .gif:focus,#lnk .gif:active{background:url(assets/img/ws-lightbulb.gif);} #clg .gif:hover,#clg .gif:focus,#clg .gif:active{background:url(assets/img/ws-laptop.gif);} #art .gif:hover,#art .gif:focus,#art .gif:active{background:url(assets/img/ws-sketchbook.gif);} #hlp .gif:hover,#hlp .gif:focus,#hlp .gif:active{background:url(assets/img/ws-tissues.gif);} summary:hover #mwo,summary:focus #mwo,summary:active #mwo,details[open] summary{background:url(assets/img/ws-mewo.gif) no-repeat;} details[open] summary img{opacity:0;}
details>summary{list-style:none;} details>summary::marker,details>summary::-webkit-details-marker{display:none;} summary,details span,header #h1box{display:inline-block;} details .box{margin-top:5px;}
/*actual content styling*/ header,#mewo .box{max-width:35em; margin:0 auto;} h1{padding:.25em 0 .35em;} header div{margin-bottom:.75em;} #mob{margin-top:-.5em;} main{text-align:center;} #room section{margin:1em 0; display:inline-block;} #room{border:.15em solid #000;}  #mewo{padding-top:1em;} #room,#mewo{max-width:1200px; margin:0 auto;}
@media only screen and (min-width:50em){#mob{display:none;} #room{height:750px; text-align:left; position:relative;} #room section{position:absolute;} #art{right:10px;} #hlp{bottom:0; right:10px;} #clg{left:10px;} #abt{left:45%; top:175px;} #lnk{left:45%; top:-275px;} header{margin:50px auto 250px;} #mewo{text-align:left;} #mewo .box{margin:0;}}"
---
<div id="load">(upfront background-gif-loader)<img src="{%include url.html%}/assets/img/ws-omori.gif" alt=""><img src="{%include url.html%}/assets/img/ws-lightbulb.gif" alt=""><img src="{%include url.html%}/assets/img/ws-laptop.gif" alt=""><img src="{%include url.html%}/assets/img/ws-sketchbook.gif" alt=""><img src="{%include url.html%}/assets/img/ws-tissues.gif" alt=""><img src="{%include url.html%}/assets/img/ws-mewo.gif" alt=""></div>

<div id="cent"><header>
<div class="box" id="h1box"><h1>A space.</h1></div>
<div class="box" id="desc"><p>a-space, if you will.</p><p id="mob"><span class="x">(notice for mobile:) </span>Pictures are strewn about. Although this website should work on mobile, it was designed for wider screens.</p></div>
</header></div>

<main>
	<div id="room">
		<section id="abt"><div class="gif"><a href="{%include url.html%}/about"><img src="{%include url.html%}/assets/img/ws-omori.png" alt="Omori. (link to About page)" title="Omori. (link to About page)"></a></div></section>

		<section id="lnk"><div class="gif"><a href="{%include url.html%}/links"><img src="{%include url.html%}/assets/img/ws-lightbulb.png" alt="A lightbulb. (link to Links page)" title="A lightbulb. (link to Links page)"></a></div></section>

		<section id="clg"><div class="gif"><a href="{%include url.html%}/changelog"><img src="{%include url.html%}/assets/img/ws-laptop.png" alt="A laptop. (link to Changelog page)" title="A laptop. (link to Changelog page)"></a></div></section>

		<section id="art"><div class="gif"><a href="{%include url.html%}/art"><img src="{%include url.html%}/assets/img/ws-sketchbook.png" alt="A sketchook. (link to Art page)" title="A sketchbook. (link to Art page)"></a></div></section>

		<section id="hlp"><div class="gif"><a href="{%include url.html%}/help"><img src="{%include url.html%}/assets/img/ws-tissues.png" alt="A tissue box. (link to ???)" title="A tissue box. (link to ???)"></a></div></section>
	</div>

	<section id="mewo"><details><summary><div class="gif" id="mwo"><img src="{%include url.html%}/assets/img/ws-mewo.png" alt="A cat." title="A cat."></div></summary><div class="box"><p><span>Waiting for something to happen?</span> <span>(All these pictures are clickable.)</span></p></div></details><!-- https://stackoverflow.com/questions/61292792/css-selector-for-details-element-when-opened + https://stackoverflow.com/questions/6195329/how-can-you-hide-the-arrow-that-is-displayed-by-default-on-the-html5-details-e/66814239#66814239 --></section>
</main>