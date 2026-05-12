---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/cleric
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dermot Wurder (Tier 1)"
---
# [Dermot Wurder (Tier 1)](3-Mechanics/CLI/bestiary/npc/dermot-wurder-tier-1-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 188*  

When you're the twelfth son of a poor goblin family in Jigow, the only way to make a name for yourself is to become a great champion—someone who can win bragging contests in the local taverns night after night. Young Dermot Wurder, however, wasn't interested in performing feats of strength or agility that would win him a boast-worthy epithet. Fame wasn't for him, nor was the aggressiveness that becoming famous required. He was more interested in cooking, planting flowers, and sewing clothes—doing the work that kept his family together while his carefree siblings dove off waterfalls and wrestled stray dogs.

Dermot and Ayo Jabe have known each other long enough that their first meeting has vanished into the haze of youthful pre-memory. Dermot accompanied Ayo whenever he could, packing herbs and medicines when they went exploring in the woods. When Ayo recently told him of her dream to form an adventuring party, he started training to wear heavy armor and threw himself into studying the faith of the Luxon so he could wield the blessings of the light to protect those he cares about.

Dermot is fiercely protective of his friends and furiously rebukes anyone who disparages or threatens them. His deepest need—one even he doesn't know he has—is to make a friend who will help him realize what he wants for himself.

> [!note] Battle Chatter Sample Quotes
> 
> "I'm here to make sure no one dies. Back off!" "The Luxon will protect me." "Ayo, Maggie, I could use a little help here!"
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Dermot Wurder (Tier 1) |
| 3 and 4 | Dermot Wurder (Tier 2) |
| 5, 6, and 7 | Dermot Wurder (Tier 3) |
^chapters-stat-blocks

The tier 1 rivals are fledgling adventurers who have gained a modicum of power through their individual exploits before the beginning of this story. They are seeking to write a grand tale of their own.

```statblock
"name": "Dermot Wurder (Tier 1) (CRCotN)"
"size": "Small"
"type": "humanoid"
"subtype": "cleric, goblin, goblinoid"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "breastplate, shield"
"hp": !!int "44"
"hit_dice": "8d6 + 16"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "2"
"skillsaves":
  - "name": "Medicine"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+2"
  - "name": "Survival"
    "desc": "+5"
"gear":
  - "warhammer"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Goblin, Orc"
"cr": "3"
"actions":
  - "desc": "Dermot makes one Warhammer attack and one Searing Wrath attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage when\
      \ used with two hands."
    "name": "Warhammer"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one creature. *Hit:*\
      \ 9 (2d8) radiant damage, and the target is blinded until the end of its next\
      \ turn."
    "name": "Searing Wrath"
  - "desc": "Dermot casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** guidance, light, spare the dying\n\
      \n**1/day each:** bless, cure wounds"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/dermot-wurder-tier-1-crcotn.webp"
```
^statblock