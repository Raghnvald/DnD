---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/12
  - Monster/Größe/Riesig
  - Monster/Typ/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fomorian Warlock of the Dark
---
# [Fomorian Warlock of the Dark](3-Mechanics\CLI\bestiary\giant/fomorian-warlock-of-the-dark-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 144*  

Some fomorians search for the arcane glory their kind possessed before their banishment into the Underdark. They forge magical pacts with entities of the dark—perhaps powerful Fey of the Gloaming Court or eldritch entities buried deep in the Underdark. Their pacts give these fomorians power over shadows, allowing them to mold and shape darkness like clay.

## Fomorians

Descended from Annam's son Karontor, fomorians once occupied a place in the giants' ordning between hill and stone giants. In ancient times, they were scholars of magic known for their keen intellect—but also for their inflated egos and sense of entitlement. Karontor exploited these qualities, tempting them with promises of higher standing in the ordning, and incited his descendants to launch an assault on the Feywild. When the assault failed, the fomorians were banished to the Underdark and their god was consigned to a subterranean prison. Subjected to the strange magic of the Underdark, the fomorians' bodies and souls twisted until they became the fomorians of today.

```statblock
"name": "Fomorian Warlock of the Dark (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "13"
  - !!int "20"
  - !!int "9"
  - !!int "14"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Giant, Undercommon"
"cr": "12"
"traits":
  - "desc": "The fomorian has a blood rune inscribed on an effigy or some other object\
      \ in its possession. While holding or wearing the object bearing the rune, the\
      \ giant can use its Corrupting Hex action and Poisoning Rebuke reaction.\n\n\
      The object bearing the blood rune has AC 15; 30 hit points; and immunity to\
      \ necrotic, poison, and psychic damage. The object regains all its hit points\
      \ at the end of every turn, but it turns to dust if reduced to 0 hit points\
      \ or when the fomorian dies. If the rune is destroyed, the fomorian can inscribe\
      \ a blood rune on an object in its possession when it finishes a short or long\
      \ rest."
    "name": "Blood Rune"
  - "desc": "Magical darkness doesn't impede the fomorian's darkvision."
    "name": "Devil's Sight"
  - "desc": "If the fomorian fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The fomorian makes three Greatclub attacks. If the fomorian has its blood\
      \ rune, it can replace one of these attacks with a use of Corrupting Hex."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 15 ft., one target. *Hit:* 19\
      \ (3d8 + 6) bludgeoning damage plus 7 (2d6) necrotic damage."
    "name": "Greatclub"
  - "desc": "The fomorian targets one creature it can see within 60 feet of itself.\
      \ The target must succeed on a DC 16 Charisma saving throw or take 27 (6d8)\
      \ necrotic damage and become cursed for 24 hours. While cursed this way, the\
      \ target's speed is reduced by half, and if it tries to cast a spell, it must\
      \ first succeed on a DC 16 Intelligence check or the spell fails and is wasted."
    "name": "Corrupting Hex (Requires Blood Rune)"
  - "desc": "Magical energy explodes in a 20-foot-radius sphere centered on a point\
      \ the fomorian can see within 120 feet of itself. Each creature in that area\
      \ must make a DC 16 Dexterity saving throw. On a failed save, a creature takes\
      \ 32 (5d12) force damage and has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition. On a successful save, a creature takes half as much damage only."
    "name": "Eldritch Burst"
  - "desc": "The fomorian casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 16):\n\n**At will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [levitate](/3-Mechanics/CLI/spells/levitate-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1/day\
      \ each:** [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [suggestion](/3-Mechanics/CLI/spells/suggestion-xphb.md), [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The fomorian momentarily conjures grasping darkness in a 30-foot-radius\
      \ sphere centered on a point it can see within 120 feet of itself. Each creature\
      \ in that area must succeed on a DC 16 Constitution saving throw or take 11\
      \ (2d10) necrotic damage and have the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ condition until the end of its next turn."
    "name": "Creeping Gloom (Recharge 6)"
"reactions":
  - "desc": "In response to being damaged by a creature the fomorian can see within\
      \ 60 feet of itself, the fomorian forces that creature to make a DC 16 Constitution\
      \ saving throw; on a failed save, the creature has the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ condition until the end of its next turn."
    "name": "Poisoning Rebuke (Requires Blood Rune)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/fomorian-warlock-of-the-dark-bgg.webp"
```
^statblock