---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Xardorok Sunblight
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Humanoid/dwarf
  - Quelle/5e/idrotf
aliases:
  - Xardorok Sunblight
linter-yaml-title-alias: Xardorok Sunblight
---
# [Xardorok Sunblight](3-Mechanics\CLI\bestiary\npc/xardorok-sunblight-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 287*  

Xardorok Sunblight leads the Sunblight clan of duergar which, until recently, dwelled in the subterranean depths beneath the Spine of the World. In the guise of Deep Duerra, the duergar god of conquest, the archdevil Asmodeus visited Xardorok and urged him to conquer Icewind Dale, beginning with Ten-Towns.

## Dark Obsession

Xardorok is obsessed with chardalyn and can't stand the thought of anyone else possessing it. He must have all the chardalyn that Icewind Dale has to offer and is using his ample supply to forge a dragon, which he plans to unleash upon Ten-Towns. See the sidebar for more information about chardalyn.

## Father of Nine

Xardorok has been married three times and has sired nine children. He killed his first wife, Thizrun, for plotting to assassinate him. His second wife, Yrraska, was killed in a tunnel collapse along with two of their daughters. His third wife, Marral, was killed during a raid against a mind flayer enclave, along with another daughter and three sons. Xardorok killed his eldest son, Ulthoon, son of Thizrun, for plotting to overthrow him. His surviving offspring are two sons given to him by Marral, named Durth and Nildar.

## Clad in Chardalyn

Xardorok wears the following nonmagical items fashioned from chardalyn: a nine-spired crown (two intact spires representing his two surviving sons, and seven partially broken-off spires representing his seven dead children), a suit of chain mail, and a spiked gauntlet.

```statblock
"name": "Xardorok Sunblight (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "chain mail"
"hp": !!int "93"
"hit_dice": "11d8 + 44"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "18"
  - !!int "12"
  - !!int "13"
  - !!int "18"
"speed": "25 ft."
"saves":
  - "wisdom": !!int "4"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+4"
  - "name": "Deception"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+7"
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Common, Dwarvish"
"cr": "5"
"traits":
  - "desc": "Xardorok's innate spellcasting ability is Charisma (spell save DC 15,\
      \ +7 to hit with spell attacks). He can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** eldritch blast (see \"Actions\"\
      \ below), mage hand\n\n**1/day each:** hold person, suggestion"
    "name": "Innate Spellcasting"
  - "desc": "Xardorok has advantage on saving throws against poison, spells, and illusions,\
      \ as well as to resist being charmed or paralyzed."
    "name": "Duergar Resilience"
  - "desc": "While in sunlight, Xardorok has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Xardorok attacks twice with a weapon or casts eldritch blast twice."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) piercing damage, or 8 (2d4 + 3) piercing damage while Xardorok is enlarged."
    "name": "Spiked Gauntlet"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 120 ft., one creature. *Hit:*\
      \ 9 (1d10 + 4) force damage."
    "name": "Eldritch Blast (Cantrip)"
  - "desc": "For 1 minute, Xardorok magically increases in size, along with anything\
      \ he is wearing or carrying. While enlarged, Xardorok is Large, doubles his\
      \ damage dice on Strength-based weapon attacks (included in his attacks), and\
      \ makes Strength checks and Strength saving throws with advantage. If Xardorok\
      \ lacks the room to become Large, he attains the maximum size possible in the\
      \ space available."
    "name": "Enlarge (Recharges after a Short or Long Rest)"
  - "desc": "Xardorok magically turns invisible until he attacks, he casts a spell,\
      \ he uses his Enlarge, or his concentration is broken (as if concentrating on\
      \ a spell). Any equipment Xardorok wears or carries is invisible with him."
    "name": "Invisibility (Recharge 4-6)"
"reactions":
  - "desc": "When Xardorok is damaged by a creature within 60 feet of him that he\
      \ can see, the creature that damaged him is engulfed in hellish flames and must\
      \ make a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Hellish Rebuke (2/Day)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/xardorok-sunblight-idrotf.webp"
```
^statblock