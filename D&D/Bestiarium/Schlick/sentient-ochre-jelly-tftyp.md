---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sentient Ochre Jelly
linter-yaml-title-alias: Sentient Ochre Jelly
tags:
  - Monster/Größe/Groß
  - Monster/HG/2
  - Monster/Typ/Schleim
  - Quelle/5e/tftyp
aliases:
  - Sentient Ochre Jelly
---
# [Sentient Ochre Jelly](3-Mechanics\CLI\bestiary\ooze/sentient-ochre-jelly-tftyp.md)
*Source: Tales from the Yawning Portal p. 158*  

```statblock
"name": "Sentient Ochre Jelly (TftYP)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "5"
  - !!int "6"
  - !!int "1"
"speed": "10 ft., climb 10 ft."
"damage_resistances": "acid"
"damage_immunities": "lightning, slashing"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, prone"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The jelly can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "The jelly can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6\
      \ + 2) bludgeoning damage plus 3 (1d6) acid damage."
    "name": "Pseudopod"
"reactions":
  - "desc": "When a jelly that is Medium or larger is subjected to lightning or slashing\
      \ damage, it splits into two new jellies if it has at least 10 hit points. Each\
      \ new jelly has hit points equal to half the original jelly's, rounded down.\
      \ New jellies are one size smaller than the original jelly."
    "name": "Split"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/sentient-ochre-jelly-tftyp.webp"
```
^statblock