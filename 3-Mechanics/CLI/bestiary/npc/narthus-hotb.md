---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Narthus"
---
# [Narthus](3-Mechanics/CLI/bestiary/npc/narthus-hotb.md)
*Source: Heroes of the Borderlands p. 26*  

A craven lackey, Narthus serves Ivlis out of fear rather than loyalty. Narthus spends his days groveling before Ivlis and cruelly whipping new initiates to the Cult of Chaos into shape. Narthus's feral nature leads some cultists to speculate that he was raised by wild animals.

Ivlis prizes Narthus for his obsequity and morbid fascinations. He grows the cult's ranks through macabre rituals, conscripting the dead to serve the cult's depraved goals.

```statblock
"name": "Narthus (HotB)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "chain shirt"
  - "mace"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "Narthus makes two attacks using Vile Mace or Fateful Bolt in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Bludgeoning\
      \ damage plus 3 (1d6) Necrotic damage."
    "name": "Vile Mace"
  - "desc": "*Ranged Attack Roll:* +4, range 120 ft. *Hit:* 8 (1d12 + 2) Necrotic\
      \ damage, and the next attack roll made against the target before the end of\
      \ Narthus's next turn has <span title=\"Player's Handbook (2024)\">Advantage</span>."
    "name": "Fateful Bolt"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/npc/token/narthus-hotb.webp"
```
^statblock