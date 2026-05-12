---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ophelia"
---
# [Ophelia](3-Mechanics/CLI/bestiary/npc/ophelia-tofw.md)
*Source: Turn of Fortune's Wheel p. 49*  

```statblock
"name": "Ophelia (ToFW)"
"size": "Huge"
"type": "beast"
"alignment": "Lawful Good"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "17"
  - !!int "10"
  - !!int "14"
  - !!int "14"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": "Common"
"cr": "4"
"traits":
  - "desc": "If Ophelia moves at least 20 feet straight toward a creature and then\
      \ hits it with a gore attack on the same turn, that target must succeed on a\
      \ DC 12 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), Ophelia\
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
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/ophelia-tofw.webp"
```
^statblock