---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Boulderfoot Giant"
---
# [Boulderfoot Giant](3-Mechanics/CLI/bestiary/giant/boulderfoot-giant-psz.md)
*Source: Plane Shift: Zendikar p. 30*  

Zendikar's giants are enormous humanoids that live in tight-knit tribes as far as possible from the settlements of other races. Compared to ogres and minotaurs, they are civilized and intelligent, though they are wilder than the smaller humanoid races.

Three major groupings of giants inhabit three of Zendikar's continents. In the mountains of Akoum, the giants of the Boulderfoot tribe have a well-earned reputation for trampling their enemies underfoot (hence their name). In the Skyfang Mountains of Murasa, the giants of the Shatterskull tribe are rough brigands who often extort "tolls" from travelers trying to navigate the treacherous pass that shares the tribe's name. The Boulderfoot and Shatterskull giants are [stone giants](3-Mechanics/CLI/bestiary/giant/stone-giant.md) in D&D terms.

In Ondu, the giants of the Turntimber tribe live in the forest of the same name. They hunt baloths and other large game, living in close harmony with the woodland. Their druids are the only giants of Zendikar that are inclined toward magic. Some legends hold that the Turntimber giants are unrelated to the other giant tribes, but were originally druids who became giants only after years of living among the twisted trees. Elsewhere on Ondu, in the Makindi Trenches, a handful of deformed giants called trench giants scale the canyon walls looking for prey. They are solitary and do not think of themselves as members of a tribe. In fact, they are outcasts of the Turntimber tribe, banished because the mana of the forest warped their bodies and their hearts. The giants of the Turntimber tribe are similar to [cloud giants](3-Mechanics/CLI/bestiary/giant/cloud-giant.md), and the trench giants can be considered [fomorians](3-Mechanics/CLI/bestiary/giant/fomorian.md).

```statblock
"name": "Boulderfoot Giant (PSZ)"
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
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/giant/token/boulderfoot-giant-psz.webp"
```
^statblock