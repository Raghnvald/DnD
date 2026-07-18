---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Beobachter
Kategorie: Aberration
Größe: Mittelgroß
HG: 3
Habitat:
  - Unterreich
Status: WIP
linter-yaml-title-alias: Beobachter
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Unterreich
  - Monster/HG/3
  - Monster/Typ/Aberration
  - Quelle/5e/mm
aliases:
  - Beobachter
  - Spectator
image: token/spectator.webp
status: completed
---
# Beobachter
*Quelle: Monsterhandbuch S. 28. Verfügbar im Grundregelwerk (2014)*  

Ein Beobachter ist ein geringerer Betrachter, der mit einem magischen Ritual von einer anderen Existenzebene beschworen wird. Zu den Komponenten des Rituals gehören vier Betrachter-Augenstiele, die von der Magie des Rituals verbraucht werden. Entsprechend hat ein Beobachter vier Augenstiele, zwei an jeder Seite des breiten Auges in der Mitte eines Körpers mit 1,2 m Durchmesser.

## Magische Wächter

Ein beschworener Beobachter bewacht für 101 Jahre einen Ort oder Schatz nach Wahl des Beschwörers. Er erlaubt es keiner Kreatur außer dem Beschwörer, den Ort zu betreten oder Zugang zum Gegenstand zu erhalten, es sei denn, der Beschwörer gibt anderweitige Anweisungen. Wenn der Gegenstand gestohlen oder zerstört wird, ehe alle Jahre verstrichen sind, verschwindet der Beobachter. Ansonsten verlässt er niemals seinen Posten.

## Durchblitzender Wahnsinn

Auch wenn er sprechen kann, kommuniziert ein Beobachter vor allem durch Telepathie. Er ist höflich, solange er Wache hält, und diskutiert offen seine Anweisungen und seinen Beschwörer. Allerdings reicht eine kurze Unterhaltung mit einem Beobachter aus, um die Macken in seiner Persönlichkeit zu offenbaren, die denJahren der Isolation entspringen. Er könnte imaginäre Feinde erfinden, über sich selbst in der dritten Person sprechen oder versuchen, die Stimme seines Beschwörers nachzuahmen.

$\quad$Wie jeder Betrachter sieht sich der Beobachter als Inbegriff seiner Art und hat einen intensiven Hass auf andere Beobachter. Wenn sich zwei Beobachter begegnen, kämpfen sie fast immer bis zum Tod.

## Vom Dienst befreit

Wenn ein Beobachter seinen Dienst erfüllt hat, kann er tun, was er möchte. Viele lassen sich an dem Ort nieder, den sie zuvor bewacht haben, besonders, wenn ihr Beschwörer gestorben ist. Da der Beobachter nun keinen Daseinszweck mehr hat, kann der Wahnsinn, den er schon während seiner Knechtschaft zeigte, noch weiter gedeihen.

```statblock
name: Beobachter
image: token/spectator.webp
source:
  - MM
size: Mittelgroß
type: Aberration
alignment: Rechtschaffen böse
ac: 14
ac_class: natürliche Rüstung
hp: 39
hit_dice: 6d8 + 12
modifier: 2
stats:
  - 8
  - 14
  - 14
  - 13
  - 14
  - 11
speed: 0 m, fliegen 9 m (schweben)
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+6"
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Liegend|Liegend<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 36 m, passive Wahrnehmung 16
languages: Tiefensprache, Gemeinsprache der Unterreiche, Telepathie 36 m
cr: 3
actions:
  - name: Biss
    desc: "*Nahkampf-Waffenangriff:* +1 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 2 (1d6-1) Stichschaden."
  - name: Augenstrahlen
    desc: |-
      Der Beobachter schießt bis zu zwei der folgenden magischen Augenstrahlen auf eine oder zwei Kreaturen innerhalb von 27 m, die er sehen kann. Er kann jeden Augenstrahl nur einmal pro Zug verwenden.

      - **1. Verwirrungsstrahl.** Das Ziel muss einen `Weisheitsrettungswurf` gegen `SG 13` schaffen, sonst kann es bis zum Ende seines nächsten Zugs keine Reaktionen verwenden. In seinem Zug kann sich das Ziel nicht bewegen und verwendet seine Aktion, um einen Nahkampf- oder Fernkampfangriff gegen eine zufällige Kreatur in Reichweite auszuführen. Wenn das Ziel nicht angreifen kann, tut es in seinem Zug nichts. 
      - **2. Lähmender Strahl.** Die Zielkreatur muss einen `Konstitutionsrettungswurf` gegen `SG 13` ablegen, um nicht für 1 Minute <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gelähmt|Gelähmt<STATBLOCK-MARKDOWN-LINK> zu werden. Das Ziel kann den Rettungswurf am Ende eines jeden seiner Züge wiederholen und den Effekt bei einem Erfolg beenden.  
      - **3. Furchtstrahl.** Die Zielkreatur muss einen `Weisheitsrettungswurf` gegen `SG 13` ablegen, um nicht für 1 Minute <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|Verängstigt<STATBLOCK-MARKDOWN-LINK> zu werden. Das Ziel kann den Rettungswurf am Ende eines jeden seiner Züge wiederholen und den Effekt bei einem Erfolg beenden. Dabei erleidet es einen Nachteil, wenn der Beobachter für das Ziel noch sichtbar ist.  
      - **4. Verwundender Strahl.** Das Ziel muss einen `Konstitutionsrettungswurf` gegen `SG 13` ablegen. Bei einem misslungenen Rettungswurf erleidet es 16 (3d10) nekrotischen Schaden, halb so viel Schaden bei einem erfolgreichen Rettungswurf.
  - name: Nahrung und Wasser erschaffen
    desc: Der Beobachter erschafft auf magische Weise genug Nahrung und Wasser, um sich selbst für 24 Stunden zu ernähren.
reactions:
  - name: Zauberspiegelung
    desc: Wenn der Beobachter einen erfolgreichen Rettungswurf gegen einen Zauber ausführt oder wenn ein Zauberangriff ihn verfehlt, kann der Beobachter eine Kreatur innerhalb von 9 m auswählen, die er sehen kann (auch den Zauberwirker). Der Zauber trifft die ausgewählte Kreatur anstelle des Beobachters. Wenn der Zauber einen Rettungswurf erzwungen hat, legt die Kreatur ihren eigenen Rettungswurf ab. Wenn der Zauber ein Angriff war, wird der Angriffswurf gegen die gewählte Kreatur wiederholt.
```
^statblock

## Vorkommen

Unterreich