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
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Tier
aliases:
  - Swarm of Wasps
---
# Swarm of Wasps
*Source: SRD / Basic Rules*  

> [!statblock] Swarm of Wasps
> ![](compendium/bestiary/beast/token/swarm-of-wasps.png#token)
> *Medium beast, Unaligned*
> 
> - **Armor Class** 12  (natural armor)
> - **Hit Points** 22 (`5d8`)
> - **Speed** 5 ft., fly 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 3 (-4)|13 (+1)|10 (+0)| 1 (-5)| 7 (-2)| 1 (-5)|
> 
> - **Proficiency Bonus** +2
> - **Saving Throws** ⏤
> - **Skills** ⏤
> - **Senses** blindsight 10 ft., passive Perception 8
> - **Damage Resistances** bludgeoning, piercing, slashing
> - **Condition Immunities** charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned
> - **Languages** —
> - **Challenge** 1/2
> 
> ## Traits
> 
> ***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny insect. The swarm can't regain hit points or gain temporary hit points.
> 
> ## Actions
> 
> ***Bites.*** *Melee Weapon Attack:* +3 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 10 (`4d4`) piercing damage, or 5 (`2d4`) piercing damage if the swarm has half of its hit points or fewer.

^statblock

## Environment

underdark, grassland, forest, swamp, hill, urban, desert

```statblock
statblock: true
name: Schwarm von Wespen
image: [[swarm-of-wasps.png]]
source: SRD / Grundregeln
size: Mittel
type: Bestie
subtype: —
alignment: Ungeordnet
ac: 12 (natürliche Rüstung)
hp: 22
hit_dice: 5d8
speed: 1,5 Meter, Flug 9 Meter
stats: [3, 13, 10, 1, 7, 1]   # ST, GE, KO, IN, VU, CH
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Hieb, Stich, Hiebschaden"
damage_immunities: ""
condition_immunities: "Bezaubert, Verängstigt, Geknebelt, Gelähmt, Versteinert, Liegend, Gefesselt, Benommen"
senses: "Blindenblick 3 Meter, passive Wahrnehmung 8"
languages: "—"
cr: 1/2
environment: Unterwelt, Grasland, Wald, Sumpf, Hügel, Stadt, Wüste
bestiary: true
traits:
  - name: Schwarm
    desc: Der Schwarm kann den Raum einer anderen Kreatur teilen und umgekehrt. Er kann durch jede Öffnung kriechen, die groß genug für ein winziges Insekt ist. Der Schwarm kann keine Trefferpunkte zurückgewinnen oder temporäre Trefferpunkte erhalten.
actions:
  - name: Stiche
    desc: "Nahkampfangriff: +3 zum Treffen, Reichweite 0 m, ein Ziel im Raum des Schwarms. Treffer: 10 (4d4) Stichschaden, oder 5 (2d4) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger hat."
    attack_bonus: 3
    damage_dice: "4d4"
    damage_bonus: 0
    alternate_damage:
      condition: "bei ≤ ½ TP"
      damage_dice: "2d4"
      damage_bonus: 0
reactions: []
```