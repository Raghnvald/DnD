---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flabbergast"
---
# [Flabbergast](3-Mechanics/CLI/bestiary/npc/flabbergast-ai.md)
*Source: Acquisitions Incorporated p. 200*  

Not much is known of the mysterious and aloof majordomo of Acquisitions Incorporated Head Office, the mage known as Flabbergast. It's said that he hails from Neverwinter, and that his wealthy family helped erect and carve the famous Dolphin Bridge in that city. Although he detests physical labor, Flabbergast is a bit of a bridge builder in his own way, always striving to bring people together and flexing his diplomatic muscles. A pacifist bureaucrat, he abhors violence, and rarely puts his magical prowess on display.

One thing that is known (though it's seldom spoken of) is that Flabbergast once worked for Dran Enterprises, and specifically for Portentia Dran. He carries a certain amount of guilt around being complicit in certain Dran Enterprises' dealings, and helped Acquisitions Incorporated on the side even before taking up an official role with the company. Though Head Office certainly trusts him, others might wonder where his true loyalties lie.

Flabbergast's familiar, Mister Snibbly, uses the cat stat block.

```statblock
"name": "Flabbergast (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "17"
  - !!int "13"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Persuasion"
    "desc": "+3"
  - "name": "History"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
"gear":
  - "dagger"
"senses": "passive Perception 13"
"languages": "Common, Draconic, Elvish, Gnomish"
"cr": "4"
"traits":
  - "desc": "Flabbergast is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** fire bolt, light, mage hand, prestidigitation\n\
      \n**1st level (4 slots):** detect magic, mage armor, [distort value](3-Mechanics/CLI/spells/distort-value-ai.md)*\n\
      \n**2nd level (3 slots):** [gift of gab](3-Mechanics/CLI/spells/gift-of-gab-ai.md)*,\
      \ suggestion\n\n**3rd level (3 slots):** [fast friends](3-Mechanics/CLI/spells/fast-friends-ai.md)*,\
      \ lightning bolt\n\n**4th level (3 slots):** greater invisibility\n\n**5th level\
      \ (1 slots):** cone of cold\n\n*New spell introduced in chapter 3"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/npc/token/flabbergast-ai.webp"
```
^statblock