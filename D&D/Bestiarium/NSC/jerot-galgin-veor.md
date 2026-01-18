---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/veor
  - Monster/HG/9
  - Monster/Größe/Mittelgroß
  - Monster/Typ/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Jerot Galgin
---
# [Jerot Galgin](3-Mechanics\CLI\bestiary\npc/jerot-galgin-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Jerot Galgin (VEoR)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "History"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "Jerot makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 25 (4d10 + 3) necrotic damage."
    "name": "Arcane Burst"
  - "desc": "Jerot casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** dancing lights, mage hand, prestidigitation\n\
      \n**2/day each:** bestow curse, dimension door, mage armor, web\n\n**1/day each:**\
      \ circle of death"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Jerot magically summons five [skeletons](/3-Mechanics/CLI/bestiary/undead/skeleton.md)\
      \ or [zombies](/3-Mechanics/CLI/bestiary/undead/zombie.md). The summoned creatures\
      \ appear in unoccupied spaces within 60 feet of Jerot, whom they obey. They\
      \ take their turns immediately after Jerot. Each lasts for 1 hour, until it\
      \ or Jerot dies, or until Jerot dismisses it as a bonus action."
    "name": "Summon Undead (1/Day)"
"reactions":
  - "desc": "When Jerot kills a creature with necrotic damage, Jerot regains 9 (2d8)\
      \ hit points. "
    "name": "Grim Harvest (1/Turn)"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/jerot-galgin-veor.webp"
```
^statblock