---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thessalar's Homunculus"
---
# [Thessalar's Homunculus](3-Mechanics/CLI/bestiary/npc/thessalars-homunculus-imr.md)
*Source: Infernal Machine Rebuild p. 35*  

```statblock
"name": "Thessalar's Homunculus (IMR)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "5"
"hit_dice": "2d4"
"modifier": !!int "2"
"stats":
  - !!int "4"
  - !!int "15"
  - !!int "11"
  - !!int "10"
  - !!int "10"
  - !!int "7"
"speed": "20 ft., fly 40 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "0"
"traits":
  - "desc": "While the homunculus is on the same plane of existence as its master,\
      \ it can magically convey what it senses to its master, and the two can communicate\
      \ telepathically."
    "name": "Telepathic Bond"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 1 piercing damage, and the target must succeed on a DC 10 Constitution saving\
      \ throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) for 1\
      \ minute. If the saving throw fails by 5 or more, the target is instead [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 5 (1d10) minutes and [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) acid damage."
    "name": "Acidic Spittle"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/thessalars-homunculus-imr.webp"
```
^statblock