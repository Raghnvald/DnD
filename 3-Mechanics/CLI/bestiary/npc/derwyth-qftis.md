---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Derwyth"
---
# [Derwyth](3-Mechanics/CLI/bestiary/npc/derwyth-qftis.md)
*Source: Quests from the Infinite Staircase p. 52*  

Derwyth lives in Cernant Valley—a forested basin at the foot of the Tegefed Mountains—along with many animals, most of which are small woodland creatures. These animals act as Derwyth's eyes and ears, quickly bringing her news of events in the wood, particularly the arrival and actions of strangers. The creatures also carry messages to more powerful Beasts in the valley that sometimes come to Derwyth's aid.

```statblock
"name": "Derwyth (QftIS)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Good"
"ac": !!int "11"
"ac_class": "16 with [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[quarterstaff](3-Mechanics/CLI/items/quarterstaff.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60, passive Perception\
  \ 14"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "Derwyth is a 4th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). She has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame.md), [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)\n\
      \n**1st level (4 slots):** [entangle](3-Mechanics/CLI/spells/entangle.md), [longstrider](3-Mechanics/CLI/spells/longstrider.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\
      \n**2nd level (3 slots):** [animal messenger](3-Mechanics/CLI/spells/animal-messenger.md),\
      \ [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
    "name": "Spellcasting"
  - "desc": "Over the course of 1 minute, Derwyth can magically transform into a Huge\
      \ or smaller tree and remain in that form for 24 hours or until she ends this\
      \ transformation early (no action required). Her equipment melds into her new\
      \ form. While in this form, her Armor Class is 16, she has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, and she can't move or speak."
    "name": "Tree Shape (2/Day)"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit (+4 to hit with shillelagh), reach\
      \ 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
      \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with\
      \ shillelagh."
    "name": "Quarterstaff"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/derwyth-qftis.webp"
```
^statblock