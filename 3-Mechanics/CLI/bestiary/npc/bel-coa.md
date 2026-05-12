---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bel"
---
# [Bel](3-Mechanics/CLI/bestiary/npc/bel-coa.md)
*Source: Chains of Asmodeus p. 234*  

From his bastion, Zariel's second-in-command and the former lord of Avernus oversees the forges that furnish weapons and armor for the Blood War. Though Asmodeus has instructed Zariel to accept Bel as her advisor, Bel and Zariel loathe each other and invent distractions to keep them apart.

Bel outwardly plays the role of Zariel's loyal vassal. However, Bel rankles at Zariel's rulership of the layer of the Nine Hells that was once his, but he won't challenge her directly as long as he thinks Asmodeus supports Zariel.

> [!note] Previous Adventures in Avernus: Bel
> 
> If you have run Baldur's Gate: Descent into Avernus, then Bel might have replaced Zariel as the ruler of Avernus. If so, his lair is the Bronze Citadel instead of the Forge.
^previous-adventures-in-avernus-bel

## Bel's Lair

Bel makes his lair in an ancient volcano known as the Forge.

```statblock
"name": "Bel (CoA)"
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
  - "name": "Arcana"
    "desc": "+15"
  - "name": "Deception"
    "desc": "+16"
  - "name": "Insight"
    "desc": "+12"
  - "name": "Persuasion"
    "desc": "+16"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"gear":
  - "greatsword"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Common, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "Any creature hostile to Bel that starts its turn within 20 feet of him\
      \ must make a DC 23 Wisdom saving throw unless Bel is incapacitated. If the\
      \ save fails, the creature has the frightened condition until the start of its\
      \ next turn. If a creature's saving throw is successful, the creature is immune\
      \ to Bel's Fear Aura for the next 24 hours."
    "name": "Fear Aura"
  - "desc": "If Bel fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Bel has advantage on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Bel attacks twice with his Greatsword and once with his Tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 23 (4d6 + 9) slashing damage plus 21 (6d6) fire damage. If the target\
      \ is a flammable object that isn't being held or worn, it catches fire."
    "name": "Greatsword"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 25 (3d10 + 9) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 23 Constitution saving throw or have the stunned condition until the\
      \ end of its next turn."
    "name": "Tail"
  - "desc": "Bel casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 24):\n\n**At\
      \ will:** Detect Magic, Fireball\n\n**2/day each:** Dispel Magic, Hold Monster,\
      \ Mirror Image, Mislead, Raise Dead, Teleport, Wall of Fire\n\n**1/day each:**\
      \ Imprisonment, Meteor Swarm"
    "name": "Spellcasting"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Bel can take one lair\
      \ action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Transmute.** If Bel has cast Wall of Fire, that wall becomes a permanent\
      \ Wall of Stone instead (doesn't require concentration).  \n\n- **Attack.**\
      \ The archdevil uses one of their available melee or ranged attacks against\
      \ a single foe.  \n- **Cast a Spell.** The archdevil uses their Spellcasting\
      \ feature to cast an available spell. If the spell normally requires concentration,\
      \ it lasts for the full duration instead.  \n- **Deceitful Whispers.** The archdevil\
      \ whispers to a creature they can see within 30 feet. The target must make a\
      \ DC 22 Wisdom saving throw. On a failed save, the target has the charmed condition\
      \ until the start of their next turn and must use their reaction immediately\
      \ to make an attack against one of the archdevil's enemies, chosen by the archdevil.\
      \  \n- **Fiendish Fortitude.** The archdevil recharges one of their expended\
      \ abilities.  \n- **Frenzy.** The archdevil casts Haste on themself. The effect\
      \ ends at initiative count 20 of the next round.  \n- **Summon Underlings.**\
      \ The archdevil summons allied devils. The devils summoned depends on the archdevil\
      \ using this feature. The summoned devils appear in unoccupied spaces which\
      \ the archdevil can see. The [Summoned Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Bel's lair is corrupted by his presence, which\
      \ creates the following effect:\n\n- **Lava.** There are numerous rivers of\
      \ lava within 3 miles of the lair. Anyone who enters the lava for the first\
      \ time or starts their turn in it takes 33 (6d10) fire damage.  \n\nIf Bel\
      \ dies, the effects fade over the course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Bel can expend a use to take one of the following actions. Bel regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Bel casts Fireball."
    "name": "Fireball"
  - "desc": "Roll a d6 for Bel. The number rolled on the die is subtracted from\
      \ the next attack roll made against Bel or an ally of his choice within the\
      \ next minute."
    "name": "Tactical Edge (Costs 2 Actions)"
  - "desc": "Bel magically summons an ice devil with an ice spear (as described in\
      \ the ice devil's entry in the Monster Manual). The ice devil appears in an\
      \ unoccupied space within 60 feet of Bel, acts as Bel's ally, and can summon\
      \ other devils if it has such power. The ice devil remains until Bel dies or\
      \ until he dismisses it with an action."
    "name": "Summon Ice Devil (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/bel-coa.webp"
```
^statblock