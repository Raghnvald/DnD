---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/sorcerer
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Simon Aumar"
---
# [Simon Aumar](3-Mechanics/CLI/bestiary/npc/simon-aumar-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Simon Aumar suffers under the weight of his family name. Though he is a descendent of an elf and the legendary wizard Elminster Aumar, Simon's own sorcerous wild magic runs uncontrolled through his veins. Simon has not yet developed the ability to harness his power, and his spells explode or fizzle seemingly at random.

Though he's dogged by doubt, the brave young mage has earned his place in Edgin's crew. He performs best under pressure, instinctively unleashing his magic in dire moments. How he will continue to unlock his potential and what he will do with his volatile gift are yet to be seen.

```statblock
"name": "Simon Aumar (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"subtype": "sorcerer"
"alignment": "Chaotic Good"
"ac": !!int "12"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "13"
  - !!int "16"
  - !!int "12"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "Deception"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
  - "name": "Religion"
    "desc": "+6"
  - "name": "Survival"
    "desc": "+4"
"gear":
  - "quarterstaff"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Draconic, Elvish"
"cr": "5"
"traits":
  - "desc": "Simon has advantage on saving throws he makes to avoid or end the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition on himself, and magic can't put him to sleep."
    "name": "Fey Ancestry"
  - "desc": "Simon carries a bag of holding, two pairs of sending stones, and a deathly\
      \ token (see Spellcasting)."
    "name": "Special Equipment"
  - "desc": "When Simon takes 20 or more damage from a single source or takes damage\
      \ from a critical hit, he must roll on the Wild Magic Surge table in the Player's\
      \ Handbook."
    "name": "Wild Magic"
"actions":
  - "desc": "Simon makes three Quarterstaff or Chaos Bolt attacks. He can replace\
      \ one attack with one use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used\
      \ with two hands, plus 11 (2d10) force damage."
    "name": "Quarterstaff"
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 60 ft., one target. *Hit:*\
      \ 14 (2d10 + 3) damage of a random type determined by rolling a d8: 1, acid;\
      \ 2, cold; 3, fire; 4, force; 5, lightning; 6, poison; 7, psychic; 8, thunder."
    "name": "Chaos Bolt"
  - "desc": "Roll a d6. On a roll of 1, Simon must roll on the Wild Magic Surge\
      \ table in the Player's Handbook. On a roll of 2 or higher, Simon casts one\
      \ of the following spells, using Charisma as the spellcasting ability (spell\
      \ save DC 14):\n\n**At will:** mage hand, minor illusion, prestidigitation,\
      \ speak with dead (Simon must be holding his deathly token to cast this spell)\n\
      \n**2/day each:** fog cloud, mage armor, magic missile, spider climb\n\n**1/day\
      \ each:** Bigby's hand, major image"
    "name": "Spellcasting"
"reactions":
  - "desc": "When Simon or another creature he can see within 10 feet of himself would\
      \ take damage, he conjures a shimmering, 10-foot-radius sphere of magical force\
      \ centered on himself. Creatures inside the sphere have resistance to the damage\
      \ that triggered this reaction."
    "name": "Sheltering Shield (3/Day)"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/simon-aumar-hat-tg.webp"
```
^statblock