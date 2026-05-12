---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Koh Tam"
---
# [Koh Tam](3-Mechanics/CLI/bestiary/npc/koh-tam-coa.md)
*Source: Chains of Asmodeus p. 265*  

Koh Tam is the powerful head priest of Kelemvor, god of death and the dead, at the Waterdeep cathedral. Seeking to know all the secrets of the realms of the dead, Koh Tam petitioned his god for permission to explore the Nine Hells. The young priest set forth into the infernal realm where he bore witness to horrors beyond mortal imagination and encountered fiendish creatures whose power greatly outmatched his own. The experience forever changed the priest. Rather than sate his curiosity, the journey only served to further incite Koh Tam's fascination with the infernal. He devoted himself to the study of arcane books concerning the subject and collected an impressive number of infernal relics.

In the many years since, the head priest has made several expeditions into the Nine Hells and has had many more encounters with fearsome devils. Koh Tam can thus be considered the expert authority on the infernal realm. He has advised many adventurers who seek to venture into the Nine Hells and has also prevented a fair number of foul creatures from fleeing that realm into mortal worlds. Though he remains devoted to the laws of Kelemvor, so much exposure to the infernal has changed Koh Tam in mind and body. The head priest has many habits and mannerisms that might seem strange to other mortals, and he has a unique perspective colored by his experience with the Nine Hells.

```statblock
"name": "Koh Tam (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "breastplate, shield"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "19"
  - !!int "20"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "History"
    "desc": "+8"
  - "name": "Insight"
    "desc": "+9"
  - "name": "Religion"
    "desc": "+8"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Abyssal, Celestial, Common, Infernal"
"cr": "10"
"actions":
  - "desc": "*Melee Spell Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) radiant damage."
    "name": "Arbiter's Touch"
  - "desc": "Koh Tam judges a creature within 60 feet of him. The target must succeed\
      \ on a DC 17 Wisdom saving throw or take 50 (10d8 + 5) radiant damage. If\
      \ the target had fewer hit points than their maximum prior to this attack, the\
      \ creature takes 70 (10d12 + 5) radiant damage instead."
    "name": "Judgement"
  - "desc": "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target. *Hit:*\
      \ 70 (10d12 + 5) radiant damage, and the target has the blinded condition\
      \ until the start of Koh Tam's next turn."
    "name": "Arbiter's Light (Recharge 4-6)"
  - "desc": "Koh Tam casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 17):\n\n**At will:** False Life, Gentle Repose, Lesser\
      \ Restoration, Protection from Evil and Good, Speak with Dead\n\n**1/day each:**\
      \ Antilife Shell, Blight, Death Ward, Dispel Evil and Good, Greater Restoration,\
      \ Raise Dead, Regenerate, Revivify, Spiritual Weapon"
    "name": "Spellcasting"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/koh-tam-coa.webp"
```
^statblock