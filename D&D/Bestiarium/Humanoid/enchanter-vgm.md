---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/5
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Enchanter
---
# [Enchanter](3-Mechanics\CLI\bestiary\humanoid/enchanter-vgm.md)
*Source: Volo's Guide to Monsters p. 213, Tales from the Yawning Portal*  

Enchanters are specialist wizards who understand how to alter and control minds using magic. They might be personable and interesting, using magic to manipulate people only when banter and conventional persuasion fails, or they might be rude and demanding, using and relying on charmed, obedient minions.

```statblock
"name": "Enchanter (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "5"
"traits":
  - "desc": "The enchanter is a 9th-level spellcaster. Its spellcasting ability is\
      \ Intelligence (spell save DC 14, +6 to hit with spell attacks). The enchanter\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** friends,\
      \ mage hand, mending, message\n\n**1st level (4 slots):** charm person*, mage\
      \ armor, magic missile\n\n**2nd level (3 slots):** hold person*, invisibility,\
      \ suggestion*\n\n**3rd level (3 slots):** fireball, haste, tongues\n\n**4th\
      \ level (3 slots):** dominate beast*, stoneskin\n\n**5th level (2 slots):**\
      \ hold monster*\n\n*Enchantment spell of 1st level or higher"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d6\
      \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"reactions":
  - "desc": "The enchanter tries to magically divert an attack made against it, provided\
      \ that the attacker is within 30 feet of it and visible to it. The enchanter\
      \ must decide to do so before the attack hits or misses.\n\nThe attacker must\
      \ make a DC 14 Wisdom saving throw. On a failed save, the attacker targets the\
      \ creature closest to it, other than the enchanter or itself. If multiple creatures\
      \ are closest, the attacker chooses which one to target."
    "name": "Instinctive Charm (Recharges after the Enchanter Casts an Enchantment\
      \ Spell of 1st level or Higher)"
"source":
  - "VGM"
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/enchanter-vgm.webp"
```
^statblock

## Environment

urban