---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "River Serpent"
---
# [River Serpent](3-Mechanics/CLI/bestiary/beast/river-serpent-psa.md)
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](3-Mechanics/CLI/bestiary/beast/crocodile.md) and [hippopotamuses](3-Mechanics/CLI/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](3-Mechanics/CLI/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](3-Mechanics/CLI/bestiary/beast/quipper.md), [giant frogs](3-Mechanics/CLI/bestiary/beast/giant-frog.md), and [crocodiles](3-Mechanics/CLI/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](3-Mechanics/CLI/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](3-Mechanics/CLI/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```statblock
"name": "River Serpent (PSA)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "60"
"hit_dice": "8d12 + 8"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "12"
  - !!int "1"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "2"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one creature. *Hit:*\
      \ 11 (2d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:*\
      \ 13 (2d8 + 4) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16). Until this grapple ends, the creature is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the serpent can't constrict another target."
    "name": "Constrict"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/beast/token/river-serpent-psa.webp"
```
^statblock