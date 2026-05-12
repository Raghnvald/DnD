---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Young Purple Worm"
---
# [Young Purple Worm](3-Mechanics/CLI/bestiary/monstrosity/young-purple-worm-pota.md)
*Source: Princes of the Apocalypse p. 113*  

```statblock
"name": "Young Purple Worm (PotA)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "184"
"hit_dice": "15d20 + 90"
"modifier": !!int "-2"
"stats":
  - !!int "28"
  - !!int "7"
  - !!int "22"
  - !!int "1"
  - !!int "8"
  - !!int "4"
"speed": "50 ft., burrow 30 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "4"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., tremorsense\
  \ 60 ft., passive Perception 9"
"languages": ""
"cr": "13"
"traits":
  - "desc": "The worm can burrow through solid rock at half its burrow speed and leaves\
      \ a 10-foot-diameter tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The worm makes two attacks: one with its bite and one with its stinger."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 19 Dexterity saving throw or be swallowed by the worm.\
      \ A swallowed creature is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the worm, and it takes 21\
      \ (6d6) acid damage at the start of each of the worm's turns.\n\nIf the worm\
      \ takes 30 damage or more on a single turn from a creature inside it, the worm\
      \ must succeed on a DC 21 Constitution saving throw at the end of that turn\
      \ or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the worm. If the worm dies, a swallowed creature\
      \ is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 20 feet of movement, exiting\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one creature. *Hit:*\
      \ 19 (3d6 + 9) piercing damage, and the target must make a DC 19 Constitution\
      \ saving throw, taking 42 (12d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Tail Stinger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/young-purple-worm-pota.webp"
```
^statblock