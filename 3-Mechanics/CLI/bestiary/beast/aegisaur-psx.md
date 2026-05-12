---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aegisaur"
---
# [Aegisaur](3-Mechanics/CLI/bestiary/beast/aegisaur-psx.md)
*Source: Plane Shift: Ixalan p. 28*  

## Scales, Spikes, and Hammers

For dinosaurs without the prominent horns of the ceratopses, armored plating and deadly tails are an effective defense against predators.

An aegisaur's back is covered with thick, armored scales that resemble a turtle's shell, while its tail is tipped with a massive bony club that can smash an aggressor's skull. Use the [ankylosaurus](3-Mechanics/CLI/bestiary/beast/ankylosaurus.md) in the "Monster Manual" for these creatures.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Aegisaur (PSX)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d12 + 16"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "15"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "3"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 18 (4d6 + 4) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 14 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/aegisaur-psx.webp"
```
^statblock