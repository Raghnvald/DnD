---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Quetzalcoatlus
linter-yaml-title-alias: Quetzalcoatlus
tags:
  - Monster/Größe/Riesig
  - Monster/Habitat/Berg
  - Monster/Habitat/Hügel
  - Monster/Habitat/Küste
  - Monster/HG/2
  - Monster/Typ/Tier
  - Quelle/5e/vgm
aliases:
  - Quetzalcoatlus
---
# [Quetzalcoatlus](3-Mechanics\CLI\bestiary\beast/quetzalcoatlus-vgm.md)
*Source: Volo's Guide to Monsters p. 140, Tomb of Annihilation*  

This giant relative of the pteranodon has a wingspan exceeding 30 feet. Although it can move on the ground like a quadruped, it is more comfortable in the air.

```statblock
"name": "Quetzalcoatlus (VGM)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d12 + 4"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "13"
  - !!int "2"
  - !!int "10"
  - !!int "5"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "If the quetzalcoatlus is flying and dives at least 30 feet toward a target\
      \ and then hits with a bite attack, the attack deals an extra 10 (3d6) damage\
      \ to the target."
    "name": "Dive Attack"
  - "desc": "The quetzalcoatlus doesn't provoke an opportunity attack when it flies\
      \ out of an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one creature. *Hit:*\
      \ 12 (3d6 + 2) piercing damage."
    "name": "Bite"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/beast/token/quetzalcoatlus-vgm.webp"
```
^statblock

## Environment

mountain, hill, coastal