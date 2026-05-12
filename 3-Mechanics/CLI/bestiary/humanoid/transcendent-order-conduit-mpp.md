---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Transcendent Order Conduit"
---
# [Transcendent Order Conduit](3-Mechanics/CLI/bestiary/humanoid/transcendent-order-conduit-mpp.md)
*Source: Morte's Planar Parade p. 62*  

Members of the Transcendent Order train to act without thinking, eliminating thought behind action. Conduits react with the cadence of the multiverse. Their sharp reflexes border on precognition, allowing them to unconsciously act before their foes.

```statblock
"name": "Transcendent Order Conduit (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "Unarmored Defense"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "19"
  - !!int "14"
  - !!int "10"
  - !!int "18"
  - !!int "12"
"speed": "50 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+4"
"senses": "passive Perception 17"
"languages": "Common plus one more language"
"cr": "8"
"traits":
  - "desc": "The conduit has advantage on initiative rolls, and it can't have disadvantage\
      \ on attack rolls."
    "name": "Instinctive Reflexes"
  - "desc": "While the conduit is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The conduit makes three Unarmed Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage. If the target is a creature, the conduit can\
      \ choose one of the following additional effects (up to once per turn each):\n\
      \n- **Incapacitate.** The target must succeed on a DC 15 Constitution saving\
      \ throw or have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition until the end of the conduit's next turn.  \n- **Push.** The target\
      \ is pushed up to 10 feet horizontally away from the conduit.  "
    "name": "Unarmed Strike"
"reactions":
  - "desc": "In response to being hit by an attack roll, the conduit partially deflects\
      \ the blow. The damage the conduit takes from the attack is reduced by 1d10."
    "name": "Deflect Attack"
  - "desc": "When the conduit must make a saving throw, it can move up to half its\
      \ speed without provoking opportunity attacks. If its new position moves it\
      \ out of range or otherwise makes it impossible to be targeted by the effect,\
      \ the conduit avoids the effect entirely."
    "name": "Don't Be There"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/transcendent-order-conduit-mpp.webp"
```
^statblock