---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rmbre
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Billy Beaver"
---
# [Billy Beaver](3-Mechanics/CLI/bestiary/npc/billy-beaver-rmbre.md)
*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 27*  

Billy Beaver is a goofy, owlbear-sized beaver with a raccoon-skin cap, playing a washboard and spoons.

The five automatons that serve as the tavern's wait staff each have a name tag, are super friendly to the patrons, and attend to everyone's needs until it comes time for the Slaughterfest. If an automaton is attacked before the Slaughterfest, it giggles and repeats folksy homilies until it is destroyed. The next round, it magically pops back to life fully healed, then asks, "What can I do for ya?"

```statblock
"name": "Billy Beaver (RMBRE)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "34"
"hit_dice": "7d10 + 21"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "17"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "Billy Beaver has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight or smell."
    "name": "Keen Sight and Smell"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (1d10 + 5) piercing damage."
    "name": "Beak"
"source":
  - "RMBRE"
"image": "3-Mechanics/CLI/bestiary/npc/token/billy-beaver-rmbre.webp"
```
^statblock