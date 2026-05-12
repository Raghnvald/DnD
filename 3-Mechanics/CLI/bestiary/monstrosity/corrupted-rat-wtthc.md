---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Corrupted Rat"
---
# [Corrupted Rat](3-Mechanics/CLI/bestiary/monstrosity/corrupted-rat-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Corrupted by a malevolent ex-adventurer's magic, the rats of Elmshire are mottled and sickly. Their organs glow and bubble beneath their scabby hides as if ready to pop. These pests sometimes gather in squeaking tides, devouring everything in their path.

```statblock
"name": "Corrupted Rat (WttHC)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "0"
"stats":
  - !!int "2"
  - !!int "11"
  - !!int "9"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "20 ft., climb 20 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The rat doesn't provoke Opportunity Attacks when it moves out of an enemy's\
      \ reach."
    "name": "Agile"
  - "desc": "The rat explodes when it dies. *Constitution Saving Throw:* DC 9, each\
      \ creature in a 5-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the rat. *Failure:* 1 Acid damage."
    "name": "Death Burst"
"actions":
  - "desc": "*Melee Attack Roll:* +2, reach 5 ft. *Hit:* 1 Piercing damage."
    "name": "Bite"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/corrupted-rat-wtthc.webp"
```
^statblock