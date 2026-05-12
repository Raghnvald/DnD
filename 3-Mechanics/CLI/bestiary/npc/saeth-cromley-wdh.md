---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/illuskan-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Saeth Cromley"
---
# [Saeth Cromley](3-Mechanics/CLI/bestiary/npc/saeth-cromley-wdh.md)
*Source: Waterdeep: Dragon Heist p. 216*  

Saeth Cromley is a retired sergeant of the City Watch, a likable fellow with a sharp, sarcastic wit. He occasionally comes out of retirement at the request of Barnibus Blastwind, and he assists the mage in investigating unusual crimes in the city. Cromley helps Barnibus relate to the common folk, and he is good at coaxing information out of them. Though Cromley was once a strict proponent of Watch regulations and dress codes, he has grown a bit lax in both matters now that he's officially retired.

```statblock
"name": "Saeth Cromley (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[splint armor](3-Mechanics/CLI/items/splint-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow-xphb.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "3"
"actions":
  - "desc": "Saeth makes two longsword attacks. If it has a shortsword drawn, it can\
      \ also make a shortsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 100/400 ft., one target. *Hit:*\
      \ 6 (1d10 + 1) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/saeth-cromley-wdh.webp"
```
^statblock