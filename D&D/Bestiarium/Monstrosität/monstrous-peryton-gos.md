---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Monstrous Peryton
linter-yaml-title-alias: Monstrous Peryton
tags:
  - Monster/Größe/Groß
  - Monster/HG/11
  - Monster/Typ/Monstrosität
  - Quelle/5e/gos
aliases:
  - Monstrous Peryton
---
# [Monstrous Peryton](3-Mechanics\CLI\bestiary\monstrosity/monstrous-peryton-gos.md)
*Source: Ghosts of Saltmarsh p. 245*  

The terror of the coast and the recent scourge of Firewatch Island in Tammeraut's Fate, this large peryton preys on ships and coastal communities alike. It has built numerous nests to mark its territory.

```statblock
"name": "Monstrous Peryton (GoS)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d10 + 51"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "9"
  - !!int "14"
  - !!int "10"
"speed": "20 ft., fly 60 ft."
"saves":
  - "strength": !!int "8"
  - "dexterity": !!int "6"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "understands Common and Elvish but can't speak"
"cr": "11"
"traits":
  - "desc": "The peryton doesn't provoke opportunity attacks when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
  - "desc": "The peryton has advantage on Wisdom (Perception) checks that rely on\
      \ sight or smell."
    "name": "Keen Sight and Smell"
  - "desc": "If the peryton fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The peryton makes two attacks: one with its gore and one with its talons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) slashing damage."
    "name": "Talons"
  - "desc": "The peryton chooses up to three creatures within 60 feet of it that it\
      \ can see. Each creature must succeed on a DC 14 Wisdom saving throw or become\
      \ cursed. While cursed, whenever the creature makes an attack roll, an ability\
      \ check, or a saving throw, it must roll a d4 and subtract that number from\
      \ the roll. A cursed creature can repeat this saving throw at the end of each\
      \ of its turns, ending the effect on itself with a success. A creature that\
      \ succeeds on this saving throw is immune to this peryton's Warp Shadow for\
      \ 24 hours."
    "name": "Warp Shadow"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the monstrous peryton can expend a use to take one of the following actions.\
  \ The monstrous peryton regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The peryton makes a Wisdom (Perception) check."
    "name": "Detect"
  - "desc": "The peryton makes one attack with its talons."
    "name": "Talons Attack"
  - "desc": "The peryton moves up to its speed toward one target of its choosing.\
      \ It then makes a gore attack that deals an extra 9 (2d8) piercing damage on\
      \ a hit."
    "name": "Dive Attack (Costs 2 Actions)"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/monstrous-peryton-gos.webp"
```
^statblock