---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/10
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nightveil Specter
---
# [Nightveil Specter](3-Mechanics\CLI\bestiary\undead/nightveil-specter-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 215*  

The Nightveil specters of Ravnica are hooded, undead guardians that ride flying creatures called gloamwings. They are fearsome agents of House Dimir, protecting the territory and interests of that guild-particularly the neighborhood of Nightveil, from which the specters get their name. Their work can include driving off people who accidentally wander too close to a secret rooftop meeting, killing those who knowingly infiltrate Dimir property, and tracking those who have stolen guild secrets, then wiping those secrets from their victims' minds to ensure that they are never shared.

## Limited Sentience

A Nightveil specter is created when the mind magic of House Dimir erases a person's identity, leaving a mind so broken it can no longer live. Thus, Nightveil specters have no memory of their previous lives, and they are just clever enough to follow their orders with some amount of creativity. They pursue their assigned tasks with fearless determination.

## Gloamwing Mount

If a gloamwing is killed, its specter becomes fixated on destroying those responsible. If the specter survives, it can create a new gloamwing over the course of a month, during which time the specter is incapacitated.

A gloamwing's head is almost ratlike, with prominent teeth, and its leathery skin is stretched tight over its skull, where its eyes are empty sockets. Its body is mottled with bony plates, and great wings stretch from its shoulders.

## Undead Nature

A Nightveil specter and its gloamwing mount don't require air, food, drink, or sleep.

```statblock
"name": "Nightveil Specter (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "19"
  - !!int "16"
  - !!int "6"
  - !!int "17"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "8"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+8"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "understands Common but can't speak"
"cr": "10"
"traits":
  - "desc": "If the specter isn't mounted, it can use a bonus action to magically\
      \ teleport onto its gloamwing mount, provided the specter and the gloamwing\
      \ are on the same plane of existence. When it teleports, the specter appears\
      \ astride the gloamwing along with any equipment it is wearing or carrying.\
      \ While mounted and not incapacitated, the specter can't be surprised, and both\
      \ it and its mount gain advantage on Dexterity saving throws."
    "name": "Mount"
"actions":
  - "desc": "The specter makes two scythe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 13 (3d8) psychic damage."
    "name": "Scythe"
  - "desc": "The specter magically emits psychic energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 15 Wisdom saving throw or take 22 (5d8)\
      \ psychic damage and be stunned for 1 minute. The stunned creature can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success."
    "name": "Mind Twist (Recharge 5-6)"
  - "desc": "The specter touches one incapacitated creature and chooses 1 hour from\
      \ among the past 24. Unless the creature succeeds on a DC 15 Intelligence saving\
      \ throw, the creature loses all memory of that hour. The creature regains the\
      \ memory only if the specter dies within the next 24 hours."
    "name": "Reap Memory (3/Day)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/undead/token/nightveil-specter-ggr.webp"
```
^statblock