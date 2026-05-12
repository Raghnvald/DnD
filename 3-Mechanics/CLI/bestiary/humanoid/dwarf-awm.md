---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dwarf"
---
# [Dwarf](3-Mechanics/CLI/bestiary/humanoid/dwarf-awm.md)
*Source: Adventure with Muk p. 32*  

Although there are no dwarves that live in the actual Dankwood, they will sometime pass through in travel or explore the forest for coveted materials and magical stones. They pride themselves in their skills and can create beautiful artifacts from the objects they find in nature.

The dwarves in the area are naturally cautious towards goblins. They will go out of their way to avoid contact and rarely stay for long periods in the Dankwood.

```statblock
"name": "Dwarf (AWM)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Good"
"ac": !!int "10"
"hp": !!int "30"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "25 ft."
"damage_resistances": "poison"
"gear":
  - "shortbow"
"senses": "passive Perception 0"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "They have advantage on saving throws against poison, and they have resistance\
      \ to poison damage."
    "name": "Dwarven Resilience"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, one target. *Hit:* 4 (1d6 + 1)\
      \ slashing damage."
    "name": "Shortbow"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dwarf-awm.webp"
```
^statblock