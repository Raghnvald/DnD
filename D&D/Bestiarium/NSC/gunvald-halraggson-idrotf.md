---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/5
  - Monster/Größe/Mittelgroß
  - Monster/Typ/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Gunvald Halraggson
---
# [Gunvald Halraggson](3-Mechanics\CLI\bestiary\npc/gunvald-halraggson-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 305*  

The thirty-year-old Bear King cuts an impressive figure and is renowned for his size and strength. He tries to be honorable, but he is often merciless and doesn't change his mind easily. He has trouble relating to Ten-Towners, so he avoids them. His perspective on townsfolk might change if they helped him destroy the chardalyn berserkers who have turned against their own.

Gunvald has had three wives in six years, each of whom died while she was pregnant. His advisors fear that the gods have cursed Gunvald and the entire tribe. In truth, the king's doting shaman, Ulkora, lusts for him and surreptitiously poisoned his wives. In time, Ulkora hopes Gunvald will turn his loving eye toward her and allow her to bear his true heir. If Gunvald were to learn the truth, he would put Ulkora to death.

```statblock
"name": "Gunvald Halraggson (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "hide armor, shield"
"hp": !!int "76"
"hit_dice": "9d8 + 36"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "8"
  - !!int "18"
  - !!int "9"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+8"
  - "name": "Intimidation"
    "desc": "+6"
  - "name": "Survival"
    "desc": "+3"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "5"
"traits":
  - "desc": "Gunvald can reroll a saving throw he fails. He must use the new roll."
    "name": "Indomitable (3/Day)"
  - "desc": "Gunvald deals an extra 6 (1d12) damage when he hits a target with a weapon\
      \ attack. If the target is a creature, it must succeed on a DC 14 Wisdom saving\
      \ throw or be frightened until the start of Gunvald's next turn."
    "name": "Menacing Blows (1/Turn)"
  - "desc": "As a bonus action, Gunvald can regain 15 hit points."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "Gunvald makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8\
      \ + 5) slashing damage, or 10 (1d10 + 5) slashing damage when used with two\
      \ hands, plus 6 (1d12) slashing damage if Gunvald uses Menacing Blows."
    "name": "Battleaxe"
  - "desc": "*Melee  or Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target.\
      \ *Hit:* 8 (1d6 + 5) piercing damage, plus 6 (1d12) piercing damage if Gunvald\
      \ uses Menacing Blows."
    "name": "Javelin"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/gunvald-halraggson-idrotf.webp"
```
^statblock