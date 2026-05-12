---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/abh
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vampire Infernalist"
---
# [Vampire Infernalist](3-Mechanics/CLI/bestiary/undead/vampire-infernalist-abh.md)
*Source: Astarion's Book of Hungers p. 18*  

*Vampire Arcanist of the Nine Hells*

While mortal wizards tend to hesitate before bartering their souls to devils for magical power, vampire wizards often believe their immortality will exempt them from any infernal claim to their souls. The archdevil Mephistopheles happily exploits such hubris and proves that even undead aren't immune to the laws of the Nine Hells.

The greatest hell-bound vampires are masters of hellfire called infernalists, who prey on mages. Vampire infernalists are usually too arrogant to work together; even a large city isn't likely to harbor more than one vampire infernalist. Vampire infernalists are dormant during the day, retreating to resting places hidden from the sun's searing rays before emerging at night to commit unsavory deeds.

> [!quote] A quote from Astarion on Vampire Infernalists  
> 
> What?! A vampire who's sold their soul to Mephistopheles for even more power? Wound not my unbeating heart. Tell me it's not true! Oh, wait. Of course it is.

## Vampire Infernalist Lairs

Vampire infernalists lurk in gloomy libraries or ritual chambers, far from the sun's light.

```statblock
"name": "Vampire Infernalist (ABH)"
"size": "Small or Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "172"
"hit_dice": "23d8 + 69"
"modifier": !!int "13"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "17"
  - !!int "20"
  - !!int "16"
  - !!int "18"
"speed": "40 ft., fly 40 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "10"
"skillsaves":
  - "name": "Arcana"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+8"
  - "name": "Religion"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+8"
"damage_resistances": "fire, necrotic, poison"
"condition_immunities": "poisoned"
"gear":
  - "orb"
"senses": "Darkvision 120 ft. (unimpeded by magical <span title=\"Player's Handbook\
  \ (2024)\">Darkness</span>), passive Perception 18"
"languages": "Common, Infernal"
"cr": "14"
"traits":
  - "desc": "If the vampire fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
  - "desc": "If the vampire drops to 0 <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> outside its resting place, the vampire uses Shape-Shift to become\
      \ mist (no action required). If it can't use Shape-Shift, it is destroyed.\n\
      \nWhile it has 0 <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ in mist form, it can't return to its vampire form, and it must reach its resting\
      \ place within 2 hours or be destroyed. Once in its resting place, it returns\
      \ to its vampire form and has the Paralyzed condition until it regains any <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span>, and it regains 1 <span\
      \ title=\"Player's Handbook (2024)\">Hit Point</span> after spending 1 hour\
      \ there."
    "name": "Misty Escape"
  - "desc": "The vampire has these weaknesses:\n\n- **Forbiddance.** The vampire can't\
      \ enter a residence without an invitation from an occupant.  \n- **Running Water.**\
      \ The vampire takes 20 Acid damage if it ends its turn in running water.  \n\
      - **Stake to the Heart.** If a weapon that deals Piercing damage is driven into\
      \ the vampire's heart while the vampire has the Incapacitated condition in its\
      \ resting place, the vampire has the Paralyzed condition until the weapon is\
      \ removed.  \n- **Sunlight.** The vampire takes 20 Radiant damage if it starts\
      \ its turn in sunlight. While in sunlight, it has <span title=\"Player's Handbook\
      \ (2024)\">Disadvantage</span> on attack rolls and ability checks.  "
    "name": "Vampire Weakness"
"actions":
  - "desc": "The vampire makes two Hellfire Claw attacks and uses Bite."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing\
      \ damage plus 10 (3d6) Fire damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 17) from one of two claws."
    "name": "Hellfire Claw (Vampire Form Only)"
  - "desc": "*Constitution Saving Throw:* DC 18, one creature within 5 feet that is\
      \ willing or that has the Grappled, Incapacitated, or Restrained condition.\
      \ *Failure:* 6 (1d4 + 4) Piercing damage plus 16 (3d10) Necrotic damage\
      \ and the creature loses its highest-level available spell slot (if any). The\
      \ target's <span title=\"Player's Handbook (2024)\">Hit Point</span> maximum\
      \ decreases by an amount equal to the Necrotic damage taken, and the vampire\
      \ regains <span title=\"Player's Handbook (2024)\">Hit Points</span> equal to\
      \ that amount. A Humanoid reduced to 0 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span> by this damage and then buried rises the following sunset\
      \ as a Vampire Spawn under the vampire's control."
    "name": "Bite (Imp or Vampire Form Only)"
  - "desc": "The vampire casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 18):\n\n**At will:** Detect Magic,\
      \ Detect Thoughts, Dispel Magic, Fireball (level 4 version), Mage Hand, Prestidigitation\n\
      \n**2/day:** Scrying\n\n**1/day:** Wall of Fire"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "If the vampire isn't in sunlight or running water, it shape-shifts into\
      \ a Tiny imp (<span title=\"Player's Handbook (2024)\">Speed</span> 20 ft.,\
      \ <span title=\"Player's Handbook (2024)\">Fly Speed</span> 40 ft.), or a Medium\
      \ cloud of mist (<span title=\"Player's Handbook (2024)\">Speed</span> 5 ft.,\
      \ <span title=\"Player's Handbook (2024)\">Fly Speed</span> 20 ft. [hover]),\
      \ or it returns to its vampire form. Anything it is wearing transforms with\
      \ it.\n\nWhile in imp form, the vampire's game statistics, other than its size\
      \ and <span title=\"Player's Handbook (2024)\">Speed</span>, are unchanged.\n\
      \nWhile in mist form, the vampire can't take any actions, speak, or manipulate\
      \ objects. It is weightless and can enter an enemy's space and stop there. If\
      \ air can pass through a space, the mist can do so, but it can't pass through\
      \ liquid. It has <span title=\"Player's Handbook (2024)\">Resistance</span>\
      \ to all damage, except the damage it takes from sunlight."
    "name": "Shape-Shift"
"regional_effects":
  - "desc": "The region containing an infernalist's lair is warped by its presence,\
      \ creating the following effects, all of which happen at the vampire's discretion:\n\
      \n- **Diabolic Beasts.** Animals in the vampire's domain serve the vampire's\
      \ will. From dusk until dawn, Medium or smaller Beasts have the Charmed condition\
      \ while within 1 mile of the lair.  \n- **Drained Essence.** Grasping shadows\
      \ within 1 mile of the lair sap the body and mind. Creatures (excluding the\
      \ vampire and its allies) that finish a Short or Long Rest while within 1 mile\
      \ of the lair make a DC 15 Wisdom saving throw. On a failed save, a creature\
      \ can't spend Hit Point Dice at the end of the rest and doesn't regain Hit Points,\
      \ Hit Point Dice, or spell slots at the end of the rest.  \n- **Tenacious Lore.**\
      \ Within 1 mile of the lair, flame doesn't burn written material.  \n\nIf the\
      \ infernalist dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, the vampire infernalist can expend a use to take one\
  \ of the following actions. The vampire infernalist regains all expended uses at\
  \ the start of each of its turns."
"legendary_actions":
  - "desc": "The vampire moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span>, and it makes one Hellfire Claw attack."
    "name": "Hellfire Strike"
  - "desc": "*Charisma Saving Throw:* DC 17, each creature in a 20-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the vampire. *Failure:*\
      \ 9 (2d8) Psychic damage, and the target has the Frightened condition until\
      \ the start of its next turn. *Success:* Half damage only. *Failure or Success:*\
      \ The vampire can't take this action again until the start of its next turn."
    "name": "Infernal Majesty"
  - "desc": "The vampire teleports up to 30 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "ABH"
"image": "3-Mechanics/CLI/bestiary/undead/token/vampire-infernalist-abh.webp"
```
^statblock

## Environment

planar, nine hells, underdark, urban