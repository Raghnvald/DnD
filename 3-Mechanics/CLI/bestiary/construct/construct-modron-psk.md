---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct (Modron)"
---
# [Construct (Modron)](3-Mechanics/CLI/bestiary/construct/construct-modron-psk.md)
*Source: Plane Shift: Kaladesh p. 32*  

The term "construct" encompasses a tremendous variety of artifact creatures. Some are automatons designed for battle—most often to fight each other in arenas, but also in real combat. Many of these battle constructs specialize in defense, sometimes carrying shields to protect their creators, or simply escorting their charges like a watchdog.

Many constructs are intended for use in foundries and workshops, assisting inventors or performing repetitive tasks. Such a construct might find and deliver a specific tool its inventor requests, or perform routine maintenance in parts of a foundry that are difficult or dangerous to reach.

Other constructs have been designed to carry messages or packages, to load and unload goods from barges and airships, to trawl the sewers for salvageable materials, and even—during the height of the Aether Revolt—to scan crowds of people for known renegades and fugitives, recognizing their facial features.

Almost any creature in the "Monster Manual" with the construct type could be used as a construct on Kaladesh, including [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [modrons](3-Mechanics/CLI/bestiary/construct/monodrone.md).

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Construct (Modron) (PSK)"
"size": "Medium"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "5"
"hit_dice": "1d8 + 1"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "12"
  - !!int "4"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., fly 30 ft."
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
  - "[javelin](3-Mechanics/CLI/items/javelin.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 10"
"languages": "Modron"
"cr": "1/8"
"traits":
  - "desc": "The construct can't be compelled to act in a manner contrary to its nature\
      \ or its instructions."
    "name": "Axiomatic Mind"
  - "desc": "If the construct dies, its body disintegrates into dust, leaving behind\
      \ its weapons and anything else it was carrying."
    "name": "Disintegration"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee  or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 3 (1d6) piercing damage."
    "name": "Javelin"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/construct-modron-psk.webp"
```
^statblock