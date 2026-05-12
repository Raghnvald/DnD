---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/esk
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spellcaster"
---
# [Spellcaster](3-Mechanics/CLI/bestiary/humanoid/spellcaster-esk.md)
*Source: Essentials Kit p. 63*  

```statblock
"name": "Spellcaster (ESK)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "leather armor"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "15"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+4"
  - "name": "Investigation"
    "desc": "+4"
  - "name": "Religion"
    "desc": "+4"
"gear":
  - "quarterstaff"
"senses": "passive Perception 12"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The spellcaster's spellcasting ability is Intelligence (spell save DC\
      \ 12, +4 to hit with spell attacks). The spellcaster has following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** fire bolt, light\n\n**1st level\
      \ (2 slots):** sleep"
    "name": "Spellcasting (Mage)"
  - "desc": "The spellcaster's spellcasting ability is Wisdom (spell save DC 12, +4\
      \ to hit with spell attacks). The spellcaster has following cleric spells prepared:\n\
      \n**Cantrips (at will):** guidance, sacred flame\n\n**1st level (2 slots):**\
      \ cure wounds"
    "name": "Spellcasting (Healer)"
  - "desc": "Choose a role for the spellcaster: healer or mage. Your choice determines\
      \ which Spellcasting trait to use below."
    "name": "Magical Role"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"source":
  - "ESK"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/spellcaster-esk.webp"
```
^statblock