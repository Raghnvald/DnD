---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Druid
---
# [Druid](3-Mechanics\CLI\bestiary\humanoid/druid.md)
*Source: Monster Manual p. 346, Explorer's Guide to Wildemount. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Druids dwell in forests and other secluded wilderness locations, where they protect the natural world from monsters and the encroachment of civilization. Some are tribal shamans who heal the sick, pray to animal spirits, and provide spiritual guidance.

```statblock
"name": "Druid"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "16 with barkskin"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Medicine"
    "desc": "+4"
  - "name": "Nature"
    "desc": "+3"
  - "name": "Perception"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": "Druidic plus any two languages"
"cr": "2"
"traits":
  - "desc": "The druid is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** druidcraft, produce flame, shillelagh\n\
      \n**1st level (4 slots):** entangle, longstrider, speak with animals, thunderwave\n\
      \n**2nd level (3 slots):** animal messenger, barkskin"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit (+4 to hit with shillelagh), reach 5\
      \ ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning damage\
      \ if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh."
    "name": "Quarterstaff"
"source":
  - "MM"
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/druid.webp"
```
^statblock

## Environment

coastal, mountain, grassland, hill, arctic, forest, swamp, underdark, desert