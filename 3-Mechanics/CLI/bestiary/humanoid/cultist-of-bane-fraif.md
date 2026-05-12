---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cultist of Bane"
---
# [Cultist of Bane](3-Mechanics/CLI/bestiary/humanoid/cultist-of-bane-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 254*  

Cultists of Bane sow strife, either by directly bullying others or by abusing existing power structures to create division and oppression. Although many cultists of Bane are tyrants capable of influencing large groups of lackeys, other cultists prefer to operate from the shadows. These cultists use their forceful personalities to counsel well-intentioned rulers, turning benign organizations into dictatorships and twisting leaders into tyrants. They tattoo Bane's symbol on their hands as a sign of devotion.

## Cultists

*Wicked Zealots of the Dead Three*

The adventurers Bane, Bhaal, and Myrkul seized divinity but were slain for their hubris. All three have been reborn and are now known as the Dead Three. Each of the Dead Three has inspired wicked cults that follow their paths of tyranny, murder, and necromancy.

More than any other gods, the Dead Three directly influence Faerûn—and particularly the city of Baldur's Gate—in malign ways. Cultists who receive orders from their patron god directly are often the most ambitious and most dangerous.

```statblock
"name": "Cultist of Bane (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "142"
"hit_dice": "19d8 + 57"
"modifier": !!int "6"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "19"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "8"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+8"
"gear":
  - "breastplate"
  - "holy symbol"
"senses": "passive Perception 18"
"languages": "Common"
"cr": "9"
"traits":
  - "desc": "The cultist regains 10 <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ at the start of each of its turns if it is Bloodied and has at least 1 <span\
      \ title=\"Player's Handbook (2024)\">Hit Point</span>."
    "name": "Determined Survivor"
"actions":
  - "desc": "The cultist makes three attacks, using Gauntlet or Oppressive Burst in\
      \ any combination. It can replace one attack with a use of Spellcasting to cast\
      \ Dominate Person, if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 17 (3d8 + 4) Bludgeoning\
      \ damage."
    "name": "Gauntlet"
  - "desc": "*Ranged Attack Roll:* +8, range 120 ft. *Hit:* 16 (2d10 + 5) Psychic\
      \ damage, and the target can't take Reactions until the start of the cultist's\
      \ next turn."
    "name": "Oppressive Burst"
  - "desc": "The cultist casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 16):\n\n**2/day each:** Calm Emotions, Detect Thoughts\n\
      \n**1/day:** Dominate Person"
    "name": "Spellcasting"
"reactions":
  - "desc": "Trigger: The cultist is hit by an attack roll. _Response:_ The cultist\
      \ makes one Gauntlet or Oppressive Burst attack against the triggering creature."
    "name": "Counterattack"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/cultist-of-bane-fraif.webp"
```
^statblock

## Environment

urban