---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warrior of Madarua"
---
# [Warrior of Madarua](3-Mechanics/CLI/bestiary/humanoid/warrior-of-madarua-qftis.md)
*Source: Quests from the Infinite Staircase p. 220*  

Warriors are the foot soldiers of the faction. They thank Madarua for each battle they see and train daily with spears to follow her to victory.

## Warriors of Madarua

Members of the Warriors of Madarua wear bronze masks that depict the determined the face of Madarua, an ancient Cynidicean god of birth, death, and the seasons. Each member bears a small tattoo of a sickle on the inside of their left wrist.

Warriors of Madarua recognize and respect the ever-changing complexity of life. In combat, they strive to be as fierce and unpredictable as nature itself.

```statblock
"name": "Warrior of Madarua (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Good"
"ac": !!int "12"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/8"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"reactions":
  - "desc": "The warrior adds 2 to its AC against one melee attack that would hit\
      \ it. To do so, the warrior must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/warrior-of-madarua-qftis.webp"
```
^statblock