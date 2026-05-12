---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/dc
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warrior"
---
# [Warrior](3-Mechanics/CLI/bestiary/humanoid/warrior-dc.md)
*Source: Divine Contention*  

```statblock
"name": "Warrior (DC)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "21"
"ac_class": "plate, shield"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
"skillsaves":
  - "name": "Athletics"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+5"
"gear":
  - "longbow"
  - "longsword"
"senses": "passive Perception 15"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The warrior has advantage on initiative rolls."
    "name": "Battle Readiness"
  - "desc": "The warrior's attack rolls score a critical hit on a roll of 19 or 20\
      \ on the d20."
    "name": "Improved Critical"
  - "desc": "The warrior's AC increases by 1."
    "name": "Improved Defense"
  - "desc": "The warrior can reroll a saving throw that it fails, but it must use\
      \ the new result."
    "name": "Indomitable (1/Day)"
  - "desc": "The warrior has one of the following traits of your choice:\n\n- **Attacker.**\
      \ The warrior gains a +2 bonus to attack rolls.  \n- **Defender.** The warrior\
      \ gains the Protection reaction below.  "
    "name": "Martial Role"
  - "desc": "The warrior can use a bonus action on its turn to regain hit points equal\
      \ to 1d10 + its level."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The warrior can attack three times, instead of once, whenever it takes\
      \ the attack action on its turn."
    "name": "Extra Attack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"reactions":
  - "desc": "When a creature the warrior can see attacks a target other than the warrior\
      \ that is within 5 feet of the warrior, the warrior can use their reaction to\
      \ impose disadvantage on the attack roll. The warrior must be wielding a shield."
    "name": "Protection (Defender Only)"
"source":
  - "DC"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/warrior-dc.webp"
```
^statblock