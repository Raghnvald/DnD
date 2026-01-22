---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Runara
tags:
  - Monster/Größe/Riesig
  - Monster/HG/13
  - Monster/Typ/Drache
  - Quelle/5e/dosi
aliases:
  - Runara
linter-yaml-title-alias: Runara
---
# [Runara](3-Mechanics\CLI\bestiary\npc/runara-dosi.md)
*Source: Dragons of Stormwreck Isle p. 40*  

Despite her innocuous disguise and her commitment to peace, the leader of Dragon's Rest is an adult bronze dragon—a fearsome opponent or a powerful ally. Her capabilities go beyond what is presented here.

## Bronze Dragons

Many bronze dragons are friendly coastal dwellers who enjoy watching ships and sailors.

```statblock
"name": "Runara (DoSI)"
"size": "Huge"
"type": "dragon"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "212"
"hit_dice": "17d12 + 102"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "23"
  - !!int "16"
  - !!int "15"
  - !!int "19"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "11"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+12"
  - "name": "Stealth"
    "desc": "+5"
"damage_immunities": "lightning"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 22"
"languages": "Common, Draconic"
"cr": "13"
"traits":
  - "desc": "Runara can breathe air and water."
    "name": "Amphibious"
  - "desc": "If Runara fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "Runara can use its Frightful Presence. It then makes three attacks: one\
      \ with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 18\
      \ (2d10 + 7) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d6 + 7) slashing damage."
    "name": "Claw"
  - "desc": "Each creature of Runara's choice that is within 120 feet of Runara and\
      \ aware of it must succeed on a DC 17 Wisdom saving throw or become frightened\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Runara's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "Runara uses one of the following breath weapons.\n\n- **Lightning Breath.**\
      \ Runara exhales lightning in a 90-foot line that is 5 feet wide. Each creature\
      \ in that line must make a DC 19 Dexterity saving throw, taking 66 (12d10) lightning\
      \ damage on a failed save, or half as much damage on a successful one.  \n-\
      \ **Repulsion Breath.** Runara exhales repulsion energy in a 30-foot cone. Each\
      \ creature in that area must succeed on a DC 19 Strength saving throw. On a\
      \ failed save, the creature is pushed 60 feet away from Runara.  "
    "name": "Breath Weapons (Recharge 5-6)"
  - "desc": "Runara magically transforms into a Humanoid or Beast that is Medium or\
      \ Small, while retaining her game statistics (other than her size). This transformation\
      \ ends if Runara is reduced to 0 hit points or uses a bonus action to end it."
    "name": "Change Shape"
"source":
  - "DoSI"
"image": "/3-Mechanics/CLI/bestiary/npc/token/runara-dosi.webp"
```
^statblock