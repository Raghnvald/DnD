---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Escher
tags:
  - Quelle/5e/cos
  - Monster/cr/5
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Escher
Typ: Untoter
Größe: Mittelgroß
Habitat:
  - /
HG: 5
status: WIP
---
# Escher
*Quelle:Fluch des Strahd S. 70*  

```statblock
"name": "Escher (CoS)"
"image": "token/escher-cos.webp"
"source":
  - "CoS"
"size": "Mittelgroß"
"type": "Untoter"
"alignment": "Neutral Böse"
"ac": !!int "15"
"ac_class": "Natürliche Rüstung"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "12"
"speed": "9 m."
"saves":
  - "Geschicklichkeit": !!int "6"
  - "Weisheit": !!int "3"
"skillsaves":
  - "name": "Heimlichkeit"
    "desc": "+3"
  - "name": "Wahrnehmung"
    "desc": "+6"
"damage_resistances": "nekrotisch; Wucht‑, Stich‑ und Hiebschaden von nichtmagischen Waffen"
"senses": "Dunkelsicht 18 m, passive Wahrnehmung 11"
"languages": "Elfisch, Gemeinsprache"
"cr": "5"
"traits":
  - "name": "Regeneration"
    "desc": "Escher erhält zu Beginn seines Zuges 10 Trefferpunkte zurück, sofern er mindestens 1 Trefferpunkt hat und nicht im Sonnenlicht oder in fließendem Wasser ist. Bei Strahlungs‑ oder Weihwasser‑Schaden funktioniert diese Fähigkeit im nächsten Zug nicht"
  - "name": "Spinnenklettern"
    "desc": "Escher kann schwierige Oberflächen und Decken ohne Probe, sogar kopfüber."
  - "name": "Vampirschwächen"
    "desc": "Escher hat die folgenden Nachteile: \n\n- **Verbot.** Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. \n- **Verletzt durch fließendes Wasser.** Escher erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. \n- **Pflock ins Herz.** Wenn eine Stichwaffe aus Holz in Eschers Herz getrieben wird, solange er sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird.  \n- **Hyperempfindlich gegenüber Sonnenlicht.** Escher erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
"actions":
  - "name": "Mehrfachangriff"
    "desc": "Escher führt zwei Angriffe aus; höchstens einer davon kann ein Biss sein."
  - name: Biss
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein williges Ziel oder ein von Escher gefesseltes, handlungsunfähiges oder gefesseltes Ziel. _Treffer:_ 1d6 + 3 Stichschaden + 2d6 nekrotischer Schaden. Das maximale Trefferpunktekontingent des Ziels wird um den nekrotischen Schaden reduziert; Escher heilt um denselben Betrag. Die Reduktion dauert bis zum Abschluss einer langen Rast. Sinkt das Maximum auf 0, stirbt das Ziel."
  - name: Krallen
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer:_ 2W4 + 3 Hiebschaden. Statt Schaden zu verursachen, kann Escher das Ziel greifen (Flucht‑SG 13)."
```
^statblock