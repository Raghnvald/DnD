---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Commander"
---
# [Drow Commander](3-Mechanics/CLI/bestiary/humanoid/drow-commander-tftyp.md)
*Source: Tales from the Yawning Portal p. 209*  

```statblock
"name": "Drow Commander (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md),\
  \ [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "110"
"hit_dice": "11d8 + 22"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+10"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
  - "desc": "The drow's spellcasting ability is Charisma (spell save DC 12). It can\
      \ innately cast the following spells, requiring no material components:\n\n\
      **At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md)\n\
      \n**1/day each:** [darkness](3-Mechanics/CLI/spells/darkness-xphb.md), [faerie\
      \ fire](3-Mechanics/CLI/spells/faerie-fire-xphb.md), [levitate](3-Mechanics/CLI/spells/levitate-xphb.md)\
      \ (self only)"
    "name": "Innate Spellcasting"
  - "desc": "The drow carries three magical bolts, as follows:\n\n- A *bolt of holding*,\
      \ which casts [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md) on a\
      \ target hit with the bolt, as well as up to two other targets within 30 feet\
      \ of that target  \n- A *bolt of blinding*, which casts [blindness/deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md)\
      \ to blind on a target hit with the bolt, as well as up to two other targets\
      \ within 30 feet of that target  \n- A *bolt of vapors*, which casts [stinking\
      \ cloud](3-Mechanics/CLI/spells/stinking-cloud-xphb.md) centered on the point\
      \ it hits  \n\nEach of these effects has a spell save DC of 15 and a duration\
      \ of 1 minute."
    "name": "Special Equipment"
  - "desc": "The drow has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d6 + 6) piercing damage plus 10 (3d6) poison damage."
    "name": "Shortsword +2"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target. *Hit:*\
      \ 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.\
      \ The target wakes up if it takes damage or if another creature takes an action\
      \ to shake it awake."
    "name": "Hand Crossbow +1"
"reactions":
  - "desc": "The drow adds 3 to its AC against one melee attack that would hit it.\
      \ To do so, the drow must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/drow-commander-tftyp.webp"
```
^statblock