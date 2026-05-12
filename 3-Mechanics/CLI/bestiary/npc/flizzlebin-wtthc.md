---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flizzlebin"
---
# [Flizzlebin](3-Mechanics/CLI/bestiary/npc/flizzlebin-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

A trickster with a penchant for games, Flizzlebin tempts novice adventurers into dungeons to test their skills. The so-called "Vanishing Gnome's" favorite game involves hiding within dangerous dungeons and rewarding those who find him with priceless treasures.

```statblock
"name": "Flizzlebin (WttHC)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Good"
"ac": !!int "12"
"hp": !!int "38"
"hit_dice": "7d6 + 14"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "15"
  - !!int "16"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Dwarvish, Gnomish"
"cr": "1"
"traits":
  - "desc": "Flizzlebin has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Flizzlebin can project his voice from anywhere within 1 mile of himself."
    "name": "Ventriloquist"
"actions":
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 60 ft. *Hit:*\
      \ 10 (2d6 + 3) Radiant damage."
    "name": "Dazzling Confetti"
  - "desc": "Flizzlebin has the [Invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ condition for 10 minutes. This effect ends early immediately after Flizzlebin\
      \ makes an attack roll, deals damage, or has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, or if his hat is removed."
    "name": "Vanishing Trick (3/Day)"
"reactions":
  - "desc": "Trigger: Flizzlebin is hit by an attack roll. _Response:_ Flizzlebin\
      \ adds 2 to his AC against that attack, possibly causing it to miss."
    "name": "Distracting Glitter"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/npc/token/flizzlebin-wtthc.webp"
```
^statblock