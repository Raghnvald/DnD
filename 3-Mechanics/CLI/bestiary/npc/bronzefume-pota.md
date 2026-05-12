---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bronzefume"
---
# [Bronzefume](3-Mechanics/CLI/bestiary/npc/bronzefume-pota.md)
*Source: Princes of the Apocalypse p. 92*  

```statblock
"name": "Bronzefume (PotA)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "220"
"hit_dice": "22d20 + 110"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "20 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "11"
  - "wisdom": !!int "7"
"damage_resistances": "fire"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Aquan, Draconic"
"cr": "13"
"traits":
  - "desc": "The dragon turtle can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The dragon turtle makes three attacks: one with its bite and two with\
      \ its claws. It can make one tail attack in place of its two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:*\
      \ 26 (3d12 + 7) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:*\
      \ 26 (3d12 + 7) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 20 Strength saving throw or be pushed up to 10 feet away from the\
      \ dragon turtle and knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Tail"
  - "desc": "The dragon turtle exhales scalding steam in a 60-foot cone. Each creature\
      \ in that area must make a DC 18 Constitution saving throw, taking 52 (15d6)\
      \ fire damage on a failed save, or half as much damage on a successful one.\
      \ Being underwater doesn't grant resistance against this damage."
    "name": "Steam Breath (Recharge 5-6)"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/bronzefume-pota.webp"
```
^statblock