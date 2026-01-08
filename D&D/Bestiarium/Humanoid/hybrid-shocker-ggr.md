---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/1
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/simic-hybrid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hybrid Shocker
---
# [Hybrid Shocker](3-Mechanics\CLI\bestiary\humanoid/hybrid-shocker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 218*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```statblock
"name": "Hybrid Shocker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "Simic hybrid"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "30 ft."
"damage_immunities": "lightning"
"senses": "passive Perception 11"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "Any creature that touches the hybrid or hits it with a melee attack while\
      \ within 5 feet of it takes 5 (1d10) lightning damage."
    "name": "Electrified Body"
  - "desc": "The hybrid sheds bright light in a 10-foot radius and dim light for an\
      \ additional 10 feet."
    "name": "Illumination"
"actions":
  - "desc": "The hybrid makes two attacks: one with its shocking touch and one with\
      \ its tentacles."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d8)\
      \ lightning damage."
    "name": "Shocking Touch"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 15 ft., one creature. *Hit:*\
      \ The target is grappled (escape DC 11), and the hybrid pulls the target up\
      \ to 15 feet straight toward it. Until this grapple ends, the target takes 5\
      \ (1d10) lightning damage at the start of each of its turns, and the hybrid\
      \ shocker can't use its tentacles on another creature."
    "name": "Tentacles"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/hybrid-shocker-ggr.webp"
```
^statblock