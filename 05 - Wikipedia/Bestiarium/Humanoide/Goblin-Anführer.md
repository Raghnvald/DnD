---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/MM
- Habitat/Wald
- Habitat/Grasland
- Habitat/Hügel
- Habitat/Unterreich
- Größe/Klein
- Typ/Humanoid/Goblinoid
aliases: ["Goblin Boss"]
---
```statblock
statblock: true
name: Goblin-Anführer
image: [[Goblin.png]]
source: Monsterhandbuch
size: Klein
type: humanoid
subtype: goblinoid
alignment: neutral böse
ac: 17
hp: 21
hit_dice: 6d6
speed: 9 Meter.
stats: [10, 14, 10, 10, 8, 10]
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 9
languages: Gemeinsprache, Goblin
cr: 1
environment: Wald, Grasland, Hügel, Unterreich
bestiary: true
traits:
  - name: Flinkes Entkommen
    desc: Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt zwei Angriffe mit dem Krummsäbel aus. Der zweite Angriff ist im Nachteil."
  - name: Krummsäbel
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 5 (1W6 + 2) Hiebschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Wurfspeer
    desc: "Nah- oder Fernkampfangriff: +4 zum Treffen, Reichweite 1,5m oder 30m/36m, ein Ziel. Treffer: 9 (2W6+2) Stichschaden im Nahkampf oder 5 (1W6 + 2) Stichschaden im Fernkampf."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
reactions:
  - name: Angriff umlenken
    desc: "Wenn der Goblin von einer Kreatur angegriffen wird, die er sehen kann, wählt der Goblin einen anderen Goblin im Umkreis von 1,5 Metern. Die beiden Goblins tauschen ihre Positionen und der gewählte Goblin wird stattdessen zum Ziel."
```