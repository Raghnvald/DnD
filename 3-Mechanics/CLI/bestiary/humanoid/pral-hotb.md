---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pral"
---
# [Pral](3-Mechanics/CLI/bestiary/humanoid/pral-hotb.md)
*Source: Heroes of the Borderlands p. 6*  

Pral's boyishly handsome, self-assured grin graces wanted posters throughout the Borderlands. A self-proclaimed "gentleman thief," Pral abides by a strict personal code. He never kills, and he always upholds his end of any bargain he makes. A lover of good food, comfortable lodgings, and stylish clothing, Pral squanders the spoils of each robbery on his extravagant lifestyle.

```statblock
"name": "Pral (HotB)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
"gear":
  - "leather armor"
  - "light crossbow"
  - "rapier"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing\
      \ damage."
    "name": "Rapier"
  - "desc": "*Ranged Attack Roll:* +5, range 80/320 ft. *Hit:* 7 (1d8 + 3) Piercing\
      \ damage."
    "name": "Light Crossbow"
"reactions":
  - "desc": "Trigger: Pral is hit with a melee attack roll while holding a weapon.\
      \ _Response:_ Pral adds 2 to his AC against that attack, potentially causing\
      \ the attack to miss."
    "name": "Parry"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/pral-hotb.webp"
```
^statblock