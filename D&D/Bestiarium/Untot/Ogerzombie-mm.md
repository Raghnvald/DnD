---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Name: Ogerzombie
Typ: Untoter
Größe: Groß
HG: 2
Habitat:
  - /
status: completed
image: image/ogre-zombie.webp
tags:
  - Quelle/5e/mm
  - Monster/HG/2
  - Monster/Größe/Groß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ogre Zombie
---
# [Ogre Zombie](3-Mechanics\CLI\bestiary\undead/ogre-zombie.md)
*Source: Monster Manual p. 316. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Von irgendwo in der Dunkelheit ertönt ein gurgelndes Stöhnen. Eine torkelnde Gestalt wird sichtbar. Sie schleift einen Fuß hinter sich her und hebt aufgedunsene Arme und zerbrochene Hände. Der Zombie rückt vor, getrieben, alle zu töten, die zu langsam sind, ihm zu entkommen.

## Dunkle Diener

Finstere nekromantische Magie erfüllt die Überreste der Toten und erhebt sie als Zombies, die ohne Furcht oder Zögern dem Willen ihres Schöpfers folgen. Sie bewegen sich mit ruckartige n, ungleichmäßigen Schritten, sind in die schimmligen Gewänder gehüllt, die sie trugen, als sie zur Ruhe gebettet wurden, und stinken nach Verwesung.

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
> Nachdem Beek gestorben war, wirkten wir [[Tote_beleben-phb|Tote beleben]] auf seinen Leichnam. Es hat eine Weile Spaß gemacht, aber der Zombie begann richtig übel zu stinken, also haben wir ihn mit Öl übergossen und angezündet. Beek hätte es saukomisch gefunden.


```statblock
name: Ogerzombie
image: token/ogre-zombie.webp
source: MM
size: Groß
type: Untoter
alignment: Neutral Böse
ac: 8
hp: 85
hit_dice: 9d10 + 36
modifier: -2
stats:
  - 19
  - 6
  - 18
  - 3
  - 6
  - 5
speed: 9 Meter
saves:
  - Wei: 0
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 8
languages: Versteht Gemeinsprache und Riesisch, kann aber nicht sprechen
cr: 2
traits:
  - name: Untote Ausdauer
    desc: "Wenn die Trefferpunkte des Zombies auf O verringert werden, muss er einen Konstitutionsrettungswurf gegen SG 5 + erlittener Schaden ablegen, es sei denn, der Schaden war gleißender Schaden oder von einem kritischen Treffer. Bei einem Erfolg fällt der Zombie stattdessen auf 1 TP."
actions:
  - name: Morgenstern
    desc: "*Nahkampf-Waffenangriff:* +6 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 13 (2d8+4) Wuchtschaden."
```
^statblock