---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Drow Commander
Status: WIP
linter-yaml-title-alias: Drow Commander
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Humanoid/elf
  - Quelle/5e/tftyp
aliases:
  - Drow Commander
---
# [Drow Commander](3-Mechanics\CLI\bestiary\humanoid/drow-commander-tftyp.md)
*Source: Tales from the Yawning Portal p. 209*  

```statblock
"name": "Drow Commander (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "studded leather, shield"
"hp": !!int "110"
"hit_dice": "11d8 + 22"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+10"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
  - "desc": "The drow's spellcasting ability is Charisma (spell save DC 12). It can\
      \ innately cast the following spells, requiring no material components:\n\n\
      **At will:** dancing lights\n\n**1/day each:** darkness, faerie fire, levitate\
      \ (self only)"
    "name": "Innate Spellcasting"
  - "desc": "The drow carries three magical bolts, as follows:\n\n- A *bolt of holding*,\
      \ which casts hold person on a target hit with the bolt, as well as up to two\
      \ other targets within 30 feet of that target  \n- A *bolt of blinding*, which\
      \ casts blindness/deafness to blind on a target hit with the bolt, as well as\
      \ up to two other targets within 30 feet of that target  \n- A *bolt of vapors*,\
      \ which casts stinking cloud centered on the point it hits  \n\nEach of these\
      \ effects has a spell save DC of 15 and a duration of 1 minute."
    "name": "Special Equipment"
  - "desc": "The drow has advantage on saving throws against being charmed, and magic\
      \ can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d6\
      \ + 6) piercing damage plus 10 (3d6) poison damage."
    "name": "Shortsword +2"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target. *Hit:*\
      \ 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or\
      \ more, the target is also unconscious while poisoned in this way. The target\
      \ wakes up if it takes damage or if another creature takes an action to shake\
      \ it awake."
    "name": "Hand Crossbow +1"
"reactions":
  - "desc": "The drow adds 3 to its AC against one melee attack that would hit it.\
      \ To do so, the drow must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/drow-commander-tftyp.webp"
```
^statblock