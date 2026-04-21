---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Forest Master
tags:
  - Monster/Größe/Groß
  - Monster/HG/8
  - Monster/Typ/Himmlische/unicorn
  - Quelle/5e/mcv2dc
aliases:
  - Forest Master
---
# [Forest Master](3-Mechanics\CLI\bestiary\celestial/forest-master-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 6*  

Said to be older than the trees themselves, the Forest Master is a wise and powerful unicorn who rules over the creatures of Darken Wood in Krynn. The ancient being's body is wreathed in protective briars, and moonlight dances around the unicorn's horn. Those who threaten the Forest Master's lands find themselves beguiled by magical mist and nigh-impregnable thorny thickets, but those who gain the Forest Master's favor are blessed with healing and protected as they traverse the woods.

```statblock
"name": "Forest Master (MCV2DC)"
"size": "Large"
"type": "celestial"
"subtype": "unicorn"
"alignment": "Neutral Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d10 + 28"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "13"
  - !!int "19"
  - !!int "17"
"speed": "50 ft."
"saves":
  - "intelligence": !!int "4"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Nature"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+7"
"damage_immunities": "poison"
"condition_immunities": "charmed, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Celestial, Elvish, Sylvan, telepathy 60 ft."
"cr": "8"
"traits":
  - "desc": "If the Forest Master fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "The Forest Master has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The Forest Master can comprehend and communicate with any Beast, even\
      \ if the Beast knows no languages."
    "name": "Master of Beasts"
"actions":
  - "desc": "The Forest Master makes either two Hooves attacks, two Moon Bolt attacks,\
      \ or one of each."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Hooves"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 60 ft., one target. *Hit:* 11\
      \ (2d6 + 4) radiant damage."
    "name": "Moon Bolt"
  - "desc": "The Forest Master casts one of the following spells, requiring no material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** druidcraft, fog cloud, guidance\n\n**2/day each:** goodberry,\
      \ greater restoration, pass without trace, speak with plants"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The Forest Master touches his horn to the earth and causes a 5-foot-tall\
      \ wall of briars to erupt in a 90-foot line that is 10 feet wide. When the wall\
      \ appears, each creature in its area is pushed into the nearest unoccupied space\
      \ adjacent to the wall and must make a DC 15 Dexterity saving throw, taking\
      \ 27 (6d8) piercing damage on a failed save or half as much damage on a successful\
      \ one.\n\nThe wall of briars lasts until the start of the Forest Master's next\
      \ turn. The wall blocks line of sight and counts as difficult terrain for all\
      \ creatures except the Forest Master. The first time a creature enters the wall's\
      \ area on a turn, that creature must succeed on a DC 15 Dexterity saving throw\
      \ or take 13 (3d8) piercing damage."
    "name": "Erupting Briars (Recharge 4-6)"
"reactions":
  - "desc": "If the Forest Master takes damage from a melee attack, he, along with\
      \ any equipment he is wearing or carrying, teleports to an unoccupied space\
      \ within 30 feet that he can see."
    "name": "Misty Escape"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/forest-master-mcv2dc.webp"
```
^statblock