---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hill Giant, Blorbo"
---
# [Hill Giant, Blorbo](3-Mechanics/CLI/bestiary/npc/hill-giant-blorbo-awm.md)
*Source: Adventure with Muk p. 34*  

The hill giant, Blorbo, is an ill-tempered brute who has a taste for goblin flesh. Goblins tell their children horror stories of Blorbo around the campfire at night to keep them from wandering too far into the Dankwood.

Blorbo is not aware that there is a shiny stone and a lost dwarven king deep within his cave but he's not interested in those things. He wants to eat stuff.

Blorbo is too powerful to defeat in combat but he can be tricked with food. Poison from a pooka toad on a well-aimed arrow might do the trick, but you better be a good shot!

```statblock
"name": "Hill Giant, Blorbo (AWM)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "105"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "19"
  - !!int "5"
  - !!int "9"
  - !!int "6"
"speed": "40 ft."
"gear":
  - "greatclub"
"senses": "passive Perception 0"
"languages": ""
"cr": "4"
"actions":
  - "desc": "The giant makes two greatclub attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, one target. *Hit:* 18 (3d8 + 5)\
      \ bludgeoning damage."
    "name": "Greatclub"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, one target. *Hit:* 21 (3d10 + 5)\
      \ bludgeoning damage."
    "name": "Rock"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/npc/token/hill-giant-blorbo-awm.webp"
```
^statblock