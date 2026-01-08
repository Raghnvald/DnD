---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/kraul
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kraul Death Priest
---
# [Kraul Death Priest](3-Mechanics\CLI\bestiary\humanoid/kraul-death-priest-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 214*  

The death priests occupy the highest roles in kraul society. They lead the buzzing chants of the kraul rites. Their inscrutable clicks and buzzing can summon crippling necromantic magic, and the presence of death seems to fortify them. They draw power from the defeat of their enemies and channel it to their followers, ensuring the continuation of the cycle.

The current leader of the kraul is a death priest named Mazirek.

## Kraul

The kraul are an ascendant power group within the Golgari Swarm, long content to linger at the margins of the undercity but now increasingly making their buzzing voices heard in the subterranean Golgari guildhall. These six-legged, insectile beings are hard-headed and literal-minded, with little grasp of metaphor or nuance.

```statblock
"name": "Kraul Death Priest (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "kraul"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "15"
  - !!int "10"
"speed": "30 ft., climb 30 ft., fly 40 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+3"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Kraul"
"cr": "4"
"traits":
  - "desc": "The kraul's innate spellcasting ability is Wisdom (spell save DC 12,\
      \ +4 to hit with spell attacks). The kraul can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** [chill touch](/3-Mechanics/CLI/spells/chill-touch-xphb.md),\
      \ [poison spray](/3-Mechanics/CLI/spells/poison-spray-xphb.md)\n\n**3/day each:**\
      \ [ray of enfeeblement](/3-Mechanics/CLI/spells/ray-of-enfeeblement-xphb.md),\
      \ [ray of sickness](/3-Mechanics/CLI/spells/ray-of-sickness-xphb.md)\n\n**1/day\
      \ each:** [animate dead](/3-Mechanics/CLI/spells/animate-dead-xphb.md), [blight](/3-Mechanics/CLI/spells/blight-xphb.md),\
      \ [vampiric touch](/3-Mechanics/CLI/spells/vampiric-touch-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "When a creature within 30 feet of the kraul drops to 0 hit points, the\
      \ kraul or another creature of its choice within 30 feet of it gains 5 (1d10)\
      \ temporary hit points, provided the kraul isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Feed on Death"
  - "desc": "The kraul is immune to the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ and [frightened](/3-Mechanics/CLI/conditions.md#Frightened) conditions while\
      \ within 30 feet of at least one other kraul."
    "name": "Hive Mind"
  - "desc": "The kraul has advantage on an attack roll against a creature if at least\
      \ one of the kraul's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "The kraul can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The kraul makes one attack with its quarterstaff and casts one of its\
      \ spells with a casting time of 1 action."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kraul-death-priest-ggr.webp"
```
^statblock