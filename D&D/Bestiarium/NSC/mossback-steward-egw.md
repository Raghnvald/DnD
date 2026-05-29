---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Mossback Steward
linter-yaml-title-alias: Mossback Steward
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/8
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Mossback Steward
---
# [Mossback Steward](3-Mechanics\CLI\bestiary\npc/mossback-steward-egw.md)
*Source: Explorer's Guide to Wildemount p. 256*  

Desolate badlands and soggy marshes are home to the ancient and massive horizonback tortoises of Eastern Wynandir. Nearly fifty feet from nose to tail, and with a habit of remaining stationary for long periods, a horizonback tortoise is easy to mistake for a low hill at a distance. But when these impressive creatures rise to begin their march, the sight inspires fear and awe in equal parts. An omnivore of incredible size, these scavengers prefer to feed on dead vegetation, but make use of whatever edible matter they come across.

```statblock
"name": "Mossback Steward (EGW)"
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
  - !!int "12"
  - !!int "17"
  - !!int "5"
"speed": "20 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft, passive Perception\
  \ 10"
"languages": "telepathy 120 ft, understands Goblin, Common, and Primordial but can't\
  \ speak"
"cr": "8"
"traits":
  - "desc": "Mossback Steward's innate spellcasting ability is Wisdom (spell save\
      \ DC 15). It can innately cast the following spells, requiring no material components.\n\
      \n**At will:** [friends](/3-Mechanics/CLI/spells/friends-xphb.md)\n\n**1/rest:**\
      \ [suggestion](/3-Mechanics/CLI/spells/suggestion-xphb.md), [divination](/3-Mechanics/CLI/spells/divination-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Mossback Steward can breathe air and water."
    "name": "Amphibious"
  - "desc": "Mossback Steward can carry up to 20,000 pounds of weight atop its shell,\
      \ but moves at half speed if the weight exceeds 10,000 pounds. Medium or smaller\
      \ creatures can move underneath Mossback Steward while it's not [prone](/3-Mechanics/CLI/conditions.md#Prone).\n\
      \nAny creature under Mossback Steward when it falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 18). Until\
      \ the grapple ends, the creature is [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Massive Frame"
"actions":
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 28\
      \ (3d12 + 9) bludgeoning damage."
    "name": "Bite"
  - "desc": "Mossback Steward withdraws into its shell, falls [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ and gains a +5 bonus to AC. While Mossback Steward is in its shell, its speed\
      \ is 0 and can't increase. Mossback Steward can emerge from its shell as an\
      \ action, whereupon it is no longer [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Shell Defense (Recharge 4-6)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/npc/token/mossback-steward-egw.webp"
```
^statblock