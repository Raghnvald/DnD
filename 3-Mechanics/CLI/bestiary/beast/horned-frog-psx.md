---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Horned Frog"
---
# [Horned Frog](3-Mechanics/CLI/bestiary/beast/horned-frog-psx.md)
*Source: Plane Shift: Ixalan p. 39*  

Frogs are more commonly heard than seen in Ixalan, joining their voices to the vivid soundscape of the jungle. They range from tiny poisonous tree frogs found in the branches of tall trees to huge horned frogs that lurk in marshy areas.

```statblock
"name": "Horned Frog (PSX)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "11"
  - !!int "2"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The frog can breathe air and water."
    "name": "Amphibious"
  - "desc": "The frog's long jump is up to 20 feet and its high jump is up to 10 feet,\
      \ with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d6 + 1) piercing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 11). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the frog can't bite another target."
    "name": "Bite"
  - "desc": "The frog makes one bite attack against a Small or smaller target it is\
      \ grappling. If the attack hits, the target is swallowed, and the grapple ends.\
      \ The swallowed target is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the frog, and it takes 5 (2d4)\
      \ acid damage at the start of each of the frog's turns. The frog can have only\
      \ one target swallowed at a time. If the frog dies, a swallowed creature is\
      \ no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) by\
      \ it and can escape from the corpse using 5 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/horned-frog-psx.webp"
```
^statblock