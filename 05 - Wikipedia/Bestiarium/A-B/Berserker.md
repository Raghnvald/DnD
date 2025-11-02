---
cssclasses: json5e-monster
tags:
  - DnD/Kompendium/Quelle/5e/MM 2024
  - Größe/Klein
  - Größe/Mittelgroß
  - Habitat/Arktis
  - Habitat/Berg
  - Habitat/Hügel
  - Habitat/Küste
  - Habitat/Wald
  - Habitat/Wüste
  - Typ/Humanoid
aliases:
  - Berserker
Typ: Humanoid
---
# Berserker (2024)
_Rasende Eroberer und leidenschaftliche Krieger_

>**Habitat:** Jedes
>**Beute:** Rüstungsgüter, Individuell

Gripped by the adrenaline of battle, berserkers are reckless invaders, pit fighters, and other ferocious warriors.

## Berserker-Befehlshaber

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

## Berserker

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