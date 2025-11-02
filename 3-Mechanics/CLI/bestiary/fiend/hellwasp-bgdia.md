---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - monster/cr/5
  - monster/size/large
  - monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Hellwasp
---
# [Hellwasp](3-Mechanics\CLI\bestiary\fiend/hellwasp-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 236*  

A hellwasp is an intelligent, malevolent insect native to the Nine Hells. It has a thick protective carapace, thin metallic wings, and strong legs ending in swordlike talons. It uses its stinger to inject a chemical admixture similar to alchemist's fire into its victims. This same solution carries a paralytic enzyme that renders the victim helpless long enough for the hellwasp to grab its prey and flee.

Hellwasps thrive in hot weather, but extreme cold causes their shells to crack and their metabolisms to shut down. Consequently, they avoid the icy layers of the Nine Hells (Stygia and Cania).

## Nests

Hellwasps spew a golden bile similar to amber, which they use to craft enormous nests riddled with chambers and passages. The hellwasps use these nests as communal shelters and food storage. A typical nest is large enough to support a commune of `1d10 + 10` hellwasps, with each hellwasp having an equal voice and role in the society.

## Hellwasp Telepathy

Hellwasps communicate with one another via a form of telepathy perceptible only to their kind.

```statblock
"name": "Hellwasp (BGDIA)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "7"
"speed": "10 ft., fly 60 ft. (hover)"
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "3"
"damage_vulnerabilities": "cold"
"damage_immunities": "fire"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Infernal, telepathy 300 ft. (with other hellwasps only)"
"cr": "5"
"traits":
  - "desc": "The hellwasp's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The hellwasp makes two attacks: one with its sting and one with its sword\
      \ talons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 8\
      \ (1d8 + 4) piercing damage plus 7 (2d6) fire damage, and the target must succeed\
      \ on a DC 12 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute. While [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) in\
      \ this way, the target is also [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed).\
      \ The target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Sting"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) piercing damage."
    "name": "Sword Talons"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/hellwasp-bgdia.webp"
```
^statblock