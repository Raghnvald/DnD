---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mountain Goat"
---
# [Mountain Goat](3-Mechanics/CLI/bestiary/beast/mountain-goat-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 304*  

Mountain goats are found throughout the Spine of the World and on the slopes of Kelvin's Cairn, their thick fur and layers of body fat protecting them from the extreme cold. They are expert climbers, able to leap and bound up sheer slopes.

Mountain goats are territorial but easily placated with offerings of food. Their stubbornness makes them difficult to domesticate.

```statblock
"name": "Mountain Goat (IDRotF)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "2"
  - !!int "10"
  - !!int "5"
"speed": "40 ft., climb 30 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "If the goat moves at least 20 feet straight toward a target and then\
      \ hits it with a ram attack on the same turn, the target takes an extra 3 (1d6)\
      \ bludgeoning damage. If the target is a creature, it must succeed on a DC 12\
      \ Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Charge"
  - "desc": "The goat has advantage on Strength and Dexterity saving throws made against\
      \ effects that would knock it [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Sure-Footed"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Ram"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/beast/token/mountain-goat-idrotf.webp"
```
^statblock