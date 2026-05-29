---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Bard
linter-yaml-title-alias: Bard
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/2
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/vgm
aliases:
  - Bard
---
# [Bard](3-Mechanics\CLI\bestiary\humanoid/bard-vgm.md)
*Source: Volo's Guide to Monsters p. 211, Waterdeep: Dragon Heist, Ghosts of Saltmarsh*  

Bards are gifted poets, storytellers, and entertainers who travel far and wide, but are commonly found in taverns or in the company of jolly bands of adventurers, rough-and-tumble mercenaries, and wealthy patrons.

```statblock
"name": "Bard (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "chain shirt"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Performance"
    "desc": "+6"
"senses": "passive Perception 15"
"languages": "any two languages"
"cr": "2"
"traits":
  - "desc": "The bard is a 4th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 12, +4 to hit with spell attacks). It has the following bard\
      \ spells prepared:\n\n**Cantrips (at will):** friends, mage hand, vicious mockery\n\
      \n**1st level (4 slots):** charm person, healing word, heroism, sleep, thunderwave\n\
      \n**2nd level (3 slots):** invisibility, shatter"
    "name": "Spellcasting"
  - "desc": "The bard can perform a song while taking a short rest. Any ally who hears\
      \ the song regains an extra 1d6 hit points if it spends any Hit Dice to regain\
      \ hit points at the end of that rest. The bard can confer this benefit on itself\
      \ as well."
    "name": "Song of Rest"
  - "desc": "The bard can use a bonus action on its turn to target one creature within\
      \ 30 feet of it. If the target can hear the bard, the target must succeed on\
      \ a DC 12 Charisma saving throw or have disadvantage on ability checks, attack\
      \ rolls, and saving throws until the start of the bard's next turn."
    "name": "Taunt (2/Day)"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Shortbow"
"source":
  - "VGM"
  - "WDH"
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/bard-vgm.webp"
```
^statblock

## Environment

urban