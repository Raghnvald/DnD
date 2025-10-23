---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: 
Typ: Untoter
Größe: 
HG: 
status:
order:
parent:
image: 
tags:
- Quelle/5e/Monster_Manual
- Habitat/Stadt
- Habitat/Sumpf
- Habitat/Unterreich
- Größe/Mittelgroß
- Typ/Untote
aliases:
- Ghast
---
# Grul (2014)
*Source: SRD / Basic Rules*  

> [!statblock] Ghast
> ![](compendium/bestiary/undead/token/ghast.png#token)
> *Medium undead, Chaotic Evil*
> 
> - **Armor Class** 13 
> - **Hit Points** 36 (`8d8`)
> - **Speed** 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |16 (+3)|17 (+3)|10 (+0)|11 (+0)|10 (+0)| 8 (-1)|
> 
> - **Proficiency Bonus** +2
> - **Saving Throws** ⏤
> - **Skills** ⏤
> - **Senses** darkvision 60 ft., passive Perception 10
> - **Damage Resistances** necrotic
> - **Damage Immunities** poison
> - **Condition Immunities** charmed, exhaustion, poisoned
> - **Languages** Common
> - **Challenge** 2
> 
> ## Traits
> 
> ***Stench.*** Any creature that starts its turn within 5 feet of the ghast must succeed on a DC 10 Constitution saving throw or be [poisoned](rules/conditions.md#poisoned) until the start of its next turn. On a successful saving throw, the creature is immune to the ghast's Stench for 24 hours.
> 
> ***Turn Defiance.*** The ghast and any ghouls within 30 feet of it have advantage on saving throws against effects that turn undead.
> 
> ## Actions
> 
> ***Bite.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 12 (`2d8 + 3`) piercing damage.
> 
> ***Claws.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10 (`2d6 + 3`) slashing damage. If the target is a creature other than an undead, it must succeed on a DC 10 Constitution saving throw or be [paralyzed](rules/conditions.md#paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^statblock

## Environment

underdark, swamp, urban

# Grul (2024)

>**Habitat:**  Stadt, Sumpf, Unterreich
>**Beute:** Jede

![](ghast-2024.webp#token)

Grule sind stinkende, unsterbliche Leichen, die eng mit Ghulen verwandt sind. Sie hungern nach den Lastern, die sie im Leben genossen haben, genauso wie nach verrottendem Fleisch.

## Grul

Grule organisieren sich häufig in Rudeln, um Gruften zu plündern und die darin befindlichen Reichtümer zu stehlen.

```statblock
name: Grul (2024)
source: Monsterhandbuch 2024
size: Mittel
type: Untot
alignment: Chaotisch Böse
ac: 13
hp: 36
hit_dice: 8d8
ini: +3 (13)
speed: 9 Meter.
stats: [16, 17, 10, 11, 10, 8]
saves:
  - STR: +3
  - GES: +3
  - KON: +0
  - INT: +0
  - WEI: +2
  - CHA: -1
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: "Nekrotisch"
damage_immunities: "Gift"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Erschöpfung|Erschöpfung]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache
cr: 2
bestiary: true
traits:
  - name: Gestank
    desc: "_Konstitutions-Rettungswurf:_ SG 10, jede Kreatur, die ihren Zug in einem 1,5m-Emanationsbereich beginnt, der von dem Grul ausgeht. Fehlschlag: Das Ziel leidet bis zum Beginn seines nächsten Zuges unter dem Zustand [[Anhang PH-A#Vergiftet|Vergiftet]]. Erfolg: Das Ziel ist 24 Stunden lang immun gegen den Gestank dieses Ghasts."
actions:
  - name: Biss
    desc: "_Nahkampfangriff:_ +5, Reichweite 1,5m. _Treffer:_ 7 (1d8 + 3) Stichschaden plus 9 (2d8) nekrotischer Schaden."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Klaue
    desc: "_Nahkampfangriff:_ +5, Reichweite 1,5m. _Treffer:_ 10 (2d6 + 3) Hiebschaden. Ist das Ziel eine nicht-untote Kreatur, wird sie dem folgenden Effekt unterworfen. _Konstitutions-Rettungswurf_: SG 10. _Fehlschlag_: Das Ziel ist bis zum Ende seines nächsten Zuges [[Anhang PH-A#Gelähmt|gelähmt]]."
    attack_bonus: 5
    damage_dice: 2d6
    damage_bonus: 3
```

## Grul-Grabrufer

Grul-Grabrufer üben teuflische Magie aus und unterhalten sich mit Leichen. Sie können sich als Liche oder Vampire ausgeben.

```statblock
name: Goblinscherge
source: Monsterhandbuch 2024
size: Kleine
type: Fee
subtype: (Goblinoid),
alignment: Chaotisch neutral
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
    desc: "_Nahkampf- oder Fernkampfangriff:_ +4, Reichweite 1,5m oder 6m/18m, ein Ziel. _Treffer:_ 4 (`1W4 + 2`) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
bonus_actions:
  - name: Flinkes Entkommen
    desc: Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen.
```