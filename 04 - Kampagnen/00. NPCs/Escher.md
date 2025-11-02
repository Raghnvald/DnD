---
tags:
- Quelle/5e/cos
aliases:
- 
---
# Rollenspiel‑Informationen

## Resonanz
Escher soll die Spieler durch sein auffallend flirtendes Verhalten amüsiert und geschmeichelt fühlen lassen, sie durch seine spöttischen oder herablassenden Kommentare irritieren und schließlich mit ihm mitfühlen, weil er sich seiner unausgesprochenen Schuld bewusst ist, dass er durch das Erwachen von Strahd Schaden über seine Freunde und Nachbarn gebracht hat.

## Emotionen
Escher empfindet am häufigsten Ärger, Neugier, Wut, Selbstgefälligkeit, Angst, Furcht, Verspieltheit, Schalkhaftigkeit, Amüsement, Schuldgefühle, Bitterkeit, Reue oder Scham.

## Motivation  
Escher möchte Strahd gefallen und vermeiden, aus dessen Gunst zu fallen.

## Inspirationen
Wenn du Escher spielst, orientiere dich an Asterion (Baldur’s Gate 3), Crowley (Good Omens) und Renly Baratheon (Game of Thrones).

# Charakter‑Information

## Persona  
Für die Welt ist Escher ein pompöser und selbstbewusster Höfling im Gefolge von Strahd, der Luxus, Selbstdarstellung und Aufmerksamkeit liebt. Nur Escher selbst weiß, dass er ein schuldbeladenes, selbstverachtendes, zerbrochenes Wesen ist, das verzweifelt nach Strahds Anerkennung strebt und sich längst dem Käfig ergeben hat, den seine eigenen Entscheidungen für ihn errichtet haben.

## Moral  
Im Kampf würde Escher versuchen, seinen Gegner zu beschwichtigen oder zu fliehen und nur dann kämpfen, wenn er in die Enge getrieben wird oder schwer beleidigt ist.

## Beziehungen  
Bevor er einer von Strahds Konkubinen wurde, hatte Escher eine Schwärmerei für Doru, seinen ehemaligen besten Freund. Heute ist er einer von Strahds Konkubinen – jedoch nicht formell mit ihm verheiratet – und ein untergeordneter Höfling im Hof von Strahd.

```statblock
name: Escher
image: [[Escher.webp]]
size: Mittelgroß
type: Untoter (Gestaltwandler)
alignment: neutral böse
ac: 16
hp: 82
hit_dice: 11d8 + 33
ini: +5 (15)
speed: 9 m
stats: [16, 16, 16, 11, 10, 16]
saves:
- GES: 6
- WEI: 3
skillsaves:
- heimlichkeit: 6
- wahrnehmung: 3
damage_resistances: nekrotisch; Wucht‑, Stich‑ und Hiebschaden von nichtmagischen Waffen
senses: Dunkelsicht 18 m; passive Wahrnehmung 11
languages: Elfisch, Gemeinsprache
cr: 5
bestiary: true
traits:
  - name: Regeneration
    desc: "Escher erhält zu Beginn seines Zuges 10 Trefferpunkte zurück, sofern er mindestens 1 Trefferpunkt hat und nicht im Sonnenlicht oder in fließendem Wasser ist. Bei Strahlungs‑ oder Weihwasser‑Schaden funktioniert diese Fähigkeit im nächsten Zug nicht"
  - name: Spinnenklettern
    desc: "Escher kann schwierige Oberflächen und Decken ohne Probe, sogar kopfüber."
    attack_bonus: 0
  - name: Vampirschwächen
    desc: "Escher hat die folgenden Nachteile: <br> **_Verbot._** Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. <br> **_Verletzt durch fließendes Wasser._** Escher erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. <br> **_Pflock ins Herz._** Wenn eine Stichwaffe aus Holz in Eschers Herz getrieben wird, solange er sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird. <br> **_Hyperempfindlich gegenüber Sonnenlicht._** Escher erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
    attack_bonus: 0
spells:
  - "Escher ist ein Zauberwirker der 4. Stufe; Charisma ist sein Zauberattribut (Zauberrettungswurf-SG 14, +6 zum Treffen mit Zauberangriffen). Escher kann die folgenden Zauber wirken:"
  - Zaubertricks: [Freundschaft](Freundschaft.md), [Gehässiger Spott](Gehässiger-Spott.md) [Taschenspielerei](Taschenspielerei.md)
  - Zaubergrad 1 (4 Plätze): [Dissonantes Flüstern](Dissonantes-Flüstern.md), [Feenfeuer](Feenfeuer.md), [Heldenmut](Heldenmut.md), [Schlaf](Schlaf.md)
  - Zaubergrad 2 (3 Plätze): [Krone des Wahnsinns](Krone-des-Wahnsinns.md), [Unsichtbarkeit](Unsichtbarkeit.md)
actions:
  - name: Mehrfachangriff
    desc: "Escher führt zwei Angriffe aus; höchstens einer davon kann ein Biss sein."
  - name: Krallen
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer:_ 2W4 + 3 Hiebschaden. Statt Schaden zu verursachen, kann Escher das Ziel greifen (Flucht‑SG 13)."
    attack_bonus: 6
    damage_dice: 2d4
    damage_bonus: 3
  - name: Rapier
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer:_ 2W6 + 3 Stichschaden."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 3
  - name: Biss
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein williges Ziel oder ein von Escher gefesseltes, handlungsunfähiges oder gefesseltes Ziel. _Treffer:_ 1W6 + 3 Stichschaden + 2W6 nekrotischer Schaden. Das maximale Trefferpunktekontingent des Ziels wird um den nekrotischen Schaden reduziert; Escher heilt um denselben Betrag. Die Reduktion dauert bis zum Abschluss einer langen Rast. Sinkt das Maximum auf 0, stirbt das Ziel."
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 3
reactions:
  - name: Riposte
    desc: "Während er sein Rapier führt, erhöht Escher seine RK um 2 gegen einen Nah‑ oder Fernkampfangriff, der ihn treffen würde. Misslingt der Angriff, kann Escher einen Nahkampfangriff gegen den Angreifer ausführen, sofern dieser in Reichweite ist."
```