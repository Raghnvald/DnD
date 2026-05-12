---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rot
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dragonsoul"
---
# [Dragonsoul](3-Mechanics/CLI/bestiary/humanoid/dragonsoul-rot.md)
*Source: The Rise of Tiamat p. 89, Tyranny of Dragons p. 183*  

```statblock
"name": "Dragonsoul (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "4"
"stats":
  - !!int "11"
  - !!int "18"
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "one of the following: acid, cold, fire, lightning, poison"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Infernal"
"cr": "7"
"traits":
  - "desc": "The dragonsoul has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). While the\
      \ dragonsoul can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
      \ to it, the dragonsoul ignores the effects of being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dragon Fanatic"
  - "desc": "Once per turn, if the dragonsoul makes a weapon attack with advantage\
      \ on the attack roll and hits, the target takes an extra 10 (3d6) damage."
    "name": "Fanatic Advantage"
  - "desc": "The dragonsoul can use a bonus action to gain a flying speed of 30 feet\
      \ until the end of its turn."
    "name": "Limited Flight"
  - "desc": "The dragonsoul has advantage on an attack roll against a creature if\
      \ at least one of the dragonsoul's allies is within 5 feet of the creature and\
      \ the ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The Dragonsoul attacks twice with its shortsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 10 (3d6) damage of the type to which the\
      \ dragonsoul has resistance."
    "name": "Shortsword"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 90 ft., one target. *Hit:*\
      \ 27 (6d8) damage of the type to which the dragonsoul has damage resistance."
    "name": "Orb of Dragon's Breath (3/Day)"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dragonsoul-rot.webp"
```
^statblock