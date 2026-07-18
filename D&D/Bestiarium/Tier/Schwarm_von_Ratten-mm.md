---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Schwarm von Ratten
Kategorie: Tier
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Stadt
  - Sumpf
Status: WIP
linter-yaml-title-alias: Schwarm von Ratten
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/HG/1-4
  - Monster/Typ/Tier
  - Quelle/5e/mm
aliases:
  - Schwarm von Ratten
  - Swarm of Rats
image:
status:
---
# Schwarm von Ratten
*Quelle: Monsterhandbuch S. 336. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

> [!note] Die Natur von Schwärmen
> 
> Die Schwärme, die wir hier vorstellen, sind keine gewöhnlichen oder harmlosen Ansammlungen kleiner Tiere. Sie formen sich als Resultat eines finsteren oder schädlichen Einflusses. Ein Vampir kann Fledermausschwärme aus den dunkelsten Ecken der Nacht beschwören, und die bloße Anwesenheit eines Mumienfürsten kann dafür sorgen, dass Skarabäen aus den sandgefüllten Tiefen seiner Gruft strömen. Eine Vettel könnte die Macht besitzen, Schwärme von Raben gegen ihre Feinde zu schicken, während ein [[Yuan-ti-Scheusal-mm|Yuan-ti-Scheusal]] von [[swarm-of-poisonous-snakes|Schwärmen von giftigen Schlangen]] verfolgt werden könnte. Nicht einmal Druiden können diese Schwärme bezaubern, und ihre Aggressivität ist fast schon widernatürlich.
^the-nature-of-swarms

```statblock
name: Schwarm von Ratten
image: token/swarm-of-rats.webp
source:
  - MM
size: Mittelgroßer Schwarm
type: winzige Tiere
alignment: gesinnungslos
ac: 10
hp: 24
hit_dice: 7d8 - 7
modifier: 0
stats:
  - 9
  - 11
  - 9
  - 2
  - 10
  - 3
speed: 9 m
damage_resistances: Hieb, Stich, Wucht
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Betäubt|Betäubt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 9 m, passive Wahrnehmung 10
languages: ""
cr: 1/4
environment: Stadt, Sumpf
traits:
  - name: Scharfer Geruchssinn
    desc: Der Schwarm hat einen Vorteil bei Würfen auf Weisheit (<STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>), die mit dem Geruchssinn zusammenhängen.
  - name: Schwarm
    desc: Der Schwarm kann sich im Bereich einer anderen Kreatur aufhalten und andersherum. Der Schwarm kann sich durch jede Öffnung bewegen, die groß genug für eine winzige Ratte ist. Der Schwarm kann keine Trefferpunkte zurückerhalten und keine temporären Trefferpunkte erhalten.
actions:
  - name: Biss
    desc: "*Nahkampf-Waffenangriff:* +2, Reichweite 0 m, ein Ziel im Bereich des Schwarms. *Treffer:* 7 (2d6) Stichschaden oder 3 (1d6) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger besitzt."
```
^statblock