---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nimblewright Hulk"
---
# [Nimblewright Hulk](3-Mechanics/CLI/bestiary/construct/nimblewright-hulk-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 267*  

Nimblewright hulks are massive guards or sentinels. These four-armed Constructs often have thick steel bolted to their frames. They are neither slow nor stupid, to the surprise of many would-be thieves or trespassers.

## Nimblewrights

*Cunningly Crafted Clockwork Sentinels*

Nimblewrights are fabricated from durable wood and animated by magic and clockwork gears. Some nimblewrights bear metal plates to protect their cogs and springs, while others have their workings exposed. No mere automatons, nimblewrights can form rudimentary plans and adapt their routines to account for dangers.

Nimblewrights are surprisingly dexterous for creations made of animated wood and metal. A nimblewright walks with a flowing grace and fights with whirling pirouettes.

Nimblewrights can serve as interesting background flavor in Calimshan or other areas where they are common. Roll or choose a result from the Nimblewright Tasks table as inspiration for what a nimblewright guard or nimblewright hulk might be doing in a busy public place.

| dice: 1d6 | The Nimblewright Is... |
|-----------|------------------------|
| 1 | Serving as an attentive bodyguard to a haughty dignitary. |
| 2 | Scouting an area for a pending assassination. |
| 3 | Seeking a thief that has stolen one of the nimblewright's cogs. |
| 4 | Working to put out a fire before it spreads. |
| 5 | Detaining a prisoner who claims innocence. |
| 6 | Hauling mundane goods, but it is lost. |
^1-the-nimblewright-is

```statblock
"name": "Nimblewright Hulk (FRAiF)"
"size": "Large"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"modifier": !!int "7"
"stats":
  - !!int "19"
  - !!int "18"
  - !!int "19"
  - !!int "10"
  - !!int "12"
  - !!int "6"
"speed": "50 ft."
"saves":
  - "strength": !!int "7"
  - "dexterity": !!int "7"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, paralyzed, petrified, poisoned"
"senses": "Darkvision 60 ft., passive Perception 17"
"languages": "understands Common plus one other language but can't speak"
"cr": "7"
"traits":
  - "desc": "If the nimblewright is subjected to an effect that allows it to make\
      \ a Dexterity saving throw to take only half damage, it instead takes no damage\
      \ if it succeeds on the save and only half damage if it fails, provided it doesn't\
      \ have the Incapacitated condition."
    "name": "Evasion"
  - "desc": "The nimblewright has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The nimblewright makes four attacks, using Halting Slam or Radiant Ray\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft. *Hit:* 15 (2d10 + 4) Bludgeoning\
      \ damage, and the target's <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is reduced to 0 until the end of its next turn."
    "name": "Halting Slam"
  - "desc": "*Ranged Attack Roll:* +7, range 60 ft. *Hit:* 14 (4d6) Radiant damage."
    "name": "Radiant Ray"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/nimblewright-hulk-fraif.webp"
```
^statblock

## Environment

urban