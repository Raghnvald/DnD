---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Virvos Magen"
---
# [Virvos Magen](3-Mechanics/CLI/bestiary/construct/virvos-magen-nf.md)
*Source: Netheril's Fall*  

Virvos magen are frequently employed at opulent events, where they use their magic to create enchanting atmospheres or entertain crowds with pleasing illusions.

```statblock
"name": "Virvos Magen (NF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "21"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "16"
"speed": "30 ft., fly 20 ft. (hover)"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 16"
"languages": "understands Common plus two other languages but can't speak"
"cr": "6"
"traits":
  - "desc": "If the magen dies, it disintegrates into dust, leaving behind anything\
      \ it was wearing or carrying."
    "name": "Disintegration"
  - "desc": "The magen has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The magen makes two Psychic Blast attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 60 ft. *Hit:*\
      \ 21 (6d6) Psychic damage."
    "name": "Psychic Blast"
  - "desc": "The magen casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 14):\n\n**At\
      \ will:** Dancing Lights, Minor Illusion\n\n**1/day each:** Hypnotic Pattern,\
      \ Major Image"
    "name": "Spellcasting"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/construct/token/virvos-magen-nf.webp"
```
^statblock

## Environment

any