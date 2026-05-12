---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grazilaxx"
---
# [Grazilaxx](3-Mechanics/CLI/bestiary/npc/grazilaxx-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Grazilaxx (OotA)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "12"
  - !!int "18"
  - !!int "17"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Deep Speech, Undercommon, telepathy 120 ft., Dwarvish, Elvish"
"cr": "7"
"traits":
  - "desc": "Grazilaxx can innately cast can cast the [teleport](3-Mechanics/CLI/spells/teleport.md)\
      \ spell once per day, but the intended destination must be within 30 feet of\
      \ another society member. This teleport effect can be disrupted (see \"Faerzress\"\
      ), which is how society members sometimes end up in far corners of the Underdark,\
      \ separated from their fellows.\n"
    "name": "Innate Spellcasting"
  - "desc": "Grazilaxx's innate spellcasting ability is Intelligence (spell save DC\
      \ 15). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [levitate](3-Mechanics/CLI/spells/levitate.md)\n\n**1/day each:** [dominate\
      \ monster](3-Mechanics/CLI/spells/dominate-monster.md), [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "Grazilaxx has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:*\
      \ 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it is\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15) and\
      \ must succeed on a DC 15 Intelligence saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until this grapple ends."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ humanoid [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by Grazilaxx.\
      \ *Hit:* The target takes 55 (10d10) piercing damage. If this damage reduces\
      \ the target to 0 hit points, Grazilaxx kills the target by extracting and devouring\
      \ its brain."
    "name": "Extract Brain"
  - "desc": "Grazilaxx magically emits psychic energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 15 Intelligence saving throw or take 22\
      \ (4d8 + 4) psychic damage and be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/grazilaxx-oota.webp"
```
^statblock