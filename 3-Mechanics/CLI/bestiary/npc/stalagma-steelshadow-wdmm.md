---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Stalagma Steelshadow"
---
# [Stalagma Steelshadow](3-Mechanics/CLI/bestiary/npc/stalagma-steelshadow-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 273*  

```statblock
"name": "Stalagma Steelshadow (WDMM)"
"size": "Huge"
"type": "dragon"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d12 + 126"
"modifier": !!int "0"
"stats":
  - !!int "27"
  - !!int "10"
  - !!int "25"
  - !!int "16"
  - !!int "13"
  - !!int "21"
"speed": "40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "12"
  - "wisdom": !!int "6"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "cold"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 21"
"languages": "Draconic, Dwarvish, Terran"
"cr": "16"
"traits":
  - "desc": "If Stalagma fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "Stalagma can use its Frightful Presence. It then makes three attacks:\
      \ one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:*\
      \ 19 (2d10 + 8) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:*\
      \ 15 (2d6 + 8) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:*\
      \ 17 (2d8 + 8) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of Stalagma's choice that is within 120 feet of Stalagma\
      \ and aware of it must succeed on a DC 18 Wisdom saving throw or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Stalagma's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "The dragon uses one of the following breath weapons.\n\n- **Acid Breath.**\
      \ The dragon exhales acid in a 60-foot line that is 5 feet wide. Each creature\
      \ in that line must make a DC 18 Dexterity saving throw, taking 58 (13d8)\
      \ acid damage on a failed save, or half as much damage on a successful one.\
      \  \n- **Paralyzing Breath.** The dragon exhales paralyzing gas in a 60-foot\
      \ cone. Each creature in that area must succeed on a DC 20 Constitution saving\
      \ throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) for\
      \ 1 minute. A creature can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success.  "
    "name": "Breath Weapons (Recharge 5-6)"
  - "desc": "Stalagma magically polymorphs into a humanoid or beast that has a challenge\
      \ rating no higher than its own, or back into its true form. It reverts to its\
      \ true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (Stalagma's choice).\n\nIn a new form, Stalagma retains\
      \ its alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary\
      \ Resistance, lair actions, and Intelligence, Wisdom, and Charisma scores, as\
      \ well as this action. Its statistics and capabilities are otherwise replaced\
      \ by those of the new form, except any class features or legendary actions of\
      \ that form."
    "name": "Change Shape"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Stalagma can expend a use to take one of the following actions. Stalagma\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Stalagma makes a Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "Stalagma makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Stalagma beats its wings. Each creature within 10 feet of Stalagma must\
      \ succeed on a DC 22 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
      \ damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ Stalagma can then fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/stalagma-steelshadow-wdmm.webp"
```
^statblock