---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Druid of the Old Ways
---
# [Druid of the Old Ways](3-Mechanics\CLI\bestiary\humanoid/druid-of-the-old-ways-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 239*  

The druids of the Old Ways are the keepers of ancient Gruul traditions devoted to the primal ferocity of animal gods such as Ilharg the Raze-Boar and Kashath the Stalker.

## The End-Raze

The druids of the Old Ways believe that civilization will never be eradicated by scattered raids and petty skirmishes. They cling to the idea of a coming apocalypse, the End-Raze, when Ilharg's hoofs will trample every brick and stone of Ravnica's soaring skylines to rubble. The world will return to a state of nature in which the lawless code of muscle and savagery will reign once again.

```statblock
"name": "Druid of the Old Ways (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "16"
  - !!int "10"
  - !!int "20"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+8"
"senses": "passive Perception 18"
"languages": "Common, Druidic"
"cr": "7"
"traits":
  - "desc": "The druid is a 12th-level Gruul spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 16, +8 to hit with spell attacks). It has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](/3-Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [produce flame](/3-Mechanics/CLI/spells/produce-flame-xphb.md), [resistance](/3-Mechanics/CLI/spells/resistance-xphb.md),\
      \ [thorn whip](/3-Mechanics/CLI/spells/thorn-whip-xphb.md)\n\n**1st level (4\
      \ slots):** [cure wounds](/3-Mechanics/CLI/spells/cure-wounds-xphb.md), [faerie\
      \ fire](/3-Mechanics/CLI/spells/faerie-fire-xphb.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\
      \n**2nd level (3 slots):** [beast sense](/3-Mechanics/CLI/spells/beast-sense-xphb.md),\
      \ [flame blade](/3-Mechanics/CLI/spells/flame-blade-xphb.md), [pass without\
      \ trace](/3-Mechanics/CLI/spells/pass-without-trace-xphb.md)\n\n**3rd level\
      \ (3 slots):** [conjure animals](/3-Mechanics/CLI/spells/conjure-animals-xphb.md),\
      \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md), [plant growth](/3-Mechanics/CLI/spells/plant-growth-xphb.md)\n\
      \n**4th level (3 slots):** [dominate beast](/3-Mechanics/CLI/spells/dominate-beast-xphb.md),\
      \ [freedom of movement](/3-Mechanics/CLI/spells/freedom-of-movement-xphb.md),\
      \ [wall of fire](/3-Mechanics/CLI/spells/wall-of-fire-xphb.md)\n\n**5th level\
      \ (2 slots):** [commune with nature](/3-Mechanics/CLI/spells/commune-with-nature-xphb.md),\
      \ [conjure elemental](/3-Mechanics/CLI/spells/conjure-elemental-xphb.md), [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)\n\
      \n**6th level (1 slots):** [transport via plants](/3-Mechanics/CLI/spells/transport-via-plants-xphb.md),\
      \ [wall of thorns](/3-Mechanics/CLI/spells/wall-of-thorns-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The druid deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "The druid can communicate with beasts and plants as if they shared a\
      \ language."
    "name": "Speak with Beasts and Plants"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6)\
      \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
    "name": "Quarterstaff"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/druid-of-the-old-ways-ggr.webp"
```
^statblock