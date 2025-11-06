---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/7
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Firefist
---
# [Firefist](3-Mechanics\CLI\bestiary\humanoid/firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+4"
  - "name": "Religion"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
  - "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). It has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** fire bolt, light, sacred\
      \ flame, spare the dying\n\n**1st level (4 slots):** guiding bolt, healing word,\
      \ heroism, shield of faith\n\n**2nd level (3 slots):** lesser restoration, scorching\
      \ ray\n\n**3rd level (3 slots):** blinding smite, crusader's mantle, revivify\n\
      \n**4th level (3 slots):** banishment, wall of fire\n\n**5th level (1 slots):**\
      \ flame strike"
    "name": "Spellcasting"
"actions":
  - "desc": "The firefist makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Greatsword"
"reactions":
  - "desc": "When the firefist or one creature it can see within 30 feet of it makes\
      \ an attack roll, the firefist grants a +10 bonus to that roll."
    "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/firefist-ggr.webp"
```
^statblock