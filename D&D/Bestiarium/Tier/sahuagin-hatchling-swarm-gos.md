---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/gos
  - Monster/HG/3
  - Monster/Größe/Groß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sahuagin Hatchling Swarm
---
# [Sahuagin Hatchling Swarm](3-Mechanics\CLI\bestiary\beast/sahuagin-hatchling-swarm-gos.md)
*Source: Ghosts of Saltmarsh p. 250*  

Roiling through the waters in The Final Enemy, these swarms of sahuagin hatchlings are dangerous to any creatures they encounter. Other sahuagin avoid the swarms, while the individual members devour one another until only the strongest hatchlings are left alive to grow to maturity.

```statblock
"name": "Sahuagin Hatchling Swarm (GoS)"
"size": "Large"
"type": "beast"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"modifier": !!int "4"
"stats":
  - !!int "9"
  - !!int "18"
  - !!int "12"
  - !!int "3"
  - !!int "10"
  - !!int "3"
"speed": "0 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "charmed, frightened, grappled, paralyzed, petrified, prone,\
  \ restrained, stunned"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The swarm has advantage on melee attack rolls against any creature that\
      \ doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "Once it enters combat, the swarm deals 10 slashing damage to itself at\
      \ the end of its turn if it did not make an attack on that turn. This damage\
      \ ignores resistance, and it cannot reduce the swarm to 0 hit points."
    "name": "Seething"
  - "desc": "The swarm can occupy another creature's space and vice versa, and it\
      \ can move through any opening large enough for a Tiny creature. The swarm can't\
      \ regain hit points or gain temporary hit points."
    "name": "Swarm"
  - "desc": "The swarm can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 0 ft., one creature in the swarm's\
      \ space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the\
      \ swarm has half of its hit points or fewer."
    "name": "Bites"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/beast/token/sahuagin-hatchling-swarm-gos.webp"
```
^statblock