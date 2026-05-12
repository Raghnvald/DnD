---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mage of Usamigaras"
---
# [Mage of Usamigaras](3-Mechanics/CLI/bestiary/humanoid/mage-of-usamigaras-qftis.md)
*Source: Quests from the Infinite Staircase p. 206*  

The common members of the Mages of Usamigaras use their magical talents to charm and deceive the faction's opponents.

## Mages of Usamigaras

The Mages of Usamigaras are Cynidicean spellcasters who worship Usamigaras, a god of magic, messengers, and lies. They hide their identities and intentions behind silver masks depicting the face of their god. Secrecy is key among the Mages of Usamigaras. Members whisper in the presence of outsiders and pepper their speech with lies, even obvious ones. Such behavior isn't rude among members, who view deceit as worthy of celebration, not chastisement.

```statblock
"name": "Mage of Usamigaras (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+3"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/8"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +4 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 7 (1d10 + 2) force damage."
    "name": "Arcane Burst"
  - "desc": "The mage casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 12):\n\n**At will:** [Light](3-Mechanics/CLI/spells/light.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md), [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\
      \n**1/day each:** [Charm Person](3-Mechanics/CLI/spells/charm-person.md), [Disguise\
      \ Self](3-Mechanics/CLI/spells/disguise-self.md), [Silent Image](3-Mechanics/CLI/spells/silent-image.md)"
    "name": "Spellcasting"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/mage-of-usamigaras-qftis.webp"
```
^statblock