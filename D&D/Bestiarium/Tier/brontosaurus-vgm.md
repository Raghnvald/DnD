---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Brontosaurus
linter-yaml-title-alias: Brontosaurus
tags:
  - Monster/Größe/Gigantisch
  - Monster/Habitat/Grasland
  - Monster/Habitat/Wald
  - Monster/HG/5
  - Monster/Typ/Tier
  - Quelle/5e/vgm
aliases:
  - Brontosaurus
---
# [Brontosaurus](3-Mechanics\CLI\bestiary\beast/brontosaurus-vgm.md)
*Source: Volo's Guide to Monsters p. 139, Tomb of Annihilation*  

This massive four-legged dinosaur is large enough that most predators leave it alone. Its deadly tail can drive away or kill smaller threats.

```statblock
"name": "Brontosaurus (VGM)"
"size": "Gargantuan"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "121"
"hit_dice": "9d20 + 27"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "10"
  - !!int "7"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one target. *Hit:* 27\
      \ (5d8 + 5) bludgeoning damage, and the target must succeed on a DC 14 Strength\
      \ saving throw or be knocked prone."
    "name": "Stomp"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one target. *Hit:* 32\
      \ (6d8 + 5) bludgeoning damage."
    "name": "Tail"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/beast/token/brontosaurus-vgm.webp"
```
^statblock

## Environment

grassland, forest