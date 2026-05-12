---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jacko"
---
# [Jacko](3-Mechanics/CLI/bestiary/npc/jacko-hotb.md)
*Source: Heroes of the Borderlands p. 11*  

Jacko advertises his cloak-and-dagger services in seedy places throughout the Borderlands. For the right price, Jacko will trail, rob, rough up, or take out any mark—no questions asked.

Satisfied customers parrot his cheesy slogan: "Jacko always has your back-o."

```statblock
"name": "Jacko (HotB)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "six daggers"
  - "disguise kit"
"senses": "passive Perception 16"
"languages": "Common, Halfling"
"cr": "1"
"traits":
  - "desc": "Jacko spends 1 minute to disguise himself as a different Humanoid of\
      \ approximately his height and weight. While Jacko is disguised, a creature\
      \ that takes the Study action to inspect Jacko's appearance can make a DC 13\
      \ Intelligence (Investigation) check, discerning his disguise on a successful\
      \ check."
    "name": "Quick Disguise"
"actions":
  - "desc": "Jacko makes two Poison Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 20/60 ft.\
      \ *Hit:* 5 (1d4 + 3) Piercing damage plus 3 (1d6) Poison damage."
    "name": "Poison Dagger"
"bonus_actions":
  - "desc": "Jacko takes the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/npc/token/jacko-hotb.webp"
```
^statblock