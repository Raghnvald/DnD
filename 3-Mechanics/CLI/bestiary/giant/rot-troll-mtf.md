---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mtf
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rot Troll"
---
# [Rot Troll](3-Mechanics/CLI/bestiary/giant/rot-troll-mtf.md)
*Source: Mordenkainen's Tome of Foes p. 244, Return to Glory p. 34*  

## Rot Troll

A troll that is infused with waves of necrotic energy as it regenerates can develop a symbiotic relationship with that deathly power. The troll's body withers, and its flesh falls away from the body as quickly as it forms. Eventually a rot troll becomes unable to regenerate, though it still heals normally. The creature courses with necrotic energy that flows out of its withered form. Simply standing near a rot troll exposes other creatures to its lethal emanations.

## Trolls

Trolls that are nearly obliterated but survive and regenerate from mere scraps of flesh can display bizarre mutations. One of these warped trolls is especially likely to arise if the creature regenerates in the presence of magical emanations, planar energy, disease, or death on a vast scale, or if its body was damaged by elemental forces. These mutated forms can also be produced and shaped by the ritual magic of evil spellcasters.

```statblock
"name": "Rot Troll (MTF)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d10 + 72"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "22"
  - !!int "5"
  - !!int "8"
  - !!int "4"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "necrotic"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Giant"
"cr": "9"
"traits":
  - "desc": "At the end of each of the troll's turns, each creature within 5 feet\
      \ of it takes 11 (2d10) necrotic damage, unless the troll has taken acid or\
      \ fire damage since the end of its last turn."
    "name": "Rancid Degeneration"
"actions":
  - "desc": "The troll makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage plus 16 (3d10) necrotic damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 5 (1d10) necrotic damage."
    "name": "Claws"
"source":
  - "MTF"
  - "RtG"
"image": "3-Mechanics/CLI/bestiary/giant/token/rot-troll-mtf.webp"
```
^statblock

## Environment

desert, forest, swamp, underdark