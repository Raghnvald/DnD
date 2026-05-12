---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sovereign Basidia"
---
# [Sovereign Basidia](3-Mechanics/CLI/bestiary/npc/sovereign-basidia-oota.md)
*Source: Out of the Abyss p. 88*  

```statblock
"name": "Sovereign Basidia (OotA)"
"size": "Large"
"type": "plant"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "13"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "When Basidia takes damage, all other myconids within 240 feet of it can\
      \ sense its pain."
    "name": "Distress Spores"
  - "desc": "While in sunlight, Basidia has disadvantage on ability checks, attack\
      \ rolls, and saving throws. Basidia dies if it spends more than 1 hour in direct\
      \ sunlight."
    "name": "Sun Sickness"
"actions":
  - "desc": "Basidia uses either its Hallucination Spores or its Pacifying Spores,\
      \ then makes a fist attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (3d4 + 1) bludgeoning damage plus 7 (3d4) poison damage."
    "name": "Fist"
  - "desc": "Basidia targets one corpse of a humanoid or a Large or smaller beast\
      \ within 5 feet of it and releases spores at the corpse. In 24 hours, the corpse\
      \ rises as a spore servant. The corpse stays animated for 1d4 + 1 weeks or\
      \ until destroyed, and it can't be animated again in this way."
    "name": "Animating Spores (3/Day)"
  - "desc": "Basidia ejects spores at one creature it can see within 5 feet of it.\
      \ The target must succeed on a DC 12 Constitution saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. The [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while it hallucinates. The target can repeat the saving throw at the end of\
      \ each of its turns, ending the effect on itself on a success."
    "name": "Hallucination Spores"
  - "desc": "Basidia ejects spores at one creature it can see within 5 feet of it.\
      \ The target must succeed on a DC 12 Constitution saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Pacifying Spores"
  - "desc": "A 30-foot radius of spores extends from Basidia. These spores can go\
      \ around corners and affect only creatures with an Intelligence of 2 or higher\
      \ that aren't undead, constructs, or elementals. Affected creatures can communicate\
      \ telepathically with one another while they are within 30 feet of each other.\
      \ The effect lasts for 1 hour."
    "name": "Rapport Spores"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/sovereign-basidia-oota.webp"
```
^statblock