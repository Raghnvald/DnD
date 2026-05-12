---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/efa
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tarkanan Marauder"
---
# [Tarkanan Marauder](3-Mechanics/CLI/bestiary/humanoid/tarkanan-marauder-efa.md)
*Source: Eberron: Forge of the Artificer p. 73*  

This powerful assassin relies on teleportation to catch targets unaware and deal out rapid death.

```statblock
"name": "Tarkanan Marauder (EFA)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "247"
"hit_dice": "26d8 + 130"
"modifier": !!int "7"
"stats":
  - !!int "15"
  - !!int "17"
  - !!int "20"
  - !!int "16"
  - !!int "15"
  - !!int "13"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Deception"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+7"
"gear":
  - "breastplate"
  - "shortsword"
"senses": "passive Perception 16"
"languages": "Common, Thieves' cant"
"cr": "11"
"traits":
  - "desc": "If the marauder is subjected to an effect that allows it to make a Dexterity\
      \ saving throw to take only half damage, the marauder instead takes no damage\
      \ if it succeeds on the save and only half as much damage if it fails. It can't\
      \ use this trait if it has the Incapacitated condition."
    "name": "Evasion"
"actions":
  - "desc": "The marauder makes three Aberrant Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 13 (3d6 + 3) Piercing\
      \ damage, plus 21 (6d6) Force damage if the marauder had <span title=\"Player's\
      \ Handbook (2024)\">Advantage</span> on the attack roll."
    "name": "Aberrant Strike"
  - "desc": "The marauder casts one of the following spells, requiring no Material\
      \ components and using Constitution as the spellcasting ability (spell save\
      \ DC 17):\n\n**At will:** Message\n\n**1/day:** Disintegrate"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The marauder teleports to a space it can see within 30 feet, appearing\
      \ in a dazzling flash. *Constitution Saving Throw:* DC 17, each creature in\
      \ a 5-foot <span title=\"Player's Handbook (2024)\">Emanation</span> originating\
      \ from the marauder when it appears. *Failure:* The target has the Blinded condition\
      \ until the end of the marauder's next turn."
    "name": "Tear Through Space"
"source":
  - "EFA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/tarkanan-marauder-efa.webp"
```
^statblock