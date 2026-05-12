---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct (Helmed Horror)"
---
# [Construct (Helmed Horror)](3-Mechanics/CLI/bestiary/construct/construct-helmed-horror-psk.md)
*Source: Plane Shift: Kaladesh p. 32*  

The term "construct" encompasses a tremendous variety of artifact creatures. Some are automatons designed for battle—most often to fight each other in arenas, but also in real combat. Many of these battle constructs specialize in defense, sometimes carrying shields to protect their creators, or simply escorting their charges like a watchdog.

Many constructs are intended for use in foundries and workshops, assisting inventors or performing repetitive tasks. Such a construct might find and deliver a specific tool its inventor requests, or perform routine maintenance in parts of a foundry that are difficult or dangerous to reach.

Other constructs have been designed to carry messages or packages, to load and unload goods from barges and airships, to trawl the sewers for salvageable materials, and even—during the height of the Aether Revolt—to scan crowds of people for known renegades and fugitives, recognizing their facial features.

Almost any creature in the "Monster Manual" with the construct type could be used as a construct on Kaladesh, including [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [modrons](3-Mechanics/CLI/bestiary/construct/monodrone.md).

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Construct (Helmed Horror) (PSK)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "force, necrotic, poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 14"
"languages": "understands the languages of its creator but can't speak"
"cr": "4"
"traits":
  - "desc": "The construct has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The construct is immune to three spells chosen by its creator. Typical\
      \ immunities include [fireball](3-Mechanics/CLI/spells/fireball.md), [heat metal](3-Mechanics/CLI/spells/heat-metal.md),\
      \ and [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md)."
    "name": "Spell Immunity"
"actions":
  - "desc": "The construct makes two longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/construct-helmed-horror-psk.webp"
```
^statblock