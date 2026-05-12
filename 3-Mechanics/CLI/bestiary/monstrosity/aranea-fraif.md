---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aranea"
---
# [Aranea](3-Mechanics/CLI/bestiary/monstrosity/aranea-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 250*  

## Aranea

*Secretive Crafter and Trader*

Araneas are reclusive shape-shifters. An aranea's natural form resembles a bulky, humpbacked spider with two short arms beneath its head. An aranea can shape-shift into a humanoid form or into a multi-armed humanoid-spider hybrid. Araneas live in insular communities, such as the Spider Swamp in Calimshan, where they create beautiful objects that express their artistry and which are sometimes traded to other communities. Most araneas prefer to avoid combat, befuddling their foes long enough to skitter to safety.

Roll or choose a result from the Aranea Crafts table as inspiration for an aranea's crafting talent.

| dice: 1d6 | The Aranea Is Skilled at Crafting... |
|-----------|--------------------------------------|
| 1 | Exceptionally comfortable bedding. |
| 2 | Furniture made of wood and canvas. |
| 3 | Poisons that are soporific rather than lethal. |
| 4 | Poultices and unguents from medicinal herbs. |
| 5 | Silks with intricate web patterns. |
| 6 | Stories with cleverly concealed morals. |
^1-the-aranea-is-skilled-at-crafting

```statblock
"name": "Aranea (FRAiF)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "17"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "15"
"speed": "30 ft., climb 30 ft. (spider or hybrid form only)"
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+5"
"gear":
  - "sling"
"senses": "Darkvision 60 ft., passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The aranea can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb (Hybrid or Spider Form Only)"
  - "desc": "The aranea ignores movement restrictions caused by webs, and it knows\
      \ the location of any other creature in contact with the same web."
    "name": "Web Walker"
"actions":
  - "desc": "The aranea makes two attacks, using Bite, Slam, or Sling in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing\
      \ damage plus 2 (1d4) Poison damage."
    "name": "Bite (Hybrid or Spider Form Only)"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning\
      \ damage."
    "name": "Slam"
  - "desc": "*Ranged Attack Roll:* +5, range 30/120 ft. *Hit:* 8 (2d4 + 3) Bludgeoning\
      \ damage."
    "name": "Sling (Humanoid or Hybrid Form Only)"
  - "desc": "The aranea casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 12):\n\n**At\
      \ will:** Friends, Silent Image\n\n**1/day:** Hold Person"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The aranea shape-shifts into a humanoid form, into a humanoid-spider\
      \ hybrid form, or back into its true spider form. Its game statistics are the\
      \ same in each form, except where noted. Any equipment it is wearing or carrying\
      \ isn't transformed."
    "name": "Shape-Shift"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/aranea-fraif.webp"
```
^statblock

## Environment

forest, swamp