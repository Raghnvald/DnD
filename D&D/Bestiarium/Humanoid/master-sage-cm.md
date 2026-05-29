---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Master Sage
linter-yaml-title-alias: Master Sage
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/cm
aliases:
  - Master Sage
---
# [Master Sage](3-Mechanics\CLI\bestiary\humanoid/master-sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Master Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "54"
"hit_dice": "12d8"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "10"
  - !!int "10"
  - !!int "20"
  - !!int "18"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+11"
  - "name": "History"
    "desc": "+11"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Investigation"
    "desc": "+11"
  - "name": "Medicine"
    "desc": "+10"
  - "name": "Nature"
    "desc": "+11"
  - "name": "Religion"
    "desc": "+11"
"senses": "passive Perception 14"
"languages": "Common plus any five languages"
"cr": "5"
"actions":
  - "desc": "*Melee Spell Attack:* +8 to hit (with advantage if the target is wearing\
      \ armor made of metal), reach 5 ft., one creature. *Hit:* 13 (3d8) lightning\
      \ damage, and the target can't take reactions until the start of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "The sage creates an eruption of magical lightning centered on a point\
      \ it can see within 150 feet of it. Each creature in a 20-foot-radius sphere\
      \ centered on that point must make a DC 16 Dexterity saving throw, taking 28\
      \ (8d6) lightning damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Lightning Eruption (3/Day)"
  - "desc": "The sage casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (save DC 16, +8 to hit with spell attacks):\n\n**At will:**\
      \ light, mage hand, mending, prestidigitation\n\n**3/day each:** comprehend\
      \ languages, detect magic, dispel magic, identify, levitate, locate object,\
      \ Tenser's Floating Disk, unseen servant\n\n**1/day each:** banishment, contact\
      \ other plane, Drawmij's instant summons, legend lore, locate creature, planar\
      \ binding, polymorph, protection from evil and good, scrying, sending, true\
      \ seeing"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the sage is hit by an attack or targeted by a magic missile spell,\
      \ it calls forth an invisible barrier of magical force that protects it. Until\
      \ the start of its next turn, the sage has a +5 bonus to AC, including against\
      \ the triggering attack, and it takes no damage from magic missile."
    "name": "Shield (1st-Level Spell; 3/Day)"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/master-sage-cm.webp"
```
^statblock