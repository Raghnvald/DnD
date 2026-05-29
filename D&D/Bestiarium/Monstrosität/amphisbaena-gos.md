---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Amphisbaena
Kategorie: Monstrosität
Größe: Mittelgroß
HG: 1/2
Habitat:
  - /
image: token/amphisbaena-gos.webp
status: WIP
linter-yaml-title-alias: Amphisbaena
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Monstrosität
  - Quelle/5e/gos
aliases:
  - Amphisbaena
---
# [Amphisbaena](3-Mechanics\CLI\bestiary\monstrosity/amphisbaena-gos.md)
*Source: Ghosts of Saltmarsh p. 230*  

Found in Danger at Dunwater, these strange reptiles have a head at either end of their serpentine bodies, each one equipped with venomous fangs. To move, an amphisbaena uses one head to grip the neck of its other head, forming a hoop that rolls over the ground.

```statblock
"name": "Amphisbaena (GoS)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "12"
  - !!int "3"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The amphisbaena has advantage on Wisdom (Perception) checks and on saving\
      \ throws against being blinded, charmed, deafened, frightened, stunned, and\
      \ knocked unconscious."
    "name": "Two Heads"
"actions":
  - "desc": "The amphisbaena makes two bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4\
      \ + 4) piercing damage, and the target must make a DC 11 Constitution saving\
      \ throw, taking 3 (1d6) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Bite"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/amphisbaena-gos.webp"
```
^statblock