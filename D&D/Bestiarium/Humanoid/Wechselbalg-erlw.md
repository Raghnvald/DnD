---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/erlw
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/changeling
  - Monster/Typ/Humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Changeling
---
# [Changeling](3-Mechanics\CLI\bestiary\humanoid/changeling-erlw.md)
*Source: Eberron: Rising from the Last War p. 317*  

Changelings are a humanoid race of shapechangers who conceal their true identities behind false faces. Their gifts of mimicry allow them to appear as members of any humanoid culture, playing the part of a dwarf one day and a dragonborn the next. Although changelings can adopt any guise, most rely on a few established personas, each with a developed history and a network of friends and acquaintances.

```statblock
"name": "Changeling (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "changeling, shapechanger"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "leather armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+4"
  - "name": "Deception"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+2"
  - "name": "Perception"
    "desc": "+2"
  - "name": "Persuasion"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish, Elvish, Halfling, Thieves' cant"
"cr": "1/2"
"traits":
  - "desc": "The changeling can use its action to polymorph into a Medium humanoid\
      \ it has seen, or back into its true form. Its statistics, other than its size,\
      \ are the same in each form. Any equipment it is wearing or carrying isn't transformed.\
      \ It reverts to its true form if it dies."
    "name": "Change Appearance"
"actions":
  - "desc": "The changeling makes two attacks with its dagger."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "Each creature within 30 feet of the changeling must succeed on a DC 13\
      \ Wisdom saving throw or be frightened for 1 minute. A creature can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success."
    "name": "Unsettling Visage (Recharges after a Short or Long Rest)"
"source":
  - "ERLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/changeling-erlw.webp"
```
^statblock