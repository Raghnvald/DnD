---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Velociraptor
tags:
  - Monster/Größe/Winzig
  - Monster/Habitat/Grasland
  - Monster/Habitat/Wald
  - Monster/HG/1-4
  - Monster/Typ/Tier
  - Quelle/5e/vgm
aliases:
  - Velociraptor
---
# [Velociraptor](3-Mechanics\CLI\bestiary\beast/velociraptor-vgm.md)
*Source: Volo's Guide to Monsters p. 140, Tomb of Annihilation*  

This feathered dinosaur is about the size of a large turkey. It is an aggressive predator and often hunts in packs to bring down larger prey.

```statblock
"name": "Velociraptor (VGM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "13"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The velociraptor has advantage on an attack roll against a creature if\
      \ at least one of the velociraptor's allies is within 5 feet of the creature\
      \ and the ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "The velociraptor makes two attacks: one with its bite and one with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) slashing damage."
    "name": "Claws"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/beast/token/velociraptor-vgm.webp"
```
^statblock

## Environment

grassland, forest