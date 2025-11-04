---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/cr/1-8
  - Monster/environment/forest
  - Monster/environment/swamp
  - Monster/environment/underdark
  - Monster/environment/urban
  - Monster/Größe/Klein
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Rat (Diseased)
---
# [Giant Rat (Diseased)](3-Mechanics\CLI\bestiary\beast/giant-rat-diseased.md)
*Source: Monster Manual p. 327. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Giant Rat (Diseased)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "11"
  - !!int "2"
  - !!int "10"
  - !!int "4"
"speed": "30 ft."
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "The rat has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The rat has advantage on an attack roll against a creature if at least\
      \ one of the rat's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
      \ 10 Constitution saving throw or contract a disease. Until the disease is cured,\
      \ the target can't regain hit points except by magical means, and the target's\
      \ hit point maximum decreases by 3 (1d6) every 24 hours. If the target's hit\
      \ point maximum drops to 0 as a result of this disease, the target dies."
    "name": "Bite"
"source":
  - "MM"
```
^statblock

## Environment

underdark, forest, swamp, urban