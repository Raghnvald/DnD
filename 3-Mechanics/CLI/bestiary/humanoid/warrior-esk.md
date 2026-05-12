---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/esk
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warrior"
---
# [Warrior](3-Mechanics/CLI/bestiary/humanoid/warrior-esk.md)
*Source: Essentials Kit p. 63*  

```statblock
"name": "Warrior (ESK)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "chain shirt, shield"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+3"
"gear":
  - "longbow"
  - "longsword"
"senses": "passive Perception 13"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The warrior has one of the following traits of your choice:\n\n- **Attacker.**\
      \ The warrior gains a +2 bonus to attack rolls.  \n- **Defender.** The warrior\
      \ gains the Protection reaction below.  "
    "name": "Martial Role"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 150/600 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage."
    "name": "Longbow"
"reactions":
  - "desc": "The warrior imposes disadvantage on the attack roll of a creature within\
      \ 5 feet of it whose target isn't the warrior. The warrior must be able to see\
      \ the attacker."
    "name": "Protection (Defender Only)"
"source":
  - "ESK"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/warrior-esk.webp"
```
^statblock