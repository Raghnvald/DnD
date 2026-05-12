---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lrdt
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dragonborn
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Alax Jadescales"
---
# [Alax Jadescales](3-Mechanics/CLI/bestiary/npc/alax-jadescales-lrdt.md)
*Source: Red Dragon's Tale: A LEGO Adventure p. 11*  

```statblock
"name": "Alax Jadescales (LRDT)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Neutral Good"
"ac": !!int "10"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "0"
"stats":
  - !!int "11"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"damage_resistances": "poison"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common, Draconic"
"cr": "2"
"actions":
  - "desc": "Alax makes two Fire Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 10 (2d6 + 3) fire damage."
    "name": "Fire Strike"
  - "desc": "Alax exhales a 15-foot cone of fire. Each creature in that area must\
      \ make a DC 12 Dexterity saving throw, taking 14 (4d6) fire damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Breath Weapon (Recharges after a Short or Long Rest)"
  - "desc": "Alax casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [Druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [Resistance](3-Mechanics/CLI/spells/resistance.md)\n\n**1/day each:** [Cure\
      \ Wounds](3-Mechanics/CLI/spells/cure-wounds.md), [Faerie Fire](3-Mechanics/CLI/spells/faerie-fire.md),\
      \ [Purify Food and Drink](3-Mechanics/CLI/spells/purify-food-and-drink.md)"
    "name": "Spellcasting"
"source":
  - "LRDT"
"image": "3-Mechanics/CLI/bestiary/npc/token/alax-jadescales-lrdt.webp"
```
^statblock