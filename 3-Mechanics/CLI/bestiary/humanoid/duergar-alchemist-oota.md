---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Duergar Alchemist"
---
# [Duergar Alchemist](3-Mechanics/CLI/bestiary/humanoid/duergar-alchemist-oota.md)
*Source: Out of the Abyss p. 76*  

```statblock
"name": "Duergar Alchemist (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[scale mail](3-Mechanics/CLI/items/scale-mail.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"gear":
  - "[javelin](3-Mechanics/CLI/items/javelin.md)"
  - "[war pick](3-Mechanics/CLI/items/war-pick.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "1"
"traits":
  - "desc": "The duergar has advantage on saving throws against poison, spells, and\
      \ illusions, as well as to resist being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)."
    "name": "Duergar Resilience"
  - "desc": "While in sunlight, the duergar has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "For 1 minute, the duergar magically increases in size, along with anything\
      \ it is wearing or carrying. While enlarged, the duergar is Large, doubles its\
      \ damage dice on Strength-based weapon attacks (included in the attacks), and\
      \ makes Strength checks and Strength saving throws with advantage. If the duergar\
      \ lacks the room to become Large, it attains the maximum size possible in the\
      \ space available."
    "name": "Enlarge (Recharges after a Short or Long Rest)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
    "name": "War Pick"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 20 ft., one target. *Hit:*\
      \ 7 (2d6) acid damage."
    "name": "Acid Vial"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 20 ft., one target. *Hit:*\
      \ 2 (1d4) fire damage at the start of each of the target's turns. A creature\
      \ can end this damage by using its action to make a successful DC 10 Dexterity\
      \ check to extinguish the flames."
    "name": "Alchemist's Fire"
  - "desc": "The duergar magically turns [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ is broken, up to 1 hour (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). Any equipment the duergar wears or carries is [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ with it."
    "name": "Invisibility (Recharges after a Short or Long Rest)"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/duergar-alchemist-oota.webp"
```
^statblock