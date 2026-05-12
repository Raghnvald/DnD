---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct (Animated Armor)"
---
# [Construct (Animated Armor)](3-Mechanics/CLI/bestiary/construct/construct-animated-armor-psk.md)
*Source: Plane Shift: Kaladesh p. 32*  

The term "construct" encompasses a tremendous variety of artifact creatures. Some are automatons designed for battle—most often to fight each other in arenas, but also in real combat. Many of these battle constructs specialize in defense, sometimes carrying shields to protect their creators, or simply escorting their charges like a watchdog.

Many constructs are intended for use in foundries and workshops, assisting inventors or performing repetitive tasks. Such a construct might find and deliver a specific tool its inventor requests, or perform routine maintenance in parts of a foundry that are difficult or dangerous to reach.

Other constructs have been designed to carry messages or packages, to load and unload goods from barges and airships, to trawl the sewers for salvageable materials, and even—during the height of the Aether Revolt—to scan crowds of people for known renegades and fugitives, recognizing their facial features.

Almost any creature in the "Monster Manual" with the construct type could be used as a construct on Kaladesh, including [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [modrons](3-Mechanics/CLI/bestiary/construct/monodrone.md).

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Construct (Animated Armor) (PSK)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The construct is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), the\
      \ construct must succeed on a Constitution saving throw against the caster's\
      \ spell save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the construct remains motionless, it is indistinguishable from\
      \ a normal suit of construct."
    "name": "False Appearance"
"actions":
  - "desc": "The construct makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Slam"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/construct-animated-armor-psk.webp"
```
^statblock