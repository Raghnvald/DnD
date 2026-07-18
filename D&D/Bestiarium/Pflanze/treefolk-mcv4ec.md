---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Treefolk
Status: WIP
linter-yaml-title-alias: Treefolk
tags:
  - Monster/Größe/Groß
  - Monster/HG/11
  - Monster/Typ/Pflanze/druid
  - Quelle/5e/mcv4ec
aliases:
  - Treefolk
---
# [Treefolk](3-Mechanics\CLI\bestiary\plant/treefolk-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

The wise and ancient treefolk thrive in the depths of Eldraine's forested wilds. Though many treefolk rival members of the high fae in age, they rarely interfere with the goings-on of the faerie court. Instead, treefolk serve as guardians and shepherds of their wild groves, dispensing wisdom and blessings to travelers who wander under their branches.

> [!quote] A quote from Borogrove, Tuinvale treefolk  
> 
> Right now, you are a feeble stick, but I will help you grow some rings.

```statblock
"name": "Treefolk (MCV4EC)"
"size": "Large"
"type": "plant"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "171"
"hit_dice": "18d10 + 72"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "12"
  - !!int "18"
  - !!int "10"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "4"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "Insight"
    "desc": "+9"
  - "name": "Nature"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+9"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "blindsight 30 ft., passive Perception 19"
"languages": "Common, Druidic, Sylvan"
"cr": "11"
"traits":
  - "desc": "The treefolk has advantage on Dexterity (Stealth) checks it makes in\
      \ forest terrain."
    "name": "Plant Camouflage"
  - "desc": "Once on each of its turns, the treefolk can use 10 feet of its movement\
      \ to step magically into one living tree within 5 feet of itself and emerge\
      \ from a second living tree within 60 feet of itself that it can see, appearing\
      \ in an unoccupied space within 5 feet of the second tree. Both trees must be\
      \ at least as large as the treefolk."
    "name": "Tree Stride"
"actions":
  - "desc": "The treefolk makes two Crushing Vine attacks, two Nightshade Bolt attacks,\
      \ or one of each."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 25\
      \ (3d12 + 6) bludgeoning damage. If the target is a creature, it has the grappled\
      \ condition (escape DC 18). While grappled, the creature also has the restrained\
      \ condition. The treefolk can grapple up to six creatures this way."
    "name": "Crushing Vine"
  - "desc": "*Ranged Spell Attack:* +9 to hit, range 60 ft., one target. *Hit:* 33\
      \ (6d10) poison damage."
    "name": "Nightshade Bolt"
  - "desc": "The treefolk casts one of the following spells, requiring no material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 17):\n\
      \n**At will:** detect poison and disease, druidcraft\n\n**2/day each:** enlarge/reduce,\
      \ speak with plants\n\n**1/day:** commune with nature (as an action)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The treefolk blesses one creature other than itself that it can see within\
      \ 60 feet of itself with the might and wisdom of the forest. While blessed in\
      \ this way, a creature can use the treefolk's Tree Stride trait and gains 5\
      \ (2d4) temporary hit points at the start of each of its turns. This blessing\
      \ lasts for 1 minute, until the treefolk has the incapacitated condition, or\
      \ until the treefolk uses this bonus action again."
    "name": "Oaken Boon"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/plant/token/treefolk-mcv4ec.webp"
```
^statblock