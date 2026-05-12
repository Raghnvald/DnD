---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drevin"
---
# [Drevin](3-Mechanics/CLI/bestiary/npc/drevin-tftyp.md)
*Source: Tales from the Yawning Portal p. 126*  

```statblock
"name": "Drevin (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "poison"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 16"
"languages": "any two languages, Halfling"
"cr": "1"
"traits":
  - "desc": "On each of its turns, Drevin can use a bonus action to take the [Dash](3-Mechanics/CLI/rules/actions.md#Dash),\
      \ [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage), or [Hide](3-Mechanics/CLI/rules/actions.md#Hide)\
      \ action."
    "name": "Cunning Action"
  - "desc": "Drevin deals an extra 7 (2d6) damage when it hits a target with a weapon\
      \ attack and has advantage on the attack roll, or when the target is within\
      \ 5 feet of an ally of Drevin that isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and Drevin doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
  - "desc": "Drevin"
    "name": "Halfling Nimbleness"
  - "desc": "Drevin"
    "name": "Brave"
  - "desc": "Drevin"
    "name": "Stout Resilience"
"actions":
  - "desc": "Drevin makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/npc/token/drevin-tftyp.webp"
```
^statblock