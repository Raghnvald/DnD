---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/derro
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Buppido"
---
# [Buppido](3-Mechanics/CLI/bestiary/npc/buppido-oota.md)
*Source: Out of the Abyss p. 6*  

```statblock
"name": "Buppido (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "5"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"gear":
  - "[hooked shortspear](3-Mechanics/CLI/items/hooked-shortspear-oota.md)"
  - "[light repeating crossbow](3-Mechanics/CLI/items/light-repeating-crossbow-oota.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "1/4"
"traits":
  - "desc": "Buppido has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Insanity"
  - "desc": "Buppido has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, Buppido has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 1\
      \ (1d4 - 1) piercing damage. If the target is a creature, Buppido can choose\
      \ to deal no damage and try to trip the target instead, in which case the target\
      \ must succeed on a DC 9 Strength saving throw or fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Hooked Shortspear"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 40/160 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Light Repeating Crossbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/buppido-oota.webp"
```
^statblock