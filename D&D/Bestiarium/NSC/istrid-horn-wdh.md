---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Istrid Horn
Status: WIP
linter-yaml-title-alias: Istrid Horn
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Humanoid/dwarf
  - Quelle/5e/wdh
aliases:
  - Istrid Horn
---
# [Istrid Horn](3-Mechanics\CLI\bestiary\npc/istrid-horn-wdh.md)
*Source: Waterdeep: Dragon Heist p. 199*  

Istrid is regarded as the Black Network's Master of Trade and Coin in Waterdeep. The shield dwarf operates an illegal lending operation out of a heavily guarded warehouse in the Dock Ward, offering loans to those in need of coin. Her interest rates are comparable to those of her competitors (including noble families of bankers such as the Cassalanters and the Irlingstars), but the penalties for not paying back Istrid's loans are severe.

Istrid worships Vergadain, the dwarven god of wealth and luck. She likes having others indebted to her, and she employs thugs and enforcers to collect on her loans. If those resources prove inadequate, Istrid can call on her old adventuring companions for assistance.

## The Doom Raiders

The Doom Raiders were five unscrupulous adventurers who liked to plunder lich lairs (called "dooms" by some). They gave up adventuring to join the Black Network and came to Waterdeep three years ago with plans to establish a Zhentarim foothold in the city. In that time, they have forged alliances with various nobles and guilds and run afoul of others, all the while fending off Harper spies.

```statblock
"name": "Istrid Horn (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "25 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+4"
  - "name": "Religion"
    "desc": "+3"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Dwarvish"
"cr": "8"
"traits":
  - "desc": "Istrid is a 9th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (spell save DC 14, +6 to hit with spell attacks) She has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** light, mending, sacred flame,\
      \ spare the dying\n\n**1st level (4 slots):** divine favor, guiding bolt, healing\
      \ word, shield of faith\n\n**2nd level (3 slots):** lesser restoration, magic\
      \ weapon, hold person, silence, spiritual weapon\n\n**3rd level (3 slots):**\
      \ beacon of hope, crusader's mantle, dispel magic, revivify, spirit guardians,\
      \ water walk\n\n**4th level (3 slots):** banishment, freedom of movement, guardian\
      \ of faith, stoneskin\n\n**5th level (1 slots):** flame strike, mass cure wounds,\
      \ hold monster"
    "name": "Spellcasting"
  - "desc": "Istrid has advantage on saving throws against being poisoned."
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Istrid makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 8 (2d6\
      \ + 1) bludgeoning damage."
    "name": "Maul"
  - "desc": "Istrid magically pinpoints precious metals and stones, such as coins\
      \ and gems, within 60 feet of her."
    "name": "Treasure Sense (3/Day)"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/istrid-horn-wdh.webp"
```
^statblock