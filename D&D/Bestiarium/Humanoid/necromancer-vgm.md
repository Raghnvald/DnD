---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/9
  - Monster/Habitat/Wüste
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Necromancer
---
# [Necromancer](3-Mechanics\CLI\bestiary\humanoid/necromancer-vgm.md)
*Source: Volo's Guide to Monsters p. 217, Tales from the Yawning Portal, Dragon of Icespire Peak*  

Necromancers are specialist wizards who study the interaction of life, death, and undeath. Some like to dig up corpses to create undead slaves. A few use their powers for good, becoming hunters of the undead and risking their lives to save others.

```statblock
"name": "Necromancer (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "History"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
  - "desc": "The necromancer is a 12th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 15, +7 to hit with spell attacks). The necromancer\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** chill\
      \ touch, dancing lights, mage hand, mending\n\n**1st level (4 slots):** false\
      \ life*, mage armor, ray of sickness*\n\n**2nd level (3 slots):** blindness/deafness*,\
      \ ray of enfeeblement*, web\n\n**3rd level (3 slots):** animate dead*, bestow\
      \ curse*, vampiric touch*\n\n**4th level (3 slots):** blight*, dimension door,\
      \ stoneskin\n\n**5th level (2 slots):** Bigby's hand, cloudkill\n\n**6th level\
      \ (1 slots):** circle of death*\n\n*Necromancy spell of 1st level or higher"
    "name": "Spellcasting"
  - "desc": "When necromancer kills a creature that is neither a construct nor undead\
      \ with a spell of 1st level or higher, the necromancer regains hit points equal\
      \ to twice the spell's level, or three times if it is a necromancy spell."
    "name": "Grim Harvest (1/Turn)"
"actions":
  - "desc": "*Melee Spell Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 5\
      \ (2d4) necrotic damage."
    "name": "Withering Touch"
"source":
  - "VGM"
  - "TftYP"
  - "DIP"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/necromancer-vgm.webp"
```
^statblock

## Environment

desert, urban