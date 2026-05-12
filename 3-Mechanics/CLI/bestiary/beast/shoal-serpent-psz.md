---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shoal Serpent"
---
# [Shoal Serpent](3-Mechanics/CLI/bestiary/beast/shoal-serpent-psz.md)
*Source: Plane Shift: Zendikar p. 26*  

The oceans, bays, and swamps of Zendikar are home to a variety of aquatic creatures that are at least as deadly as those on land, including monstrosities that can face the largest Eldrazi on almost equal footing. Given the dangers of Zendikar, even mundane animals such as octopuses, frogs, turtles, crabs, and crocodiles can grow to tremendous size (using the appropriate statistics from appendix A of the Monster Manual). The crabs of Ondu, the crocodiles of Guul Draz, the tortoises of Tazeem, and the octopuses of the deep sea (of which Lorthos the Tidemaker is but one giant specimen) are examples of these aquatic monstrosities. Enormous shoal serpents—sometimes compared to "a reef that runs aground on ships"—are a persistent danger to vessels along the Onduan coast. The [plesiosaurus](3-Mechanics/CLI/bestiary/beast/plesiosaurus.md) in the Monster Manual can represent these serpents.

```statblock
"name": "Shoal Serpent (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "20 ft., swim 40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The serpent can hold its breath for 1 hour."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:*\
      \ 14 (3d6 + 4) piercing damage."
    "name": "Bite"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/shoal-serpent-psz.webp"
```
^statblock