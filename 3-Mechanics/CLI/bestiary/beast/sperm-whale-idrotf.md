---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sperm Whale"
---
# [Sperm Whale](3-Mechanics/CLI/bestiary/beast/sperm-whale-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 309*  

Sperm whales are toothed aquatic mammals that can grow to be up to 70 feet long. Their natural predators include whalers and fellow leviathans, such as dragon turtles and krakens.

```statblock
"name": "Sperm Whale (IDRotF)"
"size": "Gargantuan"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "189"
"hit_dice": "14d20 + 42"
"modifier": !!int "-1"
"stats":
  - !!int "26"
  - !!int "8"
  - !!int "17"
  - !!int "3"
  - !!int "12"
  - !!int "5"
"speed": "0 ft., swim 60 ft."
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "8"
"traits":
  - "desc": "The whale can't use its blindsight while [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)."
    "name": "Echolocation"
  - "desc": "The whale can hold its breath for 90 minutes."
    "name": "Hold Breath"
  - "desc": "The whale has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing."
    "name": "Keen Hearing"
"actions":
  - "desc": "The whale makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (3d8 + 8) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 14 Dexterity saving throw or be swallowed by the whale.\
      \ A swallowed creature has total cover against attacks and other effects outside\
      \ the whale, and it takes 3 (1d6) acid damage at the start of each of the\
      \ whale's turns. If the whale takes 30 damage or more on a single turn from\
      \ a creature inside it, the whale must succeed on a DC 16 Constitution saving\
      \ throw at the end of that turn or regurgitate all swallowed creatures, which\
      \ fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone) in a space within\
      \ 10 feet of the whale. If the whale dies, a swallowed creature can escape from\
      \ the corpse by using 20 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target. *Hit:*\
      \ 18 (3d6 + 8) bludgeoning damage, or 37 (6d6 + 16) bludgeoning damage if\
      \ the target is an object."
    "name": "Tail"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/beast/token/sperm-whale-idrotf.webp"
```
^statblock