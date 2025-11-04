---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/cr/0
  - Monster/Größe/Winzig
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Frog
---
# [Frog](3-Mechanics\CLI\bestiary\beast/frog.md)
*Source: Monster Manual p. 322. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

A frog has no effective attacks. It feeds on small insects and typically dwells near water, in trees, or underground. The frog's statistics can also be used to represent a toad.

```statblock
"name": "Frog"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "1"
"stats":
  - !!int "1"
  - !!int "13"
  - !!int "8"
  - !!int "1"
  - !!int "8"
  - !!int "3"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 30 ft., passive Perception\
  \ 11"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The frog can breathe air and water."
    "name": "Amphibious"
  - "desc": "The frog's long jump is up to 10 feet and its high jump is up to 5 feet,\
      \ with or without a running start."
    "name": "Standing Leap"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/beast/token/frog.webp"
```
^statblock