---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Dzaan
Status: WIP
linter-yaml-title-alias: Dzaan
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/4
  - Monster/Typ/Konstrukt
  - Quelle/5e/idrotf
aliases:
  - Dzaan
---
# [Dzaan](3-Mechanics\CLI\bestiary\npc/dzaan-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 271*  

Dzaan was a Red Wizard of Thay who studied the arcane tradition of illusion. The leaders of the Arcane Brotherhood welcomed him with open arms, eager to count a Red Wizard among their ranks. Dzaan might have become a force to reckon with in the brotherhood had his quest for power not led him to Icewind Dale, where he was killed by the people of Easthaven after making a few too many enemies.

## Dzaan's Demise

Dzaan's trouble started after he broke away from his fellow wizards and hired adventurers to scour Icewind Dale for Netherese ruins. One group of them uncovered a buried tower in the tundra (see "Lost Spire of Netheril"), and Dzaan went out of his way to eliminate anyone who knew of it, including the adventurers who found it and several Ten-Towners with whom they had spoken. After turning the tower into his secret base, Dzaan visited Easthaven to gather supplies. Although he took the precaution of adopting a magical disguise, members of the local militia recognized Dzaan by the way he walked and spoke. They captured him, gagged him, confiscated his spellbook, and condemned him to death.

## Companion

Because they're so despised throughout Faerûn, Red Wizards often adopt disguises and rarely travel abroad without an escort. They generally favor undead servants and bodyguards, since they find that undead tend to be more obedient than the living. Dzaan's bodyguard is a Thayan [wight](/3-Mechanics/CLI/bestiary/undead/wight.md) named Krintaas. When Dzaan returned to Easthaven, he ordered his companion to stay with the simulacrum and watch over it and the buried Netherese spire.

```statblock
"name": "Dzaan (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Lawful Evil"
"ac": !!int "10"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Deception"
    "desc": "+4"
  - "name": "History"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Abyssal, Common, Giant, Infernal"
"cr": "4"
"traits":
  - "desc": "Dzaan is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** acid splash *, light, minor illusion,\
      \ shocking grasp *\n\n**1st level (4 slots):** detect magic, disguise self,\
      \ magic missile *\n\n**2nd level (3 slots):** invisibility, levitate, phantasmal\
      \ force\n\n**3rd level (3 slots):** fireball, sending, slow\n\n**4th level (3\
      \ slots):** arcane eye, confusion\n\n**5th level (1 slots):** animate objects\n\
      \n*See \"Actions\" below."
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Spell Attack:* +5 to hit, reach 5 ft., one creature (the attack\
      \ roll has advantage if the target is wearing armor made of metal). *Hit:* 9\
      \ (2d8) lightning damage, and the target can't take reactions until the start\
      \ of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "Dzaan hurls a bubble of acid at one creature it can see within 60 feet\
      \ of it, or at two such creatures that are within 5 feet of each other. A target\
      \ must succeed on a DC 13 Dexterity saving throw or take 7 (2d6) acid damage."
    "name": "Acid Splash (Cantrip)"
  - "desc": "Dzaan creates three darts of magical force. Each dart unerringly strikes\
      \ one creature Dzaan can see within 120 feet of it, dealing 3 (1d4 + 1) force\
      \ damage. If Dzaan casts this spell using a 2nd-level spell slot, it creates\
      \ one more dart."
    "name": "Magic Missile (1st-Level Spell; Requires a Spell Slot)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/dzaan-idrotf.webp"
```
^statblock