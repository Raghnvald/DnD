---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Dolphin
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Küste
  - Monster/Habitat/underwater
  - Monster/HG/1-8
  - Monster/Typ/Tier
  - Quelle/5e/vgm
aliases:
  - Dolphin
---
# [Dolphin](3-Mechanics\CLI\bestiary\beast/dolphin-vgm.md)
*Source: Volo's Guide to Monsters p. 208, Ghosts of Saltmarsh*  

Dolphins are clever, social marine mammals that feed on small fish and squid. An adult specimen is between 5 and 6 feet long.

```statblock
"name": "Dolphin (VGM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "13"
  - !!int "6"
  - !!int "12"
  - !!int "7"
"speed": "0 ft., swim 60 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "If the dolphin moves at least 30 feet straight toward a target and then\
      \ hits it with a slam attack on the same turn, the target takes an extra 3 (1d6)\
      \ bludgeoning damage."
    "name": "Charge"
  - "desc": "The dolphin can hold its breath for 20 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage."
    "name": "Slam"
"source":
  - "VGM"
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/beast/token/dolphin-vgm.webp"
```
^statblock

## Environment

underwater, coastal