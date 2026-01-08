---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Spy
---
# [Spy](3-Mechanics\CLI\bestiary\humanoid/spy.md)
*Source: Monster Manual p. 349, Explorer's Guide to Wildemount. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Rulers, nobles, merchants, guildmasters, and other wealthy individuals use spies to gain the upper hand in a world of cutthroat politics. A spy is trained to secretly gather information. Loyal spies would rather die than divulge information that could compromise them or their employers.

```statblock
"name": "Spy"
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
  - "name": "Deception"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+4"
  - "name": "Investigation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Persuasion"
    "desc": "+5"
  - "name": "Sleight of Hand"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+4"
"senses": "passive Perception 16"
"languages": "any two languages"
"cr": "1"
"traits":
  - "desc": "On each of its turns, the spy can use a bonus action to take the Dash,\
      \ Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "The spy deals an extra 7 (2d6) damage when it hits a target with a weapon\
      \ attack and has advantage on the attack roll, or when the target is within\
      \ 5 feet of an ally of the spy that isn't incapacitated and the spy doesn't\
      \ have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
"actions":
  - "desc": "The spy makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow"
"source":
  - "MM"
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/spy.webp"
```
^statblock

## Environment

urban