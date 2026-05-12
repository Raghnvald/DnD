---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skeletal Giant Owl"
---
# [Skeletal Giant Owl](3-Mechanics/CLI/bestiary/undead/skeletal-giant-owl-imr.md)
*Source: Infernal Machine Rebuild p. 33*  

```statblock
"name": "Skeletal Giant Owl (IMR)"
"size": "Large"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "8"
  - !!int "13"
  - !!int "10"
"speed": "5 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 15"
"languages": "Giant Owl, understands Common, Elvish, and Sylvan but can't speak them"
"cr": "1/4"
"traits":
  - "desc": "The owl doesn't provoke opportunity attacks when it flies out of an enemy's\
      \ reach."
    "name": "Flyby"
  - "desc": "The owl has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (2d6 + 1) slashing damage."
    "name": "Talons"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/undead/token/skeletal-giant-owl-imr.webp"
```
^statblock