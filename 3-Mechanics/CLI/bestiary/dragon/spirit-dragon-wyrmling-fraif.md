---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spirit Dragon Wyrmling"
---
# [Spirit Dragon Wyrmling](3-Mechanics/CLI/bestiary/dragon/spirit-dragon-wyrmling-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 277*  

When a dragon egg is found buried among ancient rubble and given the right conditions, a spirit dragon wyrmling might hatch from the egg. Left to its own devices, a wyrmling wanders the ruins that the dragon originated from.

## Spirit Dragons

*Draconic Scions of an Ancient Empire*

Spirit dragons, sometimes called song dragons, are powerful dragons whose powers stem from the magic and history of fallen realms. They embody the spirit of a bygone age, and so as they grow and mature, they develop an erratic control over time.

A spirit dragon's primary motivation is to unearth and study the ruins of the ancient realm from which it arose. Spirit dragons share an innate intellectual curiosity, and many have a deep appreciation for the culture and art of humanoid societies.

Spirit dragons find even the most commonplace melodies moving. A song written in the time and region from which a spirit dragon hails can potentially overwhelm the dragon, driving it to either morose despondence or passionate rage.

No two spirit dragons are exactly alike; each individual bears features distinct to the empire from which it hails. Roll on or choose a result from the Spirit Dragon Origins table to determine which lost realm a spirit dragon is from.

| dice: 1d6 | The Spirit Dragon Traces Its Origins to... |
|-----------|--------------------------------------------|
| 1 | Evermeet, a mythical realm of the elves. |
| 2 | Imaskar, a southern empire of artificers. |
| 3 | Jhaamdath, a prehistoric psiocracy. |
| 4 | Myth Drannor, a legendary city of magic. |
| 5 | Netheril, an empire of arcane secrets. |
| 6 | Ostoria, the first kingdom of the giants. |
^1-the-spirit-dragon-traces-its-origins-to

## Spirit Dragon Lairs

Spirit dragons haunt the ruined cities and buried monuments of ancient empires.

```statblock
"name": "Spirit Dragon Wyrmling (FRAiF)"
"size": "Medium"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "15"
  - !!int "14"
  - !!int "11"
  - !!int "14"
"speed": "30 ft., burrow 20 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "3"
  - "constitution": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
  - "name": "Stealth"
    "desc": "+3"
"damage_resistances": "necrotic"
"senses": "Blindsight 10 ft., Darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic; telepathy 120 ft."
"cr": "2"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Slashing\
      \ damage plus 3 (1d6) Necrotic damage."
    "name": "Rend"
  - "desc": "*Constitution Saving Throw:* DC 12, each creature in a 15-foot <span\
      \ title=\"Player's Handbook (2024)\">Cone</span>. *Failure:* 13 (3d8) Necrotic\
      \ damage. *Success:* Half damage."
    "name": "Ruinous Breath (Recharge 5-6)"
  - "desc": "*Wisdom Saving Throw:* DC 12, each creature that isn't currently affected\
      \ by this breath in a 15-foot <span title=\"Player's Handbook (2024)\">Cone</span>.\
      \ *Failure:* The target's <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is halved, it can't take Reactions, and it can take either an action or a\
      \ <span title=\"Player's Handbook (2024)\">Bonus Action</span> on its turn,\
      \ not both. It repeats the save at the end of each of its turns, ending the\
      \ effect on itself on a success. After 1 minute, it succeeds automatically."
    "name": "Time-Warping Breath"
"regional_effects":
  - "desc": "The region containing an adult or ancient spirit dragon's lair is changed\
      \ by its presence, creating the following effects:\n\n- **Enchanted Acoustics.**\
      \ Creatures within 1 mile of the lair have Advantage on Charisma (Performance)\
      \ checks that involve singing or playing music. Creatures other than the dragon\
      \ and its allies in that area have Disadvantage on saving throws to avoid or\
      \ end the Charmed condition.  \n- **Time Distortion.** While within 1 mile of\
      \ the lair, creatures age at one-tenth the usual rate.  \n\nIf the dragon dies\
      \ or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/spirit-dragon-wyrmling-fraif.webp"
```
^statblock

## Environment

any