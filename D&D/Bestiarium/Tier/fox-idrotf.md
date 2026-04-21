---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fox
tags:
  - Monster/Größe/Winzig
  - Monster/HG/0
  - Monster/Typ/Tier
  - Quelle/5e/idrotf
aliases:
  - Fox
---
# [Fox](3-Mechanics\CLI\bestiary\beast/fox-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 288*  

The white arctic foxes of Icewind Dale live in burrows and are acclimated to cold weather. They prowl the outskirts of Ten-Towns and nearby forests for food, hunting hares or stealing fish. These timid creatures avoid contact with humanoids, but they are sometimes used as mounts by [chwingas](/3-Mechanics/CLI/bestiary/elemental/chwinga-toa.md).

```statblock
"name": "Fox (IDRotF)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "3"
"stats":
  - !!int "2"
  - !!int "16"
  - !!int "11"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "30 ft., burrow 5 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The fox has advantage on Wisdom (Perception) checks that rely on hearing."
    "name": "Keen Hearing"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:* 1\
      \ piercing damage."
    "name": "Bite"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/beast/token/fox-idrotf.webp"
```
^statblock