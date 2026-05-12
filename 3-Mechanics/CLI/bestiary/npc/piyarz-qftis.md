---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Piyarz"
---
# [Piyarz](3-Mechanics/CLI/bestiary/npc/piyarz-qftis.md)
*Source: Quests from the Infinite Staircase p. 67*  

```statblock
"name": "Piyarz (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "10"
"ac_class": "13 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
"damage_resistances": "fire"
"senses": "passive Perception 12"
"languages": "Common plus any three languages"
"cr": "1"
"traits":
  - "desc": "Piyarz wears a Ring of Fire Resistance, granting him resistance to fire\
      \ damage."
    "name": "Special Equipment"
"actions":
  - "desc": "Piyarz makes two Arcane Burst attacks and can use Starry Radiance if\
      \ available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 8 (1d10 + 3) radiant damage."
    "name": "Arcane Burst"
  - "desc": "Dazzling light bursts from Piyarz's fingertips in a 15-foot cone. Each\
      \ creature in that area must succeed on a DC 13 Constitution saving throw or\
      \ have the [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) condition\
      \ until the end of Piyarz's next turn."
    "name": "Starry Radiance (Recharge 5-6)"
  - "desc": "Piyarz casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [Dancing Lights](3-Mechanics/CLI/spells/dancing-lights.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md), [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1/day each:** [Arcane Lock](3-Mechanics/CLI/spells/arcane-lock.md), [Burning\
      \ Hands](3-Mechanics/CLI/spells/burning-hands.md), [Comprehend Languages](3-Mechanics/CLI/spells/comprehend-languages.md),\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic.md), [Levitate](3-Mechanics/CLI/spells/levitate.md),\
      \ [Mage Armor](3-Mechanics/CLI/spells/mage-armor.md)"
    "name": "Spellcasting"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/piyarz-qftis.webp"
```
^statblock