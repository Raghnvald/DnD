---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Maw of Yeenoghu"
---
# [Maw of Yeenoghu](3-Mechanics/CLI/bestiary/fiend/maw-of-yeenoghu-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 159*  

Hill giants are known for their voracious appetites, which can attract the attention of the demon lord Yeenoghu, known as the Beast of Butchery. A cruel hill giant sometimes turns to Yeenoghu for help in expanding the reach of its malevolence. Occasionally a hill giant consumes an evil artifact that transforms the giant into a fiendish form. Once in a while, Yeenoghu whispers promises of power in the dreams of a giant whose hunger surpasses other giants'. In any case, the result is a ravenous monster called a maw of Yeenoghu, which is wholly devoted to the demon lord.

A maw of Yeenoghu grows a mane of hair and hunches over like a gnoll. Its jaw grows and widens, and its mouth fills with multiple rows of sharp teeth. These teeth constantly grow, driving the maw to bite and chew on anything within reach. Some maws desperately rip the teeth from their mouth for relief, but the teeth quickly regrow. Cunning maws use this phenomenon as a ready supply of weaponry, throwing clusters of teeth at their foes.

A maw of Yeenoghu charges at its prey on all fours with its mouth wide open, scraping the ground like a plow.

```statblock
"name": "Maw of Yeenoghu (BGG)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "14d12 + 70"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "8"
  - !!int "14"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "constitution": !!int "9"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Abyssal, Giant"
"cr": "10"
"traits":
  - "desc": "The maw has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The maw makes two Bite or Fang Fling attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 19 (2d12 + 6) piercing damage."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 30/90 ft., one target. *Hit:*\
      \ 11 (1d10 + 6) piercing damage."
    "name": "Fang Fling"
  - "desc": "The maw moves up to its speed without provoking opportunity attacks and\
      \ can move through the spaces of Large or smaller creatures. Each time the maw\
      \ enters a creature's space for the first time during this move, that creature\
      \ must succeed on a DC 18 Strength saving throw or take 25 (3d12 + 6) piercing\
      \ damage and have the grappled condition (escape DC 16); if a creature is already\
      \ grappled this way, it has the prone condition. Until this grapple ends, the\
      \ target has the restrained condition. The maw can have only one creature grappled\
      \ in this way at a time."
    "name": "Gorging Charge (Recharge 5-6)"
"reactions":
  - "desc": "In response to taking damage, the maw makes one Bite attack against a\
      \ random creature within 10 feet of itself. If no creature is within reach,\
      \ the maw can make two Fang Fling attacks."
    "name": "Fanged Rebuke"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/fiend/token/maw-of-yeenoghu-bgg.webp"
```
^statblock