---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Doric"
---
# [Doric](3-Mechanics/CLI/bestiary/npc/doric-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

The tiefling Doric was taken in by a wood elf enclave in Neverwinter Wood after being abandoned as a child, and she guards her adoptive community with nature's ferocity. The Circle of the Moon has taught her to heed her primal instincts, which rarely lead her astray. She can be brusque, but she will fight tooth and nail for a cause she believes in.

Doric has joined the Emerald Enclave, a network of survivalists who tend to the balance between civilization and nature. When the Lord of Neverwinter targeted her woodland home for its resources, Doric rallied the resistance.

```statblock
"name": "Doric (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Neutral Good"
"ac": !!int "14"
"ac_class": "leather armor"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "19"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Nature"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+7"
"damage_resistances": "fire"
"gear":
  - "sling"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Druidic, Elvish, Infernal, Sylvan"
"cr": "5"
"actions":
  - "desc": "Doric makes two Shaped Claw or Sling attacks. She can replace one attack\
      \ with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage."
    "name": "Shaped Claw"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 30/120 ft., one target. *Hit:*\
      \ 8 (2d4 + 3) bludgeoning damage."
    "name": "Sling"
  - "desc": "Doric casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** animal messenger, beast sense,\
      \ speak with animals\n\n**2/day each:** cure wounds, entangle, faerie fire,\
      \ thunderwave"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Doric magically transforms into a Beast with a challenge rating of 3\
      \ or less or into an owlbear (see the Monster Manual).\n\nDoric can remain in\
      \ that form for up to 2 hours. She can choose whether her equipment falls to\
      \ the ground, melds with her new form, or is worn by the new form. Doric reverts\
      \ to her true form if she is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ or dies. She can revert to her true form using a bonus action.\n\nWhile Doric\
      \ is transformed, her stat block is replaced by the stat block of that form,\
      \ except she keeps her current hit points, her hit point maximum, this bonus\
      \ action, her alignment, and her Intelligence, Wisdom, and Charisma scores."
    "name": "Change Shape (5/Day)"
"reactions":
  - "desc": "When Doric is damaged by a creature that she can see within 60 feet of\
      \ herself, she magically engulfs the creature in flames. The creature must make\
      \ a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage on failed save,\
      \ or half as much damage on a successful one."
    "name": "Fiery Rebuke (3/Day)"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/doric-hat-tg.webp"
```
^statblock