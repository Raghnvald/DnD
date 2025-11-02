---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/2
  - monster/size/medium
  - monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Mind Flayer Nothic
---
# [Mind Flayer Nothic](3-Mechanics\CLI\bestiary\aberration/mind-flayer-nothic-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 155*  

A nothic is a monstrous creature with terrible talons and a single great eye. When driven to violence, it uses its horrific gaze to rot the flesh from its enemies' bones.

```statblock
"name": "Mind Flayer Nothic (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 12"
"languages": "Undercommon"
"cr": "2"
"traits":
  - "desc": "The nothic has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The nothic makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Claw"
  - "desc": "The nothic magically emits psychic energy in a 30-foot cone. Each creature\
      \ in that area must succeed on a DC 12 Intelligence saving throw or take 10\
      \ (2d8 + 1) psychic damage and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the end of its next turn."
    "name": "Mind Blast (Recharge 5-6)"
  - "desc": "The nothic targets one creature it can see within 30 feet of it. The\
      \ target must contest its Charisma ([Deception](/3-Mechanics/CLI/skills.md#Deception))\
      \ check against the nothic's Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight))\
      \ check. If the nothic wins, it magically learns one fact or secret about the\
      \ target. The target automatically wins if it is immune to being [charmed](/3-Mechanics/CLI/conditions.md#Charmed)."
    "name": "Weird Insight"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/mind-flayer-nothic-pabtso.webp"
```
^statblock