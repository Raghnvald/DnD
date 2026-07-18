---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Riesenzitteraal
Status: WIP
linter-yaml-title-alias: Riesenzitteraal
tags:
  - Monster/Größe/Groß
  - Monster/HG/3
  - Monster/Typ/Tier
  - Quelle/5e/tftyp
aliases:
  - Giant Lightning Eel
  - Riesenzitteraal
---
# Riesenzitteraal
*Source: Tales from the Yawning Portal p. 236*  

```statblock
"name": "Riesenzitteraal (TftYP)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "17"
  - !!int "16"
  - !!int "2"
  - !!int "12"
  - !!int "3"
"speed": "5 ft., swim 30 ft."
"damage_resistances": "lightning"
"senses": "blindsight 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The eel can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "The eel makes two bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) piercing damage plus 4 (1d8) lightning damage."
    "name": "Bite"
  - "desc": "One creature the eel touches within 5 feet of it outside water, or each\
      \ creature within 15 feet of it in a body of water, must make a DC 12 Constitution\
      \ saving throw. On failed save, a target takes 13 (3d8) lightning damage. If\
      \ the target takes any of this damage, the target is stunned until the end of\
      \ the eel's next turn. On a successful save, a target takes half as much damage\
      \ and isn't stunned."
    "name": "Lightning Jolt (Recharge 5-6)"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/beast/token/giant-lightning-eel-tftyp.webp"
```
^statblock