---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vecna Impersonator"
---
# [Vecna Impersonator](3-Mechanics/CLI/bestiary/monstrosity/vecna-impersonator-tofw.md)
*Source: Turn of Fortune's Wheel p. 26*  

```statblock
"name": "Vecna Impersonator (ToFW)"
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
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+3"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "The impersonator can use its action to polymorph into a Small or Medium\
      \ humanoid it has seen, or back into its true form. Its statistics, other than\
      \ its size, are the same in each form. Any equipment it is wearing or carrying\
      \ isn't transformed. It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "In the first round of a combat, the impersonator has advantage on attack\
      \ rolls against any creature it [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised)."
    "name": "Ambusher"
  - "desc": "If the impersonator surprises a creature and hits it with an attack during\
      \ the first round of combat, the target takes an extra 10 (3d6) damage from\
      \ the attack."
    "name": "Surprise Attack"
"actions":
  - "desc": "The impersonator makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "The impersonator magically reads the surface thoughts of one creature\
      \ within 60 feet of it. The effect can penetrate barriers, but 3 feet of wood\
      \ or dirt, 2 feet of stone, 2 inches of metal, or a thin sheet of lead blocks\
      \ it. While the target is in range, the impersonator can continue reading its\
      \ thoughts, as long as the impersonator's [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ isn't broken (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). While reading the target's mind, the impersonator has advantage\
      \ on Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight)) and Charisma\
      \ ([Deception](3-Mechanics/CLI/rules/skills.md#Deception), [Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation),\
      \ and [Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)) checks against\
      \ the target."
    "name": "Read Thoughts"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/vecna-impersonator-tofw.webp"
```
^statblock