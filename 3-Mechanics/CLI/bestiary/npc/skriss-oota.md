---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/troglodyte
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skriss"
---
# [Skriss](3-Mechanics/CLI/bestiary/npc/skriss-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Skriss (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Neutral"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "18"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Troglodyte, Dwarvish, Elvish, Undercommon"
"cr": "1/4"
"traits":
  - "desc": "Skriss can innately cast can cast the [teleport](3-Mechanics/CLI/spells/teleport.md)\
      \ spell once per day, but the intended destination must be within 30 feet of\
      \ another society member. This teleport effect can be disrupted (see \"Faerzress\"\
      ), which is how society members sometimes end up in far corners of the Underdark,\
      \ separated from their fellows.\n"
    "name": "Innate Spellcasting"
  - "desc": "Skriss has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks made to hide."
    "name": "Chameleon Skin"
  - "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
      \ of Skriss must succeed on a DC 12 Constitution saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ until the start of the creature's next turn. On a successful saving throw,\
      \ the creature is immune to the stench of all troglodytes for 1 hour."
    "name": "Stench"
  - "desc": "While in sunlight, Skriss has disadvantage on attack rolls, as well as\
      \ on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Skriss makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) slashing damage."
    "name": "Claw"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/skriss-oota.webp"
```
^statblock