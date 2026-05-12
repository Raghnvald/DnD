---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/celestial/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kopoha"
---
# [Kopoha](3-Mechanics/CLI/bestiary/npc/kopoha-tofw.md)
*Source: Turn of Fortune's Wheel p. 61*  

```statblock
"name": "Kopoha (ToFW)"
"size": "Huge"
"type": "celestial"
"subtype": "titan"
"alignment": "Chaotic Good"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "313"
"hit_dice": "19d12 + 190"
"modifier": !!int "5"
"stats":
  - !!int "30"
  - !!int "21"
  - !!int "30"
  - !!int "21"
  - !!int "22"
  - !!int "27"
"speed": "50 ft., fly 50 ft., swim 50 ft."
"saves":
  - "strength": !!int "17"
  - "intelligence": !!int "12"
  - "wisdom": !!int "13"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+13"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+15"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"gear":
  - "[maul](3-Mechanics/CLI/items/maul-xphb.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 16"
"languages": "all"
"cr": "23"
"traits":
  - "desc": "Kopoha's innate spellcasting ability is Charisma (spell save DC 23, +15\
      \ to hit with spell attacks). It can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** [greater restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md),\
      \ [pass without trace](3-Mechanics/CLI/spells/pass-without-trace-xphb.md), [water\
      \ breathing](3-Mechanics/CLI/spells/water-breathing-xphb.md), [water walk](3-Mechanics/CLI/spells/water-walk-xphb.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune-xphb.md), [dispel\
      \ evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md), [earthquake](3-Mechanics/CLI/spells/earthquake-xphb.md),\
      \ [fire storm](3-Mechanics/CLI/spells/fire-storm-xphb.md), [plane shift](3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ (self only)"
    "name": "Innate Spellcasting"
  - "desc": "If Kopoha fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Kopoha has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Kopoha's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "*Ranged Spell Attack:* +15 to hit, range 600 ft., one target. *Hit:*\
      \ 24 (7d6) damage of one of the following types (empyrean's choice): acid,\
      \ cold, fire, force, lightning, radiant, or thunder."
    "name": "Bolt"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Kopoha can expend a use to take one of the following actions. Kopoha regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Kopoha makes one attack."
    "name": "Attack"
  - "desc": "Kopoha bolsters all nonhostile creatures within 120 feet of it until\
      \ the end of its next turn. Bolstered creatures can't be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), and they\
      \ gain advantage on ability checks and saving throws until the end of Kopoha's\
      \ next turn."
    "name": "Bolster"
  - "desc": "Kopoha strikes the ground with its maul, triggering an earth tremor.\
      \ All other creatures on the ground within 60 feet of Kopoha must succeed on\
      \ a DC 25 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Trembling Strike (Costs 2 Actions)"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/kopoha-tofw.webp"
```
^statblock