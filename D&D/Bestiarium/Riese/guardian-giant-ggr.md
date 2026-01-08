---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/8
- Monster/Größe/Riesig
- Monster/Typ/Riese
statblock: inline
statblock-link: "#^statblock"
aliases:
- Guardian Giant
---
# [Guardian Giant](3-Mechanics\CLI\bestiary\giant/guardian-giant-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 201*  

Most of the giants in the Boros Legion come from a single clan, the Skorskal, that has long been at odds with the Gruul Clans. These giants are guards and gatekeepers, well represented in the Sunhome Guard, as well as powerful muscle supporting Boros missions.

Giants of the Skorskal clan are often assigned to protect Boros garrisons and forts throughout Ravnica. They are excellent sentinels, keen-eyed and vigilant, and serve as living walls to protect smaller soldiers fighting alongside them. Skorskal giants look much like enormous humans with huge muscles and comparatively small heads.

## Giants

Giants use their tremendous size and strength to advance the cause of no less than four guilds. In the Boros Legion and the Orzhov Syndicate, they are cunning soldiers. The giants of the Cult of Rakdos and the Gruul Clans are no less effective but lack discipline.

```statblock
"name": "Guardian Giant (GGR)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Neutral"
"ac": !!int "19"
"ac_class": "half plate armor, shield"
"hp": !!int "137"
"hit_dice": "11d12 + 66"
"modifier": !!int "3"
"stats":
  - !!int "24"
  - !!int "17"
  - !!int "22"
  - !!int "10"
  - !!int "18"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+10"
"senses": "passive Perception 20"
"languages": "Common, Giant"
"cr": "8"
"traits":
  - "desc": "The giant can't be surprised."
    "name": "Vigilant"
"actions":
  - "desc": "The giant makes three spear attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +10 to hit, reach 10 ft. or range 60/240\
      \ ft., one target. *Hit:* 17 (3d6 + 7) piercing damage, or 20 (3d8 + 7) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"reactions":
  - "desc": "When an attacker the giant can see makes an attack roll against a creature\
      \ within 10 feet of the giant, the giant can impose disadvantage on the attack\
      \ roll."
    "name": "Protection"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/giant/token/guardian-giant-ggr.webp"
```
^statblock