---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/cr/2
  - Monster/environment/urban
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Priest
---
# [Priest](3-Mechanics\CLI\bestiary\humanoid/priest.md)
*Source: Monster Manual p. 348. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Priests bring the teachings of their gods to the common folk. They are the spiritual leaders of temples and shrines and often hold positions of influence in their communities. Evil priests might work openly under a tyrant, or they might be the leaders of religious sects hidden in the shadows of good society, overseeing depraved rites. A priest typically has one or more acolytes to help with religious ceremonies and other sacred duties.

```statblock
"name": "Priest"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+3"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "2"
"traits":
  - "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 13, +5 to hit with spell attacks). The priest has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](/3-Mechanics/CLI/spells/light.md),\
      \ [sacred flame](/3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [cure wounds](/3-Mechanics/CLI/spells/cure-wounds.md),\
      \ [guiding bolt](/3-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](/3-Mechanics/CLI/spells/sanctuary.md)\n\
      \n**2nd level (3 slots):** [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration.md),\
      \ [spiritual weapon](/3-Mechanics/CLI/spells/spiritual-weapon.md)\n\n**3rd level\
      \ (2 slots):** [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [spirit\
      \ guardians](/3-Mechanics/CLI/spells/spirit-guardians.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the priest can expend a spell slot to cause its melee\
      \ weapon attacks to magically deal an extra 10 (3d6) radiant damage to a target\
      \ on a hit. This benefit lasts until the end of the turn. If the priest expends\
      \ a spell slot of 2nd level or higher, the extra damage increases by 1d6 for\
      \ each level above 1st."
    "name": "Divine Eminence"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6)\
      \ bludgeoning damage."
    "name": "Mace"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/priest.webp"
```
^statblock

## Environment

urban