---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/20
  - Monster/Größe/Gigantisch
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Flesh Colossus
---
# [Flesh Colossus](3-Mechanics\CLI\bestiary\construct/flesh-colossus-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 141*  

During the dawn of the giants' empires, twisted minds sought to make their fallen comrades continue their service. Wizard giants stitched and wove the flesh of various giants over an adamantine skeleton, creating a grisly colossal construct. Inside the flesh colossus's chest is a stone sphere infused with spirits from each elemental plane acting as its core.

To this day, some of these ancient flesh colossi guard abandoned ruins, sites sacred to giants, and lost treasures—and possibly the procedure to create new examples of their kind.

```statblock
"name": "Flesh Colossus (BGG)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "280"
"hit_dice": "16d20 + 112"
"modifier": !!int "-1"
"stats":
  - !!int "24"
  - !!int "9"
  - !!int "24"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "60 ft."
"damage_immunities": "lightning; poison; psychic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 10"
"languages": "understands Giant but can't speak"
"cr": "20"
"traits":
  - "desc": "If the core inside the colossus is destroyed, the colossus goes berserk.\
      \ On each of its turns while berserk, the colossus attacks the nearest creature\
      \ it can see. If no creature is near enough to move to and attack, the colossus\
      \ attacks an object. Once the colossus goes berserk, it remains berserk until\
      \ it is destroyed."
    "name": "Berserk"
  - "desc": "The colossus is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "The colossus has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The colossus deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The colossus makes two Fist attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit (with advantage if the colossus is\
      \ berserk), reach 20 ft., one target. *Hit:* 17 (3d6 + 7) bludgeoning damage.\
      \ If the target is a Large or smaller creature, it is pulled up to 15 feet toward\
      \ the colossus, it has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 17), and it has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition until this grapple ends. The colossus can have up to two creatures\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) this way at a time."
    "name": "Fist"
  - "desc": "The colossus exhales a cloud swirling with elemental energy in a 90-foot\
      \ cone. Each creature in that area must make a DC 21 Dexterity saving throw.\
      \ On a failed save, a creature takes 40 (9d8) damage of a type of the colossus's\
      \ choosing: acid, cold, fire, or lightning. On a successful save, a creature\
      \ takes half as much damage.\n\nAt the same time as the colossus releases this\
      \ exhalation, creatures inside the colossus's chest cavity take 40 (9d8) force\
      \ damage from churning elemental energy."
    "name": "Elemental Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one Large or smaller\
      \ creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the colossus.\
      \ *Hit:* 20 (3d8 + 7) bludgeoning damage, and the creature is swallowed. A swallowed\
      \ creature has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition,\
      \ has total cover against attacks and other effects outside the colossus, and\
      \ takes 10 (3d6) force damage at the start of each of the colossus's turns.\n\
      \nThe colossus's chest cavity can hold up to two creatures at a time. Inside\
      \ its chest cavity is its core, which is a Large object with AC 16 that is immune\
      \ to lightning, poison, and psychic damage. It has 140 hit points and sheds\
      \ dim light in a 10-foot radius. If the core is destroyed, the colossus regurgitates\
      \ all swallowed creatures, each of which falls in a space within 10 feet of\
      \ the colossus and has the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition,\
      \ and the colossus can no longer swallow a creature. If the colossus dies, any\
      \ swallowed creature no longer has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition and can escape from the corpse using 10 feet of movement, exiting\
      \ with the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Bite"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/construct/token/flesh-colossus-bgg.webp"
```
^statblock