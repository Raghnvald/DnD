---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/10
  - monster/size/medium
  - monster/type/undead/mind-flayer
  - monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Oshundo the Alhoon
---
# [Oshundo the Alhoon](3-Mechanics\CLI\bestiary\npc/oshundo-the-alhoon-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 153*  

Oshundo lived in Illithinoch at the height of the mind flayer empire many centuries ago, but Oshundo was driven out for practicing arcane magic. It's obvious that this rejection still stings Oshundo, who refers to Illithinoch's long-dead leaders as "ignorant fools" who are "closed to the flexibility and power of arcane magic."

```statblock
"name": "Oshundo the Alhoon (PaBTSO)"
"size": "Medium"
"type": "undead"
"subtype": "mind flayer, wizard"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "16"
  - !!int "19"
  - !!int "17"
  - !!int "17"
"speed": "30 ft., fly 15 ft. (hover)"
"saves":
  - "constitution": !!int "7"
  - "intelligence": !!int "8"
  - "wisdom": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 17"
"languages": "Common, Deep Speech, telepathy 120 ft., Undercommon"
"cr": "10"
"traits":
  - "desc": "Oshundo has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Oshundo makes two Chilling Grasp or Arcane Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14 (4d6)\
      \ cold damage, and Oshundo regains 14 hit points if the target is a creature."
    "name": "Chilling Grasp"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 120 ft., one target. *Hit:* 28\
      \ (8d6) force damage."
    "name": "Arcane Bolt"
  - "desc": "Oshundo emits a wave of domineering energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 16 Intelligence saving throw or take 22\
      \ (4d8 + 4) thunder damage and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition for 1 minute. A [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Thundering Blast (Recharge 5-6)"
  - "desc": "Oshundo casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      **At will:** [dancing lights](/3-Mechanics/CLI/spells/dancing-lights-xphb.md),\
      \ [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1/day\
      \ each:** [dominate monster](/3-Mechanics/CLI/spells/dominate-monster-xphb.md),\
      \ [globe of invulnerability](/3-Mechanics/CLI/spells/globe-of-invulnerability-xphb.md),\
      \ [invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md), [modify memory](/3-Mechanics/CLI/spells/modify-memory-xphb.md),\
      \ [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only), [wall\
      \ of force](/3-Mechanics/CLI/spells/wall-of-force-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Oshundo targets one creature it can perceive within 60 feet of itself\
      \ that is casting a spell. If the spell is 3rd level or lower, the spell fails,\
      \ but any spell slots or charges aren't wasted."
    "name": "Negate Spell (3/Day)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/oshundo-the-alhoon-pabtso.webp"
```
^statblock