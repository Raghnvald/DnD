---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zhentilar Soldier"
---
# [Zhentilar Soldier](3-Mechanics/CLI/bestiary/humanoid/zhentilar-soldier-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 285*  

Zhentilar soldiers occupy Zhentarim fortresses and outposts. The price of betraying the organization is so steep that many Zhentilar soldiers would rather die for the Zhentarim than abandon their post.

## Zhentilar

*Wardens of the Zhentarim*

The Zhentilar is the militant wing of the Zhentarim. Zhentilar forces occupy Zhentarim strongholds such as Zhentil Keep and Darkhold and defend these places from the Zhentarim's many enemies. If the Zhentarim is one big family, then the Zhentilar are the protective older siblings who look out for their kin.

Zhentilar also conduct other important organizational work such as safeguarding powerful magic items or escorting Zhentarim leaders.

```statblock
"name": "Zhentilar Soldier (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "13"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "3"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+4"
  - "name": "Athletics"
    "desc": "+4"
"gear":
  - "leather armor"
  - "pistol"
  - "shortsword"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "The Zhentilar makes two attacks, using Shortsword or Pistol in any combination.\
      \ It can replace one attack with a use of Knock Down."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing\
      \ damage plus 2 (1d4) Poison damage."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +4, range 80/320 ft. *Hit:* 7 (1d10 + 2) Piercing\
      \ damage."
    "name": "Pistol"
  - "desc": "*Strength Saving Throw:* DC 12, one creature within 5 feet that the Zhentilar\
      \ can see. *Failure:* 4 (1d4 + 2) Bludgeoning damage. If the target is a Medium\
      \ or smaller creature, it has the Prone condition."
    "name": "Knock Down"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/zhentilar-soldier-fraif.webp"
```
^statblock

## Environment

any