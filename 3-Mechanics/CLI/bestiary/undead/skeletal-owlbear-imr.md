---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skeletal Owlbear"
---
# [Skeletal Owlbear](3-Mechanics/CLI/bestiary/undead/skeletal-owlbear-imr.md)
*Source: Infernal Machine Rebuild p. 36*  

```statblock
"name": "Skeletal Owlbear (IMR)"
"size": "Large"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "17"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The owlbear has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight or smell."
    "name": "Keen Sight and Smell"
"actions":
  - "desc": "The owlbear makes two attacks: one with its beak and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (1d10 + 5) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) slashing damage."
    "name": "Claws"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/undead/token/skeletal-owlbear-imr.webp"
```
^statblock