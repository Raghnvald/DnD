---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Bestie
Größe:
HG:
status:
image:
tags:
  - Quelle/5e/Monster_Manual
  - Monster/Habitat/Wald
  - Monster/Habitat/Hügel
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Tier
aliases:
  - Swarm of Ravens
---
# Swarm of Ravens
*Source: SRD / Basic Rules*  

> [!statblock] Swarm of Ravens
> ![](compendium/bestiary/beast/token/swarm-of-ravens.png#token)
> *Medium beast, Unaligned*
> 
> - **Armor Class** 12 
> - **Hit Points** 24 (`7d8 - 7`)
> - **Speed** 10 ft., fly 50 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 6 (-2)|14 (+2)| 8 (-1)| 3 (-4)|12 (+1)| 6 (-2)|
> 
> - **Proficiency Bonus** +2
> - **Saving Throws** ⏤
> - **Skills** Perception +5
> - **Senses** passive Perception 15
> - **Damage Resistances** bludgeoning, piercing, slashing
> - **Condition Immunities** charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned
> - **Languages** —
> - **Challenge** 1/4
> 
> ## Traits
> 
> ***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny raven. The swarm can't regain hit points or gain temporary hit points.
> 
> ## Actions
> 
> ***Beaks.*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target in the swarm's space. *Hit:* 7 (`2d6`) piercing damage, or 3 (`1d6`) piercing damage if the swarm has half of its hit points or fewer.

^statblock

## Environment

forest, swamp, hill, urban

```statblock
statblock: true
name: Schwarm von Raben
image: [[swarm-of-ravens.png]]
source: SRD / Grundregeln
size: Mittel
type: Bestie
subtype: —
alignment: Ungeordnet
ac: 12
hp: 24
hit_dice: 7d8-7
speed: 3 Meter, Flug 15 Meter
stats: [6, 14, 8, 3, 12, 6]   # ST, GE, KO, IN, VU, CH
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Hieb, Stich, Hiebschaden"
damage_immunities: ""
condition_immunities: "Bezaubert, Verängstigt, Geknebelt, Gelähmt, Versteinert, Liegend, Gefesselt, Benommen"
senses: "passive Wahrnehmung 15"
languages: "—"
cr: 1/4
environment: Wald, Sumpf, Hügel, Stadt
bestiary: true
traits:
  - name: Schwarm
    desc: Der Schwarm kann den Raum einer anderen Kreatur teilen und umgekehrt. Er kann durch jede Öffnung kriechen, die groß genug für eine winzige Krähe ist. Der Schwarm kann keine Trefferpunkte zurückgewinnen oder temporäre Trefferpunkte erhalten.
actions:
  - name: Schnäbel
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5 Meter, ein Ziel im Raum des Schwarms. Treffer: 7 (2d6) Stichschaden, oder 3 (1d6) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger hat."
    attack_bonus: 4
    damage_dice: "2d6"
    damage_bonus: 0
    alternate_damage:
      condition: "bei ≤ ½ TP"
      damage_dice: "1d6"
      damage_bonus: 0
reactions: []
```