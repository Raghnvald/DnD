---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Verbeeg Marauder
Status: WIP
linter-yaml-title-alias: Verbeeg Marauder
tags:
  - Monster/Größe/Groß
  - Monster/HG/4
  - Monster/Typ/Riese
  - Quelle/5e/idrotf
aliases:
  - Verbeeg Marauder
---
# [Verbeeg Marauder](3-Mechanics\CLI\bestiary\giant/verbeeg-marauder-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 311*  

Verbeeg are giants that resemble oversized humans with gangly limbs and elongated faces. Some have other features that give them a fearsome aspect.

Verbeeg craft their own armor and weapons. They prefer thrown spears above all other weapons, and a verbeeg usually has several spears for that purpose.

## Marauders

Verbeeg conduct themselves like brigands, robbing people they come across in the wild. If food is scarce, they kill those same people and eat them. They prefer to dwell in forlorn places, often sharing territory with hill giants and ogres. It's not unusual to find a gang of hill giants and ogres led by a verbeeg, since verbeeg are much smarter than their brutish cousins. Verbeeg also enjoy the company of mammalian beasts and allow bears, wolves, worgs, and other predators to lair with them. They catch and keep horses, mules, sheep, goats, and cattle for food and trade.

```statblock
"name": "Verbeeg Marauder (IDRotF)"
"size": "Large"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "hide armor, shield"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "2"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "Animal Handling"
    "desc": "+2"
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+2"
"senses": "passive Perception 10"
"languages": "Common, Giant"
"cr": "4"
"traits":
  - "desc": "A simple weapon deals one extra die of its damage when the verbeeg hits\
      \ with it (included in the attack)."
    "name": "Simple Weapon Wielder"
"actions":
  - "desc": "The verbeeg makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 14 (3d6 + 4) piercing damage, or 17 (3d8 + 4) piercing\
      \ damage if used to make a ranged attack or used with two hands to make a melee\
      \ attack."
    "name": "Spear"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/giant/token/verbeeg-marauder-idrotf.webp"
```
^statblock