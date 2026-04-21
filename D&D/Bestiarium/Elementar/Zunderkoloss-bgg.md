---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Cinder Hulk
tags:
  - Monster/Größe/Groß
  - Monster/HG/7
  - Monster/Typ/Elementar
  - Quelle/5e/bgg
aliases:
  - Cinder Hulk
---
# [Cinder Hulk](3-Mechanics\CLI\bestiary\elemental/cinder-hulk-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 123*  

Cinder hulks are distant descendants of fire giants who isolated themselves from the world and steeped themselves in the energy of the Elemental Planes. Over the course of centuries, these giants were transformed into Elementals made of smoke and cinders. Half the size of their giant ancestors, cinder hulks maintain the basic physical shape of fire giants, but ash and embers billow around their barely cohesive physical forms.

Cinder hulks live in isolated enclaves in fiery locations on the Material Plane, in the Elemental Planes of Air and Fire, and especially in the Great Conflagration, the border region between those two planes. They retain none of the skills and motivation of their giant ancestors; they simply want to burn as much as they can until their own flames are extinguished. When a cinder hulk dies, it collapses into a billowing cloud of searing smoke.

```statblock
"name": "Cinder Hulk (BGG)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "20"
  - !!int "9"
  - !!int "14"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 15"
"languages": "Giant, Ignan"
"cr": "7"
"traits":
  - "desc": "When the cinder hulk dies, it leaves behind a cloud of cinders and smoke\
      \ that fills a 10-foot-radius sphere centered on its space. The sphere is heavily\
      \ obscured. Any creature that moves into the area for the first time on a turn\
      \ or starts its turn there must succeed on a DC 16 Constitution saving throw\
      \ or take 10 (3d6) fire damage. The cloud lasts for 1 minute or until it is\
      \ dispersed by strong wind."
    "name": "Death Burst"
"actions":
  - "desc": "The cinder hulk makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) bludgeoning damage plus 10 (3d6) fire damage."
    "name": "Slam"
  - "desc": "The cinder hulk emits a wave of smoldering ash from its face, hands,\
      \ or chest in a 30-foot cone. Each creature in that area must make a DC 16 Dexterity\
      \ saving throw. On a failed save, a creature takes 31 (7d8) fire damage and\
      \ has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded) condition until\
      \ the end of its next turn. On a successful save, a creature takes half as much\
      \ damage only."
    "name": "Wave of Cinders (Recharge 5-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cinder-hulk-bgg.webp"
```
^statblock