---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Frilled Deathspitter"
---
# [Frilled Deathspitter](3-Mechanics/CLI/bestiary/beast/frilled-deathspitter-psx.md)
*Source: Plane Shift: Ixalan p. 30*  

The dinosaurs aptly known as deathspitters can spit venom to blind their prey before closing in for the kill.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Frilled Deathspitter (PSX)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "18"
"hit_dice": "4d6 + 4"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/2"
"actions":
  - "desc": "The deathspitter makes three attacks: one with its bite and two with\
      \ its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Claw"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 15/30 ft., one creature. *Hit:*\
      \ The target must make a DC 13 Constitution saving throw, taking 18 (4d8)\
      \ poison damage on a failed save, or half as much damage on a successful one.\
      \ In addition, a creature that fails its saving throw is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ until the end of the deathspitter's next turn."
    "name": "Spit Poison"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/frilled-deathspitter-psx.webp"
```
^statblock