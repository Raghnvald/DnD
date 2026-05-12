---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kozilek"
---
# [Kozilek](3-Mechanics/CLI/bestiary/npc/kozilek-psz.md)
*Source: Plane Shift: Zendikar p. 38*  

```statblock
"name": "Kozilek (PSZ)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "472"
"hit_dice": "27d20 + 189"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "25"
  - !!int "22"
  - !!int "18"
  - !!int "20"
"speed": "20 ft., swim 60 ft."
"saves":
  - "strength": !!int "17"
  - "dexterity": !!int "7"
  - "constitution": !!int "14"
  - "intelligence": !!int "13"
  - "wisdom": !!int "11"
"damage_immunities": "lightning; bludgeoning, piercing, slashing from nonmagical attacks;\
  \ psychic"
"condition_immunities": "[frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 14"
"languages": "Abyssal, Celestial, Infernal, Primordial, telepathy 120 ft. but can't\
  \ speak"
"cr": "23"
"traits":
  - "desc": "Kozilek can breathe air and water."
    "name": "Amphibious"
  - "desc": "Kozilek ignores difficult terrain, and magical effects can't reduce its\
      \ speed or cause it to be [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ It can spend 5 feet of movement to escape from nonmagical restraints or being\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)."
    "name": "Freedom of Movement"
  - "desc": "Kozilek deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Kozilek makes three tentacle attacks, each of which it can replace with\
      \ one use of Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 5 ft., one target. *Hit:*\
      \ 23 (3d8 + 10) piercing damage. If the target is a Large or smaller creature\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by Kozilek, that\
      \ creature is swallowed, and the grapple ends. While swallowed, the creature\
      \ is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ it has total cover against attacks and other effects outside Kozilek, and\
      \ it takes 42 (12d6) acid damage at the start of each of Kozilek's turns.\
      \ If Kozilek takes 50 damage or more on a single turn from a creature inside\
      \ it, Kozilek must succeed on a DC 25 Constitution saving throw at the end of\
      \ that turn or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of Kozilek. If Kozilek dies, a swallowed creature\
      \ is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 30 ft., one target. *Hit:*\
      \ 20 (3d6 + 10) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 18). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ Kozilek has ten tentacles, each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Large or smaller object held or creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by Kozilek is thrown up to 60 feet in a random direction and knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning\
      \ damage for every 10 feet it was thrown. If the target is thrown at another\
      \ creature, that creature must succeed on a DC 18 Dexterity saving throw or\
      \ take the same damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Fling"
  - "desc": "Kozilek magically creates three bolts of lightning, each of which can\
      \ strike a target Kozilek can see within 120 feet of it. A target must make\
      \ a DC 23 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Lightning Storm"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Kozilek can expend a use to take one of the following actions. Kozilek regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Kozilek makes one tentacle attack or uses its Fling."
    "name": "Tentacle Attack or Fling"
  - "desc": "Kozilek uses Lightning Storm."
    "name": "Lightning Storm (Costs 2 Actions)"
  - "desc": "While underwater, Kozilek expels an ink cloud in a 60-foot radius. The\
      \ cloud spreads around corners, and that area is heavily obscured to creatures\
      \ other than Kozilek. Each creature other than Kozilek that ends its turn there\
      \ must succeed on a DC 23 Constitution saving throw, taking 16 (3d10) poison\
      \ damage on a failed save, or half as much damage on a successful one. A strong\
      \ current disperses the cloud, which otherwise disappears at the end of Kozilek's\
      \ next turn."
    "name": "Ink Cloud (Costs 3 Actions)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/npc/token/kozilek-psz.webp"
```
^statblock