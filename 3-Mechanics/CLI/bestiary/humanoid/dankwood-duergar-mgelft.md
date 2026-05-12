---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mgelft
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dankwood Duergar"
---
# [Dankwood Duergar](3-Mechanics/CLI/bestiary/humanoid/dankwood-duergar-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 32*  

Dankwood duergar live in the deep caves below and are constantly on the search for treasure and magical discoveries they can claim as their own. Like their dwarven relatives, the Dankwood duergar are masters at crafting, but never seem to be happy or satisfied with their creations.

Some say that their constant pouting is what allows them the magical ability to double in size and strength for short moments. Now that's a temper tantrum!

```statblock
"name": "Dankwood Duergar (MGELFT)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "lawful grumpy"
"ac": !!int "18"
"ac_class": "Plate Mail"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
  - "desc": "The Dankwood duergar has advantage on saving throws against poison, spells,\
      \ and illusions, as well as to resist being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)."
    "name": "Duergar Resilience"
  - "desc": "While in sunlight, the Dankwood duergar has disadvantage on attack rolls,\
      \ as well as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The duergar unleashes a string of insults laced with subtle enchantments\
      \ at a creature they can see within 60 feet. If the creature can hear them (it\
      \ doesn't need to understand them), it must succeed on a DC 12 Wisdom saving\
      \ throw or take 1d4 psychic damage and have disadvantage on the next attack\
      \ roll it makes before the end of its next turn."
    "name": "Verbal Jab"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d6 + 6) bludgeoning damage. If the duergar is enlarged, increase their\
      \ damage to 10 (2d6 + 3) bludgeoning damage."
    "name": "Haymaker"
"source":
  - "MGELFT"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dankwood-duergar-mgelft.webp"
```
^statblock