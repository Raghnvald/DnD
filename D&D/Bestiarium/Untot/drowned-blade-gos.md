---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Drowned Blade
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Untote
  - Quelle/5e/gos
aliases:
  - Drowned Blade
linter-yaml-title-alias: Drowned Blade
---
# [Drowned Blade](3-Mechanics\CLI\bestiary\undead/drowned-blade-gos.md)
*Source: Ghosts of Saltmarsh p. 235*  

Assaulting the hermitage in Tammeraut's Fate, this barnacle-encrusted undead warrior fights with surprising cunning. Starfish cling to its wispy beard, and its evil rage is visible in its bloated gray eyes.

## Bluerot

This disease targets humanoids. While afflicted with bluerot, a victim grows grotesque blue boils on their face and back. This disease is carried by undead (including the drowned ones in Tammeraut's Fate), and victims most often acquire it through wounds caused by infected creatures. The disease's boils manifest in `dice:1d4|noform|noparens|avg` (`1d4`) hours, causing the victim's Constitution and Charisma scores to decrease by `dice:1d4|noform|noparens|avg` (`1d4`) each, to a minimum of 3. This is quickly followed by a fever and tingling in the extremities. An infected creature is vulnerable to radiant damage and gains the ability to breathe underwater.

At the end of each long rest, an infected creature makes a DC 12 Constitution saving throw. On a success, the victim regains 1 point of Constitution and 1 point of Charisma lost to the disease. If the infected creature regains all the points lost to the disease, it is cured. Other effects that raise the victim's ability scores do not cure the disease. On a failed saving throw, the victim takes `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) necrotic damage as the boils burst and spread. A creature reduced to 0 hit points by this damage cannot regain hit points until the disease is cured, though it can be stabilized as normal.

```statblock
"name": "Drowned Blade (GoS)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"ac_class": "leather armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "16"
  - !!int "3"
  - !!int "9"
  - !!int "5"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands the languages it knew in life but can't speak"
"cr": "2"
"traits":
  - "desc": "The drowned blade cannot swim, and it sinks to the bottom of any body\
      \ of water. It takes no penalties to its movement or attacks underwater. It\
      \ is immune to the effects of being underwater at a depth greater than 100 feet."
    "name": "Bottom Treader"
  - "desc": "The drowned blade shares its mind with every other drowned one within\
      \ 1 mile of it, and can communicate its thoughts and observations to them instantaneously\
      \ and without limitation."
    "name": "Bound Together"
  - "desc": "If damage reduces the drowned blade to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the drowned blade drops to 1 hit point\
      \ instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The drowned blade makes two rusted longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, and the target must succeed on a DC 12 Constitution\
      \ saving throw or contract [bluerot](/3-Mechanics/CLI/diseases.md#Bluerot) (see\
      \ the \"Bluerot\" in notes)."
    "name": "Rusted Longsword"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/undead/token/drowned-blade-gos.webp"
```
^statblock