---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/genie
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Biha Babir"
---
# [Biha Babir](3-Mechanics/CLI/bestiary/npc/biha-babir-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 253*  

## Biha Babir

*Scheming Marid Ruler*

The calculating Biha Babir rules the pelagic city of Maran Saya in Calimshan. Though her physical form is as fluid as the ocean itself, she typically presents as a marid crowned in coral, with her lower half lengthening into a sinewy, eel-like tail.

## History

Before becoming ruler of Maran Saya, Biha Babir worked as a spy. She has traveled across Calimshan, infiltrating rival genie courts and eliminating remnants of the Twisted Rune. Some accounts even tell of her fighting alongside Sultana Songal during the Night of Fleeing Shadows.

Biha Babir took up leadership of Maran Saya after the previous ruler, her father, retired. People

know her as a shrewd ruler, preferring battles of wit over clashes of swords. Of the genie leaders in Calimshan, Biha Babir maintains the strongest spy network, and she is rumored to have informants in every major city of the region.

For years, Biha Babir has searched tirelessly for the Calimemnon Crystal (see chapter 8), the legendary prison of the powerful genies Calim and Memnon. She believes obtaining that crystal would allow her to wipe Calimshan off the map and seize control of whatever genie empire rises from the wreckage.

## Personality

Biha Babir's demeanor is like the ocean: seemingly placid on the surface, but dangerous and fierce deep below. Her amiable attitude hides a cunning mind. Biha Babir is politically savvy and prefers to outsmart her opponents rather than battle them, though she doesn't shy from combat if necessary.

Biha Babir covets opulence, but she also values information and learning just as much as material wealth. Offering valuable information is a surefire way to gain an audience with the her, but those caught lying to her are severely punished.

```statblock
"name": "Biha Babir (FRAiF)"
"size": "Large"
"type": "elemental"
"subtype": "genie"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "229"
"hit_dice": "17d10 + 136"
"modifier": !!int "9"
"stats":
  - !!int "22"
  - !!int "12"
  - !!int "26"
  - !!int "18"
  - !!int "17"
  - !!int "20"
"speed": "30 ft., fly 60 ft., swim 90 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Deception"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+5"
"damage_resistances": "acid, cold, lightning"
"senses": "Blindsight 30 ft., Darkvision 120 ft., passive Perception 17"
"languages": "Common, Primordial (Aquan)"
"cr": "12"
"traits":
  - "desc": "Biha Babir can breathe air and water."
    "name": "Amphibious"
  - "desc": "If Biha Babir dies outside the Elemental Plane of Water, her body dissolves\
      \ into brine, and she gains a new body in 1d4 days, reviving with all her\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> somewhere on the\
      \ Plane of Water."
    "name": "Elemental Restoration"
  - "desc": "If Biha Babir fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Biha Babir knows the Wish spell but can cast it only on behalf of a non-genie\
      \ creature who communicates a wish in a way Biha Babir can understand. If Biha\
      \ Babir casts the spell for a creature, she suffers none of the spell's stress.\
      \ Once Biha Babir has cast it three times, she can't do so again for 365 days."
    "name": "Wishes"
"actions":
  - "desc": "Biha Babir makes two Marine Burst attacks. She can replace one of these\
      \ attacks with a Tail attack."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +10, reach 5 ft. or range 60 ft. *Hit:*\
      \ 17 (2d10 + 6) Cold damage."
    "name": "Marine Burst"
  - "desc": "*Melee Attack Roll:* +10, reach 15 ft. *Hit:* 13 (2d6 + 6) Bludgeoning\
      \ damage, and if the target is Huge or smaller, it has the Prone condition."
    "name": "Tail (Marid Form Only)"
  - "desc": "Biha Babir casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 17):\n\n**At\
      \ will:** Create or Destroy Water, Detect Magic, Major Image\n\n**2/day each:**\
      \ Control Water (Flood, Part Water, or Redirect Flow only), Dispel Magic, Invisibility\n\
      \n**1/day each:** Control Weather, Plane Shift"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Biha Babir shape-shifts into a form resembling a Beast or Humanoid that\
      \ is Medium or smaller, while retaining her game statistics (other than her\
      \ size), or returns to her true marid form."
    "name": "Fluid Form"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Biha can expend a use to take one of the following actions. Biha regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Biha Babir teleports to an unoccupied space she can see within 30 feet\
      \ of herself and makes one Marine Burst attack."
    "name": "Misty Burst"
  - "desc": "*Strength Saving Throw:* DC 18, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from Biha Babir. *Failure:*\
      \ 10 (3d6) Force damage, and the target is pulled 15 feet straight toward\
      \ Biha Babir. *Success:* Half damage only. *Failure or Success:* Biha Babir\
      \ can't use this action again until the start of her next turn."
    "name": "Whirlpool"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/npc/token/biha-babir-fraif.webp"
```
^statblock