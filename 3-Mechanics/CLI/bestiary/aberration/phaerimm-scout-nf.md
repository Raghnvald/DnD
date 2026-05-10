---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phaerimm Scout"
---
# [Phaerimm Scout](3-Mechanics/CLI/bestiary/aberration/phaerimm-scout-nf.md)
*Source: Netheril's Fall*  

Phaerimm scouts typically operate alone and in the shadows, gathering information for upcoming phaerimm operations.

```statblock
"name": "Phaerimm Scout (NF)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "15"
  - !!int "16"
  - !!int "16"
"speed": "10 ft., fly 40 ft."
"saves":
  - "intelligence": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 60 ft., passive\
  \ Perception 15"
"languages": "telepathy 120 ft. understands Common and Deep Speech but can't speak"
"cr": "2"
"traits":
  - "desc": "The phaerimm has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The phaerimm makes two attacks, using Stinger or Mindwarp Ray in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Piercing\
      \ damage plus 9 (2d8) Poison damage."
    "name": "Stinger"
  - "desc": "*Ranged Attack Roll:* +5, range 120 ft. *Hit:* 6 (1d6 + 3) Psychic\
      \ damage, and the target has the Charmed condition until the start of the phaerimm's\
      \ next turn."
    "name": "Mindwarp Ray"
  - "desc": "The phaerimm casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** Detect Magic, Detect Thoughts, Mage Hand\n\n**1/day:** Clairvoyance"
    "name": "Spellcasting"
"reactions":
  - "desc": "Trigger: The phaerimm is hit by an attack roll. _Response:_ The phaerimm\
      \ halves the damage (round down) it takes from that attack."
    "name": "Uncanny Dodge"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/aberration/token/phaerimm-scout-nf.webp"
```
^statblock

## Environment

underdark, urban