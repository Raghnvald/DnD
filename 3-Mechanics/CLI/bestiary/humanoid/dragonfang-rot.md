---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rot
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dragonfang"
---
# [Dragonfang](3-Mechanics/CLI/bestiary/humanoid/dragonfang-rot.md)
*Source: The Rise of Tiamat p. 89, Tyranny of Dragons p. 182*  

```statblock
"name": "Dragonfang (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "one of the following: acid, cold, fire, lightning, poison"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Infernal"
"cr": "5"
"traits":
  - "desc": "The dragonfang has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). While the\
      \ dragonfang can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
      \ to it, the dragonfang ignores the effects of being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dragon Fanatic"
  - "desc": "Once per turn, if the dragonfang makes a weapon attack with advantage\
      \ on the attack roll and hits, the target takes an extra 10 (3d6) damage."
    "name": "Fanatic Advantage"
  - "desc": "The dragonfang can use a bonus action to gain a flying speed of 30 feet\
      \ until the end of its turn."
    "name": "Limited Flight"
  - "desc": "The dragonfang has advantage on an attack roll against a creature if\
      \ at least one of the dragonfang's allies is within 5 feet of the creature and\
      \ the ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The Dragonfang attacks twice with its shortsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 7 (2d6) damage of the type to which the\
      \ dragonfang has resistance."
    "name": "Shortsword"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 50 ft., one target. *Hit:*\
      \ 22 (5d8) damage of the type to which the dragonfang has damage resistance."
    "name": "Orb of Dragon's Breath (2/Day)"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dragonfang-rot.webp"
```
^statblock