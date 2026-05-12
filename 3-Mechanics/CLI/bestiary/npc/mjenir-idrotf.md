---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mjenir"
---
# [Mjenir](3-Mechanics/CLI/bestiary/npc/mjenir-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 215*  

With grand events having been set in motion, those sensitive to prophecy have begun to experience dreams and visions. One such person is Mjenir, a fifty-year-old shaman of the Reghed Elk Tribe, who received a vision about the characters' journey to the Reghed Glacier.

Druids dwell in forests and other secluded wilderness locations, where they protect the natural world from monsters and the encroachment of civilization. Some are tribal shamans who heal the sick, pray to animal spirits, and provide spiritual guidance.

```statblock
"name": "Mjenir (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
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
"senses": "passive Perception 14"
"languages": "Druidic plus any two languages"
"cr": "2"
"traits":
  - "desc": "Mjenir is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame.md), [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)\n\
      \n**1st level (4 slots):** [entangle](3-Mechanics/CLI/spells/entangle.md), [longstrider](3-Mechanics/CLI/spells/longstrider.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\
      \n**2nd level (3 slots):** [animal messenger](3-Mechanics/CLI/spells/animal-messenger.md),\
      \ [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit (+4 to hit with shillelagh), reach\
      \ 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
      \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with\
      \ [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)."
    "name": "Quarterstaff"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/npc/token/mjenir-idrotf.webp"
```
^statblock