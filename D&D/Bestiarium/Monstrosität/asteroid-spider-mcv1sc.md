---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/mcv1sc
- Monster/HG/15
- Monster/Größe/Gigantisch
- Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
- Asteroid Spider
---
# [Asteroid Spider](3-Mechanics\CLI\bestiary\monstrosity/asteroid-spider-mcv1sc.md)
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 3*  

An asteroid spider is a menace native to Wildspace and the Astral Sea. A full-grown specimen has a body 30 feet in diameter and legs that are at least 30 feet long. When it wraps its legs tightly around its body and closes its eyes, the asteroid spider resembles nothing so much as a giant, lifeless rock in space—hence its name.

An asteroid spider has its own gravity plane and air envelope, as well as multiple spinnerets with which it can create web strands. Its living brain functions like a *spelljamming helm*, allowing the spider to travel through Wildspace without a ship. It often haunts asteroid belts, lurking among normal asteroids until a spelljamming ship comes close enough to be detected. The spider then snares the ship before using web strands to catch crew members and reel them toward its snapping jaws.

```statblock
"name": "Asteroid Spider (MCV1SC)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "348"
"hit_dice": "24d20 + 96"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "18"
  - !!int "17"
  - !!int "13"
  - !!int "12"
"speed": "60 ft., fly 60 ft. (hover)"
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Perception"
    "desc": "+11"
  - "name": "Stealth"
    "desc": "+5"
"senses": "blindsight 120 ft. while the spider's eyes are closed, darkvision 120 ft.,\
  \ passive Perception 21"
"languages": ""
"cr": "15"
"traits":
  - "desc": "If the spider is motionless, has its eyes and mouth closed, and has its\
      \ legs wrapped around its body at the start of combat, it has advantage on its\
      \ initiative roll. Moreover, if a creature hasn't observed the spider move or\
      \ act, that creature must succeed on a DC 18 Intelligence (Investigation) check\
      \ to discern that the spider is anything other than an asteroid."
    "name": "False Appearance"
  - "desc": "If the spider fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The spider doesn't require air."
    "name": "Unusual Nature"
"actions":
  - "desc": "The spider makes two Web Strand attacks, uses Reel, and makes two Bite\
      \ attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:* 21\
      \ (3d8 + 8) piercing damage plus 10 (3d6) acid damage."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +13 to hit, reach 120 ft., one creature. *Hit:*\
      \ The target is grappled (escape DC 18). The web strand can be attacked and\
      \ destroyed (AC 12; 20 hit points; vulnerability to fire damage; immunity to\
      \ bludgeoning, poison, and psychic damage). The spider can grapple up to six\
      \ creatures at a time using its web strands."
    "name": "Web Strand"
  - "desc": "The spider pulls each creature grappled by it up to 60 feet straight\
      \ toward itself."
    "name": "Reel"
"bonus_actions":
  - "desc": "The spider weaves a magical web around a spelljamming ship it can see\
      \ within 120 feet of itself. The web lasts for 1 minute and suppresses the magic\
      \ of any spelljamming helm aboard the ship. Decks and other surfaces of the\
      \ ship that aren't enclosed become difficult terrain until the effect ends.\
      \ The web is impervious to damage but is destroyed by a successful casting of\
      \ dispel magic (DC 18)."
    "name": "Snare Ship (1/Day)"
"source":
  - "MCV1SC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/asteroid-spider-mcv1sc.webp"
```
^statblock