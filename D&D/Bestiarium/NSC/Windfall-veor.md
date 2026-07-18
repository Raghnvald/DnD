---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Windfall
Image: token/windfall-veor.webp
Status: WIP
linter-yaml-title-alias: Windfall
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/23
  - Monster/Typ/Humanoid/bard
  - Monster/Typ/Humanoid/tiefling
  - Quelle/5e/veor
aliases:
  - Windfall
status: WIP
---
# Windfall
*Source: Vecna: Eve of Ruin p. 153*  

Windfall, passionierte Streiterin von Tiamat, hat von ihrer Herrin phänomenale Kräfte erhalten. Bunte Schuppen glitzern auf ihrer Haut, und im Kampf summen alle fünf Elemente der chromatischen Drachen in ihrem Schwert. Windfalls verzauberter Frack schillert in den Farben der Drachenkönigin und berückt Gäste und Feinde gleichermaßen. 

Sie ist Schaustellerin durch und durch, pompös und charismatisch. Mit Stammgästen schwatzt sie freundlich, neue Gesichter heißt sie im Casino jovial willkommen. 

```statblock
"name": "Windfall (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "bard, tiefling"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "studded leather armor"
"hp": !!int "323"
"hit_dice": "34d8 + 170"
"modifier": !!int "7"
"stats":
  - !!int "14"
  - !!int "24"
  - !!int "20"
  - !!int "22"
  - !!int "18"
  - !!int "26"
"speed": "30 ft., fly 30 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "14"
  - "wisdom": !!int "11"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "Arcana"
    "desc": "+13"
  - "name": "Deception"
    "desc": "+22"
  - "name": "Insight"
    "desc": "+18"
  - "name": "Perception"
    "desc": "+11"
  - "name": "Performance"
    "desc": "+22"
  - "name": "Persuasion"
    "desc": "+22"
  - "name": "Sleight of Hand"
    "desc": "+14"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 60 ft., passive Perception 21"
"languages": "Common, Draconic, Infernal"
"cr": "23"
"traits":
  - "desc": "A brilliant array of chromatic colors emanates from Windfall, causing\
      \ attack rolls against her to have disadvantage. This trait ceases to function\
      \ while Windfall has the incapacitated condition or has a speed of 0."
    "name": "Dazzling Visage"
  - "desc": "If Windfall fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Windfall wears an iridescent magic coat that was tailored specifically\
      \ for her and imbued with Tiamat's power. When she dies, the coat functions\
      \ as a Robe of Scintillating Colors."
    "name": "Special Equipment"
"actions":
  - "desc": "Windfall makes two Chromatic Rapier attacks and uses Dragon's Fury once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (1d8 + 7) piercing damage plus 21 (6d6) acid, cold, fire, lightning, or poison\
      \ damage (Windfall's choice)."
    "name": "Chromatic Rapier"
  - "desc": "Windfall targets one creature she can see within 60 feet of herself and\
      \ unleashes a burst of magical ire. The target must make a DC 23 Wisdom saving\
      \ throw. On a failed save, the target takes 36 (8d8) psychic damage and has\
      \ the frightened condition until the start of Windfall's next turn. On a successful\
      \ save, the target takes half as much damage only."
    "name": "Dragon's Fury"
  - "desc": "Windfall casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 23):\n\n**At\
      \ will:** Detect Magic, Light, Thaumaturgy\n\n**3/day each:** Shatter, Unseen\
      \ Servant\n\n**2/day each:** Hypnotic Pattern, Sending\n\n**1/day:** Hold Monster"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Windfall emits an overwhelming array of colors from her coat. Each creature\
      \ within 30 feet of Windfall that can see her must succeed on a DC 23 Constitution\
      \ saving throw or have the stunned condition until the start of Windfall's next\
      \ turn."
    "name": "Stunning Scintillation (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Windfall can expend a use to take one of the following actions. Windfall\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Windfall moves up to her speed without provoking opportunity attacks."
    "name": "Deft Dance"
  - "desc": "Windfall flares with multicolored flames and targets a creature she can\
      \ see within 30 feet of herself. The target must make a DC 23 Dexterity saving\
      \ throw. On a failed save, the target takes 26 (4d12) damage of a type chosen\
      \ by Windfall: acid, cold, fire, lightning, or poison. On a successful save,\
      \ the target takes half as much damage."
    "name": "Dragon's Flare"
  - "desc": "Windfall uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "VEoR"
"image": "NSC/token/windfall-veor.webp"
```
^statblock