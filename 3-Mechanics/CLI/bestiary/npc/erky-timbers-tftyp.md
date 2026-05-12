---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Erky Timbers"
---
# [Erky Timbers](3-Mechanics/CLI/bestiary/npc/erky-timbers-tftyp.md)
*Source: Tales from the Yawning Portal p. 22*  

Acolytes are junior members of a clergy, usually answerable to a priest. They perform a variety of functions in a temple and are granted minor spellcasting power by their deities.

```statblock
"name": "Erky Timbers (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "17"
"hit_dice": "5d6"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[club](3-Mechanics/CLI/items/club-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "Common, Draconic, Gnomish, Goblin"
"cr": "1/4"
"traits":
  - "desc": "The acolyte is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). The acolyte has following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (3 slots):** [bless](3-Mechanics/CLI/spells/bless-xphb.md), [cure\
      \ wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d4) bludgeoning damage."
    "name": "Club"
  - "desc": "Erky presents his holy Symbol and speaks a prayer censuring the Undead.\
      \ Each Undead that can see or hear Erky within 30 feet of him must make a DC\
      \ 12 Wisdom saving throw. If the creature fails its saving throw, it is turned\
      \ for 1 minute or until it takes any damage.\n\nA turned creature must spend\
      \ its turns trying to move as far away from Erky as it can, and it can't willingly\
      \ move to a space within 30 feet of him. It also can't take reactions. For its\
      \ action, it can use only the [Dash](3-Mechanics/CLI/rules/actions.md#Dash)\
      \ action or try to escape from an effect that prevents it from moving. If there's\
      \ nowhere to move, the creature can use the [Dodge](3-Mechanics/CLI/rules/actions.md#Dodge)\
      \ action."
    "name": "Channel Divinity: Turn Undead (1/Short Rest)"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/npc/token/erky-timbers-tftyp.webp"
```
^statblock