---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Deep Dragon Wyrmling"
---
# [Deep Dragon Wyrmling](3-Mechanics/CLI/bestiary/dragon/deep-dragon-wyrmling-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 257*  

Deep dragon wyrmlings are lithe with a narrow frame and flexible wings. They slip through crevasses in the Underdark, from which they hunt to satisfy their voracious appetites.

## Deep Dragons

*Dragons of Caverns and Secrets*

Deep dragons slither through the wet and lightless places of the Underdark. They are stealthy hunters with an affinity for lost lore and fungi that flourish in the depths. As deep dragons age, their smooth, serpentine bodies become riddled with fungal rot, particularly around their faces, to imbue their breath with terror-inducing spores.

Deep dragons covet treasure and knowledge. Some deep dragons seek to gain knowledge via experience and travel, slithering through caverns and seas of the Underdark to map hidden passages for dozens of miles. Other deep dragons enjoy cultivating groves of molds and fungi, including colossal varieties sufficient to conceal the dragons' sinuous forms. Many deep dragons collect forgotten tomes or works of art and bully, cajole, or steal collections from drow or duergar sages.

Deep dragons are excellent swimmers. They often clash with aquatic Underdark societies, such as kuo-toa. Many deep dragons demand tribute from these groups in the form of food or treasure.

Underdark explorers have many reasons to brave deep dragon lairs beyond treasure hunting; they might contain the only surviving copies of forgotten lore, fungal ingredients for cures or plagues, or maps to lost Underdark locales.

## Deep Dragon Lairs

Deep dragons lair in fungus-encrusted caverns of the Underdark or old, forgotten ruins, preferring locations near subterranean bodies of water.

```statblock
"name": "Deep Dragon Wyrmling (FRAiF)"
"size": "Medium"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "11"
  - !!int "12"
  - !!int "13"
"speed": "30 ft., burrow 15 ft., fly 60 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "2"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+4"
"damage_resistances": "poison, psychic"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "Blindsight 10 ft., Darkvision 60 ft., passive Perception 15"
"languages": "Draconic"
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing\
      \ damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 11, each creature in a 15-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 7 (2d6) Psychic damage,\
      \ and the target has the Frightened condition until the end of the dragon's\
      \ next turn. *Success:* Half damage only."
    "name": "Nightmare Breath (Recharge 5-6)"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/deep-dragon-wyrmling-fraif.webp"
```
^statblock

## Environment

underdark