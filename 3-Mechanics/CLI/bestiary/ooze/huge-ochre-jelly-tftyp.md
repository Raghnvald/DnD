---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Huge Ochre Jelly"
---
# [Huge Ochre Jelly](3-Mechanics/CLI/bestiary/ooze/huge-ochre-jelly-tftyp.md)
*Source: Tales from the Yawning Portal p. 225*  

```statblock
"name": "Huge Ochre Jelly (TftYP)"
"size": "Huge"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "51"
"hit_dice": "6d12 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "2"
  - !!int "6"
  - !!int "1"
"speed": "10 ft., climb 10 ft."
"damage_resistances": "acid"
"damage_immunities": "lightning, slashing"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 8"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The jelly can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "The jelly can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (2d6 + 2) bludgeoning damage plus 3 (1d6) acid damage."
    "name": "Pseudopod"
"reactions":
  - "desc": "When a jelly that is Medium or larger is subjected to lightning or slashing\
      \ damage, it splits into two new jellies if it has at least 10 hit points. Each\
      \ new jelly has hit points equal to half the original jelly's, rounded down.\
      \ New jellies are one size smaller than the original jelly."
    "name": "Split"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/ooze/token/huge-ochre-jelly-tftyp.webp"
```
^statblock