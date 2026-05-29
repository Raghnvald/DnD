---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sharkbody Abomination
Kategorie: Aberration
Größe: Groß
HG: 2
status: WIP
linter-yaml-title-alias: Sharkbody Abomination
tags:
  - Monster/Größe/Groß
  - Monster/HG/2
  - Monster/Typ/aberration
  - Quelle/5e/egw
aliases:
  - Sharkbody Abomination
---
# [Sharkbody Abomination](3-Mechanics\CLI\bestiary\aberration/sharkbody-abomination-egw.md)
*Source: Explorer's Guide to Wildemount p. 215*  

The sahuagin shaman Selachai tapped into Uk'otoa's magic to wreak vengeance on the shark hunters of Palma Flora. The unfortunate hunters who failed to escape were transformed into monstrosities with coarse grayish skin, the head of a shark, and a muscular, humanoid physique. These creatures possess all their previous intelligence and personality, but they respond to the control of their sahuagin masters' Shark Telepathy.

The true horror of the sharkbody abominations is that they might be people the characters met and left behind in the first part of this adventure. If you want to sting your players' emotions as they fight these monsters, describe how the sharkbody abomination resembles a specific NPC the characters failed to save.

The curse that transformed it into an abomination can be undone only by a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell or similar magic.

```statblock
"name": "Sharkbody Abomination (EGW)"
"size": "Large"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "15"
  - !!int "1"
  - !!int "10"
  - !!int "4"
"speed": "20 ft., swim 40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., passive Perception\
  \ 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The abomination has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The abomination can breathe only underwater."
    "name": "Water Breathing"
  - "desc": "The abomination can breathe air and water, but it needs to be submerged\
      \ at least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) piercing damage."
    "name": "Bite"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/sharkbody-abomination-egw.webp"
```
^statblock