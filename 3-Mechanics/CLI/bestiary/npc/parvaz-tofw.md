---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Parvaz"
---
# [Parvaz](3-Mechanics/CLI/bestiary/npc/parvaz-tofw.md)
*Source: Turn of Fortune's Wheel p. 50*  

```statblock
"name": "Parvaz (ToFW)"
"size": "Large"
"type": "beast"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "17"
  - !!int "13"
  - !!int "16"
  - !!int "14"
  - !!int "14"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": "Common"
"cr": "1"
"traits":
  - "desc": "Parvaz has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "Parvaz makes two attacks: one with its beak and one with its talons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Talons"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/parvaz-tofw.webp"
```
^statblock