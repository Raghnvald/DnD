---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Coatl"
---
# [Coatl](3-Mechanics/CLI/bestiary/celestial/coatl-psx.md)
*Source: Plane Shift: Ixalan p. 35*  

The River Heralds believe that the waters of the world are divided into two spheres: the river and the sea are the lower half, with the jungle and the sky above. They believe that the sea possesses an unfathomable wisdom, the deep musings of the unspeakably ancient world. But the wisdom of the sky and the rivers is embodied in the coatls—winged serpents that twist through the air to reflect the course of rivers along the ground.

Coatls are immortal guardians of the sky, dwelling always among the clouds. The River Heralds say that they can be enticed to the ground by the earnest supplication of the wisest of merfolk shamans. Coatls are said to be wise beyond mortal measure and incapable of speaking a falsehood, so their advice is often sought in times of desperate need. The sight of a coatl is thought to foretell favorable winds—a belief that has begun to spread from the River Herald shamans to the pirates of the Brazen Coalition. Use the [couatl](3-Mechanics/CLI/bestiary/celestial/couatl.md) statistics in the "Monster Manual" for Ixalan's coatls.

```statblock
"name": "Coatl (PSX)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "5"
"stats":
  - !!int "16"
  - !!int "20"
  - !!int "17"
  - !!int "18"
  - !!int "20"
  - !!int "18"
"speed": "30 ft., fly 90 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "7"
  - "charisma": !!int "6"
"damage_resistances": "radiant"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 15"
"languages": "all, telepathy 120 ft."
"cr": "4"
"traits":
  - "desc": "The coatl's spellcasting ability is Charisma (spell save DC 14). It can\
      \ innately cast the following spells, requiring only verbal components:\n\n\
      **At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md)\n\
      \n**3/day each:** [bless](3-Mechanics/CLI/spells/bless.md), [create food and\
      \ water](3-Mechanics/CLI/spells/create-food-and-water.md), [cure wounds](3-Mechanics/CLI/spells/cure-wounds.md),\
      \ [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md), [protection\
      \ from poison](3-Mechanics/CLI/spells/protection-from-poison.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**1/day each:** [dream](3-Mechanics/CLI/spells/dream.md),\
      \ [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md), [scrying](3-Mechanics/CLI/spells/scrying.md)"
    "name": "Innate Spellcasting"
  - "desc": "The coatl's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "The coatl is immune to scrying and to any effect that would sense its\
      \ emotions, read its thoughts, or detect its location."
    "name": "Shielded Mind"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 24 hours. Until this poison ends, the target is [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious).\
      \ Another creature can use an action to shake the target awake."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one Medium or smaller\
      \ creature. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 15). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the coatl can't constrict another target."
    "name": "Constrict"
  - "desc": "The coatl magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (the coatl's choice).\n\nIn a new form, the coatl\
      \ retains its game statistics and ability to speak, but its AC, movement modes,\
      \ Strength, Dexterity, and other actions are replaced by those of the new form,\
      \ and it gains any statistics and capabilities (except class features, legendary\
      \ actions, and lair actions) that the new form has but that it lacks. If the\
      \ new form has a bite attack, the coatl can use its bite in that form."
    "name": "Change Shape"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/celestial/token/coatl-psx.webp"
```
^statblock