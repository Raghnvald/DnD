---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Undead Cockatrice"
---
# [Undead Cockatrice](3-Mechanics/CLI/bestiary/undead/undead-cockatrice-oow.md)
*Source: The Orrery of the Wanderer p. 114*  

```statblock
"name": "Undead Cockatrice (OoW)"
"size": "Small"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"modifier": !!int "1"
"stats":
  - !!int "6"
  - !!int "12"
  - !!int "12"
  - !!int "2"
  - !!int "13"
  - !!int "5"
"speed": "20 ft., fly 40 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "1/2"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:*\
      \ 3 (1d4 + 1) piercing damage, and the target must succeed on a DC 11 Constitution\
      \ saving throw against being magically [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified).\
      \ On a failed save, the creature begins to turn to stone and is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ It must repeat the saving throw at the end of its next turn. On a success,\
      \ the effect ends. On a failure, the creature is [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)\
      \ for 24 hours."
    "name": "Bite"
"source":
  - "OoW"
"image": "3-Mechanics/CLI/bestiary/undead/token/undead-cockatrice-oow.webp"
```
^statblock