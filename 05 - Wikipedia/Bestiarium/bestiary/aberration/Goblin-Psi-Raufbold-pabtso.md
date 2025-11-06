---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/2
  - Monster/Größe/Klein
  - Monster/Typ/Aberration/Goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Goblin Psi Brawler
---
# Goblin Psi Brawler
*Source: Phandelver and Below: The Shattered Obelisk p. 215*  

Goblin‑Psi‑Raufbolde setzen ihre psionischen Talente ein, um ihre körperliche Stärke zu erhöhen. Ihre Schläge knistern vor psychischer Energie, und wenn sie wütend sind, können Goblin‑Psi‑Raufbolde einen telekinetischen Stoß entfesseln, der stark genug ist, um Feinde zu Boden zu werfen.

## Psionische Goblins

Wie ein psionischer Goblin entsteht, variiert. Manche werden geboren, verändert durch Energie, die aus dem Ferne Reich (Far Realm) leckt. Andere verwandeln sich selbst mithilfe ihrer psionischen Macht oder schließen Abkommen mit anderen Aberrationen, die ihnen im Gegenzug für ihren Dienst als Stoßtruppen bei der Transformation helfen. Unabhängig davon ist das Ergebnis dasselbe: ein Goblin mit unnatürlicher und kaum beherrschbarer psychischer Kraft.

Psionische Goblins kämpfen oft damit, die turbulente psychische Energie in ihrem Geist und Körper zu kontrollieren. Diejenigen, die lernen, diese psychische Macht sicher zu nutzen, werden zu furchterregenden Kämpfern. Psionische Goblins verstärken ihre Kampffähigkeiten häufig mit Telekinese, und heimliche Trupps psionischer Goblin‑Krieger können über Telepathie kommunizieren – das macht sie zu hervorragenden Infiltratoren und Hinterhaltern.

```statblock
statblock: true
name: Goblin-Psi-Raufbold
image: [[Goblin Psi Brawler.webp]]
source: Phandelver & Below
size: Klein
type: Aberration
subtype: goblinoid
alignment: jede Gesinnung
ac: 15 (Beschlagenes Leder)
hp: 31
hit_dice: 7d6 + 7
speed: 9 Meter.
stats: [9, 17, 12, 16, 15, 10]
skillsaves:
  - Heimlichkeit: 7
damage_vulnerabilities: ""
damage_resistances: "psychisch"
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 12
languages: Gemeinsprache, Goblin, Telepathie 9 Meter
cr: 2
bestiary: true
traits:
  - name: Flinkes Entkommen
    desc: "Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen."
    attack_bonus: 0
  - name: Telekinetischer Stoß
    desc: "Der Goblin zielt mit einem Stoß telekinetischer Kraft auf eine Kreatur im Umkreis von 9 Metern, die er sehen kann. Das Ziel muss einen Rettungswurf auf Stärke (SG 13) bestehen oder sich in den Zustand Liegen begeben."
    attack_bonus: 0
  - name: Mentaler Ausbruch
    desc: "Wenn der Goblin stirbt, explodiert seine aufgestaute mentale Energie in einer psychischen Explosion. Jede Kreatur im Umkreis von 1,5 Metern muss einen Rettungswurf auf Intelligenz (SG 13) bestehen oder `5` (`2W4`) psychischen Schaden erleiden."
    attack_bonus: 0
  - name: Mentale Widerstandskraft
    desc: "Der Goblin hat einen Vorteil bei Rettungswürfen gegen Effekte, die ihn in den Zustand der Verzauberung oder Angst versetzen würden."
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt zwei waffenlose Angriffe aus."
  - name: Waffenloser Angriff
    desc: "Nahkampfangriff: +5 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: `5` (`1W4 + 3`) Hiebschaden plus `3` (`1W6`) psychischer Schaden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 3
reactions:
  - name: Angriff umlenken
    desc: "Wenn der Goblin von einer Kreatur angegriffen wird, die er sehen kann, wählt der Goblin einen anderen Goblin im Umkreis von 1,5 Metern. Die beiden Goblins tauschen ihre Positionen und der gewählte Goblin wird stattdessen zum Ziel."
```

---

```statblock
"name": "Goblin Psi Brawler (PaBTSO)"
"size": "Small"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[studded leather armor](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "31"
"hit_dice": "7d6 + 7"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "17"
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "psychic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Goblin, telepathy 30 ft."
"cr": "2"
"traits":
  - "desc": "When the goblin dies, its pent-up mental energy explodes in a psychic\
      \ blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence\
      \ saving throw or take 5 (2d4) psychic damage."
    "name": "Mental Burst"
  - "desc": "The goblin has advantage on saving throws against effects that would\
      \ make it have the [charmed](/3-Mechanics/CLI/conditions.md#Charmed) or [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition."
    "name": "Mental Fortitude"
"actions":
  - "desc": "The goblin makes two Unarmed Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) bludgeoning damage plus 3 (1d6) psychic damage."
    "name": "Unarmed Strike"
"bonus_actions":
  - "desc": "The goblin takes the Disengage or Hide action."
    "name": "Nimble Escape"
  - "desc": "The goblin targets one creature it can see within 30 feet of itself with\
      \ a thrust of telekinetic force. The target must succeed on a DC 13 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Telekinetic Shove"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/goblin-psi-brawler-pabtso.webp"
```
^statblock