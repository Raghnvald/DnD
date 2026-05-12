---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Polar Serpent"
---
# [Polar Serpent](3-Mechanics/CLI/bestiary/elemental/polar-serpent-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 269*  

## Polar Serpent

*Ephemeral, Heat-Draining Elemental*

Polar serpents are large, white snakes of mist and cold that lurk in snowy places of the world. They pursue warm-blooded prey through snowstorms and fog, wrapping around their victims to drain away their heat.

```statblock
"name": "Polar Serpent (FRAiF)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "19"
  - !!int "12"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "40 ft., fly 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+6"
"damage_vulnerabilities": "fire"
"damage_immunities": "cold"
"senses": "Darkvision 60 ft., passive Perception 13"
"languages": "understands Primordial but can't speak"
"cr": "3"
"traits":
  - "desc": "The serpent can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Misty Slithering"
"actions":
  - "desc": "The serpent makes one Bite attack and uses Constrict."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing\
      \ damage plus 3 (1d6) Cold damage."
    "name": "Bite"
  - "desc": "*Strength Saving Throw:* DC 14, one Medium or smaller creature the snake\
      \ can see within 10 feet. *Failure:* 3 (1d6) Bludgeoning damage plus 7 (2d6)\
      \ Cold damage. The target has the Grappled condition (escape DC 14), and it\
      \ has the Restrained condition until the grapple ends."
    "name": "Constrict"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/elemental/token/polar-serpent-fraif.webp"
```
^statblock

## Environment

arctic, underdark