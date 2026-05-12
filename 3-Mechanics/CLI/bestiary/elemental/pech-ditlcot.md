---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ditlcot
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pech"
---
# [Pech](3-Mechanics/CLI/bestiary/elemental/pech-ditlcot.md)
*Source: Descent into the Lost Caverns of Tsojcanth p. 16*  

Pechs are slight, bipedal diggers from the Elemental Plane of Earth. They have a knack for finding weak points in buildings, objects, and raw materials, making them phenomenal excavators—and, if the occasion calls for it, sappers and saboteurs. Pechs enjoy sculpting and carving vast networks of tunnels and warrens, where they live in clans and mine precious metals and gems.

Small and lithe, pechs have long, thin limbs and broad feet. Their large, pupilless eyes are sensitive to bright light, which they avoid, and they find sunlight nauseating. Their skin displays a spectrum of color and texture as varied as that of clay, earth, and stone.

A single pech can draw on the magic of the Elemental Plane of Earth to shape stone to its will, but pechs are stronger together than alone. When in groups, pechs can combine their magic to conjure great curtains of stone and infuse creatures with the fortitude of elemental earth.

```statblock
"name": "Pech (DitLCoT)"
"size": "Small"
"type": "elemental"
"alignment": "typically  Neutral Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d6 + 44"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "18"
  - !!int "11"
  - !!int "14"
  - !!int "10"
"speed": "30 ft., burrow 20 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+4"
"condition_immunities": "petrified"
"senses": "darkvision 120 ft., tremorsense 120 ft., passive Perception 14"
"languages": "Common, Terran"
"cr": "4"
"traits":
  - "desc": "The pech has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, the pech has disadvantage on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The pech makes two Fortified Pickaxe attacks. If it hits a Large or smaller\
      \ creature with both attacks, the target must succeed on a DC 14 Strength saving\
      \ throw or have the prone condition."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) force damage. If the target is a Construct or an object, the attack\
      \ is automatically a critical hit."
    "name": "Fortified Pickaxe"
  - "desc": "The pech works with three or more pechs to cast spells, requiring no\
      \ spell components and using Wisdom as the spellcasting ability (save DC 12).\
      \ If at least three other pechs are within 30 feet of it, the pech can cast\
      \ Wall of Stone. If at least seven other pechs are within 30 feet of it, it\
      \ can cast Greater Restoration. Each other pech involved in casting the spell\
      \ can't have the incapacitated condition and must have at least one use of Communal\
      \ Spellcasting remaining, which it must immediately expend to participate (no\
      \ action required).\n"
    "name": "Communal Spellcasting (2/Day)"
  - "desc": "The pech casts Stone Shape, requiring no spell components and using Wisdom\
      \ as the spellcasting ability.\n"
    "name": "Stone Shape (3/Day)"
"source":
  - "DitLCoT"
"image": "3-Mechanics/CLI/bestiary/elemental/token/pech-ditlcot.webp"
```
^statblock