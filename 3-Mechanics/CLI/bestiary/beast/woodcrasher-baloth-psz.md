---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Woodcrasher Baloth"
---
# [Woodcrasher Baloth](3-Mechanics/CLI/bestiary/beast/woodcrasher-baloth-psz.md)
*Source: Plane Shift: Zendikar p. 33*  

Baloths are perhaps the most distinctive of Zendikar's beasts. They are muscular, omnivorous hunters covered in horns, spines, and plates of various shapes. The woodcrasher baloths of the Turntimber forest are surprisingly agile, leaping from tree to tree by using their great claws to clutch each spiraling trunk. The leatherback baloths of Ora Ondar are heavier and keep to the ground, where their thick, plated hide protects them from danger. Baloth herds occasionally stampede across the Onduan plains—and do so more frequently since the rise of the Eldrazi, as if sharing in Zendikar's anger. Use the [triceratops](3-Mechanics/CLI/bestiary/beast/triceratops.md) statistics for baloths, but woodcrasher baloths have a climbing speed of 30 feet in addition to their normal walking speed.

```statblock
"name": "Woodcrasher Baloth (PSZ)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d12 + 30"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "11"
  - !!int "5"
"speed": "30 ft., climb 50 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "If the baloth moves at least 20 feet straight toward a creature and then\
      \ hits it with a gore attack on the same turn, that target must succeed on a\
      \ DC 13 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the baloth\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 24\
      \ (4d8 + 6) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 22 (3d10 + 6) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/woodcrasher-baloth-psz.webp"
```
^statblock