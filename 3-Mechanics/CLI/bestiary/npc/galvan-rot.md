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
- "Galvan"
---
# [Galvan](3-Mechanics/CLI/bestiary/npc/galvan-rot.md)
*Source: The Rise of Tiamat p. 9, Tyranny of Dragons p. 12*  

```statblock
"name": "Galvan (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md);\
  \ 17 with the Blue Dragon Mask"
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
"damage_immunities": "lightning"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Common, Draconic, Infernal"
"cr": "7"
"traits":
  - "desc": "While Galvan is not presented in an encounter in The Rise of Tiamat,\
      \ the [dragonsoul](3-Mechanics/CLI/bestiary/humanoid/dragonsoul-rot.md) stat\
      \ block has been provided here for ease of use, with optional alterations for\
      \ the [Blue Dragon Mask](3-Mechanics/CLI/items/blue-dragon-mask-rotos.md)."
    "name": "5etools Note"
  - "desc": "Galvan has the [Blue Dragon Mask](3-Mechanics/CLI/items/blue-dragon-mask-rotos.md)."
    "name": "Special Equipment"
  - "desc": "While wearing no armor and wearing the Blue Dragon Mask, Galvan adds\
      \ his Charisma bonus to his AC (included)."
    "name": "Draconic Majesty"
  - "desc": "If Galvan deals lightning damage to a creature while wearing the Blue\
      \ Dragon Mask, that creature can't take reactions until its next turn."
    "name": "Lingering Shock"
  - "desc": "If Galvan fails a saving throw while wearing the Blue Dragon Mask, he\
      \ can choose to succeed instead."
    "name": "Legendary Resistance (1/Day)"
  - "desc": "Galvan has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). While Galvan\
      \ can see a dragon or higher-ranking Cult of the Dragon cultist friendly to\
      \ it, Galvan ignores the effects of being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dragon Fanatic"
  - "desc": "Once per turn, if Galvan makes a weapon attack with advantage on the\
      \ attack roll and hits, the target takes an extra 10 (3d6) damage."
    "name": "Fanatic Advantage"
  - "desc": "Galvan can use a bonus action to gain a flying speed of 30 feet until\
      \ the end of its turn."
    "name": "Limited Flight"
  - "desc": "Galvan has advantage on an attack roll against a creature if at least\
      \ one of Galvan's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "Galvan attacks twice with its shortsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 10 (3d6) damage of the type to which Galvan\
      \ has resistance."
    "name": "Shortsword"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 90 ft., one target. *Hit:*\
      \ 27 (6d8) damage of the type to which Galvan has damage resistance."
    "name": "Orb of Dragon's Breath (3/Day)"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/galvan-rot.webp"
```
^statblock