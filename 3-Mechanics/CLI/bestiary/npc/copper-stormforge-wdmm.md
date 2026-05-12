---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Copper Stormforge"
---
# [Copper Stormforge](3-Mechanics/CLI/bestiary/npc/copper-stormforge-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 30*  

Scouts are skilled hunters and trackers who offer their services for a fee. Most hunt wild game, but a few work as bounty hunters, serve as guides, or provide military reconnaissance.

```statblock
"name": "Copper Stormforge (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
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
"damage_resistances": "poison"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": "any one language (usually Common), Dwarvish"
"cr": "1/2"
"traits":
  - "desc": "Copper has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
  - "desc": "Copper"
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Copper makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, ranged 150/600 ft., one target.\
      \ *Hit:* 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/copper-stormforge-wdmm.webp"
```
^statblock