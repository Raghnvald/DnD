---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ice Piercer
---
# [Ice Piercer](3-Mechanics\CLI\bestiary\monstrosity/ice-piercer-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 226*  

Auril the Frostmaiden has transformed icicles into creatures that resemble piercers.

Clinging to the ceilings of caverns and large subterranean passages, piercers blend in perfectly with natural rock, dropping in silence to impale unsuspecting foes on the ground below.

A piercer is the larval form of a roper, and the two creatures often attack in tandem. A rock-like shell encases a piercer's body, giving it the look and texture of a stalactite. That shell protects a soft, slug-like upper body that lets the piercer move across cavern walls and ceilings to position itself for prey. With its eye and mouth closed, the piercer is difficult to distinguish from ordinary rock formations.

```statblock
"name": "Ice Piercer (IDRotF)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "16"
  - !!int "1"
  - !!int "7"
  - !!int "3"
"speed": "5 ft., climb 5 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+5"
"damage_immunities": "cold"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "While the ice piercer remains motionless on the ceiling, it is indistinguishable\
      \ from a normal stalactite."
    "name": "False Appearance"
  - "desc": "The ice piercer can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, one creature directly underneath the\
      \ piercer. *Hit:* 10 (3d6) piercing damage plus 10 (3d6) cold damage. Miss:\
      \ The piercer takes half the normal falling damage for the distance fallen."
    "name": "Drop"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/ice-piercer-idrotf.webp"
```
^statblock