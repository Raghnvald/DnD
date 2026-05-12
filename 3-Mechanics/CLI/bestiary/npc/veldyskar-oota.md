---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Veldyskar"
---
# [Veldyskar](3-Mechanics/CLI/bestiary/npc/veldyskar-oota.md)
*Source: Out of the Abyss p. 151*  

```statblock
"name": "Veldyskar (OotA)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "15"
  - !!int "10"
  - !!int "8"
  - !!int "7"
"speed": "20 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "Common, Dwarvish, Giant, Undercommon"
"cr": "3"
"traits":
  - "desc": "Veldyskar can innately cast the following spell, requiring no material\
      \ components:\n\n**1/day:** [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)"
    "name": "Innate Spellcasting"
  - "desc": "If a creature starts its turn within 30 feet of Veldyskar and the two\
      \ of them can see each other, Veldyskar can force the creature to make a DC\
      \ 12 Constitution saving throw if Veldyskar isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated).\
      \ On a failed save, the creature magically begins to turn to stone and is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ It must repeat the saving throw at the end of its next turn. On a success,\
      \ the effect ends. On a failure, the creature is [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)\
      \ until freed by the  [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell or other magic.\n\nA creature that isn't [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised)\
      \ can avert its eyes to avoid the saving throw at the start of its turn. If\
      \ it does so, it can't see Veldyskar until the start of its next turn, when\
      \ it can avert its eyes again. If it looks at Veldyskar in the meantime, it\
      \ must immediately make the save.\n\nIf Veldyskar sees its reflection within\
      \ 30 feet of it in bright light, it mistakes itself for a rival and targets\
      \ itself with its gaze."
    "name": "Petrifying Gaze"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) piercing damage plus 7 (2d6) poison damage."
    "name": "Bite"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/veldyskar-oota.webp"
```
^statblock