---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Wassergeist
Kategorie: Elementar
Größe: Groß
HG: 3
Habitat:
  - Stadt
  - Unterreich
image: Elementar/img/water-weird.webp
status: completed
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
  - Monster/HG/3
  - Monster/Typ/Elementar
  - Quelle/5e/mm
aliases:
  - Water Weird
---
# Wassergeist
*Quelle: Monsterhandbuch S. 300*  

Ein Wassergeist ist ein elementarer Wächter, der an einen bestimmten mit Wasser gefüllten Ort gebunden ist, wie einen Tümpel oder einen Brunnen. Er ist unsichtbar, solange er sich im Wasser befindet. Seine schlangenhafte Gestalt wird nur sichtbar, wenn er hervorkommt, um anzugreifen. Dabei verwendet er seine Windungen, um jede Kreatur zu zerquetschen, mit Ausnahme des Beschwörers und all jener, die der Beschwörer als tabu bestimmt hat. Wenn ein Wassergeist erschlagen wird, wird er zu einem leblosen Wassertümpel.

## Gute und böse Wassergeister

Wie die meisten Elementare haben Wassergeister keine Vorstellung von Gut und Böse. Allerdings beginnt ein Wassergeist, der an eine heilige oder verderbte Wasserquelle gebunden ist, das Wesen des Ortes anzunehmen und wird neutral gut oder neutral böse.

Ein neutral guter Wassergeist versucht, Eindringlinge zu verscheuchen anstatt sie zu töten, während ein neutral böser Wassergeist seine Opfer zum Vergnügen tötet und sich gegen seinen Beschwörer wenden könnte. Ein Wassergeist verliert seine böse Gesinnung, wenn sein Wasser mit dem Zauber [[Nahrung_und_Wasser_reinigen-phb|Nahrung und Wasser reinigen]] gereinigt wird

## Elementare Natur

Ein Wassergeist muss nicht atmen, essen, trinken oder schlafen.

> [!quote] Die 2. Regel des Überlebens im Gewölbe von X dem Mystiker
> Ehe du aus einem Brunnen oder Tümpel trinkst, wirf eine Kupfermünze hinein. Dies ist ein kleiner Preis, den du für dein Überleben bezahlst. 

```statblock
name: Wassergeist
image: Elementar/token/water-weird.webp
source:
  - MM
size: Groß
type: Elementar
alignment: Neutral
ac: 13
hp: 58
hit_dice: 9d10 + 9
modifier: 3
stats:
  - 17
  - 16
  - 13
  - 11
  - 10
  - 10
speed: 0 m, schwimmen 18 m
damage_resistances: Feuer; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe 
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bewusstlos|bewusstlos<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>/Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Blindsicht|Blindsicht<STATBLOCK-MARKDOWN-LINK> 9 m, passive Wahrnehmung 10
languages: Versteht Aqual, kann aber nicht sprechen
cr: "3"
environment: Stadt, Unterreich
traits:
  - name: Unsichtbar im Wasser.  
    desc: Der Wassergeist is <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Unsichtbar|Unsichtbar<STATBLOCK-MARKDOWN-LINK>, solange er voll im Wasser untergetaucht ist
  - name: Wassergebunden
    desc: Der Wassergeist stirbt, wenn er das Wasser verlässt, an das er gebunden ist, oder wenn dieses Wasser zerstört wird. 
actions:
  - name: Umschlingen
    desc: "*Nahkampf-Waffenangriff:* +5 zum Treffen, Reichweite 3 m, eine Kreatur. *Treffer:* 13 (3d6 + 3) Wuchtschaden. Wenn das Ziel mittelgroß oder kleiner ist, wird es <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> (SG zum Entkommen 13) und 1,5 min Richtung des Wassergeists gezogen. Bis der Haltegriff endet, ist das Ziel <STATBLOCK-MARKDOWN-LINK>Zustände-phb#festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, der Wassergeist versucht es zu ertränken, und der Wassergeist kann kein anderes Ziel umschlingen."
```
^statblock

---

> [!statblock] Wassergeist
> ![[Elementar/token/water-weird.webp|right|100]]
> *Großer Elementar, neutral*
> 
> - **Rüstungsklasse** 13
> - **Trefferpunkte** 58 (`dice: 9d10+9|render`)
> - **Bewegungsrate** 0 m, schwimmen 18 m
> 
> |STR|GES|KON|INT|WEI|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 17 (+3)|16 (+3)|13 (+1)|11 (+0)|10 (+0)|10 (+0)|
> 
> - **Übungsbonus** +2
> - **Sinne** Blindsicht 9 m, passive Wahrnehmung 10
> - **Schadensresistenzen** Feuer; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe
> - **Schadensimmunitäten** Gift
> - **Zustandsimmunitäten** Bewusstlos, [[Zustände-phb#Erschöpfung|erschöpft]], festgesetzt, gelähmt, gepackt, liegend, vergiftet  <br> <br>
> - **Sprachen** Versteht Aqual, kann aber nicht sprechen
> - **Herausforderungsgrad** 3 (700 EP)
> 
> ## Merkmale
> 
> **_Unsichtbar im Wasser._** Der Wassergeist ist unsichtbar, solange er voll im Wasser untergetaucht ist.
> 
> 
> **_Wassergebunden._** Der Wassergeist stirbt, wenn er das Wasser verlässt, an das er gebunden ist, oder wenn dieses Wasser zerstört wird. 
> 
> ## Aktionen
> 
> ***Umschlingen.*** *Nahkampf-Waffenangriff:* +5 zum Treffen, Reichweite 3 m, eine Kreatur. *Treffer*: 13 (`3W6 + 3`) Wuchtschaden. Wenn das Ziel mittelgroß oder kleiner ist, wird es gepackt (SG zum Entkommen 13) und 1,5 min Richtung des Wassergeists gezogen. Bis der Haltegriff endet, ist das Ziel festgesetzt, der Wassergeist versucht es zu ertränken, und der Wassergeist kann kein anderes Ziel umschlingen
^statblock

## Vorkommen
Stadt, Unterreich