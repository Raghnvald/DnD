---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Living Blade of Disaster
Status: WIP
linter-yaml-title-alias: Living Blade of Disaster
tags:
  - Monster/Größe/Klein
  - Monster/HG/8
  - Monster/Typ/Konstrukt
  - Quelle/5e/idrotf
aliases:
  - Living Blade of Disaster
---
# [Living Blade of Disaster](3-Mechanics\CLI\bestiary\construct/living-blade-of-disaster-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 299*  

A living blade of disaster is a [blade of disaster](/3-Mechanics/CLI/spells/blade-of-disaster-tce.md) spell (see appendix D) with a wicked will of its own. It looks like a floating, black planar rift in the shape of a sword. Like a demon, it craves destruction.

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that become living beings. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

```statblock
"name": "Living Blade of Disaster (IDRotF)"
"size": "Small"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d6 + 36"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "19"
  - !!int "6"
  - !!int "10"
  - !!int "3"
"speed": "0 ft., fly 30 ft. (hover)"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "blinded, deafened, exhaustion, grappled, paralyzed, petrified,\
  \ poisoned, restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "8"
"traits":
  - "desc": "The living spell has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The living spell can move through any barrier, even a wall of magical\
      \ force."
    "name": "Unfettered"
  - "desc": "The living spell doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Spell Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 26 (4d12)\
      \ force damage, unless the living spell rolled an 18 or higher on the d20 for\
      \ the attack, in which case the attack is a critical hit that deals 78 (12d12)\
      \ force damage instead."
    "name": "Force Blade"
"reactions":
  - "desc": "The living spell makes a melee attack against a creature that starts\
      \ its turn within 5 feet of the living spell."
    "name": "Preemptive Strike"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/construct/token/living-blade-of-disaster-idrotf.webp"
```
^statblock