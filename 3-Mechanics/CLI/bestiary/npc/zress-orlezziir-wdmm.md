---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zress Orlezziir"
---
# [Zress Orlezziir](3-Mechanics/CLI/bestiary/npc/zress-orlezziir-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 136*  

```statblock
"name": "Zress Orlezziir (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[mithral plate armor](3-Mechanics/CLI/items/mithral-armor-xdmg.md)"
"hp": !!int "162"
"hit_dice": "25d8 + 50"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "6"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+8"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow-xphb.md)"
  - "[scimitar](3-Mechanics/CLI/items/scimitar-xphb.md)"
  - "[whip](3-Mechanics/CLI/items/whip-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Elvish, Undercommon"
"cr": "9"
"traits":
  - "desc": "Zress's innate spellcasting ability is Charisma (spell save DC 13). He\
      \ can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md)\n\
      \n**1/day each:** [darkness](3-Mechanics/CLI/spells/darkness-xphb.md), [faerie\
      \ fire](3-Mechanics/CLI/spells/faerie-fire-xphb.md), [levitate](3-Mechanics/CLI/spells/levitate-xphb.md)\
      \ (self only)"
    "name": "Innate Spellcasting"
  - "desc": "As a bonus action, Zress targets one ally he can see within 30 feet of\
      \ him. If the target can see or hear Zress, the target can use its reaction\
      \ to make one melee attack or to take the [Dodge](3-Mechanics/CLI/rules/actions.md#Dodge)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Battle Command"
  - "desc": "Zress has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put Zress to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, Zress has disadvantage on attack rolls, as well as\
      \ on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Zress makes three attacks: two with her scimitar and one with her whip\
      \ or her hand crossbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage plus 14 (4d6) poison damage."
    "name": "Scimitar"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 6 (1d4 + 4) slashing damage. If the target is an ally, it has advantage\
      \ on attack rolls until the end of its next turn."
    "name": "Whip"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.\
      \ The target regains consciousness if it takes damage or if another creature\
      \ takes an action to shake it."
    "name": "Hand Crossbow"
"reactions":
  - "desc": "Zress adds 3 to her AC against one melee attack that would hit him. To\
      \ do so, Zress must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/zress-orlezziir-wdmm.webp"
```
^statblock