---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Yorn"
---
# [Yorn](3-Mechanics/CLI/bestiary/npc/yorn-wdh.md)
*Source: Waterdeep: Dragon Heist p. 150*  

A burly half-orc Zhentarim in the employ of Manshoon

```statblock
"name": "Yorn (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc"
"alignment": "Lawful Evil"
"ac": !!int "11"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+2"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow-xphb.md)"
  - "[mace](3-Mechanics/CLI/items/mace-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
  - "desc": "The thug has advantage on an attack roll against a creature if at least\
      \ one of the thug's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "When reduced to 0 hit points Yorn drops to 1 hit point instead."
    "name": "Relentless Endurance (1/Day)"
"actions":
  - "desc": "The thug makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d6 + 2) bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:*\
      \ 5 (1d10) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/yorn-wdh.webp"
```
^statblock