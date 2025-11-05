---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Winzig
HG: 4
Habitat:
  - Unterreich
status: WIP
image:
tags: [Quelle/5e/Monster_Manual]
aliases: [Flameskull]
---
# Flammenschädel (2014)

![](flameskull-2014.webp)

## Beschreibung
Flammende grüne Flammen und wahnsinniges, schallendes Gelächter umgeben einen untoten Flammenschädel. Dieser körperlose Schädel lässt seine Feinde mit feurigen Strahlen aus seinen Augen und furchtbaren Zaubersprüchen aus den dunklen Tiefen seines Gedächtnisses um sich schlagen.

Flammende grüne Flammen und wahnsinniges, hallendes Gelächter verfolgen einen körperlosen Schädel, wenn er in seinem Gebiet patrouilliert. Wenn der untote Flammenschädel Eindringlinge entdeckt, beschießt er sie mit feurigen Strahlen aus seinen Augen und furchtbaren Zaubern aus den dunklen Tiefen seines Gedächtnisses.

Dunkle Zauberwirker stellen Flammenschädel aus den Überresten toter Zauberer her. Wenn das Ritual abgeschlossen ist, brechen grüne Flammen aus dem Schädel hervor und vollenden seine grausige Verwandlung.

**_Vermächtnis des Lebens._** Ein Flammenschädel erinnert sich nur noch schemenhaft an sein früheres Leben. Auch wenn er mit seiner alten Stimme spricht und wichtige Ereignisse aus seiner Vergangenheit erzählt, ist er nur ein Echo seines früheren Selbst. Durch seine Verwandlung in einen Untoten hat er jedoch vollen Zugriff auf die Magie, die er zu Lebzeiten beherrschte, und kann Zauber wirken, während er die materiellen und körperlichen Komponenten ignoriert, die er nicht mehr einsetzen kann.

**_Ewig gefesselt._** Ein Flammenschädel ist intelligent und wachsam und dient seinem Schöpfer, indem er einen verborgenen Schatz, eine geheime Kammer oder eine bestimmte Person beschützt. Ein Flammenschädel führt die Anweisungen aus, die ihm bei seiner Erschaffung gegeben wurden, und er interpretiert diese Befehle buchstabengetreu. Der Meister eines Flammenschädels muss seine Anweisungen sorgfältig ausarbeiten, um sicherzustellen, dass die Kreatur ihre Aufgaben ordnungsgemäß ausführt.

**_In Flammen gehüllt._** Das Feuer, das einen Flammenschädel einhüllt, brennt ununterbrochen und gibt ein helles Licht ab, das die Kreatur kontrolliert. Sie setzt diese Flammen als Waffe ein und bündelt sie, um sie als feurige Strahlen aus ihren Augenhöhlen zu entlassen.

**_Eldritchische Verjüngung._** Die zersplitterten Fragmente eines Flammenschädels regenerieren sich, es sei denn, sie werden mit Weihwasser bespritzt oder mit einem Zauberspruch wie „[Magie bannen](Magie%20bannen.md)“ oder „[Fluch brechen](Fluch%20brechen.md)“ belegt. Wenn er seinen Zweck nicht mehr erfüllen kann, ist der neu geformte Flammenschädel niemandem mehr verpflichtet und wird selbstständig.

**_Untotes Wesen._** Ein Flammenschädel braucht weder Luft, noch Essen, Trinken oder Schlaf.

```statblock
name: Flammenschädel (2014)
image: pictures/flameskull-2014.webp
source: Monsterhandbuch 2024
size: Winzig
type: Untoter
alignment: Neutral Böse
ac: 13
hp: 40
hit_dice: 9d4 + 18
speed: 0 Meter, 40 Meter schwebend
stats: [1, 17, 14, 16, 10, 11]
skillsaves:
  - Arkane Kunde: 5
  - Wahrnehmung: 2
damage_vulnerabilities: ""
damage_resistances: "Blitz, Nekrotisch, Stichschaden"
damage_immunities: "Feuer, Gift, Kälte"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Gelähmt|Gelähmt]], [[Anhang PH-A#Liegend|Liegend]], [[Anhang PH-A#Verängstigt|Verängstigt]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelblick|Dunkelblick]] 18 Meter, passive Wahrnehmung 12
languages: Gemeinsprache
cr: 4
bestiary: true
traits:
  - name: Illumination.
    desc: "Der Flammenschädel verströmt helles Licht in einem Radius von 4,5 Metern und gedämpftes Licht für weitere 4,5 Meter."
  - name: Magische Resistenz.
    desc: "Der Flammenschädel ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Verjüngung.
    desc: "Wenn der Flammenschädel zerstört wird, erhält er innerhalb von 1 Stunde alle seine Trefferpunkte zurück, es sei denn, seine Überreste werden mit Weihwasser besprengt oder mit dem Zauber [Gutes und Böses bannen](Gutes-und-Böses-bannen.md) belegt."
actions:
  - name: Mehrfachangriff.
    desc: "Der Flammenschädel führt zwei Feuerstrahlen-Angriffe aus."
  - name: Feuerstrahl.
    desc: "_Nahkampf- oder Fernkampfangriffswurf:_ +5, Reichweite 1,5m oder 9m  _Treffer:_ 10 (3d6) Feuerschaden."
    attack_bonus: 5
    damage_dice: 3d6
    damage_bonus: 3
  - name: Zauberwirken.
    desc: "Der Flammenschädel ist ein Zauberwirker der 5. Stufe. Sein Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 17, +5 zum Treffen mit Zauberangriffen). Er benötigt weder verbale noch materielle Komponenten zum Zauberwirken. Der Flammenschädel hat die folgenden Magierzaubersprüche vorbereitet:"
  - name: Zaubertricks (Beliebig oft).
    desc: "[Magierhand](Magierhand.md)"
  - name: Zaubergrad 1 (3 Zauberplätze).
    desc: "[[Magische Geschosse]], [Zauber/Schild|Schild]"
  - name: Zaubergrad 2 (2 Zauberplätze).
    desc: "[Flammenkugel](Flammenkugel.md), [Verschwimmen](Verschwimmen.md)"
  - name: Zaubergrad 3 (1 Zauberplatz).
    desc: "[Feuerball](Feuerball.md)"
```

# Flammenschädel (2024)

>**Habitat:** Planar (Untere Ebenen)
>**Beute:** Arkanes

![](flameskull-2024.webp)

Flammenschädel sind fliegende Schädel, die mit magischem Feuer und den halb erinnerten Arkanen toter Zauberwirker lodern. Sie erheben sich aus den Überresten toter Magieanwender, die von finsteren Nekromanten wiederbelebt wurden oder deren magisches Streben sie über den Tod hinaus treibt. Flammenschädel können als Wächter für ihre Schöpfer dienen oder Ambitionen verfolgen, die im Leben unerfüllt blieben. Sie greifen ihre Feinde mit zerstörerischen Zaubern und Feuerstößen an und wenden Magie an, ohne die meisten Komponenten zu benötigen.

Flammenschädel nehmen verschiedene Formen an, von Schädeln mit menschenähnlichen Zügen bis hin zu solchen mit furchterregenden oder bestialischen Abwandlungen. Ihre Flammen variieren in der Farbe und werden intensiver, wenn sie wütend sind. Würfle auf oder wähle ein Ergebnis aus der Tabelle Flammenschädel-Details, um zu erfahren, was einen Flammenschädel auszeichnet.

  

## Details zum Flammenschädel
| 1d6 | Die Eigenschaften des Flammenschädels ...                |
| --- | -------------------------------------------------------- |
| 1   | Arkane Diagramme, die in den Schädel geätzt sind.        |
| 2   | Flammen wie dramatische Gesichtszüge, Hörner oder Haare. |
| 3   | Zerbrochene Teile, die im Gleichklang fliegen.           |
| 4   | Eine Eisenplatte, die über seinem Maul verschraubt ist.  |
| 5   | Tödliches Kopftrauma.                                    |
| 6   | Nicht zusammenpassende Tierzähne.                        | 

```statblock
name: Flammenschädel (2024)
image: pictures/flameskull-2024.webp
source: Monsterhandbuch 2024
size: Winzig
type: Untoter
alignment: Neutral Böse
ac: 13
hp: 40
hit_dice: 9d4 + 18
ini: +3 (13)
speed: 1,5 Meter, 40 Meter schwebend
stats: [1, 17, 14, 16, 10, 11]
saves:
  - STR: -5
  - GES: +3
  - KON: +2
  - INT: +3
  - WEI: +0
  - CHA: +0
skillsaves:
  - Arkane Kunde: 5
  - Wahrnehmung: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Feuer, Gift, Nekrotisch"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Erschöpfung|Erschöpfung]], [[Anhang PH-A#Gelähmt|Gelähmt]], [[Anhang PH-A#Liegend|Liegend]], [[Anhang PH-A#Verängstigt|Verängstigt]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelblick|Dunkelblick]] 18 Meter, passive Wahrnehmung 12
languages: Gemeinsprache, plus zwei weitere Sprachen
cr: 4
bestiary: true
traits:
  - name: Illumination.
    desc: "Der Flammenschädel verströmt helles Licht in einem Radius von 4,5 Metern und gedämpftes Licht für weitere 4,5 Meter."
  - name: Magische Resistenz.
    desc: "Der Flammenschädel ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Untote Wiederherstellung.
    desc: "Wenn der Flammenschädel zerstört wird, erhält er innerhalb von 1 Stunde alle seine Trefferpunkte zurück, es sei denn, seine Überreste werden mit Weihwasser besprengt oder mit dem Zauber [Gutes und Böses bannen](Gutes-und-Böses-bannen.md) belegt."
actions:
  - name: Mehrfachangriff.
    desc: "Der Flammenschädel führt zwei Feuerstrahlen-Angriffe aus."
  - name: Feuerstrahl.
    desc: "_Nahkampf- oder Fernkampfangriffswurf:_ +5, Reichweite 1,5m oder 18m  _Treffer:_ 13 (3d6 + 3) Feuerschaden."
    attack_bonus: 5
    damage_dice: 3d6
    damage_bonus: 3
  - name: Zauberwirken.
    desc: "Der Flammenschädel wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 13):"
  - name: Beliebig oft
    desc: "[Magierhand](Magierhand.md)"
  - name: je 2-mal täglich.
    desc: "[[Magische Geschosse]]"
  - name: je 1-mal täglich.
    desc: "[Feuerball](Feuerball.md)"
```