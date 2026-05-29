---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Animated Table
Kategorie: Konstrukt
Größe: Groß
HG: "2"
Habitat:
  - /
status: WIP
linter-yaml-title-alias: Animated Table
tags:
  - Monster/Größe/Groß
  - Monster/HG/2
  - Monster/Typ/Konstrukt
  - Quelle/5e/tftyp
aliases:
  - Animated Table
---
# [Animated Table](3-Mechanics\CLI\bestiary\construct/animated-table-tftyp.md)
*Source: Tales from the Yawning Portal p. 230*  

## Arundil's Animated Objects

A century ago, the dwarf mage Arundil animated a number of objects to defend the Foundry against intruders other than dwarves. Many of these creations remain in place today.

These animated objects never attack dwarves or duergar. In addition, a dwarf (including a duergar) can order an object to cease its attack. If so commanded, the object becomes immobile for 10 minutes, or until the one commanding it leaves the area.

### Constructed Nature

An animated table doesn't require air, food, drink, or sleep.

```statblock
"name": "Animated Table (TftYP)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "13"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "40 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, paralyzed,\
  \ petrified, poisoned"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The table is incapacitated while in the area of an antimagic field. If\
      \ targeted by dispel magic, the table must succeed on a Constitution saving\
      \ throw against the caster's spell save DC or fall unconscious for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the table remains motionless, it is indistinguishable from a normal\
      \ table."
    "name": "False Appearance"
  - "desc": "If the table moves at least 20 feet straight toward a target and then\
      \ hits it with a ram attack on the same turn, the target takes an extra 9 (2d8)\
      \ bludgeoning damage. If the target is a creature, it must succeed on a DC 15\
      \ Strength saving throw or be knocked prone."
    "name": "Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +6, reach 5 ft., one target. *Hit:* 13 (2d8 +\
      \ 4) bludgeoning damage."
    "name": "Ram"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/construct/token/animated-table-tftyp.webp"
```
^statblock