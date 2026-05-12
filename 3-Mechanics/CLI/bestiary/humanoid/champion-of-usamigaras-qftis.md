---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Champion of Usamigaras"
---
# [Champion of Usamigaras](3-Mechanics/CLI/bestiary/humanoid/champion-of-usamigaras-qftis.md)
*Source: Quests from the Infinite Staircase p. 206*  

Champions are blessed by Usamigaras to advance the faction by any means necessary. They boast a greater repertoire of spells than their fellows and can radiate an aura of illusions to confuse their foes.

## Mages of Usamigaras

The Mages of Usamigaras are Cynidicean spellcasters who worship Usamigaras, a god of magic, messengers, and lies. They hide their identities and intentions behind silver masks depicting the face of their god. Secrecy is key among the Mages of Usamigaras. Members whisper in the presence of outsiders and pepper their speech with lies, even obvious ones. Such behavior isn't rude among members, who view deceit as worthy of celebration, not chastisement.

```statblock
"name": "Champion of Usamigaras (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
  - "desc": "The champion makes two Arcane Burst attacks or makes one Arcane Burst\
      \ attack and uses Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 8 (1d10 + 3) force damage."
    "name": "Arcane Burst"
  - "desc": "The champion casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 13):\n\n**At will:** [Light](3-Mechanics/CLI/spells/light.md),\
      \ [Mage Armor](3-Mechanics/CLI/spells/mage-armor.md) (self only), [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\n**2/day each:**\
      \ [Charm Person](3-Mechanics/CLI/spells/charm-person.md), [Disguise Self](3-Mechanics/CLI/spells/disguise-self.md),\
      \ [Silent Image](3-Mechanics/CLI/spells/silent-image.md)\n\n**1/day each:**\
      \ [Crown of Madness](3-Mechanics/CLI/spells/crown-of-madness.md), [Shatter](3-Mechanics/CLI/spells/shatter.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The champion emits an aura of ghostly illusions that fills a 10-foot-radius\
      \ sphere centered on itself. While this aura is active, creatures have disadvantage\
      \ on attack rolls against the champion and any of the champion's allies that\
      \ are in the aura. The aura moves with the champion and lasts for 1 minute,\
      \ until the champion has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, or until the champion uses another bonus action to end the aura."
    "name": "Aura of Deception (1/Day)"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/champion-of-usamigaras-qftis.webp"
```
^statblock