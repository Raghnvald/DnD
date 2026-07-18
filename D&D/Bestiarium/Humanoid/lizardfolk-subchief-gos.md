---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Lizardfolk Subchief
Status: WIP
linter-yaml-title-alias: Lizardfolk Subchief
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Humanoid/lizardfolk
  - Quelle/5e/gos
aliases:
  - Lizardfolk Subchief
---
# [Lizardfolk Subchief](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-subchief-gos.md)
*Source: Ghosts of Saltmarsh p. 242, Storm Lord's Wrath*  

The lizardfolk subchief (seen in Danger at Dunwater) is a devout priest of Semuanya, pursuing the worship of its god in a manner similar to a cleric. It wields a dagger crafted of a massive crocodile tooth blessed by Semuanya, representing the subchief's prowess in both battle and piety.

```statblock
"name": "Lizardfolk Subchief (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "12"
"speed": "30 ft., swim 30 ft."
"saves":
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Draconic"
"cr": "3"
"traits":
  - "desc": "The subchief is a 5th-level spellcaster. Its spellcasting ability is\
      \ Wisdom (spell save DC 13, +5 to hit with spell attacks). It has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** light, sacred flame, spare\
      \ the dying, thaumaturgy\n\n**1st level (4 slots):** command, guiding bolt,\
      \ purify food and drink\n\n**2nd level (3 slots):** hold person, lesser restoration,\
      \ silence\n\n**3rd level (2 slots):** bestow curse, dispel magic"
    "name": "Spellcasting"
  - "desc": "The subchief can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage."
    "name": "Tooth Dagger"
  - "desc": "The subchief invokes the primal magic of Semuanya, summoning a spectral\
      \ maw around a target it can see within 60 feet of it. The target must make\
      \ a DC 13 Dexterity saving throw, taking 22 (5d8) piercing damage on a failed\
      \ save, or half as much damage on a successful one. A creature that fails this\
      \ saving throw is also frightened until the end of its next turn."
    "name": "Jaws of Semuanya (Recharge 5-6)"
"source":
  - "GoS"
  - "SLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-subchief-gos.webp"
```
^statblock