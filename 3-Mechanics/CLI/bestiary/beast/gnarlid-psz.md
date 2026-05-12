---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gnarlid"
---
# [Gnarlid](3-Mechanics/CLI/bestiary/beast/gnarlid-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

Gnarlids are about the size of a large dog and resemble a cross between a bear and a wolverine. They have horns with distinctive shapes that vary by species, and some varieties have similar spikes elsewhere on their bodies. They have an innate ability to grow larger by drawing on green mana in the environment, nearly doubling in size as well as ferocity. In this enlarged state, a gnarlid can be represented with the [brown bear](3-Mechanics/CLI/bestiary/beast/brown-bear.md) statistics in the Monster Manual. If some magic reduces its size, cut both its hit point maximum and its attack damage in half.

```statblock
"name": "Gnarlid (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "34"
"hit_dice": "4d10 + 12"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "16"
  - !!int "2"
  - !!int "13"
  - !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The gnarlid has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
"actions":
  - "desc": "The gnarlid makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claws"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/gnarlid-psz.webp"
```
^statblock