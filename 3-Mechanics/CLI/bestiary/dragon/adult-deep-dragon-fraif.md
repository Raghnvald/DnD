---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Adult Deep Dragon"
---
# [Adult Deep Dragon](3-Mechanics/CLI/bestiary/dragon/adult-deep-dragon-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 258*  

The strange magic pervading the Underdark twists deep dragons as they grow, so few adult deep dragons look alike. Their skin is usually pitted by fungal growths that spread across the body. Although lacking the versatile shape-shifting of metallic dragons, deep dragons can assume the form of animals or humanoids and often masquerade as snakes or dragonborn.

Adult deep dragons eliminate challengers with ferocious might, cunning ambushes, or fungal poisons. Some adult deep dragons plunder the surface for treasures and lore.

## Deep Dragons

*Dragons of Caverns and Secrets*

Deep dragons slither through the wet and lightless places of the Underdark. They are stealthy hunters with an affinity for lost lore and fungi that flourish in the depths. As deep dragons age, their smooth, serpentine bodies become riddled with fungal rot, particularly around their faces, to imbue their breath with terror-inducing spores.

Deep dragons covet treasure and knowledge. Some deep dragons seek to gain knowledge via experience and travel, slithering through caverns and seas of the Underdark to map hidden passages for dozens of miles. Other deep dragons enjoy cultivating groves of molds and fungi, including colossal varieties sufficient to conceal the dragons' sinuous forms. Many deep dragons collect forgotten tomes or works of art and bully, cajole, or steal collections from drow or duergar sages.

Deep dragons are excellent swimmers. They often clash with aquatic Underdark societies, such as kuo-toa. Many deep dragons demand tribute from these groups in the form of food or treasure.

Underdark explorers have many reasons to brave deep dragon lairs beyond treasure hunting; they might contain the only surviving copies of forgotten lore, fungal ingredients for cures or plagues, or maps to lost Underdark locales.

## Deep Dragon Lairs

Deep dragons lair in fungus-encrusted caverns of the Underdark or old, forgotten ruins, preferring locations near subterranean bodies of water.

```statblock
"name": "Adult Deep Dragon (FRAiF)"
"size": "Huge"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "161"
"hit_dice": "17d12 + 51"
"modifier": !!int "10"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "17"
  - !!int "16"
  - !!int "16"
  - !!int "18"
"speed": "40 ft., burrow 30 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Perception"
    "desc": "+11"
  - "name": "Stealth"
    "desc": "+10"
"damage_resistances": "poison, psychic"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "Blindsight 60 ft., Darkvision 150 ft., passive Perception 21"
"languages": "Common, Draconic, Undercommon"
"cr": "11"
"traits":
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 14 (2d8 + 5) Slashing\
      \ damage plus 5 (1d10) Poison damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 15, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 38 (7d10) Psychic damage,\
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
  - "desc": "*Constitution Saving Throw:* DC 15, one creature within 30 feet of the\
      \ dragon that it can see. *Failure:* 13 (3d8) Poison damage, and the target\
      \ has the Poisoned condition. It repeats the save at the end of each of its\
      \ turns, ending the effect on itself on a success. After 1 minute, it succeeds\
      \ automatically. *Failure or Success:* The dragon can't take this action again\
      \ until the start of its next turn."
    "name": "Spore Salvo"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/adult-deep-dragon-fraif.webp"
```
^statblock

## Environment

underdark