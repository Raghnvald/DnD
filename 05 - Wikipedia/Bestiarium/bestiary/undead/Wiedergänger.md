---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Mittelgroß
HG: 5
Habitat:
  - Arktis
  - Hügel
  - Stadt
  - Sumpf
  - Wald
  - Wüste
tags:
  - Quelle/5e/mm
  - Monster/cr/5
  - Monster/Habitat/Arktis
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Wald
  - Monster/Habitat/Wüste
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Revenant
---
# Wiedergänger
*Quelle: Monsterhandbuch S. 259*  

- **Habitat.** Arktis, Hügel, Stadt, Sümpfe, Wälder, Wüste
- **Schatz.** Jeder  

Ein Wiedergänger entsteht aus der Seele eines Sterblichen, dem ein grausames und unverdientes Schicksal widerfahren ist. Er bahnt sich seinen Weg zurück in die Welt, um sich an demjenigen zu rächen, der ihm Unrecht getan hat. Der Rächer erlangt seinen sterblichen Körper zurück und ähnelt oberflächlich betrachtet einem Zombie. Doch statt lebloser Augen brennen die Augen des Wiedergängers vor Entschlossenheit und flackern in der Gegenwart seines Gegners. Wenn der ursprüngliche Körper des Wiedergängers zerstört wurde oder aus anderen Gründen nicht verfügbar ist, geht der Geist des Wiedergängers in eine andere humanoide Leiche über. Ungeachtet des Körpers, den der Wiedergänger als Gefäß benutzt, erkennt sein Gegner den Wiedergänger immer als das, was er wirklich ist.

## Hunger nach Rache

Ein Rächer hat nur ein Jahr Zeit, um sich zu rächen. Wenn sein Gegner stirbt oder wenn er es nicht schafft, ihn vor Ablauf der Zeit zu töten, zerfällt er zu Staub und seine Seele entschwindet ins Jenseits. Wenn sein Gegner zu mächtig ist, um ihn allein zu vernichten, sucht er sich würdige Verbündete, die ihm bei der Erfüllung seines Auftrags helfen.

## Göttliche Gerechtigkeit

Keine Magie kann eine Kreatur verbergen, die von einem Rächer verfolgt wird. Er kennt immer die Richtung und die Entfernung zwischen ihm und dem Ziel seiner Rache. Wenn der Rächer sich an mehreren Gegnern rächen will, verfolgt er sie nacheinander, beginnend mit der Kreatur, die ihm den tödlichen Schlag versetzt hat. Wird der Körper des Rächers zerstört, fliegt seine Seele weiter, um sich einen neuen Leichnam zu suchen, in dem er seine Jagd fortsetzen kann.

## Untote Natur

Ein Wiedergänger braucht weder Luft, Essen, Trinken noch Schlaf.

```statblock
"name": "Wiedergänger"
"image": "token/revenant.webp"
"source":
  - "MM"
"size": "Mittelgroß"
"type": "Untoter"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "[[Lederrüstung]]"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "18"
"speed": "9 m."
"saves":
  - "Stärke": !!int "7"
  - "Konstitution": !!int "7"
  - "Weisheit": !!int "6"
  - "Charisma": !!int "7"
"damage_resistances": "Nekrotisch, Psychisch"
"damage_immunities": "Gift"
"condition_immunities": "Betäubt, Bezaubert, Erschöpfung, Gelähmt, Verängstigt, Vergiftet"
"senses": "Dunkelsicht 18 Meter, passive Wahrnehmung 13"
"languages": "Jede Sprache, die er zu Lebzeiten beherrschte"
"cr": "5"
"traits":
  - "name": "Regeneration"
    "desc": "Der Wiedergänger erhält zu Beginn seines Zuges 10 Trefferpunkte zurück. Wenn der Wiedergänger Feuer- oder gleißenden Schaden erleidet, funktioniert diese Eigenschaft zu Beginn des nächsten Zuges des Wiedergängers nicht mehr. Der Körper des Wiedergängers wird nur zerstört, wenn er seinen Zug mit 0 Trefferpunkten beginnt und sich nicht regeneriert."
  - "name": "Verjüngung"
    "desc": "Wenn der Körper des Wiedergängers zerstört wird, verbleibt seine Seele. Nach 24 Stunden bewohnt und belebt die Seele einen anderen humanoiden Leichnam auf derselben Existenzebene und erhält alle ihre Trefferpunkte zurück. Solange die Seele körperlos ist, kann man sie mit einem Wunschzauber dazu zwingen, ins Jenseits zu gehen und nicht zurückzukehren."
  - "name": "Immunität gegen Verwandlung"
    "desc": "Der Wiedergänger ist immun gegen Effekte, die Untote verwandeln."
  - "name": "Rachsüchtiger Fährtenleser"
    "desc": "Der Wiedergänger kennt die Entfernung und die Richtung jeder Kreatur, an der er sich rächen will, auch wenn sich die Kreatur und der Wiedergänger auf verschiedenen Existenzebenen befinden. Wenn die Kreatur, die der Wiedergänger verfolgt, stirbt, weiß der Wiedergänger das."
"actions":
  - "name": "Mehrfachangriff"
    "desc": "Der Wiedergänger führt zwei Faustangriffe aus."
  - "name": "Faust"
    desc: "_Nahkampf-Waffenangriff_: +7 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: 11 (2d6 + 4) Wuchtschaden. Wenn das Ziel eine Kreatur ist, gegen die der Wiedergänger Rache geschworen hat, erleidet das Ziel zusätzlich 14 (4d6) Wuchtschaden. Anstatt Schaden zuzufügen, kann der Wiedergänger das Ziel packen (SG 14 zum Entkommen), sofern es der Kategorie Groß oder kleiner angehört."
  - "name": "Rachsüchtiges Blenden"
    "desc": "Der Wiedergänger zielt auf eine Kreatur, die er im Umkreis von 9 Metern sehen kann und gegen die er Rache geschworen hat. Das Ziel muss einen Weisheits-Rettungswurf gegen SG 15 ablegen. Bei einem Fehlschlag wird das Ziel gelähmt, bis der Wiedergänger ihm Schaden zufügt oder bis zum Ende des nächsten Zuges des Wiedergänger. Wenn die Lähmung endet, hat das Ziel 1 Minute lang Angst vor dem Wiedergänger. Das verängstigte Ziel kann den Rettungswurf am Ende jeder seiner Runden wiederholen, wobei es einen Nachteil hat, wenn es den Wiedergänger sehen kann, und den Zustand der Verängstigung dadurch bei einem Erfolg selbst beenden."
```
^statblock