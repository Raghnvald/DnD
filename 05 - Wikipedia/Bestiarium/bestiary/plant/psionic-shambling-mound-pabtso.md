---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/cr/5
  - Monster/Größe/Groß
  - Monster/Typ/Pflanze
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Psionic Shambling Mound
---
# [Psionic Shambling Mound](3-Mechanics\CLI\bestiary\plant/psionic-shambling-mound-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 108*  

```statblock
"name": "Psionic Shambling Mound (PaBTSO)"
"size": "Large"
"type": "plant"
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
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+2"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "Whenever the shambling mound is subjected to lightning damage, it takes\
      \ no damage and regains a number of hit points equal to the lightning damage\
      \ dealt."
    "name": "Lightning Absorption"
"actions":
  - "desc": "The shambling mound makes two slam attacks. If both attacks hit a Medium\
      \ or smaller target, the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 14), and the shambling mound uses its Engulf on it."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "The shambling mound engulfs a Medium or smaller creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by it. The engulfed target is [blinded](/3-Mechanics/CLI/conditions.md#Blinded),\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), and unable to breathe,\
      \ and it must succeed on a DC 14 Constitution saving throw at the start of each\
      \ of the mound's turns or take 13 (2d8 + 4) bludgeoning damage. If the mound\
      \ moves, the engulfed target moves with it. The mound can have only one creature\
      \ engulfed at a time."
    "name": "Engulf"
  - "desc": "The shambling mound casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 8):\n\n**At will:** [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\
      \n**1/day:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md) (already\
      \ cast)"
    "name": "Spellcasting (Psionics)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/plant/token/psionic-shambling-mound-pabtso.webp"
```
^statblock