---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Guardian Wolf
linter-yaml-title-alias: Guardian Wolf
tags:
  - Monster/Größe/Riesig
  - Monster/HG/4
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Guardian Wolf
---
# [Guardian Wolf](3-Mechanics\CLI\bestiary\monstrosity/guardian-wolf-egw.md)
*Source: Explorer's Guide to Wildemount p. 272*  

```statblock
"name": "Guardian Wolf (EGW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "66"
"hit_dice": "7d12 + 21"
"modifier": !!int "2"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "16"
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "60 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 15"
"languages": "Common, Elvish"
"cr": "4"
"traits":
  - "desc": "The wolf has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
  - "desc": "The wolf has advantage on attack rolls against a creature if at least\
      \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The wolf makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (1d10 + 6) piercing damage. If the target is a creature, it must succeed on\
      \ a DC 16 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 15\
      \ (2d8 + 6) piercing damage."
    "name": "Claws"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/guardian-wolf-egw.webp"
```
^statblock