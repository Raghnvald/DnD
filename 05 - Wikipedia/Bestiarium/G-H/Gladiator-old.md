---
cssclasses: json5e-monster
tags:
  - DnD/Kompendium/Quelle/5e/MM 2014
  - DnD/Kompendium/Quelle/5e/MM 2024
  - Monster/Habitat/Jedes
  - Monster/Größe/Klein
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid
aliases:
  - Gladiator
Typ: Humanoid
---
# Gladiator (2024)
_Competitor and Prizefighter_

>**Habitat:** Jedes
>**Beute:** Rüstungsgüter, Individuell

Gladiatoren sind professionelle Kämpfer, die gegeneinander, gegen Monster und andere Herausforderungen antreten, um das Publikum zu unterhalten. Während einige nur um ihr Überleben kämpfen, lieben andere den Nervenkitzel der Vorstellung – und alle Gladiatoren wissen, wie wichtig Theatralik ist, um das Publikum bei Laune zu halten. Würfle oder wähle eine Option aus der Tabelle für Gladiatorentheatralik, um die einzigartigen Floskeln eines Gladiators während des Wettbewerbs zu inspirieren.

### Gladiator Theatralik
| 1d6 | Während eines Wettkampfes kann der Gladiator...                                                                           |
| --- | ------------------------------------------------------------------------------------------------------------------------- |
| 1   | Widmet seinen bevorstehenden Sieg einer Gottheit, einem Herrscher, einem geliebten Adligen oder einem Mitglied der Menge. |
| 2   | Verkleidet sich mit einer monstermäßigen Maske und einem Umhang.                                                          | 
| 3   | Beurteilt, ob sein Gegner ehrenhaft kämpft.                                                                               |
| 4   | Führt die Menge mit einem mitreißenden Titellied an.                                                                      |
| 5   | Versucht, eine Trophäe von einem Gegner zu erlangen.                                                                      |
| 6   | Nimmt Ratschläge aus der Menge, von Omen oder einem Haustier an.                                                          |

## Gladiator (2024)

```statblock
name: Gladiator (2024)
source: Monsterhandbuch 2024
size: Mittelgroß oder Klein
type: Humanoid
alignment: Neutral
ac: 16
hp: 112
hit_dice: 15d8 + 45
ini: +5 (15)
speed: 9 Meter.
stats: [18, 15, 16, 10, 12, 15]
saves:
  - STR: +7
  - GES: +5
  - KON: +6
  - INT: +0
  - WEI: +4
  - CHA: +2
skillsaves:
  - Athletik: 10
  - Auftreten: 5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [Beschlagene Lederrüstung](Beschlagene-Lederrüstung.md), [Schild](Gegenstände/Schild.md), [Speer](Speer.md) (3) 
senses: passive Wahrnehmung 11
languages: Gemeinsprache
cr: 5
bestiary: true
actions:
  - name: Mehrfachangriff
    desc: "Der Gladiator führt drei Angriffe mit dem Speer aus. Dabei kann er einen Angriff durch Schildhieb ersetzen."
  - name: Speer
    desc: "_Nahkampf- oder Fernkampfangriff_: +7, Reichweite 1,5m oder 6m / 18m. _Treffer_: 11 (2d6 + 4) Stichschaden."
    attack_bonus: 7
    damage_dice: 2d6
    damage_bonus: 4
  - name: Schildhieb
    desc: "_Stärke-Rettungswurf_: SG 15, Reichweite 1,5m. _Fehlschlag_: 9 (2d4 + 4) Wuchtschaden. If the target is a Medium or smaller creature, it has the Prone condition."
    damage_dice: 2d4
    damage_bonus: 4
reactions:
  - name: Parieren
    desc: "_Auslöser_: The gladiator is hit by a melee attack roll while holding a weapon. _Response:_ The gladiator adds 3 to its AC against that attack, possibly causing it to miss."
```