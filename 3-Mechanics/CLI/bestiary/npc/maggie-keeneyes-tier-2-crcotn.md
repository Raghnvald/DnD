---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/ogre
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Maggie Keeneyes (Tier 2)"
---
# [Maggie Keeneyes (Tier 2)](3-Mechanics/CLI/bestiary/npc/maggie-keeneyes-tier-2-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 191*  

People might laugh when a 12-foot-tall ogre orders a drink at a bar and says her name is Maggie, but they don't laugh for long. Some people fixate on her name, her enormous size, her muscles, or the weapon at her side. Wiser folk take notice of Maggie's bright blue eyes. All her life, people have considered Maggie a stupid meathead because of her size, but her eyes betray her intelligence. She can read others with a glance, whether in conversation or in a duel. When her eyes dart back and forth across a battlefield, they take in enough information to give her allies an advantage in the fight.

Things changed for Maggie when she first arrived in Jigow and met Ayo Jabe three weeks ago. She came looking for mercenary work to make ends meet but found a true friend instead. Ayo saw the intelligence in Maggie's eyes and was keen to hear Maggie's thoughts. They became fast friends, and Maggie would sooner die than let harm come to her new companion.

Maggie loves poetry and music with profound lyrics, as well as matching wits with people as clever as she is. She hates being stereotyped and has a dim view of those who are too quick to judge others.

> [!note] Battle Chatter Sample Quotes
> 
> "That was quite a blunder." "You're lucky I'm feeling merciful." "Fight smarter—and harder." "People don't win fights by fighting fair."
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Maggie Keeneyes (Tier 1) |
| 3 and 4 | Maggie Keeneyes (Tier 2) |
| 5, 6, and 7 | Maggie Keeneyes (Tier 3) |
^chapters-stat-blocks

The tier 2 rivals are learning that their adventures take them into horrific places that will test their mettle, but they face these challenges with heads held high.

```statblock
"name": "Maggie Keeneyes (Tier 2) (CRCotN)"
"size": "Large"
"type": "giant"
"subtype": "ogre"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "chain shirt"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "8"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "Athletics"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Persuasion"
    "desc": "+5"
"condition_immunities": "frightened"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Giant"
"cr": "5"
"traits":
  - "desc": "Once during each of her turns, after hitting a creature with an attack,\
      \ Maggie can force the target to make a DC 15 Strength saving throw; on a failed\
      \ save, the target is pushed up to 10 feet horizontally away from Maggie and\
      \ knocked prone."
    "name": "Push"
  - "desc": "Maggie and allies within 30 feet of her have advantage on initiative\
      \ rolls, as long as Maggie isn't incapacitated."
    "name": "Tactical Readiness"
"actions":
  - "desc": "Maggie makes two Giant Maul or Hammer Toss attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) bludgeoning damage."
    "name": "Giant Maul"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 20/60 ft., one target. *Hit:*\
      \ 9 (2d4 + 4) bludgeoning damage."
    "name": "Hammer Toss"
"bonus_actions":
  - "desc": "Maggie targets one creature she can see within 30 feet of herself and\
      \ bolsters it with words of encouragement. The target gains 15 temporary hit\
      \ points if it can see or hear Maggie."
    "name": "Rally (1/Day)"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/maggie-keeneyes-tier-2-crcotn.webp"
```
^statblock