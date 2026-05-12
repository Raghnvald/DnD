---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Gibberlings"
---
# [Swarm of Gibberlings](3-Mechanics/CLI/bestiary/fiend/swarm-of-gibberlings-qftis.md)
*Source: Quests from the Infinite Staircase p. 202*  

A single gibberling is little more than a nuisance—a babbling, hairy creature that darts about, attacking whatever it can find. Unfortunately, gibberlings are rarely encountered alone. They rampage in dense swarms, crawling and leaping over each other to rip, shred, and devour everything in their path.

Gibberlings are named for their incoherent chattering. Loud and shrill, their exasperating nonsense distracts even the most focused creatures. Gibberling swarms are heard long before they are seen.

The first gibberlings were spawned in the jungles of the Gaping Maw, a layer of the Abyss ruled by the demon lord Demogorgon. The Prince of Demons' influence instilled in gibberlings a hive-mind-like nature, protecting them from magical compulsions. However, unlike most demons, gibberlings share a strong aversion to fire.

On the Material Plane, gibberlings tend to dwell in dense forests or the Underdark.

```statblock
"name": "Swarm of Gibberlings (QftIS)"
"size": "Large"
"type": "fiend"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "38"
"hit_dice": "7d10"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "7"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 8"
"languages": "Gibberling"
"cr": "3"
"traits":
  - "desc": "If the swarm takes fire damage, it has disadvantage on attack rolls and\
      \ ability checks until the end of its next turn."
    "name": "Aversion to Fire"
  - "desc": "Any non-gibberling that is within 60 feet of the swarm and doesn't have\
      \ the [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened) condition has\
      \ disadvantage on Constitution saving throws to maintain [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on spells and similar effects."
    "name": "Incessant Gibberish"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough to accommodate a Small gibberling.\
      \ The swarm can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "The swarm makes two Gnashing Teeth attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 0 ft., one target in the swarm's\
      \ space. *Hit:* 14 (4d4 + 4) piercing damage, or 9 (2d4 + 4) piercing damage\
      \ if the swarm has half of its hit points or fewer."
    "name": "Gnashing Teeth"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/fiend/token/swarm-of-gibberlings-qftis.webp"
```
^statblock