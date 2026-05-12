---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ogrémoch"
---
# [Ogrémoch](3-Mechanics/CLI/bestiary/npc/ogremoch-pota.md)
*Source: Princes of the Apocalypse p. 216*  

The Prince of Evil Earth is Ogrémoch (pronounced oh-gray-mock), the Mountain that Walks. His natural form is a shambling, 50-foot-tall colossus of rock, with crystal growths embedded throughout his body. When he bothers to speak, his voice sounds like grinding stones.

Ogrémoch is a miser who regards all the resources and treasures found in the ground as his own. He holds nothing but contempt for mortals (or any other denizens of the Material Plane) and desires nothing more than to crush and subjugate whomever he encounters. What he can't crush, he endures and outlasts.

Ogrémoch especially resents any mortals that dare to remove valuable metal or stone from the earth, and those who shape or build things of stone. He notices each nugget of gold or raw gemstone removed from areas under his influence, seeking to reclaim treasures "stolen" from him-and to punish the thieves. When the Prince of Evil Earth gains access to the Material Plane through an elemental node, he begins to methodically locate and destroy every mine, quarry, town, or fortification in the area. It's not that he needs the wealth, but the principle of the thing-extracting treasure from the earth-is anathema to Ogrémoch.

## Ogrémoch's Lair

Ogrémoch is normally found in the depths of elemental earth, choosing caverns with black crystals and jagged rock spikes to serve as his throne room. He can enter the Material Plane through large and well-established nodes of elemental earth, with a little help from the proper rituals. Within such a node, Ogrémoch wields great power.

```statblock
"name": "Ogrémoch (PotA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "526"
"hit_dice": "27d20 + 243"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "11"
  - !!int "28"
  - !!int "11"
  - !!int "15"
  - !!int "22"
"speed": "50 ft., burrow 50 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "15"
  - "wisdom": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., tremorsense\
  \ 120 ft., passive Perception 12"
"languages": "Common, Terran"
"cr": "20"
"traits":
  - "desc": "Ogrémoch's innate spellcasting ability is Charisma (spell save DC 20,\
      \ +12 to hit with spell attacks). He can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** [meld into stone](3-Mechanics/CLI/spells/meld-into-stone.md),\
      \ [move earth](3-Mechanics/CLI/spells/move-earth.md), [wall of stone](3-Mechanics/CLI/spells/wall-of-stone.md)"
    "name": "Innate Spellcasting"
  - "desc": "Ogrémoch's slam attacks are treated as magical and adamantine for the\
      \ purpose of bypassing resistance and immunity to nonmagical attacks."
    "name": "Empowered Attacks"
  - "desc": "If Ogrémoch fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Ogrémoch has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Ogrémoch deals double damage to objects and structures with his melee\
      \ and ranged weapon attacks."
    "name": "Siege Monster"
"actions":
  - "desc": "Ogrémoch makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:*\
      \ 30 (4d10 + 8) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 500 ft., one target. *Hit:*\
      \ 46 (7d10 + 8) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 23 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Boulder"
  - "desc": "Ogrémoch summons up to three [earth elementals](3-Mechanics/CLI/bestiary/elemental/earth-elemental.md)\
      \ and loses 30 hit points for each elemental he summons. Summoned elementals\
      \ have maximum hit points, appear within 100 feet of Ogrémoch, and disappear\
      \ if Ogrémoch is reduced to 0 hit points."
    "name": "Summon Elementals (1/Day)"
"lair_actions":
  - "desc": "Ogrémoch can assert his dominion over the rock and stone around him to\
      \ take lair actions on the Elemental Plane of Earth, or in any elemental earth\
      \ node (including the Black Geode, described in chapter 5). On initiative count\
      \ 20 (losing initiative ties), Ogrémoch uses his lair action to cause one of\
      \ the following effects:\n\n- A 10-foot-radius area of rocky or earthy ground\
      \ within 60 feet of Ogrémoch turns to sticky mud. Any creature on the ground\
      \ in the area must succeed on a DC 15 Dexterity saving throw or sink 5 feet\
      \ into the mud and be [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ A creature can take an action to make a DC 15 Strength check, ending the effect\
      \ on itself or another creature within its reach on a success.  \n- Crystalline\
      \ spikes grow from the ground in a 20-foot-radius area within 60 feet of Ogré\
      moch. The area becomes difficult terrain. A creature that moves through the\
      \ affected area takes 1d8 piercing damage for every 5 feet it moves there.\
      \ Creatures that are knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in the area also take this damage.  \n- A violent tremor shakes the lair in\
      \ a 120-foot-radius around Ogrémoch. Each creature other than Ogrémoch on the\
      \ ground in the area must succeed on a DC 15 Strength or Dexterity saving throw\
      \ (target's choice) or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \  "
    "name": ""
"regional_effects":
  - "desc": "The region containing an elemental node in which Ogrémoch is present\
      \ is seriously affected, becoming geologically unstable. This creates the following\
      \ effects:\n\n- Earth tremors strike the region within 10 miles of Ogrémoch's\
      \ location every 2d12 hours, each lasting 1d10 rounds. At first, damage\
      \ is minor—broken windows, cracked plaster, items toppled off shelves. The longer\
      \ Ogrémoch remains, the stronger the tremors become. After 5 days, the tremors\
      \ are strong enough to destroy flimsy structures. After 10 days, they are strong\
      \ enough to destroy ordinary wooden buildings. After 20 days, they can seriously\
      \ damage or destroy reinforced or fortified structures.  \n- Magnetic disturbances\
      \ within 10 miles of Ogrémoch prevent compasses from functioning there.  \n\
      - Hidden sinkholes and fissures form within 1 mile of Ogrémoch's location. A\
      \ hidden sinkhole can be spotted from a safe distance by any creature with a\
      \ passive Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ score of 15 or higher or spotted with a successful DC 15 Wisdom ([Survival](3-Mechanics/CLI/rules/skills.md#Survival))\
      \ check. Otherwise, the first creature to step on the thin crust covering the\
      \ sinkhole must succeed on a DC 15 Dexterity saving throw or fall 1d6 × 10\
      \ feet into the sinkhole or fissure.  \n- Natural caves and tunnels within 1\
      \ mile of Ogrémoch's lair form intermittent portals to the Elemental Plane of\
      \ Earth, allowing elemental creatures into the mortal world to dwell near those\
      \ points.  \n\nIf Ogrémoch is destroyed or banished back to his home plane,\
      \ the regional effects fade over the next 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Ogrémoch can expend a use to take one of the following actions. Ogrémoch\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Ogrémoch's crystalline protrusions flare. Each creature within 30 feet\
      \ of Ogrémoch becomes outlined in orange light, shedding dim light in a 10-foot\
      \ radius. Any attack roll against an affected creature has advantage if the\
      \ attacker can see it, and the affected creature can't benefit from being [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)."
    "name": "Illuminating Crystals"
  - "desc": "Ogrémoch stomps the ground, creating an earth tremor that extends in\
      \ a 30-foot radius. Other creatures standing on the ground in that radius must\
      \ succeed on a DC 23 Dexterity saving throw or fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Stomp (Costs 2 Actions)"
  - "desc": "Ogrémoch's hit points are reduced by 50 as he breaks off a chunk of his\
      \ body and places it on the ground in an unoccupied space within 15 feet of\
      \ him. The chunk of rock instantly transforms into a [gargoyle](3-Mechanics/CLI/bestiary/elemental/gargoyle.md)\
      \ and acts on the same initiative count as Ogrémoch. Ogrémoch can't use this\
      \ action if he has 50 hit points or fewer. The gargoyle obeys Ogrémoch's commands\
      \ and fights until destroyed."
    "name": "Create Gargoyle (Costs 3 Actions)"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/ogremoch-pota.webp"
```
^statblock