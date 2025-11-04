---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/cr/1-8
  - Monster/environment/arctic
  - Monster/environment/coastal
  - Monster/environment/desert
  - Monster/environment/forest
  - Monster/environment/hill
  - Monster/environment/urban
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Bandit
---
# [Bandit](3-Mechanics\CLI\bestiary\humanoid/bandit.md)
*Source: Monster Manual p. 343. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Bandits rove in gangs and are sometimes led by thugs, veterans, or spellcasters. Not all bandits are evil. Oppression, drought, disease, or famine can often drive otherwise honest folk to a life of banditry.

Pirates are bandits of the high seas. They might be freebooters interested only in treasure and murder, or they might be privateers sanctioned by the crown to attack and plunder an enemy nation's vessels.

```statblock
"name": "Bandit"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "12"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6\
      \ + 1) slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage."
    "name": "Light Crossbow"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/bandit.webp"
```
^statblock

## Environment

coastal, hill, arctic, urban, forest, desert