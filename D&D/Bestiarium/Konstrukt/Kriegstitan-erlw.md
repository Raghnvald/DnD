---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Warforged Titan
Status: WIP
linter-yaml-title-alias: Warforged Titan
tags:
  - Monster/Größe/Riesig
  - Monster/HG/8
  - Monster/Typ/Konstrukt
  - Quelle/5e/erlw
aliases:
  - Warforged Titan
---
# [Warforged Titan](3-Mechanics\CLI\bestiary\construct/warforged-titan-erlw.md)
*Source: Eberron: Rising from the Last War p. 315*  

Warforged titans are hulking constructs built to wreak paths of destruction through enemy armies. Some of the most feared combatants of the Last War, warforged titans are barely sentient, with just enough intelligence to follow commands.

## Legacy of Giants

In the Age of Giants, giant artificers built mindless war golems to aid them in their war against the quori. Millennia later, some of these golems were unearthed by adventurers searching for the secrets of that age, then turned over to artificers working for the dragonmarked houses during the Last War. House Cannith studied these designs, and in the course of uncovering the secrets of the golems and the giant artificers who made them, House Cannith created the first warforged titans.

```statblock
"name": "Warforged Titan (ERLW)"
"size": "Huge"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "125"
"hit_dice": "10d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "8"
  - !!int "22"
  - !!int "3"
  - !!int "11"
  - !!int "1"
"speed": "40 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
  - "desc": "The warforged titan has two platforms built into its chassis. One Medium\
      \ or smaller creature can ride on each platform without squeezing. To make a\
      \ melee attack against a target within 5 feet of the warforged, they must use\
      \ spears or weapons with reach and the target must be Large or larger."
    "name": "Platforms"
  - "desc": "The warforged titan deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The warforged titan makes one axehand attack and one hammerfist attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 19\
      \ (3d8 + 6) slashing damage, plus 11 (2d10) slashing damage if the target is\
      \ prone."
    "name": "Axehand"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 19\
      \ (3d8 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or be knocked prone."
    "name": "Hammerfist"
  - "desc": "The warforged titan makes a sweep with its axehand, and each creature\
      \ within 10 feet of it must make a DC 17 Dexterity saving throw. A creature\
      \ takes 19 (3d8 + 6) slashing damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Sweeping Axe (Recharge 6)"
"source":
  - "ERLW"
"image": "/3-Mechanics/CLI/bestiary/construct/token/warforged-titan-erlw.webp"
```
^statblock