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
  - Habitat/Arktis
  - Habitat/Hügel
  - Habitat/Stadt
  - Habitat/Sumpf
  - Habitat/Wald
  - Habitat/Wüste
  - Größe/Mittelgroß
  - Typ/Untote
aliases:
  - Revenant
---
# Wiedergänger

Ein Wiedergänger entsteht aus der Seele eines Sterblichen, dem ein grausames und unverdientes Schicksal widerfahren ist. Er bahnt sich seinen Weg zurück in die Welt, um sich an demjenigen zu rächen, der ihm Unrecht getan hat. Der Rächer erlangt seinen sterblichen Körper zurück und ähnelt oberflächlich betrachtet einem Zombie. Doch statt lebloser Augen brennen die Augen des Wiedergängers vor Entschlossenheit und flackern in der Gegenwart seines Gegners. Wenn der ursprüngliche Körper des Wiedergängers zerstört wurde oder aus anderen Gründen nicht verfügbar ist, geht der Geist des Wiedergängers in eine andere humanoide Leiche über. Ungeachtet des Körpers, den der Wiedergänger als Gefäß benutzt, erkennt sein Gegner den Wiedergänger immer als das, was er wirklich ist.

**_Hunger nach Rache._** Ein Rächer hat nur ein Jahr Zeit, um sich zu rächen. Wenn sein Gegner stirbt oder wenn er es nicht schafft, ihn vor Ablauf der Zeit zu töten, zerfällt er zu Staub und seine Seele entschwindet ins Jenseits. Wenn sein Gegner zu mächtig ist, um ihn allein zu vernichten, sucht er sich würdige Verbündete, die ihm bei der Erfüllung seines Auftrags helfen.

**_Göttliche Gerechtigkeit.**_  Keine Magie kann eine Kreatur verbergen, die von einem Rächer verfolgt wird. Er kennt immer die Richtung und die Entfernung zwischen ihm und dem Ziel seiner Rache. Wenn der Rächer sich an mehreren Gegnern rächen will, verfolgt er sie nacheinander, beginnend mit der Kreatur, die ihm den tödlichen Schlag versetzt hat. Wird der Körper des Rächers zerstört, fliegt seine Seele weiter, um sich einen neuen Leichnam zu suchen, in dem er seine Jagd fortsetzen kann.


**_Untote Natur._** Ein Wiedergänger braucht weder Luft, Essen, Trinken noch Schlaf.


**VARIANTE: WIEDERGÄNGER MIT ZAUBERSPRÜCHEN UND WAFFEN**

Wiedergänger, die vor ihrem Tod Zauberer waren, können einige oder alle ihrer Zauberfähigkeiten behalten. Ebenso können Wiedergänger, die zu Lebzeiten Rüstungen trugen und Waffen führten, dies auch weiterhin tun.

--- 

```statblock
statblock: true
name: Wiedergänger
image: [[Wiedergänger-token.webp]]
source: Monsterhandbuch
size: Mittelgroß
type: Untoter
alignment: Neutral
ac: 13
hp: 136
hit_dice: 16d8 + 64
speed: 9 Meter.
stats: [18, 14, 18, 13, 16, 18]
saves:
  - STR: +7
  - KON: +7
  - WEI: +6
  - CHA: +7
damage_vulnerabilities: ""
damage_resistances: "Nekrotisch, Psychisch"
damage_immunities: "Gift"
condition_immunities: "Betäubt, Bezaubert, Erschöpfung, Gelähmt, Verängstigt, Vergiftet"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 13
languages: Jede Sprache, die er zu Lebzeiten beherrschte
cr: 5
environment: Arktis, Hügel, Stadt, Sümpfe, Wälder, Wüste
bestiary: true
traits:
  - name: Regeneration
    desc: Der Wiedergänger erhält zu Beginn seines Zuges 10 Trefferpunkte zurück. Wenn der Wiedergänger Feuer- oder gleißenden Schaden erleidet, funktioniert diese Eigenschaft zu Beginn des nächsten Zuges des Wiedergängers nicht mehr. Der Körper des Wiedergängers wird nur zerstört, wenn er seinen Zug mit 0 Trefferpunkten beginnt und sich nicht regeneriert.
    attack_bonus: 0
  - name: Verjüngung
    desc: Wenn der Körper des Wiedergängers zerstört wird, verbleibt seine Seele. Nach 24 Stunden bewohnt und belebt die Seele einen anderen humanoiden Leichnam auf derselben Existenzebene und erhält alle ihre Trefferpunkte zurück. Solange die Seele körperlos ist, kann man sie mit einem Wunschzauber dazu zwingen, ins Jenseits zu gehen und nicht zurückzukehren.
    attack_bonus: 0
  - name: Immunität gegen Verwandlung
    desc: Der Wiedergänger ist immun gegen Effekte, die Untote verwandeln.
    attack_bonus: 0
  - name: Rachsüchtiger Fährtenleser
    desc: Der Wiedergänger kennt die Entfernung und die Richtung jeder Kreatur, an der er sich rächen will, auch wenn sich die Kreatur und der Wiedergänger auf verschiedenen Existenzebenen befinden. Wenn die Kreatur, die der Wiedergänger verfolgt, stirbt, weiß der Wiedergänger das.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Wiedergänger führt zwei Faustangriffe aus."
    attack_bonus: 0
  - name: Faust
    desc: "_Nahkampf-Waffenangriff_: +7 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: `11` (`2W6 + 4`) Wuchtschaden. Wenn das Ziel eine Kreatur ist, gegen die der Wiedergänger Rache geschworen hat, erleidet das Ziel zusätzlich `14` (`4d6`) Wuchtschaden. Anstatt Schaden zuzufügen, kann der Wiedergänger das Ziel packen (SG 14 zum Entkommen), sofern es der Kategorie Groß oder kleiner angehört."
    attack_bonus: 7
    damage_dice: 2d6
    damage_bonus: 4
  - name: Rachsüchtiges Blenden
    desc: "Der Wiedergänger zielt auf eine Kreatur, die er im Umkreis von 9 Metern sehen kann und gegen die er Rache geschworen hat. Das Ziel muss einen Weisheits-Rettungswurf gegen SG 15 ablegen. Bei einem Fehlschlag wird das Ziel gelähmt, bis der Wiedergänger ihm Schaden zufügt oder bis zum Ende des nächsten Zuges des Wiedergänger. Wenn die Lähmung endet, hat das Ziel 1 Minute lang Angst vor dem Wiedergänger. Das verängstigte Ziel kann den Rettungswurf am Ende jeder seiner Runden wiederholen, wobei es einen Nachteil hat, wenn es den Wiedergänger sehen kann, und den Zustand der Verängstigung dadurch bei einem Erfolg selbst beenden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```