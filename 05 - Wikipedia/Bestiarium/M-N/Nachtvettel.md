---
cssclasses: json5e-monster
tags:
  - Monster/Größe/Mittelgroß
  - Quelle/5e/mm
  - Monster/Typ/Unhold
aliases:
  - Night Hag
Typ: Unhold
---
# Nachtvettel

```statblock
statblock: true
name: Nachtvettel
image: [[night-hag.webp]]
source: Grundregelwerk
size: Mittel
type: Unhold
alignment: neutral böse
ac: 17
hp: 112
hit_dice: 15d8 + 45
speed: 9 Meter.
stats: [18, 15, 16, 16, 14, 16]
saves:
  - STR: +0
  - GES: +0
  - KON: +0
  - INT: +0
  - WEI: +0
  - CHA: +0
skillsaves:
  - Akrobatik: +0
  - Arkane-Kunde: +0
  - Athletik: +0
  - Auftreten: +0
  - Einschüchtern: +0
  - Fingerfertigkeit: +0
  - Geschichte: +0
  - Heilkunde: +0
  - Heimlichkeit: +6
  - Mit-Tieren-umgehen: +0
  - Motiv-erkennen: +6
  - Nachforschungen: +0
  - Naturkunde: +0
  - Religion: +0
  - Täuschen: +7
  - Überlebenskunst: +0
  - Überzeugen: +0
  - Wahrnehmung: +6
damage_vulnerabilities: ""
damage_resistances: "Feuer, Kälte; Hieb, Stich und Wucht durch nichtmagische Angriffe ohne Silber"
damage_immunities: ""
condition_immunities: "Bezaubert"
senses: Dunkelsicht 36 Meter, passive Wahrnehmung 16
languages: Abyssisch, Gemeinsprache, Infernalisch, Urtümlich
cr: 5
environment: 
bestiary: true
traits:
  - name: Magieresistenz
    desc: Die Vettel ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.
spells:
  - "Das Attribut zum angeborenen Zauberwirken der Vettel ist Charisma (Zauberrettungswurf-SG 14, +6 auf Treffer mit Zauberangriffen). Die Vettel kann folgende angeborene Zauber wirken, ohne Materialkomponenten zu benötigen:"
  - Beliebig oft: [Magie entdecken](Magie-entdecken.md), [[Magisches Geschoss]]
  - Je 2-mal täglich: [Ebenenwechsel](Ebenenwechsel.md) (nur auf sich selbst), [Schlaf](Schlaf.md), [Schwächestrahl](Schwächestrahl.md)
actions:
  - name: Klauen (nur Vettel-Gestalt)
    desc: "_Nahkampf-Waffenangriff_: +7 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 13 (2W8+4) Hiebschaden"
    attack_bonus: 7
    damage_dice: 2d8
    damage_bonus: 4
  - name: Albtraumspuk (1-mal täglich)
    desc: "Von der Ätherebene aus berührt die Vettel magisch einen schlafenden Humanoiden auf der materiellen Ebene. Der Zauber Schutz vor Gut und Böse, der auf das Ziel gewirkt wurde, verhindert diesen Kontakt ebenso wie ein Schutzkreis. Solange der Kontakt fortbesteht, hat das Ziel grässliche Visionen. Wenn diese Visionen mindestens eine Stunde lang anhalten, hat das Ziel durch seine Rast keine Vorzüge, und sein Trefferpunktemaximum ist um 5 (1W10) verringert. Verringert dieser Effekt das Trefferpunktemaximum des Ziels auf 0, so stirbt das Ziel, und sofern es böser Gesinnung war, ist seine Seele im Seelenbeutel der Vettel gefangen. Das Trefferpunktemaximum des Ziels bleibt verringert, bis der Zauber Vollständige Genesung oder ähnliche Magie auf das Ziel gewirkt wird."
  - name: Ätherische Gestalten
    desc: "Die Vettel begibt sich von der materiellen Ebene aus magisch auf die Ätherebene oder umgekehrt. Sie muss dazu einen Herzstein besitzen."
  - name: Gestalt ändern
    desc: "Die Vettel verwandelt sich magisch in einen höchstens mittelgroßen weiblichen Humanoiden oder zurück in ihre wahre Gestalt. Ihre Spielwerte sind in jeder Gestalt gleich. Ausrüstung, die sie trägt oder hält, wird nicht verwandelt. Wenn sie stirbt, nimmt sie wieder ihre wahre Gestalt an."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```

Durchtrieben und subversiv wollen Nachtvetteln sehen, wie sich das Tugendhafte in Schurkerei verwandelt: Liebe wird zu Besessenheit, Güte zu Hass, Hingabe zu Missachtung und Großzügigkeit zu Egoismus. Nachtvetteln haben eine perverse Freude daran, Sterbliche zu verderben.
$\quad$ Die Nachtvetteln waren einst Geschöpfe der Feenwelt, doch wegen ihrer Abscheulichkeit wurden sie vor langer Zeit in den Hades verbannt, wo sie zu Unholden degenerierten. Die Nachtvetteln haben sich seit langem in den unteren Ebenen ausgebreitet.

**Gegenstände der Nachtvetteln**
>Eine Nachtvettel trägt zwei sehr seltene magische Gegenstände bei sich, die sie selbst herstellen muss. Wenn einer der beiden Gegenstände verloren geht, wird die Nachtvettel alles daran setzen, ihn wiederzubekommen, denn die Herstellung eines neuen Werkzeugs kostet Zeit und Mühe.
>
>**Herzstein.** Dieser schimmernde schwarze Edelstein erlaubt es einer Nachtvettel, ätherisch zu werden, solange er in ihrem Besitz ist. Die Berührung eines Herzstein heilt außerdem jede Krankheit. Die Herstellung eines Herzstein dauert 30 Tage.
>
>**Seelenbeutel.** Wenn ein böser Humanoider durch den Alptraumspuk einer Nachtvettel stirbt, fängt die Hexe die Seele in diesem schwarzen Beutel aus genähtem Fleisch auf. Ein Seelenbeutel kann jeweils nur eine böse Seele aufnehmen, und nur die Nachtvettel, die den Sack hergestellt hat, kann eine Seele damit fangen. Für die Herstellung eines Seelenbeutels benötigt man 7 Tage und ein humanoides Opfer (dessen Fleisch für die Herstellung des Beutels verwendet wird).

**Seelenschinder.** Während ein Humanoider schläft, kann eine Nachtvettel die Person ätherisch umarmen und in ihre Träume eindringen. Jede Kreatur mit wahrer Sicht kann die geisterhafte Gestalt der Vettel sehen, die sich auf ihre Beute spannt. Die ätherische Vettel füllt den Kopf ihres Opfers mit Zweifeln und Ängsten, in der Hoffnung, es zu bösen Taten in der wachen Welt zu verleiten. Die Vettel setzt ihre nächtlichen Heimsuchungen fort, bis das Opfer schließlich im Schlaf stirbt. Wenn die Vettel ihr Opfer dazu gebracht hat, böse Taten zu begehen, fängt sie dessen verdorbene Seele in ihrem Seelenbeutel (siehe Seitenleiste „Gegenstände der Nachtvettel“) ein, um sie in den Hades zu transportieren.

**Zirkel.** Eine Nachtvettel, die Teil eines Zirkels ist (siehe die Seitenleiste „Zirkel“), hat einen Herausforderungsgrad von 7 (2.900 EP).