---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/gos
  - Monster/HG/8
  - Monster/Größe/Groß
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Vampiric Jade Statue
---
# [Vampiric Jade Statue](3-Mechanics\CLI\bestiary\construct/vampiric-jade-statue-gos.md)
*Source: Ghosts of Saltmarsh p. 256*  

A large, exquisitely carved jade statue of a vampire guards the tunnels in Isle of the Abbey, having been brought to life by dark magic. Its stone fangs draw blood that it then uses to work a curse on its victims.

```statblock
"name": "Vampiric Jade Statue (GoS)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "18"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "force"
"damage_immunities": "lightning, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
  - "desc": "The statue is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "If the statue fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The statue makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) piercing damage. If the target is a creature, that creature becomes\
      \ cursed by the statue. The curse lasts for 10 minutes. While the creature is\
      \ cursed, the statue has advantage on all attacks against it."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Claws"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the vampiric jade statue can expend a use to take one of the following actions.\
  \ The vampiric jade statue regains all expended uses at the start of each of its\
  \ turns."
"legendary_actions":
  - "desc": "The statue makes one bite attack."
    "name": "Bite"
  - "desc": "All creatures currently cursed by the statue and within 20 feet of it\
      \ take 5 necrotic damage."
    "name": "Blood Reaper"
  - "desc": "The statue moves up to its speed without provoking opportunity attacks."
    "name": "Move"
"source":
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/construct/token/vampiric-jade-statue-gos.webp"
```
^statblock