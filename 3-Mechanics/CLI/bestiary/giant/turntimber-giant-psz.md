---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Turntimber Giant"
---
# [Turntimber Giant](3-Mechanics/CLI/bestiary/giant/turntimber-giant-psz.md)
*Source: Plane Shift: Zendikar p. 30*  

Zendikar's giants are enormous humanoids that live in tight-knit tribes as far as possible from the settlements of other races. Compared to ogres and minotaurs, they are civilized and intelligent, though they are wilder than the smaller humanoid races.

Three major groupings of giants inhabit three of Zendikar's continents. In the mountains of Akoum, the giants of the Boulderfoot tribe have a well-earned reputation for trampling their enemies underfoot (hence their name). In the Skyfang Mountains of Murasa, the giants of the Shatterskull tribe are rough brigands who often extort "tolls" from travelers trying to navigate the treacherous pass that shares the tribe's name. The Boulderfoot and Shatterskull giants are [stone giants](3-Mechanics/CLI/bestiary/giant/stone-giant.md) in D&D terms.

In Ondu, the giants of the Turntimber tribe live in the forest of the same name. They hunt baloths and other large game, living in close harmony with the woodland. Their druids are the only giants of Zendikar that are inclined toward magic. Some legends hold that the Turntimber giants are unrelated to the other giant tribes, but were originally druids who became giants only after years of living among the twisted trees. Elsewhere on Ondu, in the Makindi Trenches, a handful of deformed giants called trench giants scale the canyon walls looking for prey. They are solitary and do not think of themselves as members of a tribe. In fact, they are outcasts of the Turntimber tribe, banished because the mana of the forest warped their bodies and their hearts. The giants of the Turntimber tribe are similar to [cloud giants](3-Mechanics/CLI/bestiary/giant/cloud-giant.md), and the trench giants can be considered [fomorians](3-Mechanics/CLI/bestiary/giant/fomorian.md).

```statblock
"name": "Turntimber Giant (PSZ)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Good or Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"modifier": !!int "0"
"stats":
  - !!int "27"
  - !!int "10"
  - !!int "22"
  - !!int "12"
  - !!int "16"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"gear":
  - "[morningstar](3-Mechanics/CLI/items/morningstar.md)"
"senses": "passive Perception 17"
"languages": "Common, Giant"
"cr": "9"
"traits":
  - "desc": "The giant's innate spellcasting ability is Charisma. It can innately\
      \ cast the following spells, requiring no material components:\n\n**At will:**\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [fog cloud](3-Mechanics/CLI/spells/fog-cloud.md),\
      \ [light](3-Mechanics/CLI/spells/light.md)\n\n**3/day each:** [feather fall](3-Mechanics/CLI/spells/feather-fall.md),\
      \ [fly](3-Mechanics/CLI/spells/fly.md), [misty step](3-Mechanics/CLI/spells/misty-step.md),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis.md)\n\n**1/day each:** [control\
      \ weather](3-Mechanics/CLI/spells/control-weather.md), [gaseous form](3-Mechanics/CLI/spells/gaseous-form.md)"
    "name": "Innate Spellcasting"
  - "desc": "The giant has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
"actions":
  - "desc": "The giant makes two morningstar attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (3d8 + 8) piercing damage."
    "name": "Morningstar"
  - "desc": "*Ranged Weapon Attack:* +12 to hit, range 60/240 ft., one target. *Hit:*\
      \ 30 (4d10 + 8) bludgeoning damage."
    "name": "Rock"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/giant/token/turntimber-giant-psz.webp"
```
^statblock