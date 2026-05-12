---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aerosaur (Small)"
---
# [Aerosaur (Small)](3-Mechanics/CLI/bestiary/beast/aerosaur-small-psx.md)
*Source: Plane Shift: Ixalan p. 29*  

Aerosaurs include several varieties of large reptiles with leathery wings, including pterodons and sunwings. Though they are generally clumsy fliers, better at gliding from high perches or riding coastal updrafts than at lifting themselves from the ground, aerosaurs are sometimes used as mounts by knights of the Sun Empire. Smaller aerosaurs can be represented by the [pteranodon](3-Mechanics/CLI/bestiary/beast/pteranodon.md) in the "Monster Manual", while larger ones are more like the [quetzalcoatlus](3-Mechanics/CLI/bestiary/beast/quetzalcoatlus-mpmm.md) in "Volo's Guide to Monsters".

```statblock
"name": "Aerosaur (Small) (PSX)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "10"
  - !!int "2"
  - !!int "9"
  - !!int "5"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+1"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The aerosaur doesn't provoke opportunity attacks when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (2d4 + 1) piercing damage."
    "name": "Bite"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/aerosaur-small-psx.webp"
```
^statblock