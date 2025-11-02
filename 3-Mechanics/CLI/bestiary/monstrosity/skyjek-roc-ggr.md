---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/2
- monster/size/large
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skyjek Roc
---
# [Skyjek Roc](3-Mechanics\CLI\bestiary\monstrosity/skyjek-roc-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 219*  

The aerial forces of the Boros Legion-skyknights who fly alongside the angels-take to the air mounted on Skyjek rocs. These avians are named for the skyknights who are also part of the Wojek League, called Skyjeks. From the backs of their rocs, these mounted soldiers carry out reconnaissance missions, bombard enemies on the ground, and engage flying foes.

The shape of a Skyjek roc's body makes it relatively easy to saddle and ride, and it is typically equipped with armor plating on its head and chest.

Skyjek rocs are headstrong and impulsive, but their bravery makes them ideal mounts for the Boros knights.

```statblock
"name": "Skyjek Roc (GGR)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "breastplate"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "13"
  - !!int "14"
  - !!int "3"
  - !!int "10"
  - !!int "8"
"speed": "20 ft., fly 90 ft."
"saves":
  - "dexterity": !!int "3"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The roc has advantage on Wisdom (Perception) checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The roc makes two attacks: one with its beak and one with its talons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d8\
      \ + 5) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d4 + 5) slashing damage."
    "name": "Talons"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/skyjek-roc-ggr.webp"
```
^statblock