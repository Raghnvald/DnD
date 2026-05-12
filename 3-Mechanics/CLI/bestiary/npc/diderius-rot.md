---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rot
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Diderius"
---
# [Diderius](3-Mechanics/CLI/bestiary/npc/diderius-rot.md)
*Source: The Rise of Tiamat p. 40, Tyranny of Dragons p. 131*  

```statblock
"name": "Diderius (RoT)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "18"
  - !!int "18"
  - !!int "16"
"speed": "20 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"damage_vulnerabilities": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "the languages it knew in life"
"cr": "15"
"traits":
  - "desc": "Diderius is a 10th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [minor illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
      \ [ray of frost](3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level\
      \ (4 slots):** [charm person](3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [shield](3-Mechanics/CLI/spells/shield-xphb.md),\
      \ [thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\n**2nd level (3\
      \ slots):** [cloud of daggers](3-Mechanics/CLI/spells/cloud-of-daggers-xphb.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [see invisibility](3-Mechanics/CLI/spells/see-invisibility-xphb.md)\n\
      \n**3rd level (3 slots):** [animate dead](3-Mechanics/CLI/spells/animate-dead-xphb.md),\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md)\n\n**4th level\
      \ (3 slots):** [fire shield](3-Mechanics/CLI/spells/fire-shield-xphb.md), [greater\
      \ invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md)\n\n**5th\
      \ level (2 slots):** [cloudkill](3-Mechanics/CLI/spells/cloudkill-xphb.md),\
      \ [wall of stone](3-Mechanics/CLI/spells/wall-of-stone-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Diderius has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "A destroyed mummy lord gains a new body in 24 hours if its heart is intact,\
      \ regaining all its hit points and becoming active again. The new body appears\
      \ within 5 feet of Diderius's heart."
    "name": "Rejuvenation"
"actions":
  - "desc": "The mummy can use its Dreadful Glare and makes one attack with its rotting\
      \ fist."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
      \ is a creature, it must succeed on a DC 16 Constitution saving throw or be\
      \ cursed with mummy rot. The cursed target can't regain hit points, and its\
      \ hit point maximum decreases by 10 (3d6) for every 24 hours that elapse.\
      \ If the curse reduces the target's hit point maximum to 0, the target dies,\
      \ and its body turns to dust. The curse lasts until removed by the [remove curse](3-Mechanics/CLI/spells/remove-curse-xphb.md)\
      \ spell or other magic."
    "name": "Rotting Fist"
  - "desc": "Diderius targets one creature it can see within 60 feet of it. If the\
      \ target can see Diderius, it must succeed on a DC 16 Wisdom saving throw against\
      \ this magic or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ until the end of the mummy's next turn. If the target fails the saving throw\
      \ by 5 or more, it is also [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ for the same duration. A target that succeeds on the saving throw is immune\
      \ to the Dreadful Glare of all mummies and mummy lords for the next 24 hours."
    "name": "Dreadful Glare"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Diderius can expend a use to take one of the following actions. Diderius\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Diderius makes one attack with its rotting fist or uses its Dreadful\
      \ Glare."
    "name": "Attack"
  - "desc": "Blinding dust and sand swirls magically around Diderius. Each creature\
      \ within 5 feet of Diderius must succeed on a DC 16 Constitution saving throw\
      \ or be [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) until the end\
      \ of the creature's next turn."
    "name": "Blinding Dust"
  - "desc": "Diderius utters a blasphemous word. Each non-undead creature within 10\
      \ feet of Diderius that can hear the magical utterance must succeed on a DC\
      \ 16 Constitution saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the end of Diderius's next turn."
    "name": "Blasphemous Word (Costs 2 Actions)"
  - "desc": "Diderius magically unleashes negative energy. Creatures within 60 feet\
      \ of Diderius, including ones behind barriers and around corners, can't regain\
      \ hit points until the end of Diderius's next turn."
    "name": "Channel Negative Energy (Costs 2 Actions)"
  - "desc": "Diderius magically transforms into a whirlwind of sand, moves up to 60\
      \ feet, and reverts to its normal form. While in whirlwind form, Diderius is\
      \ immune to all damage, and it can't be [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
      \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
      \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), or [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned).\
      \ Equipment worn or carried by Diderius remain in its possession."
    "name": "Whirlwind of Sand (Costs 2 Actions)"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/diderius-rot.webp"
```
^statblock