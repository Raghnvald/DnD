---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Githzerai Uniter
Kategorie: Aberration (Gith)
Größe: Mittelgroß
HG: 7
Status: WIP
linter-yaml-title-alias: Githzerai Uniter
tags:
  - Quelle/5e/mpp
  - Monster/HG/7
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration/gith
aliases:
  - Githzerai Uniter
status: WIP
---
# [Githzerai Uniter](3-Mechanics/CLI/bestiary/aberration/githzerai-uniter-mpp.md)
*Source: Morte's Planar Parade p. 31*  

Githzerai uniters espouse wisdom and unity rather than violence. Many uniters are members of the Sha'sal Khou, a group of githyanki and githzerai who band together to reunify the gith people. Capable martial artists, uniters are more inclined to disarm and subdue their opponents than destroy them.

## Githzerai

Githzerai descend from an ancient people who were also the progenitors of the githyanki—all of whom were destroyed or transformed by mind flayers. Many githzerai dwell in Limbo, honing their psionic powers by shaping their homes on that chaotic plane. The githzerai described here oftentimes traverse the planes, crossing between them via the portals in Sigil and the Outlands. To learn more about other githzerai, see the *Monster Manual*.

```statblock
"name": "Githzerai Uniter (MPP)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "psychic defense"
"hp": !!int "123"
"hit_dice": "19d8 + 38"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "15"
  - !!int "15"
  - !!int "17"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "6"
  - "intelligence": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common, Gith"
"cr": "7"
"traits":
  - "desc": "While the githzerai is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Psychic Defense"
"actions":
  - "desc": "The githzerai makes three Unarmed Strike or Psychic Bolt attacks. It\
      \ can replace any of these attacks with one use of its Pacifying Touch."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage plus 10 (3d6) psychic damage."
    "name": "Unarmed Strike"
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 60 ft., one creature. *Hit:*\
      \ 17 (5d6) psychic damage."
    "name": "Psychic Bolt"
  - "desc": "The githzerai touches one creature it can see within 5 feet of itself.\
      \ The target must succeed on a DC 14 Intelligence saving throw, or the githzerai\
      \ chooses an action for that target: Attack, Cast a Spell, or [Dash](3-Mechanics/CLI/rules/actions.md#Dash).\
      \ The affected target can't take that action for 1 minute. At the end of each\
      \ of the target's turns, it can repeat the saving throw, ending the effect on\
      \ itself on a successful save. A target that succeeds on the saving throw becomes\
      \ immune to this githzerai's Pacifying Touch for 24 hours."
    "name": "Pacifying Touch"
  - "desc": "The githzerai casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 14):\n\n**At will:**\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible),\
      \ [see invisibility](3-Mechanics/CLI/spells/see-invisibility.md)\n\n**1/day\
      \ each:** [plane shift](3-Mechanics/CLI/spells/plane-shift.md) (self only),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis.md)"
    "name": "Spellcasting (Psionics)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-uniter-mpp.webp"
```
^statblock