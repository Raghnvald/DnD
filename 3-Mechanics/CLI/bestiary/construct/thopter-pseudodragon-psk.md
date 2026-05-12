---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thopter (Pseudodragon)"
---
# [Thopter (Pseudodragon)](3-Mechanics/CLI/bestiary/construct/thopter-pseudodragon-psk.md)
*Source: Plane Shift: Kaladesh p. 33*  

Thopters are small automatons that fly using some combination of whirling rotors and stretched-fabric wings. They are ubiquitous in Ghirapur and other settlements, where they carry messages like carrier pigeons, hunt gremlins like trained hawks, race each other in friendly and not-so-friendly competitions—and serve as remote viewing devices for Consulate authorities and crime lords alike. Thopters range from the size of pigeons to the size of eagles, with extremely intricate gearwork usually partly visible beneath glass orbs and filigree.

Different kinds of thopters could be represented by the statistics for a [bat](3-Mechanics/CLI/bestiary/beast/bat.md), [blood hawk](3-Mechanics/CLI/bestiary/beast/blood-hawk.md), [eagle](3-Mechanics/CLI/bestiary/beast/eagle.md), [hawk](3-Mechanics/CLI/bestiary/beast/hawk.md), [owl](3-Mechanics/CLI/bestiary/beast/owl.md), [pseudodragon](3-Mechanics/CLI/bestiary/dragon/pseudodragon.md), [raven](3-Mechanics/CLI/bestiary/beast/raven.md), or [vulture](3-Mechanics/CLI/bestiary/beast/vulture.md) from the "Monster Manual". All thopters have the construct type, immunity to poison damage, and immunity to the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) and [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) conditions.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Thopter (Pseudodragon) (PSK)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "2d4 + 2"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "15"
  - !!int "13"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "15 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 13"
"languages": "understands Common and Draconic but can't speak"
"cr": "1/4"
"traits":
  - "desc": "The thopter has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight, hearing, or smell."
    "name": "Keen Senses"
  - "desc": "The thopter has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The thopter can magically communicate simple ideas, emotions, and images\
      \ telepathically with any creature within 100 feet of it that can understand\
      \ a language."
    "name": "Limited Telepathy"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 11 Constitution\
      \ saving throw or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour. If the saving throw fails by 5 or more, the target falls [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for the same duration, or until it takes damage or another creature uses an\
      \ action to shake it awake."
    "name": "Sting"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/thopter-pseudodragon-psk.webp"
```
^statblock