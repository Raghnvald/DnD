---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Yeti Leader
tags:
  - Monster/Größe/Groß
  - Monster/HG/3
  - Monster/Typ/Monstrosität
  - Quelle/5e/tftyp
aliases:
  - Yeti Leader
---
# [Yeti Leader](3-Mechanics\CLI\bestiary\monstrosity/yeti-leader-tftyp.md)
*Source: Tales from the Yawning Portal p. 183*  

```statblock
"name": "Yeti Leader (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "8"
  - !!int "12"
  - !!int "7"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+3"
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Yeti"
"cr": "3"
"traits":
  - "desc": "If the yeti takes fire damage, it has disadvantage on attack rolls and\
      \ ability checks until the end of its next turn."
    "name": "Fear of Fire"
  - "desc": "The yeti has advantage on Wisdom (Perception) checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The yeti has advantage on Dexterity (Stealth) checks made to hide in\
      \ snowy terrain."
    "name": "Snow Camouflage"
"actions":
  - "desc": "The yeti can use its Chilling Gaze and makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 3 (1d6) cold damage."
    "name": "Frost Brand Greatsword"
  - "desc": "The yeti targets one creature it can see within 30 feet of it. If the\
      \ target can see the yeti, the target must succeed on a DC 13 Constitution saving\
      \ throw against this magic or take 10 (3d6) cold damage and then be paralyzed\
      \ for 1 minute, unless it is immune to cold damage. The target can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success. If the target's saving throw is successful, or if the effect\
      \ ends on it, the target is immune to the Chilling Gaze of all yetis (but not\
      \ abominable yetis) for 1 hour."
    "name": "Chilling Gaze"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/yeti-leader-tftyp.webp"
```
^statblock