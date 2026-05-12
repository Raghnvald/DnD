---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Levistus"
---
# [Levistus](3-Mechanics/CLI/bestiary/npc/levistus-coa.md)
*Source: Chains of Asmodeus p. 229*  

No archdevil is more hated than the Frozen Prince, Levistus, despite his reputation as an honorable and chivalrous archdevil. Rivaling Asmodeus and Dis in their ability to plan and strategize, Levistus is generally considered one of the most plausible archdevils for overthrowing the throne. His ambition was somewhat stifled when he committed an unspeakable betrayal and was imprisoned by Asmodeus deep within the ice of Stygia.

Even while imprisoned, Levistus continues to plot, choosing to force his rage inward and reflect. Divination and communication magic helps aid this effort, and even from within his icy tomb Levistus manages legions. Levistus is known to make many deals with adventurers, provided they can aid his search for freedom.

When the Reckoning happened. Asmodeus, noticing that Levistus played no part in the war, chose to reinstate him as ruler of Stygia. While Levistus still desired revenge on his jailor, he recognized the opportunity and pledged temporary allegiance to Asmodeus. Publicly, Levistus completely supports Asmodeus and his plans, though from beneath the ice he continues to plot his revenge.

Other archdevils describe Levistus as clever, charming, and observant, if not also traitorous. He was often known to engage adversaries in single combat, only calling upon his magic and followers if someone or something intervened. For this reason, he is often worshipped by honorable thieves and charlatans—rogues with a code.

Levistus is described as an attractive humanoid male, with dark hair, an impeccable goatee, and pale-white skin.

## Levistus' Lair

The ruler of Stygia's lair is within his floating prison. This great glacier moves ponderously over the ages, carrying with it Levistus, and the effects of his lair.

```statblock
"name": "Levistus (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "23"
"ac_class": "natural armor"
"hp": !!int "336"
"hit_dice": "32d8 + 192"
"modifier": !!int "8"
"stats":
  - !!int "19"
  - !!int "26"
  - !!int "22"
  - !!int "25"
  - !!int "28"
  - !!int "26"
"speed": "0 ft."
"saves":
  - "dexterity": !!int "16"
  - "constitution": !!int "14"
  - "intelligence": !!int "15"
  - "wisdom": !!int "17"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+24"
  - "name": "Deception"
    "desc": "+16"
  - "name": "Intimidation"
    "desc": "+16"
  - "name": "Perception"
    "desc": "+25"
  - "name": "Persuasion"
    "desc": "+16"
  - "name": "Stealth"
    "desc": "+16"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 120 ft., passive Perception 35"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 1,000 ft."
"cr": "26"
"traits":
  - "desc": "Levistus is always entombed in ice. The ice provides 100 temporary hit\
      \ points. While Levistus has these temporary hit points, he has vulnerability\
      \ to fire damage. If Levistus starts his turn with no temporary hit points from\
      \ the ice, he regains 100 temporary hit points."
    "name": "Armor of Ice"
  - "desc": "Magical darkness doesn't impede Levistus's darkvision."
    "name": "Devil's Sight"
  - "desc": "If Levistus fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Levistus has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Cold damage dealt by Levistus ignores resistances and immunities."
    "name": "Sub-zero"
"actions":
  - "desc": "Levistus makes three Touch of Stygia or Ice Bolt attacks. He can replace\
      \ one of the attacks with Blizzard (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +15 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (3d8 + 7) psychic damage, and the target must succeed on a DC 23 Intelligence\
      \ saving throw or have the stunned condition for 1 minute. The target may repeat\
      \ the saving throw at the end of its turns, ending the effect on a success.\
      \ A creature that succeeds on the saving throw is immune to this effect for\
      \ 1 hour."
    "name": "Touch of Stygia"
  - "desc": "*Ranged Spell Attack:* +15 to hit, range 120 ft., one target. *Hit:*\
      \ 23 (3d10 + 7) cold damage."
    "name": "Ice Bolt"
  - "desc": "Levistus chooses a point he can see within 300 feet of him. Each creature\
      \ in a 20-foot-radius, 40-foot-high cylinder centered on that point must make\
      \ a DC 23 Dexterity saving throw. Targets take 13 (3d8) force damage plus\
      \ 13 (3d8) cold damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Blizzard (Recharge 4-6)"
  - "desc": "Levistus casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 23):\n\n\
      **At will:** Cone of Cold, Darkness, Ice Storm, Wall of Ice"
    "name": "Spellcasting"
"reactions":
  - "desc": "As a reaction to a creature he can see casting a spell, Levistus can\
      \ attempt to prevent the casting. Levistus makes an Intelligence check (+7)\
      \ against a DC of (10 + spell level). On a success, the creature's spell fails\
      \ and has no effect."
    "name": "Counterspell"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Levistus can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Icemaw.** One creature within 60 feet of Levistus, that he can see, must\
      \ make a DC 23 Dexterity saving throw. If a creature fails the saving throw,\
      \ they sink half of their height into the ice and have the grappled condition\
      \ (escape DC 21) and their movement becomes 0. If a creature already affected\
      \ by Icemaw is affected by it a second time, they sink completely into the ice\
      \ and begin suffocating.  \n\n- **Attack.** The archdevil uses one of their\
      \ available melee or ranged attacks against a single foe.  \n- **Cast a Spell.**\
      \ The archdevil uses their Spellcasting feature to cast an available spell.\
      \ If the spell normally requires concentration, it lasts for the full duration\
      \ instead.  \n- **Deceitful Whispers.** The archdevil whispers to a creature\
      \ they can see within 30 feet. The target must make a DC 22 Wisdom saving throw.\
      \ On a failed save, the target has the charmed condition until the start of\
      \ their next turn and must use their reaction immediately to make an attack\
      \ against one of the archdevil's enemies, chosen by the archdevil.  \n- **Fiendish\
      \ Fortitude.** The archdevil recharges one of their expended abilities.  \n\
      - **Frenzy.** The archdevil casts Haste on themself. The effect ends at initiative\
      \ count 20 of the next round.  \n- **Summon Underlings.** The archdevil summons\
      \ allied devils. The devils summoned depends on the archdevil using this feature.\
      \ The summoned devils appear in unoccupied spaces which the archdevil can see.\
      \ The [Summoned Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The icy regions containing Levistus' lair is corrupted by his presence,\
      \ which creates the following effect:\n\n- **Frozen Landscape.** Any creature\
      \ that has the prone or unconscious conditions within 1 mile of the lair, takes\
      \ 21 (6d6) cold damage at the start of their turn.  \n\nIf Levistus dies,\
      \ the effects fade over the course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Levistus can expend a use to take one of the following actions. Levistus\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Levistus selects a stunned creature that he can see. The creature must\
      \ succeed on a DC 23 Charisma saving throw or Levistus erases a specific memory\
      \ from the target. The memory must be one that the target experienced in the\
      \ last 24 hours and that lasted no more than 10 minutes. The memory can only\
      \ be restored with a Remove Curse or a Greater Restoration spell."
    "name": "Amnesia"
  - "desc": "Levistus makes an Ice Bolt attack. On a hit, the target falls and has\
      \ the prone condition."
    "name": "Froststrike"
  - "desc": "Levistus summons an allied ice devil in an unoccupied space that he can\
      \ see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/levistus-coa.webp"
```
^statblock