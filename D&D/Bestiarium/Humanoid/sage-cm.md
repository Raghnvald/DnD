---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sage
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/cm
aliases:
  - Sage
---
# [Sage](3-Mechanics\CLI\bestiary\humanoid/sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "10"
  - !!int "10"
  - !!int "18"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "History"
    "desc": "+8"
  - "name": "Insight"
    "desc": "+4"
  - "name": "Investigation"
    "desc": "+8"
  - "name": "Medicine"
    "desc": "+6"
  - "name": "Nature"
    "desc": "+8"
  - "name": "Religion"
    "desc": "+8"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "1/2"
"actions":
  - "desc": "*Melee Spell Attack:* +6 to hit (with advantage if the target is wearing\
      \ armor made of metal), reach 5 ft., one creature. *Hit:* 9 (2d8) lightning\
      \ damage, and the target can't take reactions until the start of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "The sage casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (save DC 14, +6 to hit with spell attacks):\n\n**At will:**\
      \ light, mage hand, mending\n\n**3/day each:** comprehend languages, detect\
      \ magic, identify\n\n**1/day each:** dispel magic, levitate, locate object,\
      \ see invisibility, sending, tongues, unseen servant"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the sage is hit by an attack or targeted by a magic missile spell,\
      \ it calls forth an invisible barrier of magical force that protects it. Until\
      \ the start of its next turn, the sage has a +5 bonus to AC, including against\
      \ the triggering attack, and it takes no damage from magic missile."
    "name": "Shield (1st-Level Spell; 3/Day)"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/sage-cm.webp"
```
^statblock