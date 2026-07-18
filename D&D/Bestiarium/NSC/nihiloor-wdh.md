---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Nihiloor
Status: WIP
linter-yaml-title-alias: Nihiloor
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/aberration
  - Quelle/5e/wdh
aliases:
  - Nihiloor
---
# [Nihiloor](3-Mechanics\CLI\bestiary\npc/nihiloor-wdh.md)
*Source: Waterdeep: Dragon Heist p. 212*  

```statblock
"name": "Nihiloor (WDH)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "breastplate"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "12"
  - !!int "19"
  - !!int "17"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Persuasion"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+4"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "7"
"traits":
  - "desc": "Nihiloor's innate spellcasting ability is Intelligence (spell save DC\
      \ 15). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** detect thoughts, levitate\n\n**1/day each:** dominate monster,\
      \ plane shift (self only)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "Nihiloor has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 15\
      \ (2d10 + 4) psychic damage. If the target is Medium or smaller, it is grappled\
      \ (escape DC 15) and must succeed on a DC 15 Intelligence saving throw or be\
      \ stunned until this grapple ends."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one incapacitated humanoid\
      \ grappled by Nihiloor. *Hit:* The target takes 55 (10d10) piercing damage.\
      \ If this damage reduces the target to 0 hit points, Nihiloor kills the target\
      \ by extracting and devouring its brain."
    "name": "Extract Brain"
  - "desc": "Nihiloor magically emits psychic energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 15 Intelligence saving throw or take 22\
      \ (4d8 + 4) psychic damage and be stunned for 1 minute. A creature can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success."
    "name": "Mind Blast (Recharge 5-6)"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/nihiloor-wdh.webp"
```
^statblock