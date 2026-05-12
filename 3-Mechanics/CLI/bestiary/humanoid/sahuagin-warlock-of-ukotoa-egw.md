---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/sahuagin
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sahuagin Warlock of Uk'otoa"
---
# [Sahuagin Warlock of Uk'otoa](3-Mechanics/CLI/bestiary/humanoid/sahuagin-warlock-of-ukotoa-egw.md)
*Source: Explorer's Guide to Wildemount p. 297*  

The slumbering leviathan Uk'otoa preys on the fears and ambitions of humanoids that brave the depths of the Lucidian Ocean. Countless communities of sahuagin inhabit uncharted pockets of water along the Menagerie Coast, and the most ambitious among them often hear the call of the leviathan in their dreams, urging them to take his power and use it to achieve their blood-soaked dreams.

Sahuagin who answer the call of Uk'otoa tend to have one ambition in common: vengeance against the land dwellers of the Clovis Concord for daring to sail oceans that do not belong to them. As these devotees receive dark boons from their leviathan lord, other sahuagin begin to gather to their side, drawn to their displays of power and seeking their own pathway to power. Over time, these warlocks eventually become empty husks, mere receptacles for Uk'otoa's power, and puppets that the slumbering leviathan can control as he pleases.

```statblock
"name": "Sahuagin Warlock of Uk'otoa (EGW)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "8"
  - !!int "8"
  - !!int "16"
"speed": "30 ft., swim 40 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+1"
  - "name": "Persuasion"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "Common, Sahuagin"
"cr": "3"
"traits":
  - "desc": "The warlock's innate spellcasting ability is Charisma (spell save DC\
      \ 13, +5 to hit with spell attacks). It can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** eldritch blast (see \"Actions\"\
      \ below), minor illusion\n\n**1/day each:** armor of Agathys, arms of Hadar,\
      \ counterspell, crown of madness, invisibility, hunger of Hadar"
    "name": "Innate Spellcasting"
  - "desc": "The warlock has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The warlock can breathe air and water, but it needs to be submerged at\
      \ least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
  - "desc": "The warlock can magically command any shark within 120 feet of it, using\
      \ a limited telepathy."
    "name": "Shark Telepathy"
"actions":
  - "desc": "The warlock makes two attacks: one with its bite and one with its Sword\
      \ of Fathoms."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 4 (1d4 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d10 + 2) slashing damage, and if the target is a creature, it must succeed\
      \ on a DC 13 Constitution saving throw or begin choking. The choking creature\
      \ is incapacitated until the end of its next turn, when the effect ends on it."
    "name": "Sword of Fathoms"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 120 ft., one creature. *Hit:*\
      \ 5 (1d10) force damage."
    "name": "Eldritch Blast (Cantrip)"
"source":
  - "EGW"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/sahuagin-warlock-of-ukotoa-egw.webp"
```
^statblock