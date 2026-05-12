---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Transcendent Order Instinct"
---
# [Transcendent Order Instinct](3-Mechanics/CLI/bestiary/humanoid/transcendent-order-instinct-mpp.md)
*Source: Morte's Planar Parade p. 62*  

Elite martial artists, instincts have learned to fight unburdened by thought, deflecting the blows of their enemies in rapid succession.

```statblock
"name": "Transcendent Order Instinct (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "Unarmored Defense"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "3"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+3"
"senses": "passive Perception 15"
"languages": "Common plus one more language"
"cr": "3"
"traits":
  - "desc": "While the instinct is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The instinct makes three Unarmed Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "In response to being hit by a melee attack roll, the instinct partially\
      \ deflects the blow. The damage the instinct takes from the attack is reduced\
      \ by 1d6."
    "name": "Deflect Blow"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/transcendent-order-instinct-mpp.webp"
```
^statblock