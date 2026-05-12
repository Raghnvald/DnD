---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lifecraft Elephant"
---
# [Lifecraft Elephant](3-Mechanics/CLI/bestiary/construct/lifecraft-elephant-psk.md)
*Source: Plane Shift: Kaladesh p. 33*  

Many inventors—particularly elves, but members of the other races as well—view nature as the greatest artificer and strive to imitate it as closely as possible. The Greenwheel Lifecrafters are an inventor society dedicated to this kind of work, and they are responsible for coining the term "lifecrafting" to describe it. Lifecraft creatures are automatons that mimic the forms of natural animals in intricate detail. More than merely artistic endeavors, these creatures often serve practical purposes, just as domesticated animals would. A lifecraft elephant hauling a cart or carrying passengers through the streets of Ghirapur is just as effective in that work as a natural elephant, but it can't be spooked and it leaves no messy waste in its path.

The work of elf lifecrafters is particularly notable. Like most elf inventions, it incorporates living wood and foliage into its design, creating striking hybrids of plant life and animal form united as a perfect aesthetic whole.

Inventors can create lifecraft versions of virtually any creature. A lifecraft creature's type changes to construct, and it gains immunity to poison damage and to the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) and [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) conditions. Its other statistics are typically unchanged.

```statblock
"name": "Lifecraft Elephant (PSK)"
"size": "Huge"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "17"
  - !!int "3"
  - !!int "11"
  - !!int "6"
"speed": "40 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "If the elephant moves at least 20 feet straight toward a creature and\
      \ then hits it with a gore attack on the same turn, that target must succeed\
      \ on a DC 12 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the elephant\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 19\
      \ (3d8 + 6) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 22 (3d10 + 6) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/construct/token/lifecraft-elephant-psk.webp"
```
^statblock