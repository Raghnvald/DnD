---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Minotaur Living Crystal Statue
Status: WIP
linter-yaml-title-alias: Minotaur Living Crystal Statue
tags:
  - Monster/Größe/Groß
  - Monster/HG/6
  - Monster/Typ/Konstrukt
  - Quelle/5e/gos
aliases:
  - Minotaur Living Crystal Statue
---
# [Minotaur Living Crystal Statue](3-Mechanics\CLI\bestiary\construct/minotaur-living-crystal-statue-gos.md)
*Source: Ghosts of Saltmarsh p. 245*  

Given life through powerful magic, a large, crudely carved crystal minotaur guards the tunnels in Isle of the Abbey.

```statblock
"name": "Minotaur Living Crystal Statue (GoS)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "9"
  - !!int "16"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "force"
"damage_immunities": "lightning, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "6"
"traits":
  - "desc": "The statue is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
"actions":
  - "desc": "The statue makes two attacks: one with its greataxe and one gore attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 17\
      \ (2d12 + 4) slashing damage."
    "name": "Greataxe"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) piercing damage."
    "name": "Gore"
"reactions":
  - "desc": "In response to a creature hitting the statue with a melee weapon attack,\
      \ the statue deals 11 (2d10) piercing damage to the attacker."
    "name": "Flying Shards"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/construct/token/minotaur-living-crystal-statue-gos.webp"
```
^statblock