---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotdq
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dragonclaw"
---
# [Dragonclaw](3-Mechanics/CLI/bestiary/humanoid/dragonclaw-hotdq.md)
*Source: Hoard of the Dragon Queen p. 89, The Rise of Tiamat p. 89, Tyranny of Dragons p. 182*  

```statblock
"name": "Dragonclaw (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "16"
  - !!int "13"
  - !!int "11"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[scimitar](3-Mechanics/CLI/items/scimitar-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "The dragonclaw has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). While the\
      \ dragonclaw can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
      \ to it, the dragonclaw ignores the effects of being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dragon Fanatic"
  - "desc": "Once per turn, if the dragonclaw makes a weapon attack with advantage\
      \ on the attack roll and hits, it deals an extra 7 (2d6) damage."
    "name": "Fanatic Advantage"
  - "desc": "The dragonclaw has advantage on an attack roll against a creature if\
      \ at least one of the dragonclaw's allies is within 5 feet of the creature and\
      \ the ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The dragonclaw attacks twice with its scimitar."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Scimitar"
"source":
  - "HotDQ"
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dragonclaw-hotdq.webp"
```
^statblock