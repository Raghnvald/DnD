---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv2dc
  - Monster/HG/5
  - Monster/Größe/Groß
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Traag Draconian
---
# [Traag Draconian](3-Mechanics\CLI\bestiary\monstrosity/traag-draconian-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 13*  

In their experimentation with corrupting dragon eggs, the Dragon Armies created traag draconians, the precursor to what would become baaz draconian foot soldiers. Unlike their draconian brethren, traag draconians are little more than bloodthirsty engines of carnage. Few commanders have successfully used a traag draconian's reckless violence to their advantage in battle; for most, a traag draconian is as much of a danger to its allies as it is to its enemies. Even magic cannot tame a traag draconian's thirst for violence.

A traag draconian's vestigial wings lack the strength to support its hulking body in true flight, and they only minimally help to slow a falling traag's descent. Its metallic scales are coated in a sickly patina. In battle, the draconian can charge its body with vicious fire, burning all in its wake. When a traag draconian dies, its body explodes in a thick, disgusting sludge.

```statblock
"name": "Traag Draconian (MCV2DC)"
"size": "Large"
"type": "monstrosity"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "10"
  - !!int "17"
  - !!int "6"
  - !!int "8"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "strength": !!int "8"
  - "constitution": !!int "6"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "5"
"traits":
  - "desc": "The draconian has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "If the draconian falls and isn't incapacitated, it subtracts up to 50\
      \ feet from the fall when calculating the fall's damage."
    "name": "Controlled Fall"
  - "desc": "If the draconian is reduced to 0 hit points, its body erupts into sludge\
      \ that fills a 10-foot-radius sphere. Each creature within that area must succeed\
      \ on a DC 14 Dexterity saving throw or be covered in the sludge for 1 minute.\
      \ While covered in the sludge, a creature's speed is halved. A creature can\
      \ use its action to scrape the sludge off itself or another creature within\
      \ 5 feet of itself."
    "name": "Death Throes"
"actions":
  - "desc": "The draconian makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 14\
      \ (2d8 + 5) slashing damage."
    "name": "Claw"
  - "desc": "The draconian indulges its rage, wreathing itself in fire and moving\
      \ up to its speed. The draconian can enter creatures' spaces during this move.\
      \ During this movement, when the draconian enters a creature's space, the creature\
      \ must make a DC 14 Dexterity saving throw. On a failed save, the creature takes\
      \ 22 (4d10) fire damage and is knocked prone. On a successful save, the creature\
      \ takes half as much damage and is pushed to the nearest space out of the draconian's\
      \ path. A creature can be affected by this draconian's Flaming Carnage only\
      \ once during a turn."
    "name": "Flaming Carnage (Recharge 5-6)"
"reactions":
  - "desc": "If a creature within 10 feet of the draconian hits it with an attack,\
      \ the draconian can make one Claw attack against that creature. If the Claw\
      \ attack hits, it deals an additional 4 (1d8) slashing damage."
    "name": "Violent Retaliation"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/traag-draconian-mcv2dc.webp"
```
^statblock