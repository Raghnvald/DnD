---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bonnie
---
# [Bonnie](3-Mechanics\CLI\bestiary\npc/bonnie-wdh.md)
*Source: Waterdeep: Dragon Heist p. 20*  

*Human barmaid*

> [!quote]  
> 
> Many adventurers pass though the Yawning Portal on their way to greatness. All of them try the ale.


```statblock
"name": "Bonnie (WDH)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "4"
"stats":
  - !!int "11"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "14"
"speed": "20 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+3"
"condition_immunities": "charmed"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "4"
"traits":
  - "desc": "Bonnie can use its action to polymorph into a Small or Medium humanoid\
      \ it has seen, or back into its true form. Its statistics, other than its size,\
      \ are the same in each form. Any equipment it is wearing or carrying isn't transformed.\
      \ It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "In the first round of a combat, Bonnie has advantage on attack rolls\
      \ against any creature it surprised."
    "name": "Ambusher"
  - "desc": "If Bonnie surprises a creature and hits it with an attack during the\
      \ first round of combat, the target takes an extra 10 (3d6) damage from the\
      \ attack."
    "name": "Surprise Attack"
"actions":
  - "desc": "Bonnie makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "Bonnie magically reads the surface thoughts of one creature within 60\
      \ feet of it. The effect can penetrate barriers, but 3 feet of wood or dirt,\
      \ 2 feet of stone, 2 inches of metal, or a thin sheet of lead blocks it. While\
      \ the target is in range, Bonnie can continue reading its thoughts, as long\
      \ as Bonnie's concentration isn't broken (as if concentrating on a spell). While\
      \ reading the target's mind, Bonnie has advantage on Wisdom (Insight) and Charisma\
      \ (Deception, Intimidation, and Persuasion) checks against the target."
    "name": "Read Thoughts"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/bonnie-wdh.webp"
```
^statblock