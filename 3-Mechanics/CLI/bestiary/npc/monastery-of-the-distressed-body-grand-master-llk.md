---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/llk
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Monastery of the Distressed Body Grand Master"
---
# [Monastery of the Distressed Body Grand Master](3-Mechanics/CLI/bestiary/npc/monastery-of-the-distressed-body-grand-master-llk.md)
*Source: Lost Laboratory of Kwalish p. 14*  

```statblock
"name": "Monastery of the Distressed Body Grand Master (LLK)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "16"
"speed": "40 ft., fly 40 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": "Infernal, telepathy 120 ft."
"cr": "9"
"traits":
  - "desc": "Shards of a vorpal sword once broken against the devil replace its claws.\
      \ A successful DC 12 Intelligence ([Arcana](3-Mechanics/CLI/rules/skills.md#Arcana))\
      \ or Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) check\
      \ identifies them as such. When the devil rolls a 20 on an attack roll with\
      \ a claw, the target is decapitated. (At your option, the attack can instead\
      \ deal an extra 6d8 slashing damage.) A target is immune to this effect if\
      \ it is immune to slashing damage, has legendary actions, doesn't have or need\
      \ a head, or if you decide that the target is too large for its head to be cut\
      \ off by the devil's claws. If removed, the shards lose their magical powers."
    "name": "Vorpal Claws"
  - "desc": "Local teleportation-field bracelets encircle the devil's arms and tail.\
      \ These devices allow the Grand Master to make its claw and sting attacks remotely,\
      \ though still on the devil's turn and using its actions."
    "name": "Teleportation Bracelets"
  - "desc": "Magical darkness doesn't impede the Grand Master's darkvision."
    "name": "Devil's Sight"
  - "desc": "The Grand Master has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Grand Master makes three attacks: two with its claws and one with\
      \ its sting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) piercing damage plus 17 (5d6) poison damage, and the target\
      \ must succeed on a DC 14 Constitution saving throw or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Sting"
"source":
  - "LLK"
"image": "3-Mechanics/CLI/bestiary/npc/token/monastery-of-the-distressed-body-grand-master-llk.webp"
```
^statblock