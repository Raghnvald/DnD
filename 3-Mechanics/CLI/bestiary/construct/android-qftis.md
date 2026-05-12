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
- "Android"
---
# [Android](3-Mechanics/CLI/bestiary/construct/android-qftis.md)
*Source: Quests from the Infinite Staircase p. 194*  

Androids are synthetic humanoids built to assist their creators with highly specialized tasks. They are designed to be compliant and typically have friendly demeanors.

Every android has one or more upgrades to help it excel at its intended functions, but all androids are capable of defending themselves with concentrated bolts of force up close or from a distance.

Despite an android's sophisticated construction, electrical surges can temporarily disrupt its finely tuned components. Similarly, damage to its core processing functions or long stretches of isolation can wear down an android's critical faculties, causing it to behave erratically.

```statblock
"name": "Android (QftIS)"
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
"speed": "30 ft., fly 30 ft. (hover; aerialist only), swim 30 ft. (diver only)"
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
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (sentry\
  \ only), [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 17"
"languages": "Common plus the languages spoken by its creator"
"cr": "5"
"traits":
  - "desc": "When the android is created, it gains one of six possible designs suited\
      \ for its role (choose or roll a d6): 1, aerialist; 2, diplomat; 3, diver;\
      \ 4, duelist; 5, medic; 6, sentry. This design determines certain traits in\
      \ this stat block."
    "name": "Design Specialization"
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
  - "desc": "The android casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability:\n\n**2/day\
      \ each:** [Cure Wounds](3-Mechanics/CLI/spells/cure-wounds.md) (as a 3rd-level\
      \ spell; medic only), [Identify](3-Mechanics/CLI/spells/identify.md), [Tongues](3-Mechanics/CLI/spells/tongues.md)\
      \ (diplomat only)"
    "name": "Spellcasting (Diplomat and Medic Only)"
"reactions":
  - "desc": "The android adds 3 to its AC against one melee attack roll that would\
      \ hit it. To do so, the android must see the attacker."
    "name": "Parry (Duelist Only)"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/construct/token/android-qftis.webp"
```
^statblock