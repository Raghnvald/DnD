---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Griffin (Type 1)"
---
# [Griffin (Type 1)](3-Mechanics/CLI/bestiary/monstrosity/griffin-type-1-psz.md)
*Source: Plane Shift: Zendikar p. 22*  

Less intelligent and less magical than [felidars](3-Mechanics/CLI/bestiary/celestial/felidar-psz.md), griffins share those great cats' noble nature and alignment with the principles of white mana. Larger griffin species are about the size of horses and can be ridden. Indeed, such griffins are often the only reliable means of reaching certain remote locations, particularly in Akoum. Smaller griffins range from the size of donkeys to large dogs, and are trained to carry messages or supplies without a rider.

Zendikar's griffins are much like D&D's [griffons](3-Mechanics/CLI/bestiary/monstrosity/griffon.md) (aside from the spelling) and [hippogriffs](3-Mechanics/CLI/bestiary/monstrosity/hippogriff.md).

```statblock
"name": "Griffin (Type 1) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "2"
  - !!int "13"
  - !!int "8"
"speed": "30 ft., fly 80 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The griffin has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The griffin makes two attacks: one with its beak and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claws"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/griffin-type-1-psz.webp"
```
^statblock