---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Terra Stomper"
---
# [Terra Stomper](3-Mechanics/CLI/bestiary/beast/terra-stomper-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

Terra stompers are six-legged behemoths that can grow as large as the trees in the Vastwood of Tazeem. (Use the [tyrannosaurus rex](3-Mechanics/CLI/bestiary/beast/tyrannosaurus-rex.md) statistics for these fierce beasts.)

```statblock
"name": "Terra Stomper (PSZ)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "13d12 + 52"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "19"
  - !!int "2"
  - !!int "12"
  - !!int "9"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": ""
"cr": "8"
"actions":
  - "desc": "The terra stomper makes two attacks: one with its bite and one with its\
      \ tail. It can't make both attacks against the same target."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 33 (4d12 + 7) piercing damage. If the target is a Medium or smaller creature,\
      \ it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC\
      \ 17). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the terra stomper can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) bludgeoning damage."
    "name": "Tail"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/terra-stomper-psz.webp"
```
^statblock