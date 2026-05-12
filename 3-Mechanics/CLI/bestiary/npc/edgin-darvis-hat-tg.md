---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Edgin Darvis"
---
# [Edgin Darvis](3-Mechanics/CLI/bestiary/npc/edgin-darvis-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Edgin Darvis has a talent for improvisation and strategy. He's a musician and tale-teller who relies on charisma first—rather than magic or muscle—to escape trouble. Once a member of the Harpers, a spy organization dedicated to protecting Faerûn's common folk, Edgin has forsworn his oath and turned to thievery to support his family. Edgin's strong moral compass compels him to steal only from people he believes deserve to lose both coin and face.

Edgin's confidence and rakish demeanor make him a natural leader. With carefully chosen words, he inspires the members of his thieves' crew to greatness. But when his past mistakes come calling, Edgin must face the music. He now seeks to make amends to those he's wronged and to confront those who have wronged him.

```statblock
"name": "Edgin Darvis (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"subtype": "bard"
"alignment": "Chaotic Good"
"ac": !!int "14"
"ac_class": "leather armor"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "Deception"
    "desc": "+7"
  - "name": "Performance"
    "desc": "+10"
  - "name": "Persuasion"
    "desc": "+10"
  - "name": "Sleight of Hand"
    "desc": "+6"
"gear":
  - "shortsword"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "5"
"actions":
  - "desc": "Edgin makes two Reinforced Lute or Shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) bludgeoning damage plus 11 (2d10) thunder damage."
    "name": "Reinforced Lute"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 11 (2d10) thunder damage."
    "name": "Shortsword"
  - "desc": "Edgin magically taunts up to three creatures he can see within 60 feet\
      \ of himself. Each creature must succeed on a DC 15 Wisdom saving throw or take\
      \ 10 (3d6) psychic damage and have disadvantage on the next attack roll it\
      \ makes before the start of Edgin's next turn."
    "name": "Disorienting Words"
  - "desc": "Edgin casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** friends, message\n\n**3/day each:**\
      \ charm person, disguise self\n\n**1/day:** suggestion"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature Edgin can see within 60 feet of himself fails an ability\
      \ check, an attack roll, or a saving throw, Edgin grants the creature magical\
      \ encouragement. The creature can roll a d8 and add the number rolled to the\
      \ total, potentially turning the failure into a success."
    "name": "Inspiring Words (3/Day)"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/edgin-darvis-hat-tg.webp"
```
^statblock