---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgdia
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/kenku
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Clonk"
---
# [Clonk](3-Mechanics/CLI/bestiary/npc/clonk-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 83*  

```statblock
"name": "Clonk (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "kenku"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "11"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+5"
"gear":
  - "[hellfire warhammer](3-Mechanics/CLI/items/hellfire-weapon-bgdia.md)"
"senses": "passive Perception 12"
"languages": "understands Auran and Common but speaks only through the use of its\
  \ Mimicry trait"
"cr": "1/4"
"traits":
  - "desc": "In the first round of a combat, Clonk has advantage on attack rolls against\
      \ any creature it surprised."
    "name": "Ambusher"
  - "desc": "Clonk can mimic any sounds it has heard, including voices. A creature\
      \ that hears the sounds can tell they are imitations with a successful DC 14\
      \ Wisdom (Insight) check."
    "name": "Mimicry"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d8) bludgeoning damage, or 5 (1d10 + 1) bludgeoning damage if used with\
      \ two hands to make a melee attack."
    "name": "Hellfire Warhammer"
"source":
  - "BGDIA"
"image": "3-Mechanics/CLI/bestiary/npc/token/clonk-bgdia.webp"
```
^statblock