---
layout: ws-text
title: OMORI Heardle
permalink: heardle
css: "main img{float:left; max-width:50%; margin-right:1em;} main{overflow:auto;} header.box{padding:.5em 1em;} ul a{font-weight:bold; display:inline-block;} main li{margin:.5em 0;} li span{display:inline-block;}"

heardle:
  - date: 2023-03-16
    num: 148
    rec: 🔉🟥🟩⬜️⬜️⬜️⬜️
    ost: "White Space [v2]"
    bc: white-space-3
    note: "is it possible to discern the piano versions within a second, I wonder?"
  - date: 2023-03-15
    num: 147
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: See You Tomorrow
    bc: see-you-tomorrow
    note: ";_;"
  - date: 2023-03-14
    num: 146
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Recycling Really Is A Concept
    bc: recycling-really-is-a-concept
  - date: 2023-03-13
    num: 145
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Good Morning
    bc: good-morning
    note: "had to look up the title but ayyy"
  - date: 2023-03-10
    num: 142
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Playing Forever
    bc: playing-forever
  - date: 2023-03-09
    num: 141
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Those Who Forget
    bc: those-who-forget
    note: "<em>literally</em> the most area battle theme ever"
  - date: 2023-03-08
    num: 140
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Waiting For...
    bc: waiting-for
  - date: 2023-03-07
    num: 139
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Underwater Prom Queens
    bc: underwater-prom-queens
  - date: 2023-03-06
    num: 138
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Friendsssssss.
    bc: friendsssssss
    note: "hate this one a lot &lt;/3"
  - date: 2023-03-05
    num: 137
    rec: 🔊🟩⬜️⬜️⬜️⬜️⬜️
    ost: Treehouse - Here We Are, Together Again
    bc: treehouse-here-we-are-together-again
    note: "<em>ayyyy</em> I had this stuck in my head/on repeat recently!"
  - date: 2023-03-04
    num: 136
    rec: 🔈⬛️⬛️⬛️🟩⬜️⬜️
    ost: Bad Morning
    bc: bad-morning
    note: Ohh gdi, recognized it <em>immediately</em> because it reminds me of <i>deltarune</i>. No clue when it played, though; third section rang more of a bell but still not specific enough. Took <em>ages</em> to find it in the OST after that >:V
  - date: 2023-03-03
    num: 135
    rec: 🔉⬛️⬛️🟩⬜️⬜️⬜️
    ost: A Red Shape
    bc: a-red-shape
    note: Well, that was tricky! Nothing from the first second, nothing <em>recognizable</em> from the second, and at the third try I just speedran everything short from the OST. (Along the way, discovered that cursed Something battle theme is indeed on the OST (wiki fails again there); it's <a href="https://omori.bandcamp.com/track/fade">#066 Fade</a>.)
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

Heardle is a fun little thing, and [the <span class="omo">Omori</span> version](https://omori-heardle-2-5.glitch.me/) is good for showing off just how familiar you are with the OST. It was also clogging my notes so \*dumps it unceremoniously here\*

{%assign notes = page.heardle | reversed%}
<ul>{%for note in notes%}<li><span>{{note.date|date:"%b.%d"}}</span> #{{note.num}} <span>{{note.rec}}</span>: <span><a href="https://omori.bandcamp.com/track/{%if note.bc%}{{note.bc}}{%else%}{{note.ost|downcase}}{%endif%}">{{note.ost}}</a></span>{%if note.note%} ({{note.note}}){%endif%}</li>{%endfor%}</ul>