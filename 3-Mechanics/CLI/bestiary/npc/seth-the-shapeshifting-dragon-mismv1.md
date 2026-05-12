---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mismv1
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Seth the Shapeshifting Dragon"
---
# [Seth the Shapeshifting Dragon](3-Mechanics/CLI/bestiary/npc/seth-the-shapeshifting-dragon-mismv1.md)
*Source: Misplaced Monsters: Volume 1 p. 12*  

> [!note]
> Created by Reese P.

Seth the Shapeshifting Dragon is a vegetarian who likes to hide in the brush near waterfalls, rivers, and lakes. Invisible while immersed in water, Seth is capable of great bursts of speed, and his breath weapon is a blast of frigid water.

```statblock
"name": "Seth the Shapeshifting Dragon (MisMV1)"
"size": "Medium"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "17"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "7"
"stats":
  - !!int "16"
  - !!int "25"
  - !!int "19"
  - !!int "13"
  - !!int "15"
  - !!int "14"
"speed": "50 ft., swim 50 ft."
"saves":
  - "strength": !!int "7"
  - "dexterity": !!int "11"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+11"
"damage_resistances": "cold, fire"
"damage_immunities": "poison"
"condition_immunities": "[grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 16"
"languages": "Aquan, Common, Draconic"
"cr": "10"
"traits":
  - "desc": "Seth can breathe air and water."
    "name": "Amphibious"
  - "desc": "Seth has the [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ condition while fully immersed in water."
    "name": "Invisible in Water"
"actions":
  - "desc": "Seth makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (1d6 + 7) piercing damage plus 9 (2d8) cold damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 14 (2d6 + 7) slashing damage."
    "name": "Claw"
  - "desc": "Seth exhales a torrent of frigid water in a 30-foot cone. Each creature\
      \ in that area must make a DC 16 Constitution saving throw. On a failed save,\
      \ the creature takes 36 (8d8) cold damage and has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition until the end of its next turn. On a successful save, the creature\
      \ takes half as much damage only."
    "name": "Riptide Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Seth magically transforms into a Small Humanoid or a Beast that is Tiny\
      \ or Small, while retaining his game statistics (other than his size). This\
      \ transformation ends if Seth is reduced to 0 hit points or uses another bonus\
      \ action to end it."
    "name": "Change Shape"
  - "desc": "Seth's speed is doubled for as long as he maintains [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). While his speed is increased in this way, all attack rolls against\
      \ him are made with disadvantage, and he becomes partially incorporeal, allowing\
      \ him to move through creatures and objects as if they were difficult terrain.\
      \ Seth takes 5 (1d10) force damage if he ends his turn inside an object."
    "name": "Superspeed (2/Day)"
"source":
  - "MisMV1"
"image": "3-Mechanics/CLI/bestiary/npc/token/seth-the-shapeshifting-dragon-mismv1.webp"
```
^statblock