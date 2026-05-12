---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ayperobo Swarm"
---
# [Ayperobo Swarm](3-Mechanics/CLI/bestiary/fiend/ayperobo-swarm-coa.md)
*Source: Chains of Asmodeus p. 238*  

An individual ayperobo is practically harmless, and often eaten by larger devils as a delicacy. Recognizing their weakness, ayperobos gather together and create colonies that communicate using telepathy. These swarms are much stronger, capable of holding their own even against some of the greater devils.

## Something to Prove

Their perfect communication and collective strength, coupled with their ability for flight, allow the ayperobos to easily complete tasks with which larger devils struggle. They're happy to do so, as their goal is to prove their worth and, when possible, get revenge for their abusive treatment at the hands of larger devils.

## Small but Deadly

Each member of the swarm appears as a small, devilish being, with oversized heads and sparrow-like wings. Their teeth are razor sharp, and when working together in a swarm, they can devour a Humanoid in a matter of seconds. While swarming, ayperobos appear as a thick cloud of mosquitoes or a cloud of blood—and are known to hide among such phenomena. Some swarms have the power to control a "host" by burrowing under its skin and manipulating it from the inside—these hosts can even be other devils.

```statblock
"name": "Ayperobo Swarm (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "7"
"stats":
  - !!int "3"
  - !!int "24"
  - !!int "14"
  - !!int "8"
  - !!int "13"
  - !!int "13"
"speed": "5 ft., fly 60 ft. (hover)"
"saves":
  - "dexterity": !!int "11"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+11"
  - "name": "Survival"
    "desc": "+5"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, frightened, grappled, paralyzed, petrified, poisoned,\
  \ prone, restrained, stunned"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 15"
"languages": "Celestial, Draconic, Infernal, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "Magical darkness doesn't impede the ayperobo swarm's darkvision."
    "name": "Devil's Sight"
  - "desc": "The ayperobo swarm has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "The ayperobo swarm can occupy another creature's space and vice versa,\
      \ and the swarm can move through any opening large enough for a Tiny creature.\
      \ The ayperobo swarm can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "The ayperobo swarm makes three Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 0 ft., one target. *Hit:*\
      \ 27 (8d4 + 7) piercing damage, or 17 (4d4 + 7) piercing damage if the swarm\
      \ has half of its hit points (65) or fewer."
    "name": "Bite"
  - "desc": "The ayperobo swarm makes a Bite attack. On a hit, the swarm burrows inside\
      \ the creature, dealing an additional 35 (10d6) necrotic damage and taking\
      \ control of the creature. At the start of each of its turns, the target may\
      \ make a DC 17 Constitution saving throw, expelling the ayperobo swarm and taking\
      \ 14 (4d6) piercing damage on a success.\n\nWhile burrowed inside a creature,\
      \ the ayperobo swarm has total cover against attacks targeting them, and no\
      \ longer acts on their own initiative. Instead, they take total control over\
      \ their host, gaining all of its abilities, attacks, and equipment.\n\nThey\
      \ act during the host's turn, taking actions based on their host. If a host\
      \ dies while the ayperobo swarm is burrowed, they leave the host at the end\
      \ of the host's turn, rolling initiative if necessary. Creatures acting as hosts\
      \ to the ayperobo swarm are fully aware of their actions and surroundings, but\
      \ are incapable of physically operating their body."
    "name": "Burrow (Recharge 6)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/ayperobo-swarm-coa.webp"
```
^statblock