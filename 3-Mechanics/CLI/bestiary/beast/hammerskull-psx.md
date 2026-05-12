---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hammerskull"
---
# [Hammerskull](3-Mechanics/CLI/bestiary/beast/hammerskull-psx.md)
*Source: Plane Shift: Ixalan p. 29*  

## Scales, Spikes, and Hammers

For dinosaurs without the prominent horns of the ceratopses, armored plating and deadly tails are an effective defense against predators.

Even lacking horns or spikes, hammerskulls can protect themselves with their thickly plated heads. The [giant goat](3-Mechanics/CLI/bestiary/beast/giant-goat.md) statistics in the "Monster Manual" can represent a hammerskull.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Hammerskull (PSX)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "If the hammerskull moves at least 20 feet straight toward a target and\
      \ then hits it with a ram attack on the same turn, the target takes an extra\
      \ 5 (2d4) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 13 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Charge"
  - "desc": "The hammerskull has advantage on Strength and Dexterity saving throws\
      \ made against effects that would knock it [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Sure-Footed"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (2d4 + 3) bludgeoning damage."
    "name": "Ram"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/hammerskull-psx.webp"
```
^statblock