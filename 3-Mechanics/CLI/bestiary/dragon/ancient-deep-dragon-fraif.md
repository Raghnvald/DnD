---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ancient Deep Dragon"
---
# [Ancient Deep Dragon](3-Mechanics/CLI/bestiary/dragon/ancient-deep-dragon-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 259*  

Ancient deep dragons often spend years sequestered among individualized libraries, fungal gardens, or collections of esoterica. When these venerable terrors venture forth to hunt, they can remake Underdark trade routes or coastal communities with their voracious appetites and love of destruction.

## Deep Dragons

*Dragons of Caverns and Secrets*

Deep dragons slither through the wet and lightless places of the Underdark. They are stealthy hunters with an affinity for lost lore and fungi that flourish in the depths. As deep dragons age, their smooth, serpentine bodies become riddled with fungal rot, particularly around their faces, to imbue their breath with terror-inducing spores.

Deep dragons covet treasure and knowledge. Some deep dragons seek to gain knowledge via experience and travel, slithering through caverns and seas of the Underdark to map hidden passages for dozens of miles. Other deep dragons enjoy cultivating groves of molds and fungi, including colossal varieties sufficient to conceal the dragons' sinuous forms. Many deep dragons collect forgotten tomes or works of art and bully, cajole, or steal collections from drow or duergar sages.

Deep dragons are excellent swimmers. They often clash with aquatic Underdark societies, such as kuo-toa. Many deep dragons demand tribute from these groups in the form of food or treasure.

Underdark explorers have many reasons to brave deep dragon lairs beyond treasure hunting; they might contain the only surviving copies of forgotten lore, fungal ingredients for cures or plagues, or maps to lost Underdark locales.

## Deep Dragon Lairs

Deep dragons lair in fungus-encrusted caverns of the Underdark or old, forgotten ruins, preferring locations near subterranean bodies of water.

```statblock
"name": "Ancient Deep Dragon (FRAiF)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "247"
"hit_dice": "15d20 + 90"
"modifier": !!int "15"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "22"
  - !!int "19"
  - !!int "18"
  - !!int "21"
"speed": "40 ft., burrow 40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "Perception"
    "desc": "+16"
  - "name": "Stealth"
    "desc": "+15"
"damage_resistances": "poison, psychic"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "Blindsight 60 ft., Darkvision 300 ft., passive Perception 26"
"languages": "Common, Draconic, Undercommon"
"cr": "18"
"traits":
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 15 ft. *Hit:* 17 (2d10 + 6) Slashing\
      \ damage plus 5 (1d10) Poison damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 20, each creature in a 90-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 44 (8d10) Psychic damage,\
      \ and the target has the Frightened condition until the end of the dragon's\
      \ next turn. *Success:* Half damage only."
    "name": "Nightmare Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The dragon shape-shifts into a Small or Medium Humanoid or a Small or\
      \ Medium Beast, or it returns to its true form. Its game statistics, other than\
      \ its size, are the same in each form. Any equipment it is wearing or carrying\
      \ isn't transformed."
    "name": "Shape-Shift"
"regional_effects":
  - "desc": "The region containing an adult or ancient deep dragon's lair is changed\
      \ by its presence, creating the following effects:\n\n- **Preservation of Knowledge.**\
      \ Books and other written forms of communication with 1 mile of the lair become\
      \ magically protected and can't be damaged by nonmagical means.  \n- **Restless\
      \ Sleep.** When a creature finishes a Long Rest within 1 mile of the lair, the\
      \ creature makes a DC 10 Constitution saving throw. On a failed save, the creature\
      \ doesn't reduce its Exhaustion level as a result of finishing that Long Rest.\
      \ Creatures with Immunity to the Poisoned condition are immune to this effect.\
      \  \n- **Verdant Growth.** Vegetation and fungi within 1 mile of the dragon's\
      \ lair grow faster and cover a greater area than normal. Foraging in this area\
      \ yields twice the usual amount of food. The dragon is immediately aware of\
      \ the presence of any creature that eats this enhanced vegetation.  \n\nIf the\
      \ dragon dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, the dragon can expend a use to take one of the following\
  \ actions. The dragon regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The dragon moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span>, and it makes one Rend attack."
    "name": "Pounce"
  - "desc": "*Constitution Saving Throw:* DC 20, one creature within 30 feet of the\
      \ dragon that it can see. *Failure:* 16 (3d10) Poison damage, and the target\
      \ has the Poisoned condition. It repeats the save at the end of each of its\
      \ turns, ending the effect on itself on a success. After 1 minute, it succeeds\
      \ automatically. *Failure or Success:* The dragon can't take this action again\
      \ until the start of its next turn."
    "name": "Spore Salvo"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/ancient-deep-dragon-fraif.webp"
```
^statblock

## Environment

underdark