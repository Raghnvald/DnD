---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/egw
  - Monster/HG/5
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Shadowghast
---
# [Shadowghast](3-Mechanics\CLI\bestiary\undead/shadowghast-egw.md)
*Source: Explorer's Guide to Wildemount p. 299*  

A shadowghast is an undead assassin. Leaping out from the shadows and trailing tendrils of darkness, it closes in on its prey with nary a sound, then tears into a victim with its paralyzing claws and furious bite.

```statblock
"name": "Shadowghast (EGW)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"modifier": !!int "5"
"stats":
  - !!int "14"
  - !!int "20"
  - !!int "12"
  - !!int "12"
  - !!int "11"
  - !!int "8"
"speed": "35 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "5"
"traits":
  - "desc": "Any creature that starts its turn within 5 feet of the shadowghast must\
      \ succeed on a DC 12 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of its next turn. On a successful saving throw, the creature\
      \ is immune to this Stench for 24 hours."
    "name": "Stench"
  - "desc": "While in dim light or darkness, the shadowghast can take the Hide action\
      \ as a bonus action."
    "name": "Shadow Stealth"
"actions":
  - "desc": "The shadowghast makes two attacks: one with its bite and one with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:* 11\
      \ (2d8 + 2) slashing damage plus 5 (1d10) necrotic damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage. If the target is a creature other than an undead,\
      \ it must succeed on a DC 12 Constitution saving throw or be [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Claws"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/undead/token/shadowghast-egw.webp"
```
^statblock