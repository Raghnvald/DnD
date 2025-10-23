---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/Curse_of_Strahd
- Größe/Gigantisch
- Typ/Konstrukt
aliases: ["Baba Lysaga’s Creeping Hut"]
---
# Baba Lysagas krabbelnde Hütte
Baba Lysaga hat eine Hütte auf einem verrotteten Stumpf eines riesigen Baums gebaut, der vor langer Zeit gefällt wurde. Als sie einen magischen Edelstein in die Hütte einbettete, wurde das ganze Ding mit einer Art Leben erfüllt. Wenn sie es ihr befiehlt, zieht die Hütte ihre gigantischen Wurzeln aus der Erde heraus und schlurft herum, wie ein spinnenartiges Ungetüm, das bei jedem Schritt den Erdboden erzittern lässt. Die Hütte attackiert mit ihren peitschenden und stampfenden Wurzeln. Sie kann ihre Wurzeln auch benutzen, um große Felsbrocken zu schleudern.
$\quad$ **_Hütteninneres._** Die Hütte ist ein 7,50m im Quadrat messendes wackeliges Holzgebäude mit einem sanft ansteigenden Reetdach. Das Mobiliar ist mit Bolzen am Boden befestigt, da die Hütte von einer Seite zur anderen schwankt, wenn sie läuft.
$\quad$ **_Herz der Hütte._** Der Edelstein, der Baba Lysagas Hütte zum Leben erweckt hat, war zuvor im Weinmagier-Weinberg vergraben. Das Juwel war eines von dreien, die mit lebensspendender Magie durchsetzt waren, welche die Weinstücke im Weinberg gesünder machte und die besten Weine garantierten. Baba Lysaga stahl eines der Juwelen, pervertierte seine Magie und nutzte sie stattdessen, um ihre Holzhütte zu beleben.
$\quad$ Wird das Juwel aus der Hütte entfernt, wird die Hütte kampfunfähig. Dieses Vorhaben ist jedoch leichter gesagt, als getan. Das glühende grüne Juwel ist in einem Hohlraum im Stumpf untergebracht, unter den morschen Bodendielen der Hütte. Die Dielen können mit einem gelungenen Stärkewurf gegen SG 14 herausgerissen oder zerschmettert werden, wenn man ihnen 10 Schaden zufügt. Sobald die Bodendielen aus dem Weg sind, kann eine Kreatur in den Hohlraum greifen und sich das Juwel schnappen. Aber wenn jemand dies versucht, solangedie Hütte noch lebt, wachsen dem Hohlraum Holzzähne und er wird ein Maul, das alles beißt, was das Juwel zu entfernen versucht; eine Kreatur die versucht das Juwel zu entfernen, muss einen Geschicklichkeits-Rettungswurf gegen SG 20 ablegen. Bei einem gelungenen Rettungswurf bemächtigt sich die Kreatur des Steins, ohne gebissen zu werden. Bei einem misslungenen Rettungswurf wird die Kreatur mit 10 (`dice: 3d6`) Stichschaden gebissen und versagt dabei, das Juwel zu beschaffen.

```statblock
statblock: true
name: Baba Lysagas krabbelnde Hütte
source: Fluch des Strahd
size: Gigantisch
type: Konstrukt
alignment: gesinnungslos
ac: 16
hp: 263
hit_dice: 7d20 +85
speed: 9 Meter.
stats: [26, 7, 20, 1, 3, 3]
saves:
  - STR: +0
  - GES: +0
  - KON: +9
  - INT: +0
  - WEI: +0
  - CHA: +0
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift, psychisch"
condition_immunities: "Bezaubert, blind, erschöpft, gelähmt, liegend, taub, verängstigt, versteinert"
senses: Blindsicht 36 Meter (über diesen Radius hinaus blind), passive Wahrnehmung 6
languages: -
cr: 11
bestiary: true
traits:
  - name: Antimagische Empfindlichkeit
    desc: Die Hütte wird kampfunfähig, wenn sich das magische Juwel, welches sie belebt, im Bereich eines _Antimagischen Feldes_ befindet. Wenn die Hütte Ziel von _Magie bannen_ wird, muss sie einen Konstitutions-Rettungswurf gegen den Zauberrettungswurf-SG des Zauberwirkers ablegen, um nicht für 1 Minute bewusstlos zu werden.
    attack_bonus: 0
  - name: Belagerungsmonster
    desc: Die Hütte verursacht doppelten Schaden gegen Gegenstände und Bauwerke.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Die Hütte führt drei Angriffe mit ihren Wurzeln aus. Sie kann einen dieser Angriffe durch einen Fels-Angriff ersetzen."
  - name: Wurzel
    desc: "_Nahkampf-Waffenangriff_: +12 zum Treffen, Reichweite 18m, ein Ziel. Treffer: 30 (4W10 + 8) Wuchtschaden."
    attack_bonus: 12
    damage_dice: 4d10
    damage_bonus: 8
  - name: Fels
    desc: "_Fernkampf-Waffenangriff_: +12 zum Treffen, Reichweite 36m, ein Ziel. Treffer: 21 (3W8 + 8) Wuchtschaden."
    attack_bonus: 12
    damage_dice: 3d8
    damage_bonus: 8
```