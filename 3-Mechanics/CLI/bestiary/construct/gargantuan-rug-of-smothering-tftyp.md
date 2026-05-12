---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gargantuan Rug of Smothering"
---
# [Gargantuan Rug of Smothering](3-Mechanics/CLI/bestiary/construct/gargantuan-rug-of-smothering-tftyp.md)
*Source: Tales from the Yawning Portal p. 56*  

```statblock
"name": "Gargantuan Rug of Smothering (TftYP)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "63"
"hit_dice": "6d20"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "10"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "10 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 6"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The rug is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field-xphb.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ the rug must succeed on a Constitution saving throw against the caster's spell\
      \ save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While it is grappling a creature, the rug takes only half the damage\
      \ dealt to it, and the creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the rug takes the other half."
    "name": "Damage Transfer"
  - "desc": "While the rug remains motionless, it is indistinguishable from a normal\
      \ rug."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one Medium or smaller\
      \ creature. *Hit:* The creature is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 13). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), and at risk of suffocating,\
      \ and the rug can't smother another target. In addition, at the start of each\
      \ of the target's turns, the target takes 10 (2d6 + 3) bludgeoning damage."
    "name": "Smother"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/construct/token/gargantuan-rug-of-smothering-tftyp.webp"
```
^statblock