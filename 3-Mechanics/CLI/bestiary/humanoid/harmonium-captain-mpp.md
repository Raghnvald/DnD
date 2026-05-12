---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Harmonium Captain"
---
# [Harmonium Captain](3-Mechanics/CLI/bestiary/humanoid/harmonium-captain-mpp.md)
*Source: Morte's Planar Parade p. 58*  

Harmonium captains lead peacekeeper patrols throughout Sigil. They bolster their subordinates in battle and bring the authority of the Harmonium crashing down on suspects with their commands.

```statblock
"name": "Harmonium Captain (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "20"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 16"
"languages": "Common plus one more language"
"cr": "8"
"traits":
  - "desc": "Allies within 30 feet of the captain are immune to the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) conditions.\
      \ This aura is suppressed while the captain has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Aura of Command"
"actions":
  - "desc": "The captain makes three Harmonium Blade attacks. The captain can also\
      \ use Dictate if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) piercing damage plus 10 (3d6) lightning damage."
    "name": "Harmonium Blade"
  - "desc": "The captain verbally commands up to three creatures it can see within\
      \ 60 feet of itself. This magical command must be to undertake an action or\
      \ to refrain from taking actions (for example, \"Throw down your weapons\").\n\
      \nA target must succeed on a DC 14 Wisdom saving throw or have the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition for 1 minute, during which time it follows the captain's command.\
      \ The effect ends early if the target takes damage or if it successfully completes\
      \ the command. A target automatically succeeds on its saving throw if the command\
      \ is directly harmful to itself, such as commanding it to walk into fire.\n\n\
      A creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a successful save."
    "name": "Dictate (Recharge 5-6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/harmonium-captain-mpp.webp"
```
^statblock