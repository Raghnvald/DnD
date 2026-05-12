---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Terastodon"
---
# [Terastodon](3-Mechanics/CLI/bestiary/beast/terastodon-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

A terastodon is an enormous elephant (use the [mammoth](3-Mechanics/CLI/bestiary/beast/mammoth.md) statistics) with four tusks and armored hide. A bony plate on its head, sharply pointed on the edges, extends back to protect its neck.

```statblock
"name": "Terastodon (PSZ)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "-1"
"stats":
  - !!int "24"
  - !!int "9"
  - !!int "21"
  - !!int "3"
  - !!int "11"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "6"
"traits":
  - "desc": "If the terastodon moves at least 20 feet straight toward a creature and\
      \ then hits it with a gore attack on the same turn, that target must succeed\
      \ on a DC 18 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the terastodon\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 25 (4d8 + 7) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 29 (4d10 + 7) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/terastodon-psz.webp"
```
^statblock