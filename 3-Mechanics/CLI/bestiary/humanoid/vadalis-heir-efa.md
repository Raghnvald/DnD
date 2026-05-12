---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/efa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vadalis Heir"
---
# [Vadalis Heir](3-Mechanics/CLI/bestiary/humanoid/vadalis-heir-efa.md)
*Source: Eberron: Forge of the Artificer p. 85*  

Combining druidic magic with skill at handling natural and monstrous animals, the dragonmarked heirs of House Vadalis, most of whom are human, are more fearsome than their innocuous-seeming house suggests—especially when accompanied by a Giant Boar, Polar Bear, or Rhinoceros.

```statblock
"name": "Vadalis Heir (EFA)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "10"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "4"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Animal Handling"
    "desc": "+7"
  - "name": "Nature"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+5"
"gear":
  - "leather armor"
  - "scimitar"
"senses": "passive Perception 13"
"languages": "Common, Sylvan"
"cr": "4"
"traits":
  - "desc": "The heir has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on an attack roll against a creature if at least one of the heir's allies\
      \ is within 5 feet of the creature and the ally doesn't have the Incapacitated\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "The heir makes four attacks, using Scimitar or Lunar Wisp in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing\
      \ damage plus 3 (1d6) Poison damage."
    "name": "Scimitar"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 9 (2d8) Radiant damage,\
      \ and the target emits <span title=\"Player's Handbook (2024)\">Dim Light</span>\
      \ in a 10-foot radius and can't benefit from the Invisible condition until the\
      \ end of the heir's next turn."
    "name": "Lunar Wisp"
  - "desc": "The heir casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** Druidcraft, Light, Speak with\
      \ Animals\n\n**3/day each:** Animal Friendship, Animal Messenger\n\n**1/day:**\
      \ Ice Storm"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The heir targets a Beast it can see within 30 feet. The target can take\
      \ a <span title=\"Player's Handbook (2024)\">Reaction</span> to move up to half\
      \ its <span title=\"Player's Handbook (2024)\">Speed</span> and make one melee\
      \ attack."
    "name": "Spur Beast"
"source":
  - "EFA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/vadalis-heir-efa.webp"
```
^statblock