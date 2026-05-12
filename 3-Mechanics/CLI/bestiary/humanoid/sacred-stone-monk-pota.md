---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sacred Stone Monk"
---
# [Sacred Stone Monk](3-Mechanics/CLI/bestiary/humanoid/sacred-stone-monk-pota.md)
*Source: Princes of the Apocalypse p. 196*  

Sacred Stone monks are followers of a martial philosophy that seeks to emulate the strength of rock and stone. They don gargoyle masks and use a finely honed sense of touch to measure their surroundings by contact with the ground. They avoid speaking, or extraneous thought for that matter. They live only to test themselves with deprivation and to punish those who doubt the strength of elemental earth.

```statblock
"name": "Sacred Stone Monk (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "9"
"speed": "40 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "tremorsense 10 ft., passive Perception 14"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "While the monk is wearing no armor and wielding no shield, its AC includes\
      \ its Wisdom modifier."
    "name": "Unarmored Defense"
  - "desc": "While the monk is wearing no armor and wielding no shield, its walking\
      \ speed increases by 10 feet (included in its speed)."
    "name": "Unarmored Movement"
"actions":
  - "desc": "The monk makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "The monk adds 2 to its AC against one melee or ranged weapon attack that\
      \ would hit it. To do so, the monk must see the attacker."
    "name": "Parry"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/sacred-stone-monk-pota.webp"
```
^statblock