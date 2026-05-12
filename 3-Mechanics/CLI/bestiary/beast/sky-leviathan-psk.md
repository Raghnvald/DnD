---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sky Leviathan"
---
# [Sky Leviathan](3-Mechanics/CLI/bestiary/beast/sky-leviathan-psk.md)
*Source: Plane Shift: Kaladesh p. 28*  

The aethersphere is home to its own ecosystem. Tiny organisms float in the aether currents, deriving all their energy from it and serving as food for larger creatures. Leviathans (similar in form to enormous eels) and flying whales filter these organisms out of the air as they swim through the aethersphere. The whales, as a rule, are not hostile by nature, though they can cause devastating sparks or destructive storms as they move through the aether flows. But leviathans are perpetually hungry, and feed on drakes and airships just as readily as they do on smaller creatures. Along with dragons, leviathans are the primary reason that aether-mining airships carry enormous harpoons.

A sky leviathan is similar to a [purple worm](3-Mechanics/CLI/bestiary/monstrosity/purple-worm.md) in its propensity to swallow prey whole, but it lacks the worm's poison stinger and is therefore significantly less dangerous. Use the statistics presented here.

Sky whales are generally docile filter-feeders that avoid confrontations with airships and flying predators whenever possible. Use the statistics for a [giant crocodile](3-Mechanics/CLI/bestiary/beast/giant-crocodile.md), but replace its bite attack with a flipper attack that is identical to its tail attack. A sky whale has a flying speed of 50 feet and can hover.

```statblock
"name": "Sky Leviathan (PSK)"
"size": "Gargantuan"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "247"
"hit_dice": "15d20 + 90"
"modifier": !!int "-2"
"stats":
  - !!int "28"
  - !!int "7"
  - !!int "22"
  - !!int "1"
  - !!int "8"
  - !!int "4"
"speed": "fly 50 ft. (hover)"
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "3"
"senses": "passive Perception 9"
"languages": ""
"cr": "10"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 18 Dexterity saving throw or be swallowed by the leviathan.\
      \ A swallowed creature is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the leviathan, and it takes\
      \ 21 (6d6) acid damage at the start of each of the leviathan's turns.\n\n\
      If the leviathan takes 30 damage or more on a single turn from a creature inside\
      \ it, the leviathan must succeed on a DC 21 Constitution saving throw at the\
      \ end of that turn or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the leviathan. If the leviathan dies, a swallowed\
      \ creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 20 feet of movement, exiting\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/beast/token/sky-leviathan-psk.webp"
```
^statblock