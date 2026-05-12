---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/monk
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jamil A'alithiya"
---
# [Jamil A'alithiya](3-Mechanics/CLI/bestiary/npc/jamil-aalithiya-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 83*  

```statblock
"name": "Jamil A'alithiya (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, monk, wizard"
"alignment": "Chaotic Good"
"ac": !!int "19"
"ac_class": "Unarmored Defense"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "18"
  - !!int "22"
  - !!int "17"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "History"
    "desc": "+8"
  - "name": "Investigation"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+10"
"damage_resistances": "psychic"
"condition_immunities": "charmed"
"senses": "blindsight 30 ft., passive Perception 20"
"languages": "Common plus four other languages"
"cr": "10"
"traits":
  - "desc": "While Jamil is wearing no armor and wielding no shield, its AC includes\
      \ its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "Jamil makes three Force Strike attacks and uses Brain Burn (if available)."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +10 to hit, reach 5 ft. or range 10\
      \ ft., one target. *Hit:* 17 (2d10 + 6) force damage."
    "name": "Force Strike"
  - "desc": "Jamil targets up to two creatures it can see within 30 feet of itself.\
      \ Each target must make a DC 18 Constitution saving throw. On a failed saving\
      \ throw, the target takes 28 (8d6) psychic damage and can't take reactions\
      \ until the start of its next turn. On a successful save, the target takes half\
      \ as much damage and suffers no other effect."
    "name": "Brain Burn (Recharge 4-6)"
  - "desc": "Jamil casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 18):\n\n**At will:**\
      \ detect magic\n\n**2/day each:** detect thoughts, identify (as an action),\
      \ scrying (as an action)"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/jamil-aalithiya-crcotn.webp"
```
^statblock