---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Expeditious Messenger"
---
# [Expeditious Messenger](3-Mechanics/CLI/bestiary/construct/expeditious-messenger-erlw.md)
*Source: Eberron: Rising from the Last War p. 293*  

An expeditious messenger is a speedy flier, designed to quickly carry messages for its creator. Their speedy and efficient attitude makes expeditious messengers quite chatty, and they natter on as fast as they move.

These messengers come in a variety of forms, often looking like mechanical birds or sprites.

## Constructed Nature

A homunculus doesn't require air, food, drink, or sleep.

A homunculus is a construct servant created for certain tasks. Artificers and wizards are responsible for most of the homunculi in existence.

Each kind of homunculus has a body constructed from different kinds of materials, including clay, iron, and bits of hair and feathers. The process that creates a homunculus sees those materials mixed with the creator's blood and animated through an extended magical ritual.

```statblock
"name": "Expeditious Messenger (ERLW)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "2d4 + 2"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "13"
  - !!int "8"
  - !!int "12"
  - !!int "7"
"speed": "25 ft., fly 60 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "one language spoken by its creator"
"cr": "1/8"
"traits":
  - "desc": "The messenger doesn't provoke opportunity attacks when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
  - "desc": "While the messenger is on the same plane of existence as its master,\
      \ it can magically convey what it senses to its master, and the two can communicate\
      \ telepathically."
    "name": "Telepathic Bond"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) piercing damage."
    "name": "Bite"
"source":
  - "ERLW"
"image": "3-Mechanics/CLI/bestiary/construct/token/expeditious-messenger-erlw.webp"
```
^statblock