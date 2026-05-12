---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Blurg"
---
# [Blurg](3-Mechanics/CLI/bestiary/npc/blurg-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Blurg (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "42"
"hit_dice": "5d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "18"
  - !!int "18"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+2"
"gear":
  - "[greataxe](3-Mechanics/CLI/items/greataxe.md)"
  - "[javelin](3-Mechanics/CLI/items/javelin.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Orc, Dwarvish, Elvish, Undercommon"
"cr": "2"
"traits":
  - "desc": "Blurg can innately cast can cast the [teleport](3-Mechanics/CLI/spells/teleport.md)\
      \ spell once per day, but the intended destination must be within 30 feet of\
      \ another society member. This teleport effect can be disrupted (see \"Faerzress\"\
      ), which is how society members sometimes end up in far corners of the Underdark,\
      \ separated from their fellows.\n"
    "name": "Innate Spellcasting"
  - "desc": "As a bonus action, Blurg can move up to its speed toward a hostile creature\
      \ that it can see."
    "name": "Aggressive"
"actions":
  - "desc": "Blurg makes two greataxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) slashing damage."
    "name": "Greataxe"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage."
    "name": "Javelin"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/blurg-oota.webp"
```
^statblock