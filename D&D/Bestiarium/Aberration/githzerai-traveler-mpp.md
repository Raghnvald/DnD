---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Githzerai Traveler
Kategorie: Aberration (Gith)
Größe: Mittelgroß
HG: 3
status: WIP
linter-yaml-title-alias: Githzerai Traveler
tags:
  - Quelle/5e/mpp
  - ttrpg-cli/monster/cr/3
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/aberration/gith
aliases:
  - Githzerai Traveler
---
# [Githzerai Traveler](3-Mechanics/CLI/bestiary/aberration/githzerai-traveler-mpp.md)
*Source: Morte's Planar Parade p. 31*  

Githzerai travelers wander the multiverse to train and pursue cosmic enlightenment. These githzerai learn to manipulate planar energies to create wondrous effects.

Githzerai descend from an ancient people who were also the progenitors of the githyanki—all of whom were destroyed or transformed by mind flayers. Many githzerai dwell in Limbo, honing their psionic powers by shaping their homes on that chaotic plane. The githzerai described here oftentimes traverse the planes, crossing between them via the portals in Sigil and the Outlands. To learn more about other githzerai, see the *Monster Manual*.

```statblock
"name": "Githzerai Traveler (MPP)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "psychic defense"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "16"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "3"
  - "dexterity": !!int "4"
  - "intelligence": !!int "4"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common, Gith"
"cr": "3"
"traits":
  - "desc": "While the githzerai is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Psychic Defense"
"actions":
  - "desc": "The githzerai makes three Unarmed Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) bludgeoning damage plus 4 (1d8) psychic damage."
    "name": "Unarmed Strike"
  - "desc": "The githzerai casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 13):\n\n**At will:**\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)\n\
      \n**1/day each:** [jump](3-Mechanics/CLI/spells/jump.md), [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only), [see invisibility](3-Mechanics/CLI/spells/see-invisibility.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githzerai manipulates the energy of the plane of existence it's on\
      \ to produce one of the following effects (choose one or roll a d6):\n\n-\
      \ **1-2 Astral Step.** The githzerai can teleport, along with any equipment\
      \ it is wearing or carrying, up to 40 feet to an unoccupied space it can see.\
      \ In addition, its walking speed increases to 40 feet until the start of its\
      \ next turn.  \n- **3-4 Growth.** Flowers and vines grow around the githzerai\
      \ until the start of its next turn, then vanish; the ground within 15 feet of\
      \ the githzerai is difficult terrain for other creatures while the flowers and\
      \ vines are present.  \n- **5-6 Retaliating Light.** Multicolored lights surround\
      \ the githzerai until the start of its next turn. For the effect's duration,\
      \ whenever a creature within 5 feet of the githzerai hits it with a melee attack\
      \ roll, that creature takes 3 (1d6) force damage, as magic lashes out in retribution.\
      \  "
    "name": "Matter Manipulation (Recharge 4-6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-traveler-mpp.webp"
```
^statblock