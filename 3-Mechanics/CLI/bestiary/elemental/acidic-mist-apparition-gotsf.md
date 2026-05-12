---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gotsf
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Acidic Mist Apparition"
---
# [Acidic Mist Apparition](3-Mechanics/CLI/bestiary/elemental/acidic-mist-apparition-gotsf.md)
*Source: Giants of the Star Forge p. 6*  

```statblock
"name": "Acidic Mist Apparition (GotSF)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"modifier": !!int "5"
"stats":
  - !!int "14"
  - !!int "20"
  - !!int "14"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "fly 90 ft. (hover)"
"damage_resistances": "lightning; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "exhaustion, grappled, paralyzed, petrified, poisoned, prone,\
  \ restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Auran"
"cr": "5"
"traits":
  - "desc": "The apparition can enter a hostile creature's space and stop there. It\
      \ can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Air Form"
"actions":
  - "desc": "The apparition makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) acid damage."
    "name": "Slam"
  - "desc": "Each creature in the apparition's space must make a DC 13 Strength saving\
      \ throw. On a failure, a target takes 15 (3d8 + 2) bludgeoning damage and\
      \ is flung up 20 feet away from the apparition in a random direction and knocked\
      \ prone. If a thrown target strikes an object, such as a wall or floor, the\
      \ target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown.\
      \ If the target is thrown at another creature, that creature must succeed on\
      \ a DC 13 Dexterity saving throw or take the same damage and be knocked prone.\n\
      \nIf the saving throw is successful, the target takes half the bludgeoning damage\
      \ and isn't flung away or knocked prone."
    "name": "Whirlwind (Recharge 4-6)"
"source":
  - "GotSF"
"image": "3-Mechanics/CLI/bestiary/elemental/token/acidic-mist-apparition-gotsf.webp"
```
^statblock