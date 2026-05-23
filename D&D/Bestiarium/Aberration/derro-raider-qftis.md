---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Derro Raider
Kategorie: Aberration
Größe: Klein
HG: 1/4
status: WIP
tags:
  - Quelle/5e/qftis
  - ttrpg-cli/monster/cr/1-4
  - ttrpg-cli/monster/size/small
  - ttrpg-cli/monster/type/aberration
aliases:
  - Derro Raider
---
# [Derro Raider](3-Mechanics/CLI/bestiary/aberration/derro-raider-qftis.md)
*Source: Quests from the Infinite Staircase p. 196*  

Hostility and greed are guiding values for some derro. These derro indiscriminately raid settlements and rob travelers regardless of the apparent value of any goods they steal. These derro believe such acts are sanctioned by their despicable god, Diirinka, who delights in cruelty and destruction.

## Derro

Derro are Underdark dwellers of dubious origin. According to the histories of some duergar, derro are descended from a community of dwarves that was left behind when the others escaped the rule of mind flayers. The mind flayers' psionic power eventually transformed these forsaken dwarves into Aberrations.

You can learn more about derro in *Mordenkainen Presents: Monsters of the Multiverse*.

```statblock
"name": "Derro Raider (QftIS)"
"size": "Small"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "1/4"
"traits":
  - "desc": "The derro has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, the derro has disadvantage on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage. If the target is a Medium or smaller creature,\
      \ the derro can choose to deal no damage, and instead the target has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Hooked Spear"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft. *Hit:* 5 (1d6 + 2) bludgeoning damage."
    "name": "Throwing Hammer"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/aberration/token/derro-raider-qftis.webp"
```
^statblock