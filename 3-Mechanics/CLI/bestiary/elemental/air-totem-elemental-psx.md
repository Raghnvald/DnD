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
- "Air Totem Elemental"
---
# [Air Totem Elemental](3-Mechanics/CLI/bestiary/elemental/air-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Air Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"modifier": !!int "5"
"stats":
  - !!int "14"
  - !!int "20"
  - !!int "14"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "fly 90 ft. (hover)"
"damage_resistances": "lightning; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Auran"
"cr": "5"
"traits":
  - "desc": "The totem elemental can enter a hostile creature's space and stop there.\
      \ It can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Air Form"
"actions":
  - "desc": "The totem elemental makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) bludgeoning damage."
    "name": "Slam"
  - "desc": "Each creature in the totem elemental's space must make a DC 13 Strength\
      \ saving throw. On a failure, a target takes 15 (3d8 + 2) bludgeoning damage\
      \ and is flung up 20 feet away from the totem elemental in a random direction\
      \ and knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone). If a thrown\
      \ target strikes an object, such as a wall or floor, the target takes 3 (1d6)\
      \ bludgeoning damage for every 10 feet it was thrown. If the target is thrown\
      \ at another creature, that creature must succeed on a DC 13 Dexterity saving\
      \ throw or take the same damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\n\
      \nIf the saving throw is successful, the target takes half the bludgeoning damage\
      \ and isn't flung away or knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Whirlwind (Recharge 4-6)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/elemental/token/air-totem-elemental-psx.webp"
```
^statblock