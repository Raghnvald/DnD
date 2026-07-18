---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Champion
Status: WIP
linter-yaml-title-alias: Champion
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Wüste
  - Monster/HG/9
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/vgm
aliases:
  - Champion
---
# [Champion](3-Mechanics\CLI\bestiary\humanoid/champion-vgm.md)
*Source: Volo's Guide to Monsters p. 212, Tales from the Yawning Portal, Tomb of Annihilation*  

Champions are mighty warriors who honed their fighting skills in wars or gladiatorial pits. To soldiers and other people who fight for a living, champions are as influential as nobles, and their presence is courted as a sign of status among rulers.

```statblock
"name": "Champion (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "Athletics"
    "desc": "+9"
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "any one language (usually Common)"
"cr": "9"
"traits":
  - "desc": "The champion rerolls a failed saving throw."
    "name": "Indomitable (2/Day)"
  - "desc": "As a bonus action, the champion can regain 20 hit points."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The champion makes three attacks with its greatsword or its shortbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage, plus 7 (2d6) slashing damage if the champion has\
      \ more than half of its total hit points remaining."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if the champion\
      \ has more than half of its total hit points remaining."
    "name": "Shortbow"
"source":
  - "VGM"
  - "TftYP"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/champion-vgm.webp"
```
^statblock

## Environment

desert, urban