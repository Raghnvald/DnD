---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/sorcerer
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Occult Initiate"
---
# [Occult Initiate](3-Mechanics/CLI/bestiary/humanoid/occult-initiate-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 205*  

Occult initiates are the most recent inductees into their organization and the members of the organization most often encountered by outsiders.

## Occultists of the Vermilion Dream

The Consortium of the Vermilion Dream is viewed as an esoteric, profit-driven, but ultimately harmless cabal of ghost hunters and perpetuators of urban legends. This perception isn't inaccurate, but the consortium's leadership is obsessed with one set of legends in particular: those involving the Moon of Ill Omen, Ruidus, and the ancient figures cursed by exposure to its alien influence.

The cruelest desires and predilections of the consortium's most obsessive agents have been enhanced by contact with ruidium-tainted items.

```statblock
"name": "Occult Initiate (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "sorcerer"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "Deception"
    "desc": "+5"
  - "name": "History"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+2"
"gear":
  - "shortsword"
"senses": "passive Perception 12"
"languages": "Common plus one other language"
"cr": "2"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage plus 7 (2d6) psychic damage."
    "name": "Shortsword"
  - "desc": "The initiate creates an explosion of magical force in a 20-foot-radius\
      \ sphere centered on a point it can see within 120 feet of itself. Each creature\
      \ in that area must make a DC 13 Dexterity saving throw. On a failed saving\
      \ throw, the creature takes 10 (3d6) force damage and is pushed 10 feet away\
      \ from the center of the area. On a successful save, it takes half as much damage\
      \ and isn't pushed."
    "name": "Arcane Blast (Recharge 5-6)"
  - "desc": "The initiate casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 13):\n\
      \n**At will:** light, mage hand\n\n**1/day each:** detect magic, levitate"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/occult-initiate-crcotn.webp"
```
^statblock