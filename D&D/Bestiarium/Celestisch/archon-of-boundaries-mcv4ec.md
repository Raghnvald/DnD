---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/15
  - Monster/Größe/Riesig
  - Monster/Typ/Himmlische
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Archon of Boundaries
---
# [Archon of Boundaries](3-Mechanics\CLI\bestiary\celestial/archon-of-boundaries-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

The archons of Eldraine are enigmatic beings who fly over the perimeter where the realm meets the wilds, marking the boundary between safety (for the people of the realm) and danger. The sight of an archon overhead is a clear signal that one is entering the wilds.

An archon appears as a hooded, spectral rider mounted on a winged elk with glowing antlers and gleaming eyes. Despite this appearance, rider and mount are a single creature that can't be separated. Tales say that archons are ascended spirits of paladins fused with the celestial spirits of their steeds, returned from the celestial realms to watch over the boundary of the wilds and protect those who dare to cross it.

Sometimes knights of the realm get the idea that they can expand the borders of their land and keep the wilds at bay simply by driving archons deeper into the wilds. Such efforts are futile; not only are archons difficult to kill, but they don't create the boundaries, merely mark them.

> [!quote] A quote from Chulane, Teller of Tales  
> 
> A winged dawn dispels the terror of night.


```statblock
"name": "Archon of Boundaries (MCV4EC)"
"size": "Huge"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "17"
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "18"
"speed": "60 ft., fly 90 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "Insight"
    "desc": "+9"
  - "name": "Perception"
    "desc": "+9"
"damage_resistances": "radiant"
"condition_immunities": "exhaustion"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "understands Common and Celestial but can't speak"
"cr": "15"
"traits":
  - "desc": "If the archon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The archon has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The archon makes one Hooves attack and one Radiant Lance attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (4d6 + 6) bludgeoning damage plus 10 (3d6) radiant damage. If the target is\
      \ a Medium or smaller creature, it must succeed on a DC 19 Strength saving throw\
      \ or have the prone condition."
    "name": "Hooves"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 12\
      \ (1d12 + 6) piercing damage plus 28 (8d6) radiant damage, and the target is\
      \ marked until the start of the archon's next turn. While it is marked, the\
      \ target has disadvantage on attack rolls against creatures other than the archon."
    "name": "Radiant Lance"
  - "desc": "The archon casts one of the following spells, using Charisma as the spellcasting\
      \ ability:\n\n**1/day each:** daylight, lesser restoration"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature marked by the archon's Radiant Lance ends its turn within\
      \ 120 feet of the archon, the archon teleports to an unoccupied space it can\
      \ see within 5 feet of the creature."
    "name": "Archon's Pursuit"
  - "desc": "Immediately after a creature within 120 feet of the archon forces it\
      \ to make a saving throw, the archon responds with a burst of light. The creature\
      \ must succeed on a DC 17 Constitution saving throw or have the blinded condition\
      \ until the end of the creature's next turn."
    "name": "Haunting Radiance"
  - "desc": "The archon adds 5 to its AC against one melee attack that would hit it,\
      \ provided it can see the attacker."
    "name": "Parry"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/archon-of-boundaries-mcv4ec.webp"
```
^statblock