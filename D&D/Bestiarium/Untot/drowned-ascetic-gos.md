---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/gos
  - Monster/HG/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Drowned Ascetic
---
# [Drowned Ascetic](3-Mechanics\CLI\bestiary\undead/drowned-ascetic-gos.md)
*Source: Ghosts of Saltmarsh p. 233*  

Dressed in tattered robes, its fists wrapped in long rib bons of rotting cloth, the drowned ascetic moves with alarming speed for an undead creature. This martial artist, rising from the ocean in Tammeraut's Fate, retains its fighting reflexes despite its rotting flesh.

## Bluerot

This disease targets humanoids. While afflicted with bluerot, a victim grows grotesque blue boils on their face and back. This disease is carried by undead (including the drowned ones in Tammeraut's Fate), and victims most often acquire it through wounds caused by infected creatures. The disease's boils manifest in `dice:1d4|noform|noparens|avg` (`1d4`) hours, causing the victim's Constitution and Charisma scores to decrease by `dice:1d4|noform|noparens|avg` (`1d4`) each, to a minimum of 3. This is quickly followed by a fever and tingling in the extremities. An infected creature is vulnerable to radiant damage and gains the ability to breathe underwater.

At the end of each long rest, an infected creature makes a DC 12 Constitution saving throw. On a success, the victim regains 1 point of Constitution and 1 point of Charisma lost to the disease. If the infected creature regains all the points lost to the disease, it is cured. Other effects that raise the victim's ability scores do not cure the disease. On a failed saving throw, the victim takes `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) necrotic damage as the boils burst and spread. A creature reduced to 0 hit points by this damage cannot regain hit points until the disease is cured, though it can be stabilized as normal.

```statblock
"name": "Drowned Ascetic (GoS)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "16"
  - !!int "3"
  - !!int "9"
  - !!int "5"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands the languages it knew in life but can't speak"
"cr": "3"
"traits":
  - "desc": "The drowned ascetic cannot swim, and it sinks to the bottom of any body\
      \ of water. It takes no penalties to its movement or attacks underwater. It\
      \ is immune to the effects of being underwater at a depth greater than 100 feet."
    "name": "Bottom Treader"
  - "desc": "The drowned ascetic shares its mind with every other drowned one within\
      \ 1 mile of it, and can communicate its thoughts and observations to them instantaneously\
      \ and without limitation."
    "name": "Bound Together"
  - "desc": "If damage reduces the drowned ascetic to 0 hit points, it must make a\
      \ Constitution saving throw with a DC of 5 + the damage taken, unless the damage\
      \ is radiant or from a critical hit. On a success, the drowned ascetic drops\
      \ to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The drowned ascetic makes three unarmed strikes."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage, and the target must succeed on a DC 12 Constitution\
      \ saving throw or contract [bluerot](/3-Mechanics/CLI/diseases.md#Bluerot) (see\
      \ the \"Bluerot\" in notes)."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "The drowned ascetic adds 3 to its AC against one ranged attack that would\
      \ hit it. To do so, the drowned ascetic must see the attacker."
    "name": "Dexterous Target"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/undead/token/drowned-ascetic-gos.webp"
```
^statblock