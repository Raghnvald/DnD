---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Creepy Doll"
---
# [Creepy Doll](3-Mechanics/CLI/bestiary/construct/creepy-doll-psi.md)
*Source: Plane Shift: Innistrad p. 25*  

Many of the evils that plague humanity on Innistrad arise from within humanity itself, and among the most terrible of these are creatures built by human hands. Some of these are animated by the magic of [necro-alchemists](3-Mechanics/CLI/bestiary/humanoid/necro-alchemist-psi.md) or witches, but others are inhabited and given life by hostile spirits or other malign forces. These include [gargoyles](3-Mechanics/CLI/bestiary/elemental/gargoyle.md) and [scarecrows](3-Mechanics/CLI/bestiary/construct/scarecrow.md), haunted dolls and suits of [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [stone golems](3-Mechanics/CLI/bestiary/construct/stone-golem.md) formed of gravestones and mausoleums, and [homunculi](3-Mechanics/CLI/bestiary/construct/homunculus.md) created by stitchers and [necro-alchemists](3-Mechanics/CLI/bestiary/humanoid/necro-alchemist-psi.md).

```statblock
"name": "Creepy Doll (PSI)"
"size": "Tiny"
"type": "construct"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "11"
  - !!int "10"
"speed": "40 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "speaks and understands the languages known by its creator"
"cr": "2"
"traits":
  - "desc": "While the creepy doll remains motionless, it is indistinguishable from\
      \ an ordinary, inanimate doll."
    "name": "False Appearance"
"actions":
  - "desc": "The creepy doll makes one attack with its scissors and uses Psychic Assault."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d4 + 2) slashing damage."
    "name": "Scissors"
  - "desc": "The creepy doll targets one creature it can see within 10 feet of it\
      \ that has a brain. The target must succeed on a DC 12 Intelligence saving throw\
      \ or take 11 (2d10) psychic damage. Also on a failure, roll 3d6. If the\
      \ total equals or exceeds the target's Intelligence score, that score is reduced\
      \ to 0. The target is [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until it regains at least one point of Intelligence, as from the [greater\
      \ restoration](3-Mechanics/CLI/spells/greater-restoration.md) spell or similar\
      \ magic."
    "name": "Psychic Assault"
  - "desc": "The creepy doll initiates an Intelligence contest with an [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ humanoid within 5 feet of it. If it wins the contest, the creepy doll's spirit\
      \ inhabits the target's body while the target's spirit is placed into the creepy\
      \ doll's body. The creepy doll controls the target's body completely. It retains\
      \ its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise\
      \ uses the possessed target's statistics, but doesn't gain access to the target's\
      \ knowledge, class features, or proficiencies. The target retains its alignment,\
      \ Intelligence, Wisdom, and Charisma while inhabiting the creepy doll's body.\n\
      \nThe body exchange lasts until the doll's spirit is forced out by magic. (The\
      \ [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md) spell\
      \ will accomplish this, though the doll is not one of the creature types whose\
      \ possession that spell normally ends.) The body and the doll must be within\
      \ 5 feet of each other for such an effect to work. The target is immune to this\
      \ doll's Body Exchange for 24 hours after winning the Intelligence contest or\
      \ after the exchange ends."
    "name": "Body Exchange"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/construct/token/creepy-doll-psi.webp"
```
^statblock