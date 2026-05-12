---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Manshoon"
---
# [Manshoon](3-Mechanics/CLI/bestiary/npc/manshoon-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 265*  

## Manshoon

*Evil Wizard of Duplicity and Duplication*

Manshoon is an evil, arrogant wizard who was an instrumental founder of the Zhentarim centuries ago. That Manshoon is dead, and the current Manshoon is one of the original's many clones. Being a magical copy rather than an original doesn't make Manshoon any less of a threat, as he's amassed magical skill and political influence he uses for his own gain. Manshoon considers the Zhentarim to be only one tool to amass personal power, and he casually sacrifices minions once they've outlived their usefulness. Manshoon doesn't care who suffers so long he's able to crush his many enemies and force his subjects into paranoid and eager obedience.

## History

The original Manshoon was the undisputed lord of Zhentil Keep, where he honed the organization to suit his sinister will. He encouraged members to report on each other, punished discontent, and hoarded magical knowledge and personal secrets. The Zhentarim wouldn't have become the organization it is today—one where treachery and subterfuge are the order of the day—without Manshoon's formative influence.

Manshoon made many enemies and sought to preserve his power by crafting several clones. A magical accident decades ago caused all his clones to activate at once and fight against one another in a devastating conflict called the Manshoon Wars. The original Manshoon and all but three of his clones were killed, and today only a single Manshoon is believed to be active in Faerûn. Manshoon subtly cultivates this belief to keep his true forces hidden.

Manshoon seems to be a young man, but he is significantly older than he appears, and his mind harbors the skills and knowledge of an even older version of himself. One of Manshoon's enemies, Halaster Blackcloak, removed Manshoon's left arm at the elbow. Manshoon now uses a mechanical prosthetic arm.

## Personality

The Manshoon of today retains all his progenitor's arrogance and duplicity. Manshoon keeps several other clones at hand to activate if necessary. He also employs the Simulacrum spell to duplicate himself, his allies, and even his rivals. Manshoon knows that keeping people guessing about hidden identities makes them easier to manipulate.

Manshoon usually wears a mask and concealing robes when meeting with others, even with loyal lieutenants and the Zhentarim's inner circle. Even his allies aren't sure when they're meeting with the actual Manshoon, a clone, or someone else in disguise, which is just as Manshoon prefers.

Manshoon seeks power and is checked only by the many enemies who want to see him dead. He recently failed to seize control of Waterdeep in a clandestine coup. It's widely believed he's turned his attentions elsewhere, but another Manshoon clone lurks in that city, manipulating the Zhentarim behind the scenes to amass sufficient power to assault Undermountain and face his old enemy, Halaster.

```statblock
"name": "Manshoon (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Lawful Evil"
"ac": !!int "15"
"hp": !!int "214"
"hit_dice": "33d8 + 66"
"modifier": !!int "7"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "23"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "11"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+11"
  - "name": "History"
    "desc": "+11"
  - "name": "Insight"
    "desc": "+7"
"damage_immunities": "psychic"
"condition_immunities": "charmed"
"gear":
  - "component pouch"
"senses": "Darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic, Infernal, Undercommon"
"cr": "13"
"traits":
  - "desc": "Manshoon has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Manshoon makes three Arcane Burst attacks. He can replace two attacks\
      \ with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +11, reach 5 ft., or range 120 ft.\
      \ *Hit:* 32 (4d12 + 6) Force damage."
    "name": "Arcane Burst"
  - "desc": "Manshoon casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 19):\n\n**At will:** Detect Magic, Detect\
      \ Thoughts, Light, Lightning Bolt (level 4 version), Mage Armor (included in\
      \ AC), Mage Hand, Prestidigitation\n\n**2/day each:** Scrying, Sending, Wall\
      \ of Force\n\n**1/day each:** Befuddlement, Clone, Finger of Death, Mind Blank\
      \ (cast before combat), Simulacrum"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Manshoon casts Misty Step, using the same spellcasting ability as Spellcasting.\n"
    "name": "Misty Step"
"reactions":
  - "desc": "Manshoon casts Counterspell or Shield in response to the spell's trigger,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/npc/token/manshoon-fraif.webp"
```
^statblock