---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mismv1
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Coral"
---
# [Coral](3-Mechanics/CLI/bestiary/npc/coral-mismv1.md)
*Source: Misplaced Monsters: Volume 1 p. 4*  

> [!note]
> Created by Kenzie C.

Coral lives in the ocean and in the clouds. Cookies are her favorite snack. She has the power to bolster other creatures, and she can bestow upon animals the ability to speak for a short time. When she is upset, her rainbow tail lights up. If she smacks her tail on the ground, magical force spreads outward to engulf an enemy, potentially turning it to dust. When Coral has the hiccups, bubbles shoot from her horn. These bubbles transform into tasty cookies, bursts of glitter, and protective clouds of stinky gas.

```statblock
"name": "Coral (MisMV1)"
"size": "Large"
"type": "fey"
"alignment": "Chaotic Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d10 + 36"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "13"
  - !!int "15"
  - !!int "14"
  - !!int "18"
  - !!int "19"
"speed": "10 ft., fly 60 ft., swim 60 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 18"
"languages": "Common, Primordial, Sylvan"
"cr": "9"
"traits":
  - "desc": "Coral has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Coral makes two Hoof attacks and uses Tail Thump."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) bludgeoning damage."
    "name": "Hoof"
  - "desc": "Coral slams her tail down, unleashing a burst of magical force toward\
      \ one creature she can see within 60 feet of her. The target must make a DC\
      \ 16 Dexterity saving throw. On a failed save, the target takes 22 (4d10)\
      \ force damage and has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. On a successful save, the target takes half as much damage only.\
      \ If this damage reduces the target to 0 hit points, the target dies, and its\
      \ body is reduced to fine dust."
    "name": "Tail Thump"
"bonus_actions":
  - "desc": "Coral produces a stream of magical bubbles from her horn. These bubbles\
      \ float toward a creature Coral can see within 60 feet of herself. Roll a d6\
      \ to determine the bubbles' effect:\n\n- **1-2 Bolstering Treat.** The bubbles\
      \ transform into 1d4 cookies that appear in the target's space. The target\
      \ gains 11 (2d8 + 2) temporary hit points if it immediately uses its reaction\
      \ to eat one of the cookies. Any leftover cookies are delicious but confer no\
      \ benefits.  \n- **3-4 Sparkle Burst.** The bubbles transform into glitter that\
      \ swirls around the target before bursting outward. Each creature within 5 feet\
      \ of the target must succeed on a DC 16 Constitution saving throw or have the\
      \ [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) condition until the\
      \ start of Coral's next turn.  \n- **5-6 Stink Bomb Shield.** The bubbles transform\
      \ into a foul-smelling cloud of gas that surrounds and shields the target. The\
      \ target has half cover until the gas disappears at the start of Coral's next\
      \ turn.  "
    "name": "Bubbles of Whimsy (2/Day)"
  - "desc": "Coral targets one Beast she can see within 10 feet of herself. The target\
      \ gains the ability to understand and speak Common or Sylvan (Coral's choice)\
      \ for 10 minutes."
    "name": "Gift of Speech (1/Day)"
"source":
  - "MisMV1"
"image": "3-Mechanics/CLI/bestiary/npc/token/coral-mismv1.webp"
```
^statblock