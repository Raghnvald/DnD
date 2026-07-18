---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fire Hellion
Status: WIP
linter-yaml-title-alias: Fire Hellion
tags:
  - Monster/Größe/Riesig
  - Monster/HG/11
  - Monster/Typ/Unhold/devil
  - Quelle/5e/bgg
aliases:
  - Fire Hellion
---
# [Fire Hellion](3-Mechanics\CLI\bestiary\fiend/fire-hellion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 140*  

> [!quote] A quote from Bigby  
> 
> To my mind, the fire hellion perfectly illustrates the difference between natural fire and the corrupt flames of the Nine Hells.

Fire giants study war in its many forms across the multiverse, which sometimes leads the giants to a fascination with the Blood War—the endless conflict between demons and devils across the Lower Planes. Such a giant might enter into a pact with a powerful devil, hoping to learn tactics the devils have fine-tuned over millennia and to acquire magical gifts to help the giant rise in the ordning.

Over time, the giant is corrupted, becoming a Fiend in its own right. The devil teaches the giant how to forge with infernal iron and hellfire, enabling the giant to craft weapons that can funnel the souls of the slain to Avernus, the first layer of the Nine Hells. In this way, the devil stands to gain a constant supply of souls from the giant's enemies, as well as the promise that the giant will serve the devil as a smith in the Nine Hells after death.

The corrupted fire giant takes on fiendish features, including horns, cloven hooves for feet, and a forked tail.

```statblock
"name": "Fire Hellion (BGG)"
"size": "Huge"
"type": "fiend"
"subtype": "devil"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "175"
"hit_dice": "14d12 + 84"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "23"
  - !!int "16"
  - !!int "14"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Common, Giant, Infernal"
"cr": "11"
"traits":
  - "desc": "The hellion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "A Giant or a Humanoid that is reduced to 0 hit points by the hellion\
      \ dies, and its soul rises as a lemure (see the Monster Manual) on Avernus,\
      \ one of the Nine Hells, in 1d4 hours. If the creature isn't revived before\
      \ then, it can be restored to life only by a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell or by killing the lemure and casting true resurrection on the creature's\
      \ original body."
    "name": "Soul Taker"
"actions":
  - "desc": "The hellion makes two Morningstar attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 20\
      \ (3d8 + 7) piercing damage plus 11 (2d10) fire damage. If the target is a creature,\
      \ it can't regain hit points until the start of the hellion's next turn."
    "name": "Morningstar"
  - "desc": "The hellion hurls a magical ball of fire that explodes in a 20-foot-radius\
      \ sphere centered on a point the hellion can see within 120 feet of itself.\
      \ The sphere spreads around corners. Each creature in that area must make a\
      \ DC 17 Dexterity saving throw. A creature takes 18 (4d8) fire damage and 18\
      \ (4d8) necrotic damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Infernal Orb"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/fire-hellion-bgg.webp"
```
^statblock