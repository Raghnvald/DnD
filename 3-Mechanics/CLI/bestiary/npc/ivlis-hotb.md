---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ivlis"
---
# [Ivlis](3-Mechanics/CLI/bestiary/npc/ivlis-hotb.md)
*Source: Heroes of the Borderlands p. 26*  

Beneath a pretense of charity and goodness, Ivlis is a demon worshiper who leads a wicked cult. She uses deception and skulduggery to advance her power. Though she feigns kindness and compassion in public spaces, Ivlis believes the poor and downtrodden deserve their wretched lot. In battle, her magic is unpredictable.

```statblock
"name": "Ivlis (HotB)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "49"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
"gear":
  - "leather armor"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
  - "desc": "Ivlis makes three Chaos Blast attacks. She can replace one attack with\
      \ a use of Sinister Command if available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +4, reach 5 ft. or range 60 ft. *Hit:*\
      \ 7 (2d6) damage. Roll 1d4 to determine the damage type: 1, Acid; 2, Cold;\
      \ 3, Fire; 4, Lightning."
    "name": "Chaos Blast"
  - "desc": "*Wisdom Saving Throw:* DC 12, one creature Ivlis can see within 60 feet.\
      \ *Failure:* The target has the Charmed condition until the end of its next\
      \ turn. While Charmed, the target has the Incapacitated condition."
    "name": "Sinister Command (Recharge 5-6)"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/npc/token/ivlis-hotb.webp"
```
^statblock