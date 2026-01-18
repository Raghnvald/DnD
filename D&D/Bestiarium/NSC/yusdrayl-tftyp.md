---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tftyp
  - Monster/HG/1
  - Monster/Größe/Klein
  - Monster/Typ/humanoid/kobold
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Yusdrayl
---
# [Yusdrayl](3-Mechanics\CLI\bestiary\npc/yusdrayl-tftyp.md)
*Source: Tales from the Yawning Portal p. 248*  

Kobolds are craven reptilian humanoids that worship evil dragons as demigods and serve them as minions and toadies. Kobolds inhabit dragons' lairs when they can but more commonly infest dungeons, gathering treasures and trinkets to add to their own tiny hoards.

## Strength in Numbers

Kobolds are egg-laying creatures. They mature quickly and can live to be "great wyrms" more than a century old. However, many kobolds perish before they reach the end of their first decade. Physically weak, they are easy prey for predators. This vulnerability forces them to band together. Their superior numbers can win battles against powerful adversaries, but often with massive casualties on the kobold side.

## Tunnelers and Builders

Kobolds make up for their physical ineptitude with a cleverness for trap making and tunneling. Their lairs consist of low tunnels through which they move easily but which hinder larger humanoids. Kobolds also riddle their lairs with traps. The most insidious kobold traps make use of natural hazards and other creatures. A trip wire might connect to a spring-loaded trap that hurls clay pots of flesh-eating green slime or flings crates of venomous giant centipedes at intruders.

## The Lost God

In addition to the dragons they revere, kobolds worship a lesser god named Kurtulmak. Legends speak of how Kurtulmak served as Tiamat's vassal in the Nine Hells until Garl Glittergold, the god of gnomes, stole a trinket from the Dragon Queen's hoard. Tiamat sent Kurtulmak to retrieve the trinket, but Garl Glittergold played a trick on him, collapsing the earth and trapping the kobold god in an underground maze for eternity. For this reason, kobolds hate gnomes and pranks of any kind. Kurtulmak's most devoted worshipers dedicate themselves to finding and releasing their lost god from his prison-maze.

```statblock
"name": "Yusdrayl (TftYP)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+2"
  - "name": "Insight"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "Yusdrayl is a 2nd-level spellcaster. Her spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). She knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** mage hand, prestidigitation, ray\
      \ of frost, shocking grasp\n\n**1st level (4 slots):** burning hands, chromatic\
      \ orb, mage armor"
    "name": "Spellcasting"
  - "desc": "While in sunlight, Yusdrayl has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "Yusdrayl has advantage on an attack roll against a creature if at least\
      \ one of her allies is within 5 feet of the creature and the ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage."
    "name": "Dagger"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/yusdrayl-tftyp.webp"
```
^statblock