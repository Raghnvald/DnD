---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rusted Wyrm"
---
# [Rusted Wyrm](3-Mechanics/CLI/bestiary/construct/rusted-wyrm-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 273*  

A Rusted wyrm is a draconic colossus capable of phenomenal devastation. Although some Rusted wyrms evaporate rivers and destroy springs, others venture further underwater to wreck coral reefs and boil the sea.

## Rusted

*Construct Victims of a Supernatural Curse*

The supernatural Rusting curse that pervades the Moonshae Isles manifests as a thin scrim of iron over a living creature's skin. This coarse iron rusts easily, turning the creature a sickly orange gray. Unchecked, this curse transforms the victim into a Rusted, an animated iron caricature of itself that sheds flakes of toxic rust.

As the Rusting curse hardens the skin, it also hollows out the mind. Rusted creatures despise unspoiled nature and are compelled to destroy it when they can.

> [!note] Other Rusted
> 
> You can turn any Beast, Fey, Giant, Humanoid, or Monstrosity into a Rusted version of itself by doing the following: change the creature's type to Construct, and give it Immunity to Poison damage and the Exhaustion, Petrified, and Poisoned conditions.
^other-rusted

```statblock
"name": "Rusted Wyrm (FRAiF)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "20"
"hp": !!int "231"
"hit_dice": "14d20 + 84"
"modifier": !!int "6"
"stats":
  - !!int "25"
  - !!int "13"
  - !!int "22"
  - !!int "8"
  - !!int "14"
  - !!int "6"
"speed": "40 ft., swim 60 ft."
"damage_immunities": "fire, poison"
"condition_immunities": "exhaustion, frightened, petrified, poisoned"
"senses": "Darkvision 120 ft., passive Perception 12"
"languages": "Common, Draconic"
"cr": "14"
"traits":
  - "desc": "If the Rusted fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The Rusted makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 20 ft. *Hit:* 29 (4d10 + 7) Piercing\
      \ damage."
    "name": "Bite"
  - "desc": "*Dexterity Saving Throw:* DC 19, each creature and flammable object that\
      \ isn't being worn or carried in a 60-foot <span title=\"Player's Handbook (2024)\"\
      >Cone</span>. *Failure:* 45 (7d12) Fire damage, and the target starts burning.\
      \ *Success:* Half damage only. *Failure or Success:* Being underwater doesn't\
      \ grant <span title=\"Player's Handbook (2024)\">Resistance</span> to this Fire\
      \ damage."
    "name": "Steam Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "*Constitution Saving Throw:* DC 19, one creature within 20 feet of the\
      \ Rusted. *Failure:* 14 (4d6) Poison damage, and the target has the Poisoned\
      \ condition until the end of its next turn. While Poisoned, the target has the\
      \ Paralyzed condition."
    "name": "Encasing Rust"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/rusted-wyrm-fraif.webp"
```
^statblock

## Environment

coastal, forest