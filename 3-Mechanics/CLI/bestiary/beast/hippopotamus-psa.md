---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hippopotamus"
---
# [Hippopotamus](3-Mechanics/CLI/bestiary/beast/hippopotamus-psa.md)
*Source: Plane Shift: Amonkhet p. 38*  

```statblock
"name": "Hippopotamus (PSA)"
"size": "Huge"
"type": "beast"
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
"speed": "40 ft., swim 30 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "If the hippopotamus moves at least 20 feet straight toward a creature\
      \ and then hits it with a bite attack on the same turn, that target must succeed\
      \ on a DC 12 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the hippopotamus\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
  - "desc": "The hippopotamus can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 19\
      \ (3d8 + 6) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 22 (3d10 + 6) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/beast/token/hippopotamus-psa.webp"
```
^statblock