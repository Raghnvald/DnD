---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flying Wand"
---
# [Flying Wand](3-Mechanics/CLI/bestiary/construct/flying-wand-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 105*  

```statblock
"name": "Flying Wand (WDMM)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "17"
"hit_dice": "5d6"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "11"
  - !!int "1"
  - !!int "5"
  - !!int "1"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  - "dexterity": !!int "4"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 7"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The wand is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field-xphb.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ the wand must succeed on a Constitution saving throw against the caster's\
      \ spell save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the wand remains motionless and isn't flying, it is indistinguishable\
      \ from a normal wand."
    "name": "False Appearance"
"actions":
  - "desc": "The wand shoots a dart of magical force at one creature that it can detect\
      \ within 60 feet of it. The target takes 3 (1d4 + 1) force damage as the dart\
      \ hits it unerringly."
    "name": "Magic Missile"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/construct/token/flying-wand-wdmm.webp"
```
^statblock