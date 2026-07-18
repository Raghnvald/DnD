---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Derro Apprentice
Kategorie: Aberration
Größe: Klein
HG: 1
Status: WIP
linter-yaml-title-alias: Derro Apprentice
tags:
  - Quelle/5e/qftis
  - Monster/HG/1
  - Monster/Größe/Klein
  - Monster/Typ/Aberration
aliases:
  - Derro Apprentice
status: WIP
---
# [Derro Apprentice](3-Mechanics/CLI/bestiary/aberration/derro-apprentice-qftis.md)
*Source: Quests from the Infinite Staircase p. 196*  

Derro who have just begun to discover and control their magic are called apprentices. The magic of a derro apprentice is dangerous and unpredictable.

## Derro

Derro are Underdark dwellers of dubious origin. According to the histories of some duergar, derro are descended from a community of dwarves that was left behind when the others escaped the rule of mind flayers. The mind flayers' psionic power eventually transformed these forsaken dwarves into Aberrations.

You can learn more about derro in *Mordenkainen Presents: Monsters of the Multiverse*.

```statblock
"name": "Derro Apprentice (QftIS)"
"size": "Small"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "5"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "1"
"traits":
  - "desc": "The derro has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, the derro has disadvantage on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +3 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 10 (3d6) damage. Roll a d4 to determine the damage\
      \ type: 1, acid; 2, cold; 3, fire; 4, lightning."
    "name": "Chaos Blast"
  - "desc": "Raw arcane magic bursts out from the derro. Each creature within 10 feet\
      \ of it must make a DC 11 Strength saving throw. On a failed save, the creature\
      \ takes 7 (2d6) force damage and has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. On a successful save, the creature takes half as much damage only."
    "name": "Force Burst (Recharge 4-6)"
  - "desc": "The derro casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 11):\n\n**At will:** [Message](3-Mechanics/CLI/spells/message.md),\
      \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\n**1/day:**\
      \ [Charm Person](3-Mechanics/CLI/spells/charm-person.md)"
    "name": "Spellcasting"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/aberration/token/derro-apprentice-qftis.webp"
```
^statblock