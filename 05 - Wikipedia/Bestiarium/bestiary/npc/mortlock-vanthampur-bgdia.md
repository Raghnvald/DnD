---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Mortlock Vanthampur
---
# [Mortlock Vanthampur](3-Mechanics\CLI\bestiary\npc/mortlock-vanthampur-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 26*  

Mortlock is tolerated by his mother, Duke Thalamra Vanthampur, and despised by his older brothers, Thurstwell and Amrik, who view him as a simpleton and an abomination. Half of Mortlock's face was scarred by fire when he was a child, and his disfigurement gives him a fearsome countenance.

```statblock
"name": "Mortlock Vanthampur (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "17"
  - !!int "10"
  - !!int "12"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "Mortlock can reroll a saving throw that he fails. He must use the new\
      \ roll."
    "name": "Indomitable (2/Day)"
"actions":
  - "desc": "Mortlock makes two attacks with his greatclub."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4\
      \ + 4) bludgeoning damage, plus 5 (2d4) bludgeoning damage if Mortlock has taken\
      \ any damage since his last turn."
    "name": "Greatclub"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 100/400 ft., one target. *Hit:*\
      \ 7 (1d10 + 2) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/mortlock-vanthampur-bgdia.webp"
```
^statblock