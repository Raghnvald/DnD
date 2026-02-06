---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/gos
  - Monster/HG/4
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/sahuagin
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sahuagin Deep Diver
---
# [Sahuagin Deep Diver](3-Mechanics\CLI\bestiary\humanoid/sahuagin-deep-diver-gos.md)
*Source: Ghosts of Saltmarsh p. 250*  

These mighty sahuagin, found in The Final Enemy, are transformed by the divine magic of Sekolah to enable them to better explore the darkest depths of the ocean. Out of the water, they cling to shadows and serve as hunters and assassins. A long, scaly lure that can be illuminated extends from a deep diver's forehead.

```statblock
"name": "Sahuagin Deep Diver (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "9"
"speed": "30 ft., swim 40 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin"
"cr": "4"
"traits":
  - "desc": "The deep diver has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The deep diver has advantage on Dexterity (Stealth) checks made while\
      \ submerged in water."
    "name": "Brine Lurker"
  - "desc": "The deep diver can breathe air and water, but it needs to be submerged\
      \ at least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
  - "desc": "The deep diver can cause its lure to light up or darken at will. While\
      \ the lure is lit, the deep diver sheds bright light in a 30-foot radius centered\
      \ on itself and dim light for an additional 20 feet."
    "name": "Lure"
  - "desc": "The deep diver can magically command any shark within 120 feet of it,\
      \ using a limited telepathy."
    "name": "Shark Telepathy"
"actions":
  - "desc": "The deep diver makes two attacks with its glaive, or one attack with\
      \ its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d10 + 2) slashing damage."
    "name": "Glaive"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) slashing damage."
    "name": "Claws"
  - "desc": "The deep diver pulses magical light from its lure. Any creature within\
      \ 30 feet of the deep diver that can see the light must succeed on a DC 11 Wisdom\
      \ saving throw or be charmed until the end of its next turn. A creature charmed\
      \ in this way is incapacitated as it stares at the light."
    "name": "Light of Sekolah"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/sahuagin-deep-diver-gos.webp"
```
^statblock