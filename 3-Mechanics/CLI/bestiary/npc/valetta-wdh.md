---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dragonborn
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Valetta"
---
# [Valetta](3-Mechanics/CLI/bestiary/npc/valetta-wdh.md)
*Source: Waterdeep: Dragon Heist p. 47*  

A dragonborn priest of bronze dragon ancestry.

```statblock
"name": "Valetta (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "[chain shirt](3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "25 ft."
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"damage_resistances": "lightning"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace-xphb.md)"
"senses": "passive Perception 13"
"languages": "Common, Draconic"
"cr": "2"
"traits":
  - "desc": "Valetta is a 5th-level spellcaster. Her spellcasting ability is Wisdom.\
      \ Valetta has the following cleric spells prepared:\n\n**Cantrips (at will):**\
      \ [light](3-Mechanics/CLI/spells/light-xphb.md), [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md),\
      \ [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**1st level (4\
      \ slots):** [cure wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md), [guiding\
      \ bolt](3-Mechanics/CLI/spells/guiding-bolt-xphb.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary-xphb.md)\n\
      \n**2nd level (3 slots):** [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md),\
      \ [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\n\n**3rd\
      \ level (2 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [spirit guardians](3-Mechanics/CLI/spells/spirit-guardians-xphb.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, Valetta can expend a spell slot to cause her melee\
      \ weapon attacks to magically deal an extra 10 (3d6) radiant damage to a target\
      \ on a hit. This benefit lasts until the end of the turn. If Valetta expends\
      \ a spell slot of 2nd level or higher, the extra damage increases by 1d6 for\
      \ each level above 1st."
    "name": "Divine Eminence"
"actions":
  - "desc": "Valetta can use her action to exhale a 5-foot-wide, 30-foot line of lightning\
      \ (but can't do this again until she finishes a short or long rest); each creature\
      \ in the line must make a DC 11 Dexterity saving throw, taking 2d6 lightning\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Breathe Weapon"
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d6) bludgeoning damage."
    "name": "Mace"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/valetta-wdh.webp"
```
^statblock