---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Snow Golem
---
# [Snow Golem](3-Mechanics\CLI\bestiary\construct/snow-golem-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 308*  

A snow golem is a mass of snow brought to life through magic. Nonmagical weapons pass through its snowy form without dealing any appreciable damage to it, though heat is its doom.

```statblock
"name": "Snow Golem (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "1"
  - !!int "6"
  - !!int "1"
"speed": "10 ft."
"damage_vulnerabilities": "fire"
"damage_immunities": "cold; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "3"
"traits":
  - "desc": "Whenever the golem is subjected to cold damage, it takes no damage and\
      \ instead regains a number of hit points equal to the cold damage dealt."
    "name": "Cold Absorption"
  - "desc": "The golem is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "While in an area of extreme heat, the golem loses 1d6 hit points at the\
      \ start of each of its turns."
    "name": "Melt"
  - "desc": "The golem doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The golem makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage plus 7 (2d6) cold damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +0 to hit, range 60 ft., one target. *Hit:* 9\
      \ (2d6 + 2) cold damage."
    "name": "Snowball"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/construct/token/snow-golem-idrotf.webp"
```
^statblock