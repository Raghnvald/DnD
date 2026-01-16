---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/vgm
- new/monster/cr/3
- new/monster/environment/urban
- new/monster/size/medium
- new/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Illusionist
---
# [Illusionist](3-Mechanics\CLI\bestiary\humanoid/illusionist-vgm.md)
*Source: Volo's Guide to Monsters p. 214, Tales from the Yawning Portal*  

Illusionists are specialist wizards who twist light, sound, shadow, and even minds to create false and quasi-real effects. They can be flamboyant and use their powers in spectacular and obvious ways, or quiet and subtle, using their magic to conceal the truth.

```statblock
"name": "Illusionist (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "13"
  - !!int "16"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "History"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": "any four languages"
"cr": "3"
"traits":
  - "desc": "The illusionist is a 7th-level spellcaster. its spellcasting ability\
      \ is Intelligence (spell save DC 13, +5 to hit with spell attacks). The illusionist\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** dancing\
      \ lights, mage hand, minor illusion, poison spray\n\n**1st level (4 slots):**\
      \ color spray*, disguise self*, mage armor, magic missile\n\n**2nd level (3\
      \ slots):** invisibility*, mirror image*, phantasmal force*\n\n**3rd level (3\
      \ slots):** major image*, phantom steed*\n\n**4th level (1 slots):** phantasmal\
      \ killer*\n\n*Illusion spell of 1st level or higher"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the illusionist projects an illusion that makes the\
      \ illusionist appear to be standing in a place a few inches from its actual\
      \ location, causing any creature to have disadvantage on attack rolls against\
      \ the illusionist. The effect ends if the illusionist takes damage, it is incapacitated,\
      \ or its speed becomes 0."
    "name": "Displacement (Recharges after the Illusionist Casts an Illusion Spell\
      \ of 1st Level or Higher)"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6\
      \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"source":
  - "VGM"
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/illusionist-vgm.webp"
```
^statblock

## Environment

urban