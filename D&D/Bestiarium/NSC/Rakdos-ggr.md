---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/24
- Monster/Größe/Riesig
- Monster/Typ/Unhold/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rakdos
---
# [Rakdos](3-Mechanics\CLI\bestiary\npc/rakdos-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 247*  

Rakdos, the demon for whom his cult is named, embodies hedonism. He is also the consummate entertainer, whose mere appearance is an act of grisly performance art. A monstrous figure standing thirty feet tall, spreading enormous wings, crowned with fire and swinging a flaming scythe, Rakdos demands the spotlight. His every entrance is a showstopper.

Sometimes after his grand entrance, Rakdos crouches to witness the performances of those who adore him. To them, his opinion is the only one that matters, but he is a demanding spectator. He has seen thousands of years of circus tricks and has no patience for performers who don't give their all. His flaming scythe has brought more than one tepid show to a sudden and spectacular close. Jaded as he is, Rakdos attends his cult's performances only rarely. He often retreats into his lair below the cult's guildhall for months or years at a time, but his followers know that he might emerge at any time to witness the latest spectacle.

```statblock
"name": "Rakdos (GGR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "300"
"hit_dice": "24d12 + 144"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "15"
  - !!int "22"
  - !!int "14"
  - !!int "18"
  - !!int "30"
"speed": "40 ft., fly 80 ft."
"saves":
  - "strength": !!int "15"
  - "constitution": !!int "13"
  - "wisdom": !!int "11"
  - "charisma": !!int "17"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+17"
  - "name": "Performance"
    "desc": "+17"
  - "name": "Persuasion"
    "desc": "+17"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Abyssal, Common"
"cr": "24"
"traits":
  - "desc": "Rakdos's spellcasting ability is Charisma (spell save DC 25). He can\
      \ innately cast hellish rebuke (at 5th level) at will, requiring no material\
      \ components.\n"
    "name": "Innate Spellcasting"
  - "desc": "Any creature that starts its turn within 30 feet of Rakdos must make\
      \ a DC 25 Wisdom saving throw. On a failed save, the creature becomes charmed\
      \ by Rakdos for 1 minute or until the creature is farther than 30 feet away\
      \ from him. On a successful save, the creature becomes immune to Rakdos's Captivating\
      \ Presence for 24 hours."
    "name": "Captivating Presence"
  - "desc": "When a creature Rakdos can see within 60 feet of him is reduced to 0\
      \ hit points, Rakdos gains 25 temporary hit points."
    "name": "Cruel Entertainment"
  - "desc": "If Rakdos fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Rakdos has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Rakdos's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Rakdos makes two attacks with his Curtain-Call Scythe or his claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 24\
      \ (3d10 + 8) slashing damage plus 13 (3d8) fire damage."
    "name": "Curtain-Call Scythe"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 17\
      \ (2d8 + 8) slashing damage."
    "name": "Claw"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Rakdos can expend a use to take one of the following actions. Rakdos regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Each creature within 60 feet of Rakdos that is his ally or is charmed\
      \ by him must use its reaction to move up to half its speed toward the creature\
      \ closest to it that it can see, provided it isn't already within 5 feet of\
      \ that creature. It then must make one melee attack against that creature if\
      \ it is able to do so."
    "name": "Sadistic Revelry"
  - "desc": "Rakdos uses Curtain-Call Scythe."
    "name": "Scythe (Costs 2 Actions)"
  - "desc": "Rakdos makes a claw attack against one creature within 10 feet of him.\
      \ The target must succeed on a DC 25 Constitution saving throw or be poisoned\
      \ for 1 minute. While poisoned in this way, the creature can't maintain concentration\
      \ on a spell or any other effect that requires concentration. The poisoned creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Touch of Pain (Costs 3 Actions)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/rakdos-ggr.webp"
```
^statblock