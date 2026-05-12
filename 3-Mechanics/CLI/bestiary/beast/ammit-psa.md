---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ammit"
---
# [Ammit](3-Mechanics/CLI/bestiary/beast/ammit-psa.md)
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](3-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](3-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](3-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](3-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](3-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](3-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](3-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```statblock
"name": "Ammit (PSA)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "17"
  - !!int "2"
  - !!int "10"
  - !!int "7"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The ammit can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The ammit makes two attacks: one with its bite and one with its tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 21\
      \ (3d10 + 5) piercing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the ammit can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target not [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the ammit. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is a\
      \ creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/beast/token/ammit-psa.webp"
```
^statblock