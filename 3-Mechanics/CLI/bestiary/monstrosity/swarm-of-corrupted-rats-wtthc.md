---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Corrupted Rats"
---
# [Swarm of Corrupted Rats](3-Mechanics/CLI/bestiary/monstrosity/swarm-of-corrupted-rats-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

```statblock
"name": "Swarm of Corrupted Rats (WttHC)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "10"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "4"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The rat explodes when it dies. *Constitution Saving Throw:* DC 10, each\
      \ creature in a 10-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the rat. *Failure:* 2d4 Acid Damage. *Success:* Half damage."
    "name": "Death Burst"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny rat. The swarm\
      \ can't regain [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Attack Roll:* +4, Reach 5 ft. *Hit:* 6 (2d4 + 2) Piercing\
      \ damage or 1d4 + 2 Piercing damage if the swarm is Bloodied."
    "name": "Bite"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/swarm-of-corrupted-rats-wtthc.webp"
```
^statblock