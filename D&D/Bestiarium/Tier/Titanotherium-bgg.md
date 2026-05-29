---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Titanothere
linter-yaml-title-alias: Titanothere
tags:
  - Monster/Größe/Riesig
  - Monster/HG/5
  - Monster/Typ/Tier
  - Quelle/5e/bgg
aliases:
  - Titanothere
---
# [Titanothere](3-Mechanics\CLI\bestiary\beast/titanothere-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 185*  

Titanotheres are a family of enormous mammals related to rhinoceroses. Some of them lack any horns on the face, while others have one, two, or more horns of various shapes and sizes. Some have rough, almost stony skin; some have horny plates; and some have thick, shaggy fur. These creatures are united by their tremendous stature, their herding behavior, and their irritable disposition.

> [!quote] A quote from Diancastra  
> 
> I have fond memories of riding across an ice sheet on the back of a trusty, thick-furred titanothere I called Woolly. But that was thousands of years ago and many worlds away...

```statblock
"name": "Titanothere (BGG)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "16"
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
  - !!int "6"
"speed": "50 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The titanothere is considered to be one size larger for the purpose of\
      \ determining its carrying capacity."
    "name": "Beast of Burden"
"actions":
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 20\
      \ (3d8 + 7) bludgeoning damage. If the titanothere moved at least 20 feet straight\
      \ toward the target immediately before the hit, the target takes an extra 13\
      \ (3d8) bludgeoning damage, and the target must succeed on a DC 18 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition\
      \ if it is a creature."
    "name": "Stomp"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/beast/token/titanothere-bgg.webp"
```
^statblock