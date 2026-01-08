---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/xmm
  - Monster/HG/2
  - Monster/Habitat/Jedes
  - Monster/Größe/Klein-oder-Mittelgroß
  - Monster/Typ/Humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Berserker
---
# [Berserker](3-Mechanics\CLI\bestiary\humanoid/berserker-xmm.md)
*Source: Monster Manual (2024) p. 37. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Berserkers might fight for personal glory or form motivated forces or howling hordes.

## Berserkers

*Raging Invaders and Impassioned Warriors*

- **Habitat.** Any  
- **Treasure.** [Armaments](/3-Mechanics/CLI/tables/random-magic-items-armaments.md), Individual  

Gripped by the adrenaline of battle, berserkers are reckless invaders, pit fighters, and other ferocious warriors.

```statblock
"name": "Berserker (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "17"
  - !!int "9"
  - !!int "11"
  - !!int "9"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "While [Bloodied](/3-Mechanics/CLI/conditions.md#Bloodied), the berserker\
      \ has [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md) on attack\
      \ rolls and saving throws."
    "name": "Bloodied Frenzy"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 9 (1d12 + 3) Slashing damage."
    "name": "Greataxe"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/berserker-xmm.webp"
```
^statblock

## Environment

any

Berserker können für persönlichen Ruhm kämpfen oder motivierte Truppen oder brüllende Horden bilden.

```statblock
name: Berserker (2024)
source: Monsterhandbuch 2024
size: Mittelgroß oder Klein
type: Humanoid
alignment: Neutral
ac: 13
hp: 67
hit_dice: 9d8 + 27
ini: +1 (11)
speed: 9 Meter.
stats: [16, 12, 17, 9, 11, 9]
saves:
  - STR: +3
  - GES: +1
  - KON: +3
  - INT: -1
  - WEI: +0
  - CHA: -1
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [Fellrüstung](Fellrüstung.md), [Zweihandaxt](Zweihandaxt.md) 
senses: passive Wahrnehmung 10
languages: Gemeinsprache
cr: 2
bestiary: true
traits:
  - name: Blutrausch
    desc: "Während er den Zustand Blutet hat, ist der Berserker bei Angriffs- und Rettungswürfen im Vorteil."
actions:
  - name: Zweihandaxt
    desc: "_Nahkampfangriff_: +5, Reichweite 1,5m. _Treffer_: 9 (1d12 + 3) Hiebschaden."
    attack_bonus: 5
    damage_dice: 1d12
    damage_bonus: 3
```