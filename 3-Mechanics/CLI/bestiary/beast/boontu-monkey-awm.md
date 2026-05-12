---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Boontu Monkey"
---
# [Boontu Monkey](3-Mechanics/CLI/bestiary/beast/boontu-monkey-awm.md)
*Source: Adventure with Muk p. 30*  

Boontu monkeys are skittish and furtive creatures that are greedy and are always on the lookout for food. Although they are greedy, they never eat the sacred golden nuts from the boontu tree in which they live.

Some say that they were once greedy thieves that were turned to monkeys by a powerful dryad who caught them stealing the nuts from her sacred tree.

```statblock
"name": "Boontu Monkey (AWM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "12"
  - !!int "6"
"speed": "20 ft., climb 20 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The Boontu monkey has advantage on an attack roll against a creature\
      \ if at least one of the boontu monkey's allies is within 5 feet of the creature\
      \ and the ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 1\
      \ (1d4 - 1) piercing damage."
    "name": "Bite"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/beast/token/boontu-monkey-awm.webp"
```
^statblock