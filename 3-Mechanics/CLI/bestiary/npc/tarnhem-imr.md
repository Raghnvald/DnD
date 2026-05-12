---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tarnhem"
---
# [Tarnhem](3-Mechanics/CLI/bestiary/npc/tarnhem-imr.md)
*Source: Infernal Machine Rebuild p. 19*  

```statblock
"name": "Tarnhem (IMR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "262"
"hit_dice": "21d12 + 126"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "15"
  - !!int "22"
  - !!int "20"
  - !!int "16"
  - !!int "22"
"speed": "40 ft., fly 80 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "12"
  - "wisdom": !!int "9"
  - "charisma": !!int "12"
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
  - "[whip](3-Mechanics/CLI/items/whip.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 13"
"languages": "Abyssal, telepathy 120 ft."
"cr": "19"
"traits":
  - "desc": "When Tarnhem dies, it explodes, and each creature within 30 feet of it\
      \ must make a DC 20 Dexterity saving throw, taking 70 (20d6) fire damage on\
      \ a failed save, or half as much damage on a successful one. The explosion ignites\
      \ flammable objects in that area that aren't being worn or carried, and it destroys\
      \ Tarnhem's weapons."
    "name": "Death Throes"
  - "desc": "At the start of each of Tarnhem's turns, each creature within 5 feet\
      \ of it takes 10 (3d6) fire damage, and flammable objects in the aura that\
      \ aren't being worn or carried ignite. A creature that touches Tarnhem or hits\
      \ it with a melee attack while within 5 feet of it takes 10 (3d6) fire damage."
    "name": "Fire Aura"
  - "desc": "Tarnhem has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Tarnhem's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d4 + 8) bludgeoning damage plus 7 (2d6) fire damage."
    "name": "Fist of Retribution"
  - "desc": "Tarnhem makes two attacks: one with its longsword and one with its whip."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (3d8 + 8) slashing damage plus 13 (3d8) lightning damage. If Tarnhem\
      \ scores a critical hit, it rolls damage dice three times, instead of twice."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 30 ft., one target. *Hit:*\
      \ 15 (2d6 + 8) slashing damage plus 10 (3d6) fire damage, and the target\
      \ must succeed on a DC 20 Strength saving throw or be pulled up to 25 feet toward\
      \ Tarnhem."
    "name": "Whip"
  - "desc": "Tarnhem magically teleports, along with any equipment it is wearing or\
      \ carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/tarnhem-imr.webp"
```
^statblock