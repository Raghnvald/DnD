---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Blind Artist
Status: WIP
linter-yaml-title-alias: Blind Artist
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/0
  - Monster/Typ/Untote
  - Quelle/5e/toa
aliases:
  - Blind Artist
---
# [Blind Artist](3-Mechanics\CLI\bestiary\npc/blind-artist-toa.md)
*Source: Tomb of Annihilation p. 164*  

```statblock
"name": "Blind Artist (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "-2"
"stats":
  - !!int "13"
  - !!int "6"
  - !!int "16"
  - !!int "3"
  - !!int "6"
  - !!int "5"
"speed": "20 ft."
"saves":
  - "wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "blinded, poisoned"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "0"
"traits":
  - "desc": "If damage reduces the artist to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the artist drops to 1 hit point instead."
    "name": "Undead Fortitude"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/blind-artist-toa.webp"
```
^statblock