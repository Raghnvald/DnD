---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tftyp
  - Monster/HG/7
  - Monster/Größe/Riesig
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Skeleton
---
# [Giant Skeleton](3-Mechanics\CLI\bestiary\undead/giant-skeleton-tftyp.md)
*Source: Tales from the Yawning Portal p. 236*  

In the Tomb of Horrors, treasure sometimes presents itself for the taking. In one such location, the "reward" for an attempt to grab some valuables turns out to be the animated skeleton of a giant—deadly not only because of its size and strength, but because it has defenses normally possessed only by undead of much greater power.

## Undead Nature

A skeleton doesn't require air, food, drink, or sleep.

```statblock
"name": "Giant Skeleton (TftYP)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "115"
"hit_dice": "10d12 + 50"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "10"
  - !!int "20"
  - !!int "4"
  - !!int "6"
  - !!int "6"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands Giant but can't speak"
"cr": "7"
"traits":
  - "desc": "If the skeleton is subjected to an effect that allows it to make a saving\
      \ throw to take only half damage, it instead takes no damage if it succeeds\
      \ on the saving throw, and only half damage if it fails."
    "name": "Evasion"
  - "desc": "The skeleton has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The skeleton is immune to effects that turn undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "The skeleton makes three scimitar attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 15\
      \ (3d6 + 5) slashing damage."
    "name": "Scimitar"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/undead/token/giant-skeleton-tftyp.webp"
```
^statblock