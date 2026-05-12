---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mgelft
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/grung
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dankwood Grung"
---
# [Dankwood Grung](3-Mechanics/CLI/bestiary/humanoid/dankwood-grung-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 31*  

Dankwood grungs come in a variety of colors and play different roles in their community:

- Green: Warriors, hunters and workers  
- Blue: Crafters and cooks  
- Purple: Leaders and commanders  
- Red: Scholars and magic users  
- Orange: Super elite warriors  
- Gold: The big boss  

```statblock
"name": "Dankwood Grung (MGELFT)"
"size": "Small"
"type": "humanoid"
"subtype": "grung"
"alignment": "lawful grumpy"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "16"
  - !!int "15"
  - !!int "10"
  - !!int "11"
  - !!int "15"
"speed": "25 ft., climb 25 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+2"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 12"
"languages": "Grung"
"cr": "1"
"traits":
  - "desc": "The grung can breathe air and water."
    "name": "Amphibious"
  - "desc": "Any creature that grapples the grung or otherwise comes into direct contact\
      \ with the grung's skin must succeed on a DC 12 Constitution saving throw or\
      \ become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute.\
      \ A [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) creature no longer\
      \ in direct contact with the grung can repeat the saving throw at the end of\
      \ each of its turns, ending the effect on itself on a success."
    "name": "Poisonous Skin"
  - "desc": "The grung's long jump is up to 25 feet and its high jump is up to 15\
      \ feet, with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "A ferocious gurgling issues from the throat of the Dankwood grung, warning\
      \ those within 15 feet that they are indeed grumpy. Creatures in that area must\
      \ succeed at a DC 12 Charisma saving throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ until the end of their next turn."
    "name": "Grumpy Grung Growl"
  - "desc": "*Melee  or Ranged Weapon Attack:* +0 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage in melee, or 3 (1d4\
      \ + 1) piercing damage at range. Target must succeed on a DC 12 Constitution\
      \ saving throw or take 5 (2d4) poison damage."
    "name": "Dagger"
"source":
  - "MGELFT"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dankwood-grung-mgelft.webp"
```
^statblock