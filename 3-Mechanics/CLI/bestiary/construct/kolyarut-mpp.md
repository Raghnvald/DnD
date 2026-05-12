---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct/inevitable
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kolyarut"
---
# [Kolyarut](3-Mechanics/CLI/bestiary/construct/kolyarut-mpp.md)
*Source: Morte's Planar Parade p. 34*  

Created by Primus, the leader of the modrons, the Kolyarut is a wondrous machine capable of forging binding contracts between parties. From the Hall of Concordance in Sigil, the Kolyarut judges the needs of planar beings seeking uniquely binding terms and forges ironclad agreements. Those who break these contracts are pursued by maruts (detailed in *Mordenkainen Presents: Monsters of the Multiverse*) and punished in brutally decisive fashion.

In cases where the terms of a contract or a foundational truth of an agreement come into question, the Kolyarut sends a component part of itself into the planes to seek the truth. Also known as kolyaruts, these manifestations of the great machine function as multiversal investigators and pursue answers to specific quandaries. Once their questions have been satisfied, they report back to their creator, allowing the Kolyarut to impose accurate judgments.

Kolyaruts are four-armed beings of magic and machinery. Like maruts, they are inevitables, beings dedicated to the smooth exaction of laws across the planes. Kolyaruts wield blades with deadly efficiency, allowing them to defend themselves on their excursions and slice through any who obscure the truth.

Occasionally, the Hall of Concordance loans kolyaruts to lawful beings who have inherent interest in the orderly functioning of the multiverse, aiding them in seeking answers of planar importance.

```statblock
"name": "Kolyarut (MPP)"
"size": "Medium"
"type": "construct"
"subtype": "inevitable"
"alignment": "typically  Lawful Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "297"
"hit_dice": "35d8 + 140"
"modifier": !!int "1"
"stats":
  - !!int "25"
  - !!int "12"
  - !!int "19"
  - !!int "25"
  - !!int "22"
  - !!int "18"
"speed": "50 ft., fly 35 ft. (hover)"
"saves":
  - "intelligence": !!int "13"
  - "wisdom": !!int "12"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
"damage_resistances": "thunder; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 22"
"languages": "all"
"cr": "20"
"traits":
  - "desc": "The kolyarut is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "If the kolyarut fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "The kolyarut has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The kolyarut makes four Unerring Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* automatic hit, reach 5 ft., one target. *Hit:*\
      \ 24 force damage plus one of the following effects (choose one or roll a d6):\n\
      \n- **1-2 Disarm.** The target drops one item it is holding of the kolyarut's\
      \ choice.  \n- **3-4 Imbalance.** The target can't take reactions until the\
      \ start of the kolyarut's next turn.  \n- **5-6 Push.** If the target is Large\
      \ or smaller, the target is pushed up to 15 feet away from the kolyarut.  "
    "name": "Unerring Blade"
  - "desc": "The kolyarut moves up to its speed without provoking opportunity attacks\
      \ and can make one Unerring Blade attack against each creature it moves past.\
      \ Whenever it hits a creature with an Unerring Blade attack during this movement,\
      \ each spell of 5th level or lower on the creature ends, and the creature has\
      \ the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition\
      \ until the end of the kolyarut's next turn."
    "name": "Edict of Blades (Recharge 5-6)"
  - "desc": "The kolyarut casts [plane shift](3-Mechanics/CLI/spells/plane-shift.md),\
      \ requiring no material components and using Intelligence as the spellcasting\
      \ ability. The kolyarut can cast the spell normally, or it can cast the spell\
      \ on an unwilling creature it can see within 60 feet of itself. If it uses the\
      \ latter option, the targeted creature must succeed on a DC 18 Charisma saving\
      \ throw or be sent to a teleportation circle in the Hall of Concordance in Sigil."
    "name": "Plane Shift (3/Day)"
"reactions":
  - "desc": "The kolyarut adds 6 to its AC against one attack roll that would hit\
      \ it. To do so, the kolyarut must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/construct/token/kolyarut-mpp.webp"
```
^statblock