---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Lich
Typ: Untoter
Größe: Mittelgroß
HG: 21
Habitat:
  - Planar (Untere Ebenen)
status: WIP
image: pictures/lich-2024.webp
tags: [Quelle/5e/mm]
aliases: [Lich]
---
# Lich (2014)

# Lich (2024)
_Unsterbliche Meister der Magie_

>**Habitat:** Planar (Untere Ebenen)
>**Beute:** Arkanes

![](lich-2024.webp)

Einige ruchlose Magieanwender führen verbotene nekromantische Rituale durch, bei denen sie ihre Seelen von ihren Körpern trennen und sich in Lichs verwandeln, Meister der Magie und des Untodes. Mit ihren Seelen, die in verborgenen Reliquien aufbewahrt werden, sind Lichs Marionetten ihrer eigenen Leichen, während sie ihre Ambitionen frei von sterblichen Bindungen verfolgen.

Lichs verfügen über außergewöhnliche Gerissenheit und magische Fähigkeiten, und sie nutzen ihre unnatürliche Unsterblichkeit, um arkane Geheimnisse zu ergründen, die nur wenige in einem einzigen Leben begreifen könnten. Unheimliche Absichten führen sie dazu, die Geheimnisse des Lebens, des Multiversums, der Gottheit und weniger ergründbare Themen auszuloten. Ohne Rücksicht auf das Leben oder die Wünsche der Sterblichen gehen Lichs bis zum Äußersten, um ihre Ziele zu erreichen.

Das Alter und die Herkunft eines Lichs beeinflussen seine Form. Ältere Lichs sehen aus wie brüchige Skelette in den verrotteten Gewändern vergessener Reiche, während jüngere Lichs eher lebenden Kreaturen ähneln und in moderne Gewänder gekleidet sind. Viele hüllen sich in Illusionen ihrer idealisierten sterblichen Gestalt.

Obwohl Lichs den Tod nicht fürchten, sind sie nicht frei vom Zahn der Zeit. Im Laufe der Zeit verlieren einige Lichs ihre Verbindung zur Zeit und zur physischen Welt und degenerieren zu Demilichs.

>[!quote] Rudolph van Richten, <br>Van Richten's Leitfaden für Lichs
>Ehrgeiz kann zu einer Sucht des Geistes und der Seele werden. Er entwickelt sich über eine treibende Flamme hinaus zu einem heimtückischen Inferno, das einen Magier aushöhlt, bis nur noch das Verlangen nach mehr magischer Macht übrig bleibt.

## Lich-Geist-Gefäße
Der Prozess, ein Lich zu werden, ist kompliziert, gefährlich und für jeden angehenden Lich einzigartig. Wenn der Ritus erfolgreich ist, wird die Seele des Lichs an einen Geistkrug gebunden, einen speziell angefertigten magischen Behälter. Dieses Relikt verankert den Geist des Lichs in der Welt und bewahrt ihn, sollte der Körper des Lichs zerstört werden. Ein Lich kann nur getötet werden, wenn sein Geistergefäß zerstört ist. Aus diesem Grund tut ein Lich alles, um seinen Geistertopf zu verstecken und zu schützen.

Geistergefäße sind in der Regel kleine, gut gefertigte Gegenstände, die für den Lich zu Lebzeiten von Bedeutung waren. Würfle auf oder wähle ein Ergebnis aus der Tabelle Lich-Geistesgefäß, um zu erfahren, wo ein Lich seine Seele versteckt.

#### Lich-Geist-Gefäße

| 1d8 | Das Geist-Gefäß des Lichs ist...                              |
| --- | ------------------------------------------------------------- |
| 1   | Eine Flasche oder Rätselbox, die mit Siegeln beschriftet ist. |
| 2   | Ein Vertrag, der zu einer Papierfigur gefaltet ist.           |
| 3   | Der erste magische Gegenstand, den der Lich erschaffen hat.   |
| 4   | Eine hohle Figur einer Gottheit oder eines Monsters.          |
| 5   | Eine Sanduhr, deren Sand in der Stase schwebt.                |
| 6   | Ein Medaillon oder Siegelring mit einem edlen Wappen.         |
| 7   | Ein runengeätztes Ei.                                         |
| 8   | Der Schädel des Mentors des Lichs.                            |

## Lich-Verstecke
Lichs erschaffen abgelegene Bibliotheken magischer Überlieferungen und arkane Laboratorien, die in außerplanetarischen Bastionen, Festungen mit verfluchtem Ruf oder anderen tödlichen Heiligtümern versteckt sind.

Die Region, in der sich die Höhle eines Lichs befindet, wird durch seine Anwesenheit verzerrt, was die folgenden Effekte hervorruft:

**Alles sehend.** Während er sich in seiner Höhle aufhält, kann der Lich Hellsichtigkeit wirken, wofür er keine Zauberkomponenten benötigt und dieselbe Zauberfähigkeit wie seine Aktion Zaubern verwendet.

**Unvermeidlicher Siphon.** Immer wenn ein Humanoid im Umkreis von 1 Meile um die Höhle stirbt, wird seine Seele sofort von dem Lich verzehrt. Ein Humanoid, dessen Seele auf diese Weise verzehrt wird, kann nur durch einen Zauber [Wahre Auferstehung](Wahre-Auferstehung.md) oder [Wunsch](Wunsch.md) wieder zum Leben erweckt werden.

Wird der Lich zerstört oder verlegt er sein Versteck an einen anderen Ort, enden diese Effekte sofort. Diese Effekte werden wieder aufgenommen, wenn der Lich einen neuen Körper erhält (siehe seine Eigenschaft Geisterkrug).

```statblock
name: Lich (2024)
image: pictures/lich-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß
type: Untoter
subtype: (Magier)
alignment: Neutral Böse
ac: 20
hp: 315
hit_dice: 42d8 + 126
ini: +17 (27)
speed: 9 Meter
stats: [11, 16, 16, 21, 14, 16]
saves:
  - STR: +0
  - GES: +10
  - KON: +10
  - INT: +12
  - WEI: +9
  - CHA: +3
skillsaves:
  - Arkane Kunde: 19
  - Geschichte: 12  
  - Motiv erkennen: 9
  - Wahrnehmung: 9
damage_vulnerabilities: ""
damage_resistances: "Blitz, Kälte"
damage_immunities: "Gift, Nekrotisch"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Erschöpfung|Erschöpfung]], [[Anhang PH-A#Gelähmt|Gelähmt]], [[Anhang PH-A#Verängstigt|Verängstigt]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
gear: [Materialkomponentenbeutel](Materialkomponentenbeutel.md)
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Wahrer Blick|Wahrer Blick]] 36 Meter, passive Wahrnehmung 19
languages: Alle
cr: 21
bestiary: true
traits:
  - name: Legendäre Resistenz (4/Tag, oder 5/Tag im Versteck).
    desc: "Wenn der Rettungswurf des Lichs scheitert, kann dieser den Wurf in einen Erfolg verwandeln."
  - name: Seelengefäß.
    desc: "Wenn der Lich zerstört wird, jedoch über ein Seelengefäß verfügt, erhält er in 1W10 Tagen einen neuen Körper mit allen Trefferpunkten und wird wieder aktiv. Der neue Körper erscheint an einem freien Ort im Versteck des Lichs."
actions:
  - name: Mehrfachangriff.
    desc: "Der Lich führt drei Angriffe aus, wobei er Schauriger Strahl und Paralyzing Touch in beliebiger Kombination ausführt."
  - name: Schauriger Strahl.
    desc: "_Nahkampf- oder Fernkampfangriffswurf:_ +12, Reichweite 1,5m oder 36m  _Treffer:_ 31 (4d12 + 5) Energieschaden."
    attack_bonus: 12
    damage_dice: 4d12
    damage_bonus: 5
  - name: Lähmende Berührung.
    desc: "_Nahkampfangriffswurf:_ +12, Reichweite 1,5m _Treffer:_ 31 (4d12 + 5) Energieschaden."
    attack_bonus: 12
    damage_dice: 4d12
    damage_bonus: 5
  - name: Zauberwirken.
    desc: "Der Lich wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 20):"
  - name: Beliebig oft
    desc: "[Blitz](Blitz.md) (Zaubergrad 5), [Feuerball](Feuerball.md) (Zaubergrad 5), [Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Magie bannen](Magie-bannen.md), [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md), [Unsichtbarkeit](Unsichtbarkeit.md)"
  - name: je 2-mal täglich.
    desc: "[Dimensionstür](Dimensionstür.md), [Ebenenwechsel](Ebenenwechsel.md) [Tote beleben](Tote-beleben.md)"
  - name: je 1-mal täglich.
    desc: "[Ausspähung](Ausspähung.md), [Finger des Todes](Finger-des-Todes.md) [Kugelblitz](Kugelblitz.md), [Wort der Macht: Tod](Wort-der-Macht-Tod.md)"
reactions:
  - name: Schützende Magie
    desc: "Der Lich wirkt [Gegenzauber](Gegenzauber.md) oder [Schild](Zauber/Schild.md) als Reaktion auf den Auslöser des Zaubers und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
legendary_description: "Der Lich kann drei legendäre Aktionen (4 in seinem Versteck) entsprechend den unten aufgeführten Optionen ausführen. Er kann jeweils nur eine legendäre Aktionsmöglichkeit und nur am Ende des Zugs einer anderen Kreatur ausführen. Der Lich erhält verbrauchte legendäre Aktionen am Anfang seines Zugs zurück."
legendary_actions:
  - name: Furchteinflößender Blick.
    desc: "Der Lich wirkt den Zauber [Furcht](Furcht.md), wobei er die gleiche Zauberfertigkeit wie beim Zauberwirken verwendet. Der Lich kann diese Aktion erst wieder zu Beginn seines nächsten Zuges ausführen."
  - name: Lebensunterbrechung.
    desc: "_Konstitutions-Rettungswurf_: SG 20, jede nicht-untote Kreatur in einem 6m Radius um den Lich herum. _Fehlschlag_: 31 (9d6) nekrotischer Schaden. _Erfolg_: Halber Schaden. _Fehlschlag oder Erfolg_: Der Lich kann diese Aktion bis zum Ende seiner nächsten Runde nicht erneut einsetzen."
  - name: Tödliche Teleportation.
    desc: "Der Lich teleportiert sich bis zu 18 Meter an einen unbesetzten Ort, den er sehen kann, und jede Kreatur im Umkreis von 3 Metern von dem Ort, den er verlassen hat, erleidet 11 (2d10) nekrotischen Schaden."
```