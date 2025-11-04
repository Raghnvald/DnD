---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/rot
  - Monster/cr/30
  - Monster/Größe/Gigantisch
  - Monster/Typ/Unhold
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Tiamat
---
# [Tiamat](3-Mechanics\CLI\bestiary\npc/tiamat-rot.md)
*Source: The Rise of Tiamat p. 92, Baldur's Gate: Descent Into Avernus*  

```statblock
"name": "Tiamat (RoT)"
"size": "Gargantuan"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "25"
"ac_class": "natural armor"
"hp": !!int "615"
"hit_dice": "30d20 + 300"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "10"
  - !!int "30"
  - !!int "26"
  - !!int "26"
  - !!int "28"
"speed": "60 ft., fly 120 ft."
"saves":
  - "strength": !!int "19"
  - "dexterity": !!int "9"
  - "wisdom": !!int "17"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+17"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+26"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+17"
"damage_immunities": "acid; cold; fire; lightning; poison; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 240 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight)\
  \ 120 ft., passive Perception 36"
"languages": "Common, Draconic, Infernal"
"cr": "30"
"traits":
  - "desc": "Tiamat can innately cast the following spell, her spellcasting ability\
      \ is Charisma (spell save DC 26):\n\n**3/day:** [divine word](/3-Mechanics/CLI/spells/divine-word-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "When Tiamat drops to 0 hit points or dies, her body is destroyed but\
      \ her essence travels back to her domain in the Nine Hells, and she is unable\
      \ to take physical form for a time."
    "name": "Discorporation"
  - "desc": "If Tiamat fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "Unless she wishes to be affected, Tiamat is immune to spells of 6th level\
      \ or lower. She has advantage on saving throws against all other spells and\
      \ magical effects."
    "name": "Limited Magic Immunity"
  - "desc": "Tiamat's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "Tiamat can take one reaction per turn, rather than only one per round.\
      \ She also has advantage on saving throws against being knocked [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious).\
      \ If she fails a saving throw against an effect that would stun a creature,\
      \ one of her unspent legendary actions is spent."
    "name": "Multiple Heads"
  - "desc": "Tiamat regains 30 hit points at the start of her turn."
    "name": "Regeneration"
"actions":
  - "desc": "Tiamat can use her Frightful Presence. She then makes three attacks:\
      \ two with her claws and one with her tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +19 to hit, reach 15 ft., one target. *Hit:* 24\
      \ (4d6 + 10) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +19 to hit, reach 25 ft., one target. *Hit:* 28\
      \ (4d8 + 10) piercing damage."
    "name": "Tail"
  - "desc": "Each creature of Tiamat's choice that is within 240 feet of Tiamat and\
      \ aware of her must succeed on a DC 26 Wisdom saving throw or become [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Tiamat's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
"legendary_description": "Tiamat can take 5 legendary actions, choosing from the options\
  \ below. Only one legendary action can be used at a time and only at the end of\
  \ another creature's turn. Tiamat regains spent legendary actions at the start of\
  \ its turn.\n\nTiamat's legendary action options are associated with her five dragon\
  \ heads (a bite and a breath weapon for each). Once Tiamat chooses a legendary action\
  \ option for one of her heads, she can't choose another one associated with that\
  \ head until the start of her next turn."
"legendary_actions":
  - "desc": "*Melee Weapon Attack:* +19 to hit, reach 20 ft., one target. *Hit:* 32\
      \ (4d10 + 10) slashing damage plus 14 (4d6) acid damage (black dragon head),\
      \ lightning damage (blue dragon head), poison damage (green dragon head), fire\
      \ damage (red dragon head), or cold damage (white dragon head)."
    "name": "Bite"
  - "desc": "Tiamat breathes acid in a 120-foot line that is 10 feet wide. Each creature\
      \ in that line must make a DC 27 Dexterity saving throw, taking 67 (15d8) acid\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Black Dragon Head: Acid Breath (Costs 2 Actions)"
  - "desc": "Tiamat breathes lightning in a 120-foot line that is 10 feet wide. Each\
      \ creature in that line must make a DC 27 Dexterity saving throw, taking 88\
      \ (16d10) lightning damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Blue Dragon Head: Lightning Breath (Costs 2 Actions)"
  - "desc": "Tiamat breathes poisonous gas in a 90-foot cone. Each creature in that\
      \ area must make a DC 27 Constitution saving throw, taking 77 (22d6) poison\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Green Dragon Head: Poison Breath (Costs 2 Actions)"
  - "desc": "Tiamat breathes fire in a 90-foot cone. Each creature in that area must\
      \ make a DC 27 Dexterity saving throw, taking 91 (26d6) fire damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Red Dragon Head: Fire Breath (Costs 2 Actions)"
  - "desc": "Tiamat breathes an icy blast in a 90-foot cone. Each creature in that\
      \ area must make a DC 27 Dexterity saving throw, taking 72 (16d8) cold damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "White Dragon Head: Cold Breath (Costs 2 Actions)"
"source":
  - "RoT"
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/tiamat-rot.webp"
```
^statblock