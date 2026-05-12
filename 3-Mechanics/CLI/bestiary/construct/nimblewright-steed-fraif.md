---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nimblewright Steed"
---
# [Nimblewright Steed](3-Mechanics/CLI/bestiary/construct/nimblewright-steed-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 267*  

Nimblewright steeds are clockwork mounts that are tireless whether carrying a rider or pulling a coach. A nimblewright steed can become fixated on routes it frequently takes and become stubborn about following them.

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
"name": "Nimblewright Steed (FRAiF)"
"size": "Large"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "47"
"hit_dice": "5d10 + 20"
"modifier": !!int "6"
"stats":
  - !!int "17"
  - !!int "18"
  - !!int "18"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "6"
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, paralyzed, petrified, poisoned"
"senses": "Darkvision 60 ft., passive Perception 10"
"languages": "understands Common plus one other language but can't speak"
"cr": "2"
"traits":
  - "desc": "If the nimblewright is subjected to an effect that allows it to make\
      \ a Dexterity saving throw to take only half damage, it instead takes no damage\
      \ if it succeeds on the save and only half damage if it fails, provided it doesn't\
      \ have the Incapacitated condition."
    "name": "Evasion"
"actions":
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning\
      \ damage. If the nimblewright moved at least 20 feet straight toward the target\
      \ immediately before the hit, the target takes an extra 4 (1d8) Bludgeoning\
      \ damage and, if it is Huge or smaller, has the Prone condition."
    "name": "Hooves"
"bonus_actions":
  - "desc": "The nimblewright takes the Disengage action."
    "name": "Nimble Movement"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/nimblewright-steed-fraif.webp"
```
^statblock

## Environment

urban