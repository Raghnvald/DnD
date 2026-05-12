---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/llk
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Clockwork Kraken"
---
# [Clockwork Kraken](3-Mechanics/CLI/bestiary/construct/clockwork-kraken-llk.md)
*Source: Lost Laboratory of Kwalish p. 38*  

```statblock
"name": "Clockwork Kraken (LLK)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "3"
  - !!int "11"
  - !!int "1"
"speed": "30 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
  - "desc": "The clockwork kraken has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "The clockwork kraken has eight tentacles, each of which is treated as\
      \ a Medium creature, moves independently on the construct's turn, and has a\
      \ flying speed of 40 feet. The clockwork kraken's senses operate through its\
      \ tentacles as well as its main body. Each tentacle can be attacked independently,\
      \ with damage dealt to tentacles applied to the clockwork kraken's hit point\
      \ total. A tentacle is destroyed if it takes more than 20 damage.\n\nReducing\
      \ the construct to three or fewer tentacles reduces its attacks accordingly.\
      \ A clockwork kraken can regrow any destroyed tentacles at the end of a long\
      \ rest."
    "name": "Independent Tentacles"
"actions":
  - "desc": "The clockwork kraken makes four tentacle slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) bludgeoning damage."
    "name": "Tentacle Slam"
"source":
  - "LLK"
"image": "3-Mechanics/CLI/bestiary/construct/token/clockwork-kraken-llk.webp"
```
^statblock