---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- High Fae Kindguard
---
# [High Fae Kindguard](3-Mechanics\CLI\bestiary\fey/high-fae-kindguard-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

High fae kindguards have spent centuries perfecting their martial prowess, moving with a speed and grace others can only imagine. Their tall stature, large wings, elaborate horns, and massive weapons give them a truly intimidating silhouette.

The most trusted high fae kindguards are in direct service to Talion, the Kindly Lord. Nine times nine have these high fae sworn a binding oath to protect the Kindly Lord, each time pricking their hand on a hawthorn branch to seal the promise.

> [!quote] A quote from Gwyddion, messenger of Talion  
> 
> The Kindly Lord does not issue invitations to their court lightly. I suggest you accept.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

```statblock
"name": "High Fae Kindguard (MCV4EC)"
"size": "Medium"
"type": "fey"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "6"
"stats":
  - !!int "22"
  - !!int "23"
  - !!int "15"
  - !!int "14"
  - !!int "17"
  - !!int "13"
"speed": "40 ft., fly 60 ft. (hover)"
"saves":
  - "strength": !!int "10"
  - "dexterity": !!int "10"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+10"
  - "name": "Athletics"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Sylvan"
"cr": "12"
"traits":
  - "desc": "If the high fae is subjected to an effect that allows it to make a Dexterity\
      \ saving throw to take only half damage, it instead takes no damage if it succeeds\
      \ on the saving throw and only half damage if it fails, provided it doesn't\
      \ have the incapacitated condition."
    "name": "Evasion"
  - "desc": "The high fae has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The high fae makes two Fae Claymore attacks and uses Tripping Feint."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 20\
      \ (4d6 + 6) force damage, and the target's speed is reduced by 10 feet, to a\
      \ minimum speed of 5 feet. The reduction lasts until the start of the high fae's\
      \ next turn."
    "name": "Fae Claymore"
  - "desc": "The high fae targets one Large or smaller creature it can see within\
      \ 10 feet of itself. The target must succeed on a DC 18 Dexterity saving throw\
      \ or have the prone condition."
    "name": "Tripping Feint"
"bonus_actions":
  - "desc": "The high fae moves up to its speed. This movement doesn't provoke opportunity\
      \ attacks."
    "name": "Darting Flight"
"reactions":
  - "desc": "The high fae adds\_4 to its AC against one melee attack roll that would\
      \ hit it, provided it can see the attacker. After the attack hits or misses,\
      \ the high fae then makes one Fae Claymore attack against the attacker."
    "name": "Parry and Riposte"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/high-fae-kindguard-mcv4ec.webp"
```
^statblock