---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/6
- Monster/Größe/Groß
- Monster/Typ/Riese
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orzhov Giant
---
# [Orzhov Giant](3-Mechanics\CLI\bestiary\giant/orzhov-giant-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 202*  

A few giants join the ranks of the Orzhov Syndicate and serve as guards, executioners, and thugs-the muscle of the guild. The presence of Orzhov giants in markets and streets serves as an effective reminder for business owners to keep their payments up to date.

## Giants

Giants use their tremendous size and strength to advance the cause of no less than four guilds. In the Boros Legion and the Orzhov Syndicate, they are cunning soldiers. The giants of the Cult of Rakdos and the Gruul Clans are no less effective but lack discipline.

```statblock
"name": "Orzhov Giant (GGR)"
"size": "Large"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "13"
  - !!int "21"
  - !!int "12"
  - !!int "13"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Giant"
"cr": "6"
"traits":
  - "desc": "As a bonus action, the giant can target a creature it can see within\
      \ 30 feet of it and make that creature its focus. The target remains the giant's\
      \ focus for 1 minute, or until either the target or the giant drops to 0 hit\
      \ points. When the giant makes an attack roll against its focus, it adds a d4\
      \ to its attack roll. If the giant attacks a different target while it has a\
      \ focus, it subtracts a d4 from its attack roll."
    "name": "Focus"
"actions":
  - "desc": "The giant makes two greataxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 25\
      \ (3d12 + 6) slashing damage. If the Orzhov giant scores a critical hit, it\
      \ rolls the damage dice three times, instead of twice."
    "name": "Greataxe"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/giant/token/orzhov-giant-ggr.webp"
```
^statblock