---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Corrupted Giant Shark
Kategorie: Aberration
Größe: Riesig
HG: 9
status: WIP
tags:
  - Quelle/5e/crcotn
  - ttrpg-cli/monster/cr/9
  - ttrpg-cli/monster/size/huge
  - ttrpg-cli/monster/type/aberration
aliases:
  - Corrupted Giant Shark
---
# [Corrupted Giant Shark](3-Mechanics/CLI/bestiary/aberration/corrupted-giant-shark-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 196*  

In addition to its vicious bite, this giant shark projects a psychic aura that causes painful mental distress in other creatures nearby. The crystals that corrupt the shark's body enable it to regenerate, and only radiant energy or particularly devastating attacks can overcome this unnatural defense.

```statblock
"name": "Corrupted Giant Shark (CRCotN)"
"size": "Huge"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "11"
  - !!int "21"
  - !!int "1"
  - !!int "10"
  - !!int "5"
"speed": "0 ft., swim 50 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
"senses": "blindsight 60 ft., passive Perception 14"
"languages": ""
"cr": "9"
"traits":
  - "desc": "Any creature that starts its turn within 15 feet of the shark must succeed\
      \ on a DC 17 Wisdom saving throw or take 11 (2d10) psychic damage."
    "name": "Psychic Maelstrom"
  - "desc": "The shark regains 10 hit points at the start of its turn. If the shark\
      \ takes radiant damage or suffers a critical hit, this trait doesn't function\
      \ at the start of its next turn. The shark dies only if it starts its turn with\
      \ 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "The shark can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +10 to hit (with advantage if the target is\
      \ a creature missing any hit points), reach 5 ft., one target. *Hit:* 22 (3d10\
      \ + 6) piercing damage, and if the target is a creature, it must succeed on\
      \ a DC 17 Charisma saving throw or gain 1 level of exhaustion."
    "name": "Bite"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/aberration/token/corrupted-giant-shark-crcotn.webp"
```
^statblock