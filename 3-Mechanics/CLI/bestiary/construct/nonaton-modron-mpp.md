---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nonaton Modron"
---
# [Nonaton Modron](3-Mechanics/CLI/bestiary/construct/nonaton-modron-mpp.md)
*Source: Morte's Planar Parade p. 38*  

When modrons act against the will of Primus, nonatons are charged with bringing those rogue units into line. These inspectors also interrogate captured trespassers of Mechanus. Nonatons have wormlike bodies studded with nine mechanical arms.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the *Monster Manual*.

```statblock
"name": "Nonaton Modron (MPP)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "19d10 + 57"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "13"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "Modron, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The nonaton can't be compelled to act in a manner contrary to its nature\
      \ or its instructions."
    "name": "Axiomatic Mind"
  - "desc": "The nonaton has advantage on initiative rolls."
    "name": "Combat Ready"
  - "desc": "If the nonaton dies, its body disintegrates into dust, leaving behind\
      \ anything it was carrying."
    "name": "Disintegration"
"actions":
  - "desc": "The nonaton makes three Arm attacks and uses Pillar of Truth or Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) piercing damage, and if the target is a Medium or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 14). Until this grapple ends, the nonaton can't use this arm against\
      \ other targets. The nonaton has nine arms, each of which can grapple one target."
    "name": "Arm"
  - "desc": "The nonaton chooses a point on the ground that it can see within 60 feet\
      \ of itself. A 60-foot-tall, 20-foot-radius cylinder of magical force rises\
      \ from that point. Each creature in that area must make a DC 15 Dexterity saving\
      \ throw. On a failed save, a creature takes 21 (6d6) force damage, and the\
      \ creature reverts to its original form (if it's in a different form) and can't\
      \ assume a different form until the end of its next turn. On a successful save,\
      \ a creature takes half as much damage only."
    "name": "Pillar of Truth"
  - "desc": "The nonaton casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 15):\n\n**At will:** [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), [mending](3-Mechanics/CLI/spells/mending.md)\
      \ (as an action)\n\n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only), [protection from evil and good](3-Mechanics/CLI/spells/protection-from-evil-and-good.md)"
    "name": "Spellcasting"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/construct/token/nonaton-modron-mpp.webp"
```
^statblock