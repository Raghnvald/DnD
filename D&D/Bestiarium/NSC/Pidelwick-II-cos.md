---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Pidlwick II
linter-yaml-title-alias: Pidlwick II
tags:
  - Monster/Größe/Klein
  - Monster/HG/1-4
  - Monster/Typ/Konstrukt
  - Quelle/5e/cos
aliases:
  - Pidlwick II
---
# Pidlwick II
*Quelle: Fluch des Strahd S. 236*  

Nachdem ihr Ehemann in der Schlacht gefallen war, nahm Herzogin Dorfnija Dilisnja sich vor, die Braut von Graf Strahd von Zarowitsch zu werden, doch sie scheiterte daran, seine Liebe zu gewinnen. Ihre Besuche im Schloss waren nichtsdestotrotz häufig, und sie reiste nie ohne ihren Narren, den erstaunliche Pidelwick. Der kleine Mann war wie ein Sonnenstrahl in Schloss Ravenloft, und obwohl es ihm nicht gelang, Strahd zu amüsieren, erfreute er Tatjana und Sergej mit seinen Witzen und Freudensprüngen. Als Resultat erhob Strahd keine Einwände , wann immer Pidelwick und die Herzogin zu Besuch kamen.

$\quad$ In ihrem Wunsch, einen guten Eindruck zu hinterlassen und die Höflichkeit zu erwidern, beauftragte die Herzogin den legendären Spielzeugmacher Fritz von Weerg, eine aufziehbare Nachbildung Pidelwicks als Geschenk für Strahds Familie zu bauen. Obwohl das Herz der Herzogin am rechten Fleck saß, hatte die Nachbildung nicht Pidelwicks Fähigkeiten und vermochte nicht, irgendjemanden zu unterhalten. Obwohl sogar Pidelwick selbst Monate damit verbracht hatte, es zu u nte rweisen, konnte die Nachbildung nicht sprechen und seine Bewegungen waren eher ungelenk als amüsant.

$\quad$ Ein harter Winter hielt die Herzogin, ihren Narren und ihre Narrennachbildung mehrere Monate lang in Schloss Ravenloft gefangen. Die Herzogin erlag im Folgenden einer Krankheit woraufhin Tatjana Pidelwick bat, in Schloss Ravenloft zu bleiben.

## Ein Pidelwick zuviel

Von Weerg war kein gewöhnlicher Spielzeugmacher und er investierte ein wenig von sich selbst in all seine Kreationen, was heißen soll, dass seine Werke einen Hauch des Wahnsinns ihres Schöpfers hatten. Pidelwick II. wusste, dass es keine Verwendung für ihn gab, solange Pidelwick in Schloss Ravenloft blieb, also stieß es Pidelwick eine lange Treppe hinunter und tötete ihn dadurch. Jedermann sonst dachte, es wäre ein Unfall gewesen. In den folgenden Tagen gab Pidelwick II. sein Bestes, um in die Fußstapfen eines Namensgebers zu treten, doch die reine Anwesenheit der Nachbildung war betrüblich für Tatjana und es wurde nie gerufen, um aufzutreten. Schließlich wurde es einfach abgelegt.

## Böses Spielzeug

Pidelwick II. wurde in einem kleinen Wandschrank aufbewahrt, der an eines der Schlafgemächer angrenzte. Pidelwick machte sich zur Gewohnheit, mitten in der Nacht aus dem Wandschrank zu schleichen, den Gast mit einem Kissen zu ersticken und sich dann in den Wandschrank zurückzuziehen. Das Schlossgesinde zog nie in Erwägung, dass die Nachbildung verantwortlich sein könnte und nahm stattdessen an, die Gäste wären im Schlaf gestorben.

Aber Strahd ließ sich nicht zum Narren halten. Er kam recht schnell zu dem Schluss, dass die aufziehbare Nach- bildung begonnen hatte, eine mörderische Natur zu zeigen. Statt Pidelwick II. zu zerstören, behielt Strahd den Narren in der Nähe, um von Zeit zu Zeit lästige Gäste verschwinden zulassen.

Nach Sergejs und Tatjanas Tod wurde das Schloss praktisch aufgegeben, und es gab keine Gäste mehr, die Pidelwick II. „unterhalten" konnte. Die aufziehbare Nachbildung kam aus seinem Wandschrank hervor und fand neue Verstecke. Sie fürchtet Strahd und folgt begeistert jedem, der ihm die Aufmerksamkeit widmet, die sie begehrt.

Pidelwick II. ist prinzipiell ein übergroßes Spielzeug - ein 1,20 Meter großer Mechanismus, mit Zahnrädern, Uhrfedern und anderen meisterlich zusammengepassten Komponenten vollgestopft, um ihm eine Art Leben einzuflößen. Seine Haut ist aus genähtem Leder gemacht, die stramm über einen Holzrahmen mit Gelenken gezogen wurde. Pidelwick II. hat Ruß um seine Augen und seinen Mund gerieben, was ihm die dreieckigen Augen und das gezackte Grinsen einer Kürbislaterne verleiht.

## Pidlwick II's Traits

### Ideal

"Ich wünschte, ich könnte die Leute glücklich machen."

### Bindung

"Ich würde gerne jemanden finden - irgendjemanden - der keine Angst vor mir hat und meine Gesellschaft genießt."

### Makel

"Wenn ich verärgert bin, tue ich schlimme Dinge."

```statblock
"name": "Pidlwick II (CoS)"
"size": "Small"
"type": "construct"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "8"
  - !!int "13"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+2"
"damage_immunities": "poison"
"condition_immunities": "[paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": "understands Common but doesn't speak and can't read or write"
"cr": "1/4"
"traits":
  - "desc": "During the first round of combat, Pidlwick II has advantage on attack\
      \ rolls against any creature that hasn't had a turn yet."
    "name": "Ambusher"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 20/60 ft., one target. *Hit:*\
      \ 4 (1d4 + 2) piercing damage."
    "name": "Dart"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/pidlwick-ii-cos.webp"
```
^statblock

---

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