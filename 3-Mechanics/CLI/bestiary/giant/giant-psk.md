---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant"
---
# [Giant](3-Mechanics/CLI/bestiary/giant/giant-psk.md)
*Source: Plane Shift: Kaladesh p. 30*  

Standing twenty to thirty feet tall, giants are towering bipedal creatures that follow the flow of aether on regular migratory routes. Once they start moving, they build both momentum and a single-mindedness that makes them nearly impossible to stop. Anything in their path, whether it's a building or a force of soldiers, is crushed without thought.

Giants eat whatever they happen across in the course of their migrations, which includes many other creatures drawn to the aether flow. They are beings of pure aggressive instinct, but without a hint of malice. In all likelihood, giants aren't intelligent enough to wish harm on anyone or anything. Still, the combination of their regular migrations and their sheer destructive power makes these creatures a menace.

Any structure built along one of their migratory paths is sure to be destroyed unless special accommodations are made. The zone of Giant's Walk in Ghirapur was designed by the city's engineers and edificers to include such accommodations, including rotating platforms, shifting bridges, and adjustable canal locks that provide the giants a clear and easy pathway during their biannual migration through the city.

The [stone giant](3-Mechanics/CLI/bestiary/giant/stone-giant.md) statistics in the Monster Manual work well for the giants of Kaladesh.

```statblock
"name": "Giant (PSK)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[greatclub](3-Mechanics/CLI/items/greatclub.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Giant"
"cr": "7"
"traits":
  - "desc": "The giant has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks made to hide in rocky terrain."
    "name": "Stone Camouflage"
"actions":
  - "desc": "The giant makes two greatclub attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 15 ft., one target. *Hit:*\
      \ 19 (3d8 + 6) bludgeoning damage."
    "name": "Greatclub"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Rock"
"reactions":
  - "desc": "If a rock or similar object is hurled at the giant, the giant can, with\
      \ a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning\
      \ damage from it."
    "name": "Rock Catching"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/giant/token/giant-psk.webp"
```
^statblock