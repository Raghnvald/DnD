---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Pirate Deck Wizard
linter-yaml-title-alias: Pirate Deck Wizard
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/gos
aliases:
  - Pirate Deck Wizard
---
# [Pirate Deck Wizard](3-Mechanics\CLI\bestiary\humanoid/pirate-deck-wizard-gos.md)
*Source: Ghosts of Saltmarsh p. 248*  

These salt-encrusted practitioners of magic are at once learned and superstitious. The crews of pirate ships generally give their deck wizards a wide berth, as they magically step from place to place and unleash their briny magic against attackers. The ship Sea Ghost in The Sinister Secret of Saltmarsh is home to a pirate deck wizard named Punketah.

```statblock
"name": "Pirate Deck Wizard (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "1"
"traits":
  - "desc": "The deck wizard is a 4th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 13, +5 to hit with spell attacks). It has the\
      \ following wizard spells prepared:\n\n**Cantrips (at will):** friends, mage\
      \ hand, prestidigitation, ray of frost\n\n**1st level (4 slots):** disguise\
      \ self, fog cloud, mage armor, witch bolt\n\n**2nd level (3 slots):** gust of\
      \ wind, Melf's acid arrow, misty step"
    "name": "Spellcasting"
  - "desc": "The deck wizard has advantage on ability checks and saving throws to\
      \ resist being knocked prone."
    "name": "Sea Legs"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6)\
      \ bludgeoning damage."
    "name": "Quarterstaff"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/pirate-deck-wizard-gos.webp"
```
^statblock