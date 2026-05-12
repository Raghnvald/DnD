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
- "Tower Sage"
---
# [Tower Sage](3-Mechanics/CLI/bestiary/humanoid/tower-sage-qftis.md)
*Source: Quests from the Infinite Staircase p. 217*  

Tower sages are mages who study astrology and support the leader of the Tower of the Heavens, the elder sage, in divining the future. When tower sages are initiated, their arms are tattooed with magical ink that designates their status in the hierarchy. Pupil sages have simple designs patterned after individual stars and minor constellations, while the elder sage's arms depict a plethora of constellations, moons, and suns. When the elder sage dies, the arm tattoos of the elder's chosen successor magically shift into the patterns of an elder sage.

Tower sages are the only folk capable of reading the Books of Prophecy, an ancient set of tomes that hint at future events of grand significance.

## Tower Stewards

For centuries, the Tower of the Heavens has been stewarded by dutiful folk who practice two distinct traditions.

```statblock
"name": "Tower Sage (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
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
"senses": "passive Perception 12"
"languages": "Common plus any three languages"
"cr": "1"
"actions":
  - "desc": "The tower sage makes two Arcane Burst attacks and can use Starry Radiance\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 8 (1d10 + 3) radiant damage."
    "name": "Arcane Burst"
  - "desc": "Dazzling light bursts from the tower sage's fingertips in a 15-foot cone.\
      \ Each creature in that area must succeed on a DC 13 Constitution saving throw\
      \ or have the [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) condition\
      \ until the end of the tower sage's next turn."
    "name": "Starry Radiance (Recharge 5-6)"
  - "desc": "The tower sage casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 13):\n\n**At will:** [Dancing Lights](3-Mechanics/CLI/spells/dancing-lights.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md), [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1/day each:** [Arcane Lock](3-Mechanics/CLI/spells/arcane-lock.md), [Burning\
      \ Hands](3-Mechanics/CLI/spells/burning-hands.md), [Comprehend Languages](3-Mechanics/CLI/spells/comprehend-languages.md),\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic.md), [Levitate](3-Mechanics/CLI/spells/levitate.md),\
      \ [Mage Armor](3-Mechanics/CLI/spells/mage-armor.md)"
    "name": "Spellcasting"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/tower-sage-qftis.webp"
```
^statblock