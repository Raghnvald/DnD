---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Thwad Underbrew
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/9
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/wdmm
aliases:
  - Thwad Underbrew
linter-yaml-title-alias: Thwad Underbrew
---
# [Thwad Underbrew](3-Mechanics\CLI\bestiary\npc/thwad-underbrew-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 204*  

Thwad Underbrew is a former champion of Gorm Gulthyn (the dwarven god of vigilance) who long ago set out to rid Undermountain of the evil that is Halaster Blackcloak. Halaster defeated Underbrew but offered to spare the dwarf's life if he vowed to serve the Mad Mage as an enforcer, ridding the dungeon of other invaders. Unwilling to face his own mortal end, Underbrew made this vow and convinced himself over time that the executions he performed were acts of mercy, because those he killed would never be forced to turn against their beliefs as he had. In time, these acts stopped weighing on Underbrew's conscience. In fact, the dwarf began to enjoy his grisly work.

```statblock
"name": "Thwad Underbrew (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
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
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "any one language (usually Common), Dwarvish"
"cr": "9"
"traits":
  - "desc": "Thwad rerolls a failed saving throw."
    "name": "Indomitable (2/Day)"
  - "desc": "As a bonus action, Thwad can regain 20 hit points."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
  - "desc": "Thwad"
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Thwad makes three attacks with his maul or his shortbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) bludgeoning damage, plus 7 (2d6) bludgeoning damage if Thwad has\
      \ more than half of his total hit points remaining."
    "name": "Maul"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if Thwad has more\
      \ than half of its total hit points remaining."
    "name": "Shortbow"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/thwad-underbrew-wdmm.webp"
```
^statblock