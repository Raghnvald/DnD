---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Stone Giant of Evil Earth
tags:
  - Monster/Größe/Riesig
  - Monster/HG/9
  - Monster/Typ/Riese
  - Quelle/5e/bgg
aliases:
  - Stone Giant of Evil Earth
---
# [Stone Giant of Evil Earth](3-Mechanics\CLI\bestiary\giant/stone-giant-of-evil-earth-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 179*  

Stone giants with a bent toward cruelty and destruction might reject the gods of the Ordning and turn to the worship of Ogrémoch, the Prince of Evil Earth. These giants view the surface world not as a realm of dream but as a nightmare worthy only of destruction, so they lend their strength to cults that plan to reduce the world to rubble.

Outfitted in heavy armor crafted to resemble the cult's patron, stone giants of Evil Earth wield weapons that pulse with thunderous energy. These giants serve as the muscle for the cult, wielding their might to destroy the surface world in the name of Ogrémoch.

```statblock
"name": "Stone Giant of Evil Earth (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "typically  Neutral Evil"
"ac": !!int "20"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "137"
"hit_dice": "11d12 + 66"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "13"
  - !!int "22"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+14"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Giant, Terran"
"cr": "9"
"actions":
  - "desc": "The giant makes two Thundering Stone Club or Boulder attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 15 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage. The giant can cause the club to emit a burst\
      \ of thunderous energy that deals 10 (3d6) thunder damage to each creature,\
      \ other than the giant, within 30 feet of the target. The club can emit a burst\
      \ this way only once per turn."
    "name": "Thundering Stone Club"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/240 ft., one target. *Hit:*\
      \ 19 (3d8 + 6) bludgeoning damage, and the target must succeed on a DC 18 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition.\
      \ After the giant throws the boulder, roll a d6; on a roll of 3 or lower, the\
      \ giant has no more boulders to throw."
    "name": "Boulder"
"reactions":
  - "desc": "In response to failing a saving throw to avoid being moved, having the\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone) condition, or both, the giant\
      \ succeeds instead."
    "name": "Unyielding"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/stone-giant-of-evil-earth-bgg.webp"
```
^statblock