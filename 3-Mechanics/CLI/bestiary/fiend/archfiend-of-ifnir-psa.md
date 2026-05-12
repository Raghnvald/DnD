---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Archfiend of Ifnir"
---
# [Archfiend of Ifnir](3-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md)
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](3-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](3-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](3-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](3-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](3-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](3-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```statblock
"name": "Archfiend of Ifnir (PSA)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "184"
"hit_dice": "16d10 + 96"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "10"
  - !!int "22"
  - !!int "19"
  - !!int "12"
  - !!int "15"
"speed": "20 ft., fly 30 ft."
"saves":
  - "constitution": !!int "11"
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 11"
"languages": "Abyssal, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "The archfiend has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The archfiend uses Horror Nimbus if it can. It then makes three attacks:\
      \ one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 32 (5d10 + 5) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (3d6 + 5) slashing damage."
    "name": "Claw"
  - "desc": "The archfiend magically emits scintillating, multicolored light. Each\
      \ creature within 15 feet of the archfiend that can see the light must succeed\
      \ on a DC 15 Wisdom saving throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to the\
      \ archfiend's Horror Nimbus for the next 24 hours."
    "name": "Horror Nimbus (Recharge 5-6)"
  - "desc": "The archfiend magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/archfiend-of-ifnir-psa.webp"
```
^statblock