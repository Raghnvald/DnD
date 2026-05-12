---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotdq
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dragonwing"
---
# [Dragonwing](3-Mechanics/CLI/bestiary/humanoid/dragonwing-hotdq.md)
*Source: Hoard of the Dragon Queen p. 90, The Rise of Tiamat p. 89, Tyranny of Dragons p. 183*  

```statblock
"name": "Dragonwing (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "13"
  - !!int "11"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "one of the following: acid, cold, fire, lightning, poison"
"gear":
  - "[scimitar](3-Mechanics/CLI/items/scimitar-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "2"
"traits":
  - "desc": "The dragonwing has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). While the\
      \ dragonwing can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
      \ to it, the dragonwing ignores the effects of being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dragon Fanatic"
  - "desc": "Once per turn, if the dragonwing makes a weapon attack with advantage\
      \ on the attack roll and hits, the target takes an extra 7 (2d6) damage."
    "name": "Fanatic Advantage"
  - "desc": "The dragonwing can use a bonus action to gain a flying speed of 30 feet\
      \ until the end of its turn."
    "name": "Limited Flight"
  - "desc": "The dragonwing has advantage on an attack roll against a creature if\
      \ at least one of the dragonwing's allies is within 5 feet of the creature and\
      \ the ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The dragonwing attacks twice with its scimitar."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage plus 3 (1d6) damage of the type to which the\
      \ cultist has resistance."
    "name": "Scimitar"
"source":
  - "HotDQ"
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dragonwing-hotdq.webp"
```
^statblock