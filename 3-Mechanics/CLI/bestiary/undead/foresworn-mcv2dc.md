---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv2dc
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Foresworn"
---
# [Foresworn](3-Mechanics/CLI/bestiary/undead/foresworn-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 7*  

Foresworn are the spirits of fallen Solamnic knights who attend to their duty long after death. Armed with spectral armor and weaponry, a foresworn maintains the martial prowess it had in life and can call on magic and its fallen brethren for aid.

Like revenants, foresworn fixate on a singular purpose, and they refuse to abandon their undead state until the duty they had in life is fulfilled. For example, a foresworn might be pledged to protect a family's bloodline from harm or guard a dangerous artifact against thieves. If a foresworn is destroyed before it can complete its duty, it returns within a few days, its strength and purpose renewed.

```statblock
"name": "Foresworn (MCV2DC)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
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
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
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
      \n**2/day each:** [command](3-Mechanics/CLI/spells/command.md), [detect evil\
      \ and good](3-Mechanics/CLI/spells/detect-evil-and-good.md)\n\n**1/day:** [wall\
      \ of force](3-Mechanics/CLI/spells/wall-of-force.md)"
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
"image": "3-Mechanics/CLI/bestiary/undead/token/foresworn-mcv2dc.webp"
```
^statblock