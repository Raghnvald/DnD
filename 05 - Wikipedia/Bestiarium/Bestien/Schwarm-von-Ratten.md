---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/Monster_Manual
- Habitat/Sumpf
- Habitat/Stadt
- Größe/Mittelgroß
- Typ/Bestie
aliases: ["Swarm of Rats"]
---
# Swarm of Rats
*Source: SRD / Basic Rules*  

> [!statblock] Swarm of Rats
> ![](compendium/bestiary/beast/token/swarm-of-rats.png#token)
> *Medium beast, Unaligned*
> 
> - **Armor Class** 10 
> - **Hit Points** 24 (`7d8 - 7`)
> - **Speed** 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 9 (-1)|11 (+0)| 9 (-1)| 2 (-4)|10 (+0)| 3 (-4)|
> 
> - **Proficiency Bonus** +2
> - **Saving Throws** ⏤
> - **Skills** ⏤
> - **Senses** darkvision 30 ft., passive Perception 10
> - **Damage Resistances** bludgeoning, piercing, slashing
> - **Condition Immunities** charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned
> - **Languages** —
> - **Challenge** 1/4
> 
> ## Traits
> 
> ***Keen Smell.*** The swarm has advantage on Wisdom ([Perception](rules/skills.md#Perception)) checks that rely on smell.
> 
> ***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny rat. The swarm can't regain hit points or gain temporary hit points.
> 
> ## Actions
> 
> ***Bites.*** *Melee Weapon Attack:* +2 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 7 (`2d6`) piercing damage, or 3 (`1d6`) piercing damage if the swarm has half of its hit points or fewer.

^statblock

## Environment

swamp, urban

```statblock
statblock: true
name: Schwarm von Ratten
image: [[swarm-of-rats.png]]
source: SRD / Grundregeln
size: Mittel
type: Bestie
subtype: —
alignment: Ungeordnet
ac: 10
hp: 24
hit_dice: 7d8-7
speed: 9 Meter
stats: [9, 11, 9, 2, 10, 3]   # ST, GE, KO, IN, VU, CH
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Hieb, Stich, Hiebschaden"
damage_immunities: ""
condition_immunities: "Bezaubert, Verängstigt, Geknebelt, Gelähmt, Versteinert, Liegend, Gefesselt, Benommen"
senses: "Dunkelsicht 9 Meter, passive Wahrnehmung 10"
languages: "—"
cr: 1/4
environment: Sumpf, Stadt
bestiary: true
traits:
  - name: Scharfer Geruch
    desc: Der Schwarm hat Vorteil bei Weisheits‑(Wahrnehmungs‑)Proben, die sich auf Geruch beziehen.
  - name: Schwarm
    desc: Der Schwarm kann den Raum einer anderen Kreatur teilen und umgekehrt. Er kann durch jede Öffnung kriechen, die groß genug für eine winzige Ratte ist. Der Schwarm kann keine Trefferpunkte zurückgewinnen oder temporäre Trefferpunkte erhalten.
actions:
  - name: Bisse
    desc: "Nahkampfangriff: +2 zum Treffen, Reichweite 0 m, ein Ziel im Raum des Schwarms. Treffer: 7 (2d6) Stichschaden, oder 3 (1d6) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger hat."
    attack_bonus: 2
    damage_dice: "2d6"
    damage_bonus: 0
    alternate_damage:
      condition: "bei ≤ ½ TP"
      damage_dice: "1d6"
      damage_bonus: 0
```