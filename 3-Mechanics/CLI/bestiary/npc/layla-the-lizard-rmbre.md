---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rmbre
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Layla the Lizard"
---
# [Layla the Lizard](3-Mechanics/CLI/bestiary/npc/layla-the-lizard-rmbre.md)
*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 28*  

Layla the Lizard has blue overalls, a guitar, and a straw hat.

The five automatons that serve as the tavern's wait staff each have a name tag, are super friendly to the patrons, and attend to everyone's needs until it comes time for the Slaughterfest. If an automaton is attacked before the Slaughterfest, it giggles and repeats folksy homilies until it is destroyed. The next round, it magically pops back to life fully healed, then asks, "What can I do for ya?"

```statblock
"name": "Layla the Lizard (RMBRE)"
"size": "Medium"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one creature. *Hit:*\
      \ 9 (2d6 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d4 + 2) slashing damage."
    "name": "Claws"
"source":
  - "RMBRE"
"image": "3-Mechanics/CLI/bestiary/npc/token/layla-the-lizard-rmbre.webp"
```
^statblock