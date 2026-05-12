---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/abh
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vampire Warden"
---
# [Vampire Warden](3-Mechanics/CLI/bestiary/undead/vampire-warden-abh.md)
*Source: Astarion's Book of Hungers p. 20*  

*Stone-Skinned, Blood-Drinking Guardian*

Vampires need trusted guards for their lairs, minions, and treasures. After all, vampire familiars don't live for long and are inattentive while sleeping or simpering. Monstrous servants are often too unpredictable or simply unreliable. To keep their lairs safe, some vampires create more durable spawn to serve as watchful guardians. These vampire wardens appear to have the same pallid flesh as most vampires but, through sheer force of will, can shrug off blows that might fell others. When most vampires would be destroyed, a warden turns to stone, heals itself, and is ready for service once again.

> [!quote] A quote from Astarion on Vampire Wardens  
> 
> Ah, these stony-skinned prats: the insufferable watchdogs of vampirekind. I once tried to play fetch with one of ours. It didn't go well.


```statblock
"name": "Vampire Warden (ABH)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "190"
"hit_dice": "21d8 + 96"
"modifier": !!int "6"
"stats":
  - !!int "21"
  - !!int "15"
  - !!int "18"
  - !!int "10"
  - !!int "14"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Athletics"
    "desc": "+9"
  - "name": "Perception"
    "desc": "+10"
"damage_resistances": "necrotic"
"condition_immunities": "exhaustion, frightened"
"senses": "Darkvision 120 ft., passive Perception 20"
"languages": "Common"
"cr": "10"
"traits":
  - "desc": "The vampire has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The vampire has these weaknesses:\n\n- **Forbiddance.** The vampire can't\
      \ enter a residence without an invitation from an occupant.  \n- **Running Water.**\
      \ The vampire takes 20 Acid damage if it ends its turn in running water.  \n\
      - **Stake to the Heart.** If a weapon that deals Piercing damage is driven into\
      \ the vampire's heart while the vampire has the Incapacitated condition, the\
      \ vampire has the Paralyzed condition until the weapon is removed.  \n- **Sunlight.**\
      \ The vampire takes 20 Radiant damage if it starts its turn in sunlight. While\
      \ in sunlight, it has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and ability checks.  \n- **Immobile Restoration.** If the\
      \ vampire drops to 0 <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ while it doesn't have the Petrified condition, it turns to stone, regains\
      \ 50 <span title=\"Player's Handbook (2024)\">Hit Points</span>, and has the\
      \ Petrified condition for 1 hour.  "
    "name": "Vampire Weakness"
"actions":
  - "desc": "The vampire makes two Claw attacks and uses Bite or Guardian's Command."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 14 (2d8 + 5) Slashing\
      \ damage plus 7 (2d6) Necrotic damage. If the target is a Large or smaller\
      \ creature, it has the Grappled condition (escape DC 16) from one of two claws."
    "name": "Claw"
  - "desc": "*Constitution Saving Throw:* DC 16, one creature within 5 feet that is\
      \ willing or that has the Grappled, Incapacitated, or Restrained condition.\
      \ *Failure:* 7 (1d4 + 5) Piercing damage plus 7 (2d6) Necrotic damage. The\
      \ target's <span title=\"Player's Handbook (2024)\">Hit Point</span> maximum\
      \ decreases by an amount equal to the Necrotic damage taken, and the vampire\
      \ regains <span title=\"Player's Handbook (2024)\">Hit Points</span> equal to\
      \ that amount."
    "name": "Bite"
  - "desc": "The vampire casts Compulsion, requiring no spell components and using\
      \ Charisma as the spellcasting ability (spell save DC 15).\n"
    "name": "Guardian's Command"
"reactions":
  - "desc": "Trigger: The vampire is hit by a melee attack roll from an attacker the\
      \ vampire can see. _Response:_ The vampire reduces the damage it takes from\
      \ the attack by 11 (2d6 + 4)."
    "name": "Resilient Flesh"
"source":
  - "ABH"
"image": "3-Mechanics/CLI/bestiary/undead/token/vampire-warden-abh.webp"
```
^statblock

## Environment

underdark, urban