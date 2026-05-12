---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/llk
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Brain in a Jar"
---
# [Brain in a Jar](3-Mechanics/CLI/bestiary/undead/brain-in-a-jar-llk.md)
*Source: Lost Laboratory of Kwalish p. 38*  

```statblock
"name": "Brain in a Jar (LLK)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "-5"
"stats":
  - !!int "1"
  - !!int "1"
  - !!int "15"
  - !!int "19"
  - !!int "10"
  - !!int "15"
"speed": "0 ft."
"saves":
  - "intelligence": !!int "7"
  - "charisma": !!int "5"
"damage_immunities": "necrotic, poison, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "6"
"traits":
  - "desc": "The brain in a jar's innate spellcasting ability is Intelligence (spell\
      \ save DC 15). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [zone of truth](3-Mechanics/CLI/spells/zone-of-truth.md)\n\
      \n**3/day each:** [charm person](3-Mechanics/CLI/spells/charm-person.md), [command](3-Mechanics/CLI/spells/command.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person.md)\n\n**1/day each:** [compulsion](3-Mechanics/CLI/spells/compulsion.md),\
      \ [hold monster](3-Mechanics/CLI/spells/hold-monster.md), [sleep](3-Mechanics/CLI/spells/sleep.md)\
      \ (cast at 3rd level), [Tasha's hideous laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The brain in a jar can sense the presence and location of any creature\
      \ within 300 feet of it that has an Intelligence of 3 or higher, regardless\
      \ of interposing barriers, unless the creature is protected by a [mind blank](3-Mechanics/CLI/spells/mind-blank.md)\
      \ spell."
    "name": "Detect Sentience"
  - "desc": "The brain in a jar has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The brain in a jar magically emits psychic energy in a 60-foot cone.\
      \ Each creature in that area must succeed on a DC 15 Intelligence saving throw\
      \ or take 13 (2d8 + 4) psychic damage and be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
"source":
  - "LLK"
"image": "3-Mechanics/CLI/bestiary/undead/token/brain-in-a-jar-llk.webp"
```
^statblock