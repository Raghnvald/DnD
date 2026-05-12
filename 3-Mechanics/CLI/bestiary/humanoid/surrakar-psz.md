---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Surrakar"
---
# [Surrakar](3-Mechanics/CLI/bestiary/humanoid/surrakar-psz.md)
*Source: Plane Shift: Zendikar p. 26*  

The surrakar are a race of hulking amphibian humanoids native to Bala Ged. They have broad shoulders and long arms that drag on the ground when they walk. Their splayed feet and hands are webbed, and long tusks protrude from their large mouths. They have little culture and no written language, and some members of other races believe they are merely animals with no true language at all.

Surrakar are similar to D&D's [lizardfolk](3-Mechanics/CLI/bestiary/humanoid/lizardfolk.md).

```statblock
"name": "Surrakar (PSZ)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor, [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "13"
  - !!int "7"
  - !!int "12"
  - !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "[javelin](3-Mechanics/CLI/items/javelin.md)"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1/2"
"traits":
  - "desc": "The surrakar can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The surrakar makes two melee attacks, each one with a different weapon."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Heavy Club"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage."
    "name": "Javelin"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Spiked Shield"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/surrakar-psz.webp"
```
^statblock