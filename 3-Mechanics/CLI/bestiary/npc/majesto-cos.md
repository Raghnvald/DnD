---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Majesto"
---
# [Majesto](3-Mechanics/CLI/bestiary/npc/majesto-cos.md)
*Source: Curse of Strahd p. 115*  

```statblock
"name": "Majesto (CoS)"
"size": "Tiny"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "13"
  - !!int "11"
  - !!int "12"
  - !!int "14"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+4"
  - "name": "Insight"
    "desc": "+3"
  - "name": "Persuasion"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+5"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with silvered weapons"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Infernal, Common"
"cr": "1"
"traits":
  - "desc": "Majesto can use its action to polymorph into a beast form that resembles\
      \ a rat (speed 20 ft.), a raven (20 ft., fly 60 ft.), or a spider (20 ft., climb\
      \ 20 ft.), or back into its true form. Its statistics are the same in each form,\
      \ except for the speed changes noted. Any equipment it is wearing or carrying\
      \ isn't transformed. It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "Magical darkness doesn't impede Majesto's darkvision."
    "name": "Devil's Sight"
  - "desc": "Majesto has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) piercing damage, and the target must make a DC 11 Constitution\
      \ saving throw, taking 10 (3d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Sting (Bite in Beast Form)"
  - "desc": "Majesto magically turns invisible until it attacks, or until its concentration\
      \ ends (as if concentrating on a spell). Any equipment Majesto wears or carries\
      \ is invisible with it."
    "name": "Invisibility"
"source":
  - "CoS"
"image": "3-Mechanics/CLI/bestiary/npc/token/majesto-cos.webp"
```
^statblock