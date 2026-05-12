---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mind's Eye Matter Smith"
---
# [Mind's Eye Matter Smith](3-Mechanics/CLI/bestiary/humanoid/minds-eye-matter-smith-mpp.md)
*Source: Morte's Planar Parade p. 60*  

Members of the Mind's Eye believe the power to transcend the multiverse lies in every individual. Matter smiths harness this innate power to reshape reality in Sigil's Great Foundry, manifesting useful tools from nothing.

```statblock
"name": "Mind's Eye Matter Smith (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common plus two more languages"
"cr": "4"
"actions":
  - "desc": "The matter smith makes two Manifested Force attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 10 (2d6 + 3) force damage."
    "name": "Manifested Force"
  - "desc": "The matter smith casts one of the following spells, using Charisma as\
      \ the spellcasting ability:\n\n**At will:** [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1/day each:** [create food and water](3-Mechanics/CLI/spells/create-food-and-water.md),\
      \ [fabricate](3-Mechanics/CLI/spells/fabricate.md) (as an action)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The matter smith magically manipulates the energy of the plane of existence\
      \ it's on to produce one of the following effects (choose one or roll a d4):\n\
      \n- **1-2 Chains.** The matter smith creates spectral bindings around a creature\
      \ it can see within 30 feet of itself. The target must succeed on a DC 13 Dexterity\
      \ saving throw or have the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition until the end of its next turn.  \n- **3-4 Magic Shield.** The matter\
      \ smith conjures a floating, spectral shield that grants the matter smith a\
      \ +5 bonus to its AC until the shield disappears at the start of the matter\
      \ smith's next turn. The first time a creature misses a melee attack roll against\
      \ the matter smith while the shield is conjured, that creature takes 7 (2d6)\
      \ force damage.  "
    "name": "Planar Smithing"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/minds-eye-matter-smith-mpp.webp"
```
^statblock