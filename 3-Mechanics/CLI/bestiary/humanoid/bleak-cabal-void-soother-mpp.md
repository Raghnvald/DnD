---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bleak Cabal Void Soother"
---
# [Bleak Cabal Void Soother](3-Mechanics/CLI/bestiary/humanoid/bleak-cabal-void-soother-mpp.md)
*Source: Morte's Planar Parade p. 54*  

A void soother cares for creatures struck by curses and the negative effects of the planes. These warriors go to dangerous planes and areas torn by conflict to provide relief to those they find there.

```statblock
"name": "Bleak Cabal Void Soother (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "constitution": !!int "3"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "passive Perception 12"
"languages": "Common plus one more language"
"cr": "3"
"actions":
  - "desc": "The void soother makes two Mace or Void Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage plus 3 (1d6) force damage."
    "name": "Mace"
  - "desc": "*Ranged Spell Attack:* +4 to hit, range 90 ft., one target. *Hit:*\
      \ 9 (2d8) force damage."
    "name": "Void Bolt"
  - "desc": "The void soother casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 12):\n\n**At will:** [guidance](3-Mechanics/CLI/spells/guidance.md),\
      \ [light](3-Mechanics/CLI/spells/light.md)\n\n**1/day each:** [calm emotions](3-Mechanics/CLI/spells/calm-emotions.md),\
      \ [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md), [remove\
      \ curse](3-Mechanics/CLI/spells/remove-curse.md), [protection from energy](3-Mechanics/CLI/spells/protection-from-energy.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The void soother speaks a magical word of mercy, healing one creature\
      \ it can see within 60 feet of itself. The target regains 4 (1d4 + 2) hit\
      \ points."
    "name": "Soothing Word (3/Day)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/bleak-cabal-void-soother-mpp.webp"
```
^statblock