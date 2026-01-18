---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/egw
  - Monster/HG/7
  - Monster/Größe/Riesig
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Swavain Basilisk
---
# [Swavain Basilisk](3-Mechanics\CLI\bestiary\monstrosity/swavain-basilisk-egw.md)
*Source: Explorer's Guide to Wildemount p. 300*  

Pearl divers and seafloor scavengers sometimes tell tales of mysterious ocean gardens filled with statues of sea creatures and sailors—the underwater grottoes of the deadly Swavain basilisk. Though named for the Swavain Islands where they are most commonly found, these dangerous hunters have been known to wander inland waterways, and have even been spotted in subterranean sewer systems.

```statblock
"name": "Swavain Basilisk (EGW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d12 + 20"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "15"
  - !!int "2"
  - !!int "8"
  - !!int "7"
"speed": "15 ft., swim 40 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": ""
"cr": "7"
"traits":
  - "desc": "The basilisk can breathe air and water."
    "name": "Amphibious"
  - "desc": "A creature must make a DC 13 Constitution saving throw if it hits the\
      \ basilisk with a weapon attack while within 5 feet of it or if it starts its\
      \ turn [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the basilisk.\
      \ Unless the save succeeds, the creature magically begins to turn to stone and\
      \ is [restrained](/3-Mechanics/CLI/conditions.md#Restrained), and it must repeat\
      \ the saving throw at the end of its next turn. On a successful save, the effect\
      \ ends. On a failure, the creature is [petrified](/3-Mechanics/CLI/conditions.md#Petrified)."
    "name": "Petrifying Secretions"
"actions":
  - "desc": "The basilisk makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:* 13\
      \ (3d6 + 3) piercing damage plus 10 (3d6) poison damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 15 ft., one target. *Hit:* 14\
      \ (2d10 + 3) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 12)."
    "name": "Tail"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/swavain-basilisk-egw.webp"
```
^statblock