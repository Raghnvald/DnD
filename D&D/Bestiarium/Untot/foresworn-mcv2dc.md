---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Foresworn
linter-yaml-title-alias: Foresworn
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/6
  - Monster/Typ/Untote
  - Quelle/5e/mcv2dc
aliases:
  - Foresworn
---
# [Foresworn](3-Mechanics\CLI\bestiary\undead/foresworn-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 7*  

Foresworn are the spirits of fallen Solamnic knights who attend to their duty long after death. Armed with spectral armor and weaponry, a foresworn maintains the martial prowess it had in life and can call on magic and its fallen brethren for aid.

Like revenants, foresworn fixate on a singular purpose, and they refuse to abandon their undead state until the duty they had in life is fulfilled. For example, a foresworn might be pledged to protect a family's bloodline from harm or guard a dangerous artifact against thieves. If a foresworn is destroyed before it can complete its duty, it returns within a few days, its strength and purpose renewed.

```statblock
"name": "Foresworn (MCV2DC)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Lawful Good"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "17"
  - !!int "12"
  - !!int "18"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "8"
  - "wisdom": !!int "7"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, frightened, grappled, paralyzed, petrified, poisoned,\
  \ prone, restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "6"
"traits":
  - "desc": "The foresworn is bound to enacting a singular duty it pledged itself\
      \ to in life. While this duty is incomplete, whenever the foresworn is destroyed,\
      \ it re-forms at its previous location after 3 (1d6) days, with all its hit\
      \ points restored."
    "name": "Duty-Bound"
  - "desc": "The foresworn can move through other creatures and objects as if they\
      \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
      \ inside an object."
    "name": "Incorporeal Movement"
  - "desc": "The foresworn doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The foresworn makes three Spectral Polearm attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) force damage."
    "name": "Spectral Polearm"
  - "desc": "The foresworn casts one of the following spells, requiring no material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 15):\n\
      \n**2/day each:** command, detect evil and good\n\n**1/day:** wall of force"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The foresworn summons a battalion of ghostly soldiers to its aid. The\
      \ ghostly soldiers fill a 10-foot-cube centered on the foresworn, move with\
      \ the foresworn when the foresworn moves, and last until the start of the foresworn's\
      \ next turn. While the ghostly soldiers are present, the area they occupy is\
      \ considered difficult terrain for all creatures except the foresworn, and the\
      \ foresworn's reach for melee weapon attacks increases by 10 feet."
    "name": "Phantasmic Battalion (Recharge 5-6)"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/undead/token/foresworn-mcv2dc.webp"
```
^statblock