---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "X01"
---
# [X01](3-Mechanics/CLI/bestiary/npc/x01-tofw.md)
*Source: Turn of Fortune's Wheel p. 91*  

```statblock
"name": "X01 (ToFW)"
"size": "Huge"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "209"
"hit_dice": "22d12 + 66"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "17"
  - !!int "19"
  - !!int "17"
  - !!int "15"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+13"
"damage_resistances": "lightning, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 23"
"languages": "all, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "X01 can't be compelled to act in a manner contrary to its nature or its\
      \ instructions."
    "name": "Axiomatic Mind"
  - "desc": "X01 has advantage on initiative rolls."
    "name": "Combat Ready"
  - "desc": "If X01 dies, its body disintegrates into dust, leaving behind anything\
      \ it was carrying."
    "name": "Disintegration"
  - "desc": "If X01 fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
"actions":
  - "desc": "X01 makes one Pincer attack and two Tentacle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) bludgeoning damage plus 10 (3d6) force damage. If the target\
      \ is a creature, it must succeed on a DC 17 Constitution saving throw or have\
      \ the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition\
      \ until the end of its next turn."
    "name": "Pincer"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (2d10 + 4) piercing damage, and if the target is a Medium or smaller\
      \ creature, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 14). Until this grapple ends, X01 can't use this tentacle\
      \ against other targets. X01 has six tentacles, each of which can grapple one\
      \ target."
    "name": "Tentacle"
  - "desc": "X01 casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 17):\n\n\
      **At will:** [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [mending](3-Mechanics/CLI/spells/mending-xphb.md)\
      \ (as an action)\n\n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ (self only), [protection from evil and good](3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "X01 attempts to interrupt a creature it can see that is casting a spell.\
      \ If the spell is 3rd level or lower, it fails and has no effect. If the spell\
      \ is 4th level or higher, X01 makes an Intelligence check (DC 10 + the spell's\
      \ level). On a success, the spell fails and has no effect."
    "name": "Counter Magic"
  - "desc": "When a creature within 120 feet of X01 damages it, X01 magically retaliates\
      \ with an arc of lightning. The creature must make a DC 17 Dexterity saving\
      \ throw, taking 11 (2d10) lightning damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Lightning Rebuke"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/x01-tofw.webp"
```
^statblock