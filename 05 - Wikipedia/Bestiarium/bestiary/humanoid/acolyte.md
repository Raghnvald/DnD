---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/1-4
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Acolyte
---
# [Acolyte](3-Mechanics\CLI\bestiary\humanoid/acolyte.md)
*Source: Monster Manual p. 342. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Acolytes are junior members of a clergy, usually answerable to a priest. They perform a variety of functions in a temple and are granted minor spellcasting power by their deities.

```statblock
"name": "Acolyte"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
  - "desc": "The acolyte is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). The acolyte has following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](/3-Mechanics/CLI/spells/light.md),\
      \ [sacred flame](/3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (3 slots):** [bless](/3-Mechanics/CLI/spells/bless.md), [cure\
      \ wounds](/3-Mechanics/CLI/spells/cure-wounds.md), [sanctuary](/3-Mechanics/CLI/spells/sanctuary.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/acolyte.webp"
```
^statblock

## Environment

urban