---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Princess Serissa
Status: WIP
linter-yaml-title-alias: Princess Serissa
tags:
  - Monster/Größe/Riesig
  - Monster/HG/13
  - Monster/Typ/Riese
  - Quelle/5e/skt
aliases:
  - Princess Serissa
---
# [Princess Serissa](3-Mechanics\CLI\bestiary\npc/princess-serissa-skt.md)
*Source: Storm King's Thunder p. 209*  

```statblock
"name": "Princess Serissa (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Good"
"ac": !!int "14"
"ac_class": "hide armor"
"hp": !!int "200"
"hit_dice": "20d12 + 100"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "18"
"speed": "50 ft., swim 50 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "10"
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "Athletics"
    "desc": "+14"
  - "name": "History"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+9"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
  - "desc": "Serissa's innate spellcasting ability is Charisma (spell save DC 17).\
      \ It can innately cast the following spells, requiring no material components:\n\
      \n**At will:** detect magic, feather fall, levitate, light\n\n**3/day each:**\
      \ control weather, water breathing"
    "name": "Innate Spellcasting"
  - "desc": "Serissa can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Serissa makes two maul attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:* 30\
      \ (6d6 + 9) bludgeoning damage."
    "name": "Maul"
  - "desc": "*Ranged Weapon Attack:* +14 to hit, range 60/240 ft., one target. *Hit:*\
      \ 35 (4d12 + 9) bludgeoning damage."
    "name": "Rock"
  - "desc": "Serissa hurls a magical lightning bolt at a point it can see within 500\
      \ feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
      \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Lightning Strike (Recharge 5-6)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/princess-serissa-skt.webp"
```
^statblock