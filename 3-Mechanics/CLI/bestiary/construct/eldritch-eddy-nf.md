---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nf
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eldritch Eddy"
---
# [Eldritch Eddy](3-Mechanics/CLI/bestiary/construct/eldritch-eddy-nf.md)
*Source: Netheril's Fall*  

When magical energy becomes dangerously unstable, it sometimes animates into an eldritch eddy: an uncontrolled whirlwind of Evocation magic that crackles with fire and lightning. Eldritch eddies typically arise where magic use is heavy and irresponsible, such as near a fanatical mage's sanctum, a workshop that churns out magic items, or a library where undertrained scribes work with Spell Scrolls. Eldritch eddies are common in ancient Netheril near the homes and workplaces of famous mages.

Eldritch eddies rampage with one purpose: destroy as much in their paths as possible. Before eldritch eddies manifest, telltale signs signal their arrival. Roll on or choose a result from the Eldritch Eddy Manifestations table to inspire what happens right before an eldritch eddy arises.

| dice: 1d6 | Right Before an Eddy Manifests... |
|-----------|-----------------------------------|
| 1 | Brightly colored sparks fly through the air like fireworks. |
| 2 | Spectral images of screaming mages or terrible beasts swirl in a whirlwind. |
| 3 | Electricity flashes, flames ignite, and the air smells acrid. |
| 4 | Purple smoke billows into a vortex. |
| 5 | A geyser of multicolored light shoots from the ground toward the sky. |
| 6 | The air shimmers, and unsettling laughter booms from all directions. |
^1-right-before-an-eddy-manifests

```statblock
"name": "Eldritch Eddy (NF)"
"size": "Large"
"type": "construct"
"alignment": "Chaotic Neutral"
"ac": !!int "11"
"hp": !!int "144"
"hit_dice": "17d10 + 51"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "16"
  - !!int "12"
  - !!int "9"
  - !!int "17"
"speed": "10 ft., fly 40 ft. (hover)"
"saves":
  - "dexterity": !!int "4"
  - "intelligence": !!int "4"
  - "charisma": !!int "6"
"damage_resistances": "force"
"damage_immunities": "fire, lightning"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 9"
"languages": "understands Common plus one other language but can't speak"
"cr": "6"
"traits":
  - "desc": "The eddy has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The eddy makes two attacks, using Searing Swipe or Arcane Bolt in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 10 ft. *Hit:* 13 (3d6 + 3) Fire or\
      \ Lightning damage (eddy's choice)."
    "name": "Searing Swipe"
  - "desc": "*Ranged Attack Roll:* +6, range 120 ft. *Hit:* 14 (2d10 + 3) Force\
      \ damage."
    "name": "Arcane Bolt"
"reactions":
  - "desc": "Trigger: The eddy takes damage. _Response—_*Strength Saving Throw:* DC\
      \ 14, each creature of the eddy's choice in a 5-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from the eddy. *Failure:* 7\
      \ (2d6) Force damage, and the target has the Prone condition."
    "name": "Eldritch Overload"
"source":
  - "NF"
"image": "3-Mechanics/CLI/bestiary/construct/token/eldritch-eddy-nf.webp"
```
^statblock

## Environment

urban