---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sweettooth Horror
---
# [Sweettooth Horror](3-Mechanics\CLI\bestiary\fiend/sweettooth-horror-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

No one is certain of the true origin of Sweettooth Village. This eerie, abandoned town constructed of gingerbread and frosting lies deep in the wilds of Eldraine. Some say the fiendish candy monsters that prowl its butterscotch-lined streets were once servants of a powerful witch, and the entire place was a trap created to lure hungry travelers. But if the sugary horrors of Sweettooth Village were ever under someone's control, that time has long since passed.

> [!quote] A quote from Greta, scourge of Sweettooth  
> 
> I smell frosting. Ready your weapons!

> [!note] Horrors of Sweettooth Village
> 
> In addition to the Sweettooth horror described here, creatures found in and around Sweettooth Village might include gingerbrutes as well as variations of oozes from the *Monster Manual*. For example, a black pudding might have a delicious chocolatey flavor, a gelatinous cube might have a more decorative shape and taste fruity, and an ochre jelly could smell like butterscotch.
^horrors-of-sweettooth-village

```statblock
"name": "Sweettooth Horror (MCV4EC)"
"size": "Large"
"type": "fiend"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "12"
  - !!int "6"
  - !!int "8"
  - !!int "12"
"speed": "40 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "4"
"traits":
  - "desc": "If the horror takes fire damage, it releases a sweet, mesmerizing scent.\
      \ Each creature within 30 feet of the horror must succeed on a DC 11 Wisdom\
      \ saving throw or have the charmed condition. A charmed creature can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success."
    "name": "Caramelization"
  - "desc": "The horror has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The horror makes one Bite attack and two Candy Cane attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) piercing damage plus 10 (3d6) acid damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:* 8\
      \ (1d8 + 4) bludgeoning damage. If the target is a Large or smaller creature,\
      \ the horror can choose to deal no damage; instead, the target has the prone\
      \ condition, and the horror can pull the target up to 5 feet toward itself."
    "name": "Candy Cane"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/sweettooth-horror-mcv4ec.webp"
```
^statblock