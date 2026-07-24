---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Cranium Rat Squeaker
Kategorie: Aberration
Größe: Winzig
HG: 0
Status: WIP
linter-yaml-title-alias: Cranium Rat Squeaker
tags:
  - Monster/Größe/Winzig
  - Monster/HG/0
  - Monster/Typ/Aberration
  - Quelle/5e/mpp
aliases:
  - Cranium Rat Squeaker
status: WIP
---
# [Cranium Rat Squeaker](3-Mechanics/CLI/bestiary/aberration/cranium-rat-squeaker-mpp.md)
*Source: Morte's Planar Parade p. 22*  

The cranium rats squeakers of Sigil have no connection to the mind flayers that created their progenitors. Rather, these magical rodents cooperate with the residents of the City of Doors, whether by simply living together or by pursuing greater ambitions. When squeakers collect in large numbers, their swarms merge into a single intelligence with enhanced psionic abilities and the accumulated memories of its constituents.

```statblock
"name": "Cranium Rat Squeaker (MPP)"
"size": "Tiny"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "2"
"stats":
  - !!int "2"
  - !!int "14"
  - !!int "10"
  - !!int "4"
  - !!int "11"
  - !!int "8"
"speed": "30 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 10"
"languages": "telepathy 30 ft. (emotions only)"
"cr": "0"
"traits":
  - "desc": "Any creature touching the cranium rat can use the rat's telepathy if\
      \ the rat allows it. If the creature knows any language, the creature can use\
      \ the telepathy to communicate words and emotions."
    "name": "Shared Telepathy"
  - "desc": "The cranium rat is immune to any effect that would sense its emotions\
      \ or read its thoughts, as well as to divination spells."
    "name": "Telepathic Shroud"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 1\
      \ piercing damage."
    "name": "Bite"
"bonus_actions":
  - "desc": "The cranium rat sheds dim light from its exposed brain in a 5-foot radius\
      \ or extinguishes the light."
    "name": "Illumination"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/cranium-rat-squeaker-mpp.webp"
```
^statblock