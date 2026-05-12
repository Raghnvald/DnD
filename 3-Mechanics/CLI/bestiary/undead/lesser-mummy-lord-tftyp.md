---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lesser Mummy Lord"
---
# [Lesser Mummy Lord](3-Mechanics/CLI/bestiary/undead/lesser-mummy-lord-tftyp.md)
*Source: Tales from the Yawning Portal p. 224*  

```statblock
"name": "Lesser Mummy Lord (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "11"
  - !!int "18"
  - !!int "16"
"speed": "20 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"damage_resistances": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "the languages it knew in life"
"cr": "15"
"traits":
  - "desc": "The mummy lord has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "A destroyed mummy lord gains a new body in 24 hours if its heart is intact,\
      \ regaining all its hit points and becoming active again. The new body appears\
      \ within 5 feet of the mummy lord's heart."
    "name": "Rejuvenation"
  - "desc": "The mummy wears a [ring of fire resistance](3-Mechanics/CLI/items/ring-of-fire-resistance-xdmg.md)."
    "name": "Special Equipment"
"actions":
  - "desc": "The mummy can use its Dreadful Glare and makes one attack with its rotting\
      \ fist."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
      \ is a creature, it must succeed on a DC 16 Constitution saving throw or be\
      \ cursed with mummy rot. The cursed target can't regain hit points, and its\
      \ hit point maximum decreases by 10 (3d6) for every 24 hours that elapse.\
      \ If the curse reduces the target's hit point maximum to 0, the target dies,\
      \ and its body turns to dust. The curse lasts until removed by the [remove curse](3-Mechanics/CLI/spells/remove-curse-xphb.md)\
      \ spell or other magic."
    "name": "Rotting Fist"
  - "desc": "The mummy lord targets one creature it can see within 60 feet of it.\
      \ If the target can see the mummy lord, it must succeed on a DC 16 Wisdom saving\
      \ throw against this magic or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ until the end of the mummy's next turn. If the target fails the saving throw\
      \ by 5 or more, it is also [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ for the same duration. A target that succeeds on the saving throw is immune\
      \ to the Dreadful Glare of all mummies and mummy lords for the next 24 hours."
    "name": "Dreadful Glare"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/undead/token/lesser-mummy-lord-tftyp.webp"
```
^statblock