---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Schwarm von Fledermäusen
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Berg
  - Hügel
  - Stadt
  - Unterreich
image:
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Berg
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
  - Monster/HG/1-4
  - Monster/Typ/Tier
  - Quelle/5e/mm
aliases:
  - Swarm of Bats
---
# Schwarm von Fledermäusen
*Quelle: Monsterhandbuch S. 336. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

> [!note] Die Natur von Schwärmen
> 
> Die Schwärme, die wir hier vorstellen, sind keine gewöhnlichen oder harmlosen Ansammlungen kleiner Tiere. Sie formen sich als Resultat eines finsteren oder schädlichen Einflusses. Ein Vampir kann Fledermausschwärme aus den dunkelsten Ecken der Nacht beschwören, und die bloße Anwesenheit eines Mumienfürsten kann dafür sorgen, dass Skarabäen aus den sandgefüllten Tiefen seiner Gruft strömen. Eine Vettel könnte die Macht besitzen, Schwärme von Raben gegen ihre Feinde zu schicken, während ein [[Yuan-ti-Scheusal-mm|Yuan-ti-Scheusal]] von [[swarm-of-poisonous-snakes|Schwärmen von giftigen Schlangen]] verfolgt werden könnte. Nicht einmal Druiden können diese Schwärme bezaubern, und ihre Aggressivität ist fast schon widernatürlich.
^the-nature-of-swarms

```statblock
name: Schwarm von Fledermäusen
image: token/swarm-of-bats.webp
source:
  - MM
size: Mittelgroßer Schwarm 
type: winzige Tiere
alignment: gesinnungslos
ac: 12
hp: 22
hit_dice: 5d8
modifier: 2
stats:
  - 5
  - 15
  - 10
  - 2
  - 12
  - 4
speed: 0 m, fliegen 9 m
damage_resistances: Hieb, Stich, Wucht
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Betäubt|Betäubt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>/Zustände-phb#bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Blindsicht|Blindsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 11
languages: ""
cr: 1/4
environment: Berg, Hügel, Stadt, Unterreich
traits:
  - name: Echolot.
    desc: Der Schwarm kann seine Blindsicht nicht verwenden, solange er <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Taub|taub<STATBLOCK-MARKDOWN-LINK> ist.
  - name: Scharfes Gehör.
    desc: Der Schwarm hat einen Vorteil bei Würfen auf Weisheit (<STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>), die mit dem Gehör zusammenhängen.
  - name: Schwarm.
    desc: Der Schwarm kann sich im Bereich einer anderen Kreatur aufhalten und andersherum. Der Schwarm kann sich durch jede Öffnung bewegen, die groß genug für eine winzige Fledermaus ist. Der Schwarm kann keine Trefferpunkte zurückerhalten und keine temporären Trefferpunkte erhalten.
actions:
  - name: Bisse.
    desc: "*Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite O m, eine Kreatur im Bereich des Schwarms. *Treffer:* 5 (2d4) Stichschaden, oder 2 (1d4) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger besitzt."
```
^statblock