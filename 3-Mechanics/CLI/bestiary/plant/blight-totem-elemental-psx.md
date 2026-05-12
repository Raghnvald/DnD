---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Blight Totem Elemental"
---
# [Blight Totem Elemental](3-Mechanics/CLI/bestiary/plant/blight-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Blight Totem Elemental (PSX)"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"modifier": !!int "-1"
"stats":
  - !!int "15"
  - !!int "8"
  - !!int "14"
  - !!int "5"
  - !!int "10"
  - !!int "3"
"speed": "10 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+1"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "While the blight totem remains motionless, it is indistinguishable from\
      \ a tangle of vines."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:*\
      \ 9 (2d6 + 2) bludgeoning damage, and a Large or smaller target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 12). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the blight totem can't constrict another target."
    "name": "Constrict"
  - "desc": "Grasping roots and vines sprout in a 15-foot radius centered on the blight\
      \ totem, withering away after 1 minute. For the duration, that area is difficult\
      \ terrain for nonplant creatures. In addition, each creature of the blight totem's\
      \ choice in that area when the plants appear must succeed on a DC 12 Strength\
      \ saving throw or become [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ A creature can use its action to make a DC 12 Strength check, freeing itself\
      \ or another entangled creature within reach on a success."
    "name": "Entangling Plants (Recharge 5-6)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/plant/token/blight-totem-elemental-psx.webp"
```
^statblock