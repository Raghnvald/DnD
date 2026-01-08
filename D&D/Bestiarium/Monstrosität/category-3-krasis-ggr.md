---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/16
- Monster/Größe/Riesig
- Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
- Category 3 Krasis
---
# [Category 3 Krasis](3-Mechanics\CLI\bestiary\monstrosity/category-3-krasis-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 212*  

## Krasis

In the deep sinkholes that serve as laboratories and guildhalls for the Simic Combine, biomancers employ a combination of magic and scientific method to create novel life forms. They coax new morphologies from existing creatures or combine traits from multiple organisms into one, producing the creatures known as krasis. Some krasis are unique creatures that can't reproduce. A few multiply and become part of the guild's standard menagerie.

## Creating a Krasis

To create a krasis, choose the appropriate stat block: category 1 (Medium), category 2 (Large), or category 3 (Huge). Then roll once on the Major Adaptations table and once on the Minor Adaptations table (or choose an option from each table) to determine its additional characteristics. The potency of some adaptations varies based on the category of the krasis, as indicated in the descriptions of those adaptations.

Just a few examples of krasis are the battering krasis (a fusion of hammerhead shark and a powerfully built beast), the crocanura (a crocodile-frog), the drakewing krasis (a lizard-drake), the teratosuchus (a crocodile-crab), the shambleshark (a shark-crab), and the sharktocrab (an improved shambleshark that includes octopus elements as well).

![Major Adaptations](/3-Mechanics/CLI/tables/major-adaptations-ggr.md)

![Minor Adaptations](/3-Mechanics/CLI/tables/minor-adaptations-ggr.md)

```statblock
"name": "Category 3 Krasis (GGR)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "287"
"hit_dice": "25d12 + 125"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "12"
  - !!int "21"
  - !!int "2"
  - !!int "13"
  - !!int "8"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "16"
"traits":
  - "desc": "The krasis can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The krasis makes three attacks: one with its bite, one with its claws,\
      \ and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one creature. *Hit:*\
      \ 27 (6d6 + 6) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (3d10 + 6) slashing damage."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target. *Hit:* 33\
      \ (6d8 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 19 Strength saving throw or be knocked prone."
    "name": "Tail"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/category-3-krasis-ggr.webp"
```
^statblock