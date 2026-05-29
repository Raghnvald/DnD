---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Warrior
linter-yaml-title-alias: Warrior
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/
  - Monster/Typ/Humanoid
  - Quelle/5e/slw
aliases:
  - Warrior
---
# [Warrior](3-Mechanics\CLI\bestiary\humanoid/warrior-slw.md)
*Source: Storm Lord's Wrath*  

```statblock
"name": "Warrior (SLW)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "plate armor, shield"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The warrior has advantage on initiative rolls."
    "name": "Battle Readiness"
  - "desc": "The warrior's attack rolls score a critical hit on a roll of 19 or 20\
      \ on the d20."
    "name": "Improved Critical"
  - "desc": "The warrior has one of the following traits of your choice:\n\n- **Attacker.**\
      \ The warrior gains a +2 bonus to attack rolls.  \n- **Defender.** The warrior\
      \ gains the Protection reaction below.  "
    "name": "Martial Role"
"actions":
  - "desc": "The warrior can attack twice, instead of once, whenever it takes the\
      \ Attack action on its turn."
    "name": "Extra Attack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"reactions":
  - "desc": "The warrior imposes disadvantage on the attack roll of a creature within\
      \ 5 feet of it whose target isn't the warrior. The warrior must be able to see\
      \ the attacker."
    "name": "Protection (Defender Only)"
"source":
  - "SLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/warrior-slw.webp"
```
^statblock