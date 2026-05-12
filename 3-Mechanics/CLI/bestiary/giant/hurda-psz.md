---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hurda"
---
# [Hurda](3-Mechanics/CLI/bestiary/giant/hurda-psz.md)
*Source: Plane Shift: Zendikar p. 30*  

Hurdas are huge, semi-humanoid creatures thought to be distantly related to giants. They are primarily employed as heavy labor—hauling stone, shifting earth, and drawing the huge carts of the Goma Fada caravan, for example. They are essentially beasts of burden, no more intelligent than a [baloth](3-Mechanics/CLI/bestiary/beast/baloth-psz.md) or [terastodon](3-Mechanics/CLI/bestiary/beast/terastodon-psz.md)—but significantly more pliable. Murasan hurdas are more aggressive than their calmer Onduan kin, serving as protection for the caravans instead of drawing its carts.

Hurdas are bipedal, but they walk on their hugely developed arms while their tiny, vestigial legs dangle beneath them. Thick tails keep them balanced. Their massive bulk allows them to carry tremendous loads in addition to pulling carts and wagons behind them.

Use [hill giant](3-Mechanics/CLI/bestiary/giant/hill-giant.md) statistics to represent hurdas, replacing the greatclub attack with an unarmed smash attack.

```statblock
"name": "Hurda (PSZ)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "19"
  - !!int "5"
  - !!int "9"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[greatclub](3-Mechanics/CLI/items/greatclub.md)"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"actions":
  - "desc": "The hurda makes two smash attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 18 (3d8 + 5) bludgeoning damage."
    "name": "Smash"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 60/240 ft., one target. *Hit:*\
      \ 21 (3d10 + 5) bludgeoning damage."
    "name": "Rock"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/giant/token/hurda-psz.webp"
```
^statblock