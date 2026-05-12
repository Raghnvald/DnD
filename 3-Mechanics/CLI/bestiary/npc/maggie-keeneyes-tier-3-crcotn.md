---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/ogre
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Maggie Keeneyes (Tier 3)"
---
# [Maggie Keeneyes (Tier 3)](3-Mechanics/CLI/bestiary/npc/maggie-keeneyes-tier-3-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 194*  

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

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `1d4` levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

```statblock
"name": "Maggie Keeneyes (Tier 3) (CRCotN)"
"size": "Large"
"type": "giant"
"subtype": "ogre"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "plate"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "8"
"speed": "30 ft., swim 30 ft. (ruidium armor)"
"saves":
  - "strength": !!int "8"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "Athletics"
    "desc": "+8"
  - "name": "Insight"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Persuasion"
    "desc": "+5"
"damage_resistances": "psychic (granted by ruidium armor)"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Giant"
"cr": "8"
"traits":
  - "desc": "Once during each of her turns, after hitting a creature with an attack,\
      \ Maggie can force the target to make a DC 16 Strength saving throw; on a failed\
      \ save, the target is pushed up to 15 feet horizontally away from Maggie and\
      \ knocked prone."
    "name": "Push"
  - "desc": "Maggie wears a suit of ruidium armor (plate; see appendix B). If Maggie\
      \ rolls a 1 on a saving throw while wearing the armor, she must succeed on a\
      \ DC 20 Charisma saving throw or gain 1 level of exhaustion."
    "name": "Special Equipment"
  - "desc": "Maggie and allies within 30 feet of her have advantage on initiative\
      \ rolls, as long as Maggie isn't incapacitated."
    "name": "Tactical Readiness"
"actions":
  - "desc": "Maggie makes two Heavy Greataxe or Hammer Toss attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 16 (2d12 + 5) slashing damage."
    "name": "Heavy Greataxe"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 20/60 ft., one target. *Hit:*\
      \ 15 (4d4 + 5) bludgeoning damage."
    "name": "Hammer Toss"
"bonus_actions":
  - "desc": "Maggie targets one creature she can see within 60 feet of herself and\
      \ bolsters it with words of encouragement. The target gains 30 temporary hit\
      \ points if it can see or hear Maggie."
    "name": "Rally (1/Day)"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/maggie-keeneyes-tier-3-crcotn.webp"
```
^statblock