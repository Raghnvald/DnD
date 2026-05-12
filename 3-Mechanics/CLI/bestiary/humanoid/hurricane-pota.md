---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hurricane"
---
# [Hurricane](3-Mechanics/CLI/bestiary/humanoid/hurricane-pota.md)
*Source: Princes of the Apocalypse p. 191*  

Hurricanes profess their disgust with decadence, and they dedicate their bodies and their minds to the world's destruction. Through breathing exercises and ascetic philosophy, skilled Howling Hatred initiates learn to imitate the cycling patterns of the hurricane. They believe the physical world must be shattered so that the creatures of the Material Plane can live unshackled by physical things.

Hurricanes see the frenetic activity of the world in slow motion, and themselves at the calm center of the storm. Through meditation and mysticism they learn to summon powerful blasts of wind, catch missiles with ease, and fall like feathers.

```statblock
"name": "Hurricane (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "45 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Auran, Common"
"cr": "2"
"traits":
  - "desc": "The hurricane is a 3rd-level spellcaster. Its spellcasting ability is\
      \ Wisdom (spell save DC 11, +3 to hit with spell attacks). It knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [blade ward](3-Mechanics/CLI/spells/blade-ward.md),\
      \ gust, [light](3-Mechanics/CLI/spells/light.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1st level (4 slots):** [feather fall](3-Mechanics/CLI/spells/feather-fall.md),\
      \ [jump](3-Mechanics/CLI/spells/jump.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\
      \n**2nd level (2 slots):** [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md)"
    "name": "Spellcasting"
  - "desc": "While the hurricane is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Unarmored Defense"
  - "desc": "While the hurricane is wearing no armor and wielding no shield, its walking\
      \ speed increases by 15 feet (included in its speed)."
    "name": "Unarmored Movement"
"actions":
  - "desc": "The hurricane makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "When the hurricane is hit by a ranged weapon attack, it reduces the damage\
      \ from the attack by 1d10 + 9. If the damage is reduced to 0, the hurricane\
      \ can catch the missile if it is small enough to hold in one hand and the hurricane\
      \ has at least one hand free."
    "name": "Deflect Missiles"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/hurricane-pota.webp"
```
^statblock