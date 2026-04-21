---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: War Priest
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Wüste
  - Monster/HG/9
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/vgm
aliases:
  - War Priest
---
# [War Priest](3-Mechanics\CLI\bestiary\humanoid/war-priest-vgm.md)
*Source: Volo's Guide to Monsters p. 218, Dragon of Icespire Peak*  

War priests worship deities of war and combat. They plan tactics, lead soldiers into battle, confront enemy spellcasters, and tend to casualties. A war priest might command an army or serve as a warlord's right hand on the battlefield.

```statblock
"name": "War Priest (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "9"
"traits":
  - "desc": "The priest is a 9th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 15, +7 to hit with spell attacks). It has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** light, mending, sacred flame,\
      \ spare the dying\n\n**1st level (4 slots):** divine favor, guiding bolt, healing\
      \ word, shield of faith\n\n**2nd level (3 slots):** lesser restoration, magic\
      \ weapon, prayer of healing, silence, spiritual weapon\n\n**3rd level (3 slots):**\
      \ beacon of hope, crusader's mantle, dispel magic, revivify, spirit guardians,\
      \ water walk\n\n**4th level (3 slots):** banishment, freedom of movement, guardian\
      \ of faith, stoneskin\n\n**5th level (1 slots):** flame strike, mass cure wounds,\
      \ hold monster"
    "name": "Spellcasting"
"actions":
  - "desc": "The priest makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage."
    "name": "Maul"
"reactions":
  - "desc": "The priest grants a +10 bonus to an attack roll made by itself or another\
      \ creature within 30 feet of it. The priest can make this choice after the roll\
      \ is made but before it hits or misses."
    "name": "Guided Strike (Recharges after a Short or Long Rest)"
"source":
  - "VGM"
  - "DIP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/war-priest-vgm.webp"
```
^statblock

## Environment

desert, urban