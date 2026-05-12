---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Caldron Magen"
---
# [Caldron Magen](3-Mechanics/CLI/bestiary/construct/caldron-magen-nf.md)
*Source: Netheril's Fall*  

Caldron magen are powerful bodyguards that stretch their limbs and spit acid in defense of those they protect.

```statblock
"name": "Caldron Magen (NF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_immunities": "acid, poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 14"
"languages": "understands Common plus two other languages but can't speak"
"cr": "4"
"traits":
  - "desc": "If the magen dies, it disintegrates into dust, leaving behind anything\
      \ it was wearing or carrying."
    "name": "Disintegration"
  - "desc": "The magen has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The magen makes two attacks, using Extended Fist or Acid Spittle in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 15 ft. *Hit:* 8 (1d8 + 4) Bludgeoning\
      \ damage plus 5 (1d10) Acid damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 14) from one of two fists."
    "name": "Extended Fist"
  - "desc": "*Ranged Attack Roll:* +6, range 60 ft. *Hit:* 13 (2d8 + 4) Acid damage."
    "name": "Acid Spittle"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/construct/token/caldron-magen-nf.webp"
```
^statblock

## Environment

any