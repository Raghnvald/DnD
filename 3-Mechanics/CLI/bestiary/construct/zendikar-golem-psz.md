---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zendikar Golem"
---
# [Zendikar Golem](3-Mechanics/CLI/bestiary/construct/zendikar-golem-psz.md)
*Source: Plane Shift: Zendikar p. 36*  

With the power of magic at their disposal, mages of the ancient past and of Zendikar's present have been able to create objects bearing the semblance of life, capable of carrying out orders and even acting independently.

In a number of ancient sites associated with the Eldrazi, stone creatures have been found standing eternal guard. Created from fragments of hedrons or carved to resemble them, these constructs were intended to help the people of Zendikar eliminate the brood lineages after the titans were imprisoned, and were implanted with a fragment of the power that bound and imprisoned the Eldrazi. They have served as useful allies in battling the Eldrazi broods, and some mages have had limited success in prying the secrets of their magic from their artificial minds. Other hedron constructs are of more recent make, fashioned in imitation of the originals. These have no power over the Eldrazi beyond what their physical strength gives them, and their creators used them for menial tasks. They are most often found in the ancient ruins of the kor or in merfolk cities. The various **modrons** can be used to represent these dedicated constructs.

The golems of Zendikar are effectively artificial elementals, and can be represented by [stone golems](3-Mechanics/CLI/bestiary/construct/stone-golem.md). Mages fashion bodies from special stone and infuse them with the power of movement and limited understanding. Golems are rare and powerful, especially when shaped from stone that already possesses magical power.

```statblock
"name": "Zendikar Golem (PSZ)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "20"
  - !!int "3"
  - !!int "11"
  - !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
  - "desc": "The golem is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "The golem has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The golem's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The golem makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 19 (3d8 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "The golem targets one or more creatures it can see within 10 feet of\
      \ it. Each target must make a DC 17 Wisdom saving throw against this magic.\
      \ On a failed save, a target can't use reactions, its speed is halved, and it\
      \ can't make more than one attack on its turn. In addition, the target can take\
      \ either an action or a bonus action on its turn, not both. These effects last\
      \ for 1 minute. A target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Slow (Recharge 5-6)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/construct/token/zendikar-golem-psz.webp"
```
^statblock