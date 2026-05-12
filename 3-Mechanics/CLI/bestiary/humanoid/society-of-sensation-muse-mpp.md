---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Society of Sensation Muse"
---
# [Society of Sensation Muse](3-Mechanics/CLI/bestiary/humanoid/society-of-sensation-muse-mpp.md)
*Source: Morte's Planar Parade p. 61*  

The muses of the Society of Sensation are performers who enthrall crowds with spectacle and minor sensory experiences. When threatened, they beguile their foes, placating their enemies with magical displays.

```statblock
"name": "Society of Sensation Muse (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "14"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 14"
"languages": "Common plus two more languages"
"cr": "3"
"actions":
  - "desc": "The muse makes two Beguiling Resonance attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 90\
      \ ft., one target. *Hit:* 9 (2d8) psychic damage. If the target is a creature,\
      \ it must succeed on a DC 13 Charisma saving throw or have disadvantage on the\
      \ next attack roll it makes until the end of its next turn."
    "name": "Beguiling Resonance"
  - "desc": "The muse casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights.md)\n\
      \n**1/day each:** [comprehend languages](3-Mechanics/CLI/spells/comprehend-languages.md),\
      \ [hypnotic pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Each creature within 30 feet of the muse must make a DC 13 Wisdom saving\
      \ throw. On a failed save, the creature has the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition for 1 minute. On a successful save, the creature becomes immune\
      \ to any muse's Enchanting Presence for 24 hours.\n\nWhenever the muse deals\
      \ damage to the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) creature,\
      \ the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) creature can repeat\
      \ the saving throw, ending the effect on itself on a success."
    "name": "Enchanting Presence"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/society-of-sensation-muse-mpp.webp"
```
^statblock