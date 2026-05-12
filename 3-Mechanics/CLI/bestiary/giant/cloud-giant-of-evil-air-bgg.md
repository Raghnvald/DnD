---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cloud Giant of Evil Air"
---
# [Cloud Giant of Evil Air](3-Mechanics/CLI/bestiary/giant/cloud-giant-of-evil-air-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 125*  

Given their inherent link to elemental air, cloud giants who turn from the gods of the Ordning often gravitate to the service of Yan-C-Bin, Prince of Evil Air. These giants' cunning, charisma, and sheer physical and magical might make them well suited to leadership positions in the cults of Elemental Evil. A cult with a cloud giant at its head can be a formidable force of corruption and destruction in the world. As if that weren't enough, cloud giants often bring tremendous wealth with them, swelling the cult's coffers to finance more far-reaching operations.

A cloud giant dedicated to Evil Air wears a magic vest adorned with wings made from roc feathers and enchanted with elemental air, allowing the giant to fly. The vest functions only for the giant who wears it.

```statblock
"name": "Cloud Giant of Evil Air (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"modifier": !!int "0"
"stats":
  - !!int "27"
  - !!int "10"
  - !!int "22"
  - !!int "12"
  - !!int "16"
  - !!int "19"
"speed": "40 ft., fly 40 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+4"
"gear":
  - "scimitar"
"senses": "passive Perception 17"
"languages": "Auran, Common, Giant"
"cr": "12"
"traits":
  - "desc": "The giant doesn't provoke an opportunity attack when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "The giant makes two Scimitar attacks and one Storm Boomerang attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:*\
      \ 18 (3d6 + 8) slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Weapon Attack:* +12 to hit, range 60/240 ft., one target. *Hit:*\
      \ 15 (3d4 + 8) bludgeoning damage plus 7 (2d6) thunder damage, and the target\
      \ must succeed on a DC 16 Constitution saving throw or have the stunned condition\
      \ until the end of its next turn. *Hit or Miss:* The boomerang magically returns\
      \ to the giant's hand immediately after the attack."
    "name": "Storm Boomerang"
  - "desc": "The giant casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** detect magic, fog cloud, light\n\n**2/day:** telekinesis\n\n**1/day:**\
      \ gaseous form"
    "name": "Spellcasting"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/giant/token/cloud-giant-of-evil-air-bgg.webp"
```
^statblock