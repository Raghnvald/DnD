---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/wdmm
  - Monster/HG/0
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Living Unseen Servant
---
# [Living Unseen Servant](3-Mechanics\CLI\bestiary\construct/living-unseen-servant-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 313*  

## Living Spell

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that refuse to dissipate. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

A living spell appears much like a normal spell effect, except that its magical energy lingers and moves with purpose.

### Constructed Nature

A living spell doesn't require air, food, drink, or sleep.

### Magical Essence

The process that creates a living spell changes the nature of its magic. A living spell isn't subject to dispel magic and isn't affected by an antimagic field.

Like an overzealous butler or maid, a living unseen servant spell busies itself with tasks in hopes of pleasing its creator. It can wield simple weapons but prefers not to. See invisibility, true seeing, and similar effects reveal that the servant has a shape similar to that of a slender humanoid adult.

```statblock
"name": "Living Unseen Servant (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"modifier": !!int "0"
"stats":
  - !!int "2"
  - !!int "10"
  - !!int "11"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, paralyzed, petrified, poisoned, unconscious"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 12"
"languages": "understands one language (usually Common) but can't speak"
"cr": "0"
"traits":
  - "desc": "The unseen servant is invisible."
    "name": "Invisibility"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning\
      \ damage."
    "name": "Slam"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/construct/token/living-unseen-servant-wdmm.webp"
```
^statblock