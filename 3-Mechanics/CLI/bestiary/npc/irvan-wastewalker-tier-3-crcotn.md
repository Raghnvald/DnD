---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Irvan Wastewalker (Tier 3)"
---
# [Irvan Wastewalker (Tier 3)](3-Mechanics/CLI/bestiary/npc/irvan-wastewalker-tier-3-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 194*  

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

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `1d4` levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

#### Irvan's Prosthetic Arm

During a misadventure that unfolded while the rivals were apart from the characters, Irvan Wastewalker lost an arm and gained an arcane prosthetic. This magic item functions for no one else.

```statblock
"name": "Irvan Wastewalker (Tier 3) (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "17"
"ac_class": "studded leather"
"hp": !!int "123"
"hit_dice": "19d8 + 38"
"modifier": !!int "5"
"stats":
  - !!int "10"
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "16"
"speed": "40 ft., swim 40 ft. (see special equipment)"
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+8"
  - "name": "Deception"
    "desc": "+9"
  - "name": "Stealth"
    "desc": "+11"
  - "name": "Survival"
    "desc": "+6"
"gear":
  - "dagger"
  - "[ruidium shortsword](3-Mechanics/CLI/items/ruidium-weapon-crcotn.md)"
"senses": "passive Perception 13"
"languages": "Common, Goblin, Orc"
"cr": "8"
"traits":
  - "desc": "If damage reduces Irvan to 0 hit points, he can make a Constitution saving\
      \ throw with a DC equal to 5 + the damage taken. On a successful save, Irvan\
      \ drops to 1 hit point instead."
    "name": "Fortitude (Recharges after a Short or Long Rest)"
  - "desc": "Irvan wears [gloves of swimming and climbing](3-Mechanics/CLI/items/gloves-of-swimming-and-climbing.md)\
      \ and wields a ruidium shortsword (see appendix B). If Irvan rolls a 1 on an\
      \ attack roll made with the shortsword, he must succeed on a DC 20 Charisma\
      \ saving throw or gain 1 level of exhaustion.\n\nIn addition, Irvan has a magical\
      \ prosthetic arm. While the arm is attached to him, it functions the same as\
      \ the body part it is replacing. Irvan can attach or detach the arm as an action,\
      \ and it can't be removed by anyone else."
    "name": "Special Equipment"
"actions":
  - "desc": "Irvan makes one Dagger attack and two Ruidium Shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +8 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 17 (5d6) poison\
      \ damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d6 + 5) piercing damage plus 7 (2d6) psychic damage."
    "name": "Ruidium Shortsword"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/irvan-wastewalker-tier-3-crcotn.webp"
```
^statblock