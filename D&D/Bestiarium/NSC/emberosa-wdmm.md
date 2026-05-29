---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Emberosa
linter-yaml-title-alias: Emberosa
tags:
  - Monster/Größe/Riesig
  - Monster/HG/9
  - Monster/Typ/Riese
  - Quelle/5e/wdmm
aliases:
  - Emberosa
---
# [Emberosa](3-Mechanics\CLI\bestiary\npc/emberosa-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 185*  

With dark skin and flaming red hair, fire giants have a fearsome reputation as soldiers and conquerors. They dwell among volcanoes, lava flows, and rocky mountains, and are known for their ability to burn, plunder, and destroy.

```statblock
"name": "Emberosa (WDMM)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "221"
"hit_dice": "13d12 + 78"
"modifier": !!int "-1"
"stats":
  - !!int "25"
  - !!int "9"
  - !!int "23"
  - !!int "10"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "3"
  - "constitution": !!int "10"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+11"
  - "name": "Perception"
    "desc": "+6"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Giant"
"cr": "9"
"actions":
  - "desc": "Emberosa makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 28\
      \ (6d6 + 7) slashing damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +11 to hit, range 60/240 ft., one target. *Hit:*\
      \ 29 (4d10 + 7) fire damage."
    "name": "Hurl Fire"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/emberosa-wdmm.webp"
```
^statblock