---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phaerimm Hatchling"
---
# [Phaerimm Hatchling](3-Mechanics/CLI/bestiary/aberration/phaerimm-hatchling-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 268*  

Phaerimm zealously guard their rare hatchlings not out of parental devotion, but to ensure their kind's growing strength.

## Phaerimm

*Alien, Magic-Obsessed Manipulators*

Phaerimm are malevolent alien beings that seek to dominate other sentient species. A phaerimm's conical body ripples through the air, trailing behind a large, flat mouth ringed by four delicate arms. A phaerimm's body tapers to a venomous stinger they prefer to use only when magical means fail them.

Ancient phaerimm devastated the once-powerful empire of Netheril. The phaerimm were imprisoned beneath the great desert of Anauroch, where they plot a return to their former dominion. Roll or choose a result from the Phaerimm Plots table as inspiration for what a phaerimm agent might be doing when encountered.

```statblock
"name": "Phaerimm Hatchling (FRAiF)"
"size": "Small"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "12"
  - !!int "14"
  - !!int "16"
  - !!int "14"
"speed": "10 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
"condition_immunities": "charmed"
"senses": "Truesight 60 ft., passive Perception 15"
"languages": "telepathy 30 ft. understands Common and Deep Speech but can't speak"
"cr": "1/4"
"traits":
  - "desc": "The phaerimm has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The phaerimm makes two Stinger attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Piercing\
      \ damage."
    "name": "Stinger"
  - "desc": "The phaerimm casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 12):\n\n**At\
      \ will:** Detect Thoughts, Mage Hand"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/aberration/token/phaerimm-hatchling-fraif.webp"
```
^statblock

## Environment

underdark, urban