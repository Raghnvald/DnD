---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sahuagin Blademaster
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/6
  - Monster/Typ/Humanoid/sahuagin
  - Quelle/5e/gos
aliases:
  - Sahuagin Blademaster
---
# [Sahuagin Blademaster](3-Mechanics\CLI\bestiary\humanoid/sahuagin-blademaster-gos.md)
*Source: Ghosts of Saltmarsh p. 249*  

A cunning veteran of countless campaigns, the sahuagin blademaster decorates its armor with the bones of its defeated foes. As demonstrated in The Final Enemy, sahuagin blademasters often serve as officers in the sahuagin army.

```statblock
"name": "Sahuagin Blademaster (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "plate armor, shield"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "12"
"speed": "30 ft., swim 40 ft."
"saves":
  - "strength": !!int "6"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Intimidation"
    "desc": "+4"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Sahuagin"
"cr": "6"
"traits":
  - "desc": "The blademaster has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The blademaster can breathe air and water, but it needs to be submerged\
      \ at least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
  - "desc": "The blademaster can magically command any shark within 120 feet of it,\
      \ using a limited telepathy."
    "name": "Shark Telepathy"
"actions":
  - "desc": "The blademaster makes three attacks with its wavecutter blade, or one\
      \ attack with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) slashing damage."
    "name": "Wavecutter Blade"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d10\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage."
    "name": "Claws"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/sahuagin-blademaster-gos.webp"
```
^statblock