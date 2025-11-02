---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: 
Typ: Aberration (Gestaltwandler)
Größe: Mittelgroß
HG: 10
Habitat: Planar (LimbosWenn))
status: WIP
image: Death-Slaad-2024.webp
tags: [Quelle/5e/Monster_Manual]
aliases: [Death Slaad]
---
# Todesslaad
_Chaosgezüchtete Horden des Limbo_

>**Habitat:** Planar (Limbo)
>**Beute:** Alles

Unberechenbare Slaadi verschlingen und vermehren sich im ständig wechselnden Chaos von Limbo. Diese krötenähnlichen, außereuropäischen Wesen verkörpern die unendliche Potenzialität ihrer heimatlichen Ebene der Existenz. Obwohl die Slaadi nicht von Natur aus böse sind, sind ihre Triebe wild und oft zerstörerisch. Viele werden dazu getrieben, sich durch übernatürliche Prozesse fortzupflanzen. Leider sind diese Prozesse in der Regel tödlich für andere Kreaturen.

Slaadi haben keine formelle Gesellschaft. Vielmehr dominieren die starken Slaadi die schwächeren. Blaue und rote Slaadi wüten in Limbo und dringen auf Anweisung der grünen Slaadi in andere Welten vor. Mächtigere Slaadi haben Verbindungen zum Quellstein, einer Quelle chaotischer Magie, aus der die ersten Slaadi hervorgegangen sind. Der Quellstein ist tief in Limbo verborgen, und Legenden verbinden seinen Ursprung mit dem Modron-Oberherrn Primus oder den ruinösen Slaad-Lords wie Ssendam, dem goldenen amöboiden Schrecken, und Ygorl, dem geflügelten Skelett. Diese Slaad-Lords und andere planen, Slaadi über das Multiversum zu verbreiten.

>[!info] Slaad-Kontrolljuwelen
>Ein Slaad, der aus dem Laichstein geboren wird, hat einen magischen Kontrollstein in seinem Kopf. Wenn eine Kreatur den Edelstein für sich beansprucht, ist der Slaad verzaubert und gehorcht dem Träger des Edelsteins. Der Slaad hört auf, verzaubert zu sein, wenn er vom Träger des Edelsteins oder von dessen Verbündeten verletzt wird oder wenn der Edelstein an den Slaad zurückgegeben wird. Ein Großer Wiederherstellungszauber, der auf einen Slaad gewirkt wird, zerstört den Edelstein, und der Slaad ist nicht mehr verzaubert. Man kann den Kontrolledelstein eines Slaads mit einem Wunsch- oder Gefangenschaftszauber erhalten. Wenn der Slaad seinen Schutzwurf gegen die Gefangenschaft nicht besteht, erhält der Zaubernde den Edelstein, und der Slaad ist nicht gefangen. Der Kontroll-Edelstein eines entmündigten Slaads kann entfernt werden, indem er 1 Minute braucht und eine DC 20 Weisheit (Medizin) Probe besteht. Wird diese Prüfung nicht bestanden, erleidet der Slaad 22 (4d10) durchbohrenden Schaden.

>[!quote] Jebeel Sloom, Reiseführer zur Ebene des Limbos
>Wenn du gegen einen Slaad kämpfst und verlierst, ist die Geschichte zu Ende. Wenn du gegen einen Slaad kämpfst und gewinnst, stehen tausend andere Schlange, um zu beweisen, dass sie härter sind.

## Todesslaad
Slaad-Lords erschaffen Todesslaadi, indem sie graue Slaadi mit einem Teil ihrer chaotischen Energie infundieren. Wenn Gruppen von Slaadi vorsätzlich handeln, stecken oft Todesslaadi hinter ihren Plänen.

![](Death-Slaad-2024.webp)

```statblock
name: Todesslaad (2024)
image: pictures/death-slaad-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß
type: Aberration
alignment: Chaotisch Böse
ac: 18
hp: 178
hit_dice: 21d8 + 84
ini: +10 (20)
speed: 12 Meter
stats: [20, 15, 19, 15, 10, 19]
saves:
  - STR: +5
  - GES: +2
  - KON: +4
  - INT: +2
  - WEI: +0
  - CHA: +4
skillsaves:
  - Arkane Kunde: 6
  - Wahrnehmung: 8
damage_vulnerabilities: ""
damage_resistances: "Blitz, Feuer, Kälte, Säure, Schall"
damage_immunities: ""
condition_immunities: ""
gear: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Blindsicht|Blindsicht]] 18 Meter, [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 18
languages: Gemeinsprache, Slaad; telepatisch 18 Meter
cr: 10
bestiary: true
traits:
  - name: Magische Resistenz.
    desc: "Der Slaad ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Regeneration.
    desc: "Der Slaad erhält zu Beginn seines Zuges 20 TP zurück, wenn er zum Beginn seines Zuges mindestens 1 Trefferpunkt besitzt."
actions:
  - name: Mehrfachangriff.
    desc: "Der Slaad führt zwei Chaosklingen-Angriffe aus."
  - name: Chaosklinge.
    desc: "_Nahkampfangriffswurf:_ +9, Reichweite 3m. _Treffer:_ 11 (1d12 + 5) Hiebschaden plus 10 (3d6) nekrotischer Schaden. Bis zum Beginn des nächsten Zuges des Slaad leidet das Ziel unter einem der folgenden Zustände, die durch den Wurf eines d4 bestimmt werden: 1: [[Anhang PH-A#Bezaubert|Bezaubert]], 2: [[Anhang PH-A#Kampfunfähig|Kampfunfähig]], 3: [[Anhang PH-A#Verängstigt|Verängstigt]], 4: [[Anhang PH-A#Vergiftet|Vergiftet]]"
    attack_bonus: 9
    damage_dice: 1d12
    damage_bonus: 5
  - name: Zauberwirken.
    desc: "Der Slaad wirkt einen der folgenden Zauber, ohne Komponenten zu benötigen. Seine Zauberfertigkeit ist Charisma (Zauber-Rettungswurf SG 16):"
  - name: Beliebig oft
    desc: "[Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Mächtiges Trugbild](Mächtiges-Trugbild.md) [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Unsichtbarkeit](Unsichtbarkeit.md) (nur selbst)"
  - name: je 1-mal täglich.
    desc: "[Dürre](Dürre.md) (Zaubergrad 8), [Ebenenwechsel](Ebenenwechsel.md), [Fliegen](Zauber/Fliegen.md), [Todeswolke](Todeswolke.md) (Zaubergrad 6), [Zungen](Zungen.md)"
bonus_actions:
  - name: Gestaltwandeln.
    desc: "Der Slaad verwandelt sich in einen kleinen oder mittelgroßen Humanoiden oder er kehrt in seine wahre Gestalt zurück. Abgesehen von ihrer Größe sind ihre Spielstatistiken in jeder Form gleich. Jegliche Ausrüstung, die er trägt, wird nicht transformiert."
```