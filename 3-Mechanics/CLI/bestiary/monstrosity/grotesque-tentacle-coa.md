---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grotesque Tentacle"
---
# [Grotesque Tentacle](3-Mechanics/CLI/bestiary/monstrosity/grotesque-tentacle-coa.md)
*Source: Chains of Asmodeus p. 78*  

```statblock
"name": "Grotesque Tentacle (CoA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"modifier": !!int "4"
"stats":
  - !!int "19"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "18"
"speed": "0 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "7"
  - "intelligence": !!int "7"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Celestial, Common"
"cr": "10"
"traits":
  - "desc": "If it dies, the tentacle returns to life in 1d6 days and regains all\
      \ its hit points. Only a wish spell can prevent this trait from functioning."
    "name": "Rejuvenation"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one creature. *Hit:*\
      \ 8 (1d8 + 4) piercing damage, and the target must make a DC 15 Constitution\
      \ saving throw, taking 45 (10d8) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 15/30 ft., one creature. *Hit:*\
      \ The target must make a DC 15 Constitution saving throw, taking 45 (10d8)\
      \ poison damage on a failed save, or half as much damage on a successful one."
    "name": "Spit Poison"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/grotesque-tentacle-coa.webp"
```
^statblock