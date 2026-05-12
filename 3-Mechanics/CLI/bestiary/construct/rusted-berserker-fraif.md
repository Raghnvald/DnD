---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rusted Berserker"
---
# [Rusted Berserker](3-Mechanics/CLI/bestiary/construct/rusted-berserker-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 273*  

A Rusted berserker is a human Norlander transformed by the Rusting. These berserkers have forsaken the traditional Norlander lifestyle to rage against nature and its protectors.

## Rusted

*Construct Victims of a Supernatural Curse*

The supernatural Rusting curse that pervades the Moonshae Isles manifests as a thin scrim of iron over a living creature's skin. This coarse iron rusts easily, turning the creature a sickly orange gray. Unchecked, this curse transforms the victim into a Rusted, an animated iron caricature of itself that sheds flakes of toxic rust.

As the Rusting curse hardens the skin, it also hollows out the mind. Rusted creatures despise unspoiled nature and are compelled to destroy it when they can.

> [!note] Other Rusted
> 
> You can turn any Beast, Fey, Giant, Humanoid, or Monstrosity into a Rusted version of itself by doing the following: change the creature's type to Construct, and give it Immunity to Poison damage and the Exhaustion, Petrified, and Poisoned conditions.
^other-rusted

```statblock
"name": "Rusted Berserker (FRAiF)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "17"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "exhaustion, petrified, poisoned"
"gear":
  - "greatsword"
  - "six javelins"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "4"
"actions":
  - "desc": "The Rusted makes two attacks, using Greatsword or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing\
      \ damage, and the target has the Poisoned condition until the end of its next\
      \ turn."
    "name": "Greatsword"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 30/120 ft.\
      \ *Hit:* 11 (2d6 + 4) Piercing damage, and the target has the Poisoned condition\
      \ until the end of its next turn."
    "name": "Javelin"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/rusted-berserker-fraif.webp"
```
^statblock

## Environment

coastal, forest