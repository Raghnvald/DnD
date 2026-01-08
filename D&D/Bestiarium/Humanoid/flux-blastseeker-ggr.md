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
- Flux Blastseeker
---
# [Flux Blastseeker](3-Mechanics\CLI\bestiary\humanoid/flux-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Flux Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "12"
  - !!int "20"
  - !!int "9"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "8"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "5"
"traits":
  - "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell\
      \ save DC 16, +8 to hit with spell attacks). The blastseeker can innately cast\
      \ the following spells, requiring no components other than its Izzet gear, which\
      \ doesn't function for others:\n\n**3/day each:** mage armor (self only), scorching\
      \ ray\n\n**1/day each:** banishment, cone of cold, dimension door, fireball,\
      \ ice storm"
    "name": "Innate Spellcasting"
  - "desc": "The blastseeker can create an additional effect immediately after casting\
      \ a spell. Roll a d6 to determine the effect: 1-3. The blastseeker teleports,\
      \ swapping places with a creature it can see within 30 feet of it. 4-6. The\
      \ blastseeker and each creature within 10 feet of it must succeed on a DC 16\
      \ Constitution saving throw or take 11 (2d10) thunder damage."
    "name": "Fluxbending Overcast (Recharge 5-6)"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6)\
      \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
    "name": "Quarterstaff"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/flux-blastseeker-ggr.webp"
```
^statblock