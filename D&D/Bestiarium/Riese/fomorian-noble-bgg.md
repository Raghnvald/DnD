---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fomorian Noble
linter-yaml-title-alias: Fomorian Noble
tags:
  - Monster/Größe/Riesig
  - Monster/HG/15
  - Monster/Typ/Riese/wizard
  - Quelle/5e/bgg
aliases:
  - Fomorian Noble
---
# [Fomorian Noble](3-Mechanics\CLI\bestiary\giant/fomorian-noble-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 143*  

Before their banishment to the Underdark, fomorians ordered themselves based on achievements of knowledge and magical power. Before Karontor urged his descendants into an ill-fated assault against the Feywild, some of the most ambitious, inquisitive, and power-hungry fomorians felt they had already learned all they could from the Material Plane, and they departed to the Inner Planes, where they could continue their journeys of knowledge unopposed.

In their arrogance, these fomorian nobles unknowingly escaped the dreadful fate of their kin, and they remain unchanged in their remote enclaves. Occasionally they return to the Material Plane to survey the world they left. With angular features and apparently ageless faces, these fomorians resemble gigantic elves.

> [!quote] A quote from Diancastra  
> 
> The fomorian nobles I have met are so utterly unrepentant and so unmoved by the plight of their cursed kindred that I struggle to embrace them as my cousins.

## Fomorians

Descended from Annam's son Karontor, fomorians once occupied a place in the giants' ordning between hill and stone giants. In ancient times, they were scholars of magic known for their keen intellect—but also for their inflated egos and sense of entitlement. Karontor exploited these qualities, tempting them with promises of higher standing in the ordning, and incited his descendants to launch an assault on the Feywild. When the assault failed, the fomorians were banished to the Underdark and their god was consigned to a subterranean prison. Subjected to the strange magic of the Underdark, the fomorians' bodies and souls twisted until they became the fomorians of today.

```statblock
"name": "Fomorian Noble (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "wizard"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "17 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "253"
"hit_dice": "22d12 + 110"
"modifier": !!int "4"
"stats":
  - !!int "23"
  - !!int "18"
  - !!int "20"
  - !!int "19"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+14"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "passive Perception 17"
"languages": "Giant plus any three languages"
"cr": "15"
"actions":
  - "desc": "The fomorian makes three Rod attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage plus 11 (2d10) force damage."
    "name": "Rod"
  - "desc": "The fomorian casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\n**At will:** [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)\
      \ (self only), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md), [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\
      \n**1/day each:** [chain lightning](/3-Mechanics/CLI/spells/chain-lightning-xphb.md),\
      \ [cone of cold](/3-Mechanics/CLI/spells/cone-of-cold-xphb.md) (6th-level version),\
      \ [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md) (6th-level version),\
      \ [fly](/3-Mechanics/CLI/spells/fly-xphb.md), [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ (self only)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The fomorian targets a creature it can see within 60 feet of itself.\
      \ The target must succeed on a DC 17 Wisdom saving throw or have the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ condition for 1 minute. An affected target can repeat the saving throw at\
      \ the end of each of its turns and whenever it takes damage, ending the effect\
      \ on itself on a success. If a target's saving throw is successful or the effect\
      \ ends for it, the target becomes immune to all fomorians' Beguiling Presence\
      \ for the next 24 hours."
    "name": "Beguiling Presence"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/fomorian-noble-bgg.webp"
```
^statblock