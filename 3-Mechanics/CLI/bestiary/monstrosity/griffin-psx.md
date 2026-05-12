---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Griffin"
---
# [Griffin](3-Mechanics/CLI/bestiary/monstrosity/griffin-psx.md)
*Source: Plane Shift: Ixalan p. 39*  

Colorful griffins combine the heads and plumage of jungle parrots with the sleek bodies of jaguars. They are intelligent and noble, and they share the River Heralds' desire to ensure that the power of the Immortal Sun is never again unleashed on the world.

```statblock
"name": "Griffin (PSX)"
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
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/griffin-psx.webp"
```
^statblock