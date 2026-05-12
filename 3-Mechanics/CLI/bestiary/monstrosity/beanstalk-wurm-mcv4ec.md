---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Beanstalk Wurm"
---
# [Beanstalk Wurm](3-Mechanics/CLI/bestiary/monstrosity/beanstalk-wurm-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Wurms are enormous creatures that resemble limbless, wingless dragons, though they lack a dragon's breath weapons and keen intelligence. On the world of Eldraine, many wurms have adapted to life among the world's skyscraping beanstalks. These beanstalk wurms sport leafy growths, sustaining themselves on a mixture of natural photosynthesis and a carnivorous diet.

Cloud-dwelling giants often use beanstalk wurms as a first line of defense against those who would ascend massive beanstalks—also known as Everstalks—to intrude on their lofty palaces. Beanstalk wurms lie coiled along the length of an Everstalk with their eyes closed and their stomach flattened against the stalk, appearing to be just another enormous vine until a tasty intruder attempts to climb them.

> [!quote]  
> 
> When giants' prized pets escape Stormkeld, villages fall and new Everstalks rise.


```statblock
"name": "Beanstalk Wurm (MCV4EC)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "14d20 + 84"
"modifier": !!int "4"
"stats":
  - !!int "27"
  - !!int "18"
  - !!int "22"
  - !!int "4"
  - !!int "14"
  - !!int "10"
"speed": "50 ft., climb 50 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "12"
"senses": "passive Perception 12"
"languages": ""
"cr": "18"
"traits":
  - "desc": "If the wurm is motionless at the start of combat, it has advantage on\
      \ its initiative roll. Moreover, if a creature hasn't observed the wurm move\
      \ or act, that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the wurm is animate."
    "name": "False Appearance"
  - "desc": "Creatures have advantage on ability checks made to climb the wurm."
    "name": "Leafy Handholds"
  - "desc": "If the wurm fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The wurm regains 20 hit points at the start of its turn if it has at\
      \ least 1 hit point. If the wurm takes fire or lightning damage, this trait\
      \ doesn't function at the start of the wurm's next turn."
    "name": "Regeneration"
"actions":
  - "desc": "The wurm makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:*\
      \ 30 (5d8 + 8) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 22 Dexterity saving throw or be swallowed by the wurm.\
      \ A swallowed creature has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition, has total cover against attacks and other effects outside the wurm,\
      \ and takes 28 (8d6) piercing damage at the start of each of the wurm's turns\
      \ from thorns in the wurm's gullet.\n\nThe wurm's stomach can hold up to two\
      \ creatures at a time. If the wurm takes 30 damage or more on a single turn\
      \ from a creature inside it, the wurm must succeed on a DC 22 Constitution saving\
      \ throw at the end of that turn or regurgitate all swallowed creatures, each\
      \ of which falls in a space within 10 feet of the wurm and has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. If the wurm dies, a swallowed creature no longer has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition and can escape from the corpse by using 10 feet of movement, exiting\
      \ with the [prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition."
    "name": "Bite"
"source":
  - "MCV4EC"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/beanstalk-wurm-mcv4ec.webp"
```
^statblock