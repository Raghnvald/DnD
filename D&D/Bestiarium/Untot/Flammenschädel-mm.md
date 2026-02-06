---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Flammenschädel
Kategorie: Untoter
Größe: Winzig
HG: 4
Habitat:
  - Unterreich
image: image/flameskull-webp
status: completed
tags:
  - Monster/Größe/Winzig
  - Monster/Habitat/Unterreich
  - Monster/HG/4
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Flammenschädel
  - Flameskull
linter-yaml-title-alias: Flammenschädel
---
# Flammenschädel
*Quelle: Monsterhandbuch S. 316. Verfügbar im  Grundregelwerk (2014)*  

Lodernde grüne Flammen und wahnsinniges, widerhallendes Lachen folgen einem körperlosen Schädel, während er durch seine Domäne streift. Wenn der untote Flammenschädel Eindringlinge bemerkt, zerstört er die Eindringlinge mit feurigen Strahlen aus seinen Augen und schrecklichen Zaubersprüchen, die er aus den dunkelsten Winkeln seiner Erinnerung gezogen hat.

$\quad$Dunkle Zauberwirker erschaffen Flammenschädel aus den Überresten toter Magier. Wenn das Ritual abgeschlossen ist, brechen grüne Flammen aus dem Schädel hervor und vervollständigen die grausige Verwandlung.

## Vermächtnis des Lebens 

Ein Flammenschädel erinnert sich nur vage an sein früheres Leben. Auch wenn er vielleicht mit seiner alten Stimme spricht und von Schlüsselereignissen aus seiner Vergangenheit berichtet, ist er nur ein Echo seines ehemaligen Selbst. Allerdings gewährt ihm seine untote Verwandlung vollen Zugriff auf die Magie, die er im Leben genutzt hat, sodass er Zauber wirken kann. Dabei ignoriert er die Materialkomponente und die Gestenkomponente, die er nicht mehr länger verwenden kann.

## Ewig gebunden

Flammenschädel sind intelligent und wachsam und dienen ihrem Erschaffer, indem sie eine verborgene Schatzkammer, einen geheimen Raum oder eine bestimmte Person beschützen. Ein Flammenschädel führt die Befehle aus, die ihm bei seiner Erschaffung gegeben worden sind, und interpretiert diese Befehle buchstäblich. Der Meister eines Flammenschädels muss seine Anweisungen sorgfältig formulieren, damit die Kreatur sie richtig ausführen kann.

## In Flammen gehüllt

Das Feuer, das einen Flammenschädel umzüngelt, brennt beständig und gibt helles Licht ab, das die Kreatur kontrolliert. Sie verwendet diese Flammen als Waffe, indem sie sie fokussiert und als Feuerstrahlen aus ihren Augenhöhlen entfesselt.

## Unheimliche Auferstehung

Die zerstörten Fragmente eines Flammenschädels formen sich neu, wenn sie nicht mit Weihwasser besprenkelt oder mit dem Zauber [[Magie_bannen-phb|Magie bannen]] oder [[Fluch_brechen-phb|Fluch brechen]] belegt werden. Wenn der neu geformte Flammenschädel seinen Daseinszweck nicht mehr erfüllen kann, untersteht er niemandem mehr und wird selbstständig.

## Untote Natur

Ein Flammenschädel braucht keine Luft, Nahrung, Wasser oder Schlaf.

```statblock
name: Flammenschädel
image: token/flameskull.webp
source: MM
size: Winzig
type: Untoter
alignment: Neutral Böse
ac: 13
hp: 40
hit_dice: 9d4 + 18
modifier: 3
stats:
  - 1
  - 17
  - 14
  - 16
  - 10
  - 11
speed: 0 m, fliegen 12 m (schweben)
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Arkane%20Kunde|Arkane Kunde<STATBLOCK-MARKDOWN-LINK>
    desc: "+5"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+2"
damage_resistances: Blitz, Nekrotisch, Stich
damage_immunities: Feuer, Gift, Kälte
condition_immunities:  <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>,  <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gelähmt|Gelähmt<STATBLOCK-MARKDOWN-LINK>,  <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Liegend|Liegend<STATBLOCK-MARKDOWN-LINK>,  <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|Verängstigt<STATBLOCK-MARKDOWN-LINK>,  <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 60 ft., passive Wahrnehmung 12
languages: Gemeinsprache
cr: 4
traits:
  - name: Beleuchtung
    desc: "Der Flammenschädel gibt entweder schwaches Licht in einem Radius von 4,5 m oder helles Licht in einem Radius von 4,5 m und schwaches Licht in einem Radius von weiteren 4,5 m ab. Es kann als Aktion zwischen diesen beiden Möglichkeiten wechseln."
  - name: Magieresistenz
    desc: "Der Flammenschädel hat einen Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte"
  - name: Wiederbelebung
    desc: "Wenn der Flammenschädel zerstört wird, erhält er innerhalb von 1 Stunde alle Trefferpunkte zurück, wenn nicht <STATBLOCK-MARKDOWN-LINK>Gegenstände/Weihwasser-Flasche-phb|Weihwasser<STATBLOCK-MARKDOWN-LINK> auf die Überreste gesprenkelt wird oder jemand den Zauber <STATBLOCK-MARKDOWN-LINK>Zauber/Magie_bannen-phb|Magie bannen<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>Zauber/Fluch_brechen-phb|Fluch brechen<STATBLOCK-MARKDOWN-LINK> auf ihn wirkt."
  - name: Zauberwirken
    desc: |-
      Der Flammenschädel ist ein Zauberwirker der 5. Stufe. Sein Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 13, +5 zum Treffen mit Zauberangriffen). Erbenötigt keine Gesten oder Materialkomponenten, um seine Zauber zu wirken. Der Flammenschädel hat die folgenden Magierzauber vorbereitet:

      **Zaubertricks (willentlich):** <STATBLOCK-MARKDOWN-LINK>Zauber/Magierhand-phb.md|Magierhand<STATBLOCK-MARKDOWN-LINK>

      **1. Grad (3 Plätze):** <STATBLOCK-MARKDOWN-LINK>Zauber/Magisches_Geschoss-phb|Magisches Geschoss<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Schild-phb|Schild<STATBLOCK-MARKDOWN-LINK>

      **2. Grad (2 Plätze):** <STATBLOCK-MARKDOWN-LINK>Zauber/Flammenkugel-phb|Flammenkugel<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Verschwimmen-phb|Verschwimmen<STATBLOCK-MARKDOWN-LINK>

      **3. Grad (1 Platz):** <STATBLOCK-MARKDOWN-LINK>Zauber/Feuerball-phb|Feuerball<STATBLOCK-MARKDOWN-LINK>
actions:
  - name: Mehrfachangriff
    desc: Der Flammenschädel verwendet zweimal seinen Feuerstrahl.
  - name: Feuerstrahl
    desc: "*Fernkampf-Zauberangriff:* +5 zum Treffen, Reichweite 9 m, ein Ziel. *Treffer:* 10 (3d6) Feuerschaden."
```
^statblock

## Vorkommen

Unterreich