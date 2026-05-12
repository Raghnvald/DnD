---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Amun Sa"
---
# [Amun Sa](3-Mechanics/CLI/bestiary/npc/amun-sa-qftis.md)
*Source: Quests from the Infinite Staircase p. 106*  

```statblock
"name": "Amun Sa (QftIS)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "17"
"speed": "0 ft., fly 40 ft. (hover)"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any languages it knew in life"
"cr": "4"
"traits":
  - "desc": "Amun can see 60 feet into the Ethereal Plane when it is on the Material\
      \ Plane, and vice versa."
    "name": "Ethereal Sight"
  - "desc": "Amun can move through other creatures and objects as if they were difficult\
      \ terrain. It takes 5 (1d10) force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 17\
      \ (4d6 + 3) necrotic damage."
    "name": "Withering Touch"
  - "desc": "Amun enters the Ethereal Plane from the Material Plane, or vice versa.\
      \ It is visible on the Material Plane while it is in the Border Ethereal, and\
      \ vice versa, yet it can't affect or be affected by anything on the other plane."
    "name": "Etherealness"
  - "desc": "Each non-undead creature within 60 feet of Amun that can see it must\
      \ succeed on a DC 13 Wisdom saving throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. If the save fails by 5 or more, the target also ages 1d4 ×\
      \ 10 years. A [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) condition\
      \ on itself on a success. If a target's saving throw is successful or the effect\
      \ ends for it, the target is immune to this ghost's Horrifying Visage for the\
      \ next 24 hours. The aging effect can be reversed with a  [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell, but only within 24 hours of it occurring."
    "name": "Horrifying Visage"
  - "desc": "One humanoid that Amun can see within 5 feet of it must succeed on a\
      \ DC 13 Charisma saving throw or be possessed by Amun; Amun then disappears,\
      \ and the target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and loses control of its body. Amun now controls the body but doesn't deprive\
      \ the target of awareness. Amun can't be targeted by any attack, spell, or other\
      \ effect, except ones that turn undead, and it retains its alignment, Intelligence,\
      \ Wisdom, Charisma, and immunity to being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise\
      \ uses the possessed target's statistics, but doesn't gain access to the target's\
      \ knowledge, class features, or proficiencies.\n\nThe possession lasts until\
      \ the body drops to 0 hit points, Amun ends it as a bonus action, or Amun is\
      \ turned or forced out by an effect like the [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md)\
      \ spell. When the possession ends, Amun reappears in an unoccupied space within\
      \ 5 feet of the body. The target is immune to this ghost's Possession for 24\
      \ hours after succeeding on the saving throw or after the possession ends."
    "name": "Possession (Recharge 6)"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/amun-sa-qftis.webp"
```
^statblock