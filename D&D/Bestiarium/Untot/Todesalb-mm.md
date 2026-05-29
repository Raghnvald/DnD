---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Todesalb
Kategorie: Untoter
Größe: Mittelgroß
HG: 5
Habitat:
  - Unterreich
image: token/wraith.webp
status: WIP
linter-yaml-title-alias: Todesalb
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Unterreich
  - Monster/HG/5
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Todesalb
---
# Todesalb
*Quelle: Monsterhandbuch S. 285. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span>*  

Ein Todesalb ist fleischgewordene Bösartigkeit, konzentriert in eine körperlose Gestalt, die alles Leben auslöschen möchte. Die Kreatur ist von negativer Energie erfüllt, und ihr bloßes Wandern durch die Welt lässt nahe Pflanzen schwarz werden und verdorren. Tiere flüchten vor ihrer Gegenwart. Selbst kleine Feuer können durch das strudelnde Vergessen der grauenhaften Existenz des Todesalbs ausgelöscht werden.

## Abscheuliches Vergessen

Wenn ein sterblicher Humanoider ein verkommenes Leben führt oder einen unheiligen Pakt eingeht, schickt er seine Seele in die ewige Verdammnis in den Unteren Ebenen. Manchmal jedoch wird die Seele so sehr von negativer Energie erfüllt, dass sie in sich zusammenfällt und aufhört, zu existieren, in dem Augenblick, ehe sie in ein schreckliches Leben nach dem Tod übergehen kann. Wenn es dazu kommt, wird der Geist ein seelenloser Todesalb - eine bösartige Leere, die auf der Ebene, auf der sie gestorben ist, gefangen ist. So gut wie nichts von der ehemaligen Existenz des· Todesalbs bleibt bestehen; in seiner neuen Gestalt existiert er nur, um das Leben anderer auszulöschen.

## Eines Körpers beraubt

Ein Todesalb kann sich durch feste Kreaturen und Gegenstände bewegen, so mühelos wie sterbli- . ehe Kreaturen durch Nebel.

Ein Todesalb könnte einige Erinnerungen an sein sterbliches Leben als schattenhafte Echos bewahren. Allerdings werden selbst die stärksten Ereignisse und Empfindungen wenig mehr als schwache Eindrücke, so flüchtig wie halb vergessene Träume. Ein Todesalb könnte innehalten, um etwas anzustarren, das ihn im Leben faszinierte, oder er könnte seinen Zorn zügeln, um eine vergangene Freundschaft zu ehren. Solche Augenblicke sind aber selten, da die meisten Todesalben das, was sie waren, verachten, weil es sie daran erinnert, was sie geworden sind.

## Untote Anführer

Ein Todesalb kann untote Diener aus den Geistern von humanoiden Kreaturen erschaffen, die kürzlich einen gewalttätigen Tod erlitten haben. Solche Fragmente des Leides werden zu Schreckgespenstern, die alles verabscheuen, was lebt.

Todesalben regieren manchmal über die Legionen der Toten und planen den Untergang von lebenden Wesen. Wenn sie aus ihren Gräbern steigen, um in die Schlacht zu ziehen, verdorren Leben und Hoffnung vor ihnen. Selbst wenn die Armeen eines Todesalbs gezwungen werden, sich zurückzuziehen, ist das Land, das seine Truppen besetzt haben, so zersprengt und verdorrt, dass jene, die dort leben, oft verhungern und sterben.

## Untote Natur

Ein Todesalb muss nicht atmen, essen, trinken oder schlafen.

```statblock
name: Todesalb
image: token/wraith.webp
source:
  - MM
size: Mittelgroß
type: Untoter
alignment: Neutral Böse
ac: 13
hp: 67
hit_dice: 9d8 + 27
modifier: 3
stats:
  - 6
  - 16
  - 16
  - 12
  - 14
  - 15
speed: 0 ft., fly 60 ft. (hover)
damage_resistances: Blitz, Feuer, Kälte, Säure, Schall; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe, die nicht von versilberten Waffen zugefügt werden.
damage_immunities: Gift, nekrotisch
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 12
languages: die Sprachen, die er im Leben kannte
cr: "5"
environment: Unterreich
traits:
  - name: Körperlose Bewegung
    desc: "Der Todesalb kann sich durch andere Kreaturen und Gegenstände bewegen als seien sie schwieriges Gelände. Er erleidet 5 (1d10) Energieschaden, wenn er seinen Zug in einem Gegenstand beendet."
  - name: Empfindlich gegenüber Sonnenlicht
    desc: "Solange sich der Todesalb im Sonnenlicht befindet, hat er einen Nachteil bei Angriffswürfen und Würfen auf Weisheit (<STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>), die Sicht verwenden."
actions:
  - name: Lebensentzug
    desc: "*Nahkampf-Waffenangriff:* +6 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 21 (4d8 + 3) nekrotischer Schaden. Das Ziel muss einen Konstitutionsrettungswurf gegen SG 14 ablegen, sonst werden seine maximalen Trefferpunkte um den erlittenen Schaden verringert. Diese Verringerung hält an, bis das Ziel eine lange Rast beendet. Das Ziel stirbt, wenn dieser Effekt es aufO maximale Trefferpunkte reduziert."
  - name: Schreckgespenst erschaffen
    desc: "Der Todesalb wählt einen Humaneiden innerhalb von 3 m aus, der nicht länger als 1 Minute tot ist und einen gewalttätigen Tod .erlitten hat. Der Geist des Ziels erhebt sich als <STATBLOCK-MARKDOWN-LINK>Schreckgespenst-mm|Schreckgespenst<STATBLOCK-MARKDOWN-LINK> im Bereich seines Leichnams oder im nächsten nicht besetzten Bereich. Das <STATBLOCK-MARKDOWN-LINK>Schreckgespenst-mm|Schreckgespenst<STATBLOCK-MARKDOWN-LINK> steht unter der Kontrolle des Todesalbs. Der Todesalb kann nicht mehr als sieben Schreckgespenster auf einmal unter seiner Kontrolle haben."
```
^statblock