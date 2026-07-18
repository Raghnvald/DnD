---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Isarr Kronenstrom
Status: WIP
linter-yaml-title-alias: Isarr Kronenstrom
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/idrotf
aliases:
  - Isarr Kronenstrom
---
# [Isarr Kronenstrom](3-Mechanics\CLI\bestiary\npc/isarr-kronenstrom-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 307*  

The Wolf Tribe has been without a king or queen for years. Its most powerful chieftain, Isarr Kronenstrom, is a psychotic brute who worships Malar the Beast Lord. He hunts Ten-Towners for sport, bathes in their blood, and strikes fear into the hearts of his enemies. Several members of Isarr's clan have deserted him or been killed off, but the few that remain are fiercely loyal. They believe, incorrectly, that he's the Chosen of Malar.

Although Isarr calls himself the Wolf King, few others in the Wolf Tribe support him in that claim, but the other Wolf clan chieftains are too weak and disorganized to challenge him.

```statblock
"name": "Isarr Kronenstrom (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "hide armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "15"
  - !!int "14"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Intimidation"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+6"
  - "name": "Survival"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common"
"cr": "8"
"traits":
  - "desc": "Isarr has advantage on melee attack rolls against any creature that doesn't\
      \ have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "Isarr can reroll a saving throw he fails. He must use the new roll."
    "name": "Indomitable (3/Day)"
  - "desc": "Isarr has advantage on Wisdom (Perception) checks that rely on hearing\
      \ or smell."
    "name": "Keen Hearing and Smell"
"actions":
  - "desc": "Isarr makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) piercing damage, plus 13 (2d12) piercing damage if the target has no\
      \ allies it can see within 10 feet of it."
    "name": "Sickle"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 100/400 ft., one target. *Hit:*\
      \ 8 (1d10 + 3) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/isarr-kronenstrom-idrotf.webp"
```
^statblock