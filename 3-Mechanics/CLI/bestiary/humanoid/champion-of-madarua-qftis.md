---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Champion of Madarua"
---
# [Champion of Madarua](3-Mechanics/CLI/bestiary/humanoid/champion-of-madarua-qftis.md)
*Source: Quests from the Infinite Staircase p. 220*  

Champions of Madarua represent the most skilled warriors in the faction. Hardened by battle, they lead the charge into the fray and inspire their fellow warriors to strike with decisive fury.

## Warriors of Madarua

Members of the Warriors of Madarua wear bronze masks that depict the determined the face of Madarua, an ancient Cynidicean god of birth, death, and the seasons. Each member bears a small tattoo of a sickle on the inside of their left wrist.

Warriors of Madarua recognize and respect the ever-changing complexity of life. In combat, they strive to be as fierce and unpredictable as nature itself.

```statblock
"name": "Champion of Madarua (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Good"
"ac": !!int "13"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "dexterity": !!int "3"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+3"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "2"
"actions":
  - "desc": "The champion makes three Longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) piercing damage, or 8 (1d10 + 3) piercing damage if used with\
      \ two hands."
    "name": "Longsword"
"bonus_actions":
  - "desc": "The champion summons an aura of ghostly animals that fills a 10-foot-radius\
      \ sphere centered on itself. While this aura is active, the champion and all\
      \ its allies in the aura have advantage on attack rolls. The aura moves with\
      \ the champion and lasts for 1 minute, until the champion has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, or until the champion uses another bonus action to end the aura."
    "name": "Aura of Fury (1/Day)"
"reactions":
  - "desc": "The champion adds 2 to its AC against one melee attack that would hit\
      \ it. To do so, the champion must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/champion-of-madarua-qftis.webp"
```
^statblock