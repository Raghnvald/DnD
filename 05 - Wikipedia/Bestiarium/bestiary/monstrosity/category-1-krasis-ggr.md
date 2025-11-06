---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/1
- Monster/Größe/Mittelgroß
- Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
- Category 1 Krasis
---
# [Category 1 Krasis](3-Mechanics\CLI\bestiary\monstrosity/category-1-krasis-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 210*  

## Krasis

In the deep sinkholes that serve as laboratories and guildhalls for the Simic Combine, biomancers employ a combination of magic and scientific method to create novel life forms. They coax new morphologies from existing creatures or combine traits from multiple organisms into one, producing the creatures known as krasis. Some krasis are unique creatures that can't reproduce. A few multiply and become part of the guild's standard menagerie.

## Creating a Krasis

To create a krasis, choose the appropriate stat block: category 1 (Medium), category 2 (Large), or category 3 (Huge). Then roll once on the Major Adaptations table and once on the Minor Adaptations table (or choose an option from each table) to determine its additional characteristics. The potency of some adaptations varies based on the category of the krasis, as indicated in the descriptions of those adaptations.

Just a few examples of krasis are the battering krasis (a fusion of hammerhead shark and a powerfully built beast), the crocanura (a crocodile-frog), the drakewing krasis (a lizard-drake), the teratosuchus (a crocodile-crab), the shambleshark (a shark-crab), and the sharktocrab (an improved shambleshark that includes octopus elements as well).

![Major Adaptations](/3-Mechanics/CLI/tables/major-adaptations-ggr.md)

![Minor Adaptations](/3-Mechanics/CLI/tables/minor-adaptations-ggr.md)

```statblock
"name": "Category 1 Krasis (GGR)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "14"
  - !!int "2"
  - !!int "13"
  - !!int "8"
"speed": "30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The krasis can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The krasis makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:* 8\
      \ (1d10 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage."
    "name": "Claws"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/category-1-krasis-ggr.webp"
```
^statblock