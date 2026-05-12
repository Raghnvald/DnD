---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demobat"
---
# [Demobat](3-Mechanics/CLI/bestiary/fiend/demobat-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Demobats are slimy, winged pests endemic to demonic realms. A demobat has four serrated tentacles, which trail behind it during flight, and its eyeless head opens wide to reveal a toothed maw. Demobats hunt in flocks, using their tails to strangle and immobilize their prey as they feed.

```statblock
"name": "Demobat (WttHC)"
"size": "Tiny"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "4"
  - !!int "16"
  - !!int "12"
  - !!int "2"
  - !!int "10"
  - !!int "6"
"speed": "10 ft., fly 40 ft."
"damage_resistances": "cold, lightning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "1/2"
"actions":
  - "desc": "*Melee Attack Roll:* +5 (with [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ if the target is [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by a Demobat), reach 5 ft.  *Hit:* 10 (2d6 + 3) Piercing damage."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing\
      \ damage. If the target is a Medium or smaller creature, the target has the\
      \ [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape\
      \ DC 13) from all four tentacles."
    "name": "Tentacles"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/demobat-wtthc.webp"
```
^statblock