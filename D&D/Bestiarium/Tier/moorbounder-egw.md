---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Moorbounder
Status: WIP
linter-yaml-title-alias: Moorbounder
tags:
  - Monster/Größe/Groß
  - Monster/HG/1
  - Monster/Typ/Tier
  - Quelle/5e/egw
aliases:
  - Moorbounder
---
# [Moorbounder](3-Mechanics\CLI\bestiary\beast/moorbounder-egw.md)
*Source: Explorer's Guide to Wildemount p. 295*  

One of the many predators to stalk the marshlands and muddy foothills of Xhorhas, moorbounders are known as dangerous killers to those who try to avoid them on their travels—and as prized mounts for those willing to capture and train them. Though the process of domesticating a moorbounder is fraught with peril, these creatures can become favored hunting companions and powerful war mounts.

## Natural Hunters

Moorbounders hunt with elongated tusks and retractable claws. With a vague resemblance to large hunting cats, their muscular bodies are built for combat, granting them incredible prowess at leaping and a running speed that makes them dominant carnivores.

```statblock
"name": "Moorbounder (EGW)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d10 + 8"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "2"
  - !!int "13"
  - !!int "5"
"speed": "70 ft."
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The moorbounder's long jump is up to 40 feet and its high jump is up\
      \ to 20 feet, with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (4d4 + 4) slashing damage."
    "name": "Claws"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/beast/token/moorbounder-egw.webp"
```
^statblock