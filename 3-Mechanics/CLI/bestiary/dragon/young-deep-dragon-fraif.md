---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Young Deep Dragon"
---
# [Young Deep Dragon](3-Mechanics/CLI/bestiary/dragon/young-deep-dragon-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 257*  

Young deep dragons establish lairs in familiar hunting grounds and defend their lairs with twisting passages and traps such as deadfalls. They dominate the local environment, consuming vast quantities of fish and pale crabs and cultivating fungal growths. They bully nearby communities when they can or enter into cautious arrangements with powerful Underdark settlements, such as drow cities.

## Deep Dragons

*Dragons of Caverns and Secrets*

Deep dragons slither through the wet and lightless places of the Underdark. They are stealthy hunters with an affinity for lost lore and fungi that flourish in the depths. As deep dragons age, their smooth, serpentine bodies become riddled with fungal rot, particularly around their faces, to imbue their breath with terror-inducing spores.

Deep dragons covet treasure and knowledge. Some deep dragons seek to gain knowledge via experience and travel, slithering through caverns and seas of the Underdark to map hidden passages for dozens of miles. Other deep dragons enjoy cultivating groves of molds and fungi, including colossal varieties sufficient to conceal the dragons' sinuous forms. Many deep dragons collect forgotten tomes or works of art and bully, cajole, or steal collections from drow or duergar sages.

Deep dragons are excellent swimmers. They often clash with aquatic Underdark societies, such as kuo-toa. Many deep dragons demand tribute from these groups in the form of food or treasure.

Underdark explorers have many reasons to brave deep dragon lairs beyond treasure hunting; they might contain the only surviving copies of forgotten lore, fungal ingredients for cures or plagues, or maps to lost Underdark locales.

## Deep Dragon Lairs

Deep dragons lair in fungus-encrusted caverns of the Underdark or old, forgotten ruins, preferring locations near subterranean bodies of water.

```statblock
"name": "Young Deep Dragon (FRAiF)"
"size": "Large"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "40 ft., burrow 20 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "4"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Perception"
    "desc": "+8"
  - "name": "Stealth"
    "desc": "+7"
"damage_resistances": "poison, psychic"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "Blindsight 30 ft., Darkvision 150 ft., passive Perception 18"
"languages": "Common, Draconic, Undercommon"
"cr": "5"
"actions":
  - "desc": "The dragon makes three Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Slashing\
      \ damage plus 3 (1d6) Poison damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 14, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 22 (4d10) Psychic damage,\
      \ and the target has the Frightened condition until the end of the dragon's\
      \ next turn. *Success:* Half damage only."
    "name": "Nightmare Breath (Recharge 5-6)"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/young-deep-dragon-fraif.webp"
```
^statblock

## Environment

underdark