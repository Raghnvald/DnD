---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grisdelfawr"
---
# [Grisdelfawr](3-Mechanics/CLI/bestiary/npc/grisdelfawr-qftis.md)
*Source: Quests from the Infinite Staircase p. 70*  

```statblock
"name": "Grisdelfawr (QftIS)"
"size": "Large"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "14"
  - !!int "11"
  - !!int "19"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "9"
  - "wisdom": !!int "4"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "fire"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "10"
"actions":
  - "desc": "Grisdelfawr makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (2d10 + 6) piercing damage plus 3 (1d6) fire damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage."
    "name": "Claw"
  - "desc": "Grisdelfawr exhales fire in a 30-foot cone. Each creature in that area\
      \ must make a DC 17 Dexterity saving throw, taking 56 (16d6) fire damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/grisdelfawr-qftis.webp"
```
^statblock