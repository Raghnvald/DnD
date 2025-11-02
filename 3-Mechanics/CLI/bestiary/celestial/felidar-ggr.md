---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Felidar
---
# [Felidar](3-Mechanics\CLI\bestiary\celestial/felidar-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 199*  

A felidar is a celestial creature whose nature reflects an inherent devotion to law and order. It resembles an enormous cat with two pairs of downward-sloping horns and prominent teeth. Its blue-gray hide has a silvery, geometric pattern, and its thick white mane falls in an orderly fashion around its shoulders.

Nearly every felidar forms a close bond with one other creature. Winged felidars almost always bond with archons, joining in their relentless pursuit of justice. Other felidars ally with members of the Azorius Senate and form bonds with high-ranking justiciars and ministers, aiding them in enforcing the law and tracking down criminals. Some Azorius felidars form bonds with important prisoners in Azorius custody, ensuring that the felidars can track down the felons if they escape custody.

```statblock
"name": "Felidar (GGR)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "17"
  - !!int "10"
  - !!int "17"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "6"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
"senses": "truesight 120 ft., passive Perception 16"
"languages": "understands Celestial and Common but can't speak"
"cr": "5"
"traits":
  - "desc": "The felidar can magically bond with one creature it can see, right after\
      \ spending at least 1 hour observing that creature while within 30 feet of it.\
      \ The bond lasts until the felidar bonds with a different creature or until\
      \ the bonded creature dies. This bond has the following effects: The felidar\
      \ and the bonded creature can communicate telepathically with each other at\
      \ a distance of up to 100 feet. The felidar can sense the direction and distance\
      \ to the bonded creature if they're on the same plane of existence. As an action,\
      \ the felidar or the bonded creature can sense what the other sees and hears,\
      \ during which time it loses its own sight and hearing. This effect lasts until\
      \ the start of its next turn."
    "name": "Bonding"
  - "desc": "The felidar has advantage on Wisdom (Perception) checks that rely on\
      \ hearing or sight."
    "name": "Keen Hearing and Sight"
  - "desc": "If the felidar moves at least 20 feet straight toward a creature and\
      \ hits it with a claw attack on the same turn, that target must succeed on a\
      \ DC 15 Strength saving throw or be knocked prone. If the target is prone, the\
      \ felidar can make one claw attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The felidar makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 17\
      \ (3d8 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) slashing damage."
    "name": "Claws"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/felidar-ggr.webp"
```
^statblock