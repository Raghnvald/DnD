---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/xmm
  - Monster/HG/8
  - Monster/Habitat/Jedes
  - Monster/Größe/Klein-oder-Mittelgroß
  - Monster/Typ/Humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Berserker Commander
---
# [Berserker Commander](3-Mechanics\CLI\bestiary\humanoid/berserker-commander-xmm.md)
*Source: Monster Manual (2024) p. 37*  

Berserker commanders bear the scars of battle and drive their followers to match their deadly zeal. These commanders tap into a primal magic to enhance their might.

## Berserkers

*Raging Invaders and Impassioned Warriors*

- **Habitat.** Any  
- **Treasure.** [Armaments](/3-Mechanics/CLI/tables/random-magic-items-armaments.md), Individual  

Gripped by the adrenaline of battle, berserkers are reckless invaders, pit fighters, and other ferocious warriors.

```statblock
"name": "Berserker Commander (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "5"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "19"
  - !!int "10"
  - !!int "14"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "8"
"traits":
  - "desc": "While [Bloodied](/3-Mechanics/CLI/conditions.md#Bloodied), the berserker\
      \ has [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md) on attack\
      \ rolls and saving throws."
    "name": "Bloodied Frenzy"
"actions":
  - "desc": "The berserker makes three attacks, using Greataxe or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 10 (1d12 + 4) Slashing damage,\
      \ plus 10 (3d6) Thunder damage to the target or another creature within 5 feet\
      \ of the target."
    "name": "Greataxe"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 30/120 ft. *Hit:*\
      \ 18 (4d6 + 4) Piercing damage, and the target's [Speed](/3-Mechanics/CLI/variant-rules/speed-xphb.md)\
      \ decreases by 5 feet until the start of the berserker's next turn."
    "name": "Javelin"
"bonus_actions":
  - "desc": "Each ally within 30 feet of the berserker can take a [Reaction](/3-Mechanics/CLI/variant-rules/reaction-xphb.md)\
      \ to move up to half the ally's [Speed](/3-Mechanics/CLI/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attacks](/3-Mechanics/CLI/actions.md#Opportunity%20Attack).\
      \ The berserker can also move up to half its [Speed](/3-Mechanics/CLI/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attacks](/3-Mechanics/CLI/actions.md#Opportunity%20Attack)."
    "name": "Frenzied Rush"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/berserker-commander-xmm.webp"
```
^statblock

## Environment

any

Berserker-Befehlshaber tragen die Narben der Schlacht und treiben ihre Gefolgsleute dazu an, es ihnen gleichzutun mit ihrem tödlichen Eifer. Diese Befehlshaber zapfen eine ursprüngliche Magie an, um ihre Macht zu verstärken.

```statblock
name: Goblinscherge
size: Mittel oder Klein
type: Humanoid
alignment: Neutral
ac: 12
hp: 7
hit_dice: 2d6
ini: +2 (12)
speed: 9 Meter.
stats: [8, 15, 10, 10, 8, 8]
saves:
  - STR: -1
  - GES: +2
  - KON: +0
  - INT: +0
  - WEI: -1
  - CHA: -1
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [[Dolch]] (3)
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 9
languages: Gemeinsprache, Goblin
cr: 1/8
bestiary: true
actions:
  - name: Dolch
    desc: "_Nahkampf- oder Fernkampfangriff:_ +4, Reichweite 1,5m oder 6m/18m. _Treffer:_ 4 (`1W4 + 2`) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
```