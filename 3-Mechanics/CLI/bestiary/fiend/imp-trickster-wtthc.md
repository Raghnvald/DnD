---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Imp Trickster"
---
# [Imp Trickster](3-Mechanics/CLI/bestiary/fiend/imp-trickster-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

```statblock
"name": "Imp Trickster (WttHC)"
"size": "Tiny"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "13"
  - !!int "11"
  - !!int "12"
  - !!int "14"
"speed": "20 ft., climb 20 ft., fly 40 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Common, Infernal"
"cr": "1"
"traits":
  - "desc": "The imp has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 1d6 + 3 Piercing damage\
      \ plus 2d6 Poison damage."
    "name": "Sting"
  - "desc": "The imp has the [Invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ condition for 1 minute. This effect ends early immediately after the imp makes\
      \ an attack roll or deals damage, or if the imp has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Invisibility"
  - "desc": "The imp shape-shifts to resemble a rat ([Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
      \ 20 ft.), a raven (20 ft., Fly 60 ft.), or a spider (20 ft., Climb 20 ft.),\
      \ or it returns to its true form. Its game statistics are the same in each form,\
      \ except for its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md).\
      \ Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/imp-trickster-wtthc.webp"
```
^statblock