---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Stalker of Baphomet
linter-yaml-title-alias: Stalker of Baphomet
tags:
  - Monster/Größe/Riesig
  - Monster/HG/12
  - Monster/Typ/Unhold/demon
  - Quelle/5e/bgg
aliases:
  - Stalker of Baphomet
---
# [Stalker of Baphomet](3-Mechanics\CLI\bestiary\fiend/stalker-of-baphomet-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 178*  

Demon worship is rare among stone giants; the destructive tendency of demons is the antithesis of the artistry that drives the stone giant's ordning. The Horned King, Baphomet, is an exception. Though he is a merciless hunter, the Prince of Beasts also crafts complex mazes as his hunting grounds. Stone giants can become mesmerized by the demon lord's mazes and enter his service. These giants can continue pursuing art by crafting mazes, while satiating their bloodlust by hunting in them.

Baphomet rewards his most faithful cultists with transformation into demonic stalkers. Such a giant grows an elaborate crown of six horns, and Baphomet gives the stone giant a magic glaive and the ability to call up horns of stone from the earth.

```statblock
"name": "Stalker of Baphomet (BGG)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"modifier": !!int "3"
"stats":
  - !!int "25"
  - !!int "17"
  - !!int "22"
  - !!int "13"
  - !!int "16"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+11"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 17"
"languages": "Abyssal, Giant"
"cr": "12"
"traits":
  - "desc": "The stalker can perfectly recall any path it has traveled."
    "name": "Labyrinthine Recall"
  - "desc": "The stalker has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The stalker makes two Glaive attacks or two Rock attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target. *Hit:* 18\
      \ (2d10 + 7) slashing damage plus 9 (2d8) force damage."
    "name": "Glaive"
  - "desc": "*Ranged Weapon Attack:* +11 to hit, range 60/240 ft., one target. *Hit:*\
      \ 23 (3d10 + 7) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 19 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition. After the stalker throws the rock, roll a d6; on a roll of 3 or\
      \ lower, the stalker has no more rocks to throw."
    "name": "Rock"
  - "desc": "The stalker causes the earth to churn at a point on the ground it can\
      \ see within 60 feet of itself. Six horn-shaped stones erupt in a 30-foot-radius,\
      \ 30-foot-high cylinder centered on that point and then crumble to dust.\n\n\
      Each creature in that area must make a DC 15 Dexterity saving throw. On a failed\
      \ save, a creature takes 33 (6d10) piercing damage and is pushed up to 30 feet\
      \ upward and then falls. On a successful save, a creature takes half as much\
      \ damage only."
    "name": "Erupting Horns (Recharge 5-6)"
  - "desc": "The stalker casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\n**1/day\
      \ each:** [meld into stone](/3-Mechanics/CLI/spells/meld-into-stone-xphb.md),\
      \ [stone shape](/3-Mechanics/CLI/spells/stone-shape-xphb.md), [wall of stone](/3-Mechanics/CLI/spells/wall-of-stone-xphb.md)"
    "name": "Spellcasting"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/stalker-of-baphomet-bgg.webp"
```
^statblock