---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rihuud"
---
# [Rihuud](3-Mechanics/CLI/bestiary/npc/rihuud-oota.md)
*Source: Out of the Abyss p. 59*  

```statblock
"name": "Rihuud (OotA)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[greatclub](3-Mechanics/CLI/items/greatclub.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Giant"
"cr": "7"
"traits":
  - "desc": "Rihuud has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks made to hide in rocky terrain."
    "name": "Stone Camouflage"
  - "desc": "Rihuud has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks and on saving throws against being [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded),\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
      \ or knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)."
    "name": "Two Heads"
"actions":
  - "desc": "Rihuud makes two unarmed strikes."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) bludgeoning damage."
    "name": "Unarmed Strike"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Rock"
"reactions":
  - "desc": "If a rock or similar object is hurled at Rihuud, Rihuud can, with a successful\
      \ DC 10 Dexterity saving throw, catch the missile and take no bludgeoning damage\
      \ from it."
    "name": "Rock Catching"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/rihuud-oota.webp"
```
^statblock