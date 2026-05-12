---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ferocidon"
---
# [Ferocidon](3-Mechanics/CLI/bestiary/beast/ferocidon-psx.md)
*Source: Plane Shift: Ixalan p. 30*  

## Teeth and Frills

Ferocidons are particularly vicious relatives of raptors, specialized to take down much larger prey. Use the [allosaurus](3-Mechanics/CLI/bestiary/beast/allosaurus.md) statistics in the "Monster Manual" for these creatures.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Ferocidon (PSX)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "13"
  - !!int "17"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": ""
"cr": "2"
"traits":
  - "desc": "If the ferocidon moves at least 30 feet straight toward a creature and\
      \ then hits it with a claw attack on the same turn, that target must succeed\
      \ on a DC 13 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the ferocidon\
      \ can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 15\
      \ (2d10 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage."
    "name": "Claw"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/ferocidon-psx.webp"
```
^statblock