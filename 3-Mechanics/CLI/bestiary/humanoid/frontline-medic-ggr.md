---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Frontline Medic
---
# [Frontline Medic](3-Mechanics\CLI\bestiary\humanoid/frontline-medic-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

The soldiers of the Boros Legion depend on skilled healers to keep them on their feet. Frontline medics use a mix of magical healing and mundane medicine to keep their compatriots alive.

```statblock
"name": "Frontline Medic (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "20"
"ac_class": "[plate armor](/3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
  - "desc": "The medic is a 3rd-level Boros spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 11). The medic has the following cleric spells prepared:\n\
      \n**Cantrips (at will):** [mending](/3-Mechanics/CLI/spells/mending-xphb.md),\
      \ [resistance](/3-Mechanics/CLI/spells/resistance-xphb.md), [spare the dying](/3-Mechanics/CLI/spells/spare-the-dying-xphb.md)\n\
      \n**1st level (4 slots):** [cure wounds](/3-Mechanics/CLI/spells/cure-wounds-xphb.md),\
      \ [sanctuary](/3-Mechanics/CLI/spells/sanctuary-xphb.md)\n\n**2nd level (2 slots):**\
      \ [aid](/3-Mechanics/CLI/spells/aid-xphb.md), [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/frontline-medic-ggr.webp"
```
^statblock