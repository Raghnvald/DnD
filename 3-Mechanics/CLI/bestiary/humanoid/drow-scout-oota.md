---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Scout"
---
# [Drow Scout](3-Mechanics/CLI/bestiary/humanoid/drow-scout-oota.md)
*Source: Out of the Abyss p. 191*  

```statblock
"name": "Drow Scout (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 15"
"languages": "any one language (usually Common), Elvish, Undercommon"
"cr": "1/2"
"traits":
  - "desc": "The drow scout\n\n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights.md)\n\
      \n**1/day each:** [darkness](3-Mechanics/CLI/spells/darkness.md), [faerie fire](3-Mechanics/CLI/spells/faerie-fire.md),\
      \ [levitate](3-Mechanics/CLI/spells/levitate.md) (self only)"
    "name": "Innate Spellcasting"
  - "desc": "The scout has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
  - "desc": "The drow scout"
    "name": "Fey Ancestry"
  - "desc": "the drow scout"
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The scout makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, ranged 150/600 ft., one target.\
      \ *Hit:* 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/drow-scout-oota.webp"
```
^statblock