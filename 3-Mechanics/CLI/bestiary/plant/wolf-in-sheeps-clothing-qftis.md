---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wolf-in-Sheep's-Clothing"
---
# [Wolf-in-Sheep's-Clothing](3-Mechanics/CLI/bestiary/plant/wolf-in-sheeps-clothing-qftis.md)
*Source: Quests from the Infinite Staircase p. 221*  

A wolf-in-sheep's-clothing is a predatory plant that resembles a tree stump. It hides in areas of thick vegetation and has a bark-like hide, eyestalks like vines or withered flowers, rootlike tentacles, and a fleshy growth atop its body that it uses to lure prey toward its fang-filled maw.

Wolves-in-sheep's-clothing can reshape their lures to mimic the appearance of various small, often adorable creatures to entice their prey. The Lure Forms table suggests some forms the lure might take.

| dice: d6 | Lure Appearance |
|----------|-----------------|
| 1 | Clumsy puppy |
| 2 | Cute little bunnyoid |
| 3 | Dapper, smiling frog with a little top hat |
| 4 | Fluffy kitten |
| 5 | Fox with adorably large ears |
| 6 | Spunky, dancing crawfish |
^lure-appearance

```statblock
"name": "Wolf-in-Sheep's-Clothing (QftIS)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "9"
  - !!int "16"
  - !!int "5"
  - !!int "12"
  - !!int "5"
"speed": "20 ft., climb 20 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"condition_immunities": "[prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 17"
"languages": ""
"cr": "7"
"traits":
  - "desc": "If the wolf-in-sheep's-clothing is motionless (except for its lure) at\
      \ the start of combat, it has advantage on its initiative roll. Moreover, if\
      \ a creature hasn't observed the wolf-in-sheep's-clothing move or act (except\
      \ for the lure), that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the wolf-in-sheep's-clothing is animate."
    "name": "False Appearance"
"actions":
  - "desc": "The wolf-in-sheep's-clothing makes one Bite attack and two Root Tentacle\
      \ attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d8 + 5) piercing damage plus 7 (2d6) acid damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one target. *Hit:*\
      \ 8 (1d6 + 5) bludgeoning damage, and if the target is a Medium or smaller\
      \ creature, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 16). While [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ in this way, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition, and at the start of each of the wolf-in-sheep's-clothing's turns,\
      \ the wolf-in-sheep's-clothing can pull the target up to 10 feet toward itself\
      \ (no action required). The wolf-in-sheep's-clothing has four root tentacles,\
      \ each of which can grapple one target."
    "name": "Root Tentacle"
"bonus_actions":
  - "desc": "The wolf-in-sheep's-clothing can change the color, texture, and shape\
      \ of its lure to resemble a Tiny Beast or Tiny object. It can move the lure\
      \ to reinforce the resemblance (no action required), but the lure must remain\
      \ within 15 feet of the wolf-in-sheep's-clothing, connected by nearly [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ filament-like tendrils."
    "name": "Completely Harmless Lure"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/plant/token/wolf-in-sheeps-clothing-qftis.webp"
```
^statblock