---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Redtooth Werefox
Status: WIP
linter-yaml-title-alias: Redtooth Werefox
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Monstrosität/elf
  - Quelle/5e/mcv4ec
aliases:
  - Redtooth Werefox
---
# [Redtooth Werefox](3-Mechanics\CLI\bestiary\monstrosity/redtooth-werefox-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

By day, the elves of Redtooth Keep are agile and adept rangers, expertly patrolling the lands around one of the last elven citadels in Eldraine. But at night, terrifying howls echo from the keep's halls as its inhabitants transform into ruthless werefoxes.

Unlike other forms of lycanthropy, the werefox curse isn't contagious and is limited to the elves of Redtooth Keep. Legends say that long ago, the garrison at Redtooth Keep turned away a group of travelers seeking shelter. Before departing, one of the travelers was revealed to be a powerful witch and cursed the elves, declaring that their bodies would forever transform to match their hearts' selfish and bestial natures.

> [!quote] A quote from Yenna, Redtooth regent  
> 
> My people are both bloom and thorn. Our ferocious impulses are as much a part of us as our skills, our beauty, and our history.

```statblock
"name": "Redtooth Werefox (MCV4EC)"
"size": "Medium"
"type": "monstrosity"
"subtype": "elf"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "60"
"hit_dice": "11d8 + 11"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "17"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "10"
"speed": "30 ft. (in elf form; 40 ft. in fox and hybrid form)"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Elvish (can't speak in fox form)"
"cr": "3"
"actions":
  - "desc": "The werefox makes two Bite attacks, two Lance attacks, or one Bite attack\
      \ and one Lance attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10\
      \ + 3) piercing damage. If the werefox moved at least 20 feet straight toward\
      \ the target immediately before the hit and the target is a Medium or smaller\
      \ creature, the target must succeed on a DC 13 Strength saving throw or have\
      \ the prone condition."
    "name": "Bite (Fox or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (1d12 + 3) piercing damage."
    "name": "Lance (Elf or Hybrid Form Only)"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 150/600 ft., one target. *Hit:*\
      \ 10 (2d6 + 3) piercing damage, and the target must succeed on a DC 11 Dexterity\
      \ saving throw or have the restrained condition until the start of the werefox's\
      \ next turn."
    "name": "Entangling Arrow (Elf or Hybrid Form Only)"
"bonus_actions":
  - "desc": "The werefox polymorphs into a fox-elf hybrid, into a fox, or back into\
      \ its elf form. Its game statistics, other than its speed, are the same in each\
      \ form. Any equipment it is wearing or carrying isn't transformed. It reverts\
      \ to its elf form if it dies."
    "name": "Change Shape"
  - "desc": "The werefox takes the Dash or Disengage action."
    "name": "Vulpine Nimbleness (Fox or Hybrid Form Only)"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/redtooth-werefox-mcv4ec.webp"
```
^statblock