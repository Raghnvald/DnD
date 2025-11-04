---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Bestie
Größe:
HG:
status:
image:
tags:
  - Quelle/5e/Monster_Manual
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Größe/Groß
  - Monster/Typ/Tier
aliases:
  - Giant Spider
---
```statblock
statblock: true
name: Riesenspinne
image: [[Giant-Spider.webp]]
source: Grundregelwerk
size: Groß
type: Bestie
alignment: gesinnungslos
ac: 14
hp: 26
hit_dice: 4d10 + 4
speed: 9 Meter, 9m kletternd.
stats: [14, 16, 12, 2, 11, 4]
skillsaves:
  - Heimlichkeit: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Blindsicht 3 Meter, Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: -
cr: 1
environment: Stadt, Sümpfe, Unterreich, Wüste, Wälder
bestiary: true
traits:
  - name: Netzsinn
    desc: "Solange die Spinne in Kontakt mit einem Spinnennetz ist, weiß sie genau, wo sich andere Kreaturen aufhalten, die in Kontakt mit demselben Netz sind."
    attack_bonus: 0
  - name: Netzwandler
    desc: "Die Spinne ignoriert Bewegungseinschränkungen, die durch Netze verursacht werden."
    attack_bonus: 0
  - name: Spinnenklettern
    desc: "Die Spinne kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ausführen zu müssen."
    attack_bonus: 0
actions:
  - name: Biss
    desc: "Nahkampfwaffenangriff: +5 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 7 (`1W8+3`) Stichschaden, und das Ziel muss einen SG-11-Konstitutionsrettungswurf ausführen. Scheitert der Wurf, erleidet es 9 (`2W8`) Giftschaden, anderenfalls die Hälfte. Wenn die Trefferpunkte des Ziels durch den Giftschaden auf 0 sinken, ist das Ziel stabil, aber eine Stunde lang vergiftet sowie gelähmt, selbst wenn es Trefferpunkte zurückgewinnt"
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Netz (Aufladung 5–6)
    desc: "Fernkampfwaffenangriff: +5 auf Treffer, Reichweite 9/18 m, ein Ziel. Treffer: Das Ziel ist durch das Netz festgesetzt. Als Aktion kann dasfestgesetzte Ziel einen SG-12-Stärkewurf ausführen. Bei einem Erfolg befreit es sich aus den Netzen. Das Netz kann auch angegriffen und zerstört werden (RK 10, 5 Trefferpunkte, anfällig für Feuerschaden, immun gegen Gift-, psychischen und Wuchtschaden)."
    attack_bonus: 5
```

![[picture/Giant-Spider.png|cover hsmall]]
[[picture/Giant-Spider.png|Show To Players]]

Um ihre Beute zu fangen, weben Riesenspinnen komplexe Netze oder schießen klebrige Stränge aus dem Unterleib. Riesenspinnen findet man vor allem unter der Erde, wo sie sich an der Decke oder in dunklen, mit Netzen gefüllten Spalten niederlassen. Solche Behausungen sind oft mit Netzkokons behangen, in denen frühere Opfer eingesponnen sind.