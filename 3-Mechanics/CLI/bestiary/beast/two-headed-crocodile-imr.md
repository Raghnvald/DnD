---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Two-Headed Crocodile"
---
# [Two-Headed Crocodile](3-Mechanics/CLI/bestiary/beast/two-headed-crocodile-imr.md)
*Source: Infernal Machine Rebuild p. 89*  

```statblock
"name": "Two-Headed Crocodile (IMR)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "13"
  - !!int "2"
  - !!int "10"
  - !!int "5"
"speed": "20 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The two-headed crocodile can hold its breath for 15 minutes."
    "name": "Hold Breath"
  - "desc": "The two-headed crocodile has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks and on saving throws against being [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded),\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
      \ and knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)."
    "name": "Two Heads"
  - "desc": "When one of the crocodile's heads is asleep, its other head is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The two-headed crocodile makes two attacks with its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d10 + 2) piercing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 12). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and that head of the crocodile can't bite another target."
    "name": "Bite"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/beast/token/two-headed-crocodile-imr.webp"
```
^statblock