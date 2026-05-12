---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/sdw
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Shark Skeleton"
---
# [Giant Shark Skeleton](3-Mechanics/CLI/bestiary/undead/giant-shark-skeleton-sdw.md)
*Source: Sleeping Dragon's Wake*  

A giant shark is 30 feet long and normally found in deep oceans. Utterly fearless, it preys on anything that crosses its path, including whales and ships.

The giant shark skeleton doesn't require air, food, drink, or sleep. The shark has had skeletal feet attached by some demented necromancer.

```statblock
"name": "Giant Shark Skeleton (SDW)"
"size": "Huge"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "11"
  - !!int "21"
  - !!int "1"
  - !!int "10"
  - !!int "5"
"speed": "20 ft., swim 50 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 13"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The giant shark skeleton has advantage on melee attack rolls against\
      \ any creature that doesn't have all its hit points."
    "name": "Blood Frenzy"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 22\
      \ (3d10 + 6) piercing damage."
    "name": "Bite"
"source":
  - "SDW"
"image": "3-Mechanics/CLI/bestiary/undead/token/giant-shark-skeleton-sdw.webp"
```
^statblock