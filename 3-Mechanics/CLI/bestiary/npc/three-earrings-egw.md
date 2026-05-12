---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Three Earrings"
---
# [Three Earrings](3-Mechanics/CLI/bestiary/npc/three-earrings-egw.md)
*Source: Explorer's Guide to Wildemount p. 211*  

This pale, spotted, Tabaxi bandit captain is a low-ranking member of the Revelry pirates. She brought her vessel to the village of Palma Flora because she was informed that a local sahuagin tribe had uncovered an unusual treasure. Three Earrings rightly assumed that they were going to attack the village, and she intended to be there to plunder the ruins after the attack. She didn't anticipate Flora Isle sinking.

```statblock
"name": "Three Earrings (EGW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "studded leather"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Deception"
    "desc": "+4"
"gear":
  - "dagger"
  - "scimitar"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "any two languages"
"cr": "2"
"traits":
  - "desc": "Three"
    "name": "Feline Agility"
"actions":
  - "desc": "The captain makes three melee attacks: two with its scimitar and one\
      \ with its dagger. Or Three Earrings makes two ranged attacks with its daggers."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Scimitar"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
  - "desc": "+4"
    "name": "Claws"
"reactions":
  - "desc": "The captain adds 2 to its AC against one melee attack that would hit\
      \ it. To do so, Three Earrings must see the attacker and be wielding a melee\
      \ weapon."
    "name": "Parry"
"source":
  - "EGW"
"image": "3-Mechanics/CLI/bestiary/npc/token/three-earrings-egw.webp"
```
^statblock