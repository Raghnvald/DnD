---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: 
Typ: Bestie
Größe: 
HG: 
status:
order:
parent:
image: 
tags:
- Quelle/5e/Monster_Manual
- Habitat/Hügel
- Habitat/Berg
- Habitat/Unterreich
- Habitat/Stadt
- Größe/Mittelgroß
- Typ/Bestie
aliases: ["Swarm of Bats"]
---
# Swarm of Bats
*Source: SRD / Basic Rules*  

> [!statblock] Swarm of Bats
> ![](compendium/bestiary/beast/token/swarm-of-bats.png#token)
> *Medium beast, Unaligned*
> 
> - **Armor Class** 12 
> - **Hit Points** 22 (`5d8`)
> - **Speed** 0 ft., fly 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 5 (-3)|15 (+2)|10 (+0)| 2 (-4)|12 (+1)| 4 (-3)|
> 
> - **Proficiency Bonus** +2
> - **Saving Throws** ⏤
> - **Skills** ⏤
> - **Senses** blindsight 60 ft., passive Perception 11
> - **Damage Resistances** bludgeoning, piercing, slashing
> - **Condition Immunities** charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned
> - **Languages** —
> - **Challenge** 1/4
> 
> ## Traits
> 
> ***Echolocation.*** The swarm can't use its blindsight while [deafened](rules/conditions.md#deafened).
> 
> ***Keen Hearing.*** The swarm has advantage on Wisdom ([Perception](rules/skills.md#Perception)) checks that rely on hearing.
> 
> ***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny bat. The swarm can't regain hit points or gain temporary hit points.
> 
> ## Actions
> 
> ***Bites.*** *Melee Weapon Attack:* +4 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 5 (`2d4`) piercing damage, or 2 (`1d4`) piercing damage if the swarm has half of its hit points or fewer.

^statblock

## Environment

underdark, mountain, hill, urban

```statblock
statblock: true
name: Schwarm von Fledermäusen
image: [[swarm-of-bats.png]]
source: SRD / Grundregeln
size: Mittel
type: Bestie
subtype: —
alignment: Ungeordnet
ac: 12
hp: 22
hit_dice: 5d8
speed: 0 Meter, Flug 9 Meter
stats: [5, 15, 10, 2, 12, 4]   # ST, GE, KO, IN, VU, CH
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Hieb, Stich, Hiebschaden"
damage_immunities: ""
condition_immunities: "Bezaubert, Verängstigt, Geknebelt, Gelähmt, Versteinert, Liegend, Gefesselt, Benommen"
senses: "Blindenblick 18 Meter, passive Wahrnehmung 11"
languages: "—"
cr: 1/4
environment: Unterwelt, Berge, Hügel, Stadt
bestiary: true
traits:
  - name: Echoortung
    desc: Der Schwarm kann seinen Blindenblick nicht nutzen, solange er betäubt ist.
  - name: Scharfes Gehör
    desc: Der Schwarm hat Vorteil bei Weisheits‑(Wahrnehmungs‑)Proben, die sich auf Hören beziehen.
  - name: Schwarm
    desc: Der Schwarm kann den Raum einer anderen Kreatur teilen und umgekehrt. Er kann durch jede Öffnung kriechen, die groß genug für eine winzige Fledermaus ist. Der Schwarm kann keine Trefferpunkte zurückgewinnen oder temporäre Trefferpunkte erhalten.
actions:
  - name: Bisse
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 0 m, ein Ziel im Raum des Schwarms. Treffer: 5 (2d4) Stichschaden, oder 2 (1d4) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger hat."
    attack_bonus: 4
    damage_dice: "2d4"
    damage_bonus: 0
    alternate_damage:
      condition: "bei ≤ ½ TP"
      damage_dice: "1d4"
      damage_bonus: 0
reactions: []
```