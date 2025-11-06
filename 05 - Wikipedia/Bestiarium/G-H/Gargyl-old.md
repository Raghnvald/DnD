---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Gargyl
Typ: Elementar
Größe: Mittelgroß
HG: 2
status:
image: token/Gargyl.webp
tags:
  - Quelle/5e/mm
  - Monster/Typ/Elementar
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
aliases:
  - Gargoyle
---
# Gargyl (2014)
Die unbelebten Gargylen, die auf Gebäuden hocken, sind von diesen bösartigen Kreaturen der elementaren Erde inspiriert, die an groteske, teuflische Statuen erinnern. Ein Gargyl lauert zwischen Steinen und Ruinen, so regungslos wie jede Statue, und erfreut sich an dem Schrecken, den er auslöst, wenn er sich aus seiner Bewegungslosigkeit löst. Er genießt auch die Schmerzen, die er seinen Opfern zufügt.

$\quad$**_Belebter Stein._** Gargylen halten sich an felsigen Klippen und Bergen fest oder nisten auf Simsen in unterirdischen Höhlen. Sie suchen die Dächer von Städten heim und hocken wie Geier auf hohen steinernen Bögen und Zinnen von Burgen und Kathedralen, und sie können so regungslos bleiben, dass sie unbelebt erscheinen. Gargylen können für Jahre in diesem Zustand bleiben und sind somit perfekte Wächter.

$\quad$**_Tödlicher Ruf._** Gargylen haben den Ruf, grausam zu sein. Statuen, die Gargylen ähneln sollen, tauchen in der Architektur zahlloser Kulturen auf, um Eindringlinge zu verscheuchen. Auch wenn diese Statuen nur Dekoration sind, können sich echte Gargylen zwischen ihnen verstecken, um arglose Opfer zu überfallen. Ein Gargyl könnte seine Langeweile lindern, indem er Vögel und Nagetiere fängt und quält, doch erhöht die lange Wartezeit nur seinen Wunsch, denkenden Wesen Schmerzen zuzufügen.

$\quad$**_Grausame Diener._** Gargylen lassen sich leicht von der Gerissenheit eines intelligenten Meisters inspirieren. Sie enießen einfache Aufgaben, wie das Bewachen des Hauses ihres Meisters, das Foltern und Töten von Eindringlingen, und a lles, das wenig Mühe und maximalen Schmerz und Blutvergießen bedeutet.

$\quad$Gargylen dienen manchmal Dämonen, weil diese ebenfalls an willkürlichem Chaos und Zerstörung interessiert sind. Mächtige Zauberwirker können Gargylen ebenfalls verpflichten, um Tore und Mauern zu bewachen. Gargylen haben die Geduld und Belastbarkeit von Steinen und dienen sogar den grausamsten Meistern für Jahre, ohne sich zu beschweren.

$\quad$**_Elementare Natur._** Ein Gargyl braucht keine Luft, Nahrung, Wasser oder Schlaf.

>[!info] Bruchstücke des Elementaren Bösen
>Wenn Ogremoch, der böse Prinz der Elementaren Erde, durch sein steinernes Reich schreitet, lässt er eine Spur aus zerbrochenen Felsen zurück. Diese Scherben werden mit einem Bewusstseinsfragment erfüllt und beben mit der Essenz des Elementarprinzen. Im Lauf von langen Jahren wachsen sie zu vage humanoiden Felsformationen heran, die sich am Ende in der harten, grausamen Gestalt des Gargyls auflösen.
>
>Ogremoch erschafft die Gargylen nicht bewusst, aber sie sind eine körperliche Manifestation seiner Bosheit. Gargylen sind eine Verhöhnung der elementaren Luft, die Ogremoch verabscheut. Sie sind schwere Kreaturen aus lebendem Stein, aber doch können sie fliegen . Wie ihr Erschaffer haben sie einen fundamentalen Hass auf Wesen der elementaren Luft, besonders auf Aarakocra, und genießen jede Gelegenheit, solche Wesen zu zerstören.
>
>Auf ihrer Heimatebene graben die Gargylen Erdpartikel aus, die Ogremoch nach Aaqa schleudert, die Domäne der Aarakocra und der wohlwollenden Windherzöge, denen die Vogelmenschen in der Elementarebene der Luft folgen.

```statblock
statblock: true
name: Gargyl
layout: Basic 5e German Layout
image: [[Gargyle.webp]]
source: Monsterhandbuch 2014
size: Mittelgroß
type: Elementar
alignment: chaotisch böse
ac: 15
hp: 52
hit_dice: 7d8 + 21
speed: 9 Meter.
stats: [15, 11, 16, 6, 11, 7]
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: "Wucht-, Stich- und Hiebschaden durch nicht-magische Angriffe, wenn die Waffen nicht aus Adama nt bestehen"
damage_immunities: "Gift"
condition_immunities: "Bezaubert, Erschöpft, Vergiftet"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Terral
cr: 2
environment: Stadt, Unterreich
bestiary: true
traits:
  - name: Falsches Erscheinungsbild
    desc: "Wenn der Gargyl bewegungslos bleibt, ist er nicht von einer unbelebten Statue zu unterscheiden."
actions:
  - name: Mehrfachangriff
    desc: "Der Gargyl führt zwei Angriffe aus: einen mit seinem Biss und einen mit seinen Klauen"
  - name: Biss
    desc: "_Nahkampf-Waffenangriff:_ +2 auf Treffer, Reichweite 1,5 m, ein Ziel. _Treffer:_ 5 (`1W6+2`) Stichschaden."
    attack_bonus: 2
    damage_dice: 1d6
    damage_bonus: 2
  - name: Klauen
    desc: "_Nahkampf-Waffenangriff:_ +4, Reichweite 1,5m, ein Ziel. _Treffer:_ 5 (`1W6 + 2`) Hiebschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```