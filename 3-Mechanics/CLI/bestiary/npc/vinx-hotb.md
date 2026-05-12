---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vinx"
---
# [Vinx](3-Mechanics/CLI/bestiary/npc/vinx-hotb.md)
*Source: Heroes of the Borderlands p. 12*  

This itinerant explorer knows the caves around the Keep on the Borderlands better than anyone else. Vinx frequently delves these caves in search of treasure.

Recently, Vinx got caught in a bind while pursuing a stolen family heirloom. When she gets loose, those goblins won't know what hit them!

```statblock
"name": "Vinx (HotB)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "leather armor"
  - "shortsword"
  - "sling"
"senses": "passive Perception 15"
"languages": "Common, Dwarvish"
"cr": "1/4"
"actions":
  - "desc": "Vinx makes two attacks, using Shortsword and Sling in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing\
      \ damage."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +4, range 30/120 ft. *Hit:* 4 (1d4 + 2) Bludgeoning\
      \ damage."
    "name": "Sling"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/npc/token/vinx-hotb.webp"
```
^statblock