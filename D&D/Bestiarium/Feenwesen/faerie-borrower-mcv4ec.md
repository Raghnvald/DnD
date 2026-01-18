---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/1-2
  - Monster/Größe/Winzig
  - Monster/Typ/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Faerie Borrower
---
# [Faerie Borrower](3-Mechanics\CLI\bestiary\fey/faerie-borrower-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Faerie borrowers are tiny thieves who steal whatever they can lay their hands on to cause confusion and consternation. A faerie borrower stands less than six inches tall, with blue or blue-gray skin and wings resembling shards of broken glass.

Faerie borrowers often adorn themselves with purloined trophies: stolen keys and needles filed into swords, and buttons and scraps of paper fashioned into clothing. Though they are often boastful and love to mock their victims, faerie borrowers are quick to dart away from losing battles on their nimble wings.

> [!quote]  
> 
> The throng of faeries flitted from castle to castle, leaving a trail of star-crossed love, damaging rumors, and missing heirlooms in their wake.

## Faeries

The faeries of Eldraine are winged, elfin creatures similar to sprites or pixies. Unpredictable, unreliable, and amoral, they lurk in the wilds and harass travelers they perceive as intruders.

> [!note] Ouphes
> 
> Ouphes are curious creatures found throughout the wilds of Eldraine. While often seen as foolish, ouphes are magically connected to the natural world and know more about the secret lives of trees, mushrooms, and moss than most mortals. While ouphes are related to Eldraine's faeries, the faeries treat them like distant (and somewhat embarrassing) cousins. Ouphes can be represented with the stat blocks for pixies or sprites.
^ouphes

```statblock
"name": "Faerie Borrower (MCV4EC)"
"size": "Tiny"
"type": "fey"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "12"
"hit_dice": "5d4"
"modifier": !!int "5"
"stats":
  - !!int "2"
  - !!int "20"
  - !!int "10"
  - !!int "13"
  - !!int "12"
  - !!int "16"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  - "name": "Sleight of Hand"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+7"
"senses": "passive Perception 11"
"languages": "Common, Sylvan"
"cr": "1/2"
"traits":
  - "desc": "The faerie doesn't provoke opportunity attacks when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d4\
      \ + 5) piercing damage."
    "name": "Needle Blade"
  - "desc": "The faerie hurls magical taunts at one creature it can see within 60\
      \ feet of itself. The creature must succeed on a DC 13 Wisdom saving throw or\
      \ take 3 (1d6) psychic damage and have disadvantage on attack rolls and ability\
      \ checks until the start of the faerie's next turn."
    "name": "Magic Mockery"
  - "desc": "The faerie casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** prestidigitation\n\n**1/day:** silent image"
    "name": "Spellcasting"
"reactions":
  - "desc": "Immediately after taking damage, the faerie reduces the damage taken\
      \ by 2 (1d4)."
    "name": "Tricksy Parry"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/faerie-borrower-mcv4ec.webp"
```
^statblock