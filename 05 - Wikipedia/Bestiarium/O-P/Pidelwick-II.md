---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/Curse_of_Strahd
  - Habitat/Stadt
  - Größe/Klein
  - Typ/Konstrukt
aliases:
  - Pidelwick II.
---
# Pidelwick II.
Nachdem ihr Ehemann in der Schlacht gefallen war, nahm Herzogin Dorfnija Dilisnja sich vor, die Braut von Graf Strahd von Zarowitsch zu werden, doch sie scheiterte daran, seine Liebe zu gewinnen. Ihre Besuche im Schloss waren nichtsdestotrotz häufig, und sie reiste nie ohne ihren Narren, den erstaunliche Pidelwick. Der kleine Mann war wie ein Sonnenstrahl in Schloss Ravenloft, und obwohl es ihm nicht gelang, Strahd zu amüsieren, erfreute er Tatjana und Sergej mit seinen Witzen und Freudensprüngen. Als Resultat erhob Strahd keine Einwände , wann immer Pidelwick und die Herzogin zu Besuch kamen.
$\quad$ In ihrem Wunsch, einen guten Eindruck zu hinterlassen und die Höflichkeit zu erwidern, beauftragte die Herzogin den legendären Spielzeugmacher Fritz von Weerg, eine aufziehbare Nachbildung Pidelwicks als Geschenk für Strahds Familie zu bauen. Obwohl das Herz der Herzogin am rechten Fleck saß, hatte die Nachbildung nicht Pidelwicks Fähigkeiten und vermochte nicht, irgendjemanden zu unterhalten. Obwohl sogar Pidelwick selbst Monate damit verbracht hatte, es zu u nte rweisen, konnte die Nachbildung nicht sprechen und seine Bewegungen waren eher ungelenk als amüsant.
$\quad$ Ein harter Winter hielt die Herzogin, ihren Narren und ihre Narrennachbildung mehrere Monate lang in Schloss Ravenloft gefangen. Die Herzogin erlag im Folgenden einer Krankheit woraufhin Tatjana Pidelwick bat, in Schloss Ravenloft zu bleiben.
$\quad$ **_Ein Pidelwick zuviel._** Von Weerg war kein gewöhnlicher Spielzeugmacher und er investierte ein wenig von sich selbst in all seine Kreationen, was heißen soll, dass seine Werke einen Hauch des Wahnsinns ihres Schöpfers hatten. Pidelwick II. wusste, dass es keine Verwendung für ihn gab, solange Pidelwick in Schloss Ravenloft blieb, also stieß es Pidelwick eine lange Treppe hinunter und tötete ihn dadurch. Jedermann sonst dachte, es wäre ein Unfall gewesen. In den folgenden Tagen gab Pidelwick II. sein Bestes, um in die Fußstapfen eines Namensgebers zu treten, doch die reine Anwesenheit der Nachbildung war betrüblich für Tatjana und es wurde nie gerufen, um aufzutreten. Schließlich wurde es einfach abgelegt.
$\quad$ **_Böses Spielzeug._** Pidelwick II. wurde in einem kleinen Wandschrank aufbewahrt, der an eines der Schlafgemächer angrenzte. Pidelwick machte sich zur Gewohnheit, mitten in der Nacht aus dem Wandschrank zu schleichen, den Gast mit einem Kissen zu ersticken und sich dann in den Wandschrank zurückzuziehen. Das Schlossgesinde zog nie in Erwägung, dass die Nachbildung verantwortlich sein könnte und nahm stattdessen an, die Gäste wären im Schlaf gestorben.
$\quad$ Aber Strahd ließ sich nicht zum Narren halten. Er kam recht schnell zu dem Schluss, dass die aufziehbare Nach- bildung begonnen hatte, eine mörderische Natur zu zeigen. Statt Pidelwick II. zu zerstören, behielt Strahd den Narren in der Nähe, um von Zeit zu Zeit lästige Gäste verschwinden zulassen.
$\quad$ Nach Sergejs und Tatjanas Tod wurde das Schloss praktisch aufgegeben, und es gab keine Gäste mehr, die Pidelwick II. „unterhalten" konnte. Die aufziehbare Nachbildung kam aus seinem Wandschrank hervor und fand neue Verstecke. Sie fürchtet Strahd und folgt begeistert jedem, der ihm die Aufmerksamkeit widmet, die sie begehrt.
$\quad$ Pidelwick II. ist prinzipiell ein übergroßes Spielzeug - ein 1,20 Meter großer Mechanismus, mit Zahnrädern, Uhrfedern und anderen meisterlich zusammengepassten Komponenten vollgestopft, um ihm eine Art Leben einzuflößen. Seine Haut ist aus genähtem Leder gemacht, die stramm über einen Holzrahmen mit Gelenken gezogen wurde. Pidelwick II. hat Ruß um seine Augen und seinen Mund gerieben, was ihm die dreieckigen Augen und das gezackte Grinsen einer Kürbislaterne verleiht.

![](../../../04%20-%20Kampagnen/00.%20NPCs/pictures/pidelwick_ii.webp)

### Charakteristika von Pidelwick II.
$\quad$ **_Ideal._** „Ich wünschte, ich könnte die Leute glücklich machen." 
$\quad$ **_Bindung._** „Ich würde gerne jemanden finden - irgendjemanden - der keine Angst vor mir hat und meine Gesellschaft genießt." 
$\quad$ **_Makel._** „Wenn ich verärgert bin, tue ich schlimme Dinge."

```statblock
statblock: true
name: Pidelwick II.
image: [[token/pidelwick_ii_token.webp]]
source: Fluch des Strahd
size: Klein
type: Konstrukt
alignment: Neutral Böse
ac: 14
hp: 10
hit_dice: 3d6
speed: 9 Meter.
stats: [10, 14, 11, 8, 13, 10]
skillsaves:
  - Auftreten: +2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift"
condition_immunities: "Gelähmt, Vergiftet, Versteinert"
senses: passive Wahrnehmung 11
languages: Versteht Gemeinsprache, spricht aber nicht und kann nicht lesen oder schreiben
cr: 1/4
bestiary: true
traits:
  - name: Lauerjäger.
    desc: "In der ersten Kampfrunde hat Pidelwick II. einen Vorteil auf seine Angriffswürfe gegen jede Kreatur, die er überrascht hat."
actions:
  - name: Keule
    desc: "_Nahkampf-Waffenangriff_: +2 zum Treffen, Reichweite 1,50 m, ein Ziel. _Treffer_: 2 (`1W4`) Wuchtschaden."
    attack_bonus: 2
    damage_dice: 1d4
    damage_bonus: 0
  - name: Wurfpfeil
    desc: "_Fernkampf-Waffenangriff_: +4 zum Treffen, Reichweite 6/18 m, ein Ziel. _Treffer_: 4 (`1W4 + 2`) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
```