---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bariaur Wanderer"
---
# [Bariaur Wanderer](3-Mechanics/CLI/bestiary/celestial/bariaur-wanderer-mpp.md)
*Source: Morte's Planar Parade p. 21*  

Hailing from Ysgard, bariaurs are centaur-like Celestials with the lower bodies of goats, humanoid torsos, and curved horns. Some bariaurs sate their wanderlust by exploring their home plane, the Outlands, and the Great Wheel beyond. These bariaur wanderers often serve as guides in the Outlands, assisting visitors by eagerly suggesting gate-town attractions and other points of interest. Throughout their travels, these hardy wanderers absorb ambient planar energies, adapting to the vast and varied terrains of the Outer Planes and frequently taking on aspects of those planes (see ""Planar Influences"" in "Morte's Planar Parade").

```statblock
"name": "Bariaur Wanderer (MPP)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Chaotic Good"
"ac": !!int "14"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "15"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "4"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+6"
"gear":
  - "[shortbow](3-Mechanics/CLI/items/shortbow.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Celestial, Common"
"cr": "3"
"traits":
  - "desc": "The bariaur can sense the presence of portals within 30 feet of itself,\
      \ including inactive portals, and instinctively knows the destination of each\
      \ one. The bariaur knows the distance and direction to the last portal it used\
      \ as long as they're on the same plane."
    "name": "Portal Sense"
"actions":
  - "desc": "The bariaur makes two Barbed Javelin or Shortbow attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 9 (1d10 + 4) piercing damage. If the target is a\
      \ creature, its speed is reduced by 10 feet until the start of the bariaur's\
      \ next turn."
    "name": "Barbed Javelin"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) bludgeoning damage. If the bariaur moved at least 20 feet straight\
      \ toward the target immediately before the hit, the target takes an extra 10\
      \ (3d6) bludgeoning damage, and the target must succeed on a DC 14 Strength\
      \ saving throw or have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Ram"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage, plus 4 (1d8) piercing damage if the target\
      \ doesn't have all its hit points."
    "name": "Shortbow"
  - "desc": "The bariaur casts one of the following spells, requiring no material\
      \ components and using Wisdom as the spellcasting ability:\n\n**At will:** [dancing\
      \ lights](3-Mechanics/CLI/spells/dancing-lights.md), [druidcraft](3-Mechanics/CLI/spells/druidcraft.md)\n\
      \n**1/day each:** [goodberry](3-Mechanics/CLI/spells/goodberry.md), [pass without\
      \ trace](3-Mechanics/CLI/spells/pass-without-trace.md), [tongues](3-Mechanics/CLI/spells/tongues.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The bariaur jumps a distance up to its walking speed."
    "name": "Mighty Leap"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/bariaur-wanderer-mpp.webp"
```
^statblock