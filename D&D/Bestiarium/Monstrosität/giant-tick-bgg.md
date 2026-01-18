---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Tick
---
# [Giant Tick](3-Mechanics\CLI\bestiary\monstrosity/giant-tick-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 153*  

Ticks the size of boars have feasted on the blood of giants for countless ages. Though these parasites are painful nuisances to giants, they can be terrible threats to smaller folk, since a hungry tick will consume the blood of any creature it can catch.

```statblock
"name": "Giant Tick (BGG)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "16"
  - !!int "2"
  - !!int "10"
  - !!int "2"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "2"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:* 10\
      \ (2d6 + 3) piercing damage, and the tick attaches to the target. While attached,\
      \ the tick can't make Proboscis attacks. The tick can detach itself by spending\
      \ 5 feet of its movement. As an action, a creature within reach of the tick\
      \ can try to detach the tick, doing so with a successful DC 13 Strength check."
    "name": "Proboscis"
  - "desc": "The tick deals 10 (2d6 + 3) necrotic damage to one creature it is physically\
      \ attached to, provided that creature isn't a Construct or an Undead, or 17\
      \ (4d6 + 3) necrotic damage if the creature is a Giant. The tick regains hit\
      \ points equal to the damage dealt."
    "name": "Blood Drain"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/giant-tick-bgg.webp"
```
^statblock