---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shemeshka"
---
# [Shemeshka](3-Mechanics/CLI/bestiary/npc/shemeshka-mpp.md)
*Source: Morte's Planar Parade p. 46*  

Shemeshka the arcanaloth is one of Sigil's most ambitious and notorious crime bosses. From her multiplanar casino, Fortune's Wheel, she manipulates secrets and fates across the planes. Shemeshka and her plots are further detailed in the adventure *Turn of Fortune's Wheel*.

```statblock
"name": "Shemeshka (MPP)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "162"
"hit_dice": "25d8 + 50"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "14"
  - !!int "21"
  - !!int "16"
  - !!int "18"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "7"
  - "intelligence": !!int "10"
  - "wisdom": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 18"
"languages": "all, telepathy 120 ft."
"cr": "14"
"traits":
  - "desc": "If Shemeshka fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "Shemeshka has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Shemeshka carries a magic crown called the Razorvine Tiara. In the hands\
      \ of anyone other than Shemeshka, the Razorvine Tiara functions as a tentacle\
      \ rod that deals slashing damage instead of bludgeoning damage."
    "name": "Special Equipment"
"actions":
  - "desc": "Shemeshka uses Arcane Flux or Spellcasting. She then makes one Claw attack\
      \ or one attack with her Razorvine Tiara."
    "name": "Multiattack"
  - "desc": "Shemeshka causes a surge of arcane energy to burst around one creature\
      \ she can see within 120 feet of herself. The target must make a DC 18 Dexterity\
      \ saving throw. On a failed save, the target takes 45 (7d12) force damage\
      \ and has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition until the end of its next turn. On a successful save, the target\
      \ takes half as much damage only."
    "name": "Arcane Flux"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (2d4 + 5) slashing damage plus 14 (4d6) poison damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 15 ft., one target. *Hit:*\
      \ 10 (3d6) slashing damage plus 9 (2d8) necrotic damage. If the target is\
      \ a creature, it must succeed on a DC 15 Constitution saving throw, or its speed\
      \ is halved and it has disadvantage on attack rolls and saving throws until\
      \ the end of its next turn."
    "name": "Razorvine Tiara"
  - "desc": "Shemeshka casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 18):\n\n\
      **At will:** [alter self](3-Mechanics/CLI/spells/alter-self.md), [darkness](3-Mechanics/CLI/spells/darkness.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only), [mage\
      \ hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**2/day each:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**1/day each:** [banishment](3-Mechanics/CLI/spells/banishment.md), [contact\
      \ other plane](3-Mechanics/CLI/spells/contact-other-plane.md) (as an action),\
      \ [mind blank](3-Mechanics/CLI/spells/mind-blank.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Shemeshka teleports, along with any equipment she is wearing or carrying,\
      \ up to 60 feet to an unoccupied space she can see."
    "name": "Teleport"
"reactions":
  - "desc": "Shemeshka utters a magical word to interrupt a creature she can see that\
      \ is casting a spell. If the spell is 5th level or lower, it fails and has no\
      \ effect. If the spell is 6th level or higher, Shemeshka makes an Intelligence\
      \ check (DC 10 + the spell's level). On a success, the spell fails and has no\
      \ effect. Whatever the spell's level, the caster gains the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition until the end of its next turn."
    "name": "Fell Counterspell (3/Day)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/npc/token/shemeshka-mpp.webp"
```
^statblock