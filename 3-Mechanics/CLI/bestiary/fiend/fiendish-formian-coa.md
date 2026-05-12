---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fiendish Formian"
---
# [Fiendish Formian](3-Mechanics/CLI/bestiary/fiend/fiendish-formian-coa.md)
*Source: Chains of Asmodeus p. 144*  

```statblock
"name": "Fiendish Formian (CoA)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "17"
  - !!int "10"
  - !!int "12"
  - !!int "11"
"speed": "40 ft."
"saves":
  - "strength": !!int "6"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Formian"
"cr": "4"
"traits":
  - "desc": "All fiendish formians within 1 mile of Ekengarik can telepathically communicate\
      \ with each other and Ekengarik."
    "name": "Hive Mind"
"actions":
  - "desc": "The fiendish formian makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage and the target must make a DC 14 Constitution\
      \ saving throw. On a failed save, the target's Strength score is reduced by\
      \ 1. The target dies if this reduces its Strength to 0. Otherwise, the reduction\
      \ lasts until the target finishes a short or long rest."
    "name": "Bite"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/fiendish-formian-coa.webp"
```
^statblock