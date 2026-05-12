---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Korex"
---
# [Korex](3-Mechanics/CLI/bestiary/npc/korex-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

```statblock
"name": "Korex (WttHC)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d8"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "14"
  - !!int "8"
  - !!int "12"
  - !!int "15"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[pipes of pestilence](3-Mechanics/CLI/items/pipes-of-pestilence-wtthc.md)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "Korex can comprehend and verbally communicate with Monstrosities."
    "name": "Sewer Speech"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing\
      \ damage plus 7 (2d6) Poison damage, and the target has the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition until the start of Korex's next turn."
    "name": "Rancid Knife"
  - "desc": "*Wisdom Saving Throw:* DC 12, one creature Korex can see within 120 feet.\
      \ *Failure:* 14 (4d6) Psychic damage, and the target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition until the start of Korex's next turn. *Success:* Half damage only."
    "name": "Entrancing Pipes"
"bonus_actions":
  - "desc": "Korex takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash) or [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ action."
    "name": "Skitter"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/npc/token/korex-wtthc.webp"
```
^statblock