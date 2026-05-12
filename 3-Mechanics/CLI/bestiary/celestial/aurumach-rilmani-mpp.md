---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aurumach Rilmani"
---
# [Aurumach Rilmani](3-Mechanics/CLI/bestiary/celestial/aurumach-rilmani-mpp.md)
*Source: Morte's Planar Parade p. 43*  

From redoubts near the Spire in the Outlands, aurumachs oversee the preservation of the cosmic status quo, serving as leaders and strategists of the rilmani. Employing mysterious magic, occult calculations, and networks of informants, aurumachs monitor forces across the planes. Only when planar balance is under threat of total collapse do these elusive, gold-skinned beings leave the Outlands, manifesting gleaming blades to destroy those that threaten multiversal stability.

## Rilmani

Rilmani protect the balance between the forces and philosophies of the multiverse. They seek to maintain planar equilibrium, assuring that good, evil, law, or chaos never grow too powerful or too weak. To the rilmani, each of these forces is fundamental to the multiverse's existence. Whenever one threatens to tip the balance in its favor or a plane is on the verge of collapse, the rilmani act to even the odds.

While the rilmani might be found anywhere, they're most frequently encountered on their home plane, the Outlands, where they work to ensure that no force overexerts itself on the Concordant Opposition.

Rilmani are bipedal, with bodies of living metal that ranges in appearance from cold iron to brilliant gold. Most have smooth faces with few features, and their extraordinary anatomies often act in defiance of natural forces.

```statblock
"name": "Aurumach Rilmani (MPP)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "285"
"hit_dice": "30d10 + 120"
"modifier": !!int "5"
"stats":
  - !!int "20"
  - !!int "21"
  - !!int "18"
  - !!int "21"
  - !!int "18"
  - !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  - "dexterity": !!int "11"
  - "intelligence": !!int "11"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+11"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+10"
"damage_resistances": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 20"
"languages": "all, telepathy 120 ft."
"cr": "17"
"actions":
  - "desc": "The aurumach makes three Manifested Blade or Gleaming Ray attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:*\
      \ 23 (4d8 + 5) force damage."
    "name": "Manifested Blade"
  - "desc": "*Ranged Spell Attack:* +11 to hit, range 120 ft., one target. *Hit:*\
      \ 24 (3d12 + 5) force damage."
    "name": "Gleaming Ray"
  - "desc": "The aurumach casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 19):\n\n**At will:** [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md)\n\n**1/day each:**\
      \ [fly](3-Mechanics/CLI/spells/fly.md), [geas](3-Mechanics/CLI/spells/geas.md)\
      \ (as an action), [slow](3-Mechanics/CLI/spells/slow.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The aurumach manifests a spectral, golden aura of blades around itself.\
      \ While this aura is manifested, each creature that starts its turn within 10\
      \ feet of the aurumach must make a DC 19 Dexterity saving throw, taking 16 (3d10)\
      \ force damage on a failed save, or half as much damage on a successful one.\
      \ The aura disappears after 1 minute, when the aurumach has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition or dies, or when the aurumach uses a bonus action to end it."
    "name": "Aura of Blades"
  - "desc": "The aurumach attempts to use its magic to weaken the defenses of a creature\
      \ it can see within 120 feet of itself. The target must succeed on a DC 19 Wisdom\
      \ saving throw or become cursed until the end of the aurumach's next turn. The\
      \ next time the aurumach hits the cursed target with a Manifested Blade or Gleaming\
      \ Ray attack, the target takes an extra 27 (6d8) force damage."
    "name": "Invoke Weakness (Recharge 5-6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/aurumach-rilmani-mpp.webp"
```
^statblock