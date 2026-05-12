---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lizardfolk Warden"
---
# [Lizardfolk Warden](3-Mechanics/CLI/bestiary/elemental/lizardfolk-warden-hotb.md)
*Source: Heroes of the Borderlands p. 10*  

Lizardfolk wardens draw on primal magic to protect nature's boundaries. These territorial guardians lurk in wetlands and jungles, surfacing from murky pools to track down trespassers and drive them out. Wardens wield weapons and shields fashioned from the husks of giant beetles, snapping turtles, and other mighty creatures. When these tools fail them, they channel the forces of nature to augment their natural attacks with poison saliva.

```statblock
"name": "Lizardfolk Warden (HotB)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "8"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "shield"
"senses": "passive Perception 11"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "The lizardfolk can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The lizardfolk makes one Bite attack and one Bone Pike attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing\
      \ damage plus 3 (1d6) Poison damage."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +4, reach 10 ft. *Hit:* 7 (1d10 + 2) Piercing\
      \ damage."
    "name": "Bone Pike"
  - "desc": "*Ranged Attack Roll:* +4, range 60 ft. *Hit:* 12 (3d6 + 2) Poison\
      \ damage."
    "name": "Poison Spit"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/elemental/token/lizardfolk-warden-hotb.webp"
```
^statblock