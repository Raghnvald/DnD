---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/11
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Voalsh
---
# [Voalsh](3-Mechanics\CLI\bestiary\npc/voalsh-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 194*  

```statblock
"name": "Voalsh (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md)"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "15"
  - !!int "21"
  - !!int "17"
  - !!int "18"
"speed": "0 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight)\
  \ 15 ft., passive Perception 17"
"languages": "Deep Speech, telepathy 120 ft., Undercommon"
"cr": "11"
"traits":
  - "desc": "If Voalsh fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Voalsh has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Voalsh makes two Tentacle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature. *Hit:* 21\
      \ (3d10 + 5) psychic damage. If the target is Medium or smaller, it has the\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape DC 17)\
      \ and must succeed on a DC 17 Intelligence saving throw or have the [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the grapple ends."
    "name": "Tentacle"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ Humanoid [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by Voalsh. *Hit:*\
      \ 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points,\
      \ Voalsh kills it by extracting and devouring its brain."
    "name": "Extract Brain"
  - "desc": "Voalsh opens a rift into the Far Realm, centered on a point Voalsh can\
      \ see within 60 feet of itself, and a tentacle lashes across creatures near\
      \ the rift. Each creature other than mind flayers within 30 feet of the rift\
      \ must make a DC 17 Intelligence saving throw, after which the tentacle disappears\
      \ and the rift closes. On a failed save, a creature takes 18 (4d8) cold damage\
      \ from the rift plus 18 (4d8) psychic damage from the tentacle and has the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition for 1 minute. On a successful save, a creature takes half as much\
      \ damage only. A [stunned](/3-Mechanics/CLI/conditions.md#Stunned) creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Unleash Void (Recharge 5-6)"
  - "desc": "Voalsh casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 17):\n\n\
      **At will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is invisible)\n\n**3/day each:** [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md)\
      \ (as an action), [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md)\n\
      \n**1/day:** [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md) (self\
      \ only)"
    "name": "Spellcasting (Psionics)"
"reactions":
  - "desc": "When hit by an attack roll, Voalsh gains a +4 bonus to its AC against\
      \ that attack roll, potentially causing it to miss. Then Voalsh, along with\
      \ any equipment it is wearing or carrying, magically teleports up to 60 feet\
      \ to an unoccupied space it can see."
    "name": "Warp Reality"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/voalsh-pabtso.webp"
```
^statblock