---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rusted Behemoth"
---
# [Rusted Behemoth](3-Mechanics/CLI/bestiary/construct/rusted-behemoth-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 272*  

A giant overtaken by the Rusting is a fearsome juggernaut, rending trees and hills in a mindless rage. Their tough, rusted skin turns away blades and arrows in a shower of toxic orange dust. Rusted behemoths enjoy despoiling the wilderness.

## Rusted

*Construct Victims of a Supernatural Curse*

The supernatural Rusting curse that pervades the Moonshae Isles manifests as a thin scrim of iron over a living creature's skin. This coarse iron rusts easily, turning the creature a sickly orange gray. Unchecked, this curse transforms the victim into a Rusted, an animated iron caricature of itself that sheds flakes of toxic rust.

As the Rusting curse hardens the skin, it also hollows out the mind. Rusted creatures despise unspoiled nature and are compelled to destroy it when they can.

> [!note] Other Rusted
> 
> You can turn any Beast, Fey, Giant, Humanoid, or Monstrosity into a Rusted version of itself by doing the following: change the creature's type to Construct, and give it Immunity to Poison damage and the Exhaustion, Petrified, and Poisoned conditions.
^other-rusted

```statblock
"name": "Rusted Behemoth (FRAiF)"
"size": "Huge"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "19"
  - !!int "6"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"damage_immunities": "poison"
"condition_immunities": "exhaustion, petrified, poisoned"
"senses": "Darkvision 120 ft., passive Perception 11"
"languages": "Common, Giant"
"cr": "9"
"actions":
  - "desc": "The Rusted makes three attacks, using Slam or Rusted Shot Put in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 20 (4d6 + 6) Bludgeoning\
      \ damage."
    "name": "Slam"
  - "desc": "*Ranged Attack Roll:* +10, range 60/240 ft. *Hit:* 15 (2d8 + 6) Bludgeoning\
      \ damage, and the target has the Poisoned condition until the end of its next\
      \ turn."
    "name": "Rusted Shot Put"
"reactions":
  - "desc": "Trigger: The Rusted is hit by an attack roll that deals Bludgeoning,\
      \ Piercing, or Slashing damage. _Response—_*Constitution Saving Throw:* DC 16,\
      \ each creature of the Rusted's choice in a 5-foot <span title=\"Player's Handbook\
      \ (2024)\">Emanation</span> originating from the Rusted. *Failure:* the target\
      \ has the Poisoned condition until the end of the target's next turn."
    "name": "Rust-Riddled Hide"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/rusted-behemoth-fraif.webp"
```
^statblock

## Environment

coastal, forest