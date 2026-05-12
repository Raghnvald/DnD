---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sky Whale"
---
# [Sky Whale](3-Mechanics/CLI/bestiary/beast/sky-whale-psk.md)
*Source: Plane Shift: Kaladesh p. 28*  

The aethersphere is home to its own ecosystem. Tiny organisms float in the aether currents, deriving all their energy from it and serving as food for larger creatures. Leviathans (similar in form to enormous eels) and flying whales filter these organisms out of the air as they swim through the aethersphere. The whales, as a rule, are not hostile by nature, though they can cause devastating sparks or destructive storms as they move through the aether flows. But leviathans are perpetually hungry, and feed on drakes and airships just as readily as they do on smaller creatures. Along with dragons, leviathans are the primary reason that aether-mining airships carry enormous harpoons.

A sky leviathan is similar to a [purple worm](3-Mechanics/CLI/bestiary/monstrosity/purple-worm.md) in its propensity to swallow prey whole, but it lacks the worm's poison stinger and is therefore significantly less dangerous. Use the statistics presented here.

Sky whales are generally docile filter-feeders that avoid confrontations with airships and flying predators whenever possible. Use the statistics for a [giant crocodile](3-Mechanics/CLI/bestiary/beast/giant-crocodile.md), but replace its bite attack with a flipper attack that is identical to its tail attack. A sky whale has a flying speed of 50 feet and can hover.

```statblock
"name": "Sky Whale (PSK)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "10"
  - !!int "7"
"speed": "fly 50 ft. (hover)"
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The whale can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The whale makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target not [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the whale. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is a\
      \ creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Flipper"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target not [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the whale. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is a\
      \ creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/beast/token/sky-whale-psk.webp"
```
^statblock