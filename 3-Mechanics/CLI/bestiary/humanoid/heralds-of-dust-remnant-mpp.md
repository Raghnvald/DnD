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
- "Heralds of Dust Remnant"
---
# [Heralds of Dust Remnant](3-Mechanics/CLI/bestiary/humanoid/heralds-of-dust-remnant-mpp.md)
*Source: Morte's Planar Parade p. 59*  

Remnants are Dusters who sought undeath via rituals but failed. Liaisons and spies, these agents exist in a halfway point between life and death.

```statblock
"name": "Heralds of Dust Remnant (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "15"
  - !!int "17"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic"
"senses": "passive Perception 14"
"languages": "Common plus three more languages"
"cr": "4"
"actions":
  - "desc": "The remnant makes two Necrotic Surge attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 14 (2d10 + 3) necrotic damage."
    "name": "Necrotic Surge"
  - "desc": "The remnant casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 13):\n\n**At will:** [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1/day each:** [bane](3-Mechanics/CLI/spells/bane.md), [dimension door](3-Mechanics/CLI/spells/dimension-door.md),\
      \ [web](3-Mechanics/CLI/spells/web.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The remnant becomes partially incorporeal for as long as it maintains\
      \ [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration) on the\
      \ effect (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). While partially incorporeal, the remnant has resistance to bludgeoning,\
      \ piercing, and slashing damage."
    "name": "Phase (2/Day)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/heralds-of-dust-remnant-mpp.webp"
```
^statblock