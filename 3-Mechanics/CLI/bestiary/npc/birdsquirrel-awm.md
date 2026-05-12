---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Birdsquirrel"
---
# [Birdsquirrel](3-Mechanics/CLI/bestiary/npc/birdsquirrel-awm.md)
*Source: Adventure with Muk p. 30*  

Birdsquirrel is a plucky, little critter who loves Muk with all its heart. Some say that Birdsquirrel was created by Doonwaggle the wizard, and that it is the only birdsquirrel in the Dankwood (and maybe the whole world) but who knows?

```statblock
"name": "Birdsquirrel (AWM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "10"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "13"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "20 ft., climb 20 ft., fly 30 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "Birdsquirrel has advantage on an attack roll against a creature if at\
      \ least one of the Birdsquirrel's allies is within 5 feet of the creature and\
      \ the ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "Birdsquirrel makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6+2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4+2) slashing damage."
    "name": "Claws"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/npc/token/birdsquirrel-awm.webp"
```
^statblock