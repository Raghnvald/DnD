---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Yeti Tyke
linter-yaml-title-alias: Yeti Tyke
tags:
  - Monster/Größe/Klein
  - Monster/HG/1-8
  - Monster/Typ/Monstrosität
  - Quelle/5e/idrotf
aliases:
  - Yeti Tyke
---
# [Yeti Tyke](3-Mechanics\CLI\bestiary\monstrosity/yeti-tyke-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 313*  

Yeti tykes are as volatile and mean as their parents, their fearsomeness diminished only by their size. Standing 3 feet tall on average, they like to bully creatures of their height or smaller. But they are easily intimidated by bigger and stronger creatures. A cowed yeti tyke can be controlled, at least for a while, but raising one to be anything other than a savage, flesh-eating predator is incredibly difficult (though not impossible).

```statblock
"name": "Yeti Tyke (IDRotF)"
"size": "Small"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "12"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Yeti but can't speak"
"cr": "1/8"
"traits":
  - "desc": "The yeti has advantage on Wisdom (Perception) checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The yeti has advantage on Dexterity (Stealth) checks made to hide in\
      \ snowy terrain."
    "name": "Snow Camouflage"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ slashing damage plus 2 (1d4) cold damage."
    "name": "Claw"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/yeti-tyke-idrotf.webp"
```
^statblock