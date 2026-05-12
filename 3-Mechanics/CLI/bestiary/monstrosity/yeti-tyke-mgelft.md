---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mgelft
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Yeti Tyke"
---
# [Yeti Tyke](3-Mechanics/CLI/bestiary/monstrosity/yeti-tyke-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 34*  

This family of yetis don't normally venture down to the Dankwood. Their home is in the frosty, Snowy Hills up north, where the air is cool and their fluffy-white fur makes for perfect camouflage.

A yeti tyke who has been separated from its family is scared, hungry and looking for a friendly face. Its loud, sorrowful howls will be a sure-fire way to locate where it's currently hiding.

To coax the scared yeti tyke out, you might try the following:

- Yetis have an amazing sense of smell and a smelly snack might do the trick!  
- You might not speak the same language, but some well-pitched yeti howls and yeti hand motions are sure to show that you mean no harm. (Make sure you show how it's done!)  
- This yeti tyke is missing its family, is there a way to disguise yourself as a long-lost yeti relative?  

```statblock
"name": "Yeti Tyke (MGELFT)"
"size": "Small"
"type": "monstrosity"
"alignment": "chaotic silly"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "12"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "cold"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "understands Yeti but can't speak"
"cr": "1/8"
"traits":
  - "desc": "The yeti tyke has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The yeti tyke has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks made to hide in snowy terrain."
    "name": "Snow Camouflage"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) slashing damage, plus 2 (1d4) cold damage. Claw does both slashing\
      \ and cold damage."
    "name": "Claw"
"source":
  - "MGELFT"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/yeti-tyke-mgelft.webp"
```
^statblock