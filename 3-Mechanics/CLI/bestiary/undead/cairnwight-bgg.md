---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cairnwight"
---
# [Cairnwight](3-Mechanics/CLI/bestiary/undead/cairnwight-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 122*  

Stone giants believe the god Skoraeus Stonebones inspires artists to create their finest stone carvings. Sometimes a giant pursues this divine inspiration to the exclusion of all other tasks, retreating into a spacious cavern and blocking out all distractions. Creating a masterwork can become such a driving obsession that death can't stop it: a giant who dies while creating art might rise as a cairnwight and continue the work. Once the artwork is completed, the cairnwight remains as its undying guardian.

A cairnwight looks much like an emaciated stone giant. Its form is caked with lichens and mineral deposits, which help it blend with its cavern tomb. Should a creature attempt to interfere with the completion of the cairnwight's project, damage the art, or steal from the cairnwight, the giant petrifies the creature, places the resulting statue outside as a warning, then reseals its cavern vault.

```statblock
"name": "Cairnwight (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Neutral"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+8"
"condition_immunities": "charmed, exhaustion, frightened, petrified"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Giant"
"cr": "9"
"actions":
  - "desc": "The cairnwight makes two Slam attacks or two Rock attacks, and it uses\
      \ its Petrifying Touch if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d10 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/240 ft., one target. *Hit:*\
      \ 19 (3d8 + 6) bludgeoning damage, and the target must succeed on a DC 17\
      \ Strength saving throw or have the prone condition."
    "name": "Rock"
  - "desc": "The cairnwight touches one creature it can see within 10 feet of itself.\
      \ The target must succeed on a DC 17 Constitution saving throw or take 26 (4d12)\
      \ force damage and have the restrained condition as it begins to turn to stone.\
      \ The affected target must repeat the saving throw at the end of its next turn.\
      \ On a successful save, the effect ends on the target. On a failed save, the\
      \ target has the petrified condition instead of the restrained condition."
    "name": "Petrifying Touch (Recharge 5-6)"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/undead/token/cairnwight-bgg.webp"
```
^statblock