---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Eater of Knowledge
Kategorie: Aberration
Größe: Groß
HG: 6
Status: WIP
linter-yaml-title-alias: Eater of Knowledge
tags:
  - Monster/Größe/Groß
  - Monster/HG/6
  - Monster/Typ/Aberration
  - Quelle/5e/mpp
aliases:
  - Eater of Knowledge
status: WIP
---
# [Eater of Knowledge](3-Mechanics/CLI/bestiary/aberration/eater-of-knowledge-mpp.md)
*Source: Morte's Planar Parade p. 29*  

Originally created by the mind flayer god-brain Ilsensine and now produced by some of that god's followers, eaters of knowledge are lumbering, bipedal masses of squelching muscles and exposed brain matter. These rugose hulks collect information from others by devouring brains before returning to their masters with delicious secrets. Unlike illithids, which overwhelm their foes with psionic power, eaters of knowledge use their physical strength to hold prey while burly feeding tentacles crack free their victims' brains. Consuming brains fuels these brutes' psionic power, making eaters of knowledge deadlier with each brain devoured.

```statblock
"name": "Eater of Knowledge (MPP)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "18"
  - !!int "16"
  - !!int "15"
"speed": "40 ft."
"saves":
  - "strength": !!int "7"
  - "intelligence": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 16"
"languages": "telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "When the eater of knowledge is first encountered, roll 1d10 to determine\
      \ the number of brains it has already consumed."
    "name": "Brains Devoured"
  - "desc": "The eater of knowledge has advantage on saving throws against spells\
      \ and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The eater of knowledge makes two Slam attacks. If both attacks hit the\
      \ same creature and the target is Large or smaller, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 14) and must succeed on a DC 15 Intelligence saving throw\
      \ or have the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition\
      \ until the grapple ends."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one Humanoid with the\
      \ [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.\
      \ *Hit:* 45 (10d8) piercing damage. If this damage reduces the target to 0\
      \ hit points, the eater of knowledge kills the target by extracting and consuming\
      \ its brain."
    "name": "Extract Brain"
  - "desc": "The eater of knowledge casts one of the following spells, requiring no\
      \ spell components and using Intelligence as its spellcasting ability (spell\
      \ save DC 15). It must have consumed the requisite number of brains to cast\
      \ the spell, as indicated:\n\n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only, 0 brains), [detect magic](3-Mechanics/CLI/spells/detect-magic.md)\
      \ (1 brain), [silent image](3-Mechanics/CLI/spells/silent-image.md) (2 brains),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (3 brains), [hypnotic\
      \ pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md) (4 brains), [major image](3-Mechanics/CLI/spells/major-image.md)\
      \ (5 brains), [telekinesis](3-Mechanics/CLI/spells/telekinesis.md) (6 brains),\
      \ [arcane eye](3-Mechanics/CLI/spells/arcane-eye.md) (7 brains), [mislead](3-Mechanics/CLI/spells/mislead.md)\
      \ (8 brains), [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md)\
      \ (9 brains), [mass suggestion](3-Mechanics/CLI/spells/mass-suggestion.md) (10\
      \ or more brains)"
    "name": "Spellcasting (Psionics)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/eater-of-knowledge-mpp.webp"
```
^statblock