---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Space Mollymawk"
---
# [Space Mollymawk](3-Mechanics/CLI/bestiary/beast/space-mollymawk-bam.md)
*Source: Boo's Astral Menagerie p. 57*  

Space mollymawks are as common in Wildspace as albatrosses are on the Material Plane. They perch on the hulls of spelljamming ships and move from one ship's air envelope to another's when they need to.

A fully grown specimen is 3 feet tall with a 10-foot wingspan, and it eats whatever it can scavenge. If it finds a reliable food source, it lingers in the area (usually around a ship) until the food becomes scarce. Superstitious Wildspace voyagers consider it bad luck to kill a space mollymawk.

```statblock
"name": "Space Mollymawk (BAM)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "11"
  - !!int "3"
  - !!int "12"
  - !!int "3"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The mollymawk doesn't provoke opportunity attacks when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
  - "desc": "The mollymawk can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) piercing damage."
    "name": "Bite"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/beast/token/space-mollymawk-bam.webp"
```
^statblock