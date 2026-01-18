---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Mittelgroß
HG: 1
Habitat:
  - Stadt
  - Sumpf
  - Unterreich
status: completed
image: image/ghoul.webp
tags:
  - Quelle/5e/mm
  - Monster/Typ/Untote
  - Monster/Größe/Mittelgroß
  - Monster/HG/1
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ghoul
---
# Ghul
*Quelle: Monsterhandbuch S. 133. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Ghule streifen in Rudeln durch die Nacht, angetrieben von einem unstillbaren Hunger nach dem Fleisch von Humanoiden.

## Verschlinger des Fleisches 

Wie Maden oder Aaskäfer gedeihen Ghule an Orten des Verfalls und Todes. Ghule suchen Orte heim, wo sie sich mit totem Fleisch und verwesenden Organen mästen können. Wenn sie nicht das Fleisch der Toten verschlingen können, verfolgen sie lebende Kreaturen und versuchen, sie zu Leichen zu machen. Auch wenn sie von den Leichen, die sie verschlingen, nicht ernährt werden, sind Ghule doch von einem endlosen Hunger angetrieben, der sie antreibt, weiter zu fressen. Das untote Fleisch eines Ghuls verwest niemals, und das Monster kann für unzählige Zeitalter in einer Gruft überleben, ohne zu fressen.

## Abyssische Herkunft

Ghuls stammen aus dem Abyss. Doresain, der erste ihrer Art, war ein elfischer Anhänger des Orcus. Er wandte sich gegen sein Volk und verzehrte das Fleisch von Humanoiden, um den Dämonenprinz des Untodes zu ehren. Als Belohnung für seine Dienste verwandelte Orcus Doresain in den ersten Ghul. Doresain diente Orcus treu im Abyss und erschuf Ghule aus den anderen Dienern des Dämonenfürsten, bis eine Invasion von Yeenoghu, dem dämonischen Gnollfürsten, Doresain seine abyssische Domäne kostete. Als Orcus nicht für ihn eingreifen wollte, wandte sich Doresain an die elfischen Götter und bat um Hilfe. Sie hatten Mitleid mit ihm und halfen ihm dabei, der sicheren Zerstörung zu entkommen. Seitdem sind Elfen immun gegen die lähmende Berührung der Ghule.

## Grule

Orcus erfüllt einen Ghul manchmal mit einer größeren Dosis abyssischer Energie, um einen Grul zu erschaffen. Wo Ghule kaum mehr als wilde Bestien sind, sind Grule gerissen und können ein Rudel von Ghulen dazu bringen, ihren Befehlen zu folgen.

```statblock
name: Ghul
image: token/ghoul.webp
source: MM
size: Mittelgroß
type: Untoter
alignment: chaotisch böse
ac: 12
hp: 22
hit_dice: 5d8
modifier: 2
stats:
  - 13
  - 15
  - 10
  - 7
  - 10
  - 6
speed: 9 Meter
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Erschöpft|Erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|Vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache
cr: 1
actions:
  - name: Biss
    desc: "*Nahkampf-Waffenangriff:* +2 zum Treffer, Reichweite 1,5 m, ein Ziel. *Treffer:* 9 (2d6+2) Stichschaden."
  - name: Klauen
    desc: "*Nahkampf-Waffenangriff:* +4 zum Treffer, Reichweite 1,5 m, ein Ziel. *Treffer:* 7 (2d4+2) Hiebschaden. Wenn das Ziel eine Kreatur und kein Elf oder Untoter ist, muss es einen Konstitutionsrettungswurf gegen SG 10 ablegen, um nicht für 1 Minute <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK> zu werden. Das Ziel kann den gleichen Rettungswurf am Ende eines jeden seiner Züge wiederholen und den Effekt auf sich selbst bei einem Erfolg beenden."
```
^statblock

## Environment

underdark, swamp, urban