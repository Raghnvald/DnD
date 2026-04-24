---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Mächtiger Zombie
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Untote
  - Quelle/5e/tftyp
aliases:
  - Greater Zombie
linter-yaml-title-alias: Greater Zombie
---
# Mächtiger Zombie
*Source: Tales from the Yawning Portal p. 237*  

Many of those who brave the Tomb of Horrors believe they have reached their ultimate destination when they disturb a skeletal figure inside a secluded crypt. It is, in fact, a greater zombie, a creature magically created from a humanoid corpse to be far more resilient than a typical zombie.

## Undead Nature

A zombie doesn't require air, food, drink, or sleep.

```statblock
"name": "Mächtiger Zombie (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "4"
  - !!int "6"
  - !!int "6"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "1"
"damage_resistances": "cold, necrotic"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands the languages it knew in life but can't speak"
"cr": "5"
"traits":
  - "desc": "The zombie has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The zombie makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) bludgeoning damage and 7 (2d6) necrotic damage."
    "name": "Empowered Slam"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/undead/token/greater-zombie-tftyp.webp"
```
^statblock