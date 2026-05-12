---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Splugoth the Returned"
---
# [Splugoth the Returned](3-Mechanics/CLI/bestiary/npc/splugoth-the-returned-ai.md)
*Source: Acquisitions Incorporated p. 213*  

> [!quote]  
> 
> I'm going to give you a piece of advice. Don't trust Acquisitions Incorporated. And never, ever, ever trust Omin Dran. Wait, that's two pieces of advice. You owe me.

Sometimes a goblin can't catch a break. First, you fall in with a cult that works for the release of a death god. Then you get taken prisoner by a group of sociopathic adventurers who end up letting you die after you save their sorry lives. One minute, you're a dead goblin named Splug. And then you're alive again, and it seems like a really good idea to play up the drama of resurrection with a cool new name-and a master plan for cold, cold revenge against those who betrayed you.

Every once in a while, the (accidentally) capricious and (totally unintentionally) self-centered nature of an Acquisitions Incorporated franchise might incur some collateral damage among followers, hirelings, and staff. When that happens, the collateral damage sometimes inspires some collateral damage of its own. No one is entirely sure how many times Splugoth the Returned has actually returned from the dead. But as the point goblin for the group known as the Six (see "Factions and Rivals" in chapter 3), he's made vengeance against Acq Inc and Omin Dran his life's work. And then the work of his next life. And the one after that.

```statblock
"name": "Splugoth the Returned (AI)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "4"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Stealth"
    "desc": "+6"
"gear":
  - "dagger"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic, Elvish, Goblin"
"cr": "2"
"traits":
  - "desc": "As long as two or more of Splugoth's allies are within 5 feet of him\
      \ and are not incapacitated, attack rolls against him are made with disadvantage."
    "name": "Defensive Advantage"
  - "desc": "Splugoth can take the Disengage or Hide action as a bonus action on each\
      \ of his turns."
    "name": "Nimble Escape"
  - "desc": "Splugoth has advantage on saving throws against being charmed or frightened."
    "name": "Touch of Madness"
"actions":
  - "desc": "Splugoth makes two attacks with his dagger."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) slashing damage."
    "name": "Dagger"
  - "desc": "Splugoth remembers and repeats aloud a few words from a place he entered\
      \ while walking back from the next world to this one. Each creature of his choice\
      \ within 30 feet of him that can hear him must succeed on a DC 12 Wisdom saving\
      \ throw or be stunned until the end of its next turn."
    "name": "Word From Beyond (1/Day)"
"reactions":
  - "desc": "When a creature Splugoth can see hits him with a melee weapon attack,\
      \ the weapon snags on a pocket of residual resurrectional energy and is caught\
      \ fast. The attack is negated and the weapon cannot be used until the creature\
      \ succeeds on a DC 12 Strength (Athletics) check as an action to pull it out\
      \ of Splugoth. Natural weapons can have their attacks negated by this feature,\
      \ but can then be retracted automatically at the end of the attacking creature's\
      \ turn."
    "name": "Absorb Attack"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/npc/token/splugoth-the-returned-ai.webp"
```
^statblock