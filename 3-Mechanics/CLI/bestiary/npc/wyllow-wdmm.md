---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wyllow"
---
# [Wyllow](3-Mechanics/CLI/bestiary/npc/wyllow-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 70*  

Wyllow is a moon elf druid with eyes as green as emeralds. Butterflies nest in her tangled black hair, and small critters gather around her feet.

```statblock
"name": "Wyllow (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "132"
"hit_dice": "24d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"gear":
  - "[scimitar](3-Mechanics/CLI/items/scimitar-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 19"
"languages": "Common, Druidic, Elvish"
"cr": "12"
"traits":
  - "desc": "Wyllow is an 18th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 17, +9 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** [druidcraft](3-Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [mending](3-Mechanics/CLI/spells/mending-xphb.md), [poison spray](3-Mechanics/CLI/spells/poison-spray-xphb.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame-xphb.md)\n\n**1st level\
      \ (4 slots):** [cure wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md), [entangle](3-Mechanics/CLI/spells/entangle-xphb.md),\
      \ [faerie fire](3-Mechanics/CLI/spells/faerie-fire-xphb.md), [speak with animals](3-Mechanics/CLI/spells/speak-with-animals-xphb.md)\n\
      \n**2nd level (3 slots):** [animal messenger](3-Mechanics/CLI/spells/animal-messenger-xphb.md),\
      \ [beast sense](3-Mechanics/CLI/spells/beast-sense-xphb.md), [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md)\n\
      \n**3rd level (3 slots):** [conjure animals](3-Mechanics/CLI/spells/conjure-animals-xphb.md),\
      \ [meld into stone](3-Mechanics/CLI/spells/meld-into-stone-xphb.md), [water\
      \ breathing](3-Mechanics/CLI/spells/water-breathing-xphb.md)\n\n**4th level\
      \ (3 slots):** [dominate beast](3-Mechanics/CLI/spells/dominate-beast-xphb.md),\
      \ [locate creature](3-Mechanics/CLI/spells/locate-creature-xphb.md), [stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md),\
      \ [wall of fire](3-Mechanics/CLI/spells/wall-of-fire-xphb.md)\n\n**5th level\
      \ (3 slots):** [commune with nature](3-Mechanics/CLI/spells/commune-with-nature-xphb.md),\
      \ [mass cure wounds](3-Mechanics/CLI/spells/mass-cure-wounds-xphb.md), [tree\
      \ stride](3-Mechanics/CLI/spells/tree-stride-xphb.md)\n\n**6th level (1 slots):**\
      \ [heal](3-Mechanics/CLI/spells/heal-xphb.md), [heroes' feast](3-Mechanics/CLI/spells/heroes-feast-xphb.md),\
      \ [sunbeam](3-Mechanics/CLI/spells/sunbeam-xphb.md)\n\n**7th level (1 slots):**\
      \ [fire storm](3-Mechanics/CLI/spells/fire-storm-xphb.md)\n\n**8th level (1\
      \ slots):** [animal shapes](3-Mechanics/CLI/spells/animal-shapes-xphb.md)\n\n\
      **9th level (1 slots):** [foresight](3-Mechanics/CLI/spells/foresight-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Wyllow"
    "name": "Fey Ancestry"
  - "desc": "Wyllow"
    "name": "Mask of the Wild"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) slashing damage."
    "name": "Scimitar"
  - "desc": "Wyllow magically polymorphs into a beast or elemental with a challenge\
      \ rating of 6 or less, and can remain in this form for up to 9 hours. Wyllow\
      \ can choose whether its equipment falls to the ground, melds with its new form,\
      \ or is worn by the new form. Wyllow reverts to its true form if it dies or\
      \ falls [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious). Wyllow\
      \ can revert to its true form using a bonus action on its turn.\n\nWhile in\
      \ a new form, Wyllow retains its game statistics and ability to speak, but its\
      \ AC, movement modes, Strength, and Dexterity are replaced by those of the new\
      \ form, and it gains any special senses, proficiencies, traits, actions, and\
      \ reactions (except class features, legendary actions, and lair actions) that\
      \ the new form has but that it lacks. It can cast its spells with verbal or\
      \ somatic components in its new form.\n\nThe new form's attacks count as magical\
      \ for the purpose of overcoming resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/wyllow-wdmm.webp"
```
^statblock