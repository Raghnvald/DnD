---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Big Water Slurpent"
---
# [Big Water Slurpent](3-Mechanics/CLI/bestiary/npc/big-water-slurpent-awm.md)
*Source: Adventure with Muk p. 29*  

The Big Water Slurpent is a magical creature that has lived within the Big Water for centuries. It was created by a wizard to guard the tower that has long since sunk into the Big Water. Many goblins have seen the slurpent and have run away. Many goblins believe that it likes to eat goblins.

The Big Water Slurpent is dangerous if goblins go snooping around the Big Water. But there are ways to get around it if you do one of the following:

- Sing it a song (gotta really sing your goblin heart out!)  
- Feed it some tasty goblin pie (it better be a good one!)  
- Hold up a mirror and show it its reflection (it is a lonely slurpent)  

```statblock
"name": "Big Water Slurpent (AWM)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "58"
"modifier": !!int "3"
"stats":
  - !!int "17"
  - !!int "16"
  - !!int "13"
  - !!int "11"
  - !!int "10"
  - !!int "10"
"speed": "0 ft., swim 60 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The big water slurpent is invisible while fully immersed in water."
    "name": "Invisible in Water"
  - "desc": "The big water slurpent dies if it leaves the water to which it is bound\
      \ or if that water is destroyed."
    "name": "Water Bound"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, one target. *Hit:* 13 (3d6+3) bludgeoning\
      \ damage. If the target is Medium or smaller, it is grappled (escape DC 13)\
      \ and pulled 5 feet toward the big water slurpent. Until this grapple ends,\
      \ the target is restrained, the big water slurpent tries to drown it, and the\
      \ big water slurpent can't constrict another target."
    "name": "Constrict"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/npc/token/big-water-slurpent-awm.webp"
```
^statblock