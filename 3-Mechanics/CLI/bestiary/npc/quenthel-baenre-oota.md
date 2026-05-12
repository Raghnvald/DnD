---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Quenthel Baenre"
---
# [Quenthel Baenre](3-Mechanics/CLI/bestiary/npc/quenthel-baenre-oota.md)
*Source: Out of the Abyss p. 204*  

```statblock
"name": "Quenthel Baenre (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "+3 scale mail"
"hp": !!int "132"
"hit_dice": "24d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "18"
  - !!int "20"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "12"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+11"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+9"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Elvish, Undercommon"
"cr": "22"
"traits":
  - "desc": "Quenthel is a 20th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (save DC 20, +12 to hit with spell attacks). Quenthel can cast any cleric\
      \ spell up to 9th level at will.\n"
    "name": "Spellcasting"
  - "desc": "Quenthel's spellcasting ability is Charisma (spell save DC 19). She can\
      \ innately cast the following spells, requiring no material components:\n\n\
      **At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights.md)\n\n\
      **1/day each:** [darkness](3-Mechanics/CLI/spells/darkness.md), [faerie fire](3-Mechanics/CLI/spells/faerie-fire.md),\
      \ [levitate](3-Mechanics/CLI/spells/levitate.md) (self only)"
    "name": "Innate Spellcasting"
  - "desc": "Quenthel has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put Quenthel to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, Quenthel has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "Quenthel wields a tentacle rod."
    "name": "Special Equipment"
"actions":
  - "desc": "Quenthel makes three tentacle rod attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage plus 17 (5d6) poison damage."
    "name": "Scourge"
  - "desc": "Quenthel attempts to magically summon a [yochlol](3-Mechanics/CLI/bestiary/fiend/yochlol.md)\
      \ with a 30 percent chance of success. If the attempt fails, Quenthel takes\
      \ 5 (1d10) psychic damage. Otherwise, the summoned demon appears in an unoccupied\
      \ space within 60 feet of its summoner, acts as an ally of its summoner, and\
      \ can't summon other demons. It remains for 10 minutes, until it or its summoner\
      \ dies, or until its summoner dismisses it as an action."
    "name": "Summon Demon (1/Day)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage. If she hits a target with all three tentacles,\
      \ it must make a DC 15 Constitution saving throw. On a failure, the creature's\
      \ speed is halved, it has disadvantage on Dexterity saving throws, and it can't\
      \ use reactions for 1 minute. Moreover, on each of its turns, it can take either\
      \ an action or a bonus action, but not both. At the end of each of its turns,\
      \ it can repeat the saving throw, ending the effect on itself on a success."
    "name": "Tentacle Rod"
  - "desc": "While seated on her throne, Quenthel can use an action on her turn to\
      \ cast [disintegrate](3-Mechanics/CLI/spells/disintegrate.md) (save DC 19).\
      \ A target that fails its saving throw takes 10d6 + 40 force damage. If this\
      \ damage reduces the target to 0 hit points, it is disintegrated."
    "name": "Throne Activation"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/quenthel-baenre-oota.webp"
```
^statblock