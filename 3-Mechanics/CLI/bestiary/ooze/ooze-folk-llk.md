---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/llk
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ooze-Folk"
---
# [Ooze-Folk](3-Mechanics/CLI/bestiary/ooze/ooze-folk-llk.md)
*Source: Lost Laboratory of Kwalish p. 46*  

```statblock
"name": "Ooze-Folk (LLK)"
"size": "Medium"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "10"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "2d8 + 10"
"modifier": !!int "-4"
"stats":
  - !!int "14"
  - !!int "3"
  - !!int "20"
  - !!int "1"
  - !!int "6"
  - !!int "1"
"speed": "30 ft."
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "Even when an ooze-folk is in plain sight, it takes a DC 12 Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check to spot an ooze-folk that has neither moved nor attacked. A creature\
      \ that tries to enter the ooze-folk's space while unaware of the ooze-folk is\
      \ [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised) by the ooze-folk."
    "name": "Transparent"
  - "desc": "For each 5 damage it takes, the ooze-folk's walking speed is reduced\
      \ by 5 feet."
    "name": "Fragile Bones"
"actions":
  - "desc": "The ooze folk makes one glass longsword attack and one pseudopod attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 6 (1d8 + 2) slashing damage. If a 1 is rolled on an attack roll with a glass\
      \ longsword, it shatters and can no longer be used."
    "name": "Glass Longsword"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d6 + 2) acid damage. "
    "name": "Pseudopod"
"source":
  - "LLK"
"image": "3-Mechanics/CLI/bestiary/ooze/token/ooze-folk-llk.webp"
```
^statblock