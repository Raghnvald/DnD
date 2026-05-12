---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Trilobite (Giant)"
---
# [Trilobite (Giant)](3-Mechanics/CLI/bestiary/beast/trilobite-giant-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

On the beaches and banks of the rivers and seas, crabs scuttle across the sand and birds wade in the shallow water. Trilobites are among the most common shore-dwellers, including predatory varieties as well as scavengers and filter-feeders consuming scraps they find in the sand.

```statblock
"name": "Trilobite (Giant) (PSX)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "11"
  - !!int "1"
  - !!int "9"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., passive\
  \ Perception 9"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "The trilobite can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d6 + 1) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 11). The trilobite has two claws, each of which can grapple only\
      \ one target."
    "name": "Claw"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/trilobite-giant-psx.webp"
```
^statblock