---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: The Keeper
Status: WIP
linter-yaml-title-alias: The Keeper
tags:
  - Monster/Größe/Riesig
  - Monster/HG/7
  - Monster/Typ/Riese
  - Quelle/5e/tftyp
aliases:
  - The Keeper
---
# [The Keeper](3-Mechanics\CLI\bestiary\npc/the-keeper-tftyp.md)
*Source: Tales from the Yawning Portal p. 173*  

```statblock
"name": "The Keeper (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "chain mail"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Athletics"
    "desc": "+12"
  - "name": "Perception"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Giant"
"cr": "7"
"actions":
  - "desc": "The Keeper makes two battleaxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 15 ft., one target. *Hit:* 20\
      \ (3d8 + 7) slashing damage, or 23 (3d10 + 7) slashing damage if used with both\
      \ hands."
    "name": "Battleaxe +1"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or be knocked prone."
    "name": "Rock"
"reactions":
  - "desc": "If a rock or similar object is hurled at the Keeper, the Keeper can,\
      \ with a successful DC 10 Dexterity saving throw, catch the missile and take\
      \ no bludgeoning damage from it."
    "name": "Rock Catching"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/the-keeper-tftyp.webp"
```
^statblock