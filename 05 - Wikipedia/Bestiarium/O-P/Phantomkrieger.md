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
- Quelle/5e/Curse_of_Strahd
- Habitat/Stadt
- Größe/Mittelgroß
- Typ/Untote
aliases:
- NAME
---
# Phantomkrieger
Ein Phantomkrieger ist der geisterhafte Überrest eines starrsinnigen Soldaten oder Ritters, der auf dem Schlachtfeld fiel oder in Ausübung seiner geschworenen Pflicht starb. Er erscheint wie eine durchscheinende Version seines lebenden Selbst.
$\quad$ **_Aufgabengetrieben._** Obwohl er oft mit einem Geist verwechselt wird, ist ein Phantomkrieger nicht von dem Wunsch erfüllt, ein unerledigtes Ziel zu erreichen. Er kann jederzeit entscheiden, seine untote Existenz zu beenden. Sein Geist bleibt aus freiem Willen zurück, entweder aus Loyalität seinem ehemaligen Herrn gegenüber oder weil er glaubt, eine Aufgabe erfüllen zu müssen um seiner Ehre oder seinem Pflichtbewusstsein zu genügen. Zum Beispiel könnte ein Wächter, der bei der Verteidigung eines Walls stirbt, als Phantomkrieger zurückkehren, weiterhin den Wall bewachen und dann für immer verschwinden, sobald ein neuer Wächter seinen Posten antritt oder der Wall zerstört wird. Der Zeitraum zwischen dem Todeszeitpunkt und dem Zeitpunkt, zu dem er sich als Phantomkrieger erhebt, beträgt üblicherweise 24 Stunden.
$\quad$ **_Verblasste Erinnerungen._** Ein Phantomkrieger behält die Gesinnung und Persönlichkeit, die er vor seinem Tod hatte, und er erinnert sich daran, wie er starb. Erinnerungen an sein Leben kurz vor seinem Tod sind verschwommen, und ältere Erinnerungen meist ganz vergessen. Ein Phantomkrieger kann sich üblicherweise an die letzten 1W10 + 10 Tage seines Lebens erinnern; alles, was vorher passierte, wird von einem undurchdringlichen Nebel verdeckt.
$\quad$ **_Machtvolle Präsenz._** Obwohl sie körperlos sind, können Phantomkrieger die Energie um sie herum nutzen, um gegen sie gerichtete Angriffe abzuwehren und mit großer Stärke zuzuschlagen. Eine unsichtbare Hülle aus Energie umgibt die geisterhaften Rüstungen, Schilde und Waffen eines Phantomkriegers, die hart wie Stahl werden und dennoch nicht die Fähigkeit eines Phantomkriegers beeinträchtigen, sich durch Wände und andere solide Objekte hindurchzubewegen.
$\quad$ **_Untote Natur._** Ein Phantomkrieger benötigt weder Luft, Nahrung, Wasser oder Schlaf.

```statblock
statblock: true
name: Phantomkrieger
image: [[NAME.png]]
source: Fluch des Strahd
size: Mittelgroß
type: Untoter
alignment: beliebige Gesinnung
ac: 16
hp: 45
hit_dice: 6d8 + 18
speed: 9 Meter.
stats: [16, 11, 16, 8, 10, 15]
skillsaves:
  - Heimlichkeit: +4
  - Wahrnehmung: +2
damage_vulnerabilities: ""
damage_resistances: "Hieb-, Stich- und Wuchtschaden von nicht-magischen Angriffen"
damage_immunities: "Gift, Kälte, nekrotisch"
condition_immunities: "Bezaubert, Erschöpft, Festgesetzt, Gelähmt, Gepackt, Liegend, Verängstigt, Vergiftet, Versteinert"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 12
languages: Jede Sprache, die er zu Lebzeiten beherrschte
cr: 3
bestiary: true
traits:
  - name: Ätherische Sicht
    desc: Der Phantomkrieger kann 18 Meter weit in die Ätherebene blicken, wenn er sich auf der Materiellen Ebene befindet, und umgekehrt.
    attack_bonus: 0
  - name: Körperlose Bewegung
    desc: Der Phantomkrieger kann sich durch andere Kreaturen und Gegenstände bewegen, als seien sie schwieriges Gelände. Er erleidet `5 (1W10)` Energieschaden, wenn er seinen Zug in einem Gegenstand beendet.
    attack_bonus: 0
  - name: Spektrale Rüstung und spektraler Schild
    desc: Die RK des Phantomkriegers berücksichtigt seine spektrale Rüstung und seinen spektralen Schild.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Phantomkrieger führt zwei Angriffe mit seinem spektralen Langschwert aus."
    attack_bonus: 0
  - name: Spektrales Langschwert
    desc: "_Nahkampf-Waffenangriff_: +5 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: `7` (`1W8 + 3`) Energieschaden."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Körperlosigkeit
    desc: "Der Phantomkrieger kann die Ätherebene von der Materiellen Ebene aus betreten und andersherum. Er ist auf der Materiellen Ebene sichtbar, solange er sich in der Äthergrenze befindet, doch er kann nichts auf der anderen Ebene beeinflussen oder beeinflusst werden."
    attack_bonus: 0
```