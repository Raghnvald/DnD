---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/sdw
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warrior"
---
# [Warrior](3-Mechanics/CLI/bestiary/humanoid/warrior-sdw.md)
*Source: Sleeping Dragon's Wake*  

```statblock
"name": "Warrior (SDW)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate](3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow-xphb.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "passive Perception 15"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The warrior has advantage on initiative rolls."
    "name": "Battle Readiness"
  - "desc": "The warrior's attack rolls score a critical hit on a roll of 19 or 20\
      \ on the d20."
    "name": "Improved Critical"
  - "desc": "The warrior can reroll a saving throw that it fails, but it must use\
      \ the new result."
    "name": "Indomitable (1/Day)"
  - "desc": "The warrior has one of the following traits of your choice:\n\n- **Attacker.**\
      \ The warrior gains a +2 bonus to attack rolls.  \n- **Defender.** The warrior\
      \ gains the Protection reaction below.  "
    "name": "Martial Role"
  - "desc": "The warrior can use a bonus action on its turn to regain hit points equal\
      \ to 1d10 + its level."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The warrior can attack twice, instead of once, whenever it takes the\
      \ attack action on its turn."
    "name": "Extra Attack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"reactions":
  - "desc": "When a creature the warrior can see attacks a target other than the warrior\
      \ that is within 5 feet of the warrior, the warrior can use their reaction to\
      \ impose disadvantage on the attack roll. The warrior must be wielding a shield."
    "name": "Protection (Defender Only)"
"source":
  - "SDW"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/warrior-sdw.webp"
```
^statblock