---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Githzerai Futurist
Kategorie: Aberration (Gith)
Größe: Mittelgroß
HG: 9
Status: WIP
linter-yaml-title-alias: Githzerai Futurist
tags:
  - Quelle/5e/mpp
  - Monster/HG/9
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration/gith
aliases:
  - Githzerai Futurist
status: WIP
---
# [Githzerai Futurist](3-Mechanics/CLI/bestiary/aberration/githzerai-futurist-mpp.md)
*Source: Morte's Planar Parade p. 30*  

Githzerai futurists have transcended their limits through focused meditation and can now catch glimpses of the future. They foresee the possible outcomes of battles, using those portents to tilt the balance in their favor.

## Githzerai

Githzerai descend from an ancient people who were also the progenitors of the githyanki—all of whom were destroyed or transformed by mind flayers. Many githzerai dwell in Limbo, honing their psionic powers by shaping their homes on that chaotic plane. The githzerai described here oftentimes traverse the planes, crossing between them via the portals in Sigil and the Outlands. To learn more about other githzerai, see the *Monster Manual*.

```statblock
"name": "Githzerai Futurist (MPP)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "psychic defense"
"hp": !!int "149"
"hit_dice": "23d8 + 46"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "15"
  - !!int "17"
  - !!int "17"
  - !!int "13"
"speed": "40 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "7"
  - "intelligence": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 30 ft., passive\
  \ Perception 17"
"languages": "Common, Gith"
"cr": "9"
"traits":
  - "desc": "While the githzerai is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Psychic Defense"
"actions":
  - "desc": "The githzerai makes three Unarmed Strike or Psychic Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) bludgeoning damage plus 11 (2d10) psychic damage."
    "name": "Unarmed Strike"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 60 ft., one creature. *Hit:*\
      \ 21 (4d8 + 3) psychic damage."
    "name": "Psychic Bolt"
  - "desc": "The githzerai casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\n**At will:**\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), [levitate](3-Mechanics/CLI/spells/levitate.md)\
      \ (self only), [mage hand](3-Mechanics/CLI/spells/mage-hand.md) (the hand is\
      \ invisible), [see invisibility](3-Mechanics/CLI/spells/see-invisibility.md)\n\
      \n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift.md) (self\
      \ only), [scrying](3-Mechanics/CLI/spells/scrying.md) (as an action), [slow](3-Mechanics/CLI/spells/slow.md),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis.md)"
    "name": "Spellcasting (Psionics)"
"reactions":
  - "desc": "When the githzerai or a creature it can see makes an attack roll, a saving\
      \ throw, or an ability check, the githzerai can cause the roll to be made with\
      \ advantage or disadvantage."
    "name": "Future Insight (3/Day)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-futurist-mpp.webp"
```
^statblock