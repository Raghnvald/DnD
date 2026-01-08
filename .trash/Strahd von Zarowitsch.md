---
 token/count_strahd_von_zarovich_token.webp
tags: [Quelle/5e/cos]
aliases: [Strahd, Strahd von Zarowitsch]
---

# Strahd von Zarowitsch









## Hortaktionen
Während Strahd sich in der Burg Ravenloft aufhält und er nicht kampfunfähig ist, kann er Hortaktionen ausführen. 

$\quad$ Bei Initiative 20 (er verliert Initiative-Gleichstände) kann Strahd eine der folgenden möglichen Hortaktionen auswählen oder darauf verzichten, sie in dieser Runde zu benutzen.
- Bis Initiative 20 der nächsten Runde kann Strahd durch solide Wände, Türen, Decken und Böden gehen, als ob sie nicht existieren.
- Strahd wählt eine beliebige Anzahl von Türen und Fenstern, die er sehen kann, als Ziel, und bringt alle dazu, sich nach seinen Wünschen entweder zu öffnen oder zu schließen. Geschlossene Türen können auf magische Weise verriegelt werden (sie benötigen einen gelungenen <font color="red">**Stärkewurf**</font> gegen <font color="orange">SG 20</font>, um aufgestemmt zu werden), bis Strahd entscheidet, den Effekt zu beenden oder bis Strahd diese Hortaktion wieder ausführt.
- Strahd ruft den wütenden Geist von jemandem herbei, der in der Burg gestorben ist. Die Erscheinung taucht neben einer feindlichen Kreatur auf, die Strahd sehen kann, führt einen Angriff gegen diese Kreatur aus und verschwindet dann. Die Erscheinung hat die Spielwerte eines [[Schreckgespenst-old]].
- Strahd wählt eine mittelgroße oder kleine Kreatur als Ziel aus, die einen Schatten wirft. Der Schatten des Ziels muss für Strahd sichtbar und höchstens 9 Meter von ihm entfernt sein. Wenn dem Ziel ein <font color="darkviolet">**Charisma**</font>-<font color="#FF00E0">Rettungswurf</font> gegen <font color="yellow">SG 17</font> misslingt, löst sich der Schatten von ihm und wird zu einem [Schatten](Schatten.md), der Strahds Befehle befolgt und bei Initiative 20 handelt. Ein auf das Ziel gewirkter Zauber _[[Vollständige Genesung]]_ oder _[[Fluch brechen]]_ stellt seinen natürlichen Schatten wieder her, aber nur, wenn sein untoter Schatten zerstört wurde.



## DragnaCarta CoS Reloaded


### Phase 1

```statblock
name: Strahd, der Magier
layout: Basic 5e German Layout
image: [[count_strahd_von_zarovich_token.webp]]
source: DragnaCarta's Curse of Strahd Reloaded
size: Mittelgroß
type: Untoter (Gestaltwandler)
alignment: rechtschaffen böse
ac: 16
hp: 331
hit_dice: 39d8 + 156
ini: +5 (15)
speed: 12 m
stats: [20, 20, 18, 20, 15, 20]
saves:
- GES: 12
- WEI: 9
- CHA: 12
skillsaves:
- arkane kunde: 19
- athletik: 12
- heimlichkeit: 19
- motiv erkennen: 9
- religion: 12
- täuschung: 19
- wahrnehmung: 16
damage_resistances: nekrotisch; Wucht‑, Stich‑ und Hiebschaden von nichtmagischen Waffen
senses: Dunkelsicht 36 m; passive Wahrnehmung 24
languages: Abgründisch, Drakonisch, Elfisch, Gemeinsprache, Infernalisch, Riesisch
cr: 21
bestiary: true
traits:
  - name: Komplexes Zauberwirken
    desc: "Wenn Strahd in seinem Zug einen Zauber als Bonusaktion wirkt, kann er zusätzlich seine Aktion nutzen, um einen Zauber des Grades 1 oder höher zu wirken."
  - name: Regeneration
    desc: "Strahd erhält zu Beginn seines Zuges 20 TP zurück, wenn er mindestens 1 Trefferpunkt besitzt und sich nicht im Sonnenlicht oder in fließendem Wasser befindet. Wenn er gleißenden Schaden oder Schaden durch Weihwasser erleidet, funktioniert dieses Merkmal zu Beginn von Strahds nächstem Zugs nicht."
  - name: Spinnenklettern
    desc: "Strahd kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen. Seine Hände bleiben dabei frei."
    attack_bonus: 0
  - name: Vampirschwächen
    desc: "Strahd hat die folgenden Nachteile: <br> **_Verbot._** Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. <br> **_Verletzt durch fließendes Wasser._** Strahd erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. <br> **_Pflock ins Herz._** Wenn eine Stichwaffe aus Holz ins Herz Strahds getrieben wird, solange er sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird. <br> **_Hyperempfindlich gegenüber Sonnenlicht._** Strahd erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
    attack_bonus: 0
spells:
  - "Strahd ist ein Zauberwirker der 9. Stufe (Attribut Intelligenz, Zauberrettungswurf-SG 18, +10 zum Treffen mit Zauberangriffen). Strahd kann die folgenden Zauber wirken:"
  - je 3-mal täglich: [Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Untote erschaffen](Untote-erschaffen.md)
  - je 1-mal täglich: [Ausspähung](Ausspähung.md)
actions:
  - name: Mehrfachangriff
    desc: "Strahd verwendet zweimal **_Vampirische Berührung_** oder einmal **_Vampirische Berührung_** und einmal **_Telekinetischer Griff_**."
  - name: Vampirische Berührung
    desc: "**_Nahkampfangriff:_** +12 zum Treffen, Reichweite 1,5 m, ein Ziel. **_Rettungswurf:_** SG 20, Konstitution. Bei Misserfolg ist das Ziel bis zum Beginn von Strahds nächstem Zug benommen (kann sich entweder bewegen ODER eine Aktion ausführen, jedoch nicht beides; keine Bonusaktion oder Reaktion)."
    attack_bonus: 12
  - name: Telekinetischer Griff
    desc: "**_Transmutation des 2. Grades_**, **_Reichweite:_** 18 m, **_Komponenten:_** verbal, somatisch, materiell, **_Dauer:_** 1 Runde. **_Rettungswurf:_** SG 20, Stärke. Bei Misserfolg schwebt das Ziel bis zu 6 m vertikal, bleibt dort bis zum Beginn von Strahds nächstem Zug, erleidet 7 (2d6) nekrotischen Schaden und ist bis zum Ende von Strahds nächstem Zug [[Anhang PH-A#Festgesetzt|festgesetzt]]. Wenn der Effekt endet, fällt das Ziel zu Boden, falls es noch in der Luft ist."
    damage_dice: 2d6
  - name: Magie bannen
    desc: "Strahd kann bis zu dreimal pro Tag den Zauber *[Magie bannen](Magie-bannen.md)* wirken."
bonus_actions:
  - name: Kreis der Krankheit
    desc: "**_Nekromantie des 3. Grades_**, **_Reichweite:_** Selbst, **_Komponenten:_** verbal, somatisch, materiell. Eine Sphäre negativer Energie entspringt Strahd. Jede Kreatur im Umkreis von 3 m muss einen Rettungswurf (SG 20, Konstitution) ablegen. Bei Misserfolg erleidet die Kreatur 28 (8d6) nekrotischen Schaden und hat Nachteil beim nächsten Angriffswurf bis zum Ende ihres nächsten Zuges. Bei Erfolg erleidet das Ziel halben Schaden und erhält keinen Nachteil."
  - name: Blitz
    desc: "Strahd wirkt [Blitz](Blitz.md) (SG 20)"
reactions:
  - name: 
    desc: "Strahd kann bis zu drei Reaktionen pro Runde einsetzen, jedoch jeweils nur eine pro Zug. Wenn er seine Reaktion verlieren würde und nicht kampfunfähig ist, verliert er lediglich eine seiner Reaktionen."
  - name: Unbezwingbar
    desc: "**_Auslöser:_** Eine feindliche Kreatur beendet ihren Zug. <br> **_Effekt:_** Strahd kann den Rettungswurf gegen einen Effekt oder Zustand, der ihn betrifft, wiederholen."
  - name: Nebelschritt
    desc: "Als Reaktion auf erlittenen Schaden wirkt Strahd [Nebelschritt](Nebelschritt.md)."
  - name: Blindheit/Taubheit
    desc: "Als Reaktion auf Schaden durch einen Nahkampfangriff wirkt Strahd [Blindheit/Taubheit](Blindheit-Taubheit.md) (SG 20) gegen den Angreifer. Bei einem misslungenen Rettungswurf erleidet das Ziel zusätzlich 7 (2d6) nekrotischen Schaden."
lair_actions:
  - name: 
    desc: "Wenn Strahd im Freien ist und die Spieler den Sumpffane noch nicht wieder geweiht haben, kann er zu Beginn des 20. Initiativzählers (bei Gleichstand verliert er die Initiative) eine der folgenden Aktionen ausführen oder darauf verzichten:"
  - name: Wasser kontrollieren  (erfordert Sumpffane)
    desc: "Strahd wirkt [Wasser kontrollieren](Wasser-kontrollieren.md) ohne Komponenten oder Konzentration."
  - name: Nebelwolke (erfordert Sumpffane)
    desc: "Strahd wirkt [Nebelwolke](Nebelwolke.md) auf Stufe 5 ohne Komponenten oder Konzentration. Solange der Nebel besteht, besitzt Strahd [[08-Abenteuersuche#Lichtverhältnisse und Sicht|Blindsicht]] bis zum Rand des Nebels"
```

### Phase 2

```statblock
name: Strahd, der Soldat
layout: Basic 5e German Layout
image: [[count_strahd_von_zarovich_token.webp]]
source: DragnaCarta's Curse of Strahd Reloaded
size: Mittelgroß
type: Untoter (Gestaltwandler)
alignment: rechtschaffen böse
ac: 16
hp: 331
hit_dice: 39d8 + 156
ini: +5 (15)
speed: 12 m
stats: [20, 20, 18, 20, 15, 20]
saves:
- GES: 12
- WEI: 9
- CHA: 12
skillsaves:
- arkane kunde: 19
- athletik: 12
- heimlichkeit: 19
- motiv erkennen: 9
- religion: 12
- täuschung: 19
- wahrnehmung: 16
damage_resistances: nekrotisch; Wucht‑, Stich‑ und Hiebschaden von nichtmagischen Waffen
senses: Dunkelsicht 36 m; passive Wahrnehmung 24
languages: Abgründisch, Drakonisch, Elfisch, Gemeinsprache, Infernalisch, Riesisch
cr: 21
bestiary: true
traits:
  - name: Kampfbewusstsein
    desc: "Strahd ist bei Rettungswürfen auf Stärke und Geschicklichkeit gegen Effekte, die er sehen oder hören kann (z. B. Fallen, Zauber) im Vorteil und kann nicht entwaffnet werden."
  - name: Regeneration
    desc: "Strahd erhält zu Beginn seines Zuges 20 TP zurück, wenn er mindestens 1 Trefferpunkt besitzt und sich nicht im Sonnenlicht oder in fließendem Wasser befindet. Wenn er gleißenden Schaden oder Schaden durch Weihwasser erleidet, funktioniert dieses Merkmal zu Beginn von Strahds nächstem Zugs nicht."
  - name: Spinnenklettern
    desc: "Strahd kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen. Seine Hände bleiben dabei frei."
    attack_bonus: 0
  - name: Vampirschwächen
    desc: "Strahd hat die folgenden Nachteile: <br> **_Verbot._** Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. <br> **_Verletzt durch fließendes Wasser._** Strahd erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. <br> **_Pflock ins Herz._** Wenn eine Stichwaffe aus Holz ins Herz Strahds getrieben wird, solange er sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird. <br> **_Hyperempfindlich gegenüber Sonnenlicht._** Strahd erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
actions:
  - name: Mehrfachangriff
    desc: "Strahd führt zwei Angriffe aus; höchstens einer davon kann **_Schattennetz_** sein"
  - name: Langschwert
    desc: "**Nahkampfangriff:** +12 zum Treffen, Reichweite 1,5 m, ein Ziel. **Treffer:** 8 (1d10+5) Hiebschaden + 7 (2d6) nekrotischer Schaden. Das Ziel muss einen Rettungswurf (SG 20, Stärke) bestehen, sonst wird es 1,5m zurückgestoßen und erhält den Status [[Anhang PH-A#Liegend|Liegend]]."
    attack_bonus: 12
    damage_dice: 1d10
    damage_bonus: 5
  - name: Schattennetz
    desc: "**Fernkampfzauber:** +12 zum Treffen, Reichweite 9/18 m, ein Ziel. **Treffer:** 7 (2d6) nekrotischer Schaden; das Ziel ist bis zum Beginn von Strahds nächstem Zug [[Anhang PH-A#Festgesetzt|festgesetzt]]."
    attack_bonus: 12
    damage_dice: 2d6
    damage_bonus: 0
bonus_actions:
  - name: Donnernde Welle
    desc: "Strahd schlägt mit seiner Schwertspitze auf den Boden und erzeugt eine Schockwelle. Jede Kreatur im Umkreis von 1,5 m muss einen Rettungswurf (SG 20, Stärke) ablegen. Bei einem Misserfolg erleidet die Kreatur 13 (3d8) Donnerschaden und wird 1,5 m zurückgestoßen. Bei Erfolg halbiert sich der Schaden und das Ziel wird nicht gestoßen."
  - name: Dunkle Salve
    desc: "Strahd beschwört einen Regen aus schattenhaften Pfeilen, die auf einen Punkt innerhalb von 36 m gerichtet sind. Jede Kreatur innerhalb eines Zylinders von 3 m Radius und 12 m Höhe muss einen Rettungswurf (SG 20, Geschicklichkeit) ablegen, sonst erleidet sie 17 (4d8) nekrotischen Schaden; bei Erfolg halbiert sich der Schaden."
reactions:
  - name: 
    desc: "Strahd kann bis zu drei Reaktionen pro Runde einsetzen, jedoch jeweils nur eine pro Zug. Wenn er seine Reaktion verlieren würde und nicht kampfunfähig ist, verliert er lediglich eine seiner Reaktionen."
  - name: Unbezwingbar
    desc: "**_Auslöser:_** Eine feindliche Kreatur beendet ihren Zug. <br> **_Effekt:_** Strahd kann den Rettungswurf gegen einen Effekt oder Zustand, der ihn betrifft, wiederholen."
  - name: Kommandantenrückzug
    desc: "Als Reaktion auf Schaden durch einen Nahkampfangriff zwingt Strahd den Angreifer, einen Rettungswurf (SG 20, Stärke) zu bestehen, sonst wird er 1,5 m zurückgestoßen. Anschließend kann Strahd sich bis zu seiner Bewegungsrate vom Angreifer entfernen, ohne Gelegenheitsangriffe zu provozieren."
  - name: Rachsüchtiger Schlag
    desc: "Als Reaktion auf Schaden durch einen Zauber oder Angriff bewegt sich Strahd bis zu seiner Geschwindigkeit auf den Angreifer zu und kann einen Langschwertangriff gegen ihn ausführen. Diese Bewegung löst keine Gelegenheitsangriffe aus."
lair_actions:
  - name: 
    desc: "Wenn Strahd im Freien ist und die Spieler den Waldfane noch nicht wieder geweiht haben, kann er zu Beginn des 20. Initiativzählers (bei Gleichstand verliert er die Initiative) eine der folgenden Aktionen ausführen oder darauf verzichten:"
  - name: Pflanzenwachstum  (erfordert Waldfane)
    desc: "Strahd wirkt [Pflanzenwachstum](Pflanzenwachstum.md) ohne Komponenten oder Konzentration."
  - name: Zorn der Natur (erfordert Waldfane)
    desc: "Strahd wirkt [Zorn der Natur](Zorn-der-Natur.md) ohne Komponenten oder Konzentration (Steine‑Effekt entfällt)."
```

### Phase 3

```statblock
name: Strahd, der Vampir
layout: Basic 5e German Layout
image: [[count_strahd_von_zarovich_token.webp]]
source: DragnaCarta's Curse of Strahd Reloaded
size: Mittelgroß
type: Untoter (Gestaltwandler)
alignment: rechtschaffen böse
ac: 16
hp: 331
hit_dice: 39d8 + 156
ini: +5 (15)
speed: 12 m
stats: [20, 20, 18, 20, 15, 20]
saves:
- GES: 12
- WEI: 9
- CHA: 12
skillsaves:
- arkane kunde: 19
- athletik: 12
- heimlichkeit: 19
- motiv erkennen: 9
- religion: 12
- täuschung: 19
- wahrnehmung: 16
damage_resistances: nekrotisch; Wucht‑, Stich‑ und Hiebschaden von nichtmagischen Waffen
senses: Dunkelsicht 36 m; passive Wahrnehmung 24
languages: Abgründisch, Drakonisch, Elfisch, Gemeinsprache, Infernalisch, Riesisch
cr: 21
bestiary: true
traits:
  - name: Kampfbewusstsein
    desc: "Strahd ist bei Rettungswürfen auf Stärke und Geschicklichkeit gegen Effekte, die er sehen oder hören kann (z. B. Fallen, Zauber) im Vorteil und kann nicht entwaffnet werden."
  - name: Regeneration
    desc: "Strahd erhält zu Beginn seines Zuges 20 TP zurück, wenn er mindestens 1 Trefferpunkt besitzt und sich nicht im Sonnenlicht oder in fließendem Wasser befindet. Wenn er gleißenden Schaden oder Schaden durch Weihwasser erleidet, funktioniert dieses Merkmal zu Beginn von Strahds nächstem Zugs nicht."
  - name: Spinnenklettern
    desc: "Strahd kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen. Seine Hände bleiben dabei frei."
    attack_bonus: 0
  - name: Vampirschwächen
    desc: "Strahd hat die folgenden Nachteile: <br> **_Verbot._** Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. <br> **_Verletzt durch fließendes Wasser._** Strahd erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. <br> **_Pflock ins Herz._** Wenn eine Stichwaffe aus Holz ins Herz Strahds getrieben wird, solange er sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird. <br> **_Hyperempfindlich gegenüber Sonnenlicht._** Strahd erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
actions:
  - name: Mehrfachangriff
    desc: "Strahd führt zwei Angriffe aus; höchstens einer davon kann ein Biss sein. Er kann einen seiner Angriffe durch einen Charme ersetzen."
  - name: Unbewaffneter Schlag
    desc: "**Nahkampfangriff:** +12 zum Treffen, Reichweite 1,5 m, ein Ziel. **Treffer:** 7 (1d8+5) Hiebschaden + 13 (4d6) nekrotischer Schaden. Trifft er ein Wesen, kann Strahd es greifen (Flucht‑SG 20)"
    attack_bonus: 12
    damage_dice: 1d8
    damage_bonus: 5
  - name: Biss
    desc: "**Nahkampfangriff:** +12 zum Treffen, Reichweite 1,5 m, ein williges Ziel oder ein von Strahd [[Anhang PH-A#Gepackt|gepacktes]], [[Anhang PH-A#Kampfunfähig|kampfunfähiges]] oder [[Anhang PH-A#Festgesetzt|festgesetztes]] Ziel. **Treffer:** 8 (1d6+5) Stichschaden + 10 (3d6) nekrotischer Schaden. Das maximale Trefferpunktekontingent des Ziels wird um den nekrotischen Schaden reduziert; Strahd heilt um denselben Betrag. Reduziert sich das Maximum auf 0, stirbt das Ziel. Ein humanoides Ziel, das auf 0 reduziert wurde, erhebt sich beim nächsten Sonnenuntergang als Vampir‑Spawn unter Strahds Kontrolle."
    attack_bonus: 12
    damage_dice: 1d6
    damage_bonus: 5
  - name: Charme
    desc: "**Reichweite:** 9 m, Sichtkontakt. Ziel muss einen Weisheitsrettungswurf (SG 20) bestehen, sonst ist es 1  Minute lang verzaubert. Ein Ziel, das Strahd nicht sehen kann, besteht automatisch. Verzauberte Ziele sehen Strahd als vertrauenswürdigen Freund, folgen seinen Bitten und lassen sich von ihm beißen. Das Ziel kann am Ende jedes Zuges den Rettungswurf wiederholen; bei Erfolg endet der Effekt. Bleibt das Ziel nach Ablauf der Minute verzaubert, hält der Effekt 24 Stunden, bis Strahd zerstört wird oder er eine Bonusaktion nutzt, um ihn zu beenden."
bonus_actions:
  - name: Raserei der Fledermäuse
    desc: "Strahd beschwört einen Schwarm schattenhafter Fledermaus‑Gestalten. Jede Kreatur im Umkreis von 3 m muss einen Geschicklichkeitsrettungswurf (SG 20) bestehen, sonst erleidet sie 13 (6d4) nekrotischen Schaden und hat Nachteil beim nächsten Angriffswurf bis zum Beginn von Strahds nächstem Zug. Bei Erfolg halbiert sich der Schaden und der Nachteil wird nicht verliehen."
  - name: Wut des Jägers
    desc: "Strahd ruft ein paar wolfsartiger Schatten herbei und wählt bis zu zwei Ziele, die er innerhalb von 18 m sehen kann und die höchstens 1,5 m voneinander entfernt stehen. Jeder muss einen Geschicklichkeitsrettungswurf (SG 20) bestehen, sonst erleidet er 13 (2d10 + 5) Schallschaden und wird zu Boden geworfen. Bei Erfolg halbiert sich der Schaden und das Ziel bleibt stehen."
reactions:
  - name: 
    desc: "Strahd kann bis zu drei Reaktionen pro Runde einsetzen, jedoch jeweils nur eine pro Zug. Wenn er seine Reaktion verlieren würde und nicht kampfunfähig ist, verliert er lediglich eine seiner Reaktionen."
  - name: Unbezwingbar
    desc: "**_Auslöser:_** Eine feindliche Kreatur beendet ihren Zug. <br> **_Effekt:_** Strahd kann den Rettungswurf gegen einen Effekt oder Zustand, der ihn betrifft, wiederholen."
  - name: Rückzug der Nacht
    desc: "Als Reaktion auf erlittenen Schaden kann Strahd bis zu seiner Bewegungsrate fliegend (ohne Gelegenheitsangriffe) ausweichen. Wenn eine oder mehrere Kreaturen Strahd gepackt haben löst er diese Griffe."
  - name: Blutrausch
    desc: "Als Reaktion auf erlittenen Schaden kann Strahd bis zu seiner Bewegungsrate auf den Angreifer zulaufen und einen unbewaffneten Schlag ausführen."
lair_actions:
  - name: 
    desc: "Wenn Strahd im Freien ist und die Spieler den Waldfane noch nicht wieder geweiht haben, kann er zu Beginn des 20. Initiativzählers (bei Gleichstand verliert er die Initiative) eine der folgenden Aktionen ausführen oder darauf verzichten:"
  - name: Wetter ändern (erfordert Bergfane)
    desc: "Strahd wirkt [Wetterkontrolle](Wetterkontrolle.md) als Aktion, ohne Konzentration oder Komponenten, und kann beliebige Wetterbedingungen nach Belieben anpassen."
  - name: Blitz herbeirufen (erfordert Bergfane)
    desc: "Strahd wirkt [Blitz herbeirufen](Blitze-herbeirufen.md) ohne Komponenten oder Konzentration. Während eines Sturms verursacht jeder Blitzwurf maximalen Schaden, anstatt zu würfeln."
```