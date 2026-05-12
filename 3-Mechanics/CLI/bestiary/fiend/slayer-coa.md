---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Slayer"
---
# [Slayer](3-Mechanics/CLI/bestiary/fiend/slayer-coa.md)
*Source: Chains of Asmodeus p. 30*  

```statblock
"name": "Slayer (CoA)"
"size": "Medium"
"type": "fiend"
"alignment": "host's alignment"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "4"
"stats":
  - !!int "20"
  - !!int "19"
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "8"
  - "intelligence": !!int "5"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+8"
  - "name": "Deception"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "poison"
"senses": "passive Perception 16"
"languages": "Languages of the host"
"cr": "12"
"traits":
  - "desc": "During its first turn, the Slayer has advantage on attack rolls against\
      \ any creature that hasn't taken a turn. Any hit the Slayer scores against a\
      \ surprised creature is a critical hit."
    "name": "Assassinate"
  - "desc": "Magical darkness doesn't impede the Slayer's darkvision."
    "name": "Devil's Sight"
  - "desc": "The Slayer has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Slayer makes four Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage plus 7 (2d6) poison damage. The Slayer deals\
      \ an extra 14 (4d6) slashing damage when it has advantage on the attack roll\
      \ and hits the target."
    "name": "Claw"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/slayer-coa.webp"
```
^statblock