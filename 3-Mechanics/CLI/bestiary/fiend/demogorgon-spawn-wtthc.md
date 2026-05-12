---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demogorgon Spawn"
---
# [Demogorgon Spawn](3-Mechanics/CLI/bestiary/fiend/demogorgon-spawn-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Monstrous offspring of the bestial demon lord Demogorgon, these spawn are lean, bipedal creatures with bulbous, featureless heads. A Demogorgon spawn's head opens like a flower in bloom, revealing a gaping maw and five or more fleshy petals lined with teeth.

Light flickers in the presence of these resilient predators, foretelling their arrival. Demogorgon spawns relentlessly pursue their prey.

```statblock
"name": "Demogorgon Spawn (WttHC)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "13"
  - !!int "8"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "cold, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 13"
"languages": ""
"cr": "2"
"traits":
  - "desc": "Sources of light in a 60-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the spawn flicker wildly. Nonmagical sources of [Bright Light](3-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md)\
      \ in that area instead shed [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md)."
    "name": "Baleful Presence"
  - "desc": "The spawn regains 5 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)."
    "name": "Regeneration"
  - "desc": "With a 10-foot running start, the spawn can [Long Jump](3-Mechanics/CLI/rules/variant-rules/long-jump-xphb.md)\
      \ up to 30 feet."
    "name": "Running Leap"
"actions":
  - "desc": "The spawn makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 10 ft. *Hit:* 6 (1d6 + 3) Slashing\
      \ damage."
    "name": "Claw"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing\
      \ damage. If the target is a Medium or smaller creature, it has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 13). While [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
      \ the target has the [Blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ condition."
    "name": "Bite"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/demogorgon-spawn-wtthc.webp"
```
^statblock