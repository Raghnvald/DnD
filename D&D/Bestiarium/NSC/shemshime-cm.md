---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/cm
  - Monster/HG/4
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Shemshime
---
# [Shemshime](3-Mechanics\CLI\bestiary\npc/shemshime-cm.md)
*Source: Candlekeep Mysteries p. 69*  

```statblock
"name": "Shemshime (CM)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "31"
"hit_dice": "7d8"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "10"
  - !!int "17"
  - !!int "14"
  - !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+7"
"damage_resistances": "acid, bludgeoning, fire, lightning, piercing, slashing, thunder"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone, restrained"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "telepathy 60 ft."
"cr": "4"
"traits":
  - "desc": "If damage reduces Shemshime to 0 hit points, Shemshime instead drops\
      \ to 1 hit point unless the damage is the result of Shemshime being crushed\
      \ by an object weighing at least 1,000 pounds."
    "name": "Crushing End"
  - "desc": "Shemshime can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Spell Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 17 (4d6\
      \ + 3) psychic damage."
    "name": "Maddening Touch"
  - "desc": "Shemshime chooses up to two creatures it can see within 60 feet of it.\
      \ Each target must succeed on a DC 13 Wisdom saving throw, or that target takes\
      \ 7 (1d8 + 3) psychic damage and must use its reaction to make a melee weapon\
      \ attack against one creature it can reach (Shemshime's choice) that Shemshime\
      \ can see."
    "name": "Whispers of Violence"
  - "desc": "Shemshime targets one creature it can see within 30 feet of it. The creature\
      \ must make a DC 13 Wisdom saving throw. On a failed save, it takes 21 (4d8\
      \ + 3) psychic damage and is stunned until the end of its next turn. On a successful\
      \ save, it takes half as much damage and isn't stunned."
    "name": "Howling Babble (Recharge 6)"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/shemshime-cm.webp"
```
^statblock