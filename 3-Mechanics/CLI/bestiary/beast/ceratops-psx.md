---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ceratops"
---
# [Ceratops](3-Mechanics/CLI/bestiary/beast/ceratops-psx.md)
*Source: Plane Shift: Ixalan p. 28*  

## Horned Herbivores

Many smaller herbivores are found on the plains of Ixalan. Rather than depending on size for defense, these dinosaurs are protected by plated scales, sharp horns, or spiked tails. Most are aggressively proactive in chasing off predators even before they are attacked, and the people of the Sun Empire find these creatures among the hardest dinosaurs to control.

Ceratopses sport enormous horns on and around the large, feathered frills that protect their necks. The related snubhorns lack the sharp pointed horns of their cousins. Despite their surly temper, ceratopses make excellent mounts. The [triceratops](3-Mechanics/CLI/bestiary/beast/triceratops.md) in the "Monster Manual" can represent all of these dinosaurs.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Ceratops (PSX)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d12 + 30"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "11"
  - !!int "5"
"speed": "50 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "If the ceratops moves at least 20 feet straight toward a creature and\
      \ then hits it with a gore attack on the same turn, that target must succeed\
      \ on a DC 13 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the ceratops\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 24\
      \ (4d8 + 6) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 22 (3d10 + 6) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/ceratops-psx.webp"
```
^statblock