---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demon"
---
# [Demon](3-Mechanics/CLI/bestiary/fiend/demon-psx.md)
*Source: Plane Shift: Ixalan p. 36*  

Resembling twisted bats, the demons of Ixalan are the spawn of a bat-god, the source of all darkness. While the sun's aspects include destruction as well as creation and growth, the demons represent stagnation and decay. The sun consumes in glorious fire; demons work through rot and degeneration. They are said to be active at night, when the sun is hidden, and their efforts are directed toward preventing the sun from rising again each morning. In the meantime, they spread plague and corruption across the land. The [vrock](3-Mechanics/CLI/bestiary/fiend/vrock.md) in the "Monster Manual" is a good representation of Ixalan's demons.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

```statblock
"name": "Demon (PSX)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "18"
  - !!int "8"
  - !!int "13"
  - !!int "8"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "4"
  - "charisma": !!int "2"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Abyssal, telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "The demon has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The demon makes two attacks: one with its beak and one with its talons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d10 + 3) slashing damage."
    "name": "Talons"
  - "desc": "A 15-foot-radius cloud of toxic spores extends out from the demon. The\
      \ spores spread around corners. Each creature in that area must succeed on a\
      \ DC 14 Constitution saving throw or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned).\
      \ While [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way,\
      \ a target takes 5 (1d10) poison damage at the start of each of its turns.\
      \ A target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success. Emptying a [vial of holy water](3-Mechanics/CLI/items/holy-water-flask.md)\
      \ on the target also ends the effect on it."
    "name": "Spores (Recharge 6)"
  - "desc": "The demon emits a horrific screech. Each creature within 20 feet of it\
      \ that can hear it and that isn't a demon must succeed on a DC 14 Constitution\
      \ saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the end of the demon's next turn."
    "name": "Stunning Screech (1/Day)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/fiend/token/demon-psx.webp"
```
^statblock