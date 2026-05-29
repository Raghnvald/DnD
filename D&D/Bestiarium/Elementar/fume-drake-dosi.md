---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fume Drake
linter-yaml-title-alias: Fume Drake
tags:
  - Monster/Größe/Klein
  - Monster/HG/1-4
  - Monster/Typ/Elementar
  - Quelle/5e/dosi
aliases:
  - Fume Drake
---
# [Fume Drake](3-Mechanics\CLI\bestiary\elemental/fume-drake-dosi.md)
*Source: Dragons of Stormwreck Isle p. 41*  

Fume drakes are mischievous creatures that arise from the lingering magical energy of a dead dragon. They resemble small, legless dragons formed from clouds of greenish smoke. They delight in causing pain and confusion in other creatures.

```statblock
"name": "Fume Drake (DoSI)"
"size": "Small"
"type": "elemental"
"alignment": "typically  Neutral"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "12"
  - !!int "6"
  - !!int "10"
  - !!int "11"
"speed": "30 ft., fly 30 ft."
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Draconic, Ignan"
"cr": "1/4"
"traits":
  - "desc": "When the fume drake dies, it explodes in a cloud of noxious fumes. Each\
      \ creature within 5 feet of the fume drake must succeed on a DC 11 Constitution\
      \ saving throw or take 4 (1d8) poison damage."
    "name": "Death Burst"
  - "desc": "The fume drake doesn't require food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) fire damage."
    "name": "Bite"
  - "desc": "The fume drake exhales a 15-foot cone of scalding steam. Each creature\
      \ in that area must make a DC 11 Dexterity saving throw, taking 4 (1d8) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Scalding Breath (Recharge 6)"
"source":
  - "DoSI"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/fume-drake-dosi.webp"
```
^statblock