---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Kharbek
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/cm
aliases:
  - Kharbek
linter-yaml-title-alias: Kharbek
---
# [Kharbek](3-Mechanics\CLI\bestiary\npc/kharbek-cm.md)
*Source: Candlekeep Mysteries p. 167*  

Kharbek, a 145-year-old shield dwarf, is the only survivor of a party of adventurers captured by the Order of the Immortal Lotus. If questioned, Kharbek is able to recall how a member of the Immortal Lotus disguised as a beggar lured the group to the temple, where the adventurers were tortured one by one. Kharbek's weapons rest on a nearby table. If their wounds are healed and levels of exhaustion removed, Kharbek offers to fight alongside the characters as a sign of gratitude.

Kharbek is a mountain dwarf explorer with brown skin, brown eyes, and jet-black hair. They stand just over 4 feet tall and have an athletic build.

## Personality Trait

"I am a zealous worshiper of Moradin and take it upon myself to protect those in need."

## Ideal

"Honesty is the best policy."

## Bond

"When someone helps me, I'm bound by my honor to return the favor."

## Flaw

"I am far too trusting and have a difficult time discerning a lie."

```statblock
"name": "Kharbek (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "leather armor"
"hp": !!int "1"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Nature"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+6"
  - "name": "Survival"
    "desc": "+5"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Dwarvish"
"cr": "1/2"
"traits":
  - "desc": "Kharbek has advantage on Wisdom (Perception) checks that rely on hearing\
      \ or sight."
    "name": "Keen Hearing and Sight"
  - "desc": "Kharbek has 5 levels of exhaustion."
    "name": "Exhaustion"
  - "desc": "Kharbek"
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Kharbek makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, ranged 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/kharbek-cm.webp"
```
^statblock