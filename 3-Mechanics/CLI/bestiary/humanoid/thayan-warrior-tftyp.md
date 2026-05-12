---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thayan Warrior"
---
# [Thayan Warrior](3-Mechanics/CLI/bestiary/humanoid/thayan-warrior-tftyp.md)
*Source: Tales from the Yawning Portal p. 246*  

```statblock
"name": "Thayan Warrior (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any Non-Good alignment"
"ac": !!int "16"
"ac_class": "[chain shirt](3-Mechanics/CLI/items/chain-shirt-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[javelin](3-Mechanics/CLI/items/javelin-xphb.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "passive Perception 12"
"languages": "Common, Thayan"
"cr": "2"
"traits":
  - "desc": "Within the Doomvault, the warrior has advantage on saving throws against\
      \ being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Doomvault Devotion"
  - "desc": "The warrior has advantage on an attack roll against a creature if at\
      \ least one of the warrior's allies is within 5 feet of the creature and the\
      \ ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The warrior makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 6 (1d6 + 3) piercing damage."
    "name": "Javelin"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/thayan-warrior-tftyp.webp"
```
^statblock