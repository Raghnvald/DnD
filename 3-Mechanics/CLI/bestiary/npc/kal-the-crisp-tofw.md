---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kal the Crisp"
---
# [Kal the Crisp](3-Mechanics/CLI/bestiary/npc/kal-the-crisp-tofw.md)
*Source: Turn of Fortune's Wheel p. 17*  

```statblock
"name": "Kal the Crisp (ToFW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "constitution": !!int "4"
"damage_resistances": "fire"
"senses": "passive Perception 13"
"languages": "Common plus one more language"
"cr": "4"
"actions":
  - "desc": "Kal makes two Havoc Hammer or Havoc Flask attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage plus 9 (2d8) fire damage. If the target is\
      \ a creature, magical flames cling to it, causing it to take 3 (1d6) fire\
      \ damage at the start of each of its turns. Immediately after taking this damage\
      \ on its turn, the target can make a DC 13 Dexterity saving throw, ending the\
      \ effect on itself on a successful save."
    "name": "Havoc Hammer"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/90 ft., one target. *Hit:*\
      \ 13 (2d12) fire damage. If the target is a creature, magical flames cling\
      \ to it, causing it to take 3 (1d6) fire damage at the start of each of its\
      \ turns. Immediately after taking this damage on its turn, the target can make\
      \ a DC 13 Dexterity saving throw, ending the effect on itself on a successful\
      \ save.\n\nAfter Kal throws the flask, roll a d6; on a 3 or lower, Kal has\
      \ no more flasks to throw."
    "name": "Havoc Flask"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/kal-the-crisp-tofw.webp"
```
^statblock