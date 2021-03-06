---
number: 15
title: Snek Konnekt
short_desc: A simple puzzle game, from Flutter to HTML5
iframe_width: 550
iframe_height: 570
iframe_source: https://itch.io/embed-upload/1865249?color=0484d1
---

<iframe style="font-size: larger; width: {{ page.iframe_width }}px; height: {{ page.iframe_height }}px;" 
        width="{{ page.iframe_width }}" height="{{ page.iframe_height }}"
        frameborder="0"
        src="{{ page.iframe_source }}">
</iframe>

## Snek Konnekt was my first game using *Flutter*
I wrote it in the *Dart* language around late 2019.  
As the description suggests, this was an attempt at doing **something** that year, no matter how small.  
The game itself is not very complicated, but I made it a technical challenge for myself. The entire game is rendered using 2D elements, with transforms applied to look like 3D faces. If memory serves, it wasn't perfect, hence the rotation being allowed only on one axis.  

Originally I envisioned something much more, advanced, with more levels, some powerups, verticality (snek could ride on itself from lower levels). At some point my patience with the project reached its limit, and I luckily decided to just finish up and publish it instead of dropping the project.  

It is possible that this game is the point where I first came up with the idea of "partially solved" games. If you pause for a second you will notice that half of the levels (1, 2, 5) cannot be failed. You can push any button and you **will** eventually win. There are also many situations where your choice is an illusory one. You can select a spot, but unless you select the one that leads you to an intersection, you are just delaying the inevitable. I'd like to revisit this project one day, from the perspective of better communicating those false choices to the player.
