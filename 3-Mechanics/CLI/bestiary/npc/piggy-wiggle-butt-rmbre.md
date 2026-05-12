---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rmbre
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Piggy Wiggle Butt"
---
# [Piggy Wiggle Butt](3-Mechanics/CLI/bestiary/npc/piggy-wiggle-butt-rmbre.md)
*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 28*  

Piggy Wiggle Butt is an anthropomorphic pig with no pants and no butt. She plays a clay jug and dances.

The five automatons that serve as the tavern's wait staff each have a name tag, are super friendly to the patrons, and attend to everyone's needs until it comes time for the Slaughterfest. If an automaton is attacked before the Slaughterfest, it giggles and repeats folksy homilies until it is destroyed. The next round, it magically pops back to life fully healed, then asks, "What can I do for ya?"

```statblock
"name": "Piggy Wiggle Butt (RMBRE)"
"size": "Medium"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "16"
  - !!int "7"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+2"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "As a bonus action, Piggy Wiggle Butt can move up to its speed toward\
      \ a hostile creature that it can see."
    "name": "Aggressive"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage."
    "name": "Clay Jug"
"source":
  - "RMBRE"
"image": "3-Mechanics/CLI/bestiary/npc/token/piggy-wiggle-butt-rmbre.webp"
```
^statblock