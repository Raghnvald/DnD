---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wight Lifedrinker"
---
# [Wight Lifedrinker](3-Mechanics/CLI/bestiary/undead/wight-lifedrinker-hotb.md)
*Source: Heroes of the Borderlands p. 19*  

Wights are the withered corpses of relentless warriors whose wickedness sustains them beyond death. After dying and returning from the grave, a wight continues its villainous ways, but it is now driven by a hunger for life. A wight drains living essence through its attacks.

```statblock
"name": "Wight Lifedrinker (HotB)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "studded leather armor"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common plus one other language"
"cr": "3"
"traits":
  - "desc": "While in sunlight, the wight has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on ability checks and attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The wight makes two attacks, using Necrotic Sword or Necrotic Bow in\
      \ any combination. It can replace one attack with a use of Drink Life."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing\
      \ damage plus 4 (1d8) Necrotic damage."
    "name": "Necrotic Sword"
  - "desc": "*Ranged Attack Roll:* +4, range 150/600 ft. *Hit:* 6 (1d8 + 2) Piercing\
      \ damage plus 4 (1d8) Necrotic damage."
    "name": "Necrotic Bow"
  - "desc": "*Constitution Saving Throw:* DC 13, one creature within 5 feet. *Failure:*\
      \ 6 (1d8 + 2) Necrotic damage, and the wight regains a number of <span title=\"\
      Player's Handbook (2024)\">Hit Points</span> equal to the Necrotic damage taken."
    "name": "Drink Life (Recharge 5-6)"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/undead/token/wight-lifedrinker-hotb.webp"
```
^statblock