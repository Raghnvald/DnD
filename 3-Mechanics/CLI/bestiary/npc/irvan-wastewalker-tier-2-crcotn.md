---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Irvan Wastewalker (Tier 2)"
---
# [Irvan Wastewalker (Tier 2)](3-Mechanics/CLI/bestiary/npc/irvan-wastewalker-tier-2-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 191*  

The name "Wastewalker" conjures fear on the plains of Xhorhas, as the name of a clan of Xhorhasian nomads. Irvan—Irv to his friends—was born into that clan, but he hates the name. He left his family when he was a teenager, struck out on his own across the wastes, and made his way to the city of Asarius. Even though the "City of Beasts" is renowned for danger, Irv felt at home there in a way he'd never felt with his clan.

He earned a reputation for being a party animal who could put down a dozen drinks in a night and still dance with the vigor and elegance of an archfey. Irv is young—just a few weeks past his nineteenth birthday—and he is secretly ashamed of his patchy beard and scrawny, human body. He has a bigger secret related to that feeling: he was consecuted in another life. The act of consecution is a sacred Kryn ritual of rebirth through the mystical power of the Luxon. Irvan has memories of his previous life as a bugbear of Den Hythenos, and he hopes to prove to himself that he can do great things without the aid of his powerful "family" in the Kryn Dynasty.

He met Ayo and her friends when he traveled to Jigow to experience its contests of strength and skill. He sticks with the group in part because he's interested in what adventures they'll get into, and also because he's smitten with the group's newest addition, a drow arcanist named Galsariad.

> [!note] Battle Chatter Sample Quotes
> 
> "Heh, that was a good hit, wasn't it?" "Come on, come on! Eyes on me!" "Can I have this dance? No?"
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Irvan Wastewalker (Tier 1) |
| 3 and 4 | Irvan Wastewalker (Tier 2) |
| 5, 6, and 7 | Irvan Wastewalker (Tier 3) |
^chapters-stat-blocks

The tier 2 rivals are learning that their adventures take them into horrific places that will test their mettle, but they face these challenges with heads held high.

```statblock
"name": "Irvan Wastewalker (Tier 2) (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "studded leather"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "14"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "4"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+6"
  - "name": "Deception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+9"
  - "name": "Survival"
    "desc": "+5"
"gear":
  - "dagger"
"senses": "passive Perception 12"
"languages": "Common, Goblin"
"cr": "5"
"traits":
  - "desc": "If damage reduces Irvan to 0 hit points, he can make a Constitution saving\
      \ throw with a DC equal to 5 + the damage taken. On a successful save, Irvan\
      \ drops to 1 hit point instead."
    "name": "Fortitude (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "Irvan makes two Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 14 (4d6) poison\
      \ damage."
    "name": "Dagger"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/irvan-wastewalker-tier-2-crcotn.webp"
```
^statblock