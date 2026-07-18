---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ziraj the Hunter
Status: WIP
linter-yaml-title-alias: Ziraj the Hunter
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Humanoid/half-orc
  - Quelle/5e/wdh
aliases:
  - Ziraj the Hunter
---
# [Ziraj the Hunter](3-Mechanics\CLI\bestiary\npc/ziraj-the-hunter-wdh.md)
*Source: Waterdeep: Dragon Heist p. 201*  

Ziraj is a half-orc hunter who wields an oversized bow that shoots correspondingly large arrows. He is the Master of Assassination for the Black Network. If Ziraj sets out to kill someone, it's because one of his friends (Davil, Istrid, Skeemo, or Tashlyn) asked him to. The characters might become Ziraj's prey, or Ziraj might come to their aid to eliminate a common enemy. He's the strong, silent type.

The City Watch has received reports of a figure who haunts the rooftops of Waterdeep-a hulking shadow that glares from its perch, rains down death in the form of long black arrows, and slinks off without so much as a whisper. Where he comes from-if he even has a home-remains a mystery, as does the question of where he might show up next.

## Treasure

Ziraj wears +2 leather armor and carries an oversized longbow. This unique weapon can be used only by a Medium or larger creature that has a Strength of 18 or higher. The bow shoots oversized arrows that deal piercing damage equal to `dice:2d6|noform|noparens|avg` (`2d6`) + the wielder's Strength modifier. Its range is the same as an ordinary longbow.

## The Doom Raiders

The Doom Raiders were five unscrupulous adventurers who liked to plunder lich lairs (called "dooms" by some). They gave up adventuring to join the Black Network and came to Waterdeep three years ago with plans to establish a Zhentarim foothold in the city. In that time, they have forged alliances with various nobles and guilds and run afoul of others, all the while fending off Harper spies.

```statblock
"name": "Ziraj the Hunter (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "+2 leather armor"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "11"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Orc"
"cr": "8"
"traits":
  - "desc": "Ziraj is a 10th-level spellcaster. His spellcasting ability is Charisma.\
      \ He has the following paladin spells prepared:\n\n**1st level (4 slots):**\
      \ command, protection from evil and good, thunderous smite\n\n**2nd level (3\
      \ slots):** branding smite, find steed\n\n**3rd level (2 slots):** blinding\
      \ smite, dispel magic"
    "name": "Spellcasting"
"actions":
  - "desc": "Ziraj makes three attacks with his glaive or with his oversized longbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10\
      \ + 4) slashing damage."
    "name": "Glaive"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 150/600 ft., one target. *Hit:*\
      \ 11 (2d6 + 4) piercing damage."
    "name": "Oversized Longbow"
  - "desc": "Ziraj exudes magical menace. Each enemy within 30 feet of him must succeed\
      \ on a DC 13 Wisdom saving throw or be frightened for 1 minute of Ziraj. If\
      \ a frightened enemy ends its turn more than 30 feet away from Ziraj, the enemy\
      \ can repeat the saving throw, ending the effect on itself on a success."
    "name": "Dreadful Aspect (Recharges after a Short or Long Rest)"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ziraj-the-hunter-wdh.webp"
```
^statblock