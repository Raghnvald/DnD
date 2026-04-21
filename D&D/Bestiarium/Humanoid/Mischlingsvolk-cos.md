---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Mongrelfolk
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-4
  - Monster/Typ/Humanoid/mongrelfolk
  - Quelle/5e/cos
aliases:
  - Mongrelfolk
---
# Mongrelfolk
*Source: Curse of Strahd p. 234*  

Das Mischlingsvolk sind Humanoiden, die oder deren Vor- fahren in einem solchen Ausmaß fürchterliche magische Transformationen erlitten haben, dass sie nur einen Bruchteil ihres ursprünglichen Wesens behielten. Ihre humanoiden Körper vereinigen die Merkmale verschiedener Tiere. Zum Beispiel könnte ein Angehöriger des Mischlingsvolks die Körpergrundform eines Zwergs mit einem Kopf haben, der die Merkmale einer Katze und einer Echse verbindet, einen Arm, der in einer Krabbenschere endet und ein Bein, das in einen gespaltenen Huf mündet. Ein anderer könnte die Haut und Hörner einer Kuh aufweisen, die Augen einer Spinne, die Schenkel eines Froschs und ein en schuppigen Echsenschwanz. Die blasphemische Verbindung von humanoiden und Tiergestalten jedes Angehörigen des Mischlingsvolks führte dazu, dass er einen langsamen, unbeholfenen Gang hat.

## Geräuschnachahmung

Angehörige des Mischlingsvolks haben fehlgebildete Münder und Stimmbänder. Sie sprechen die Gemeinsprache gebrochen, gemischt mit verschiedenen Tierschreien und Gebrabbel. Sie können effektiv Geräusche von Tieren und Humanoiden nachahmen, die sie gehört haben. Das Mischlingsvolk ist nicht hochentwickelt genug, um diese Geräusche als eine verdeckte Form der Verständigung zu nutzen, aber es kann die Geräusche nutzen, um Feinde in eine Falle zu locken oder abzulenken.

## Ausgestoßene

Angehörige des Mischlingsvolks sind selten in anderen humanoiden Gesellschaften willkommen, wo sie misshandelt, versklavt oder gemieden werden. Sie leben typischerweise an den Rändern der Zivilisation in Ruinen, verlassenen Gebäuden oder anderen Orten, die humanoide Völker einst bewohnt oder gebaut haben. Sie tendieren außerhalb ihrer Heimstätten dazu, zaghaft und nervös zu sein und zeigen innerhalb ihrer Verstecke heftiges Territorialverhalten.

## Tarnungsexperten

Angehörige des Mischlingsvolks verstecken ihre Missbildungen oft unter Mänteln- und Kapuzen. Auf diese Art können sie manchmal als stämmige Menschen oder dünne Zwerge durchgehen. Sie mögen Tarnung gern, und befestigen Blätter und Zweige an ihren Mänteln, mischen braune Farbe, um ihre Haut zu bestreichen und weben Grasnetze, unter denen sie sich verstecken. Sie nutzen solche Tarnung auf der Jagd in der Wildnis oder während sie vor ihren Heimstätten Wache halten. Ein Angehöriger des Mischlingsvolks genießt einen Vorteil bei Heimlichkeitswürfen zum Verstecken.

## Fürchterliche Abkömmlinge

Es ist möglich, die ursprüngliche Gestalt eines ursprünglichen Angehörigen des Mischlingsvolks mittels des Zaubers [Vollständige Genesung](Zauber/Vollständige-Genesung.md) wiederherzustellen, doch gleiches kann nicht für dessen Nachfahren gesagt werden. Als Mischlingsvolk geborene Kreaturen stellen eine eigene Rasse dar und sich nicht die Leidtragenden eines Zaubers oder Effekts, der rückgängig gemacht werden kann.

$\quad$ Das Mischlingsvolk kann sich mit anderen Humanoiden fortpflanzen, aber beinahe alle Kinder, die solchen Eltern geboren werden, gehören wiederum zum Mischlingsvolk. (Etwa eines von hundert Kindern wird mit dem Aussehen seines Nichtmischlingsvolk-Elternteils geboren.)

```statblock
"name": "Mongrelfolk (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "mongrelfolk"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "-1"
"stats":
  - !!int "12"
  - !!int "9"
  - !!int "15"
  - !!int "9"
  - !!int "10"
  - !!int "6"
"speed": "20 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+2"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/4"
"traits":
  - "desc": "The mongrelfolk has one of the following extraordinary features, determined\
      \ randomly by rolling a d20 or chosen by the DM:\n\n1–3: Amphibious. The mongrelfolk\
      \ can breathe air and water.\n\n4–9: Darkvision. The mongrelfolk has darkvision\
      \ out to a range of 60 feet.\n\n10: Flight. The mongrelfolk has leathery wings\
      \ and a flying speed of 40 feet.\n\n11–15: Keen Hearing and Smell. The mongrelfolk\
      \ has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on hearing or smell.\n\n16–17: Spider Climb. The mongrelfolk\
      \ can climb difficult surfaces, including upside down on ceilings, without needing\
      \ to make an ability check.\n\n18–19: Standing Leap. The mongrelfolk's long\
      \ jump is up to 20 feet and its high jump up to 10 feet, with or without a running\
      \ start.\n\n20: Two-Headed. The mongrelfolk has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks and on saving throws against being [blinded](/3-Mechanics/CLI/conditions.md#Blinded),\
      \ [charmed](/3-Mechanics/CLI/conditions.md#Charmed), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [stunned](/3-Mechanics/CLI/conditions.md#Stunned),\
      \ or knocked [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)."
    "name": "Extraordinary Feature"
  - "desc": "The mongrelfolk can mimic any sounds it has heard, including voices.\
      \ A creature that hears the sounds can tell they are imitations with a successful\
      \ DC 12 Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight)) check."
    "name": "Mimicry"
"actions":
  - "desc": "The mongrelfolk makes two attacks: one with its bite and one with its\
      \ claw or dagger."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) slashing damage."
    "name": "Claw"
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/mongrelfolk-cos.webp"
```
^statblock

--- 

```statblock
statblock: true
name: Mischlingsvolk
image: [[.png]]
source: Fluch des Strahd
size: Mittelgroß
type: Humanoide
alignment: beliebige Gesinnung
ac: 11
hp: 26
hit_dice: 4d8 + 8
speed: 9 Meter.
stats: [12, 9, 15, 9, 10, 6]
skillsaves:
  - Heimlichkeit: +3
  - Täuschen: +2
  - Wahrnehmung: +2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 12
languages: Gemeinsprache
cr: 1/4
bestiary: true
traits:
  - name: Außergewöhnliches Merkmal.
    desc: "Ein Angehöriger des Mischlingsvolks hat eines der folgenden außergewöhnlichen Merkmale, die zufällig mit dem Wurf eines `W20` bestimmt oder vom SL ausgewählt werden: <br>**1-3: Amphibisch**. Das Wesen kann Luft und Wasser atmen. <br>**4-9: Dunkelsicht.** Das Wesen hat Dunkelsicht bis zu einer Entfernung von 18 m. <br>**10: Fliegen.** Das Wesen hat ledrige Schwingen und eine Flugbewegungsrate von 12 m. <br>**11-15: Scharfes Gehör und scharfer Geruchssinn.** Das Wesen hat einen Vorteil bei Würfen auf Weisheit (Wahrnehmung), die mit dem Gehör oder Geruchssinn zusammenhängen. <br>**16-17: Spinnenklettern.** Das Wesen kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen. <br>**18-19: Stehender Sprung.** Das Wesen kann bis zu 6 m weit und 3 m hoch springen, mit oder ohne Anlauf. <br>**20: Zweiköpfig.** Das Wesen hat einen Vorteil bei Würfen auf Weisheit (Wahrnehmung) und bei Rettungswürfen, die die Zustände blind, bezaubert, taub , verängstigt, betäubt oder bewusstlos verursachen."
    attack_bonus: 0
  - name: Nachahmung.
    desc: "Das Wesen kann jedes Geräusch nachahmen, das es gehört hat, einschließlich Stimmen. Eine Kreatur, die die Geräusche hört, kann sie mit einem gelungenen Wurf auf Weisheit (Motiv erkennen) gegen SG 12 als Imitationen erkennen."
actions:
  - name: Mehrfachangriff
    desc: "Das Mischlingsvolk führt zwei Angriffe aus: eine mit einem Biss und eine mit einer Klaue oder einem Dolch."
  - name: Biss
    desc: "_Nahkampf-Waffenangriff_: +3 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: 3 (`1W4 + 1`) Stichschaden."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
  - name: Klaue
    desc: "_Nahkampf-Waffenangriff_: +3 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: 3 (`1W4 + 1`) Hiebschaden"
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
  - name: Dolch
    desc: "_Nahkampf- oder Fernkampf-Waffenangriff_: +3 zum Treffen , Reichweite 1,50 m oder Reichweite 6/18 m, ein Ziel. _Treffer_: 3 (`1W4 + 1`) Stichschaden."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```