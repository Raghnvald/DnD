---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Avarice
Status: WIP
linter-yaml-title-alias: Avarice
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/Humanoid/tiefling
  - Quelle/5e/idrotf
aliases:
  - Avarice
---
# [Avarice](3-Mechanics\CLI\bestiary\npc/avarice-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 269*  

Avarice is a cruel and vindictive tiefling trained in the arcane tradition of evocation. She likes using her magic to destroy things, and her hunger for magic items knows no bounds. Her supreme confidence means that she never backs down from a challenge, even when the odds are clearly stacked against her. Seeing other wizards as a threat, paranoia rules her life.

Avarice has been a member of the Arcane Brotherhood for almost two years. She fantasizes about rising to fame and prominence in record time and hopes that plundering the lost Netherese city of Ythryn will turn her fantasies into reality.

The tiefling has the secret support of the archdevil Levistus, having traded her soul years ago for her first taste of magical power. Levistus speaks to her in dreams and guides her path. Shortly after Avarice arrived in Ten-Towns, Levistus urged her to seek out the Black Sword. Avarice didn't know who or what the Black Sword was until she was approached by cultists of Levistus bearing swordlike shards of chardalyn worn as pendants around their necks. These self-styled Knights of the Black Sword offered her sanctuary in the keep of Caer-Dineval, where they are based. Although she doesn't trust the cultists, they treat her with more respect than anyone else does, and the keep is a safer location than most other places in Ten-Towns.

## Companions

Avarice has a pair of loyal [gargoyles](/3-Mechanics/CLI/bestiary/elemental/gargoyle.md) named Gargle and Gurgle who serve her as bodyguards and scouts. Avarice uses her Rary's telepathic bond spell to stay in telepathic contact with her gargoyles before sending them off on any mission. Avarice also has the support of the Knights of the Black Sword, if she needs to call on their talents.

## Familiar

Avarice's familiar throughout the adventure is a squawking raven named Skelm. It uses the [raven](/3-Mechanics/CLI/bestiary/beast/raven.md) stat block in the "Monster Manual" but is a fiend instead of a beast.

## Spellbook

Avarice's spellbook has white leather covers and vellum pages. The tiefling's personal sigil is burned into the front cover. The book contains the spells Avarice has prepared plus the following additional spells: burning hands, cone of cold, find familiar, ice storm, lightning bolt, rope trick, thunderwave, tongues, wall of fire, and wall of force.

```statblock
"name": "Avarice (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "14"
  - !!int "17"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
"damage_resistances": "cold, fire"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic, Infernal, Orc, Yeti"
"cr": "7"
"traits":
  - "desc": "Avarice is a 10th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 14; +6 to hit with spell attacks). She has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** fire bolt (see \"Actions\" below),\
      \ mage hand, message, minor illusion, prestidigitation\n\n**1st level (4 slots):**\
      \ detect magic, mage armor, magic missile\n\n**2nd level (3 slots):** flaming\
      \ sphere, knock, scorching ray\n\n**3rd level (3 slots):** counterspell, fireball,\
      \ fly\n\n**4th level (3 slots):** banishment, fire shield\n\n**5th level (2\
      \ slots):** Bigby's hand, Rary's telepathic bond"
    "name": "Spellcasting"
  - "desc": "When Avarice dies, her corpse freezes for 9 days, during which time it\
      \ can't be thawed, harmed by fire, animated, or raised from the dead."
    "name": "Icy Doom"
  - "desc": "Avarice wields a staff of frost with 10 charges (see \"Actions\" below)."
    "name": "Special Equipment"
"actions":
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 120 ft., one target. *Hit:* 11\
      \ (2d10) fire damage."
    "name": "Fire Bolt (Cantrip)"
  - "desc": "While holding this staff, Avarice can expend 1 or more of its charges\
      \ to cast one of the following spells from it (spell save DC 14): cone of cold\
      \ (5 charges), fog cloud (1 charge), ice storm (4 charges), or wall of ice (4\
      \ charges). The staff regains 1d6 + 4 charges daily at dawn. If its last charge\
      \ is expended, roll a d20; on a 1, the staff turns to water and is destroyed."
    "name": "Staff of Frost"
"reactions":
  - "desc": "When Avarice is damaged by a creature that she can see within 60 feet\
      \ of her, she can banish that creature to a frigid extradimensional prison for\
      \ 1 minute. While there, the creature is incapacitated and takes 5 (1d10) cold\
      \ damage at the start of each of its turns. At the end of each of its turns,\
      \ the creature can make a DC 14 Charisma saving throw, escaping the prison on\
      \ a success and reappearing in the space it left or in the nearest unoccupied\
      \ space if that space is occupied. A creature that dies in the prison is trapped\
      \ there indefinitely."
    "name": "Banishing Rebuke (Recharges after a Long Rest)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/avarice-idrotf.webp"
```
^statblock