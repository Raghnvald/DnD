---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Old Croaker
tags:
  - Monster/Größe/Groß
  - Monster/HG/1
  - Monster/Typ/Tier
  - Quelle/5e/egw
aliases:
  - Old Croaker
linter-yaml-title-alias: Old Croaker
---
# [Old Croaker](3-Mechanics\CLI\bestiary\npc/old-croaker-egw.md)
*Source: Explorer's Guide to Wildemount p. 240*  

```statblock
"name": "Old Croaker (EGW)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "13"
  - !!int "2"
  - !!int "10"
  - !!int "3"
"speed": "20 ft., swim 40 ft."
"damage_immunities": "cold"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 30 ft., passive Perception\
  \ 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "Old Croaker can breathe air and water."
    "name": "Amphibious"
  - "desc": "Old Croaker's long jump is up to 20 feet and its high jump is up to 10\
      \ feet, with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10\
      \ + 2) piercing damage plus 5 (1d10) poison damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 13). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and Old Croaker can't bite another target."
    "name": "Bite"
  - "desc": "Old Croaker makes one bite attack against a Medium or smaller target\
      \ it is grappling. If the attack hits, the target is swallowed, and the grapple\
      \ ends. The swallowed target is [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside Old Croaker, and it takes\
      \ 10 (3d6) acid damage at the start of each of Old Croaker's turns. Old Croaker\
      \ can have only one target swallowed at a time.\n\nIf Old Croaker dies, a swallowed\
      \ creature is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 5 feet of movement, exiting [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/npc/token/old-croaker-egw.webp"
```
^statblock