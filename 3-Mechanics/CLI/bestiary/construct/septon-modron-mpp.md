---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Septon Modron"
---
# [Septon Modron](3-Mechanics/CLI/bestiary/construct/septon-modron-mpp.md)
*Source: Morte's Planar Parade p. 40*  

Septons are auditors of base modrons in Mechanus, recording the activities in each of the plane's sectors to ensure operations are in perfect order. They are easily identified by their seven flexible limbs.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the *Monster Manual*.

```statblock
"name": "Septon Modron (MPP)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d10 + 72"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "17"
  - !!int "18"
  - !!int "16"
  - !!int "14"
"speed": "30 ft., fly 30 ft. (hover), swim 30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "lightning, psychic"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "The septon can't be compelled to act in a manner contrary to its nature\
      \ or its instructions."
    "name": "Axiomatic Mind"
  - "desc": "The septon has advantage on initiative checks."
    "name": "Combat Ready"
  - "desc": "If the septon dies, its body disintegrates into dust, leaving behind\
      \ anything it was carrying."
    "name": "Disintegration"
"actions":
  - "desc": "The septon makes four Tentacle attacks and uses Lightning Network or\
      \ Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (2d10 + 4) piercing damage, and if the target is a Medium or smaller\
      \ creature, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 14). Until this grapple ends, the septon can't use this\
      \ tentacle against other targets. The septon has seven tentacles, each of which\
      \ can grapple one target."
    "name": "Tentacle"
  - "desc": "The septon conjures a field of electricity that fills a 30-foot cube\
      \ originating from itself before dissipating. Each creature in that area must\
      \ make a DC 16 Dexterity saving throw. On a failed save, a creature takes 33\
      \ (6d10) lightning damage and has the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition for 1 minute. On a successful save, a creature takes half as much\
      \ damage only. A [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Lightning Network"
  - "desc": "The septon casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      **At will:** [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic.md), [mending](3-Mechanics/CLI/spells/mending.md)\
      \ (as an action)\n\n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only), [protection from evil and good](3-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
      \ [sending](3-Mechanics/CLI/spells/sending.md)"
    "name": "Spellcasting"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/construct/token/septon-modron-mpp.webp"
```
^statblock