---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kkw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Loading Rig"
---
# [Loading Rig](3-Mechanics/CLI/bestiary/npc/loading-rig-kkw.md)
*Source: Krenko's Way p. 170*  

```statblock
"name": "Loading Rig (KKW)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "13"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The rig is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), the\
      \ rig must succeed on a Constitution saving throw against the caster's spell\
      \ save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "If the rig takes damage, it must succeed on a DC 10 Constitution saving\
      \ throw or be [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ with a speed of 0 until a creature activates it with a successful DC 10 Intelligence\
      \ ([Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)) check made as an action."
    "name": "Unstable"
"actions":
  - "desc": "The armor makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) bludgeoning damage."
    "name": "Slam"
"source":
  - "KKW"
"image": "3-Mechanics/CLI/bestiary/npc/token/loading-rig-kkw.webp"
```
^statblock