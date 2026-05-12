---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hellion"
---
# [Hellion](3-Mechanics/CLI/bestiary/monstrosity/hellion-psz.md)
*Source: Plane Shift: Zendikar p. 32*  

Similar to wurms, hellions are enormous serpentine creatures that dwell in the lava deep beneath the surface of Akoum. When an eruption brings lava to the surface, hellions occasionally emerge as well. Thrust into what seems to them like freezing air, the hellions begin a rampage of devastation resembling an extension of the lava flow.

A hellion bears a certain resemblance to both a millipede and a crustacean. Small legs tucked close to its body help propel it through its tunnels. Six long, jointed limbs protrude from its head, allowing it to drag prey into its mouth. Its body exudes infernal heat and its movements shake the earth like a tremor.

The [remorhaz](3-Mechanics/CLI/bestiary/monstrosity/remorhaz.md) statistics in the Monster Manual work well for hellions of different sizes.

```statblock
"name": "Hellion (PSZ)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"modifier": !!int "1"
"stats":
  - !!int "24"
  - !!int "13"
  - !!int "21"
  - !!int "4"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "cold, fire"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 10"
"languages": ""
"cr": "11"
"traits":
  - "desc": "A creature that touches the hellion or hits it with a melee attack while\
      \ within 5 feet of it takes 10 (3d6) fire damage."
    "name": "Heated Body"
"actions":
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:*\
      \ 40 (6d10 + 7) piercing damage plus 10 (3d6) fire damage. If the target\
      \ is a creature, it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 17). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the hellion can't bite another target."
    "name": "Bite"
  - "desc": "The hellion makes one bite attack against a Medium or smaller creature\
      \ it is grappling. If the attack hits, that creature takes the bite's damage\
      \ and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the hellion, and it takes\
      \ 21 (6d6) acid damage at the start of each of the hellion's turns.\n\nIf\
      \ the hellion takes 30 damage or more on a single turn from a creature inside\
      \ it, the hellion must succeed on a DC 15 Constitution saving throw at the end\
      \ of that turn or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the hellion. If the hellion dies, a swallowed\
      \ creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/hellion-psz.webp"
```
^statblock