---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotdq
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Langdedrosa Cyanwrath"
---
# [Langdedrosa Cyanwrath](3-Mechanics/CLI/bestiary/npc/langdedrosa-cyanwrath-hotdq.md)
*Source: Hoard of the Dragon Queen p. 91, Tyranny of Dragons p. 186*  

```statblock
"name": "Langdedrosa Cyanwrath (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-dragon"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[splint armor](3-Mechanics/CLI/items/splint-armor-xphb.md)"
"hp": !!int "57"
"hit_dice": "6d12 + 18"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "strength": !!int "6"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "lightning"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword-xphb.md)"
  - "[spear](3-Mechanics/CLI/items/spear-xphb.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 14"
"languages": "Common, Draconic"
"cr": "4"
"traits":
  - "desc": "On his turn, Langdedrosa can take one additional action."
    "name": "Action Surge (Recharges on a Short or Long Rest)"
  - "desc": "Langdedrosa's weapon attacks score a critical hit on a roll of 19 or\
      \ 20."
    "name": "Improved Critical"
"actions":
  - "desc": "Langdedrosa attacks twice, either with his greatsword or spear."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Greatsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or ranged\
      \ 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage."
    "name": "Spear"
  - "desc": "Langdedrosa breathes lightning in a 30-foot line that is 5 feet wide.\
      \ Each creature in the line must make a DC 13 Dexterity saving throw, taking\
      \ 22 (4d10) lightning damage on a failed save, or half as much damage on a\
      \ successful one."
    "name": "Lightning Breath (Recharge 5-6)"
"source":
  - "HotDQ"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/langdedrosa-cyanwrath-hotdq.webp"
```
^statblock