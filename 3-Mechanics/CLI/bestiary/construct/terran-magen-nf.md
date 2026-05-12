---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Terran Magen"
---
# [Terran Magen](3-Mechanics/CLI/bestiary/construct/terran-magen-nf.md)
*Source: Netheril's Fall*  

Terran magen are equipped with magic to help them perform laborious physical tasks. These magen commonly perform household handiwork and build infrastructure.

```statblock
"name": "Terran Magen (NF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "21"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "18"
  - !!int "10"
"speed": "30 ft., fly 20 ft. (hover)"
"saves":
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "poison, thunder"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "understands Common plus two other languages but can't speak"
"cr": "8"
"traits":
  - "desc": "If the magen dies, it disintegrates into dust, leaving behind anything\
      \ it was wearing or carrying."
    "name": "Disintegration"
  - "desc": "The magen has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The magen makes two attacks, using Hammer Fist or Thunderous Boom in\
      \ any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 16 (3d8 + 3) Bludgeoning\
      \ damage plus 13 (3d8) Force damage."
    "name": "Hammer Fist"
  - "desc": "*Ranged Attack Roll:* +7, range 60 ft. *Hit:* 28 (8d6) Thunder damage."
    "name": "Thunderous Boom"
  - "desc": "The magen casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\n**At will:**\
      \ Mage Hand, Mending, Prestidigitation\n\n**1/day each:** Disintegrate, Move\
      \ Earth, Stone Shape"
    "name": "Spellcasting"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/construct/token/terran-magen-nf.webp"
```
^statblock

## Environment

any