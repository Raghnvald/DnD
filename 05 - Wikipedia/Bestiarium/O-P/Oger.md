---
cssclasses: json5e-monster
tags:
  - Quelle/5e/Monster_Manual
  - Habitat/Arktis
  - Habitat/Berg
  - Habitat/Grasland
  - Habitat/Hügel
  - Habitat/Küste
  - Habitat/Sumpf
  - Habitat/Unterreich
  - Habitat/Wald
  - Habitat/Wüste
  - Größe/Groß
  - Typ/Riese
aliases:
  - Ogre
---
```statblock
statblock: true
name: Oger
image: [[Ogre.png]]
source: Grundregelwerk
size: Groß
type: Riese
alignment: chaotisch böse
ac: 11
hp: 59
hit_dice: 7d10 + 21
speed: 12 Meter.
stats: [19, 8, 16, 5, 7, 7]
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 8
languages: Gemeinsprache, Riesisch
cr: 2
environment: Arktis, Berge, Grasland, Hügel, Küste, Sümpfe, Unterreich, Wälder, Wüste
bestiary: true
actions:
  - name: Zweihandknüppel
    desc: "Nahkampfwaffenangriff: +6 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 13 (`2W8+4`) Wuchtschaden."
    attack_bonus: 6
    damage_dice: 2d8
    damage_bonus: 4
  - name: Wurfspeer
    desc: "Nah- oder Fernkampfwaffenangriff: +6 auf Treffer, Reichweite 1,5 m oder Reichweite 9/36 m, ein Ziel. Treffer: 11 (`2W6+4`) Stichschaden."
    attack_bonus: &
    damage_dice: 2d6
    damage_bonus: 4
```
