---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Queen Forfallen"
---
# [Queen Forfallen](3-Mechanics/CLI/bestiary/construct/queen-forfallen-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 271*  

## Queen Forfallen

*Rust-Riddled Pirate Queen*

One of the most influential victims of the supernatural rusting curse throughout the Moonshae Isles is the pirate queen known as Queen Forfallen. She plies the seas in the largest and best-defended ship in the Moonshaes, the prize of her armada, which she's strengthened with rusty metal plates and filled with a crew of bloodthirsty Rusted berserkers (see this chapter).

Queen Forfallen is a strong human woman with long, red hair. Although the rusting curse has transformed most of her extremities into metal, she's thus far resisted the weakening corrosion that the curse typically imparts to its victims. Her crew insists that her unquenchable thirst for plunder keep her hale.

```statblock
"name": "Queen Forfallen (FRAiF)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "6"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "19"
  - !!int "15"
  - !!int "17"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Athletics"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, petrified, poisoned"
"gear":
  - "breastplate"
  - "greataxe"
  - "six handaxes"
"senses": "passive Perception 17"
"languages": "Common"
"cr": "10"
"traits":
  - "desc": "Creatures of Forfallen's choice (excluding herself) in a 30-foot <span\
      \ title=\"Player's Handbook (2024)\">Emanation</span> originating from her have\
      \ <span title=\"Player's Handbook (2024)\">Advantage</span> on attack rolls.\
      \ She can't use this trait if she has the Incapacitated condition."
    "name": "Inspiring Presence"
  - "desc": "Forfallen has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Forfallen makes three attacks, using Greataxe or Handaxe in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 18 (2d12 + 5) Slashing\
      \ damage, and the target has the Poisoned condition until the end of its next\
      \ turn."
    "name": "Greataxe"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 20/60 ft.\
      \ *Hit:* 22 (5d6 + 5) Slashing damage."
    "name": "Handaxe"
"bonus_actions":
  - "desc": "*Constitution Saving Throw:* DC 16, one creature Forfallen can see within\
      \ 20 feet. The target has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on this save if it has the Poisoned condition. *1St Failure:* The target has\
      \ the Restrained condition and repeats the save at the end of its next turn\
      \ if it's still Restrained, ending the effect on itself on a success. *2Nd Failure:*\
      \ The target has the Petrified condition instead of the Restrained condition,\
      \ becoming a statue of rusted iron."
    "name": "Rust's Grip"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/construct/token/queen-forfallen-fraif.webp"
```
^statblock