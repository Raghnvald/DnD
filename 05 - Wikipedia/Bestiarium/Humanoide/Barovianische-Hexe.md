---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/CoS
  - Habitat/Wald
  - Größe/Mittelgroß
  - Typ/Humanoid
aliases:
  - Barovian Witch
---
# Barovianische Hexe
Die wahnsinnigen Frauen und Männer, die als Barovianische Hexen bekannt sind, schmieden im Austausch für Magie und Langlebigkeit Pakte mit Strahd und den Dunklen Mächten von Ravenloft. Sie ziehen es vor, in den Schatten zu leben und können im Dunklen sehen. Wenn sie offen reisen, benutzen sie den Zauber Gestalt verändern, um eine weniger auffällige Gestalt anzunehmen. Sie benutzen diesen Zauber auch, um sich lange, scharfe Klauen wachsen zu lassen, mit denen sie tiefe Schnittwunden zufügen können.
$\quad$**Brüder und Schwestern von Strahd.** Barovianische Hexen haben keine Skrupel. Im Austausch für Macht handeln sie mit jedem. Sie werden aus dem gleichen Grund auch jeden verraten. Das Einzige, was sie fürchten, ist Strahd, und sein Wunsch ist ihnen Befehl. Barovianische Hexen sprechen von sich selbst manchmal als die Brüder und Schwestern von Strahd, aber nie, wenn er dabei ist.
$\quad$**Ratten und Katzen zusammenpacken.** Barovianische Hexen sind obsessive Sammler. Jede glaubt, dass fast alles, was man findet - ein Stück zerbrochener Knochen, ein totes Nagetier, eine Handvoll Staub oder irgendein anderes wertloses Objekt oder Material - als Zauberkomponente, Ritualobjekt oder Zaubertrankzutat nutzbar wäre.
$\quad$Barovianische Hexen benutzen den Zauber Vertrauten finden, um Vertraute herbeizurufen. Besonders beliebt sind Katzen, obwohl Schlangen und Kröten auch verbreitet sind. Diese Tiere lauern inmitten des Gerümpels in den Verstecken der Hexen und entfernen sich selten weit von ihren scheußlichen Meistern.

```statblock
name: Barovianische Hexe
source: Fluch des Strahd
size: Mittelgroß
type: Humanoid
alignment: Chaotisch Böse
ac: 10
hp: 16
hit_dice: 3d8 + 3
speed: 9 Meter.
stats: [7, 11, 13, 14, 11, 12]
skillsaves:
  - Arkane Kunde: 4
  - Wahrnehmung: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]], passive Wahrnehmung 12
languages: Gemeinsprache
cr: 1/2
bestiary: true
actions:
  - name: Klauen (benötigt Gestalt verändern)
    desc: "_Nahkampf-Waffenangriff_: +3 zum Treffen, Reichweite 1,50 m, ein Ziel. _Treffer_: 4 (1d6 + 1) Hiebschaden. Dieser Angriff ist magisch."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1
  - name: Dolch
    desc: "_Nahkampf- oder Fernkampf-Waffenangriff_: +2 zum Treffen, Reichweite 1,50 m oder Reichweite 6/18 m, ein Ziel. _Treffer_: 2 (1d4) Stichschaden."
    attack_bonus: 2
    damage_dice: 1d4
    damage_bonus: 0
spells:
  - Die Hexe ist eine Zauberwirkerin der 3. Stufe. Ihr Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 12, +4 zum Treffen mit Zauberangriffen). Die Hexe hat die folgenden Magierzaubersprüche vorbereitet:
  - Zaubertricks (beliebig oft): [Kältestrahl](Kältestrahl.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md)
  - Zaubergrad 1 (4 Plätze): [Schlaf](Schlaf.md), [Strahl der Übelkeit](Strahl-der-Übelkeit.md), [Tashas Fürchterlicher Lachanfall](Tashas-Fürchterlicher-Lachanfall.md)
  - Zaubergrad 2 (2 Plätze): [Gestalt verändern](Gestalt-verändern.md), [Unsichtbarkeit](Unsichtbarkeit.md)
```