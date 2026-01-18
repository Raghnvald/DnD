---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/15
  - Monster/Größe/Riesig
  - Monster/Typ/Drache/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Witchkite
---
# [Witchkite](3-Mechanics\CLI\bestiary\dragon/witchkite-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

While many dragons of Eldraine hoard wealth and material goods, witchkites prefer hoarding forbidden and dangerous magical secrets. The arcane nature of a witchkite's hoard seeps into the dragon's core, granting it spellcasting abilities and twisting its fiery breath into malevolent motes of magical flame.

> [!quote] A quote from Last words of the mostly forgotten adventurer Osval  
> 
> I heard there's an especially fearsome witch around here. Or was it a particularly cruel dragon? The tales were very confu—

> [!note] Dragons of Eldraine
> 
> The dragons of Eldraine, are much like those of other D&D worlds. You can use any dragon stat block for a dragon of Eldraine. On Magic cards, there are red dragons (Opportunistic Dragon (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=532521), Decadent Dragon (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=629724), and Realm-Scorcher Hellkite (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=629646)), bronze dragons (Loch Dragon (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=473173)), and moonstone dragons (Shimmer Dragon (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=612484) and Archive Dragon (https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=629542)). Moonstone dragons are described in "Fizban's Treasury of Dragons."
^dragons-of-eldraine

```statblock
"name": "Witchkite (MCV4EC)"
"size": "Huge"
"type": "dragon"
"subtype": "warlock"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "220"
"hit_dice": "21d12 + 84"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "18"
  - !!int "15"
  - !!int "17"
  - !!int "19"
"speed": "40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+8"
  - "name": "Stealth"
    "desc": "+5"
"damage_resistances": "fire, psychic"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Draconic"
"cr": "15"
"traits":
  - "desc": "If the witchkite fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The witchkite makes two Rend attacks and uses Malevolent Flare once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 16\
      \ (3d6 + 6) slashing damage."
    "name": "Rend"
  - "desc": "The witchkite spits magical, green-tinged flame at one creature it can\
      \ see within 60 feet of itself. The target must make a DC 17 Dexterity saving\
      \ throw. On a failed save, the target takes 22 (5d8) fire damage and suffers\
      \ one of the following effects of the witchkite's choice:\n\n- The target must\
      \ use its reaction to make a melee attack against another creature of the witchkite's\
      \ choice that is within the target's reach.  \n- The target takes 13 (2d12)\
      \ psychic damage.  \n\nOn a successful save, the target takes half as much damage\
      \ only."
    "name": "Malevolent Flare"
  - "desc": "The witchkite casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
      \n**At will:** detect magic, minor illusion, speak with dead\n\n**1/day each:**\
      \ detect thoughts, dimension door, hold monster"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature the witchkite can see moves within 10 feet of it, the\
      \ witchkite emits an enchanting gaze at the creature. The creature must succeed\
      \ on a DC 17 Wisdom saving throw or take 10 (3d6) psychic damage and have the\
      \ charmed condition until the end of its next turn."
    "name": "Enchanting Gaze"
  - "desc": "Immediately after taking damage from a melee attack, the witchkite makes\
      \ one Rend attack against the attacker."
    "name": "Retribution"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/witchkite-mcv4ec.webp"
```
^statblock