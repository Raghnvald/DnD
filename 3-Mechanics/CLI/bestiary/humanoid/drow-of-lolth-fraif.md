---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow of Lolth"
---
# [Drow of Lolth](3-Mechanics/CLI/bestiary/humanoid/drow-of-lolth-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 260*  

Drow of Lolth defend cities in the Underdark and raid the surface in the name of the Spider Queen.

## Drow of Lolth

*Elves Who Serve the Spider Queen*

Throughout the vast Underdark, in cities such as Menzoberranzan, many drow worship Lolth, the Spider Queen. Exiled from the surface world millennia ago, these drow now consider the Underdark to be their true home. Their insidious schemes include raiding the surface, plotting against each other, and preparing for ultimate war.

```statblock
"name": "Drow of Lolth (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+4"
"gear":
  - "chain shirt"
  - "rapier"
"senses": "Darkvision 120 ft., passive Perception 12"
"languages": "Common, Elvish, Undercommon"
"cr": "1/4"
"traits":
  - "desc": "The drow has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws it makes to avoid or end the Charmed condition, and magic\
      \ can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing\
      \ damage."
    "name": "Rapier"
  - "desc": "*Ranged Attack Roll:* +4, range 30/120 ft. *Hit:* 4 (1d4 + 2) Piercing\
      \ damage, and the target makes a saving throw. *Constitution Saving Throw:*\
      \ DC 12. *Failure:* The target has the Poisoned condition for 1 hour. If the\
      \ target fails the save by 5 or more, it also has the Unconscious condition\
      \ while Poisoned in this way. The target wakes up if it takes damage or if a\
      \ creature within 5 feet of it takes an action to wake it."
    "name": "Drow Hand Crossbow"
  - "desc": "The drow casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 11):\n\n**At\
      \ will:** Dancing Lights\n\n**1/day:** Faerie Fire"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/drow-of-lolth-fraif.webp"
```
^statblock

## Environment

underdark, urban