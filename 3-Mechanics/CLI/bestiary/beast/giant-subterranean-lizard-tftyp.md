---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Subterranean Lizard"
---
# [Giant Subterranean Lizard](3-Mechanics/CLI/bestiary/beast/giant-subterranean-lizard-tftyp.md)
*Source: Tales from the Yawning Portal p. 236*  

```statblock
"name": "Giant Subterranean Lizard (TftYP)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "66"
"hit_dice": "7d12 + 21"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "10"
  - !!int "7"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "passive Perception 10"
"languages": ""
"cr": "4"
"actions":
  - "desc": "The lizard makes two attacks: one with its bite and one with its tail.\
      \ One attack can be replaced by Swallow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) piercing damage and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 15). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the lizard can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target not grappled\
      \ by the lizard. *Hit:* 12 (2d6 + 5) bludgeoning damage. If the target is\
      \ a creature, it must succeed on a DC 15 Strength saving throw or be knocked\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one Medium or smaller\
      \ creature the lizard is grappling. *Hit:* 16 (2d10 + 5) piercing damage.\
      \ The target is swallowed, and the grapple ends. The swallowed target is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the lizard, and it takes 10\
      \ (3d6) acid damage at the start of each of the lizard's turns. The lizard\
      \ can have only one target swallowed at a time.\n\nIf the lizard dies, a swallowed\
      \ creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 10 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/beast/token/giant-subterranean-lizard-tftyp.webp"
```
^statblock