---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mechachimera"
---
# [Mechachimera](3-Mechanics/CLI/bestiary/construct/mechachimera-oow.md)
*Source: The Orrery of the Wanderer p. 134*  

```statblock
"name": "Mechachimera (OoW)"
"size": "Large"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "19"
  - !!int "3"
  - !!int "14"
  - !!int "10"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_immunities": "poison, psychic"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 18"
"languages": "understands Draconic but can't speak"
"cr": "6"
"actions":
  - "desc": "The chimera makes three attacks: one with its bite, one with its horns,\
      \ and one with its claws. When its fire breath is available, it can use the\
      \ breath in place of its bite or horns."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) bludgeoning damage."
    "name": "Horns"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claws"
  - "desc": "The dragon head exhales fire in a 15-foot cone. Each creature in that\
      \ area must make a DC 15 Dexterity saving throw, taking 31 (7d8) fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"source":
  - "OoW"
"image": "3-Mechanics/CLI/bestiary/construct/token/mechachimera-oow.webp"
```
^statblock