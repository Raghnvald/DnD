---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Conjurer
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/6
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/vgm
aliases:
  - Conjurer
---
# [Conjurer](3-Mechanics\CLI\bestiary\humanoid/conjurer-vgm.md)
*Source: Volo's Guide to Monsters p. 212, Tales from the Yawning Portal*  

Conjurers are specialist wizards who summon creatures from other planes and create materials out of thin air. Some conjurers use their magic to bolster armies or destroy enemies on battlefields, while others use summoned creatures to guard their lairs.

```statblock
"name": "Conjurer (VGM)"
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
"cr": "6"
"traits":
  - "desc": "The conjurer is a 9th-level spellcaster. Its spellcasting ability is\
      \ intelligence (spell save DC 14, +6 to hit with spell attacks). The conjurer\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** acid\
      \ splash, mage hand, poison spray, prestidigitation\n\n**1st level (4 slots):**\
      \ mage armor, magic missile, unseen servant*\n\n**2nd level (3 slots):** cloud\
      \ of daggers*, misty step*, web*\n\n**3rd level (3 slots):** fireball, stinking\
      \ cloud*\n\n**4th level (3 slots):** Evard's black tentacles*, stoneskin\n\n\
      **5th level (2 slots):** cloudkill*, conjure elemental*\n\n*Conjuration spell\
      \ of 1st level or higher"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the conjurer teleports up to 30 feet to an unoccupied\
      \ space that it can see. If it instead chooses a space within range that is\
      \ occupied by a willing Small or Medium creature, they both teleport, swapping\
      \ places."
    "name": "Benign Transportation (Recharges after the Conjurer Casts a Conjuration\
      \ Spell of 1st Level or Higher)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "VGM"
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/conjurer-vgm.webp"
```
^statblock

## Environment

urban