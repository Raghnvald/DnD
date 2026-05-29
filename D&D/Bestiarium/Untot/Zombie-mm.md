---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Zombie
Kategorie: Untoter
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Stadt
image: token/zombie.webp
status: completed
linter-yaml-title-alias: Zombie
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/1-4
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Zombie
---
# Zombie
*Quelle: Monsterhandbuch S. 316. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Von irgendwo in der Dunkelheit ertönt ein gurgelndes Stöhnen. Eine torkelnde Gestalt wird sichtbar. Sie schleift einen Fuß hinter sich her und hebt aufgedunsene Arme und zerbrochene Hände. Der Zombie rückt vor, getrieben, alle zu töten, die zu langsam sind, ihm zu entkommen.

## Dunkle Diener

Finstere nekromantische Magie erfüllt die Überreste der Toten und erhebt sie als Zombies, die ohne Furcht oder Zögern dem Willen ihres Schöpfers folgen. Sie bewegen sich mit ruckartigen, ungleichmäßigen Schritten, sind in die schimmligen Gewänder gehüllt, die sie trugen, als sie zur Ruhe gebettet wurden, und stinken nach Verwesung.

$\quad$Die meisten Zombies werden aus humanoiden Überresten erschaffen, doch Fleisch und Knochen jeder ehemals lebenden Kreatur kann mit dem Anschein von Leben erfüllt werden. Nekromantische Magie, normalerweise durch Zaubersprüche, belebt einen Zombie. Einige Zombies erheben sich spontan, wenn dunkle Magie einen Bereich erfüllt. Sobald eine Kreatur in einen Zombie verwandelt wurde, kann sie nur noch mit mächtiger Magie zum Leben erweckt werden, beispielsweise durch einen Auferstehungszauber.

$\quad$Ein Zombie behält nichts von seinem ehemaligen Selbst, sein Geist ist leer von Gedanken und Vorstellungskraft. Ein Zombie, der keine Befehle erhalten hat, steht einfach herum und verwest, bis etwas kommt, das er töten kann. Die Magie, die einen Zombie belebt, erfüllt ihn mit böser Essenz. Wenn er also keine Anweisungen erhält, greift er alle lebenden Kreaturen an, denen er begegnet.

## Grässliche Gestalt

Zombies sehen aus, wie sie es im Leben taten, und weisen auch die Wunden auf, die sie getötet haben. Die Magie, die diese verderbten Kreaturen erschafft, braucht aber oft eine gewisse Zeit, bis sie wirkt. Tote Krieger könnten sich von einem Schlachtfeld erheben, ausgeweidet und aufgedunsen nach Tagen, die sie in der Sonne lagen.

$\quad$Der schlammige Kadaver eines Bauern könnte sich aus dem Boden kämpfen, gespickt mit Maden und Würmern. Ein Zombie könnte ans Ufer gespült werden oder sich aus einem Sumpf erheben, geschwollen und stinkend, nachdem er wochenlang im Wasser lag.

## Geistlose Soldaten

Zombies nehmen den direktesten Weg zu jedem Feind, weil sie Hindernisse, Taktiken oder gefährliches Gelände nicht verstehen können. Ein Zombie könnte in einen schnell fließenden Fluss taumeln, um Feinde am anderen Ufer zu erreichen, und nach der Wasseroberfläche schlagen, während er gegen Felsen geschmettert und zerstört wird. Um einen Feind unter sich zu erreichen, könnte ein Zombie aus einem offenen Fenster treten. Zombies stolpern, ohne zu zögern, durch lodernde Infernos, in Säurebecken und über Felder, die mit Krähenfüßen bedeckt sind.

$\quad$Ein Zombie kann einfache Befehle ausführen und Freund von Feind unterscheiden, aber seine Fähigkeit zu denken beschränkt sich darauf, in die Richtung zu torkeln, die ihm gezeigt wird, und auf jeden Gegner in seinem Weg einzuschlagen. Ein Zombie, der mit einer Waffe ausgerüstet ist, benutzt sie, aber er wird keine Waffe, die am Boden liegt, aufheben und kein anderes Werkzeug nutzen, wenn ihm dies nicht befohlen wird.

## Untote Natur

Ein Zombie muss nicht atmen, essen, trinken oder schlafen.

> [!quote] Fonkin Muldgipfel, über Freundschaft 
> Nachdem Beek gestorben war, wirkten wir Tote beleben auf seinen Leichnam. Es hat eine Weile Spaß gemacht, aber der Zombie begann richtig übel zu stinken, also haben wir ihn mit Öl übergossen und angezündet. Beek hätte es saukomisch gefunden.

```statblock
name: Zombie
image: token/zombie.webp
source: MM
size: Mittelgroß
type: Untoter
alignment: Neutral Böse
ac: 8
hp: 22
hit_dice: 3d8 + 9
modifier: -2
stats:
  - 13
  - 6
  - 16
  - 3
  - 6
  - 5
speed: 6 Meter
saves:
  - Weisheit: 0
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 8
languages: Versteht die Sprachen, die er im Leben sprach, kann aber nicht sprechen
cr: 1/4
environment: Stadt
traits:
  - name: Untote Ausdauer
    desc: "Wenn die Trefferpunkte des Zombies auf 0 verringert werden, muss er einen `Konstitutionsrettungswurf` gegen `SG 5` + erlittener Schaden ablegen, es sei denn, der Schaden war gleißender Schaden oder von einem kritischen Treffer. Bei einem Erfolg fällt der Zombie stattdessen auf 1 TP."
actions:
  - name: Hieb
    desc: "*Nahkampf-Waffenangriff:* +3 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 4 (1d6 + 1) Wuchtschaden."
```
^statblock