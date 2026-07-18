---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Reghed Warrior
Status: WIP
linter-yaml-title-alias: Reghed Warrior
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-8
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/idrotf
aliases:
  - Reghed Warrior
---
# [Reghed Warrior](3-Mechanics\CLI\bestiary\humanoid/reghed-warrior-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 152*  

Tribal warriors live beyond civilization, most often subsisting on fishing and hunting. Each tribe acts in accordance with the wishes of its chief, who is the greatest or oldest warrior of the tribe or a tribe member blessed by the gods.

```statblock
"name": "Reghed Warrior (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "hide armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "0"
"stats":
  - !!int "13"
  - !!int "11"
  - !!int "12"
  - !!int "8"
  - !!int "11"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "Survival"
    "desc": "+4"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/8"
"traits":
  - "desc": "The warrior has advantage on an attack roll against a creature if at\
      \ least one of the warrior's allies is within 5 feet of the creature and the\
      \ ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/reghed-warrior-idrotf.webp"
```
^statblock