---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Treant Totem Elemental"
---
# [Treant Totem Elemental](3-Mechanics/CLI/bestiary/plant/treant-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](3-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](3-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](3-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](3-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](3-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](3-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](3-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Treant Totem Elemental (PSX)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "8"
  - !!int "21"
  - !!int "12"
  - !!int "16"
  - !!int "12"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
  - "desc": "While the treant totem remains motionless, it is indistinguishable from\
      \ a normal tree."
    "name": "False Appearance"
  - "desc": "The treant totem deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The treant totem makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (3d6 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/180 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
  - "desc": "The treant totem magically animates one or two trees it can see within\
      \ 60 feet of it. These trees have the same statistics as a treant totem, except\
      \ they have Intelligence and Charisma scores of 1, they can't speak, and they\
      \ have only the Slam action option. An animated tree acts as an ally of the\
      \ treant totem. The tree remains animate for 1 day or until it dies; until the\
      \ treant totem dies or is more than 120 feet from the tree; or until the treant\
      \ totem takes a bonus action to turn it back into an inanimate tree. The tree\
      \ then takes root if possible."
    "name": "Animate Trees (1/Day)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/plant/token/treant-totem-elemental-psx.webp"
```
^statblock