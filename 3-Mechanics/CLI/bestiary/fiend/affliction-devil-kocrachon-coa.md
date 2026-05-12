---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Affliction Devil (Kocrachon)"
---
# [Affliction Devil (Kocrachon)](3-Mechanics/CLI/bestiary/fiend/affliction-devil-kocrachon-coa.md)
*Source: Chains of Asmodeus p. 236*  

Masters of torture and pain, kocrachons are some of the most respected lesser devils in the Nine Hells. Each is driven to break the greatest number of creatures during their lifespan—the bigger and more dangerous their charges, the better. The most effective kocrachons study under other torturers, or in infernal schools, to best understand the physiologies of any victim they might come across. Perhaps due to their nature as clandestine torturers, kocrachons abhor direct conflict, choosing instead to flee if given the option.

## Devils with Purpose

They're insect-like and have a brightly colored carapace, with retractable wings, multiple arms and legs, and pincer-like hands. Even their heads appear strangely insectoid, often with multiple proboscises, eyes and false eyes, and waving antennae. Kocrachon inject a lethal poison into victims and, if they acquire the information they needed, may cure said poison.

## Flame and Ice

Though they are just as comfortable in the fires of the Nine Hells as any other devil, unlike many other of their peers, kocrachons are also resilient to the cold. This makes them useful in Stygia and Cania, where they are often employed by the archdevils of those layers to wring information from recalcitrant opponents. Their affinity to the cold also provides kocrachons with other, more interesting avenues of torture.

```statblock
"name": "Affliction Devil (Kocrachon) (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "4"
"stats":
  - !!int "16"
  - !!int "19"
  - !!int "15"
  - !!int "17"
  - !!int "12"
  - !!int "14"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  - "dexterity": !!int "8"
  - "intelligence": !!int "7"
"skillsaves":
  - "name": "Deception"
    "desc": "+6"
  - "name": "Intimidation"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Infernal, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "Magical darkness doesn't impede the kocrachon's darkvision."
    "name": "Devil's Sight"
  - "desc": "A creature afflicted with this disease has the poisoned condition until\
      \ the disease ends. While diseased, creatures gain no benefits from a long rest,\
      \ gaining exhaustion when necessary. If a creature dies while afflicted with\
      \ Infernal Rot, its corpse transforms into a newborn kocrachon after 4 (1d8)\
      \ days."
    "name": "Infernal Rot"
  - "desc": "The kocrachon has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The kocrachon gains a +1 bonus to attack and damage rolls for each different\
      \ creature it damaged on its previous turn."
    "name": "Sadism"
"actions":
  - "desc": "The kocrachon makes three Claw attacks. It can replace one of the attacks\
      \ with a Proboscis attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (1d12 + 4) piercing damage plus 14 (4d6) poison damage. Creatures damaged\
      \ by this attack must succeed on a DC 16 Constitution saving throw or suffer\
      \ the Infernal Rot disease."
    "name": "Proboscis"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/affliction-devil-kocrachon-coa.webp"
```
^statblock