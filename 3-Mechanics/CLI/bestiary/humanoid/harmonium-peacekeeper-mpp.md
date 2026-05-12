---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Harmonium Peacekeeper"
---
# [Harmonium Peacekeeper](3-Mechanics/CLI/bestiary/humanoid/harmonium-peacekeeper-mpp.md)
*Source: Morte's Planar Parade p. 59*  

Peacekeepers wear distinctive red plate armor and wield planar mancatchers, polearms whose metal pincers prevent criminals clamped in their grasp from teleporting away, making them excellent at catching wrongdoers in Sigil.

```statblock
"name": "Harmonium Peacekeeper (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": "Common plus one more language"
"cr": "3"
"traits":
  - "desc": "The peacekeeper has advantage on an attack roll against a creature if\
      \ at least one of the peacekeeper's allies is within 5 feet of the creature\
      \ and the ally doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:*\
      \ 8 (1d10 + 3) piercing damage plus 4 (1d8) lightning damage. If the target\
      \ is a Large or smaller creature, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 13). Until the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition and can't teleport, the peacekeeper can't make Electrified Mancatcher\
      \ attacks, and the target takes 8 (1d10 + 3) lightning damage at the start\
      \ of each of its turns."
    "name": "Electrified Mancatcher"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/harmonium-peacekeeper-mpp.webp"
```
^statblock