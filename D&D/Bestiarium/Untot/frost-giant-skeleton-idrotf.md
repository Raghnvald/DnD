---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/idrotf
- new/monster/cr/6
- new/monster/size/huge
- new/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Frost Giant Skeleton
---
# [Frost Giant Skeleton](3-Mechanics\CLI\bestiary\undead/frost-giant-skeleton-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 288*  

Necromancers can transform the inanimate bones of long-dead frost giants into malevolent juggernauts that love to harm the living.

```statblock
"name": "Frost Giant Skeleton (IDRotF)"
"size": "Huge"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "armor scraps"
"hp": !!int "102"
"hit_dice": "12d12 + 24"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "9"
  - !!int "15"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "40 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "cold, poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Giant but can't speak"
"cr": "6"
"traits":
  - "desc": "The skeleton doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The skeleton makes two greataxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 25\
      \ (3d12 + 6) slashing damage."
    "name": "Greataxe"
  - "desc": "The skeleton targets one creature it can see within 60 feet of it. The\
      \ target must succeed on a DC 13 Constitution saving throw or take 35 (10d6)\
      \ cold damage and be paralyzed until the end of its next turn."
    "name": "Freezing Stare"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/undead/token/frost-giant-skeleton-idrotf.webp"
```
^statblock