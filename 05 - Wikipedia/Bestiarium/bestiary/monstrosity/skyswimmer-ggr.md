---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/13
- Monster/Größe/Gigantisch
- Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skyswimmer
---
# [Skyswimmer](3-Mechanics\CLI\bestiary\monstrosity/skyswimmer-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 220*  

Skyswimmers are enormous, predatory leviathans that feed on drakes, rocs, griffins, and anything else they encounter as they soar through the clouds above Ravnica.

```statblock
"name": "Skyswimmer (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d20 + 48"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "16"
  - !!int "7"
  - !!int "12"
  - !!int "6"
"speed": "10 ft., fly 60 ft."
"saves":
  - "constitution": !!int "8"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": ""
"cr": "13"
"traits":
  - "desc": "The skyswimmer can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The skyswimmer makes three attacks: one with its bite and two with its\
      \ slam."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (3d10 + 6) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 19 Dexterity saving throw or be swallowed by the skyswimmer.\
      \ A swallowed creature is blinded and restrained, it has total cover against\
      \ attacks and other effects outside the skyswimmer, and it takes 21 (6d6) acid\
      \ damage at the start of each of the skyswimmer's turns. If the skyswimmer takes\
      \ 30 damage or more on a single turn from the swallowed creature, the skyswimmer\
      \ must succeed on a DC 18 Constitution saving throw at the end of that turn\
      \ or regurgitate the creature, which falls prone in a space within 10 feet of\
      \ the skyswimmer. If the skyswimmer dies, a swallowed creature is no longer\
      \ restrained by it and can escape from the corpse by using 15 feet of movement,\
      \ exiting prone."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 30 ft., one target. *Hit:* 19\
      \ (2d12 + 6) bludgeoning damage."
    "name": "Slam"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/skyswimmer-ggr.webp"
```
^statblock