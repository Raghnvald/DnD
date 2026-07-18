---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sahuagin Champion
Status: WIP
linter-yaml-title-alias: Sahuagin Champion
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Humanoid/sahuagin
  - Quelle/5e/gos
aliases:
  - Sahuagin Champion
---
# [Sahuagin Champion](3-Mechanics\CLI\bestiary\humanoid/sahuagin-champion-gos.md)
*Source: Ghosts of Saltmarsh p. 249*  

Those sahuagin warriors who prove themselves through heroic acts are given both title and status. Sahuagin champions often serve as lieutenants in the sahuagin army, as they do in The Final Enemy.

```statblock
"name": "Sahuagin Champion (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "13"
  - !!int "9"
"speed": "30 ft., swim 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin"
"cr": "3"
"traits":
  - "desc": "The champion has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The champion can breathe air and water, but it needs to be submerged\
      \ at least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
  - "desc": "The champion can magically command any shark within 120 feet of it, using\
      \ a limited telepathy."
    "name": "Shark Telepathy"
"actions":
  - "desc": "The champion makes three attacks with its spear, or one attack with its\
      \ bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Claws"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/sahuagin-champion-gos.webp"
```
^statblock