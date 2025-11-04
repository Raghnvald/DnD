---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/vgm
- Monster/cr/4
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Booyahg Slave of the Archfey
---
# [Booyahg Slave of the Archfey](3-Mechanics\CLI\bestiary\humanoid/booyahg-slave-of-the-archfey-vgm.md)
*Source: Volo's Guide to Monsters p. 42*  

This goblin warlock serves a patron who can extract payment in flesh if the goblin doesn't do as promised. Often this patron is a coven of hags serving as the tribe's boss, a fiend that has made its way into the world, or an undying lord such as a lich or a vampire. (For more information on undying lord patrons, see the "Sword Coast Adventurer's Guide").

## Booyahgs

Spellcasters of any sort among the goblins are rare. Goblins typically lack the intelligence and patience needed to learn and practice wizardry, and they fare poorly even when given access to the necessary training and knowledge. Sorcerers are less prevalent among them than in many other races, and Khurgorbaeyag seems to dislike sharing his divine power with his followers. And although many goblins would readily offer anything to have the abilities of a warlock, the patrons that grant such power know a goblin is unlikely to be able to uphold its end of any bargain.

Even when a goblin is born with the ability to become a spellcaster, the knowledge and talent necessary to carry on the tradition rarely persists for more than a couple of generations. Because they have so little experience with magic, goblins make no distinction between its forms. To them all magic is "booyahg," and the word is part of the name they give to any of its practitioners.

A goblin with access to booyahg becomes a member of the lashers and can often rise to the role of boss.

```statblock
"name": "Booyahg Slave of the Archfey (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "14 with mage armor"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "1"
"stats":
  - !!int "9"
  - !!int "13"
  - !!int "11"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+2"
  - "name": "Deception"
    "desc": "+6"
  - "name": "Nature"
    "desc": "+2"
  - "name": "Persuasion"
    "desc": "+6"
"condition_immunities": "charmed"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "any two languages (usually Sylvan), Goblin"
"cr": "4"
"traits":
  - "desc": "The goblin is an 11th-level spellcaster. Its spellcasting ability is\
      \ Charisma (spell save DC 14, +6 to hit with spell attacks). It regains its\
      \ expended spell slots when it finishes a short or long rest. It knows the following\
      \ warlock spells:\n\n**Cantrips (at will):** dancing lights, eldritch blast,\
      \ friends, mage hand, minor illusion, prestidigitation, vicious mockery\n\n\
      **1st-5th level (3 slots):** blink, charm person, dimension door, dominate beast,\
      \ faerie fire, fear, hold monster, misty step, phantasmal force, seeming, sleep"
    "name": "Spellcasting"
  - "desc": "The goblin's innate spellcasting ability is Charisma. It can innately\
      \ cast the following spells (spell save DC 15), requiring no material components:\n\
      \n**At will:** disguise self, mage armor (self only), silent image, speak with\
      \ animals\n\n**1/day:** conjure fey"
    "name": "Innate Spellcasting"
  - "desc": "The goblin"
    "name": "Nimble Escape"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "In response to taking damage, the goblin turns invisible and teleports\
      \ up to 60 feet to an unoccupied space it can see. It remains invisible until\
      \ the start of its next turn or until it attacks, makes a damage roll, or casts\
      \ a spell."
    "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
  - "VGM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/booyahg-slave-of-the-archfey-vgm.webp"
```
^statblock