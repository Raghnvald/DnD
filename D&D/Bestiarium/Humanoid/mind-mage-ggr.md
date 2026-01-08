---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/5
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mind Mage
---
# [Mind Mage](3-Mechanics\CLI\bestiary\humanoid/mind-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+5"
  - "name": "Persuasion"
    "desc": "+6"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
  - "desc": "The mage's spellcasting ability is Intelligence (spell save DC 16). It\
      \ can innately cast the following spells, requiring no components:\n\n**At will:**\
      \ [encode thoughts](/3-Mechanics/CLI/spells/encode-thoughts-ggr.md) (see chapter\
      \ 2), friends\n\n**3/day each:** charm person, detect thoughts, mage armor,\
      \ sleep, suggestion\n\n**1/day each:** dominate person, mass suggestion, modify\
      \ memory"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The mage wears a [spies' murmur](/3-Mechanics/CLI/items/spies-murmur-ggr.md)\
      \ (see chapter 5)."
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/mind-mage-ggr.webp"
```
^statblock