---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Curate"
---
# [Curate](3-Mechanics/CLI/bestiary/humanoid/curate-hotb.md)
*Source: Heroes of the Borderlands p. 15*  

A curate earns a special connection to the divine through service to shrines and temples. This devotion endows these spiritual leaders with the power to heal injuries, repel evil, and raise the dead.

```statblock
"name": "Curate (HotB)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Good"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "18"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "7"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 14"
"languages": "Celestial, Common"
"cr": "6"
"traits":
  - "desc": "The curate has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "In a ritual that takes 8 hours, the curate touches a creature that has\
      \ died within the past 7 days. That creature returns to life with 1 <span title=\"\
      Player's Handbook (2024)\">Hit Point</span>. The curate can't revive a creature\
      \ that died of old age."
    "name": "Raise the Dead (1/Day)"
"actions":
  - "desc": "The curate makes three Celestial Radiance attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 60 ft. *Hit:*\
      \ 18 (4d8) Radiant damage."
    "name": "Celestial Radiance"
  - "desc": "The curate touches another creature. That creature regains 13 (2d8 +\
      \ 4) <span title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Healer's Touch (2/Day)"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/curate-hotb.webp"
```
^statblock