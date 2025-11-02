---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/1
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Indentured Spirit
---
# [Indentured Spirit](3-Mechanics\CLI\bestiary\undead/indentured-spirit-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 206*  

Those who die with unpaid debts to the Orzhov Syndicate don't get a reprieve. Instead, their spirits serve the syndicate until they have worked off their obligation. Sometimes that means existing as an indentured spirit for years or even millennia.

An indentured spirit is an incorporeal being draped in ghostly black robes and a hood that hides whatever face it might have. Chains are hung around its chest and arms as a perpetual marker of its servitude.

```statblock
"name": "Indentured Spirit (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "11"
"speed": "0 ft., fly 40 ft. (hover)"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone, restrained"
"senses": "passive Perception 11"
"languages": "the languages it knew in life"
"cr": "1"
"traits":
  - "desc": "The spirit can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (3d6) necrotic damage."
    "name": "Withering Touch"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/undead/token/indentured-spirit-ggr.webp"
```
^statblock