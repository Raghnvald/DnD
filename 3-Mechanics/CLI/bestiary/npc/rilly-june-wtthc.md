---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rilly June"
---
# [Rilly June](3-Mechanics/CLI/bestiary/npc/rilly-june-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Rilly June is a hardworking halfling farmer who's used to tackling tough jobs herself. When her grandfather's farm started to suffer from a mysterious blight, she was determined to investigate the cause. Rilly June is stern and tough, but she's got a soft spot for animals and the other people who work her family's land or look out for the common folk.

```statblock
"name": "Rilly June (WttHC)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d6"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "13"
  - !!int "10"
  - !!int "13"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common, Halfling"
"cr": "1/2"
"actions":
  - "desc": "Rilly June makes two Hayfork attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing\
      \ damage."
    "name": "Hayfork"
  - "desc": "*Wisdom Saving Throw:* DC 11, one creature Rilly June can see within\
      \ 60 feet. *Failure:* 10 (3d6) Psychic damage, and the target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the end of its next turn. *Success:* Half damage only."
    "name": "G'wan, Git! (1/Day)"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/npc/token/rilly-june-wtthc.webp"
```
^statblock