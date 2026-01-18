---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/5
  - Monster/Größe/Groß
  - Monster/Typ/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Rime Hulk
---
# [Rime Hulk](3-Mechanics\CLI\bestiary\elemental/rime-hulk-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 162*  

Rime hulks are a withered branch of the frost giant family tree, descended from ancient giants who withdrew from the world and succumbed to their elemental nature. Most rime hulks dwell in the Frostfell, the "plane of ice" that forms the border between the Elemental Planes of Air and Water. Others lurk in isolated rifts in enormous polar glaciers.

Smaller and weaker than their ancestors, rime hulks are roughly formed masses of frost and ice. Their vaguely giant-shaped physical forms are unstable, constantly breaking apart and reforming as clouds of frost billow off them. As a rime hulk moves, it leaves a trail of ice that can freeze enemies in place. When it dies, a rime hulk explodes in a burst of frost.

> [!quote] A quote from Bigby  
> 
> In all seriousness, though, it's best not to get caught up in what these hulks were or might have become had things gone differently for them. They're dangerous, and most of them do not wish you well. Act accordingly.


```statblock
"name": "Rime Hulk (BGG)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d10 + 36"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "8"
  - !!int "9"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 9"
"languages": "Aquan, Giant"
"cr": "5"
"traits":
  - "desc": "When the rime hulk dies, it explodes in a 10-foot-radius sphere of frigid\
      \ air and frost centered on itself. Each creature in that area must succeed\
      \ on a DC 15 Constitution saving throw or take 10 (3d6) cold damage."
    "name": "Death Burst"
"actions":
  - "desc": "The rime hulk makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (1d10 + 4) bludgeoning damage plus 9 (2d8) cold damage."
    "name": "Slam"
  - "desc": "The rime hulk moves up to its speed without provoking opportunity attacks\
      \ and can move through the space of any Medium or smaller creature. Each time\
      \ the rime hulk enters another creature's space for the first time during this\
      \ move, that creature must make a DC 15 Constitution saving throw. On a failed\
      \ save, the creature takes 22 (4d10) cold damage, and its speed is reduced by\
      \ 10 feet until the start of the rime hulk's next turn. On a successful save,\
      \ the creature takes half as much damage only."
    "name": "Trail of Frost (Recharge 5-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/rime-hulk-bgg.webp"
```
^statblock