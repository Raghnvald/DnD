---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/13
  - Monster/Größe/Mittelgroß
  - Monster/Typ/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
  - High Fae Noble
---
# [High Fae Noble](3-Mechanics\CLI\bestiary\fey/high-fae-noble-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

High fae nobles regard themselves as the natural and obvious superiors of all in Eldraine. Many have been given dominion over a small aspect of the natural world; there are dukes and duchesses for each of the seasons, and noble archivists track every promise made and broken within the borders of Eldraine.

High fae nobles use their illusions and innate magic to impress their peers and express their capricious natures. Many adorn themselves with auras of magic that dazzle others, while uttering mocking phrases that magically stun and ridicule their opponents. High fae nobles will spend countless years in mind-bendingly complicated games of political calculus, their alliances ever-shifting as they jockey for favors and status in the Kindly Lord's court.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

```statblock
"name": "High Fae Noble (MCV4EC)"
"size": "Medium"
"type": "fey"
"alignment": "Any alignment"
"ac": !!int "17"
"hp": !!int "175"
"hit_dice": "27d8 + 54"
"modifier": !!int "7"
"stats":
  - !!int "13"
  - !!int "25"
  - !!int "15"
  - !!int "19"
  - !!int "18"
  - !!int "22"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  - "dexterity": !!int "12"
  - "intelligence": !!int "9"
  - "wisdom": !!int "9"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "History"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+14"
  - "name": "Perception"
    "desc": "+9"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Sylvan, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "The high fae radiates dazzling and mollifying magic. Each creature of\
      \ the high fae's choice that starts its turn within 5 feet of the high fae must\
      \ succeed on a DC 19 Wisdom saving throw or have the charmed condition until\
      \ the start of its next turn. While charmed, the creature also has the incapacitated\
      \ condition."
    "name": "Aura of Overwhelming Splendor"
  - "desc": "If the high fae fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The high fae has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The high fae makes two Fae Blade attacks. It can replace one of these\
      \ attacks with Stunning Soliloquy if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (3d8 + 7) force damage."
    "name": "Fae Blade"
  - "desc": "The high fae unleashes a string of magical words. Each creature of the\
      \ high fae's choice within 30 feet of itself must succeed on a DC 19 Wisdom\
      \ saving throw or have the stunned condition for 1 minute. A stunned creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Stunning Soliloquy (Recharge 5-6)"
  - "desc": "The high fae casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 19):\n\
      \n**At will:** detect magic, prestidigitation, suggestion\n\n**1/day each:**\
      \ major image, zone of truth"
    "name": "Spellcasting"
"reactions":
  - "desc": "Immediately after taking damage, the high fae magically has the invisible\
      \ condition and teleports, along with any equipment it is wearing or carrying,\
      \ to an unoccupied space it can see within 30 feet of itself. The invisibility\
      \ lasts until the end of the high fae's next turn."
    "name": "Capricious Step"
  - "desc": "When a creature misses the high fae with an attack roll, the high fae\
      \ magically mocks the creature, dealing 5 (2d4) psychic damage to the attacker."
    "name": "Ridicule"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/high-fae-noble-mcv4ec.webp"
```
^statblock