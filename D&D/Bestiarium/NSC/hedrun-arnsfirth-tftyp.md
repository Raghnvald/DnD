---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Hedrun Arnsfirth
Status: WIP
linter-yaml-title-alias: Hedrun Arnsfirth
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Untote
  - Quelle/5e/tftyp
aliases:
  - Hedrun Arnsfirth
---
# [Hedrun Arnsfirth](3-Mechanics\CLI\bestiary\npc/hedrun-arnsfirth-tftyp.md)
*Source: Tales from the Yawning Portal p. 160*  

```statblock
"name": "Hedrun Arnsfirth (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+3"
  - "name": "Perception"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
  - "desc": "Hedrun's innate spellcasting ability is Charisma (spell save DC 13).\
      \ It can innately cast the following spells, requiring no verbal or material\
      \ components:\n\n**At will:** detect magic, disguise self, mage armor\n\n**1/day\
      \ each:** fear, hold person, misty step"
    "name": "Innate Spellcasting"
  - "desc": "While in sunlight, Hedrun has disadvantage on attack rolls, as well as\
      \ on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Hedrun attacks twice with Grave Bolt."
    "name": "Multiattack"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 120 ft., one target. *Hit:* 7\
      \ (1d8 + 3) necrotic damage."
    "name": "Grave Bolt"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 9\
      \ (2d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0.\n\nA humanoid\
      \ slain by this attack rises 24 hours later as a [zombie](/3-Mechanics/CLI/bestiary/undead/zombie.md)\
      \ under Hedrun's control, unless the humanoid is restored to life or its body\
      \ is destroyed. Hedrun can have no more than twelve [zombies](/3-Mechanics/CLI/bestiary/undead/zombie.md)\
      \ under its control at one time."
    "name": "Life Drain"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/hedrun-arnsfirth-tftyp.webp"
```
^statblock