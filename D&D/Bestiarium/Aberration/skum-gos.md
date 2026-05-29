---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Skum
Kategorie: Aberration
Größe: Mittelgroß
HG: 5
status: WIP
linter-yaml-title-alias: Skum
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/aberration
  - Quelle/5e/gos
aliases:
  - Skum
---
# [Skum](3-Mechanics\CLI\bestiary\aberration/skum-gos.md)
*Source: Ghosts of Saltmarsh p. 254*  

Several poor souls around the Styes have succumbed to an aboleth's magic through its disease-bearing touch. Transformed into creatures called skum, they barely resemble their past forms, their skin turning slimy and translucent while their limbs warp to resemble those of deep-sea oddities. The change makes them dependent on water, which they must immerse themselves in regularly lest they experience painful-and potentially lethal-skin eruptions. Skum are bound to their aboleth master not just by their cursed state, but by a psychic bond that compels them to serve its every sinister whim.

```statblock
"name": "Skum (GoS)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d8 + 44"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "18"
  - !!int "7"
  - !!int "12"
  - !!int "9"
"speed": "20 ft., swim 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
"damage_resistances": "psychic"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Common, Deep Speech, telepathy 60 ft."
"cr": "5"
"traits":
  - "desc": "The skum is permanently charmed by its aboleth master."
    "name": "Abolethic Vassal"
  - "desc": "The skum can breathe air and water."
    "name": "Amphibious"
  - "desc": "The skum is immune to the frightened and charmed conditions unless they\
      \ are from effects created by an aboleth."
    "name": "Psychic Conditioning"
  - "desc": "The skum takes 6 (1d12) acid damage every 10 minutes it goes without\
      \ exposure to water."
    "name": "Water Dependency"
"actions":
  - "desc": "The skum makes three attacks: two with its trident and one with its Mind-Breaking\
      \ Touch."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) piercing damage."
    "name": "Trident"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 18\
      \ (4d8) psychic damage, and the target has disadvantage on Wisdom saving throws\
      \ until the end of the skum's next turn."
    "name": "Mind-Breaking Touch"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/skum-gos.webp"
```
^statblock