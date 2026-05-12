---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lizardfolk Scaleshield"
---
# [Lizardfolk Scaleshield](3-Mechanics/CLI/bestiary/humanoid/lizardfolk-scaleshield-gos.md)
*Source: Ghosts of Saltmarsh p. 242*  

Serving as the elite warriors and officers of a lizardfolk clan, these robust creatures wear thick armor made from crocodile scales and metal. Trained in martial weapons and advanced combat tactics, they are found protecting lizardfolk lairs such as the one in Danger at Dunwater.

```statblock
"name": "Lizardfolk Scaleshield (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "scale mail, shield"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "14"
  - !!int "7"
  - !!int "12"
  - !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+5"
"gear":
  - "morningstar"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1"
"traits":
  - "desc": "The scaleshield can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The scaleshield makes two melee attacks, each one with a different weapon."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) piercing damage."
    "name": "Morningstar"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Spiked Shield"
"reactions":
  - "desc": "If an ally within 5 feet of the scaleshield is hit by an attack, the\
      \ scaleshield can reduce that attack's damage by half."
    "name": "Shield Block"
"source":
  - "GoS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-scaleshield-gos.webp"
```
^statblock