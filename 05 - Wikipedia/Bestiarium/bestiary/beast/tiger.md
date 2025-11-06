---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/1
  - Monster/Habitat/Wald
  - Monster/Habitat/Grasland
  - Monster/Größe/Groß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Tiger
---
# [Tiger](3-Mechanics\CLI\bestiary\beast/tiger.md)
*Source: Monster Manual p. 339. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Tiger"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "14"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The tiger has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "If the tiger moves at least 20 feet straight toward a creature and then\
      \ hits it with a claw attack on the same turn, that target must succeed on a\
      \ DC 13 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is [prone](/3-Mechanics/CLI/conditions.md#Prone), the tiger\
      \ can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage."
    "name": "Claw"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/beast/token/tiger.webp"
```
^statblock

## Environment

grassland, forest