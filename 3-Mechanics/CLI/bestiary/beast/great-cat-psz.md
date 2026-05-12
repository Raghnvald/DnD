---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Great Cat"
---
# [Great Cat](3-Mechanics/CLI/bestiary/beast/great-cat-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

At least two varieties of great cat (similar to the [saber-toothed tiger](3-Mechanics/CLI/bestiary/beast/saber-toothed-tiger.md)) sport enormous blades jutting back from the forelegs, which help them cut through heavy undergrowth and take down much larger prey.

```statblock
"name": "Great Cat (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The cat has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "If the cat moves at least 20 feet straight toward a creature and then\
      \ hits it with a claw attack on the same turn, that target must succeed on a\
      \ DC 14 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the cat\
      \ can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d10 + 5) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage."
    "name": "Claw"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/great-cat-psz.webp"
```
^statblock