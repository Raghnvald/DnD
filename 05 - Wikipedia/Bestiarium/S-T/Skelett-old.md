---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Stadt
status: WIP
image:
tags: [Quelle/5e/Monster_Manual]
aliases: [Skeleton]
---
```statblock
statblock: true
name: Skelett
image: [[Skeleton.png]]
source: Grundregelwerk
size: Mittelgroß
type: Untoter
alignment: Rechtschaffen böse
ac: 13
hp: 13
hit_dice: 2d8 + 4
speed: 9 Meter.
stats: [10, 14, 15, 6, 8, 5]
damage_vulnerabilities: "Wucht"
damage_resistances: ""
damage_immunities: "Gift"
condition_immunities: "Erschöpft, Vergiftet"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 9
languages: Versteht alle zu Lebzeiten bekannten Sprachen, kann aber nicht sprechen
cr: 1/4
environment: Stadt
bestiary: true
actions:
  - name: Kurzschwert
    desc: "Nahkampfwaffenangriff: +4 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 5 (1W6+2) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Kurzbogen
    desc: "Fernkampfwaffenangriff: +4 auf Treffer, Reichweite 24/96 m, ein Ziel. Treffer: 5 (1W6+2) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```