---
layout: ws
title: Artwork.
img:
  url: ws-sketchbook
  alt: A sketchbook. (back to homepage)
  link: a-space
css: "body{background:#808080 url(../assets/img/bg-art2.png); text-align:center;} .gif:hover,.gif:focus,.gif:active{background-image:url(../assets/img/ws-sketchbook.gif);} .box{margin:.35em 0;} .title{display:inline-block; padding:.75em 1.5em; font-size:initial;} @media only screen and (min-width:600px){header{overflow:auto;} .col{float:left; width:50%;} .img{text-align:right; padding-right:1em;} .a-info{text-align:left; margin-top:2em; max-width:20em;}} #roco{box-shadow:0 0 0 .15em #000; background:url(../assets/img/bg-paper.png); padding:10px; margin-top:2em; max-width:1030px; margin:0 auto;} #roco a{display:inline-block; line-height:0; border:10px #efefef solid; box-shadow:0 0 3px 2px #000; box-shadow:0 0 3px 2px rgba(0,0,0,.15); margin:10px;} /*hmm maybe not, sticks out too much #roco a.dark-b{border-color:#101010;}*/ #roco a:hover,#roco a:active,#roco a:focus{opacity:.5;} #roco div{position:relative;} #roco div::after{box-shadow:inset 0 0 12px 3px #000; content:''; display:block; position:absolute; height:100%; left:0; right:0; top:0; opacity:.25;} footer{background:#000; padding:1em; font-family:monospace; color:#bfbfbf;} footer p:last-child{margin-bottom:0;}"
---
<div style="position:absolute; height:1px; width:1px; font-size:0; opacity:0;"><img src="{%include url.html%}/assets/img/{{page.img.url}}.gif" alt=""></div>
<main>
	<header><div class="col img">
		<div class="gif"><a href="{%include url.html%}/a-space"><img src="{%include url.html%}/assets/img/ws-sketchbook.png" alt="A sketchbook. (back to homepage)" title="A sketchbook. (back to homepage)"></a></div>
	</div><div class="col a-info">
		<div class="box title"><h1>{{page.title}}</h1></div>
		<div class="box"><p>Scribbles and scrawlings. Feel free to use for whatever, just link back here~</p></div>
	</div></header>
	<!--
	https://stackoverflow.com/questions/8771178/putting-a-inset-box-shadow-on-an-image-or-image-within-a-div/36534181#36534181
	_128: that exact size, or proportionate & downscaled (128, 256, 384...)
	_64: 128 down to 32, then back--adds a bit of pixelation but shouldn't look censored
	-->
	<section id="roco">{%for art in site.art%}<a href="{%include url.html%}/art/{{art.slug}}" title="{{art.title}}"{%if art.class contains 'dark'%} class="dark-b"{%endif%}><div><img src="{%include url.html%}/assets/img/art/{{art.date|date:"%F"}}_128.png" alt="{{art.title}}"></div></a>{%endfor%}
	</section>
</main>