---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wurm"
---
# [Wurm](3-Mechanics/CLI/bestiary/monstrosity/wurm-psk.md)
*Source: Plane Shift: Kaladesh p. 31*  

Wurms are enormous, legless creatures that burrow under the forests, mountains, and plains of Kaladesh, and which can exceed fifty feet in length when fully grown. A wurm devours everything in its path—flora, fauna, and inanimate objects alike—with a gaping maw containing multiple rings of sharp teeth and grinding plates. Rumor has it that at least one wurm tunnels beneath the large, lush park in Ghirapur called the Cowl, accounting for at least some of the mysterious disappearances there.

Both the colored scales of a wurm's skin and the winding patterns of its tunnels mimic the flow of aether through the sky. Some elf aether-seers believe that these tunnels reveal a deep connection between wurms and aether, and they explore wurm burrows in the hope of developing a similar connection. It is said that a wurm never doubles back along its own path, so following those paths is less dangerous than it might seem. However, the existence of a single wurm in an area suggests that others might be nearby, and wurm tunnels do cross each other—so not all these brave aether-seers return. Those who do are said to gain insights that they find difficult to express to others.

The [purple worm](3-Mechanics/CLI/bestiary/monstrosity/purple-worm.md) in the "Monster Manual" works well as a representation of Kaladesh's wurms.

```statblock
"name": "Wurm (PSK)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "247"
"hit_dice": "15d20 + 90"
"modifier": !!int "-2"
"stats":
  - !!int "28"
  - !!int "7"
  - !!int "22"
  - !!int "1"
  - !!int "8"
  - !!int "4"
"speed": "50 ft., burrow 30 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "4"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., tremorsense\
  \ 60 ft., passive Perception 9"
"languages": ""
"cr": "15"
"traits":
  - "desc": "The wurm can burrow through solid rock at half its burrow speed and leaves\
      \ a 10-foot-diameter tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The wurm makes two attacks: one with its bite and one with its stinger."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 19 Dexterity saving throw or be swallowed by the wurm.\
      \ A swallowed creature is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the wurm, and it takes 21\
      \ (6d6) acid damage at the start of each of the wurm's turns.\n\nIf the wurm\
      \ takes 30 damage or more on a single turn from a creature inside it, the wurm\
      \ must succeed on a DC 21 Constitution saving throw at the end of that turn\
      \ or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature\
      \ is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 20 feet of movement, exiting\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one creature. *Hit:*\
      \ 19 (3d6 + 9) piercing damage, and the target must make a DC 19 Constitution\
      \ saving throw, taking 42 (12d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Tail Stinger"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/wurm-psk.webp"
```
^statblock