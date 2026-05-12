---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Replica Pentadrone"
---
# [Replica Pentadrone](3-Mechanics/CLI/bestiary/construct/replica-pentadrone-oow.md)
*Source: The Orrery of the Wanderer p. 132*  

```statblock
"name": "Replica Pentadrone (OoW)"
"size": "Large"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "32"
"hit_dice": "5d10 + 5"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "13"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Modron, can understand Common but speaks only preprogrammed responses"
"cr": "2"
"traits":
  - "desc": "The pentadrone can't be compelled to act in a manner contrary to its\
      \ nature or its instructions."
    "name": "Axiomatic Mind"
  - "desc": "If the replica pentadrone dies, its body falls into a pile of parts (gears,\
      \ plates, screws, and wires), leaving behind its weapons and anything else it\
      \ was carrying."
    "name": "Dismantlable"
"actions":
  - "desc": "The pentadrone makes five arm attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Arm"
  - "desc": "The pentadrone exhales a 30-foot cone of gas. Each creature in that area\
      \ must succeed on a DC 11 Constitution saving throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Paralysis Gas (Recharge 5-6)"
"source":
  - "OoW"
"image": "3-Mechanics/CLI/bestiary/construct/token/replica-pentadrone-oow.webp"
```
^statblock