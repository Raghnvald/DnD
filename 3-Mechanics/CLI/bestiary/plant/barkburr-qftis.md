---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Barkburr"
---
# [Barkburr](3-Mechanics/CLI/bestiary/plant/barkburr-qftis.md)
*Source: Quests from the Infinite Staircase p. 195*  

Barkburrs are animate, poisonous Plants that spontaneously grow from trees when a spark of nature's magic takes root in the wood. They appear as limpet-like knots of bark and wood indistinguishable from ordinary tree burls. Barkburrs often act in defense of a grove or forest.

Some barkburrs cling to the trees from which they sprouted, while others slowly wander until they encounter creatures that threaten the forest's natural order. When a barkburr identifies such a creature, the barkburr leaps at the invader and injects it with a poisonous sap that quickly and painfully transforms the creature into a tree.

```statblock
"name": "Barkburr (QftIS)"
"size": "Small"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d6 + 24"
"modifier": !!int "-2"
"stats":
  - !!int "16"
  - !!int "6"
  - !!int "16"
  - !!int "1"
  - !!int "15"
  - !!int "1"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
"damage_immunities": "psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 12"
"languages": ""
"cr": "3"
"traits":
  - "desc": "If the barkburr is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the barkburr\
      \ move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the barkburr is animate."
    "name": "False Appearance"
  - "desc": "With or without a running start, the barkburr's high jump is up to 15\
      \ feet, and its long jump is up to 30 feet. The barkburr's jumps can exceed\
      \ its speed if its speed isn't 0."
    "name": "Springing Leap"
"actions":
  - "desc": "The barkburr makes two Poison Barb attacks and uses Lignify if able."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage, and the barkburr\
      \ attaches to the target. While the barkburr is attached, it can't make Poison\
      \ Barb attacks, and the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition as its body begins to transform into wood.\n\nAn attached barkburr\
      \ can detach itself by spending 5 feet of its movement on its turn. A creature\
      \ that can reach the barkburr, including the target, can use its action to detach\
      \ the barkburr by making a successful DC 13 Strength ([Athletics](3-Mechanics/CLI/rules/skills.md#Athletics))\
      \ check."
    "name": "Poison Barb"
  - "desc": "The barkburr targets the creature it is attached to, and the target must\
      \ make a DC 13 Constitution saving throw. On a failed save, the target has the\
      \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified) condition until\
      \ freed by the [Greater Restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell or another effect, except it turns into a tree instead of stone. Any\
      \ equipment the target is wearing or carrying is absorbed into the tree's bark."
    "name": "Lignify"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/plant/token/barkburr-qftis.webp"
```
^statblock