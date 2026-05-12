---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Whirlwyrm"
---
# [Whirlwyrm](3-Mechanics/CLI/bestiary/beast/whirlwyrm-tofw.md)
*Source: Turn of Fortune's Wheel p. 52*  

```statblock
"name": "Whirlwyrm (ToFW)"
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
"speed": "30 ft., swim 50 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The whirlwyrm can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The whirlwyrm makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 21\
      \ (3d10 + 5) piercing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the whirlwyrm can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target not [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the whirlwyrm. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target\
      \ is a creature, it must succeed on a DC 16 Strength saving throw or be knocked\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/beast/token/whirlwyrm-tofw.webp"
```
^statblock