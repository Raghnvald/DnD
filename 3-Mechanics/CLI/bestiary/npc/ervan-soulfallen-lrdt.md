---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lrdt
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ervan Soulfallen"
---
# [Ervan Soulfallen](3-Mechanics/CLI/bestiary/npc/ervan-soulfallen-lrdt.md)
*Source: Red Dragon's Tale: A LEGO Adventure p. 11*  

```statblock
"name": "Ervan Soulfallen (LRDT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "14"
  - !!int "11"
  - !!int "8"
  - !!int "17"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
"senses": "passive Perception 9"
"languages": "Common, Draconic"
"cr": "5"
"actions":
  - "desc": "Ervan uses his staff to make three Arcane Blast attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 13 (3d6 + 3) force damage."
    "name": "Arcane Blast"
  - "desc": "Acid falls in a 10-foot-radius, 20-foot-high cylinder centered on a point\
      \ Ervan can see within 120 feet of himself. Each creature in that area must\
      \ make a DC 14 Dexterity saving throw, taking 22 (4d10) acid damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Acid Rain (Recharges after a Short or Long Rest)"
  - "desc": "Ervan casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 14):\n\n**At will:** [Light](3-Mechanics/CLI/spells/light.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md)\n\n**2/day:** [Dimension\
      \ Door](3-Mechanics/CLI/spells/dimension-door.md)\n\n**1/day each:** [Disguise\
      \ Self](3-Mechanics/CLI/spells/disguise-self.md), [Levitate](3-Mechanics/CLI/spells/levitate.md),\
      \ [Mage Armor](3-Mechanics/CLI/spells/mage-armor.md)"
    "name": "Spellcasting"
"source":
  - "LRDT"
"image": "3-Mechanics/CLI/bestiary/npc/token/ervan-soulfallen-lrdt.webp"
```
^statblock