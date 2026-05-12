---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spore of Moander"
---
# [Spore of Moander](3-Mechanics/CLI/bestiary/plant/spore-of-moander-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 280*  

## Spore of Moander

*Hulking Heap of the Rotting God*

A spore of Moander is a rotting mass of vegetation infused with the divine power of Moander, dead god of corruption and decay. Spores arise on the Material Plane where Moander's influence can still be felt: primordial swamps, ancient forests, and miasmic lagoons touched by Abyssal evil.

A spore of Moander has no grand agenda beyond spreading death and sorrow. Still, cultists of Moander look on these terrible creatures with reverence, believing that each spore is a window into the unknowable mind of Moander.

```statblock
"name": "Spore of Moander (FRAiF)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "3"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "20"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., climb 30 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "9"
"damage_resistances": "acid, cold, lightning"
"damage_immunities": "fire, poison"
"condition_immunities": "blinded, deafened, exhaustion, paralyzed, poisoned, prone"
"senses": "Blindsight 120 ft., passive Perception 10"
"languages": "understands Abyssal but can't speak"
"cr": "12"
"traits":
  - "desc": "When the spore is subjected to Fire damage, each creature in a 5-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ the spore takes 7 (2d6) Fire damage."
    "name": "Explosive Core"
  - "desc": "The spore doesn't need to expend extra movement to move through <span\
      \ title=\"Player's Handbook (2024)\">Difficult Terrain</span>."
    "name": "Rolling Mass"
"actions":
  - "desc": "The spore makes four Tendril attacks. Alternatively, it makes two Tendril\
      \ attacks and uses Consume once."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 20 ft. *Hit:* 11 (1d10 + 6) Piercing\
      \ damage plus 10 (3d6) Acid damage. If the target is Large or smaller, the\
      \ spore pulls the target 5 feet straight toward itself."
    "name": "Tendril"
  - "desc": "*Strength Saving Throw:* DC 18, one Large or smaller creature within\
      \ 5 feet. *Failure:* The target is pulled into the spore's space and has the\
      \ Grappled condition (escape DC 16). Until the grapple ends, the target has\
      \ the Blinded and Restrained conditions, and it takes 17 (5d6) Acid damage\
      \ at the start of each of the spore's turns. When the spore moves, the Grappled\
      \ target moves with it, costing it no extra movement. The spore can have one\
      \ Large creature or up to nine Medium or smaller creatures Grappled at a time."
    "name": "Consume"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/plant/token/spore-of-moander-fraif.webp"
```
^statblock

## Environment

forest, swamp