---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Jijibisha Manivarshi
Status: WIP
linter-yaml-title-alias: Jijibisha Manivarshi
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/13
  - Monster/Typ/Unhold/yugoloth
  - Quelle/5e/jttrc
aliases:
  - Jijibisha Manivarshi
---
# [Jijibisha Manivarshi](3-Mechanics\CLI\bestiary\npc/jijibisha-manivarshi-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 128*  

Jijibisha Manivarshi, a vicious soul from the land's past, lurks in the nearby forest. Long ago she made a deal with wicked otherworldly forces that gave her longevity and fiendish powers, a bargain that ultimately resulted in the ruin of Manivarsha.

Despite her fiendish powers, she looks like an ancient, withered human.

```statblock
"name": "Jijibisha Manivarshi (JttRC)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "18"
  - !!int "18"
  - !!int "15"
  - !!int "19"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "Intimidation"
    "desc": "+9"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+8"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "truesight 120 ft., passive Perception 17"
"languages": "Abyssal, Infernal, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "Jijibisha's innate spellcasting ability is Charisma (spell save DC 17).\
      \ Jijibisha can innately cast the following spells, requiring no material components:\n\
      \n**At will:** alter self, clairvoyance, darkness, detect magic, detect thoughts,\
      \ dispel magic, invisibility (self only), suggestion\n\n**3/day each:** dimension\
      \ door, fear, wall of fire\n\n**1/day each:** fire storm, mass suggestion"
    "name": "Innate Spellcasting"
  - "desc": "Jijibisha has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Jijibisha's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Jijibisha can use its Hypnotic Gaze and makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
    "name": "Longsword"
  - "desc": "Jijibisha's eyes sparkle with opalescent light as it targets one creature\
      \ it can see within 30 feet of it. If the target can see Jijibisha, the target\
      \ must succeed on a DC 17 Wisdom saving throw against this magic or be charmed\
      \ until the end of Jijibisha's next turn. The charmed target is stunned. If\
      \ the target's saving throw is successful, the target is immune to Jijibisha's\
      \ gaze for the next 24 hours."
    "name": "Hypnotic Gaze"
  - "desc": "Jijibisha magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 60 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "JttRC"
"image": "/3-Mechanics/CLI/bestiary/npc/token/jijibisha-manivarshi-jttrc.webp"
```
^statblock