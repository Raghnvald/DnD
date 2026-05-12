---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotdq
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Captain Othelstan"
---
# [Captain Othelstan](3-Mechanics/CLI/bestiary/npc/captain-othelstan-hotdq.md)
*Source: Hoard of the Dragon Queen p. 89, Tyranny of Dragons p. 181*  

```statblock
"name": "Captain Othelstan (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "[splint armor](3-Mechanics/CLI/items/splint-armor-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+4"
"gear":
  - "[flail](3-Mechanics/CLI/items/flail-xphb.md)"
  - "[spear](3-Mechanics/CLI/items/spear-xphb.md)"
"senses": "passive Perception 15"
"languages": "Common, Draconic, Giant"
"cr": "5"
"traits":
  - "desc": "On his turn, Othelstan can take one additional action."
    "name": "Action Surge (Recharges on a Short or Long Rest)"
  - "desc": "When Othelstan takes damage that reduces him to 0 hit points, he immediately\
      \ regains 20 hit points. If he has 20 hit points or fewer at the end of his\
      \ next turn, he dies."
    "name": "Tiamat's Blessing of Retribution"
"actions":
  - "desc": "Othelstan attacks twice with his flail or spear, or makes two ranged\
      \ attacks with his spears."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) bludgeoning damage."
    "name": "Flail"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or ranged\
      \ 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage."
    "name": "Spear"
"source":
  - "HotDQ"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/captain-othelstan-hotdq.webp"
```
^statblock