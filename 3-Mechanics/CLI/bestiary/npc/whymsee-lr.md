---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Whymsee"
---
# [Whymsee](3-Mechanics/CLI/bestiary/npc/whymsee-lr.md)
*Source: Locathah Rising p. 20*  

```statblock
"name": "Whymsee (LR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "passive Perception 15"
"languages": "Common, Aquan"
"cr": "5"
"traits":
  - "desc": "Whymsee's spellcasting ability is Wisdom (spell save DC 13, +5 to hit\
      \ with spell attacks). It can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** [command](3-Mechanics/CLI/spells/command.md),\
      \ [create or destroy water](3-Mechanics/CLI/spells/create-or-destroy-water.md)\n\
      \n**3/day each:** [control water](3-Mechanics/CLI/spells/control-water.md),\
      \ [darkness](3-Mechanics/CLI/spells/darkness.md), [water breathing](3-Mechanics/CLI/spells/water-breathing.md),\
      \ [water walk](3-Mechanics/CLI/spells/water-walk.md)\n\n**1/day each:** [lightning\
      \ bolt](3-Mechanics/CLI/spells/lightning-bolt.md), [Evard's black tentacles](3-Mechanics/CLI/spells/evards-black-tentacles.md)"
    "name": "Innate Spellcasting"
  - "desc": "Whymsee can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "*Melee Spell Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 27 (5d10) thunder damage."
    "name": "Thunderous Touch"
  - "desc": "While underwater, Whymsee can expel an ink cloud in a 20-foot radius.\
      \ The cloud spreads around corners, and that area is heavily obscured to creatures\
      \ other than kraken priests or a kraken. Each creature other than a kraken priest\
      \ or a kraken that ends its turn there must succeed on a DC 14 Constitution\
      \ saving throw, taking 9 (2d8) poison damage on a failed save, or half as\
      \ much damage on a successful one. A strong current disperses the cloud, which\
      \ otherwise disappears at the end of Whymsee's next turn."
    "name": "Ink Cloud"
  - "desc": "Whymsee withdraws into her shell. Until she emerges, she gains a +4 bonus\
      \ to AC and has advantage on Strength and Constitution saving throws. While\
      \ in her shell, Whymsee is [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
      \ her speed is 0 and can't increase, she has disadvantage on Dexterity saving\
      \ throws, it can't take reactions, and the only action she can take is a bonus\
      \ action to emerge."
    "name": "Shell Defense"
"source":
  - "LR"
"image": "3-Mechanics/CLI/bestiary/npc/token/whymsee-lr.webp"
```
^statblock