---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Deinonychus
Status: WIP
linter-yaml-title-alias: Deinonychus
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Wald
  - Monster/HG/1
  - Monster/Typ/Tier
  - Quelle/5e/vgm
aliases:
  - Deinonychus
---
# [Deinonychus](3-Mechanics\CLI\bestiary\beast/deinonychus-vgm.md)
*Source: Volo's Guide to Monsters p. 139, Tomb of Annihilation*  

This larger cousin of the velociraptor kills by gripping its target with its claws and feeding while the creature is still alive.

```statblock
"name": "Deinonychus (VGM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "15"
  - !!int "14"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "If the deinonychus moves at least 20 feet straight toward a creature\
      \ and then hits it with a claw attack on the same turn, that target must succeed\
      \ on a DC 12 Strength saving throw or be knocked prone. If the target is prone,\
      \ the deinonychus can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The deinonychus makes three attacks: one with its bite and two with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) slashing damage."
    "name": "Claw"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/beast/token/deinonychus-vgm.webp"
```
^statblock

## Environment

grassland, forest, hill