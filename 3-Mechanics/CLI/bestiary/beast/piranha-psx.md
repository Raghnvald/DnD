---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Piranha"
---
# [Piranha](3-Mechanics/CLI/bestiary/beast/piranha-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

The waters of the Great River and all its tributaries are home to fish that serve as one of the most important food sources for other animals in the forest. These include large predatory fish, as well as churning swarms of small biting fish such as piranhas.

```statblock
"name": "Piranha (PSX)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "3"
"stats":
  - !!int "2"
  - !!int "16"
  - !!int "9"
  - !!int "1"
  - !!int "7"
  - !!int "2"
"speed": "swim 40 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The piranha has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The piranha can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 1\
      \ piercing damage."
    "name": "Bite"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/piranha-psx.webp"
```
^statblock