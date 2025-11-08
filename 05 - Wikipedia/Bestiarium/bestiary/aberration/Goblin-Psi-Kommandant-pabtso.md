---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/4
  - Monster/Größe/Klein
  - Monster/Typ/Aberration/Goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Goblin Psi Commander
---
# Goblin Psi Commander
*Source: Phandelver and Below: The Shattered Obelisk p. 216*  

Goblin‑Psi‑Kommandanten gehören zu den wenigen psionischen Goblins, die es schaffen, die Kraft in sich vollständig zu kontrollieren. Erwacht zur vollen Breite ihrer psionischen Fähigkeiten, schwingen Goblin‑Psi‑Kommandanten Klingen reiner psychischer Energie. Sie können Barrieren aus mentaler Kraft erzeugen und Gegner mit einem einzigen, geistzerreißenden Stoß zu Fall bringen.

## Psionische Goblins

Wie ein psionischer Goblin entsteht, variiert. Manche werden geboren, verändert durch Energie, die aus dem Ferne Reich (Far Realm) leckt. Andere verwandeln sich selbst mithilfe ihrer psionischen Macht oder schließen Abkommen mit anderen Aberrationen, die ihnen im Gegenzug für ihren Dienst als Stoßtruppen bei der Transformation helfen. Unabhängig davon ist das Ergebnis dasselbe: ein Goblin mit unnatürlicher und kaum beherrschbarer psychischer Kraft.

Psionische Goblins kämpfen oft damit, die turbulente psychische Energie in ihrem Geist und Körper zu kontrollieren. Diejenigen, die lernen, diese psychische Macht sicher zu nutzen, werden zu furchterregenden Kämpfern. Psionische Goblins verstärken ihre Kampffähigkeiten häufig mit Telekinese, und heimliche Trupps psionischer Goblin‑Krieger können über Telepathie kommunizieren – das macht sie zu hervorragenden Infiltratoren und Hinterhaltern.

```statblock
statblock: true
name: Goblin-Psi-Kommandant
image: [[Goblin Psi Commander.webp]]
source: Phandelver & Below
size: Klein
type: Aberration
subtype: goblinoid
alignment: jede Gesinnung
ac: 16 (Beschlagenes Leder)
hp: 58
hit_dice: 13d6 + 13
speed: 9 Meter.
stats: [12, 19, 13, 17, 15, 10]
skillsaves:
  - Heimlichkeit: 8
damage_vulnerabilities: ""
damage_resistances: "psychisch"
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 12
languages: Gemeinsprache, Goblin
cr: 4
bestiary: true
traits:
  - name: Flinkes Entkommen
    desc: "Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen."
  - name: Psionischer Schild
    desc: "Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen."
    attack_bonus: 0
  - name: Mentaler Ausbruch
    desc: "Wenn der Goblin stirbt, explodiert seine aufgestaute mentale Energie in einer psychischen Explosion. Jede Kreatur im Umkreis von 1,5 Metern muss einen Rettungswurf auf Intelligenz (SG 13) bestehen oder `5` (`2W4`) psychischen Schaden erleiden."
    attack_bonus: 0
  - name: Mentale Widerstandskraft
    desc: "Der Goblin hat einen Vorteil bei Rettungswürfen gegen Effekte, die ihn in den Zustand der Verzauberung oder Angst versetzen würden."
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt drei Angriffe mit psychischen Klingen aus."
    attack_bonus: 0
  - name: Psychische Klinge
    desc: "Nahkampf- oder Fernkampfangriff: +6 zum Treffen, Reichweite 1,5m oder 18m, ein Ziel. Treffer: 11 (2W6 + 4) psychischer Schaden und das Ziel muss 1W4 von seinem nächsten Angriffs- oder Rettungswurf abziehen, bevor der Goblin seinen nächsten Zug beendet."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
spells:
  - "(Psionisch) Der Goblin wirkt einen der folgenden Zauber, die keine Zauberkomponenten benötigen und Intelligenz als Zauberattribut verwenden (Zauberrettungswurf SG 13):"
  - Nach Belieben: [[Magierhand.md|Magierhand]] (die Hand ist unsichtbar), [[minor-illusion.md|Einfache Illusion]]
  - Je 1/Tag: [[Person-bezaubern|Person berzaubern]], [[Dissonantes-Flüstern.md|Dissonantes Flüstern]], [[telekinesis.md|Telekinese]]
```

---

```statblock
"name": "Goblin Psi Commander (PaBTSO)"
"size": "Small"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather armor](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "13d6 + 13"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "19"
  - !!int "13"
  - !!int "17"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "psychic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Goblin, telepathy 60 ft."
"cr": "4"
"traits":
  - "desc": "When the goblin dies, its pent-up mental energy explodes in a psychic\
      \ blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence\
      \ saving throw or take 10 (4d4) psychic damage."
    "name": "Mental Burst"
  - "desc": "The goblin has advantage on saving throws against effects that would\
      \ make it have the [charmed](/3-Mechanics/CLI/conditions.md#Charmed) or [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ conditions."
    "name": "Mental Fortitude"
"actions":
  - "desc": "The goblin makes three Psychic Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 60\
      \ ft., one creature. *Hit:* 11 (2d6 + 4) psychic damage, and the target must\
      \ subtract 1d4 from the next attack roll or saving throw it makes before the\
      \ end of the goblin's next turn."
    "name": "Psychic Blade"
  - "desc": "The goblin unleashes a 30-foot-radius sphere of psychic energy, centered\
      \ on a point the goblin can see within 60 feet of itself. Each creature in that\
      \ area must make a DC 13 Intelligence saving throw. On a failed save, a creature\
      \ takes 14 (4d6) psychic damage and has the [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of the goblin's next turn. On a successful save, a\
      \ creature takes half as much damage only."
    "name": "Synaptic Rend (Recharge 5-6)"
  - "desc": "The goblin casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand\
      \ is invisible), [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\
      \n**1/day each:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [dissonant whispers](/3-Mechanics/CLI/spells/dissonant-whispers-xphb.md),\
      \ [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The goblin takes the Disengage or Hide action."
    "name": "Nimble Escape"
"reactions":
  - "desc": "When the goblin or one of its allies within 15 feet of it is hit by an\
      \ attack roll, the goblin conjures a shield of force. The target of the attack\
      \ gains a +3 bonus to its AC against the triggering attack roll, potentially\
      \ causing it to miss."
    "name": "Psionic Shield"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/goblin-psi-commander-pabtso.webp"
```
^statblock