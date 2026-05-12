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
- "Water Totem Elemental"
---
# [Water Totem Elemental](3-Mechanics/CLI/bestiary/elemental/water-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Water Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., swim 90 ft."
"damage_resistances": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Aquan"
"cr": "5"
"traits":
  - "desc": "The totem elemental can enter a hostile creature's space and stop there.\
      \ It can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Water Form"
  - "desc": "If the totem elemental takes cold damage, it partially freezes; its speed\
      \ is reduced by 20 feet until the end of its next turn."
    "name": "Freeze"
"actions":
  - "desc": "The totem elemental makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "Each creature in the totem elemental's space must make a DC 15 Strength\
      \ saving throw. On a failure, a target takes 13 (2d8 + 4) bludgeoning damage.\
      \ If it is Large or smaller, it is also [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 14). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ and unable to breathe unless it can breathe water. If the saving throw is\
      \ successful, the target is pushed out of the totem elemental's space.\n\nThe\
      \ totem elemental can grapple one Large creature or up to two Medium or smaller\
      \ creatures at one time. At the start of each of the totem elemental's turns,\
      \ each target [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by it\
      \ takes 13 (2d8 + 4) bludgeoning damage. A creature within 5 feet of the totem\
      \ elemental can pull a creature or object out of it by taking an action to make\
      \ a DC 14 Strength check and succeeding."
    "name": "Whelm (Recharge 4-6)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/elemental/token/water-totem-elemental-psx.webp"
```
^statblock