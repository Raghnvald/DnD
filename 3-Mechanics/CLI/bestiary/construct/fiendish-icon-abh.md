---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/abh
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fiendish Icon"
---
# [Fiendish Icon](3-Mechanics/CLI/bestiary/construct/fiendish-icon-abh.md)
*Source: Astarion's Book of Hungers p. 14*  

*Effigy Animated by Hellish Magic*

Fiendish icons are grotesque, sapient statues depicting fearsome fiends. These creatures gain life as a result of sinister rituals. Fiendish icons can explode with hellfire to roast their foes, and they often pretend to be ordinary statues until they leap up to ambush invaders.

Roll on or choose a result from the Fiendish Icon Appearances table to inspire what a particular fiendish icon resembles.

| dice: 1d6 | The Fiendish Icon Depicts... |
|-----------|------------------------------|
| 1 | A muscular, fiendish figure holding a lit candelabra. |
| 2 | A rotund imp licking a serrated knife. |
| 3 | A squat, robed figure with a forked tail poking from beneath its garments. |
| 4 | A cherub with sharp fangs and a hand outstretched in welcome. |
| 5 | Six crows perched atop each other in a roughly humanoid shape. |
| 6 | A horned fiend that bears an uncanny resemblance to one of the characters. |
^1-the-fiendish-icon-depicts

> [!quote] A quote from Astarion on Fiendish Icons  
> 
> The only thing uglier than these wretched statues are my siblings and I when the servants forget to secure our blackout curtains.


```statblock
"name": "Fiendish Icon (ABH)"
"size": "Small"
"type": "construct"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "6"
  - !!int "11"
  - !!int "6"
"speed": "30 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+5"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, deafened, exhaustion, frightened, paralyzed, petrified,\
  \ poisoned"
"senses": "Darkvision 60, passive Perception 10"
"languages": "understands Common and Infernal but can't speak"
"cr": "1"
"traits":
  - "desc": "The icon has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The icon makes two Slam attacks and uses Fiery Eruption."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Bludgeoning\
      \ damage."
    "name": "Slam"
  - "desc": "*Dexterity Saving Throw:* DC 11, each creature in a 5-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the icon. *Failure:*\
      \ 7 (2d6) Fire damage."
    "name": "Fiery Eruption"
"source":
  - "ABH"
"image": "3-Mechanics/CLI/bestiary/construct/token/fiendish-icon-abh.webp"
```
^statblock

## Environment

urban