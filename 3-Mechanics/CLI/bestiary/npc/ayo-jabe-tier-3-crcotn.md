---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ranger
- ttrpg-cli/monster/type/humanoid/water-genasi
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ayo Jabe (Tier 3)"
---
# [Ayo Jabe (Tier 3)](3-Mechanics/CLI/bestiary/npc/ayo-jabe-tier-3-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 192*  

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

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `1d4` levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

```statblock
"name": "Ayo Jabe (Tier 3) (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "ranger, Water genasi"
"alignment": "Chaotic Good"
"ac": !!int "17"
"ac_class": "studded leather"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "5"
"stats":
  - !!int "16"
  - !!int "20"
  - !!int "16"
  - !!int "10"
  - !!int "16"
  - !!int "14"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "8"
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Survival"
    "desc": "+6"
"damage_resistances": "acid"
"condition_immunities": "frightened"
"gear":
  - "longbow"
"senses": "passive Perception 16"
"languages": "Common, Goblin, Orc"
"cr": "8"
"traits":
  - "desc": "Ayo can breathe air and water."
    "name": "Amphibious"
  - "desc": "Ayo wields a ruidium harpoon (see appendix B). If Ayo rolls a 1 on an\
      \ attack roll made with the harpoon, she must succeed on a DC 20 Charisma saving\
      \ throw or gain 1 level of exhaustion."
    "name": "Special Equipment"
"actions":
  - "desc": "Ayo makes three Harpoon or Longbow attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) piercing damage plus 7 (2d6) psychic damage."
    "name": "Ruidium Harpoon"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 150/600 ft., one target. *Hit:*\
      \ 18 (3d8 + 5) piercing damage."
    "name": "Longbow"
  - "desc": "Ayo casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 14):\n\n**1/day each:** animal friendship, freedom\
      \ of movement, goodberry, pass without trace, protection from energy"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Ayo issues orders to one ally she can see within 30 feet of herself.\
      \ If the target can see or hear Ayo, it can spend its reaction to move up to\
      \ its speed. This movement doesn't provoke opportunity attacks."
    "name": "Reposition"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/ayo-jabe-tier-3-crcotn.webp"
```
^statblock