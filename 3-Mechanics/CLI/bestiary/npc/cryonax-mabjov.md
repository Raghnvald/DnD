---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cryonax"
---
# [Cryonax](3-Mechanics/CLI/bestiary/npc/cryonax-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 98*  

> [!quote] A quote from Volo  
> 
> By all the gods! How the ranger hasn't gotten himself killed is beyond my understanding.

> [!quote] A quote from MINSC  
> 
> Some fish people told Boo about a dread beast called Leemooggoogoon. We eventually found it on the icy glaciers to the north, but it didn't go so well. Sometimes when you dare to kick the butt of evil, your feet get frozen into icicles..

Cryonax, the Prince of Evil Ice Creatures, is an elemental prince of evil from the Plane of Ice. Cryonax appears as a hulking simian beast that stands about fifteen feet tall. Shaggy white fur covers his powerfully built humanoid body. Instead of arms, he has a pair of long, suckered, tentacles. The air around him is frigid and cold as death itself.

The elemental princes of evil are ancient elemental beings that wield immense power. Each one of them commands countless twisted and evil elementals and is worshipped by insane cultists on the mortal world. Unlike the princes that are embodiments of the four base elements, Cryonax draws power from multiple elements. For this reason, some feel that Cryonax is the favorite prince of the Elder Elemental Eye. The Eye is a dark, primordial god that corrupted the elements in the beginning of the world, giving rise to each of the princes.

Cryonax seeks to turn the multiverse into ice. To this end, he strives to unleash eternal winter upon entire worlds. When he comes to a realm, he schemes to prevent the coming of summer, dim the light of a world's sun, and extend the glaciers of a world's polar regions through weather control magic.

Cryonax rules the Frostfell, also known as the Plane of Ice. It is a place of pure, bone-chilling cold. Cryonax resides in the Chiseled Estate; a massive fortress constructed of ice, rock, crystal, and glass that rises a mile above the surface of Frostfell's glaciers.

```statblock
"name": "Cryonax (MaBJoV)"
"size": "Huge"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "391"
"hit_dice": "27d12 + 216"
"modifier": !!int "3"
"stats":
  - !!int "26"
  - !!int "16"
  - !!int "26"
  - !!int "19"
  - !!int "19"
  - !!int "23"
"speed": "40 ft., climb 40 ft."
"saves":
  - "strength": !!int "15"
  - "dexterity": !!int "10"
  - "constitution": !!int "15"
  - "wisdom": !!int "11"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "cold, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Primordial"
"cr": "22"
"traits":
  - "desc": "At the start of each of Cryonax's turns, each creature within 10 feet\
      \ of him takes 21 (6d6) cold damage. A creature also takes 21 (6d6) cold\
      \ damage if they touch or hit Cryonax. Nonmagical weapons that hit Cryonax are\
      \ frozen immediately after dealing damage to Cryonax. If used again and they\
      \ hit any creature, the weapon shatters. The freezing effect disappears after\
      \ an hour."
    "name": "Cold Aura"
  - "desc": "Cryonax's Slam attacks are treated as magical for the purpose of bypassing\
      \ resistance and immunity to nonmagical weapons."
    "name": "Empowered Attacks"
  - "desc": "No ability checks are required when Cryonax walks or climbs across icy\
      \ surfaces and difficult snow or ice terrain does not cost him extra movement."
    "name": "Ice Walker"
  - "desc": "If Cryonax fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Cryonax has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Cryonax makes two Slam attacks with his tentacles or two Ice Spear attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target. *Hit:*\
      \ 27 (3d12 + 8) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 20). Cryonax can grapple up to two targets but any tentacle that\
      \ is grappling can't be used to make a Slam or Ice Spear attack."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 120 ft., one target. *Hit:*\
      \ 36 (6d10 + 3) cold damage."
    "name": "Ice Spear"
  - "desc": "Cryonax summons two [young white dragons](3-Mechanics/CLI/bestiary/dragon/young-white-dragon.md)\
      \ or a [frost giant](3-Mechanics/CLI/bestiary/giant/frost-giant.md) with two\
      \ [yetis](3-Mechanics/CLI/bestiary/monstrosity/yeti.md). The summoning costs\
      \ Cryonax 50 hit points. The summoned creatures have maximum hit points and\
      \ appear within 100 feet of Cryonax."
    "name": "Summon Frost Horde (1/Day)"
  - "desc": "Cryonax casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 21, +13 to\
      \ hit with spell attacks):\n\n**At will:** [ice storm](3-Mechanics/CLI/spells/ice-storm.md),\
      \ [sleet storm](3-Mechanics/CLI/spells/sleet-storm.md), [wall of ice](3-Mechanics/CLI/spells/wall-of-ice.md)\n\
      \n**2/day each:** [cone of cold](3-Mechanics/CLI/spells/cone-of-cold.md), [otiluke's\
      \ freezing sphere](3-Mechanics/CLI/spells/otilukes-freezing-sphere.md) (45 (13d6)\
      \ damage)"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Cryonax can expend a use to take one of the following actions. Cryonax regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Cryonax slams a [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ target against the ground, dealing 13 (3d8) bludgeoning damage to it."
    "name": "Smash"
  - "desc": "Cryonax's tentacle freezes a [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ target. If the target fails a DC 22 Constitution saving throw they are [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ and Cryonax releases them from its tentacle. They remain frozen indefinitely\
      \ but can attempt the Constitution saving throw at the end of each of their\
      \ turns. Success means they are no longer frozen."
    "name": "Tentacle Freeze"
  - "desc": "With a gesture Cryonax targets a frozen creature (see Tentacle Freeze)\
      \ that is within 30 feet of him. The target is encased instantly in a hard shell\
      \ of crushing ice. The target receives no saving throw and takes 22 (5d8)\
      \ cold damage immediately and at the start of each of their turns. The target\
      \ is considered [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) but is\
      \ partly protected by the shroud and resistant to all damage. The shroud disappears\
      \ if Cryonax removes it, Cryonax dies, the shroud takes 100 hit points of damage\
      \ or another character uses their action and succeeds on a DC 22 Strength check\
      \ to remove the trapped ally."
    "name": "Ice Shroud (Costs 3 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/cryonax-mabjov.webp"
```
^statblock