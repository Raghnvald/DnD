---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/cr/9
- Monster/Größe/Mittelgroß
- Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
- Conclave Dryad
---
# [Conclave Dryad](3-Mechanics\CLI\bestiary\fey/conclave-dryad-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 194*  

The lush forests that once grew on Ravnica are gone, but the dryads remain, striving to bring the sprawling city and the verdant green of nature into harmony. Dryads believe that their efforts are the will of Mat'Selesnya, the soul of the world, and they spread their teachings through every Selesnya enclave.

Thanks to their attunement to Mat'Selesnya, dryads serve as visionaries and spiritual intermediaries for the Selesnya Conclave. They hold positions of great respect as spiritual leaders, and also share their vision of harmonious construction as architects, working with stonemasons and woodshapers to create Selesnya enclaves.

## Summoned Mount

When leading its guild into battle, a dryad rides a magically summoned creature woven of living branches, vines, and grasses and imbued with a fey spirit.

```statblock
"name": "Conclave Dryad (GGR)"
"size": "Medium"
"type": "fey"
"alignment": "Lawful Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "19"
  - !!int "14"
  - !!int "19"
  - !!int "20"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "Nature"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+9"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Elvish, Sylvan"
"cr": "9"
"traits":
  - "desc": "The dryad's innate spellcasting ability is Charisma (spell save DC 17).\
      \ The dryad can innately cast the following spells, requiring no material components:\n\
      \n**At will:** druidcraft\n\n**3/day each:** dispel magic, entangle, plant growth,\
      \ spike growth\n\n**1/day each:** moonbeam, grasping vine, wall of thorns"
    "name": "Innate Spellcasting"
  - "desc": "The dryad has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The dryad can communicate with beasts and plants as if they and the dryad\
      \ shared a language."
    "name": "Speak with Beasts and Plants"
"actions":
  - "desc": "The dryad makes three attacks, using its vine staff, its longbow, or\
      \ both."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Dexterity saving throw or become restrained by twisting vines for\
      \ 1 minute. A target restrained in this way can use an action to make a DC 17\
      \ Strength (Athletics) or Dexterity (Acrobatics) check, ending the effect on\
      \ itself on a success."
    "name": "Vine Staff"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 150/600 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) piercing damage."
    "name": "Longbow"
  - "desc": "The dryad magically summons a mount, which appears in an unoccupied space\
      \ within 60 feet of the dryad. The mount remains for 8 hours, until it or the\
      \ dryad dies, or until the dryad dismisses it as an action. The mount uses the\
      \ stat block of an [elk](/3-Mechanics/CLI/bestiary/beast/elk.md) (see the Monster\
      \ Manual) with these changes: it is a plant instead of a beast, it has an Intelligence\
      \ of 6, and it understands Sylvan but can't speak. While within 1 mile of the\
      \ mount, the dryad can communicate with it telepathically."
    "name": "Summon Mount (1/Day)"
  - "desc": "The dryad targets one magic item it can see within 120 feet of it. If\
      \ the magic item isn't an artifact, its magical properties are suppressed for\
      \ 10 minutes, until the dryad is incapacitated or dies, or until the dryad uses\
      \ a bonus action to end the effect."
    "name": "Suppress Magic (Recharge 5-6)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/fey/token/conclave-dryad-ggr.webp"
```
^statblock