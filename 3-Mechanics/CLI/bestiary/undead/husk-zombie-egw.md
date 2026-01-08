---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Husk Zombie
---
# [Husk Zombie](3-Mechanics\CLI\bestiary\undead/husk-zombie-egw.md)
*Source: Explorer's Guide to Wildemount p. 293*  

The wastes of Eastern Wynandir retain many curses and corruptions from the time of the Calamity, the worst of which pervert the sanctity of death. One such curse manifests as a terrible roving fog that draws the corpses of the fallen to rise as husk zombies—resilient undead of frightening speed and bloodlust. As well, some of the more heinous fiends that walk these scarred lands feed on the life force of the living, leaving these terrible undead in their wake.

```statblock
"name": "Husk Zombie (EGW)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "10"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "16"
  - !!int "3"
  - !!int "6"
  - !!int "5"
"speed": "35 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 8"
"languages": "understands the languages it knew in life but can't speak"
"cr": "1"
"traits":
  - "desc": "A humanoid slain by a melee attack from the zombie revives as a husk\
      \ zombie on its next turn."
    "name": "Curse of the Husk"
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The zombie makes two claw attacks. For each of these attacks that reduces\
      \ a creature to 0 hit points, the zombie can make an additional claw attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Claw"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/undead/token/husk-zombie-egw.webp"
```
^statblock