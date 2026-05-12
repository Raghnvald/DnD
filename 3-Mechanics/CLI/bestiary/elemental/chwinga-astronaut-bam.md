---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Chwinga Astronaut"
---
# [Chwinga Astronaut](3-Mechanics/CLI/bestiary/elemental/chwinga-astronaut-bam.md)
*Source: Boo's Astral Menagerie p. 17*  

Chwingas that live in Wildspace usually dwell on habitable moons and asteroids, though they occasionally stow away on spelljamming ships or ride around on space guppies. Using its Magical Gift ability, a chwinga astronaut can bestow one of the following charms in place of those described in the "chapter 7".

- [Charm of Air Bubbles](3-Mechanics/CLI/rewards/charm-of-air-bubbles-bam.md)  
- [Charm of Instant Tools](3-Mechanics/CLI/rewards/charm-of-instant-tools-bam.md)  

```statblock
"name": "Chwinga Astronaut (BAM)"
"size": "Tiny"
"type": "elemental"
"alignment": "typically  Neutral"
"ac": !!int "15"
"hp": !!int "7"
"hit_dice": "3d4"
"modifier": !!int "5"
"stats":
  - !!int "1"
  - !!int "20"
  - !!int "10"
  - !!int "14"
  - !!int "16"
  - !!int "16"
"speed": "20 ft., climb 20 ft., swim 20 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+7"
"senses": "blindsight 60 ft., passive Perception 17"
"languages": ""
"cr": "0"
"traits":
  - "desc": "When the chwinga is subjected to an effect that allows it to make a Dexterity\
      \ saving throw to take only half damage, it instead takes no damage if it succeeds\
      \ on the saving throw, and only half damage if it fails, provided it isn't incapacitated."
    "name": "Evasion"
  - "desc": "The chwinga doesn't require air, food, or drink. When it dies, it turns\
      \ into a tiny pile of moondust, a cloud of glittering spores, a statuette resembling\
      \ its former self, a chunk of ice, or a sponge shaped like a dodecahedron (DM's\
      \ choice)."
    "name": "Unusual Nature"
"actions":
  - "desc": "The chwinga targets a Humanoid it can see within 5 feet of itself. The\
      \ target gains a supernatural charm of the DM's choice. See \"chapter 7\" for\
      \ more information on supernatural charms."
    "name": "Magical Gift (1/Day)"
  - "desc": "The chwinga takes shelter inside a rock, a bush, a tree, or a natural\
      \ source of fresh water in its space. The chwinga can't be targeted by any attack,\
      \ spell, or other effect while it is magically protected in this way, and the\
      \ shelter doesn't impair the chwinga's blindsight. The chwinga can use its action\
      \ to emerge from a shelter. If its shelter is destroyed, the chwinga is forced\
      \ out and appears in the shelter's space, but is otherwise unharmed."
    "name": "Natural Shelter"
  - "desc": "The chwinga casts one of the following spells, requiring no material\
      \ or verbal components and using Charisma as the spellcasting ability:\n\n**At\
      \ will:** druidcraft, guidance, pass without trace, resistance"
    "name": "Spellcasting"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/chwinga-astronaut-bam.webp"
```
^statblock