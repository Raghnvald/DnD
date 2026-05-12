---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skeletal Polar Bear"
---
# [Skeletal Polar Bear](3-Mechanics/CLI/bestiary/undead/skeletal-polar-bear-imr.md)
*Source: Infernal Machine Rebuild p. 34*  

```statblock
"name": "Skeletal Polar Bear (IMR)"
"size": "Large"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "2"
  - !!int "13"
  - !!int "7"
"speed": "40 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The bear has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
"actions":
  - "desc": "The bear makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d8 + 5) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage."
    "name": "Claws"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/undead/token/skeletal-polar-bear-imr.webp"
```
^statblock