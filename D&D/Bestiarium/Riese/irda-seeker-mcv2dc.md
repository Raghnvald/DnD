---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv2dc
  - Monster/HG/1
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Riese
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Irda Seeker
---
# [Irda Seeker](3-Mechanics\CLI\bestiary\giant/irda-seeker-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 8*  

Irda seekers are skilled spies who use their magic to disguise themselves and gather intelligence for their allies. In combat, irda seekers can momentarily cloak themselves as they dart around the battlefield.

## Irda

The Dragon Queen created the irda long ago. While most irda embraced their wicked creator's teachings, some of them adopted the philosophies of other deities. Those irda who don't serve the Dragon Queen live in hidden communities across Krynn, avoiding the eyes of their creator and her minions.

Distantly related to oni, ogres, and other giant folk, irda have shimmering skin that ranges through shades of indigo and sea green. Their innate magic provides them with limited shape-shifting abilities and the power to create illusions.

```statblock
"name": "Irda Seeker (MCV2DC)"
"size": "Medium"
"type": "giant"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "12"
  - !!int "11"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+4"
"senses": "darkvision 60 ft., truesight 5 ft., passive Perception 16"
"languages": "Common, Giant, Sylvan"
"cr": "1"
"actions":
  - "desc": "The seeker uses Augment Physicality, if available, and makes two Crystal\
      \ Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) force damage, plus 7 (2d6) force damage if the seeker is Large."
    "name": "Crystal Blade"
  - "desc": "For 1 minute, the seeker magically heightens its physical ability and\
      \ increases in size, along with anything it is wearing or carrying. While augmented,\
      \ the seeker is Large, and makes Strength and Dexterity saving throws with advantage.\
      \ If the seeker lacks the room to become Large, it attains the maximum size\
      \ possible in the space available."
    "name": "Augment Physicality (1/Day)"
  - "desc": "The seeker magically transforms to look and feel like a Medium Humanoid\
      \ it has seen. Any equipment the seeker is wearing or carrying isn't transformed,\
      \ and the seeker's statistics don't change. The seeker reverts to its true form\
      \ if the seeker is reduced to 0 hit points or if the seeker uses an action to\
      \ end the transformation."
    "name": "Change Shape (1/Day)"
"bonus_actions":
  - "desc": "The seeker, along with any equipment it is wearing or carrying, turns\
      \ invisible and teleports to an unoccupied space it can see within 30 feet of\
      \ itself. The seeker remains invisible until the start of its next turn or until\
      \ immediately after the seeker makes an attack roll, whichever comes first."
    "name": "Veil Walk (Recharge 4-6)"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/giant/token/irda-seeker-mcv2dc.webp"
```
^statblock