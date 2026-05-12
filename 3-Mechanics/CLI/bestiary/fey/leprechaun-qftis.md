---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Leprechaun"
---
# [Leprechaun](3-Mechanics/CLI/bestiary/fey/leprechaun-qftis.md)
*Source: Quests from the Infinite Staircase p. 205*  

Leprechauns are manifestations of the Feywild rules of hospitality and reciprocity. These rules infuse leprechauns with a deep connection to fixing and making things. Industrious and proud, leprechauns channel this creative energy into their tools, using them to quickly mend damaged objects, craft new ones from raw materials, and mold ideas into vivid illusions.

A leprechaun's adherence to Feywild rules affords it tremendous luck, but this fortune comes at a cost. These same magical strictures compel leprechauns to use their powers on behalf of those who offer them gifts. Leprechauns despise greed and are spiteful toward anyone who makes demands without first offering a gift or, worse, anyone who tries to steal from them. They delight in pranking such foolish creatures or pilfering from them in return.

Leprechauns take pride in their appearances, dressing in dapper outfits that typically feature red fabrics, gleaming belts and buckles, and natural woodland accouterments. These fashions compliment their bright green skin, exuberant hair, and upbeat demeanors.

```statblock
"name": "Leprechaun (QftIS)"
"size": "Small"
"type": "fey"
"alignment": "typically  Neutral"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d6 + 24"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Sylvan"
"cr": "4"
"traits":
  - "desc": "The leprechaun is proficient with all artisan's tools and adds double\
      \ its proficiency bonus to ability checks made with them."
    "name": "Industrious"
  - "desc": "When a creature offers the leprechaun the chance to partake in merriment\
      \ or revelry such as a song, a dance, or a good meal, the leprechaun must succeed\
      \ on a DC 15 Wisdom saving throw or have the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition for 24 hours. While [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ in this way, the leprechaun partakes of the offering, treats the creature\
      \ as a trusted friend, and seeks to defend it from harm. The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition ends if the creature or any of its allies damage the leprechaun,\
      \ force the leprechaun to make a saving throw, or steal from the leprechaun."
    "name": "Reluctant Refusal"
"actions":
  - "desc": "The leprechaun makes two Cobbler's Hammer attacks and can use Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage plus 13 (3d8) force damage. If the target\
      \ is a creature, its speed is halved until the start of the leprechaun's next\
      \ turn."
    "name": "Cobbler's Hammer"
  - "desc": "The leprechaun touches a creature and magically gifts the target a measure\
      \ of luck. The creature gains the leprechaun's Astonishing Luck reaction. The\
      \ creature can use the reaction three times, after which this gift goes away.\
      \ The leprechaun can revoke this gift from a creature at any time (no action\
      \ required). A creature can benefit from only one leprechaun's Gift of Luck\
      \ at a time."
    "name": "Gift of Luck (1/Day)"
  - "desc": "The leprechaun casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
      \n**At will:** [Mending](3-Mechanics/CLI/spells/mending.md) (as an action),\
      \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\n**2/day\
      \ each:** [Invisibility](3-Mechanics/CLI/spells/invisibility.md), [Phantasmal\
      \ Force](3-Mechanics/CLI/spells/phantasmal-force.md)\n\n**1/day each:** [Fabricate](3-Mechanics/CLI/spells/fabricate.md)\
      \ (as an action), [Mislead](3-Mechanics/CLI/spells/mislead.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The leprechaun takes the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action or makes a Dexterity\
      \ ([Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)) check."
    "name": "Cunning Trick"
"reactions":
  - "desc": "When the leprechaun fails an ability check, an attack roll, or a saving\
      \ throw, it can roll a new d20 and choose which roll to use, potentially turning\
      \ the failure into a success."
    "name": "Astonishing Luck"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/fey/token/leprechaun-qftis.webp"
```
^statblock