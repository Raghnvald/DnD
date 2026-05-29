---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ram Sugar
linter-yaml-title-alias: Ram Sugar
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Humanoid/dragonborn
  - Quelle/5e/cm
aliases:
  - Ram Sugar
---
# [Ram Sugar](3-Mechanics\CLI\bestiary\npc/ram-sugar-cm.md)
*Source: Candlekeep Mysteries p. 132*  

Fanatics are often part of a cult's leadership, using their charisma and dogma to influence and prey on those of weak will. Most are interested in personal power above all else.

```statblock
"name": "Ram Sugar (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "leather armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+4"
  - "name": "Persuasion"
    "desc": "+4"
  - "name": "Religion"
    "desc": "+2"
"damage_resistances": "fire"
"senses": "passive Perception 11"
"languages": "Common, Draconic"
"cr": "2"
"traits":
  - "desc": "Ram Sugar is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 11, +3 to hit with spell attacks). Ram Sugar has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** light, sacred flame, thaumaturgy\n\
      \n**1st level (4 slots):** command, inflict wounds, shield of faith\n\n**2nd\
      \ level (3 slots):** hold person, spiritual weapon"
    "name": "Spellcasting"
  - "desc": "Ram Sugar has advantage on saving throws against being charmed or frightened."
    "name": "Dark Devotion"
"actions":
  - "desc": "Ram Sugar makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "Ram Sugar exhales fire in a 30-foot-long line that is 5 feet wide. Any\
      \ creature in the line must make a DC 11 Dexterity saving throw, taking 7 (2d6)\
      \ fire damage on a failed save, or half as much damage on a successful one."
    "name": "Breath Weapon (Recharges after a Short or Long Rest)"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ram-sugar-cm.webp"
```
^statblock