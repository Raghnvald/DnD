---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Jarund Elkhardt
linter-yaml-title-alias: Jarund Elkhardt
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/idrotf
aliases:
  - Jarund Elkhardt
---
# [Jarund Elkhardt](3-Mechanics\CLI\bestiary\npc/jarund-elkhardt-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 305*  

The Elk King is Jarund Elkhardt, a terse yet thoughtful giant of a man who is nearly fifty years old—ancient by tribal standards. He has led the Elk Tribe for over half his life, and age has made him cautious. He has seen other kings and queens rise and fall, has made war with friends and peace with his enemies, and has led warriors he knew as babes to their deaths in battle. The strain of his long years of rule is etched on his weather-worn face.

Jarund's late son, Jarund Twice-Born, was killed almost a decade ago while trying to bring down a cave bear, leaving Jarund without an heir. He has failed to produce another child with his wife, Wynneth, and his mistress, Froya, so the future of his royal line remains uncertain.

Auril's unyielding winter concerns Jarund deeply, and he often turns to his shaman, Mjenir, for guidance. The king respects the shaman's understanding of gods and spirits, and the fact that both men have lost their sons serves to strengthen the bond between them. Mjenir believes that the only way to break Auril's spell is to slay the goddess in her home, but Jarund believes that his warriors aren't strong enough to accomplish that task alone.

```statblock
"name": "Jarund Elkhardt (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "hide armor, shield"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "5"
"traits":
  - "desc": "A melee weapon deals one extra die of its damage when Jarund hits with\
      \ it (included in the attack)."
    "name": "Brute"
"actions":
  - "desc": "Jarund makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage, or 15 (2d10 + 4) bludgeoning damage when used\
      \ with two hands."
    "name": "Warhammer"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage, and Jarund pushes the target 5 feet away from\
      \ him if it's Large or smaller. Jarund then enters the space vacated by the\
      \ target. If the target is pushed to within 5 feet of a creature friendly to\
      \ Jarund, that creature can make an attack against the target as a reaction."
    "name": "Shield"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 11 (2d6 + 4) piercing damage."
    "name": "Javelin"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/jarund-elkhardt-idrotf.webp"
```
^statblock