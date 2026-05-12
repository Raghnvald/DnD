---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scholarly Excavator"
---
# [Scholarly Excavator](3-Mechanics/CLI/bestiary/humanoid/scholarly-excavator-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 206*  

Field research is often dangerous work, especially when it involves ancient magic and monster-infested ruins. Scholarly excavators are trained to deal with those dangers, adept at protecting their allies and clearing obstacles from their path.

## Scholars of Allsight

The Allegiance of Allsight is a scholarly faction that operates primarily within the Marquesian metropolis of Ank'Harel. Though most members of the allegiance are academics unfamiliar with combat, the faction's field agents are skilled archaeologists who are also trained to contend with and overcome the threats that lurk in the depths of Exandria.

```statblock
"name": "Scholarly Excavator (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "breastplate"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+4"
  - "name": "Athletics"
    "desc": "+4"
  - "name": "History"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common plus two other languages"
"cr": "3"
"traits":
  - "desc": "The excavator deals double damage to objects and structures."
    "name": "Siege Expert"
"actions":
  - "desc": "The excavator makes three Thunderous Warhammer attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d10 + 2) thunder damage."
    "name": "Thunderous Warhammer"
"bonus_actions":
  - "desc": "The excavator targets one Medium or smaller creature or an object weighing\
      \ 300 pounds or less that isn't being worn or carried. The target, which must\
      \ be within 30 feet of the excavator and visible to it, is magically pushed\
      \ up to 20 feet horizontally in a direction of the excavator's choice. If the\
      \ target is a creature, it can make a DC 13 Strength saving throw to resist\
      \ the effect and is not pushed on a successful save."
    "name": "Telekinetic Toss (Recharge 5-6)"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/scholarly-excavator-crcotn.webp"
```
^statblock