---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/derro
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Droki"
---
# [Droki](3-Mechanics/CLI/bestiary/npc/droki-oota.md)
*Source: Out of the Abyss p. 231*  

## Roleplaying Droki

Droki hates everyone in general and surfacers in particular. He gnashes his teeth if he has to address the characters, taking every opportunity to be insulting and misleading. If the characters look through his satchel while he's still conscious, he throws an epic tantrum and becomes intractable until knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious).

Droki is also obsessed with things happening where and when they should. If he is captured before he runs his errands in the Whorlstone Tunnels, he constantly complains about the characters altering fate by delaying him, and a good tactic to pressure him is to threaten to hold him indefinitely. He prefers to escape than to fight, except if the characters take his satchel.

```statblock
"name": "Droki (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "31"
"hit_dice": "7d6 + 7"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "5"
  - !!int "16"
"speed": "30 ft. (60 ft. with boots of speed)"
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
  - "desc": "Droki's innate spellcasting ability is Charisma (spell save DC 13). He\
      \ can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\n\
      **1/day each:** [darkness](3-Mechanics/CLI/spells/darkness.md), [fear](3-Mechanics/CLI/spells/fear.md),\
      \ [shatter](3-Mechanics/CLI/spells/shatter.md)"
    "name": "Innate Spellcasting"
  - "desc": "Droki wears boots of speed."
    "name": "Special Equipment"
  - "desc": "Droki has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Insanity"
  - "desc": "Droki deals an extra 7 (2d6) damage when he hits a target with a weapon\
      \ attack and has advantage on the attack roll, or when the target is within\
      \ 5 feet of an ally of Droki that isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and Droki doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
  - "desc": "The derro has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "While in sunlight, the derro has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Droki makes two attacks with his shortsword"
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage. The sword is coated with serpent venom that wears\
      \ off after the first hit. A target subjected to the venom must make a DC 11\
      \ Constitution saving throw, taking 10 (3d6) poison damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "Shortsword"
"reactions":
  - "desc": "Droki adds 3 to his AC against one melee attack that would hit him. To\
      \ do so, Droki must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/droki-oota.webp"
```
^statblock