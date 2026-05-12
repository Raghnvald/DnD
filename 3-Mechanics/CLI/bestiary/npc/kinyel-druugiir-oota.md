---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kinyel Druu'giir"
---
# [Kinyel Druu'giir](3-Mechanics/CLI/bestiary/npc/kinyel-druugiir-oota.md)
*Source: Out of the Abyss p. 134*  

```statblock
"name": "Kinyel Druu'giir (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "poison"
"gear":
  - "[light crossbow](3-Mechanics/CLI/items/light-crossbow.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 13"
"languages": "Thieves' cant plus any two languages, Elvish, Undercommon"
"cr": "8"
"traits":
  - "desc": "The drow assassin\n\n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights.md)\n\
      \n**1/day each:** [darkness](3-Mechanics/CLI/spells/darkness.md), [faerie fire](3-Mechanics/CLI/spells/faerie-fire.md),\
      \ [levitate](3-Mechanics/CLI/spells/levitate.md) (self only)"
    "name": "Innate Spellcasting"
  - "desc": "During its first turn, Kinyel has advantage on attack rolls against any\
      \ creature that hasn't taken a turn. Any hit Kinyel scores against a [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised)\
      \ creature is a critical hit."
    "name": "Assassinate"
  - "desc": "If Kinyel is subjected to an effect that allows it to make a Dexterity\
      \ saving throw to take only half damage, Kinyel instead takes no damage if it\
      \ succeeds on the saving throw, and only half damage if it fails."
    "name": "Evasion"
  - "desc": "Kinyel deals an extra 14 (4d6) damage when it hits a target with a\
      \ weapon attack and has advantage on the attack roll, or when the target is\
      \ within 5 feet of an ally of Kinyel that isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and Kinyel doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
  - "desc": "The drow assassin"
    "name": "Fey Ancestry"
  - "desc": "the drow assassin"
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Kinyel makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage, and the target must make a DC 15 Constitution\
      \ saving throw, taking 24 (7d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution\
      \ saving throw, taking 24 (7d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Light Crossbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/kinyel-druugiir-oota.webp"
```
^statblock