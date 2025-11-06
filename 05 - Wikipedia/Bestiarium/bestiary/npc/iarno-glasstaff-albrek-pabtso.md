---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/1
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
  - Monster/Typ/Humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Iarno "Glasstaff" Albrek
---
# [Iarno "Glasstaff" Albrek](3-Mechanics\CLI\bestiary\npc/iarno-glasstaff-albrek-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 43*  

A former member of the Lords' Alliance, Glasstaff seized an opportunity in Phandalin to line his own pockets. Originally tasked with setting up a constabulary, he instead assembled a group of outlaws and local ruffians to secure his own position in town.

Glasstaff puts on airs of gentility and courteous manners, addressing his bandits and ruffians as "my good fellows," and referring to sordid acts such as kidnapping or arson as "that unpleasant little business" or "those unfortunate events." He may refer to the characters as his "honored guests," and expresses regret that he cannot provide suitable entertainment for the occasion of their visit. Beneath his genteel demeanor, however, Glasstaff is just as violent and arrogant as any of the Redbrands.

```statblock
"name": "Iarno \"Glasstaff\" Albrek (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "16 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md) and\
  \ [staff of defense](/3-Mechanics/CLI/items/staff-of-defense-pabtso.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
  - "desc": "Glasstaff wields a [staff of defense](/3-Mechanics/CLI/items/staff-of-defense-pabtso.md)\
      \ (see appendix B). With the staff in hand, he can use an action to cast the\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md) spell and use his\
      \ reaction to cast the [shield](/3-Mechanics/CLI/spells/shield-xphb.md) spell."
    "name": "Special Equipment"
"actions":
  - "desc": "Glasstaff makes two Shocking Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 6 (1d6 + 3) lightning damage."
    "name": "Shocking Burst"
  - "desc": "Glasstaff casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [light](/3-Mechanics/CLI/spells/light-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\
      \n**1/day each:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [magic missile](/3-Mechanics/CLI/spells/magic-missile-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Glasstaff magically teleports, along with any equipment he is wearing\
      \ or carrying, up to 30 feet to an unoccupied space he can see."
    "name": "Teleport (2/Day)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/iarno-glasstaff-albrek-pabtso.webp"
```
^statblock