---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Earth Totem Elemental"
---
# [Earth Totem Elemental](3-Mechanics/CLI/bestiary/elemental/earth-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Earth Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "8"
  - !!int "20"
  - !!int "5"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., burrow 30 ft."
"damage_vulnerabilities": "thunder"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 10"
"languages": "Terran"
"cr": "5"
"traits":
  - "desc": "The totem elemental can burrow through nonmagical, unworked earth and\
      \ stone. While doing so, the totem elemental doesn't disturb the material it\
      \ moves through."
    "name": "Earth Glide"
  - "desc": "The totem elemental deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The totem elemental makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 14 (2d8 + 5) bludgeoning damage."
    "name": "Slam"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/elemental/token/earth-totem-elemental-psx.webp"
```
^statblock