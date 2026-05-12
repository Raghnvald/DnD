---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nrh-awol
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Szikzith"
---
# [Szikzith](3-Mechanics/CLI/bestiary/npc/szikzith-nrh-awol.md)
*Source: NERDS Restoring Harmony: A Web of Lies p. 6*  

```statblock
"name": "Szikzith (NRH-AWoL)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "8"
  - !!int "12"
  - !!int "4"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "Szikzith can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "While in contact with a web, Szikzith knows the exact location of any\
      \ other creature in contact with the same web."
    "name": "Web Sense"
  - "desc": "Szikzith ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:*\
      \ 4 (1d6 + 1) piercing damage, and the target must make a DC 11 Constitution\
      \ saving throw, taking 7 (2d6) poison damage on a failed save, or half as\
      \ much damage on a successful one. If the poison damage reduces the target to\
      \ 0 hit points, the target is stable but [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour, even after regaining hit points, and is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way."
    "name": "Bite"
"source":
  - "NRH-AWoL"
"image": "3-Mechanics/CLI/bestiary/npc/token/szikzith-nrh-awol.webp"
```
^statblock