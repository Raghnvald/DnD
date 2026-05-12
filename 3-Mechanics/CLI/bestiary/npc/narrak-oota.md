---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/derro
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Narrak"
---
# [Narrak](3-Mechanics/CLI/bestiary/npc/narrak-oota.md)
*Source: Out of the Abyss p. 232*  

```statblock
"name": "Narrak (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d6 + 9"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "5"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
  - "desc": "Narrak is a 5th-level spellcaster. His spellcasting ability is Charisma\
      \ (Save DC 13, +5 to hit with spell attacks) Narrak has two 2nd-level spell\
      \ slots, which he regains after finishing a short or long rest, and knows the\
      \ following warlock spells:\n\n**Cantrips (at will):** [eldritch blast](3-Mechanics/CLI/spells/eldritch-blast.md),\
      \ [friends](3-Mechanics/CLI/spells/friends.md), [poison spray](3-Mechanics/CLI/spells/poison-spray.md)\n\
      \n**1st-2nd level (2 slots):** [armor of Agathys](3-Mechanics/CLI/spells/armor-of-agathys.md),\
      \ [charm person](3-Mechanics/CLI/spells/charm-person.md), [hex](3-Mechanics/CLI/spells/hex.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person.md), [ray of enfeeblement](3-Mechanics/CLI/spells/ray-of-enfeeblement.md),\
      \ [spider climb](3-Mechanics/CLI/spells/spider-climb.md)"
    "name": "Spellcasting"
  - "desc": "Narrak has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Insanity"
  - "desc": "Narrak has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, Narrak has disadvantage on attack rolls, as well as\
      \ on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Narrak casts [mage armor](3-Mechanics/CLI/spells/mage-armor.md) on himself"
    "name": "Armor of Shadows (Recharges after a Short or Long Rest)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "While he is in a dim light or darkness, Narrak can become [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible).\
      \ He remains so until he moves or takes an action or reaction."
    "name": "One with Shadows"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/narrak-oota.webp"
```
^statblock