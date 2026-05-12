---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demodog"
---
# [Demodog](3-Mechanics/CLI/bestiary/fiend/demodog-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Demodogs are sinister, quadrupedal predators that spawn from limacine larvae. From a distance, they loosely resemble hairless dogs with tough, wrinkled hides and faceless, flower-like heads. When a demodog attacks, its head parts to reveal powerful jaws framed by toothed, fleshy petals.

Like wolves, demodogs typically hunt in packs, overwhelming their prey in gloomy places. Their howls strike fear into the most hardened adventurers.

```statblock
"name": "Demodog (WttHC)"
"size": "Small"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "6"
  - !!int "12"
  - !!int "6"
"speed": "50 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "cold, lightning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The demodog has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on an attack roll against a creature if at least one of the demodog's allies\
      \ is within 5 feet of the creature and the ally doesn't have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing\
      \ damage. If the target is a Medium or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Bite"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/demodog-wtthc.webp"
```
^statblock