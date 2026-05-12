---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Doomguard Rot Blade"
---
# [Doomguard Rot Blade](3-Mechanics/CLI/bestiary/humanoid/doomguard-rot-blade-mpp.md)
*Source: Morte's Planar Parade p. 56*  

Rot blades are the entropic levers through which the Doomguard quickens the natural decay of the multiverse. These members wield weapons immersed in necrotic energy, which can turn their enemies to ash.

```statblock
"name": "Doomguard Rot Blade (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "necrotic"
"senses": "passive Perception 13"
"languages": "Common plus two more languages"
"cr": "6"
"actions":
  - "desc": "The rot blade makes two Entropic Blade or Entropic Javelin attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) slashing damage plus 7 (2d6) necrotic damage. A creature killed\
      \ by this attack has its body and everything it is wearing or carrying, except\
      \ for magic items, reduced to ash. *Hit or Miss:* The rot blade can cause the\
      \ blade to emit a burst of entropic magic in a 10-foot-radius sphere centered\
      \ on the weapon. Each creature in that area other than the rot blade must succeed\
      \ on a DC 13 Constitution saving throw or take 6 (1d12) necrotic damage. The\
      \ blade can emit entropic magic in this way only once per turn."
    "name": "Entropic Blade"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 13 (2d12) necrotic\
      \ damage. A creature killed by this attack has its body and everything it is\
      \ wearing or carrying, except for magic items, reduced to ash."
    "name": "Entropic Javelin"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/doomguard-rot-blade-mpp.webp"
```
^statblock