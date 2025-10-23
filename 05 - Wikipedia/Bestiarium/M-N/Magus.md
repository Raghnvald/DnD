---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- DnD/Kompendium/Quelle/5e/MM 2014
- DnD/Kompendium/Quelle/5e/MM 2024
- Habitat/Jedes
- Größe/Klein
- Größe/Mittelgroß
- Typ/Humanoid
aliases:
- Mage
---
# Mage (2014)
*Source: SRD / Basic Rules*  

> [!statblock] Mage
> ![](compendium/bestiary/humanoid/token/mage.png#token)
> *Medium humanoid (any race), Any alignment*
> 
> - **Armor Class** 12  (15 with [mage armor](compendium/spells/mage-armor.md))
> - **Hit Points** 40 (`9W8`)
> - **Speed** 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 9 (-1)|14 (+2)|11 (+0)|17 (+3)|12 (+1)|11 (+0)|
> 
> - **Proficiency Bonus** +3
> - **Saving Throws** Intelligence +6, Wisdom +4
> - **Skills** Arcana +6, History +6
> - **Senses** passive Perception 11
> 
> - **Languages** any four languages
> - **Challenge** 6
> 
> ***Spellcasting.*** The mage is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). The mage has the following wizard spells prepared:
> 
> **Cantrips (at will)**: [fire bolt](compendium/spells/fire-bolt.md), [light](compendium/spells/light.md), [mage hand](compendium/spells/mage-hand.md), [prestidigitation](compendium/spells/prestidigitation.md)
> 
> **1st level (4 1st-level slots)**: [detect magic](compendium/spells/detect-magic.md), [mage armor](compendium/spells/mage-armor.md), [magic missile](compendium/spells/magic-missile.md), [shield](compendium/spells/shield.md)
> 
> **2nd level (3 2nd-level slots)**: [misty step](compendium/spells/misty-step.md), [suggestion](compendium/spells/suggestion.md)
> 
> **3rd level (3 3rd-level slots)**: [counterspell](compendium/spells/counterspell.md), [fireball](compendium/spells/fireball.md), [fly](compendium/spells/fly.md)
> 
> **4th level (3 4th-level slots)**: [greater invisibility](compendium/spells/greater-invisibility.md), [ice storm](compendium/spells/ice-storm.md)
> 
> **5th level (1 5th-level slots)**: [cone of cold](compendium/spells/cone-of-cold.md)
> 
> ## Actions
> 
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (`1W4 + 2`) piercing damage.

^statblock

## Environment

urban

# Mages (2024)
_Gelehrte der Magie und Zauberwirker_

>**Habitat:** Jedes
>**Beute:** Arkanes, Individuell

![](mages-2024.webp)

Magier sind magische Wundertäter, die von zaubernden Oberherren bis hin zu zurückgezogenen Hexen reichen. Sie studieren mystische Geheimnisse und haben Einblick in Monster, Legenden, Omen und andere Überlieferungen. Magier versammeln oft Verbündete oder heuern Assistenten an, die sie bei ihren Forschungen unterstützen oder magische Macht erlangen wollen.

Würfle auf oder wähle ein Ergebnis aus der Magier-Rollentabelle, um verschiedene Arten von Magiern zu inspirieren.

## Magier-Rollen
| 1d10 | Der Magier ist...                                              |
| ---- | -------------------------------------------------------------- |
| 1    | Ein Astronom, der Magie aus den Sternen zieht.                 |
| 2    | Ein Autor, der über das Okkulte schreibt.                      |
| 3    | Ein magischer Ingenieur, der Wunder erschafft.                 |
| 4    | Ein Orakel, das Omen deutet.                                   |
| 5    | Ein Wunderkind mit einem bemerkenswerten magischen Erbe.       |
| 6    | Ein Psion, dessen Kräfte sich als Zaubersprüche manifestieren. |
| 7    | Ein Gelehrter, der alte Überlieferungen erforscht.             |
| 8    | Ein Wahrsager, der Herrscher berät.                            |
| 9    | Ein Kriegsmagier, der Soldaten im Kampf unterstützt.           |
| 10   | Eine Hexe, die geheime Weisheiten weitergibt.                  |

## Magier-Lehrling
Magierlehrlinge sind Zauberwirker mit bescheidenen Fähigkeiten. Einige sind Schüler von erfahrenen Magiern, andere haben angeborene Kräfte.

```statblock
name: Magier-Lehrling (2024)
image: pictures/mages-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß oder Klein
type: Humanoid
subtype: Magier
alignment: Neutral
ac: 15
hp: 49
hit_dice: 9d8 +9
ini: +2 (12)
speed: 9 Meter.
stats: [8, 14, 12, 16, 13, 10]
saves:
  - STR: -1
  - GES: +2
  - KON: +1
  - INT: +5
  - WEI: +3
  - CHA: +0
skillsaves:
  - Arkane Kunde: 5
  - Wahrnehmung: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [Materialkomponentenbeutel](Materialkomponentenbeutel.md)
senses: passive Wahrnehmung 13
languages: Gemeinsprache plus eine andere Sprachen
cr: 2
bestiary: true
actions:
  - name: Arkanschlag
    desc: "_Nahkampf- oder Fernkampfangriff_: +5, Reichweite 1,5m oder 36m. _Treffer_: 14 (2d10 + 3) Energieschaden."
    attack_bonus: 6
    damage_dice: 3d8
    damage_bonus: 3
  - name: Zauberwirken
    desc: "Der Magier wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 13, +5 auf Treffer mit Zauberangriffen):"
  - name: Beliebig oft
    desc: "[Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md)"
  - name: je 1-mal täglich
    desc: "[Donnerwoge](Donnerwoge.md), [Eismesser](Eismesser.md), [Magierrüstung](Magierrüstung.md) (in RK inbegriffen), [Selbstverkleidung](Selbstverkleidung.md)"
```

## Magier
Magier sind begabte Zauberer, deren Leben von der Magie geprägt ist. Sie können ihre Kräfte einsetzen, um andere Kreaturen zu verteidigen oder zu beherrschen, oder sie können sich auf die Erforschung der Magie und die Entschlüsselung mystischer Geheimnisse konzentrieren.

```statblock
name: Magier (2024)
image: pictures/mages-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß oder Klein
type: Humanoid
subtype: Magier
alignment: Neutral
ac: 15
hp: 81
hit_dice: 18d8
ini: +2 (12)
speed: 9 Meter.
stats: [9, 14, 11, 17, 12, 11]
saves:
  - STR: -1
  - GES: +2
  - KON: +0
  - INT: +6
  - WEI: +4
  - CHA: +0
skillsaves:
  - Arkane Kunde: 6
  - Geschichte: 6
  - Wahrnehmung: 4
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [Zauberstab](Zauberstab.md)
senses: passive Wahrnehmung 14
languages: Gemeinsprache plus drei andere Sprachen
cr: 6
bestiary: true
actions:
  - name: Mehrfachangriff
    desc: "Der Magier führt drei Angriffe mit Arkanschlag aus."
  - name: Arkanschlag
    desc: "_Nahkampf- oder Fernkampfangriff_: +6, Reichweite 1,5m oder 36m. _Treffer_: 16 (3d8 + 3) Energieschaden."
    attack_bonus: 6
    damage_dice: 3d8
    damage_bonus: 3
  - name: Zauberwirken
    desc: "Der Magier wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 14):"
  - name: Beliebig oft
    desc: "[Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Licht](Licht.md), [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Magierrüstung](Magierrüstung.md) (in RK inbegriffen), [Selbstverkleidung](Selbstverkleidung.md), [Taschenspielerei](Taschenspielerei.md) [Unsichtbarkeit](Unsichtbarkeit.md)"
  - name: je 2-mal täglich
    desc: "[Blitz](Blitz.md) (Zaubergrad 7), [Fliegen](Zauber/Fliegen.md)"
  - name: je 1-mal täglich
    desc: "[Ausspähung](Ausspähung.md), [Gedankenleere](Gedankenleere.md) (vor Kampfbeginn gewirkt), [Kältekegel](Kältekegel.md) (Zaubergrad 9), [Teleportation](Teleportation.md)"
bonus_actions:
  - name: Nebelschritt (3/Tag)
    desc: "Der Magier wirkt [Nebelschritt](Nebelschritt.md) und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
reactions:
  - name: Schützende Magie (3/Tag)
    desc: "Der Magier wirkt [Gegenzauber](Gegenzauber.md) oder [Schild](Zauber/Schild.md) als Reaktion auf den Auslöser des Zaubers und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
```

## Erzmagier
Erzmagier verfügen über unglaubliche magische Kräfte. Während einige ihre Magie zum Schutz der Welt einsetzen, werden andere zu Tyrannen oder verfolgen verbotene Geheimnisse. Viele Erzmagier halten sich magische Diener und sammeln magische Gegenstände und okkulte Überlieferungen.

>[!quote]  Nathor, Thayanischer Flüchtling
>Haben Ihr die Runen des Chaos betrachtet, den Todesmond-Orb in Euren zitternden Händen gehalten, das Verschlingende Portal betreten und die Pfade der Verdammten beschritten oder während des Rituals der Zwillingsverbrennung zur linken Hand von Szass Tam gesessen? Nein? Dann sprecht mit mir nicht über Zauberer. Sprecht mit mir nicht über Thay.

```statblock
name: Erzmagier (2024)
image: pictures/mages-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß oder Klein
type: Humanoid
subtype: Magier
alignment: Neutral
ac: 17
hp: 170
hit_dice: 31d8 + 31
ini: +7 (17)
speed: 9 Meter.
stats: [10, 14, 12, 20, 15, 16]
saves:
  - STR: +0
  - GES: +2
  - KON: +1
  - INT: +9
  - WEI: +6
  - CHA: +3
skillsaves:
  - Arkane Kunde: 13
  - Geschichte: 9
  - Wahrnehmung: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Psychisch"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]] (mit [Gedankenleere](Gedankenleere.md))"
gear: [Zauberstab](Zauberstab.md)
senses: passive Wahrnehmung 16
languages: Gemeinsprache plus fünf andere Sprachen
cr: 12
bestiary: true
traits:
  - name: Magische Resistenz.
    desc: "Der Erzmagier ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
actions:
  - name: Mehrfachangriff
    desc: "Der Erzmagier führt vier Angriffe mit Arkanschlag aus."
  - name: Arkanschlag
    desc: "_Nahkampf- oder Fernkampfangriff_: +9, Reichweite 1,5m oder 45m. _Treffer_: 27 (4d10 + 5) Energieschaden."
    attack_bonus: 9
    damage_dice: 4d10
    damage_bonus: 5
  - name: Zauberwirken
    desc: "Der Erzmagier wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 17):"
  - name: Beliebig oft
    desc: "[Licht](Licht.md), [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Magierrüstung](Magierrüstung.md) (in RK inbegriffen), [Taschenspielerei](Taschenspielerei.md)"
  - name: je 2-mal täglich
    desc: "[Feuerball](Feuerball.md) (Zaubergrad 4), [Unsichtbarkeit](Unsichtbarkeit.md)"
  - name: je 1-mal täglich
    desc: "[Fliegen](Zauber/Fliegen.md), [Kältekegel](Kältekegel.md)"
bonus_actions:
  - name: Nebelschritt (3/Tag)
    desc: "Der Magier wirkt [Nebelschritt](Nebelschritt.md) und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
reactions:
  - name: Schützende Magie (3/Tag)
    desc: "Der Erzmagier wirkt [Gegenzauber](Gegenzauber.md) oder [Schild](Zauber/Schild.md) als Reaktion auf den Auslöser des Zaubers und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
```