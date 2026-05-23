---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Storm Herald
Kategorie: Aberration
Größe: Riesig
HG: 17
status: WIP
tags:
  - Monster/Größe/Riesig
  - Monster/HG/17
  - Monster/Typ/aberration
  - Quelle/5e/bgg
aliases:
  - Storm Herald
---
# [Storm Herald](3-Mechanics\CLI\bestiary\aberration/storm-herald-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 183*  

Ancient and alien beings dwell or slumber in ocean depths, awaiting some cosmic circumstance that signals their time to rise. In their retreat from the world, storm giants sometimes stray into the orbit of such creatures, perhaps while seeking insight into some omen, vision, or prophecy. Krakens, aboleths, and Great Old Ones delight in corrupting storm giants to their service, transforming them into storm heralds.

A storm herald grows fins and tentacles, giving it a monstrous appearance. Its mind is wholly under its master's sway, and the herald gains fearsome psychic powers to use in advancing its master's plans. When the herald dies, it reverts to its previous appearance.

A storm herald might try to sway other storm giants to its master's service, while others gather devoted cults of lesser creatures to serve the monsters of the deep.

```statblock
"name": "Storm Herald (BGG)"
"size": "Huge"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "287"
"hit_dice": "23d12 + 138"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "22"
  - !!int "24"
  - !!int "18"
  - !!int "18"
"speed": "50 ft., swim 100 ft."
"saves":
  - "wisdom": !!int "10"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
"damage_resistances": "cold, psychic"
"damage_immunities": "lightning, thunder"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 20"
"languages": "Common, Giant, telepathy 120 ft."
"cr": "17"
"traits":
  - "desc": "The herald can breathe air and water."
    "name": "Amphibious"
  - "desc": "The herald has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The herald makes one Claw attack, one Tentacles attack, and one Trident\
      \ attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:* 18\
      \ (3d6 + 8) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:* 21\
      \ (3d8 + 8) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape\
      \ DC 18). It also has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition and takes 16 (3d10) psychic damage at the start of each of its turns\
      \ until this grapple ends. The herald can have only one creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ this way at a time."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:* 18\
      \ (3d6 + 8) piercing damage or 21 (3d8 + 8) piercing damage if used with two\
      \ hands, plus 13 (3d8) lightning damage."
    "name": "Trident"
  - "desc": "The herald unleashes a blast of psionic energy into the minds of up to\
      \ three creatures it can see within 90 feet of itself. Each target must make\
      \ a DC 21 Intelligence saving throw. On a failed save, a target takes 23 (3d10\
      \ + 7) psychic damage and has the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition for 1 minute. On a successful save, a target takes half as much\
      \ damage only. An affected creature can repeat the saving throw at the end of\
      \ each of its turns, ending the effect on itself on a success.\n\nIf a creature\
      \ is reduced to 0 hit points by this psychic damage, it dies and its head explodes\
      \ if it has one."
    "name": "Psychic Wave (Recharge 6)"
  - "desc": "The herald casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 21):\n\n\
      **At will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is invisible)\n\n**1/day each:** [control water](/3-Mechanics/CLI/spells/control-water-xphb.md),\
      \ [control weather](/3-Mechanics/CLI/spells/control-weather-xphb.md) (as an\
      \ action), [sending](/3-Mechanics/CLI/spells/sending-xphb.md)"
    "name": "Spellcasting (Psionics)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/storm-herald-bgg.webp"
```
^statblock