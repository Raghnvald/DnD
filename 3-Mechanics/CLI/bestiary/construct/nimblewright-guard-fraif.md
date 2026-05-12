---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nimblewright Guard"
---
# [Nimblewright Guard](3-Mechanics/CLI/bestiary/construct/nimblewright-guard-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 266*  

Watchful sentries that patrol important sites, nimblewright guards serve as loyal soldiers or work as vigilant bodyguards.

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
"name": "Nimblewright Guard (FRAiF)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "6"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "16"
  - !!int "8"
  - !!int "12"
  - !!int "6"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+3"
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, paralyzed, petrified, poisoned"
"gear":
  - "scimitar"
"senses": "Darkvision 60 ft., passive Perception 13"
"languages": "understands Common plus one other language but can't speak"
"cr": "3"
"traits":
  - "desc": "If the nimblewright is subjected to an effect that allows it to make\
      \ a Dexterity saving throw to take only half damage, it instead takes no damage\
      \ if it succeeds on the save and only half damage if it fails, provided it doesn't\
      \ have the Incapacitated condition."
    "name": "Evasion"
"actions":
  - "desc": "The nimblewright makes three attacks, using Scimitar or Clockwork Crossbow\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing\
      \ damage."
    "name": "Scimitar"
  - "desc": "*Ranged Attack Roll:* +6, range 80/320 ft. *Hit:* 8 (1d8 + 4) Piercing\
      \ damage."
    "name": "Clockwork Crossbow"
"reactions":
  - "desc": "Trigger: The nimblewright is hit by a melee attack roll while holding\
      \ a weapon. _Response:_ The nimblewright adds 2 to its AC against that attack,\
      \ potentially causing it to miss."
    "name": "Parry"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/nimblewright-guard-fraif.webp"
```
^statblock

## Environment

urban