---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/gos
  - Monster/HG/2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Koalinth Sergeant
---
# [Koalinth Sergeant](3-Mechanics\CLI\bestiary\humanoid/koalinth-sergeant-gos.md)
*Source: Ghosts of Saltmarsh p. 239*  

These fierce koalinths lead special missions for their people, such as the diplomatic envoy encountered in Danger at Dunwater. A koalinth sergeant focuses its ire on the most significant threats on the battlefield, then eliminates those threats one by one.

```statblock
"name": "Koalinth Sergeant (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "scale mail"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "11"
  - !!int "10"
  - !!int "12"
"speed": "30 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "2"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin"
"cr": "2"
"traits":
  - "desc": "The koalinth can breathe air and water."
    "name": "Amphibious"
  - "desc": "Once per turn, the sergeant can deal an extra 7 (2d6) damage to a creature\
      \ it hits with a weapon attack if that creature is within 5 feet of an ally\
      \ of the sergeant that isn't incapacitated."
    "name": "Martial Advantage"
"actions":
  - "desc": "The sergeant makes two melee attacks with its trident."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Trident"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 10/30 ft., one target. *Hit:*\
      \ 4 (1d4 + 2) piercing damage, and the target is restrained. A creature can\
      \ use its action to make a DC 12 Strength check to free itself or another creature\
      \ in a hooked net, ending the effect on a success. Dealing 5 slashing damage\
      \ to the net (AC 12) frees the target without harming it and destroys the net."
    "name": "Hooked Net"
"reactions":
  - "desc": "Whenever a creature within 30 feet of the sergeant becomes restrained,\
      \ the sergeant can move its speed toward the restrained creature. If the sergeant\
      \ ends its move within reach of the restrained creature, it can make a melee\
      \ attack against it."
    "name": "Spear the Helpless (2/Day)"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/koalinth-sergeant-gos.webp"
```
^statblock