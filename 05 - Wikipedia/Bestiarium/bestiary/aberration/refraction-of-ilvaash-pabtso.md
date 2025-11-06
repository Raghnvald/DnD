---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/15
  - Monster/Größe/Riesig
  - Monster/Typ/Aberration/Gedankenschinder
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Refraction of Ilvaash
---
# [Refraction of Ilvaash](3-Mechanics\CLI\bestiary\aberration/refraction-of-ilvaash-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 197*  

Ilvaash was formed from the remains of the mind flayer god Ilsensine, the God-Brain. When Ilsensine left the Far Realm to establish a divine domain elsewhere, pieces of the God-Brain sloughed away and awoke to sentience. This is Ilvaash, the Dissonant Psyche.

The refraction of Ilvaash wields only a sliver of the godlet's power but is nevertheless a formidable foe.

```statblock
"name": "Refraction of Ilvaash (PaBTSO)"
"size": "Huge"
"type": "aberration"
"subtype": "mind flayer"
"alignment": "Lawful Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "21d12 + 63"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "10"
  - !!int "17"
  - !!int "23"
  - !!int "20"
  - !!int "22"
"speed": "10 ft., fly 30 ft. (hover), swim 10 ft."
"saves":
  - "intelligence": !!int "11"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+15"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+11"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+11"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 120 ft., passive Perception\
  \ 15"
"languages": "Common, Deep Speech, telepathy 100 miles, Undercommon"
"cr": "15"
"traits":
  - "desc": "The refraction is aware of creatures within 100 miles of it that have\
      \ an Intelligence score of 4 or higher. It knows the distance and direction\
      \ to each creature, as well as each one's Intelligence score, but can't sense\
      \ anything else about it. A creature protected by a [mind blank](/3-Mechanics/CLI/spells/mind-blank-xphb.md)\
      \ spell, a [nondetection](/3-Mechanics/CLI/spells/nondetection-xphb.md) spell,\
      \ or similar magic can't be perceived in this manner."
    "name": "Creature Sense"
  - "desc": "The refraction can move through other creatures and objects as if they\
      \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
      \ inside an object."
    "name": "Incorporeal Movement"
  - "desc": "If the refraction fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "The refraction has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The refraction makes two Dissonant Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft. or range 120 ft., one\
      \ creature. *Hit:* 25 (3d12 + 6) psychic damage. If the target is a creature\
      \ [concentrating](/3-Mechanics/CLI/conditions.md#Concentration) on a spell,\
      \ its [concentration](/3-Mechanics/CLI/conditions.md#Concentration) is broken."
    "name": "Dissonant Claw"
  - "desc": "Creatures of the refraction's choice within 60 feet of it must succeed\
      \ on a DC 19 Intelligence saving throw or take 33 (5d10 + 6) psychic damage\
      \ and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned) condition for\
      \ 1 minute. A [stunned](/3-Mechanics/CLI/conditions.md#Stunned) creature can\
      \ repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
  - "desc": "The refraction teleports, along with any equipment it is wearing or carrying,\
      \ up to 120 feet to an unoccupied place that it can see."
    "name": "Teleport"
  - "desc": "The refraction casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 19):\n\n**At will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md)\n\n**3/day\
      \ each:** [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md), [modify\
      \ memory](/3-Mechanics/CLI/spells/modify-memory-xphb.md)\n\n**1/day each:**\
      \ [feeblemind](/3-Mechanics/CLI/spells/befuddlement-xphb.md), [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ (self only)"
    "name": "Spellcasting (Psionics)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the refraction of ilvaash can expend a use to take one of the following\
  \ actions. The refraction of ilvaash regains all expended uses at the start of each\
  \ of its turns."
"legendary_actions":
  - "desc": "The refraction targets a creature within 120 feet of itself and disrupts\
      \ its mental processes, causing the target to have disadvantage on all ability\
      \ checks, attack rolls, and saving throws until the end of the target's next\
      \ turn."
    "name": "Mindbreaker"
  - "desc": "The refraction makes one Dissonant Claw attack."
    "name": "Projected Claw (Costs 2 Actions)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/refraction-of-ilvaash-pabtso.webp"
```
^statblock