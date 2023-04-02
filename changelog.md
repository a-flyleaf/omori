---
layout: ws
title: A log of changes.
dark: y
css: "body{background:#000;} #lt-content{padding:0 1em;} #laptop{margin:1em auto; border:.5em #000 solid; box-shadow:0 0 0 .15em #808080; background:url(assets/img/bg-wall-500.png) no-repeat fixed center; background-size:cover;} hr{border:0; height:.1em; background:#fff; margin:0 -1em;} .box{margin:1em;} #bar{background:#bfbfbf; border-top:.1em #efefef solid; font-family:monospace; text-transform:uppercase;} .lt-box{display:inline-block; margin:.25em; padding:.25em .5em; border:.1em #808080 solid;} #bar a{text-decoration:none; font-weight:bold;} #bar a:focus,#bar a:hover,#bar a:active{color:initial; background:#808080; border-color:#404040;} .lt-box:last-child{float:right; cursor:default; border-color:#dfdfdf;}
	header{text-transform:uppercase; padding:.5em 0; letter-spacing:.025em;}
	header a{text-decoration:0; display:inline-block; float:right; margin-top:-1.5em; margin-right:-.75em; padding:0 .35em; border:.1em #fff solid;} header a:hover,header a:focus,header a:active{color:red; border-color:inherit; background:#fff;}
	.box h1,.box h2{font-size:1em;} article{border-bottom:.1em solid; padding:.5em 0;} article:last-of-type{border:0;} .box h2{color:inherit;} p span{display:inline-block;} .done{font-size:.85em; margin-top:-1em;} .box li>ul{margin-bottom:0;}
	@media only screen and (min-width:500px){#laptop{background-image:url(assets/img/bg-wall-1000.png);}}
	@media only screen and (min-width:50em){main{overflow:auto;} article{width:47.5%; float:left; margin-right:2.5%;} @supports (display:flex){main{display:flex; flex-wrap:wrap;} article{margin:0;}  article:nth-child(odd){margin-right:2.5%;} article:nth-child(even){margin-left:2.5%;}}}
	@media only screen and (min-width:75em){article{width:22.5%; min-height:20em;} /*https://stackoverflow.com/questions/4844456/is-it-possible-to-select-the-last-n-items-with-nth-child*/ article:nth-last-child(-n+4){border-bottom:0;} @supports (display:flex){article{min-height:auto; width:23.5%;} article:nth-child(odd){margin-right:0;} article:nth-child(even){margin-left:0;} article{margin-right:1.5% !important;}}
	@media only screen and (min-width:1000px){#laptop{background-image:url(assets/img/bg-wall-2000.png); max-width:1500px;}"

log:
  - dt: 2023-02-20
    line: Made this site.
    done: |-
      - art: gifs for the homepage
      - code: core layouts/site setup
      - full page: [splash (index.html)](index.html)
      - words: main content (full about & links, notes for other pages)
      - full page: [Black Space reference table](black-space)
  - dt: 2023-02-21
    line: Continued working on site.
    done: |-
      - full page: [nothing here (404.html)](nothing)
      - art/code: back button
      - code: text layout
        - finished pages: [About](about) & [Links](links)
      - full page: Changelog (you are here)
  - dt: 2023-02-22
    line: Added… <a href="help">whatever this is</a>.
  - dt: 2023-02-24
    line: Continued working on site.
    done: |-
      - code: art layouts
      - full page: [art index](art)
  - dt: 2023-02-25
    line: <a href="art/friend-fight">Drew a thing</a>.
  - dt: 2023-02-27
    line: Continued working on site.
    done: |-
      - code: finished art layouts
      - words: art pages up to present
        - full page: [art: <span class="omo">Omori alter</span>](art/omori-alter)
  - dt: 2023-02-28
    line: Cleaned up site for launch.
    done: |-
      - full page: [the actual index](a-space)
      - art: <a href="art/roundup-2023-02">Februrary roundup</a>
  - dt: 2023-03-01
    line: <a href="art/mar1">Drew a thing</a>.
  - dt: 2023-03-02
    line: Did some stuff.
    done: |-
      - misc: assorted minor fixes
      - misc: image folder shuffling
      - new page: [Heardle](heardle)
      - words: meta <a href="meta">index</a>, <a href="meta/intropost">intropost</a>, <a href="meta/playground">playground</a>, <a href="meta/not-playground">not-playground</a>
  - dt: 2023-03-03
    line: Revised yesterday’s meta.
    done: |-
      - words: essentially rewrote the "<a href="meta/not-playground">not-playground</a>" post from the ground up
  - dt: 2023-03-04
    line: Fixed things, added things.
    done: |-
      - words: <a href="meta/intermission">meta intermission</a>
  - dt: 2023-03-05
    line: Wrote more meta (incomplete).
  - dt: 2023-03-07
    line: <a href="art/smad">Drew a thing</a>.
  - dt: 2023-03-16
    line: Fixed assorted things.
  - dt: 2023-03-30
    line: <a href="hrvatski" lang="hr"><i>Jezik je pojam!</i></a>
  - dt: 2023-04-01
    line: <a href="art/roundup-2023-03">March art roundup</a> is a thing.
---
<div id="lt-content"><div id="laptop">
	<div class="box">
		<header><h1>Changelog</h1><a href="a-space">✕</a></header>
		<hr>
		<main>{%for log in page.log%}<article><h2>{{log.dt}}</h2><p><span>Today I thought about <span class="omo">Omori</span>.</span> <span>{{log.line}}</span></p>{%if log.done%}<div class="done">{{log.done|markdownify}}</div>{%endif%}</article>{%endfor%}</main>
	</div><div id="bar">
		<a href="https://unsplash.com/photos/4Zaq5xY5M_c" class="lt-box">BG credit</a>
		<div class="lt-box">2023</div>
</div><!--/#bar--></div></div>