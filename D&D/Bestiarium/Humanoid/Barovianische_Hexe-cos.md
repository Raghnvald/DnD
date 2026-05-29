---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Barovianische Hexe
Kategorie: Humanoid
Größe: Mittelgroß
HG: 1/2
image:
status:
linter-yaml-title-alias: Barovianische Hexe
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/cos
aliases:
  - Barovian Witch
  - Barovianische Hexe
---
# Barovianische Hexe
*Source: Curse of Strahd p. 229*  

The mad women and men known as Barovian witches forge pacts with Strahd and the Dark Powers of Ravenloft in exchange for magic and longevity. They prefer to live in the shadows and can see in the dark. When traveling in the open, they use [alter self](/3-Mechanics/CLI/spells/alter-self-xphb.md) spells to assume less conspicuous forms. They also use these spells to grow long, sharp claws with which they can attack.

## Brothers and Sisters of Strahd

Barovian witches have no scruples. They will deal with anyone in return for power. They will also betray anyone for the same reason. The only thing they fear is Strahd, and his wish is their command. Barovian witches sometimes refer to themselves as the brothers and sisters of Strahd, though never to Strahd's face.

### Pack Rats with Cats

Barovian witches are obsessive collectors, each believing that almost anything found - a piece of broken bone, a dead rodent, a handful of dust, or some other worthless item or substance - could be valuable or useful as a spell component, a ritual object, or a potion ingredient.

Barovian witches use the [find familiar](/3-Mechanics/CLI/spells/find-familiar-xphb.md) spell to call forth familiars. They are particularly fond of cats, though snakes and toads are also common. These animals lurk amid the clutter of the witches' lairs, seldom wandering far from their vile masters.

```statblock
"name": "Barovian Witch (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "0"
"stats":
  - !!int "7"
  - !!int "11"
  - !!int "13"
  - !!int "14"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "The witch is a 3rd-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 12, +4 to hit with spell attacks). The witch has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](/3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level (4\
      \ slots):** [ray of sickness](/3-Mechanics/CLI/spells/ray-of-sickness-xphb.md),\
      \ [sleep](/3-Mechanics/CLI/spells/sleep-xphb.md), [Tasha's hideous laughter](/3-Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md)\n\
      \n**2nd level (2 slots):** [alter self](/3-Mechanics/CLI/spells/alter-self-xphb.md),\
      \ [invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6\
      \ + 1) slashing damage. This attack is magical."
    "name": "Claws (Requires Alter Self)"
  - "desc": "*Melee  or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 2 (1d4) piercing damage."
    "name": "Dagger"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/barovian-witch-cos.webp"
```
^statblock

Die wahnsinnigen Frauen und Männer, die als Barovianische Hexen bekannt sind, schmieden im Austausch für Magie und Langlebigkeit Pakte mit Strahd und den Dunklen Mächten von Ravenloft. Sie ziehen es vor, in den Schatten zu leben und können im Dunklen sehen. Wenn sie offen reisen, benutzen sie den Zauber Gestalt verändern, um eine weniger auffällige Gestalt anzunehmen. Sie benutzen diesen Zauber auch, um sich lange, scharfe Klauen wachsen zu lassen, mit denen sie tiefe Schnittwunden zufügen können.

$\quad$**_Brüder und Schwestern von Strahd._** Barovianische Hexen haben keine Skrupel. Im Austausch für Macht handeln sie mit jedem. Sie werden aus dem gleichen Grund auch jeden verraten. Das Einzige, was sie fürchten, ist Strahd, und sein Wunsch ist ihnen Befehl. Barovianische Hexen sprechen von sich selbst manchmal als die Brüder und Schwestern von Strahd, aber nie, wenn er dabei ist.

$\quad$**_Ratten und Katzen zusammenpacken._** Barovianische Hexen sind obsessive Sammler. Jede glaubt, dass fast alles, was man findet - ein Stück zerbrochener Knochen, ein totes Nagetier, eine Handvoll Staub oder irgendein anderes wertloses Objekt oder Material - als Zauberkomponente, Ritualobjekt oder Zaubertrankzutat nutzbar wäre.

$\quad$Barovianische Hexen benutzen den Zauber Vertrauten finden, um Vertraute herbeizurufen. Besonders beliebt sind Katzen, obwohl Schlangen und Kröten auch verbreitet sind. Diese Tiere lauern inmitten des Gerümpels in den Verstecken der Hexen und entfernen sich selten weit von ihren scheußlichen Meistern.

```statblock
name: Barovianische Hexe
source: Fluch des Strahd
size: Mittelgroß
type: Humanoid
alignment: Chaotisch Böse
ac: 10
hp: 16
hit_dice: 3d8 + 3
speed: 9 Meter.
stats: [7, 11, 13, 14, 11, 12]
skillsaves:
  - Arkane Kunde: 4
  - Wahrnehmung: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]], passive Wahrnehmung 12
languages: Gemeinsprache
cr: 1/2
bestiary: true
actions:
  - name: Klauen (benötigt Gestalt verändern)
    desc: "_Nahkampf-Waffenangriff_: +3 zum Treffen, Reichweite 1,50 m, ein Ziel. _Treffer_: 4 (1d6 + 1) Hiebschaden. Dieser Angriff ist magisch."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1
  - name: Dolch
    desc: "_Nahkampf- oder Fernkampf-Waffenangriff_: +2 zum Treffen, Reichweite 1,50 m oder Reichweite 6/18 m, ein Ziel. _Treffer_: 2 (1d4) Stichschaden."
    attack_bonus: 2
    damage_dice: 1d4
    damage_bonus: 0
spells:
  - Die Hexe ist eine Zauberwirkerin der 3. Stufe. Ihr Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 12, +4 zum Treffen mit Zauberangriffen). Die Hexe hat die folgenden Magierzaubersprüche vorbereitet:
  - Zaubertricks (beliebig oft): [Kältestrahl](Kältestrahl.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md)
  - Zaubergrad 1 (4 Plätze): [Schlaf](Schlaf.md), [Strahl der Übelkeit](Strahl-der-Übelkeit.md), [Tashas Fürchterlicher Lachanfall](Tashas-Fürchterlicher-Lachanfall.md)
  - Zaubergrad 2 (2 Plätze): [Gestalt verändern](Gestalt-verändern.md), [Unsichtbarkeit](Unsichtbarkeit.md)
```