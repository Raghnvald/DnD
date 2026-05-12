---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Living Bigby's Hand"
---
# [Living Bigby's Hand](3-Mechanics/CLI/bestiary/construct/living-bigbys-hand-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 298*  

A living Bigby's hand is a Large, hovering hand of shimmering, translucent force. It often serves as a guardian, attacking creatures that cross its path while remaining loyal to its caster.

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that become living beings. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

```statblock
"name": "Living Bigby's Hand (IDRotF)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "5d10 + 25"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "20"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  - "dexterity": !!int "2"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"damage_immunities": "poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The living spell has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The living spell doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Spell Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 26\
      \ (4d8 + 8) force damage. If the target is a Large or smaller creature, the\
      \ living spell can move it up to 5 feet and move with it, without provoking\
      \ opportunity attacks."
    "name": "Force Fist"
  - "desc": "The living spell attempts to grab a Huge or smaller creature within 5\
      \ feet of it. The target must succeed on a DC 15 Dexterity saving throw or be\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until\
      \ the grapple ends, the target takes 15 (2d6 + 8) bludgeoning damage at the\
      \ start of each of its turns. The living spell can grapple only one creature\
      \ at a time and can't use Force Fist until the grapple ends."
    "name": "Grasping Hand"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/construct/token/living-bigbys-hand-idrotf.webp"
```
^statblock