---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - monster/cr/25
  - monster/size/large
  - monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Bel
---
# [Bel](3-Mechanics\CLI\bestiary\npc/bel-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 115*  

From his bastion, Zariel's second-in-command and the former lord of Avernus oversees the forges that furnish weapons and armor for the Blood War. Though Asmodeus has instructed Zariel to accept Bel as her advisor, Bel and Zariel loathe each other and invent distractions to keep them apart.

Bel outwardly plays the role of Zariel's loyal vassal. However, Bel rankles at Zariel's rulership of the layer of the Nine Hells that was once his, but he won't challenge her directly as long as he thinks Asmodeus supports Zariel.

```statblock
"name": "Bel (BGDIA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "364"
"hit_dice": "27d10 + 216"
"modifier": !!int "2"
"stats":
  - !!int "28"
  - !!int "14"
  - !!int "26"
  - !!int "25"
  - !!int "19"
  - !!int "26"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "10"
  - "constitution": !!int "16"
  - "wisdom": !!int "12"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+16"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+16"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 14"
"languages": "Common, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "Bel's spellcasting ability is Charisma (spell save DC 23). Bel can innately\
      \ cast the following spells, requiring no material components:\n\n**At will:**\
      \ [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md)\n\
      \n**3/day each:** [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [hold monster](/3-Mechanics/CLI/spells/hold-monster-xphb.md), [mirror image](/3-Mechanics/CLI/spells/mirror-image-xphb.md),\
      \ [mislead](/3-Mechanics/CLI/spells/mislead-xphb.md), [raise dead](/3-Mechanics/CLI/spells/raise-dead-xphb.md),\
      \ [teleport](/3-Mechanics/CLI/spells/teleport-xphb.md), [wall of fire](/3-Mechanics/CLI/spells/wall-of-fire-xphb.md)\n\
      \n**1/day each:** [imprisonment](/3-Mechanics/CLI/spells/imprisonment-xphb.md),\
      \ [meteor swarm](/3-Mechanics/CLI/spells/meteor-swarm-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Any creature hostile to Bel that starts its turn within 20 feet of him\
      \ must make a DC 23 Wisdom saving throw, unless Bel is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\
      \ Unless the save succeeds, the creature is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ until the start of its next turn. If a creature's saving throw is successful,\
      \ the creature is immune to Bel's Fear Aura for the next 24 hours."
    "name": "Fear Aura"
  - "desc": "If Bel fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Bel has advantage on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Bel's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Bel makes three attacks: two with his greatsword and one with his tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +16 to hit, reach 10 ft., one target. *Hit:* 23\
      \ (4d6 + 9) slashing damage plus 21 (6d6) fire damage. If the target is a flammable\
      \ object that is not being held or worn, it catches fire."
    "name": "Greatsword"
  - "desc": "*Melee Weapon Attack:* +16 to hit, reach 10 ft., one target. *Hit:* 25\
      \ (3d10 + 9) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 23 Constitution saving throw or be [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ until the end of its next turn."
    "name": "Tail"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Bel can expend a use to take one of the following actions. Bel regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Bel casts [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md)."
    "name": "Fireball"
  - "desc": "Roll a d6 for Bel. The number rolled on the die is subtracted from the\
      \ next attack roll made against Bel or an ally of his choice within the next\
      \ minute."
    "name": "Tactical Edge (Costs 2 Actions)"
  - "desc": "Bel magically summons an ice devil with an ice spear (as described in\
      \ the ice devil's entry in the Monster Manual). The ice devil appears in an\
      \ unoccupied space within 60 feet of Bel, acts as Bel's ally, and can summon\
      \ other devils if it has such power. The ice devil remains until Bel dies or\
      \ until he dismisses it as an action."
    "name": "Summon Ice Devil (Costs 3 Actions)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/bel-bgdia.webp"
```
^statblock