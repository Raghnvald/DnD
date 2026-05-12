---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thopter (Bat)"
---
# [Thopter (Bat)](3-Mechanics/CLI/bestiary/construct/thopter-bat-psk.md)
*Source: Plane Shift: Kaladesh p. 33*  

Thopters are small automatons that fly using some combination of whirling rotors and stretched-fabric wings. They are ubiquitous in Ghirapur and other settlements, where they carry messages like carrier pigeons, hunt gremlins like trained hawks, race each other in friendly and not-so-friendly competitions—and serve as remote viewing devices for Consulate authorities and crime lords alike. Thopters range from the size of pigeons to the size of eagles, with extremely intricate gearwork usually partly visible beneath glass orbs and filigree.

Different kinds of thopters could be represented by the statistics for a [bat](3-Mechanics/CLI/bestiary/beast/bat.md), [blood hawk](3-Mechanics/CLI/bestiary/beast/blood-hawk.md), [eagle](3-Mechanics/CLI/bestiary/beast/eagle.md), [hawk](3-Mechanics/CLI/bestiary/beast/hawk.md), [owl](3-Mechanics/CLI/bestiary/beast/owl.md), [pseudodragon](3-Mechanics/CLI/bestiary/dragon/pseudodragon.md), [raven](3-Mechanics/CLI/bestiary/beast/raven.md), or [vulture](3-Mechanics/CLI/bestiary/beast/vulture.md) from the "Monster Manual". All thopters have the construct type, immunity to poison damage, and immunity to the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) and [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) conditions.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Thopter (Bat) (PSK)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "2"
"stats":
  - !!int "2"
  - !!int "15"
  - !!int "8"
  - !!int "2"
  - !!int "12"
  - !!int "4"
"speed": "5 ft., fly 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The thopter can't use its blindsight while [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)."
    "name": "Echolocation"
  - "desc": "The thopter has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing."
    "name": "Keen Hearing"
"actions":
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 5 ft., one creature. *Hit:*\
      \ 1 piercing damage."
    "name": "Bite"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/thopter-bat-psk.webp"
```
^statblock