---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Gingerbrute
tags:
  - Monster/Größe/Winzig
  - Monster/HG/1-2
  - Monster/Typ/Konstrukt
  - Quelle/5e/mcv4ec
aliases:
  - Gingerbrute
---
# [Gingerbrute](3-Mechanics\CLI\bestiary\construct/gingerbrute-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Gingerbread cookies baked in the wilds of Eldraine—or made from ingredients grown there—have a habit of developing a life of their own. Known as gingerbrutes, these cookie Constructs are notoriously difficult to pin down.

When an unfortunate baker accidentally creates a gingerbrute, the cookie causes mayhem throughout the kitchen before running back to the wilds where its ingredients originated. Many witches of Dunbarrow craft gingerbrutes intentionally, whipping them into shape (sometimes with actual whipped cream) as soldiers to defend their wicked cauldrons.

The same magic that animates a gingerbrute also makes it extra scrumptious. Those who have eaten a gingerbrute report feeling a burst of energy like a long-lasting sugar rush.

> [!quote] A quote from Todwin Mallow, now-destitute baker  
> 
> The unlabeled vial was not vanilla extract after all.

```statblock
"name": "Gingerbrute (MCV4EC)"
"size": "Tiny"
"type": "construct"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "18"
"hit_dice": "4d4 + 8"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "7"
  - !!int "10"
  - !!int "12"
"speed": "60 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+6"
  - "name": "Athletics"
    "desc": "+3"
"damage_vulnerabilities": "bludgeoning"
"condition_immunities": "exhaustion"
"senses": "passive Perception 10"
"languages": "one language of its creator"
"cr": "1/2"
"traits":
  - "desc": "The gingerbrute has advantage on any ability checks or saving throws\
      \ it makes to avoid or end the grappled or the restrained condition on itself."
    "name": "Can't Catch Me"
  - "desc": "Once the gingerbrute is destroyed, a creature can use its action to eat\
      \ all the remains and gain 5 temporary hit points. The remains crumble away\
      \ after 24 hours if not eaten."
    "name": "Sweet Victory"
"actions":
  - "desc": "The gingerbrute makes two Fork attacks, two Gumdrop Slingshot attacks,\
      \ or one of each."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4\
      \ + 4) piercing damage."
    "name": "Fork"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 30/120 ft., one target. *Hit:*\
      \ 6 (1d4 + 4) bludgeoning damage."
    "name": "Gumdrop Slingshot"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/construct/token/gingerbrute-mcv4ec.webp"
```
^statblock