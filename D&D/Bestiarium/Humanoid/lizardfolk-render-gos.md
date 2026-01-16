---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/gos
- new/monster/cr/3
- new/monster/size/large
- new/monster/type/humanoid/lizardfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Render
---
# [Lizardfolk Render](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-render-gos.md)
*Source: Ghosts of Saltmarsh p. 241, Storm Lord's Wrath*  

Filled with the primal magic of Semuanya, the lizardfolk render undergoes terrifying changes during a dayslong ritual performed by a shaman. As seen in Danger at Dunwater, the render's claws grow long and hard as steel, its frame enlarges, and its temperament becomes even more ferocious.

```statblock
"name": "Lizardfolk Render (GoS)"
"size": "Large"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "7"
  - !!int "12"
  - !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "3"
"traits":
  - "desc": "The render has advantage on melee attack rolls against any creature that\
      \ doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The render can hold its breath for 15 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The render makes two attacks: one with its claws and one with its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 12\
      \ (2d8 + 3) slashing damage."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "The render makes a claw attack against each creature of its choice within\
      \ 10 feet of it. A creature hit by this attack must succeed on a DC 13 Strength\
      \ saving throw or be knocked prone."
    "name": "Rend the Field (Recharge 5-6)"
"source":
  - "GoS"
  - "SLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-render-gos.webp"
```
^statblock