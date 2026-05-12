---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grum'shar"
---
# [Grum'shar](3-Mechanics/CLI/bestiary/npc/grumshar-wdh.md)
*Source: Waterdeep: Dragon Heist p. 29*  

Apprentice wizards are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work, such as cooking and cleaning, in exchange for education in the ways of magic.

```statblock
"name": "Grum'shar (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+4"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Orc"
"cr": "1/4"
"traits":
  - "desc": "Grum'shar is a 1st-level spellcaster. His spellcasting ability is Intelligence.\
      \ He has the following wizard spells prepared:\n\n**Cantrips (at will):** [fire\
      \ bolt](3-Mechanics/CLI/spells/fire-bolt-xphb.md), [mending](3-Mechanics/CLI/spells/mending-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1st\
      \ level (2 slots):** [burning hands](3-Mechanics/CLI/spells/burning-hands-xphb.md),\
      \ [disguise self](3-Mechanics/CLI/spells/disguise-self-xphb.md), [shield](3-Mechanics/CLI/spells/shield-xphb.md)"
    "name": "Spellcasting"
  - "desc": "When reduced to 0 hit points, Grum'shar drops to 1 hit point instead.\
      \ He can only do this once per long rest."
    "name": "Relentless Endurance"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d4) piercing damage. Or Ranged Weapon Attack: +2 to hit, range 20/60\
      \ ft., one target. *Hit:* 2 (1d4) piercing damage."
    "name": "Dagger"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/grumshar-wdh.webp"
```
^statblock