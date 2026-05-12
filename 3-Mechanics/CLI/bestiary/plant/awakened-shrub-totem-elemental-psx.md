---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Awakened Shrub Totem Elemental"
---
# [Awakened Shrub Totem Elemental](3-Mechanics/CLI/bestiary/plant/awakened-shrub-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Awakened Shrub Totem Elemental (PSX)"
"size": "Small"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "10"
"hit_dice": "3d6"
"modifier": !!int "-1"
"stats":
  - !!int "3"
  - !!int "8"
  - !!int "11"
  - !!int "10"
  - !!int "10"
  - !!int "6"
"speed": "20 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "piercing"
"senses": "passive Perception 10"
"languages": "one language known by its creator"
"cr": "0"
"traits":
  - "desc": "While the shrub totem remains motionless, it is indistinguishable from\
      \ a normal shrub totem."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 1\
      \ (1d4 - 1) slashing damage."
    "name": "Rake"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/plant/token/awakened-shrub-totem-elemental-psx.webp"
```
^statblock