---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mismv1
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rain"
---
# [Rain](3-Mechanics/CLI/bestiary/npc/rain-mismv1.md)
*Source: Misplaced Monsters: Volume 1 p. 8*  

> [!note]
> Created by Kenzie C.

Rain lives in happy meadows atop clouds, away from all the evil of the world. She loves cupcakes and readily accepts them as gifts. She has fiery wings and a tiny halo around the tip of her horn. When confronted by bullies or evildoers, she can emit rainbow-colored positive energy from her haloed horn. Rain uses her rainbows to heal friendly creatures and punish evildoers, transforming the latter into glittering flowers.

```statblock
"name": "Rain (MisMV1)"
"size": "Small"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "11d6 + 22"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "14"
  - !!int "14"
  - !!int "18"
  - !!int "15"
"speed": "30 ft., fly 120 ft."
"saves":
  - "dexterity": !!int "3"
  - "constitution": !!int "5"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+3"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison, radiant"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 14"
"languages": "Celestial, Common"
"cr": "5"
"traits":
  - "desc": "Rain's wings are made of flame, and they shed bright light out to 15\
      \ feet and dim light for an additional 15 feet. At the start of each of Rain's\
      \ turns, each creature of Rain's choice within 5 feet of her takes 3 (1d6)\
      \ fire damage. A creature that hits Rain with a melee attack takes 3 (1d6)\
      \ fire damage."
    "name": "Fiery Wings"
  - "desc": "Rain has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Rain makes two Hoof attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (2d4) bludgeoning damage."
    "name": "Hoof"
  - "desc": "Rain uses her haloed horn to produce one of the following magical effects:"
    "name": "Haloed Horn Burst (Recharge 5-6)"
  - "desc": "Rain emits a rainbow beam in a 30-foot line that is 5 feet wide. Each\
      \ creature in that area must make a DC 15 Dexterity saving throw, taking 21\
      \ (6d6) radiant damage on a failed saving throw, or half as much damage on\
      \ a successful one; creatures of evil alignment have disadvantage on this saving\
      \ throw. If the damage from this effect reduces a creature to 0 hit points,\
      \ the creature dies, and its body turns into glittery flowers."
    "name": "Glitterstorm"
  - "desc": "Rain releases a wave of rejuvenating multicolored light in a 30-foot\
      \ cone. Each creature of Rain's choice in that area regains 18 (4d8) hit points."
    "name": "Healing Rainbows"
"bonus_actions":
  - "desc": "Rain takes either the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or the [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Nimble Escape"
"source":
  - "MisMV1"
"image": "3-Mechanics/CLI/bestiary/npc/token/rain-mismv1.webp"
```
^statblock