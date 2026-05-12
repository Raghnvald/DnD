---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Saleeth the Couatl"
---
# [Saleeth the Couatl](3-Mechanics/CLI/bestiary/npc/saleeth-the-couatl-awm.md)
*Source: Adventure with Muk p. 34*  

Saleeth is a wise and beautiful couatl that is very kind to polite and well-mannered goblins. If she is approached by adventurers, she may have a noble quest for them to undertake if they are ready to help her defend the world against the forces of evil.

```statblock
"name": "Saleeth the Couatl (AWM)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "97"
"modifier": !!int "5"
"stats":
  - !!int "16"
  - !!int "20"
  - !!int "17"
  - !!int "18"
  - !!int "20"
  - !!int "18"
"speed": "30 ft., fly 90 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The couatl's spellcasting ability is Charisma (spell save DC 14). It\
      \ can innately cast the following spells, requiring only verbal components:\n\
      \n**At will:** detect evil and good, detect magic, detect thoughts\n\n**3/day\
      \ each:** bless, create food and water, cure wounds, lesser restoration, protection\
      \ from poison, sanctuary, shield\n\n**1/day each:** dream, greater restoration,\
      \ scrying"
    "name": "Innate Spellcasting"
  - "desc": "The couatl's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "The couatl is immune to scrying and to any effect that would sense its\
      \ emotions, read its thoughts, or detect its location."
    "name": "Shielded Mind"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (1d6 + 5) piercing damage. Target must make a DC 13 Constitution save,\
      \ or fall unconscious. Another creature can use an action to shake the target\
      \ awake."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one Medium or smaller\
      \ creature. *Hit:* 10 (2d6 + 3) bludgeoning damage. Target is grappled (escape\
      \ DC 15). The couatl can constrain only one target at a time."
    "name": "Constrict"
  - "desc": "The couatl magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (the couatl's choice).\n\nIn a new form, the couatl\
      \ retains its game statistics and ability to speak, but its AC, movement modes,\
      \ Strength, Dexterity, and other actions are replaced by those of the new form,\
      \ and it gains any statistics and capabilities (except class features, legendary\
      \ actions, and lair actions) that the new form has but that it lacks. If the\
      \ new form has a bite attack, the couatl can use its bite in that form."
    "name": "Change Shape"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/npc/token/saleeth-the-couatl-awm.webp"
```
^statblock