---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gray Ooze Glob"
---
# [Gray Ooze Glob](3-Mechanics/CLI/bestiary/ooze/gray-ooze-glob-hotb.md)
*Source: Heroes of the Borderlands p. 18*  

Gray oozes are predatory, corrosive slimes that blend in with stony surroundings. Unpredictable magic and other chaotic forces can cause these oozes to split, creating smaller, unstable globs.

```statblock
"name": "Gray Ooze Glob (HotB)"
"size": "Small"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "19"
"hit_dice": "3d6 + 9"
"modifier": !!int "-2"
"stats":
  - !!int "12"
  - !!int "6"
  - !!int "16"
  - !!int "1"
  - !!int "6"
  - !!int "2"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"damage_resistances": "acid, cold, fire"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The ooze can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Amorphous"
  - "desc": "Whenever a creature hits the ooze with a melee attack, that creature\
      \ takes 2 Acid damage."
    "name": "Corrosive Form"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 10 (2d8 + 1) Acid damage."
    "name": "Pseudopod"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/ooze/token/gray-ooze-glob-hotb.webp"
```
^statblock