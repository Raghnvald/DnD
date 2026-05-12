---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elder Giant Lizard"
---
# [Elder Giant Lizard](3-Mechanics/CLI/bestiary/beast/elder-giant-lizard-tftyp.md)
*Source: Tales from the Yawning Portal p. 176*  

```statblock
"name": "Elder Giant Lizard (TftYP)"
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
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The lizard can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The lizard makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 21\
      \ (3d10 + 5) piercing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the lizard can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target not [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the lizard. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is\
      \ a creature, it must succeed on a DC 16 Strength saving throw or be knocked\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/beast/token/elder-giant-lizard-tftyp.webp"
```
^statblock