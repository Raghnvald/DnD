---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scholarly Mastermind"
---
# [Scholarly Mastermind](3-Mechanics/CLI/bestiary/humanoid/scholarly-mastermind-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 207*  

Scholarly masterminds are the formidable leaders of academic research organizations, responsible for planning and carrying out operations that delve into the secrets of the past. Some masterminds are headmasters at academies or universities. Others operate individually and in secret, pursuing agendas that might diverge wildly from those of the rest of their organization.

## Scholars of Allsight

The Allegiance of Allsight is a scholarly faction that operates primarily within the Marquesian metropolis of Ank'Harel. Though most members of the allegiance are academics unfamiliar with combat, the faction's field agents are skilled archaeologists who are also trained to contend with and overcome the threats that lurk in the depths of Exandria.

```statblock
"name": "Scholarly Mastermind (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "13"
  - !!int "18"
  - !!int "16"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "History"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common plus three other languages"
"cr": "5"
"actions":
  - "desc": "The mastermind makes two Arcane Shock or Dagger of the Poisoned Mind\
      \ attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 26 (4d10 + 4) lightning damage. If the target is\
      \ a creature, it can't take reactions until the start of its next turn."
    "name": "Arcane Shock"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 10 (3d6) psychic\
      \ damage. If the target is a creature, it must succeed on a DC 15 Wisdom saving\
      \ throw or be frightened until the end of its next turn."
    "name": "Dagger of the Poisoned Mind"
  - "desc": "The mastermind casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 15):\n\n**At will:** alter self, light, mage hand\n\n**1/day each:** comprehend\
      \ languages, mage armor, zone of truth"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/scholarly-mastermind-crcotn.webp"
```
^statblock