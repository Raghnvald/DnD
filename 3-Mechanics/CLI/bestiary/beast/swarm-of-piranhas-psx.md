---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Piranhas"
---
# [Swarm of Piranhas](3-Mechanics/CLI/bestiary/beast/swarm-of-piranhas-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

The waters of the Great River and all its tributaries are home to fish that serve as one of the most important food sources for other animals in the forest. These include large predatory fish, as well as churning swarms of small biting fish such as piranhas.

```statblock
"name": "Swarm of Piranhas (PSX)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "28"
"hit_dice": "8d8 - 8"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "9"
  - !!int "1"
  - !!int "7"
  - !!int "2"
"speed": "0 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The swarm has advantage on melee attack rolls against any creature that\
      \ doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny piranha. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
  - "desc": "The swarm can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 0 ft., one creature in the\
      \ swarm's space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage\
      \ if the swarm has half of its hit points or fewer."
    "name": "Bites"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/swarm-of-piranhas-psx.webp"
```
^statblock