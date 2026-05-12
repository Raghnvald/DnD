---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dabus"
---
# [Dabus](3-Mechanics/CLI/bestiary/celestial/dabus-mpp.md)
*Source: Morte's Planar Parade p. 23*  

Among the bustling throngs of Sigil's streets float gray-skinned, vaguely humanlike figures with curled horns. Where they travel, cracks in the mortar seal shut, stray bricks float back into place, and ruined city blocks are restored. These are dabus, the silent caretakers of Sigil and loyal servants of the Lady of Pain.

Dabus patrol the City of Doors to maintain public buildings, portals, and utilities. They use their innate ability to manipulate Sigil's infrastructure not only to effect repairs but also to combat individuals who disrupt the city's operations or violate the Lady's edicts, hurling bricks at troublemakers and subduing them by causing the streets to sprout grasping cobblestone hands.

When dabus communicate, rather than speaking or signing words, they create esoteric illusory images and symbols in front of themselves. Scholars have yet to determine the origin of dabus's difficult-to-comprehend rebuses, though some speculate their etymology predates Sigil itself.

```statblock
"name": "Dabus (MPP)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Lawful Neutral"
"ac": !!int "12"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "14"
"speed": "20 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": "understands all languages but can't speak; communicates via Symbol Speech"
"cr": "2"
"traits":
  - "desc": "The dabus doesn't make melee attacks or opportunity attacks, even in\
      \ self-defense."
    "name": "Physical Restraint"
  - "desc": "A dabus communicates by creating illusory symbols and pictures that float\
      \ in the air in front of itself and disappear a few seconds later. A creature\
      \ that can see such a message can decipher it with a successful DC 10 Intelligence\
      \ ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)) check (no\
      \ action required)."
    "name": "Symbol Speech"
"actions":
  - "desc": "The dabus makes two Flying Brick attacks."
    "name": "Multiattack"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 90 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) bludgeoning damage."
    "name": "Flying Brick"
  - "desc": "The dabus causes a 20-foot-square area of ground it can see within 60\
      \ feet of itself to sprout clutching appendages made of stone. Each creature\
      \ of the dabus's choice in that area must succeed on a DC 13 Dexterity saving\
      \ throw or take 9 (2d8) bludgeoning damage and have the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 13). While [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ in this way, the creature has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition. The appendages vanish after 1 minute or if the dabus's [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ ends (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell)."
    "name": "Grasping Ground (Recharge 6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/dabus-mpp.webp"
```
^statblock