---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: "Nar'l Xibrindas"
linter-yaml-title-alias: "Nar'l Xibrindas"
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/Humanoid/elf
  - Quelle/5e/wdh
aliases:
  - "Nar'l Xibrindas"
  - Nar'l Xibrindas
---
# [Nar'l Xibrindas](3-Mechanics\CLI\bestiary\npc/narl-xibrindas-wdh.md)
*Source: Waterdeep: Dragon Heist p. 211*  

Xanathar's advisor is a nervous and conniving male drow named Nar'l Xibrindas. Nar'l's house was wiped out long ago, but he and his elder brother Soluun survived and joined Bregan D'aerthe. A year ago, Nar'l was given the difficult task of infiltrating the Xanathar Guild and getting as close to the beholder as possible. Not only did he succeed, but in the course of gaining Xanathar's trust, he managed to convince the beholder to eliminate its other advisors. The beholder's paranoia will eventually cause Xanathar to question the drow's loyalty, though, and Nar'l has become increasingly worried about his future. If forced to decide between himself and Bregan D'aerthe, he'll choose the former and betray his drow allies to save his own skin.

Xanathar is aware that something is off with Nar'l, and recently assigned him a grell bodyguard. The grell has instructions to dispose of Nar'l at the first sign of disloyalty.

```statblock
"name": "Nar'l Xibrindas (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "10"
  - !!int "17"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "Deception"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "7"
"traits":
  - "desc": "Nar'l is a 10th-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). Nar'l has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** mage hand, minor illusion,\
      \ poison spray, ray of frost\n\n**1st level (4 slots):** mage armor, magic missile,\
      \ shield, witch bolt\n\n**2nd level (3 slots):** alter self, misty step, web\n\
      \n**3rd level (3 slots):** fly, lightning bolt\n\n**4th level (3 slots):** Evard's\
      \ black tentacles, greater invisibility\n\n**5th level (2 slots):** cloudkill"
    "name": "Spellcasting"
  - "desc": "Nar'l's spellcasting ability is Charisma (spell save DC 12). It can innately\
      \ cast the following spells, requiring no material components:\n\n**At will:**\
      \ dancing lights\n\n**1/day each:** darkness, faerie fire, levitate (self only)"
    "name": "Innate Spellcasting"
  - "desc": "Nar'l has advantage on saving throws against being charmed, and magic\
      \ can't put Nar'l to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, Nar'l has disadvantage on attack rolls, as well as\
      \ on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "Nar'l carries a vial containing three doses of [eyescratch](/3-Mechanics/CLI/items/eyescratch-wdh.md),\
      \ a contact poison. A creature that comes into contact with the poison must\
      \ succeed on a DC 14 Constitution saving throw or be poisoned for 1 hour and\
      \ blinded while poisoned in this way. A lesser restoration spell or similar\
      \ magic ends the effect."
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d6\
      \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
      \ hands, plus 3 (1d6) poison damage."
    "name": "Staff"
  - "desc": "Nar'l magically summons a [quasit](/3-Mechanics/CLI/bestiary/fiend/quasit.md),\
      \ or attempts to summon a [shadow demon](/3-Mechanics/CLI/bestiary/fiend/shadow-demon.md)\
      \ with a 50 percent chance of success. The summoned demon appears in an unoccupied\
      \ space within 60 feet of its summoner, acts as an ally of its summoner, and\
      \ can't summon other demons. It remains for 10 minutes, until it or its summoner\
      \ dies, or until its summoner dismisses it as an action."
    "name": "Summon Demon (1/Day)"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/narl-xibrindas-wdh.webp"
```
^statblock