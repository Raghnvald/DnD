---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/llk
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "West Wind"
---
# [West Wind](3-Mechanics/CLI/bestiary/npc/west-wind-llk.md)
*Source: Lost Laboratory of Kwalish p. 14*  

```statblock
"name": "West Wind (LLK)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "60"
"hit_dice": "11d8 + 11"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "17"
  - !!int "13"
  - !!int "11"
  - !!int "16"
  - !!int "10"
"speed": "40 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[dart](3-Mechanics/CLI/items/dart.md)"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
  - "desc": "West Wind is armed with a longsword that is a [blade of the medusa](3-Mechanics/CLI/items/blade-of-the-medusa-llk.md)."
    "name": "Special Equipment"
  - "desc": "While West Wind is wearing no armor and wielding no shield, its AC includes\
      \ its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "West Wind makes three unarmed strikes or three dart attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage. If the target is a creature, West Wind can\
      \ choose one of the following additional effects:\n\n- The target must succeed\
      \ on a DC 13 Strength saving throw or drop one item it is holding (adept's choice).\
      \  \n- The target must succeed on a DC 13 Dexterity saving throw or be knocked\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone).  \n- The target must succeed\
      \ on a DC 13 Constitution saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the end of West Wind's next turn.  "
    "name": "Unarmed Strike"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 20/60 ft., one target. *Hit:*\
      \ 5 (1d4 + 3) piercing damage."
    "name": "Dart"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft., one creature.\
      \ *Hit:* 7 (1d8 + 3) piercing damage. If West Wind rolls a 20 on the attack\
      \ roll, the target must succeed on a DC 15 Constitution saving throw or suffer\
      \ the effects of a [flesh to stone](3-Mechanics/CLI/spells/flesh-to-stone.md)\
      \ spell."
    "name": "Blade of the Medusa"
"reactions":
  - "desc": "In response to being hit by a ranged weapon attack, West Wind deflects\
      \ the missile. The damage it takes from the attack is reduced by 1d10 + 3.\
      \ If the damage is reduced to 0, West Wind catches the missile if it's small\
      \ enough to hold in one hand and West Wind has a hand free."
    "name": "Deflect Missile"
"source":
  - "LLK"
"image": "3-Mechanics/CLI/bestiary/npc/token/west-wind-llk.webp"
```
^statblock