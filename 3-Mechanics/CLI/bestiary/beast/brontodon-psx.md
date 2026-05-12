---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Brontodon"
---
# [Brontodon](3-Mechanics/CLI/bestiary/beast/brontodon-psx.md)
*Source: Plane Shift: Ixalan p. 27*  

## The Rumbling Herds

The largest of the dinosaurs are huge, long-necked herbivores that feed on the leaves of tall trees. The enormous size of these dinosaurs means that a single beast—often a young, old, or injured one that becomes separated from the herd—can feed a whole pack of smaller predators. The magnificent Altisaurs wander across the plains and through the sparse forests of the Sun Coast, grazing on the tops of trees. Brontodons travel in herds, causing the ground to thunder beneath their tremendous weight when they build up speed. Use [brontosaurus](3-Mechanics/CLI/bestiary/beast/brontosaurus-mpmm.md) stats from "Volo's Guide to Monsters" for these beasts.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Brontodon (PSX)"
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
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one target. *Hit:*\
      \ 27 (5d8 + 5) bludgeoning damage, and the target must succeed on a DC 14\
      \ Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Stomp"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one target. *Hit:*\
      \ 32 (6d8 + 5) bludgeoning damage."
    "name": "Tail"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/brontodon-psx.webp"
```
^statblock