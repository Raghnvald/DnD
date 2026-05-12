---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jerot Galgin"
---
# [Jerot Galgin](3-Mechanics/CLI/bestiary/npc/jerot-galgin-veor.md)
*Source: Vecna: Eve of Ruin p. 28*  

```statblock
"name": "Jerot Galgin (VEoR)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "Jerot makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 25 (4d10 + 3) necrotic damage."
    "name": "Arcane Burst"
  - "desc": "Jerot casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\
      \n**2/day each:** [bestow curse](3-Mechanics/CLI/spells/bestow-curse-xphb.md),\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md),\
      \ [web](3-Mechanics/CLI/spells/web-xphb.md)\n\n**1/day each:** [circle of death](3-Mechanics/CLI/spells/circle-of-death-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Jerot magically summons five [skeletons](3-Mechanics/CLI/bestiary/undead/skeleton-xmm.md)\
      \ or [zombies](3-Mechanics/CLI/bestiary/undead/zombie-xmm.md). The summoned\
      \ creatures appear in unoccupied spaces within 60 feet of Jerot, whom they obey.\
      \ They take their turns immediately after Jerot. Each lasts for 1 hour, until\
      \ it or Jerot dies, or until Jerot dismisses it as a bonus action."
    "name": "Summon Undead (1/Day)"
"reactions":
  - "desc": "When Jerot kills a creature with necrotic damage, Jerot regains 9 (2d8)\
      \ hit points. "
    "name": "Grim Harvest (1/Turn)"
"source":
  - "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/jerot-galgin-veor.webp"
```
^statblock