---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ranger
- ttrpg-cli/monster/type/humanoid/water-genasi
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ayo Jabe (Tier 1)"
---
# [Ayo Jabe (Tier 1)](3-Mechanics/CLI/bestiary/npc/ayo-jabe-tier-1-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 188*  

As the de facto leader of a new, unnamed adventuring party, Ayo Jabe has a lot of responsibility on her shoulders. She and her companions have worked odd jobs around the town of Jigow for a few weeks now, and she's starting to feel confident that they're ready for real adventure.

Ayo is a water genasi who was born to orc parents during a terrible storm in the Emerald Gulch. Her family has lived in Jigow for generations, and she's eager to leave home and see the world.

Ayo picked up her combat skills while working as a hunter for the town of Jigow. She recently joined up with her childhood friend Dermot, as well as Maggie Keeneyes, a mercenary who came to town several weeks ago. Despite Maggie's brusque demeanor, she became a loyal friend of Ayo and Dermot, and the three of them have become inseparable, even as more adventurers have joined their party.

Ayo is hotheaded and appreciates people who make decisions as impulsively as she does. Nevertheless, she respects Dermot's even-tempered advice and dutifully plays the role of the wise leader. She has no patience for people who are indecisive, and she is infuriated by people who don't say what they really mean.

> [!note] Battle Chatter Sample Quotes
> 
> "Okay team, they're off-balance. Rally!" "Have you had enough?" "Yeah, just give up. You're finished."
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Ayo Jabe (Tier 1) |
| 3 and 4 | Ayo Jabe (Tier 2) |
| 5, 6, and 7 | Ayo Jabe (Tier 3) |
^chapters-stat-blocks

The tier 1 rivals are fledgling adventurers who have gained a modicum of power through their individual exploits before the beginning of this story. They are seeking to write a grand tale of their own.

```statblock
"name": "Ayo Jabe (Tier 1) (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "ranger, Water genasi"
"alignment": "Chaotic Good"
"ac": !!int "14"
"ac_class": "studded leather"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "4"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+3"
"damage_resistances": "acid"
"gear":
  - "longbow"
"senses": "passive Perception 13"
"languages": "Common, Goblin, Orc"
"cr": "3"
"traits":
  - "desc": "Ayo can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Ayo makes two Harpoon or Longbow attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d8 + 2) piercing damage."
    "name": "Harpoon"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target. *Hit:*\
      \ 11 (2d8 + 2) piercing damage."
    "name": "Longbow"
  - "desc": "Ayo casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 11):\n\n**1/day each:** animal friendship, goodberry"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/ayo-jabe-tier-1-crcotn.webp"
```
^statblock