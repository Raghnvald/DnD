---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Android Diver"
---
# [Android Diver](3-Mechanics/CLI/bestiary/construct/android-diver-qftis.md)
*Source: Quests from the Infinite Staircase p. 194*  

```statblock
"name": "Android Diver (QftIS)"
"size": "Medium"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "10"
"speed": "30 ft., swim 30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "acid, fire"
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 17"
"languages": "Common plus the languages spoken by its creator"
"cr": "5"
"traits":
  - "desc": "When the android takes lightning damage, it must succeed on a DC 10 Constitution\
      \ saving throw or have the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition until the start of its next turn."
    "name": "Lightning Overload"
"actions":
  - "desc": "The android makes two Force Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 40/120\
      \ ft., one target. *Hit:* 15 (2d10 + 4) force damage. If the target is a Medium\
      \ or smaller creature, it must succeed on a DC 15 Strength saving throw or have\
      \ the [prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition."
    "name": "Force Strike"
"source":
  - "QftIS"
```
^statblock