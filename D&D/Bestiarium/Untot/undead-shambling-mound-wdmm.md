---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Undead Shambling Mound
Status: WIP
linter-yaml-title-alias: Undead Shambling Mound
tags:
  - Monster/Größe/Groß
  - Monster/HG/5
  - Monster/Typ/Untote
  - Quelle/5e/wdmm
aliases:
  - Undead Shambling Mound
---
# [Undead Shambling Mound](3-Mechanics\CLI\bestiary\undead/undead-shambling-mound-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 142*  

Made entirely of skulls and bones.

```statblock
"name": "Undead Shambling Mound (WDMM)"
"size": "Large"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "16"
  - !!int "5"
  - !!int "10"
  - !!int "5"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+2"
"damage_resistances": "cold, fire"
"damage_immunities": "necrotic, poison"
"condition_immunities": "blinded, deafened, exhaustion, poisoned"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "Whenever the shambling mound is subjected to necrotic damage, it takes\
      \ no damage and regains a number of hit points equal to the necrotic damage\
      \ dealt."
    "name": "Necrotic Absorption"
"actions":
  - "desc": "The shambling mound makes two slam attacks. If both attacks hit a Medium\
      \ or smaller target, the target is grappled (escape DC 14), and the shambling\
      \ mound uses its Engulf on it."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "The shambling mound engulfs a Medium or smaller creature grappled by\
      \ it. The engulfed target is blinded, restrained, and unable to breathe, and\
      \ it must succeed on a DC 14 Constitution saving throw at the start of each\
      \ of the mound's turns or take 13 (2d8 + 4) bludgeoning damage. If the mound\
      \ moves, the engulfed target moves with it. The mound can have only one creature\
      \ engulfed at a time."
    "name": "Engulf"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/undead/token/undead-shambling-mound-wdmm.webp"
```
^statblock