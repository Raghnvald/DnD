---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reduced-Threat Clay Golem"
---
# [Reduced-Threat Clay Golem](3-Mechanics/CLI/bestiary/construct/reduced-threat-clay-golem-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Clay Golem (TftYP)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "66"
"hit_dice": "14d10 + 56"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "9"
  - !!int "18"
  - !!int "3"
  - !!int "8"
  - !!int "1"
"speed": "20 ft."
"damage_immunities": "acid; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks that aren't adamantine"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "understands the languages of its creator but can't speak"
"cr": "9"
"traits":
  - "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included\
      \ in the stat block), ability checks (included in the stat block for skill proficiencies),\
      \ saving throws (included in the stat block for saving throw proficiencies),\
      \ and saving throw DCs (included in the stat block)."
    "name": "Reduced Threat"
  - "desc": "Whenever the golem is subjected to acid damage, it takes no damage and\
      \ instead regains a number of hit points equal to the acid damage dealt."
    "name": "Acid Absorption"
  - "desc": "Whenever the golem starts its turn with 60 hit points or fewer, roll\
      \ a d6. On a 6, the golem goes berserk. On each of its turns while berserk,\
      \ the golem attacks the nearest creature it can see. If no creature is near\
      \ enough to move to and attack, the golem attacks an object, with preference\
      \ for an object smaller than itself. Once the golem goes berserk, it continues\
      \ to do so until it is destroyed or regains all its hit points."
    "name": "Berserk"
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
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 13 Constitution saving throw or have its hit point maximum reduced\
      \ by an amount equal to the damage taken. The target dies if this attack reduces\
      \ its hit point maximum to 0. The reduction lasts until removed by the  [greater\
      \ restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md) spell or\
      \ other magic."
    "name": "Slam"
  - "desc": "Until the end of its next turn, the golem magically gains a +2 bonus\
      \ to its AC, has advantage on Dexterity saving throws, and can use its slam\
      \ attack as a bonus action."
    "name": "Haste (Recharge 5-6)"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/construct/token/reduced-threat-clay-golem-tftyp.webp"
```
^statblock