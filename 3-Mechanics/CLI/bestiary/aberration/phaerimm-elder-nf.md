---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phaerimm Elder"
---
# [Phaerimm Elder](3-Mechanics/CLI/bestiary/aberration/phaerimm-elder-nf.md)
*Source: Netheril's Fall*  

Phaerimm elders are generals of phaerimm forces, directing covert and direct operations to help their kind subjugate all who stand in their way. Their ability to siphon magic from magic items makes them incredibly dangerous foes.

```statblock
"name": "Phaerimm Elder (NF)"
"size": "Huge"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "218"
"hit_dice": "23d12 + 69"
"modifier": !!int "8"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "17"
  - !!int "17"
  - !!int "16"
  - !!int "18"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "8"
  - "wisdom": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "mind lash"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 18"
"languages": "telepathy 120 ft. understands Common and Deep Speech but can't speak"
"cr": "14"
"traits":
  - "desc": "The phaerimm has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The phaerimm makes three Mind Lash attacks. It can replace one attack\
      \ with either (A) a Vicious Stinger attack or (B) a use of Spellcasting to cast\
      \ Command (level 3 version)."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 10 ft. or range 120 ft. *Hit:*\
      \ 32 (6d8 + 4) Psychic damage."
    "name": "Mind Lash"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing\
      \ damage plus 26 (4d12) Poison damage, and the target's <span title=\"Player's\
      \ Handbook (2024)\">Speed</span> is reduced to 0 feet until the start of the\
      \ phaerimm's next turn."
    "name": "Vicious Stinger"
  - "desc": "The phaerimm focuses on a magic item it can see within 10 feet. When\
      \ it does, the phaerimm drains the magic item of any charges. Regardless of\
      \ whether charges are drained, the phaerimm can cast Clairvoyance, Geas, Major\
      \ Image, and Mirage Arcane one additional time that day."
    "name": "Siphon Magic (Recharge 5-6)"
  - "desc": "The phaerimm casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 17):\n\n**At\
      \ will:** Command (level 3 version), Detect Magic, Detect Thoughts, Mage Hand\n\
      \n**1/day each:** Clairvoyance, Geas, Major Image, Mirage Arcane"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The phaerimm teleports up to 30 feet to an unoccupied space it can see."
    "name": "Teleport"
"reactions":
  - "desc": "The phaerimm casts Counterspell or Shield in response to the spell's\
      \ trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic (3/Day)"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/aberration/token/phaerimm-elder-nf.webp"
```
^statblock

## Environment

underdark, urban