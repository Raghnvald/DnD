---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Feenwesen (Goblinoid)
Größe: Klein
HG:
Habitat:
  - Grasland
  - Hügel
  - Planar (Acheron)
  - Planar (Fernwildnis)
  - Unterreich
  - Wald
status: WIP
image:
tags: [Quelle/5e/mm]
aliases: [Goblin Warrior]
---
# Goblins (2024)
_Wilde Gauner und Störenfriede_

>**Habitat:** Grasland, Hügel, Planar (Acheron, Feenwildnis), Unterreich, Wald
>**Beute:** Werkzeuge, Individuell

![](group-of-goblins-2024.png)

Goblins sind die Feywild-Verkörperung von Rücksichtslosigkeit und Ruin. Sie haben Freude am Zerstören - je lauter, je energischer und je verworrener, desto besser. Goblinüberfälle sind oft ebenso eine Gelegenheit, Feuer zu legen und das Vieh zu quälen, wie sie Teil eines störenden Plans sind.

Goblins gehorchen denen, die die wildesten Pläne verwirklichen. Solche Anführer können Goblin-Überfallkommandanten, bombastische Magieanwender oder diejenigen sein, die den lautesten Krach machen können. Hobgoblins und kräftige Humanoide können auch ungestüme Gruppen von Goblins anführen und deren Zerstörungswut auf Banditentum, Sabotage oder Krieg lenken.

Die Gottheit Maglubiyet behauptet, der Gott der Goblins, Hobgoblins und Käferbären zu sein, und auf dem Unendlichen Schlachtfeld von [[Acheron]] befehligt die Gottheit unzählige Goblinoiden-Legionen. In längst vergangenen Zeiten wurde Maglubiyet Zeuge der Zerstörungswut der Goblinoiden und siedelte eine Population von ihnen aus dem Feenreich in sein Reich in den Äußeren Ebenen um. Seitdem haben sich Horden dieser eher kriegerisch gesinnten Goblins ausgebreitet, von denen einige ihren Weg auf die Welten der Materiellen Ebene gefunden haben. Diese bösartigen Eindringlinge versuchen, als Vorbereitung auf die Eroberung durch ihren Gott Verderben zu säen.

>[!Quote] Ungefähre Übersetzung von Goblin zu Common: "Hey, Trottel!"
>Bree-yark!

## Goblinschergen
Die Goblinschergen beteiligen sich gerne an den störenden Plänen kluger Anführer, fliehen aber schnell, wenn sie mit ihrer Strafe konfrontiert werden.

```statblock
name: Goblinscherge
size: Klein
type: Fee
subtype: (Goblinoid),
alignment: Chaotisch neutral
ac: 12
hp: 7
hit_dice: 2d6
ini: +2 (12)
speed: 9 Meter.
stats: [8, 15, 10, 10, 8, 8]
saves:
  - STR: -1
  - GES: +2
  - KON: +0
  - INT: +0
  - WEI: -1
  - CHA: -1
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [[Dolch]] (3)
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 9
languages: Gemeinsprache, Goblin
cr: 1/8
bestiary: true
actions:
  - name: Dolch
    desc: "_Nahkampf- oder Fernkampfangriff:_ +4, Reichweite 1,5m oder 6m/18m. _Treffer:_ 4 (1d4 + 2) Stichschaden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
bonus_actions:
  - name: Flinkes Entkommen
    desc: Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen.
```

## Goblinkrieger
Goblinkrieger sind besonders gut darin, Unheil zu stiften. Diejenigen, die im Dienste von Maglubiyet stehen, sind disziplinierter und ziehen sich eher zurück, um Hinterhalte zu legen.

```statblock
name: Goblinkrieger
size: Klein
type: Fee
subtype: (Goblinoid),
alignment: Chaotisch neutral
ac: 15
hp: 10
hit_dice: 3d6
ini: +2 (12)
speed: 9 Meter.
stats: [8, 15, 10, 10, 8, 8]
saves:
  - STR: -1
  - GES: +2
  - KON: +0
  - INT: +0
  - WEI: -1
  - CHA: -1
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [[Kurzbogen]], [[Krummsäbel]], [[Lederrüstung]], [[Schild]]
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 9
languages: Gemeinsprache, Goblin
cr: 1/4
bestiary: true
actions:
  - name: Krummsäbel
    desc: "_Nahkampfangriff:_ +4, Reichweite 1,5m. _Treffer:_ 5 (1d6 + 2) Hiebschaden plus 2 (1d4) Hiebschaden wenn der Angriff im Vorteil ist."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Kurzbogen
    desc: "_Fernkampfangriff:_ +4, Reichweite 24m/96m. _Treffer:_ 5 (1d6 + 2) Stichschaden plus 2 (1d4) Stichschaden wenn der Angriff im Vorteil ist"
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
bonus_actions:
  - name: Flinkes Entkommen
    desc: Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen.
```

## Goblinanführer
Goblinanführer sind oft die einfallsreichsten, störendsten oder energischsten Goblins. Durch eine Kombination aus Glück, Feigheit und Gefühllosigkeit vermeiden diese Anführer Schaden auf Kosten ihrer Gefolgsleute.

```statblock
name: Goblinanführer
size: Klein
type: Fee
subtype: (Goblinoid),
alignment: Chaotisch neutral
ac: 17
hp: 21
hit_dice: 6d6
ini: +2 (12)
speed: 9 Meter.
stats: [10, 15, 10, 10, 8, 10]
saves:
  - STR: +0
  - GES: +2
  - KON: +0
  - INT: +0
  - WEI: -1
  - CHA: +0
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
gear: [[Kettenhemd]], [[Kurzbogen]], [[Krummsäbel]], [[Schild]]
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 9
languages: Gemeinsprache, Goblin
cr: 1
bestiary: true
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt zwei Angriffe mit Krummsäbel oder Kurzbogen aus, in beliebiger Kombination"
  - name: Krummsäbel
    desc: "_Nahkampfangriff:_ +4, Reichweite 1,5m. _Treffer:_ 5 (1d6 + 2) Hiebschaden plus 2 (1d4) Hiebschaden wenn der Angriff im Vorteil ist."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Kurzbogen
    desc: "_Fernkampfangriff:_ +4, Reichweite 24m/96m. _Treffer:_ 5 (`1W6 + 2`) Stichschaden plus 2 (1d4) Stichschaden wenn der Angriff im Vorteil ist"
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
bonus_actions:
  - name: Flinkes Entkommen
    desc: Der Goblin kann in jedem seiner Züge die Aktion Rückzug oder Verstecken als Bonusaktion ausführen.
reactions:
  - name: Angriff umlenken
    desc: "_Auslöser:_ Eine Kreatur, die der Goblin sehen kann, macht einen Angriffswurf gegen ihn. _Reaktion:_ Der Goblin wählt einen kleinen oder mittleren Verbündeten im Umkreis von 1,5m um sich selbst. Der Goblin und dieser Verbündete tauschen die Plätze, und der Verbündete wird stattdessen zum Ziel des Angriffs."
```

## Goblinhexer
Goblinhexer verwenden auffällige und störende Magie. Viele Goblinhexer sind theatralisch, kleiden sich und verhalten sich in übertriebener Nachahmung von Erzmagiern.

```statblock
name: Goblinscherge
size: Klein
type: Fee
subtype: (Goblinoid),
alignment: Chaotisch neutral
ac: 13
hp: 45
hit_dice: 10d6 +10
ini: +3 (13)
speed: 9 Meter.
stats: [8, 16, 12, 16, 10, 10]
saves:
  - STR: -1
  - GES: +3
  - KON: +1
  - INT: +3
  - WEI: +0
  - CHA: +0
skillsaves:
  - Fingerfertigkeit: 5
  - Heimlichkeit: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache, Goblin
cr: 3
bestiary: true
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt zwei Angriffe mit dem Hexenstecken aus. Ein Angriff kann durch einen Zauber ausgetauscht werden."
  - name: Hexenstecken
    desc: "_Nahkampf- oder Fernkampfangriff:_ +5, Reichweite 1,5m oder 18m. _Treffer:_ 12 (2d8 + 3) Psychischer Schaden."
    attack_bonus: 5
    damage_dice: 2d8
    damage_bonus: 3
spells:
  - "Der Goblin wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 13):"
  - "- Willentlich: [Einfache Illusion](Einfache-Illusion.md)"
  - "- 1/pro Tag jeweils: [Blindheit/Taubheit](Blindheit-Taubheit.md), [Feenfeuer](Faerie-Fire.md), [Schmieren](Schmieren.md)"
reactions:
  - name: Verhexen
    desc: "_Auslöser:_ Eine Kreatur, die der Goblin sehen kann, trifft ihn mit einem Angriffswurf. _Reaktion:_ Weisheits-Rettungswurf SG 13, die auslösende Kreatur. _Fehlschlag:_ Der Angriff geht daneben."
```


## Versteck
Ihre bauartigen Höhlen sind durch Alarmsysteme vor Eindringlingen geschützt. Meist graben sie kleine Fluchttunnel, die mittelgroße Humanoide nicht passieren können. Diese nutzen sie aber auch für Überraschungsangriffe.

## Beute
**Rostiges Kurzschwert**: Dieses kleine, ramponierte Schwert wird oft von Goblins benutzt. Bei einem Treffer muss eine Kreatur einen KON-Rettungswurf SG 10 schaffen oder ist eine Stunde lang vergiftet. Ist der Effekt beendet, ist die Kreatur 24 Stunden lang immun gegen den Effekt.
**Giftkelch**: Dieser kleine, silberne Kelch ist mit einfachem Gift gefüllt. Ein schlauer Goblin bietet seinen Feinden unterwürfig diesen Kelch als Geschenk an, um sie zu vergiften. Sobald der Kelch mit Gift gefüllt ist, muss eine Kreatur bei einem Treffer einen KON-Rettungswurf SG 10 bestehen oder erleidet 2 (1w4) Giftschaden.