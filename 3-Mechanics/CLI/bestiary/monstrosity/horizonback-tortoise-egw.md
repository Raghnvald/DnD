---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Horizonback Tortoise
---
# [Horizonback Tortoise](3-Mechanics\CLI\bestiary\monstrosity/horizonback-tortoise-egw.md)
*Source: Explorer's Guide to Wildemount p. 292*  

Desolate badlands and soggy marshes are home to the ancient and massive horizonback tortoises of Eastern Wynandir. Nearly fifty feet from nose to tail, and with a habit of remaining stationary for long periods, a horizonback tortoise is easy to mistake for a low hill at a distance. But when these impressive creatures rise to begin their march, the sight inspires fear and awe in equal parts. An omnivore of incredible size, these scavengers prefer to feed on dead vegetation, but make use of whatever edible matter they come across.

```statblock
"name": "Horizonback Tortoise (EGW)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor; 22 while in its shell"
"hp": !!int "227"
"hit_dice": "13d20 + 91"
"modifier": !!int "-4"
"stats":
  - !!int "28"
  - !!int "3"
  - !!int "25"
  - !!int "4"
  - !!int "10"
  - !!int "5"
"speed": "20 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "10"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft, passive Perception\
  \ 10"
"languages": "understands Goblin but can't speak"
"cr": "8"
"traits":
  - "desc": "The tortoise can breathe air and water."
    "name": "Amphibious"
  - "desc": "The tortoise can carry up to 20,000 pounds of weight atop its shell,\
      \ but moves at half speed if the weight exceeds 10,000 pounds. Medium or smaller\
      \ creatures can move underneath the tortoise while it's not [prone](/3-Mechanics/CLI/conditions.md#Prone).\n\
      \nAny creature under the tortoise when it falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 18). Until\
      \ the grapple ends, the creature is [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Massive Frame"
"actions":
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 28\
      \ (3d12 + 9) bludgeoning damage."
    "name": "Bite"
  - "desc": "The tortoise withdraws into its shell, falls [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ and gains a +5 bonus to AC. While the tortoise is in its shell, its speed\
      \ is 0 and can't increase. The tortoise can emerge from its shell as an action,\
      \ whereupon it is no longer [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Shell Defense (Recharge 4-6)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/horizonback-tortoise-egw.webp"
```
^statblock