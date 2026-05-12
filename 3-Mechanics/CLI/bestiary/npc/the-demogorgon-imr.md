---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "The Demogorgon"
---
# ["The Demogorgon"](3-Mechanics/CLI/bestiary/npc/the-demogorgon-imr.md)
*Source: Infernal Machine Rebuild p. 53*  

```statblock
"name": "\"The Demogorgon\" (IMR)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "123"
"hit_dice": "13d12 + 39"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "17"
  - !!int "6"
  - !!int "10"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"gear":
  - "[battleaxe](3-Mechanics/CLI/items/battleaxe.md)"
  - "[morningstar](3-Mechanics/CLI/items/morningstar.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Giant, Orc"
"cr": "8"
"traits":
  - "desc": "The ettin has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks and on saving throws against being [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded),\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
      \ and knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)."
    "name": "Two Heads"
  - "desc": "When one of the ettin's heads is asleep, its other head is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The ettin makes two attacks: one with its battleaxe and one with its\
      \ morningstar."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) slashing damage."
    "name": "Battleaxe"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) piercing damage."
    "name": "Morningstar"
  - "desc": "The ettin's right head exhales fire in a 30-foot cone. Each creature\
      \ in that area must make a DC 14 Dexterity saving throw, taking 45 (10d8)\
      \ fire damage on a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
  - "desc": "The ettin's left head exhales an icy blast in a 30-foot cone. Each creature\
      \ in that area must make a DC 14 Constitution saving throw, taking 45 (10d8)\
      \ cold damage on a failed save, or half as much damage on a successful one."
    "name": "Cold Breath (Recharge 5-6)"
  - "desc": "The ettin turns its magical gaze toward one creature that it can see\
      \ within 120 feet of it. That target must make a DC 14 Wisdom saving throw.\
      \ Unless the target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ it can avert its eyes to avoid the gaze and to automatically succeed on the\
      \ save. If the target does so, it can't see the ettin until the start of the\
      \ ettin's next turn. If the target looks at the ettin in the meantime, it must\
      \ immediately make the save.\n\nIf the target fails the save, it suffers one\
      \ of the following effects of the ettin's choice or at random:"
    "name": "Gaze"
  - "desc": "The target is [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the start of the ettin's next turn or until the ettin is no longer within\
      \ line of sight."
    "name": "Beguiling Gaze"
  - "desc": "The target is [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ by the ettin until the start of the ettin's next turn. The ettin chooses how\
      \ the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target uses its\
      \ actions, reactions, and movement."
    "name": "Hypnotic Gaze"
  - "desc": "The target suffers the effect of the [confusion](3-Mechanics/CLI/spells/confusion.md)\
      \ spell without making a saving throw. The effect lasts until the start of the\
      \ ettin's next turn. The ettin doesn't need to concentrate on the spell."
    "name": "Insanity Gaze"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/the-demogorgon-imr.webp"
```
^statblock