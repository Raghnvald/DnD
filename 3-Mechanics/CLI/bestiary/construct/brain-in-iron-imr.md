---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Brain in Iron"
---
# [Brain in Iron](3-Mechanics/CLI/bestiary/construct/brain-in-iron-imr.md)
*Source: Infernal Machine Rebuild p. 48*  

```statblock
"name": "Brain in Iron (IMR)"
"size": "Large"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "15"
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
"speed": "20 ft."
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
  - "desc": "The brain in iron's innate spellcasting ability is Intelligence (spell\
      \ save DC 15). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [zone of truth](3-Mechanics/CLI/spells/zone-of-truth.md)\n\
      \n**3/day each:** [charm person](3-Mechanics/CLI/spells/charm-person.md), [command](3-Mechanics/CLI/spells/command.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person.md)\n\n**1/day each:** [compulsion](3-Mechanics/CLI/spells/compulsion.md),\
      \ [hold monster](3-Mechanics/CLI/spells/hold-monster.md), [sleep](3-Mechanics/CLI/spells/sleep.md)\
      \ (cast at 3rd level), [Tasha's hideous laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The brain in iron can sense the presence and location of any creature\
      \ within 300 feet of it that has an Intelligence of 3 or higher, regardless\
      \ of interposing barriers, unless the creature is protected by a [mind blank](3-Mechanics/CLI/spells/mind-blank.md)\
      \ spell."
    "name": "Detect Sentience"
  - "desc": "The brain in iron has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The brain in iron magically emits psychic energy in a 60-foot cone. Each\
      \ creature in that area must succeed on a DC 15 Intelligence saving throw or\
      \ take 13 (2d8 + 4) psychic damage and be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/construct/token/brain-in-iron-imr.webp"
```
^statblock