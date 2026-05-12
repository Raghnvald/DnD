---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Morte"
---
# [Morte](3-Mechanics/CLI/bestiary/npc/morte-tofw.md)
*Source: Turn of Fortune's Wheel p. 10*  

The talking skull Morte is a curmudgeonly interplanar traveler plucked from his eternal punishment in the Nine Hells. Tormented by the lies he told in life, Morte masks his pain with a morbid sense of humor and an insufferable dose of sarcasm.

```statblock
"name": "Morte (ToFW)"
"size": "Tiny"
"type": "undead"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d4 + 12"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "12"
"speed": "0 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "1/4"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) piercing damage."
    "name": "Bite"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/morte-tofw.webp"
```
^statblock