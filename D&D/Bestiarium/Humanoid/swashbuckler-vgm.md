---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/3
  - Monster/Habitat/coastal
  - Monster/Habitat/urban
  - Monster/Größe/Mittelgroß
  - Monster/Typ/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Swashbuckler
---
# [Swashbuckler](3-Mechanics\CLI\bestiary\humanoid/swashbuckler-vgm.md)
*Source: Volo's Guide to Monsters p. 217, Tomb of Annihilation, Dragon of Icespire Peak, Storm Lord's Wrath*  

Swashbucklers are charming ne'er-do-wells who live by their own codes of honor. They crave notoriety, often indulge in romantic trysts, and eke out livings as pirates and corsairs, rarely staying in one place for too long.

```statblock
"name": "Swashbuckler (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "17"
"ac_class": "leather armor"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+8"
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Persuasion"
    "desc": "+6"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
  - "desc": "The swashbuckler can take the Dash or Disengage action as a bonus action\
      \ on each of its turns."
    "name": "Lightfooted"
  - "desc": "While the swashbuckler is wearing light or no armor and wielding no shield,\
      \ its AC includes its Charisma modifier."
    "name": "Suave Defense"
"actions":
  - "desc": "The swashbuckler makes three attacks: one with a dagger and two with\
      \ its rapier."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) piercing damage."
    "name": "Rapier"
"source":
  - "VGM"
  - "ToA"
  - "DIP"
  - "SLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/swashbuckler-vgm.webp"
```
^statblock

## Environment

coastal, urban