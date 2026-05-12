---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Soulstinger Demon"
---
# [Soulstinger Demon](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md)
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](3-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](3-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](3-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](3-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](3-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](3-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```statblock
"name": "Soulstinger Demon (PSA)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "16"
"speed": "40 ft., fly 40 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": "Infernal, telepathy 120 ft."
"cr": "9"
"traits":
  - "desc": "Magical darkness doesn't impede the demon's darkvision."
    "name": "Devil's Sight"
  - "desc": "The demon has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The demon makes three attacks: two with its claws and one with its sting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) piercing damage plus 17 (5d6) poison damage, and the target\
      \ must succeed on a DC 14 Constitution saving throw or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Sting"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/soulstinger-demon-psa.webp"
```
^statblock