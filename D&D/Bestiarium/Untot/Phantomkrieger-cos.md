---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Phantomkrieger
Kategorie: Untoter
Größe: Mittelgroß
HG: 3
Habitat:
  - Stadt
image:
status: WIP
linter-yaml-title-alias: Phantomkrieger
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Untote
  - Quelle/5e/cos
aliases:
  - Phantom Warrior
  - Phantomkrieger
---
# Phantomkrieger
*Quellen: Fluch des Strahd S. 235*  

Ein Phantomkrieger ist der geisterhafte Überrest eines starrsinnigen Soldaten oder Ritters, der auf dem Schlachtfeld fiel oder in Ausübung seiner geschworenen Pflicht starb. Er erscheint wie eine durchscheinende Version seines lebenden Selbst.

## Aufgabengetrieben

Obwohl er oft mit einem Geist verwechselt wird, ist ein Phantomkrieger nicht von dem Wunsch erfüllt, ein unerledigtes Ziel zu erreichen. Er kann jederzeit entscheiden, seine untote Existenz zu beenden. Sein Geist bleibt aus freiem Willen zurück, entweder aus Loyalität seinem ehemaligen Herrn gegenüber oder weil er glaubt, eine Aufgabe erfüllen zu müssen um seiner Ehre oder seinem Pflichtbewusstsein zu genügen. Zum Beispiel könnte ein Wächter, der bei der Verteidigung eines Walls stirbt, als Phantomkrieger zurückkehren, weiterhin den Wall bewachen und dann für immer verschwinden, sobald ein neuer Wächter seinen Posten antritt oder der Wall zerstört wird. Der Zeitraum zwischen dem Todeszeitpunkt und dem Zeitpunkt, zu dem er sich als Phantomkrieger erhebt, beträgt üblicherweise 24 Stunden.

## Verblasste Erinnerungen

Ein Phantomkrieger behält die Gesinnung und Persönlichkeit, die er vor seinem Tod hatte, und er erinnert sich daran, wie er starb. Erinnerungen an sein Leben kurz vor seinem Tod sind verschwommen, und ältere Erinnerungen meist ganz vergessen. Ein Phantomkrieger kann sich üblicherweise an die letzten `1W10 + 10` Tage seines Lebens erinnern; alles, was vorher passierte, wird von einem undurchdringlichen Nebel verdeckt.

## Machtvolle Präsenz

Obwohl sie körperlos sind, können Phantomkrieger die Energie um sie herum nutzen, um gegen sie gerichtete Angriffe abzuwehren und mit großer Stärke zuzuschlagen. Eine [unsichtbare](/3-Mechanics/CLI/conditions.md#Invisible) Hülle aus Energie umgibt die geisterhaften Rüstungen, Schilde und Waffen eines Phantomkriegers, die hart wie Stahl werden und dennoch nicht die Fähigkeit eines Phantomkriegers beeinträchtigen, sich durch Wände und andere solide Objekte hindurchzubewegen.

Although they are incorporeal, phantom warriors can harness the energy around them to deflect incoming attacks and strike with great force. An  sheath of energy surrounds a phantom warrior's ghostly armor, shields, and weapons, which become as hard as steel yet don't impede the warrior's ability to move through walls and other solid objects.

## Untote Natur

Ein Phantomkrieger benötigt weder Luft, Nahrung, Wasser oder Schlaf.

```statblock
"name": "Phantom Warrior (CoS)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "16"
  - !!int "8"
  - !!int "10"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "any languages it knew in life"
"cr": "3"
"traits":
  - "desc": "The phantom warrior can see 60 feet into the Ethereal Plane when it is\
      \ on the Material Plane, and vice versa."
    "name": "Ethereal Sight"
  - "desc": "The phantom warrior can move through other creatures and objects as if\
      \ they were difficult terrain. It takes 5 (1d10) force damage if it ends its\
      \ turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "The phantom warrior's AC accounts for its spectral armor and shield."
    "name": "Spectral Armor and Shield"
"actions":
  - "desc": "The phantom warrior makes two attacks with its spectral longsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) force damage."
    "name": "Spectral Longsword"
  - "desc": "The phantom warrior enters the Ethereal Plane from the Material Plane,\
      \ or vice versa. It is visible on the Material Plane while it is in the Border\
      \ Ethereal, and vice versa, yet it can't affect or be affected by anything on\
      \ the other plane."
    "name": "Etherealness"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/undead/token/phantom-warrior-cos.webp"
```
^statblock

---

```statblock
statblock: true
name: Phantomkrieger
image: [[NAME.png]]
source: Fluch des Strahd
size: Mittelgroß
type: Untoter
alignment: beliebige Gesinnung
ac: 16
hp: 45
hit_dice: 6d8 + 18
speed: 9 Meter.
stats: [16, 11, 16, 8, 10, 15]
skillsaves:
  - Heimlichkeit: +4
  - Wahrnehmung: +2
damage_vulnerabilities: ""
damage_resistances: "Hieb-, Stich- und Wuchtschaden von nicht-magischen Angriffen"
damage_immunities: "Gift, Kälte, nekrotisch"
condition_immunities: "Bezaubert, Erschöpft, Festgesetzt, Gelähmt, Gepackt, Liegend, Verängstigt, Vergiftet, Versteinert"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 12
languages: Jede Sprache, die er zu Lebzeiten beherrschte
cr: 3
bestiary: true
traits:
  - name: Ätherische Sicht
    desc: Der Phantomkrieger kann 18 Meter weit in die Ätherebene blicken, wenn er sich auf der Materiellen Ebene befindet, und umgekehrt.
    attack_bonus: 0
  - name: Körperlose Bewegung
    desc: Der Phantomkrieger kann sich durch andere Kreaturen und Gegenstände bewegen, als seien sie schwieriges Gelände. Er erleidet `5 (1W10)` Energieschaden, wenn er seinen Zug in einem Gegenstand beendet.
    attack_bonus: 0
  - name: Spektrale Rüstung und spektraler Schild
    desc: Die RK des Phantomkriegers berücksichtigt seine spektrale Rüstung und seinen spektralen Schild.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Phantomkrieger führt zwei Angriffe mit seinem spektralen Langschwert aus."
    attack_bonus: 0
  - name: Spektrales Langschwert
    desc: "_Nahkampf-Waffenangriff_: +5 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: `7` (`1W8 + 3`) Energieschaden."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Körperlosigkeit
    desc: "Der Phantomkrieger kann die Ätherebene von der Materiellen Ebene aus betreten und andersherum. Er ist auf der Materiellen Ebene sichtbar, solange er sich in der Äthergrenze befindet, doch er kann nichts auf der anderen Ebene beeinflussen oder beeinflusst werden."
    attack_bonus: 0
```