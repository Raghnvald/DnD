---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Griffin (Type 2)"
---
# [Griffin (Type 2)](3-Mechanics/CLI/bestiary/monstrosity/griffin-type-2-psz.md)
*Source: Plane Shift: Zendikar p. 22*  

Less intelligent and less magical than [felidars](3-Mechanics/CLI/bestiary/celestial/felidar-psz.md), griffins share those great cats' noble nature and alignment with the principles of white mana. Larger griffin species are about the size of horses and can be ridden. Indeed, such griffins are often the only reliable means of reaching certain remote locations, particularly in Akoum. Smaller griffins range from the size of donkeys to large dogs, and are trained to carry messages or supplies without a rider.

Zendikar's griffins are much like D&D's [griffons](3-Mechanics/CLI/bestiary/monstrosity/griffon.md) (aside from the spelling) and [hippogriffs](3-Mechanics/CLI/bestiary/monstrosity/hippogriff.md).

```statblock
"name": "Griffin (Type 2) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "13"
  - !!int "2"
  - !!int "12"
  - !!int "8"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The griffin has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The griffin makes two attacks: one with its beak and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d10 + 3) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Claws"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/griffin-type-2-psz.webp"
```
^statblock