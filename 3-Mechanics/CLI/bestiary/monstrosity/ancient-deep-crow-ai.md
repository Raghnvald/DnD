---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ancient Deep Crow"
---
# [Ancient Deep Crow](3-Mechanics/CLI/bestiary/monstrosity/ancient-deep-crow-ai.md)
*Source: Acquisitions Incorporated p. 211*  

So little is known of the deep crows that even less is known of their monstrous leviathan cousins, the ancient deep crows. Whether these gargantuan specimens are elder deep crows grown to great size or some higher form that holds lesser deep crows in thrall remains to be determined. Ideally by someone else. Seriously, stay away from these things.

```statblock
"name": "Ancient Deep Crow (AI)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "15d12 + 90"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "23"
  - !!int "10"
  - !!int "15"
  - !!int "19"
"speed": "20 ft., fly 80 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+13"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 17"
"languages": "Deep Crow"
"cr": "15"
"traits":
  - "desc": "The ancient deep crow has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "While in dim light or darkness, the ancient deep crow can take the Hide\
      \ action as a bonus action."
    "name": "Shadow Stealth"
"actions":
  - "desc": "The ancient deep crow makes three attacks: one with its mandibles and\
      \ two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (2d10 + 6) piercing damage, and the target is grappled (escape DC 19).\
      \ Until this grapple ends, the target is restrained, and the ancient deep crow\
      \ can't use its mandibles on another target."
    "name": "Mandibles"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage."
    "name": "Claw"
  - "desc": "The ancient deep crow releases an ear-splitting caw. Each creature within\
      \ 60 feet of the crow and able to hear it must make a DC 17 Constitution saving\
      \ throw. On a failure, a creature takes 10 (3d6) psychic damage."
    "name": "Shadow Caw"
"regional_effects":
  - "desc": "The region containing an ancient deep crow's lair is transformed by the\
      \ creature's presence, which creates one or more of the following effects:\n\
      \n- Supernatural shadow turns all bright light to dim light in underground regions\
      \ within 6 miles of the lair.  \n- Intermittent, echoing caws can be heard coming\
      \ from all directions within 6 miles of the lair.  \n- Subterranean beasts within\
      \ 1 mile of the ancient deep crow's lair serve as the creature's eyes and ears,\
      \ alerting it to the presence of intruders and making it all but impossible\
      \ to surprise the ancient deep crow.  \n\nIf the ancient deep crow dies, these\
      \ effects fade immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the ancient deep crow can expend a use to take one of the following actions.\
  \ The ancient deep crow regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The deep crow makes a Wisdom (Perception) check."
    "name": "Detect"
  - "desc": "The ancient deep crow uses Shadow Caw."
    "name": "Shadow Caw (Costs 2 Actions)"
  - "desc": "The ancient deep crow beats its wings. Each creature within 10 feet of\
      \ the deep crow must succeed on a DC 19 Dexterity saving throw or take 13 (2d6\
      \ + 6) bludgeoning damage and be knocked prone. The ancient deep crow can then\
      \ fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/ancient-deep-crow-ai.webp"
```
^statblock