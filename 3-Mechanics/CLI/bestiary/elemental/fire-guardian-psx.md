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
- "Fire Guardian"
---
# [Fire Guardian](3-Mechanics/CLI/bestiary/elemental/fire-guardian-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Fire Guardian (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "17"
  - !!int "16"
  - !!int "6"
  - !!int "10"
  - !!int "7"
"speed": "50 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Ignan"
"cr": "5"
"traits":
  - "desc": "The fire guardian can move through a space as narrow as 1 inch wide without\
      \ squeezing. A creature that touches the fire guardian or hits it with a melee\
      \ attack while within 5 feet of it takes 5 (1d10) fire damage. In addition,\
      \ the fire guardian can enter a hostile creature's space and stop there. The\
      \ first time it enters a creature's space on a turn, that creature takes 5 (1d10)\
      \ fire damage and catches fire; until someone takes an action to douse the fire,\
      \ the creature takes 5 (1d10) fire damage at the start of each of its turns."
    "name": "Fire Form"
  - "desc": "The fire guardian sheds bright light in a 30-foot radius and dim light\
      \ in an additional 30 feet."
    "name": "Illumination"
  - "desc": "For every 5 feet the fire guardian moves in water, or for every gallon\
      \ of water splashed on it, it takes 1 cold damage."
    "name": "Water Susceptibility"
"actions":
  - "desc": "The fire guardian makes two touch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) fire damage. If the target is a creature or a flammable object,\
      \ it ignites. Until a creature takes an action to douse the fire, the target\
      \ takes 5 (1d10) fire damage at the start of each of its turns."
    "name": "Touch"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/elemental/token/fire-guardian-psx.webp"
```
^statblock