---
layout: ws-text
title: OMORI Heardle
permalink: heardle
css: "main img{float:left; max-width:50%; margin-right:1em;} main{overflow:auto;} header.box{padding:.5em 1em;} ul a{font-weight:bold; display:inline-block;} main li{margin:.5em 0;} li span{display:inline-block;}"

heardle:
  - date: 2023-03-02
    num: 134
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: A Place By A Lake
    bc: a-place-by-a-lake-2
    note: needed to look up the name but the ocean was a dead giveaway
  - date: 2023-02-28
    num: 132
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Three Bar Logos
    bc: three-bar-logos
    note: <em>easy</em>
  - date: 2023-02-27
    num: 131
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Valour Against All Odds
    bc: valour-against-all-odds
  - date: 2023-02-25
    num: 129
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Help Me
    bc: help-me
  - date: 2023-02-24
    num: 128
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Orchard
    note: immediately recognized it from Black Space but took a sec to remember the name
  - date: 2023-02-23
    num: 127
    rec: 🔉🟥🟥🟩⬜️⬜️⬜️⬜
    ost: Bookcase
  - date: 2023-02-22
    num: 126
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Acrophobia
---
<img src="{%include url.html%}/assets/img/misc/herothonk.png" alt="Hero thinks about some tunes." title="Hero thinks about some tunes."/>

Heardle is a fun little thing, and [the <span class="omo">Omori</span> version](https://omori-heardle-2-5.glitch.me/) is good for showing off just how familiar you are with the OST. It was also clogging my notes so /dumps it unceremoniously here

{%assign notes = page.heardle | reverse%}
<ul>{%for note in notes%}<li><span>{{note.date|date:"%b.%d"}}</span> #{{note.num}} <span>{{note.rec}}</span>: <span><a href="https://omori.bandcamp.com/track/{%if note.bc%}{{note.bc}}{%else%}{{note.ost|downcase}}{%endif%}">{{note.ost}}</a></span>{%if note.note%} ({{note.note}}){%endif%}</li>{%endfor%}</ul>