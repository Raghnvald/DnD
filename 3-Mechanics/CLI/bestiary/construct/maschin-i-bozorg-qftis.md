---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Maschin-i-Bozorg"
---
# [Maschin-i-Bozorg](3-Mechanics/CLI/bestiary/construct/maschin-i-bozorg-qftis.md)
*Source: Quests from the Infinite Staircase p. 207*  

The kagu-svirfneblin's most prized invention is the maschin-i-bozorg: a dome-shaped, steam-powered battle construct propelled by a multitude of wheels along its flat underside. Maschin-i-bozorgs typically act as guardians and sentries, tirelessly patrolling the sites they're assigned to protect. Each machine obeys the commands of its creator.

A machin-i-bozorg can roll over its enemies to crush them with its immense weight. It can also fire poison darts with deadly precision, jab creatures with similar darts attached to extendable arms that retract inside its body, and spray jets of scalding steam to fend off intruders.

```statblock
"name": "Maschin-i-Bozorg (QftIS)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "20"
  - !!int "2"
  - !!int "10"
  - !!int "1"
"speed": "20 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
  \ [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 10"
"languages": "understands Gnomish but can't speak"
"cr": "8"
"traits":
  - "desc": "When the maschin-i-bozorg is reduced to 0 hit points, its power source\
      \ overloads, briefly superheating its outer shell. Each creature within 10 feet\
      \ of the maschin-i-bozorg must make a DC 16 Constitution saving throw, taking\
      \ 7 (2d6) fire damage on a failed save or half as much damage on a successful\
      \ one."
    "name": "Overheat"
"actions":
  - "desc": "The maschin-i-bozorg makes two Poison Jab attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 13 (4d4 + 3) piercing damage, and the target must\
      \ succeed on a DC 16 Constitution saving throw or have the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition for 1 minute. The target can repeat the saving throw at the end\
      \ of each of its turns, ending the effect on itself on a success."
    "name": "Poison Jab"
  - "desc": "The maschin-i-bozorg emits scalding steam in a 30-foot cone. Each creature\
      \ in that area must make a DC 16 Constitution saving throw, taking 28 (8d6)\
      \ fire damage on a failed save or half as much damage on a successful one."
    "name": "Steam Jet (Recharge 5-6)"
"bonus_actions":
  - "desc": "The maschin-i-bozorg moves up to its speed in a straight line. During\
      \ this movement, it can enter Medium and smaller creatures' spaces. A creature\
      \ whose space the maschin-i-bozorg enters must make a DC 15 Dexterity saving\
      \ throw. On a successful save, the creature is pushed to the nearest unoccupied\
      \ space out of the maschin-i-bozorg's path. On a failed save, the creature takes\
      \ 10 (3d6) bludgeoning damage and has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition.\n\nIf the maschin-i-bozorg remains in the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature's space, the creature also has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition until it's no longer in the same space as the maschin-i-bozorg.\
      \ While [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) in this\
      \ way, the creature, or another creature within 5 feet of it, can use its action\
      \ to make a DC 15 Strength ([Athletics](3-Mechanics/CLI/rules/skills.md#Athletics))\
      \ check. On a successful check, the creature is shunted to an unoccupied space\
      \ of its choice within 5 feet of the maschin-i-bozorg."
    "name": "Crushing Stride"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/construct/token/maschin-i-bozorg-qftis.webp"
```
^statblock