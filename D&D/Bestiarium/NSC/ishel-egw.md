---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ishel
Status: WIP
linter-yaml-title-alias: Ishel
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Humanoid/elf
  - Quelle/5e/egw
aliases:
  - Ishel
---
# [Ishel](3-Mechanics\CLI\bestiary\npc/ishel-egw.md)
*Source: Explorer's Guide to Wildemount p. 231*  

Ishel—a drow ambassador from the Kryn Dynasty.

```statblock
"name": "Ishel (EGW)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "24"
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
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 12"
"languages": "Elvish, Undercommon"
"cr": "1/2"
"traits":
  - "desc": "Ishel's spellcasting ability is Charisma (spell save DC 11). It can innately\
      \ cast the following spells, requiring no material components:\n\n**At will:**\
      \ [dancing lights](/3-Mechanics/CLI/spells/dancing-lights-xphb.md)\n\n**1/day\
      \ each:** [darkness](/3-Mechanics/CLI/spells/darkness-xphb.md), [faerie fire](/3-Mechanics/CLI/spells/faerie-fire-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Ishel has advantage on saving throws against being [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ and magic can't put Ishel to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, Ishel has disadvantage on attack rolls, as well as\
      \ on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception)) checks that\
      \ rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) for\
      \ 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ while [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) in this way. The\
      \ target wakes up if it takes damage or if another creature takes an action\
      \ to shake it awake."
    "name": "Hand Crossbow"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ishel-egw.webp"
```
^statblock