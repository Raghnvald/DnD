---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aatm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Heralds of Dust Exorcist"
---
# [Heralds of Dust Exorcist](3-Mechanics/CLI/bestiary/humanoid/heralds-of-dust-exorcist-aatm.md)
*Source: Adventure Atlas: The Mortuary*  

Dauntless in the face of death, exorcists in the Heralds of Dust cleanse hapless creatures and resting places haunted by ghosts, specters, and other malign entities that prevent the dead from being interred or jeopardize those already in repose. Though most Duster exorcists conduct their operations in the Mortuary, many heed calls throughout Sigil and the planes beyond.

The vagaries of undeath make spirits difficult to predict. Nevertheless, exorcists are well equipped for their work. Molded by experiences with apparitions and their ilk, exorcists channel the forces of death to preserve the living, commune with the dead, and drive evil spirits back to their graves. They can also fire versatile bolts of necrotic or radiant energy from their staves to repel a host of supernatural entities.

An exorcist's senses pierce the veil of death to perceive wandering ghosts on the Ethereal Plane as well as shadow demons, wraiths, and other incorporeal entities hiding in palls of darkness. With a brief reboant chant, an exorcist can expunge a harmful entity from a possessed creature—or make that creature vulnerable to a painful spiritual inhabitation.

```statblock
"name": "Heralds of Dust Exorcist (AATM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with mage armor"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "16"
  - !!int "17"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "5"
  - "charisma": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+6"
"damage_resistances": "necrotic"
"condition_immunities": "charmed, frightened"
"senses": "truesight 60 ft., passive Perception 15"
"languages": "Common plus three more languages"
"cr": "6"
"traits":
  - "desc": "The exorcist can't be possessed by Celestials, Fiends, or Undead."
    "name": "Incorruptible Vessel"
"actions":
  - "desc": "The exorcist makes two Grave Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 19 (3d10 + 3) necrotic or radiant damage (exorcist's\
      \ choice)."
    "name": "Grave Burst"
  - "desc": "The exorcist thins the veil of death for a creature it can see within\
      \ 60 feet of itself, exposing the target to malevolent entities. The target\
      \ must make a DC 14 Charisma saving throw. On a failed save, the target takes\
      \ 36 (8d8) psychic damage and has the incapacitated condition for 1 minute,\
      \ during which time it retches and babbles incoherently in a voice that is not\
      \ its own. On a successful save, the target takes half as much damage only.\
      \ An incapacitated target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Admit Entity (Recharge 5-6)"
  - "desc": "The exorcist casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 14, +6 to hit with spell attacks):\n\n**At will:** detect evil and good,\
      \ mage armor (self only), mage hand\n\n**2/day each:** protection from evil\
      \ and good, remove curse, speak with dead\n\n**1/day each:** banishment, dispel\
      \ evil and good"
    "name": "Spellcasting"
"source":
  - "AATM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/heralds-of-dust-exorcist-aatm.webp"
```
^statblock