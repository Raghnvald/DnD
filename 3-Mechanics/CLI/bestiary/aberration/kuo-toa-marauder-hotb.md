---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kuo-toa Marauder"
---
# [Kuo-toa Marauder](3-Mechanics/CLI/bestiary/aberration/kuo-toa-marauder-hotb.md)
*Source: Heroes of the Borderlands p. 8*  

Kuo-toa have slimy, humanoid bodies and the heads of goggle-eyed deep-sea fish. They claim they once dominated whole worlds, their empires spanning land and sea under the blessings of piscine gods.

Kuo-toa undertake contrived plots to propel themselves to dominance, often kidnapping people to learn their secrets or making dubious sacrifices to bizarre gods. These marauders lurk in wet places, eager to shed blood and claim plunder.

```statblock
"name": "Kuo-toa Marauder (HotB)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., [Truesight](3-Mechanics/CLI/rules/senses.md#Truesight)\
  \ 30 ft., passive Perception 14"
"languages": "Common, Undercommon"
"cr": "1/2"
"traits":
  - "desc": "The kuo-toa can breathe air and water."
    "name": "Amphibious"
  - "desc": "While in sunlight, the kuo-toa has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on ability checks and attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Slashing\
      \ damage."
    "name": "Brine Slicer"
"bonus_actions":
  - "desc": "The kuo-toa takes the Disengage action."
    "name": "Slippery"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/aberration/token/kuo-toa-marauder-hotb.webp"
```
^statblock