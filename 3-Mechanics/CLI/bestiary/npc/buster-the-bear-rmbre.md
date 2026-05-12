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
- "Buster the Bear"
---
# [Buster the Bear](3-Mechanics/CLI/bestiary/npc/buster-the-bear-rmbre.md)
*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 27*  

Buster the Bear is a lovable, roly-poly teddy bear with a plaid shirt, torn jeans, and a banjo.

The five automatons that serve as the tavern's wait staff each have a name tag, are super friendly to the patrons, and attend to everyone's needs until it comes time for the Slaughterfest. If an automaton is attacked before the Slaughterfest, it giggles and repeats folksy homilies until it is destroyed. The next round, it magically pops back to life fully healed, then asks, "What can I do for ya?"

```statblock
"name": "Buster the Bear (RMBRE)"
"size": "Medium"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "8"
  - !!int "11"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+2"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "1"
"traits":
  - "desc": "If Buster the Bear surprises a creature and hits it with an attack during\
      \ the first round of combat, the target takes an extra 7 (2d6) damage from\
      \ the attack."
    "name": "Surprise Attack"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) bludgeoning damage."
    "name": "Bashin' Banjo"
"source":
  - "RMBRE"
"image": "3-Mechanics/CLI/bestiary/npc/token/buster-the-bear-rmbre.webp"
```
^statblock