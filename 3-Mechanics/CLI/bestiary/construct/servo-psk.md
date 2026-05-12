---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Servo"
---
# [Servo](3-Mechanics/CLI/bestiary/construct/servo-psk.md)
*Source: Plane Shift: Kaladesh p. 32*  

Servos are tiny constructs that function as personal assistants. They are often seen perched on the shoulders of their inventors, acting as a fashion statement as well as a useful extra hand. Servos are small enough to be grasped in one hand, with tiny gears providing impressive motive force from a small aether supply. They rarely stray far from their inventor-masters, but they can be sent to carry messages or perform similar tasks.

A servo can serve as a familiar to a character with the [Servo Crafting](3-Mechanics/CLI/feats/servo-crafting-psk.md) feat (see ""Inventing Options""), using the statistics below.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Servo (PSK)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"modifier": !!int "0"
"stats":
  - !!int "4"
  - !!int "11"
  - !!int "12"
  - !!int "3"
  - !!int "10"
  - !!int "7"
"speed": "20 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 10"
"languages": ""
"cr": "0"
"actions":
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 5 ft., one target. *Hit:* 1\
      \ slashing damage."
    "name": "Claw"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/servo-psk.webp"
```
^statblock