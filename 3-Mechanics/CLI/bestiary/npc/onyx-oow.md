---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Onyx"
---
# [Onyx](3-Mechanics/CLI/bestiary/npc/onyx-oow.md)
*Source: The Orrery of the Wanderer p. 186*  

Onyx is a regular cat, with special traits, and a modified attack, that only apply when used in the Onyx Ascendant encounter.

Further information can be found within that encounter on how to run it.

Without the special circumstances from that encounter, Onyx can be considered a standard cat

```statblock
"name": "Onyx (OoW)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "2"
"stats":
  - !!int "3"
  - !!int "15"
  - !!int "10"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "400 ft., climb 200 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The cat has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "Any damage Onyx would take is reduced to 0. She has advantage on ability\
      \ checks and saving throws."
    "name": "Relative Size"
  - "desc": "Onyx cannot be overcome or killed by combat. Any weapon attack against\
      \ her that hits AC 12 makes contact but deals no lasting damage. However, if\
      \ the attack would deal 10 or more damage, Onyx has disadvantage on attack rolls\
      \ until the end of her next turn. If Onyx would take 10 or more damage from\
      \ spells or other effects, it yields the same result. Spells that impose conditions\
      \ function normally against Onyx, but those conditions end automatically at\
      \ the end of the cat's next turn."
    "name": "Dealing with Onyx"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 20 ft., one target. *Hit:*\
      \ 11 (2d10) slashing damage."
    "name": "Claws"
"source":
  - "OoW"
"image": "3-Mechanics/CLI/bestiary/npc/token/onyx-oow.webp"
```
^statblock