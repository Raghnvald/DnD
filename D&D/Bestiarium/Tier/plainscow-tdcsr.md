---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tdcsr
  - Monster/HG/2
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Größe/Groß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Plainscow
---
# [Plainscow](3-Mechanics\CLI\bestiary\beast/plainscow-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 248*  

The hulking plainscow is an exceptionally sturdy beast of burden native to the "Dividing Plains" and used by the people of central Tal'Dorei for centuries. Though many wild herds still roam the plains, domesticated plainscows are more common, used as mounts, pack animals, and livestock. Plainscows are unusually empathetic for beasts, and often bond with a rider for life. They stand 6 feet tall, weigh about two tons, and live for 70 years.

## Market Value

Plainscows can be bought in "Westruun" for 200 gp. A plainscow has a carrying capacity of 1,500 pounds.

```statblock
"name": "Plainscow (TDCSR)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "16"
  - !!int "2"
  - !!int "10"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+2"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "passive Perception 10"
"languages": ""
"cr": "2"
"traits":
  - "desc": "If the plainscow moves at least 20 feet straight toward a creature and\
      \ then hits it with a hooves attack on the same turn, that target must succeed\
      \ on a DC 14 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is [prone](/3-Mechanics/CLI/conditions.md#Prone), the plainscow\
      \ can make another attack with its hooves as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Hooves"
"source":
  - "TDCSR"
"image": "/3-Mechanics/CLI/bestiary/beast/token/plainscow-tdcsr.webp"
```
^statblock

## Environment

grassland, hill, urban