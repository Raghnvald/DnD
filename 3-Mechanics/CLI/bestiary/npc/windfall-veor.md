---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bard
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Windfall"
---
# [Windfall](3-Mechanics/CLI/bestiary/npc/windfall-veor.md)
*Source: Vecna: Eve of Ruin p. 153*  

As a dedicated champion of Tiamat, Windfall has been granted phenomenal power by her master. Her skin glitters with patches of multicolored scales, and in combat, her blade sings with all five of the chromatic dragons' elements. Windfall's enchanted tailcoat shimmers with the colors of the Dragon Queen, and she uses this coat to dazzle patrons and enemies alike.

A performer at heart, Windfall is ostentatious and charismatic, making small talk with regular patrons and jovially welcoming new faces to the casino.

```statblock
"name": "Windfall (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "bard, tiefling"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "[studded leather armor](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
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
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+22"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+18"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+22"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+22"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+14"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 21"
"languages": "Common, Draconic, Infernal"
"cr": "23"
"traits":
  - "desc": "A brilliant array of chromatic colors emanates from Windfall, causing\
      \ attack rolls against her to have disadvantage. This trait ceases to function\
      \ while Windfall has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition or has a speed of 0."
    "name": "Dazzling Visage"
  - "desc": "If Windfall fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Windfall wears an iridescent magic coat that was tailored specifically\
      \ for her and imbued with Tiamat's power. When she dies, the coat functions\
      \ as a [Robe of Scintillating Colors](3-Mechanics/CLI/items/robe-of-scintillating-colors-xdmg.md)."
    "name": "Special Equipment"
"actions":
  - "desc": "Windfall makes two Chromatic Rapier attacks and uses Dragon's Fury once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (1d8 + 7) piercing damage plus 21 (6d6) acid, cold, fire, lightning,\
      \ or poison damage (Windfall's choice)."
    "name": "Chromatic Rapier"
  - "desc": "Windfall targets one creature she can see within 60 feet of herself and\
      \ unleashes a burst of magical ire. The target must make a DC 23 Wisdom saving\
      \ throw. On a failed save, the target takes 36 (8d8) psychic damage and has\
      \ the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) condition\
      \ until the start of Windfall's next turn. On a successful save, the target\
      \ takes half as much damage only."
    "name": "Dragon's Fury"
  - "desc": "Windfall casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 23):\n\n**At\
      \ will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**3/day each:**\
      \ [Shatter](3-Mechanics/CLI/spells/shatter-xphb.md), [Unseen Servant](3-Mechanics/CLI/spells/unseen-servant-xphb.md)\n\
      \n**2/day each:** [Hypnotic Pattern](3-Mechanics/CLI/spells/hypnotic-pattern-xphb.md),\
      \ [Sending](3-Mechanics/CLI/spells/sending-xphb.md)\n\n**1/day:** [Hold Monster](3-Mechanics/CLI/spells/hold-monster-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Windfall emits an overwhelming array of colors from her coat. Each creature\
      \ within 30 feet of Windfall that can see her must succeed on a DC 23 Constitution\
      \ saving throw or have the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition until the start of Windfall's next turn."
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
"image": "3-Mechanics/CLI/bestiary/npc/token/windfall-veor.webp"
```
^statblock