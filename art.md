---
layout: ws-text
title: Artwork.
img:
  url: ws-sketchbook
  alt: A sketchbook. (back to homepage)
  link: a-space
css: ".gif:hover,.gif:focus,.gif:active{background-image:url(../assets/img/ws-sketchbook.gif);}"
---
<!--ditch the text layout entirely, make it look like a wall? specifically Rococo's, or at least use a paper texture... apply that to the art page too (maybe move the .box to the base css?)-->
Scribbles and scrawlings. Feel free to use for whatever, just link back here somehow~

<section id="roco">{%for art in site.art%}<a href="{%include url.html%}/art/{{art.slug}}"><img src="{%include url.html%}/assets/img/art/{{art.date|date:"%F"}}_128.png" alt="{{art.title}}"></a>{%endfor%}</section>

<!--128x128 thumbnails--that exact size, or proportionate & downscaled (128, 256, 384...)

# "Name" - [date]
## image description (visible but small; long transcriptions (e.g. roundup scrawling) in details)
## ARTIST COMMENTARY
[blablabla]
(we're just straight-up not gonna bother with dA links this time. maybe?? idk dA sucks, but it wouldn't /hurt/ to have it in the code just for ref)
-->