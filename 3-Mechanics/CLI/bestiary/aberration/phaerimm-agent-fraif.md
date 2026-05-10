---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phaerimm Agent"
---
# [Phaerimm Agent](3-Mechanics/CLI/bestiary/aberration/phaerimm-agent-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 269*  

Phaerimm agents travel the surface world, seeking out powerful magic to rule others.

## Phaerimm

*Alien, Magic-Obsessed Manipulators*

Phaerimm are malevolent alien beings that seek to dominate other sentient species. A phaerimm's conical body ripples through the air, trailing behind a large, flat mouth ringed by four delicate arms. A phaerimm's body tapers to a venomous stinger they prefer to use only when magical means fail them.

Ancient phaerimm devastated the once-powerful empire of Netheril. The phaerimm were imprisoned beneath the great desert of Anauroch, where they plot a return to their former dominion. Roll or choose a result from the Phaerimm Plots table as inspiration for what a phaerimm agent might be doing when encountered.

```statblock
"name": "Phaerimm Agent (FRAiF)"
"size": "Large"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "123"
"hit_dice": "19d10 + 19"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "16"
  - !!int "18"
"speed": "10 ft., fly 40 ft. (hover)"
"saves":
  - "constitution": !!int "4"
  - "intelligence": !!int "6"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
"condition_immunities": "charmed"
"senses": "Truesight 120 ft., passive Perception 16"
"languages": "telepathy 120 ft. understands Common and Deep Speech but can't speak"
"cr": "8"
"traits":
  - "desc": "The phaerimm has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The phaerimm makes three attacks, using Dread Stinger or Mindwarp Ray\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing\
      \ damage plus 13 (2d12) Poison damage."
    "name": "Dread Stinger"
  - "desc": "*Ranged Attack Roll:* +7, range 120 ft. *Hit:* 13 (2d8 + 4) Psychic\
      \ damage, and the target has the Charmed condition until the start of the phaerimm's\
      \ next turn."
    "name": "Mindwarp Ray"
  - "desc": "The phaerimm casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** Detect Magic, Detect Thoughts, Mage Hand\n\n**1/day each:** Clairvoyance,\
      \ Major Image, Synaptic Static"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The phaerimm teleports up to 30 feet to an unoccupied space it can see."
    "name": "Teleport"
"reactions":
  - "desc": "The phaerimm casts Counterspell or Shield in response to the spell's\
      \ trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic (3/Day)"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/aberration/token/phaerimm-agent-fraif.webp"
```
^statblock

## Environment

underdark, urban