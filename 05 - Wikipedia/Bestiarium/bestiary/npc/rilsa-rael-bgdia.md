---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Rilsa Rael
---
# [Rilsa Rael](3-Mechanics\CLI\bestiary\npc/rilsa-rael-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 199*  

The Guild kingpin of Little Calimshan. Among Little Calimshan's most notorious locations is the Calim Jewel Emporium, widely regarded as the best jeweler in the city—and the best place to fence stolen gems, as it's also the local Guild headquarters. In addition to hosting regular public forums in her shop, Rael tacitly oversees the Garden of Whispers, a maze of wood-and-paper screens where people from across the city can buy and sell secrets with Guild agents and each other, speaking through the barriers so as to maintain anonymity.

```statblock
"name": "Rilsa Rael (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "passive Perception 12"
"languages": "Common, Thieves' cant"
"cr": "3"
"traits":
  - "desc": "On each of her turns in combat, Rilsa can use a bonus action to take\
      \ the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "If Rilsa damages a creature with a weapon attack, she gains advantage\
      \ on attack rolls against that target until the end of her next turn."
    "name": "Focus"
  - "desc": "As a bonus action, Rilsa chooses one creature she can see within 30 feet\
      \ of her. The creature doesn't provoke opportunity attacks until the end of\
      \ its next turn, provided it can hear Rilsa's commands."
    "name": "Tactical Leadership"
"actions":
  - "desc": "Rilsa makes three weapon attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) piercing damage."
    "name": "Shortsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage."
    "name": "Dagger"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/rilsa-rael-bgdia.webp"
```
^statblock