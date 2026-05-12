---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Uma"
---
# [Uma](3-Mechanics/CLI/bestiary/npc/uma-qftis.md)
*Source: Quests from the Infinite Staircase p. 120*  

```statblock
"name": "Uma (QftIS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow.md)"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
  - "desc": "Uma has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
"actions":
  - "desc": "Uma makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:*\
      \ 5 (1d10) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "For 1 minute, Uma can utter a special command or warning whenever a nonhostile\
      \ creature that it can see within 30 feet of it makes an attack roll or a saving\
      \ throw. The creature can add a d4 to its roll provided it can hear and understand\
      \ Uma. A creature can benefit from only one Leadership die at a time. This effect\
      \ ends if Uma is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
  - "desc": "Uma adds 2 to its AC against one melee attack that would hit it. To do\
      \ so, Uma must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/uma-qftis.webp"
```
^statblock