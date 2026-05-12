---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swanmay"
---
# [Swanmay](3-Mechanics/CLI/bestiary/fey/swanmay-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 281*  

## Swanmay

*Shape-Changing Protector of Nature*

Swanmays are members of a reclusive order of wilderness defenders. Each bears a primal blessing that allows them to transform into a swan to watch over the lakes and woods they call home. Swanmays get along well with dryads and other creatures devoted to protecting the wilderness.

Roll or choose a result from the Swanmay's Charge table as inspiration for what a swanmay protects.

| dice: 1d6 | The Swanmay Is Devoted to Protecting... |
|-----------|-----------------------------------------|
| 1 | A hidden spring. |
| 2 | A lakeshore recently ravaged by a forest fire. |
| 3 | The conjunction of three rivers. |
| 4 | A dryad whose tree is recovering from illness. |
| 5 | A Humanoid ignorant of the swanmay's true nature. |
| 6 | A handful of seeds bearing primal power. |
^1-the-swanmay-is-devoted-to-protecting

```statblock
"name": "Swanmay (FRAiF)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "14"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "15"
"speed": "30 ft., fly 40 ft. (swan form only)"
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Nature"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+5"
"gear":
  - "longbow"
  - "scimitar"
"senses": "passive Perception 15"
"languages": "Common, Sylvan"
"cr": "3"
"traits":
  - "desc": "The swanmay doesn't provoke an Opportunity Attack action when it flies\
      \ out of an enemy's reach."
    "name": "Flyby (Swan Form Only)"
"actions":
  - "desc": "The swanmay makes two attacks, using Beak, Longbow, or Scimitar in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing\
      \ damage. If the target is a Large or smaller creature, it has the Prone condition."
    "name": "Beak (Swan Form Only)"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing\
      \ damage."
    "name": "Scimitar (Humanoid Form Only)"
  - "desc": "*Ranged Attack Roll:* +6, range 150/600 ft. *Hit:* 13 (2d8 + 4) Piercing\
      \ damage."
    "name": "Longbow (Humanoid Form Only)"
  - "desc": "The swanmay casts one of the following spells, requiring no Somatic or\
      \ Material components and using Wisdom as the spellcasting ability (spell save\
      \ DC 13):\n\n**At will:** Druidcraft, Speak with Animals (swan form only)\n\n\
      **1/day each:** Animal Friendship, Beast Sense, Spike Growth"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The swanmay shape-shifts into a Small swan, or it returns to its true\
      \ humanoid form. Its game statistics are the same in each form, except where\
      \ noted. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/fey/token/swanmay-fraif.webp"
```
^statblock

## Environment

forest