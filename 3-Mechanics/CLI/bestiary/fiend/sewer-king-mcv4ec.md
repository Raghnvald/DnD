---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sewer King"
---
# [Sewer King](3-Mechanics/CLI/bestiary/fiend/sewer-king-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Sewer kings are hulking, monstrous rats empowered by fiendish blood. This unholy influence gives sewer kings their enormous size, supernatural strength, wicked cunning, and ability to speak.

Deep in the bowels of towns and cities, sewer kings reign over underground vermin, dreaming of the day when rats will overthrow surface dwellers. Rancid saliva drips from a sewer king's maw, and swarms of vermin skitter at the monstrous rat's beck and call.

> [!quote]  
> 
> 'The human world will fall,' whispered the monstrous rat. 'You have but one choice to make: Will you fall with it?'

> [!note] Lord Skitter of Edgewall
> 
> Lord Skitter is a sewer king who lives deep in the ancient dwarven ruins beneath the town of Edgewall, situated in the lands between the realm and the wilds of Eldraine. Deep within these ruins, a human minstrel named Totentanz encountered Lord Skitter and struck a vile bargain. Lord Skitter promised the piper wicked and wondrous powers in exchange for Totentanz luring the townsfolk of Edgewall into the sewer king's subterranean domain to become food for his rat minions.
^lord-skitter-of-edgewall

```statblock
"name": "Sewer King (MCV4EC)"
"size": "Medium"
"type": "fiend"
"alignment": "typically  Lawful Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "8"
  - !!int "12"
  - !!int "11"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 15"
"languages": "Infernal, telepathy 30 ft."
"cr": "2"
"traits":
  - "desc": "The sewer king can comprehend and verbally communicate with any Beast."
    "name": "Beast Speech"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage plus 7 (2d6) acid damage. If the target is a\
      \ creature, it must succeed on a DC 12 Constitution saving throw or have the\
      \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the\
      \ start of the sewer king's next turn."
    "name": "Rancid Bite"
  - "desc": "The sewer king chitters and summons a swarm of rats to its aid. The swarm\
      \ appears in an unoccupied space within 30 feet of the sewer king that the sewer\
      \ king can see. It acts as the sewer king's ally, obeys the sewer king's commands,\
      \ and takes its turn immediately after the sewer king's. The swarm remains until\
      \ it dies, the sewer king dies, or until the sewer king dismisses it as an action."
    "name": "Summon Swarm (1/Day)"
"bonus_actions":
  - "desc": "The sewer king moves up to its speed without provoking opportunity attacks."
    "name": "Skitter"
"source":
  - "MCV4EC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/sewer-king-mcv4ec.webp"
```
^statblock