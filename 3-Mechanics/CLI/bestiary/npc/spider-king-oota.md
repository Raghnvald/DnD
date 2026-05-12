---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spider King"
---
# [Spider King](3-Mechanics/CLI/bestiary/npc/spider-king-oota.md)
*Source: Out of the Abyss p. 74*  

```statblock
"name": "Spider King (OotA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "4d10 + 4"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"saves":
  - "constitution": !!int "3"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "While in contact with a web, the spider knows the exact location of any\
      \ other creature in contact with the same web."
    "name": "Web Sense"
  - "desc": "The spider ignores movement restrictions caused by webbing."
    "name": "Web Walker"
  - "desc": "Because of its two heads, the Spider King has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks and on saving throws against being [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded),\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
      \ and knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)."
    "name": "Two Heads"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 7 (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution\
      \ saving throw, taking 9 (2d8) poison damage on a failed save, or half as\
      \ much damage on a successful one. If the poison damage reduces the target to\
      \ 0 hit points, the target is stable but [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour, even after regaining hit points, and is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/60 ft., one creature. *Hit:*\
      \ The target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by webbing. As an action, the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ target can make a DC 12 Strength check, bursting the webbing on a success.\
      \ The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability\
      \ to fire damage; immunity to bludgeoning, poison, and psychic damage)."
    "name": "Web (Recharge 5-6)"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/spider-king-oota.webp"
```
^statblock