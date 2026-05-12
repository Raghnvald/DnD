---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Geist: Horrifying Visage"
---
# [Geist: Horrifying Visage](3-Mechanics/CLI/bestiary/undead/geist-horrifying-visage-psi.md)
*Source: Plane Shift: Innistrad p. 19*  

```statblock
"name": "Geist: Horrifying Visage (PSI)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "17"
"speed": "0 ft., fly 40 ft."
"damage_resistances": "acid, fire, lightning, thunder, bludgeoning"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any languages it knew in life"
"cr": "4"
"traits":
  - "desc": "The geist can see 60 feet into the Ethereal Plane when it is on the Material\
      \ Plane, and vice versa."
    "name": "Ethereal Sight"
  - "desc": "The geist can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target *Hit:* 17\
      \ (4d6 + 3) necrotic damage."
    "name": "Withering Touch"
  - "desc": "The geist enters the Ethereal Plane from the Material Plane, or vice\
      \ versa. It is visible on the Material Plane while it is in the Border Ethereal,\
      \ and vice versa, yet it can't affect or be affected by anything on the other\
      \ plane."
    "name": "Etherealness"
  - "desc": "One creature that the geist can see within 5 feet of it must succeed\
      \ on a DC 13 Charisma saving throw or be possessed by the geist; the geist then\
      \ disappears, and the target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and loses control of its body. The geist now controls the body but doesn't\
      \ deprive the target of awareness. The geist can't be targeted by any attack,\
      \ spell, or other effect, except ones that turn undead, and it retains its alignment,\
      \ Intelligence, Wisdom, Charisma, and immunity to being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise\
      \ uses the possessed target's statistics, but doesn't gain access to the target's\
      \ knowledge, class features, or proficiencies. The possession lasts until the\
      \ body drops to 0 hit points, the geist ends it as a bonus action, or the geist\
      \ is turned or forced out by an effect like the [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md)\
      \ spell. When the possession ends, the geist reappears in an unoccupied space\
      \ within 5 feet of the body. The target is immune to this geist's Possession\
      \ for 24 hours after succeeding on the saving throw or after the possession\
      \ ends. The geist can instead target the corpse of a creature, effectively using\
      \ its own life force to animate the corpse as a zombie. The animated corpse\
      \ uses zombie statistics and returns to death if the geist ends the possession."
    "name": "Possession (Recharge 6)"
  - "desc": "Black-aligned geists can make themselves terrible to behold, even when\
      \ they are possessing the living. Each non-undead creature within 60 feet of\
      \ the geist that can see it must succeed on a DC 13 Wisdom saving throw or be\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute.\
      \ If the save fails by 5 or more, the target also ages 1d4 × 10 years. A [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) condition\
      \ on itself on a success. If a target's saving throw is successful or the effect\
      \ ends for it, the target is immune to this geist's Horrifying Visage for the\
      \ next 24 hours. The aging effect can be reversed with a [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell, but only within 24 hours of it occurring."
    "name": "Horrifying Visage"
"source":
  - "PSI"
```
^statblock